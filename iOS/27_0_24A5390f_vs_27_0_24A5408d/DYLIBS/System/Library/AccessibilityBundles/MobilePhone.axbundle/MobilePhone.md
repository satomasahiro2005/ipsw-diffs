## MobilePhone

> `/System/Library/AccessibilityBundles/MobilePhone.axbundle/MobilePhone`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f08` | `0x50f0` | **`+0x1e8`** |
| `__DATA_CONST.__objc_selrefs` | `0x540` | `0x560` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x91c` | `0x92c` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x168` | `0x170` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x238` | `0x240` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 161
-  Symbols:   523
+  Functions: 162
+  Symbols:   526
Symbols:
+ -[VMPlayerTimelineSliderAccessibility accessibilityAttributedValue]
+ _AXCompactDurationStringForDuration
+ _OBJC_CLASS_$_NSAttributedString
Functions:
+ -[VMPlayerTimelineSliderAccessibility accessibilityAttributedValue]
```
