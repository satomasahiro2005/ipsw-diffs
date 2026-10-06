## fm

> `/usr/bin/fm`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc0d6c` | `0xc0dc0` | **`+0x54`** |
| `__TEXT.__unwind_info` | `0x1a30` | `0x1a28` | **`-0x8`** |

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

```text
Functions:
~ sub_10000cc14 : 5856 -> 5868
~ sub_10002e438 -> sub_10002e444 : 348 -> 356
~ sub_100031bdc -> sub_100031bf0 : 312 -> 324
~ sub_100034854 -> sub_100034874 : 1444 -> 1456
~ sub_10003fd4c -> sub_10003fd78 : 968 -> 972
~ sub_100047d6c -> sub_100047d9c : 648 -> 652
~ sub_100047ff4 -> sub_100048028 : 352 -> 356
~ sub_10006eba0 -> sub_10006ebd8 : 900 -> 888
~ sub_100071288 -> sub_1000712b4 : 3576 -> 3580
~ sub_100073a78 -> sub_100073aa8 : 5488 -> 5492
~ sub_1000823a0 -> sub_1000823d4 : 928 -> 936
~ sub_100092390 -> sub_1000923cc : 1300 -> 1296
~ sub_1000a7ef8 -> sub_1000a7f30 : 3232 -> 3260
```
