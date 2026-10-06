## PlugInKitDaemon

> `/System/Library/PrivateFrameworks/PlugInKitDaemon.framework/PlugInKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x177ec` | `0x17848` | **`+0x5c`** |
| `__TEXT.__objc_stubs` | `0x3180` | `0x31a0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x3062` | `0x307e` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0xfe8` | `0xff8` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xe28` | `0xe30` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-511.0.0.0.0
+512.0.0.0.0

-  Functions: 436
-  Symbols:   1366
-  CStrings:  1104
+  Functions: 437
+  Symbols:   1368
+  CStrings:  1105
Symbols:
+ -[PKDTransaction _getInstanceUUIDFromRequest]
+ GCC_except_table15
+ GCC_except_table18
+ GCC_except_table34
+ GCC_except_table36
+ _objc_msgSend$_getInstanceUUIDFromRequest
- GCC_except_table14
- GCC_except_table17
- GCC_except_table33
- GCC_except_table35
Functions:
~ -[PKDTransaction initWithRequest:forClient:] : 568 -> 256
~ -[PKDTransaction dispatch] : 668 -> 812
+ -[PKDTransaction marshalPaths:]
CStrings:
+ "_getInstanceUUIDFromRequest"
```
