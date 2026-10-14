## MobileSafariUI

> `/System/Library/AccessibilityBundles/MobileSafariUI.axbundle/MobileSafariUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa4e0` | `0xa5b8` | **`+0xd8`** |
| `__TEXT.__objc_methlist` | `0xd60` | `0xd78` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x788` | `0x798` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x204` | `0x1f4` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x3a8` | `0x3b0` | **`+0x8`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  Functions: 274
-  Symbols:   798
+  Functions: 276
+  Symbols:   800
Symbols:
+ -[StartPageSegmentedViewControllerAccessibility _axSetUpAccessibilityElementsForView:]
+ -[StartPageSegmentedViewControllerAccessibility viewDidLoad]
+ GCC_except_table117
+ GCC_except_table126
+ GCC_except_table181
+ GCC_except_table253
+ GCC_except_table262
+ GCC_except_table73
+ GCC_except_table91
+ ___86-[StartPageSegmentedViewControllerAccessibility _axSetUpAccessibilityElementsForView:]_block_invoke
- GCC_except_table115
- GCC_except_table124
- GCC_except_table179
- GCC_except_table251
- GCC_except_table260
- GCC_except_table71
- GCC_except_table89
- ___91-[StartPageSegmentedViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
```
