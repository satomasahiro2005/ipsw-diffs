## PhotosUIFramework

> `/System/Library/AccessibilityBundles/PhotosUIFramework.axbundle/PhotosUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1474c` | `0x140dc` | **`-0x670`** |
| `__AUTH.__objc_data` | `0x690` | `0x230` | **`-0x460`** |
| `__DATA_DIRTY.__objc_data` | `0x22b0` | `0x2710` | **`+0x460`** |
| `__AUTH_CONST.__cfstring` | `0x4f60` | `0x4f00` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0x21ac` | `0x2154` | **`-0x58`** |
| `__AUTH_CONST.__const` | `0x4c0` | `0x4a0` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x7d8` | `0x7b8` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x5050` | `0x5068` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xeb8` | `0xea0` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x250` | `0x258` | **`+0x8`** |
| `__TEXT.__cstring` | `0x3b3f` | `0x3b37` | **`-0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 672
-  Symbols:   1600
-  CStrings:  677
+  Functions: 660
+  Symbols:   1591
+  CStrings:  674
Symbols:
+ +[PUPhotoStyleTitleViewControllerAccessibility _accessibilityPerformValidations:]
+ +[PUPhotoStyleTitleViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PUPhotoStyleTitleViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PUOneUpDetailsBarButtonControllerAccessibility setWithConfiguration:]
+ -[PUPhotoStyleTitleViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
+ GCC_except_table154
+ GCC_except_table158
+ GCC_except_table213
+ GCC_except_table225
+ GCC_except_table311
+ GCC_except_table315
+ GCC_except_table319
+ GCC_except_table368
+ GCC_except_table387
+ GCC_except_table408
+ GCC_except_table432
+ GCC_except_table463
+ GCC_except_table495
+ GCC_except_table499
+ GCC_except_table502
+ GCC_except_table555
+ GCC_except_table559
+ GCC_except_table60
+ GCC_except_table63
+ GCC_except_table644
+ _OBJC_CLASS_$_PUPhotoStyleTitleViewControllerAccessibility
+ _OBJC_CLASS_$_UILabel
+ _OBJC_CLASS_$___PUPhotoStyleTitleViewControllerAccessibility_super
+ _OBJC_METACLASS_$_PUPhotoStyleTitleViewControllerAccessibility
+ _OBJC_METACLASS_$___PUPhotoStyleTitleViewControllerAccessibility_super
+ __OBJC_$_CLASS_METHODS_PUPhotoStyleTitleViewControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PUPhotoStyleTitleViewControllerAccessibility
+ __OBJC_CLASS_RO_$_PUPhotoStyleTitleViewControllerAccessibility
+ __OBJC_CLASS_RO_$___PUPhotoStyleTitleViewControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_PUPhotoStyleTitleViewControllerAccessibility
+ __OBJC_METACLASS_RO_$___PUPhotoStyleTitleViewControllerAccessibility_super
+ ___71-[PUOneUpDetailsBarButtonControllerAccessibility setWithConfiguration:]_block_invoke
+ ___72-[PUOneUpBarsControllerAccessibility _axLoadDetailsButtonAccessibility:]_block_invoke
- +[PUPickerOnboardingHeaderViewAccessibility _accessibilityPerformValidations:]
- +[PUPickerOnboardingHeaderViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[PUPickerOnboardingHeaderViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[PUOneUpBarsControllerAccessibility _handleFavoriteButton:]
- -[PUOneUpDetailsBarButtonControllerAccessibility _axAssetViewModel]
- -[PUOneUpDetailsBarButtonControllerAccessibility _axDetailsShowing]
- -[PUOneUpDetailsBarButtonControllerAccessibility _axLoadDetailsButtonAccessibility:]
- -[PUOneUpDetailsBarButtonControllerAccessibility update]
- -[PUPhotoEditMediaToolControllerAccessibility _updateTrimControlAndToolbarButtons]
- -[PUPickerOnboardingHeaderViewAccessibility _accessibilitySupplementaryFooterViews]
- -[PUPickerOnboardingHeaderViewAccessibility accessibilityLabel]
- -[PUPickerOnboardingHeaderViewAccessibility isAccessibilityElement]
- -[UIButtonAccessibility__PhotosUI__UIKit accessibilityTraits]
- GCC_except_table132
- GCC_except_table168
- GCC_except_table172
- GCC_except_table227
- GCC_except_table239
- GCC_except_table330
- GCC_except_table334
- GCC_except_table384
- GCC_except_table403
- GCC_except_table424
- GCC_except_table448
- GCC_except_table479
- GCC_except_table511
- GCC_except_table515
- GCC_except_table518
- GCC_except_table571
- GCC_except_table575
- GCC_except_table656
- GCC_except_table66
- GCC_except_table69
- _OBJC_CLASS_$_PUPickerOnboardingHeaderViewAccessibility
- _OBJC_CLASS_$___PUPickerOnboardingHeaderViewAccessibility_super
- _OBJC_METACLASS_$_PUPickerOnboardingHeaderViewAccessibility
- _OBJC_METACLASS_$___PUPickerOnboardingHeaderViewAccessibility_super
- __OBJC_$_CLASS_METHODS_PUPickerOnboardingHeaderViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_PUPickerOnboardingHeaderViewAccessibility
- __OBJC_CLASS_RO_$_PUPickerOnboardingHeaderViewAccessibility
- __OBJC_CLASS_RO_$___PUPickerOnboardingHeaderViewAccessibility_super
- __OBJC_METACLASS_RO_$_PUPickerOnboardingHeaderViewAccessibility
- __OBJC_METACLASS_RO_$___PUPickerOnboardingHeaderViewAccessibility_super
- ___56-[PUOneUpDetailsBarButtonControllerAccessibility update]_block_invoke
- ___60-[PUOneUpBarsControllerAccessibility _handleFavoriteButton:]_block_invoke
- ___61-[UIButtonAccessibility__PhotosUI__UIKit accessibilityTraits]_block_invoke
- ___67-[PUOneUpDetailsBarButtonControllerAccessibility _axAssetViewModel]_block_invoke
CStrings:
+ "PUOneUpDetailsButtonConfiguration"
+ "PUPhotoStyleTitleViewControllerAccessibility"
+ "PXUserTransformView"
+ "PhotosUIPrivate.PUPhotoStyleTitleViewController"
+ "UIBarButtonItem"
+ "customView"
+ "setWithConfiguration:"
+ "titleLabel"
- "PUPhotoEditToolPickerController"
- "PUPickerOnboardingHeaderView"
- "PUPickerOnboardingHeaderViewAccessibility"
- "_updateTrimControlAndToolbarButtons"
- "browseViewModel"
- "closeButton"
- "icon"
- "learnMoreButton"
- "selectedToolTag"
- "tag"
- "update"
```
