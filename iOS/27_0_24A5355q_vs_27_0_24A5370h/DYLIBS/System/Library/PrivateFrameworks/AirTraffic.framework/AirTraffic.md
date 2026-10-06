## AirTraffic

> `/System/Library/PrivateFrameworks/AirTraffic.framework/AirTraffic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18c64` | `0x18bf0` | **`-0x74`** |

### Other Changes

```diff

-4026.100.55.0.0
+4026.100.68.0.0
Functions:
~ ___43-[ATMessageLinkProxy messageLinkWasOpened:]_block_invoke : 404 -> 400
~ ___48-[ATMessageLinkProxy messageLinkWasInitialized:]_block_invoke : 404 -> 400
~ ___43-[ATMessageLinkProxy messageLinkWasClosed:]_block_invoke : 412 -> 408
~ _ATGetLibrarianDocumentUsage : 1048 -> 1044
~ +[ATSession sessionsWithSessionTypeIdentifier:] : 684 -> 680
~ +[ATSession sessionsWithSessionTypeIdentifier:dataClass:] : 380 -> 376
~ +[ATSession activeSessionCountWithSessionTypeIdentifier:] : 548 -> 544
~ ___19-[ATSession cancel]_block_invoke : 440 -> 436
~ ___26-[ATSession setSuspended:]_block_invoke.26 : 336 -> 332
~ ___29-[ATSession addSessionTasks:]_block_invoke : 592 -> 588
~ ___41-[ATSession sessionTasksWithGroupingKey:]_block_invoke : 372 -> 368
~ -[ATSession debugDescription] : 420 -> 416
~ -[ATSession initWithCoder:] : 948 -> 944
~ -[ATSession encodeWithCoder:] : 704 -> 700
~ ___31-[ATSession updateSessionTask:]_block_invoke : 760 -> 756
~ -[ATSession _observeKeysForTask:] : 296 -> 292
~ -[ATSession _stopObservingKeysForTask:] : 308 -> 304
~ -[ATSession _beginTasks:] : 440 -> 436
~ -[ATSession _performSelectorOnObservers:object:] : 408 -> 404
~ -[ATSession _performSelectorOnObservers:object:object:] : 448 -> 444
~ -[ATSession _finishWithError:] : 304 -> 328
~ -[ATServiceProxy service:willOpenMessageLink:completion:] : 312 -> 308
~ -[ATServiceProxy service:willOpenMessageLink:] : 276 -> 272
~ +[ATAsset assetsWithDownloadStateFromAssets:] : 332 -> 328
~ -[ATAsset _variantDescription] : 536 -> 532
~ -[ATRemoteFileManager uploadFilesAtPaths:options:results:error:] : 492 -> 488
~ -[ATRemoteFileManager downloadFilesAtPaths:options:results:error:] : 536 -> 532
~ -[ATRemoteFileManager moveItemsAtPaths:options:results:error:] : 568 -> 564
~ -[ATRemoteFileManager removeItemsAtPaths:options:results:error:] : 628 -> 624
~ ___38-[ATService messageLinkForIdentifier:]_block_invoke : 316 -> 312
~ -[ATXPCServer _doingWork] : 256 -> 252
~ -[ATXPCMessage _createXPCMessage] : 344 -> 336
~ -[ATAirlock createAirlockForDataclasses:] : 424 -> 420
~ -[ATAirlock evacuateDataclasses:] : 764 -> 760
~ -[ATAirlock copyAssetToAirlock:] : 1348 -> 1344
```
