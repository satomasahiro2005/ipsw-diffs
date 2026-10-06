## SharingUI

> `/System/Library/PrivateFrameworks/SharingUI.framework/SharingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaad30` | `0xaac5c` | **`-0xd4`** |
| `__TEXT.__unwind_info` | `0x1ba0` | `0x1bb0` | **`+0x10`** |

### Other Changes

```diff

-2118.10.4.2.3
+2122.10.2.2.1
Functions:
~ _SFUILinkMetadataSerializationForLocalLowFidelityUseOnly : 320 -> 316
~ -[SFUILoadedMetadataCollection _listenForMetadataChanges] : 540 -> 536
~ -[SFUILoadedMetadataCollection _load] : 616 -> 612
~ ___SFUILinkMetadataSerializationForLocalUseOnly_block_invoke : 320 -> 316
~ __ZN13CMOQuaternion15northAndGravityE8CMVectorIfLm3EES1_S1_PKfRS_R8CMMatrixIfLm3ELm3EE : 2052 -> 2016
~ __ZmlIfLm3ELm3ELm3EE8CMMatrixIT_XT0_EXT1_EERKS0_IS1_XT0_EXT2_EERKS0_IS1_XT2_EXT1_EE : 136 -> 116
~ -[SFAppContent initWithAdamIDs:] : 528 -> 524
~ -[SFAppContent _amsFetchArtworkIfNeeded] : 892 -> 880
~ -[SFAirDropMagicHeadViewController updateNodes:withPersonToProgress:] : 1056 -> 1052
~ _SFPlaybackTimeRangesFromFeaturesTimeURL : 524 -> 520
~ -[SFMediaPlayerView stop] : 512 -> 508
~ -[SFMediaPlayerView removeAllQueuedItems] : 268 -> 264
~ -[SFMediaPlayerView breakFirstEnqueuedLoop] : 400 -> 396
~ -[SFMediaPlayerView enqueueItemsFromMediaItem:afterItem:] : 736 -> 732
~ -[SFMediaPlayerView dequeueNonPlayingItemsFromMediaItem:] : 620 -> 616
~ -[SFMediaPlayerView observeValueForKeyPath:ofObject:change:context:] : 864 -> 860
~ -[SFMediaPlayerView setUpTimeRangeNotificationsForItem:] : 956 -> 952
~ ___43-[SFMediaPlayerView playerItemDidReachEnd:]_block_invoke : 492 -> 488
~ -[SFUIImageProvider deliverImage:identifier:placeholder:error:] : 708 -> 704
~ -[SFCollectionViewLayout prepareLayout] : 600 -> 596
~ -[SFCollectionViewLayout initialLayoutAttributesForAppearingItemAtIndexPath:] : 460 -> 456
~ -[SFCollectionViewLayout finalLayoutAttributesForDisappearingItemAtIndexPath:] : 464 -> 460
~ -[SFCAPackageView stateController:transitionDidStop:completed:] : 440 -> 436
~ -[SFAirDropActivityViewController invalidate] : 396 -> 392
~ +[SFAirDropActivityViewController airDropActivityCanPerformActivityWithItemClasses:] : 1244 -> 1232
~ -[SFAirDropActivityViewController unsubscribeToProgresses] : 324 -> 320
~ -[SFAirDropActivityViewController subscribedProgress:forPersonWithRealName:] : 428 -> 424
~ -[SFAirDropActivityViewController unpublishedProgressForPersonWithRealName:] : 512 -> 508
~ ___59-[SFAirDropActivityViewController setSharedItemsAvailable:]_block_invoke : 416 -> 412
~ -[SFAirDropActivityViewController startTransferForPeople:] : 1560 -> 1556
~ -[SFAirDropActivityViewController isValidPayload:toPerson:invalidMessage:] : 1952 -> 1944
~ -[SFAirDropActivityViewController handleOtherItemProvider:withDataType:attachmentName:description:previewImage:] : 1540 -> 1536
~ -[SFAirDropActivityViewController generateSpecialPreviewPhotoForRequestID:] : 916 -> 908
~ -[SFAirDropActivityViewController _collectTelemetryForPeople:] : 380 -> 376
~ -[SFPersonCollectionViewCell addObserverOfValuesForKeyPaths:ofObject:] : 288 -> 284
~ -[SFPersonCollectionViewCell removeObserverOfValuesForKeyPaths:ofObject:] : 280 -> 276
~ -[SFPersonCollectionViewCell triggerKVOForKeyPaths:ofObject:] : 288 -> 284
~ -[SFMagicHead addObserverOfValuesForKeyPaths:ofObject:] : 288 -> 284
~ -[SFMagicHead removeObserverOfValuesForKeyPaths:ofObject:] : 280 -> 276
~ -[SFMagicHead triggerKVOForKeyPaths:ofObject:] : 288 -> 284
~ -[SFShareAudioBringCloseViewController _cycleProductImage] : 964 -> 960
~ sub_1c51dd254 -> sub_1c59c7168 : 500 -> 484
~ sub_1c51e6328 -> sub_1c59d022c : 444 -> 488
~ sub_1c521eb2c -> sub_1c5a08a5c : 488 -> 484
```
