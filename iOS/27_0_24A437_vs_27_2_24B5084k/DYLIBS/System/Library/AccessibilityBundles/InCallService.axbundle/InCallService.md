## InCallService

> `/System/Library/AccessibilityBundles/InCallService.axbundle/InCallService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e7c` | `0x4bcc` | **`-0x2b0`** |
| `__AUTH_CONST.__cfstring` | `0x1580` | `0x1420` | **`-0x160`** |
| `__AUTH_CONST.__objc_const` | `0x1830` | `0x1710` | **`-0x120`** |
| `__TEXT.__cstring` | `0xf44` | `0xe9b` | **`-0xa9`** |
| `__DATA_DIRTY.__objc_data` | `0xcd0` | `0xc30` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x8d8` | `0x870` | **`-0x68`** |
| `__AUTH_CONST.__const` | `0x80` | `0xa0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x200` | `0x220` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x158` | `0x148` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x260` | `0x250` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x528` | `0x520` | **`-0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 177
-  Symbols:   532
-  CStrings:  189
+  Functions: 170
+  Symbols:   515
+  CStrings:  177
Symbols:
+ -[PHEmergencyDialerViewControllerAccessibility _axAnnotateCallButton]
+ -[PHEmergencyDialerViewControllerAccessibility viewWillAppear:]
+ GCC_except_table132
+ GCC_except_table150
+ GCC_except_table164
+ GCC_except_table35
+ GCC_except_table41
+ GCC_except_table77
+ ___69-[PHEmergencyDialerViewControllerAccessibility _axAnnotateCallButton]_block_invoke
+ ___block_descriptor_32_e15_"NSString"8?0l
- +[PHActionSliderAccessibility _accessibilityPerformValidations:]
- +[PHActionSliderAccessibility(SafeCategory) safeCategoryBaseClass]
- +[PHActionSliderAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[PHActionSliderAccessibility _accessibilityScannerShouldUseActivateInPointMode]
- -[PHActionSliderAccessibility accessibilityActivate]
- -[PHActionSliderAccessibility accessibilityLabel]
- -[PHActionSliderAccessibility accessibilityPath]
- -[PHActionSliderAccessibility accessibilityRespondsToUserInteraction]
- -[PHActionSliderAccessibility isAccessibilityElement]
- GCC_except_table139
- GCC_except_table157
- GCC_except_table171
- GCC_except_table45
- GCC_except_table51
- GCC_except_table87
- _OBJC_CLASS_$_PHActionSliderAccessibility
- _OBJC_CLASS_$___PHActionSliderAccessibility_super
- _OBJC_METACLASS_$_PHActionSliderAccessibility
- _OBJC_METACLASS_$___PHActionSliderAccessibility_super
- _UIAccessibilityConvertPathToScreenCoordinates
- __OBJC_$_CLASS_METHODS_PHActionSliderAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_PHActionSliderAccessibility
- __OBJC_CLASS_RO_$_PHActionSliderAccessibility
- __OBJC_CLASS_RO_$___PHActionSliderAccessibility_super
- __OBJC_METACLASS_RO_$_PHActionSliderAccessibility
- __OBJC_METACLASS_RO_$___PHActionSliderAccessibility_super
- ___52-[PHActionSliderAccessibility accessibilityActivate]_block_invoke
CStrings:
- "PHActionSlider"
- "PHActionSliderAccessibility"
- "PHSlidingButton"
- "UIBezierPath"
- "_slideCompleted:"
- "_trackBackgroundView"
- "delegate"
- "i"
- "slide.to.power.off"
- "trackMaskPath"
- "trackText"
- "type"
```
