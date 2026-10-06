## HealthExperienceUI

> `/System/Library/AccessibilityBundles/HealthExperienceUI.axbundle/HealthExperienceUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a74` | `0x2b44` | **`+0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x90` | `0x98` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xa34` | `0xa3c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1e0` | `0x1e8` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 181
-  Symbols:   541
+  Functions: 182
+  Symbols:   542
Symbols:
+ -[DataTypeTileHeaderViewAccessibility _axIsContainingCellSelectable]
+ GCC_except_table153
- GCC_except_table152
Functions:
~ -[DataTypeTileHeaderViewAccessibility accessibilityTraits] : 16 -> 116
+ -[DataTypeTileHeaderViewAccessibility _axIsContainingCellSelectable]
```
