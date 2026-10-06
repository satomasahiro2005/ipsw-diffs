## CameraEditKitFramework

> `/System/Library/AccessibilityBundles/CameraEditKitFramework.axbundle/CameraEditKitFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0xe40` | `0xe80` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x200` | `0x1d8` | **`-0x28`** |
| `__TEXT.__text` | `0x39a8` | `0x39d0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x340` | `0x328` | **`-0x18`** |
| `__TEXT.__cstring` | `0x8c0` | `0x8c4` | **`+0x4`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 116
-  Symbols:   272
-  CStrings:  127
+  Functions: 117
+  Symbols:   271
+  CStrings:  129
Symbols:
+ GCC_except_table81
+ ___49-[CEKApertureSliderAccessibility _axAdjustValue:]_block_invoke_6
- GCC_except_table80
- ___block_descriptor_56_e8_32s40s_e5_v8?0ls32l8s40l8
- _objc_retain_x22
Functions:
~ +[CEKApertureSliderAccessibility _accessibilityPerformValidations:] : 432 -> 412
~ -[CEKApertureSliderAccessibility _axAdjustValue:] : 500 -> 508
~ ___49-[CEKApertureSliderAccessibility _axAdjustValue:]_block_invoke : 96 -> 12
~ ___49-[CEKApertureSliderAccessibility _axAdjustValue:]_block_invoke_2 : 80 -> 12
~ ___49-[CEKApertureSliderAccessibility _axAdjustValue:]_block_invoke_3 : 84 -> 80
~ ___49-[CEKApertureSliderAccessibility _axAdjustValue:]_block_invoke_4 : 80 -> 84
~ ___49-[CEKApertureSliderAccessibility _axAdjustValue:]_block_invoke_5 : 84 -> 80
+ ___49-[CEKApertureSliderAccessibility _axAdjustValue:]_block_invoke_6
~ -[CEKApertureSliderAccessibility accessibilityValue] : 232 -> 276
~ +[CEKSliderAccessibility _accessibilityPerformValidations:] : 424 -> 452
~ ___41-[CEKSliderAccessibility _axAdjustValue:]_block_invoke : 16 -> 68
CStrings:
+ "depth.off"
+ "indexCount"
+ "isSliderOn"
+ "sendActionsForControlEvents:"
+ "setSelectedIndex:"
+ "sliderOn"
- "CEKApertureStops"
- "markedApertureValue"
- "setApertureValueClosestTo:"
- "validApertureValues"
```
