## CameraEditKitFramework

> `/System/Library/AccessibilityBundles/CameraEditKitFramework.axbundle/CameraEditKitFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3eac` | `0x407c` | **`+0x1d0`** |
| `__AUTH_CONST.__cfstring` | `0xec0` | `0xf20` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x55c` | `0x574` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x330` | `0x340` | **`+0x10`** |
| `__TEXT.__cstring` | `0x8ed` | `0x8fd` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__TEXT.__ustring` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 129
-  Symbols:   293
-  CStrings:  131
+  Functions: 132
+  Symbols:   297
+  CStrings:  134
Symbols:
+ -[CEKExpandingSliderAccessibility accessibilityActivationPoint]
+ -[CEKExpandingSliderAccessibility accessibilityElementDidLoseFocus]
+ GCC_except_table96
+ _AX_CGRectGetCenter
+ ___67-[CEKExpandingSliderAccessibility accessibilityElementDidLoseFocus]_block_invoke
- GCC_except_table93
CStrings:
+ "_ticksView"
+ "text"
+ "ƒ%@"
```
