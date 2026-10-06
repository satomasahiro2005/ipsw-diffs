## ptpd

> `/usr/libexec/ptpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22918` | `0x22874` | **`-0xa4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2118.0.0.0.0
+2118.1.0.0.0

-  Functions: 616
+  Functions: 615
Functions:
~ sub_100017bf8 : 300 -> 236
- sub_100017d24
```
