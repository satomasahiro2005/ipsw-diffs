## HeadphoneConfigs

> `/System/Library/PrivateFrameworks/HeadphoneConfigs.framework/HeadphoneConfigs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc90f8` | `0xc9064` | **`-0x94`** |
| `__AUTH_CONST.__cfstring` | `0x9580` | `0x95a0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xf90` | `0xfa0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x95d3` | `0x95e3` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x4f88` | `0x4f98` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xb80` | `0xb88` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3660` | `0x3668` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2418` | `0x2410` | **`-0x8`** |

### Other Changes

```diff

-2700.13.0.0.0
+2700.14.0.0.0

-  Functions: 4179
-  Symbols:   3533
-  CStrings:  2242
+  Functions: 4181
+  Symbols:   3536
+  CStrings:  2243
Symbols:
+ -[BTSDevice isLEAudioSupported]
+ -[BTSDeviceLE isLEAudioSupported]
+ _swift_release_x10
CStrings:
+ "_LEAUDIO_DEVICE_"
```
