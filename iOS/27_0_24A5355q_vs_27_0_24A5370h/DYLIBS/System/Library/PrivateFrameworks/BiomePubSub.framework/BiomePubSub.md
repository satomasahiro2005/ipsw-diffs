## BiomePubSub

> `/System/Library/PrivateFrameworks/BiomePubSub.framework/BiomePubSub`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4070c` | `0x405ec` | **`-0x120`** |

### Other Changes

```diff

-236.0.2.0.0
+239.0.2.0.0
Functions:
~ _BPSPipelineSupportsPullBasedPublishers : 468 -> 464
~ -[BMBookmarkablePublisher bookmarkNode] : 444 -> 440
~ +[BMBookmarkablePublisher bookmarkablePublishersFromPublishers:] : 336 -> 332
~ +[BMBookmarkablePublisher isPipelineBookmarkable:] : 372 -> 368
~ -[BPSPublisher reset] : 240 -> 236
~ -[BPSPublisher completed] : 260 -> 256
~ -[BPSPublisher startWithSubscriber:] : 312 -> 308
~ -[BPSApproxPercentileDigest mergeCentroids] : 1040 -> 1036
~ -[BPSApproxPercentileDigest proto] : 396 -> 392
~ -[_BPSCorrelateInner newBookmark] : 572 -> 568
~ -[BPSCountWindowAssigner assignWindow:input:] : 436 -> 432
~ -[BPSCountWindowAssigner updateAndReturnNewWindowStates:input:] : 684 -> 680
~ -[BPSBufferInner _drain] : 880 -> 868
~ -[BPSBufferInner newBookmark] : 552 -> 548
~ -[BPSMulticast nextEventForMulticastDownstream:] : 696 -> 692
~ -[BPSMulticast requestNextEvents] : 296 -> 292
~ -[_BPSMerged receiveCompletion:atIndex:] : 1744 -> 1732
~ -[_BPSMerged requestDemand:] : 2212 -> 2192
~ -[_BPSMerged cancel] : 696 -> 692
~ -[BPSPublisher didCompleteWithoutError:] : 268 -> 264
~ -[BPSApproximateDistinctCount approximateDistinctCount] : 200 -> 208
~ -[BPSApproximateDistinctCount countMapFull] : 92 -> 100
~ -[BPSApproximateDistinctCount printState] : 124 -> 120
~ -[BPSTumblingWindowAssigner assignWindow:input:] : 628 -> 624
~ -[BPSTumblingWindowAssigner updateAndReturnNewWindowStates:input:] : 888 -> 884
~ -[BPSPBApproxPercentileDigest writeTo:] : 440 -> 432
~ -[BPSOrderedMerge nextEvent] : 884 -> 880
~ -[_BPSFlatMapOuter receiveCompletion:] : 824 -> 820
~ -[_BPSFlatMapOuter requestDemand:] : 1524 -> 1516
~ -[_BPSFlatMapOuter cancel] : 412 -> 408
~ -[_BPSFlatMapOuter receiveInnerCompletion:index:] : 1040 -> 1036
~ -[BPSSessionWindowAssigner assignWindow:input:] : 788 -> 784
~ -[BPSSessionWindowAssigner updateAndReturnNewWindowStates:input:] : 1256 -> 1248
~ -[BPSHistogram _setKeyTypeFromKey:] : 352 -> 348
~ -[BPSHistogram allKeysAtLevel:] : 876 -> 868
~ -[BPSHistogram _enumerateWithBlock:node:currentKey:stop:] : 468 -> 464
~ -[BMBookmarkableSubscription newBookmark] : 536 -> 532
~ -[_BPSAbstractCombineLatest requestDemand:] : 460 -> 456
~ -[_BPSAbstractCombineLatest receiveInput:atIndex:] : 720 -> 716
~ -[_BPSAbstractCombineLatest cancel] : 524 -> 520
~ -[BPSSink _cancelPublisher:] : 304 -> 300
~ -[BPSDrivableSink _cancelPublisher:] : 304 -> 300
~ -[_BPSAbstractZip receiveSubscription:index:] : 672 -> 668
~ -[_BPSAbstractZip receiveInput:index:] : 1336 -> 1328
~ -[_BPSAbstractZip cancel] : 536 -> 532
~ -[_BPSAbstractZip resolvePendingDemandAndUnlock] : 376 -> 372
~ -[_BPSAbstractZip requestDemand:] : 472 -> 468
~ -[BPSZipMany _tryConstructResultArray] : 436 -> 432
~ -[BPSZipMany completed] : 256 -> 252
~ -[BPSPassThroughSubject dealloc] : 284 -> 280
~ -[BPSPassThroughSubject acknowledgeDownstreamDemand] : 392 -> 388
~ -[BPSPassThroughSubject sendValue:] : 360 -> 356
~ -[BPSPassThroughSubject sendCompletion:] : 396 -> 392
~ -[BPSPassThroughSubject cancel] : 352 -> 348
~ -[BPSReduceProducer newBookmark] : 552 -> 548
~ -[BPSSlidingWindowAssigner assignWindowOverlappingIntervals:timestamp:] : 908 -> 904
~ -[BPSSlidingWindowAssigner assignWindowNonOverlappingIntervals:timestamp:] : 644 -> 640
~ -[BPSSlidingWindowAssigner updateWindowStateOverlappingIntervals:timestamp:input:] : 1096 -> 1092
~ -[BPSSlidingWindowAssigner updateWindowStateNonOverlappingIntervals:timestamp:input:] : 884 -> 880
~ ___38-[BPSFuture initWithAttemptToFulfill:]_block_invoke : 472 -> 468
~ -[_BPSWindowerInner receiveCompletion:] : 1304 -> 1300
~ -[_BPSWindowerInner cancel] : 752 -> 744
~ -[_BPSWindowerInner upstreamSubscriptions] : 408 -> 404
~ -[BPSWindower updateWindowsWithEvent:] : 584 -> 580
```
