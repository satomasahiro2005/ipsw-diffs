## TVMLKit

> `/System/Library/PrivateFrameworks/TVMLKit.framework/TVMLKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc194` | `0xdc3d4` | **`+0x240`** |
| `__DATA_CONST.__got` | `0xe60` | `0xf48` | **`+0xe8`** |
| `__AUTH_CONST.__objc_const` | `0x2f150` | `0x2f180` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x3568` | `0x3590` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x8628` | `0x8650` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x10144` | `0x1015c` | **`+0x18`** |

### Other Changes

```diff

-1151.0.0.0.0
+1151.0.1.0.0

-  Functions: 5339
-  Symbols:   10391
+  Functions: 5340
+  Symbols:   10395
Symbols:
+ GCC_except_table64
+ GCC_except_table70
+ _OBJC_CLASS_$_UIFontMetrics
+ ___53-[TVMLViewFactory _labelViewForElement:existingView:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48s_e35_v40?0"UIFont"8{_NSRange=QQ}16^B32ls32l8s40l8s48l8
- GCC_except_table69
Functions:
~ -[TVMLViewFactory _labelViewForElement:existingView:] : 2668 -> 3100
+ ___53-[TVMLViewFactory _labelViewForElement:existingView:]_block_invoke
```
