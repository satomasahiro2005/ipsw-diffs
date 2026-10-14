## ControlCenterUI

> `/System/Library/AccessibilityBundles/ControlCenterUI.axbundle/ControlCenterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21b0` | `0x229c` | **`+0xec`** |
| `__TEXT.__cstring` | `0xa04` | `0xa2f` | **`+0x2b`** |
| `__AUTH_CONST.__cfstring` | `0xb40` | `0xb60` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x118` | `0x138` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x230` | `0x240` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x168` | `0x170` | **`+0x8`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  Functions: 83
-  Symbols:   274
-  CStrings:  105
+  Functions: 84
+  Symbols:   276
+  CStrings:  107
Symbols:
+ GCC_except_table73
+ GCC_except_table76
+ ___58-[CCUIHeaderPocketViewAccessibility accessibilityElements]_block_invoke
+ ___block_descriptor_40_e16_B16?0"UIView"8lu32l8
- GCC_except_table72
- GCC_except_table75
Functions:
~ -[CCUIHeaderPocketViewAccessibility accessibilityElements] : 380 -> 536
+ ___58-[CCUIHeaderPocketViewAccessibility accessibilityElements]_block_invoke
CStrings:
+ "B16@?0@\"UIView\"8"
+ "STUIStatusBarCombinedView"
```
