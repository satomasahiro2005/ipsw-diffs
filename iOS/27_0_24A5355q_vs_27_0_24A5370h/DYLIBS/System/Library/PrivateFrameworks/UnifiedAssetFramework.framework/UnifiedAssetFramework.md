## UnifiedAssetFramework

> `/System/Library/PrivateFrameworks/UnifiedAssetFramework.framework/UnifiedAssetFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77f64` | `0x7761c` | **`-0x948`** |
| `__TEXT.__oslogstring` | `0xef4d` | `0xedd1` | **`-0x17c`** |
| `__TEXT.__gcc_except_tab` | `0xf3c` | `0xe08` | **`-0x134`** |
| `__AUTH_CONST.__const` | `0x588` | `0x5c8` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x858` | `0x890` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x5080` | `0x5060` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x230` | `0x250` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3628` | `0x3640` | **`+0x18`** |
| `__TEXT.__cstring` | `0xb754` | `0xb73d` | **`-0x17`** |
| `__DATA_CONST.__const` | `0x1cd8` | `0x1ce8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2680` | `0x2670` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x5c0` | `0x5b8` | **`-0x8`** |

### Other Changes

```diff

-3600.61.1.0.0
+3600.67.1.0.0

-  Functions: 1448
-  Symbols:   2736
-  CStrings:  2110
+  Functions: 1449
+  Symbols:   2745
+  CStrings:  2105
Symbols:
+ +[UAFCoreAnalyticsInstrumenter sendCAEvent:assetSpecifier:assetVersion:sessionId:]
+ +[UAFCoreAnalyticsInstrumenter sendCAEventLazy:assetSpecifier:assetVersion:]
+ +[UAFPlatform OSVersion]
+ +[UAFPlatform buildVersion]
+ +[UAFUserManager resolveUserForUID:honorUID:error:]
+ GCC_except_table101
+ GCC_except_table107
+ GCC_except_table110
+ GCC_except_table126
+ GCC_except_table149
+ GCC_except_table56
+ GCC_except_table71
+ GCC_except_table75
+ GCC_except_table78
+ GCC_except_table87
+ GCC_except_table89
+ GCC_except_table93
+ GCC_except_table99
+ _AnalyticsCreateSession
+ _AnalyticsEndSession
+ _AnalyticsSendEventWithSession
+ ___24+[UAFPlatform OSVersion]_block_invoke
+ ___27+[UAFPlatform buildVersion]_block_invoke
+ ___49-[UAFSubscriptionStoreManager _subscriptionTime:]_block_invoke
+ ___76+[UAFCoreAnalyticsInstrumenter sendCAEventLazy:assetSpecifier:assetVersion:]_block_invoke
+ ___block_descriptor_121_e8_32s40s48s56s64s72s80bs88bs96bs104bs_e5_v8?0ls32l8s40l8s48l8s56l8s80l8s64l8s88l8s96l8s104l8s72l8
+ _kUAFUserResolutionFailurePhaseConsoleUser
+ _kUAFUserResolutionFailurePhaseUIDLookup
+ _nw_path_create_default_evaluator
+ _nw_path_evaluator_copy_path
+ _nw_path_get_status
+ _nw_path_is_expensive
- +[UAFAssetSetMetadata OSVersion]
- +[UAFCommonUtilities emptyLegacyStagingLogsDirectoryUnderStoragePath:]
- +[UAFCoreAnalyticsInstrumenter sendCAEvent:assetSpecifier:assetVersion:]
- GCC_except_table100
- GCC_except_table106
- GCC_except_table109
- GCC_except_table125
- GCC_except_table148
- GCC_except_table55
- GCC_except_table69
- GCC_except_table70
- GCC_except_table74
- GCC_except_table76
- GCC_except_table86
- GCC_except_table88
- GCC_except_table91
- GCC_except_table96
- GCC_except_table98
- _OBJC_CLASS_$_NWPathEvaluator
- ___32+[UAFAssetSetMetadata OSVersion]_block_invoke
- ___70+[UAFCommonUtilities emptyLegacyStagingLogsDirectoryUnderStoragePath:]_block_invoke
- ___72+[UAFCoreAnalyticsInstrumenter sendCAEvent:assetSpecifier:assetVersion:]_block_invoke
- ___block_descriptor_40_e8_32r_e27_B24?0"NSURL"8"NSError"16lr32l8
CStrings:
+ "%s CA session creation failed for %{public}@, will only emit lazy CA events"
+ "%s Could not determine system user for platform asset unsubscribe, not unsubscribing: %{public}@"
+ "%s Emitting asset set state CA event for %{public}@ with session id: %{public}@"
+ "%s Failed to close the CA session for %{public}@"
+ "%s OS version: %{public}@"
+ "%s Platform asset unsubscribe failed"
+ "%s Subscribe: could not resolve user for pid %d subscriber %{public}@: %{public}@"
+ "%s Unsubscribe: could not resolve user for pid %d subscriber %{public}@: %{public}@"
+ "%s XPC: Unsubscribed platform asset"
+ "%s build version: %{public}@"
+ "+[UAFPlatform OSVersion]_block_invoke"
+ "+[UAFPlatform buildVersion]_block_invoke"
+ "Could not determine user for uid %u"
+ "Could not resolve user for subscription"
+ "Could not resolve user for unsubscription"
+ "No console user available for system uid %u"
- "%s Cannot empty legacy StagingLogs directory: empty storagePath"
- "%s Cannot enumerate legacy StagingLogs directory at %{public}@"
- "%s Could not determine console user, trying via XPC"
- "%s Could not determine console user, trying with XPC"
- "%s Emitting asset set state CA event for %{public}@"
- "%s Emptied legacy StagingLogs directory at %{public}@ (removed %lu of %lu entries)"
- "%s Failed to enumerate legacy StagingLogs directory at %{public}@: %{public}@"
- "%s Failed to remove legacy StagingLogs entry %{public}@: %{public}@"
- "%s Legacy StagingLogs directory already absent at %{public}@"
- "%s Legacy StagingLogs directory already empty at %{public}@"
- "%s OS version for the metadata asset: %{public}@"
- "%s Partially emptied legacy StagingLogs directory at %{public}@ (removed %lu of %lu visited entries before enumeration error)"
- "%s Received subscription request without user from pid %d for subscriber: %{public}@, could not determine console user"
- "%s XPC: Unsubscribed platform asset: %{public}@"
- "+[UAFAssetSetMetadata OSVersion]_block_invoke"
- "+[UAFCommonUtilities emptyLegacyStagingLogsDirectoryUnderStoragePath:]"
- "Could not determine console user"
- "Could not determine current user"
- "StagingLogs"
- "could not determine console user"
- "could not determine user for uid %u"
```
