## libSecureMAHelper.dylib

> `/usr/lib/libSecureMAHelper.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e3c0` | `0x1e548` | **`+0x188`** |
| `__DATA_CONST.__objc_selrefs` | `0x858` | `0x868` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x56c` | `0x57c` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2c8` | `0x2d0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x530` | `0x538` | **`+0x8`** |

### Other Changes

```diff

-2215.0.4.0.0
+2215.0.13.0.0

-  Functions: 430
-  Symbols:   851
+  Functions: 431
+  Symbols:   853
Symbols:
+ +[SecureMobileAssetBundle doesPersonalizationErrorIndicateServerUnreachable:]
+ GCC_except_table57
+ GCC_except_table59
+ GCC_except_table74
+ GCC_except_table91
+ _kAMAuthInstallErrorDomain
- GCC_except_table56
- GCC_except_table58
- GCC_except_table73
- GCC_except_table88
Functions:
+ +[SecureMobileAssetBundle doesPersonalizationErrorIndicateServerUnreachable:]
~ _getMappedExclavePath : 1380 -> 1384
```
