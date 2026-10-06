## hybridsearchd

> `/usr/libexec/hybridsearchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x740` | `0x750` | **`+0x10`** |
| `__TEXT.__text` | `0x385c` | `0x3868` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x3a8` | `0x3b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-53.0.0.0.0
+57.0.1.0.0
Functions:
~ sub_1000034e4 : 116 -> 124
~ sub_100003ad0 -> sub_100003ad8 : 268 -> 264
~ sub_100004370 -> sub_100004374 : 116 -> 124
```
