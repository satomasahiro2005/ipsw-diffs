## ASMessagesProvider

> `/System/Library/AccessibilityBundles/ASMessagesProvider.axbundle/ASMessagesProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x76b0` | `0x77d0` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x41f0` | `0x4290` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x39a0` | `0x3940` | **`-0x60`** |
| `__TEXT.__cstring` | `0x3cd5` | `0x3c7b` | **`-0x5a`** |
| `__TEXT.__objc_methlist` | `0x270c` | `0x2724` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x698` | `0x6a8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x508` | `0x510` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1f8` | `0x200` | **`+0x8`** |
| `__TEXT.__text` | `0xb428` | `0xb424` | **`-0x4`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Symbols:   1832
-  CStrings:  506
+  Symbols:   1842
+  CStrings:  503
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
Functions:
~ +[AppUpdatesDetailCollectionViewCellAccessibility _accessibilityPerformValidations:] : 184 -> 216
~ -[AppUpdatesDetailCollectionViewCellAccessibility accessibilityTraits] : 72 -> 128
~ +[AlertActionTrailingImageViewAccessibility _accessibilityPerformValidations:] -> +[JULoadingViewControllerAccessibility _accessibilityPerformValidations:] : 64 -> 24
~ -[AlertActionTrailingImageViewAccessibility isAccessibilityElement] -> -[JULoadingViewControllerAccessibility _axRecursivelyHideSubtreeOfView:] : 8 -> 308
~ -[AlertActionTrailingImageViewAccessibility accessibilityLabel] -> -[JULoadingViewControllerAccessibility viewDidLayoutSubviews] : 12 -> 184
~ -[AlertActionTrailingImageViewAccessibility accessibilityTraits] -> +[AlertActionTrailingImageViewAccessibility(SafeCategory) safeCategoryTargetClassName] : 72 -> 12
~ +[AnnotationCollectionViewCellAccessibility(SafeCategory) safeCategoryBaseClass] -> +[AlertActionTrailingImageViewAccessibility _accessibilityPerformValidations:] : 12 -> 64
~ +[AnnotationCollectionViewCellAccessibility _accessibilityPerformValidations:] -> -[AlertActionTrailingImageViewAccessibility isAccessibilityElement] : 288 -> 8
~ -[AnnotationCollectionViewCellAccessibility isAccessibilityElement] -> -[AlertActionTrailingImageViewAccessibility accessibilityLabel] : 8 -> 12
~ -[AnnotationCollectionViewCellAccessibility accessibilityLabel] -> -[AlertActionTrailingImageViewAccessibility accessibilityTraits] : 200 -> 72
~ -[AnnotationCollectionViewCellAccessibility accessibilityCustomActions] -> +[AnnotationCollectionViewCellAccessibility _accessibilityPerformValidations:] : 248 -> 188
~ -[AnnotationCollectionViewCellAccessibility _accessibilityPerformLinkAction:] -> -[AnnotationCollectionViewCellAccessibility isAccessibilityElement] : 112 -> 8
~ ___77-[AnnotationCollectionViewCellAccessibility _accessibilityPerformLinkAction:]_block_invoke -> -[AnnotationCollectionViewCellAccessibility accessibilityLabel] : 8 -> 12
~ -[AnnotationCollectionViewCellAccessibility accessibilityTraits] -> -[AnnotationCollectionViewCellAccessibility accessibilityCustomActions] : 116 -> 236
~ -[AnnotationCollectionViewCellAccessibility accessibilityHint] -> -[AnnotationCollectionViewCellAccessibility _accessibilityPerformLinkAction:] : 128 -> 112
~ -[AnnotationCollectionViewCellAccessibility _accessibilityOverridesInstructionsHint] -> ___77-[AnnotationCollectionViewCellAccessibility _accessibilityPerformLinkAction:]_block_invoke : 64 -> 8
CStrings:
+ "JULoadingViewControllerAccessibility"
+ "JetUI.JULoadingViewController"
- "AppUpdatesDetailCollectionViewCellAccessibility"
- "accessibilityCellIsExpanded"
- "accessibilityDetailItems"
- "accessibilityIsSummaryExpandable"
- "expand.annotation.cell"
```
