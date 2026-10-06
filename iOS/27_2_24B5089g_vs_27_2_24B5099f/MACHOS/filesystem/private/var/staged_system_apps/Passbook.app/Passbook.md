## Passbook

> `/private/var/staged_system_apps/Passbook.app/Passbook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xffb8` | `0x1019c` | **`+0x1e4`** |
| `__TEXT.__objc_methname` | `0x4844` | `0x4887` | **`+0x43`** |
| `__TEXT.__objc_stubs` | `0x2f60` | `0x2fa0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xfe8` | `0xff8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1696.2.5.0.0
+1696.2.8.1.0

-  CStrings:  789
+  CStrings:  791
Functions:
~ sub_1000034b0 : 14580 -> 14632
~ sub_100007954 -> sub_100007988 : 14872 -> 15304
CStrings:
+ "isNewToWalletUser"
+ "numberWithBool:"
+ "reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:"
- "reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:"
```
