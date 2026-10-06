## mlir-ml-viewer-tool

> `/System/Library/PrivateFrameworks/MLIR_ML.framework/mlir-ml-viewer-tool`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x180` | `0x1c0` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x10d` | `0x146` | **`+0x39`** |
| `__TEXT.__text` | `0x1a58` | `0x1a88` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x60` | `0x70` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x200` | `0x210` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x110` | `0x118` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x70` | `0x78` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7.0.72.0.0
+7.0.75.1.0

-  Symbols:   112
-  CStrings:  41
+  Symbols:   116
+  CStrings:  43
Symbols:
+ _OBJC_CLASS_$_MLViewerGraphDescriptorSPI
+ _objc_alloc_init
+ _objc_msgSend$newGraphWithMLIR:descriptor:
+ _objc_msgSend$newGraphWithMLIRByteCode:descriptor:
+ _objc_msgSend$setAlwaysIncludeNodeLocations:
+ _objc_msgSend$setSignature:
- _objc_msgSend$newGraphWithMLIR:
- _objc_msgSend$newGraphWithMLIRByteCode:signature:
Functions:
~ _main : 2516 -> 2564
CStrings:
+ "newGraphWithMLIR:descriptor:"
+ "newGraphWithMLIRByteCode:descriptor:"
+ "setAlwaysIncludeNodeLocations:"
+ "setSignature:"
- "newGraphWithMLIR:"
- "newGraphWithMLIRByteCode:signature:"
```
