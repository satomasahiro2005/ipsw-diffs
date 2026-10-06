## com.apple.CallKit.CallDirectoryMaintenance

> `/System/Library/Frameworks/CallKit.framework/XPCServices/com.apple.CallKit.CallDirectoryMaintenance.xpc/com.apple.CallKit.CallDirectoryMaintenance`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24584` | `0x245f4` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0x3a0` | `0x3e0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x843` | `0x853` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-156.200.70.2.2
+156.200.88.2.3

-  CStrings:  1048
+  CStrings:  1051
Functions:
~ sub_10000eb68 : 456 -> 568
CStrings:
+ "Migration %@"
+ "failed"
+ "requestedMigrationOfAllDataFromExtensionWithBundleID:%@ toBundleID:%@"
+ "succeeded"
- "requestedMigrationOfAllDataFromExtensionWithBundleID:%@ fromBundleID:%@"
```
