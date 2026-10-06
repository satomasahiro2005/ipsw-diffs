## StatusKitAgent

> `/System/Library/PrivateFrameworks/StatusKit.framework/StatusKitAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x714` | `0x630` | **`-0xe4`** |
| `__TEXT.__objc_stubs` | `0x100` | `0xc0` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x89` | `0x6d` | **`-0x1c`** |
| `__TEXT.__objc_methname` | `0xa4` | `0x8c` | **`-0x18`** |
| `__DATA.__objc_selrefs` | `0x40` | `0x30` | **`-0x10`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-154.100.1.0.0
+154.200.11.0.0

-  Functions: 16
-  Symbols:   92
-  CStrings:  19
+  Functions: 14
+  Symbols:   88
+  CStrings:  16
Symbols:
+ _HandleSignal
+ _objc_alloc_init
- _OUTLINED_FUNCTION_1
- ___HandleSignal_block_invoke
- ____HandleSignal_block_invoke
- _dispatch_async
- _objc_msgSend$sharedInstance
- _objc_msgSend$shutdown
CStrings:
- "Quit - shutting down daemon"
- "sharedInstance"
- "shutdown"
```
