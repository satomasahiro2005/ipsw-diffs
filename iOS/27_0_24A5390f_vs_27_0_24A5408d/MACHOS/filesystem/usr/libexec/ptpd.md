## ptpd

> `/usr/libexec/ptpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22818` | `0x22918` | **`+0x100`** |
| `__TEXT.__objc_stubs` | `0x41a0` | `0x41c0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xa00` | `0xa10` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x4f63` | `0x4f70` | **`+0xd`** |
| `__DATA.__objc_selrefs` | `0x1628` | `0x1630` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x510` | `0x518` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x220` | `0x228` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2116.0.0.0.0
+2118.0.0.0.0

-  Functions: 615
-  Symbols:   238
-  CStrings:  1588
+  Functions: 616
+  Symbols:   240
+  CStrings:  1589
Symbols:
+ _OBJC_CLASS_$_NSThread
+ _objc_retainBlock
CStrings:
+ "isMainThread"
```
