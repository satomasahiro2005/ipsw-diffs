## Podcasts

> `/System/Library/AccessibilityBundles/Podcasts.axbundle/Podcasts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c64` | `0x7d0c` | **`+0xa8`** |
| `__DATA_CONST.__objc_selrefs` | `0x530` | `0x548` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x12cc` | `0x12dc` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xe8` | `0xf0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3f8` | `0x400` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 306
-  Symbols:   928
+  Functions: 308
+  Symbols:   932
Symbols:
+ -[EpisodeInfoViewAccessibility accessibilityTraits]
+ -[PlayControlsStackViewAccessibility accessibilityActivate]
+ GCC_except_table114
+ GCC_except_table141
+ GCC_except_table162
+ GCC_except_table186
+ GCC_except_table213
+ GCC_except_table271
+ GCC_except_table299
+ GCC_except_table60
+ GCC_except_table63
+ GCC_except_table74
+ GCC_except_table78
+ _AXCompactDurationStringForDuration
+ _UIAccessibilityTraitStaticText
- GCC_except_table112
- GCC_except_table139
- GCC_except_table160
- GCC_except_table184
- GCC_except_table211
- GCC_except_table269
- GCC_except_table297
- GCC_except_table59
- GCC_except_table62
- GCC_except_table73
- GCC_except_table77
Functions:
+ -[PlayControlsStackViewAccessibility accessibilityActivate]
+ -[EpisodeInfoViewAccessibility accessibilityTraits]
~ -[MTAVPlayerTOCViewControllerAccessibility configureCell:withObject:atIndexPath:] : 212 -> 308
```
