## PrintKitUI

> `/System/Library/PrivateFrameworks/PrintKitUI.framework/PrintKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x64aa8` | `0x64dc8` | **`+0x320`** |
| `__AUTH.__objc_data` | `0x15e0` | `0x1590` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x320` | `0x370` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x70a4` | `0x70d4` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2a95` | `0x2abb` | **`+0x26`** |
| `__AUTH_CONST.__cfstring` | `0x3b80` | `0x3ba0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4948` | `0x4960` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1718` | `0x1728` | **`+0x10`** |

### Other Changes

```diff

-97.2.0.0.0
+97.4.0.0.0

-  Functions: 2285
-  Symbols:   4253
-  CStrings:  560
+  Functions: 2289
+  Symbols:   4256
+  CStrings:  561
Symbols:
+ -[UIFinishingOptionsSection previewDidChangeSize:]
+ -[UIPrintOptionListViewController dealloc]
+ -[UIPrintOptionListViewController previewStateChanged:]
+ -[UIPrintPanelViewController viewDidLayoutSubviews]
+ GCC_except_table43
+ GCC_except_table46
+ GCC_except_table66
- GCC_except_table25
- GCC_except_table41
- GCC_except_table45
- GCC_except_table65
CStrings:
+ "UIPrintPreviewStateChangeNotification"
```
