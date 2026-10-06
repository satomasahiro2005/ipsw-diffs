## AccessibilitySettingsLoader

> `/System/Library/AccessibilityBundles/AccessibilitySettingsLoader.bundle/AccessibilitySettingsLoader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x125a0` | `0x12b24` | **`+0x584`** |
| `__DATA.__bss` | `0x290` | `0x2e8` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x23c0` | `0x2410` | **`+0x50`** |
| `__DATA_DIRTY.__bss` | `0x170` | `0x128` | **`-0x48`** |
| `__TEXT.__objc_methlist` | `0x11bc` | `0x11fc` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xd90` | `0xdc0` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x574` | `0x598` | **`+0x24`** |
| `__TEXT.__unwind_info` | `0x750` | `0x770` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x2c` | `0x30` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

-  Functions: 413
-  Symbols:   1042
+  Functions: 419
+  Symbols:   1048
Symbols:
+ -[AccessibilityFloatingUIKeyboardHelper _mirrorToAssistiveTouchVisible:frame:]
+ -[AccessibilityFloatingUIKeyboardHelper astMessagingCenter]
+ -[AccessibilityFloatingUIKeyboardHelper setAstMessagingCenter:]
+ GCC_except_table323
+ GCC_except_table329
+ GCC_except_table336
+ GCC_except_table352
+ GCC_except_table357
+ GCC_except_table362
+ GCC_except_table373
+ GCC_except_table375
+ GCC_except_table383
+ GCC_except_table413
+ _OBJC_IVAR_$_AccessibilityFloatingUIKeyboardHelper._astMessagingCenter
+ ___78-[AccessibilityFloatingUIKeyboardHelper _mirrorToAssistiveTouchVisible:frame:]_block_invoke
- GCC_except_table322
- GCC_except_table328
- GCC_except_table338
- GCC_except_table350
- GCC_except_table351
- GCC_except_table367
- GCC_except_table369
- GCC_except_table377
- GCC_except_table407
```
