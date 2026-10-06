## FitnessIntelligencePlugin

> `/System/Library/Health/Plugins/FitnessIntelligencePlugin.bundle/FitnessIntelligencePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x810f8` | `0x81b58` | **`+0xa60`** |
| `__TEXT.__oslogstring` | `0x14cf` | `0x160f` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x4380` | `0x4430` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x1b0f` | `0x1b2f` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x550` | `0x558` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1348` | `0x1350` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
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

-2027.0.77.1.1
+2027.0.77.1.3

-  Functions: 1821
+  Functions: 1826

-  CStrings:  523
+  CStrings:  529
CStrings:
+ " WHERE version < ?;"
+ "Failed to decode LegacyInferenceRecord from row: %ld, ignoring."
+ "Failed to decode PropertyRecordCheckpoint from row: %ld"
+ "Failed to deserialize InferenceRecord: %@"
+ "Starting migration to v12"
+ "[%s] Generate sync objects from %s"
+ "[PropertyRecordCheckpoint] Failed to parse snapshotPropertiesType from %s"
+ "[PropertyRecordCheckpoint] Failed to read snapshotPropertiesType from row"
- "Failed to decode InferenceRecord from row: %ld, ignoring."
- "Generate sync objects from %s"
```
