## PerformanceControlKit

> `/System/Library/PrivateFrameworks/PerformanceControlKit.framework/PerformanceControlKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12dd8` | `0x1304c` | **`+0x274`** |
| `__TEXT.__gcc_except_tab` | `0x1788` | `0x17d8` | **`+0x50`** |
| `__TEXT.__cstring` | `0xa88` | `0xace` | **`+0x46`** |
| `__AUTH_CONST.__cfstring` | `0xc40` | `0xc80` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x654` | `0x684` | **`+0x30`** |
| `__TEXT.__const` | `0xef0` | `0xf10` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x798` | `0x7b0` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0xe30` | `0xe40` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x380` | `0x390` | **`+0x10`** |

### Other Changes

```diff

-1794.0.24.0.0
+1794.0.32.0.4

-  Functions: 314
-  Symbols:   811
-  CStrings:  126
+  Functions: 316
+  Symbols:   815
+  CStrings:  128
Symbols:
+ -[CLPCUserClient getDeviceThermalMode:]
+ -[CLPCUserClient setDeviceThermalMode:error:]
+ GCC_except_table30
+ GCC_except_table31
+ GCC_except_table34
- GCC_except_table32
CStrings:
+ "Failed to get Device Thermal Mode."
+ "Failed to set Device Thermal Mode."
```
