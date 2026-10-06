## HeadphoneSettings

> `/System/Library/PrivateFrameworks/HeadphoneSettings.framework/HeadphoneSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x10e0` | `0x1100` | **`+0x20`** |
| `__TEXT.__cstring` | `0xbd9` | `0xbe9` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xdfc` | `0xe0c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x900` | `0x908` | **`+0x8`** |
| `__TEXT.__text` | `0xca50` | `0xca58` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4f0` | `0x4f8` | **`+0x8`** |

### Other Changes

```diff

-2700.13.0.0.0
+2700.14.0.0.0

-  Functions: 486
-  Symbols:   678
-  CStrings:  210
+  Functions: 488
+  Symbols:   680
+  CStrings:  211
Symbols:
+ -[BTSDevice isLEAudioSupported]
+ -[BTSDeviceLE isLEAudioSupported]
CStrings:
+ "_LEAUDIO_DEVICE_"
```
