## MagnifierAngel

> `/Applications/MagnifierAngel.app/MagnifierAngel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80bac` | `0x814fc` | **`+0x950`** |
| `__TEXT.__eh_frame` | `0x4844` | `0x489c` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x3260` | `0x3290` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2c38` | `0x2c60` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1d50` | `0x1d70` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1938` | `0x1950` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0xc2c` | `0xc40` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xae8` | `0xaf8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x18ee` | `0x18fe` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x169d` | `0x168d` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x3e4` | `0x3f4` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-275.0.0.0.0
+278.0.0.0.0

-  Functions: 2116
-  Symbols:   1415
+  Functions: 2125
+  Symbols:   1420
Symbols:
+ _$s16MagnifierSupport14MAGOutputEventV12loopScanning6source11environmentAcA0cD6SourceO_AA0cD11EnvironmentOtFZ
+ _$s16MagnifierSupport26MAGGenerativeModelsServiceC013frameProviderE0013textDetectionE0012imageCaptionE012eventHandler015documentFramingE022pulseFeedbackProcessor017sceneIntelligenceE016analyticsSurfaceAcA08MAGFramegE0C_AA07MAGTextiE0CAA08MAGImagekE0CAA016MAGAdvancedEventM0CAA011MAGDocumentoE0CAA08MAGPulseqR0CAA08MAGScenetE0C0A8Services012MAGAnalyticsV0Otcfc
+ _$s16MagnifierSupport26MAGGenerativeModelsServiceC34handleSceneDescriptionModelRequest14capturedImages28additionalSystemInstructions010peripheralL029shouldAnnounceErrorConditions16imageOrientationSSSaySo11CVBufferRefaG_SSSgS2bSo015CGImagePropertyV0VSgtYaKF
+ _$s16MagnifierSupport26MAGGenerativeModelsServiceC34handleSceneDescriptionModelRequest14capturedImages28additionalSystemInstructions010peripheralL029shouldAnnounceErrorConditions16imageOrientationSSSaySo11CVBufferRefaG_SSSgS2bSo015CGImagePropertyV0VSgtYaKFTu
+ _$s16MagnifierSupport26MAGGenerativeModelsServiceC41setConversationStartedWithDefaultQuestionyySbF
+ _$s16MagnifierSupport8MAGErrorO27GenerativeModelsErrorReasonO30inputFailedMultimodalGuardrailyA2EmFWC
+ _$s16MagnifierSupport8MAGErrorO27GenerativeModelsErrorReasonO31inputDetectedAsJailbreakAttemptyA2EmFWC
+ _$s17MagnifierServices19MAGAnalyticsSurfaceO15liveRecognitionyA2CmFWC
+ _$s17MagnifierServices19MAGAnalyticsSurfaceOMa
- _$s16MagnifierSupport14MAGSoundEffectO12loopScanningyA2CmFWC
- _$s16MagnifierSupport26MAGGenerativeModelsServiceC013frameProviderE0013textDetectionE0012imageCaptionE012eventHandler015documentFramingE022pulseFeedbackProcessor017sceneIntelligenceE0AcA08MAGFramegE0C_AA07MAGTextiE0CAA08MAGImagekE0CAA016MAGAdvancedEventM0CAA011MAGDocumentoE0CAA08MAGPulseqR0CAA08MAGScenetE0Ctcfc
- _$s16MagnifierSupport26MAGGenerativeModelsServiceC34handleSceneDescriptionModelRequest14capturedImages28additionalSystemInstructions010peripheralL029shouldAnnounceErrorConditionsSSSaySo11CVBufferRefaG_SSSgS2btYaKF
- _$s16MagnifierSupport26MAGGenerativeModelsServiceC34handleSceneDescriptionModelRequest14capturedImages28additionalSystemInstructions010peripheralL029shouldAnnounceErrorConditionsSSSaySo11CVBufferRefaG_SSSgS2btYaKFTu
CStrings:
+ "LiveRecognitionPromptDelegate submitting prompt='%s' isFollowUp=%{bool}d transcriptCount=%ld"
+ "generateSceneDecriptionFromDeviceImage(_:orientation:_:)"
- "[AngelContext] LiveRecognitionPromptDelegate submitting prompt='%s' isFollowUp=%{bool}d transcriptCount=%ld"
- "generateSceneDecriptionFromDeviceImage(_:_:)"
```
