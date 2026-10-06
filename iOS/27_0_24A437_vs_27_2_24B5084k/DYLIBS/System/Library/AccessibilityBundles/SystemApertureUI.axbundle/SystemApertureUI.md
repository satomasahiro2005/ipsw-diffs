## SystemApertureUI

> `/System/Library/AccessibilityBundles/SystemApertureUI.axbundle/SystemApertureUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2950` | `0x29d0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x3fc` | `0x414` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3c0` | `0x3d0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x160` | `0x168` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 71
-  Symbols:   252
+  Functions: 73
+  Symbols:   254
Symbols:
+ -[SAUIElementViewAccessibility _accessibilityHintIsInstructional]
+ -[SAUIElementViewAccessibility _axHintLocalizationKey]
```
