## AVFCapture

> `/System/Library/PrivateFrameworks/AVFCapture.framework/AVFCapture`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1782ec` | `0x178820` | **`+0x534`** |
| `__TEXT.__cstring` | `0x2d349` | `0x2d4b9` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x24906` | `0x249f0` | **`+0xea`** |
| `__AUTH_CONST.__cfstring` | `0x158a0` | `0x15960` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0xf714` | `0xf79c` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x81b0` | `0x8228` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0x19278` | `0x192d8` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x51d0` | `0x5200` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x2fd4` | `0x2ff8` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x29f8` | `0x2a10` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x87b8` | `0x87c8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x10a0` | `0x10a8` | **`+0x8`** |
| `__DATA.__data` | `0xcf8` | `0xd00` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1afc` | `0x1b04` | **`+0x8`** |

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3

-  Functions: 7269
-  Symbols:   13006
-  CStrings:  5679
+  Functions: 7284
+  Symbols:   13028
+  CStrings:  5688
Symbols:
+ -[AVCaptureDevice isAdjustingSignalCompensationDelayWhileRunningSupported]
+ -[AVCaptureDeviceRotationCoordinator _bsDeviceOrientationToVideoRotationAngle:unsupportedDeviceOrientation:]
+ -[AVCaptureDeviceRotationCoordinator _videoRotationAngleForDeviceOrientation:]
+ -[AVCaptureDeviceRotationCoordinator videoRotationAngleRelativeToDeviceOrientation:]
+ -[AVCaptureFigVideoDevice isAdjustingSignalCompensationDelayWhileRunningSupported]
+ -[AVCaptureMetadataOutput _activeVideoMaxFrameDurationInSeconds]
+ -[AVCaptureMetadataOutput _setSynchronizationEnabledBySynchronizer:]
+ -[AVCaptureOutput handlePreviewSizedOutputBuffersDidChangeForVideoDataOutput:]
+ -[AVCapturePhotoOutput _updateTextOrientationPrioritizationSupportedForSourceDevice:]
+ -[AVCapturePhotoOutput handlePreviewSizedOutputBuffersDidChangeForVideoDataOutput:]
+ -[AVCaptureSession _addInputWithNoConnections:resetVideoZoomFactorAndMinMaxFrameDurations:exceptionReason:]
+ -[AVCaptureSession _handlePreviewSizedOutputBuffersDidChangeForVideoDataOutput:]
+ -[AVExternalSyncDevice isSignalCompensationDelaySupported]
+ GCC_except_table148
+ GCC_except_table172
+ GCC_except_table175
+ GCC_except_table184
+ GCC_except_table187
+ GCC_except_table198
+ GCC_except_table200
+ GCC_except_table205
+ GCC_except_table210
+ GCC_except_table212
+ GCC_except_table214
+ GCC_except_table219
+ GCC_except_table223
+ GCC_except_table228
+ GCC_except_table233
+ GCC_except_table239
+ GCC_except_table249
+ GCC_except_table254
+ GCC_except_table263
+ GCC_except_table269
+ GCC_except_table278
+ GCC_except_table284
+ GCC_except_table290
+ GCC_except_table295
+ GCC_except_table298
+ GCC_except_table317
+ GCC_except_table320
+ GCC_except_table323
+ GCC_except_table324
+ GCC_except_table327
+ GCC_except_table330
+ GCC_except_table332
+ GCC_except_table340
+ GCC_except_table343
+ GCC_except_table349
+ GCC_except_table358
+ GCC_except_table379
+ GCC_except_table390
+ GCC_except_table392
+ GCC_except_table394
+ GCC_except_table403
+ GCC_except_table419
+ GCC_except_table442
+ GCC_except_table452
+ GCC_except_table464
+ GCC_except_table479
+ GCC_except_table482
+ GCC_except_table508
+ GCC_except_table512
+ GCC_except_table520
+ GCC_except_table523
+ GCC_except_table531
+ GCC_except_table539
+ GCC_except_table545
+ GCC_except_table550
+ GCC_except_table557
+ GCC_except_table564
+ GCC_except_table574
+ GCC_except_table588
+ GCC_except_table611
+ GCC_except_table622
+ GCC_except_table632
+ GCC_except_table646
+ GCC_except_table656
+ GCC_except_table668
+ GCC_except_table687
+ GCC_except_table708
+ GCC_except_table711
+ GCC_except_table738
+ GCC_except_table740
+ GCC_except_table742
+ GCC_except_table767
+ GCC_except_table779
+ GCC_except_table781
+ GCC_except_table783
+ GCC_except_table789
+ GCC_except_table791
+ GCC_except_table834
+ GCC_except_table838
+ GCC_except_table894
+ GCC_except_table896
+ GCC_except_table898
+ GCC_except_table900
+ GCC_except_table944
+ GCC_except_table946
+ GCC_except_table952
+ GCC_except_table96
+ GCC_except_table960
+ GCC_except_table968
+ _AVCaptureSessionRequiresRestartKey
+ _AVCaptureSessionVideoDataOutputDeliversPreviewSizedBuffersChangedContext
+ _AVGQ47VE37PL2WQ2B6PNAKBKYS55GY
+ _CMTimeConvertScale
+ _FigCaptureFrameRateAsInt
+ _FigCaptureRadarOptionGenerateTailspinWithReasonKey
+ _OBJC_IVAR_$_AVCaptureDeviceRotationCoordinator._videoRotationAnglesRelativeToDeviceOrientation
+ _OBJC_IVAR_$_AVCaptureMetadataOutputInternal.synchronizationEnabledBySynchronizer
+ ___43-[AVCaptureFigAudioDevice figCaptureSource]_block_invoke
+ _avccm_cameraAppOrDerivativeForBundleID
+ _kFigCaptureSessionNotificationPayloadKey_SessionRequiresRestart
- -[AVCaptureSession _addInputWithNoConnections:exceptionReason:]
- GCC_except_table106
- GCC_except_table146
- GCC_except_table170
- GCC_except_table174
- GCC_except_table178
- GCC_except_table186
- GCC_except_table188
- GCC_except_table199
- GCC_except_table202
- GCC_except_table209
- GCC_except_table211
- GCC_except_table213
- GCC_except_table215
- GCC_except_table222
- GCC_except_table226
- GCC_except_table231
- GCC_except_table238
- GCC_except_table247
- GCC_except_table253
- GCC_except_table262
- GCC_except_table268
- GCC_except_table277
- GCC_except_table282
- GCC_except_table289
- GCC_except_table294
- GCC_except_table297
- GCC_except_table316
- GCC_except_table318
- GCC_except_table322
- GCC_except_table326
- GCC_except_table329
- GCC_except_table331
- GCC_except_table339
- GCC_except_table342
- GCC_except_table348
- GCC_except_table357
- GCC_except_table378
- GCC_except_table389
- GCC_except_table391
- GCC_except_table393
- GCC_except_table402
- GCC_except_table418
- GCC_except_table441
- GCC_except_table451
- GCC_except_table463
- GCC_except_table478
- GCC_except_table481
- GCC_except_table507
- GCC_except_table511
- GCC_except_table519
- GCC_except_table522
- GCC_except_table530
- GCC_except_table538
- GCC_except_table544
- GCC_except_table549
- GCC_except_table556
- GCC_except_table563
- GCC_except_table573
- GCC_except_table587
- GCC_except_table610
- GCC_except_table621
- GCC_except_table631
- GCC_except_table645
- GCC_except_table655
- GCC_except_table667
- GCC_except_table686
- GCC_except_table707
- GCC_except_table710
- GCC_except_table73
- GCC_except_table737
- GCC_except_table739
- GCC_except_table741
- GCC_except_table766
- GCC_except_table778
- GCC_except_table780
- GCC_except_table782
- GCC_except_table788
- GCC_except_table790
- GCC_except_table833
- GCC_except_table837
- GCC_except_table893
- GCC_except_table895
- GCC_except_table897
- GCC_except_table899
- GCC_except_table943
- GCC_except_table945
- GCC_except_table951
- GCC_except_table959
- GCC_except_table967
- _CMTimeAbsoluteValue
CStrings:
+ "-[AVCaptureDeviceRotationCoordinator _videoRotationAngleForDeviceOrientation:]"
+ "2f1e4dc8b43af60f53ae6a8af761e3e1a56ee345"
+ "3a829a464addf25e052dc3e6d2d5f089f1093455"
+ "40fddd6d92eab3d590b4a36dec7d4a84942e1b93"
+ "<<<< AVCaptureDeviceRotationCoordinator >>>> %s: %{public}@ videoRotationAngleForDeviceOrientation given unsupported device orientation: %d!"
+ "<<<< AVCaptureSession >>>> %s: (%p) New fcs config(%lld) differs from old due to: %{public}@"
+ "AVCaptureSessionRequiresRestartKey"
+ "AVGQ47VE37PL2WQ2B6PNAKBKYS55GY"
+ "LastShownBuild:AVCaptureDevice.m:4799"
+ "LastShownBuild:AVCaptureDevice.m:4803"
+ "LastShownBuild:AVControlCenterModules.m:4665"
+ "LastShownBuild:AVControlCenterModules.m:4669"
+ "LastShownBuild:AVSpatialOverCaptureVideoPreviewLayer.m:283"
+ "LastShownDate:AVCaptureDevice.m:4799"
+ "LastShownDate:AVCaptureDevice.m:4803"
+ "LastShownDate:AVControlCenterModules.m:4665"
+ "LastShownDate:AVControlCenterModules.m:4669"
+ "LastShownDate:AVSpatialOverCaptureVideoPreviewLayer.m:283"
+ "PreviewMonitorTimeout"
+ "description=CameraCapture_AVF-753.0.0.122.3"
+ "signalCompensationDelay may not be changed - use -[AVExternalSyncDevice isSignalCompensationDelaySupported] to check support."
+ "textOrientationPrioritizationEnabled"
+ "textOrientationPrioritizationSupported"
+ "yyyy-MM-dd HH:mm:ss.SSS"
- "9c8e3c1920776cf8eeec6ae399defc5475c07d61"
- "LastShownBuild:AVCaptureDevice.m:4758"
- "LastShownBuild:AVCaptureDevice.m:4762"
- "LastShownBuild:AVControlCenterModules.m:4656"
- "LastShownBuild:AVControlCenterModules.m:4660"
- "LastShownBuild:AVSpatialOverCaptureVideoPreviewLayer.m:282"
- "LastShownDate:AVCaptureDevice.m:4758"
- "LastShownDate:AVCaptureDevice.m:4762"
- "LastShownDate:AVControlCenterModules.m:4656"
- "LastShownDate:AVControlCenterModules.m:4660"
- "LastShownDate:AVSpatialOverCaptureVideoPreviewLayer.m:282"
- "d348493b66fa8d5adfee0206daeffec13b91b09d"
- "description=CameraCapture_AVF-748.0.0.122.2"
- "f0104621c45ca6afb45f58a5c14f81118d19a64d"
- "yyyy-MM-dd hh:mm:ss.SSS"
```
