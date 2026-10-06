## ControlCenterUI

> `/System/Library/PrivateFrameworks/ControlCenterUI.framework/ControlCenterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbb00c` | `0xbb298` | **`+0x28c`** |
| `__AUTH_CONST.__objc_const` | `0x11108` | `0x11190` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x68e8` | `0x6928` | **`+0x40`** |
| `__DATA_DIRTY.__objc_data` | `0x3a40` | `0x3a68` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x2a5c` | `0x2a7c` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1de2` | `0x1e02` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2d70` | `0x2d58` | **`-0x18`** |
| `__DATA.__data` | `0x3a70` | `0x3a80` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xb4f0` | `0xb500` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1380` | `0x138c` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x738` | `0x740` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xd28` | `0xd30` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-702.0.0.0.0
+704.0.1.0.0

-  Symbols:   5616
+  Symbols:   5619
Symbols:
+ -[CCUIBluetoothModuleViewController _menuContentForActions:]
+ -[CCUIMainViewController overlayCompactStatusBar]
+ -[CCUIOverlayStatusBarPresentationProvider _addCompactStatusBarAlphaAnimationToBatch:transitionState:]
+ -[CCUIOverlayStatusBarPresentationProvider _compactStatusBarAlphaForTransitionState:]
+ GCC_except_table53
+ _OBJC_IVAR_$_CCUIBluetoothModuleViewController._lastPushedContextMenuContent
+ _OBJC_IVAR_$_CCUIMainViewController._appNameMenuBarProvider
+ _OBJC_IVAR_$_CCUIMainViewController._compactStatusBar
+ __UIStatusBarPartIdentifierCenter
+ ___102-[CCUIOverlayStatusBarPresentationProvider _addCompactStatusBarAlphaAnimationToBatch:transitionState:]_block_invoke
- -[CCUIMainViewController overlayLeadingStatusBar]
- -[CCUIOverlayStatusBarPresentationProvider _addLeadingStatusBarAlphaAnimationToBatch:transitionState:]
- -[CCUIOverlayStatusBarPresentationProvider _leadingStatusBarAlphaForTransitionState:]
- GCC_except_table50
- GCC_except_table52
- _OBJC_IVAR_$_CCUIMainViewController._compactLeadingStatusBar
- ___102-[CCUIOverlayStatusBarPresentationProvider _addLeadingStatusBarAlphaAnimationToBatch:transitionState:]_block_invoke
CStrings:
+ "\xf0\x92!b"
- "\xf0\x82!b"
```
