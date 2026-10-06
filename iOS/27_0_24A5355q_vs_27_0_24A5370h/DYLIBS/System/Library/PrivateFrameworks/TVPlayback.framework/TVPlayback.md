## TVPlayback

> `/System/Library/PrivateFrameworks/TVPlayback.framework/TVPlayback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68460` | `0x682e0` | **`-0x180`** |
| `__TEXT.__oslogstring` | `0x6cd4` | `0x6d43` | **`+0x6f`** |
| `__TEXT.__gcc_except_tab` | `0x1fe4` | `0x1f9c` | **`-0x48`** |
| `__TEXT.__cstring` | `0x6aae` | `0x6ad0` | **`+0x22`** |
| `__TEXT.__unwind_info` | `0x16e0` | `0x16c0` | **`-0x20`** |
| `__DATA.__bss` | `0xa8` | `0xb0` | **`+0x8`** |

### Other Changes

```diff

-631.0.0.0.0
+634.0.0.0.0

-  Symbols:   4201
-  CStrings:  1433
+  Symbols:   4199
+  CStrings:  1435
Symbols:
+ _sPeriodicObserverQueue
- GCC_except_table233
- GCC_except_table235
- GCC_except_table239
Functions:
~ -[TVPStateMachine(Private) _executePostTransitionBlocks] : 328 -> 324
~ -[TVPInterstitialCollection timeAdjustedByRemovingInterstitials:] : 444 -> 440
~ -[TVPInterstitialCollection timeAdjustedByIncludingInterstitials:] : 380 -> 376
~ -[TVPInterstitialCollection interstitialForTime:] : 324 -> 320
~ -[TVPInterstitialCollection mergedInterstitialForTime:] : 324 -> 320
~ +[NSString(TVPlaybackAdditions) tvp_hexStringWithBytes:length:lowercase:] : 216 -> 228
~ -[AVAsset(TVPAdditions) tvp_maximumVideoRange] : 320 -> 316
~ -[TVPChapterCollection chapterForTime:] : 324 -> 320
~ -[TVPChapterCollection nearestChapterForTime:] : 496 -> 492
~ -[TVPChapterCollection chapterForDate:] : 340 -> 336
~ -[TVPChapterCollection nearestChapterForDate:] : 540 -> 536
~ -[TVPPlaybackReportingEventCollection rtcReportingEventDict] : 5268 -> 5256
~ -[TVPPlaybackReportingEventCollection startupEventsDict] : 1092 -> 1088
~ +[TVPPlaybackReportingEventCollection _totalTimeSpentDoingFPSFetchesFromEndEvents:] : 712 -> 708
~ +[TVPTimeRange forwardmostCMTimeRangeInCMTimeRanges:] : 648 -> 644
~ +[TVPStateMachine stateMachinesOfType:] : 348 -> 344
~ -[TVPStateMachine registerHandlerForEvent:onStates:withBlock:] : 324 -> 320
~ -[TVPStateMachine registerHandlerForEvents:onStates:withBlock:] : 476 -> 472
~ -[TVPStateMachine logUnhandledEvents] : 1192 -> 1180
~ -[TVPSecureKeyStandardLoader setHoldKeyResponses:] : 608 -> 604
~ ___45-[TVPStoreFPSKeyLoader loadSecureKeyRequest:]_block_invoke_2 : 1392 -> 1388
~ -[TVPStoreFPSKeyLoader _failPendingKeyRequestsWithError:] : 460 -> 456
~ -[TVPExternalImagePlayer _loadImagesIfNecessary] : 1064 -> 1060
~ -[TVPDownload _addMediaSelectionOptionsIfNotAlreadyAdded:toMediaSelections:forMediaSelectionGroup:baseMediaSelection:] : 540 -> 536
~ -[TVPDownload _audibleInterstitialDownloadCriteriaForPreferredAudioLanguages:includeOriginalAudio:audioDescriptionsEnabled:] : 888 -> 884
~ -[TVPDownload _legibleInterstitialDownloadCriteriaForSubtitleLanguages:includeSDH:] : 756 -> 752
~ ___44-[TVPDownload _registerStateMachineHandlers]_block_invoke_2.195 : 7712 -> 7668
~ -[AVMediaSelection(TVPAdditions) tvp_description] : 492 -> 488
~ +[TVPVideoView preserveVideoViewForReuse:identifier:] : 556 -> 552
~ +[TVPVideoView preservedVideoViewsForPlayer:identifier:] : 376 -> 372
~ +[TVPVideoView _purgePreservedVideoViewsForPlayer:] : 460 -> 456
~ ___23+[TVPPlayer initialize]_block_invoke : 200 -> 232
~ -[TVPPlayer setInteractive:] : 404 -> 400
~ -[TVPPlayer addBoundaryTimeObserverForTimes:withHandler:] : 848 -> 844
~ -[TVPPlayer removeBoundaryTimeObserverWithToken:] : 700 -> 696
~ -[TVPPlayer _updateSynchronizationForAVQueuePlayer:synchronizationIdentifier:] : 808 -> 804
~ -[TVPPlayer setCurrentChapterCollection:] : 780 -> 776
~ -[TVPPlayer skipToNextChapterInDirection:] : 656 -> 652
~ -[TVPPlayer setCurrentInterstitialCollection:] : 808 -> 804
~ -[TVPPlayer audioOptions] : 420 -> 416
~ -[TVPPlayer selectedAudioOption] : 544 -> 540
~ -[TVPPlayer subtitleOptions] : 648 -> 644
~ -[TVPPlayer setMaximumBitRate:] : 284 -> 280
~ -[TVPPlayer hasInterstitials] : 320 -> 316
~ -[TVPPlayer _selectMediaArray:withItem:] : 460 -> 456
~ -[TVPPlayer currentMediaItemLoader] : 344 -> 340
~ -[TVPPlayer setPreferredForwardBufferDuration:] : 296 -> 292
~ -[TVPPlayer setPreferredMaximumResolution:] : 300 -> 296
~ -[TVPPlayer setReportingValueWithString:forKey:] : 492 -> 488
~ -[TVPPlayer setReportingValueWithNumber:forKey:] : 492 -> 488
~ -[TVPPlayer setPreferredMaximumResolutionForExpensiveNetworks:] : 300 -> 296
~ -[TVPPlayer setAllowsCellularUsage:] : 264 -> 260
~ -[TVPPlayer setAllowsConstrainedNetworkUsage:] : 264 -> 260
~ -[TVPPlayer _addPeriodicTimeObserverToIntegratedTimeline:] : 604 -> 572
~ ___58-[TVPPlayer _addPeriodicTimeObserverToIntegratedTimeline:]_block_invoke : 176 -> 164
~ ___58-[TVPPlayer _addPeriodicTimeObserverToIntegratedTimeline:]_block_invoke_3 : 160 -> 144
~ -[TVPPlayer _addHighFrequencyTimeObserverIfNecessary] : 468 -> 452
~ ___53-[TVPPlayer _addHighFrequencyTimeObserverIfNecessary]_block_invoke : 176 -> 164
~ -[TVPPlayer _addBoundaryTimeObserversToIntegratedTimeline:] : 1440 -> 1436
~ -[TVPPlayer _addCustomTimelineBoundaryTimeObserversWithSnapshot:] : 1736 -> 1732
~ -[TVPPlayer _removeBoundaryTimeObserversFromIntegratedTimeline:] : 448 -> 444
~ -[TVPPlayer _removeCustomTimelineBoundaryTimeObservers] : 716 -> 712
~ -[TVPPlayer _updateCustomTimelineBoundaryObserversDueToCurrentSegmentChange:] : 1836 -> 1824
~ -[TVPPlayer _avPlayer:timeControlStatusDidChangeTo:oldStatusNum:] : 1232 -> 1360
~ -[TVPPlayer _currentPlayerItemTracksDidChangeTo:from:] : 668 -> 664
~ -[TVPPlayer _playerItemMediaSelectionDidChange:] : 1792 -> 1788
~ -[TVPPlayer _currentMediaItemMetadataDidChange:] : 1432 -> 1424
~ -[TVPPlayer _notifyListenersOfElapsedTimeChange:playbackDate:dueToTimeJump:] : 692 -> 688
~ -[TVPPlayer _notifyOfBoundaryCrossingBetweenPreviousTime:updatedTime:] : 724 -> 720
~ -[TVPPlayer _videoTrackIDFromTracks:] : 396 -> 392
~ -[TVPPlayer _configureSoundCheckForPlayerItem:tracks:] : 624 -> 620
~ -[TVPPlayer _assetTracksOfType:fromTracks:] : 408 -> 404
~ -[TVPPlayer _updateCurrentMediaItemAudioInfoForPlayerItem:tracks:] : 720 -> 716
~ ___66-[TVPPlayer _updateCurrentMediaItemAudioInfoForPlayerItem:tracks:]_block_invoke_2 : 672 -> 668
~ -[TVPPlayer _updateCurrentMediaItemVideoRangeForTracks:] : 700 -> 696
~ ___56-[TVPPlayer _updateCurrentMediaItemVideoRangeForTracks:]_block_invoke_2 : 612 -> 608
~ ___42-[TVPPlayer _registerStateMachineHandlers]_block_invoke_3.789 -> ___42-[TVPPlayer _registerStateMachineHandlers]_block_invoke_3.790 : 4316 -> 4312
~ ___42-[TVPPlayer _registerStateMachineHandlers]_block_invoke_3.839 -> ___42-[TVPPlayer _registerStateMachineHandlers]_block_invoke_3.840 : 736 -> 732
~ ___42-[TVPPlayer _registerStateMachineHandlers]_block_invoke_4.846 -> ___42-[TVPPlayer _registerStateMachineHandlers]_block_invoke_4.847 : 1380 -> 1376
~ ___42-[TVPPlayer _registerStateMachineHandlers]_block_invoke_6.848 -> ___42-[TVPPlayer _registerStateMachineHandlers]_block_invoke_6.849 : 300 -> 296
~ ___42-[TVPPlayer _registerStateMachineHandlers]_block_invoke.854 -> ___42-[TVPPlayer _registerStateMachineHandlers]_block_invoke.855 : 2000 -> 1996
~ ___42-[TVPPlayer _registerStateMachineHandlers]_block_invoke.934 -> ___42-[TVPPlayer _registerStateMachineHandlers]_block_invoke.935 : 1812 -> 1804
~ ___58-[TVPDownloadSession initializeWithDownloadingMediaItems:]_block_invoke_5 : 1792 -> 1780
~ -[AVAsset(TVPAudioSubtitleAdditions) tvp_sortedSubtitleAVMediaSelectionOptions] : 924 -> 920
~ ___79-[AVAsset(TVPAudioSubtitleAdditions) tvp_sortedSubtitleAVMediaSelectionOptions]_block_invoke_2 : 400 -> 396
~ +[AVAsset(ATVAudioSubtitleAdditionsPrivate) tvp_groupedAudioAVMediaSelectionOptionsFromOptions:] : 536 -> 532
~ +[AVAsset(ATVAudioSubtitleAdditionsPrivate) tvp_filteredAndSubsortedMainProgramSubtitleOptionsFromOptions:] : 620 -> 616
~ -[NSArray(TVPlaybackAdditions) tvp_shallowIsEqualToArray:] : 500 -> 496
~ -[TVPSecureKeyDeliveryCoordinator secureKeyLoader:didLoadCertificateData:forRequest:] : 836 -> 832
~ -[TVPSecureKeyDeliveryCoordinator secureKeyLoader:didFailWithError:forRequest:] : 1116 -> 1112
~ +[TVPMediaItemLoader loaderForMediaItem:] : 556 -> 552
~ +[TVPMediaItemLoader loaderForPlayerItem:] : 476 -> 472
~ ___51-[TVPMediaItemLoader _registerStateMachineHandlers]_block_invoke_2.136 : 1980 -> 1976
~ ___51-[TVPMediaItemLoader _registerStateMachineHandlers]_block_invoke_2.178 : 740 -> 736
~ ___51-[TVPMediaItemLoader _registerStateMachineHandlers]_block_invoke_6 : 880 -> 876
~ ___51-[TVPMediaItemLoader _registerStateMachineHandlers]_block_invoke_8 : 576 -> 572
~ -[TVPMediaItemLoader _needToLoadBlockingMetadataKeys] : 700 -> 696
~ -[TVPMediaItemLoader _contentKeyRequestParamsFromBase64String:] : 1152 -> 1148
~ ___58-[TVPMediaItemLoader _loadMediaItemMetadataAsynchronously]_block_invoke_2 : 660 -> 656
~ ___58-[TVPMediaItemLoader _loadMediaItemMetadataAsynchronously]_block_invoke.516 : 3176 -> 3172
~ ___58-[TVPMediaItemLoader _loadMediaItemMetadataAsynchronously]_block_invoke.525 : 1812 -> 1808
~ -[TVPContentKeySession fetchOfflineKeysForParams:completion:] : 484 -> 480
~ ___61-[TVPContentKeySession fetchOfflineKeysForParams:completion:]_block_invoke : 848 -> 844
~ -[TVPContentKeySession _generateOfflineKeyRequestsForIdentifiers:isRenewal:completion:] : 576 -> 572
~ -[TVPContentKeySession _loadAVContentKeyRequests:type:isRenewal:] : 480 -> 476
CStrings:
+ "Main player resumed before interstitial player paused; synthesizing paused event for preroll->feature boundary"
+ "TVPPlayer periodic observer queue"
```
