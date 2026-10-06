## EnergyKitService

> `/System/Library/PrivateFrameworks/EnergyKitInternal.framework/XPCServices/EnergyKitService.xpc/EnergyKitService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x2c68` | `0x2cca` | **`+0x62`** |
| `__DATA_CONST.__const` | `0x3518` | `0x3528` | **`+0x10`** |
| `__DATA.__objc_const` | `0x3630` | `0x3638` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xae0` | `0xae8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xb98` | `0xba0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-490.1.4.0.0
+504.0.0.0.0

+  - /usr/lib/swift/libswiftAccelerate.dylib

+  - /usr/lib/swift/libswiftIntents.dylib

-  Symbols:   6310
-  CStrings:  926
+  Symbols:   6314
+  CStrings:  927
Symbols:
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftAccelerate_$_EnergyKitService
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftIntents_$_EnergyKitService
CStrings:
+ "homeManager:didRemoveCurrentAccessoryWithRegulatoryEraseRequired:"
```
