## securityuploadd

> `/usr/libexec/securityuploadd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13214` | `0x13224` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1080` | `0x1088` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ sub_100002a60 : 1172 -> 1188
CStrings:
+ "DevicePercentageCustomer"
+ "SecondsBetweenUploadsCustomer"
- "DevicePercentageSeed"
- "SecondsBetweenUploadsSeed"
```
