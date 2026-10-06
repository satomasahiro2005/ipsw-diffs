## CallKit

> `/System/Library/Frameworks/CallKit.framework/CallKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x67700` | `0x678a8` | **`+0x1a8`** |
| `__TEXT.__oslogstring` | `0x3bb1` | `0x3c25` | **`+0x74`** |
| `__TEXT.__objc_methlist` | `0x927c` | `0x92a4` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x6e4` | `0x6f8` | **`+0x14`** |

### Other Changes

```diff

-1397.100.1.0.0
+1403.100.1.0.0

-  Functions: 3240
-  Symbols:   5449
-  CStrings:  1005
+  Functions: 3244
+  Symbols:   5453
+  CStrings:  1006
Symbols:
+ -[CXProvider _registerCurrentConfigurationIfAudioSessionIDStaleOnQueue]
+ -[CXProvider _registerCurrentConfigurationOnQueue]
+ -[CXProvider currentOpaqueAudioSessionID]
+ ___28-[CXProvider performAction:]_block_invoke
CStrings:
+ "Cached audioSessionID %u no longer matches current opaqueSessionID %u; re-registering configuration for CXProvider."
```
