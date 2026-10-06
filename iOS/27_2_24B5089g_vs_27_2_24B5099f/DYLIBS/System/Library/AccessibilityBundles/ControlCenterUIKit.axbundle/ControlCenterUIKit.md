## ControlCenterUIKit

> `/System/Library/AccessibilityBundles/ControlCenterUIKit.axbundle/ControlCenterUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5870` | `0x5944` | **`+0xd4`** |
| `__TEXT.__objc_methlist` | `0x834` | `0x83c` | **`+0x8`** |

### Other Changes

```diff

-3050.3.1.0.0
+3050.3.5.0.0

-  Functions: 186
-  Symbols:   462
+  Functions: 187
+  Symbols:   463
Symbols:
+ -[CCUIControlTemplateViewAccessibility accessibilityTraits]
+ GCC_except_table111
+ GCC_except_table119
+ GCC_except_table172
+ GCC_except_table76
- GCC_except_table110
- GCC_except_table118
- GCC_except_table171
- GCC_except_table75
Functions:
+ -[CCUIControlTemplateViewAccessibility accessibilityTraits]
~ -[CCUIButtonModuleViewControllerAccessibility _accessibilityLoadAccessibilityInformation] : 1668 -> 1708
~ ___89-[CCUIButtonModuleViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_3 : 188 -> 224
```
