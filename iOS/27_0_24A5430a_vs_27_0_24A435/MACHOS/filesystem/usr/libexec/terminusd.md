## terminusd

> `/usr/libexec/terminusd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x200eb8` | `0x200e74` | **`-0x44`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ sub_100011100 : 2876 -> 2880
~ sub_1000163bc -> sub_1000163c0 : 22264 -> 22260
~ sub_1000d2078 : 20596 -> 20672
~ sub_1000e67b8 -> sub_1000e6804 : 21132 -> 20976
~ sub_1001ef50c -> sub_1001ef4bc : 252 -> 260
~ sub_1001fbd2c -> sub_1001fbce4 : 648 -> 652
CStrings:
+ "22:06:48"
- "22:49:05"
```
