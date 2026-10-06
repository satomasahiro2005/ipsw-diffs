## findmybeaconingd

> `/usr/libexec/findmybeaconingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1801c` | `0x18048` | **`+0x2c`** |
| `__TEXT.__auth_stubs` | `0x1290` | `0x1280` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x950` | `0x948` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x850` | `0x858` | **`+0x8`** |

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
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Symbols:   513
+  Symbols:   512
Symbols:
- _swift_release_x25
Functions:
~ sub_1000078b4 : 280 -> 276
~ sub_100007dec -> sub_100007de8 : 472 -> 476
~ sub_100008818 : 1764 -> 1760
~ sub_100008efc -> sub_100008ef8 : 984 -> 1016
~ sub_10000cfe8 -> sub_10000d004 : 1536 -> 1532
~ sub_10000ecec -> sub_10000ed04 : 256 -> 276
```
