## MobileSafari

> `/System/Library/PrivateFrameworks/MobileSafari.framework/MobileSafari`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4d32fc` | `0x4dc8ac` | **`+0x95b0`** |
| `__AUTH_CONST.__objc_const` | `0x3a840` | `0x3afd8` | **`+0x798`** |
| `__AUTH_CONST.__const` | `0x206a0` | `0x20b30` | **`+0x490`** |
| `__TEXT.__objc_methlist` | `0x1c608` | `0x1c9c8` | **`+0x3c0`** |
| `__AUTH.__objc_data` | `0x10bd0` | `0x10ed0` | **`+0x300`** |
| `__TEXT.__gcc_except_tab` | `0x753c` | `0x77c0` | **`+0x284`** |
| `__TEXT.__unwind_info` | `0x12060` | `0x122b0` | **`+0x250`** |
| `__TEXT.__const` | `0x1c894` | `0x1caa4` | **`+0x210`** |
| `__DATA_CONST.__objc_selrefs` | `0x10098` | `0x10288` | **`+0x1f0`** |
| `__TEXT.__cstring` | `0x131d9` | `0x133c9` | **`+0x1f0`** |
| `__AUTH_CONST.__cfstring` | `0xa8e0` | `0xaac0` | **`+0x1e0`** |
| `__TEXT.__eh_frame` | `0x8c3c` | `0x8dac` | **`+0x170`** |
| `__TEXT.__swift5_typeref` | `0xcf6c` | `0xd0cc` | **`+0x160`** |
| `__TEXT.__swift5_capture` | `0x701c` | `0x7138` | **`+0x11c`** |
| `__DATA.__bss` | `0x20950` | `0x20a60` | **`+0x110`** |
| `__DATA.__data` | `0xe088` | `0xe178` | **`+0xf0`** |
| `__AUTH_CONST.__auth_got` | `0x3828` | `0x3900` | **`+0xd8`** |
| `__AUTH.__data` | `0x7fc8` | `0x8088` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x6448` | `0x6508` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x11bdc` | `0x11c8c` | **`+0xb0`** |
| `__DATA_CONST.__got` | `0x2878` | `0x28f0` | **`+0x78`** |
| `__TEXT.__swift5_reflstr` | `0xc5d1` | `0xc641` | **`+0x70`** |
| `__TEXT.__ustring` | `0x23aa` | `0x2414` | **`+0x6a`** |
| `__TEXT.__swift5_fieldmd` | `0x9a20` | `0x9a88` | **`+0x68`** |
| `__DATA_CONST.__objc_classlist` | `0x1080` | `0x10b0` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x1c9c` | `0x1cc8` | **`+0x2c`** |
| `__TEXT.__swift5_assocty` | `0x1b98` | `0x1bb0` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x4c4` | `0x4d0` | **`+0xc`** |
| `__DATA_CONST.__objc_superrefs` | `0x7c8` | `0x7d0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1198` | `0x11a0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x954` | `0x95c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x488` | `0x490` | **`+0x8`** |

### Other Changes

```diff

-625.1.18.10.4
+625.1.20.10.3

-  Functions: 26532
-  Symbols:   20084
-  CStrings:  2652
+  Functions: 26737
+  Symbols:   20214
+  CStrings:  2669
Symbols:
+ +[SFTraitIsInSegmentedViewController defaultValue]
+ +[SFTraitIsInSegmentedViewController identifier]
+ +[SFTraitIsInSegmentedViewController name]
+ -[SFClusterPreviewItem mediaStateMuteButtonTapHandler]
+ -[SFClusterPreviewItem setMediaStateMuteButtonTapHandler:]
+ -[SFClusterPreviewItemConfiguration mediaStateIcon]
+ -[SFClusterPreviewItemConfiguration setMediaStateIcon:]
+ -[SFClusterPreviewItemView _accessibilityLabelForMediaStateIcon:]
+ -[SFClusterPreviewItemView _fadeView:visible:additionalAnimations:isStillVisible:]
+ -[SFClusterPreviewItemView _mediaStateMuteButtonTapped]
+ -[SFClusterPreviewItemView _showsMediaStateMuteButton]
+ -[SFClusterPreviewItemView _updateMediaStateMuteButton]
+ -[SFClusterPreviewItemView mediaStateMuteButtonTapHandler]
+ -[SFClusterPreviewItemView setMediaStateMuteButtonTapHandler:]
+ -[SFMagicExtensionBanner initWithMagicExtensionName:icon:errorMessage:usageDescription:state:progress:openButtonHandler:bannerTapHandler:dismissButtonHandler:]
+ -[SFNotifyMeWhenBanner _fileRadarButtonTapped]
+ -[SFNotifyMeWhenBanner _makeFileRadarButton]
+ -[SFStartPageCollectionViewController _squareSectionLayoutForEnvironment:numberOfItems:sectionSupportsPagination:]
+ -[SFStartPageCollectionViewController _viewCellSectionLayoutForEnvironment:]
+ -[SFStartPageCustomizationViewController _makeSearchDataSourcesFooterRegistration]
+ -[SFStartPageCustomizationViewController _makeSearchDataSourcesHeaderRegistration]
+ -[SFStartPageCustomizationViewController _makeSearchDataSourcesToggleRegistration]
+ -[SFStartPageCustomizationViewController searchSectionFooterTextForIsRecentSearchesEnabled:]
+ -[SFStartPageSectionHeader _updateCompositingFiltersForButtons]
+ -[SFStartPageViewController rootViewVisibilityObserver]
+ -[SFStartPageViewController setRootViewVisibilityObserver:]
+ -[SFStartPageViewController setTopScrollEdgeEffectUserInterfaceStyle:]
+ -[SFStartPageViewController topScrollEdgeEffectUserInterfaceStyle]
+ -[SFUnifiedBar _indexes:ofItems:containAllItemsInGroupWithIdentifier:]
+ -[SFUnifiedBarItemGroupContainerView setTransitioning:]
+ -[SFUnifiedBarItemGroupContainerView transitioning]
+ -[SFUnifiedTabBarItemView showsSearchIconInTitleContainer]
+ -[SFUnifiedTabBarLayout _outsetsItem:]
+ -[SFUnifiedTabBarLayout outsetsSingleItem]
+ -[SFUnifiedTabBarScrollView alwaysCancelsContentTouches]
+ -[SFUnifiedTabBarScrollView setAlwaysCancelsContentTouches:]
+ -[SFUnifiedTabBarScrollView touchesShouldCancelInContentView:]
+ -[UIColor(MobileSafariExtras) safari_adaptiveGlassUserInterfaceStyle]
+ -[UITraitCollection(MobileSafariExtras) safari_isInSegmentedViewController]
+ GCC_except_table94
+ GCC_except_table98
+ _OBJC_CLASS_$_SFBrowsingAssistantFavoritedMenuActionsStore
+ _OBJC_CLASS_$_SFEnhancedSiriAvailabilityMonitor
+ _OBJC_CLASS_$_SFRecentSearchesStartPageController
+ _OBJC_CLASS_$_SFStartPageHostedViewCell
+ _OBJC_CLASS_$_SFTraitIsInSegmentedViewController
+ _OBJC_CLASS_$_SFUnifiedTabBarScrollView
+ _OBJC_CLASS_$_UIScrollEdgeEffect
+ _OBJC_CLASS_$_WBSCompletionQuery
+ _OBJC_CLASS_$_WBSMagicExtensionsController
+ _OBJC_CLASS_$_WBSTrialSearchParameters
+ _OBJC_IVAR_$_SFClusterPreviewItem._mediaStateMuteButtonTapHandler
+ _OBJC_IVAR_$_SFClusterPreviewItemConfiguration._mediaStateIcon
+ _OBJC_IVAR_$_SFClusterPreviewItemView._mediaStateMuteButton
+ _OBJC_IVAR_$_SFClusterPreviewItemView._mediaStateMuteButtonTapHandler
+ _OBJC_IVAR_$_SFNotifyMeWhenBanner._fileRadarButton
+ _OBJC_IVAR_$_SFStartPageCustomizationViewController._identifierToSearchDataSourceCustomizationItemMap
+ _OBJC_IVAR_$_SFStartPageViewController._rootViewVisibilityObserver
+ _OBJC_IVAR_$_SFStartPageViewController._topScrollEdgeEffectUserInterfaceStyle
+ _OBJC_IVAR_$_SFUnifiedBarItemGroupContainerView._transitioning
+ _OBJC_IVAR_$_SFUnifiedTabBarItemView._showsSearchIcon
+ _OBJC_IVAR_$_SFUnifiedTabBarScrollView._alwaysCancelsContentTouches
+ _OBJC_METACLASS_$_SFBrowsingAssistantFavoritedMenuActionsStore
+ _OBJC_METACLASS_$_SFEnhancedSiriAvailabilityMonitor
+ _OBJC_METACLASS_$_SFRecentSearchesStartPageController
+ _OBJC_METACLASS_$_SFStartPageHostedViewCell
+ _OBJC_METACLASS_$_SFTraitIsInSegmentedViewController
+ _OBJC_METACLASS_$_SFUnifiedTabBarScrollView
+ _SFBrowsingAssistantMenuSectionIdentifierCustomize
+ _SFBrowsingAssistantMenuSectionIdentifierEditPrivacyAndSecurityActions
+ _SFBrowsingAssistantMenuSectionIdentifierEditTabActions
+ _SFDefaultActionsMenuFavoritedActions
+ _SFDefaultActionsMenuFavoritedActions.defaultFavoritedActions
+ _SFDefaultActionsMenuFavoritedActions.onceToken
+ _SFDidMigratePreActionsMenuFavoritedMenuActionsKey
+ _WBSRecentSearchesWereUpdated
+ _WBSShouldDisplayRecentSearchesInStartPageKey
+ _WBSStartPageSectionRecentSearches
+ _WBSStartPageSectionResumeBrowsing
+ __CATEGORY_INSTANCE_METHODS_UIScrollEdgeEffect_$_MobileSafariFrameworkExtras_Swift
+ __CATEGORY_PROPERTIES_UIScrollEdgeEffect_$_MobileSafariFrameworkExtras_Swift
+ __CATEGORY_UIScrollEdgeEffect_$_MobileSafariFrameworkExtras_Swift
+ __CLASS_METHODS_SFEnhancedSiriAvailabilityMonitor
+ __CLASS_METHODS_SFStartPageHostedViewCell
+ __CLASS_PROPERTIES_SFEnhancedSiriAvailabilityMonitor
+ __CLASS_PROPERTIES_SFStartPageHostedViewCell
+ __DATA_SFBrowsingAssistantFavoritedMenuActionsStore
+ __DATA_SFEnhancedSiriAvailabilityMonitor
+ __DATA_SFRecentSearchesStartPageController
+ __DATA_SFStartPageHostedViewCell
+ __INSTANCE_METHODS_SFBrowsingAssistantFavoritedMenuActionsStore
+ __INSTANCE_METHODS_SFEnhancedSiriAvailabilityMonitor
+ __INSTANCE_METHODS_SFRecentSearchesStartPageController
+ __INSTANCE_METHODS_SFStartPageHostedViewCell
+ __IVARS_SFEnhancedSiriAvailabilityMonitor
+ __IVARS_SFRecentSearchesStartPageController
+ __IVARS_SFStartPageHostedViewCell
+ __METACLASS_DATA_SFBrowsingAssistantFavoritedMenuActionsStore
+ __METACLASS_DATA_SFEnhancedSiriAvailabilityMonitor
+ __METACLASS_DATA_SFRecentSearchesStartPageController
+ __METACLASS_DATA_SFStartPageHostedViewCell
+ __OBJC_$_CLASS_METHODS_SFTraitIsInSegmentedViewController
+ __OBJC_$_CLASS_PROP_LIST_SFTraitIsInSegmentedViewController
+ __OBJC_$_INSTANCE_METHODS_SFUnifiedTabBarScrollView
+ __OBJC_$_INSTANCE_VARIABLES_SFUnifiedTabBarScrollView
+ __OBJC_$_PROP_LIST_SFUnifiedTabBarScrollView
+ __OBJC_CLASS_PROTOCOLS_$_SFTraitIsInSegmentedViewController
+ __OBJC_CLASS_RO_$_SFTraitIsInSegmentedViewController
+ __OBJC_CLASS_RO_$_SFUnifiedTabBarScrollView
+ __OBJC_METACLASS_RO_$_SFTraitIsInSegmentedViewController
+ __OBJC_METACLASS_RO_$_SFUnifiedTabBarScrollView
+ __PROPERTIES_SFBrowsingAssistantFavoritedMenuActionsStore
+ __PROPERTIES_SFRecentSearchesStartPageController
+ __SFHighestPriorityMediaStateIcon
+ ___159-[SFMagicExtensionBanner initWithMagicExtensionName:icon:errorMessage:usageDescription:state:progress:openButtonHandler:bannerTapHandler:dismissButtonHandler:]_block_invoke
+ ___159-[SFMagicExtensionBanner initWithMagicExtensionName:icon:errorMessage:usageDescription:state:progress:openButtonHandler:bannerTapHandler:dismissButtonHandler:]_block_invoke_2
+ ___55-[SFClusterPreviewItemView _updateMediaStateMuteButton]_block_invoke
+ ___70-[SFUnifiedBar _indexes:ofItems:containAllItemsInGroupWithIdentifier:]_block_invoke
+ ___82-[SFClusterPreviewItemView _fadeView:visible:additionalAnimations:isStillVisible:]_block_invoke
+ ___82-[SFClusterPreviewItemView _fadeView:visible:additionalAnimations:isStillVisible:]_block_invoke_2
+ ___82-[SFStartPageCustomizationViewController _makeSearchDataSourcesFooterRegistration]_block_invoke
+ ___82-[SFStartPageCustomizationViewController _makeSearchDataSourcesHeaderRegistration]_block_invoke
+ ___82-[SFStartPageCustomizationViewController _makeSearchDataSourcesToggleRegistration]_block_invoke
+ ___SFDefaultActionsMenuFavoritedActions_block_invoke
+ ___block_descriptor_40_ea8_32w_e63_v32?0"UICollectionViewListCell"8"NSString"16"NSIndexPath"24lw32l8
+ ___block_descriptor_48_e8_32s40bs_e8_v12?0B8ls40l8s32l8
+ ___block_descriptor_49_e8_32s40bs_e5_v8?0ls32l8s40l8
+ ___block_descriptor_57_e8_32s40s48s_e34_v32?0"NSString"8"NSValue"16^B24ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48r56r_e33_v32?0"SFUnifiedBarItem"8Q16^B24ls32l8r48l8s40l8r56l8
+ ___block_descriptor_72_ea8_32s40s48s56s64w_e81_"UICollectionReusableView"32?0"UICollectionView"8"NSString"16"NSIndexPath"24lw64l8s32l8s40l8s48l8s56l8
+ ___block_descriptor_88_ea8_32s40s48s56s64s72s80w_e67_"UICollectionViewCell"32?0"UICollectionView"8"NSIndexPath"1624lw80l8s32l8s40l8s48l8s56l8s64l8s72l8
+ ___swift_closure_destructor.53Tm
+ ___swift_closure_destructor.69Tm
+ _keypath_get_selector_recentSearchesSectionChanged
+ _objc_retain_x12
+ _priorityOrderedIcons
+ _symbolic SDy_____yxq_q0__GSDySSypGG 12MobileSafari21SFFluidCollectionViewC7ElementO
+ _symbolic Say_____G So29SFBrowsingAssistantMenuActiona
+ _symbolic So33SFEnhancedSiriAvailabilityMonitorCSgXw
+ _symbolic So35SFRecentSearchesStartPageControllerC
+ _symbolic So35SFRecentSearchesStartPageControllerCSgXw
+ _symbolic So44SFBrowsingAssistantFavoritedMenuActionsStoreC
+ _symbolic _____ 12MobileSafari25SFStartPageHostedViewCellC
+ _symbolic _____ 12MobileSafari34SFTraitIsInSegmentedViewControllerV
+ _symbolic _____Sg So17OS_dispatch_queueC8DispatchE16SchedulerOptionsV
+ _symbolic _____xq______XjSgXw r1_l12MobileSafari40SFFluidTabOverviewViewGridLayoutDelegate_pq_4ItemRts_x7SectionRtsq0_13SupplementaryRtsXPXGMq AA0cdeL0O
+ _symbolic _____xq______XjSgXw r1_l12MobileSafari44SFFluidTabOverviewZoomableGridLayoutDelegate_pq_4ItemRts_x7SectionRtsq0_13SupplementaryRtsXPXGMq AA0cdeL0O
+ _symbolic _____ySay_____G_G 7Combine9PublishedV9PublisherV 14SafariSharedUI24WBSCompletionListSectionV
+ _symbolic _____y_____G 7SwiftUI19UIHostingControllerC 012SafariSharedB021WBSCompletionListViewV
+ _symbolic _____y_____G s11_SetStorageC So29SFBrowsingAssistantMenuActiona
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 14SafariSharedUI24WBSCompletionListContextV
+ _symbolic _____y________________G_SDySSypGt 12MobileSafari21SFFluidCollectionViewC7ElementO AA11TabOverviewC7SectionV AG4ItemV AA0cgH13SupplementaryO
+ _symbolic _____y______ySay_____G_GSo17OS_dispatch_queueCG 7Combine10PublishersO9ReceiveOnV AA9PublishedV9PublisherV 14SafariSharedUI24WBSCompletionListSectionV
+ _symbolic _____y_____y________________GSDySSypGG s18_DictionaryStorageC 12MobileSafari21SFFluidCollectionViewC7ElementO AC11TabOverviewC7SectionV AI4ItemV AC0eiJ13SupplementaryO
- -[NSUserDefaults(BrowsingAssistantExtras) browsingAssistant_favoritedMenuActions]
- -[NSUserDefaults(BrowsingAssistantExtras) browsingAssistant_isMenuActionFavorited:]
- -[NSUserDefaults(BrowsingAssistantExtras) browsingAssistant_setFavoritedMenuActions:]
- -[NSUserDefaults(BrowsingAssistantExtras) browsingAssistant_setMenuActionFavorited:favorited:]
- -[SFMagicExtensionBanner initWithMagicExtensionName:icon:errorMessage:state:progress:openButtonHandler:bannerTapHandler:dismissButtonHandler:]
- -[SFStartPageCollectionViewController _squareSectionLayoutForEnvironment:numberOfItems:]
- GCC_except_table113
- _SFBrowsingAssistantMenuSectionIdentifierCustomizeAndWebsiteSettings
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSUserDefaults_$_BrowsingAssistantExtras
- __OBJC_$_CATEGORY_NSUserDefaults_$_BrowsingAssistantExtras
- __OBJC_$_PROP_LIST_NSUserDefaults_$_BrowsingAssistantExtras
- ___142-[SFMagicExtensionBanner initWithMagicExtensionName:icon:errorMessage:state:progress:openButtonHandler:bannerTapHandler:dismissButtonHandler:]_block_invoke
- ___142-[SFMagicExtensionBanner initWithMagicExtensionName:icon:errorMessage:state:progress:openButtonHandler:bannerTapHandler:dismissButtonHandler:]_block_invoke_2
- ___81-[NSUserDefaults(BrowsingAssistantExtras) browsingAssistant_favoritedMenuActions]_block_invoke
- ___block_descriptor_32_e18_B16?0"NSString"8l
- ___block_descriptor_41_e8_32s_e34_v32?0"NSString"8"NSValue"16^B24ls32l8
- ___block_descriptor_56_ea8_32s40s48w_e81_"UICollectionReusableView"32?0"UICollectionView"8"NSString"16"NSIndexPath"24lw48l8s32l8s40l8
- ___block_descriptor_80_ea8_32s40s48s56s64s72w_e67_"UICollectionViewCell"32?0"UICollectionView"8"NSIndexPath"1624lw72l8s32l8s40l8s48l8s56l8s64l8
- ___swift_closure_destructor.71Tm
- _keypath_get_selector_controlsAreHiddenForSnapshot
- _symbolic SDy_____ypG s11AnyHashableV
- _symbolic SDy_____yxq_q0__GSDy_____ypGG 12MobileSafari21SFFluidCollectionViewC7ElementO s11AnyHashableV
- _symbolic _____y________________G_SDy_____ypGt 12MobileSafari21SFFluidCollectionViewC7ElementO AA11TabOverviewC7SectionV AG4ItemV AA0cgH13SupplementaryO s11AnyHashableV
- _symbolic _____y_____y________________GSDy_____ypGG s18_DictionaryStorageC 12MobileSafari21SFFluidCollectionViewC7ElementO AC11TabOverviewC7SectionV AI4ItemV AC0eiJ13SupplementaryO s11AnyHashableV
CStrings:
+ "Camera active in topic"
+ "Camera muted in topic"
+ "Microphone active in topic"
+ "Microphone muted in topic"
+ "MobileSafari.SFEnhancedSiriAvailabilityMonitor"
+ "Mute topic audio"
+ "PageMenuSectionCustomize"
+ "PageMenuSectionEditPrivacyAndSecurityActions"
+ "PageMenuSectionEditTabActions"
+ "Privacy & Security"
+ "Recent searches will appear on the Start Page when navigating from an existing tab."
+ "Recent searches will appear only when searching."
+ "SFDidMigratePreActionsMenuFavoritedMenuActions"
+ "Search (Start Page Customization)"
+ "Something Isn’t Right"
+ "This will close %zu tabs that aren’t in a Tab Group."
+ "Unmute topic audio"
+ "isInSegmentedViewController"
+ "ladybug"
+ "search-customization-items"
+ "\xd1"
- "PageMenuSectionCustomizeAndWebsiteSettings"
- "Something Isn't Right"
- "This will close %zu tabs that aren't in a Tab Group."
- "\xf0!"
```
