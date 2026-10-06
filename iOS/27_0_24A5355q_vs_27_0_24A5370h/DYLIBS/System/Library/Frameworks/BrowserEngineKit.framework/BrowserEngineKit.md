## BrowserEngineKit

> `/System/Library/Frameworks/BrowserEngineKit.framework/BrowserEngineKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x212d8` | `0x21164` | **`-0x174`** |
| `__TEXT.__gcc_except_tab` | `0x2fc` | `0x2b0` | **`-0x4c`** |
| `__TEXT.__objc_methlist` | `0x1a08` | `0x19f0` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x11a0` | `0x1190` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xc08` | `0xbf8` | **`-0x10`** |

### Other Changes

```diff

-7625.1.18.3.0
+7625.1.20.0.0

-  Functions: 1030
-  Symbols:   1233
+  Functions: 1027
+  Symbols:   1228
Symbols:
+ GCC_except_table28
+ GCC_except_table29
+ ___77-[BEWebContentFilter evaluateURL:mainFrameURL:isMainFrame:completionHandler:]_block_invoke
+ ___77-[BEWebContentFilter evaluateURL:mainFrameURL:isMainFrame:completionHandler:]_block_invoke_2
- -[BEWebContentFilter evaluateURL:mainDocumentURL:completionHandler:]
- -[BEWebContentFilter requestPermissionForURL:referrerURL:completionHandler:]
- GCC_except_table26
- GCC_except_table30
- GCC_except_table31
- GCC_except_table32
- ___103-[BEWebContentFilter requestPermissionForURLOnMainThread:referrerURL:presentingView:completionHandler:]_block_invoke_3
- ___68-[BEWebContentFilter evaluateURL:mainDocumentURL:completionHandler:]_block_invoke
- ___68-[BEWebContentFilter evaluateURL:mainDocumentURL:completionHandler:]_block_invoke_2
```
