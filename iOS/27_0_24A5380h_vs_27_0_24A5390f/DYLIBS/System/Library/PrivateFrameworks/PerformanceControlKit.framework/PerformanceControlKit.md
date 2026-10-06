## PerformanceControlKit

> `/System/Library/PrivateFrameworks/PerformanceControlKit.framework/PerformanceControlKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12b64` | `0x12dd8` | **`+0x274`** |
| `__TEXT.__gcc_except_tab` | `0x1738` | `0x1788` | **`+0x50`** |
| `__TEXT.__cstring` | `0xa3a` | `0xa88` | **`+0x4e`** |
| `__AUTH_CONST.__cfstring` | `0xc00` | `0xc40` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x624` | `0x654` | **`+0x30`** |
| `__TEXT.__const` | `0xed0` | `0xef0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x780` | `0x798` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0xe20` | `0xe30` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x370` | `0x380` | **`+0x10`** |

### Other Changes

```diff

-1794.0.7.0.2
+1794.0.24.0.0

-  Functions: 312
-  Symbols:   807
-  CStrings:  124
+  Functions: 314
+  Symbols:   811
+  CStrings:  126
Symbols:
+ -[CLPCUserClient getDeviceOrientationMode:]
+ -[CLPCUserClient setDeviceOrientationMode:error:]
+ GCC_except_table28
+ GCC_except_table29
+ GCC_except_table32
- GCC_except_table30
CStrings:
+ "Failed to get Device Orientation Mode."
+ "Failed to set Device Orientation Mode."
```
