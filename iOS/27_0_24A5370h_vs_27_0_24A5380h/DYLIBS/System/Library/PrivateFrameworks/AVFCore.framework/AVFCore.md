## AVFCore

> `/System/Library/PrivateFrameworks/AVFCore.framework/AVFCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21a69c` | `0x21d068` | **`+0x29cc`** |
| `__AUTH.__objc_data` | `0x7e20` | `0x8d48` | **`+0xf28`** |
| `__DATA_DIRTY.__objc_data` | `0x3700` | `0x2828` | **`-0xed8`** |
| `__TEXT.__oslogstring` | `0x2051a` | `0x20ab9` | **`+0x59f`** |
| `__AUTH_CONST.__objc_const` | `0x32070` | `0x32598` | **`+0x528`** |
| `__TEXT.__cstring` | `0x34f13` | `0x35323` | **`+0x410`** |
| `__TEXT.__objc_methlist` | `0x1bca4` | `0x1bed4` | **`+0x230`** |
| `__TEXT.__gcc_except_tab` | `0xb1a8` | `0xb348` | **`+0x1a0`** |
| `__DATA_CONST.__objc_selrefs` | `0xb408` | `0xb528` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0x1a880` | `0x1a920` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0xa610` | `0xa6a8` | **`+0x98`** |
| `__DATA.__bss` | `0x1460` | `0x13d0` | **`-0x90`** |
| `__DATA_DIRTY.__bss` | `0x189` | `0x211` | **`+0x88`** |
| `__DATA_CONST.__got` | `0x47a8` | `0x4820` | **`+0x78`** |
| `__DATA.__objc_ivar` | `0x2758` | `0x27bc` | **`+0x64`** |
| `__DATA.__data` | `0x183c` | `0x189c` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x5b18` | `0x5b58` | **`+0x40`** |
| `__DATA_DIRTY.__common` | `0x2b0` | `0x2e0` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x2060` | `0x2070` | **`+0x10`** |
| `__DATA.__common` | `0x460` | `0x450` | **`-0x10`** |
| `__AUTH.__data` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1210` | `0x1218` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xd48` | `0xd50` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-2450.63.2.0.0
+2450.67.3.0.0

+  - /usr/lib/libAccessibility.dylib

-  Functions: 12510
-  Symbols:   23761
-  CStrings:  6464
+  Functions: 12570
+  Symbols:   23860
+  CStrings:  6500
Symbols:
+ +[AVAssetWritingPlannerTrackSegmentState fromDictionary:mediaType:error:]
+ +[AVSystemMuteObserver initialize]
+ -[AVAssetTrackPlan requiresCompression]
+ -[AVAssetTrackPlanExecutor aspFrequency]
+ -[AVAssetTrackPlanExecutor callWritingSegmentCallbackForTrack:mediaType:mediaSubType:segmentOverlapDuration:segmentFlushDuration:segmentState:isFirstSegment:isLastSegment:initialClientState:finalClientState:initialCompressionSessionState:finalCompressionSessionState:progress:error:]
+ -[AVAssetTrackPlanExecutor mediaSubType]
+ -[AVAssetTrackPlanExecutor requiresCompression]
+ -[AVAssetTrackPlanExecutor segmentFlushDuration]
+ -[AVAssetTrackPlanExecutor segmentOverlapDuration]
+ -[AVAssetTrackPlanExecutor trackPlan]
+ -[AVAssetVideoTrackPlan requiresCompression]
+ -[AVAssetVideoTrackPlan videoCodec]
+ -[AVAssetWritingPlannerIncrementalState allSegmentsCompleted]
+ -[AVAssetWritingPlannerIncrementalState setAllSegmentsCompleted:]
+ -[AVAssetWritingPlannerTrackSegmentState flushDuration]
+ -[AVAssetWritingPlannerTrackSegmentState mediaType]
+ -[AVAssetWritingPlannerTrackSegmentState overlapDuration]
+ -[AVAssetWritingPlannerTrackSegmentState requiresCompression]
+ -[AVAssetWritingPlannerTrackSegmentState setFlushDuration:]
+ -[AVAssetWritingPlannerTrackSegmentState setMediaType:]
+ -[AVAssetWritingPlannerTrackSegmentState setOverlapDuration:]
+ -[AVAssetWritingPlannerTrackSegmentState setRequiresCompression:]
+ -[AVAssetWritingPlannerTrackState audioCodecType]
+ -[AVAssetWritingPlannerTrackState loudnessMeasurementCompleted]
+ -[AVAssetWritingPlannerTrackState measuredLoudnessMagicCookie]
+ -[AVAssetWritingPlannerTrackState requiresCompression]
+ -[AVAssetWritingPlannerTrackState setAudioCodecType:]
+ -[AVAssetWritingPlannerTrackState setLoudnessMeasurementCompleted:]
+ -[AVAssetWritingPlannerTrackState setMeasuredLoudnessMagicCookie:]
+ -[AVAssetWritingPlannerTrackState setRequiresCompression:]
+ -[AVPlayer _maximumAVPlayerLayerDisplaySize_invokeOnMainQueue]
+ -[AVPlayer(AVPlayerLegibleFallback) _updateCaptionAppearanceDisplayTypeOverride]
+ -[AVPlayer(AVPlayerLegibleFallback) endUserTurnedOffSubtitles]
+ -[AVPlayer(AVPlayerLegibleFallback) isOverridingCaptionDisplayTypeWhileMuted]
+ -[AVPlayer(AVPlayerSystemMute) _isEffectivelyMuted]
+ -[AVPlayer(AVPlayerSystemMute) systemMuteDidChange:]
+ -[AVPlayerLayer _displaySize_invokeOnMainQueue]
+ -[AVPlayerLayer _percentCoverageRelativeToRootLayer_invokeOnMainQueue]
+ -[AVSampleBufferVideoRenderer(AVSampleBufferVideoRendererForUnitTests) _unitTest_simulateLostDecoderState]
+ -[AVSystemMuteObserver .cxx_destruct]
+ -[AVSystemMuteObserver _evaluate]
+ -[AVSystemMuteObserver _notifyDelegateOfChange]
+ -[AVSystemMuteObserver _refreshCachedCaptionsOnMutePreferenceEnabled]
+ -[AVSystemMuteObserver _startObservingAccessibility]
+ -[AVSystemMuteObserver _startObservingOnIPhoneFamily]
+ -[AVSystemMuteObserver _stopObservingOnIPhoneFamily]
+ -[AVSystemMuteObserver dealloc]
+ -[AVSystemMuteObserver delegate]
+ -[AVSystemMuteObserver init]
+ -[AVSystemMuteObserver isCaptionsOnMutePreferenceEnabled]
+ -[AVSystemMuteObserver isSystemMuted]
+ -[AVSystemMuteObserver setDelegate:]
+ -[AVSystemMuteObserver startObservingWithDelegate:]
+ -[AVSystemMuteObserver stopObserving]
+ GCC_except_table137
+ GCC_except_table146
+ GCC_except_table154
+ GCC_except_table389
+ GCC_except_table403
+ GCC_except_table405
+ GCC_except_table413
+ GCC_except_table430
+ GCC_except_table452
+ GCC_except_table454
+ GCC_except_table461
+ GCC_except_table464
+ GCC_except_table466
+ GCC_except_table468
+ GCC_except_table470
+ GCC_except_table482
+ GCC_except_table496
+ GCC_except_table502
+ GCC_except_table519
+ GCC_except_table559
+ GCC_except_table567
+ GCC_except_table574
+ GCC_except_table578
+ GCC_except_table598
+ GCC_except_table605
+ GCC_except_table610
+ GCC_except_table614
+ GCC_except_table616
+ GCC_except_table620
+ GCC_except_table633
+ GCC_except_table635
+ GCC_except_table639
+ GCC_except_table641
+ GCC_except_table647
+ GCC_except_table653
+ GCC_except_table656
+ GCC_except_table669
+ GCC_except_table673
+ GCC_except_table675
+ GCC_except_table679
+ GCC_except_table686
+ GCC_except_table700
+ GCC_except_table705
+ GCC_except_table707
+ GCC_except_table709
+ GCC_except_table713
+ GCC_except_table721
+ GCC_except_table723
+ GCC_except_table725
+ GCC_except_table741
+ GCC_except_table742
+ GCC_except_table746
+ GCC_except_table754
+ GCC_except_table760
+ GCC_except_table776
+ GCC_except_table782
+ GCC_except_table789
+ GCC_except_table796
+ GCC_except_table801
+ GCC_except_table803
+ GCC_except_table809
+ GCC_except_table824
+ GCC_except_table825
+ GCC_except_table833
+ GCC_except_table836
+ GCC_except_table837
+ GCC_except_table841
+ GCC_except_table876
+ GCC_except_table878
+ GCC_except_table880
+ _AVSystemController_CurrentRouteHasVolumeControlDidChangeNotification
+ _AVSystemController_ServerConnectionDiedNotification
+ _AVSystemController_SubscribeToNotificationsAttribute
+ _AVSystemController_SystemVolumeDidChangeNotification
+ _OBJC_CLASS_$_AVSystemMuteObserver
+ _OBJC_IVAR_$_AVAssetTrackPlanExecutor._aspFrequency
+ _OBJC_IVAR_$_AVAssetTrackPlanExecutor._segmentFlushDuration
+ _OBJC_IVAR_$_AVAssetTrackPlanExecutor._segmentOverlapDuration
+ _OBJC_IVAR_$_AVAssetWritingPlannerIncrementalState._allSegmentsCompleted
+ _OBJC_IVAR_$_AVAssetWritingPlannerProgress._apacTrackIDs
+ _OBJC_IVAR_$_AVAssetWritingPlannerProgress._loudnessCompletedTrackIDs
+ _OBJC_IVAR_$_AVAssetWritingPlannerTrackSegmentState._flushDuration
+ _OBJC_IVAR_$_AVAssetWritingPlannerTrackSegmentState._mediaType
+ _OBJC_IVAR_$_AVAssetWritingPlannerTrackSegmentState._overlapDuration
+ _OBJC_IVAR_$_AVAssetWritingPlannerTrackSegmentState._requiresCompression
+ _OBJC_IVAR_$_AVAssetWritingPlannerTrackState._audioCodecType
+ _OBJC_IVAR_$_AVAssetWritingPlannerTrackState._loudnessMeasurementCompleted
+ _OBJC_IVAR_$_AVAssetWritingPlannerTrackState._measuredLoudnessMagicCookie
+ _OBJC_IVAR_$_AVAssetWritingPlannerTrackState._requiresCompression
+ _OBJC_IVAR_$_AVPlayerInternal.lastCaptionAppearanceDisplayTypeOverride
+ _OBJC_IVAR_$_AVPlayerInternal.muteOverrideSuppressedUntilUnmute
+ _OBJC_IVAR_$_AVPlayerInternal.systemMute
+ _OBJC_IVAR_$_AVSampleBufferDisplayLayer._initFailureError
+ _OBJC_IVAR_$_AVSystemMuteObserver._avSystemController
+ _OBJC_IVAR_$_AVSystemMuteObserver._avSystemControllerRouteToken
+ _OBJC_IVAR_$_AVSystemMuteObserver._avSystemControllerServerDiedToken
+ _OBJC_IVAR_$_AVSystemMuteObserver._avSystemControllerVolumeToken
+ _OBJC_IVAR_$_AVSystemMuteObserver._cachedCaptionsOnMutePreferenceEnabled
+ _OBJC_IVAR_$_AVSystemMuteObserver._captionsOnMutePreferenceNotifyToken
+ _OBJC_IVAR_$_AVSystemMuteObserver._delegate
+ _OBJC_IVAR_$_AVSystemMuteObserver._observing
+ _OBJC_IVAR_$_AVSystemMuteObserver._serialQueue
+ _OBJC_IVAR_$_AVSystemMuteObserver._systemMuted
+ _OBJC_METACLASS_$_AVSystemMuteObserver
+ __AVSystemMuteObserverRemoveAndReleaseNotificationToken
+ __AXSAutomaticSubtitlesShowWhenMuted
+ __OBJC_$_CLASS_METHODS_AVPlayer(AVPlayerVideoDisplaySleepPrevention|AVPlayerAllowsCaptureOfClearKeyVideo|AVPlayerAutomaticBackgroundPrevention|AVPlayerProtectedContentPrivate|AVPlayer_PIPSupport|AVPlayerAudioPlaybackRateLimits|AVPlayerMultitaskSupport|AVPlayerSupportForMediaPlayer|AVPlayerPixelBufferPoolSharing|AVPlayerFormatRestrictions|AVPlayerAutomaticMediaSelection|AVPlayerAutomaticMediaSelectionPrivate|AVPlayerAudioDeviceSupport|AVPlayerOutOfBandTextTrackRendering|AVPlayerMultichannelAudioStrategy|AVPlayerCaptionStrategySelection|AVPlayerAudioSessionParticipant|AVPlayerVideoDecoderGPUSupport|AVPlayerLoggingIdentifier|AVPlayerAutoPauseOnRouteRemoval|AVPlayerImplicitInterruption|AVPlayerSTSLabel|AVPlayerPIPSupport|AVPlayerSystemMute|FigVideoTargetSupport|AVPlayerTaggedBufferOutputSupport|AVPlayerOutputSupport|AVPlayerInterstitialSupport_Internal|PlaybackCoordination|AVPlayerResourceArbitrationSupport|AVPlayerRoutingPlaybackArbitrationSupport|AVPlayerLegibleFallback|AVIntegrityChecking|AVPlayerAdvanceWithOverlap|AVPlayer_OverlapPlaybackConditions|AVPlayerSpeedRamp|AVPlayer_ForTestingOnly|AVPlayerLocalCoplayback|AVPlayerAudioSubmixTapping|AVPlayerObservation|AVPlayer_Observation)
+ __OBJC_$_CLASS_METHODS_AVSystemMuteObserver
+ __OBJC_$_INSTANCE_METHODS_AVPlayer(AVPlayerVideoDisplaySleepPrevention|AVPlayerAllowsCaptureOfClearKeyVideo|AVPlayerAutomaticBackgroundPrevention|AVPlayerProtectedContentPrivate|AVPlayer_PIPSupport|AVPlayerAudioPlaybackRateLimits|AVPlayerMultitaskSupport|AVPlayerSupportForMediaPlayer|AVPlayerPixelBufferPoolSharing|AVPlayerFormatRestrictions|AVPlayerAutomaticMediaSelection|AVPlayerAutomaticMediaSelectionPrivate|AVPlayerAudioDeviceSupport|AVPlayerOutOfBandTextTrackRendering|AVPlayerMultichannelAudioStrategy|AVPlayerCaptionStrategySelection|AVPlayerAudioSessionParticipant|AVPlayerVideoDecoderGPUSupport|AVPlayerLoggingIdentifier|AVPlayerAutoPauseOnRouteRemoval|AVPlayerImplicitInterruption|AVPlayerSTSLabel|AVPlayerPIPSupport|AVPlayerSystemMute|FigVideoTargetSupport|AVPlayerTaggedBufferOutputSupport|AVPlayerOutputSupport|AVPlayerInterstitialSupport_Internal|PlaybackCoordination|AVPlayerResourceArbitrationSupport|AVPlayerRoutingPlaybackArbitrationSupport|AVPlayerLegibleFallback|AVIntegrityChecking|AVPlayerAdvanceWithOverlap|AVPlayer_OverlapPlaybackConditions|AVPlayerSpeedRamp|AVPlayer_ForTestingOnly|AVPlayerLocalCoplayback|AVPlayerAudioSubmixTapping|AVPlayerObservation|AVPlayer_Observation)
+ __OBJC_$_INSTANCE_METHODS_AVSystemMuteObserver
+ __OBJC_$_INSTANCE_VARIABLES_AVSystemMuteObserver
+ __OBJC_$_PROP_LIST_AVSystemMuteObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVSystemMuteObserverDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AVSystemMuteObserverDelegate
+ __OBJC_$_PROTOCOL_REFS_AVSystemMuteObserverDelegate
+ __OBJC_CLASS_PROTOCOLS_$_AVPlayer(AVPlayerVideoDisplaySleepPrevention|AVPlayerAllowsCaptureOfClearKeyVideo|AVPlayerAutomaticBackgroundPrevention|AVPlayerProtectedContentPrivate|AVPlayer_PIPSupport|AVPlayerAudioPlaybackRateLimits|AVPlayerMultitaskSupport|AVPlayerSupportForMediaPlayer|AVPlayerPixelBufferPoolSharing|AVPlayerFormatRestrictions|AVPlayerAutomaticMediaSelection|AVPlayerAutomaticMediaSelectionPrivate|AVPlayerAudioDeviceSupport|AVPlayerOutOfBandTextTrackRendering|AVPlayerMultichannelAudioStrategy|AVPlayerCaptionStrategySelection|AVPlayerAudioSessionParticipant|AVPlayerVideoDecoderGPUSupport|AVPlayerLoggingIdentifier|AVPlayerAutoPauseOnRouteRemoval|AVPlayerImplicitInterruption|AVPlayerSTSLabel|AVPlayerPIPSupport|AVPlayerSystemMute|FigVideoTargetSupport|AVPlayerTaggedBufferOutputSupport|AVPlayerOutputSupport|AVPlayerInterstitialSupport_Internal|PlaybackCoordination|AVPlayerResourceArbitrationSupport|AVPlayerRoutingPlaybackArbitrationSupport|AVPlayerLegibleFallback|AVIntegrityChecking|AVPlayerAdvanceWithOverlap|AVPlayer_OverlapPlaybackConditions|AVPlayerSpeedRamp|AVPlayer_ForTestingOnly|AVPlayerLocalCoplayback|AVPlayerAudioSubmixTapping|AVPlayerObservation|AVPlayer_Observation)
+ __OBJC_CLASS_RO_$_AVSystemMuteObserver
+ __OBJC_LABEL_PROTOCOL_$_AVSystemMuteObserverDelegate
+ __OBJC_METACLASS_RO_$_AVSystemMuteObserver
+ __OBJC_PROTOCOL_$_AVSystemMuteObserverDelegate
+ ___283-[AVAssetTrackPlanExecutor callWritingSegmentCallbackForTrack:mediaType:mediaSubType:segmentOverlapDuration:segmentFlushDuration:segmentState:isFirstSegment:isLastSegment:initialClientState:finalClientState:initialCompressionSessionState:finalCompressionSessionState:progress:error:]_block_invoke
+ ___283-[AVAssetTrackPlanExecutor callWritingSegmentCallbackForTrack:mediaType:mediaSubType:segmentOverlapDuration:segmentFlushDuration:segmentState:isFirstSegment:isLastSegment:initialClientState:finalClientState:initialCompressionSessionState:finalCompressionSessionState:progress:error:]_block_invoke_2
+ ___30-[AVChapterMetadataItem value]_block_invoke
+ ___36-[AVChapterMetadataItem description]_block_invoke
+ ___37-[AVSystemMuteObserver stopObserving]_block_invoke
+ ___40-[AVChapterMetadataItem _takeValueFrom:]_block_invoke
+ ___51-[AVSystemMuteObserver startObservingWithDelegate:]_block_invoke
+ ___52-[AVSystemMuteObserver _startObservingAccessibility]_block_invoke
+ ___53-[AVSystemMuteObserver _startObservingOnIPhoneFamily]_block_invoke
+ ___62-[AVPlayer(AVPlayerLegibleFallback) endUserTurnedOffSubtitles]_block_invoke
+ ___77-[AVPlayer(AVPlayerLegibleFallback) isOverridingCaptionDisplayTypeWhileMuted]_block_invoke
+ ___80-[AVPlayer(AVPlayerLegibleFallback) _updateCaptionAppearanceDisplayTypeOverride]_block_invoke
+ ___80-[AVPlayer(AVPlayerLegibleFallback) _updateCaptionAppearanceDisplayTypeOverride]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e8_v12?0i8lw32l8
+ _gAVSystemMuteObserverTrace
+ _kAXSAutomaticSubtitlesShowWhenMutedEnabledNotification
+ _notify_register_dispatch
- +[AVAssetWritingPlannerTrackSegmentState fromDictionary:error:]
- -[AVAssetTrackPlan requiresVideoCompression]
- -[AVAssetTrackPlanExecutor callWritingSegmentCallbackForTrack:segmentState:isFirstSegment:isLastSegment:initialClientState:finalClientState:initialCompressionSessionState:finalCompressionSessionState:progress:error:]
- -[AVAssetTrackPlanExecutor requiresVideoCompression]
- -[AVAssetVideoTrackPlan requiresVideoCompression]
- -[AVAssetWritingPlannerTrackSegmentState requiresVideoCompression]
- -[AVAssetWritingPlannerTrackSegmentState setRequiresVideoCompression:]
- -[AVAssetWritingPlannerTrackState requiresVideoCompression]
- -[AVAssetWritingPlannerTrackState setRequiresVideoCompression:]
- -[AVPlayer _maximumAVPlayerLayerDisplaySize]
- -[AVPlayerLayer _displaySize]
- -[AVPlayerLayer _percentCoverageRelativeToRootLayer]
- GCC_except_table216
- GCC_except_table383
- GCC_except_table388
- GCC_except_table400
- GCC_except_table412
- GCC_except_table416
- GCC_except_table421
- GCC_except_table424
- GCC_except_table429
- GCC_except_table438
- GCC_except_table440
- GCC_except_table445
- GCC_except_table462
- GCC_except_table465
- GCC_except_table469
- GCC_except_table471
- GCC_except_table475
- GCC_except_table481
- GCC_except_table497
- GCC_except_table505
- GCC_except_table546
- GCC_except_table553
- GCC_except_table558
- GCC_except_table566
- GCC_except_table575
- GCC_except_table577
- GCC_except_table581
- GCC_except_table586
- GCC_except_table594
- GCC_except_table597
- GCC_except_table602
- GCC_except_table606
- GCC_except_table608
- GCC_except_table619
- GCC_except_table623
- GCC_except_table631
- GCC_except_table636
- GCC_except_table640
- GCC_except_table642
- GCC_except_table646
- GCC_except_table652
- GCC_except_table654
- GCC_except_table670
- GCC_except_table674
- GCC_except_table687
- GCC_except_table691
- GCC_except_table696
- GCC_except_table703
- GCC_except_table706
- GCC_except_table710
- GCC_except_table715
- GCC_except_table719
- GCC_except_table720
- GCC_except_table738
- GCC_except_table743
- GCC_except_table753
- GCC_except_table759
- GCC_except_table779
- GCC_except_table783
- GCC_except_table793
- GCC_except_table806
- GCC_except_table810
- GCC_except_table812
- GCC_except_table814
- GCC_except_table821
- GCC_except_table831
- GCC_except_table843
- GCC_except_table851
- GCC_except_table856
- GCC_except_table863
- GCC_except_table870
- _OBJC_IVAR_$_AVAssetWritingPlannerTrackSegmentState._requiresFrameCount
- _OBJC_IVAR_$_AVAssetWritingPlannerTrackSegmentState._requiresVideoCompression
- _OBJC_IVAR_$_AVAssetWritingPlannerTrackState._requiresVideoCompression
- __OBJC_$_CLASS_METHODS_AVPlayer(AVPlayerVideoDisplaySleepPrevention|AVPlayerAllowsCaptureOfClearKeyVideo|AVPlayerAutomaticBackgroundPrevention|AVPlayerProtectedContentPrivate|AVPlayer_PIPSupport|AVPlayerAudioPlaybackRateLimits|AVPlayerMultitaskSupport|AVPlayerSupportForMediaPlayer|AVPlayerPixelBufferPoolSharing|AVPlayerFormatRestrictions|AVPlayerAutomaticMediaSelection|AVPlayerAutomaticMediaSelectionPrivate|AVPlayerAudioDeviceSupport|AVPlayerOutOfBandTextTrackRendering|AVPlayerMultichannelAudioStrategy|AVPlayerCaptionStrategySelection|AVPlayerAudioSessionParticipant|AVPlayerVideoDecoderGPUSupport|AVPlayerLoggingIdentifier|AVPlayerAutoPauseOnRouteRemoval|AVPlayerImplicitInterruption|AVPlayerSTSLabel|AVPlayerPIPSupport|FigVideoTargetSupport|AVPlayerTaggedBufferOutputSupport|AVPlayerOutputSupport|AVPlayerInterstitialSupport_Internal|PlaybackCoordination|AVPlayerResourceArbitrationSupport|AVPlayerRoutingPlaybackArbitrationSupport|AVPlayerLegibleFallback|AVIntegrityChecking|AVPlayerAdvanceWithOverlap|AVPlayer_OverlapPlaybackConditions|AVPlayerSpeedRamp|AVPlayer_ForTestingOnly|AVPlayerLocalCoplayback|AVPlayerAudioSubmixTapping|AVPlayerObservation|AVPlayer_Observation)
- __OBJC_$_INSTANCE_METHODS_AVPlayer(AVPlayerVideoDisplaySleepPrevention|AVPlayerAllowsCaptureOfClearKeyVideo|AVPlayerAutomaticBackgroundPrevention|AVPlayerProtectedContentPrivate|AVPlayer_PIPSupport|AVPlayerAudioPlaybackRateLimits|AVPlayerMultitaskSupport|AVPlayerSupportForMediaPlayer|AVPlayerPixelBufferPoolSharing|AVPlayerFormatRestrictions|AVPlayerAutomaticMediaSelection|AVPlayerAutomaticMediaSelectionPrivate|AVPlayerAudioDeviceSupport|AVPlayerOutOfBandTextTrackRendering|AVPlayerMultichannelAudioStrategy|AVPlayerCaptionStrategySelection|AVPlayerAudioSessionParticipant|AVPlayerVideoDecoderGPUSupport|AVPlayerLoggingIdentifier|AVPlayerAutoPauseOnRouteRemoval|AVPlayerImplicitInterruption|AVPlayerSTSLabel|AVPlayerPIPSupport|FigVideoTargetSupport|AVPlayerTaggedBufferOutputSupport|AVPlayerOutputSupport|AVPlayerInterstitialSupport_Internal|PlaybackCoordination|AVPlayerResourceArbitrationSupport|AVPlayerRoutingPlaybackArbitrationSupport|AVPlayerLegibleFallback|AVIntegrityChecking|AVPlayerAdvanceWithOverlap|AVPlayer_OverlapPlaybackConditions|AVPlayerSpeedRamp|AVPlayer_ForTestingOnly|AVPlayerLocalCoplayback|AVPlayerAudioSubmixTapping|AVPlayerObservation|AVPlayer_Observation)
- __OBJC_CLASS_PROTOCOLS_$_AVPlayer(AVPlayerVideoDisplaySleepPrevention|AVPlayerAllowsCaptureOfClearKeyVideo|AVPlayerAutomaticBackgroundPrevention|AVPlayerProtectedContentPrivate|AVPlayer_PIPSupport|AVPlayerAudioPlaybackRateLimits|AVPlayerMultitaskSupport|AVPlayerSupportForMediaPlayer|AVPlayerPixelBufferPoolSharing|AVPlayerFormatRestrictions|AVPlayerAutomaticMediaSelection|AVPlayerAutomaticMediaSelectionPrivate|AVPlayerAudioDeviceSupport|AVPlayerOutOfBandTextTrackRendering|AVPlayerMultichannelAudioStrategy|AVPlayerCaptionStrategySelection|AVPlayerAudioSessionParticipant|AVPlayerVideoDecoderGPUSupport|AVPlayerLoggingIdentifier|AVPlayerAutoPauseOnRouteRemoval|AVPlayerImplicitInterruption|AVPlayerSTSLabel|AVPlayerPIPSupport|FigVideoTargetSupport|AVPlayerTaggedBufferOutputSupport|AVPlayerOutputSupport|AVPlayerInterstitialSupport_Internal|PlaybackCoordination|AVPlayerResourceArbitrationSupport|AVPlayerRoutingPlaybackArbitrationSupport|AVPlayerLegibleFallback|AVIntegrityChecking|AVPlayerAdvanceWithOverlap|AVPlayer_OverlapPlaybackConditions|AVPlayerSpeedRamp|AVPlayer_ForTestingOnly|AVPlayerLocalCoplayback|AVPlayerAudioSubmixTapping|AVPlayerObservation|AVPlayer_Observation)
- ___216-[AVAssetTrackPlanExecutor callWritingSegmentCallbackForTrack:segmentState:isFirstSegment:isLastSegment:initialClientState:finalClientState:initialCompressionSessionState:finalCompressionSessionState:progress:error:]_block_invoke
- ___216-[AVAssetTrackPlanExecutor callWritingSegmentCallbackForTrack:segmentState:isFirstSegment:isLastSegment:initialClientState:finalClientState:initialCompressionSessionState:finalCompressionSessionState:progress:error:]_block_invoke_2
- ___77-[AVPlayer(AVPlayerLegibleFallback) setCaptionAppearanceDisplayTypeOverride:]_block_invoke_2
CStrings:
+ "+[AVAssetWritingPlannerTrackSegmentState fromDictionary:mediaType:error:]"
+ "-[AVAssetTrackPlanExecutor callWritingSegmentCallbackForTrack:mediaType:mediaSubType:segmentOverlapDuration:segmentFlushDuration:segmentState:isFirstSegment:isLastSegment:initialClientState:finalClientState:initialCompressionSessionState:finalCompressionSessionState:progress:error:]"
+ "-[AVAssetWritingPlanner buildAssemblyComposition:]"
+ "-[AVPlayer(AVPlayerLegibleFallback) _updateCaptionAppearanceDisplayTypeOverride]"
+ "-[AVPlayer(AVPlayerLegibleFallback) endUserTurnedOffSubtitles]"
+ "-[AVPlayerLayer _displaySize_invokeOnMainQueue]"
+ "-[AVPlayerLayer _percentCoverageRelativeToRootLayer_invokeOnMainQueue]"
+ "-[AVSystemMuteObserver _evaluate]"
+ "-[AVSystemMuteObserver _refreshCachedCaptionsOnMutePreferenceEnabled]"
+ "-[AVSystemMuteObserver _startObservingAccessibility]"
+ "-[AVSystemMuteObserver _startObservingAccessibility]_block_invoke"
+ "-[AVSystemMuteObserver _startObservingOnIPhoneFamily]"
+ "-[AVSystemMuteObserver _startObservingOnIPhoneFamily]_block_invoke"
+ "<<<< AVAssetWritingPlanner >>>> %s: Failed to construct assemblyComposition"
+ "<<<< AVAssetWritingPlanner >>>> %s: Failed to load track from track segment output URL"
+ "<<<< AVAssetWritingPlanner >>>> %s: _requiresCompression (%d) from savedState does not match _requiresCompression (%d) from current state"
+ "<<<< AVAssetWritingPlanner >>>> %s: segment mediaType from saved state (%@) does not match current segment's mediaType (%@)"
+ "<<<< AVAssetWritingPlanner >>>> %s: segmentFileTimeRange %1.3f - %1.3f --> outputTrackTime %1.3f"
+ "<<<< AVAssetWritingPlanner >>>> %s: trackPlanExecutor %@"
+ "<<<< AVPlayer >>>> %s: <%{public}@|%p> cleared muteOverrideSuppressedUntilUnmute on unmute"
+ "<<<< AVPlayer >>>> %s: <%{public}@|%p> effectivelyMuted=%d playerMuted=%d captionsOnMuteEnabled=%d muteOverrideSuppressed=%d effectiveOverride=%ld"
+ "<<<< AVPlayer >>>> %s: <%{public}@|%p> endUserTurnedOffSubtitles; suppressing mute override until next mute"
+ "<<<< AVPlayerLayer >>>> %s: <%{public}@|%p> notifying player %p about new display size"
+ "<<<< AVSystemMuteObserver >>>> %s: AVSystemController unavailable; cannot observe system volume/mute. AVSystemController class=%p"
+ "<<<< AVSystemMuteObserver >>>> %s: Audio notification: %{public}@"
+ "<<<< AVSystemMuteObserver >>>> %s: cachedCaptionsOnMutePreferenceEnabled=%d"
+ "<<<< AVSystemMuteObserver >>>> %s: kAXSAutomaticSubtitlesShowWhenMutedEnabledNotification"
+ "<<<< AVSystemMuteObserver >>>> %s: mute status: AVSystemController=%s, (tvOS MASystemMute=%s), (macOS outputContext=%s, coreAudio=%s)"
+ "<<<< AVSystemMuteObserver >>>> %s: notify_register_dispatch failed for AX captions-on-mute pref (status=%u)"
+ "<<<< AVSystemMuteObserver >>>> %s: systemMuted changed -> %d"
+ "AllSegmentsCompleted"
+ "Audio/Video"
+ "AudioCodecType"
+ "AudioCodecType not found in dictionary"
+ "Media type is not supported.  Expect AVMediaTypeVideo or AVMediaTypeAuxiliaryPicture."
+ "NoSignal"
+ "NotMuted"
+ "RequiresCompression"
+ "RequiresCompression not found in dictionary"
+ "audioCodecType is not NSString"
+ "avsystemmuteobserver_trace"
+ "com.apple.avplayer.systemMuteObserver"
+ "requiresCompression not found from dictionary"
+ "requiresCompressionNumber is not NSNumber"
+ "segmentConfigurations must only contain AVPlannedSegmentConfiguration or AVPlannedVideoSegmentConfiguration objects"
+ "v12@?0i8"
- "+[AVAssetWritingPlannerTrackSegmentState fromDictionary:error:]"
- "-[AVAssetTrackPlanExecutor callWritingSegmentCallbackForTrack:segmentState:isFirstSegment:isLastSegment:initialClientState:finalClientState:initialCompressionSessionState:finalCompressionSessionState:progress:error:]"
- "-[AVPlayerLayer _displaySize]"
- "-[AVPlayerLayer _percentCoverageRelativeToRootLayer]"
- "<<<< AVAssetWritingPlanner >>>> %s: _requiresVideoCompression (%d) from savedState does not match _requiresVideoCompression (%d) from current state"
- "<<<< AVPlayerLayer >>>> %s: <%{public}@|%p> notifying player %p about new display size %@"
- "RequiresVideoCompression"
- "RequiresVideoCompression not found in dictionary"
- "requiresVideoCompression not found from dictionary"
- "requiresVideoCompressionNumber is not NSNumber"
```
