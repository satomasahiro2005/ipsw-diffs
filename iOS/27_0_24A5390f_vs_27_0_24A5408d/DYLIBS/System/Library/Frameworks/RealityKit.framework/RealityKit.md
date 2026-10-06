## RealityKit

> `/System/Library/Frameworks/RealityKit.framework/RealityKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ae08` | `0x7b168` | **`+0x360`** |
| `__AUTH_CONST.__const` | `0x32d8` | `0x3378` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1744` | `0x16a4` | **`-0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x17e1` | `0x1841` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x2f78` | `0x2fb8` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x484` | `0x4a4` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1a18` | `0x1a38` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1404` | `0x141c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xeb0` | `0xea0` | **`-0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x568` | `0x578` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x11ac` | `0x119c` | **`-0x10`** |
| `__AUTH.__objc_data` | `0xa60` | `0xa68` | **`+0x8`** |
| `__AUTH_CONST.__auth_got` | `0x2698` | `0x2690` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x1a58` | `0x1a60` | **`+0x8`** |

### Other Changes

```diff

-453.0.5.502.1
+453.2.1.0.0

-  Functions: 2717
-  Symbols:   7444
-  CStrings:  137
+  Functions: 2724
+  Symbols:   7439
+  CStrings:  133
Symbols:
+ _$s10RealityKit10RKARSystemC15SessionDelegate33_7C42569567E429B6AB2725E2C535D529LLC7session_26didChangeViewRotationAngleySo9ARSessionC_12CoreGraphics7CGFloatVtFTf4dnn_n
+ _$s10RealityKit10RKARSystemC15SessionDelegate33_7C42569567E429B6AB2725E2C535D529LLC7session_26didChangeViewRotationAngleySo9ARSessionC_12CoreGraphics7CGFloatVtFTo
+ _$s10RealityKit10RKARSystemC23updateCameraWorldMatrix33_7C42569567E429B6AB2725E2C535D529LL4fromySo7ARFrameC_tF
+ _$s10RealityKit6ARViewC11orientationSo22UIInterfaceOrientationVvg
+ _$s10RealityKit6ARViewC23renderTargetOrientationSo011UIInterfaceF0Vvg
+ _$s10RealityKit6ARViewC25handleRotationAngleChangeyy12CoreGraphics7CGFloatVF
+ _$s10RealityKit6ARViewC25handleRotationAngleChangeyy12CoreGraphics7CGFloatVFySbcfU0_
+ _$s10RealityKit6ARViewC25handleRotationAngleChangeyy12CoreGraphics7CGFloatVFySbcfU0_TA
+ _$s10RealityKit6ARViewC25handleRotationAngleChangeyy12CoreGraphics7CGFloatVFyycfU_TA
+ _$s10RealityKit6ARViewC29applyCounterRotationTransformyyF
+ _$s10RealityKit6ARViewC34viewRotationAngleHandlerRegisteredSbvpWvd
+ _$s10RealityKit6ARViewC41isInitialViewRotationAngleDeliveryPendingSbvpWvd
+ _$s10RealityKit6EntityC12ComponentSetV0A10FoundationE4loadyxSgxmAA0D0RzlF
+ _$s10RealityKit6EntityC12ComponentSetV0A10FoundationE5store_8newValueyxm_xSgtAA0D0RzlF
+ _$s10RealityKit6EntityC12ComponentSetV0A10FoundationE6borrowyxSgxmAA0D0RzlF
+ _$s10RealityKit6EntityC12ComponentSetV0A10FoundationE7restore_8newValueyxm_xSgtAA0D0RzlF
+ _$s17RealityFoundation0A13FusionSessionC0A3KitE18orientationForView33_315EBF8DEF4D8157A4217B809BAE72A4LL02arH0So22UIInterfaceOrientationVAD6ARViewC_tFTf4nd_n
+ _$sSbIegy_SbIeyBy_TR
+ _ARDisplayRotationFromViewRotationAngle
+ _ARInterfaceOrientationFromViewRotationAngle
+ _ARViewRotationAngleFromInterfaceOrientation
+ _ARViewToCameraImageTransformWithAngle
+ _CGRectGetHeight
+ _CGRectGetWidth
+ __OBJC_$_CLASS_METHODS__TtC10RealityKit6ARView(RealityKit|RealityKit1|RealityKit2|RealityKit3|RealityKit4|RealityKit5|RealityKit6)
+ __OBJC_$_INSTANCE_METHODS__TtC10RealityKit6ARView(RealityKit|RealityKit1|RealityKit2|RealityKit3|RealityKit4|RealityKit5|RealityKit6)
+ __OBJC_CLASS_PROTOCOLS_$__TtC10RealityKit6ARView(RealityKit|RealityKit1|RealityKit2|RealityKit3|RealityKit4|RealityKit5|RealityKit6)
- _$s10RealityKit10RKARSystemC11orientation33_7C42569567E429B6AB2725E2C535D529LLSo22UIInterfaceOrientationVvg
- _$s10RealityKit6ARViewC15windowDidRotate12notificationySo14NSNotificationC_tFTo
- _$s10RealityKit6ARViewC16windowWillRotate12notificationySo14NSNotificationC_tF
- _$s10RealityKit6ARViewC16windowWillRotate12notificationySo14NSNotificationC_tFTo
- _$s10RealityKit6ARViewC25windowWillAnimateRotation12notificationySo14NSNotificationC_tFTf4dn_n
- _$s10RealityKit6ARViewC25windowWillAnimateRotation12notificationySo14NSNotificationC_tFTo
- _$s10RealityKit6EntityC0A10FoundationE4loadyxSgxmAA9ComponentRzlF
- _$s10RealityKit6EntityC0A10FoundationE5store_8newValueyxm_xSgtAA9ComponentRzlF
- _$s10RealityKit6EntityC0A10FoundationE6borrowyxSgxmAA9ComponentRzlF
- _$s10RealityKit6EntityC0A10FoundationE7restore_8newValueyxm_xSgtAA9ComponentRzlF
- _$s10RealityKit6EntityC12ComponentSetV6entityACvg
- _$s17RealityFoundation0A13FusionSessionC0A3KitE18getCameraTransform33_315EBF8DEF4D8157A4217B809BAE72A4LL6arViewSo13simd_float4x4aAD6ARViewC_tFTf4nd_n
- _$sSD10FoundationE36_unconditionallyBridgeFromObjectiveCySDyxq_GSo12NSDictionaryCSgFZ
- _$sSo8NSNumberCML
- _$sSo8UIWindowCML
- _$sSo8UIWindowCMaTm
- _$ss11AnyHashableV13_rawHashValue4seedS2i_tF
- _$ss11AnyHashableV2eeoiySbAB_ABtFZ
- _$ss11AnyHashableVN
- _$ss11AnyHashableVSHsWP
- _$ss11AnyHashableVWOc
- _$ss11AnyHashableVWOh
- _$ss11AnyHashableVyABxcSHRzlufC
- _$ss22__RawDictionaryStorageC4find_9hashValues10_HashTableV6BucketV6bucket_Sb5foundtx_SitSHRzlFs11AnyHashableV_Tg5
- _$ss22__RawDictionaryStorageC4findys10_HashTableV6BucketV6bucket_Sb5foundtxSHRzlFs11AnyHashableV_Tg5
- _ARCameraToDisplayRotation
- _ARViewToCameraImageTransform
- _OBJC_CLASS_$_NSNumber
- _OBJC_CLASS_$_UIWindow
- __OBJC_$_CLASS_METHODS__TtC10RealityKit6ARView(RealityKit|RealityKit1|RealityKit2|RealityKit3|RealityKit4|RealityKit5|RealityKit6|RealityKit7)
- __OBJC_$_INSTANCE_METHODS__TtC10RealityKit6ARView(RealityKit|RealityKit1|RealityKit2|RealityKit3|RealityKit4|RealityKit5|RealityKit6|RealityKit7)
- __OBJC_CLASS_PROTOCOLS_$__TtC10RealityKit6ARView(RealityKit|RealityKit1|RealityKit2|RealityKit3|RealityKit4|RealityKit5|RealityKit6|RealityKit7)
CStrings:
- "UIWindowDidRotateNotification"
- "UIWindowNewOrientationUserInfoKey"
- "UIWindowWillAnimateRotationNotification"
- "UIWindowWillRotateNotification"
```
