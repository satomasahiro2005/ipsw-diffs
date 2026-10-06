## SystemStatusUI

> `/System/Library/AccessibilityBundles/SystemStatusUI.axbundle/SystemStatusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7528` | `0x7710` | **`+0x1e8`** |
| `__TEXT.__objc_methlist` | `0xa58` | `0xa7c` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x28c0` | `0x28e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x23d1` | `0x23e2` | **`+0x11`** |
| `__TEXT.__unwind_info` | `0x2f8` | `0x300` | **`+0x8`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  Functions: 203
-  Symbols:   663
-  CStrings:  344
+  Functions: 206
+  Symbols:   668
+  CStrings:  345
Symbols:
+ -[STUIStatusBarAccessibility _accessibilityStatusBarIsVerticalAlongWindowEdge]
+ -[STUIStatusBarAccessibility shouldGroupAccessibilityChildren]
+ -[STUIStatusBar_WrapperAccessibility _accessibilityStatusBarIsVerticalAlongWindowEdge]
+ GCC_except_table100
+ GCC_except_table27
+ GCC_except_table32
+ GCC_except_table53
+ GCC_except_table70
+ GCC_except_table81
+ _NSSelectorFromString
+ _objc_opt_respondsToSelector
- GCC_except_table26
- GCC_except_table31
- GCC_except_table50
- GCC_except_table67
- GCC_except_table78
- GCC_except_table97
CStrings:
+ "isVerticalLayout"
```
