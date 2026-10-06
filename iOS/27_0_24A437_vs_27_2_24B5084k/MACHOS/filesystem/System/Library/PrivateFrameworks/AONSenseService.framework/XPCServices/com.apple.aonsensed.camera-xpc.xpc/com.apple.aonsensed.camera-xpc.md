## com.apple.aonsensed.camera-xpc

> `/System/Library/PrivateFrameworks/AONSenseService.framework/XPCServices/com.apple.aonsensed.camera-xpc.xpc/com.apple.aonsensed.camera-xpc`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x133c8` | `0x136a4` | **`+0x2dc`** |
| `__DATA.__objc_const` | `0xa80` | `0xaa0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x101a` | `0x103a` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x4d3` | `0x4f3` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x166f` | `0x167f` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2fc` | `0x308` | **`+0xc`** |
| `__DATA.__objc_data` | `0x518` | `0x520` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-118.0.2.0.0
+131.0.0.0.0

-  Functions: 316
-  Symbols:   1224
-  CStrings:  315
+  Functions: 317
+  Symbols:   1226
+  CStrings:  317
Symbols:
+ _$s30com_apple_aonsensed_camera_xpc18ALCameraXPCServiceC22disableConvergenceGate33_22D344278D26B8DDDF15E77B95C8AE90LLSbvpWvd
+ _$s30com_apple_aonsensed_camera_xpc18ALCameraXPCServiceC22disableConvergenceGate33_22D344278D26B8DDDF15E77B95C8AE90LLSbvpfi
+ _$s30com_apple_aonsensed_camera_xpc18ALCameraXPCServiceC27configureDynamicAspectRatio33_22D344278D26B8DDDF15E77B95C8AE90LL3forSbSo15AVCaptureDeviceC_tF
+ _$s30com_apple_aonsensed_camera_xpc18ALCameraXPCServiceC27configureDynamicAspectRatio33_22D344278D26B8DDDF15E77B95C8AE90LL3forSbSo15AVCaptureDeviceC_tFTf4nd_n
- _$s30com_apple_aonsensed_camera_xpc18ALCameraXPCServiceC27configureDynamicAspectRatio33_22D344278D26B8DDDF15E77B95C8AE90LL3forySo15AVCaptureDeviceC_tF
- _$s30com_apple_aonsensed_camera_xpc18ALCameraXPCServiceC27configureDynamicAspectRatio33_22D344278D26B8DDDF15E77B95C8AE90LL3forySo15AVCaptureDeviceC_tFTf4nd_n
CStrings:
+ "Camera XPC: DisableCameraConvergenceGate = %s"
+ "Camera XPC: Failed to lock camera for configuration: %s, falling back to minimal full-FoV"
+ "Camera XPC: No format supports dynamic aspect ratio on %s, falling back to minimal full-FoV"
+ "Camera XPC: selectActiveFormat for %s — isFrontUltraWide=%{bool}d"
+ "DisableCameraConvergenceGate"
+ "disableConvergenceGate"
- "Camera XPC: Failed to lock camera for configuration: %s"
- "Camera XPC: No format supports dynamic aspect ratio on this device, continuing with default"
- "Camera XPC: selectActiveFormat for %s — isFrontUltraWide=%{bool}d, EnableNonCroppedFCAMFullFoV=%{bool}d, useDynamicAspectRatio=%{bool}d"
- "EnableNonCroppedFCAMFullFoV"
```
