## MediaPlaybackCore

> `/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/MediaPlaybackCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x489b60` | `0x4913e0` | **`+0x7880`** |
| `__TEXT.__oslogstring` | `0x4aa29` | `0x4b1af` | **`+0x786`** |
| `__TEXT.__unwind_info` | `0xd518` | `0xdb38` | **`+0x620`** |
| `__TEXT.__eh_frame` | `0xf5c8` | `0xfab4` | **`+0x4ec`** |
| `__AUTH_CONST.__const` | `0x22b00` | `0x22f10` | **`+0x410`** |
| `__TEXT.__cstring` | `0x25077` | `0x25313` | **`+0x29c`** |
| `__TEXT.__const` | `0x103b8` | `0x105d8` | **`+0x220`** |
| `__AUTH_CONST.__objc_const` | `0x343c0` | `0x34558` | **`+0x198`** |
| `__TEXT.__gcc_except_tab` | `0x5648` | `0x57c8` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x9168` | `0x9290` | **`+0x128`** |
| `__TEXT.__swift5_capture` | `0xa9e0` | `0xab00` | **`+0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0xc9c0` | `0xcaa0` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x17cd8` | `0x17db8` | **`+0xe0`** |
| `__TEXT.__swift5_reflstr` | `0x5842` | `0x5912` | **`+0xd0`** |
| `__AUTH.__objc_data` | `0x5c70` | `0x5bb0` | **`-0xc0`** |
| `__AUTH_CONST.__cfstring` | `0x1e700` | `0x1e7c0` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x5554` | `0x5614` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x5332` | `0x53ba` | **`+0x88`** |
| `__AUTH_CONST.__auth_got` | `0x33d0` | `0x3430` | **`+0x60`** |
| `__AUTH_CONST.__objc_intobj` | `0x7f8` | `0x840` | **`+0x48`** |
| `__DATA_DIRTY.__data` | `0x4588` | `0x4548` | **`-0x40`** |
| `__TEXT.__constg_swiftt` | `0x79e8` | `0x7a24` | **`+0x3c`** |
| `__DATA_CONST.__got` | `0x3378` | `0x33b0` | **`+0x38`** |
| `__DATA.__data` | `0x72e0` | `0x72b0` | **`-0x30`** |
| `__DATA.__objc_ivar` | `0x1a80` | `0x1ab0` | **`+0x30`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x270` | `0x288` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x280` | `0x298` | **`+0x18`** |
| `__AUTH.__data` | `0x3f80` | `0x3f90` | **`+0x10`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x60` | `0x70` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x800` | `0x7f0` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0xdc4` | `0xdd4` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x59c` | `0x5ac` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x554` | `0x560` | **`+0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0x3a8` | `0x3a0` | **`-0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x33e0` | `0x33e8` | **`+0x8`** |

### Other Changes

```diff

-26100.26.21.301.0
+26100.26.24.301.0

-  Functions: 24021
-  Symbols:   18522
-  CStrings:  8139
+  Functions: 24182
+  Symbols:   18605
+  CStrings:  8175
Symbols:
+ -[MPCAssistantCommandInternal _resolveSupportedInsertionPosition:forPlayerPath:queue:completion:]
+ -[MPCAssistantCommandInternal insertPlaybackQueueWithResult:atPosition:onDestination:withOptions:completion:]
+ -[MPCAssistantSendCommand _applyOptionsResolverIfNeededForCommand:options:playerPath:completion:]
+ -[MPCAssistantSendCommand optionsResolver]
+ -[MPCAssistantSendCommand setOptionsResolver:]
+ -[MPCContentKeyDeliveryScheduler .cxx_destruct]
+ -[MPCContentKeyDeliveryScheduler _attachTimebaseObservers_lockedForItem:]
+ -[MPCContentKeyDeliveryScheduler _currentItemPositionSec]
+ -[MPCContentKeyDeliveryScheduler _detachTimebaseObservers_locked]
+ -[MPCContentKeyDeliveryScheduler _dispatchFire_locked:reason:expectedGeneration:delay:]
+ -[MPCContentKeyDeliveryScheduler _fireTask:reason:expectedGeneration:]
+ -[MPCContentKeyDeliveryScheduler _handleStateChanged:]
+ -[MPCContentKeyDeliveryScheduler _reevaluateAllPending_locked]
+ -[MPCContentKeyDeliveryScheduler _reevaluateTask_locked:]
+ -[MPCContentKeyDeliveryScheduler currentItem]
+ -[MPCContentKeyDeliveryScheduler dealloc]
+ -[MPCContentKeyDeliveryScheduler flushPendingTasks]
+ -[MPCContentKeyDeliveryScheduler init]
+ -[MPCContentKeyDeliveryScheduler scheduleKeyDeliveryBlock:forKey:jitterTime:timeout:]
+ -[MPCContentKeyDeliveryScheduler setCurrentItem:]
+ -[MPCModelGenericAVItem _finishDeferredLeaseAcquisitionWithCompletionHandler:]
+ -[MPCModelGenericAVItem musicContentKeySession]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) contentKeyDeliveryScheduler]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) keyDeliveryJitterTime]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) sharedKeySegmentDuration]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) shouldPerformKeyDeliveryRequestForKey:isPrefetchKey:isPersistable:isRenewal:completionHandler:]
+ -[MPCPlaybackEngine(MusicContentKeySession) contentKeySession:didFinishProcessingKey:withResponse:error:]
+ -[MPCPlaybackEngine(MusicContentKeySession) contentKeySession:didStartProcessingKey:isPrefetchKey:isPersistable:isRenewal:]
+ -[MPCPlaybackEngine(MusicContentKeySession) contentKeySession:shouldPerformKeyDeliveryRequestForKey:isPrefetchKey:isPersistable:isRenewal:completionHandler:]
+ -[_MPCKeyDeliveryTask .cxx_destruct]
+ -[_MPCKeyDeliveryTask block]
+ -[_MPCKeyDeliveryTask claimed]
+ -[_MPCKeyDeliveryTask description]
+ -[_MPCKeyDeliveryTask generation]
+ -[_MPCKeyDeliveryTask identifier]
+ -[_MPCKeyDeliveryTask jitterTime]
+ -[_MPCKeyDeliveryTask setBlock:]
+ -[_MPCKeyDeliveryTask setClaimed:]
+ -[_MPCKeyDeliveryTask setGeneration:]
+ -[_MPCKeyDeliveryTask setIdentifier:]
+ -[_MPCKeyDeliveryTask setJitterTime:]
+ -[_MPCKeyDeliveryTask setSignpostWaitToFireID:]
+ -[_MPCKeyDeliveryTask setSignpostWaitToScheduleID:]
+ -[_MPCKeyDeliveryTask setTargetItemTime:]
+ -[_MPCKeyDeliveryTask setWaitToFireBegun:]
+ -[_MPCKeyDeliveryTask setWaitToScheduleEnded:]
+ -[_MPCKeyDeliveryTask signpostWaitToFireID]
+ -[_MPCKeyDeliveryTask signpostWaitToScheduleID]
+ -[_MPCKeyDeliveryTask targetItemTime]
+ -[_MPCKeyDeliveryTask waitToFireBegun]
+ -[_MPCKeyDeliveryTask waitToScheduleEnded]
+ -[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy refreshAccount]
+ -[_MPCModelStorePlaybackItemsRequestAccumulator_Modern refreshAccount]
+ -[_MPCPlaybackEnginePlayer contentKeyDeliveryScheduler]
+ -[_MPCPlaybackEnginePlayer didPerformPlayerOperationWithPlayerIdentifier:items:operation:error:]
+ GCC_except_table117
+ GCC_except_table1184
+ GCC_except_table1188
+ GCC_except_table1190
+ GCC_except_table1358
+ GCC_except_table1360
+ GCC_except_table1407
+ GCC_except_table1418
+ GCC_except_table1425
+ GCC_except_table1432
+ GCC_except_table1481
+ GCC_except_table1490
+ GCC_except_table1533
+ GCC_except_table1706
+ GCC_except_table1708
+ GCC_except_table1721
+ GCC_except_table1726
+ GCC_except_table1796
+ GCC_except_table1878
+ GCC_except_table1879
+ GCC_except_table194
+ GCC_except_table1990
+ GCC_except_table2010
+ GCC_except_table2012
+ GCC_except_table2040
+ GCC_except_table2054
+ GCC_except_table2056
+ GCC_except_table2059
+ GCC_except_table2080
+ GCC_except_table2195
+ GCC_except_table2246
+ GCC_except_table2250
+ GCC_except_table2253
+ GCC_except_table2302
+ GCC_except_table2334
+ GCC_except_table24
+ GCC_except_table2414
+ GCC_except_table2601
+ GCC_except_table2629
+ GCC_except_table2656
+ GCC_except_table2799
+ GCC_except_table2827
+ GCC_except_table2828
+ GCC_except_table2853
+ GCC_except_table2855
+ GCC_except_table2860
+ GCC_except_table2864
+ GCC_except_table2866
+ GCC_except_table2868
+ GCC_except_table2870
+ GCC_except_table2873
+ GCC_except_table2899
+ GCC_except_table2906
+ GCC_except_table2911
+ GCC_except_table2913
+ GCC_except_table2917
+ GCC_except_table2922
+ GCC_except_table2923
+ GCC_except_table2928
+ GCC_except_table2934
+ GCC_except_table2954
+ GCC_except_table2962
+ GCC_except_table3005
+ GCC_except_table3091
+ GCC_except_table3095
+ GCC_except_table3106
+ GCC_except_table3107
+ GCC_except_table3131
+ GCC_except_table3139
+ GCC_except_table3180
+ GCC_except_table3181
+ GCC_except_table3197
+ GCC_except_table3254
+ GCC_except_table3279
+ GCC_except_table3321
+ GCC_except_table3323
+ GCC_except_table3330
+ GCC_except_table3341
+ GCC_except_table3345
+ GCC_except_table3383
+ GCC_except_table3428
+ GCC_except_table3433
+ GCC_except_table348
+ GCC_except_table350
+ GCC_except_table3561
+ GCC_except_table3582
+ GCC_except_table3589
+ GCC_except_table3614
+ GCC_except_table3618
+ GCC_except_table3628
+ GCC_except_table3685
+ GCC_except_table3690
+ GCC_except_table3694
+ GCC_except_table3764
+ GCC_except_table3861
+ GCC_except_table3865
+ GCC_except_table3876
+ GCC_except_table3892
+ GCC_except_table3898
+ GCC_except_table3907
+ GCC_except_table396
+ GCC_except_table4036
+ GCC_except_table404
+ GCC_except_table4080
+ GCC_except_table4081
+ GCC_except_table4082
+ GCC_except_table41
+ GCC_except_table4102
+ GCC_except_table412
+ GCC_except_table4129
+ GCC_except_table4136
+ GCC_except_table4150
+ GCC_except_table4173
+ GCC_except_table4184
+ GCC_except_table421
+ GCC_except_table4273
+ GCC_except_table4292
+ GCC_except_table4305
+ GCC_except_table4316
+ GCC_except_table4347
+ GCC_except_table4518
+ GCC_except_table4519
+ GCC_except_table4698
+ GCC_except_table4732
+ GCC_except_table4750
+ GCC_except_table4765
+ GCC_except_table4773
+ GCC_except_table4781
+ GCC_except_table4791
+ GCC_except_table4806
+ GCC_except_table4850
+ GCC_except_table4865
+ GCC_except_table4881
+ GCC_except_table4884
+ GCC_except_table4890
+ GCC_except_table49
+ GCC_except_table4942
+ GCC_except_table4978
+ GCC_except_table504
+ GCC_except_table5061
+ GCC_except_table5162
+ GCC_except_table520
+ GCC_except_table521
+ GCC_except_table537
+ GCC_except_table538
+ GCC_except_table5401
+ GCC_except_table5402
+ GCC_except_table5478
+ GCC_except_table5568
+ GCC_except_table5719
+ GCC_except_table5744
+ GCC_except_table5861
+ GCC_except_table5942
+ GCC_except_table5950
+ GCC_except_table5951
+ GCC_except_table6015
+ GCC_except_table6040
+ GCC_except_table6075
+ GCC_except_table6078
+ GCC_except_table6081
+ GCC_except_table6167
+ GCC_except_table6384
+ GCC_except_table6401
+ GCC_except_table6449
+ GCC_except_table6462
+ GCC_except_table6974
+ GCC_except_table7308
+ GCC_except_table7318
+ GCC_except_table7411
+ GCC_except_table7420
+ GCC_except_table7502
+ GCC_except_table7509
+ GCC_except_table7527
+ GCC_except_table7578
+ GCC_except_table7579
+ GCC_except_table7582
+ GCC_except_table7587
+ GCC_except_table7603
+ GCC_except_table789
+ GCC_except_table845
+ GCC_except_table921
+ GCC_except_table955
+ GCC_except_table957
+ GCC_except_table962
+ GCC_except_table964
+ GCC_except_table977
+ GCC_except_table981
+ GCC_except_table987
+ GCC_except_table991
+ GCC_except_table994
+ GCC_except_table997
+ _MPCPlaybackEngineEventPayloadKeyPlayerOperationError
+ _OBJC_CLASS_$_AVPlayerItemSampleBufferOutputAudioConfiguration
+ _OBJC_CLASS_$_MPCContentKeyDeliveryScheduler
+ _OBJC_CLASS_$_MSVTrialExperiment
+ _OBJC_CLASS_$__MPCKeyDeliveryTask
+ _OBJC_IVAR_$_MPCAssistantSendCommand._optionsResolver
+ _OBJC_IVAR_$_MPCContentKeyDeliveryScheduler._currentItem
+ _OBJC_IVAR_$_MPCContentKeyDeliveryScheduler._effectiveRateObserver
+ _OBJC_IVAR_$_MPCContentKeyDeliveryScheduler._lock
+ _OBJC_IVAR_$_MPCContentKeyDeliveryScheduler._observedTimebase
+ _OBJC_IVAR_$_MPCContentKeyDeliveryScheduler._pending
+ _OBJC_IVAR_$_MPCContentKeyDeliveryScheduler._queue
+ _OBJC_IVAR_$_MPCContentKeyDeliveryScheduler._randState
+ _OBJC_IVAR_$_MPCContentKeyDeliveryScheduler._timeJumpedObserver
+ _OBJC_IVAR_$_MPCModelGenericAVItem._hasPendingDeferredLeaseAcquisition
+ _OBJC_IVAR_$__MPCKeyDeliveryTask._block
+ _OBJC_IVAR_$__MPCKeyDeliveryTask._claimed
+ _OBJC_IVAR_$__MPCKeyDeliveryTask._generation
+ _OBJC_IVAR_$__MPCKeyDeliveryTask._identifier
+ _OBJC_IVAR_$__MPCKeyDeliveryTask._jitterTime
+ _OBJC_IVAR_$__MPCKeyDeliveryTask._signpostWaitToFireID
+ _OBJC_IVAR_$__MPCKeyDeliveryTask._signpostWaitToScheduleID
+ _OBJC_IVAR_$__MPCKeyDeliveryTask._targetItemTime
+ _OBJC_IVAR_$__MPCKeyDeliveryTask._waitToFireBegun
+ _OBJC_IVAR_$__MPCKeyDeliveryTask._waitToScheduleEnded
+ _OBJC_IVAR_$__MPCPlaybackEnginePlayer._contentKeyDeliveryScheduler
+ _OBJC_IVAR_$__MPCQueueControllerBehaviorMusic._dataSourcesLock
+ _OBJC_METACLASS_$_MPCContentKeyDeliveryScheduler
+ _OBJC_METACLASS_$__MPCKeyDeliveryTask
+ _OUTLINED_FUNCTION_491
+ _OUTLINED_FUNCTION_492
+ _OUTLINED_FUNCTION_611
+ _OUTLINED_FUNCTION_612
+ _OUTLINED_FUNCTION_613
+ _OUTLINED_FUNCTION_614
+ _OUTLINED_FUNCTION_615
+ _OUTLINED_FUNCTION_616
+ _OUTLINED_FUNCTION_617
+ _OUTLINED_FUNCTION_618
+ _OUTLINED_FUNCTION_619
+ _OUTLINED_FUNCTION_620
+ _OUTLINED_FUNCTION_621
+ __DATA__TtC17MediaPlaybackCore25ChapterScanningController
+ __IVARS__TtC17MediaPlaybackCore25ChapterScanningController
+ __METACLASS_DATA__TtC17MediaPlaybackCore25ChapterScanningController
+ __OBJC_$_INSTANCE_METHODS_MPCContentKeyDeliveryScheduler
+ __OBJC_$_INSTANCE_METHODS_MPCModelGenericAVItem(MediaPlaybackCore|AppEntityPaths|KeyDeliveryDeferral)
+ __OBJC_$_INSTANCE_METHODS_MPCPlaybackEngine(MediaPlaybackCore|MediaPlaybackCore1|MediaPlaybackCore2|MusicContentKeySession)
+ __OBJC_$_INSTANCE_METHODS_MPCPlaybackEngineEventStream
+ __OBJC_$_INSTANCE_METHODS__MPCKeyDeliveryTask
+ __OBJC_$_INSTANCE_VARIABLES_MPCContentKeyDeliveryScheduler
+ __OBJC_$_INSTANCE_VARIABLES__MPCKeyDeliveryTask
+ __OBJC_$_PROP_LIST_MPCAssistantSendCommand
+ __OBJC_$_PROP_LIST_MPCContentKeyDeliveryScheduler
+ __OBJC_$_PROP_LIST_MPCPlaybackEngineEventStream
+ __OBJC_$_PROP_LIST__MPCKeyDeliveryTask
+ __OBJC_CLASS_PROTOCOLS_$_MPCPlaybackEngine(MediaPlaybackCore|MediaPlaybackCore1|MediaPlaybackCore2|MusicContentKeySession)
+ __OBJC_CLASS_RO_$_MPCContentKeyDeliveryScheduler
+ __OBJC_CLASS_RO_$__MPCKeyDeliveryTask
+ __OBJC_METACLASS_RO_$_MPCContentKeyDeliveryScheduler
+ __OBJC_METACLASS_RO_$__MPCKeyDeliveryTask
+ ___109-[MPCAssistantCommandInternal insertPlaybackQueueWithResult:atPosition:onDestination:withOptions:completion:]_block_invoke
+ ___109-[MPCAssistantCommandInternal insertPlaybackQueueWithResult:atPosition:onDestination:withOptions:completion:]_block_invoke_2
+ ___109-[MPCAssistantCommandInternal insertPlaybackQueueWithResult:atPosition:onDestination:withOptions:completion:]_block_invoke_3
+ ___109-[MPCAssistantCommandInternal insertPlaybackQueueWithResult:atPosition:onDestination:withOptions:completion:]_block_invoke_4
+ ___140-[MPCModelGenericAVItem(KeyDeliveryDeferral) shouldPerformKeyDeliveryRequestForKey:isPrefetchKey:isPersistable:isRenewal:completionHandler:]_block_invoke
+ ___140-[MPCModelGenericAVItem(KeyDeliveryDeferral) shouldPerformKeyDeliveryRequestForKey:isPrefetchKey:isPersistable:isRenewal:completionHandler:]_block_invoke_2
+ ___140-[MPCModelGenericAVItem(KeyDeliveryDeferral) shouldPerformKeyDeliveryRequestForKey:isPrefetchKey:isPersistable:isRenewal:completionHandler:]_block_invoke_3
+ ___51-[MPCContentKeyDeliveryScheduler flushPendingTasks]_block_invoke
+ ___73-[MPCContentKeyDeliveryScheduler _attachTimebaseObservers_lockedForItem:]_block_invoke
+ ___73-[MPCContentKeyDeliveryScheduler _attachTimebaseObservers_lockedForItem:]_block_invoke_2
+ ___78-[MPCModelGenericAVItem _finishDeferredLeaseAcquisitionWithCompletionHandler:]_block_invoke
+ ___78-[MPCModelGenericAVItem _finishDeferredLeaseAcquisitionWithCompletionHandler:]_block_invoke_2
+ ___85-[MPCContentKeyDeliveryScheduler scheduleKeyDeliveryBlock:forKey:jitterTime:timeout:]_block_invoke
+ ___85-[MPCContentKeyDeliveryScheduler scheduleKeyDeliveryBlock:forKey:jitterTime:timeout:]_block_invoke_2
+ ___87-[MPCContentKeyDeliveryScheduler _dispatchFire_locked:reason:expectedGeneration:delay:]_block_invoke
+ ___88-[MPCAssistantSendCommand _sendCommand:withOptions:toEndpoint:toDestination:completion:]_block_invoke_2
+ ___97-[MPCAssistantCommandInternal _resolveSupportedInsertionPosition:forPlayerPath:queue:completion:]_block_invoke
+ ___97-[MPCAssistantSendCommand _applyOptionsResolverIfNeededForCommand:options:playerPath:completion:]_block_invoke
+ ___block_descriptor_104_e8_32s40s48s56s64s72bs80r88r_e5_v8?0ls32l8s40l8s48l8s56l8r80l8r88l8s64l8s72l8
+ ___block_descriptor_104_e8_32s40s48s56s64s72s80s88s96w_e5_v8?0lw96l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8
+ ___block_descriptor_40_e8_32bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32w_e76_v36?0I8"NSDictionary"12"MRPlayerPath"20?<v?"NSDictionary""NSError">28lw32l8
+ ___block_descriptor_48_e8_32bs40w_e5_v8?0lw40l8s32l8
+ ___block_descriptor_48_e8_32w40w_e5_v8?0lw32l8w40l8
+ ___block_descriptor_52_e8_32s40bs_e20_v20?0i8"NSError"12ls40l8s32l8
+ ___block_descriptor_52_e8_32s40bs_e35_v24?0^{__CFArray=}8^{__CFError=}16ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48bs56r_e39_v16?0"MPCAssistantSendCommandResult"8lr56l8s32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48bs_e20_v16?0^{__CFArray=}8ls48l8s32l8s40l8
+ ___block_descriptor_64_e8_32s40s48w56w_e5_v8?0lw48l8w56l8s32l8s40l8
+ ___block_descriptor_68_e8_32s40s48s56bs_e34_v24?0"NSDictionary"8"NSError"16ls56l8s32l8s40l8s48l8
+ ___block_descriptor_77_e8_32s40s48s56bs64bs_e34_v24?0"MRAVEndpoint"8"NSError"16ls56l8s32l8s40l8s48l8s64l8
+ ___block_descriptor_80_e8_32s40s48s56s64bs_e30_v24?0"NSArray"8"MROrigin"16ls32l8s40l8s48l8s64l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56s64bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8s64l8s40l8s48l8s56l8
+ ___block_descriptor_84_e8_32s40s48s56bs64bs72bs_e22_v16?0"MRAVEndpoint"8ls32l8s40l8s48l8s56l8s64l8s72l8
+ ___block_descriptor_84_e8_32s40s48s56s64bs72bs_e34_v24?0"NSDictionary"8"NSError"16ls64l8s32l8s40l8s48l8s56l8s72l8
+ ___block_descriptor_85_e8_32s40s48s56s64bs72bs_e8_v12?0B8ls32l8s40l8s48l8s64l8s72l8s56l8
+ ___block_descriptor_86_e8_32s40s48s56s64bs72bs_e58_v32?0"MRAVEndpoint"8"NSArray"16?<v?"MRAVEndpoint">24ls32l8s40l8s48l8s64l8s72l8s56l8
+ ___block_descriptor_86_e8_32s40s48s56s64bs72bs_e5_v8?0ls32l8s40l8s48l8s64l8s72l8s56l8
+ ___swift_closure_destructor.104Tm
+ ___swift_closure_destructor.245Tm
+ ___swift_closure_destructor.257Tm
+ ___swift_closure_destructor.86Tm
+ ___swift_closure_destructor.94Tm
+ ___swift_memcpy43_8
+ ___swift_memcpy96_8
+ _erand48
+ _kCMTimebaseNotification_TimeJumped
+ _symbolic SaySdGyc
+ _symbolic Say_____GSgyc 17MediaPlaybackCore18SegmentTimeMappingV
+ _symbolic Sd4time_______p4item_____0A5Stampt 17MediaPlaybackCore10PlayerItemP AA9EventTimeC
+ _symbolic _____ 17MediaPlaybackCore25ChapterScanningControllerC
+ _symbolic _____ 17MediaPlaybackCore25ChapterScanningControllerC06PlayerF7ActionsV
+ _symbolic _____ 17MediaPlaybackCore25ChapterScanningControllerC0E7ContextV
+ _symbolic _____ 17MediaPlaybackCore29ScanningSlowdownConfigurationV
+ _symbolic _____Sg 17MediaPlaybackCore16InterruptedStateC
+ _symbolic _____Sg 17MediaPlaybackCore25ChapterScanningControllerC
+ _symbolic _____Sg 17MediaPlaybackCore25ChapterScanningControllerC0E7ContextV
+ _symbolic _____Sg 17MediaPlaybackCore26PlayerBoundaryTimeObserverC
+ _symbolic _____Sg 17MediaPlaybackCore29ScanningSlowdownConfigurationV
+ _symbolic _____SgXw 17MediaPlaybackCore25ChapterScanningControllerC
+ _symbolic _____SgXwz_Xx 17MediaPlaybackCore25ChapterScanningControllerC
+ _symbolic ______pSg4item_______pSg5error_____9timeStampt 17MediaPlaybackCore10PlayerItemP s5ErrorP AA9EventTimeC
+ _symbolic ______pSgXw 17MediaPlaybackCore6PlayerP
+ _symbolic ______pSgyc 17MediaPlaybackCore10PlayerItemP
+ _symbolic ySf_SStc
+ _symbolic y_____c 17MediaPlaybackCore5EventO
+ _type_layout_string 17MediaPlaybackCore25ChapterScanningControllerC06PlayerF7ActionsV
+ _type_layout_string 17MediaPlaybackCore25ChapterScanningControllerC0E7ContextV
+ _type_layout_string 17MediaPlaybackCore29ScanningSlowdownConfigurationV
- -[MPCDeferrableTask .cxx_destruct]
- -[MPCDeferrableTask block]
- -[MPCDeferrableTask cancel]
- -[MPCDeferrableTask dealloc]
- -[MPCDeferrableTask deallocating]
- -[MPCDeferrableTask description]
- -[MPCDeferrableTask disarmTimeout]
- -[MPCDeferrableTask execute:]
- -[MPCDeferrableTask guard]
- -[MPCDeferrableTask identifier]
- -[MPCDeferrableTask initWithIdentifier:timeout:queue:block:]
- -[MPCDeferrableTask isFinished]
- -[MPCDeferrableTask lock]
- -[MPCDeferrableTask queue]
- -[MPCDeferrableTask setBlock:]
- -[MPCDeferrableTask setDeallocating:]
- -[MPCDeferrableTask setFinished:]
- -[MPCDeferrableTask setGuard:]
- -[MPCDeferrableTask setIdentifier:]
- -[MPCDeferrableTask setLock:]
- -[MPCDeferrableTask setQueue:]
- -[MPCDeferrableTask taskDidExecute]
- -[MPCNonZeroEffectiveRateTask .cxx_destruct]
- -[MPCNonZeroEffectiveRateTask effectiveRateDidChange:]
- -[MPCNonZeroEffectiveRateTask initWithPlayerItem:identifier:timeout:queue:block:]
- -[MPCNonZeroEffectiveRateTask playerItem]
- -[MPCNonZeroEffectiveRateTask setPlayerItem:]
- -[MPCNonZeroEffectiveRateTask taskDidExecute]
- -[MPCPlaybackEngineEventStream(MusicContentKeySession) contentKeySession:didFinishProcessingKey:withResponse:error:]
- -[MPCPlaybackEngineEventStream(MusicContentKeySession) contentKeySession:didStartProcessingKey:isPrefetchKey:isPersistable:isRenewal:]
- -[_MPCPlaybackEnginePlayer didPerformPlayerOperationWithPlayerIdentifier:items:operation:]
- GCC_except_table112
- GCC_except_table1172
- GCC_except_table1176
- GCC_except_table1178
- GCC_except_table1346
- GCC_except_table1348
- GCC_except_table1395
- GCC_except_table1406
- GCC_except_table1413
- GCC_except_table1420
- GCC_except_table1457
- GCC_except_table1478
- GCC_except_table1521
- GCC_except_table1694
- GCC_except_table1696
- GCC_except_table1709
- GCC_except_table1714
- GCC_except_table1784
- GCC_except_table1868
- GCC_except_table1869
- GCC_except_table189
- GCC_except_table1980
- GCC_except_table2000
- GCC_except_table2002
- GCC_except_table2030
- GCC_except_table2039
- GCC_except_table2044
- GCC_except_table2046
- GCC_except_table2060
- GCC_except_table2185
- GCC_except_table2236
- GCC_except_table2240
- GCC_except_table2243
- GCC_except_table2292
- GCC_except_table2324
- GCC_except_table2419
- GCC_except_table2435
- GCC_except_table2622
- GCC_except_table2650
- GCC_except_table2677
- GCC_except_table2841
- GCC_except_table2848
- GCC_except_table2849
- GCC_except_table2874
- GCC_except_table2876
- GCC_except_table2880
- GCC_except_table2884
- GCC_except_table2886
- GCC_except_table2888
- GCC_except_table2890
- GCC_except_table2893
- GCC_except_table2919
- GCC_except_table2926
- GCC_except_table2933
- GCC_except_table2936
- GCC_except_table2941
- GCC_except_table2942
- GCC_except_table2947
- GCC_except_table2950
- GCC_except_table2953
- GCC_except_table2973
- GCC_except_table2981
- GCC_except_table3024
- GCC_except_table3109
- GCC_except_table3113
- GCC_except_table3124
- GCC_except_table3125
- GCC_except_table3149
- GCC_except_table3157
- GCC_except_table3198
- GCC_except_table3199
- GCC_except_table3215
- GCC_except_table3287
- GCC_except_table3293
- GCC_except_table3335
- GCC_except_table3337
- GCC_except_table3344
- GCC_except_table3355
- GCC_except_table3359
- GCC_except_table337
- GCC_except_table339
- GCC_except_table3395
- GCC_except_table34
- GCC_except_table3440
- GCC_except_table3566
- GCC_except_table3587
- GCC_except_table3594
- GCC_except_table3619
- GCC_except_table3623
- GCC_except_table3633
- GCC_except_table3725
- GCC_except_table3822
- GCC_except_table3826
- GCC_except_table3837
- GCC_except_table384
- GCC_except_table3853
- GCC_except_table3859
- GCC_except_table3868
- GCC_except_table392
- GCC_except_table3997
- GCC_except_table400
- GCC_except_table4041
- GCC_except_table4042
- GCC_except_table4043
- GCC_except_table4063
- GCC_except_table4072
- GCC_except_table409
- GCC_except_table4090
- GCC_except_table4095
- GCC_except_table4097
- GCC_except_table4145
- GCC_except_table4234
- GCC_except_table4253
- GCC_except_table4266
- GCC_except_table4277
- GCC_except_table4308
- GCC_except_table4479
- GCC_except_table4480
- GCC_except_table4659
- GCC_except_table4693
- GCC_except_table4695
- GCC_except_table4703
- GCC_except_table4711
- GCC_except_table4726
- GCC_except_table4752
- GCC_except_table4767
- GCC_except_table4811
- GCC_except_table4826
- GCC_except_table4842
- GCC_except_table4845
- GCC_except_table4851
- GCC_except_table4903
- GCC_except_table492
- GCC_except_table4939
- GCC_except_table5022
- GCC_except_table508
- GCC_except_table509
- GCC_except_table5123
- GCC_except_table525
- GCC_except_table526
- GCC_except_table5362
- GCC_except_table5363
- GCC_except_table5439
- GCC_except_table5529
- GCC_except_table5677
- GCC_except_table5702
- GCC_except_table5819
- GCC_except_table5900
- GCC_except_table5908
- GCC_except_table5909
- GCC_except_table5973
- GCC_except_table5998
- GCC_except_table6033
- GCC_except_table6036
- GCC_except_table6039
- GCC_except_table6125
- GCC_except_table6342
- GCC_except_table6359
- GCC_except_table6407
- GCC_except_table6420
- GCC_except_table6932
- GCC_except_table7266
- GCC_except_table7276
- GCC_except_table7369
- GCC_except_table7378
- GCC_except_table7460
- GCC_except_table7467
- GCC_except_table7485
- GCC_except_table7536
- GCC_except_table7537
- GCC_except_table7540
- GCC_except_table7545
- GCC_except_table7561
- GCC_except_table777
- GCC_except_table833
- GCC_except_table909
- GCC_except_table940
- GCC_except_table943
- GCC_except_table945
- GCC_except_table950
- GCC_except_table965
- GCC_except_table969
- GCC_except_table975
- GCC_except_table979
- GCC_except_table982
- GCC_except_table985
- _OBJC_CLASS_$_AVPlayerItemSampleBufferOutputConfiguration
- _OBJC_CLASS_$_MPCDeferrableTask
- _OBJC_CLASS_$_MPCNonZeroEffectiveRateTask
- _OBJC_CLASS_$__TtC17MediaPlaybackCore32SampleBufferOutputDelegateBridge
- _OBJC_IVAR_$_MPCDeferrableTask._block
- _OBJC_IVAR_$_MPCDeferrableTask._deallocating
- _OBJC_IVAR_$_MPCDeferrableTask._finished
- _OBJC_IVAR_$_MPCDeferrableTask._guard
- _OBJC_IVAR_$_MPCDeferrableTask._identifier
- _OBJC_IVAR_$_MPCDeferrableTask._lock
- _OBJC_IVAR_$_MPCDeferrableTask._queue
- _OBJC_IVAR_$_MPCModelGenericAVItem._deferredHLSDownloadTask
- _OBJC_IVAR_$_MPCModelGenericAVItem._deferredLeaseAcquisitionTask
- _OBJC_IVAR_$_MPCNonZeroEffectiveRateTask._playerItem
- _OBJC_METACLASS_$_MPCDeferrableTask
- _OBJC_METACLASS_$_MPCNonZeroEffectiveRateTask
- _OBJC_METACLASS_$__TtC17MediaPlaybackCore32SampleBufferOutputDelegateBridge
- _OUTLINED_FUNCTION_501
- _OUTLINED_FUNCTION_502
- __DATA__TtC17MediaPlaybackCore32SampleBufferOutputDelegateBridge
- __INSTANCE_METHODS__TtC17MediaPlaybackCore32SampleBufferOutputDelegateBridge
- __IVARS__TtC17MediaPlaybackCore32SampleBufferOutputDelegateBridge
- __METACLASS_DATA__TtC17MediaPlaybackCore32SampleBufferOutputDelegateBridge
- __OBJC_$_INSTANCE_METHODS_MPCDeferrableTask
- __OBJC_$_INSTANCE_METHODS_MPCModelGenericAVItem(MediaPlaybackCore|AppEntityPaths)
- __OBJC_$_INSTANCE_METHODS_MPCNonZeroEffectiveRateTask
- __OBJC_$_INSTANCE_METHODS_MPCPlaybackEngine(MediaPlaybackCore|MediaPlaybackCore1|MediaPlaybackCore2)
- __OBJC_$_INSTANCE_METHODS_MPCPlaybackEngineEventStream(MusicContentKeySession)
- __OBJC_$_INSTANCE_VARIABLES_MPCDeferrableTask
- __OBJC_$_INSTANCE_VARIABLES_MPCNonZeroEffectiveRateTask
- __OBJC_$_PROP_LIST_MPCDeferrableTask
- __OBJC_$_PROP_LIST_MPCNonZeroEffectiveRateTask
- __OBJC_$_PROP_LIST_MPCPlaybackEngine
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_AVPlayerItemSampleBufferOutputDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_AVPlayerItemSampleBufferOutputDelegate
- __OBJC_$_PROTOCOL_REFS_AVPlayerItemSampleBufferOutputDelegate
- __OBJC_CLASS_PROTOCOLS_$_MPCPlaybackEngine
- __OBJC_CLASS_PROTOCOLS_$_MPCPlaybackEngineEventStream(MusicContentKeySession)
- __OBJC_CLASS_RO_$_MPCDeferrableTask
- __OBJC_CLASS_RO_$_MPCNonZeroEffectiveRateTask
- __OBJC_LABEL_PROTOCOL_$_AVPlayerItemSampleBufferOutputDelegate
- __OBJC_METACLASS_RO_$_MPCDeferrableTask
- __OBJC_METACLASS_RO_$_MPCNonZeroEffectiveRateTask
- __OBJC_PROTOCOL_$_AVPlayerItemSampleBufferOutputDelegate
- __PROTOCOLS__TtC17MediaPlaybackCore32SampleBufferOutputDelegateBridge
- ___101-[MPCAssistantCommand insertPlaybackQueueWithResult:atPosition:onDestination:withOptions:completion:]_block_invoke
- ___101-[MPCAssistantCommand insertPlaybackQueueWithResult:atPosition:onDestination:withOptions:completion:]_block_invoke_2
- ___29-[MPCDeferrableTask execute:]_block_invoke
- ___29-[MPCDeferrableTask execute:]_block_invoke_2
- ___60-[MPCDeferrableTask initWithIdentifier:timeout:queue:block:]_block_invoke
- ___block_descriptor_104_e8_32s40s48s56s64s72s80s88s96w_e8_v16?0q8lw96l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8
- ___block_descriptor_48_e8_32s_e8_v16?0q8ls32l8
- ___block_descriptor_56_e8_32s40bs_e20_v16?0^{__CFArray=}8ls40l8s32l8
- ___block_descriptor_56_e8_32s40s48bs_e39_v16?0"MPCAssistantSendCommandResult"8ls32l8s40l8s48l8
- ___block_descriptor_76_e8_32s40s48s56bs64bs_e34_v24?0"NSDictionary"8"NSError"16ls56l8s32l8s40l8s48l8s64l8
- ___block_descriptor_80_e8_32s40s48s56s64bs_e17_v16?0"NSArray"8ls32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_85_e8_32s40s48s56bs64bs72bs_e34_v24?0"MRAVEndpoint"8"NSError"16ls32l8s40l8s48l8s56l8s64l8s72l8
- ___block_descriptor_92_e8_32s40s48s56bs64bs72bs80bs_e22_v16?0"MRAVEndpoint"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8
- ___block_descriptor_92_e8_32s40s48s56s64bs72bs80bs_e34_v24?0"NSDictionary"8"NSError"16ls64l8s32l8s40l8s48l8s56l8s72l8s80l8
- ___block_descriptor_93_e8_32s40s48s56s64bs72bs80bs_e8_v12?0B8ls32l8s40l8s48l8s64l8s72l8s80l8s56l8
- ___block_descriptor_94_e8_32s40s48s56s64bs72bs80bs_e58_v32?0"MRAVEndpoint"8"NSArray"16?<v?"MRAVEndpoint">24ls32l8s40l8s48l8s64l8s72l8s80l8s56l8
- ___block_descriptor_94_e8_32s40s48s56s64bs72bs80bs_e5_v8?0ls32l8s40l8s48l8s64l8s72l8s80l8s56l8
- ___block_descriptor_96_e8_32s40s48s56s64bs72r80r_e5_v8?0ls32l8s40l8s48l8s56l8r72l8r80l8s64l8
- ___swift_closure_destructor.102Tm
- ___swift_closure_destructor.255Tm
- ___swift_closure_destructor.267Tm
- ___swift_closure_destructor.270Tm
- ___swift_closure_destructor.85Tm
- ___swift_closure_destructor.92Tm
- _objc_retain_x12
- _symbolic _____ 17MediaPlaybackCore32SampleBufferOutputDelegateBridgeC
- _symbolic _____SgXw 17MediaPlaybackCore14ScoutingPlayerC
- _symbolic _____SgXwz_Xx 17MediaPlaybackCore14ScoutingPlayerC
- _symbolic _____y__________G 7Combine18PassthroughSubjectC 17MediaPlaybackCore12SignpostTypeO s5NeverO
- _symbolic _____yyt_GSg ScS12ContinuationV
- _symbolic ySo30AVPlayerItemSampleBufferOutputCcSg
CStrings:
+ " [FAILED]"
+ " enableTelemetry=YES outcome=%{public, signpost.telemetry:string1, name=outcome}s positionSec=%{public, signpost.telemetry:number1, name=positionSec}d"
+ "%@ identifier=%@ target=%.3f jitter=%.3f"
+ "-[MPCAssistantCommandInternal insertPlaybackQueueWithResult:atPosition:onDestination:withOptions:completion:]_block_invoke"
+ "AssetCache"
+ "ContentKeyDeliverySchedulerTimeout"
+ "DeferredLeaseAcquisition"
+ "DownloadToAssetCache"
+ "DownloadToCache"
+ "InsertIntoPlaybackQueue validation: 'Specified' position not supported (supported: %{public}@); will not demote"
+ "InsertIntoPlaybackQueue validation: no player path available; sending requested position %ld unchanged"
+ "InsertIntoPlaybackQueue validation: receiver did not advertise supported insertion positions for path %{public}@; sending requested position %ld unchanged"
+ "InsertIntoPlaybackQueue validation: requested position %ld unsupported and no fallback available (supported: %{public}@)"
+ "InsertIntoPlaybackQueue validation: supported-commands query failed for path %{public}@: %{public}@; sending requested position %ld unchanged"
+ "InsertIntoPlaybackQueue: requested position %ld unsupported (supported: %{public}@); falling back to %ld"
+ "KeyDeliveryWaitToFire"
+ "KeyDeliveryWaitToSchedule"
+ "MPCContentKeyDeliveryScheduler %p: currentItem -> %{public}@ (timebase=%{public}s, pending=%lu)"
+ "MPCContentKeyDeliveryScheduler %p: fired %{public}@ reason=%{public}@"
+ "MPCContentKeyDeliveryScheduler %p: flushing %lu pending task(s)"
+ "MPCContentKeyDeliveryScheduler %p: scheduling %{public}@ timeout=%.3f"
+ "MediaPlaybackCore.ScanningSlowdownReached"
+ "MusicKeyDeliveryJitter"
+ "No samples received for range: %fs - %fs"
+ "The requested insertion position is not supported by the playing device."
+ "Timeout (%fs) elapsed before samples received for range: %fs - %fs"
+ "UnexpectedRollBackToInterruptedState"
+ "[AC] AssetCache is enabled [FF]"
+ "[ChapterScanningController] Boundary fired at %f but no chapter nearby — ignoring"
+ "[ChapterScanningController] Scanning slowdown reached at %f"
+ "[Chapters/%{private,mask.hash}s] No chapters found post processing."
+ "[MPCPlaybackIntent:%p] getArchiveFromIntent: | created archive [] archive=%{public}@"
+ "[MPCPlaybackIntent:%p] getArchiveFromIntent: | intent=%{public}@ configuration.preferredArtworkSize=%{public}@"
+ "[PL:%{public}s] PLAYER CONTROLLER: Injecting synthesized player event: %{public}s"
+ "[PL:%{public}s] PLAYER PROCESSING: InternalPlayerController - resumePlayFromInterruption failed - error:%{public}s - currentItem:%{public}s - player:%{public}s - will inject resumeFromInterruptionDidFail"
+ "chapterBoundariesDidChange - timeStamp:"
+ "com.apple.mediaplaybackcore.contentKeyDeliveryScheduler"
+ "command == MRMediaRemoteCommandInsertIntoPlaybackQueue"
+ "deallocated"
+ "effectiveRateChanged"
+ "flush"
+ "key-delivery-jitter-time"
+ "pastWindow"
+ "player-operation-error"
+ "reason=%{public, signpost.telemetry:string1, name=reason}s"
+ "resumeAfterSlowdown [commandID: "
+ "resumeFromInterruptionDidFail:"
+ "scanningSlowdownReached:"
+ "scheduledTime"
+ "timeJumped"
+ "timeout"
+ "v20@?0i8@\"NSError\"12"
+ "v24@?0@\"NSArray\"8@\"MROrigin\"16"
+ "v36@?0I8@\"NSDictionary\"12@\"MRPlayerPath\"20@?<v@?@\"NSDictionary\"@\"NSError\">28"
+ "valid"
+ "|%{public}@ %{public}@ %2i %{public}@  ╰ error: %{public}@"
+ "\xb2"
+ "⚠️ [SampleBufferOutput] processLoop cancelled after %ld buffers"
+ "⚡ [SampleBufferOutput] Sequence restarted"
+ "\xf0\xf0\xf0\xa1"
- "%@ Deferred task can't be executed multiple times"
- "%{public}@ Started executing (%{public}@)"
- "%{public}@ Started waiting for a EffectiveRateChanged notification"
- "<%@: %p identifier=%@>"
- "Canceled"
- "HLSDownload:%@"
- "MPCDeferrableTask.m"
- "MPCEnableMusicAssetCache"
- "MUSIC_PLAYBACK_PERFORMANCE_ASSET_CACHE"
- "No samples received"
- "Optimal"
- "SonicAssetDownloadTask:%@"
- "[AC] AssetCache is enabled [TrialExperiment]"
- "[AC] AssetCache is enabled [UserDefaults]"
- "[MPCPlaybackIntent:%p] getArchiveFromIntent: | intent=%{public}@"
- "com.apple.MediaPlaybackCore.SampleBufferOutput"
- "com.apple.MediaPlaybackCore.ScoutingPlayer.delegate"
- "leaseAcquisition:%@"
- "\xa2"
- "⚠️ [SampleBufferOutput] pullAndProcessBuffers cancelled after %ld buffers"
- "⚡ [SampleBufferOutput] Sequence flush handled"
- "⚡ [SampleBufferOutput] Sequence flush handled, restarted processing"
- "⚡ [SampleBufferOutput] handleSequenceFlushed"
- "\xf0\xf0\xf0\xb1"
```
