## PencilKit

> `/System/Library/AccessibilityBundles/PencilKit.axbundle/PencilKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3c0` | `0xa0` | **`-0x320`** |
| `__DATA_DIRTY.__objc_data` | `0xe10` | `0x1090` | **`+0x280`** |
| `__AUTH_CONST.__objc_const` | `0x2010` | `0x1ef0` | **`-0x120`** |
| `__TEXT.__objc_methlist` | `0xa60` | `0x9f8` | **`-0x68`** |
| `__TEXT.__text` | `0x42cc` | `0x426c` | **`-0x60`** |
| `__AUTH_CONST.__cfstring` | `0x1980` | `0x1940` | **`-0x40`** |
| `__TEXT.__cstring` | `0x13e1` | `0x13ae` | **`-0x33`** |
| `__DATA_CONST.__objc_classlist` | `0x1c8` | `0x1b8` | **`-0x10`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 180
-  Symbols:   562
-  CStrings:  220
+  Functions: 173
+  Symbols:   545
+  CStrings:  218
Symbols:
+ GCC_except_table117
- +[PKDragIndicatorViewAccessibility _accessibilityPerformValidations:]
- +[PKDragIndicatorViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[PKDragIndicatorViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[PKDragIndicatorViewAccessibility accessibilityHint]
- -[PKDragIndicatorViewAccessibility accessibilityLabel]
- -[PKDragIndicatorViewAccessibility accessibilityTraits]
- -[PKDragIndicatorViewAccessibility isAccessibilityElement]
- GCC_except_table124
- _OBJC_CLASS_$_PKDragIndicatorViewAccessibility
- _OBJC_CLASS_$___PKDragIndicatorViewAccessibility_super
- _OBJC_METACLASS_$_PKDragIndicatorViewAccessibility
- _OBJC_METACLASS_$___PKDragIndicatorViewAccessibility_super
- __OBJC_$_CLASS_METHODS_PKDragIndicatorViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_PKDragIndicatorViewAccessibility
- __OBJC_CLASS_RO_$_PKDragIndicatorViewAccessibility
- __OBJC_CLASS_RO_$___PKDragIndicatorViewAccessibility_super
- __OBJC_METACLASS_RO_$_PKDragIndicatorViewAccessibility
- __OBJC_METACLASS_RO_$___PKDragIndicatorViewAccessibility_super
CStrings:
+ "_accessoryView"
+ "_dragHandleView"
- "PKDragIndicatorView"
- "PKDragIndicatorViewAccessibility"
- "accessoryView"
- "dragHandleView"
```
