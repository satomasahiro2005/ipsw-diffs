## CameraUI

> `/System/Library/AccessibilityBundles/CameraUI.axbundle/CameraUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e114` | `0x1e40c` | **`+0x2f8`** |
| `__DATA_CONST.__const` | `0xaf8` | `0xb30` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x5c80` | `0x5ca0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x15a0` | `0x15b8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x371c` | `0x3734` | **`+0x18`** |
| `__TEXT.__cstring` | `0x4623` | `0x4639` | **`+0x16`** |
| `__TEXT.__gcc_except_tab` | `0x4f8` | `0x50c` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0xc98` | `0xca0` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 1159
-  Symbols:   2548
-  CStrings:  798
+  Functions: 1162
+  Symbols:   2553
+  CStrings:  799
Symbols:
+ -[CAMZoomControlAccessibility _accessibilityAdditionalElements]
+ -[CAMZoomControlAccessibility _accessibilityHitTest:withEvent:]
+ GCC_except_table1063
+ GCC_except_table1090
+ GCC_except_table771
+ GCC_except_table807
+ GCC_except_table819
+ GCC_except_table838
+ GCC_except_table871
+ GCC_except_table934
+ GCC_except_table952
+ GCC_except_table958
+ GCC_except_table962
+ GCC_except_table976
+ _CGRectContainsPoint
+ _UIAccessibilityPointForPoint
+ ___66-[CAMDynamicShutterControlAccessibility _axElementForCenterButton]_block_invoke_6
- GCC_except_table1062
- GCC_except_table1089
- GCC_except_table770
- GCC_except_table806
- GCC_except_table818
- GCC_except_table837
- GCC_except_table870
- GCC_except_table933
- GCC_except_table950
- GCC_except_table957
- GCC_except_table961
- GCC_except_table975
CStrings:
+ "flipAspectRatioButton"
```
