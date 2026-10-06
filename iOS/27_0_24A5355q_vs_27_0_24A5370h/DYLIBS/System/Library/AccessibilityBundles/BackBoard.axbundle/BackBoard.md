## BackBoard

> `/System/Library/AccessibilityBundles/BackBoard.axbundle/BackBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27cd0` | `0x27d9c` | **`+0xcc`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bb0` | `0x1bc8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x22bc` | `0x22d4` | **`+0x18`** |
| `__DATA.__bss` | `0x528` | `0x530` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd08` | `0xd10` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 1015
-  Symbols:   2089
+  Functions: 1018
+  Symbols:   2092
Symbols:
+ -[AXBHomeClickController presentAccessibilityShortcutChooser]
+ -[AXBackBoardServerInstance _handlePresentAccessibilityShortcutChooser:]
+ GCC_except_table567
+ GCC_except_table596
+ GCC_except_table613
+ GCC_except_table626
+ GCC_except_table638
+ GCC_except_table671
+ GCC_except_table709
+ GCC_except_table723
+ GCC_except_table797
+ ___61-[AXBHomeClickController presentAccessibilityShortcutChooser]_block_invoke
- GCC_except_table565
- GCC_except_table594
- GCC_except_table611
- GCC_except_table624
- GCC_except_table636
- GCC_except_table669
- GCC_except_table707
- GCC_except_table721
- GCC_except_table794
```
