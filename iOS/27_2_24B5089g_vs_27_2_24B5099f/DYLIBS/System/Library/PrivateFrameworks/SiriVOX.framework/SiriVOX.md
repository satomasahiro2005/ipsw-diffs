## SiriVOX

> `/System/Library/PrivateFrameworks/SiriVOX.framework/SiriVOX`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85f40` | `0x86764` | **`+0x824`** |
| `__TEXT.__oslogstring` | `0x8c2d` | `0x8ec0` | **`+0x293`** |
| `__TEXT.__cstring` | `0x11acb` | `0x11b5e` | **`+0x93`** |
| `__AUTH_CONST.__objc_const` | `0x139a0` | `0x13a28` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0x8c78` | `0x8cb0` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x3e38` | `0x3e58` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x5cc` | `0x5e8` | **`+0x1c`** |
| `__DATA.__objc_ivar` | `0xcdc` | `0xce8` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x2458` | `0x2460` | **`+0x8`** |

### Other Changes

```diff

-3605.17.1.0.0
+3605.18.1.0.0

-  Functions: 3179
-  Symbols:   6754
-  CStrings:  2276
+  Functions: 3186
+  Symbols:   6764
+  CStrings:  2286
Symbols:
+ -[SVXHomePodUIBridgeClientDelegate didPauseTTSForCurrentUserTurn]
+ -[SVXHomePodUIBridgeClientDelegate setDidPauseTTSForCurrentUserTurn:]
+ -[SVXSession currentActivationContext]
+ -[SVXSession speechSynthesizerDidFailStreamWithError:taskTracker:]
+ GCC_except_table2078
+ GCC_except_table2103
+ GCC_except_table2240
+ GCC_except_table2363
+ GCC_except_table2365
+ GCC_except_table2367
+ GCC_except_table2383
+ GCC_except_table2384
+ GCC_except_table2512
+ GCC_except_table2518
+ GCC_except_table2521
+ GCC_except_table2827
+ GCC_except_table2982
+ GCC_except_table3057
+ _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._didPauseTTSForCurrentUserTurn
+ _OBJC_IVAR_$_SVXSpeechSynthesizer._streamTaskTrackers
+ _OBJC_IVAR_$_SVXSpeechSynthesizer._streamsWithFinishedPlayback
+ ___66-[SVXSession speechSynthesizerDidFailStreamWithError:taskTracker:]_block_invoke
+ ___71-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDetectedSpeechStart:]_block_invoke
+ ___82-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceReceivedSpeechMitigationResult:]_block_invoke
- GCC_except_table2076
- GCC_except_table2099
- GCC_except_table2236
- GCC_except_table2358
- GCC_except_table2360
- GCC_except_table2362
- GCC_except_table2378
- GCC_except_table2379
- GCC_except_table2507
- GCC_except_table2511
- GCC_except_table2513
- GCC_except_table2820
- GCC_except_table2975
- GCC_except_table3050
CStrings:
+ "#Choreography - TTS was never paused for this turn, skipping resume"
+ "#Choreography - TTS was never paused, skipping legacy resume"
+ "%s Ignored because the stream does not belong to the current request. (_currentRequestUUID = %@, streamRequestUUID = %@)"
+ "%s Ignored failure of an unregistered stream. (streamId = %@, error = %@)"
+ "%s Response stream failed; ending the abandoned request. (_currentRequestUUID = %@, error = %@)"
+ "%s Stopping TTS for the active request with no current speaking context... (ttsSession = %@, activeTTSRequest = %@)"
+ "%s Stream errored after its audio finished; reporting success. (streamId = %@, error = %@)"
+ "%s error = %@, taskTracker = %@"
+ "-[SVXSession speechSynthesizerDidFailStreamWithError:taskTracker:]"
+ "-[SVXSession speechSynthesizerDidFailStreamWithError:taskTracker:]_block_invoke"
```
