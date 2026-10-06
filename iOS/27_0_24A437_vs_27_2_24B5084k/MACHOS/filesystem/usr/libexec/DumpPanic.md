## DumpPanic

> `/usr/libexec/DumpPanic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b410` | `0x2b49c` | **`+0x8c`** |
| `__DATA_CONST.__const` | `0x778` | `0x780` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x8f0` | `0x8e8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-37.0.1.0.0
+41.40.5.0.0

-  Functions: 871
+  Functions: 870
```
