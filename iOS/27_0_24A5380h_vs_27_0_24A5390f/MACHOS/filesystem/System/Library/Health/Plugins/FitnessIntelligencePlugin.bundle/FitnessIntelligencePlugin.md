## FitnessIntelligencePlugin

> `/System/Library/Health/Plugins/FitnessIntelligencePlugin.bundle/FitnessIntelligencePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80554` | `0x810f8` | **`+0xba4`** |
| `__TEXT.__eh_frame` | `0x1d18` | `0x1de8` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x142f` | `0x14cf` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x4318` | `0x4368` | **`+0x50`** |
| `__TEXT.__const` | `0x15e8` | `0x1618` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x1110` | `0x1134` | **`+0x24`** |
| `__TEXT.__unwind_info` | `0x1328` | `0x1348` | **`+0x20`** |
| `__DATA.__data` | `0x1708` | `0x1718` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xc` | `0x18` | **`+0xc`** |
| `__DATA.__objc_data` | `0x12a8` | `0x12b0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xbbc` | `0xbc4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x8` | `0xc` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x8` | `0xc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2027.0.71.0.0
+2027.0.74.0.0

-  Functions: 1813
-  Symbols:   237
-  CStrings:  519
+  Functions: 1821
+  Symbols:   236
+  CStrings:  523
Symbols:
- _notify_post
CStrings:
+ "[%s] Active Workout going on, cancelling snapshot processing"
+ "[%s] Failed to cancel snapshot processing: %@."
+ "[%s] Failed to invalidate OSTransaction: %@."
+ "isReadyToProcess = %{bool}d"
+ "isReadyToProcess = false: workout is active"
+ "isReadyToProcessWithCompletion:"
- "[%s] Failed to invalidate OSTransaction: %@. Sending Darwin Notification"
- "hasDataToProcessWithCompletion:"
```
