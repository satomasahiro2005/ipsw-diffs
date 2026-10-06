## libGSFont.dylib

> `/System/Library/PrivateFrameworks/FontServices.framework/libGSFont.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x821c` | `0x896c` | **`+0x750`** |
| `__DATA_CONST.__objc_selrefs` | `0x270` | `0x288` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x268` | `0x278` | **`+0x10`** |
| `__DATA.__bss` | `0xa0` | `0x98` | **`-0x8`** |

### Other Changes

```diff

-168.0.0.0.0
+169.0.0.0.0

-  Functions: 144
-  Symbols:   427
+  Functions: 149
+  Symbols:   433
Symbols:
+ GCC_except_table82
+ _GSFontCopyLocallyActivatedFontsInfo
+ _GSFontRegisterLocallyActivatedFontsInfo
+ _GSFontUnregisterLocallyActivatedURL
+ _IsFontPathLikelyLocallyActivated
+ _OBJC_CLASS_$_NSMutableOrderedSet
+ ___GSFontCopyLocallyActivatedFontsInfo_block_invoke
- GCC_except_table77
```
