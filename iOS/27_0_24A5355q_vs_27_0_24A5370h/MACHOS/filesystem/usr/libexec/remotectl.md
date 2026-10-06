## remotectl

> `/usr/libexec/remotectl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x838` | `0x850` | **`+0x18`** |
| `__TEXT.__text` | `0x1a5c4` | `0x1a5dc` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4d0` | `0x4c8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-243.0.0.0.0
+245.0.1.502.2
Functions:
~ sub_100003500 : 1112 -> 1108
~ sub_100005fe0 -> sub_100005fdc : 544 -> 540
~ sub_1000095c4 -> sub_1000095bc : 280 -> 276
~ sub_100009c54 -> sub_100009c48 : 236 -> 256
~ sub_1000114f8 -> sub_100011500 : 716 -> 740
~ sub_10001198c -> sub_1000119ac : 1400 -> 1424
~ sub_1000120d8 -> sub_100012110 : 524 -> 508
~ sub_100018e64 -> sub_100018e8c : 540 -> 520
~ sub_10001a78c -> sub_10001a7a0 : 256 -> 264
~ sub_10001a9d8 -> sub_10001a9f4 : 72 -> 68
```
