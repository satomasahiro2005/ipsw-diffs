## meminfo

> `/usr/bin/meminfo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x137b4` | `0x138a8` | **`+0xf4`** |
| `__TEXT.__unwind_info` | `0x3b8` | `0x3c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1071.0.1.0.0
+1071.40.6.0.0
Functions:
~ sub_1000016cc : 3160 -> 3376
~ sub_100010330 -> sub_100010408 : 1000 -> 1016
~ sub_100011078 -> sub_100011160 : 1272 -> 1284
CStrings:
+ " requires root to expand zones; showing aggregate zone total\n"
- "meminfo: --zones requires root; showing aggregate zone total\n"
```
