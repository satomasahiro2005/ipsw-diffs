## ARKitCore

> `/System/Library/SubFrameworks/ARKitCore.framework/ARKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19a784` | `0x19ad54` | **`+0x5d0`** |
| `__DATA.__bss` | `0x1888` | `0x19a8` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0x3d080` | `0x3d0e0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x20d74` | `0x20dc6` | **`+0x52`** |
| `__AUTH_CONST.__const` | `0x3dd8` | `0x3e18` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1140c` | `0x1143c` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xff20` | `0xff40` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x7ec0` | `0x7ed8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x15e8` | `0x15f8` | **`+0x10`** |
| `__TEXT.__const` | `0x25d68` | `0x25d78` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x13480` | `0x13490` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1d98c` | `0x1d99a` | **`+0xe`** |
| `__AUTH_CONST.__auth_got` | `0x1f08` | `0x1f10` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2030` | `0x2038` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 8008
-  Symbols:   14577
-  CStrings:  4551
+  Functions: 8024
+  Symbols:   14602
+  CStrings:  4554
Symbols:
+ -[ARCamera displayRegion]
+ -[ARCamera initWithIntrinsics:imageResolution:devicePosition:radialDistortion:tangentialDistortion:exposureDuration:calibrationData:extrinsicsMap:captureLens:displayRegion:]
+ -[ARCamera setDisplayRegion:]
+ -[ARImageData displayRegion]
+ -[ARImageData setDisplayRegion:]
+ _ARDeviceIsV68
+ _ARDeviceIsV68.onceToken
+ _ARDisplayCenterTransformForRegion
+ _ARDisplayCenterTransformForRegion.frontTransforms
+ _ARDisplayCenterTransformForRegion.onceToken
+ _ARDisplayCenterTransformForRegion.rearTransforms
+ _ARDisplayRegionFromAVCaptureDisplayRegion
+ _ARFrontCameraDisplayCenterTransformForDisplayIndex
+ _ARFrontWideCameraTransformFromBackWideAngleCameraTransformForRegion
+ _ARFrontWideCameraTransformFromBackWideAngleCameraTransformWithZFlipForRegion
+ _ARGetFrontCameraOffset
+ _ARGetRearCameraOffset
+ _ARMobileGestaltArrayForKeyAndDisplayIndex
+ _AROverrideARDeviceIsV68
+ _ARRearCameraDisplayCenterTransformForDisplayIndex
+ _ARResetARDeviceIsV68
+ _MGCopyAnswerForDisplayAtIndex
+ _OBJC_IVAR_$_ARCamera._displayRegion
+ _OBJC_IVAR_$_ARImageData._displayRegion
+ ___ARDeviceIsV68_block_invoke
+ ___ARDisplayCenterTransformForRegion_block_invoke
+ _kMGDisplayIndexedQueryFrontCameraOffsetFromDisplayCenter
+ _kMGDisplayIndexedQueryRearCameraOffsetFromDisplayCenter
+ _s_deviceIsV68
- -[ARCamera initWithIntrinsics:imageResolution:devicePosition:radialDistortion:tangentialDistortion:exposureDuration:calibrationData:extrinsicsMap:captureLens:]
- _ARDisplayCenterTransformForCaptureDevicePosition
- _ARFrontWideCameraTransformFromBackWideAngleCameraTransform
- _ARFrontWideCameraTransformFromBackWideAngleCameraTransformWithZFlip
CStrings:
+ "A!"
+ "MobileGestalt display-indexed query failed (error %d, display %ld) for device: %@"
+ "displayRegion"
```
