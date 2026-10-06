## PDFKit

> `/System/Library/Frameworks/PDFKit.framework/PDFKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbf328` | `0xbf828` | **`+0x500`** |
| `__TEXT.__gcc_except_tab` | `0x7fcc` | `0x8010` | **`+0x44`** |
| `__AUTH_CONST.__cfstring` | `0x7660` | `0x7680` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0xf100` | `0xf120` | **`+0x20`** |
| `__TEXT.__const` | `0x964` | `0x944` | **`-0x20`** |
| `__TEXT.__cstring` | `0x7364` | `0x7384` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xb04c` | `0xb064` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3c88` | `0x3ca0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x7110` | `0x7120` | **`+0x10`** |
| `__DATA.__data` | `0x13c8` | `0x13d0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xc78` | `0xc7c` | **`+0x4`** |

### Other Changes

```diff

-1534.0.0.0.0
+1537.0.0.0.0

-  Functions: 3767
-  Symbols:   7464
-  CStrings:  1272
+  Functions: 3768
+  Symbols:   7467
+  CStrings:  1273
Symbols:
+ +[PDFPageAnalyzerV2 normalizedToPageTransformForPage:box:]
+ -[PDFAnnotation _createInkListArrayFromBezierPaths:]
+ -[PDFAnnotation copyAppearance:]
+ GCC_except_table328
+ GCC_except_table334
+ _CGPDFFormRetain
+ _OBJC_IVAR_$_PDFAnnotation._appearanceLock
+ _PDFKitContextIsAppearanceStreamCreation
+ __ZNSt3__16vectorI14ParsedWordDataNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRU8__strongP8NSStringRdSA_ddRbR13PDFQuadPointsEEEPS1_DpOT_
- +[PDFPageAnalyzerV2 normalizedToPageTransformForPageWithBounds:]
- GCC_except_table326
- GCC_except_table332
- __ZNSt3__16vectorI14ParsedWordDataNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRU8__strongP8NSStringRdSA_SA_SA_SA_RbR13PDFQuadPointsEEEPS1_DpOT_
- __ZZNSt3__16vectorI14ParsedWordDataNS_9allocatorIS1_EEE12emplace_backIJRU8__strongP8NSStringRdSA_SA_SA_SA_RbR13PDFQuadPointsEEERS1_DpOT_ENKUlvE0_clEv
- _tan
CStrings:
+ "PDFKitContextIsAppearanceStreamCreation"
```
