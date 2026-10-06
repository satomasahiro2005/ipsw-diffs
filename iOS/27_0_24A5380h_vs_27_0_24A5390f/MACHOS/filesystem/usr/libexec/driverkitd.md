## driverkitd

> `/usr/libexec/driverkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe9650` | `0xe96bc` | **`+0x6c`** |
| `__TEXT.__cstring` | `0x8d04` | `0x8ce4` | **`-0x20`** |

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
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-511.0.0.0.0
+514.0.0.0.0

-  CStrings:  1206
+  CStrings:  1205
Functions:
~ sub_10006f0a0 : 3204 -> 3212
~ sub_10006fed0 -> sub_10006fed8 : 344 -> 408
~ sub_100072f14 -> sub_100072f5c : 2984 -> 3020
CStrings:
+ "%{public}s is marked as LPN agent but is not a platform dext"
+ "KernelManagement_executables-514"
- "%{public}s is marked as LPN agent but is not a first-party dext"
- "EnableNetworkCapability"
- "KernelManagement_executables-511"
```
