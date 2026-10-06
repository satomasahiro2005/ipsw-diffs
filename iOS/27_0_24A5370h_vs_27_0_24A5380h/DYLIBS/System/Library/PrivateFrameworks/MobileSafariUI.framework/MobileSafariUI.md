## MobileSafariUI

> `/System/Library/PrivateFrameworks/MobileSafariUI.framework/MobileSafariUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d2fac` | `0x2d7dc4` | **`+0x4e18`** |
| `__TEXT.__gcc_except_tab` | `0x1ed88` | `0x1f1c0` | **`+0x438`** |
| `__AUTH.__objc_data` | `0x32f0` | `0x30f0` | **`-0x200`** |
| `__DATA_DIRTY.__objc_data` | `0x4440` | `0x4640` | **`+0x200`** |
| `__AUTH_CONST.__objc_const` | `0x32a68` | `0x32c58` | **`+0x1f0`** |
| `__DATA_CONST.__objc_selrefs` | `0x182b0` | `0x18498` | **`+0x1e8`** |
| `__DATA.__bss` | `0x3280` | `0x30c0` | **`-0x1c0`** |
| `__DATA_DIRTY.__bss` | `0x9d0` | `0xb90` | **`+0x1c0`** |
| `__AUTH_CONST.__const` | `0x7f48` | `0x80f8` | **`+0x1b0`** |
| `__TEXT.__objc_methlist` | `0x248e4` | `0x24a5c` | **`+0x178`** |
| `__DATA_DIRTY.__data` | `0x11c8` | `0x12c0` | **`+0xf8`** |
| `__TEXT.__unwind_info` | `0xfa60` | `0xfb48` | **`+0xe8`** |
| `__DATA.__data` | `0x9968` | `0x9898` | **`-0xd0`** |
| `__DATA_CONST.__got` | `0x35a8` | `0x3678` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0xdc80` | `0xdd40` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x10614` | `0x106a4` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x2238` | `0x22a8` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x5d7b` | `0x5dd9` | **`+0x5e`** |
| `__AUTH.__data` | `0xda8` | `0xd50` | **`-0x58`** |
| `__TEXT.__dlopen_cstrs` | `0x83a` | `0x7e6` | **`-0x54`** |
| `__DATA_CONST.__const` | `0x97a8` | `0x97f8` | **`+0x50`** |
| `__TEXT.__const` | `0x4370` | `0x43b0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0xab1f` | `0xab4f` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x1c9c` | `0x1c84` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2b90` | `0x2ba0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2094` | `0x20a4` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xd6c` | `0xd78` | **`+0xc`** |
| `__TEXT.__eh_frame` | `0x23a4` | `0x239c` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-625.1.20.10.3
+625.1.22.10.3

+  - /System/Library/PrivateFrameworks/PassKitCore.framework/PassKitCore

-  Functions: 15772
-  Symbols:   22736
-  CStrings:  3238
+  Functions: 15847
+  Symbols:   22791
+  CStrings:  3245
Symbols:
+ +[WBSParsecDSession sendLaunchFeedbackWithEvent:isPrivate:usesLoweredSearchBar:isStartPageVisible:]
+ -[Application activeWindowIsShowingStartPage]
+ -[ApplicationShortcutController _openNewEmptyTabWithURLFieldFocused:privateBrowsingState:showingRecentSearches:]
+ -[BrowserController magicExtensionsController:didFinishRefiningExtension:name:icon:shouldReloadPage:shouldPromptAboutNewTabPage:]
+ -[BrowserController notifyMeWhenBanner:didSelectFeedbackAction:]
+ -[BrowserController recentSearchWasEngagedOnStartPage:]
+ -[CatalogViewController _suppressFavoritesUnfocusForLibrarySearch]
+ -[CompletionListTableViewCell setShouldApplyBlendMode:]
+ -[CompletionListTableViewCell shouldApplyBlendMode]
+ -[CompletionListTableViewDataSource isHostedAsPopover]
+ -[CompletionListTableViewDataSource setIsHostedAsPopover:]
+ -[ReadingListMetadataFetcher _saveBackfilledFeatureText:fetchError:forBookmarkWithID:]
+ -[SearchSuggestionTableViewCell _setSearchSuggestion:ranges:]
+ -[SearchSuggestionTableViewCell setSearchSuggestion:withHighlightedRanges:]
+ -[StartPageController _buildResultsForSectionIdentifier:bundleIdentifier:]
+ -[StartPageController _emitEnabledSectionsForSessionQueryID:]
+ -[StartPageController _emitStartPageFeedbackOnAppear]
+ -[StartPageController invalidateCollectionViewLayout]
+ -[StartPageController notifyStartPageDidAppear]
+ -[StartPageController updateStartPageSessionQueryID:]
+ -[StartPageController viewControllerIfLoaded]
+ -[WBSAnalyticsLogger(BookmarksAnalyticsLogger) _performBookmarkClusteringUsageReport]
+ -[WBSAnalyticsLogger(BookmarksAnalyticsLogger) _performBookmarksUsageReport]
+ -[WBSPageTestController(WBSBulkIntelligenceInferenceControllerDelegate) automaticPasswordChangeController:firstVisibleFormMatchingPredicate:completionHandler:]
+ GCC_except_table1008
+ GCC_except_table1015
+ GCC_except_table1026
+ GCC_except_table1027
+ GCC_except_table1030
+ GCC_except_table1033
+ GCC_except_table1040
+ GCC_except_table1043
+ GCC_except_table1048
+ GCC_except_table1049
+ GCC_except_table1062
+ GCC_except_table1067
+ GCC_except_table1094
+ GCC_except_table1103
+ GCC_except_table1110
+ GCC_except_table1114
+ GCC_except_table1120
+ GCC_except_table1121
+ GCC_except_table1125
+ GCC_except_table1131
+ GCC_except_table1132
+ GCC_except_table1139
+ GCC_except_table1142
+ GCC_except_table1143
+ GCC_except_table1149
+ GCC_except_table1155
+ GCC_except_table1171
+ GCC_except_table1178
+ GCC_except_table1184
+ GCC_except_table1188
+ GCC_except_table1192
+ GCC_except_table1201
+ GCC_except_table1209
+ GCC_except_table1215
+ GCC_except_table1222
+ GCC_except_table1223
+ GCC_except_table1238
+ GCC_except_table1239
+ GCC_except_table1243
+ GCC_except_table1244
+ GCC_except_table1250
+ GCC_except_table1261
+ GCC_except_table1262
+ GCC_except_table1265
+ GCC_except_table1269
+ GCC_except_table1273
+ GCC_except_table1281
+ GCC_except_table1282
+ GCC_except_table1285
+ GCC_except_table1290
+ GCC_except_table1293
+ GCC_except_table1302
+ GCC_except_table1307
+ GCC_except_table1319
+ GCC_except_table1323
+ GCC_except_table1326
+ GCC_except_table1329
+ GCC_except_table1332
+ GCC_except_table1339
+ GCC_except_table1346
+ GCC_except_table1354
+ GCC_except_table1357
+ GCC_except_table137
+ GCC_except_table138
+ GCC_except_table1430
+ GCC_except_table1433
+ GCC_except_table232
+ GCC_except_table350
+ GCC_except_table391
+ GCC_except_table411
+ GCC_except_table423
+ GCC_except_table447
+ GCC_except_table468
+ GCC_except_table479
+ GCC_except_table482
+ GCC_except_table506
+ GCC_except_table526
+ GCC_except_table529
+ GCC_except_table570
+ GCC_except_table572
+ GCC_except_table575
+ GCC_except_table577
+ GCC_except_table579
+ GCC_except_table588
+ GCC_except_table618
+ GCC_except_table622
+ GCC_except_table650
+ GCC_except_table658
+ GCC_except_table692
+ GCC_except_table695
+ GCC_except_table704
+ GCC_except_table712
+ GCC_except_table745
+ GCC_except_table755
+ GCC_except_table757
+ GCC_except_table772
+ GCC_except_table779
+ GCC_except_table787
+ GCC_except_table803
+ GCC_except_table815
+ GCC_except_table827
+ GCC_except_table845
+ GCC_except_table857
+ GCC_except_table858
+ GCC_except_table862
+ GCC_except_table865
+ GCC_except_table866
+ GCC_except_table880
+ GCC_except_table883
+ GCC_except_table903
+ GCC_except_table908
+ GCC_except_table911
+ GCC_except_table912
+ GCC_except_table915
+ GCC_except_table916
+ GCC_except_table920
+ GCC_except_table922
+ GCC_except_table938
+ GCC_except_table939
+ GCC_except_table957
+ GCC_except_table960
+ GCC_except_table965
+ GCC_except_table973
+ GCC_except_table975
+ GCC_except_table976
+ GCC_except_table985
+ _OBJC_CLASS_$_PKPassLibrary
+ _OBJC_CLASS_$_WBSUsageRetentionDonationManager
+ _OBJC_CLASS_$_WBSWellKnownChangePasswordURLFallbackController
+ _OBJC_IVAR_$_CompletionListTableViewCell._shouldApplyBlendMode
+ _OBJC_IVAR_$_CompletionListTableViewDataSource._isHostedAsPopover
+ _OBJC_IVAR_$_StartPageController._startPageSessionQueryID
+ _OBJC_IVAR_$_TabDocument._wellKnownChangePasswordURLFallbackController
+ _OUTLINED_FUNCTION_120
+ _WBSParsecDomainSafariStartPageFavorites
+ _WBSParsecDomainSafariStartPageICloud
+ _WBSParsecDomainSafariStartPageRecentSearches
+ _WBSParsecDomainSafariStartPageRecentlyClosedTabs
+ _WBSParsecDomainSafariStartPageSuggestions
+ __OBJC_$_PROP_LIST_CompletionListTableViewCell
+ __SFBookmarkFeatureTextBackfillCompletedForAltDSIDKey
+ __ZL27_SFSearchResultForStartPageP8NSStringS0_P5NSURLS0_
+ __ZZ61-[StartPageController _emitEnabledSectionsForSessionQueryID:]E17sectionToBundleID
+ __ZZ61-[StartPageController _emitEnabledSectionsForSessionQueryID:]E9onceToken
+ ___112-[ApplicationShortcutController _openNewEmptyTabWithURLFieldFocused:privateBrowsingState:showingRecentSearches:]_block_invoke
+ ___112-[ApplicationShortcutController _openNewEmptyTabWithURLFieldFocused:privateBrowsingState:showingRecentSearches:]_block_invoke_2
+ ___116+[WBSParsecDSession(FeedbackHelpers) sendLaunchFeedbackWithEvent:isPrivate:usesLoweredSearchBar:isStartPageVisible:]_block_invoke
+ ___129-[BrowserController magicExtensionsController:didFinishRefiningExtension:name:icon:shouldReloadPage:shouldPromptAboutNewTabPage:]_block_invoke
+ ___41-[Application _reportLaunchAnalyticsSoon]_block_invoke_3
+ ___48-[CompletionListTableViewController viewDidLoad]_block_invoke
+ ___60-[CatalogViewController initWithDelegate:browserController:]_block_invoke_6
+ ___61-[StartPageController _emitEnabledSectionsForSessionQueryID:]_block_invoke
+ ___63-[TabController sortTabsInTabGroupWithUUIDString:withSortMode:]_block_invoke_3
+ ___83-[TabDocument _loadURLInternal:userDriven:eventAttribution:skipSyncableTabUpdates:]_block_invoke
+ ___86-[ReadingListMetadataFetcher _saveBackfilledFeatureText:fetchError:forBookmarkWithID:]_block_invoke
+ ___block_descriptor_105_e8_32s40s48s56s64s72s80s88s96s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8
+ ___block_descriptor_40_e8_32s_e12_"NSSet"8?0ls32l8
+ ___block_descriptor_40_e8_32w_e5_B8?0lw32l8
+ ___block_descriptor_48_e8_32s_e27_v16?0"WBMutableTabGroup"8ls32l8
+ ___block_descriptor_50_e5_v8?0l
+ ___block_descriptor_50_ea8_32s40w_e15_v16?0"NSURL"8lw40l8s32l8
+ ___block_descriptor_51_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48s_e84_v60?0B8"NSString"12"NSString"20"NSString"28"NSString"36"NSData"44"NSString"52ls32l8s40l8s48l8
+ ___block_descriptor_81_e8_32s40s48s56bs64r72r_e31_v24?0"NSString"8"NSString"16lr64l8s32l8s40l8s48l8r72l8s56l8
+ ___swift_closure_destructor.137Tm
+ ___swift_closure_destructor.160Tm
+ ___swift_closure_destructor.22Tm
+ ___swift_closure_destructor.26Tm
+ ___swift_closure_destructor.33Tm
+ _countLeafBookmarksOutsideReadingList
+ _keypath_get_selector_searchBarShouldResignFirstResponderHandler
+ _swift_deallocPartialClassInstance
+ _symbolic SS______t 10Foundation4UUIDV
+ _symbolic So32StartPageSegmentedViewControllerCSgXw
+ _symbolic _____ySS_____G s18_DictionaryStorageC 10Foundation4UUIDV
+ _symbolic _____ySS______tG s23_ContiguousArrayStorageC 10Foundation4UUIDV
+ _symbolic ytIegr_
- +[CompletionGroupListing shouldMoveSuggestionFromSearchProvider:toTopOfSectionForUserTypedQuery:]
- +[WBSParsecDSession sendLaunchFeedbackWithEvent:isPrivate:usesLoweredSearchBar:]
- -[BrowserController magicExtensionsController:didFinishRefiningExtension:name:icon:webView:shouldPromptAboutNewTabPage:]
- -[ReadingListMetadataFetcher _saveBackfilledFeatureText:forBookmarkWithID:]
- -[WBSPageTestController(WBSBulkIntelligenceInferenceControllerDelegate) automaticPasswordChangeController:canAutoFillNewPasswordOnPageWithCompletionHandler:]
- GCC_except_table1017
- GCC_except_table1023
- GCC_except_table1028
- GCC_except_table1029
- GCC_except_table1036
- GCC_except_table1037
- GCC_except_table1042
- GCC_except_table1045
- GCC_except_table1050
- GCC_except_table1051
- GCC_except_table1064
- GCC_except_table1071
- GCC_except_table1096
- GCC_except_table1105
- GCC_except_table1112
- GCC_except_table1118
- GCC_except_table1122
- GCC_except_table1123
- GCC_except_table1127
- GCC_except_table113
- GCC_except_table1135
- GCC_except_table1136
- GCC_except_table1141
- GCC_except_table1145
- GCC_except_table1148
- GCC_except_table1151
- GCC_except_table1157
- GCC_except_table1175
- GCC_except_table1182
- GCC_except_table1186
- GCC_except_table1190
- GCC_except_table1194
- GCC_except_table1205
- GCC_except_table1213
- GCC_except_table1220
- GCC_except_table1225
- GCC_except_table1228
- GCC_except_table1240
- GCC_except_table1241
- GCC_except_table1246
- GCC_except_table1249
- GCC_except_table1252
- GCC_except_table1263
- GCC_except_table1266
- GCC_except_table1267
- GCC_except_table1271
- GCC_except_table1275
- GCC_except_table1283
- GCC_except_table1284
- GCC_except_table1291
- GCC_except_table1294
- GCC_except_table1295
- GCC_except_table1304
- GCC_except_table1309
- GCC_except_table1321
- GCC_except_table1327
- GCC_except_table1330
- GCC_except_table1334
- GCC_except_table1335
- GCC_except_table1341
- GCC_except_table1348
- GCC_except_table141
- GCC_except_table1428
- GCC_except_table1431
- GCC_except_table195
- GCC_except_table251
- GCC_except_table352
- GCC_except_table359
- GCC_except_table412
- GCC_except_table425
- GCC_except_table448
- GCC_except_table469
- GCC_except_table480
- GCC_except_table483
- GCC_except_table507
- GCC_except_table527
- GCC_except_table530
- GCC_except_table571
- GCC_except_table574
- GCC_except_table576
- GCC_except_table578
- GCC_except_table580
- GCC_except_table589
- GCC_except_table620
- GCC_except_table623
- GCC_except_table651
- GCC_except_table659
- GCC_except_table694
- GCC_except_table696
- GCC_except_table707
- GCC_except_table713
- GCC_except_table746
- GCC_except_table756
- GCC_except_table758
- GCC_except_table773
- GCC_except_table780
- GCC_except_table788
- GCC_except_table804
- GCC_except_table813
- GCC_except_table823
- GCC_except_table831
- GCC_except_table846
- GCC_except_table854
- GCC_except_table859
- GCC_except_table867
- GCC_except_table868
- GCC_except_table914
- GCC_except_table918
- GCC_except_table925
- GCC_except_table944
- GCC_except_table945
- GCC_except_table948
- GCC_except_table958
- GCC_except_table961
- GCC_except_table977
- GCC_except_table980
- _WBUHistoryDefaultItemAgeLimit
- __OBJC_$_CLASS_METHODS_CompletionGroupListing
- __SFHasCompletedBookmarkFeatureTextBackfillKey
- __ZL23audit_stringPassKitCore
- __ZZL21getPKPassLibraryClassvE9softClass
- __ZZL22PassKitCoreLibraryCorePPcE16frameworkLibrary
- ___120-[BrowserController magicExtensionsController:didFinishRefiningExtension:name:icon:webView:shouldPromptAboutNewTabPage:]_block_invoke
- ___75-[ReadingListMetadataFetcher _saveBackfilledFeatureText:forBookmarkWithID:]_block_invoke
- ___90-[ApplicationShortcutController _openNewEmptyTabWithURLFieldFocused:privateBrowsingState:]_block_invoke
- ___90-[ApplicationShortcutController _openNewEmptyTabWithURLFieldFocused:privateBrowsingState:]_block_invoke_2
- ___95-[BrowserRootViewController bannerController:didSetNotifyMeWhenBanner:previousBanner:animated:]_block_invoke
- ___97+[WBSParsecDSession(FeedbackHelpers) sendLaunchFeedbackWithEvent:isPrivate:usesLoweredSearchBar:]_block_invoke
- ____ZL21getPKPassLibraryClassv_block_invoke
- ____ZL22PassKitCoreLibraryCorePPc_block_invoke
- ___block_descriptor_40_e27_v16?0"WBMutableTabGroup"8l
- ___block_descriptor_48_e8_32s40s_e71_v52?0B8"NSString"12"NSString"20"NSString"28"NSString"36"NSData"44ls32l8s40l8
- ___block_descriptor_49_e5_v8?0l
- ___block_descriptor_50_e8_32s40s_e5_v8?0ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48s_e71_v52?0B8"NSString"12"NSString"20"NSString"28"NSString"36"NSData"44ls32l8s40l8s48l8
- ___block_descriptor_81_e8_32s40s48bs56r64r72r_e31_v24?0"NSString"8"NSString"16lr56l8r64l8s32l8s40l8r72l8s48l8
- ___block_descriptor_97_e8_32s40s48s56s64s72s80s88s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8
- ___swift_closure_destructor.158Tm
- ___swift_closure_destructor.24Tm
- ___swift_closure_destructor.36Tm
- _swift_willThrowTypedImpl
CStrings:
+ "%lld"
+ "Clear All (Recent Searches)"
+ "Duplicate values for key: '"
+ "Failed to create cluster item: tab has no UUID"
+ "Skipping featureText backfill: already completed for current account"
+ "Swift/NativeDictionary.swift"
+ "bundleIdentifier"
+ "comgoogleapp"
+ "googlechrome"
+ "intent"
+ "scheme=googlechrome"
+ "v60@?0B8@\"NSString\"12@\"NSString\"20@\"NSString\"28@\"NSString\"36@\"NSData\"44@\"NSString\"52"
+ "\xf0\xf0\xf0a"
- "Clear (Recent Searches)"
- "PKPassLibrary"
- "Skipping featureText backfill: already completed in a previous session"
- "softlink:r:path:/System/Library/PrivateFrameworks/PassKitCore.framework/PassKitCore"
- "v52@?0B8@\"NSString\"12@\"NSString\"20@\"NSString\"28@\"NSString\"36@\"NSData\"44"
- "\xf0\xf0\xf0Q"
```
