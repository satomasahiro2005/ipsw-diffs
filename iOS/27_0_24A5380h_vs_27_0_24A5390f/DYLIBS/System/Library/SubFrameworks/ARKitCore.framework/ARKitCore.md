## ARKitCore

> `/System/Library/SubFrameworks/ARKitCore.framework/ARKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x198510` | `0x19a6d8` | **`+0x21c8`** |
| `__AUTH_CONST.__objc_const` | `0x3cc50` | `0x3d080` | **`+0x430`** |
| `__TEXT.__oslogstring` | `0x20960` | `0x20d3d` | **`+0x3dd`** |
| `__TEXT.__objc_methlist` | `0x11234` | `0x1140c` | **`+0x1d8`** |
| `__TEXT.__cstring` | `0x1d885` | `0x1d98c` | **`+0x107`** |
| `__DATA_CONST.__objc_selrefs` | `0x7dc8` | `0x7ec0` | **`+0xf8`** |
| `__AUTH.__objc_data` | `—` | `0xf0` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x13390` | `0x13480` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x6a20` | `0x6ad0` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0xfea0` | `0xff20` | **`+0x80`** |
| `__DATA.__objc_ivar` | `0x1ff8` | `0x2030` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x3490` | `0x34c8` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x3db8` | `0x3dd8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x15c8` | `0x15e8` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x5b8` | `0x5d0` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x38a0` | `0x38b8` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x858` | `0x870` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x880` | `0x898` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x790` | `0x7a8` | **`+0x18`** |
| `__DATA.__bss` | `0x1878` | `0x1888` | **`+0x10`** |
| `__DATA.__data` | `0x1c88` | `0x1c90` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-781.0.1.0.4
+781.0.4.0.0

-  Functions: 7958
-  Symbols:   14489
-  CStrings:  4535
+  Functions: 8008
+  Symbols:   14577
+  CStrings:  4550
Symbols:
+ +[ARFaceTrackingConfiguration clearSupportedVideoFormatsCache]
+ +[ARVideoFormat clearSupportedVideoFormatsCache]
+ +[ARViewRotationContext replayContext]
+ -[ARCamera projectPoint:viewRotationAngle:viewportSize:]
+ -[ARCamera projectionMatrixForViewRotationAngle:viewportSize:zNear:zFar:]
+ -[ARCamera unprojectPoint:ontoPlaneWithTransform:viewRotationAngle:viewportSize:]
+ -[ARCamera viewMatrixForViewRotationAngle:]
+ -[ARFrame displayTransformForViewRotationAngle:viewportSize:]
+ -[ARImageSensor defaultVideoRotationAngle]
+ -[ARImageSensor setDefaultVideoRotationAngle:]
+ -[ARObjectTrackingTechnique _verifyDetectionObjectCount]
+ -[ARParentImageSensor primaryCaptureDevice]
+ -[ARParentImageSensor primaryDefaultVideoRotationAngle]
+ -[ARRotationCoordinatorPreviewAngleSource .cxx_destruct]
+ -[ARRotationCoordinatorPreviewAngleSource dealloc]
+ -[ARRotationCoordinatorPreviewAngleSource initWithLayer:device:previewAngleChangeHandler:]
+ -[ARRotationCoordinatorPreviewAngleSource observeValueForKeyPath:ofObject:change:context:]
+ -[ARSession _currentParentImageSensor]
+ -[ARSession _sessionDidChangeViewRotationAngle:]
+ -[ARSession _updateViewRotationContext]
+ -[ARSession setViewLayer:]
+ -[ARSession setViewRotationAngle:]
+ -[ARSession viewLayer]
+ -[ARSession viewRotationAngle]
+ -[ARVideoFormat captureDevice]
+ -[ARViewRotationAngleProvider .cxx_destruct]
+ -[ARViewRotationAngleProvider _deliverPreviewAngle:]
+ -[ARViewRotationAngleProvider _updatePreviewAngleSource]
+ -[ARViewRotationAngleProvider initWithLayer:handler:context:]
+ -[ARViewRotationAngleProvider updateContext:]
+ -[ARViewRotationAngleProvider weakLayer]
+ -[ARViewRotationContext .cxx_destruct]
+ -[ARViewRotationContext defaultVideoRotationAngle]
+ -[ARViewRotationContext device]
+ -[ARViewRotationContext initWithDevice:defaultVideoRotationAngle:]
+ -[ARViewRotationContext isEqual:]
+ -[ARWorldTrackingTechnique _pushWTResultDataForTimestamp:context:]
+ GCC_except_table135
+ GCC_except_table140
+ GCC_except_table142
+ GCC_except_table143
+ GCC_except_table172
+ GCC_except_table176
+ GCC_except_table179
+ GCC_except_table183
+ GCC_except_table187
+ _ARBackFacingWideImageSensorPixelFormatUserDefaultsKey
+ _ARCameraImageToViewTransformWithAngle
+ _ARCorrectedViewRotationAngleForRotation
+ _ARDisplayRotationFromViewRotationAngle
+ _ARFaceTrackingAdditionalNonBinnedFormatsDefaultsKey
+ _ARInterfaceOrientationFromViewRotationAngle
+ _ARRotationCoordinatorPreviewAngleSourceKVOContext
+ _ARViewRotationAngleFromFrontPreviewAngle
+ _ARViewRotationAngleFromInterfaceOrientation
+ _ARViewRotationAngleFromRearPreviewAngle
+ _ARViewToCameraImageTransformWithAngle
+ _OBJC_CLASS_$_ARRotationCoordinatorPreviewAngleSource
+ _OBJC_CLASS_$_ARViewRotationAngleProvider
+ _OBJC_CLASS_$_ARViewRotationContext
+ _OBJC_CLASS_$_AVCaptureDeviceRotationCoordinator
+ _OBJC_IVAR_$_ARImageSensor._defaultVideoRotationAngle
+ _OBJC_IVAR_$_ARRotationCoordinatorPreviewAngleSource._coordinator
+ _OBJC_IVAR_$_ARRotationCoordinatorPreviewAngleSource._previewAngleChangeHandler
+ _OBJC_IVAR_$_ARSession._currentViewRotationContext
+ _OBJC_IVAR_$_ARSession._viewRotationAngle
+ _OBJC_IVAR_$_ARSession._viewRotationAngleLock
+ _OBJC_IVAR_$_ARSession._viewRotationAngleProvider
+ _OBJC_IVAR_$_ARViewRotationAngleProvider._context
+ _OBJC_IVAR_$_ARViewRotationAngleProvider._handler
+ _OBJC_IVAR_$_ARViewRotationAngleProvider._lastRotationAngle
+ _OBJC_IVAR_$_ARViewRotationAngleProvider._previewAngleSource
+ _OBJC_IVAR_$_ARViewRotationAngleProvider._weakLayer
+ _OBJC_IVAR_$_ARViewRotationContext._defaultVideoRotationAngle
+ _OBJC_IVAR_$_ARViewRotationContext._device
+ _OBJC_METACLASS_$_ARRotationCoordinatorPreviewAngleSource
+ _OBJC_METACLASS_$_ARViewRotationAngleProvider
+ _OBJC_METACLASS_$_ARViewRotationContext
+ __OBJC_$_CLASS_METHODS_ARViewRotationContext
+ __OBJC_$_INSTANCE_METHODS_ARRotationCoordinatorPreviewAngleSource
+ __OBJC_$_INSTANCE_METHODS_ARViewRotationAngleProvider
+ __OBJC_$_INSTANCE_METHODS_ARViewRotationContext
+ __OBJC_$_INSTANCE_VARIABLES_ARRotationCoordinatorPreviewAngleSource
+ __OBJC_$_INSTANCE_VARIABLES_ARViewRotationAngleProvider
+ __OBJC_$_INSTANCE_VARIABLES_ARViewRotationContext
+ __OBJC_$_PROP_LIST_ARViewRotationAngleProvider
+ __OBJC_$_PROP_LIST_ARViewRotationContext
+ __OBJC_CLASS_RO_$_ARRotationCoordinatorPreviewAngleSource
+ __OBJC_CLASS_RO_$_ARViewRotationAngleProvider
+ __OBJC_CLASS_RO_$_ARViewRotationContext
+ __OBJC_METACLASS_RO_$_ARRotationCoordinatorPreviewAngleSource
+ __OBJC_METACLASS_RO_$_ARViewRotationAngleProvider
+ __OBJC_METACLASS_RO_$_ARViewRotationContext
+ ___26-[ARSession setViewLayer:]_block_invoke
+ ___48-[ARSession _sessionDidChangeViewRotationAngle:]_block_invoke
+ ___52-[ARViewRotationAngleProvider _deliverPreviewAngle:]_block_invoke
+ ___56-[ARViewRotationAngleProvider _updatePreviewAngleSource]_block_invoke
+ ___block_descriptor_40_e8_32w_e8_v16?0d8lw32l8
+ ___block_descriptor_48_e8_32bs_e5_v8?0ls32l8
+ _s_supportedVideoFormatsCache
+ _s_supportedVideoFormatsCacheSemaphore
- -[ARWorldTrackingTechnique _pushWTResultDataForTimestamp:]
- GCC_except_table131
- GCC_except_table136
- GCC_except_table138
- GCC_except_table139
- GCC_except_table146
- GCC_except_table160
- GCC_except_table169
- GCC_except_table173
- GCC_except_table177
- ___block_descriptor_40_e8_32s_e27_v32?0"<ARSensor>"8Q16^B24ls32l8
- _supportedVideoFormatsForDevicePosition:deviceType:videoBinned:frameRate:.cachedSupportedVideoFormats
- _supportedVideoFormatsForDevicePosition:deviceType:videoBinned:frameRate:.semaphore
CStrings:
+ "%@ <%p>: delivering viewRotationAngle %.0f"
+ "%{public}@ <%p>: ARVideoFormat ignoring unsupported pixel format user default \"%{public}@\""
+ "%{public}@ <%p>: ARVideoFormat pixel format set to %{public}@ by user defaults"
+ "%{public}@ <%p>: Delivering view rotation angle %f degrees"
+ "%{public}@ <%p>: Replay: gave up after %ld attempts to find a frame with a plausible data.timestamp; record/movie timestamp difference will be 0 and customDataForTimestamp will not work"
+ "%{public}@ <%p>: Replay: skipping main-stream frame with bogus data.timestamp=%f (stream.ts=%f)"
+ "%{public}@ <%p>: Video format not supported by this configuration"
+ "Error: %{public}@ <%p>: Replay: gave up after %ld attempts to find a frame with a plausible data.timestamp; record/movie timestamp difference will be 0 and customDataForTimestamp will not work"
+ "Error: %{public}@ <%p>: Replay: skipping main-stream frame with bogus data.timestamp=%f (stream.ts=%f)"
+ "Error: %{public}@ <%p>: Video format not supported by this configuration"
+ "The configuration requests %lu reference objects for object tracking, which exceeds the maximum of %zu."
+ "The configuration requests %lu reference objects with high-frame-rate tracking, which exceeds the maximum of %zu."
+ "com.apple.arkit.faceTracking.exposeAdditionalNonBinnedFormats"
+ "com.apple.arkit.imagesensor.back.wide.pixelFormat"
+ "devicePosition"
+ "v16@?0d8"
+ "videoRotationAngleForHorizonLevelPreview"
+ "\xf0\xf0\xf0\x81"
- "Too many reference objects for object tracking requested, the max is: %zu, got: %lu"
- "Video format not supported by this configuration"
- "\xf0\xf0\xf0A"
```
