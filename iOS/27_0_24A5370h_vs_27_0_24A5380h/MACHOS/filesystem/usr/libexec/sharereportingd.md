## sharereportingd

> `/usr/libexec/sharereportingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4475c` | `0x446dc` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0x1490` | `0x1498` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-92.0.0.0.0
+94.0.0.0.0
Functions:
~ sub_100042028 : 116 -> 28
~ sub_1000421b4 -> sub_10004215c : 136 -> 116
~ sub_1000453c8 -> sub_10004535c : 356 -> 336
```
