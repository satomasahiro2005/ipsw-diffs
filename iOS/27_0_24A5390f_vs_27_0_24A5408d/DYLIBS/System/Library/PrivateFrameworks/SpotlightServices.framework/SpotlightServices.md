## SpotlightServices

> `/System/Library/PrivateFrameworks/SpotlightServices.framework/SpotlightServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15ff68` | `0x15f5e4` | **`-0x984`** |
| `__TEXT.__unwind_info` | `0x31f8` | `0x3438` | **`+0x240`** |
| `__TEXT.__oslogstring` | `0xbc3b` | `0xba3b` | **`-0x200`** |
| `__TEXT.__cstring` | `0x3aa1a` | `0x3a8aa` | **`-0x170`** |
| `__AUTH_CONST.__cfstring` | `0x36ca0` | `0x36be0` | **`-0xc0`** |
| `__AUTH_CONST.__const` | `0x2b80` | `0x2b20` | **`-0x60`** |
| `__DATA.__bss` | `0x618` | `0x5d8` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0xf70` | `0xf40` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x10100` | `0x100d8` | **`-0x28`** |
| `__TEXT.__const` | `0x2e18` | `0x2df8` | **`-0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x47a0` | `0x4788` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x5050` | `0x5068` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xe610` | `0xe628` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1c40` | `0x1c30` | **`-0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x4770` | `0x4778` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x8d98` | `0x8da0` | **`+0x8`** |

### Other Changes

```diff

-2454.100.0.0.0
+2459.102.0.0.0

-  - /System/Library/PrivateFrameworks/AppProtection.framework/AppProtection

-  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 6458
-  Symbols:   11502
-  CStrings:  7947
+  Functions: 6435
+  Symbols:   11465
+  CStrings:  7928
Symbols:
+ -[PRSRankingItem populateOtherFeatures:withEvaluator:currentTime:quParsedEvaluator:queryID:isSearchToolClient:quParsedArgSearchTermsEvaluator:]
+ -[PRSRankingItem(Scoring) topicalityScoreWithEvaluator:quParsedEvaluator:isSearchToolClient:quParsedArgSearchTermsEvaluator:]
+ -[SFSearchResult_SpotlightExtras initWithSearchResult:]
+ -[SPQUParse presentIntentArgTypes]
+ -[SPSearchQueryContext searchToolPredictedAppBundleIDs]
+ -[SPSearchQueryContext setSearchToolPredictedAppBundleIDs:]
+ _OBJC_IVAR_$_SPSearchQueryContext._searchToolPredictedAppBundleIDs
+ _OUTLINED_FUNCTION_23
+ _SPCopyPrefsDisabledApps.onceToken
+ ___SPCopyPrefsDisabledApps_block_invoke
+ _homeCosineForSlot
- -[PRSQueryRankingConfiguration isSiriDeserving]
- -[PRSQueryRankingConfiguration setIsSiriDeserving:]
- -[PRSRankingItem populateOtherFeatures:withEvaluator:currentTime:quParsedEvaluator:queryID:isSearchToolClient:quParsedArgSearchTermsEvaluator:isSiriDeserving:]
- -[PRSRankingItem(Scoring) topicalityScoreWithEvaluator:quParsedEvaluator:isSearchToolClient:quParsedArgSearchTermsEvaluator:isSiriDeserving:]
- GCC_except_table32
- GCC_except_table70
- _OBJC_CLASS_$_APApplication
- _OBJC_IVAR_$_PRSQueryRankingConfiguration._isSiriDeserving
- _OUTLINED_FUNCTION_13
- _SSAppExclusionsEnabled
- _SSAppExclusionsEnabled.sEnabled
- _SSAppExclusionsEnabled.sOnce
- _SSCopyTCCDisabledBundlesForSiriAccess
- _SSCopyTCCDisabledBundlesForSiriAccess.tccOnce
- _SSForcedSpotlightMaxChars
- _SSForcedSpotlightMaxWordCount
- _SSInvalidateAppExclusionsDisabledIDsCache
- _SSNumberOfResultsToConsiderForSiriDeserving
- _SSRefreshTCCDisabledBundlesCache
- _SSSantizedBundleIDList
- _SSSiriDeservingEarlyExitTimeout
- _SSSiriDeservingHeuristicDisabled
- _SSSiriDeservingMinChars
- _SSSiriDeservingMinWordCount
- _SSSiriDeservingRegexDisabled
- _SSSiriDeservingScoreThreshold
- _SSSiriDeservingSimulatedDelay
- _SSSubscribeTCCEventsForSiriAccess
- _SSUnsubscribeTCCEventsForSiriAccess
- _TCCAccessCopyBundleIdentifiersDisabledForService
- __SSApply11_2Migration.onceToken
- __SSApply11_2Migration.sResult
- ___SSAppExclusionsEnabled_block_invoke
- ___SSCopyTCCDisabledBundlesForSiriAccess_block_invoke
- ___SSSubscribeTCCEventsForSiriAccess_block_invoke
- ____SSApply11_2Migration_block_invoke
- ___block_descriptor_40_e8_32bs_e50_v24?0Q8"NSObject<OS_tcc_authorization_record>"16ls32l8
- _kTCCServiceSiriAccess
- _sDisabledIDsCache
- _sDisabledIDsCacheLock
- _sDisabledIDsCacheValid
- _tccCacheLock
- _tccCachedBundles
- _tcc_events_filter_create_with_criteria
- _tcc_events_subscribe
- _tcc_events_unsubscribe
- _xpc_bool_create
- _xpc_dictionary_create
CStrings:
+ "[HomeDebug] [Consine] rejecting slot %lu: sqDist=%f out of valid [0,4] range (or NaN)"
+ "[bundle=%@][qid=%lu][query=\"%@\"] Home item %@: L1=%.4f embSim=%.4f normSparse=%.4f normDense=%.4f normText=%.4f normMedia=%.4f base=%.4f cam=%.2f room=%.2f home=%.2f temp=%.2f content=%.2f tmBoost=%.2f sdBoost=%.2f L2=%.4f"
+ "_kMDItemBundleID==com.apple.spotlight"
+ "normMedia"
+ "normText"
+ "sparseDenseBoost"
+ "textMediaBoost"
- "AppExclusions"
- "DisabledBundlesFromSiriTCC"
- "Failed to create TCC events filter; disabled bundle cache will not auto-refresh"
- "Failed to get TCC service name; disabled bundle cache will not auto-refresh"
- "IntelligenceFlow"
- "SSSpotlightSiriDeservingHeuristicDisabled"
- "SSSpotlightSiriDeservingRegexDisabled"
- "TCCAccessCopyBundleIdentifiersDisabledForService returned NULL; preserving existing cache"
- "TCCAccessCopyBundleIdentifiersDisabledForService returned invalid type; preserving existing cache"
- "[bundle=%@][qid=%lu][query=\"%@\"] Home item %@: L1=%.4f embSim=%.4f normSparse=%.4f normDense=%.4f base=%.4f cam=%.2f room=%.2f home=%.2f temp=%.2f content=%.2f L2=%.4f"
- "[siri-deserving-diag][qid=%lu] responseHandler ENTERED for PriorityTimeout (localSelf=%s, cancelled=%s)"
- "[siri-deserving-diag][qid=%lu] responseHandler: delegate=%s, about to call gotResponse"
- "com.apple.spotlight.tcc.siri-access"
- "forcedSpotlightMaxChars"
- "forcedSpotlightMaxWordCount"
- "n/a"
- "numberOfResultsToConsiderForSiriDeserving"
- "siri-access TCC event fired"
- "siri-access TCC subscription armed"
- "siriDeservingEarlyExitTimeout"
- "siriDeservingMinChars"
- "siriDeservingMinWordCount"
- "siriDeservingSimulatedDelay"
- "siriDeservingThreshold"
- "spotlight: TCC siri-access disabled bundles refreshed: %{private}@"
- "v24@?0Q8@\"NSObject<OS_tcc_authorization_record>\"16"
```
