## CryptoKit

> `/System/Library/Frameworks/CryptoKit.framework/CryptoKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85ab4` | `0x86f6c` | **`+0x14b8`** |
| `__TEXT.__eh_frame` | `0x72f0` | `0x73a8` | **`+0xb8`** |
| `__DATA.__data` | `0xea0` | `0xf20` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x7d08` | `0x7d60` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x2900` | `0x2948` | **`+0x48`** |
| `__TEXT.__const` | `0x80f8` | `0x8138` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x28ec` | `0x2914` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x1fb0` | `0x1fd8` | **`+0x28`** |
| `__AUTH.__data` | `0x14f8` | `0x14e8` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xce0` | `0xcf0` | **`+0x10`** |
| `__TEXT.__swift5_assocty` | `0xec8` | `0xeb8` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x102f` | `0x101f` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x1d5c` | `0x1d56` | **`-0x6`** |
| `__TEXT.__swift5_types` | `0x374` | `0x378` | **`+0x4`** |

### Other Changes

```diff

-383.0.6.502.1
+383.0.12.0.0

-  Functions: 3127
-  Symbols:   1168
+  Functions: 3141
+  Symbols:   1172
Symbols:
+ ___unnamed_10
+ ___unnamed_8
+ ___unnamed_9
+ _cckem_mlkem1024_unmasked
+ _cckem_mlkem768_unmasked
+ _symbolic _____ 9CryptoKit04CoreA26MLKEMOneTimePrivateKeyImplV
+ _symbolic _____y_____G 9CryptoKit04CoreA26MLKEMOneTimePrivateKeyImplV AA8MLKEM768O
+ _symbolic _____y_____G 9CryptoKit04CoreA26MLKEMOneTimePrivateKeyImplV AA9MLKEM1024O
+ _type_layout_string 9CryptoKit27CorecryptoSupportedMLKEMKEMRzlAA04CoreA26MLKEMOneTimePrivateKeyImplVyxG
- ___unnamed_5
- _associated conformance 9CryptoKit8MLKEM768OAA27CorecryptoSupportedMLKEMKEMAA14privateKeyTypeAaDP_AA010KEMPrivateH0
- _associated conformance 9CryptoKit9MLKEM1024OAA27CorecryptoSupportedMLKEMKEMAA14privateKeyTypeAaDP_AA010KEMPrivateH0
- _symbolic 14privateKeyType_____Qz 9CryptoKit27CorecryptoSupportedMLKEMKEMP
- _type_layout_string 9CryptoKit27CorecryptoSupportedMLKEMKEMRzlAA04CoreA19MLKEMPrivateKeyImplVyxG
```
