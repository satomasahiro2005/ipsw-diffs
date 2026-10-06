## csfdiagnose

> `/usr/bin/csfdiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x163b0` | `0x16400` | **`+0x50`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
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

-301.24.0.20.1
+301.24.0.22.0
Functions:
~ sub_1000053c0 : 4276 -> 4296
~ sub_1000087e8 -> sub_1000087fc : 1624 -> 1632
~ sub_10000aed8 -> sub_10000aef4 : 3568 -> 3580
~ sub_10000cf34 -> sub_10000cf5c : 1760 -> 1776
~ sub_10000dbdc -> sub_10000dc14 : 3524 -> 3536
~ sub_100010e2c -> sub_100010e70 : 240 -> 244
~ sub_10001162c -> sub_100011674 : 140 -> 148
```
