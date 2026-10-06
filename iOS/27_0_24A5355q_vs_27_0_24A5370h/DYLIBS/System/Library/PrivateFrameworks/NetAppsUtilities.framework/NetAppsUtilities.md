## NetAppsUtilities

> `/System/Library/PrivateFrameworks/NetAppsUtilities.framework/NetAppsUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a6cc` | `0x1a600` | **`-0xcc`** |

### Other Changes

```text
Functions:
~ -[NSArray(NAAdditions) na_map:] : 376 -> 372
~ -[NAFuture finishWithResult:error:] : 660 -> 656
~ -[NSArray(NAAdditions) na_dictionaryWithKeyGenerator:] : 380 -> 376
~ +[NADelegateDispatcher _findMethodSignatureForSelector:inProtocol:] : 260 -> 256
~ ___23-[NAFuture reschedule:]_block_invoke : 640 -> 636
~ -[NAFuture finishWithNoResult] : 632 -> 628
~ ___20-[NAFuture flatMap:]_block_invoke : 1064 -> 1060
~ ___36-[NAFuture completionHandlerAdapter]_block_invoke : 640 -> 636
~ -[NSArray(NAAdditions) na_dictionaryByBucketingObjectsUsingKeyGenerator:] : 400 -> 396
~ -[NSInvocation(NAAdditions) na_argumentDescriptionsWithObjectFormatter:] : 760 -> 748
~ -[NSInvocation(NAAdditions) na_argumentsAsObjects] : 1072 -> 1052
~ -[NSArray(NAAdditions) na_flatMap:] : 376 -> 372
~ -[NSSet(NAAdditions) na_flatMap:] : 388 -> 384
~ ___20-[NAFuture recover:]_block_invoke : 1068 -> 1064
~ -[NAIdentity hashOfObject:] : 400 -> 396
~ -[NAFuture finishWithResult:] : 624 -> 620
~ -[NAIdentity isObject:equalToObject:] : 512 -> 508
~ ___42-[NADelegateDispatcher forwardInvocation:]_block_invoke : 288 -> 284
~ -[NSSet(NAAdditions) na_dictionaryByBucketingObjectsUsingKeyGenerator:] : 400 -> 396
~ ___72-[NADelegateDispatcher _trampolineBlockForSelector:withMethodSignature:]_block_invoke_8 : 284 -> 280
~ ___72-[NADelegateDispatcher _trampolineBlockForSelector:withMethodSignature:]_block_invoke_4 : 280 -> 276
~ -[NAFuture cancel] : 604 -> 600
~ -[NACancelationToken callCancelationBlocks:] : 244 -> 240
~ ___72-[NADelegateDispatcher _trampolineBlockForSelector:withMethodSignature:]_block_invoke_6 : 284 -> 280
~ __NADictionaryOfMetrics : 432 -> 428
~ -[NSCountedSet(NAAdditions) na_mostCommonObject] : 328 -> 324
~ -[NAMutableTreeNode removeChildrenPassingTest:] : 324 -> 320
~ +[NAUniqueArrayDiff diffFromArray:toArray:options:] : 2588 -> 2560
~ -[NAUniqueArrayDiff enumerateMovesUsingBlock:] : 376 -> 372
~ -[NAValueThrottler _notifyObserversOfValueUpdate] : 288 -> 284
~ -[NAFuture finishWithError:] : 624 -> 620
~ ___45-[NAFuture errorOnlyCompletionHandlerAdapter]_block_invoke : 1092 -> 1084
~ -[NAPromise finishWithResult:] : 628 -> 624
~ -[NAPromise finishWithError:] : 628 -> 624
~ -[NAPromise finishWithResult:error:] : 664 -> 660
~ ___72-[NADelegateDispatcher _trampolineBlockForSelector:withMethodSignature:]_block_invoke_2 : 280 -> 276
~ ___72-[NADelegateDispatcher _trampolineBlockForSelector:withMethodSignature:]_block_invoke_10 : 288 -> 284
~ ___72-[NADelegateDispatcher _trampolineBlockForSelector:withMethodSignature:]_block_invoke_12 : 288 -> 284
~ ___72-[NADelegateDispatcher _trampolineBlockForSelector:withMethodSignature:]_block_invoke_14 : 292 -> 288
~ -[NSSet(NAAdditions) na_dictionaryWithKeyGenerator:] : 380 -> 376
~ -[NAGroupedItemDiff _briefDescriptionForOperations:type:] : 700 -> 696
~ -[NSIndexPath(NAAdditions) na_each:] : 180 -> 184
~ -[NADescriptionBuilder _activeComponentString] : 32 -> 28
~ -[NADescriptionBuilder appendSuper] : 552 -> 568
~ -[NADescriptionBuilder appendKeys:] : 320 -> 316
```
