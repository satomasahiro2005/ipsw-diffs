## PDFKit

> `/System/Library/AccessibilityBundles/PDFKit.axbundle/PDFKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa7e4` | `0xa218` | **`-0x5cc`** |
| `__AUTH_CONST.__objc_const` | `0x1010` | `0x1130` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x1e0` | `0x280` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x15e0` | `0x1580` | **`-0x60`** |
| `__TEXT.__cstring` | `0xf06` | `0xec4` | **`-0x42`** |
| `__DATA_CONST.__objc_selrefs` | `0xa60` | `0xa20` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0xca8` | `0xcd0` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x98` | `0xa8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x300` | `0x2f8` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x340` | `0x338` | **`-0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 245
-  Symbols:   645
-  CStrings:  199
+  Functions: 246
+  Symbols:   655
+  CStrings:  195
Symbols:
+ +[PDFAnnotationManagerAccessibility _accessibilityPerformValidations:]
+ +[PDFAnnotationManagerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PDFAnnotationManagerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PDFAnnotationManagerAccessibility _removeControlForAnnotation:]
+ GCC_except_table170
+ GCC_except_table198
+ GCC_except_table223
+ GCC_except_table80
+ _OBJC_CLASS_$_PDFAnnotationManagerAccessibility
+ _OBJC_CLASS_$___PDFAnnotationManagerAccessibility_super
+ _OBJC_METACLASS_$_PDFAnnotationManagerAccessibility
+ _OBJC_METACLASS_$___PDFAnnotationManagerAccessibility_super
+ __OBJC_$_CLASS_METHODS_PDFAnnotationManagerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PDFAnnotationManagerAccessibility
+ __OBJC_CLASS_RO_$_PDFAnnotationManagerAccessibility
+ __OBJC_CLASS_RO_$___PDFAnnotationManagerAccessibility_super
+ __OBJC_METACLASS_RO_$_PDFAnnotationManagerAccessibility
+ __OBJC_METACLASS_RO_$___PDFAnnotationManagerAccessibility_super
- -[PDFDocumentViewAccessibility _axIsUsingPDFExtensionView]
- -[PDFPageViewAccessibility _axIsUsingPDFExtensionView]
- -[PDFPageViewAccessibility removeControlForAnnotation:]
- GCC_except_table169
- GCC_except_table197
- GCC_except_table222
- GCC_except_table81
- _OBJC_CLASS_$_UIScrollView
CStrings:
+ "PDFAnnotationManager"
+ "PDFAnnotationManagerAccessibility"
+ "_removeControlForAnnotation:"
- "PDFExtensionTopView"
- "PDFRenderingProperties"
- "d"
- "extensionViewBoundsInDocument"
- "extensionViewZoomScale"
- "isUsingPDFExtensionView"
- "removeControlForAnnotation:"
```
