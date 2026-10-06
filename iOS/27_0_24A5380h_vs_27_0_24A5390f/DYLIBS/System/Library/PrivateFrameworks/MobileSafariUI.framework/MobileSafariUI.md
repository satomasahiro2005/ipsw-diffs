## MobileSafariUI

> `/System/Library/PrivateFrameworks/MobileSafariUI.framework/MobileSafariUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d7dc4` | `0x2da14c` | **`+0x2388`** |
| `__DATA.__bss` | `0x30c0` | `0x33c0` | **`+0x300`** |
| `__TEXT.__oslogstring` | `0xab4f` | `0xadef` | **`+0x2a0`** |
| `__TEXT.__gcc_except_tab` | `0x1f1c0` | `0x1f3dc` | **`+0x21c`** |
| `__AUTH_CONST.__objc_const` | `0x32c58` | `0x32e70` | **`+0x218`** |
| `__TEXT.__const` | `0x43b0` | `0x4550` | **`+0x1a0`** |
| `__TEXT.__objc_methlist` | `0x24a5c` | `0x24bb4` | **`+0x158`** |
| `__DATA_CONST.__objc_selrefs` | `0x18498` | `0x185a8` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0xfb48` | `0xfc38` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x106a4` | `0x10714` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0x80f8` | `0x8160` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x97f8` | `0x9850` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x30f0` | `0x3140` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x5dd9` | `0x5e23` | **`+0x4a`** |
| `__DATA.__data` | `0x9898` | `0x98d8` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x12c0` | `0x12f0` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x4c8` | `0x4f8` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x1c84` | `0x1cb0` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x3678` | `0x36a0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xdd40` | `0xdd60` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x20a4` | `0x20c4` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xd78` | `0xd94` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0x1b0` | `0x1c8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x1b8` | `0x1cc` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x9e8` | `0x9f0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x688` | `0x690` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x130` | `0x134` | **`+0x4`** |

### Other Changes

```diff

-625.1.22.10.3
+625.1.24.10.1

-  Functions: 15847
-  Symbols:   22791
-  CStrings:  3245
+  Functions: 15889
+  Symbols:   22844
+  CStrings:  3254
Symbols:
+ -[BookmarkImporter _getBookmarksDataclassEnabledWithCompletionHandler:]
+ -[BookmarkImporter _importBuiltinBookmarksIfNeeded]
+ -[BookmarkImporter _scheduleBuiltinBookmarkImportAfterMigrationFinishes]
+ -[BrowserController _notifyMeWhenAutomationDeletedFromSettings:]
+ -[BrowserController linkPreviewProviderShouldPresentOpenInBackgroundAsOpenToSide]
+ -[BrowserController usesPopoverForCompletions]
+ -[CompletionList _checkForUnsupportedAutoCompletedGoogleSuggestionsKeyboardInputModes]
+ -[CompletionListPlatteredIconView .cxx_destruct]
+ -[CompletionListPlatteredIconView initWithFrame:]
+ -[CompletionListPlatteredIconView isHighlighted]
+ -[CompletionListPlatteredIconView layoutSubviews]
+ -[CompletionListPlatteredIconView setIsHighlighted:]
+ -[CompletionListPlatteredIconView setSymbolName:]
+ -[CompletionListPlatteredIconView setSymbolOffset:]
+ -[CompletionListPlatteredIconView symbolName]
+ -[CompletionListPlatteredIconView symbolOffset]
+ -[CompletionListTableViewCell setSymbolOffset:]
+ -[StartPageController _enabledSectionIdentifiersUsingTrialState]
+ -[StartPageController _reloadRecentSearchesSection]
+ -[StartPageController shouldPresentOpenInBackgroundAsOpenToSide]
+ -[TabDocument _callDidFinishNavigationHandlersForNavigation:error:]
+ -[TabDocument addDidFinishNavigationHandler:]
+ -[TabDocument pageContextDataFetcherGetPageContext:]
+ -[TabDocument readerController:didRequestSummaryFeedbackWithActionType:readerTextUsedForSummarization:]
+ -[TabDocument setWasOpenedInBackground:]
+ -[TabDocument shouldPresentOpenInBackgroundAsOpenToSideForLinkPreviewHelper:]
+ -[TabDocument wasOpenedInBackground]
+ -[TabGroupLibraryItemController _pinnedTabs]
+ -[TabSwitcherViewController _indexToDropDragItems:atEndOfSection:]
+ GCC_except_table1010
+ GCC_except_table1017
+ GCC_except_table1023
+ GCC_except_table1028
+ GCC_except_table1029
+ GCC_except_table1032
+ GCC_except_table1035
+ GCC_except_table1042
+ GCC_except_table1045
+ GCC_except_table1050
+ GCC_except_table1051
+ GCC_except_table1064
+ GCC_except_table1069
+ GCC_except_table1096
+ GCC_except_table1105
+ GCC_except_table1112
+ GCC_except_table1116
+ GCC_except_table1122
+ GCC_except_table1123
+ GCC_except_table1127
+ GCC_except_table1133
+ GCC_except_table1134
+ GCC_except_table1141
+ GCC_except_table1144
+ GCC_except_table1145
+ GCC_except_table1151
+ GCC_except_table1157
+ GCC_except_table1173
+ GCC_except_table1180
+ GCC_except_table1186
+ GCC_except_table1190
+ GCC_except_table1194
+ GCC_except_table1203
+ GCC_except_table1211
+ GCC_except_table1220
+ GCC_except_table1224
+ GCC_except_table1225
+ GCC_except_table1240
+ GCC_except_table1241
+ GCC_except_table1245
+ GCC_except_table1246
+ GCC_except_table1252
+ GCC_except_table1263
+ GCC_except_table1264
+ GCC_except_table1267
+ GCC_except_table1271
+ GCC_except_table1275
+ GCC_except_table1283
+ GCC_except_table1284
+ GCC_except_table1287
+ GCC_except_table1292
+ GCC_except_table1295
+ GCC_except_table1304
+ GCC_except_table1309
+ GCC_except_table1321
+ GCC_except_table1325
+ GCC_except_table1328
+ GCC_except_table1331
+ GCC_except_table1334
+ GCC_except_table1341
+ GCC_except_table1348
+ GCC_except_table1356
+ GCC_except_table1359
+ GCC_except_table1432
+ GCC_except_table1435
+ GCC_except_table352
+ GCC_except_table359
+ GCC_except_table424
+ GCC_except_table448
+ GCC_except_table469
+ GCC_except_table480
+ GCC_except_table527
+ GCC_except_table530
+ GCC_except_table571
+ GCC_except_table573
+ GCC_except_table576
+ GCC_except_table578
+ GCC_except_table580
+ GCC_except_table589
+ GCC_except_table619
+ GCC_except_table620
+ GCC_except_table623
+ GCC_except_table651
+ GCC_except_table659
+ GCC_except_table693
+ GCC_except_table694
+ GCC_except_table696
+ GCC_except_table705
+ GCC_except_table706
+ GCC_except_table713
+ GCC_except_table746
+ GCC_except_table756
+ GCC_except_table758
+ GCC_except_table773
+ GCC_except_table780
+ GCC_except_table788
+ GCC_except_table804
+ GCC_except_table813
+ GCC_except_table823
+ GCC_except_table829
+ GCC_except_table831
+ GCC_except_table846
+ GCC_except_table854
+ GCC_except_table859
+ GCC_except_table867
+ GCC_except_table868
+ GCC_except_table913
+ GCC_except_table914
+ GCC_except_table918
+ GCC_except_table923
+ GCC_except_table940
+ GCC_except_table941
+ GCC_except_table942
+ GCC_except_table948
+ GCC_except_table958
+ GCC_except_table959
+ GCC_except_table961
+ GCC_except_table977
+ _NSPOSIXErrorDomain
+ _OBJC_CLASS_$_CompletionListPlatteredIconView
+ _OBJC_CLASS_$_SFOnDemandSummarizationFeedbackController
+ _OBJC_CLASS_$_UINavigationBarAppearance
+ _OBJC_IVAR_$_BookmarkImporter._migrationStateObserver
+ _OBJC_IVAR_$_CompletionList._firstAutocompletedGoogleSuggestionDuringSession
+ _OBJC_IVAR_$_CompletionList._usedUnsupportedAutoCompletedGoogleSuggestionsKeyboardInputModeDuringSession
+ _OBJC_IVAR_$_CompletionListPlatteredIconView._isHighlighted
+ _OBJC_IVAR_$_CompletionListPlatteredIconView._platterView
+ _OBJC_IVAR_$_CompletionListPlatteredIconView._symbolName
+ _OBJC_IVAR_$_CompletionListPlatteredIconView._symbolOffset
+ _OBJC_IVAR_$_CompletionListPlatteredIconView._symbolView
+ _OBJC_IVAR_$_CompletionListTableViewCell._platteredIconView
+ _OBJC_IVAR_$_ReadingListMetadataFetcher._hasSkippedEmptySummaryDuringBackfill
+ _OBJC_IVAR_$_TabDocument._didFinishNavigationHandlers
+ _OBJC_IVAR_$_TabDocument._wasOpenedInBackground
+ _OBJC_METACLASS_$_CompletionListPlatteredIconView
+ _SFReloadRecentSearchesSectionNotification
+ _WBSAutomaticPasswordChangeUsesElementActionClassifierKey
+ _WBSPageContextFetchOperationErrorDomain
+ _WBSWebExtensionDidChangeEnabledStateInPrivateBrowsingNotification
+ __OBJC_$_INSTANCE_METHODS_CompletionListPlatteredIconView
+ __OBJC_$_INSTANCE_VARIABLES_CompletionListPlatteredIconView
+ __OBJC_$_PROP_LIST_CompletionListPlatteredIconView
+ __OBJC_CLASS_RO_$_CompletionListPlatteredIconView
+ __OBJC_METACLASS_RO_$_CompletionListPlatteredIconView
+ ___40-[TabDocument _setReaderArticleSummary:]_block_invoke
+ ___52-[TabSwitcherViewController _performDropWithIntent:]_block_invoke_2
+ ___66-[TabSwitcherViewController _indexToDropDragItems:atEndOfSection:]_block_invoke
+ ___66-[TabSwitcherViewController _indexToDropDragItems:atEndOfSection:]_block_invoke_2
+ ___71-[BookmarkImporter _getBookmarksDataclassEnabledWithCompletionHandler:]_block_invoke
+ ___71-[BookmarkImporter _getBookmarksDataclassEnabledWithCompletionHandler:]_block_invoke_2
+ ___72-[BookmarkImporter _scheduleBuiltinBookmarkImportAfterMigrationFinishes]_block_invoke
+ ___block_descriptor_40_e8_32s_e27_B16?0"SFTabSwitcherItem"8ls32l8
+ ___block_descriptor_40_ea8_32s_e24_v16?0"NSNotification"8ls32l8
+ ___block_descriptor_56_e8_32s40bs48r_e17_v16?0"NSError"8ls32l8r48l8s40l8
+ ___block_descriptor_56_e8_32s40bs48r_e34_v24?0"WKNavigation"8"NSError"16ls32l8r48l8s40l8
+ ___block_descriptor_64_ea8_32s40s48s56r_e8_v12?0B8ls32l8s40l8s48l8r56l8
+ _associated conformance So21NSAttributedStringKeyaSHSCSQ
+ _associated conformance So21NSAttributedStringKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So21NSAttributedStringKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _symbolic _____ So21NSAttributedStringKeya
+ _symbolic ______ypt So21NSAttributedStringKeya
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC So21NSAttributedStringKeya
+ _symbolic _____y_____ypG s18_DictionaryStorageC So21NSAttributedStringKeya
- -[BrowserController linkPreviewProviderShouldHideOpenInBackgroundAction]
- -[CompletionListTableViewCell setShouldApplyBlendMode:]
- -[CompletionListTableViewCell shouldApplyBlendMode]
- -[CompletionListTableViewDataSource isHostedAsPopover]
- -[CompletionListTableViewDataSource setIsHostedAsPopover:]
- -[StartPageController shouldHideOpenInBackgroundAction]
- -[TabDocument shouldHideOpenInBackgroundActionForLinkPreviewHelper:]
- GCC_except_table1014
- GCC_except_table1019
- GCC_except_table1030
- GCC_except_table1031
- GCC_except_table1038
- GCC_except_table1039
- GCC_except_table1044
- GCC_except_table1047
- GCC_except_table1052
- GCC_except_table1053
- GCC_except_table1066
- GCC_except_table1073
- GCC_except_table1098
- GCC_except_table1107
- GCC_except_table1114
- GCC_except_table1120
- GCC_except_table1124
- GCC_except_table1125
- GCC_except_table1129
- GCC_except_table1137
- GCC_except_table1138
- GCC_except_table1143
- GCC_except_table1147
- GCC_except_table1150
- GCC_except_table1153
- GCC_except_table1159
- GCC_except_table1177
- GCC_except_table1184
- GCC_except_table1188
- GCC_except_table1192
- GCC_except_table1196
- GCC_except_table1207
- GCC_except_table1215
- GCC_except_table1219
- GCC_except_table1222
- GCC_except_table1227
- GCC_except_table1230
- GCC_except_table1242
- GCC_except_table1243
- GCC_except_table1248
- GCC_except_table1251
- GCC_except_table1254
- GCC_except_table1265
- GCC_except_table1268
- GCC_except_table1269
- GCC_except_table1273
- GCC_except_table1277
- GCC_except_table1285
- GCC_except_table1286
- GCC_except_table1293
- GCC_except_table1296
- GCC_except_table1297
- GCC_except_table1306
- GCC_except_table1311
- GCC_except_table1323
- GCC_except_table1329
- GCC_except_table1332
- GCC_except_table1336
- GCC_except_table1337
- GCC_except_table1343
- GCC_except_table1350
- GCC_except_table1430
- GCC_except_table1433
- GCC_except_table353
- GCC_except_table399
- GCC_except_table404
- GCC_except_table413
- GCC_except_table416
- GCC_except_table426
- GCC_except_table442
- GCC_except_table447
- GCC_except_table449
- GCC_except_table488
- GCC_except_table508
- GCC_except_table531
- GCC_except_table540
- GCC_except_table572
- GCC_except_table575
- GCC_except_table577
- GCC_except_table579
- GCC_except_table581
- GCC_except_table590
- GCC_except_table621
- GCC_except_table622
- GCC_except_table632
- GCC_except_table644
- GCC_except_table676
- GCC_except_table688
- GCC_except_table695
- GCC_except_table708
- GCC_except_table714
- GCC_except_table716
- GCC_except_table760
- GCC_except_table782
- GCC_except_table806
- GCC_except_table815
- GCC_except_table825
- GCC_except_table828
- GCC_except_table833
- GCC_except_table838
- GCC_except_table848
- GCC_except_table850
- GCC_except_table861
- GCC_except_table862
- GCC_except_table870
- GCC_except_table884
- GCC_except_table885
- GCC_except_table895
- GCC_except_table912
- GCC_except_table915
- GCC_except_table916
- GCC_except_table920
- GCC_except_table921
- GCC_except_table927
- GCC_except_table928
- GCC_except_table946
- GCC_except_table947
- GCC_except_table952
- GCC_except_table954
- GCC_except_table960
- GCC_except_table963
- GCC_except_table964
- GCC_except_table989
- _OBJC_CLASS_$_WBSCompletionListIconHostingController
- _OBJC_IVAR_$_CompletionListTableViewCell._completionIconHostingController
- _OBJC_IVAR_$_CompletionListTableViewCell._iconView
- _OBJC_IVAR_$_CompletionListTableViewCell._shouldApplyBlendMode
- _OBJC_IVAR_$_CompletionListTableViewDataSource._isHostedAsPopover
- ___48-[CompletionListTableViewController viewDidLoad]_block_invoke
- ___block_descriptor_40_e8_32w_e5_B8?0lw32l8
- ___block_descriptor_56_e8_32s40s48s_e19_"WKNavigation"8?0ls32l8s40l8s48l8
- ___block_descriptor_64_e8_32s40s48bs56r_e32_v16?0"PageLoadTestStatistics"8lr56l8s32l8s48l8s40l8
CStrings:
+ "B16@?0@\"SFTabSwitcherItem\"8"
+ "Deferring built-in bookmark import until CloudKit bookmark migration finishes"
+ "Deferring featureText backfill completion: some bookmarks returned empty summary, will retry next session"
+ "Detected bookmarks needing featureText backfill (partial sync or stuck state), resetting to retry"
+ "SFReloadRecentSearchesSectionNotification"
+ "bulkIntelligenceInferenceController:setupWindowWithTabURLs:allowingReadAccessTo:completionHandler: failed to load %@ with error: %@"
+ "bulkIntelligenceInferenceController:setupWindowWithTabURLs:allowingReadAccessTo:completionHandler: is ignoring about:blank URL and will continue to wait for successful navigation."
+ "bulkIntelligenceInferenceController:setupWindowWithTabURLs:allowingReadAccessTo:completionHandler: loaded %@"
+ "featureText request succeeded with empty summary for bookmark %d, will retry in a future session"
+ "v24@?0@\"WKNavigation\"8@\"NSError\"16"
- "bulkIntelligenceInferenceController:setupWindowWithTabURLs:allowingReadAccessTo:completionHandler: has loaded %@ with error: %@"
```
