## AvatarKit

> `/System/Library/PrivateFrameworks/AvatarKit.framework/AvatarKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77bb0` | `0x777d8` | **`-0x3d8`** |
| `__TEXT.__const` | `0xa4c` | `0xb2c` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x2818` | `0x27f0` | **`-0x28`** |
| `__TEXT.__cstring` | `0x1df64` | `0x1df4c` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0xde4` | `0xdd0` | **`-0x14`** |
| `__AUTH_CONST.__objc_const` | `0xdd58` | `0xdd48` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d78` | `0x3d88` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x54b4` | `0x54c4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1be0` | `0x1bd0` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x798` | `0x790` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x9e8` | `0x9e0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xa54` | `0xa50` | **`-0x4`** |

### Other Changes

```diff

-367.0.0.0.0
+368.0.0.0.0

-  Functions: 2530
-  Symbols:   4668
-  CStrings:  5160
+  Functions: 2529
+  Symbols:   4666
+  CStrings:  5159
Symbols:
+ +[AVTFaceTrackingInfo dataWithARFrame:videoRotationAngle:]
+ +[AVTFaceTrackingInfo trackingInfoWithARFrame:worldAlignment:videoRotationAngle:]
+ +[AVTFaceTrackingInfo trackingInfoWithARFrame:worldAlignment:videoRotationAngle:constrainHeadPose:]
+ -[AVTARMaskRenderer updateWithARFrame:fallBackDepthData:videoRotationAngle:mirroredDepthData:]
+ -[AVTFaceTracker captureDevicePreviewLayer]
+ -[AVTFaceTracker session:didChangeViewRotationAngle:]
+ -[AVTFaceTracker setCaptureDevicePreviewLayer:]
+ -[AVTFaceTracker updateWithARFrame:videoRotationAngle:constrainHeadPose:mirroredDepthData:]
+ -[AVTFaceTracker updateWithARFrame:worldAlignment:fallBackDepthData:videoRotationAngle:constrainHeadPose:mirroredDepthData:]
+ -[AVTFaceTracker videoRotationAngle]
+ GCC_except_table115
+ GCC_except_table47
+ GCC_except_table49
+ GCC_except_table82
+ GCC_except_table92
+ _OBJC_IVAR_$_AVTARMaskRenderer._indexedVideoRotationAngle
+ _OBJC_IVAR_$_AVTFaceTracker._captureDevicePreviewLayer
+ _OBJC_IVAR_$_AVTFaceTracker._indexedVideoRotationAngle
+ __AVTConvertARFaceAnchorTransformToVFXTransform
+ __AVTConvertARFaceAnchorTransformToVFXTransform.kAVTRotationMatrices
+ __AVTGetVideoRotationAngleFromCaptureOrientationAndInterfaceOrientation
+ __AVTGetVideoRotationAngleFromCaptureOrientationAndInterfaceOrientation.kIndexedRotationAngles
+ ___124-[AVTFaceTracker updateWithARFrame:worldAlignment:fallBackDepthData:videoRotationAngle:constrainHeadPose:mirroredDepthData:]_block_invoke
+ _kAVTCaptureDeviceTextureCoordinates
+ _projectionMatrixForViewportSize:zNear:zFar:.kRotationAngles
+ _session:didChangeViewRotationAngle:.kIndexedRotationAngles
+ _trackingInfoWithARFrame:inputOrientation:outputOrientation:constrainHeadPose:.kAVTInterfaceOrientationsToCaptureVideoOrientations
- +[AVTFaceTrackingInfo dataWithARFrame:captureOrientation:interfaceOrientation:]
- +[AVTFaceTrackingInfo trackingInfoWithARFrame:worldAlignment:captureOrientation:interfaceOrientation:]
- +[AVTFaceTrackingInfo trackingInfoWithARFrame:worldAlignment:captureOrientation:interfaceOrientation:constrainHeadPose:]
- -[AVTARMaskRenderer updateWithARFrame:fallBackDepthData:captureOrientation:interfaceOrientation:mirroredDepthData:]
- -[AVTARMaskRenderer updateWithDepthTexture:captureOrientation:interfaceOrientation:mirroredDepthData:]
- -[AVTFaceTracker captureVideoOrientation]
- -[AVTView _windowDidRotateNotification:]
- -[AVTView didMoveToWindow]
- GCC_except_table118
- GCC_except_table44
- GCC_except_table50
- GCC_except_table55
- GCC_except_table85
- GCC_except_table95
- _ARCameraToDisplayRotation
- _AVTARKitTransformToSceneKitTransformMatrix
- _AVTARKitTransformToSceneKitTransformMatrix.rotationMatrices
- _AVTSceneKitTextureCoordinatesForCaptureDeviceTexture
- _AVTVideoCaptureOrientationFromInterfaceOrientation.orientations
- _OBJC_IVAR_$_AVTARMaskRenderer._interfaceOrientation
- _OBJC_IVAR_$_AVTFaceTracker._captureVideoOrientation
- _OBJC_IVAR_$_AVTFaceTracker._interfaceOrientation
- _OBJC_IVAR_$_AVTView._windowDidRotateObserver
- _UIWindowDidRotateNotification
- ___112-[AVTFaceTracker updateWithARFrame:captureOrientation:interfaceOrientation:constrainHeadPose:mirroredDepthData:]_block_invoke
- ___145-[AVTFaceTracker updateWithARFrame:worldAlignment:fallBackDepthData:captureOrientation:interfaceOrientation:constrainHeadPose:mirroredDepthData:]_block_invoke
- ___26-[AVTView didMoveToWindow]_block_invoke
- ___block_descriptor_40_e8_32w_e24_v16?0"NSNotification"8lw32l8
- __convertARFaceAnchorTransformToSceneKitTransform
CStrings:
- "v16@?0@\"NSNotification\"8"
```
