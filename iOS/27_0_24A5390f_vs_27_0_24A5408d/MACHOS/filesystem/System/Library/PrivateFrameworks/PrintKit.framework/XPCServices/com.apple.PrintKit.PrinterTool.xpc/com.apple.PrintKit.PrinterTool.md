## com.apple.PrintKit.PrinterTool

> `/System/Library/PrivateFrameworks/PrintKit.framework/XPCServices/com.apple.PrintKit.PrinterTool.xpc/com.apple.PrintKit.PrinterTool`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5bf9c` | `0x5c038` | **`+0x9c`** |
| `__TEXT.__auth_stubs` | `0x1860` | `0x1880` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x6820` | `0x6800` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0xc48` | `0xc58` | **`+0x10`** |
| `__DATA_CONST.__const` | `0xed58` | `0xed60` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xaa08` | `0xaa10` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2e40` | `0x2e48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-326.0.0.0.0
+327.0.0.0.0

-  Functions: 1628
-  Symbols:   939
+  Functions: 1629
+  Symbols:   941
Symbols:
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
```
