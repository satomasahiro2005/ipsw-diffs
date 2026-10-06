## CoreRecognition

> `/System/Library/PrivateFrameworks/CoreRecognition.framework/CoreRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b654` | `0x5b2dc` | **`-0x378`** |
| `__TEXT.__const` | `0x7bc` | `0x744` | **`-0x78`** |
| `__TEXT.__objc_methlist` | `0x2394` | `0x23ec` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x2030` | `0x2078` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x5e0` | `0x5a0` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x3900` | `0x3938` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x8744` | `0x8758` | **`+0x14`** |
| `__TEXT.__cstring` | `0x4b56` | `0x4b5f` | **`+0x9`** |
| `__DATA.__bss` | `0x98` | `0x90` | **`-0x8`** |
| `__DATA_CONST.__const` | `0xac8` | `0xad0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x58` | `0x60` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2c8` | `0x2cc` | **`+0x4`** |

### Other Changes

```diff

-446.11.0.0.0
+446.13.0.0.0

-  Functions: 1124
-  Symbols:   2351
-  CStrings:  2129
+  Functions: 1122
+  Symbols:   2331
+  CStrings:  2127
Symbols:
+ +[CRCameraReader boundsForPaddedCornersOfBoundingBox:padding:topLeft:topRight:bottomRight:bottomLeft:]
+ +[CRCameraReader extractCardImage:fromPixelBuffer:withCardBuffer:withPoints:cameraIntrinsicData:inputImage:]
+ +[CRCameraReader extractCardImage:fromPixelBuffer:withCardBuffer:withPoints:cameraIntrinsicData:padding:inputOrientation:unpaddedCardImage:inputImage:]
+ +[CRCameraReader inputOrientationForCaptureAngle:]
+ -[CRCameraReader findIDObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]
+ -[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]
+ -[CRDefaultCaptureSessionManager captureBufferRotationAngle]
+ -[CRDefaultCaptureSessionManager dealloc]
+ -[CRDefaultCaptureSessionManager observeValueForKeyPath:ofObject:change:context:]
+ -[CRDefaultCaptureSessionManager rotationCoordinator]
+ -[CRDefaultCaptureSessionManager setRotationCoordinator:]
+ -[CRDefaultCaptureSessionManager setupRotationCoordinatorForDevice:]
+ -[CRDefaultCaptureSessionManager teardownRotationCoordinator]
+ -[CRDefaultCaptureSessionManager updatePreviewRotationFromCoordinator]
+ GCC_except_table109
+ GCC_except_table113
+ GCC_except_table116
+ GCC_except_table127
+ GCC_except_table130
+ GCC_except_table132
+ GCC_except_table136
+ GCC_except_table139
+ GCC_except_table149
+ GCC_except_table168
+ GCC_except_table174
+ GCC_except_table184
+ GCC_except_table186
+ GCC_except_table189
+ GCC_except_table193
+ GCC_except_table195
+ GCC_except_table197
+ GCC_except_table203
+ GCC_except_table209
+ GCC_except_table210
+ GCC_except_table30
+ GCC_except_table33
+ GCC_except_table363
+ GCC_except_table366
+ GCC_except_table369
+ GCC_except_table37
+ GCC_except_table41
+ GCC_except_table51
+ GCC_except_table58
+ GCC_except_table62
+ GCC_except_table69
+ GCC_except_table83
+ GCC_except_table86
+ GCC_except_table99
+ _OBJC_CLASS_$_AVCaptureDeviceRotationCoordinator
+ _OBJC_IVAR_$_CRDefaultCaptureSessionManager._rotationCoordinator
+ __Z10ccCardRectf
+ __Z18ccUnitRectToMMRect6CGRect
+ __Z18isLeastBlurryFrameP7CIImageP14NSMutableArrayi
+ __Z27ccArea1RectScaleIndependentv
+ __Z27ccArea2RectScaleIndependentv
+ __Z28ccUnitRectToMMRectIsPortrait6CGRectb
+ __ZL24CRCameraReaderFrameImageP10__CVBufferPK14__CFDictionary
+ ___26-[CRCameraReader loadView]_block_invoke_3
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_10
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_11
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_12
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_13
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_14
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_15
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_17
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_2
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_3
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_4
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_5
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_6
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_7
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_8
+ ___85-[CRCameraReader findObjects:inPixelBuffer:frameImage:cameraIntrinsicData:frameTime:]_block_invoke_9
+ ___block_descriptor_56_ea8_32s40s48s_e42_v48?0^{__CVBuffer=}8"NSData"16{?=qiIq}24ls32l8s40l8s48l8
+ _kCRPreviewRotationContext
+ _objc_release_x2
- +[ActivationMapTools colInImage:forPoint:inActivationMapWithSize:]
- +[CRCameraReader extractCardImage:fromPixelBuffer:withCardBuffer:cameraIntrinsicData:]
- +[CRCameraReader extractCardImage:fromPixelBuffer:withCardBuffer:withPoints:cameraIntrinsicData:]
- +[CRCameraReader extractCardImage:fromPixelBuffer:withCardBuffer:withPoints:cameraIntrinsicData:padding:inputOrientation:]
- +[CRCameraReader extractCardImage:fromPixelBuffer:withCardBuffer:withPoints:cameraIntrinsicData:padding:inputOrientation:unpaddedCardImage:]
- -[CRCameraReader aetPlacementTextColor:]
- -[CRCameraReader findIDObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]
- -[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]
- GCC_except_table103
- GCC_except_table110
- GCC_except_table114
- GCC_except_table117
- GCC_except_table129
- GCC_except_table131
- GCC_except_table134
- GCC_except_table142
- GCC_except_table150
- GCC_except_table169
- GCC_except_table175
- GCC_except_table185
- GCC_except_table188
- GCC_except_table191
- GCC_except_table194
- GCC_except_table196
- GCC_except_table198
- GCC_except_table206
- GCC_except_table207
- GCC_except_table31
- GCC_except_table34
- GCC_except_table362
- GCC_except_table365
- GCC_except_table368
- GCC_except_table40
- GCC_except_table42
- GCC_except_table52
- GCC_except_table65
- GCC_except_table70
- GCC_except_table71
- GCC_except_table77
- GCC_except_table78
- GCC_except_table96
- _CFDataGetBytePtr
- _CFDictionaryCreateMutable
- _CFDictionarySetValue
- _CGDataProviderCopyData
- _CGImageGetAlphaInfo
- _CGImageGetBitsPerPixel
- _CGImageGetBytesPerRow
- _CGImageGetDataProvider
- _CGImageGetHeight
- _CGImageGetWidth
- _CVPixelBufferCreate
- _IOServiceGetMatchingService
- _IOServiceMatching
- __ZL11setIntValueP14__CFDictionaryPK10__CFStringi
- __ZL6hasVXDv
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_10
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_11
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_12
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_13
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_14
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_15
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_17
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_2
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_3
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_4
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_5
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_6
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_7
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_8
- ___74-[CRCameraReader findObjects:inPixelBuffer:cameraIntrinsicData:frameTime:]_block_invoke_9
- ___block_descriptor_48_ea8_32s40s_e42_v48?0^{__CVBuffer=}8"NSData"16{?=qiIq}24ls32l8s40l8
- _allocatePixel8Buffer
- _calculateImageBlur
- _ccArea1Rect
- _ccArea1RectScaleIndependent
- _ccArea2Rect
- _ccArea2RectScaleIndependent
- _ccCardRect
- _ccMMRectToUnitRect
- _ccMMRectToUnitRectIsPortait
- _ccUnitRectToMMRect
- _ccUnitRectToMMRectIsPortrait
- _createPlanar420PixelBufferFromImageFile
- _isLeastBlurryFrame
- _kCVPixelBufferIOSurfacePropertiesKey
- _kIOMainPortDefault
- _kIOSurfaceAllocSize
- _kIOSurfaceBytesPerRow
- _kIOSurfaceCacheMode
- _kIOSurfaceHeight
- _kIOSurfaceMemoryRegion
- _kIOSurfacePixelFormat
- _kIOSurfaceWidth
- _rotateBuffer180
- _vImageRotate90_Planar8
CStrings:
+ "CoreRecognition: Unable to display camera view due to connection inturrupted notification %@"
+ "CoreRecognition: Unable to display camera view due to device in use by another client %@"
+ "CoreRecognition: Unable to display camera view due to device unavailable in the background %@"
+ "CoreRecognition: Unable to display camera view while running multiple foreground applications %@"
+ "videoRotationAngleForHorizonLevelPreview"
- "AppleVXD375"
- "AppleVXD390"
- "CoreRecogntion: Unable to display camera view due to connection inturrupted notification %@"
- "CoreRecogntion: Unable to display camera view due to device in use by another client %@"
- "CoreRecogntion: Unable to display camera view due to device unavailable in the background %@"
- "CoreRecogntion: Unable to display camera view while running multiple foreground applications %@"
- "PurpleGfxMem"
```
