## SystemStatusUI

> `/System/Library/AccessibilityBundles/SystemStatusUI.axbundle/SystemStatusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7354` | `0x7528` | **`+0x1d4`** |
| `__DATA_CONST.__const` | `0x358` | `0x380` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x430` | `0x448` | **`+0x18`** |
| `__TEXT.__cstring` | `0x23c0` | `0x23d1` | **`+0x11`** |
| `__TEXT.__gcc_except_tab` | `0xfc` | `0x10c` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x258` | `0x260` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 202
-  Symbols:   659
-  CStrings:  343
+  Functions: 203
+  Symbols:   663
+  CStrings:  344
Symbols:
+ GCC_except_table78
+ GCC_except_table97
+ _AX_CGRectGetCenter
+ _OBJC_CLASS_$_UIView
+ ___67-[STUIStatusBarBatteryItemAccessibility applyUpdate:toDisplayItem:]_block_invoke_3
+ ___block_descriptor_40_e8_32w_e16_{CGPoint=dd}8?0lw32l8
- GCC_except_table77
- GCC_except_table96
Functions:
~ -[STUIStatusBarAccessibility _accessibilityHitTest:withEvent:] : 1344 -> 1356
~ -[STUIStatusBarAccessibility accessibilityElements] : 164 -> 280
~ -[STUIStatusBarBatteryItemAccessibility applyUpdate:toDisplayItem:] : 648 -> 780
~ ___67-[STUIStatusBarBatteryItemAccessibility applyUpdate:toDisplayItem:]_block_invoke_2 : 188 -> 208
+ ___67-[STUIStatusBarBatteryItemAccessibility applyUpdate:toDisplayItem:]_block_invoke_3
CStrings:
+ "{CGPoint=dd}8@?0"
```
