## Podcasts

> `/System/Library/AccessibilityBundles/Podcasts.axbundle/Podcasts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa6f8` | `0x7f74` | **`-0x2784`** |
| `__AUTH_CONST.__objc_const` | `0x4850` | `0x3998` | **`-0xeb8`** |
| `__AUTH_CONST.__cfstring` | `0x3060` | `0x25a0` | **`-0xac0`** |
| `__TEXT.__cstring` | `0x2599` | `0x1d94` | **`-0x805`** |
| `__DATA_DIRTY.__objc_data` | `0x23f0` | `0x1c70` | **`-0x780`** |
| `__TEXT.__objc_methlist` | `0x18dc` | `0x132c` | **`-0x5b0`** |
| `__TEXT.__unwind_info` | `0x520` | `0x410` | **`-0x110`** |
| `__DATA_CONST.__objc_selrefs` | `0x630` | `0x538` | **`-0xf8`** |
| `__DATA_CONST.__objc_classlist` | `0x3e8` | `0x318` | **`-0xd0`** |
| `__AUTH.__objc_data` | `0x320` | `0x280` | **`-0xa0`** |
| `__DATA_CONST.__const` | `0x238` | `0x1e8` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x120` | `0xe8` | **`-0x38`** |
| `__AUTH_CONST.__const` | `0xe0` | `0xc0` | **`-0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x120` | `0x108` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1c8` | `0x1b0` | **`-0x18`** |
| `__DATA.__bss` | `0x11` | `0x1` | **`-0x10`** |
| `__TEXT.__ustring` | `0x4` | `—` | **`-0x4`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 417
-  Symbols:   1194
-  CStrings:  420
+  Functions: 314
+  Symbols:   947
+  CStrings:  327
Symbols:
+ +[DownloadButtonAccessibility _accessibilityPerformValidations:]
+ +[DownloadButtonAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[DownloadButtonAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[DownloadButtonAccessibility accessibilityTraits]
+ GCC_except_table120
+ GCC_except_table147
+ GCC_except_table168
+ GCC_except_table192
+ GCC_except_table219
+ GCC_except_table277
+ GCC_except_table305
+ GCC_except_table67
+ GCC_except_table70
+ GCC_except_table81
+ GCC_except_table85
+ _OBJC_CLASS_$_DownloadButtonAccessibility
+ _OBJC_CLASS_$___DownloadButtonAccessibility_super
+ _OBJC_METACLASS_$_DownloadButtonAccessibility
+ _OBJC_METACLASS_$___DownloadButtonAccessibility_super
+ __OBJC_$_CLASS_METHODS_DownloadButtonAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_DownloadButtonAccessibility
+ __OBJC_CLASS_RO_$_DownloadButtonAccessibility
+ __OBJC_CLASS_RO_$___DownloadButtonAccessibility_super
+ __OBJC_METACLASS_RO_$_DownloadButtonAccessibility
+ __OBJC_METACLASS_RO_$___DownloadButtonAccessibility_super
- +[CircleListCellAccessibility _accessibilityPerformValidations:]
- +[CircleListCellAccessibility(SafeCategory) safeCategoryBaseClass]
- +[CircleListCellAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[MTActionButtonContainerViewAccessibility _accessibilityPerformValidations:]
- +[MTActionButtonContainerViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[MTActionButtonContainerViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[MTAddPodcastCellAccessoryViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[MTAddPodcastCellAccessoryViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[MTCollectionSectionHeaderViewAccessibility _accessibilityPerformValidations:]
- +[MTCollectionSectionHeaderViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[MTCollectionSectionHeaderViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[MTEpisodeDownloadCellAccessibility _accessibilityPerformValidations:]
- +[MTEpisodeDownloadCellAccessibility(SafeCategory) safeCategoryBaseClass]
- +[MTEpisodeDownloadCellAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[MTPodcastInfoViewAccessibility _accessibilityPerformValidations:]
- +[MTPodcastInfoViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[MTPodcastInfoViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[MTPodcastPlaylistSheetHeaderViewAccessibility _accessibilityPerformValidations:]
- +[MTPodcastPlaylistSheetHeaderViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[MTPodcastPlaylistSheetHeaderViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[MTSwitchAccessibility(SafeCategory) safeCategoryBaseClass]
- +[MTSwitchAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[MTSwitchCellAccessibility_temp _accessibilityPerformValidations:]
- +[MTSwitchCellAccessibility_temp(SafeCategory) safeCategoryBaseClass]
- +[MTSwitchCellAccessibility_temp(SafeCategory) safeCategoryTargetClassName]
- +[MTTVSectionHeaderViewAccessibility _accessibilityPerformValidations:]
- +[MTTVSectionHeaderViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[MTTVSectionHeaderViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[ModernProductReviewCollectionViewCellAccessibility _accessibilityPerformValidations:]
- +[ModernProductReviewCollectionViewCellAccessibility(SafeCategory) safeCategoryBaseClass]
- +[ModernProductReviewCollectionViewCellAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[ModernTitleHeaderViewAccessibility _accessibilityPerformValidations:]
- +[ModernTitleHeaderViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[ModernTitleHeaderViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[MusicLibraryAddKeepLocalControlAccessibility _accessibilityPerformValidations:]
- +[MusicLibraryAddKeepLocalControlAccessibility(SafeCategory) safeCategoryBaseClass]
- +[MusicLibraryAddKeepLocalControlAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[ShowMetadataViewAccessibility _accessibilityPerformValidations:]
- +[ShowMetadataViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[ShowMetadataViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[CircleListCellAccessibility accessibilityLabel]
- -[CircleListCellAccessibility accessibilityTraits]
- -[CircleListCellAccessibility isAccessibilityElement]
- -[MTActionButtonContainerViewAccessibility accessibilityElementsHidden]
- -[MTAddPodcastCellAccessoryViewAccessibility accessibilityLabel]
- -[MTAddPodcastCellAccessoryViewAccessibility accessibilityTraits]
- -[MTAddPodcastCellAccessoryViewAccessibility isAccessibilityElement]
- -[MTCollectionSectionHeaderViewAccessibility accessibilityLabel]
- -[MTCollectionSectionHeaderViewAccessibility accessibilityTraits]
- -[MTCollectionSectionHeaderViewAccessibility isAccessibilityElement]
- -[MTEpisodeDownloadCellAccessibility _accessibilitySupplementaryFooterViews]
- -[MTEpisodeDownloadCellAccessibility _privateAccessibilityCustomActions]
- -[MTEpisodeDownloadCellAccessibility accessibilityDeleteAction:]
- -[MTEpisodeDownloadCellAccessibility accessibilityLabel]
- -[MTEpisodeDownloadCellAccessibility isAccessibilityElement]
- -[MTPodcastInfoViewAccessibility accessibilityLabel]
- -[MTPodcastInfoViewAccessibility isAccessibilityElement]
- -[MTPodcastPlaylistSheetHeaderViewAccessibility _axSwitch]
- -[MTPodcastPlaylistSheetHeaderViewAccessibility accessibilityActivationPoint]
- -[MTPodcastPlaylistSheetHeaderViewAccessibility accessibilityLabel]
- -[MTPodcastPlaylistSheetHeaderViewAccessibility accessibilityTraits]
- -[MTPodcastPlaylistSheetHeaderViewAccessibility accessibilityValue]
- -[MTPodcastPlaylistSheetHeaderViewAccessibility isAccessibilityElement]
- -[MTSwitchAccessibility accessibilityLabel]
- -[MTSwitchAccessibility accessibilityValue]
- -[MTSwitchAccessibility isAccessibilityElement]
- -[MTSwitchCellAccessibility_temp accessibilityActivationPoint]
- -[MTSwitchCellAccessibility_temp accessibilityTraits]
- -[MTSwitchCellAccessibility_temp accessibilityValue]
- -[MTSwitchCellAccessibility_temp isAccessibilityElement]
- -[MTTVSectionHeaderViewAccessibility accessibilityLabel]
- -[MTTVSectionHeaderViewAccessibility accessibilityTraits]
- -[MTTVSectionHeaderViewAccessibility isAccessibilityElement]
- -[ModernProductReviewCollectionViewCellAccessibility accessibilityLabel]
- -[ModernProductReviewCollectionViewCellAccessibility accessibilityTraits]
- -[ModernProductReviewCollectionViewCellAccessibility accessibilityValue]
- -[ModernProductReviewCollectionViewCellAccessibility automationElements]
- -[ModernTitleHeaderViewAccessibility _accessibilitySupplementaryFooterViews]
- -[ModernTitleHeaderViewAccessibility _axFavoriteHeaderButton]
- -[ModernTitleHeaderViewAccessibility _axSuggestLessButton]
- -[ModernTitleHeaderViewAccessibility accessibilityElements]
- -[ModernTitleHeaderViewAccessibility accessibilityLabel]
- -[ModernTitleHeaderViewAccessibility accessibilityTraits]
- -[ModernTitleHeaderViewAccessibility accessibilityValue]
- -[ModernTitleHeaderViewAccessibility isAccessibilityElement]
- -[MusicLibraryAddKeepLocalControlAccessibility _accessibilityCustomActionLabelForControlStatus:]
- -[MusicLibraryAddKeepLocalControlAccessibility _accessibilityCustomActionLabel]
- -[MusicLibraryAddKeepLocalControlAccessibility _accessibilityLabelForStatusType:]
- -[MusicLibraryAddKeepLocalControlAccessibility _accessibilityLoadAccessibilityInformation]
- -[MusicLibraryAddKeepLocalControlAccessibility _accessibilitySetCustomActionLabel:]
- -[MusicLibraryAddKeepLocalControlAccessibility _accessibilityValueForStatusType:andDownloadProgress:]
- -[MusicLibraryAddKeepLocalControlAccessibility _accessibilityisStatusStructValidated]
- -[MusicLibraryAddKeepLocalControlAccessibility _updateControlStatusProperties]
- -[MusicLibraryAddKeepLocalControlAccessibility accessibilityLabel]
- -[MusicLibraryAddKeepLocalControlAccessibility accessibilityTraits]
- -[MusicLibraryAddKeepLocalControlAccessibility accessibilityValue]
- -[MusicLibraryAddKeepLocalControlAccessibility isAccessibilityElement]
- -[MusicLibraryAddKeepLocalControlAccessibility setControlStatus:animated:]
- -[MusicLibraryAddKeepLocalControlAccessibility setTitle:forControlStatusType:]
- -[ShowMetadataViewAccessibility accessibilityLabel]
- -[ShowMetadataViewAccessibility isAccessibilityElement]
- -[ShowMetadataViewAccessibility ratingFormatter]
- GCC_except_table130
- GCC_except_table157
- GCC_except_table184
- GCC_except_table223
- GCC_except_table233
- GCC_except_table275
- GCC_except_table380
- GCC_except_table408
- GCC_except_table77
- GCC_except_table80
- GCC_except_table91
- GCC_except_table95
- _AXCustomActionSortPriorityDelete
- _AXFormatFloatWithPercentage
- _CGSizeZero
- _OBJC_CLASS_$_CircleListCellAccessibility
- _OBJC_CLASS_$_MTActionButtonContainerViewAccessibility
- _OBJC_CLASS_$_MTAddPodcastCellAccessoryViewAccessibility
- _OBJC_CLASS_$_MTCollectionSectionHeaderViewAccessibility
- _OBJC_CLASS_$_MTEpisodeDownloadCellAccessibility
- _OBJC_CLASS_$_MTPodcastInfoViewAccessibility
- _OBJC_CLASS_$_MTPodcastPlaylistSheetHeaderViewAccessibility
- _OBJC_CLASS_$_MTSwitchAccessibility
- _OBJC_CLASS_$_MTSwitchCellAccessibility_temp
- _OBJC_CLASS_$_MTTVSectionHeaderViewAccessibility
- _OBJC_CLASS_$_ModernProductReviewCollectionViewCellAccessibility
- _OBJC_CLASS_$_ModernTitleHeaderViewAccessibility
- _OBJC_CLASS_$_MusicLibraryAddKeepLocalControlAccessibility
- _OBJC_CLASS_$_NSNumberFormatter
- _OBJC_CLASS_$_ShowMetadataViewAccessibility
- _OBJC_CLASS_$_UIButton
- _OBJC_CLASS_$_UICollectionView
- _OBJC_CLASS_$___CircleListCellAccessibility_super
- _OBJC_CLASS_$___MTActionButtonContainerViewAccessibility_super
- _OBJC_CLASS_$___MTAddPodcastCellAccessoryViewAccessibility_super
- _OBJC_CLASS_$___MTCollectionSectionHeaderViewAccessibility_super
- _OBJC_CLASS_$___MTEpisodeDownloadCellAccessibility_super
- _OBJC_CLASS_$___MTPodcastInfoViewAccessibility_super
- _OBJC_CLASS_$___MTPodcastPlaylistSheetHeaderViewAccessibility_super
- _OBJC_CLASS_$___MTSwitchAccessibility_super
- _OBJC_CLASS_$___MTSwitchCellAccessibility_temp_super
- _OBJC_CLASS_$___MTTVSectionHeaderViewAccessibility_super
- _OBJC_CLASS_$___ModernProductReviewCollectionViewCellAccessibility_super
- _OBJC_CLASS_$___ModernTitleHeaderViewAccessibility_super
- _OBJC_CLASS_$___MusicLibraryAddKeepLocalControlAccessibility_super
- _OBJC_CLASS_$___ShowMetadataViewAccessibility_super
- _OBJC_METACLASS_$_CircleListCellAccessibility
- _OBJC_METACLASS_$_MTActionButtonContainerViewAccessibility
- _OBJC_METACLASS_$_MTAddPodcastCellAccessoryViewAccessibility
- _OBJC_METACLASS_$_MTCollectionSectionHeaderViewAccessibility
- _OBJC_METACLASS_$_MTEpisodeDownloadCellAccessibility
- _OBJC_METACLASS_$_MTPodcastInfoViewAccessibility
- _OBJC_METACLASS_$_MTPodcastPlaylistSheetHeaderViewAccessibility
- _OBJC_METACLASS_$_MTSwitchAccessibility
- _OBJC_METACLASS_$_MTSwitchCellAccessibility_temp
- _OBJC_METACLASS_$_MTTVSectionHeaderViewAccessibility
- _OBJC_METACLASS_$_ModernProductReviewCollectionViewCellAccessibility
- _OBJC_METACLASS_$_ModernTitleHeaderViewAccessibility
- _OBJC_METACLASS_$_MusicLibraryAddKeepLocalControlAccessibility
- _OBJC_METACLASS_$_ShowMetadataViewAccessibility
- _OBJC_METACLASS_$___CircleListCellAccessibility_super
- _OBJC_METACLASS_$___MTActionButtonContainerViewAccessibility_super
- _OBJC_METACLASS_$___MTAddPodcastCellAccessoryViewAccessibility_super
- _OBJC_METACLASS_$___MTCollectionSectionHeaderViewAccessibility_super
- _OBJC_METACLASS_$___MTEpisodeDownloadCellAccessibility_super
- _OBJC_METACLASS_$___MTPodcastInfoViewAccessibility_super
- _OBJC_METACLASS_$___MTPodcastPlaylistSheetHeaderViewAccessibility_super
- _OBJC_METACLASS_$___MTSwitchAccessibility_super
- _OBJC_METACLASS_$___MTSwitchCellAccessibility_temp_super
- _OBJC_METACLASS_$___MTTVSectionHeaderViewAccessibility_super
- _OBJC_METACLASS_$___ModernProductReviewCollectionViewCellAccessibility_super
- _OBJC_METACLASS_$___ModernTitleHeaderViewAccessibility_super
- _OBJC_METACLASS_$___MusicLibraryAddKeepLocalControlAccessibility_super
- _OBJC_METACLASS_$___ShowMetadataViewAccessibility_super
- _UIAccessibilityTraitHeader
- __AXTraitsRemoveTrait
- __OBJC_$_CLASS_METHODS_CircleListCellAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_MTActionButtonContainerViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_MTAddPodcastCellAccessoryViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_MTCollectionSectionHeaderViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_MTEpisodeDownloadCellAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_MTPodcastInfoViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_MTPodcastPlaylistSheetHeaderViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_MTSwitchAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_MTSwitchCellAccessibility_temp(SafeCategory)
- __OBJC_$_CLASS_METHODS_MTTVSectionHeaderViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_ModernProductReviewCollectionViewCellAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_ModernTitleHeaderViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_MusicLibraryAddKeepLocalControlAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_ShowMetadataViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_CircleListCellAccessibility
- __OBJC_$_INSTANCE_METHODS_MTActionButtonContainerViewAccessibility
- __OBJC_$_INSTANCE_METHODS_MTAddPodcastCellAccessoryViewAccessibility
- __OBJC_$_INSTANCE_METHODS_MTCollectionSectionHeaderViewAccessibility
- __OBJC_$_INSTANCE_METHODS_MTEpisodeDownloadCellAccessibility
- __OBJC_$_INSTANCE_METHODS_MTPodcastInfoViewAccessibility
- __OBJC_$_INSTANCE_METHODS_MTPodcastPlaylistSheetHeaderViewAccessibility
- __OBJC_$_INSTANCE_METHODS_MTSwitchAccessibility
- __OBJC_$_INSTANCE_METHODS_MTSwitchCellAccessibility_temp
- __OBJC_$_INSTANCE_METHODS_MTTVSectionHeaderViewAccessibility
- __OBJC_$_INSTANCE_METHODS_ModernProductReviewCollectionViewCellAccessibility
- __OBJC_$_INSTANCE_METHODS_ModernTitleHeaderViewAccessibility
- __OBJC_$_INSTANCE_METHODS_MusicLibraryAddKeepLocalControlAccessibility
- __OBJC_$_INSTANCE_METHODS_ShowMetadataViewAccessibility
- __OBJC_$_PROP_LIST_MusicLibraryAddKeepLocalControlAccessibility
- __OBJC_CLASS_RO_$_CircleListCellAccessibility
- __OBJC_CLASS_RO_$_MTActionButtonContainerViewAccessibility
- __OBJC_CLASS_RO_$_MTAddPodcastCellAccessoryViewAccessibility
- __OBJC_CLASS_RO_$_MTCollectionSectionHeaderViewAccessibility
- __OBJC_CLASS_RO_$_MTEpisodeDownloadCellAccessibility
- __OBJC_CLASS_RO_$_MTPodcastInfoViewAccessibility
- __OBJC_CLASS_RO_$_MTPodcastPlaylistSheetHeaderViewAccessibility
- __OBJC_CLASS_RO_$_MTSwitchAccessibility
- __OBJC_CLASS_RO_$_MTSwitchCellAccessibility_temp
- __OBJC_CLASS_RO_$_MTTVSectionHeaderViewAccessibility
- __OBJC_CLASS_RO_$_ModernProductReviewCollectionViewCellAccessibility
- __OBJC_CLASS_RO_$_ModernTitleHeaderViewAccessibility
- __OBJC_CLASS_RO_$_MusicLibraryAddKeepLocalControlAccessibility
- __OBJC_CLASS_RO_$_ShowMetadataViewAccessibility
- __OBJC_CLASS_RO_$___CircleListCellAccessibility_super
- __OBJC_CLASS_RO_$___MTActionButtonContainerViewAccessibility_super
- __OBJC_CLASS_RO_$___MTAddPodcastCellAccessoryViewAccessibility_super
- __OBJC_CLASS_RO_$___MTCollectionSectionHeaderViewAccessibility_super
- __OBJC_CLASS_RO_$___MTEpisodeDownloadCellAccessibility_super
- __OBJC_CLASS_RO_$___MTPodcastInfoViewAccessibility_super
- __OBJC_CLASS_RO_$___MTPodcastPlaylistSheetHeaderViewAccessibility_super
- __OBJC_CLASS_RO_$___MTSwitchAccessibility_super
- __OBJC_CLASS_RO_$___MTSwitchCellAccessibility_temp_super
- __OBJC_CLASS_RO_$___MTTVSectionHeaderViewAccessibility_super
- __OBJC_CLASS_RO_$___ModernProductReviewCollectionViewCellAccessibility_super
- __OBJC_CLASS_RO_$___ModernTitleHeaderViewAccessibility_super
- __OBJC_CLASS_RO_$___MusicLibraryAddKeepLocalControlAccessibility_super
- __OBJC_CLASS_RO_$___ShowMetadataViewAccessibility_super
- __OBJC_METACLASS_RO_$_CircleListCellAccessibility
- __OBJC_METACLASS_RO_$_MTActionButtonContainerViewAccessibility
- __OBJC_METACLASS_RO_$_MTAddPodcastCellAccessoryViewAccessibility
- __OBJC_METACLASS_RO_$_MTCollectionSectionHeaderViewAccessibility
- __OBJC_METACLASS_RO_$_MTEpisodeDownloadCellAccessibility
- __OBJC_METACLASS_RO_$_MTPodcastInfoViewAccessibility
- __OBJC_METACLASS_RO_$_MTPodcastPlaylistSheetHeaderViewAccessibility
- __OBJC_METACLASS_RO_$_MTSwitchAccessibility
- __OBJC_METACLASS_RO_$_MTSwitchCellAccessibility_temp
- __OBJC_METACLASS_RO_$_MTTVSectionHeaderViewAccessibility
- __OBJC_METACLASS_RO_$_ModernProductReviewCollectionViewCellAccessibility
- __OBJC_METACLASS_RO_$_ModernTitleHeaderViewAccessibility
- __OBJC_METACLASS_RO_$_MusicLibraryAddKeepLocalControlAccessibility
- __OBJC_METACLASS_RO_$_ShowMetadataViewAccessibility
- __OBJC_METACLASS_RO_$___CircleListCellAccessibility_super
- __OBJC_METACLASS_RO_$___MTActionButtonContainerViewAccessibility_super
- __OBJC_METACLASS_RO_$___MTAddPodcastCellAccessoryViewAccessibility_super
- __OBJC_METACLASS_RO_$___MTCollectionSectionHeaderViewAccessibility_super
- __OBJC_METACLASS_RO_$___MTEpisodeDownloadCellAccessibility_super
- __OBJC_METACLASS_RO_$___MTPodcastInfoViewAccessibility_super
- __OBJC_METACLASS_RO_$___MTPodcastPlaylistSheetHeaderViewAccessibility_super
- __OBJC_METACLASS_RO_$___MTSwitchAccessibility_super
- __OBJC_METACLASS_RO_$___MTSwitchCellAccessibility_temp_super
- __OBJC_METACLASS_RO_$___MTTVSectionHeaderViewAccessibility_super
- __OBJC_METACLASS_RO_$___ModernProductReviewCollectionViewCellAccessibility_super
- __OBJC_METACLASS_RO_$___ModernTitleHeaderViewAccessibility_super
- __OBJC_METACLASS_RO_$___MusicLibraryAddKeepLocalControlAccessibility_super
- __OBJC_METACLASS_RO_$___ShowMetadataViewAccessibility_super
- ___56-[MTEpisodeDownloadCellAccessibility accessibilityLabel]_block_invoke
- ___57-[CachingArtworkViewAccessibility isAccessibilityElement]_block_invoke
- ___85-[MusicLibraryAddKeepLocalControlAccessibility _accessibilityisStatusStructValidated]_block_invoke
- ___MusicLibraryAddKeepLocalControlAccessibility___accessibilityCustomActionLabel
- ___block_descriptor_56_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
- __accessibilityisStatusStructValidated.onceToken
- __accessibilityisStatusStructValidated.validated
- _dispatch_once
- _kAXSpacerTrait
CStrings:
+ "DownloadButtonAccessibility"
+ "Optional<ProgressState>"
+ "ShelfKitCollectionViews.DownloadButton"
+ "accessibilityEyebrowLabel, accessibilityTitleLabel, accessibilityDescriptionLabel, accessibilityFooterLabel"
+ "isAudio"
+ "isVideo"
+ "progress"
+ "progressState"
- ", "
- "AudioVideoSwitch"
- "Bool"
- "CircleListCellAccessibility"
- "EyebrowBuilderSource"
- "Float"
- "IMExpandingLabel"
- "MTActionButtonContainerView"
- "MTActionButtonContainerViewAccessibility"
- "MTAddPodcastCellAccessoryView"
- "MTAddPodcastCellAccessoryViewAccessibility"
- "MTCollectionSectionHeaderView"
- "MTCollectionView"
- "MTCollectionViewCell"
- "MTDownloadsCollectionViewController"
- "MTEpisodeDownloadCell"
- "MTEpisodeDownloadCellAccessibility"
- "MTGenericCollectionCell"
- "MTPodcastInfoView"
- "MTPodcastPlaylistSheetHeaderView"
- "MTPodcastPlaylistSheetHeaderViewAccessibility"
- "MTSwitch"
- "MTSwitchAccessibility"
- "MTSwitchCell"
- "MTSwitchCellAccessibility_temp"
- "MTTVSectionHeaderView"
- "ModernProductReviewCollectionViewCellAccessibility"
- "ModernTitleHeaderViewAccessibility"
- "MusicLibraryAddKeepLocalControl"
- "MusicLibraryAddKeepLocalControlAccessibility"
- "NSNumberFormatter"
- "Optional<Eyebrow>"
- "PodcastsFoundation.Eyebrow"
- "ShelfKit.LibraryEpisodeLockup"
- "ShelfKitCollectionViews.CircleListCell"
- "ShelfKitCollectionViews.EpisodeHeaderCollectionViewCell"
- "ShelfKitCollectionViews.FavoriteHeaderButton"
- "ShelfKitCollectionViews.ModernProductReviewCollectionViewCell"
- "ShelfKitCollectionViews.ModernTitleHeaderView"
- "ShelfKitCollectionViews.ShowMetadataView"
- "ShelfKitCollectionViews.SuggestLessButton"
- "ShowMetadataViewAccessibility"
- "UICollectionView"
- "UISwitch"
- "_added"
- "_controlStatus"
- "_controlTitleLabel"
- "_switch"
- "_title"
- "_updateControlStatusProperties"
- "accessibilityDateLabel"
- "accessibilityHasContextAction"
- "accessibilityHeaderButton"
- "accessibilityReviewMoreButton"
- "accessibilityTextLabel"
- "accessibilityTitleLabel, accessibilityDescriptionLabel, accessibilityFooterLabel"
- "accessibilityTitleLabel, accessibilityRatingView, accessibilityDateLabel, accessibilityUsernameLabel"
- "accessibilityUsernameLabel"
- "add.to.playlist"
- "audio"
- "authorLabel"
- "av.switch.label"
- "av.switch.value.audio"
- "av.switch.value.video"
- "c"
- "cancel.download"
- "collectionView"
- "controlStatus"
- "delegate"
- "deleteButton"
- "descriptionView"
- "download.button"
- "downloadButton"
- "downloading.percentage"
- "episodeForDownloadAtIndex:"
- "eyebrow"
- "filter"
- "hasVideo"
- "isExplicit"
- "isOn"
- "label"
- "not.selected"
- "numberFormatter"
- "numberOfRatings"
- "ordinalLabel"
- "rating"
- "ratings.count"
- "selected"
- "setControlStatus:animated:"
- "setTitle:forControlStatusType:"
- "stars.count"
- "text"
- "textLabel"
- "titleButton"
- "toggle"
- "toggleChanged:"
- "userInteractionEnabled"
- "video"
- "waiting.download"
- "{MusicLibraryAddKeepLocalControlStatus=qd}"
- "·"
```
