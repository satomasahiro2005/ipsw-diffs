## aidearlyboot

> `/usr/libexec/aidearlyboot`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2d4` | `0xa340` | **`+0x6c`** |
| `__TEXT.__cstring` | `0xee5` | `0xf1d` | **`+0x38`** |
| `__DATA_CONST.__cfstring` | `0xbe0` | `0xc00` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xab1` | `0xabd` | **`+0xc`** |
| `__TEXT.__objc_methtype` | `0x220` | `0x21f` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-10100.41.0.0.0
+10110.1.0.0.0

-  CStrings:  295
+  CStrings:  296
Symbols:
+ _CFErrorCopyDescription
+ _objc_retain_x25
- _objc_autorelease
- _objc_retain_x23
Functions:
~ sub_100002b68 : 976 -> 952
~ sub_100002f68 -> sub_100002f50 : 1204 -> 1336
CStrings:
+ "%s: failed to retrieve localData for key (%@) dataInstance (%@) error (%@)"
+ "%s: failed to retrieve localDict for key (%@) dataInstance (%@) error (%@)"
+ "-[AIDFirmwareUpdateController extractFDRDataWithClassKey:usesMultiInstance:]"
+ "@28@0:8@16B24"
+ "Error finding FDR data collection for class '%@'"
+ "extractFDRDataWithClassKey:usesMultiInstance:"
+ "nil"
- "%s: localData is NULL for key (%@) dataInstance (%@)"
- "%s: localDict is NULL for key (%@) dataInstance (%@)"
- "-[AIDFirmwareUpdateController extractFDRDataWithClassKey:error:]"
- "@32@0:8@16^@24"
- "Error finding FDR data collection for class '%@': %@"
- "extractFDRDataWithClassKey:error:"
```
