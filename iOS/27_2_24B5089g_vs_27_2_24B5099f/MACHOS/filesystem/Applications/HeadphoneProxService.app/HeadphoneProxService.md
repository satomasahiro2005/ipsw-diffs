## HeadphoneProxService

> `/Applications/HeadphoneProxService.app/HeadphoneProxService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x115a24` | `0x115a5c` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x21e0` | `0x2208` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x85f5` | `0x8605` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-41.4.0.0.0
+41.6.0.0.0
Functions:
~ sub_10003f7d4 : 1992 -> 2000
~ sub_100045690 -> sub_100045698 : 856 -> 860
~ sub_1000a65f4 -> sub_1000a6600 : 120 -> 124
~ sub_1000a666c -> sub_1000a667c : 112 -> 116
~ sub_10011626c -> sub_100116280 : 32 -> 68
CStrings:
+ "setActive:withOptions:error:"
- "setActive:error:"
```
