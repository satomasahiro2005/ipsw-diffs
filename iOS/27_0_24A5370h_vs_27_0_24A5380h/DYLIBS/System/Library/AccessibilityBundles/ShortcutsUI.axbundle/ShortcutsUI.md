## ShortcutsUI

> `/System/Library/AccessibilityBundles/ShortcutsUI.axbundle/ShortcutsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x468` | `0x978` | **`+0x510`** |
| `__AUTH_CONST.__objc_const` | `0x1b0` | `0x3f0` | **`+0x240`** |
| `__AUTH_CONST.__cfstring` | `0x220` | `0x3e0` | **`+0x1c0`** |
| `__AUTH.__objc_data` | `0xf0` | `0x230` | **`+0x140`** |
| `__TEXT.__cstring` | `0x163` | `0x26c` | **`+0x109`** |
| `__TEXT.__objc_methlist` | `0x5c` | `0x13c` | **`+0xe0`** |
| `__DATA_CONST.__objc_selrefs` | `0x90` | `0xf0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x80` | `0xb8` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x40` | `0x68` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x38` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x20` | `0x30` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x8` | `0x18` | **`+0x10`** |
| `__TEXT.__const` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 9
-  Symbols:   60
-  CStrings:  20
+  Functions: 25
+  Symbols:   101
+  CStrings:  37
Symbols:
+ +[WFEggTimerControlAccessibility _accessibilityPerformValidations:]
+ +[WFEggTimerControlAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[WFEggTimerControlAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[WFEggTimerViewControllerAccessibility _accessibilityPerformValidations:]
+ +[WFEggTimerViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[WFEggTimerViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[WFEggTimerControlAccessibility _axAdjustTimerValueForward:]
+ -[WFEggTimerControlAccessibility accessibilityDecrement]
+ -[WFEggTimerControlAccessibility accessibilityElements]
+ -[WFEggTimerControlAccessibility accessibilityIncrement]
+ -[WFEggTimerControlAccessibility accessibilityLabel]
+ -[WFEggTimerControlAccessibility accessibilityTraits]
+ -[WFEggTimerControlAccessibility accessibilityValue]
+ -[WFEggTimerControlAccessibility isAccessibilityElement]
+ -[WFEggTimerViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
+ _AXDurationStringForDurationWithSeconds
+ _AXPerformSafeBlock
+ _OBJC_CLASS_$_WFEggTimerControlAccessibility
+ _OBJC_CLASS_$_WFEggTimerViewControllerAccessibility
+ _OBJC_CLASS_$___WFEggTimerControlAccessibility_super
+ _OBJC_CLASS_$___WFEggTimerViewControllerAccessibility_super
+ _OBJC_METACLASS_$_WFEggTimerControlAccessibility
+ _OBJC_METACLASS_$_WFEggTimerViewControllerAccessibility
+ _OBJC_METACLASS_$___WFEggTimerControlAccessibility_super
+ _OBJC_METACLASS_$___WFEggTimerViewControllerAccessibility_super
+ _UIAccessibilityTraitAdjustable
+ __NSConcreteStackBlock
+ __OBJC_$_CLASS_METHODS_WFEggTimerControlAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS_WFEggTimerViewControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_WFEggTimerControlAccessibility
+ __OBJC_$_INSTANCE_METHODS_WFEggTimerViewControllerAccessibility
+ __OBJC_CLASS_RO_$_WFEggTimerControlAccessibility
+ __OBJC_CLASS_RO_$_WFEggTimerViewControllerAccessibility
+ __OBJC_CLASS_RO_$___WFEggTimerControlAccessibility_super
+ __OBJC_CLASS_RO_$___WFEggTimerViewControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_WFEggTimerControlAccessibility
+ __OBJC_METACLASS_RO_$_WFEggTimerViewControllerAccessibility
+ __OBJC_METACLASS_RO_$___WFEggTimerControlAccessibility_super
+ __OBJC_METACLASS_RO_$___WFEggTimerViewControllerAccessibility_super
+ ___61-[WFEggTimerControlAccessibility _axAdjustTimerValueForward:]_block_invoke
+ ___block_descriptor_48_e8_32s_e5_v8?0ls32l8
Functions:
~ ___50+[AXShortcutsUIGlue accessibilityInitializeBundle]_block_invoke_3 : 20 -> 112
CStrings:
+ "UIControl"
+ "WFEggTimerControl"
+ "WFEggTimerControlAccessibility"
+ "WFEggTimerViewController"
+ "WFEggTimerViewControllerAccessibility"
+ "currentValue"
+ "d"
+ "durationValueLabel"
+ "egg.timer.control.label"
+ "rangeMax"
+ "rangeMin"
+ "setCurrentValue:"
+ "stepSize"
+ "timerControl"
+ "v"
+ "v8@?0"
+ "valueChangedHandler"
```
