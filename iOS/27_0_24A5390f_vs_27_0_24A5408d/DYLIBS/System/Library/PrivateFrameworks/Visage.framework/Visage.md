## Visage

> `/System/Library/PrivateFrameworks/Visage.framework/Visage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9b644` | `0x9c534` | **`+0xef0`** |
| `__TEXT.__oslogstring` | `0x5c5a` | `0x5dff` | **`+0x1a5`** |
| `__TEXT.__gcc_except_tab` | `0xf268` | `0xf3d0` | **`+0x168`** |
| `__AUTH_CONST.__objc_const` | `0xa0c0` | `0xa1b0` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x452c` | `0x4584` | **`+0x58`** |
| `__TEXT.__cstring` | `0x54f8` | `0x5548` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x46e0` | `0x4700` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x510` | `0x530` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3770` | `0x3790` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x724` | `0x73c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2728` | `0x2740` | **`+0x18`** |
| `__TEXT.__const` | `0x34c0` | `0x34d0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x7b0` | `0x7b8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1d8` | `0x1e0` | **`+0x8`** |

### Other Changes

```diff

-279.0.9.0.0
+279.0.11.0.0

-  Functions: 3062
-  Symbols:   5100
-  CStrings:  1380
+  Functions: 3070
+  Symbols:   5116
+  CStrings:  1393
Symbols:
+ -[VGEarPCACaptureOptions setUseDepth:]
+ -[VGEarPCACaptureOptions useDepth]
+ -[VGFaceCaptureOptions setUseDepth:]
+ -[VGFaceCaptureOptions useDepth]
+ -[VGHRTFEarPCACaptureProcessor initWithDebugDataPath:withModelsRootPath:useDepth:]
+ -[VGHRTFFaceCaptureProcessor initWithDebugDataPath:useDepth:]
+ -[VGHRTFSessionConfig init]
+ -[VGHRTFSessionConfig setUseDepth:]
+ -[VGHRTFSessionConfig useDepth]
+ _OBJC_IVAR_$_VGEarPCACaptureOptions._useDepth
+ _OBJC_IVAR_$_VGFaceCaptureOptions._useDepth
+ _OBJC_IVAR_$_VGHRTFEarPCACaptureProcessor._useDepth
+ _OBJC_IVAR_$_VGHRTFFaceCaptureProcessor._useDepth
+ _OBJC_IVAR_$_VGHRTFPostProcessor._useDepth
+ _OBJC_IVAR_$_VGHRTFSessionConfig._useDepth
+ __ZN2vg13ear_detection18EarPCADetectorImpl13checkDistanceEPK9IOSurfaceS4_RKDv4_f
+ __ZN2vg13ear_detection19classifyEarDistanceERKDv4_ff
+ __ZN2vg4hrtf22writeSelectedRGBFramesENSt3__14spanIU8__strongKP9IOSurfaceLm18446744073709551615EEENS1_17basic_string_viewIcNS1_11char_traitsIcEEEESA_
+ __ZN2vg4hrtf7Rectify6createEb
+ __ZN2vg4hrtf7RectifyC1Eb
+ __ZN2vg4hrtf7RectifyC2Eb
+ ___block_descriptor_48_e5_v8?0l
+ _kCVAFaceTracking_ColorOnly
- -[VGHRTFEarPCACaptureProcessor initWithDebugDataPath:withModelsRootPath:]
- -[VGHRTFFaceCaptureProcessor initWithDebugDataPath:]
- __ZN2vg4hrtf7Rectify6createEv
- __ZN2vg4hrtf7RectifyC1Ev
- __ZN2vg4hrtf7RectifyC2Ev
- ___58-[VGHRTFFaceCaptureProcessor processCaptureData:faceData:]_block_invoke_4
- ___60-[VGHRTFEarPCACaptureProcessor processCaptureData:faceData:]_block_invoke_2
CStrings:
+ " HRTF post-processing skipped: useDepth=NO (frame selection only). "
+ " Missing lens calibration on captureData. "
+ " Rectify configured for %s but call provided %s. "
+ " Unable to write selected frame %.*s_%zu. "
+ " VGFaceKitTracker useDepth=NO but per-frame data.depth is non-nil; ignoring. "
+ " VGFaceKitTracker useDepth=YES but per-frame data.depth is nil; failing frame. "
+ "/selected_"
+ "Input image size (%u x %u) Frame count threshold %u Ear bbox detection visibility threshold %f Ear landmark detection visibility threshold %f Use ear side smooth predictor %@ (buffer capacity: %u, confidence threshold: %f) Use motion blur filter %@ Motion blur filter threshold %fFace yaw limit %f Use depth %@"
+ "Selector configured with useDepth=NO but per-frame depth is non-nil; depth will be ignored."
+ "Yaw Poses %lu (limit %.f) Pitch Poses %lu (limit %.f) Expressions %@ Eyes Forward Sensitivity (yaw %g, pitch %g) Selection Frustum Offsets (non-front poses): { %@ } Selection Frustum Offsets (front pose): { %@ } Use FoV Margin: front pose [%@], non front poses [%@] Margins Head Ratio (left %g, right %g, top %g, bottom %g) Margins Head Ratio Front Pose (left %g, right %g, top %g, bottom %g) Bottom margin front pose delta %g Bottom margin pitch pose delta %g Ensure Eyes Forward On Front Pose %@ (use look-at check: %@) Eyes Open Sensitivity %g Neutral Expression Lower Bound %g Neutral Expression Upper Bound %g Ensure Eyes Open On Front Pose %@ Ensure Eyes Open On Non Front Pose %@ Ensure Almost Neutral Expression On Front Pose %@ Ensure Almost Neutral Expression On Non Front Pose %@ Face Tracking Result Set in VGCaptureData %@ Use FaceKit Tracker internal Face Detector %@ Use FaceKit Force CPU %@ Convert FaceKit tracking dictionary to ARKit tracking dictionary %@ Send Metrics %@ Use simple selector: %@ (min offset: %g, max offset: %g) Use distance filter: %@ (close threshold: %g cm, far threshold: %g cm) Body Pose Guidance Options: { %@ } Use Vision Filters %@ (during Frame Selection) Use Vision Filters %@ (during Enrollment) Vision Front Pose Blink Confidence Threshold %g Use computed depth bounding box %@ Use computed depth bounding box for poses with bad alignment %@ Use ambient light filter %@ (low threshold: %g) Use tracked face identifier filter %@ Use Vision face landmarks filter %@ Use Motion Blur Filter %@ (threshold: %g) Use Depth %@"
+ "_"
+ "color-only"
+ "depth+color"
+ "left_ear"
+ "useDepth"
+ "\xf0&"
- " Failed to rectify face images. "
- "Input image size (%u x %u) Frame count threshold %u Ear bbox detection visibility threshold %f Ear landmark detection visibility threshold %f Use ear side smooth predictor %@ (buffer capacity: %u, confidence threshold: %f) Use motion blur filter %@ Motion blur filter threshold %fFace yaw limit %f"
- "Yaw Poses %lu (limit %.f) Pitch Poses %lu (limit %.f) Expressions %@ Eyes Forward Sensitivity (yaw %g, pitch %g) Selection Frustum Offsets (non-front poses): { %@ } Selection Frustum Offsets (front pose): { %@ } Use FoV Margin: front pose [%@], non front poses [%@] Margins Head Ratio (left %g, right %g, top %g, bottom %g) Margins Head Ratio Front Pose (left %g, right %g, top %g, bottom %g) Bottom margin front pose delta %g Bottom margin pitch pose delta %g Ensure Eyes Forward On Front Pose %@ (use look-at check: %@) Eyes Open Sensitivity %g Neutral Expression Lower Bound %g Neutral Expression Upper Bound %g Ensure Eyes Open On Front Pose %@ Ensure Eyes Open On Non Front Pose %@ Ensure Almost Neutral Expression On Front Pose %@ Ensure Almost Neutral Expression On Non Front Pose %@ Face Tracking Result Set in VGCaptureData %@ Use FaceKit Tracker internal Face Detector %@ Use FaceKit Force CPU %@ Convert FaceKit tracking dictionary to ARKit tracking dictionary %@ Send Metrics %@ Use simple selector: %@ (min offset: %g, max offset: %g) Use distance filter: %@ (close threshold: %g cm, far threshold: %g cm) Body Pose Guidance Options: { %@ } Use Vision Filters %@ (during Frame Selection) Use Vision Filters %@ (during Enrollment) Vision Front Pose Blink Confidence Threshold %g Use computed depth bounding box %@ Use computed depth bounding box for poses with bad alignment %@ Use ambient light filter %@ (low threshold: %g) Use tracked face identifier filter %@ Use Vision face landmarks filter %@ Use Motion Blur Filter %@ (threshold: %g)"
```
