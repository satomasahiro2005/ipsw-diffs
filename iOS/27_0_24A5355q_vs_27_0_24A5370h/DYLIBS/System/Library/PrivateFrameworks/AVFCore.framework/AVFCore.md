## AVFCore

> `/System/Library/PrivateFrameworks/AVFCore.framework/AVFCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x219a78` | `0x21a69c` | **`+0xc24`** |
| `__TEXT.__oslogstring` | `0x20156` | `0x2051a` | **`+0x3c4`** |
| `__TEXT.__cstring` | `0x34ca3` | `0x34f13` | **`+0x270`** |
| `__AUTH_CONST.__cfstring` | `0x1a760` | `0x1a880` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0x31fe0` | `0x32070` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0xa588` | `0xa610` | **`+0x88`** |
| `__TEXT.__gcc_except_tab` | `0xb12c` | `0xb1a8` | **`+0x7c`** |
| `__DATA_CONST.__got` | `0x4778` | `0x47a8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1bc84` | `0x1bca4` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2050` | `0x2060` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2748` | `0x2758` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xb3f8` | `0xb408` | **`+0x10`** |

### Other Changes

```diff

-2450.58.1.0.0
+2450.63.2.0.0

-  Functions: 12506
-  Symbols:   23736
-  CStrings:  6443
+  Functions: 12510
+  Symbols:   23761
+  CStrings:  6464
Symbols:
+ +[AVPlannedVideoSegmentWritingRequest requestWithSegmentFileOutputURL:assemblyTrackID:timeRange:frameCount:clientState:outputSettings:expectedVideoCodecType:progress:finishBlock:]
+ +[AVTelemetryInterval reportInterval:durationMicroseconds:]
+ -[AVAssetDownloadLiveActivity _subtitleForCompleted:failed:willRetry:]
+ -[AVAssetDownloadLiveActivity _unsafeRouteTerminalForClientState:]
+ -[AVAssetDownloadLiveActivity _unsafeSchedulePendingFinalizeForClientState:]
+ -[AVAssetDownloadLiveActivity errorMayBeRetriedByBackgroundSession:]
+ -[AVAssetDownloadLiveActivity unregisterDownload:terminalStatus:error:]
+ -[AVAssetDownloadLiveActivityClientState setWillRetryDownloadIDs:]
+ -[AVAssetDownloadLiveActivityClientState willRetryDownloadIDs]
+ -[AVAssetDownloadSession isRetryAttempt]
+ -[AVAssetVideoTrackPlan encoderSpecification]
+ -[AVPlannedVideoSegmentWritingRequest initWithSegmentFileOutputURL:assemblyTrackID:timeRange:frameCount:clientState:resumableOutputSettings:expectedVideoCodecType:progress:finishBlock:]
+ -[AVPlayer _addFPListenersForFigPlayer:]
+ -[AVPlayer _addListenersToInterstitialCoordinator:]
+ -[AVPlayer _removeListenersFromInterstitialCoordinator:]
+ -[AVPlayerLayer _scheduleTimerToUpdateVisibilityOfInterstitialLayer:maskLayer:toShowInterstitial:atDispatchTime:atCAMediaTime:]
+ GCC_except_table100
+ GCC_except_table136
+ GCC_except_table440
+ GCC_except_table441
+ GCC_except_table445
+ GCC_except_table446
+ GCC_except_table463
+ GCC_except_table465
+ GCC_except_table469
+ GCC_except_table471
+ GCC_except_table475
+ GCC_except_table481
+ GCC_except_table497
+ GCC_except_table505
+ GCC_except_table511
+ GCC_except_table548
+ GCC_except_table553
+ GCC_except_table562
+ GCC_except_table566
+ GCC_except_table575
+ GCC_except_table577
+ GCC_except_table581
+ GCC_except_table586
+ GCC_except_table587
+ GCC_except_table595
+ GCC_except_table602
+ GCC_except_table608
+ GCC_except_table609
+ GCC_except_table619
+ GCC_except_table623
+ GCC_except_table632
+ GCC_except_table636
+ GCC_except_table640
+ GCC_except_table642
+ GCC_except_table646
+ GCC_except_table654
+ GCC_except_table670
+ GCC_except_table674
+ GCC_except_table685
+ GCC_except_table687
+ GCC_except_table691
+ GCC_except_table692
+ GCC_except_table697
+ GCC_except_table704
+ GCC_except_table706
+ GCC_except_table710
+ GCC_except_table720
+ GCC_except_table722
+ GCC_except_table731
+ GCC_except_table738
+ GCC_except_table743
+ GCC_except_table753
+ GCC_except_table759
+ GCC_except_table783
+ GCC_except_table786
+ GCC_except_table800
+ GCC_except_table812
+ GCC_except_table814
+ GCC_except_table821
+ GCC_except_table831
+ GCC_except_table843
+ GCC_except_table851
+ GCC_except_table856
+ GCC_except_table863
+ GCC_except_table870
+ _CFDictionaryContainsKey
+ _NSURLErrorBackgroundTaskCancelledReasonKey
+ _OBJC_IVAR_$_AVAssetDownloadLiveActivityClientState._willRetryDownloadIDs
+ _OBJC_IVAR_$_AVAssetDownloadSessionInternal.isRetryAttempt
+ _OBJC_IVAR_$_AVAssetTrackPlanExecutor._encoderSupportedProperties
+ _OBJC_IVAR_$_AVAssetVideoTrackPlan._encoderSpecification
+ _OBJC_IVAR_$_AVPlannedVideoSegmentWritingRequest._expectedVideoCodecType
+ _OBJC_IVAR_$_AVPlayerInternal.cachedHasCurrentInterstitialEvent
+ _OUTLINED_FUNCTION_137
+ _OUTLINED_FUNCTION_138
+ _OUTLINED_FUNCTION_139
+ _OUTLINED_FUNCTION_140
+ _OUTLINED_FUNCTION_141
+ _OUTLINED_FUNCTION_142
+ _VTCompressionSessionCopySupportedPropertyDictionary
+ __OBJC_$_CLASS_METHODS_AVTelemetryInterval
+ ___127-[AVPlayerLayer _scheduleTimerToUpdateVisibilityOfInterstitialLayer:maskLayer:toShowInterstitial:atDispatchTime:atCAMediaTime:]_block_invoke
+ ___127-[AVPlayerLayer _scheduleTimerToUpdateVisibilityOfInterstitialLayer:maskLayer:toShowInterstitial:atDispatchTime:atCAMediaTime:]_block_invoke_2
+ ___76-[AVAssetDownloadLiveActivity _unsafeSchedulePendingFinalizeForClientState:]_block_invoke
+ ___78-[AVPlayer(AVPlayerInterstitialSupport_Internal) _hasCurrentInterstitialEvent]_block_invoke
+ ___avplayer_fpInterstitialCoordinatorNotificationCallback_block_invoke
+ ___block_descriptor_73_e8_32o40o48o56w_e5_v8?0lw56l8s32l8s40l8s48l8
+ _avplayer_fpInterstitialCoordinatorNotificationCallback
+ _kCFErrorDomainCFNetwork
+ _kFigPlayerInterstitialNotification_CurrentEventChangeEventIDKey
+ _kVTCompressionPropertyKey_EnableResumableEncoding
+ _kVTCompressionPropertyKey_RecommendedResumableSegmentMinimumDuration
+ _kVTCompressionPropertyKey_RecommendedResumableSegmentMinimumFrameCount
- +[AVPlannedVideoSegmentWritingRequest requestWithSegmentFileOutputURL:assemblyTrackID:timeRange:frameCount:clientState:outputSettings:progress:finishBlock:]
- -[AVAssetDownloadLiveActivity _unsafeCommitDeferredFinalizeForClientState:]
- -[AVAssetDownloadLiveActivity _unsafeFailActivityForClientState:]
- -[AVAssetDownloadLiveActivity _unsafeSchedulePendingFinalizeForClientState:terminalStatus:]
- -[AVAssetDownloadLiveActivity unregisterDownload:terminalStatus:]
- -[AVAssetDownloadLiveActivityClientState pendingFinalizeDownloadID]
- -[AVAssetDownloadLiveActivityClientState pendingFinalizeStatus]
- -[AVAssetDownloadLiveActivityClientState setPendingFinalizeDownloadID:]
- -[AVAssetDownloadLiveActivityClientState setPendingFinalizeStatus:]
- -[AVAssetWriter isVirtualCaptureCardSupported]
- -[AVAssetWriter setUsesVirtualCaptureCard:]
- -[AVAssetWriter usesVirtualCaptureCard]
- -[AVPlannedVideoSegmentWritingRequest initWithSegmentFileOutputURL:assemblyTrackID:timeRange:frameCount:clientState:resumableOutputSettings:progress:finishBlock:]
- -[AVPlayer _addFPListeners]
- -[AVPlayerLayer _scheduleTimerToUpdateVisibilityOfInterstitialLayer:maskLayer:toShowInterstitial:atDispatchTime:]
- GCC_except_table110
- GCC_except_table158
- GCC_except_table188
- GCC_except_table435
- GCC_except_table437
- GCC_except_table443
- GCC_except_table448
- GCC_except_table457
- GCC_except_table464
- GCC_except_table466
- GCC_except_table468
- GCC_except_table470
- GCC_except_table478
- GCC_except_table482
- GCC_except_table502
- GCC_except_table503
- GCC_except_table508
- GCC_except_table543
- GCC_except_table551
- GCC_except_table559
- GCC_except_table570
- GCC_except_table574
- GCC_except_table578
- GCC_except_table584
- GCC_except_table605
- GCC_except_table610
- GCC_except_table612
- GCC_except_table616
- GCC_except_table620
- GCC_except_table621
- GCC_except_table633
- GCC_except_table635
- GCC_except_table639
- GCC_except_table651
- GCC_except_table665
- GCC_except_table667
- GCC_except_table669
- GCC_except_table675
- GCC_except_table677
- GCC_except_table700
- GCC_except_table701
- GCC_except_table705
- GCC_except_table707
- GCC_except_table716
- GCC_except_table721
- GCC_except_table725
- GCC_except_table735
- GCC_except_table740
- GCC_except_table750
- GCC_except_table754
- GCC_except_table765
- GCC_except_table774
- GCC_except_table777
- GCC_except_table782
- GCC_except_table789
- GCC_except_table796
- GCC_except_table818
- GCC_except_table823
- GCC_except_table839
- GCC_except_table847
- GCC_except_table852
- GCC_except_table857
- GCC_except_table864
- _OBJC_IVAR_$_AVAssetDownloadLiveActivityClientState._pendingFinalizeDownloadID
- _OBJC_IVAR_$_AVAssetDownloadLiveActivityClientState._pendingFinalizeStatus
- ___113-[AVPlayerLayer _scheduleTimerToUpdateVisibilityOfInterstitialLayer:maskLayer:toShowInterstitial:atDispatchTime:]_block_invoke
- ___113-[AVPlayerLayer _scheduleTimerToUpdateVisibilityOfInterstitialLayer:maskLayer:toShowInterstitial:atDispatchTime:]_block_invoke_2
- ___91-[AVAssetDownloadLiveActivity _unsafeSchedulePendingFinalizeForClientState:terminalStatus:]_block_invoke
- ___block_descriptor_65_e8_32o40o48o56w_e5_v8?0lw56l8s32l8s40l8s48l8
CStrings:
+ "-[AVActivityProgressClient postActivityEvent:forIdentifier:]"
+ "-[AVAssetDownloadLiveActivity _unsafeRouteTerminalForClientState:]"
+ "-[AVAssetDownloadLiveActivity unregisterDownload:terminalStatus:error:]"
+ "<<<< AVActivityProgressClient >>>> %s: Dropping endActivityForTaskID %s — ActivityProgressUI server unavailable; activity may remain on screen"
+ "<<<< AVActivityProgressClient >>>> %s: Dropping handleActivityEvent (event=%ld) for taskID %s — ActivityProgressUI server unavailable"
+ "<<<< AVActivityProgressClient >>>> %s: Dropping startProgressActivity for taskID %s bundleID '%s' — ActivityProgressUI server unavailable"
+ "<<<< AVActivityProgressClient >>>> %s: Dropping updateActivityName for taskID %s — ActivityProgressUI server unavailable"
+ "<<<< AVActivityProgressClient >>>> %s: Dropping updateProgress for taskID %s — ActivityProgressUI server unavailable"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: Cancelling cooldown hold for '%{public}@' to coalesce new download into existing activity"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: Cooldown elapsed for '%@' (cooldownMS=%lld); ending activity silently"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: FigAssetDownloaderCopyLiveActivityConfiguration failed (err=%d); using default cooldownMS=%lld"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: Holding activity for '%@' at 100%% for %lld ms before ending (%ld completed, %ld failed, %ld will-retry)"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: Live Activity configuration loaded: cooldownMS=%lld"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: Terminal completion for '%@' (%ld completed, %ld failed, %ld will-retry); ending"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: Terminal for '%@' with no tracked items; dismissing"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: Unreachable: progress update called with empty client state for '%@'"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: Updated progress for '%@': %lld/%lld (%ld active, %ld completed, %ld failed, %ld will-retry)"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: [%p] Skipping Live Activity for bundle '%{public}@' — download is marked discretionary"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: [%p] Skipping Live Activity for bundle '%{public}@' — retry attempt"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: [%p] Unregistering download (%@) for bundle '%{public}@' (terminalStatus=%ld, willRetry=%d)"
+ "<<<< AVAssetDownloadLiveActivity >>>> %s: [%p] Unregistering download for bundle '%@' (terminalStatus=%ld, willRetry=%d, error=%@ [%ld])"
+ "<<<< AVAssetDownloadSession >>>> %s: [%p] Unregistering download from Live Activity manager (terminalStatus=%ld, error=%@ [%ld])"
+ "<<<< AVPlayer >>>> %s: <%{public}@|%p> current interstitial event (cached): %@"
+ "<<<< AVPlayer >>>> %s: <%{public}@|%p> dispatched (inNotificationName = %@)"
+ "<<<< AVPlayer >>>> %s: <%{public}@|%p> setting hasCurrentInterstitialEvent=%d with id=%@"
+ "<<<< AVSampleBufferVideoRenderer >>>> %s: addSampleBufferDisplayLayer failed to set content layer with error %d"
+ "AVURLAssetDelayByteStreamReadAheadUntilExplicitlyHinted"
+ "AVURLAssetInhibitReferenceMovieResolution"
+ "COMPLETED_AND_WILL_RETRY_FORMAT"
+ "COMPLETED_FAILED_AND_WILL_RETRY_FORMAT"
+ "DVPEnhancements"
+ "FAILED_AND_WILL_RETRY_FORMAT"
+ "GENERATED_FORMAT"
+ "GENERATED_SPARKLE_FORMAT"
+ "ITEMS_COMPLETED_ALL_FORMAT"
+ "NO since one of the items is in a failed state"
+ "Video codec type mismatch: track plan specifies '%@' but client provided '%@'"
+ "WILL_RETRY_FORMAT"
+ "avplayer_fpInterstitialCoordinatorNotificationCallback"
+ "avplayer_fpInterstitialCoordinatorNotificationCallback_block_invoke"
+ "avplayer_fpInterstitialCoordinatorNotificationCallback_block_invoke_2"
+ "liveActivityCooldown100PercentMS"
- "-[AVAssetDownloadLiveActivity _unsafeFailActivityForClientState:]"
- "-[AVAssetDownloadLiveActivity unregisterDownload:terminalStatus:]"
- "<<<< AVAssetDownloadLiveActivity >>>> %s: All downloads complete for '%@', showing completion state"
- "<<<< AVAssetDownloadLiveActivity >>>> %s: Cancelling pending finalize for '%{public}@' to coalesce new download into existing activity"
- "<<<< AVAssetDownloadLiveActivity >>>> %s: Cooldown elapsed for '%@'; finalizing activity (terminalStatus=%ld, failed=%ld, completed=%ld)"
- "<<<< AVAssetDownloadLiveActivity >>>> %s: Downloads cancelled/stopped for '%@', dismissing immediately"
- "<<<< AVAssetDownloadLiveActivity >>>> %s: Downloads finished for '%@' with %ld failed, %ld completed - showing failure state"
- "<<<< AVAssetDownloadLiveActivity >>>> %s: Failing activity %@ for '%{public}@' (%ld failed, %ld completed)"
- "<<<< AVAssetDownloadLiveActivity >>>> %s: Holding activity for '%@' open for %lld ms (deferred terminalStatus=%ld)"
- "<<<< AVAssetDownloadLiveActivity >>>> %s: Live Activity configuration loaded: cooldownMS=%lld (err=%d)"
- "<<<< AVAssetDownloadLiveActivity >>>> %s: Updated progress for '%@': %lld/%lld (%ld active, %ld completed, %ld failed)"
- "<<<< AVAssetDownloadLiveActivity >>>> %s: [%p] Skipping Live Activity for bundle '%{public}@' — download is marked discretionary (background/opportunistic; intentionally hidden from the user)"
- "<<<< AVAssetDownloadLiveActivity >>>> %s: [%p] Unregistering download (%@) for bundle '%{public}@' (terminalStatus=%ld)"
- "<<<< AVAssetDownloadLiveActivity >>>> %s: [%p] Unregistering download for bundle '%@' (terminalStatus=%ld)"
- "<<<< AVAssetDownloadSession >>>> %s: [%p] Unregistering download from Live Activity manager (terminalStatus=%ld)"
- "<<<< AVPlayer >>>> %s: <%{public}@|%p> NULL FigPlayerInterstitialCoordinator"
- "<<<< AVPlayer >>>> %s: <%{public}@|%p> current event %@ %f"
- "<<<< AVPlayer >>>> %s: <%{public}@|%p> current interstitial event %@"
- "DOWNLOADING_ONE_ITEM"
- "addSampleBufferDisplayLayer failed to set content layer"
- "liveActivityCooldownMS"
```
