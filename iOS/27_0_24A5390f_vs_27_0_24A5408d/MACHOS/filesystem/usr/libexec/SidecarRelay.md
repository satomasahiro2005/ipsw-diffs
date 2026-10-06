## SidecarRelay

> `/usr/libexec/SidecarRelay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87b0c` | `0x87ac8` | **`-0x44`** |

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
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-400.40.0.0.0
+400.42.0.0.0
Functions:
~ sub_10005ad38 : 1452 -> 1436
~ sub_10005d320 -> sub_10005d310 : 432 -> 416
~ sub_100074fa8 -> sub_100074f88 : 820 -> 800
~ sub_10007540c -> sub_1000753d8 : 1440 -> 1424
CStrings:
+ "400.42"
- "400.40"
```
