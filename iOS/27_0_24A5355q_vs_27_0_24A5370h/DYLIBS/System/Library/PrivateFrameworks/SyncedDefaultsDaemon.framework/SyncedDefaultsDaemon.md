## SyncedDefaultsDaemon

> `/System/Library/PrivateFrameworks/SyncedDefaultsDaemon.framework/SyncedDefaultsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32ff8` | `0x32f74` | **`-0x84`** |
| `__DATA_CONST.__const` | `0xd10` | `0xd20` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1748` | `0x1750` | **`+0x8`** |

### Other Changes

```diff

-2707.0.0.0.0
+2708.0.0.0.0

+  - /usr/lib/swift/libswiftCoreLocation.dylib

+  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib

-  Symbols:   1313
+  Symbols:   1317
Symbols:
+ -[SYDDaemonToClientConnection setCloudSyncUserDefaultEnabled:storeIdentifier:completionHandler:]
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_FORCE_LOAD_$_swiftCoreLocation_$_SyncedDefaultsDaemon
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers_$_SyncedDefaultsDaemon
- -[SYDDaemonToClientConnection setCloudSyncUserDefaultEnabled:storeIdentifier:]
Functions:
~ ___60-[SYDTCCHelper isUbiquityEnabledForAuditToken:defaultValue:]_block_invoke : 872 -> 868
~ -[SYDSyncManager syncEngine:handleEvent:] : 1904 -> 1876
~ ___63-[SYDCoreDataStore keyValuesForKeyIDs:createIfNecessary:error:]_block_invoke_2 : 1016 -> 1012
~ ___73-[SYDCoreDataStore changedKeysForStoreIdentifier:sinceChangeToken:error:]_block_invoke : 3220 -> 3212
~ ___73-[SYDCoreDataStore dictionaryRepresentationForStoreWithIdentifier:error:]_block_invoke : 1288 -> 1284
~ -[SYDSyncManager syncEngine:nextRecordZoneChangeBatchForContext:] : 704 -> 700
~ ___39-[SYDSyncManager didEndFetchingChanges]_block_invoke : 572 -> 568
~ -[SYDSyncManager savePendingChangesToCloudForStoreIdentifiers:group:completionHandler:] : 1000 -> 996
~ -[SYDSyncManager fetchChangesFromCloudForStoreIdentifiers:group:completionHandler:] : 860 -> 856
~ _SYDSanitizedErrorObjectForXPC : 792 -> 788
~ -[SYDCoreDataStore keyValuesForKeyIDs:createIfNecessary:error:] : 828 -> 824
~ -[SYDCoreDataStore managedKeyValuesForKeyIDs:inContext:error:] : 1132 -> 1124
~ _SYDMigrateToDaemonContainerIfNecessary : 2332 -> 2324
~ ___SYDStoreTypesForCurrentPlatform_block_invoke : 308 -> 304
~ -[ACAccountStore(SYD) syd_accountForPersonaIdentifier:error:] : 616 -> 612
~ -[SYDTCCHelper findDisabledStoreIdentifiers] : 868 -> 864
~ -[SYDStoreBundleMap generateStoreBundleMap] : 1452 -> 1448
~ -[SYDDaemon _processAccountChanges] : 1356 -> 1348
~ -[SYDDaemon applicationIdentifiersForStoreIdentifiers:] : 580 -> 576
~ ___55-[SYDDaemon applicationIdentifiersForStoreIdentifiers:]_block_invoke : 696 -> 692
~ -[SYDDaemon initializeKnownSyncManagers] : 520 -> 516
~ ___40-[SYDDaemon initializeKnownSyncManagers]_block_invoke : 564 -> 560
~ -[SYDDaemon allStoreIdentifiersWithError:] : 852 -> 848
~ ___39-[SYDDaemon removeUnitTestSyncManagers]_block_invoke : 424 -> 420
~ -[SYDDaemon sendAnalyticsEventForCurrentState] : 1728 -> 1724
~ ___27-[SYDDaemon willSwitchUser]_block_invoke : 348 -> 344
~ ___26-[SYDDaemon uploadContent]_block_invoke : 708 -> 704
~ -[SYDDaemonToClientConnection synchronizeStoresWithIdentifiers:type:testConfiguration:completionHandler:] : 1104 -> 1100
~ -[SYDDaemonToClientConnection setCloudSyncUserDefaultEnabled:storeIdentifier:] -> -[SYDDaemonToClientConnection setCloudSyncUserDefaultEnabled:storeIdentifier:completionHandler:] : 124 -> 164
~ ___97-[SYDDaemonToClientConnection notifyAccountDidChangeFromAccountID:toAccountID:completionHandler:]_block_invoke : 736 -> 732
~ +[SYDKeyValue deleteFilesForAssetsInKeyValueRecord:] : 652 -> 648
~ ___59-[SYDSyncManager deleteDataFromCloudWithCompletionHandler:]_block_invoke : 720 -> 716
~ ___55-[SYDSyncManager markAllKeyValuesAsNeedingToBeUploaded]_block_invoke : 396 -> 392
~ -[SYDSyncManager markAllKeyValuesAsNeedingToBeUploadedForStoreWithIdentifier:] : 716 -> 712
~ -[SYDSyncManager addKeyValueRecordIDsToSave:recordIDsToDelete:storeIdentifier:] : 1256 -> 1236
~ ___57-[SYDSyncManager processFetchedRecords:deletedRecordIDs:]_block_invoke : 2748 -> 2736
~ -[SYDSyncManager syncEngine:nextFetchChangesOptionsForContext:] : 968 -> 960
~ -[SYDSyncManager syncEngine:relatedApplicationBundleIdentifiersForZoneIDs:recordIDs:] : 636 -> 628
~ +[SYDSyncManager isDataSeparated] : 284 -> 280
~ -[SYDCoreDataStore _saveKeyValues:excludeFromChangeTracking:enforceQuota:forceCreateNewRow:error:] : 688 -> 684
~ ___98-[SYDCoreDataStore _saveKeyValues:excludeFromChangeTracking:enforceQuota:forceCreateNewRow:error:]_block_invoke_2 : 2388 -> 2376
~ ___62-[SYDCoreDataStore allRecordNamesInStoreWithIdentifier:error:]_block_invoke : 660 -> 656
~ ___49-[SYDCoreDataStore allStoreIdentifiersWithError:]_block_invoke : 652 -> 648
~ -[SYDCoreDataStore fileSizeBytes] : 764 -> 760
~ +[SYDCoreDataStore isCorruptionError:] : 388 -> 480
~ +[SYDPlistToCoreDataMigrator allPossibleStorePlistURLsWithLibraryDirectoryURL:] : 588 -> 580
~ +[SYDPlistToCoreDataMigrator addPlistURLsForBundleIdentifier:defaultStoreIdentifier:additionalStoreIdentifiers:toDictionary:syncedPreferencesDirectoryURL:] : 740 -> 736
```
