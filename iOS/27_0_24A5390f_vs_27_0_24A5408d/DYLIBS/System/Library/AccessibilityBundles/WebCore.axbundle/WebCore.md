## WebCore

> `/System/Library/AccessibilityBundles/WebCore.axbundle/WebCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x111b8` | `0x1111c` | **`-0x9c`** |
| `__TEXT.__gcc_except_tab` | `0x418` | `0x3e4` | **`-0x34`** |
| `__DATA_CONST.__const` | `0x3c0` | `0x398` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x500` | `0x4f0` | **`-0x10`** |
| `__TEXT.__cstring` | `0x23ad` | `0x23a9` | **`-0x4`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 350
-  Symbols:   786
-  CStrings:  487
+  Functions: 349
+  Symbols:   783
+  CStrings:  486
Symbols:
+ GCC_except_table202
+ GCC_except_table213
+ GCC_except_table226
+ GCC_except_table228
+ GCC_except_table245
+ GCC_except_table249
+ GCC_except_table267
+ GCC_except_table276
+ GCC_except_table278
+ _objc_retain_x27
- GCC_except_table190
- GCC_except_table203
- GCC_except_table214
- GCC_except_table227
- GCC_except_table229
- GCC_except_table246
- GCC_except_table250
- GCC_except_table268
- GCC_except_table277
- GCC_except_table279
- ___block_descriptor_84_e8_32s40r48r_e15_v32?08Q16^B24ls32l8u56l8r40l8r48l8
- ___fuzzyAccessibilityHitTest_block_invoke
- _objc_release_x3
Functions:
~ -[UIKitWebAccessibilityObjectWrapper accessibilityCanFuzzyHitTest] : 116 -> 124
~ -[UIKitWebAccessibilityObjectWrapper accessibilityHitTest:] : 196 -> 220
~ -[UIKitWebAccessibilityObjectWrapper accessibilityPostProcessHitTest:] : 664 -> 1560
- ___fuzzyAccessibilityHitTest_block_invoke
CStrings:
- "0A`"
```
