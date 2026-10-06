## AccessibilityUIUtilities

> `/System/Library/PrivateFrameworks/AccessibilityUIUtilities.framework/AccessibilityUIUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6204c` | `0x621a4` | **`+0x158`** |
| `__TEXT.__oslogstring` | `0x1155` | `0x11dc` | **`+0x87`** |
| `__AUTH_CONST.__cfstring` | `0x6a60` | `0x6aa0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x5cf1` | `0x5d2f` | **`+0x3e`** |
| `__DATA_CONST.__const` | `0xde8` | `0xe18` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0xa38` | `0xa58` | **`+0x20`** |
| `__DATA.__bss` | `0xa60` | `0xa70` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x51d8` | `0x51e8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x6584` | `0x6594` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x11f8` | `0x1200` | **`+0x8`** |
| `__TEXT.__const` | `0xd38` | `0xd40` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1980` | `0x1988` | **`+0x8`** |

### Other Changes

```diff

-3245.8.2.0.0
+3245.8.4.2.0

-  Functions: 2418
-  Symbols:   4671
-  CStrings:  1077
+  Functions: 2420
+  Symbols:   4679
+  CStrings:  1081
Symbols:
+ -[AXCameraSceneDescriber _describeCameraSceneWithOptions:featureDescriptionOptions:handler:remainingAttempts:]
+ -[AXCameraSceneDescriber visionResultHandler:withFeatureDescriptionOptions:options:result:error:remainingAttempts:]
+ GCC_except_table1408
+ GCC_except_table1525
+ GCC_except_table1636
+ GCC_except_table1845
+ GCC_except_table1868
+ GCC_except_table1876
+ GCC_except_table1889
+ GCC_except_table1892
+ GCC_except_table1899
+ GCC_except_table1924
+ _AXCameraSceneDescriberErrorDomain
+ _AXUIDeviceSupportsDynamicIsland.onceToken
+ _AXUIDeviceSupportsDynamicIsland.supportsDynamicIsland
+ ___110-[AXCameraSceneDescriber _describeCameraSceneWithOptions:featureDescriptionOptions:handler:remainingAttempts:]_block_invoke
+ ___110-[AXCameraSceneDescriber _describeCameraSceneWithOptions:featureDescriptionOptions:handler:remainingAttempts:]_block_invoke_2
+ ___115-[AXCameraSceneDescriber visionResultHandler:withFeatureDescriptionOptions:options:result:error:remainingAttempts:]_block_invoke
+ ___AXUIDeviceSupportsDynamicIsland_block_invoke
+ ___block_descriptor_56_e8_32s40s48bs_e21_v16?0^{__CVBuffer=}8ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48bs56w_e5_v8?0lw56l8s32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e37_v24?0"AXMVisionResult"8"NSError"16ls32l8s56l8s40l8s48l8
+ _objc_retain_x28
- -[AXCameraSceneDescriber visionResultHandler:withFeatureDescriptionOptions:result:error:]
- GCC_except_table1407
- GCC_except_table1524
- GCC_except_table1635
- GCC_except_table1842
- GCC_except_table1867
- GCC_except_table1875
- GCC_except_table1888
- GCC_except_table1891
- GCC_except_table1898
- GCC_except_table1923
- ___84-[AXCameraSceneDescriber imageDescriptionForCurrentCameraScene:withPreferredLocale:]_block_invoke
- ___84-[AXCameraSceneDescriber imageDescriptionForCurrentCameraScene:withPreferredLocale:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48bs_e37_v24?0"AXMVisionResult"8"NSError"16ls32l8s48l8s40l8
- ___block_descriptor_64_e8_32s40s48s56bs_e21_v16?0^{__CVBuffer=}8ls32l8s40l8s56l8s48l8
CStrings:
+ "AXCameraSceneDescriberErrorDomain"
+ "Camera scene detection failed after retries: %@"
+ "Camera scene detection returned no description, retrying: %@"
+ "DeviceSupportsDynamicIsland"
+ "Starting camera scene detection, %lu attempt(s) remaining: %@"
- "Starting camera scene detection: %@"
```
