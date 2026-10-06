## SpotlightServices

> `/System/Library/PrivateFrameworks/SpotlightServices.framework/SpotlightServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15ef68` | `0x15fe28` | **`+0xec0`** |
| `__TEXT.__oslogstring` | `0xb9cb` | `0xbc3b` | **`+0x270`** |
| `__AUTH.__objc_data` | `0x1828` | `0x16e8` | **`-0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x2440` | `0x2580` | **`+0x140`** |
| `__TEXT.__cstring` | `0x3a94a` | `0x3aa1a` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x36c20` | `0x36ca0` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x2b20` | `0x2b80` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0xf40` | `0xf70` | **`+0x30`** |
| `__AUTH_CONST.__objc_intobj` | `0x4770` | `0x47a0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x100d0` | `0x10100` | **`+0x30`** |
| `__DATA_DIRTY.__bss` | `0x54b8` | `0x54e8` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x18168` | `0x18190` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x1c18` | `0x1c40` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xe5d0` | `0xe5f8` | **`+0x28`** |
| `__DATA.__bss` | `0x638` | `0x618` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8d68` | `0x8d88` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x31d0` | `0x31f0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x5068` | `0x5050` | **`-0x18`** |
| `__DATA.__data` | `0xe80` | `0xe88` | **`+0x8`** |

### Other Changes

```diff

-2448.100.0.0.0
+2451.1.101.0.0

+  - /System/Library/PrivateFrameworks/AppProtection.framework/AppProtection

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 6436
-  Symbols:   11464
-  CStrings:  7931
+  Functions: 6456
+  Symbols:   11499
+  CStrings:  7947
Symbols:
+ +[SSSectionRankingBlender rankingItemLacksKeywordAnchor:]
+ -[SSSectionRankingBlender topResultLacksKeywordAnchor]
+ -[SSSectionRankingBlender topResultQualityCap]
+ _MDItemEventEndTimeIsUnknown
+ _MDItemEventStartTimeIsUnknown
+ _OBJC_CLASS_$_APApplication
+ _SSAppExclusionsEnabled
+ _SSAppExclusionsEnabled.sEnabled
+ _SSAppExclusionsEnabled.sOnce
+ _SSCopyTCCDisabledBundlesForSiriAccess
+ _SSCopyTCCDisabledBundlesForSiriAccess.tccOnce
+ _SSInvalidateAppExclusionsDisabledIDsCache
+ _SSRefreshTCCDisabledBundlesCache
+ _SSRemindersIntegrationAccountIdentifier
+ _SSSantizedBundleIDList
+ _SSSubscribeTCCEventsForSiriAccess
+ _SSUnsubscribeTCCEventsForSiriAccess
+ _TCCAccessCopyBundleIdentifiersDisabledForService
+ __OBJC_$_PROP_LIST_SSSectionRankingBlender
+ __SSApply11_2Migration.onceToken
+ __SSApply11_2Migration.sResult
+ ___SSAppExclusionsEnabled_block_invoke
+ ___SSCopyTCCDisabledBundlesForSiriAccess_block_invoke
+ ___SSSubscribeTCCEventsForSiriAccess_block_invoke
+ ____SSApply11_2Migration_block_invoke
+ ___block_descriptor_40_e8_32bs_e50_v24?0Q8"NSObject<OS_tcc_authorization_record>"16ls32l8
+ _kTCCServiceSiri
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
- _SPCopyPrefsDisabledApps.onceToken
- ___SPCopyPrefsDisabledApps_block_invoke
CStrings:
+ "AppExclusions"
+ "DisabledBundlesFromSiriTCC"
+ "Failed to create TCC events filter; disabled bundle cache will not auto-refresh"
+ "Failed to get TCC service name; disabled bundle cache will not auto-refresh"
+ "IntelligenceFlow"
+ "TCCAccessCopyBundleIdentifiersDisabledForService returned NULL; preserving existing cache"
+ "TCCAccessCopyBundleIdentifiersDisabledForService returned invalid type; preserving existing cache"
+ "[SpotlightRanking] [SearchTool] [BookmarkFreshnessFloor] query=%@ qid=%llu identifier=%@ appEntityType=%@ no usable date attribute; setting freshnessScore=%f"
+ "com.apple.spotlight.tcc.siri-access"
+ "integration:reminders"
+ "lacksKeywordAnchor"
+ "qualityCapped"
+ "siri-access TCC event fired"
+ "siri-access TCC subscription armed"
+ "spotlight: TCC siri-access disabled bundles refreshed: %{private}@"
+ "v24@?0Q8@\"NSObject<OS_tcc_authorization_record>\"16"
```
