## SafetyMonitorApp

> `/Applications/SafetyMonitorApp.app/SafetyMonitorApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xce40` | `0xce60` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2e0` | `0x2d8` | **`-0x8`** |

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
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1109.0.3.0.0
+1114.0.0.0.0
Functions:
~ sub_100001e38 : 172 -> 176
~ sub_100001f0c -> sub_100001f10 : 124 -> 128
~ sub_10000468c -> sub_100004694 : 4628 -> 4640
~ sub_10000625c -> sub_100006270 : 3004 -> 3008
~ sub_100008790 -> sub_1000087a8 : 344 -> 340
~ sub_100008a10 -> sub_100008a24 : 152 -> 164
~ sub_10000b250 -> sub_10000b270 : 424 -> 420
~ sub_10000b3f8 -> sub_10000b414 : 680 -> 672
~ sub_10000b6a0 -> sub_10000b6b4 : 256 -> 276
~ sub_10000baf8 -> sub_10000bb20 : 772 -> 768
~ sub_10000d134 -> sub_10000d158 : 280 -> 276
```
