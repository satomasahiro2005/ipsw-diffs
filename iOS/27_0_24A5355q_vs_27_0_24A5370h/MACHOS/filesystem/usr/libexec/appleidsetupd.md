## appleidsetupd

> `/usr/libexec/appleidsetupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7670` | `0x7688` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__objc_const`
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

-120.0.0.0.0
+122.0.0.0.0
Functions:
~ sub_100001d70 : 1348 -> 1352
~ sub_1000022b4 -> sub_1000022b8 : 1348 -> 1352
~ sub_10000360c -> sub_100003614 : 140 -> 148
~ sub_1000039e0 -> sub_1000039f0 : 176 -> 180
~ sub_100004050 -> sub_100004064 : 1444 -> 1448
~ sub_100006ca8 -> sub_100006cc0 : 280 -> 276
~ sub_1000071a0 -> sub_1000071b4 : 692 -> 688
~ sub_100008be8 -> sub_100008bf8 : 132 -> 140
```
