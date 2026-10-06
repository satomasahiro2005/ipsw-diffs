## Accessory Updater Service

> `/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/Accessory Updater Service.xpc/Accessory Updater Service`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x780c0` | `0x78100` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__TEXT.__cstring` | `0x178bf` | `0x178c0` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3696.0.12.0.3
+3696.40.10.0.0

-  Symbols:   1875
+  Symbols:   1876
Symbols:
+ _kAMSupportHttpOptionRequestHTTPAllowed
Functions:
~ _AMAuthInstallApFinalize : 264 -> 288
~ sub_1000185d0 -> sub_1000185e8 : 1836 -> 1876
CStrings:
+ "libauthinstall_device-1155.40.6"
- "libauthinstall_device-1155.0.5"
```
