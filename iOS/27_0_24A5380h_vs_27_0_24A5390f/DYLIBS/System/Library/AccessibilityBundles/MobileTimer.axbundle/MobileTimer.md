## MobileTimer

> `/System/Library/AccessibilityBundles/MobileTimer.axbundle/MobileTimer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8c0c` | `0x8d28` | **`+0x11c`** |
| `__DATA_CONST.__objc_selrefs` | `0x748` | `0x758` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xf98` | `0xfa8` | **`+0x10`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 302
-  Symbols:   860
+  Functions: 304
+  Symbols:   863
Symbols:
+ -[MTAAlarmTableViewCellAccessibility accessibilityActivate]
+ GCC_except_table173
+ GCC_except_table217
+ GCC_except_table245
+ GCC_except_table79
+ GCC_except_table82
+ _UIAccessibilityTraitToggleButton
+ ___59-[MTAAlarmTableViewCellAccessibility accessibilityActivate]_block_invoke
+ _objc_retainAutoreleaseReturnValue
- GCC_except_table171
- GCC_except_table215
- GCC_except_table243
- GCC_except_table77
- GCC_except_table80
- _UIAccessibilityTraitToggle
```
