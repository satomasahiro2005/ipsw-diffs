## HRTFEnrollment

> `/System/Library/PrivateFrameworks/HRTFEnrollment.framework/HRTFEnrollment`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x969c` | `0xb118` | **`+0x1a7c`** |
| `__TEXT.__oslogstring` | `0x52d` | `0x719` | **`+0x1ec`** |
| `__TEXT.__objc_methlist` | `0x8d8` | `0x928` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x828` | `0x858` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1ea8` | `0x1ec8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x350` | `0x360` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x200` | **`+0x10`** |
| `__TEXT.__const` | `0xd4` | `0xe4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x350` | `0x360` | **`+0x10`** |
| `__DATA.__bss` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__cstring` | `0x9a7` | `0x9ac` | **`+0x5`** |
| `__DATA.__objc_ivar` | `0x138` | `0x13c` | **`+0x4`** |

### Other Changes

```diff

-40.41.1.1.7
+40.41.1.1.10

-  Functions: 189
-  Symbols:   604
-  CStrings:  164
+  Functions: 196
+  Symbols:   617
+  CStrings:  175
Symbols:
+ -[HRTFEnrollmentSession _verifyNonDepthFormatCaptureDevice:]
+ -[HRTFEnrollmentSession didReceiveNonDepthFormatVideoData:colorData:depthData:faceObject:]
+ -[HRTFEnrollmentSession initializeNonDepthFormatDevice]
+ -[HRTFSyncedCaptureSource _configureNonDepthFormatVideoOutputsForDevice:inSession:]
+ -[HRTFSyncedCaptureSource _initializeForNonDepthFormat]
+ -[HRTFSyncedCaptureSource _verifyNonDepthFormatCaptureDevice:]
+ -[HRTFSyncedCaptureSource dataOutputSynchronizerForNonDepthFormat:didOutputSynchronizedDataCollection:]
+ _AVCaptureDeviceTypeBuiltInWideAngleCamera
+ _CGPointZero
+ _HRTFDepthFormatNotSupported.sDepthFormatNotSupported
+ _MGIsDeviceOfType
+ _OBJC_IVAR_$_HRTFEnrollmentSession._dummyDepthPixelBuffer
+ _objc_retain_x27
CStrings:
+ "Non Depth: capture device color format: %s"
+ "Non Depth: failed to verify color format for capture device"
+ "NonDepth: Depth format not supported, fill in with dummy data for cameraCalibrationData"
+ "NonDepth: Depth format not supported, fill in with dummy data for depthPixelBuffer"
+ "NonDepth: cannot retrieve exposure time"
+ "NonDepth: color data is absent"
+ "NonDepth: color instrinsics data is absent"
+ "NonDepth: depth data is absent"
+ "NonDepth: lense calibration data is absent"
+ "NonDepth: video frame arrived"
+ "True"
+ "\xf0Q"
- "\xf0A"
```
