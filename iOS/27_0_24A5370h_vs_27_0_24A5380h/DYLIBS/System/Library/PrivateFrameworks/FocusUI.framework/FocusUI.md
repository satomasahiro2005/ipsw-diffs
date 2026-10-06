## FocusUI

> `/System/Library/PrivateFrameworks/FocusUI.framework/FocusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methlist` | `0x305c` | `0x2fbc` | **`-0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c38` | `0x1bc0` | **`-0x78`** |
| `__AUTH_CONST.__objc_const` | `0x9f28` | `0x9ec8` | **`-0x60`** |
| `__DATA.__data` | `0xef0` | `0xe90` | **`-0x60`** |
| `__TEXT.__text` | `0x23e00` | `0x23db8` | **`-0x48`** |
| `__DATA.__bss` | `0xa0` | `0x90` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x18` | `0x28` | **`+0x10`** |
| `__TEXT.__const` | `0x328` | `0x318` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x5d0` | `0x5c8` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x148` | `0x140` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x2f4` | `0x2f8` | **`+0x4`** |

### Other Changes

```diff

-502.0.100.0.0
+506.0.0.0.0

-  Functions: 993
-  Symbols:   2033
+  Functions: 994
+  Symbols:   2030
Symbols:
+ -[FCUIActivityListView contentHorizontalMargin]
+ -[FCUIActivityListView setContentHorizontalMargin:]
+ GCC_except_table17
+ _OBJC_IVAR_$_FCUIActivityListView._contentHorizontalMargin
- -[FCUIFocusSelectionViewController scrollViewDidScroll:]
- _UIRectRoundToScale
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UIScrollViewDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_UIScrollViewDelegate
- __OBJC_$_PROTOCOL_REFS_UIScrollViewDelegate
- __OBJC_LABEL_PROTOCOL_$_UIScrollViewDelegate
- __OBJC_PROTOCOL_$_UIScrollViewDelegate
Functions:
~ -[FCUIFocusSelectionViewController viewDidLoad] : 536 -> 420
- -[FCUIFocusSelectionViewController scrollViewDidScroll:]
+ -[FCUIActivityListView setContentHorizontalMargin:]
~ -[FCUIActivityListView _recalculateContentSize] : 380 -> 540
+ -[FCUIActivityListView contentHorizontalMargin]
```
