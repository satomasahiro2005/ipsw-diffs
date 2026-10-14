## FitnessIntelligencePlugin

> `/System/Library/Health/Plugins/FitnessIntelligencePlugin.bundle/FitnessIntelligencePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x849d4` | `0x85058` | **`+0x684`** |
| `__DATA_CONST.__const` | `0x47f8` | `0x48e8` | **`+0xf0`** |
| `__TEXT.__swift5_capture` | `0x11cc` | `0x1210` | **`+0x44`** |
| `__TEXT.__cstring` | `0x1c2f` | `0x1c6f` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x16df` | `0x171f` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x1e40` | `0x1e78` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1390` | `0x13a0` | **`+0x10`** |
| `__DATA.__objc_data` | `0x12c0` | `0x12c8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xbf0` | `0xbf8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.1.34.0.0
+2027.1.35.0.0

-  Functions: 1863
+  Functions: 1875

-  CStrings:  540
+  CStrings:  542
CStrings:
+ "Migration %ld: table %s already has column year, skipping..."
+ "SELECT 1 FROM pragma_table_info(?) WHERE name = ?;"
```
