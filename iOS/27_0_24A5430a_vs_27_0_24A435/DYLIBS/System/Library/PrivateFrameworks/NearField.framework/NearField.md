## NearField

> `/System/Library/PrivateFrameworks/NearField.framework/NearField`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x92b88` | `0x93560` | **`+0x9d8`** |
| `__TEXT.__cstring` | `0xb8b0` | `0xb952` | **`+0xa2`** |
| `__AUTH_CONST.__cfstring` | `0x40a0` | `0x40e0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0xc6f8` | `0xc738` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x74a4` | `0x74dc` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x34e8` | `0x3510` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1cc0` | `0x1ce0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x648` | `0x64c` | **`+0x4`** |

### Other Changes

```diff

-  Functions: 2824
+  Functions: 2831

-  CStrings:  1749
+  CStrings:  1753
CStrings:
+ "-[NFHardwareManager queryNFCCBootMeasurements:]_block_invoke"
+ "-[NFHardwareManager querySEBootMeasurements:]_block_invoke"
+ "InvalidBStateSettingsPolicy"
+ "hasSWDEnabled"
```
