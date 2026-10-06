## tzd

> `/usr/libexec/tzd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15c58` | `0x15cc4` | **`+0x6c`** |
| `__TEXT.__unwind_info` | `0x460` | `0x458` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`

### Other Changes

```text
Functions:
~ sub_10000414c : 1688 -> 1692
~ sub_1000080f4 -> sub_1000080f8 : 3468 -> 3492
~ sub_1000097f4 -> sub_100009810 : 116 -> 132
~ sub_10000bb74 -> sub_10000bba0 : 380 -> 376
~ sub_10000ce94 -> sub_10000cebc : 4020 -> 4012
~ sub_10000dfe4 -> sub_10000e004 : 1872 -> 1884
~ sub_1000116f4 -> sub_100011720 : 536 -> 540
~ sub_100012f20 -> sub_100012f50 : 252 -> 276
~ sub_1000135e4 -> sub_10001362c : 236 -> 256
~ sub_1000136d0 -> sub_10001372c : 256 -> 264
~ sub_100016260 -> sub_1000162c4 : 344 -> 340
~ sub_10001682c -> sub_10001688c : 152 -> 164
```
