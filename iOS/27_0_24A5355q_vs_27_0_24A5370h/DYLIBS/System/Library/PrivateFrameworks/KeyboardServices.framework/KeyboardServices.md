## KeyboardServices

> `/System/Library/PrivateFrameworks/KeyboardServices.framework/KeyboardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b130` | `0x2b088` | **`-0xa8`** |

### Other Changes

```text
Functions:
~ ___61-[_KSTextReplacementCoreDataStore persistentStoreCoordinator]_block_invoke : 1236 -> 1232
~ -[_KSSystemTask initWithName:isPeriodic:period:handler:] : 652 -> 644
~ -[_KSSystemTask initWithName:delay:handler:] : 628 -> 620
~ ___70-[_KSiCloudDeviceListMonitor fetchCloudKitDevicesWithCompletionBlock:]_block_invoke.140 : 552 -> 548
~ ___68-[_KSiCloudDeviceListMonitor fetchICloudDevicesWithCompletionBlock:]_block_invoke : 524 -> 520
~ ___87-[_KSiCloudDeviceListMonitor isAccountCompatibleForCloudKitSyncingWithCompletionBlock:]_block_invoke : 340 -> 336
~ -[_KSCloudKitManager resolveConflicts:] : 576 -> 572
~ -[_KSCloudKitManager copyFieldsFromRecord:toRecord:] : 784 -> 776
~ ___68-[_KSCloudKitManager fetchPublicRecordsWithNames:completionHandler:]_block_invoke : 608 -> 604
~ -[_KSTextReplacementCKStore addEntries:removeEntries:withCompletionHandler:] : 524 -> 520
~ ___76-[_KSTextReplacementCKStore pushLocalChangesWithPriority:completionHandler:]_block_invoke.96 : 1096 -> 1084
~ -[_KSTextReplacementCKStore cloudEntriesFromLocalEntries:] : 680 -> 676
~ -[_KSTextReplacementCKStore cloudRecordIDsForLocalEntries:] : 532 -> 528
~ -[_KSTextReplacementCKStore localEntriesFromCloudEntries:] : 748 -> 744
~ -[_KSTextReplacementClientStore phraseShortcuts] : 344 -> 340
~ -[_KSFileEntry serialiseToTemporaryFile] : 708 -> 704
~ -[_KSFileEntry dealloc] : 280 -> 276
~ -[_KSFileEntry addBlobToFile:] : 304 -> 300
~ -[_KSFileEntry loadAttributesFromURL:] : 844 -> 840
~ -[_KSFileEntry saveAttributesToURL:] : 372 -> 368
~ -[_KSFileDirectory performOnEverything:] : 288 -> 284
~ -[_KSFileDirectory consistencyCheck] : 276 -> 272
~ -[_KSFileDirectory restoreToPath:] : 440 -> 436
~ -[_KSFileDirectory findEntryWithComparison:recursively:] : 408 -> 404
~ -[_KSTextReplacementCoreDataStore recordTextReplacementEntries:] : 584 -> 580
~ -[_KSTextReplacementCoreDataStore deleteTextReplacementsFromLocalStoreWithNames:excludeSavesToCloud:] : 700 -> 696
~ ___67-[_KSTextReplacementCoreDataStore textReplacementEntriesWithLimit:]_block_invoke : 660 -> 656
~ ___67-[_KSTextReplacementCoreDataStore queryEntriesWithPredicate:limit:]_block_invoke : 296 -> 292
~ -[NSManagedObject(TIUserDictionaryWordServer) _copyAttributeValuesFromObject:] : 444 -> 440
~ ___80-[_KSTextReplacementLegacyStore addEntries:removeEntries:withCompletionHandler:]_block_invoke : 1056 -> 1048
~ ___60-[_KSTextReplacementLegacyStore removeEntriesWithPredicate:]_block_invoke : 348 -> 344
~ +[_KSTextReplacementLegacyStore textReplacementEntriesFromManagedObjects:] : 544 -> 540
~ ___59-[_KSTextReplacementLegacyStore mergeShortcutsFromContext:]_block_invoke_2 : 560 -> 556
~ -[_KSTextReplacementLegacyStore mergeEntriesFromAllStoresIncludeLocalVariations:] : 1028 -> 1024
~ ___69-[_KSTextReplacementLegacyStore detectAndCleanDuplicatesWithContext:]_block_invoke : 540 -> 536
~ +[_KSTextReplacementLegacyStore legacyImportFilePaths] : 504 -> 500
~ +[_KSTextReplacementLegacyStore legacyImportWordKeyPairsFromFiles:] : 332 -> 328
~ -[_KSTextReplacementLegacyStore importLegacyEntries] : 672 -> 668
~ ___85-[_KSTextReplacementServer addEntries:removeEntries:forClient:withCompletionHandler:]_block_invoke : 2112 -> 2104
~ ___60-[_KSTextReplacementServer textReplacementEntriesForClient:]_block_invoke : 312 -> 308
~ ___62-[_KSTextReplacementServer queryTextReplacementsWithCallback:]_block_invoke_2 : 540 -> 536
~ ___72-[_KSTextReplacementServer queryTextReplacementsWithPredicate:callback:]_block_invoke_2 : 540 -> 536
~ +[_KSUserWordsSynchroniser generateRecordNameForFilename:withKey:] : 340 -> 344
~ ___66-[_KSUserWordsSynchroniser checkForDownload:uploads:allLanguages:]_block_invoke_5 : 1888 -> 1916
~ ___66-[_KSUserWordsSynchroniser checkForDownload:uploads:allLanguages:]_block_invoke.131 : 1512 -> 1520
~ ___66-[_KSUserWordsSynchroniser checkForDownload:uploads:allLanguages:]_block_invoke.142 : 1776 -> 1772
~ -[_KSUserWordsSynchroniser generateRecordListForLanguages:] : 520 -> 516
~ -[_KSUserWordsSynchroniser checkErrors:] : 688 -> 684
```
