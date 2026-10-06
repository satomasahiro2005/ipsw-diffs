## DeviceEnrollmentDataClassPlugIn

> `/System/Library/Accounts/DataclassOwners/DeviceEnrollmentDataClassPlugIn.bundle/DeviceEnrollmentDataClassPlugIn`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59e8` | `0x5a0c` | **`+0x24`** |
| `__TEXT.__auth_stubs` | `0x620` | `0x630` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x318` | `0x320` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-40.0.0.0.0
+40.0.1.0.0

-  Symbols:   78
+  Symbols:   79
Symbols:
+ _objc_release_x26
Functions:
~ sub_2e98 : 620 -> 628
~ sub_39b0 -> sub_39b8 : 280 -> 276
~ sub_3fec -> sub_3ff0 : 3212 -> 3232
~ sub_6594 -> sub_65ac : 200 -> 204
~ sub_6738 -> sub_6754 : 200 -> 204
~ sub_69b4 -> sub_69d4 : 200 -> 204
```
