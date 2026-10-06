## SiriUIFoundation

> `/System/Library/PrivateFrameworks/SiriUIFoundation.framework/SiriUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x916d8` | `0x910e8` | **`-0x5f0`** |
| `__TEXT.__cstring` | `0x6836` | `0x66f6` | **`-0x140`** |
| `__AUTH_CONST.__const` | `0x3b21` | `0x3aa1` | **`-0x80`** |
| `__TEXT.__oslogstring` | `0x703b` | `0x6fcb` | **`-0x70`** |
| `__AUTH_CONST.__cfstring` | `0x2400` | `0x23a0` | **`-0x60`** |
| `__AUTH_CONST.__objc_const` | `0x8f90` | `0x8ff0` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x9dc` | `0x97c` | **`-0x60`** |
| `__DATA_DIRTY.__bss` | `0x238` | `0x208` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x19a0` | `0x1978` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x26b8` | `0x2690` | **`-0x28`** |
| `__DATA.__bss` | `0x4680` | `0x4670` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f28` | `0x2f38` | **`+0x10`** |
| `__TEXT.__const` | `0x388c` | `0x389c` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x46a8` | `0x46b8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x424` | `0x430` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xf40` | `0xf38` | **`-0x8`** |

### Other Changes

```diff

-3600.55.26.0.0
+3600.55.30.0.0

-  Functions: 3369
-  Symbols:   3741
-  CStrings:  1137
+  Functions: 3358
+  Symbols:   3726
+  CStrings:  1132
Symbols:
+ -[SRUIFStateFeedbackDefaultProvider isFadingOut]
+ -[SRUIFStateFeedbackDefaultProvider setPlaybackBarrierEngaged:]
+ -[SRUIFStateFeedbackManager _fadeProcessingFeedbackAtResponseStart]
+ -[SRUIFStateFeedbackManager lastScheduledDelayToneInterval]
+ GCC_except_table22
+ GCC_except_table31
+ GCC_except_table56
+ _OBJC_IVAR_$_SRUIFStateFeedbackDefaultProvider._isFadingOut
+ _OBJC_IVAR_$_SRUIFStateFeedbackDefaultProvider._playbackBarrierEngaged
+ _OBJC_IVAR_$_SRUIFStateFeedbackManager._lastScheduledDelayToneInterval
- -[SRUIFStateFeedbackDefaultProvider _startLatencyResponseFeedback:withCompletion:]
- -[SRUIFStateFeedbackManager _playLatencyResponseFeedback]
- GCC_except_table15
- GCC_except_table21
- GCC_except_table24
- GCC_except_table45
- GCC_except_table49
- GCC_except_table54
- _AFSoundIDGetName
- ___57-[SRUIFStateFeedbackManager _playLatencyResponseFeedback]_block_invoke
- ___82-[SRUIFStateFeedbackDefaultProvider _startLatencyResponseFeedback:withCompletion:]_block_invoke
- ___82-[SRUIFStateFeedbackDefaultProvider _startLatencyResponseFeedback:withCompletion:]_block_invoke_2
- ___block_descriptor_40_e8_32w_e20_v24?0q8"NSError"16lw32l8
- ___latencyResponseFadeInDuration_block_invoke
- ___latencyResponseFadeOutDuration_block_invoke
- ___latencyResponseLoopCount_block_invoke
- ___latencyResponseVolume_block_invoke
- _latencyResponseFadeInDuration.cachedValue
- _latencyResponseFadeInDuration.onceToken
- _latencyResponseFadeOutDuration.cachedValue
- _latencyResponseFadeOutDuration.onceToken
- _latencyResponseLoopCount.cachedValue
- _latencyResponseLoopCount.onceToken
- _latencyResponseVolume.cachedValue
- _latencyResponseVolume.onceToken
CStrings:
+ "%s #statefeedback Fade-out started, suppressing further volume decay"
+ "%s #statefeedback Playback barrier %@"
+ "%s #statefeedback Playback barrier engaged; rejecting audio session acquisition and playback"
+ "%s #statefeedback Playback barrier engaged; rejecting playAudioPlaybackRequest"
+ "%s #statefeedback Playback barrier engaged; rejecting state feedback type %ld"
+ "%s #statefeedback Volume decay reschedule suppressed - fade-out in progress"
+ "%s #statefeedback Volume decay suppressed - fade-out in progress"
+ "%s #statefeedback fading processing loop at TTS start"
+ "%s #statefeedback no processing feedback in flight at TTS start; nothing to fade"
+ "%s #statefeedback synthesis response TTS did finish, canceling feedback"
+ "%s #statefeedback synthesis response TTS will start, fading out the processing loop"
+ "%s #tts [stopStream] [rdar://178734021] Stream %@ is queued or activating, deferring stop until the stream starts (fix active)"
+ "-[SRUIFStateFeedbackDefaultProvider setPlaybackBarrierEngaged:]"
+ "-[SRUIFStateFeedbackManager _fadeProcessingFeedbackAtResponseStart]"
+ "Playback barrier engaged"
+ "disengaged"
+ "engaged"
- "%s #statefeedback Failed to play latencyResponse tone with error: %@"
- "%s #statefeedback Playing siriLatencyResponse tone for synthesis transition (latencyResponseFadeOutDuration: %f)"
- "%s #statefeedback latency response feedback not needed. Skipping latency response tone"
- "%s #statefeedback latency response feedback started with error, inform delegate anyway"
- "%s #statefeedback latency response feedback started, inform delegate immediately"
- "%s #statefeedback playing latency response feedback for synthesis transition"
- "%s #statefeedback siriLatencyResponse audio resource not found, not playing latency response tone"
- "%s #statefeedback siriLatencyResponse sound not found, using %@"
- "%s #statefeedback synthesis response TTS did finish, canceling latency response tone"
- "%s #statefeedback synthesis response TTS will start, transitioning from delay to latency response tone"
- "%s #tts [stopStream] Stream %@ is being processed (audio session activating), deferring stop"
- "%s #tts [stopStream] Waiting for the stream task to begin processing"
- "-[SRUIFStateFeedbackDefaultProvider _startLatencyResponseFeedback:withCompletion:]"
- "-[SRUIFStateFeedbackDefaultProvider _startLatencyResponseFeedback:withCompletion:]_block_invoke_2"
- "-[SRUIFStateFeedbackManager _playLatencyResponseFeedback]"
- "-[SRUIFStateFeedbackManager _playLatencyResponseFeedback]_block_invoke"
- "SRUIFSiriStateFeedbackTypeLatencyResponse"
- "SiriLatencyResponseFadeInDuration"
- "SiriLatencyResponseFadeOutDuration"
- "SiriLatencyResponseLoopCount"
- "SiriLatencyResponseVolume"
- "siriLatencyResponse"
```
