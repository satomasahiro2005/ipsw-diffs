## MagnifierAngel

> `/Applications/MagnifierAngel.app/MagnifierAngel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x84260` | `0x8bfb8` | **`+0x7d58`** |
| `__TEXT.__swift5_typeref` | `0x70c6` | `0x78ba` | **`+0x7f4`** |
| `__TEXT.__eh_frame` | `0x489c` | `0x4e94` | **`+0x5f8`** |
| `__TEXT.__oslogstring` | `0x17fd` | `0x1b6d` | **`+0x370`** |
| `__TEXT.__const` | `0x3994` | `0x3b54` | **`+0x1c0`** |
| `__TEXT.__objc_methname` | `0x3e9d` | `0x404d` | **`+0x1b0`** |
| `__TEXT.__swift5_reflstr` | `0x1ac9` | `0x1c49` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x1da8` | `0x1f08` | **`+0x160`** |
| `__TEXT.__auth_stubs` | `0x33a0` | `0x34f0` | **`+0x150`** |
| `__DATA.__objc_const` | `0x24c0` | `0x2608` | **`+0x148`** |
| `__DATA.__objc_data` | `0x1400` | `0x1520` | **`+0x120`** |
| `__TEXT.__constg_swiftt` | `0x1490` | `0x1598` | **`+0x108`** |
| `__DATA.__data` | `0x2be8` | `0x2cc8` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x2c38` | `0x2cf8` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x197e` | `0x1a3e` | **`+0xc0`** |
| `__DATA_CONST.__auth_got` | `0x19d8` | `0x1a80` | **`+0xa8`** |
| `__TEXT.__objc_stubs` | `0x1760` | `0x1800` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x1140` | `0x11d0` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0xc34` | `0xc98` | **`+0x64`** |
| `__TEXT.__swift_as_cont` | `0x3e8` | `0x448` | **`+0x60`** |
| `__DATA_CONST.__got` | `0xb08` | `0xb60` | **`+0x58`** |
| `__DATA.__bss` | `0x2f08` | `0x2f38` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0xbc8` | `0xbf8` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x184` | `0x1a4` | **`+0x20`** |
| `__DATA.__common` | `0x178` | `0x190` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0xa0` | **`+0x14`** |
| `__TEXT.__objc_methlist` | `0xe94` | `0xea4` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x18c` | `0x19c` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x948` | `0x950` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xf8` | `0xfc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-283.0.0.0.0
+286.0.0.0.0
+  - /System/Library/Frameworks/ARKit.framework/ARKit

+  - /System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/AccessibilitySharedSupport

-  Functions: 2142
-  Symbols:   1440
-  CStrings:  987
+  Functions: 2216
+  Symbols:   1471
+  CStrings:  1022
Symbols:
+ _$s10Foundation6LocaleV10identifierSSvg
+ _$s16MagnifierSupport12MAGARServiceC12eventHandler19captureSessionQueue20frameWatchdogEnabledAcA010MAGAREventE0C_So17OS_dispatch_queueCSbtcfc
+ _$s16MagnifierSupport12MAGARServiceC23restartForFrameRecoveryyyFTj
+ _$s16MagnifierSupport15MAGOutputEngineC12isAnnouncingSbvgTj
+ _$s16MagnifierSupport15MAGOutputEngineC22clearDetectedTextStateyyFTj
+ _$s16MagnifierSupport15MAGOutputEngineC24isAnnouncingDetectedTextSbvgTj
+ _$s16MagnifierSupport15MAGOutputEngineC27bypassNextImageCaptionDedupSbvsTj
+ _$s16MagnifierSupport19MAGFrameFingerprintVSQAAMc
+ _$s16MagnifierSupport22MAGImageCaptionServiceC013generateImageD03for16imageOrientation26comparingToPreviousCaptureSSAA23MAGCVPixelBufferWrapperC_So015CGImagePropertyJ0VSbtYaKF
+ _$s16MagnifierSupport22MAGImageCaptionServiceC013generateImageD03for16imageOrientation26comparingToPreviousCaptureSSAA23MAGCVPixelBufferWrapperC_So015CGImagePropertyJ0VSbtYaKFTu
+ _$s16MagnifierSupport22MAGImageCaptionServiceC16isFrameTooBlurryySbSo11CVBufferRefaYaF
+ _$s16MagnifierSupport22MAGImageCaptionServiceC16isFrameTooBlurryySbSo11CVBufferRefaYaFTu
+ _$s16MagnifierSupport22MAGImageCaptionServiceC20resetSceneComparisonyyF
+ _$s16MagnifierSupport23MAGPointAndSpeakServiceC10detectBlur3forSbAA23MAGCVPixelBufferWrapperC_tYaKFTjTu
+ _$s16MagnifierSupport23MAGTextDetectionServiceC16detectTextViaPCC15fromPixelBuffer11orientationSSSo11CVBufferRefa_So26CGImagePropertyOrientationVtYaKFTjTu
+ _$s16MagnifierSupport23MAGTextDetectionServiceC18isNetworkAvailableSbvgTj
+ _$s16MagnifierSupport25MFParentalApprovalManagerC20shouldHideAskOptionsSbvg
+ _$s16MagnifierSupport25MFParentalApprovalManagerC30isRestrictedByParentalControlsSbvg
+ _$s16MagnifierSupport25MFParentalApprovalManagerC6sharedACvgZ
+ _$s16MagnifierSupport25MFParentalApprovalManagerCMa
+ _$s16MagnifierSupport26MAGVQAOnboardingControllerC11EnvironmentO15liveRecognitionyA2EmFWC
+ _$s16MagnifierSupport26MAGVQAOnboardingControllerC11EnvironmentOMa
+ _$s16MagnifierSupport26MAGVQAOnboardingControllerC13dismissAction9tintColor11environmentACyyc_So7UIColorCAC11EnvironmentOtcfc
+ _$s16MagnifierSupport8MAGErrorO17blurValueDetectedyA2CmFWC
+ _$s16MagnifierSupport9DetectionV24textInterruptMinIntervalSdvgZ
+ _$s26AccessibilitySharedSupport25AXAskRestrictionEvaluatorC6sharedACvgZ
+ _$s26AccessibilitySharedSupport25AXAskRestrictionEvaluatorCMa
+ _$s7SwiftUI10ButtonRoleV6cancelACvgZ
+ _$s7SwiftUI10ButtonRoleVMa
+ _$s7SwiftUI10ButtonRoleVMn
+ _$s7SwiftUI45_AccessibilityIgnoresInvertColorsViewModifierVAA0gH0AAWP
+ _$s7SwiftUI6ButtonVA2A4TextVRszrlE_4role6actionACyAEGqd___AA0C4RoleVSgyyctcSyRd__lufC
+ _$sBi32_WV
+ _$sSS5countSivg
+ _OBJC_CLASS_$_ARWorldTrackingConfiguration
+ _OBJC_CLASS_$_AVCaptureDeviceRotationCoordinator
+ _OBJC_CLASS_$_NSProcessInfo
- _$s16MagnifierSupport12MAGARServiceC12eventHandler19captureSessionQueueAcA010MAGAREventE0C_So17OS_dispatch_queueCtcfc
- _$s16MagnifierSupport22MAGImageCaptionServiceC013generateImageD03forSSAA23MAGCVPixelBufferWrapperC_tYaKF
- _$s16MagnifierSupport22MAGImageCaptionServiceC013generateImageD03forSSAA23MAGCVPixelBufferWrapperC_tYaKFTu
- _$s16MagnifierSupport26MAGVQAOnboardingControllerC13dismissAction9tintColorACyyc_So7UIColorCtcfc
- _$s7SwiftUI45_AccessibilityIgnoresInvertColorsViewModifierVAA0gH0AAMc
- _$s7SwiftUI45_AccessibilityIgnoresInvertColorsViewModifierVN
CStrings:
+ "$__lazy_storage_$_rotationCoordinator"
+ "%s: Scenes mode active — restarting scene description"
+ "%s: Session finished but still speaking. Stopping speech."
+ "%s: Will start new one-shot scene description session"
+ "Ask found stale camera feed (age=%fs) — recovered=%{bool}d after %ldms. rdar://181350682"
+ "Image descriptions: announcing scene caption '%{sensitive}s'"
+ "Image descriptions: could not fingerprint frame; skipping"
+ "Image descriptions: frame too blurry; skipping scene caption"
+ "Image descriptions: generating scene caption (%ld frames skipped since last)"
+ "Image descriptions: no notable change; not announcing"
+ "PCC text detection returned no text; will retry PCC on the next frame"
+ "PCC text detection skipped: image too blurry"
+ "PCC text detection unavailable, falling back to on-device OCR: %@"
+ "Text detection: sending frame to PCC"
+ "Text detection: used PCC (%ld chars)"
+ "Text detection: using on-device OCR"
+ "_showingRestrictionAlert"
+ "configurableCaptureDeviceForPrimaryCamera"
+ "handleStopSpeechGesture"
+ "handleStopSpeechGesture()"
+ "hashDistanceThreshold"
+ "inFlightTextFingerprint"
+ "initWithDevice:previewLayer:"
+ "lastPixelBufferOrientation"
+ "lastPixelBufferUpdateUptime"
+ "lastTextInterruptCheckTime"
+ "luminanceThreshold"
+ "parentalRestriction.alert.message"
+ "parentalRestriction.alert.ok"
+ "parentalRestriction.alert.title"
+ "pixelBufferUpdateCount"
+ "processInfo"
+ "request.error.camera.stalled.abbreviated"
+ "systemUptime"
+ "textDetectionTask"
+ "videoRotationAngleForHorizonLevelCapture"
- "%s: Current session is nil or isFinished. Will start new one-shot scene description session"
```
