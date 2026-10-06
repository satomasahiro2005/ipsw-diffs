## FitnessIntelligencePlugin

> `/System/Library/Health/Plugins/FitnessIntelligencePlugin.bundle/FitnessIntelligencePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81b14` | `0x849d4` | **`+0x2ec0`** |
| `__DATA_CONST.__const` | `0x4418` | `0x47f8` | **`+0x3e0`** |
| `__TEXT.__cstring` | `0x1b2f` | `0x1c2f` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x7f0` | `0x8d8` | **`+0xe8`** |
| `__TEXT.__oslogstring` | `0x160f` | `0x16df` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0x1134` | `0x11cc` | **`+0x98`** |
| `__TEXT.__auth_stubs` | `0x1f30` | `0x1fa0` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x1de8` | `0x1e40` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x130e` | `0x1354` | **`+0x46`** |
| `__TEXT.__swift5_reflstr` | `0x77f` | `0x7bf` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1350` | `0x1390` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0xfa0` | `0xfd8` | **`+0x38`** |
| `__DATA.__data` | `0x1718` | `0x1748` | **`+0x30`** |
| `__TEXT.__const` | `0x1618` | `0x1648` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0xbc4` | `0xbf0` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x558` | `0x580` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0xb8b` | `0xb6b` | **`-0x20`** |
| `__DATA.__objc_data` | `0x12b0` | `0x12c0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x468` | `0x470` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.1.26.0.0
+2027.1.34.0.0

-  Functions: 1826
+  Functions: 1863

-  CStrings:  529
+  CStrings:  540
CStrings:
+ " ADD COLUMN year INTEGER;"
+ " SET year = CAST(strftime('%Y', startCacheIndex + "
+ ", 'unixepoch') AS INTEGER)"
+ "Failed to run migration to v%ld: %@"
+ "Migration %ld: table %s doesn't exist, skipping..."
+ "SELECT 1 from sqlite_master where type='table' and name=?;"
+ "Starting migration to v%ld"
+ "Starting migration to v13"
+ "Starting migration to v14"
+ "monthOfYear IS NOT NULL"
+ "year"
```
