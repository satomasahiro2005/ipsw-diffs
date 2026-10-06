## Arcade

> `/System/Library/AccessibilityBundles/Arcade.axbundle/Arcade`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x76b0` | `0x77d0` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x41f0` | `0x4290` | **`+0xa0`** |
| `__TEXT.__text` | `0xa7e4` | `0xa864` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x39a0` | `0x3960` | **`-0x40`** |
| `__TEXT.__cstring` | `0x36e2` | `0x36a5` | **`-0x3d`** |
| `__TEXT.__objc_methlist` | `0x276c` | `0x2784` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x698` | `0x6a8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x528` | `0x530` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1f8` | `0x200` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Symbols:   1843
-  CStrings:  496
+  Symbols:   1853
+  CStrings:  494
Symbols:
+ +[JULoadingViewControllerAccessibility _accessibilityPerformValidations:]
+ +[JULoadingViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[JULoadingViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[JULoadingViewControllerAccessibility _axRecursivelyHideSubtreeOfView:]
+ -[JULoadingViewControllerAccessibility viewDidLayoutSubviews]
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
CStrings:
+ "JULoadingViewControllerAccessibility"
+ "JetUI.JULoadingViewController"
+ "accessibilityLinkLabelTapped"
- "AppUpdatesDetailCollectionViewCellAccessibility"
- "accessibilityCellIsExpanded"
- "accessibilityDetailItems"
- "accessibilityIsSummaryExpandable"
- "expand.annotation.cell"
```
