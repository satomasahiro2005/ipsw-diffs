## searchdiagnose

> `/usr/bin/searchdiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__eh_frame` | `0x1874` | `0x18a4` | **`+0x30`** |
| `__TEXT.__text` | `0x28c8c` | `0x28c5c` | **`-0x30`** |
| `__TEXT.__auth_stubs` | `0x1590` | `0x1580` | **`-0x10`** |
| `__TEXT.__const` | `0x1888` | `0x1898` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xad0` | `0xac8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x9c8` | `0x9d0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2448.100.0.0.0
+2451.1.101.0.0

-  Functions: 673
-  Symbols:   592
+  Functions: 674
+  Symbols:   591
Symbols:
- _swift_release_x28
```
