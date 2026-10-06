## WebCore

> `/System/Library/AccessibilityBundles/WebCore.axbundle/WebCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1111c` | `0x11198` | **`+0x7c`** |
| `__TEXT.__objc_methlist` | `0x1090` | `0x10a8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x3e4` | `0x3d0` | **`-0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x10b8` | `0x10c8` | **`+0x10`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  Functions: 349
-  Symbols:   783
+  Functions: 351
+  Symbols:   785
Symbols:
+ -[UIKitWebAccessibilityObjectWrapper _accessibilityIncludeRoleDescription]
+ -[UIKitWebAccessibilityObjectWrapper _axWebKitRoleDescription]
+ GCC_except_table269
+ GCC_except_table280
+ ___62-[UIKitWebAccessibilityObjectWrapper _axWebKitRoleDescription]_block_invoke
- GCC_except_table267
- GCC_except_table276
- ___67-[UIKitWebAccessibilityObjectWrapper _accessibilityRoleDescription]_block_invoke
```
