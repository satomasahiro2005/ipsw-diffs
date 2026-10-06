## WebCore

> `/System/Library/AccessibilityBundles/WebCore.axbundle/WebCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10fdc` | `0x111b8` | **`+0x1dc`** |
| `__DATA_CONST.__const` | `0x398` | `0x3c0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x3840` | `0x3860` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x400` | `0x418` | **`+0x18`** |
| `__TEXT.__cstring` | `0x2399` | `0x23ad` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x10a8` | `0x10b8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1080` | `0x1090` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4f0` | `0x500` | **`+0x10`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 348
-  Symbols:   782
-  CStrings:  486
+  Functions: 350
+  Symbols:   786
+  CStrings:  487
Symbols:
+ -[UIKitWebAccessibilityObjectWrapper _accessibilityLineForIndex:]
+ GCC_except_table229
+ GCC_except_table246
+ GCC_except_table250
+ GCC_except_table268
+ GCC_except_table279
+ ___65-[UIKitWebAccessibilityObjectWrapper _accessibilityLineForIndex:]_block_invoke
+ ___block_descriptor_56_e8_32s40r_e5_v8?0lr40l8s32l8
- GCC_except_table244
- GCC_except_table248
- GCC_except_table266
- GCC_except_table275
CStrings:
+ "lineNumberForIndex:"
```
