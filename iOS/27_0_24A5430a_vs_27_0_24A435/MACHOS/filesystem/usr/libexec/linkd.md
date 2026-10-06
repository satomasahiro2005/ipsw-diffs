## linkd

> `/usr/libexec/linkd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b95fc` | `0x1b96d4` | **`+0xd8`** |
| `__TEXT.__eh_frame` | `0x1565c` | `0x1569c` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x7800` | `0x7838` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x3c50` | `0x3c40` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1e30` | `0x1e28` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 11269
-  Symbols:   1776
+  Functions: 11308
+  Symbols:   1775
Symbols:
- _objc_retain_x10
```
