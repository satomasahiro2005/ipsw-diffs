## VideosUIFramework

> `/System/Library/AccessibilityBundles/VideosUIFramework.axbundle/VideosUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15f4c` | `0x15104` | **`-0xe48`** |
| `__AUTH_CONST.__objc_const` | `0x6b70` | `0x6390` | **`-0x7e0`** |
| `__AUTH_CONST.__cfstring` | `0x4c20` | `0x48a0` | **`-0x380`** |
| `__DATA_DIRTY.__objc_data` | `0x2c10` | `0x28f0` | **`-0x320`** |
| `__TEXT.__objc_methlist` | `0x242c` | `0x21bc` | **`-0x270`** |
| `__TEXT.__cstring` | `0x3e3b` | `0x3bec` | **`-0x24f`** |
| `__AUTH.__objc_data` | `0xfa0` | `0xe60` | **`-0x140`** |
| `__DATA_CONST.__objc_classlist` | `0x5f8` | `0x588` | **`-0x70`** |
| `__TEXT.__unwind_info` | `0x8b0` | `0x848` | **`-0x68`** |
| `__DATA_CONST.__const` | `0x770` | `0x728` | **`-0x48`** |
| `__AUTH_CONST.__const` | `0x840` | `0x800` | **`-0x40`** |
| `__DATA_CONST.__objc_superrefs` | `0x218` | `0x1f8` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1d8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa20` | `0xa28` | **`+0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 724
-  Symbols:   1931
-  CStrings:  690
+  Functions: 682
+  Symbols:   1817
+  CStrings:  665
Symbols:
+ +[MediaShelfViewControllerAccessibility _accessibilityPerformValidations:]
+ +[MediaShelfViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[MediaShelfViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[MediaShelfViewControllerAccessibility viewDidAppear:]
+ -[VUIButtonAccessibility _axIsFollowingSportsButton]
+ GCC_except_table144
+ GCC_except_table156
+ GCC_except_table163
+ GCC_except_table199
+ GCC_except_table210
+ GCC_except_table238
+ GCC_except_table271
+ GCC_except_table272
+ GCC_except_table278
+ GCC_except_table410
+ GCC_except_table444
+ GCC_except_table575
+ GCC_except_table627
+ _OBJC_CLASS_$_MediaShelfViewControllerAccessibility
+ _OBJC_CLASS_$___MediaShelfViewControllerAccessibility_super
+ _OBJC_METACLASS_$_MediaShelfViewControllerAccessibility
+ _OBJC_METACLASS_$___MediaShelfViewControllerAccessibility_super
+ __OBJC_$_CLASS_METHODS_MediaShelfViewControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_MediaShelfViewControllerAccessibility
+ __OBJC_CLASS_RO_$_MediaShelfViewControllerAccessibility
+ __OBJC_CLASS_RO_$___MediaShelfViewControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_MediaShelfViewControllerAccessibility
+ __OBJC_METACLASS_RO_$___MediaShelfViewControllerAccessibility_super
+ ___55-[MediaShelfViewControllerAccessibility viewDidAppear:]_block_invoke
- +[EpicShowcaseViewControllerAccessibility _accessibilityPerformValidations:]
- +[EpicShowcaseViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[EpicShowcaseViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[VUIDownloadButtonAccessibility _accessibilityPerformValidations:]
- +[VUIDownloadButtonAccessibility(SafeCategory) safeCategoryBaseClass]
- +[VUIDownloadButtonAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[VUILibraryMenuItemViewCellAccessibility _accessibilityPerformValidations:]
- +[VUILibraryMenuItemViewCellAccessibility(SafeCategory) safeCategoryBaseClass]
- +[VUILibraryMenuItemViewCellAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[VUIMenuCollectionViewCellAccessibility _accessibilityPerformValidations:]
- +[VUIMenuCollectionViewCellAccessibility(SafeCategory) safeCategoryBaseClass]
- +[VUIMenuCollectionViewCellAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[VUITVEpisodeInformationViewAccessibility _accessibilityPerformValidations:]
- +[VUITVEpisodeInformationViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[VUITVEpisodeInformationViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[VUIVideoAdvisoryLegendViewAccessibility _accessibilityPerformValidations:]
- +[VUIVideoAdvisoryLegendViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[VUIVideoAdvisoryLegendViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[VUIVideoAdvisoryViewAccessibility _accessibilityPerformValidations:]
- +[VUIVideoAdvisoryViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[VUIVideoAdvisoryViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[VideosUI_EpicInlineViewAccessibility _accessibilityPerformValidations:]
- +[VideosUI_EpicInlineViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[VideosUI_EpicInlineViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[EpicShowcaseViewControllerAccessibility viewDidAppear:]
- -[VUIDownloadButtonAccessibility _accessibilityDownloadState]
- -[VUIDownloadButtonAccessibility accessibilityHint]
- -[VUIDownloadButtonAccessibility accessibilityLabel]
- -[VUIDownloadButtonAccessibility accessibilityTraits]
- -[VUIDownloadButtonAccessibility accessibilityValue]
- -[VUIDownloadButtonAccessibility isAccessibilityElement]
- -[VUILibraryMenuItemViewCellAccessibility accessibilityLabel]
- -[VUILibraryMenuItemViewCellAccessibility accessibilityTraits]
- -[VUILibraryMenuItemViewCellAccessibility isAccessibilityElement]
- -[VUIMenuCollectionViewCellAccessibility accessibilityLabel]
- -[VUIStackingPosterViewAccessibility _accessibilityLoadAccessibilityInformation]
- -[VUIStackingPosterViewAccessibility layoutSubviews]
- -[VUITVEpisodeInformationViewAccessibility accessibilityLabel]
- -[VUIVideoAdvisoryLegendViewAccessibility accessibilityLabel]
- -[VUIVideoAdvisoryViewAccessibility accessibilityLabel]
- -[VUIVideoAdvisoryViewAccessibility accessibilityValue]
- -[VUIVideoAdvisoryViewAccessibility isAccessibilityElement]
- -[VideosUI_EpicInlineViewAccessibility _accessibilityLoadAccessibilityInformation]
- -[VideosUI_EpicInlineViewAccessibility layoutSubviews]
- GCC_except_table143
- GCC_except_table155
- GCC_except_table162
- GCC_except_table211
- GCC_except_table222
- GCC_except_table250
- GCC_except_table283
- GCC_except_table284
- GCC_except_table290
- GCC_except_table435
- GCC_except_table473
- GCC_except_table604
- GCC_except_table669
- _OBJC_CLASS_$_EpicShowcaseViewControllerAccessibility
- _OBJC_CLASS_$_VUIDownloadButtonAccessibility
- _OBJC_CLASS_$_VUILibraryMenuItemViewCellAccessibility
- _OBJC_CLASS_$_VUIMenuCollectionViewCellAccessibility
- _OBJC_CLASS_$_VUITVEpisodeInformationViewAccessibility
- _OBJC_CLASS_$_VUIVideoAdvisoryLegendViewAccessibility
- _OBJC_CLASS_$_VUIVideoAdvisoryViewAccessibility
- _OBJC_CLASS_$_VideosUI_EpicInlineViewAccessibility
- _OBJC_CLASS_$___EpicShowcaseViewControllerAccessibility_super
- _OBJC_CLASS_$___VUIDownloadButtonAccessibility_super
- _OBJC_CLASS_$___VUILibraryMenuItemViewCellAccessibility_super
- _OBJC_CLASS_$___VUIMenuCollectionViewCellAccessibility_super
- _OBJC_CLASS_$___VUITVEpisodeInformationViewAccessibility_super
- _OBJC_CLASS_$___VUIVideoAdvisoryLegendViewAccessibility_super
- _OBJC_CLASS_$___VUIVideoAdvisoryViewAccessibility_super
- _OBJC_CLASS_$___VideosUI_EpicInlineViewAccessibility_super
- _OBJC_METACLASS_$_EpicShowcaseViewControllerAccessibility
- _OBJC_METACLASS_$_VUIDownloadButtonAccessibility
- _OBJC_METACLASS_$_VUILibraryMenuItemViewCellAccessibility
- _OBJC_METACLASS_$_VUIMenuCollectionViewCellAccessibility
- _OBJC_METACLASS_$_VUITVEpisodeInformationViewAccessibility
- _OBJC_METACLASS_$_VUIVideoAdvisoryLegendViewAccessibility
- _OBJC_METACLASS_$_VUIVideoAdvisoryViewAccessibility
- _OBJC_METACLASS_$_VideosUI_EpicInlineViewAccessibility
- _OBJC_METACLASS_$___EpicShowcaseViewControllerAccessibility_super
- _OBJC_METACLASS_$___VUIDownloadButtonAccessibility_super
- _OBJC_METACLASS_$___VUILibraryMenuItemViewCellAccessibility_super
- _OBJC_METACLASS_$___VUIMenuCollectionViewCellAccessibility_super
- _OBJC_METACLASS_$___VUITVEpisodeInformationViewAccessibility_super
- _OBJC_METACLASS_$___VUIVideoAdvisoryLegendViewAccessibility_super
- _OBJC_METACLASS_$___VUIVideoAdvisoryViewAccessibility_super
- _OBJC_METACLASS_$___VideosUI_EpicInlineViewAccessibility_super
- _UIAccessibilityTraitUpdatesFrequently
- __OBJC_$_CLASS_METHODS_EpicShowcaseViewControllerAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_VUIDownloadButtonAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_VUILibraryMenuItemViewCellAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_VUIMenuCollectionViewCellAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_VUITVEpisodeInformationViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_VUIVideoAdvisoryLegendViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_VUIVideoAdvisoryViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_VideosUI_EpicInlineViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_EpicShowcaseViewControllerAccessibility
- __OBJC_$_INSTANCE_METHODS_VUIDownloadButtonAccessibility
- __OBJC_$_INSTANCE_METHODS_VUILibraryMenuItemViewCellAccessibility
- __OBJC_$_INSTANCE_METHODS_VUIMenuCollectionViewCellAccessibility
- __OBJC_$_INSTANCE_METHODS_VUITVEpisodeInformationViewAccessibility
- __OBJC_$_INSTANCE_METHODS_VUIVideoAdvisoryLegendViewAccessibility
- __OBJC_$_INSTANCE_METHODS_VUIVideoAdvisoryViewAccessibility
- __OBJC_$_INSTANCE_METHODS_VideosUI_EpicInlineViewAccessibility
- __OBJC_CLASS_RO_$_EpicShowcaseViewControllerAccessibility
- __OBJC_CLASS_RO_$_VUIDownloadButtonAccessibility
- __OBJC_CLASS_RO_$_VUILibraryMenuItemViewCellAccessibility
- __OBJC_CLASS_RO_$_VUIMenuCollectionViewCellAccessibility
- __OBJC_CLASS_RO_$_VUITVEpisodeInformationViewAccessibility
- __OBJC_CLASS_RO_$_VUIVideoAdvisoryLegendViewAccessibility
- __OBJC_CLASS_RO_$_VUIVideoAdvisoryViewAccessibility
- __OBJC_CLASS_RO_$_VideosUI_EpicInlineViewAccessibility
- __OBJC_CLASS_RO_$___EpicShowcaseViewControllerAccessibility_super
- __OBJC_CLASS_RO_$___VUIDownloadButtonAccessibility_super
- __OBJC_CLASS_RO_$___VUILibraryMenuItemViewCellAccessibility_super
- __OBJC_CLASS_RO_$___VUIMenuCollectionViewCellAccessibility_super
- __OBJC_CLASS_RO_$___VUITVEpisodeInformationViewAccessibility_super
- __OBJC_CLASS_RO_$___VUIVideoAdvisoryLegendViewAccessibility_super
- __OBJC_CLASS_RO_$___VUIVideoAdvisoryViewAccessibility_super
- __OBJC_CLASS_RO_$___VideosUI_EpicInlineViewAccessibility_super
- __OBJC_METACLASS_RO_$_EpicShowcaseViewControllerAccessibility
- __OBJC_METACLASS_RO_$_VUIDownloadButtonAccessibility
- __OBJC_METACLASS_RO_$_VUILibraryMenuItemViewCellAccessibility
- __OBJC_METACLASS_RO_$_VUIMenuCollectionViewCellAccessibility
- __OBJC_METACLASS_RO_$_VUITVEpisodeInformationViewAccessibility
- __OBJC_METACLASS_RO_$_VUIVideoAdvisoryLegendViewAccessibility
- __OBJC_METACLASS_RO_$_VUIVideoAdvisoryViewAccessibility
- __OBJC_METACLASS_RO_$_VideosUI_EpicInlineViewAccessibility
- __OBJC_METACLASS_RO_$___EpicShowcaseViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$___VUIDownloadButtonAccessibility_super
- __OBJC_METACLASS_RO_$___VUILibraryMenuItemViewCellAccessibility_super
- __OBJC_METACLASS_RO_$___VUIMenuCollectionViewCellAccessibility_super
- __OBJC_METACLASS_RO_$___VUITVEpisodeInformationViewAccessibility_super
- __OBJC_METACLASS_RO_$___VUIVideoAdvisoryLegendViewAccessibility_super
- __OBJC_METACLASS_RO_$___VUIVideoAdvisoryViewAccessibility_super
- __OBJC_METACLASS_RO_$___VideosUI_EpicInlineViewAccessibility_super
- ___57-[EpicShowcaseViewControllerAccessibility viewDidAppear:]_block_invoke
- ___80-[VUIStackingPosterViewAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
- ___82-[VideosUI_EpicInlineViewAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
- ___82-[VideosUI_EpicInlineViewAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_2
- ___block_descriptor_40_e8_32s_e12_B24?08^B16ls32l8
CStrings:
+ "CollectionViewFeaturedView"
+ "MediaShelfViewControllerAccessibility"
+ "Optional<CanonicalBannerInfoView>"
+ "Optional<CollectionViewCellInteractor>"
+ "UpNextButtonPresenter"
+ "VideosUI.BaseCollectionViewCell"
+ "VideosUI.CollectionHeaderView"
+ "VideosUI.CollectionViewFeaturedCell"
+ "VideosUI.MediaShelfViewController"
+ "VideosUI.UpNextButtonPresenter"
+ "infoView"
+ "overrideTextValue"
- "EpicShowcaseViewControllerAccessibility"
- "UICollectionViewCell"
- "VUIBaseCollectionViewCell"
- "VUICollectionViewFeaturedCell"
- "VUIDownloadButton"
- "VUIDownloadButtonAccessibility"
- "VUIDownloadButtonViewModel"
- "VUILayeredImageContainerView"
- "VUILibraryMenuItemViewCell"
- "VUILibraryMenuItemViewCellAccessibility"
- "VUIMenuCollectionViewCell"
- "VUITVEpisodeInformationView"
- "VUIUpNextButton"
- "VUIUpNextButtonProperties"
- "VUIVideoAdvisoryLegendView"
- "VUIVideoAdvisoryLegendViewAccessibility"
- "VUIVideoAdvisoryView"
- "VUIVideoAdvisoryViewAccessibility"
- "VideosUI.CollectionRichHeaderView"
- "VideosUI.EpicInlineView"
- "VideosUI.EpicShowcaseViewController"
- "VideosUI.LegacyEditorialCollectionViewCell"
- "_configureSubviewsWithDictionary:"
- "_downloadState"
- "advisories.title"
- "d"
- "descriptionLabel"
- "download.button.cancel.hint"
- "download.button.remove.hint"
- "episodeLabel"
- "hideAnimated:platterView:completion:"
- "legendDescriptionLabel"
- "legendViews"
- "metadataView"
- "properties"
- "showAnimated:platterView:completion:"
- "textValue"
```
