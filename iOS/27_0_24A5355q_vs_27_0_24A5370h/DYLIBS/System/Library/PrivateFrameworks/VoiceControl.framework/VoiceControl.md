## VoiceControl

> `/System/Library/PrivateFrameworks/VoiceControl.framework/VoiceControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e7e0` | `0x3f8f8` | **`+0x1118`** |
| `__DATA_CONST.__const` | `0x358` | `0x398` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1afa` | `0x1b3a` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x9dc` | `0xa1c` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x1b68` | `0x1b98` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0xac8` | `0xaf8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xc28` | `0xc58` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x708` | `0x730` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x5c8` | `0x5da` | **`+0x12`** |
| `__TEXT.__const` | `0x1438` | `0x1448` | **`+0x10`** |
| `__DATA.__data` | `0x660` | `0x668` | **`+0x8`** |

### Other Changes

```diff

-34.0.0.0.0
+37.0.0.0.0

-  Functions: 1227
-  Symbols:   504
-  CStrings:  259
+  Functions: 1260
+  Symbols:   507
+  CStrings:  261
Symbols:
+ _keypath_get_selector_vcAudioInputType
+ _keypath_get_selector_vcBluetoothHeadsetConnected
+ _swift_release_x9
+ _symbolic SS3key_yp5valuet
- _swift_retain_x23
CStrings:
+ "VCAudioInputType"
+ "VCBluetoothHeadsetConnected"
```
