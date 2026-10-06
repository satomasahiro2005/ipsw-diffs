## LiveTranscription

> `/System/Library/PrivateFrameworks/LiveTranscription.framework/LiveTranscription`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30a5c` | `0x31b5c` | **`+0x1100`** |
| `__TEXT.__oslogstring` | `0x2a0e` | `0x2bbd` | **`+0x1af`** |
| `__TEXT.__gcc_except_tab` | `0x88` | `0xf4` | **`+0x6c`** |
| `__AUTH_CONST.__const` | `0xb50` | `0xbb0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x610` | `0x660` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x2ae0` | `0x2b10` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x16ec` | `0x171c` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xf00` | `0xf20` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xa50` | `0xa70` | **`+0x20`** |
| `__TEXT.__const` | `0x978` | `0x990` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x8f8` | `0x908` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3d8` | `0x3e0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x18c` | `0x190` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-584.0.0.0.0
+587.0.0.0.0

-  Functions: 1000
-  Symbols:   1163
-  CStrings:  295
+  Functions: 1008
+  Symbols:   1177
+  CStrings:  301
Symbols:
+ -[AXLTAudioOutManager _removeRunningStateListenerForTranscriber:]
+ -[AXLTAudioOutManager handleAudioQueueStoppedForTranscriber:]
+ -[AXLTAudioOutManager lastTapRebuildDates]
+ -[AXLTAudioOutManager setLastTapRebuildDates:]
+ GCC_except_table339
+ GCC_except_table349
+ _AVSystemController_CallIsActiveDidChangeNotification
+ _AudioQueueAddPropertyListener
+ _AudioQueueRemovePropertyListener
+ _OBJC_IVAR_$_AXLTAudioOutManager._lastTapRebuildDates
+ ___61-[AXLTAudioOutManager handleAudioQueueStoppedForTranscriber:]_block_invoke
+ ___61-[AXLTAudioOutManager handleAudioQueueStoppedForTranscriber:]_block_invoke_2
+ ___block_descriptor_60_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
+ ___block_descriptor_68_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ _handleAudioQueueRunningStateChanged
- GCC_except_table342
CStrings:
+ "5"
+ "AudioManager: Audio queue stopped again for pid %d %.1fs after rebuild, not retrying"
+ "AudioManager: Audio queue stopped unexpectedly for app: %@, pid: %d, rebuilding tap"
+ "AudioManager: Failed to add running-state listener for pid %@: %d"
+ "AudioManager: Failed to rebuild tap for app: %@, pid: %d, error: %@"
+ "TranscriberV2: %s %s: %s"
+ "TranscriberV2: found default is %s locale with removed region from supported locales: %s"
+ "TranscriberV2: removed region from %s locale identifier: %s"
- "4"
- "TranscriberV2: found %s locale identifier with no region: %s"
```
