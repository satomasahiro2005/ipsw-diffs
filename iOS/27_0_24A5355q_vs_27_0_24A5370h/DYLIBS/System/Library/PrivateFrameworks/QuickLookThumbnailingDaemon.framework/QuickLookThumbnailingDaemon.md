## QuickLookThumbnailingDaemon

> `/System/Library/PrivateFrameworks/QuickLookThumbnailingDaemon.framework/QuickLookThumbnailingDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x54684` | `0x54604` | **`-0x80`** |

### Other Changes

```diff

-215.0.0.0.0
+216.0.0.0.0
Functions:
~ -[QLCacheMMAPBlobDatabase copyBlobWithInfo:] : 764 -> 760
~ -[QLServerThread generateSuccessiveThumbnailRepresentationsForGeneratorRequests:completionHandler:] : 712 -> 704
~ -[QLServerThread _addThumbnailRequestBatchToQueue:completionHandler:] : 756 -> 752
~ sub_293ec4a78 -> sub_29529aa68 : 2136 -> 2176
~ sub_293ec5428 -> sub_29529b440 : 884 -> 872
~ sub_293ec63c4 -> sub_29529c3d0 : 392 -> 388
~ sub_293ec704c -> sub_29529d054 : 1932 -> 1912
~ sub_293ec7b50 -> sub_29529db44 : 676 -> 696
~ ___68-[QLDiskCacheQueryEnumerator _createNewCacheIndexDatabaseEnumerator]_block_invoke : 828 -> 816
~ sub_293ec9174 -> sub_29529f170 : 280 -> 276
~ -[_QLCacheThread _drainPendingBlocks] : 444 -> 440
~ -[QLCacheIndexDatabase updateHitCount:forFileIdentifier:] : 692 -> 688
~ -[QLCacheIndexDatabase removeThumbnailsForDeletedFiles] : 1056 -> 1052
~ -[QLCacheIndexDatabase removeFilesWithFileInfo:] : 680 -> 676
~ -[QLCacheIndexDatabase _deleteAllTables] : 488 -> 484
~ -[QLCacheIndexDatabase itemsGroupedByProviderDomain:] : 416 -> 412
~ ___59-[QLCacheIndexDatabase noteRemoteThumbnailPresentForItems:]_block_invoke : 416 -> 412
~ ___73-[QLCacheIndexDatabase itemsAfterFilteringOutItemsWithMissingThumbnails:]_block_invoke : 932 -> 924
~ -[QLSqliteDatabase _dropStatementCache] : 308 -> 304
~ -[QLSqliteDatabase(SqliteHelpers) runStatement:withBoundRowIds:count:startingAtIndex:stepHandler:] : 380 -> 376
~ -[QLCacheFragHandler compact] : 688 -> 684
~ -[QLServerThread(ExternalCache) _updateInformationForProviderAndCallPendingBlocksForProviderDomainID:withConnection:inboxURL:thumbnailsURL:] : 648 -> 644
~ -[QLDiskCacheQueryOperation main] : 800 -> 796
~ -[QLDiskCacheQueryOperation cancel] : 1020 -> 1016
~ -[QLCacheIndexDatabaseQueryEnumerator _getCacheIdsForHomogeneousArrayOfRequests:] : 952 -> 944
~ -[QLCacheIndexDatabaseQueryEnumerator _getCacheIds] : 576 -> 568
~ -[QLServerThread uncachedCacheThreadForFileAtURL:] : 1260 -> 1256
~ -[QLServerThread generateSuccessiveThumbnailRepresentationsForRequests:generationHandler:completionHandler:] : 400 -> 396
~ ___42-[QLServerThread cancelThumbnailRequests:]_block_invoke : 492 -> 488
~ ___94-[QLServerThread generateThumbnailForThumbnailRequest:shouldUpdateGenstore:completionHandler:]_block_invoke_2 : 1180 -> 1176
~ -[QLServerThread removeCachedThumbnailsFromUninstalledFileProvidersWithRemainingFileProviderIdentifiers:completionHandler:] : 680 -> 676
~ -[QLServerThread removeCachedThumbnailsFromUninstalledFileProvidersWithIdentifiers:completionHandler:] : 680 -> 676
~ -[QLCacheMMAPBlobDatabase deleteBlobsWithArray:] : 272 -> 268
~ -[QLCacheMMAPBlobDatabase checkConsistency:] : 1248 -> 1244
~ -[QLDiskCache _setThumbnailData:] : 1368 -> 1364
~ -[QLDiskCache writeThumbnailDataBatch:] : 244 -> 240
~ -[QLDiskCache discardThumbnailDataBatchForReset:] : 244 -> 240
~ -[QLDiskCache _deleteBlobArrayFromDatabase:] : 288 -> 284
~ -[QLDiskCache _open] : 1956 -> 1952
~ ___61-[QLThumbnailAdditionIndex enumerateCacheEntriesWithHandler:]_block_invoke : 260 -> 256
~ ___38-[QLThumbnailAdditionIndex allEntries]_block_invoke : 252 -> 248
~ ___62-[QLThumbnailAdditionIndex batchOfEntriesStartingAt:endingAt:]_block_invoke : 548 -> 544
~ -[QLThumbnailAdditionIndex removeAllAdditions] : 456 -> 452
~ -[QLThumbnailAdditionIndex removeEntriesFromDatabase:] : 312 -> 308
~ -[QLThumbnailAdditionIndex cleanUpBatchOfEntries:] : 1528 -> 1524
~ ___50-[QLThumbnailAdditionIndex cleanUpBatchOfEntries:]_block_invoke : 376 -> 372
~ -[QLThumbnailAdditionIndex(CacheDelete) purgeOnMountPoint:withUrgency:beforeDate:] : 1176 -> 1172
~ ___82-[QLThumbnailAdditionIndex(CacheDelete) purgeOnMountPoint:withUrgency:beforeDate:]_block_invoke : 552 -> 548
~ -[QLMemoryCache reset] : 348 -> 344
~ -[QLMemoryCache sendThumbnailDataForThumbnailRequest:withCacheThread:] : 1020 -> 1016
~ ___104-[QLMemoryCache removeCachedThumbnailsFromUninstalledFileProvidersWithRemainingFileProviderIdentifiers:]_block_invoke : 436 -> 432
~ ___83-[QLMemoryCache removeCachedThumbnailsFromUninstalledFileProvidersWithIdentifiers:]_block_invoke : 436 -> 432
~ -[QLServerThread(UbiquitousRequests) downloadThumbnails:forProvider:] : 2324 -> 2308
~ ___69-[QLServerThread(UbiquitousRequests) downloadThumbnails:forProvider:]_block_invoke_2 : 2448 -> 2428
~ ___69-[QLServerThread(UbiquitousRequests) downloadThumbnails:forProvider:]_block_invoke.29 : 296 -> 292
~ ___69-[QLServerThread(UbiquitousRequests) downloadThumbnails:forProvider:]_block_invoke.32 : 532 -> 528
~ sub_293efad60 -> sub_2952d0c78 : 844 -> 836
~ sub_293f01860 -> sub_2952d7770 : 380 -> 376
~ sub_293f01fc4 -> sub_2952d7ed0 : 256 -> 276
~ sub_293f03e54 -> sub_2952d9d74 : 180 -> 192
~ sub_293f06034 -> sub_2952dbf60 : 4940 -> 5000
~ sub_293f07390 -> sub_2952dd2f8 : 392 -> 388
~ sub_293f08068 -> sub_2952ddfcc : 292 -> 288
~ sub_293f08894 -> sub_2952de7f4 : 476 -> 480
~ sub_293f09590 -> sub_2952df4f4 : 472 -> 476
~ sub_293f0abb0 -> sub_2952e0b18 : 344 -> 340
~ sub_293f0afe0 -> sub_2952e0f44 : 632 -> 620
~ sub_293f0b258 -> sub_2952e11b0 : 1312 -> 1316
~ sub_293f0c768 -> sub_2952e26c4 : 304 -> 312
~ sub_293f0c898 -> sub_2952e27fc : 140 -> 172
~ sub_293f0e284 -> sub_2952e4208 : 84 -> 80
```
