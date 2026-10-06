## FitnessIntelligencePlugin

> `/System/Library/Health/Plugins/FitnessIntelligencePlugin.bundle/FitnessIntelligencePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7d0b4` | `0x7f3a4` | **`+0x22f0`** |
| `__DATA_CONST.__const` | `0x40a8` | `0x42c8` | **`+0x220`** |
| `__TEXT.__cstring` | `0x19cf` | `0x1b0f` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x125f` | `0x138f` | **`+0x130`** |
| `__TEXT.__eh_frame` | `0x1ad8` | `0x1bd8` | **`+0x100`** |
| `__TEXT.__swift5_capture` | `0x1078` | `0x10ec` | **`+0x74`** |
| `__TEXT.__unwind_info` | `0x1290` | `0x12d0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1e20` | `0x1e40` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x16a9` | `0x16c9` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0xb6b` | `0xb8b` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1154` | `0x1168` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0xf18` | `0xf28` | **`+0x10`** |
| `__TEXT.__const` | `0x15a8` | `0x15b8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x76f` | `0x77f` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x7e4` | `0x7f0` | **`+0xc`** |
| `__DATA.__objc_const` | `0x15e0` | `0x15e8` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x4b8` | `0x4c0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x530` | `0x538` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2027.0.59.0.2
+2027.0.66.0.0

-  Functions: 1763
+  Functions: 1796

-  CStrings:  502
+  CStrings:  515
CStrings:
+ "  SELECT\n    1\n  FROM\n    activity_caches\n  WHERE\n    cache_index >= "
+ "  SELECT\n    1\n  FROM\n    workout_activities\n  WHERE\n    start_date >= "
+ " AND cache_index <= "
+ " AND start_date <= "
+ "ALTER TABLE FitnessIntelligencePlugin_workoutPropertyRecords ADD COLUMN planIdentifier TEXT;"
+ "Failed to check if there's data to process: %@"
+ "Starting migration to v11"
+ "[%s] Failed to check hasRawDataAvailable: %@"
+ "[%s] Failed to query Monthly Database Checksums: %@"
+ "hasDataAvailable = %{bool}d, hasRingsDataAvailable = %{bool}d, hasWorkoutDataAvailable = %{bool}d"
+ "hasDataToProcessWithCompletion:"
+ "planIdentifier"
+ "v24@0:8@?<v@?B@\"NSError\">16"
```
