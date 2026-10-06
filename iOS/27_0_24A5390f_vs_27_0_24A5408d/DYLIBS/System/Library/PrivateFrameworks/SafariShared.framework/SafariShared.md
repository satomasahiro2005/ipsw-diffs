## SafariShared

> `/System/Library/PrivateFrameworks/SafariShared.framework/SafariShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a6a40` | `0x2a8e40` | **`+0x2400`** |
| `__TEXT.__const` | `0x9a814` | `0x9afa4` | **`+0x790`** |
| `__TEXT.__oslogstring` | `0x15642` | `0x158e2` | **`+0x2a0`** |
| `__AUTH_CONST.__objc_const` | `0x284a8` | `0x285e8` | **`+0x140`** |
| `__AUTH_CONST.__const` | `0xa860` | `0xa7b0` | **`-0xb0`** |
| `__TEXT.__objc_methlist` | `0x15f6c` | `0x15fe4` | **`+0x78`** |
| `__TEXT.__eh_frame` | `0x53d0` | `0x5428` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x1ea40` | `0x1ea80` | **`+0x40`** |
| `__DATA.__data` | `0x5708` | `0x5738` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x16520` | `0x16550` | **`+0x30`** |
| `__TEXT.__cstring` | `0x23607` | `0x23637` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xedd8` | `0xee08` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1b0a0` | `0x1b080` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x2104` | `0x2124` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xc30` | `0xc10` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x1920` | `0x1938` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x3650` | `0x3666` | **`+0x16`** |
| `__AUTH_CONST.__auth_got` | `0x2bc8` | `0x2bd8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x14a8` | `0x14b8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1700` | `0x170c` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x2000` | `0x2008` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xc060` | `0xc068` | **`+0x8`** |

### Other Changes

```diff

-625.1.24.10.1
+625.1.29.10.3

-  Functions: 14553
-  Symbols:   19299
-  CStrings:  6125
+  Functions: 14561
+  Symbols:   19320
+  CStrings:  6134
Symbols:
+ +[WBSPasswordBreachNotificationManager _passwordManagerURLForSavedAccount:containsHighPriorityAccount:]
+ +[WBSPasswordBreachNotificationManager highLevelDomain:isIncludedInTopFraudTargets:]
+ -[WBSAutoFillValuesResult oneTimeCodeAppearsToHaveBeenFilledInItsEntirety]
+ -[WBSAutoFillValuesResult setOneTimeCodeAppearsToHaveBeenFilledInItsEntirety:]
+ -[WBSBrowserTabCompletionProvider _compareTabMatch:otherTabMatch:usingSelectedTabInfo:]
+ -[WBSBrowserTabCompletionProvider _distanceFromSelectedTabForTabMatch:usingSelectedTabInfo:]
+ -[WBSClusteringCalibration _calibrationDataForLanguage:]
+ -[WBSClusteringCalibration _processCalibrationData:referenceLanguage:]
+ -[WBSClusteringCalibration _registerForOverrideObservation]
+ -[WBSClusteringCalibration _resolveModelVersionForLanguage:]
+ -[WBSClusteringCalibration _version:excludesLanguage:]
+ -[WBSClusteringCalibration defaultMaximumDistanceForLanguage:]
+ -[WBSClusteringCalibration modelVersionForLanguage:]
+ -[WBSDevice(ScreenTime) getIsScreenTimeBlockingURL:completionHandler:]
+ -[WBSEmbeddingStore embedFeatureText:forURL:inProfileIdentifier:language:lastVisitTime:completionHandler:]
+ -[WBSFormMetadata typeConfidence]
+ -[WBSPageContext isCJK]
+ -[WBSSiriIntelligenceDonor _coreSpotlightItemsSubarrays:batchSize:]
+ -[WBSTrialSearchParameters shouldPromoteRecentSearchesStartPageModuleBelowFavorites]
+ GCC_except_table188
+ GCC_except_table193
+ GCC_except_table237
+ GCC_except_table243
+ GCC_except_table250
+ GCC_except_table280
+ GCC_except_table287
+ GCC_except_table296
+ GCC_except_table297
+ GCC_except_table308
+ GCC_except_table311
+ GCC_except_table322
+ _OBJC_IVAR_$_WBSAutoFillValuesResult._oneTimeCodeAppearsToHaveBeenFilledInItsEntirety
+ _OBJC_IVAR_$_WBSClusteringCalibration._defaultMaximumDistance
+ _OBJC_IVAR_$_WBSClusteringCalibration._overrideObservation
+ _OBJC_IVAR_$_WBSClusteringCalibration._referenceLanguage
+ _OBJC_IVAR_$_WBSClusteringCalibration._resolvedVersionCache
+ _OBJC_IVAR_$_WBSFormMetadata._typeConfidence
+ _OBJC_IVAR_$_WBSTrialSearchParameters._shouldPromoteRecentSearchesStartPageModuleBelowFavorites
+ _TRIAL_shouldPromoteRecentSearchesStartPageModuleBelowFavorites
+ _WBSEverLaunchedOnPreRaveOSVersionPreferenceKey
+ _WBSFormMetadataAutoFillFormTypeConfidenceKey
+ _WBSOSLogScreenTime
+ _WBSParsecDomainSafariDouyinCompletion
+ _WBSParsecDomainSafariDouyinSearch
+ _WBSPasswordManagerURLContainsHighPriorityAccountKey
+ _WBSPasswordManagerURLIsForBreachNotificationKey
+ _WBSStartPageSectionTrialRecentSearches
+ _WBSTabClusteringPolicyKey
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_WBSDevice_$_ScreenTime
+ __OBJC_$_CATEGORY_WBSDevice_$_ScreenTime
+ ___106-[WBSEmbeddingStore embedFeatureText:forURL:inProfileIdentifier:language:lastVisitTime:completionHandler:]_block_invoke
+ ___106-[WBSEmbeddingStore embedFeatureText:forURL:inProfileIdentifier:language:lastVisitTime:completionHandler:]_block_invoke_2
+ ___106-[WBSEmbeddingStore embedFeatureText:forURL:inProfileIdentifier:language:lastVisitTime:completionHandler:]_block_invoke_3
+ ___106-[WBSEmbeddingStore embedFeatureText:forURL:inProfileIdentifier:language:lastVisitTime:completionHandler:]_block_invoke_4
+ ___59-[WBSClusteringCalibration _registerForOverrideObservation]_block_invoke
+ ___70-[WBSDevice(ScreenTime) getIsScreenTimeBlockingURL:completionHandler:]_block_invoke
+ ___82-[WBSPasswordBreachNotificationManager _contentWithSavedAccounts:topFraudTargets:]_block_invoke
+ ___block_descriptor_40_e8_32s_e25_B16?0"WBSSavedAccount"8ls32l8
+ ___block_descriptor_48_ea8_32s40s_e71_q24?0"WBSBrowserTabCompletionMatch"8"WBSBrowserTabCompletionMatch"16ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8s48l8s40l8
+ ___block_descriptor_88_ea8_32s40s48s56s64s72bs_e17_v16?0"NSArray"8ls72l8s32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_88_ea8_32s40s48s56s64s72bs_e22_v16?0"WBSEmbedding"8ls32l8s72l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_88_ea8_32s40s48s56s64s72bs_e5_v8?0ls32l8s40l8s48l8s72l8s56l8s64l8
+ ___swift_closure_destructor.178Tm
+ _isCJKLanguage
+ _symbolic SDyS2SSgG
+ _symbolic _____yS2SSgG s18_DictionaryStorageC
+ _symbolic _____ySsG s23_ContiguousArrayStorageC
- +[WBSPasswordBreachNotificationManager _highLevelDomain:isIncludedInTopFraudTargets:]
- -[WBSAnalyticsLogger(WBSAnalyticsLoggerExtras) reportNumberOfFlaggedPasswordsUsingSavedAccountAuditorIfNeeded:]
- -[WBSBrowserTabCompletionProvider _compareTabMatch:otherTabMatch:]
- -[WBSBrowserTabCompletionProvider _distanceFromSelectedTabForTabMatch:]
- -[WBSClusteringCalibration _processCalibrationData:]
- -[WBSClusteringCalibration referenceLanguage]
- -[WBSClusteringCalibration referenceMean]
- -[WBSClusteringCalibration referenceStandardDeviation]
- -[WBSEmbeddingStore embedFeatureText:forURL:inProfileIdentifier:lastVisitTime:completionHandler:]
- -[WBSPageContext setPageLanguage:]
- -[WBSPasswordBreachNotificationManager _passwordManagerURLForSavedAccount:]
- -[WBSStartPageSectionManager _sectionsWithRecentSearchesModule:favoritesIndex:recentSearchesIndex:]
- -[WBSTrialSearchParameters shouldPromoteRecentSearchesStartPageModuleBellowFavorites]
- GCC_except_table196
- GCC_except_table197
- GCC_except_table239
- GCC_except_table258
- GCC_except_table259
- GCC_except_table291
- GCC_except_table303
- GCC_except_table304
- GCC_except_table310
- GCC_except_table313
- _OBJC_CLASS_$_WBSPasswordEvaluator
- _OBJC_IVAR_$_WBSTrialSearchParameters._shouldPromoteRecentSearchesStartPageModuleBellowFavorites
- _TRIAL_shouldPromoteRecentSearchesStartPageModuleBellowFavorites
- _WBSAutoTabClusteringEnabledKey
- _WBSAutoTabClusteringImmediateModeEnabledKey
- _WBSAutoTabClusteringImmediateModeMigratedKey
- _WBSStartPageSectionRecentSearches
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WBSAnalyticsLogger_$_WBSAnalyticsLoggerExtras
- __OBJC_$_CATEGORY_WBSAnalyticsLogger_$_WBSAnalyticsLoggerExtras
- ___111-[WBSAnalyticsLogger(WBSAnalyticsLoggerExtras) reportNumberOfFlaggedPasswordsUsingSavedAccountAuditorIfNeeded:]_block_invoke
- ___53-[WBSStartPageSectionManager readAndValidateSections]_block_invoke_3
- ___53-[WBSStartPageSectionManager readAndValidateSections]_block_invoke_4
- ___53-[WBSStartPageSectionManager readAndValidateSections]_block_invoke_5
- ___97-[WBSEmbeddingStore embedFeatureText:forURL:inProfileIdentifier:lastVisitTime:completionHandler:]_block_invoke
- ___97-[WBSEmbeddingStore embedFeatureText:forURL:inProfileIdentifier:lastVisitTime:completionHandler:]_block_invoke_2
- ___97-[WBSEmbeddingStore embedFeatureText:forURL:inProfileIdentifier:lastVisitTime:completionHandler:]_block_invoke_3
- ___97-[WBSEmbeddingStore embedFeatureText:forURL:inProfileIdentifier:lastVisitTime:completionHandler:]_block_invoke_4
- ___block_descriptor_32_e46_B32?0"WBSStartPageSectionDescriptor"8Q16^B24l
- ___block_descriptor_40_ea8_32s_e71_q24?0"WBSBrowserTabCompletionMatch"8"WBSBrowserTabCompletionMatch"16ls32l8
- ___block_descriptor_80_ea8_32s40s48s56s64bs_e17_v16?0"NSArray"8ls64l8s32l8s40l8s48l8s56l8
- ___block_descriptor_80_ea8_32s40s48s56s64bs_e22_v16?0"WBSEmbedding"8ls32l8s64l8s40l8s48l8s56l8
- ___block_descriptor_80_ea8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s64l8s56l8
- ___swift_closure_destructor.180Tm
- _symbolic So12NSDictionaryCSgIeyBy_
CStrings:
+ "8625.1.29.10.3"
+ "Agent (%{public}s) has no instructions available for model %{public}s."
+ "AutoFillFormTypeConfidence"
+ "AutoTabClusteringEnabled"
+ "Coalescing duplicate search-engagement donation: previous donation was %{public}ldms ago, within the %{public}ldms coalescing window."
+ "Ejecting over-merged outlier tab from cluster"
+ "EverLaunchedOnPreRaveOSVersion"
+ "Failed to enable WAL mode for magic extensions database: %s"
+ "Failed to query Screen Time policy; treating URL as allowed: %{public}@"
+ "Ignoring bookmark change caused by our own topic write-back"
+ "Ignoring bookmark metadata change caused by our own topic write-back"
+ "No instructions available for model "
+ "No non-excluding calibrated version found for language %{public}@, falling back to default version %lu despite exclusion"
+ "douyin_comp"
+ "douyin_search"
+ "excludedLanguages"
+ "trialRecentSearchesIdentifier"
- "8625.1.24.10.1"
- "com.apple.Safari.WeakPasswordReport"
- "numberOfFlaggedPasswords"
- "percentageOfFlaggedPasswords"
- "recentSearchesIdentifier"
- "referenceMean"
- "referenceStandardDeviation"
- "totalNumberOfPasswords"
```
