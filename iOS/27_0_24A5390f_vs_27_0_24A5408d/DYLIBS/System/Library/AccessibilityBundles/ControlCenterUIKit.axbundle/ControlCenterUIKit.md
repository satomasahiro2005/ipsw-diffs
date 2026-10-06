## ControlCenterUIKit

> `/System/Library/AccessibilityBundles/ControlCenterUIKit.axbundle/ControlCenterUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methlist` | `0x82c` | `0x834` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__text` | `0x586c` | `0x5864` | **`-0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 185
-  Symbols:   464
-  CStrings:  145
+  Functions: 186
+  Symbols:   462
+  CStrings:  144
Symbols:
+ -[CCUIButtonModuleViewControllerAccessibility viewWillAppear:]
+ GCC_except_table171
- GCC_except_table170
- _AXLogTemp
- __os_log_debug_impl
- _os_log_type_enabled
Functions:
~ -[CCUIButtonModuleViewControllerAccessibility _accessibilityControlCenterRoundButtonIdentifier] : 276 -> 192
CStrings:
- "SUP MAN"
```
