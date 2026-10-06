## TVAppServicesAccountNotificationPlugin

> `/System/Library/Accounts/Notification/TVAppServicesAccountNotificationPlugin.bundle/TVAppServicesAccountNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b08` | `0x1d44` | **`+0x23c`** |
| `__TEXT.__oslogstring` | `0x1ef` | `0x22f` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x300` | `0x320` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x80` | `0xa0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x188` | `0x198` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x2ae` | `0x2bd` | **`+0xf`** |
| `__DATA.__objc_selrefs` | `0x110` | `0x118` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-203.0.0.0.0
+206.0.0.0.0

-  CStrings:  74
+  CStrings:  76
Functions:
~ sub_1bac : 344 -> 340
~ sub_1d04 -> sub_1d00 : 152 -> 164
~ sub_23c8 -> sub_23d0 : 772 -> 1336
CStrings:
+ "AccountNotificationPlugin:: storefront changed - will notify"
+ "ams_storefront"
```
