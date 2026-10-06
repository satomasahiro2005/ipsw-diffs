## CallKit

> `/System/Library/Frameworks/CallKit.framework/CallKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x67528` | `0x67700` | **`+0x1d8`** |
| `__TEXT.__oslogstring` | `0x3b4d` | `0x3bb1` | **`+0x64`** |
| `__TEXT.__objc_methlist` | `0x9254` | `0x927c` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x34d0` | `0x34e8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1dd8` | `0x1de8` | **`+0x10`** |

### Other Changes

```diff

-1395.100.1.0.0
+1397.100.1.0.0

-  Functions: 3236
-  Symbols:   5444
-  CStrings:  1004
+  Functions: 3240
+  Symbols:   5449
+  CStrings:  1005
Symbols:
+ -[CXChannelProvider _registerCurrentConfigurationIfAudioSessionIDStaleOnQueue]
+ -[CXChannelProvider _registerCurrentConfigurationOnQueue]
+ -[CXChannelProvider currentOpaqueAudioSessionID]
+ ___35-[CXChannelProvider performAction:]_block_invoke
+ ___57-[CXChannelProvider _registerCurrentConfigurationOnQueue]_block_invoke
CStrings:
+ "Cached audioSessionID %u no longer matches current opaqueSessionID %u; re-registering configuration"
```
