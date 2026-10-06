## AppPredictionClient

> `/System/Library/PrivateFrameworks/AppPredictionClient.framework/AppPredictionClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18c558` | `0x18d314` | **`+0xdbc`** |
| `__TEXT.__oslogstring` | `0x179bc` | `0x17c32` | **`+0x276`** |
| `__TEXT.__cstring` | `0x1c3ab` | `0x1c4ba` | **`+0x10f`** |
| `__AUTH_CONST.__objc_const` | `0x46178` | `0x461d8` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x18f44` | `0x18f7c` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0xa0f8` | `0xa120` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x155a0` | `0x155c0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x1c98` | `0x1ca4` | **`+0xc`** |
| `__TEXT.__const` | `0x708` | `0x710` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6910` | `0x6908` | **`-0x8`** |

### Other Changes

```diff

-671.0.2.0.1
+674.0.1.0.0

-  Functions: 10921
-  Symbols:   16827
-  CStrings:  4821
+  Functions: 10928
+  Symbols:   16833
+  CStrings:  4841
Symbols:
+ +[ATXDefaultHomeScreenItemProducerUtilities similarThirdPartyWidgetsForPosition:assets:]
+ -[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLastDays:withFilter:]
+ -[ATXAppLaunches rawLaunchCountAndDistinctDaysLaunchedForAllAppsOverLastDays:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _dayZeroStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _firstWidgetThatIsntUsedYet:usedPersonalities:size:]
+ -[ATXDefaultHomeScreenItemProducer _computeNewlyInstalledThresholdsIfNeeded]
+ -[ATXInformationStore _fetchDistinctWidgetsIgnoringIntentWithQuery:sinceDate:]
+ -[ATXInformationStore fetchAllDistinctWidgetsIgnoringIntentWithTimelineDonations]
+ GCC_except_table236
+ GCC_except_table240
+ GCC_except_table244
+ GCC_except_table248
+ GCC_except_table252
+ GCC_except_table255
+ GCC_except_table259
+ GCC_except_table262
+ GCC_except_table266
+ GCC_except_table275
+ GCC_except_table280
+ GCC_except_table284
+ GCC_except_table288
+ GCC_except_table291
+ GCC_except_table294
+ GCC_except_table298
+ GCC_except_table302
+ GCC_except_table305
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemProducer._newInstallThreshold
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemProducer._widgetInstallDateThreshold
+ _OBJC_IVAR_$_ATXHomeScreenConfigCache._usesDefaultRootPath
+ ___78-[ATXAppLaunches rawLaunchCountAndDistinctDaysLaunchedForAllAppsOverLastDays:]_block_invoke
+ ___78-[ATXInformationStore _fetchDistinctWidgetsIgnoringIntentWithQuery:sinceDate:]_block_invoke
+ ___78-[ATXInformationStore _fetchDistinctWidgetsIgnoringIntentWithQuery:sinceDate:]_block_invoke_2
+ ___78-[ATXInformationStore _fetchDistinctWidgetsIgnoringIntentWithQuery:sinceDate:]_block_invoke_3
+ ___80-[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLastDays:withFilter:]_block_invoke
+ ___80-[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLastDays:withFilter:]_block_invoke_2
+ ___80-[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLastDays:withFilter:]_block_invoke_3
+ ___88+[ATXDefaultHomeScreenItemProducerUtilities similarThirdPartyWidgetsForPosition:assets:]_block_invoke
+ _kATXAppLaunchesSmartStackLookbackDays
- +[ATXDefaultHomeScreenItemProducerUtilities similarThirdPartyWidgetsForPosition:]
- -[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLast28DaysWithFilter:]
- -[ATXDefaultHomeScreenItemOnboardingStacksProducer _firstWidgetThatIsntUsedYet:usedPersonalities:]
- GCC_except_table234
- GCC_except_table238
- GCC_except_table242
- GCC_except_table246
- GCC_except_table250
- GCC_except_table253
- GCC_except_table257
- GCC_except_table260
- GCC_except_table264
- GCC_except_table273
- GCC_except_table278
- GCC_except_table28
- GCC_except_table282
- GCC_except_table286
- GCC_except_table289
- GCC_except_table292
- GCC_except_table296
- GCC_except_table300
- GCC_except_table303
- ___67-[ATXInformationStore fetchDistinctWidgetsIgnoringIntentSinceDate:]_block_invoke
- ___67-[ATXInformationStore fetchDistinctWidgetsIgnoringIntentSinceDate:]_block_invoke_2
- ___67-[ATXInformationStore fetchDistinctWidgetsIgnoringIntentSinceDate:]_block_invoke_3
- ___71-[ATXWidgetDescriptorCache _queue_fetchAllDescriptorMetadataWithError:]_block_invoke
- ___79-[ATXAppLaunches rawLaunchCountAndDistinctDaysLaunchedOverLast28DaysForAllApps]_block_invoke
- ___81+[ATXDefaultHomeScreenItemProducerUtilities similarThirdPartyWidgetsForPosition:]_block_invoke
- ___81-[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLast28DaysWithFilter:]_block_invoke
- ___81-[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLast28DaysWithFilter:]_block_invoke_2
- ___81-[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLast28DaysWithFilter:]_block_invoke_3
- ___86-[ATXDefaultHomeScreenItemManager fetchWidgetSmartStackWithRequest:completionHandler:]_block_invoke_2
CStrings:
+ "%s: Skipping descriptor disfavored for tvOS: %@"
+ "%s: Skipping descriptor that does not support systemSmall: %@"
+ "%s: built day zero default stack with %lu widgets"
+ "%s: not adding default widget %{public}@ because it is already used"
+ "%s: not adding default widget %{public}@ because it is in the client's deny list"
+ "%s: not adding widget %{public}@ because it does not support stack layout size %lu"
+ "-[ATXDefaultHomeScreenItemOnboardingStacksProducer _dayZeroStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]"
+ "-[ATXDefaultHomeScreenItemOnboardingStacksProducer _firstWidgetThatIsntUsedYet:usedPersonalities:size:]"
+ "SELECT DISTINCT extensionBundleId, containerBundleIdentifier, widgetKind, widgetFamily FROM timelineDonations;"
+ "SELECT timestamp, score, duration, suggestionId, suggestionMappingReason FROM timelineDonations WHERE extensionBundleId = :extensionBundleId AND widgetKind = :widgetKind AND containerBundleIdentifier IS :containerBundleIdentifier AND suggestionMappingReason IS NOT NULL ORDER BY timestamp"
+ "apps:%lu"
+ "dayZero:%{BOOL}d"
+ "descriptors:%lu"
+ "metadata:%lu"
+ "smartStackAppLaunchHistory"
+ "smartStackFetchAndFilterDescriptors"
+ "smartStackFetchDescriptorMetadata"
+ "smartStackGenerateStacks"
+ "smartStackProducerInit"
+ "smartStackRequest"
+ "stacks:%lu"
+ "stacks:0"
- "-[ATXDefaultHomeScreenItemOnboardingStacksProducer _firstWidgetThatIsntUsedYet:usedPersonalities:]"
- "SELECT timestamp, score, duration, suggestionId, suggestionMappingReason FROM timelineDonations WHERE extensionBundleId = :extensionBundleId AND widgetKind = :widgetKind AND containerBundleIdentifier = :containerBundleIdentifier AND suggestionMappingReason IS NOT NULL ORDER BY timestamp"
```
