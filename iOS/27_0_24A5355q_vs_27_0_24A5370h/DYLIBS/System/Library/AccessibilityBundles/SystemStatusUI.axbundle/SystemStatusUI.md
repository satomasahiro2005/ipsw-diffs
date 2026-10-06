## SystemStatusUI

> `/System/Library/AccessibilityBundles/SystemStatusUI.axbundle/SystemStatusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x1090` | `0xff0` | **`-0xa0`** |
| `__TEXT.__text` | `0x7370` | `0x7354` | **`-0x1c`** |
| `__TEXT.__cstring` | `0x23b8` | `0x23c0` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0
Symbols:
+ +[STUIStatusBarWifiSignalIconViewAccessibility _accessibilityPerformValidations:]
+ +[STUIStatusBarWifiSignalIconViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[STUIStatusBarWifiSignalIconViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[STUIStatusBarWifiSignalIconViewAccessibility accessibilityIdentifier]
+ -[STUIStatusBarWifiSignalIconViewAccessibility accessibilityValue]
+ _OBJC_CLASS_$_STUIStatusBarWifiSignalIconViewAccessibility
+ _OBJC_CLASS_$___STUIStatusBarWifiSignalIconViewAccessibility_super
+ _OBJC_METACLASS_$_STUIStatusBarWifiSignalIconViewAccessibility
+ _OBJC_METACLASS_$___STUIStatusBarWifiSignalIconViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_STUIStatusBarWifiSignalIconViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_STUIStatusBarWifiSignalIconViewAccessibility
+ __OBJC_CLASS_RO_$_STUIStatusBarWifiSignalIconViewAccessibility
+ __OBJC_CLASS_RO_$___STUIStatusBarWifiSignalIconViewAccessibility_super
+ __OBJC_METACLASS_RO_$_STUIStatusBarWifiSignalIconViewAccessibility
+ __OBJC_METACLASS_RO_$___STUIStatusBarWifiSignalIconViewAccessibility_super
- +[STUIStatusBarWifiSignalViewAccessibility _accessibilityPerformValidations:]
- +[STUIStatusBarWifiSignalViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[STUIStatusBarWifiSignalViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[STUIStatusBarWifiSignalViewAccessibility accessibilityIdentifier]
- -[STUIStatusBarWifiSignalViewAccessibility accessibilityValue]
- _OBJC_CLASS_$_STUIStatusBarWifiSignalViewAccessibility
- _OBJC_CLASS_$___STUIStatusBarWifiSignalViewAccessibility_super
- _OBJC_METACLASS_$_STUIStatusBarWifiSignalViewAccessibility
- _OBJC_METACLASS_$___STUIStatusBarWifiSignalViewAccessibility_super
- __OBJC_$_CLASS_METHODS_STUIStatusBarWifiSignalViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_STUIStatusBarWifiSignalViewAccessibility
- __OBJC_CLASS_RO_$_STUIStatusBarWifiSignalViewAccessibility
- __OBJC_CLASS_RO_$___STUIStatusBarWifiSignalViewAccessibility_super
- __OBJC_METACLASS_RO_$_STUIStatusBarWifiSignalViewAccessibility
- __OBJC_METACLASS_RO_$___STUIStatusBarWifiSignalViewAccessibility_super
Functions:
~ -[STUIStatusBarIndicatorItemAccessibility _accessibilityLoadAccessibilityInformation] : 608 -> 604
~ -[STUIStatusBarAccessibility _accessibilityLoadAccessibilityInformation] : 1208 -> 1200
~ -[STUIStatusBarAccessibility _axElementWithinFocused] : 380 -> 376
~ -[STUIStatusBarSensorActivityViewAccessibility accessibilityLabel] : 528 -> 524
~ -[STUIStatusBarAccessibility _accessibilityHitTest:withEvent:] : 1348 -> 1344
~ -[STUIStatusBarAccessibility _frameForActionable:actionInsets:] : 564 -> 560
CStrings:
+ "STUIStatusBarWifiSignalIconView"
+ "STUIStatusBarWifiSignalIconViewAccessibility"
- "STUIStatusBarWifiSignalView"
- "STUIStatusBarWifiSignalViewAccessibility"
```
