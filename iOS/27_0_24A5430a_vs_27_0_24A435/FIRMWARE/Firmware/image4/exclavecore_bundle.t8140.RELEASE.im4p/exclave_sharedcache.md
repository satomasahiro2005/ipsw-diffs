## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeb5250` | `0xebf848` | **`+0xa5f8`** |
| `__TEXT.__cstring` | `0xaefb1` | `0xb0c81` | **`+0x1cd0`** |
| `__DATA.__data` | `0x5b808` | `0x5be78` | **`+0x670`** |
| `__TEXT.__constg_swiftt` | `0x71dc4` | `0x7241c` | **`+0x658`** |
| `__TEXT.__const` | `0x1eb9d4` | `0x1ebe34` | **`+0x460`** |
| `__TEXT.__swift5_reflstr` | `0x49b68` | `0x49fc8` | **`+0x460`** |
| `__DATA.__const` | `0x13b978` | `0x13bdd0` | **`+0x458`** |
| `__TEXT.__swift5_fieldmd` | `0x79c5c` | `0x79fc8` | **`+0x36c`** |
| `__TEXT.__swift5_typeref` | `0x30f0a` | `0x31114` | **`+0x20a`** |
| `__TEXT.__eh_frame` | `0x80e1c` | `0x81004` | **`+0x1e8`** |
| `__DATA.__auth_ptr` | `0x7c70` | `0x7d28` | **`+0xb8`** |
| `__TEXT.__swift5_proto` | `0xbe10` | `0xbe54` | **`+0x44`** |
| `__TEXT.__swift5_types` | `0x77ec` | `0x7828` | **`+0x3c`** |
| `__TEXT.__swift5_assocty` | `0xfa30` | `0xfa60` | **`+0x30`** |
| `__TEXT.__swift5_mpenum` | `0xda8` | `0xdc8` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x2b84` | `0x2b98` | **`+0x14`** |
| `__DATA.__common` | `0x4811` | `0x4821` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x1494` | `0x14a4` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__TIGHTBEAM`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`
- `__PDATA.__mod_init_func`
- `__PDATA.__shared_cache`
- `__TEXT.__chain_fixups`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 52736
+  Functions: 52805

-  CStrings:  16317
+  CStrings:  16428
CStrings:
+ "  Device state = "
+ " never came on during display wake allowance policy. "
+ " not allowed while strobe alternative indicator is active"
+ ", cutting sensor access"
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Sun Aug  9 21:40:10 PDT 2026; root:AppleImage4_exclavecore-374~17299/ExclaveImage4/RELEASE_ARM64E"
+ "Alternative Indicator Triggered = "
+ "BacklitSunClassifier_V6X"
+ "Build Date: Sun Aug  9 21:08:46 PDT 2026"
+ "DEFAULT INDICATOR MACHINE: "
+ "Default display changed policy canceled ("
+ "Default display changed policy resolved @ GLTB "
+ "Default display changed policy violated @ GLTB "
+ "Display POST Failed = "
+ "Display issue detected: continuing to use health checks until microphone is turned on"
+ "Display issue detected: switching to strobe alternative indicator"
+ "Display power policy canceled ("
+ "Display power policy resolved @ GLTB "
+ "Display power policy violated @ GLTB "
+ "Enforcing new MOT @ GLTB "
+ "ExclaveOS Image4 Framework Version 7.0.0: Sun Aug  9 21:40:10 PDT 2026; root:AppleImage4_exclavecore-374~17299/ExclaveImage4/RELEASE_ARM64E"
+ "FaceDetectionIR_V6X"
+ "FaceDetectionRGB_V6X"
+ "FaceLivelinessFull_Int"
+ "FaceLivelinessFull_UC"
+ "Faceliveliness_UC"
+ "Failed to end strobe"
+ "Failed to end strobe after MOT met"
+ "Failed to get Medina state"
+ "Failed to notify corerepaird of strobe start"
+ "Failed to prepare strobe"
+ "Failed to prepare strobe before MOT was met"
+ "Failed to update strobe before MOT was met"
+ "Failed to update strobe power state"
+ "Failed to update strobe power state to "
+ "Force TCON Threshold Exceeded = "
+ "GlassesClassifierIR_V6X"
+ "GlassesClassifierRGB_V6X"
+ "GlassesClassifier_V6X"
+ "INDICATOR: CAM -> OFF ("
+ "INDICATOR: MIC -> OFF ("
+ "INDICATOR: STROBE ALT -> OFF"
+ "INDICATOR: STROBE ALT -> ON"
+ "INDICATOR: STROBE ALT -> PENDING STOP"
+ "INDICATOR: STROBE ALT -> PENDING STOP CANCELED"
+ "INDICATOR: STROBE ALT -> PREPARE"
+ "INDICATOR: STROBE FLASH ALT -> DONE"
+ "INDICATOR: STROBE FLASH ALT -> OFF"
+ "INDICATOR: STROBE FLASH ALT -> ON"
+ "INDICATOR: STROBE FLASH ALT -> PENDING STOP"
+ "INDICATOR: STROBE FLASH ALT -> PENDING STOP CANCELED"
+ "INDICATOR: STROBE FLASH ALT -> PREPARE"
+ "Invalid start state for strobe flash machine (pending: "
+ "LandmarkSemanticFaceIR_V6X"
+ "LandmarkSemanticFaceRGB_V6X"
+ "MedinaStateAOP/MedinaStateAOP_Swift.swift"
+ "Notified corerepaird of strobe start"
+ "ObstructionDetection_V6X"
+ "Starting default display changed policy @ GLTB "
+ "Starting display power policy @ GLTB "
+ "Sun Aug  9 22:19:50 PDT 2026"
+ "System/ExclaveKit/System/Library/Frameworks/"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/Vision_internal.framework/Resources/faceliveliness_uc_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/Vision_internal.framework/Resources/facelivelinessfull_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/Vision_internal.framework/Resources/facelivelinessfull_uc_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/Vision_internal.framework/Resources/faceprint_uc_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/attention_detection_ir.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/attention_detection_rgb.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/backlit_sun_classifier.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/face_detection.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/face_detection_ir.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/face_detection_rgb.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasses_classifier.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasses_classifier_ir.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasses_classifier_rgb.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswing_net_res1.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswing_net_res2.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswing_net_res3.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswingnet.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswingnet256.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswingnet352.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswingnet512.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswingnet768.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/glasswingnet816.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/landmark_semantic_face.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/landmark_semantic_face_ir.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/landmark_semantic_face_rgb.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/FaceIDCoreLib_exclavekit.framework/models/V6X.bundle/obstruction_detection.bundle/*.bundle"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/ViewingDistance.framework/Resources/model.bundle/*.bundle/main/main_ane"
+ "VIOLATION resolved: "
+ "backlit_sun_classifier.*.hwx"
+ "display powered off"
+ "display-post-failed"
+ "display-post-failed-1"
+ "face_detection_ir.*.hwx"
+ "face_detection_rgb.*.hwx"
+ "glasses_classifier.*.hwx"
+ "glasses_classifier_ir.*.hwx"
+ "glasses_classifier_rgb.*.hwx"
+ "glasswing_net_res1.*.hwx"
+ "glasswing_net_res2.*.hwx"
+ "glasswing_net_res3.*.hwx"
+ "glasswingnet.*.hwx"
+ "glasswingnet256.*.hwx"
+ "glasswingnet352.*.hwx"
+ "glasswingnet512.*.hwx"
+ "glasswingnet768.*.hwx"
+ "glasswingnet816.*.hwx"
+ "ignored in Medina state B"
+ "invalid rawValue for MedinaStateCode: "
+ "landmark_semantic_face_ir.*.hwx"
+ "landmark_semantic_face_rgb.*.hwx"
+ "obstruction_detection.*.hwx"
+ "octopus_fang_alt_indicator"
+ "octopus_force_alt_indicator"
+ "octopus_force_display_POST_failed"
+ "octopus_force_tcon_threshold_exceeded"
+ "octopus_no_fang_alt_indicator"
+ "policy-alt-indicator"
+ "unknown indicator"
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Mon Aug 10 00:47:09 PDT 2026; root:AppleImage4_exclavecore-374~17307/ExclaveImage4/RELEASE_ARM64E"
- "Build Date: Sun Aug  9 22:40:38 PDT 2026"
- "ExclaveOS Image4 Framework Version 7.0.0: Mon Aug 10 00:47:09 PDT 2026; root:AppleImage4_exclavecore-374~17307/ExclaveImage4/RELEASE_ARM64E"
- "Mon Aug 10 01:23:18 PDT 2026"
- "[B] Start Siri dark wake policy"
- "[B] Start prox policy"
- "[B] Stop Siri dark wake policy"
- "[B] Stop prox policy"
```
