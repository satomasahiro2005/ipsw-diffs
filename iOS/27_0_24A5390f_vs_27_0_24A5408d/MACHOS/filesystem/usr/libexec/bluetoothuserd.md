## bluetoothuserd

> `/usr/libexec/bluetoothuserd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x23e1` | `0x23d1` | **`-0x10`** |
| `__TEXT.__text` | `0x6fe00` | `0x6fdf8` | **`-0x8`** |

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
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2700.46.1.1.0
+2700.51.1.1.0

-  CStrings:  1109
+  CStrings:  1108
Functions:
~ sub_100002a10 : 3300 -> 3320
~ sub_100003760 -> sub_100003774 : 68 -> 64
~ sub_10004eec8 -> sub_10004eed8 : 1008 -> 992
~ sub_10004f5c0 : 1444 -> 1436
CStrings:
- "MockA2DPActivity"
```
