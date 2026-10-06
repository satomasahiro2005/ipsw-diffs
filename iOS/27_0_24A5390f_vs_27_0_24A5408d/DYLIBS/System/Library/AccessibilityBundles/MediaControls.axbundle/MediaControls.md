## MediaControls

> `/System/Library/AccessibilityBundles/MediaControls.axbundle/MediaControls`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa7a4` | `0xa928` | **`+0x184`** |
| `__DATA_CONST.__objc_selrefs` | `0x690` | `0x6a8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1304` | `0x1314` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x468` | `0x470` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 367
-  Symbols:   1004
+  Functions: 368
+  Symbols:   1006
Symbols:
+ -[MRUNowPlayingTimeControlsViewAccessibility accessibilityAttributedValue]
+ GCC_except_table309
+ GCC_except_table346
+ _AXCompactDurationStringForDuration
- GCC_except_table308
- GCC_except_table345
Functions:
+ -[MRUNowPlayingTimeControlsViewAccessibility accessibilityAttributedValue]
~ ___88-[MRUNowPlayingTimeControlsViewAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke : 176 -> 196
```
