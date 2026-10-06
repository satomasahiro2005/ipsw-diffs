## KoaMapper

> `/System/Library/PrivateFrameworks/KoaMapper.framework/KoaMapper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d520` | `0x1d66c` | **`+0x14c`** |
| `__TEXT.__cstring` | `0x112f` | `0x1179` | **`+0x4a`** |
| `__AUTH_CONST.__cfstring` | `0x9a0` | `0x9c0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0xf65` | `0xf85` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xb38` | `0xb48` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x11fc` | `0x1204` | **`+0x8`** |

### Other Changes

```diff

-3600.13.1.0.0
+3600.13.3.0.0

-  Functions: 683
-  Symbols:   1932
-  CStrings:  202
+  Functions: 684
+  Symbols:   1933
+  CStrings:  205
Symbols:
+ -[KMLaunchServicesBridge _isAppHiddenBySystem:]
+ GCC_except_table121
+ GCC_except_table159
+ GCC_except_table202
+ GCC_except_table241
+ GCC_except_table260
- GCC_except_table120
- GCC_except_table157
- GCC_except_table201
- GCC_except_table240
- GCC_except_table259
CStrings:
+ "%s Failed to read %@ for %@: %@"
+ "-[KMLaunchServicesBridge _isAppHiddenBySystem:]"
+ "_NSURLIsHiddenBySystemKey"
```
