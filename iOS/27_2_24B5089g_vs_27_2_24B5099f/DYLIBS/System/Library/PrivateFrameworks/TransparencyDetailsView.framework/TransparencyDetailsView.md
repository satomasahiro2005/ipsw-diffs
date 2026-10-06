## TransparencyDetailsView

> `/System/Library/PrivateFrameworks/TransparencyDetailsView.framework/TransparencyDetailsView`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x86fc` | `0x8a3c` | **`+0x340`** |
| `__DATA_CONST.__objc_selrefs` | `0x990` | `0x9b8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x8b8` | `0x8d8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1b0` | `0x1c0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x1d8` | **`+0x8`** |

### Other Changes

```diff

-638.2.2.0.0
+638.2.3.0.0

-  Functions: 161
-  Symbols:   387
+  Functions: 164
+  Symbols:   391
Symbols:
+ -[ADTransparencyViewController viewWillAppear:]
+ -[NewsTransparencyViewController viewWillAppear:]
+ -[UserTransparencyViewController viewWillAppear:]
+ GCC_except_table19
+ GCC_except_table4
+ _OBJC_CLASS_$_UISheetPresentationControllerDetent
- GCC_except_table18
- GCC_except_table3
Functions:
+ -[UserTransparencyViewController viewWillAppear:]
~ -[UserTransparencyViewController immediatelyLoadViewControllerBeforeNetworkRequest] : 2664 -> 2648
~ -[NewsTransparencyViewController loadWebView] : 1620 -> 1600
+ -[NewsTransparencyViewController viewWillAppear:]
+ -[ADTransparencyViewController viewWillAppear:]
~ -[ADTransparencyViewController configureWebView] : 1524 -> 1504
```
