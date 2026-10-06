## AppStore

> `/System/Library/AccessibilityBundles/AppStore.axbundle/AppStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__objc_data` | `0x3750` | `0x4010` | **`+0x8c0`** |
| `__AUTH.__objc_data` | `0xbe0` | `0x3c0` | **`-0x820`** |
| `__AUTH_CONST.__objc_const` | `0x78f0` | `0x7a10` | **`+0x120`** |
| `__TEXT.__text` | `0xbda4` | `0xbe18` | **`+0x74`** |
| `__AUTH_CONST.__cfstring` | `0x3ae0` | `0x3aa0` | **`-0x40`** |
| `__TEXT.__cstring` | `0x399c` | `0x3972` | **`-0x2a`** |
| `__TEXT.__objc_methlist` | `0x2814` | `0x282c` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x6b8` | `0x6c8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x530` | `0x538` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x208` | `0x210` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Symbols:   1875
-  CStrings:  518
+  Symbols:   1885
+  CStrings:  516
Symbols:
+ +[JULoadingViewControllerAccessibility _accessibilityPerformValidations:]
+ +[JULoadingViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[JULoadingViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[JULoadingViewControllerAccessibility _axRecursivelyHideSubtreeOfView:]
+ -[JULoadingViewControllerAccessibility viewDidLayoutSubviews]
+ GCC_except_table179
+ GCC_except_table195
+ GCC_except_table277
+ GCC_except_table617
+ _OBJC_CLASS_$_JULoadingViewControllerAccessibility
+ _OBJC_CLASS_$___JULoadingViewControllerAccessibility_super
+ _OBJC_METACLASS_$_JULoadingViewControllerAccessibility
+ _OBJC_METACLASS_$___JULoadingViewControllerAccessibility_super
+ __OBJC_$_CLASS_METHODS_JULoadingViewControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_JULoadingViewControllerAccessibility
+ __OBJC_CLASS_RO_$_JULoadingViewControllerAccessibility
+ __OBJC_CLASS_RO_$___JULoadingViewControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_JULoadingViewControllerAccessibility
+ __OBJC_METACLASS_RO_$___JULoadingViewControllerAccessibility_super
- -[AnnotationCollectionViewCellAccessibility _accessibilityOverridesInstructionsHint]
- -[AnnotationCollectionViewCellAccessibility _axIsAnnotationCellExpanded]
- -[AnnotationCollectionViewCellAccessibility _axIsSummaryExpandable]
- -[AnnotationCollectionViewCellAccessibility accessibilityHint]
- -[AnnotationCollectionViewCellAccessibility accessibilityTraits]
- GCC_except_table184
- GCC_except_table200
- GCC_except_table282
- GCC_except_table622
CStrings:
+ "JULoadingViewControllerAccessibility"
+ "JetUI.JULoadingViewController"
- "accessibilityCellIsExpanded"
- "accessibilityDetailItems"
- "accessibilityIsSummaryExpandable"
- "expand.annotation.cell"
```
