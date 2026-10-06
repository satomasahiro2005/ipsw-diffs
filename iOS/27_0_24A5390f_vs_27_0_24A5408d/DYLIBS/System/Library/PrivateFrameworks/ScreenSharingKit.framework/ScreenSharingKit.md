## ScreenSharingKit

> `/System/Library/PrivateFrameworks/ScreenSharingKit.framework/ScreenSharingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x267f64` | `0x269ad0` | **`+0x1b6c`** |
| `__TEXT.__unwind_info` | `0x8f10` | `0x8c28` | **`-0x2e8`** |
| `__AUTH_CONST.__const` | `0x10ae0` | `0x10d20` | **`+0x240`** |
| `__TEXT.__const` | `0x195f4` | `0x19794` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x96c5` | `0x9865` | **`+0x1a0`** |
| `__TEXT.__swift5_reflstr` | `0x8eb5` | `0x8f95` | **`+0xe0`** |
| `__TEXT.__swift5_fieldmd` | `0x7100` | `0x71a8` | **`+0xa8`** |
| `__TEXT.__eh_frame` | `0x18878` | `0x188f0` | **`+0x78`** |
| `__TEXT.__constg_swiftt` | `0x885c` | `0x88bc` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x3d68` | `0x3da8` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x7936` | `0x7968` | **`+0x32`** |
| `__AUTH_CONST.__auth_got` | `0x1840` | `0x1858` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xe08` | `0xe20` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x10a8` | `0x10b4` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x6f8` | `0x704` | **`+0xc`** |
| `__DATA.__data` | `0x57b0` | `0x57a8` | **`-0x8`** |

### Other Changes

```diff

-114.51.0.0.0
+114.56.0.0.0

-  Functions: 9612
-  Symbols:   3408
-  CStrings:  1573
+  Functions: 9671
+  Symbols:   3420
+  CStrings:  1582
Symbols:
+ _OBJC_CLASS_$_NSThread
+ _OBJC_CLASS_$_UIApplication
+ ___swift_memcpy121_8
+ ___swift_memcpy169_8
+ ___swift_memcpy57_8
+ ___swift_memcpy74_8
+ _swift_task_getMainExecutor
+ _swift_task_isCurrentExecutor
+ _symbolic _____ 16ScreenSharingKit40UIApplicationBackedTerminationPrimitivesV
+ _symbolic _____ 16ScreenSharingKit42SystemUISizeHydratingCanvasSizesPrimitivesV
+ _symbolic _____ 16ScreenSharingKit47BuildConfigurationCheckingTerminationPrimitivesV
+ _symbolic _____ 16ScreenSharingKit48CADisplayFrameBackedDisplayInformationPrimitivesV
+ _symbolic _____ 16ScreenSharingKit49CADisplayBoundsBackedDisplayInformationPrimitivesV
+ _symbolic _____ 16ScreenSharingKit53OverSampledDeviceCheckingDisplayInformationPrimitivesV
+ _symbolic _____Sg So6CGSizeV
+ _symbolic _____Sg s25FloatingPointRoundingRuleO
+ _symbolic yt______pIgrzo_ s5ErrorP
+ _type_layout_string 16ScreenSharingKit42SystemUISizeHydratingCanvasSizesPrimitivesV
+ _type_layout_string 16ScreenSharingKit47BuildConfigurationCheckingTerminationPrimitivesV
+ _type_layout_string 16ScreenSharingKit53OverSampledDeviceCheckingDisplayInformationPrimitivesV
+ _type_layout_string So6CGSizeV
- ___swift_memcpy145_8
- ___swift_memcpy50_8
- ___swift_memcpy97_8
- _abort
- _symbolic _____ 16ScreenSharingKit32AbortBackedTerminationPrimitivesV
- _symbolic _____ 16ScreenSharingKit40DeviceModelCheckingCanvasSizesPrimitivesV
- _symbolic _____ 16ScreenSharingKit43CADisplayBackedDisplayInformationPrimitivesV
- _type_layout_string 16ScreenSharingKit40DeviceModelCheckingCanvasSizesPrimitivesV
- _type_layout_string So7CGPointV
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ScreenSharingKit/ScreenSharingKit/Primitives/Implementations/Termination/UIApplicationBackedTerminationPrimitives_iOS.swift"
+ "Incorrect actor executor assumption; Expected same executor as "
+ "SSKResizabilityDeblur"
+ "SSKResizabilityLiveResizeEnded"
+ "SSKResizabilityRegionOfInterestChanged"
+ "SSKResizabilityRequestSent"
+ "SSKResizabilitySceneSizeChanged"
+ "SSKResizabilityTimedOut"
+ "ScreenSharingKit/UIApplicationBackedTerminationPrimitives_iOS.swift"
+ "Terminating cleanly - calling terminateWithSuccess()"
+ "performTermination()"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ScreenSharingKit/ScreenSharingKit/Primitives/Implementations/Termination/AbortBackedTerminationPrimitives.swift"
- "Process termination requested - calling abort()"
```
