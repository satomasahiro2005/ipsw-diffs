## WebSheet

> `/System/Library/PrivateFrameworks/WebSheet.framework/WebSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e28` | `0x7ed8` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x2a8` | `0x2d0` | **`+0x28`** |
| `__TEXT.__cstring` | `0x1565` | `0x1586` | **`+0x21`** |
| `__AUTH_CONST.__cfstring` | `0xb20` | `0xb00` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0xc70` | `0xc90` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x268` | `0x250` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x290` | `0x2a0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xe50` | `0xe48` | **`-0x8`** |

### Other Changes

```diff

-332.0.0.0.0
+334.0.0.0.0

-  Functions: 190
-  Symbols:   531
+  Functions: 194
+  Symbols:   533
Symbols:
+ -[WSWebSheetView shouldHideStatusBar]
+ -[WSWebSheetViewController prefersStatusBarHidden]
+ -[WSWebSheetViewController viewWillTransitionToSize:withTransitionCoordinator:]
+ GCC_except_table119
+ ___79-[WSWebSheetViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
+ ___block_descriptor_40_e8_32s_e56_v16?0"<UIViewControllerTransitionCoordinatorContext>"8ls32l8
- GCC_except_table118
- _OBJC_CLASS_$_WKProcessPool
- _OBJC_CLASS_$__SFWebView
- _OBJC_CLASS_$__WKProcessPoolConfiguration
CStrings:
+ "v16@?0@\"<UIViewControllerTransitionCoordinatorContext>\"8"
- "SafariServices.wkbundle"
```
