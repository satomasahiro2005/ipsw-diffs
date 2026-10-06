## SleepHealthUI

> `/System/Library/AccessibilityBundles/SleepHealthUI.axbundle/SleepHealthUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0xab0` | `0xbd0` | **`+0x120`** |
| `__TEXT.__text` | `0x1c34` | `0x1d0c` | **`+0xd8`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x720` | `0x780` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x418` | `0x478` | **`+0x60`** |
| `__TEXT.__cstring` | `0x762` | `0x7b2` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x70` | `0x80` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x98` | `0xa8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x228` | `0x238` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x110` | `0x118` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 79
-  Symbols:   251
-  CStrings:  66
+  Functions: 85
+  Symbols:   269
+  CStrings:  69
Symbols:
+ +[ScheduleOccurrenceCellAccessibility _accessibilityPerformValidations:]
+ +[ScheduleOccurrenceCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[ScheduleOccurrenceCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[ScheduleOccurrenceCellAccessibility accessibilityLabel]
+ -[ScheduleOccurrenceCellAccessibility accessibilityTraits]
+ -[ScheduleOccurrenceCellAccessibility isAccessibilityElement]
+ _OBJC_CLASS_$_ScheduleOccurrenceCellAccessibility
+ _OBJC_CLASS_$___ScheduleOccurrenceCellAccessibility_super
+ _OBJC_METACLASS_$_ScheduleOccurrenceCellAccessibility
+ _OBJC_METACLASS_$___ScheduleOccurrenceCellAccessibility_super
+ _UIAccessibilityTraitButton
+ _UIAccessibilityTraitNone
+ __OBJC_$_CLASS_METHODS_ScheduleOccurrenceCellAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_ScheduleOccurrenceCellAccessibility
+ __OBJC_CLASS_RO_$_ScheduleOccurrenceCellAccessibility
+ __OBJC_CLASS_RO_$___ScheduleOccurrenceCellAccessibility_super
+ __OBJC_METACLASS_RO_$_ScheduleOccurrenceCellAccessibility
+ __OBJC_METACLASS_RO_$___ScheduleOccurrenceCellAccessibility_super
Functions:
~ ___52+[AXSleepHealthUIGlue accessibilityInitializeBundle]_block_invoke_3 : 232 -> 252
CStrings:
+ "ScheduleOccurrenceCellAccessibility"
+ "SleepHealthUI.ScheduleOccurrenceCell"
+ "UIView"
```
