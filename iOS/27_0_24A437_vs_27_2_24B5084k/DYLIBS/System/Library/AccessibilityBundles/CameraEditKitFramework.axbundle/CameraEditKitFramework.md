## CameraEditKitFramework

> `/System/Library/AccessibilityBundles/CameraEditKitFramework.axbundle/CameraEditKitFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x407c` | `0x3fd8` | **`-0xa4`** |
| `__DATA_CONST.__objc_selrefs` | `0x340` | `0x348` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1f0` | `0x1f8` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 132
-  Symbols:   297
+  Functions: 133
+  Symbols:   298
Symbols:
+ GCC_except_table97
+ ___75-[CEKExpandingSliderAccessibility _axChangeValueInDirection:withLargeStep:]_block_invoke_3
- GCC_except_table96
Functions:
~ +[CEKExpandingSliderAccessibility _accessibilityPerformValidations:] : 464 -> 484
~ -[CEKExpandingSliderAccessibility accessibilityTraits] : 104 -> 72
~ -[CEKExpandingSliderAccessibility _axChangeValueInDirection:withLargeStep:] : 348 -> 440
~ ___75-[CEKExpandingSliderAccessibility _axChangeValueInDirection:withLargeStep:]_block_invoke : 120 -> 20
~ ___75-[CEKExpandingSliderAccessibility _axChangeValueInDirection:withLargeStep:]_block_invoke_2 : 120 -> 112
+ ___75-[CEKExpandingSliderAccessibility _axChangeValueInDirection:withLargeStep:]_block_invoke_3
~ -[CEKSliderAccessibility accessibilityValue] : 424 -> 464
~ -[CEKSliderAccessibility scrollViewDidScroll:] : 936 -> 648
```
