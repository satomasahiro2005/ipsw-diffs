## PosterKit

> `/System/Library/AccessibilityBundles/PosterKit.axbundle/PosterKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7448` | `0x7cc4` | **`+0x87c`** |
| `__TEXT.__oslogstring` | `—` | `0x2ec` | **`+0x2ec`** |
| `__AUTH.__objc_data` | `0xa0` | `0x1e0` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x27f0` | `0x2910` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0x2340` | `0x2400` | **`+0xc0`** |
| `__DATA_DIRTY.__objc_data` | `0x1590` | `0x14f0` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x1d39` | `0x1d9f` | **`+0x66`** |
| `__TEXT.__objc_methlist` | `0xcec` | `0xd4c` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x538` | `0x558` | **`+0x20`** |
| `__TEXT.__const` | `0x28` | `0x48` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x328` | `0x340` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x238` | `0x248` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xa0` | `0xb0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x108` | `0x110` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 248
-  Symbols:   745
-  CStrings:  299
+  Functions: 254
+  Symbols:   769
+  CStrings:  311
Symbols:
+ +[AccessibilityNodeAccessibility__PosterKit__SwiftUI _accessibilityPerformValidations:]
+ +[AccessibilityNodeAccessibility__PosterKit__SwiftUI(SafeCategory) safeCategoryBaseClass]
+ +[AccessibilityNodeAccessibility__PosterKit__SwiftUI(SafeCategory) safeCategoryTargetClassName]
+ +[UIViewAccessibility__PosterKit__UIKit _accessibilityPerformValidations:]
+ +[UIViewAccessibility__PosterKit__UIKit(SafeCategory) safeCategoryBaseClass]
+ +[UIViewAccessibility__PosterKit__UIKit(SafeCategory) safeCategoryTargetClassName]
+ -[AccessibilityNodeAccessibility__PosterKit__SwiftUI _accessibilityShouldUseHostContextIDForLongPress]
+ -[PREditingCloseBoxButtonAccessibility accessibilityFrame]
+ -[PREditingCloseBoxButtonAccessibility accessibilityPath]
+ -[UIViewAccessibility__PosterKit__UIKit _accessibilityShouldUseHostContextIDForLongPress]
+ GCC_except_table113
+ GCC_except_table154
+ GCC_except_table156
+ GCC_except_table23
+ GCC_except_table32
+ GCC_except_table33
+ GCC_except_table34
+ GCC_except_table37
+ GCC_except_table88
+ GCC_except_table90
+ _AXAIWhiteGloveLoggingEnabled
+ _AXLogAppAccessibility
+ _CGRectZero
+ _NSStringFromCGRect
+ _NSStringFromClass
+ _OBJC_CLASS_$_AccessibilityNodeAccessibility__PosterKit__SwiftUI
+ _OBJC_CLASS_$_UIViewAccessibility__PosterKit__UIKit
+ _OBJC_CLASS_$___AccessibilityNodeAccessibility__PosterKit__SwiftUI_super
+ _OBJC_CLASS_$___UIViewAccessibility__PosterKit__UIKit_super
+ _OBJC_METACLASS_$_AccessibilityNodeAccessibility__PosterKit__SwiftUI
+ _OBJC_METACLASS_$_UIViewAccessibility__PosterKit__UIKit
+ _OBJC_METACLASS_$___AccessibilityNodeAccessibility__PosterKit__SwiftUI_super
+ _OBJC_METACLASS_$___UIViewAccessibility__PosterKit__UIKit_super
+ __OBJC_$_CLASS_METHODS_AccessibilityNodeAccessibility__PosterKit__SwiftUI(SafeCategory)
+ __OBJC_$_CLASS_METHODS_UIViewAccessibility__PosterKit__UIKit(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_AccessibilityNodeAccessibility__PosterKit__SwiftUI
+ __OBJC_$_INSTANCE_METHODS_UIViewAccessibility__PosterKit__UIKit
+ __OBJC_CLASS_RO_$_AccessibilityNodeAccessibility__PosterKit__SwiftUI
+ __OBJC_CLASS_RO_$_UIViewAccessibility__PosterKit__UIKit
+ __OBJC_CLASS_RO_$___AccessibilityNodeAccessibility__PosterKit__SwiftUI_super
+ __OBJC_CLASS_RO_$___UIViewAccessibility__PosterKit__UIKit_super
+ __OBJC_METACLASS_RO_$_AccessibilityNodeAccessibility__PosterKit__SwiftUI
+ __OBJC_METACLASS_RO_$_UIViewAccessibility__PosterKit__UIKit
+ __OBJC_METACLASS_RO_$___AccessibilityNodeAccessibility__PosterKit__SwiftUI_super
+ __OBJC_METACLASS_RO_$___UIViewAccessibility__PosterKit__UIKit_super
+ __os_log_impl
+ _objc_opt_respondsToSelector
+ _os_log_type_enabled
- +[UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility _accessibilityPerformValidations:]
- +[UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility(SafeCategory) safeCategoryBaseClass]
- +[UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility _accessibilityShouldUseHostContextIDForLongPress]
- GCC_except_table107
- GCC_except_table148
- GCC_except_table150
- GCC_except_table17
- GCC_except_table21
- GCC_except_table22
- GCC_except_table26
- GCC_except_table31
- GCC_except_table82
- GCC_except_table84
- _OBJC_CLASS_$_UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility
- _OBJC_CLASS_$___UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility_super
- _OBJC_METACLASS_$_UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility
- _OBJC_METACLASS_$___UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility_super
- __OBJC_$_CLASS_METHODS_UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility
- __OBJC_CLASS_RO_$_UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility
- __OBJC_CLASS_RO_$___UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility_super
- __OBJC_METACLASS_RO_$_UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility
- __OBJC_METACLASS_RO_$___UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility_super
CStrings:
+ "(nil)"
+ "AccessibilityNodeAccessibility__PosterKit__SwiftUI"
+ "PRPosterRoleAmbient"
+ "SwiftUI.AccessibilityNode"
+ "UIViewAccessibility__PosterKit__UIKit"
+ "contentOverlayContainerView"
+ "n/a"
+ "rdar://166768799 PREditingCloseBoxButton accessibilityFrame class=%{public}@ axFrame={%.1f,%.1f,%.1f,%.1f} viewFrame={%.1f,%.1f,%.1f,%.1f} viewBounds={%.1f,%.1f,%.1f,%.1f} superviewClass=%{public}@ superviewBounds={%.1f,%.1f,%.1f,%.1f}"
+ "rdar://166768799 PREditingCloseBoxButton accessibilityLabel (Cancel/Close branch) class=%{public}@"
+ "rdar://166768799 PREditingCloseBoxButton accessibilityLabel (CheckMark branch) class=%{public}@"
+ "rdar://166768799 PREditingCloseBoxButton accessibilityLabel (Hide branch) class=%{public}@"
+ "rdar://166768799 PREditingCloseBoxButton accessibilityLabel (user-defined) class=%{public}@ userLabel=%{public}@"
+ "rdar://166768799 PREditingCloseBoxButton accessibilityPath class=%{public}@ pathIsNil=%d pathBounds={%{public}@}"
- "UIViewLongPressHostContextAccessibility__PosterKit__UIKitAccessibility"
```
