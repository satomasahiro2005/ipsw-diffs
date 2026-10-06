## SatelliteSMS

> `/System/Library/Messages/PlugIns/SatelliteSMS.imservice/SatelliteSMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xde6c` | `0xde8c` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x308` | `0x300` | **`-0x8`** |

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
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4
Functions:
~ sub_70ac : 272 -> 288
~ sub_71bc -> sub_71cc : 5156 -> 5148
~ sub_89c0 -> sub_89c8 : 172 -> 176
~ sub_8ff0 -> sub_8ffc : 280 -> 276
~ sub_9eac -> sub_9eb4 : 256 -> 276
~ sub_9fac -> sub_9fc8 : 256 -> 264
~ sub_a9ec -> sub_aa10 : 5212 -> 5200
~ sub_e74c -> sub_e764 : 400 -> 408
```
