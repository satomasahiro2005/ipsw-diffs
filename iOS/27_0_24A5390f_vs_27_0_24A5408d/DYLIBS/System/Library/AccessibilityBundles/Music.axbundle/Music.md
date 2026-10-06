## Music

> `/System/Library/AccessibilityBundles/Music.axbundle/Music`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc4dc` | `0xc630` | **`+0x154`** |
| `__DATA_CONST.__objc_selrefs` | `0x810` | `0x830` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x131c` | `0x1324` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4c8` | `0x4d0` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 398
-  Symbols:   1040
+  Functions: 399
+  Symbols:   1042
Symbols:
+ -[PlayerTimeControlAccessibility accessibilityAttributedValue]
+ _AXCompactDurationStringForDuration
Functions:
+ -[PlayerTimeControlAccessibility accessibilityAttributedValue]
```
