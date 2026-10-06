## usbaudiod

> `/System/Library/Audio/Plug-Ins/usbaudio.bundle/usbaudiod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10187c` | `0x102f2c` | **`+0x16b0`** |
| `__TEXT.__eh_frame` | `0x5c30` | `0x5c50` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x35f8` | `0x35d8` | **`-0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-901.42.0.0.0
+901.44.0.0.0

-  Functions: 5075
+  Functions: 5077
Symbols:
+ _objc_release_x13
- _objc_release_x12
```
