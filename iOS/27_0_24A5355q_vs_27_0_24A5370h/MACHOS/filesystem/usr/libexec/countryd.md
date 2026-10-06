## countryd

> `/usr/libexec/countryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc120` | `0xbf54` | **`-0x1cc`** |
| `__TEXT.__eh_frame` | `0x490` | `0x3e0` | **`-0xb0`** |
| `__TEXT.__unwind_info` | `0x2e8` | `0x2c8` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x28` | `0x18` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 185
+  Functions: 181
```
