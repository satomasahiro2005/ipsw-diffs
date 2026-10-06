## CameraEditKitFramework

> `/System/Library/AccessibilityBundles/CameraEditKitFramework.axbundle/CameraEditKitFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39d8` | `0x3eac` | **`+0x4d4`** |
| `__AUTH_CONST.__objc_const` | `0x870` | `0x990` | **`+0x120`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x4c4` | `0x55c` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0xe80` | `0xec0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x8c4` | `0x8ed` | **`+0x29`** |
| `__TEXT.__unwind_info` | `0x1c8` | `0x1e8` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x78` | `0x88` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x328` | `0x330` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x28` | `0x30` | **`+0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 117
-  Symbols:   271
-  CStrings:  129
+  Functions: 129
+  Symbols:   293
+  CStrings:  131
Symbols:
+ +[CEKDiscreteSliderAccessibility _accessibilityPerformValidations:]
+ +[CEKDiscreteSliderAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[CEKDiscreteSliderAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[CEKDiscreteSliderAccessibility _axAdjustValue:]
+ -[CEKDiscreteSliderAccessibility accessibilityDecrement]
+ -[CEKDiscreteSliderAccessibility accessibilityIncrement]
+ -[CEKDiscreteSliderAccessibility accessibilityLabel]
+ -[CEKDiscreteSliderAccessibility accessibilityTraits]
+ -[CEKDiscreteSliderAccessibility accessibilityValue]
+ -[CEKDiscreteSliderAccessibility isAccessibilityElement]
+ -[CEKDiscreteSliderAccessibility scrollViewDidScroll:]
+ GCC_except_table93
+ _OBJC_CLASS_$_CEKDiscreteSliderAccessibility
+ _OBJC_CLASS_$___CEKDiscreteSliderAccessibility_super
+ _OBJC_METACLASS_$_CEKDiscreteSliderAccessibility
+ _OBJC_METACLASS_$___CEKDiscreteSliderAccessibility_super
+ __OBJC_$_CLASS_METHODS_CEKDiscreteSliderAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_CEKDiscreteSliderAccessibility
+ __OBJC_CLASS_RO_$_CEKDiscreteSliderAccessibility
+ __OBJC_CLASS_RO_$___CEKDiscreteSliderAccessibility_super
+ __OBJC_METACLASS_RO_$_CEKDiscreteSliderAccessibility
+ __OBJC_METACLASS_RO_$___CEKDiscreteSliderAccessibility_super
+ ___49-[CEKDiscreteSliderAccessibility _axAdjustValue:]_block_invoke
- GCC_except_table81
CStrings:
+ "CEKDiscreteSliderAccessibility"
+ "UIControl"
```
