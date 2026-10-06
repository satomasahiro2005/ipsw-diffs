## Catalyst

> `/System/Library/PrivateFrameworks/Catalyst.framework/Catalyst`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5f2b8` | `0x5f238` | **`-0x80`** |

### Other Changes

```text
Functions:
~ -[CATArbitrator resourcesForKeys:exclusive:] : 760 -> 756
~ -[CATArbitrator waitForResourcesForKeys:exclusive:delegateQueue:completionBlock:] : 548 -> 544
~ -[CATBatchRemoteTaskOperation initWithTaskClient:requests:] : 376 -> 372
~ -[CATBatchRemoteTaskOperation main] : 444 -> 440
~ -[CATCollectionController initWithObjects:] : 312 -> 308
~ -[CATCollectionController unbindContent] : 328 -> 324
~ -[CATCollectionController addObserversToObject:forKeyPaths:] : 288 -> 284
~ -[CATCollectionController removeObserversFromObject:forKeyPaths:] : 272 -> 268
~ ___63-[CATCollectionController newIndexForObject:inArrangedObjects:]_block_invoke : 452 -> 448
~ ___49-[CATCollectionController rearrangeTimerDidFire:]_block_invoke : 252 -> 248
~ ___87-[CATCollectionController updateKeysAffectingArrangementForceUpdate:includeAllContent:]_block_invoke : 612 -> 604
~ -[CATCollectionController notifyArrangedObjectsWillChange] : 772 -> 764
~ -[CATCollectionController notifyArrangedObjectsDidChangeWithPreviousArrangedObjects:] : 744 -> 736
~ -[CATCollectionController changeObject:atIndex:forChangeType:newIndex:] : 268 -> 264
~ -[CATIDSServiceConnectionInvitationInbox dealloc] : 276 -> 272
~ _CATFormattedStringForKey : 392 -> 388
~ -[CATOperation start] : 572 -> 568
~ ___41-[_CATObserverManager operationDidStart:]_block_invoke : 336 -> 332
~ -[_CATObserverManager notifyObserversOperationDidProgress:] : 328 -> 324
~ ___42-[_CATObserverManager operationDidFinish:]_block_invoke : 412 -> 408
~ -[CATOperationQueue addOperations:waitUntilFinished:] : 400 -> 392
~ +[CATProperty propertiesForClass:] : 484 -> 480
~ +[CATProperty propertiesForProtocol:] : 472 -> 468
~ -[CATRemoteConnection close] : 676 -> 672
~ -[CATRemoteConnection connectionDidInterruptWithError:] : 404 -> 400
~ -[CATRemoteTransport connection:didInterruptWithError:] : 324 -> 320
~ -[CATRemoteTransport connectionDidClose:] : 332 -> 328
~ -[CATSendSerialIDSMessagesOperation sendMessages] : 696 -> 692
~ -[CATTaskBlockServer cancelLongRunningOperationsForRequestClass:] : 304 -> 300
~ -[CATTaskClient resumeWithTaskUUIDs:] : 648 -> 640
~ -[CATIDSServiceConnectionTerminal processMessage:senderAppleID:senderAddress:] : 616 -> 612
~ ___51-[CATTaskServer postNotificationWithName:userInfo:]_block_invoke : 252 -> 248
~ -[NSArray(CATAdditions) cat_map:] : 384 -> 380
~ -[NSArray(CATAdditions) cat_forEach:] : 272 -> 268
~ -[NSArray(CATAdditions) cat_flatMapUsingBlock:] : 532 -> 528
~ -[CATTaskSession clearQueuedMessagesAndCancelAllOperationsWithError:] : 384 -> 380
~ -[CATTaskSession sendResumedMessage] : 416 -> 412
~ ___55+[NSDate(CATInternetDateAndTime) cat_RFC3339Formatters]_block_invoke : 388 -> 384
~ +[NSDate(CATInternetDateAndTime) cat_dateWithInternetTimeString:] : 324 -> 320
~ __CATErrorDescriptionsWithCodeAndUserInfo : 2084 -> 2076
~ +[NSNetService(CATTXTRecord) cat_dictionaryFromData:] : 904 -> 900
~ -[NSOperation(CATOperation) cat_addDependencies:] : 244 -> 240
~ sub_250cfc78c -> sub_251fd46cc : 252 -> 256
~ sub_250cfd0c0 -> sub_251fd5004 : 1056 -> 1104
~ sub_250d02d94 -> sub_251fdad08 : 632 -> 636
~ sub_250d03520 -> sub_251fdb498 : 504 -> 508
~ sub_250d0bfd8 -> sub_251fe3f54 : 1216 -> 1212
~ sub_250d0c498 -> sub_251fe4410 : 2292 -> 2296
~ sub_250d0d690 -> sub_251fe560c : 480 -> 484
~ sub_250d0d9ac -> sub_251fe592c : 300 -> 304
~ sub_250d0dd7c -> sub_251fe5d00 : 252 -> 256
~ sub_250d0df60 -> sub_251fe5ee8 : 300 -> 304
~ sub_250d0f5e4 -> sub_251fe7570 : 1892 -> 1880
~ sub_250d131dc -> sub_251feb15c : 380 -> 376
~ sub_250d1352c -> sub_251feb4a8 : 364 -> 360
~ ___swift_closure_destructor : 500 -> 504
~ sub_250d1388c -> sub_251feb808 : 428 -> 432
```
