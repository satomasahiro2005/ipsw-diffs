## migrationd

> `/System/Library/PrivateFrameworks/MigrationKit.framework/migrationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b998` | `0x1b7f0` | **`-0x1a8`** |
| `__TEXT.__cstring` | `0x41c` | `0x43c` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x5ab` | `0x58b` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0xadd` | `0xaed` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x424` | `0x428` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1428.2.1.0.0
+1439.0.0.0.0

-  CStrings:  245
+  CStrings:  244
Symbols:
+ _$s12MigrationKit6ServerC18preflightSelection10selections17disabledBundleIDsyShyAA0E0OG_ShySSGtYaFTjTu
- _$s12MigrationKit6ServerC18preflightSelection10selectionsyShyAA0E0OG_tYaFTjTu
CStrings:
+ "preflightSelection(selections:disabledBundleIDs:)"
+ "preflightSelectionWithSelections:disabledBundleIDs:"
- "preflightSelection(selections:)"
- "preflightSelectionWithSelections:"
- "v24@0:8@\"NSSet\"16"
```
