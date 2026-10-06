## MobileSafariUI

> `/System/Library/PrivateFrameworks/MobileSafariUI.framework/MobileSafariUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ce694` | `0x2d2fac` | **`+0x4918`** |
| `__TEXT.__gcc_except_tab` | `0x1ea2c` | `0x1ed88` | **`+0x35c`** |
| `__AUTH_CONST.__objc_const` | `0x32898` | `0x32a68` | **`+0x1d0`** |
| `__DATA_CONST.__objc_selrefs` | `0x180f0` | `0x182b0` | **`+0x1c0`** |
| `__TEXT.__objc_methlist` | `0x2477c` | `0x248e4` | **`+0x168`** |
| `__TEXT.__unwind_info` | `0xf908` | `0xfa60` | **`+0x158`** |
| `__DATA.__data` | `0x9820` | `0x9968` | **`+0x148`** |
| `__TEXT.__oslogstring` | `0xa9ef` | `0xab1f` | **`+0x130`** |
| `__AUTH_CONST.__cfstring` | `0xdb60` | `0xdc80` | **`+0x120`** |
| `__AUTH_CONST.__const` | `0x7e48` | `0x7f48` | **`+0x100`** |
| `__DATA.__bss` | `0x3180` | `0x3280` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x96d8` | `0x97a8` | **`+0xd0`** |
| `__TEXT.__const` | `0x42a0` | `0x4370` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x10544` | `0x10614` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0x5d14` | `0x5d7b` | **`+0x67`** |
| `__DATA_CONST.__got` | `0x3548` | `0x35a8` | **`+0x60`** |
| `__TEXT.__ustring` | `0x117a` | `0x11da` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x2204` | `0x2238` | **`+0x34`** |
| `__DATA.__objc_ivar` | `0x2070` | `0x2094` | **`+0x24`** |
| `__TEXT.__constg_swiftt` | `0x1c7c` | `0x1c9c` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x2384` | `0x23a4` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2b78` | `0x2b90` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x4b0` | `0x4c8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x1a4` | `0x1b8` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0xbc0` | `0xbd0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x12c` | `0x130` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x15c` | `0x160` | **`+0x4`** |

### Other Changes

```diff

-625.1.18.10.4
+625.1.20.10.3

+  - /System/Library/PrivateFrameworks/PasswordManagerUI.framework/PasswordManagerUI

+  - /System/Library/PrivateFrameworks/SafariFoundation.framework/SafariFoundation

-  Functions: 15708
-  Symbols:   22657
-  CStrings:  3226
+  Functions: 15772
+  Symbols:   22736
+  CStrings:  3238
Symbols:
+ +[CompletionListTableViewCell _transparentImageViewPlaceholder]
+ -[Application shouldGenerateEmbeddingsNow]
+ -[ApplicationShortcutController _selectStartPageLibrarySegment:]
+ -[BrowserController didFocusFavoritesForApplicationShortcut]
+ -[BrowserController notifyMeWhenBannerDidTapFileRadar:]
+ -[BrowserController setDidFocusFavoritesForApplicationShortcut:]
+ -[CapsuleNavigationBarViewController _observeActionsMenuPresentationOnNavigationBar:]
+ -[CapsuleNavigationBarViewController backAndTabsButtonsHiddenForActionsMenuPresentation]
+ -[CapsuleNavigationBarViewController capsuleCollectionView:shouldHideSupplementaryViewWithIdentifier:]
+ -[CapsuleNavigationBarViewController setBackAndTabsButtonsHiddenForActionsMenuPresentation:]
+ -[CatalogViewController didSwitchProfile]
+ -[CompletionListTableViewCell setImage:orCreateImageFromSystemImageName:]
+ -[CompletionListTableViewController _isHostedAsPopover]
+ -[LibrarySectionController itemControllerToHandleDropItemsFromSession:withProposedDestinationItemController:atIndex:intent:]
+ -[QuickWebsiteSearchCompletionItem originalURLString]
+ -[StartPageController _recentSearchesSection]
+ -[StartPageController _setShouldDisplayRecentSearchesSectionInOverlayedStartPage:]
+ -[StartPageController _shouldDisplayRecentSearchesSectionInOverlayedStartPage]
+ -[StartPageController _shouldDisplayRecentSearchesSection]
+ -[StartPageController recentSearchesController:didSelectSearchString:]
+ -[TabDocument allowsBrowsingAssistantForReaderController:]
+ -[TabGroupLibraryItemController isDirectDropDestination]
+ -[TabGroupLibraryItemController setIsDirectDropDestination:]
+ -[TabGroupLibrarySectionController itemControllerToHandleDropItemsFromSession:withProposedDestinationItemController:atIndex:intent:]
+ -[WBSPageTestController(WBSBulkIntelligenceInferenceControllerDelegate) automaticPasswordChangeController:canAutoFillNewPasswordOnPageWithCompletionHandler:]
+ GCC_except_table1005
+ GCC_except_table1007
+ GCC_except_table1012
+ GCC_except_table1023
+ GCC_except_table1024
+ GCC_except_table1029
+ GCC_except_table1031
+ GCC_except_table1037
+ GCC_except_table1045
+ GCC_except_table1046
+ GCC_except_table1059
+ GCC_except_table1064
+ GCC_except_table1066
+ GCC_except_table1091
+ GCC_except_table1100
+ GCC_except_table1107
+ GCC_except_table1111
+ GCC_except_table1113
+ GCC_except_table1117
+ GCC_except_table1118
+ GCC_except_table1122
+ GCC_except_table1128
+ GCC_except_table1129
+ GCC_except_table1130
+ GCC_except_table1136
+ GCC_except_table1140
+ GCC_except_table1141
+ GCC_except_table1152
+ GCC_except_table1168
+ GCC_except_table1170
+ GCC_except_table1175
+ GCC_except_table1177
+ GCC_except_table1181
+ GCC_except_table1185
+ GCC_except_table1189
+ GCC_except_table1198
+ GCC_except_table1200
+ GCC_except_table1206
+ GCC_except_table1208
+ GCC_except_table1212
+ GCC_except_table1219
+ GCC_except_table1220
+ GCC_except_table1221
+ GCC_except_table1235
+ GCC_except_table1236
+ GCC_except_table1240
+ GCC_except_table1241
+ GCC_except_table1242
+ GCC_except_table1258
+ GCC_except_table1259
+ GCC_except_table1266
+ GCC_except_table1270
+ GCC_except_table1278
+ GCC_except_table1279
+ GCC_except_table1284
+ GCC_except_table1286
+ GCC_except_table1299
+ GCC_except_table1304
+ GCC_except_table1316
+ GCC_except_table1320
+ GCC_except_table1322
+ GCC_except_table1330
+ GCC_except_table1336
+ GCC_except_table1343
+ GCC_except_table1351
+ GCC_except_table1353
+ GCC_except_table1355
+ GCC_except_table140
+ GCC_except_table141
+ GCC_except_table1428
+ GCC_except_table1431
+ GCC_except_table206
+ GCC_except_table210
+ GCC_except_table224
+ GCC_except_table227
+ GCC_except_table253
+ GCC_except_table362
+ GCC_except_table376
+ GCC_except_table378
+ GCC_except_table392
+ GCC_except_table397
+ GCC_except_table402
+ GCC_except_table410
+ GCC_except_table414
+ GCC_except_table440
+ GCC_except_table481
+ GCC_except_table486
+ GCC_except_table505
+ GCC_except_table538
+ GCC_except_table574
+ GCC_except_table584
+ GCC_except_table586
+ GCC_except_table596
+ GCC_except_table617
+ GCC_except_table621
+ GCC_except_table649
+ GCC_except_table754
+ GCC_except_table756
+ GCC_except_table771
+ GCC_except_table778
+ GCC_except_table786
+ GCC_except_table813
+ GCC_except_table825
+ GCC_except_table843
+ GCC_except_table854
+ GCC_except_table855
+ GCC_except_table863
+ GCC_except_table877
+ GCC_except_table878
+ GCC_except_table888
+ GCC_except_table905
+ GCC_except_table909
+ GCC_except_table910
+ GCC_except_table914
+ GCC_except_table918
+ GCC_except_table921
+ GCC_except_table936
+ GCC_except_table937
+ GCC_except_table945
+ GCC_except_table947
+ GCC_except_table953
+ GCC_except_table956
+ GCC_except_table982
+ _OBJC_CLASS_$_PMSafariAutoFillStrongPasswordIntroductionViewController
+ _OBJC_CLASS_$_SFEnhancedSiriAvailabilityMonitor
+ _OBJC_CLASS_$_SFRecentSearchesStartPageController
+ _OBJC_CLASS_$_SFSafariCredentialStore
+ _OBJC_CLASS_$_WBSCompletionListIconHostingController
+ _OBJC_CLASS_$_WBSEmbeddingScheduler
+ _OBJC_CLASS_$_WBSSearchProvidersController
+ _OBJC_IVAR_$_BrowserController._didFocusFavoritesForApplicationShortcut
+ _OBJC_IVAR_$_BrowserController._enhancedSiriAvailabilityMonitor
+ _OBJC_IVAR_$_CapsuleNavigationBarViewController._backAndTabsButtonsHiddenForActionsMenuPresentation
+ _OBJC_IVAR_$_CompletionListTableViewCell._completionIconHostingController
+ _OBJC_IVAR_$_CompletionListTableViewCell._iconView
+ _OBJC_IVAR_$_StartPageController._recentSearchesStartPageController
+ _OBJC_IVAR_$_TabDocument._currentNavigationIsPageInitiated
+ _OBJC_IVAR_$_TabDocument._navigationRedirectChainURLs
+ _OBJC_IVAR_$_TabDocument._openerPageURL
+ _OBJC_IVAR_$_TabGroupLibraryItemController._isDirectDropDestination
+ _WBSCompletionListIconCornerRadiusRatio
+ _WBSCompletionListPlatteredIconSize
+ _WBSShouldDisplayRecentSearchesInStartPageKey
+ _WBSStartPageSectionRecentSearches
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SFRecentSearchesStartPageControllerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_WBSEmbeddingSchedulerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SFRecentSearchesStartPageControllerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_WBSEmbeddingSchedulerDelegate
+ __OBJC_$_PROTOCOL_REFS_SFRecentSearchesStartPageControllerDelegate
+ __OBJC_$_PROTOCOL_REFS_WBSEmbeddingSchedulerDelegate
+ __OBJC_LABEL_PROTOCOL_$_SFRecentSearchesStartPageControllerDelegate
+ __OBJC_LABEL_PROTOCOL_$_WBSEmbeddingSchedulerDelegate
+ __OBJC_PROTOCOL_$_SFRecentSearchesStartPageControllerDelegate
+ __OBJC_PROTOCOL_$_WBSEmbeddingSchedulerDelegate
+ __SFHighestPriorityMediaStateIcon
+ __SFMediaStateIconForWBSMediaCaptureState
+ __ZNSt3__119__shared_weak_count16__release_sharedB9sqe220106Ev
+ __ZZL21getPKPassLibraryClassvE9softClass
+ ___105-[BrowserController initWithUUID:sceneID:browserWindowController:tabGroupManager:controlledByAutomation:]_block_invoke_17
+ ___132-[TabGroupLibrarySectionController itemControllerToHandleDropItemsFromSession:withProposedDestinationItemController:atIndex:intent:]_block_invoke
+ ___34-[TabDocument _showDownload:path:]_block_invoke_3
+ ___42-[BrowserController shouldShowShareAction]_block_invoke
+ ___45-[StartPageController _recentSearchesSection]_block_invoke
+ ___45-[StartPageController _recentSearchesSection]_block_invoke_2
+ ___51-[StartPageController initWithVisualStyleProvider:]_block_invoke_3
+ ___51-[StartPageController initWithVisualStyleProvider:]_block_invoke_4
+ ___53-[StartPageController _updateStartPageSectionManager]_block_invoke
+ ___63+[CompletionListTableViewCell _transparentImageViewPlaceholder]_block_invoke
+ ___63+[CompletionListTableViewCell _transparentImageViewPlaceholder]_block_invoke_2
+ ___85-[CapsuleNavigationBarViewController _observeActionsMenuPresentationOnNavigationBar:]_block_invoke
+ ___85-[CapsuleNavigationBarViewController _observeActionsMenuPresentationOnNavigationBar:]_block_invoke_2
+ ___85-[CapsuleNavigationBarViewController _observeActionsMenuPresentationOnNavigationBar:]_block_invoke_3
+ ___85-[CapsuleNavigationBarViewController _observeActionsMenuPresentationOnNavigationBar:]_block_invoke_4
+ ____ZL21getPKPassLibraryClassv_block_invoke
+ ___block_descriptor_32_e40_v16?0"UIGraphicsImageRendererContext"8l
+ ___block_descriptor_40_e8_32bs_e17_v16?0"NSArray"8ls32l8
+ ___block_descriptor_40_e8_32bs_e45_v16?0"<UIContextMenuInteractionAnimating>"8ls32l8
+ ___block_descriptor_40_ea8_32r_e49_v32?0q8"<_SFBarRegistrationToken>"16"UIView"24lr32l8
+ ___block_descriptor_40_ea8_32s_e11_v24?0816ls32l8
+ ___block_descriptor_65_ea8_32s40s48s56w_e8_v16?0q8lw56l8s32l8s40l8s48l8
+ ___block_descriptor_73_ea8_32s40s48s56w_e5_v8?0lw56l8s32l8s40l8s48l8
+ ___block_descriptor_81_ea8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_88_ea8_32s40s48s56s64s72bs_e5_v8?0ls32l8s40l8s72l8s48l8s56l8s64l8
+ __transparentImageViewPlaceholder.onceToken
+ __transparentImageViewPlaceholder.transparentImageViewPlaceholder
+ _keypath_get_selector_controlsAreHiddenForSnapshot
+ _symbolic So15SFUnifiedTabBarC
+ _symbolic So23BookmarksClusterManagerCXMT
+ _symbolic _____ So17_SFMediaStateIconV
+ _symbolic _____ySSSo14WBSPageContextCG s18_DictionaryStorageC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So17_SFMediaStateIconV
- -[CompletionListTableViewCell completionIconSystemImageName]
- -[CompletionListTableViewCell initWithStyle:reuseIdentifier:]
- -[CompletionListTableViewCell setCompletionIconSystemImageName:]
- -[LibrarySectionController itemControllerToHandleDropItemsFromSession:withProposedDestinationItemController:atIndex:]
- -[TabController contextManagerShouldGenerateEmbeddingsNow:]
- -[TabDocument _showPassBookControllerForPasses:]
- -[TabGroupLibrarySectionController itemControllerToHandleDropItemsFromSession:withProposedDestinationItemController:atIndex:]
- GCC_except_table1008
- GCC_except_table1010
- GCC_except_table1015
- GCC_except_table1026
- GCC_except_table1033
- GCC_except_table1034
- GCC_except_table1035
- GCC_except_table1043
- GCC_except_table1048
- GCC_except_table1049
- GCC_except_table1062
- GCC_except_table1067
- GCC_except_table1069
- GCC_except_table1094
- GCC_except_table1103
- GCC_except_table1110
- GCC_except_table1114
- GCC_except_table1116
- GCC_except_table1120
- GCC_except_table1121
- GCC_except_table1125
- GCC_except_table1132
- GCC_except_table1133
- GCC_except_table1134
- GCC_except_table1142
- GCC_except_table1144
- GCC_except_table1149
- GCC_except_table1155
- GCC_except_table1171
- GCC_except_table1173
- GCC_except_table1178
- GCC_except_table1180
- GCC_except_table1184
- GCC_except_table1188
- GCC_except_table1192
- GCC_except_table1201
- GCC_except_table1203
- GCC_except_table1209
- GCC_except_table1211
- GCC_except_table1222
- GCC_except_table1224
- GCC_except_table1226
- GCC_except_table1238
- GCC_except_table1239
- GCC_except_table1243
- GCC_except_table1245
- GCC_except_table1250
- GCC_except_table1264
- GCC_except_table1265
- GCC_except_table1269
- GCC_except_table1273
- GCC_except_table1281
- GCC_except_table1285
- GCC_except_table1292
- GCC_except_table1293
- GCC_except_table1302
- GCC_except_table1307
- GCC_except_table1319
- GCC_except_table1331
- GCC_except_table1332
- GCC_except_table1333
- GCC_except_table1339
- GCC_except_table1346
- GCC_except_table137
- GCC_except_table138
- GCC_except_table1423
- GCC_except_table1426
- GCC_except_table146
- GCC_except_table232
- GCC_except_table350
- GCC_except_table391
- GCC_except_table482
- GCC_except_table526
- GCC_except_table573
- GCC_except_table579
- GCC_except_table588
- GCC_except_table619
- GCC_except_table622
- GCC_except_table658
- GCC_except_table693
- GCC_except_table695
- GCC_except_table745
- GCC_except_table755
- GCC_except_table757
- GCC_except_table772
- GCC_except_table779
- GCC_except_table787
- GCC_except_table803
- GCC_except_table815
- GCC_except_table829
- GCC_except_table845
- GCC_except_table857
- GCC_except_table858
- GCC_except_table862
- GCC_except_table865
- GCC_except_table866
- GCC_except_table880
- GCC_except_table883
- GCC_except_table903
- GCC_except_table911
- GCC_except_table912
- GCC_except_table915
- GCC_except_table916
- GCC_except_table922
- GCC_except_table923
- GCC_except_table924
- GCC_except_table941
- GCC_except_table942
- GCC_except_table950
- GCC_except_table959
- GCC_except_table960
- GCC_except_table965
- GCC_except_table975
- GCC_except_table976
- GCC_except_table985
- _OBJC_CLASS_$_WBSCompletionIconProvider
- _OBJC_IVAR_$_CompletionListTableViewCell._completionIconSystemImageName
- _OUTLINED_FUNCTION_120
- __OBJC_$_PROP_LIST_CompletionListTableViewCell
- __ZL18PassKitCoreLibraryv
- __ZNSt3__119__shared_weak_count16__release_sharedB9sqe220100Ev
- __ZZL14getPKPassClassvE9softClass
- __ZZL28getPKPassesXPCContainerClassvE9softClass
- ___125-[TabGroupLibrarySectionController itemControllerToHandleDropItemsFromSession:withProposedDestinationItemController:atIndex:]_block_invoke
- ____ZL14getPKPassClassv_block_invoke
- ____ZL28getPKPassesXPCContainerClassv_block_invoke
- ___block_descriptor_40_ea8_32s_e36_v40?0"PKPass"8Q16"NSString"24^B32ls32l8
- ___block_descriptor_64_ea8_32s40s48s56s_e17_v16?0"NSArray"8ls32l8s40l8s48l8s56l8
- ___block_descriptor_65_ea8_32s40s_e5_v8?0ls32l8s40l8
- ___block_descriptor_80_ea8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s64l8s48l8s56l8
CStrings:
+ "; ai item = %@"
+ "AI Search Suggestion"
+ "AISearchSuggestion"
+ "Clear (Recent Searches)"
+ "Deferring featureText backfill: Apple Intelligence not available"
+ "Don’t Show Links on Hover"
+ "PKPassLibrary"
+ "Recent Searches (Start Page Customization)"
+ "Recent Searches (Start Page Section Title)"
+ "SFContinuousReadingBanner"
+ "Safari groups related tabs into topics."
+ "Safari requested starting playback because of app intent based invocation"
+ "Safari requested starting playback because of menu based invocation"
+ "Show Related Tabs"
+ "Something Isn’t Right"
+ "WebsiteSettings"
+ "_bookmarksDonationWriter is nil when attempting to reindex all searchable items. It should be intialized before reindexing"
+ "_bookmarksDonationWriter is nil when attempting to reindex all searchable items. It should be intialized before reindexing."
+ "actions menu"
+ "from collapsed cluster media indicator"
+ "magnifyingglass.badge.sparkles"
+ "v16@?0@\"<UIContextMenuInteractionAnimating>\"8"
+ "v24@?0@8@16"
+ "\xf0\xf0\xf0Q"
- "By Recommended Topics"
- "Don't Show Links on Hover"
- "PKPass"
- "PKPassesXPCContainer"
- "PassBook Pass download failed: %{public}@"
- "PassBook passes download succeeded, showing passbook adding passes view controller."
- "Safari automatically detects related tabs and groups them into topics."
- "Safari requested starting playback"
- "ShowRecentSearches"
- "Something Isn't Right"
- "v40@?0@\"PKPass\"8Q16@\"NSString\"24^B32"
- "\xf0\xf0\xf0A"
```
