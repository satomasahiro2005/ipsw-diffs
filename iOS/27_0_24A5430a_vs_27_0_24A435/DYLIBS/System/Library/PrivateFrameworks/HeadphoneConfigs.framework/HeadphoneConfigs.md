## HeadphoneConfigs

> `/System/Library/PrivateFrameworks/HeadphoneConfigs.framework/HeadphoneConfigs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc9614` | `0xca3e4` | **`+0xdd0`** |
| `__TEXT.__oslogstring` | `0xa3db` | `0xa59b` | **`+0x1c0`** |
| `__AUTH_CONST.__cfstring` | `0x95e0` | `0x96c0` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x9643` | `0x9723` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x11b0` | `0x1200` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x22a0` | `0x22e0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3680` | `0x36c0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x4fa8` | `0x4fd8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2428` | `0x2458` | **`+0x30`** |
| `__TEXT.__const` | `0x2414` | `0x2434` | **`+0x20`** |
| `__DATA.__bss` | `0x28e8` | `0x28f8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xfa0` | `0xfa8` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 4195
-  Symbols:   3538
-  CStrings:  2248
+  Functions: 4204
+  Symbols:   3550
+  CStrings:  2264
Symbols:
+ +[HPSProductUtils isShortScreenDevice]
+ +[HPSProductUtils stringForUIInterfaceOrientation:]
+ -[HPSSpatialProfileSingeStepEnrollmentController showNonLandscapeLeftAlert]
+ -[HPSSpatialProfileSingeStepEnrollmentController viewWillTransitionToSize:withTransitionCoordinator:]
+ _MGGetProductType
+ _MGIsDeviceOfType
+ ___101-[HPSSpatialProfileSingeStepEnrollmentController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
+ ___38+[HPSProductUtils isShortScreenDevice]_block_invoke
+ ___75-[HPSSpatialProfileSingeStepEnrollmentController showNonLandscapeLeftAlert]_block_invoke
+ ___76-[HPSSpatialProfileManagementController presentProfileEnrollmentController:]_block_invoke
+ ___block_descriptor_40_e8_32s_e56_v16?0"<UIViewControllerTransitionCoordinatorContext>"8ls32l8
+ _isShortScreenDevice.onceToken
+ _isShortScreenDevice.sIsShortScreenDevice
- _swift_release_x10
CStrings:
+ "HPSProductUtils: isShortScreenDevice -> %s"
+ "LandscapeLeft"
+ "LandscapeRight"
+ "NON_LANDSCAPE_LEFT_MODE_ALERT_DETAIL"
+ "NON_LANDSCAPE_LEFT_MODE_ALERT_TITLE"
+ "Portrait"
+ "PortraitUpsideDown"
+ "Spatial Profile: Enrollment not supported, Tall Screen: %u, Orientation: %@, Show pop up alert"
+ "Spatial Profile: Force hiding Prox Card"
+ "Spatial Profile: Interface Orientation Changed"
+ "Spatial Profile: Non Landscape Left Mode Detected, not supported, show pop up alert"
+ "Spatial Profile: Tall Screen: %u (%f), Orientation: %@"
+ "Spatial Profile: V68: localHardwareSupport was %s, forced to True for V68"
+ "True"
+ "Unrecognized (%ld)"
+ "v16@?0@\"<UIViewControllerTransitionCoordinatorContext>\"8"
```
