## SwiftUI

> `/System/Library/AccessibilityBundles/SwiftUI.axbundle/SwiftUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0xd90` | `0xc70` | **`-0x120`** |
| `__TEXT.__text` | `0x2da8` | `0x2e94` | **`+0xec`** |
| `__DATA_DIRTY.__objc_data` | `0x4b0` | `0x410` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x5c0` | `0x560` | **`-0x60`** |
| `__TEXT.__cstring` | `0x527` | `0x4d3` | **`-0x54`** |
| `__DATA_CONST.__const` | `0x138` | `0x180` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x4b8` | `0x4f0` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x718` | `0x6e8` | **`-0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x78` | `0x68` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x98` | `0xa0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x28` | `0x20` | **`-0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Symbols:   312
-  CStrings:  56
+  Symbols:   307
+  CStrings:  53
Symbols:
+ -[AccessibilityNodeAccessibility _accessibilityIsSpeakThisElement]
+ -[AccessibilityNodeAccessibility _accessibilityKeyboardKeyAllowsTouchTyping]
+ -[AccessibilityNodeAccessibility _accessibilityReplacementForFocusedOpaqueElement]
+ -[AccessibilityNodeAccessibility _accessibilityVisiblePoint]
+ -[AccessibilityNodeAccessibility _axIsDetachedFromAccessibilityContainer]
+ GCC_except_table39
+ GCC_except_table43
+ GCC_except_table48
+ GCC_except_table62
+ GCC_except_table74
+ _AXSafeClassFromString
+ _UIAccessibilityTraitKeyboardKey
+ ___66-[AccessibilityNodeAccessibility _accessibilityIsSpeakThisElement]_block_invoke
+ ___82-[AccessibilityNodeAccessibility _accessibilityReplacementForFocusedOpaqueElement]_block_invoke
+ ___block_descriptor_48_e8_B16?08lu32l8u40l8
+ ___block_descriptor_64_e8_32s40s48s_e8_B16?08ls32l8s40l8s48l8
+ _objc_retain_x21
- +[SwiftUIUIKitBarButtonItemAccessibility _accessibilityPerformValidations:]
- +[SwiftUIUIKitBarButtonItemAccessibility(SafeCategory) safeCategoryBaseClass]
- +[SwiftUIUIKitBarButtonItemAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[SwiftUIUIKitBarButtonItemAccessibility accessibilityHint]
- -[SwiftUIUIKitBarButtonItemAccessibility accessibilityIdentifier]
- -[SwiftUIUIKitBarButtonItemAccessibility accessibilityLabel]
- -[SwiftUIUIKitBarButtonItemAccessibility accessibilityValue]
- GCC_except_table42
- GCC_except_table46
- GCC_except_table60
- GCC_except_table70
- GCC_except_table76
- _OBJC_CLASS_$_SwiftUIUIKitBarButtonItemAccessibility
- _OBJC_CLASS_$___SwiftUIUIKitBarButtonItemAccessibility_super
- _OBJC_METACLASS_$_SwiftUIUIKitBarButtonItemAccessibility
- _OBJC_METACLASS_$___SwiftUIUIKitBarButtonItemAccessibility_super
- __OBJC_$_CLASS_METHODS_SwiftUIUIKitBarButtonItemAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_SwiftUIUIKitBarButtonItemAccessibility
- __OBJC_CLASS_RO_$_SwiftUIUIKitBarButtonItemAccessibility
- __OBJC_CLASS_RO_$___SwiftUIUIKitBarButtonItemAccessibility_super
- __OBJC_METACLASS_RO_$_SwiftUIUIKitBarButtonItemAccessibility
- __OBJC_METACLASS_RO_$___SwiftUIUIKitBarButtonItemAccessibility_super
CStrings:
+ "SwiftUI.ListCollectionViewCell"
+ "a"
- "SwiftUI.UIKitBarButtonItem"
- "SwiftUIUIKitBarButtonItemAccessibility"
- "UIBarButtonItem"
- "UIKitBarItemHost<BarItemView>"
- "host"
```
