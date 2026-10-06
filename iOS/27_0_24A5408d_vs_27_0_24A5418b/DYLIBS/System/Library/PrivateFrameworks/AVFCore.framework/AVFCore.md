## AVFCore

> `/System/Library/PrivateFrameworks/AVFCore.framework/AVFCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c9894` | `0x1c9db4` | **`+0x520`** |
| `__TEXT.__cstring` | `0x26da3` | `0x26f43` | **`+0x1a0`** |
| `__AUTH_CONST.__cfstring` | `0x1a640` | `0x1a720` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x9fec` | `0xa024` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xa4e8` | `0xa520` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x1c114` | `0x1c144` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x5b90` | `0x5bb8` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x329b8` | `0x329d8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xb5a0` | `0xb5c0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2040` | `0x2048` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x50d7` | `0x50d1` | **`-0x6`** |
| `__DATA.__objc_ivar` | `0x27dc` | `0x27e0` | **`+0x4`** |

### Other Changes

```diff

-2450.75.1.0.0
+2450.77.1.1.0

-  Functions: 12078
-  Symbols:   23912
-  CStrings:  4299
+  Functions: 12084
+  Symbols:   23941
+  CStrings:  4306
Symbols:
+ -[AVAssetExportSession _simulateMediaServicesWereResetForTesting]
+ -[AVPlaybackItemInspectorLoader _handlePlaybackItemNotification:notificationPayload:]
+ -[AVPlaybackItemInspectorLoader _processItemReadyForInspection:figErrorCode:]
+ -[AVPlayerItemIntegratedTimelinePeriodicObserver _doesTimeResideInPrimarySegment:atTime:timeMappingOut:]
+ GCC_except_table141
+ GCC_except_table201
+ GCC_except_table254
+ GCC_except_table261
+ GCC_except_table266
+ GCC_except_table268
+ GCC_except_table270
+ GCC_except_table277
+ GCC_except_table280
+ GCC_except_table290
+ GCC_except_table302
+ GCC_except_table307
+ GCC_except_table310
+ GCC_except_table312
+ GCC_except_table318
+ GCC_except_table325
+ GCC_except_table330
+ GCC_except_table340
+ GCC_except_table342
+ GCC_except_table350
+ GCC_except_table352
+ GCC_except_table361
+ GCC_except_table369
+ GCC_except_table375
+ GCC_except_table377
+ GCC_except_table386
+ GCC_except_table392
+ GCC_except_table411
+ GCC_except_table413
+ GCC_except_table425
+ GCC_except_table431
+ GCC_except_table434
+ GCC_except_table438
+ GCC_except_table447
+ GCC_except_table450
+ GCC_except_table455
+ GCC_except_table462
+ GCC_except_table469
+ GCC_except_table472
+ GCC_except_table476
+ GCC_except_table482
+ GCC_except_table501
+ GCC_except_table504
+ GCC_except_table506
+ GCC_except_table510
+ GCC_except_table515
+ GCC_except_table520
+ GCC_except_table563
+ GCC_except_table567
+ GCC_except_table571
+ GCC_except_table575
+ GCC_except_table582
+ GCC_except_table587
+ GCC_except_table591
+ GCC_except_table596
+ GCC_except_table601
+ GCC_except_table604
+ GCC_except_table609
+ GCC_except_table613
+ GCC_except_table618
+ GCC_except_table619
+ GCC_except_table633
+ GCC_except_table634
+ GCC_except_table641
+ GCC_except_table652
+ GCC_except_table684
+ GCC_except_table697
+ GCC_except_table701
+ GCC_except_table702
+ GCC_except_table706
+ GCC_except_table722
+ GCC_except_table727
+ GCC_except_table736
+ GCC_except_table743
+ GCC_except_table750
+ GCC_except_table751
+ GCC_except_table755
+ GCC_except_table765
+ GCC_except_table771
+ GCC_except_table778
+ GCC_except_table781
+ GCC_except_table790
+ GCC_except_table818
+ GCC_except_table826
+ GCC_except_table829
+ GCC_except_table833
+ GCC_except_table836
+ GCC_except_table842
+ GCC_except_table845
+ GCC_except_table850
+ GCC_except_table862
+ GCC_except_table870
+ GCC_except_table875
+ GCC_except_table884
+ GCC_except_table902
+ _AVAssetWritingPlannerErrorWithUnderlyingSPICode
+ _FigAssetExportSessionSimulateMediaServicesWereReset
+ _OBJC_IVAR_$_AVPlaybackItemInspectorLoader._notificationProcessingQueue
+ _OBJC_IVAR_$_AVPlayerInternal.cachedCurrentInterstitialEvent
+ ___104-[AVPlayer _setRate:withVolumeRampDuration:playImmediately:rateChangeReason:affectsCoordinatedPlayback:]_block_invoke_2
+ ___65-[AVPlayer(AVPlayerSupportForMediaPlayer) _resumePlayback:error:]_block_invoke
+ ___block_descriptor_48_e8_32r_e29_v20?0^{OpaqueFigPlayer=}8i16lr32l8
+ _kFigPlayerInterstitialNotification_CurrentEventChangeEventKey
- GCC_except_table138
- GCC_except_table217
- GCC_except_table225
- GCC_except_table227
- GCC_except_table231
- GCC_except_table244
- GCC_except_table253
- GCC_except_table257
- GCC_except_table264
- GCC_except_table271
- GCC_except_table283
- GCC_except_table285
- GCC_except_table293
- GCC_except_table298
- GCC_except_table301
- GCC_except_table304
- GCC_except_table306
- GCC_except_table317
- GCC_except_table334
- GCC_except_table339
- GCC_except_table341
- GCC_except_table344
- GCC_except_table359
- GCC_except_table368
- GCC_except_table370
- GCC_except_table374
- GCC_except_table378
- GCC_except_table396
- GCC_except_table408
- GCC_except_table420
- GCC_except_table446
- GCC_except_table453
- GCC_except_table470
- GCC_except_table479
- GCC_except_table483
- GCC_except_table503
- GCC_except_table509
- GCC_except_table554
- GCC_except_table566
- GCC_except_table595
- GCC_except_table599
- GCC_except_table603
- GCC_except_table611
- GCC_except_table617
- GCC_except_table621
- GCC_except_table631
- GCC_except_table632
- GCC_except_table636
- GCC_except_table640
- GCC_except_table654
- GCC_except_table660
- GCC_except_table663
- GCC_except_table676
- GCC_except_table686
- GCC_except_table692
- GCC_except_table693
- GCC_except_table704
- GCC_except_table705
- GCC_except_table711
- GCC_except_table720
- GCC_except_table738
- GCC_except_table741
- GCC_except_table746
- GCC_except_table761
- GCC_except_table783
- GCC_except_table788
- GCC_except_table808
- GCC_except_table820
- GCC_except_table831
- GCC_except_table832
- GCC_except_table840
- GCC_except_table844
- GCC_except_table848
- GCC_except_table868
- GCC_except_table873
- GCC_except_table883
- _OBJC_IVAR_$_AVPlayerInternal.cachedHasCurrentInterstitialEvent
- _kFigPlayerInterstitialNotification_CurrentEventChangeEventIDKey
CStrings:
+ "<<<< AVPlayer >>>> %s: <%{public}@|%p> setting CurrentInterstitialEvent with id=%@"
+ "Cannot call executePlanWithCompletionHandler more than once"
+ "Client cancelled planner export"
+ "Client segment writing callback returned error"
+ "Internal planner error"
+ "Must plan at least one track before calling executePlanWithCompletionHandler"
+ "Planner could not save session state file"
+ "Planner encountered an error in creating assembly composition"
+ "Planner encountered an error reconciling previous session state with current planner settings"
+ "Planner encountered corrupt state file"
+ "avplayer_fpNotificationCallback_block_invoke_3"
- "<<<< AVPlayer >>>> %s: <%{public}@|%p> setting hasCurrentInterstitialEvent=%d with id=%@"
- "Failure reason"
- "Unable to update internal state file"
- "avplayer_fpNotificationCallback_block_invoke_4"
```
