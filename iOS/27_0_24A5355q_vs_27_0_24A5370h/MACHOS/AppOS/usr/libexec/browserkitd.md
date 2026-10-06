## browserkitd

> `/usr/libexec/browserkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xff4c` | `0xffa4` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0x998` | `0x990` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.18.10.4
+7625.1.20.10.3
Functions:
~ sub_1000021a4 : 172 -> 176
~ sub_100003990 -> sub_100003994 : 116 -> 132
~ sub_100006774 -> sub_100006788 : 1264 -> 1276
~ sub_100009068 -> sub_100009088 : 476 -> 480
~ sub_10000cf80 -> sub_10000cfa4 : 340 -> 332
~ sub_10000d314 -> sub_10000d330 : 108 -> 112
~ sub_10000d5b0 -> sub_10000d5d0 : 124 -> 132
~ sub_10000d808 -> sub_10000d830 : 344 -> 356
~ sub_100010fc4 -> sub_100010ff8 : 772 -> 760
~ sub_1000112c8 -> sub_1000112f0 : 256 -> 276
~ sub_1000113e4 -> sub_100011420 : 256 -> 264
~ sub_1000114e4 -> sub_100011528 : 236 -> 256
```
