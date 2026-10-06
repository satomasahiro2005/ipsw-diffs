## MobileCal

> `/System/Library/AccessibilityBundles/MobileCal.axbundle/MobileCal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc6fc` | `0xc8a8` | **`+0x1ac`** |
| `__AUTH_CONST.__cfstring` | `0x2c40` | `0x2cc0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2cc3` | `0x2d0c` | **`+0x49`** |
| `__AUTH_CONST.__const` | `0x1e0` | `0x200` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xb00` | `0xb20` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1600` | `0x1618` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1a8` | `0x1b4` | **`+0xc`** |

### Other Changes

```diff

-3050.3.1.0.0
+3050.3.5.0.0

-  Functions: 382
-  Symbols:   1104
-  CStrings:  406
+  Functions: 385
+  Symbols:   1107
+  CStrings:  410
Symbols:
+ -[RootNavigationControllerAccessibility _axAnnotateTodayButton:]
+ -[RootNavigationControllerAccessibility largeTodayBarButtonItem]
+ GCC_except_table256
+ GCC_except_table263
+ GCC_except_table337
+ GCC_except_table346
+ GCC_except_table356
+ ___64-[RootNavigationControllerAccessibility _axAnnotateTodayButton:]_block_invoke
- GCC_except_table253
- GCC_except_table260
- GCC_except_table334
- GCC_except_table343
- GCC_except_table353
CStrings:
+ "EEEE, MMMM d"
+ "_largeTodayBarButtonItem"
+ "customView"
+ "largeTodayBarButtonItem"
```
