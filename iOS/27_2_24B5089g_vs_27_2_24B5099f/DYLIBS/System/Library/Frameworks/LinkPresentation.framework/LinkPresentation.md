## LinkPresentation

> `/System/Library/Frameworks/LinkPresentation.framework/LinkPresentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b480` | `0x10bd1c` | **`+0x89c`** |
| `__TEXT.__gcc_except_tab` | `0x23290` | `0x23308` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x110bc` | `0x11104` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x83b0` | `0x83f8` | **`+0x48`** |
| `__DATA.__bss` | `0x1b10` | `0x1b40` | **`+0x30`** |
| `__DATA.__data` | `0x1c18` | `0x1c48` | **`+0x30`** |
| `__DATA_DIRTY.__bss` | `0x100` | `0xd0` | **`-0x30`** |
| `__AUTH.__objc_data` | `0x3698` | `0x3670` | **`-0x28`** |
| `__DATA_DIRTY.__objc_data` | `0x22b0` | `0x22d8` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x2dc80` | `0x2dca0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1058` | `0x1070` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x7ac0` | `0x7ad8` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__const` | `0x2324` | `0x2334` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xa94` | `0xa9e` | **`+0xa`** |
| `__DATA.__objc_ivar` | `0x17f0` | `0x17f4` | **`+0x4`** |

### Other Changes

```diff

-314.0.0.0.0
+316.0.0.0.0

-  Functions: 6843
-  Symbols:   11686
+  Functions: 6852
+  Symbols:   11697
Symbols:
+ -[LPCollaborationFooterView _setPressed:]
+ -[LPCollaborationFooterView _updateBackgroundColor]
+ -[LPCollaborationFooterView touchesBegan:withEvent:]
+ -[LPCollaborationFooterView touchesCancelled:withEvent:]
+ -[LPCollaborationFooterView touchesEnded:withEvent:]
+ -[LPCollaborationFooterView touchesMoved:withEvent:]
+ _CGRectContainsPoint
+ _CVPixelBufferGetHeight
+ _CVPixelBufferGetWidth
+ _OBJC_IVAR_$_LPCollaborationFooterView._pressed
+ _symbolic _____ySbG s23_ContiguousArrayStorageC
```
