## SiriUICore

> `/System/Library/PrivateFrameworks/SiriUICore.framework/SiriUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b7e8` | `0x2b95c` | **`+0x174`** |
| `__AUTH_CONST.__objc_const` | `0x9610` | `0x9650` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x3430` | `0x3448` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x24d8` | `0x24e8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x744` | `0x74c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc00` | `0xc08` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3600.9.1.0.0
+3600.9.2.0.0

-  Functions: 1149
-  Symbols:   2544
+  Functions: 1151
+  Symbols:   2548
Symbols:
+ -[SUICOrbView _initForPrewarmWithFrame:]
+ -[SUICOrbView _prepareBlurAndTexturesForRasterSize:]
+ GCC_except_table35
+ _OBJC_IVAR_$_SUICOrbView._prewarmDeferred
+ _OBJC_IVAR_$_SUICOrbView._prewarmRasterSize
- GCC_except_table34
```
