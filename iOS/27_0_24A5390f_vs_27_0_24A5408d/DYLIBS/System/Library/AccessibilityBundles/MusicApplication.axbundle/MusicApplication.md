## MusicApplication

> `/System/Library/AccessibilityBundles/MusicApplication.axbundle/MusicApplication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x122a0` | `0x12598` | **`+0x2f8`** |
| `__DATA_CONST.__objc_selrefs` | `0x8b8` | `0x900` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x218` | `0x238` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2960` | `0x2980` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x880` | `0x890` | **`+0x10`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 761
-  Symbols:   1978
+  Functions: 764
+  Symbols:   1986
Symbols:
+ -[PlayerTimeControlAccessibility accessibilityAttributedValue]
+ -[SongCellAccessibility _axLabelWithDurationString:]
+ -[SongCellAccessibility accessibilityAttributedLabel]
+ GCC_except_table519
+ GCC_except_table537
+ GCC_except_table665
+ _AXCompactDurationStringForDuration
+ _OBJC_CLASS_$_AXAttributedString
+ _UIAccessibilityTokenDurationTimeHHMMSS
+ _UIAccessibilityTokenDurationTimeMMSS
+ ___kCFBooleanTrue
- GCC_except_table516
- GCC_except_table534
- GCC_except_table662
```
