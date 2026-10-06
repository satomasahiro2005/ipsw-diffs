## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/AVConference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7dfa1c` | `0x7e00b0` | **`+0x694`** |
| `__TEXT.__oslogstring` | `0x141b50` | `0x141d19` | **`+0x1c9`** |
| `__TEXT.__cstring` | `0x9f9b5` | `0x9f9f5` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x3abe8` | `0x3ac00` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x18d88` | `0x18d98` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2cf8` | `0x2d04` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x12600` | `0x12608` | **`+0x8`** |

### Other Changes

```diff

-2235.63.1.1.0
+2235.63.1.2.0

-  Functions: 35499
-  Symbols:   42021
-  CStrings:  34064
+  Functions: 35501
+  Symbols:   42024
+  CStrings:  34071
Symbols:
+ -[VCAVFoundationCapture anyCameraConnectionEnabled]
+ -[VCAVFoundationCapture bothCameraConnectionsDisabled]
+ GCC_except_table146
+ GCC_except_table28
- GCC_except_table136
CStrings:
+ " [%s] %s:%d %@(%p) [FTDC] All camera connections disabled, not starting session context=%@"
+ " [%s] %s:%d %@(%p) audioChannelIndex changed %u -> %u for streamGroup=%s"
+ " [%s] %s:%d [FTDC] All camera connections disabled, not starting session context=%@"
+ " [%s] %s:%d audioChannelIndex changed %u -> %u for streamGroup=%s"
+ "-[VCAudioStreamReceiveGroup setAudioChannelIndex:]_block_invoke"
+ "2235.63.1.2"
+ "VCSession [%s] %s:%d %@(%p) sessionMode=%ld hasExistingSpatialAudioPool=%d"
+ "VCSession [%s] %s:%d sessionMode=%ld hasExistingSpatialAudioPool=%d"
- "2235.63.1.1"
```
