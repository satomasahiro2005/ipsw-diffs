## libSparse.dylib

> `/System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libSparse.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1671d8` | `0x168a38` | **`+0x1860`** |
| `__TEXT.__eh_frame` | `0x2a8` | `0x208` | **`-0xa0`** |
| `__AUTH_CONST.__auth_got` | `0x618` | `0x638` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x1d0` | `0x1b0` | **`-0x20`** |
| `__DATA_CONST.__const` | `0xad0` | `0xab0` | **`-0x20`** |
| `__DATA.__bss` | `0x12018` | `0x12008` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x16a0` | `0x1690` | **`-0x10`** |
| `__TEXT.__cstring` | `0x4e08` | `0x4e02` | **`-0x6`** |

### Other Changes

```diff

-194.0.0.0.0
+196.0.1.0.0

-  Functions: 1967
-  Symbols:   676
-  CStrings:  602
+  Functions: 1963
+  Symbols:   680
+  CStrings:  601
Symbols:
+ _getHardwareInfo
+ _sparse_csc_spmv_complex_double
+ _sparse_csc_spmv_complex_float
+ _sparse_csc_spmv_double
+ _sparse_csc_spmv_float
- _dispatch_once
CStrings:
- "v8@?0"
```
