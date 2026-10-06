## Siri

> `/Applications/Siri.app/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xee050` | `0xeee1c` | **`+0xdcc`** |
| `__TEXT.__objc_methname` | `0x2b34f` | `0x2b51f` | **`+0x1d0`** |
| `__TEXT.__cstring` | `0x24185` | `0x242d0` | **`+0x14b`** |
| `__TEXT.__auth_stubs` | `0x2f80` | `0x2ff0` | **`+0x70`** |
| `__DATA.__objc_data` | `0x4aa8` | `0x4b10` | **`+0x68`** |
| `__DATA.__objc_const` | `0x10b00` | `0x10b60` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x1907` | `0x1967` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x247c` | `0x24cc` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x17d0` | `0x1808` | **`+0x38`** |
| `__DATA.__data` | `0x4708` | `0x4738` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xae91` | `0xaec1` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x1234` | `0x1264` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x4c40` | `0x4c68` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xe278` | `0xe2a0` | **`+0x28`** |
| `__TEXT.__const` | `0x2fa4` | `0x2f84` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x1b440` | `0x1b420` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x3888` | `0x38a0` | **`+0x18`** |
| `__DATA.__bss` | `0x1ff0` | `0x1fe0` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x6dc` | `0x6ec` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x25f6` | `0x2606` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x8f0` | `0x8f8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1800` | `0x1808` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x8c8` | `0x8c4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.49.31.1.6
+3600.55.10.0.0

-  Functions: 5156
-  Symbols:   1849
-  CStrings:  8984
+  Functions: 5157
+  Symbols:   1858
+  CStrings:  8993
Symbols:
+ _$s7SwiftUI6_GlassV15SiriWaveOptionsV11AudioMetersV25normalizedPowerAmplitudes17stopFrequenciesHzAGSaySfG_AJtcfC
+ _$s7SwiftUI6_GlassV15SiriWaveOptionsV11AudioMetersVMa
+ _$s7SwiftUI6_GlassV15SiriWaveOptionsV11AudioMetersVMn
+ _$s7SwiftUI6_GlassV15SiriWaveOptionsV11AudioMetersVSQAAMc
+ _$s7SwiftUI6_GlassV15SiriWaveOptionsV11anchorPoint7opacity11personality11audioMetersAeA04UnitH0V_SfAE11PersonalityVAE05AudioL0VtcfC
+ _$s7SwiftUI6_GlassV15SiriWaveOptionsV23AudioMeterConfigurationV11recommendedAGvgZ
+ _$s7SwiftUI6_GlassV15SiriWaveOptionsV23AudioMeterConfigurationV17stopFrequenciesHzSaySfGvg
+ _$s7SwiftUI6_GlassV15SiriWaveOptionsV23AudioMeterConfigurationVMa
+ _$sSa28_allocateBufferUninitialized15minimumCapacitys06_ArrayB0VyxGSi_tFZ
+ _AFIsLinwoodEnabledAndWasEverAvailable
+ ___exp10f
- _$s7SwiftUI6_GlassV15SiriWaveOptionsV11PersonalityV10respondingAGvgZ
- _$s7SwiftUI6_GlassV15SiriWaveOptionsV11anchorPoint7opacity11personality15audioPowerLevelAeA04UnitH0V_SfAE11PersonalityVSftcfC
CStrings:
+ "-[SRSiriViewController _speakText:audioData:ignoreMuteSwitch:identifier:sessionId:streamId:preferredVoice:language:gender:promptStyle:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:speakableUtteranceParser:analyticsContext:speakableContextInfo:preparation:completion:]"
+ "-[SRSiriViewController _speakText:audioData:ignoreMuteSwitch:identifier:sessionId:streamId:preferredVoice:language:gender:promptStyle:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:speakableUtteranceParser:analyticsContext:speakableContextInfo:preparation:completion:]_block_invoke"
+ "Cancel any scheduled attending window closure and pending autodismiss due to SiriDirectedSpeech"
+ "Extending attending window by "
+ "Speech detected but attending window already extended once; ignoring"
+ "Speech detected with no active attending window; ignoring"
+ "_audioMeters"
+ "_speakText:audioData:ignoreMuteSwitch:identifier:sessionId:streamId:preferredVoice:language:gender:promptStyle:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:speakableUtteranceParser:analyticsContext:speakableContextInfo:preparation:completion:"
+ "_speakText:identifier:sessionId:streamId:preferredVoice:promptStyle:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:speakableUtteranceParser:analyticsContext:speakableContextInfo:preparation:completion:"
+ "attendingWindowScheduled"
+ "extendAttendingWindowForSpeechDetectedIfEligible()"
+ "isAttendingCar"
+ "not clearing snippet for supplemental SAUIAssistantUtteranceView (streaming TTS fragment)"
+ "s due to speech detected (one-time)"
+ "setInput:"
+ "siriAudioRecordingDidChangePowerLevel:peakLevel:frequencyBands:"
+ "siriSessionAudioRecordingDidChangePowerLevel:peakLevel:frequencyBands:"
+ "siri_read_this_v3"
+ "snippetContainerView"
+ "speechDetectedExtensionUsed"
+ "v124@0:8@16@24@32@40@48@56B64d68B76B80@84@92@100@?108@?116"
+ "v152@0:8@16@24B32@36@44@52@60@68@76@84B92d96B104B108@112@120@128@?136@?144"
+ "v32@0:8f16f20@\"NSArray\"24"
+ "v32@0:8f16f20@24"
- "-[SRSiriViewController _speakText:audioData:ignoreMuteSwitch:identifier:sessionId:streamId:preferredVoice:language:gender:promptStyle:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:optInNextGenVoice:speakableUtteranceParser:analyticsContext:speakableContextInfo:preparation:completion:]"
- "-[SRSiriViewController _speakText:audioData:ignoreMuteSwitch:identifier:sessionId:streamId:preferredVoice:language:gender:promptStyle:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:optInNextGenVoice:speakableUtteranceParser:analyticsContext:speakableContextInfo:preparation:completion:]_block_invoke"
- "Cancel any scheduled attending window closure due to siri directed speech"
- "Cancel any scheduled attending window closure due to speech detected"
- "TB,N,V_optInNextGenVoice"
- "_audioPowerLevel"
- "_optInNextGenVoice"
- "_speakText:audioData:ignoreMuteSwitch:identifier:sessionId:streamId:preferredVoice:language:gender:promptStyle:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:optInNextGenVoice:speakableUtteranceParser:analyticsContext:speakableContextInfo:preparation:completion:"
- "_speakText:identifier:sessionId:streamId:preferredVoice:promptStyle:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:optInNextGenVoice:speakableUtteranceParser:analyticsContext:speakableContextInfo:preparation:completion:"
- "enqueueText:identifier:sessionId:preferredVoice:language:gender:promptStyle:isPhonetic:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:optInNextGenVoice:preparationIdentifier:completion:analyticsContext:speakableContextInfo:"
- "optInNextGenVoice"
- "setOptInNextGenVoice:"
- "snippetHostView"
- "v128@0:8@16@24@32@40@48@56B64d68B76B80B84@88@96@104@?112@?120"
- "v156@0:8@16@24B32@36@44@52@60@68@76@84B92d96B104B108B112@116@124@132@?140@?148"
```
