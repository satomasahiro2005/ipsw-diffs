## AvatarPersistence

> `/System/Library/PrivateFrameworks/AvatarPersistence.framework/AvatarPersistence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ba3c` | `0x2b9bc` | **`-0x80`** |

### Other Changes

```diff

-402.100.1.0.0
+403.100.1.0.0
Functions:
~ -[AVTCoreDataStoreBackend recordIdentifiersForManagedObjectIDs:managedObjectContext:error:] : 712 -> 708
~ -[AVTCoreDataStoreBackend getChangedObjectIDsOfInterest:deletedIdentifiers:forTransactions:] : 844 -> 840
~ ___56-[AVTCoreDataStoreBackend avatarsForFetchRequest:error:]_block_invoke : 908 -> 900
~ ___45-[AVTCoreDataStoreBackend saveAvatars:error:]_block_invoke : 984 -> 980
~ +[AVTCoreDataStoreBackend cdFetchRequestForAvatarFetchRequest:recordTransformer:] : 976 -> 968
~ +[AVTPAvatarRecordDataSource sortedRecordsEditableFirstReverseOrder:] : 352 -> 348
~ ___79-[AVTPAvatarRecordDataSource enumerateObserversRespondingToSelector:withBlock:]_block_invoke : 288 -> 284
~ +[AVTAvatarRecordRendering preloadAvatarsWithIdentifiers:store:environment:completionHandler:] : 396 -> 392
~ ___96+[AVTAvatarRecordRendering preloadAvatarsWithFetchRequests:store:environment:completionHandler:]_block_invoke : 640 -> 636
~ +[AVTPuppetStore createPuppetRecords] : 332 -> 328
~ -[AVTPuppetStore avatarsWithIdentifiers:error:] : 600 -> 596
~ ___88-[AVTCoreDataStoreMaintenance fixDuplicateRecordIdentifiers:managedObjectContext:error:]_block_invoke : 440 -> 436
~ -[AVTCoreDataStoreMaintenance fetchDuplicatedRecordsForIdentifiers:managedObjectContext:error:] : 724 -> 720
~ -[NSArray(AvatarUI) avt_map:] : 420 -> 416
~ -[NSArray(AvatarUI) avt_firstObjectPassingTest:] : 312 -> 308
~ +[NSDictionary(AvatarUI) _avtui_dictionaryByIndexingObjectsInArray:by:] : 484 -> 480
~ _AVTAnyTransactionHasChangesFromAuthor_block_invoke_3 : 360 -> 356
~ _AVTAnyTransactionHasChangesFromOtherThanAuthor_block_invoke_4 : 360 -> 356
~ _AVTAnyTransactionHasChangesFromOtherThanBundleID_block_invoke_5 : 360 -> 356
~ _AVTAnyTransactionHasAvatarChange_block_invoke_6 : 508 -> 504
~ -[AVTArchiverBasedStoreBackend avatarsWithIdentifiers:error:] : 524 -> 520
~ -[AVTArchiverBasedStoreBackend saveAvatars:error:] : 288 -> 284
~ +[AVTArchiverBasedStoreBackend classifyRecordsByIdentifiers:] : 356 -> 352
~ ___88-[AVTStickerUserDefaultsBackend deleteRecentStickersForChangeTracker:completionHandler:]_block_invoke_2 : 308 -> 304
~ +[AVTArchiverBasedStorePersistence _migrateDifferentAvatarKitVersionsForContent:logger:] : 472 -> 468
~ -[AVTCoreDataChangeTracker trackerChangesFromPersistentChanges:managedObjectContext:] : 496 -> 492
~ -[AVTCoreDataChangeTracker enumerateChangesAfterToken:managedObjectContext:changesHandler:error:] : 732 -> 728
~ -[_AVTCoreDataPersistentStoreLocalConfiguration tearDownAndEraseAllContent:] : 688 -> 684
~ ___77-[AVTStickerChangeObserver processChangesForChangeTracker:completionHandler:]_block_invoke_2 : 352 -> 348
~ -[AVTCoreDataStoreServer migrate] : 412 -> 408
```
