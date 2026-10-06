## motiontrackingd

> `/System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/Support/motiontrackingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a924` | `0x2b728` | **`+0xe04`** |
| `__TEXT.__objc_methname` | `0x9609` | `0x9a71` | **`+0x468`** |
| `__TEXT.__objc_stubs` | `0x71e0` | `0x74a0` | **`+0x2c0`** |
| `__TEXT.__oslogstring` | `0x2455` | `0x267e` | **`+0x229`** |
| `__DATA.__objc_const` | `0x4b58` | `0x4cb8` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x2f84` | `0x306c` | **`+0xe8`** |
| `__TEXT.__const` | `0x30c` | `0x3ec` | **`+0xe0`** |
| `__DATA.__objc_selrefs` | `0x2120` | `0x21d8` | **`+0xb8`** |
| `__TEXT.__gcc_except_tab` | `0xa5c` | `0xa84` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x1e4c` | `0x1e73` | **`+0x27`** |
| `__DATA_CONST.__cfstring` | `0x7a0` | `0x7c0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x978` | `0x998` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xa00` | `0xa20` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x3d8` | `0x3f4` | **`+0x1c`** |
| `__TEXT.__unwind_info` | `0x9f0` | `0xa08` | **`+0x18`** |
| `__DATA.__bss` | `0x370` | `0x380` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x510` | `0x520` | **`+0x10`** |
| `__TEXT.__cstring` | `0x2268` | `0x2278` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`

### Other Changes

```diff

-581.0.0.0.0
+584.0.0.0.0

-  Functions: 1053
-  Symbols:   305
-  CStrings:  2221
+  Functions: 1074
+  Symbols:   307
+  CStrings:  2267
Symbols:
+ _AXSSDeviceIsViridian
+ _mach_timebase_info
CStrings:
+ "AXMTCameraBasedLookAtPointTracker: active display changed; updated mapper bounds to %@"
+ "AXMTFaceKitFaceTracker: alternate head-tracking seed locked after first successful result"
+ "AXMTVideoCapturer: alternate head-tracking could not set videoRotationAngle 0 (default %.0f) for %@"
+ "AXMTVideoCapturer: alternate head-tracking normalized videoRotationAngle %.0f -> %.0f for %@"
+ "AXMT[AltHeadTrackingPose] holding cursor: confidence %ld < %ld (acquiring)"
+ "AXMT[FaceKitQuality] ignoring low-confidence pose (confidenceLevel=%ld < %ld); unlocking seed to re-acquire"
+ "T@\"NSNumber\",&,N,V__altHeadTrackingLastPitch"
+ "T@\"NSNumber\",&,N,V__altHeadTrackingLastYaw"
+ "TB,N,V__altHeadTrackingSeedLocked"
+ "TQ,N,V__altHeadTrackingLastFrameMachTime"
+ "Tq,N,V__altHeadTrackingConfidenceLevel"
+ "Tq,N,V_confidenceLevel"
+ "T{CGPoint=dd},N,V__altHeadTrackingInterfacePoint"
+ "__altHeadTrackingConfidenceLevel"
+ "__altHeadTrackingInterfacePoint"
+ "__altHeadTrackingLastFrameMachTime"
+ "__altHeadTrackingLastPitch"
+ "__altHeadTrackingLastYaw"
+ "__altHeadTrackingSeedLocked"
+ "_altHeadTrackingConfidenceLevel"
+ "_altHeadTrackingInterfacePoint"
+ "_altHeadTrackingLastFrameMachTime"
+ "_altHeadTrackingLastPitch"
+ "_altHeadTrackingLastYaw"
+ "_altHeadTrackingSeedLocked"
+ "_confidenceLevel"
+ "_handleAltHeadTrackingDetectedFaceWithPose:"
+ "_makeFaceKitFaceTracker"
+ "_resetAltHeadTrackingPoseBaseline"
+ "altHeadTrackingOverride"
+ "confidenceLevel"
+ "confidence_level"
+ "isVideoRotationAngleSupported:"
+ "localizedName"
+ "session:didChangeViewRotationAngle:"
+ "setConfidenceLevel:"
+ "setVideoRotationAngle:"
+ "set_altHeadTrackingConfidenceLevel:"
+ "set_altHeadTrackingInterfacePoint:"
+ "set_altHeadTrackingLastFrameMachTime:"
+ "set_altHeadTrackingLastPitch:"
+ "set_altHeadTrackingLastYaw:"
+ "set_altHeadTrackingSeedLocked:"
+ "v32@0:8@\"ARSession\"16d24"
+ "v32@0:8@16d24"
+ "videoRotationAngle"
```
