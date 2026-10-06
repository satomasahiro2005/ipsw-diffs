## PrintKitUI

> `/System/Library/PrivateFrameworks/PrintKitUI.framework/PrintKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6560c` | `0x6590c` | **`+0x300`** |
| `__TEXT.__gcc_except_tab` | `0x1c9c` | `0x1ba8` | **`-0xf4`** |
| `__AUTH_CONST.__objc_const` | `0xa720` | `0xa750` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x3b60` | `0x3b80` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4970` | `0x4988` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x716c` | `0x7184` | **`+0x18`** |
| `__TEXT.__cstring` | `0x2a85` | `0x2a97` | **`+0x12`** |
| `__DATA.__objc_ivar` | `0x7cc` | `0x7d0` | **`+0x4`** |

### Other Changes

```diff

-94.0.0.0.0
+97.0.0.0.0

-  Functions: 2299
-  Symbols:   4280
-  CStrings:  559
+  Functions: 2303
+  Symbols:   4285
+  CStrings:  560
Symbols:
+ -[UIPrintPreviewViewController dealloc]
+ -[UIPrintPreviewViewController printPanelDismissed]
+ -[UIPrintPreviewViewController setPrintPanelDismissed:]
+ GCC_except_table77
+ _OBJC_IVAR_$_UIPrintPreviewViewController._printPanelDismissed
+ ___41-[UIPrintPanelViewController setPrinter:]_block_invoke_3
+ ___41-[UIPrintPanelViewController setPrinter:]_block_invoke_4
- -[UIPrintPreviewViewController printPanelDidDismiss]
- GCC_except_table120
CStrings:
+ "effectiveGeometry"
```
