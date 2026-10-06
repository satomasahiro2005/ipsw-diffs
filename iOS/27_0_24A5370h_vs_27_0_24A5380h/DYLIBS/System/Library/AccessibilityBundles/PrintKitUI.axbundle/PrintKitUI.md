## PrintKitUI

> `/System/Library/AccessibilityBundles/PrintKitUI.axbundle/PrintKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x834` | `0xa20` | **`+0x1ec`** |
| `__AUTH_CONST.__cfstring` | `0x380` | `0x400` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2fc` | `0x347` | **`+0x4b`** |
| `__DATA_CONST.__const` | `0x60` | `0x88` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x100` | `0x118` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xb0` | `0xc8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__const` | `0x8` | `0x18` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x38` | `0x40` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 31
-  Symbols:   125
-  CStrings:  36
+  Functions: 34
+  Symbols:   136
+  CStrings:  41
Symbols:
+ GCC_except_table11
+ _AXPerformSafeBlock
+ _AXSafeClassFromString
+ __Block_object_dispose
+ __NSConcreteStackBlock
+ __Unwind_Resume
+ ___58-[UIPrinterTableViewCellAccessibility accessibilityTraits]_block_invoke
+ ___Block_byref_object_copy_
+ ___Block_byref_object_dispose_
+ ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
+ ___objc_personality_v0
CStrings:
+ "UIListContentConfiguration"
+ "UITableViewCell"
+ "checkmarkImage"
+ "contentConfiguration"
+ "image"
+ "v8@?0"
- "printerSelected"
```
