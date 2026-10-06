## SpotlightServices

> `/System/Library/PrivateFrameworks/SpotlightServices.framework/SpotlightServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15f6cc` | `0x1603cc` | **`+0xd00`** |
| `__TEXT.__oslogstring` | `0xba3b` | `0xbc0b` | **`+0x1d0`** |
| `__TEXT.__cstring` | `0x3a8ba` | `0x3a99a` | **`+0xe0`** |
| `__AUTH_CONST.__cfstring` | `0x36c00` | `0x36c60` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x2b20` | `0x2b80` | **`+0x60`** |
| `__DATA.__bss` | `0x5d8` | `0x628` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0xf40` | `0xf80` | **`+0x40`** |
| `__TEXT.__const` | `0x2df8` | `0x2e38` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3450` | `0x3488` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x181c0` | `0x181f0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x100d8` | `0x10108` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x8da0` | `0x8dd0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xe628` | `0xe648` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1c30` | `0x1c40` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x5068` | `0x5058` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x15b4` | `0x15b8` | **`+0x4`** |

### Other Changes

```diff

-2459.105.0.0.0
+2465.1.2.0.0

+  - /System/Library/PrivateFrameworks/AppProtection.framework/AppProtection

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 6435
-  Symbols:   11466
-  CStrings:  7929
+  Functions: 6458
+  Symbols:   11506
+  CStrings:  7943
Symbols:
+ -[PRSRankingItem hasCorrespondingBookmark]
+ -[PRSRankingItem setHasCorrespondingBookmark:]
+ -[SPSearchQueryContext contactEntity]
+ GCC_except_table58
+ GCC_except_table61
+ GCC_except_table91
+ _OBJC_CLASS_$_APApplication
+ _OBJC_IVAR_$_PRSRankingItem._hasCorrespondingBookmark
+ _SSAppExclusionsEnabled
+ _SSAppExclusionsEnabled.sEnabled
+ _SSAppExclusionsEnabled.sOnce
+ _SSCampoEnabled.cachedResult
+ _SSCampoEnabled.deadline
+ _SSCopyTCCDisabledBundlesForSiriAccess
+ _SSCopyTCCDisabledBundlesForSiriAccess.tccOnce
+ _SSHomeBundleIdentifier
+ _SSHomeItemBelowRetrievalThresholds
+ _SSInvalidateAppExclusionsDisabledIDsCache
+ _SSRefreshTCCDisabledBundlesCache
+ _SSSantizedBundleIDList
+ _SSSectionIsHome
+ _SSSubscribeTCCEventsForSiriAccess
+ _SSUnsubscribeTCCEventsForSiriAccess
+ _TCCAccessCopyBundleIdentifiersDisabledForService
+ __SSApply11_2Migration.onceToken
+ __SSApply11_2Migration.sResult
+ ___SSAppExclusionsEnabled_block_invoke
+ ___SSCopyTCCDisabledBundlesForSiriAccess_block_invoke
+ ___SSSubscribeTCCEventsForSiriAccess_block_invoke
+ ____SSApply11_2Migration_block_invoke
+ ___block_descriptor_40_e8_32bs_e50_v24?0Q8"NSObject<OS_tcc_authorization_record>"16ls32l8
+ _homeExtractEmbeddingSqDistances
+ _homeSqDistanceForSlot
+ _kTCCServiceSiriAccess
+ _mach_continuous_time
+ _mach_timebase_info
+ _sDisabledIDsCache
+ _sDisabledIDsCacheLock
+ _sDisabledIDsCacheValid
+ _tccCacheLock
+ _tccCachedBundles
+ _tcc_events_filter_create_with_criteria
+ _tcc_events_subscribe
+ _tcc_events_unsubscribe
+ _xpc_bool_create
+ _xpc_dictionary_create
- GCC_except_table50
- GCC_except_table57
- GCC_except_table90
- _SPCopyPrefsDisabledApps.onceToken
- ___SPCopyPrefsDisabledApps_block_invoke
- _homeCosineForSlot
CStrings:
+ "AppExclusions"
+ "DisabledBundlesFromSiriTCC"
+ "Failed to create TCC events filter; disabled bundle cache will not auto-refresh"
+ "Failed to get TCC service name; disabled bundle cache will not auto-refresh"
+ "IntelligenceFlow"
+ "TCCAccessCopyBundleIdentifiersDisabledForService returned NULL; preserving existing cache"
+ "TCCAccessCopyBundleIdentifiersDisabledForService returned invalid type; preserving existing cache"
+ "[HomeDebug] [SqDistance] rejecting slot %lu: sqDist=%f out of valid [0,4] range (or NaN)"
+ "[HomeWeakRetrieval]"
+ "com.apple.spotlight.clear.pasteboard.history"
+ "com.apple.spotlight.tcc.siri-access"
+ "siri-access TCC event fired"
+ "siri-access TCC subscription armed"
+ "spotlight: TCC siri-access disabled bundles refreshed: %{private}@"
+ "v24@?0Q8@\"NSObject<OS_tcc_authorization_record>\"16"
- "[HomeDebug] [Consine] rejecting slot %lu: sqDist=%f out of valid [0,4] range (or NaN)"
```
