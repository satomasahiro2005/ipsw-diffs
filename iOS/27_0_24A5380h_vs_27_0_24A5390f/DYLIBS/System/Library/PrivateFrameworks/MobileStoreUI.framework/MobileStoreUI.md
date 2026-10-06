## MobileStoreUI

> `/System/Library/PrivateFrameworks/MobileStoreUI.framework/MobileStoreUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e5e8c` | `0x2e6158` | **`+0x2cc`** |
| `__DATA_CONST.__got` | `0x1c80` | `0x1eb8` | **`+0x238`** |
| `__TEXT.__gcc_except_tab` | `0x5dc0` | `0x5de4` | **`+0x24`** |
| `__TEXT.__unwind_info` | `0xca00` | `0xca18` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0xbb350` | `0xbb360` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x33284` | `0x33294` | **`+0x10`** |

### Other Changes

```diff

-1203.0.13.0.0
+1203.0.14.0.0

-  Functions: 17831
-  Symbols:   33313
+  Functions: 17834
+  Symbols:   33316
Symbols:
+ -[SUUINavigationPaletteView safeAreaInsetsDidChange]
+ -[SUUISegmentedControlViewElement numberOfSegments]
+ ___51-[SUUISegmentedControlViewElement numberOfSegments]_block_invoke
+ ___block_descriptor_128_e8_32s40r48r_e23_v32?0"UIView"8Q16^B24lr40l8s32l8r48l8
- ___block_descriptor_96_e8_32s40r48r_e23_v32?0"UIView"8Q16^B24lr40l8s32l8r48l8
```
