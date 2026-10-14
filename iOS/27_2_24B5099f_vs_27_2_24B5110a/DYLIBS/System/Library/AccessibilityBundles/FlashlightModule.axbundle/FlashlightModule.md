## FlashlightModule

> `/System/Library/AccessibilityBundles/FlashlightModule.axbundle/FlashlightModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5cc` | `0xc68` | **`+0x69c`** |
| `__AUTH_CONST.__cfstring` | `0x2a0` | `0x3e0` | **`+0x140`** |
| `__TEXT.__cstring` | `0x39e` | `0x454` | **`+0xb6`** |
| `__DATA_CONST.__const` | `0xa8` | `0x148` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0xd0` | `0x118` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x1c` | `0x50` | **`+0x34`** |
| `__TEXT.__objc_methlist` | `0xdc` | `0x100` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xa8` | `0xb0` | **`+0x8`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  Functions: 20
-  Symbols:   85
-  CStrings:  30
+  Functions: 28
+  Symbols:   104
+  CStrings:  43
Symbols:
+ -[CCUIFlashlightModuleViewControllerAccessibility _accessibilityControlCenterButtonAdditionalTraits]
+ -[CCUIFlashlightModuleViewControllerAccessibility _axAdjustFlashlightLevelInForwardDirection:]
+ -[CCUIFlashlightModuleViewControllerAccessibility _axDescriptionForFlashlightLevel:]
+ GCC_except_table11
+ _AXPerformSafeBlock
+ _OBJC_CLASS_$_NSNumber
+ _UIAccessibilityTraitAdjustable
+ _UIAccessibilityTraitNone
+ ___93-[CCUIFlashlightModuleViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_2
+ ___93-[CCUIFlashlightModuleViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_3
+ ___93-[CCUIFlashlightModuleViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_4
+ ___93-[CCUIFlashlightModuleViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_5
+ ___94-[CCUIFlashlightModuleViewControllerAccessibility _axAdjustFlashlightLevelInForwardDirection:]_block_invoke
+ ___block_descriptor_40_e8_32w_e5_B8?0lw32l8
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_48_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32w40w_e15_"NSString"8?0lw32l8w40l8
+ _objc_release_x8
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x19
- GCC_except_table8
CStrings:
+ "-[CCUIFlashlightModuleViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_2"
+ "B"
+ "B8@?0"
+ "CCUIButtonModuleViewController"
+ "CCUISliderModuleViewController"
+ "Q"
+ "SBUIFlashlightController"
+ "_flashlight"
+ "_isSliderInteractive"
+ "buttonView"
+ "isAvailable"
+ "isExpanded"
+ "level"
+ "setLevel:"
- "-[CCUIFlashlightModuleViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke"
```
