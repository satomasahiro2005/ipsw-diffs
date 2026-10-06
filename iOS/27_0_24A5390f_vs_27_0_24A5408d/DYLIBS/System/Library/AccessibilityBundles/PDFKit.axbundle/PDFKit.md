## PDFKit

> `/System/Library/AccessibilityBundles/PDFKit.axbundle/PDFKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa218` | `0xa2e4` | **`+0xcc`** |
| `__DATA_CONST.__objc_selrefs` | `0xa20` | `0xa30` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xcd0` | `0xce0` | **`+0x10`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 246
-  Symbols:   655
+  Functions: 247
+  Symbols:   656
Symbols:
+ -[PDFAnnotationAccessibilityElement accessibilityActivate]
+ GCC_except_table171
+ GCC_except_table199
+ GCC_except_table224
+ GCC_except_table66
+ GCC_except_table81
- GCC_except_table170
- GCC_except_table198
- GCC_except_table223
- GCC_except_table65
- GCC_except_table80
Functions:
+ -[PDFAnnotationAccessibilityElement accessibilityActivate]
~ -[PDFPageViewAccessibility accessibilityElements] : 328 -> 312
```
