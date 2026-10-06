## StorageData

> `/System/Library/PrivateFrameworks/StorageData.framework/StorageData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19540` | `0x19444` | **`-0xfc`** |

### Other Changes

```text
Functions:
~ -[STStorageGroupSizeOperation main] : 412 -> 408
~ -[STStorageGroupSizeOperation cancel] : 272 -> 268
~ -[STStorageAppsMonitor loadApps] : 1536 -> 1524
~ ___53-[STStorageAppsMonitor applicationInstallsDidChange:]_block_invoke : 640 -> 632
~ -[STStorageAppsMonitor filteredApps:sortedUsingBlock:] : 444 -> 440
~ -[STStorageAppsMonitor appsSortedBySize] : 836 -> 828
~ -[STStorageAppsMonitor storageInfoDict] : 932 -> 928
~ -[STStorageAppsMonitor appSizesDict] : 412 -> 408
~ ___37-[STStorageAppsMonitor _logAppSizes:]_block_invoke : 2092 -> 2084
~ -[STStorageSharedContainer setOwners:] : 868 -> 864
~ _STPersonaCopyPersonaUniqueStrings : 676 -> 672
~ _STPersonaUniqueStringOfType : 336 -> 332
~ +[STAppOverrides overridesForApplication:] : 360 -> 356
~ -[STStorageApp documents] : 552 -> 548
~ _SizesOfContainers : 612 -> 608
~ -[STSizeDict remapKeys:removeMissing:] : 392 -> 388
~ -[STSizeDict total] : 380 -> 376
~ -[STMutableSizeDict removeSmallerThan:] : 312 -> 308
~ -[STMSizeCache loadCacheFromPref] : 1300 -> 1296
~ __CompressPath : 396 -> 392
~ -[STMSizeCache _writeCache] : 720 -> 716
~ -[STMSizeCache itemsContainingPath:] : 408 -> 404
~ -[STMSizeCache itemsContainedByPath:] : 576 -> 572
~ -[STMSizeCache pruneCache] : 320 -> 316
~ -[STMSizeCache addItems:] : 244 -> 240
~ -[STMSizeCache processCacheEvents:] : 724 -> 720
~ -[STMSizer(Apps) addApps:] : 724 -> 716
~ +[STMSizer(Apps) listOfUsedPathsInOverrides:] : 352 -> 348
~ -[STMSizer setRootPaths:] : 788 -> 784
~ __FSEventStreamCallback : 484 -> 492
~ -[STMSizer processEvents:] : 724 -> 720
~ -[STMSizer(URLs) addURLs:usingFastSizingIfPossible:] : 360 -> 356
~ -[STMSizer(Containers) addContainers:] : 344 -> 340
~ +[STMSizer(Containers) containersWithClass:] : 368 -> 364
~ +[STStorageMediaMonitor listOfUsedDataClassesInOverrides:] : 548 -> 544
~ -[STUsageBundleRegistry loadReporters] : 924 -> 920
~ -[STUsageBundleRegistry loadBundlesForReporters:] : 1132 -> 1124
~ +[STStorageDataManager sharedContainersFor:] : 564 -> 560
~ +[STStorageDataManager computeCategoriesForApps:] : 560 -> 556
~ +[STStorageDataManager computeBundleRemappings:] : 572 -> 568
~ +[STStorageDataManager updateAppsWithPrevious:usageBundles:skipAppRecordBlock:] : 4664 -> 4644
~ ___79+[STStorageDataManager updateAppsWithPrevious:usageBundles:skipAppRecordBlock:]_block_invoke_4 : 1532 -> 1524
~ _MakePseudoAppForContainer : 744 -> 740
~ +[STStorageDataManager fixClonesInPhotosAndMessages:] : 552 -> 548
~ ___37-[STFileProviderMonitor startMonitor]_block_invoke : 380 -> 376
~ ___29-[STFileProviderMonitor sync]_block_invoke : 380 -> 376
~ -[STLaunchDates updateDates:] : 600 -> 596
~ ___34-[STLaunchDates addSpotlightDates]_block_invoke : 356 -> 352
~ _STDictLookup : 376 -> 372
~ ___STSelectMediaUsage_block_invoke : 288 -> 284
~ _STComputeUsageBundleData : 520 -> 516
~ ___STComputeFSOverrides_block_invoke : 608 -> 604
~ ___STComputeCacheDeleteOverrides_block_invoke : 600 -> 596
~ _STFileProviderExternalDataSize : 1408 -> 1404
```
