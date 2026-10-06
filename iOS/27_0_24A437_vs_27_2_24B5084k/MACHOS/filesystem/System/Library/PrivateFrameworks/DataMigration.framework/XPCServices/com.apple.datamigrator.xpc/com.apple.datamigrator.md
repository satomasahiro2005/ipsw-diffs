## com.apple.datamigrator

> `/System/Library/PrivateFrameworks/DataMigration.framework/XPCServices/com.apple.datamigrator.xpc/com.apple.datamigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12ebc` | `0x12f0c` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x2a60` | `0x2a80` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xa00` | `0x9f0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x510` | `0x508` | **`-0x8`** |
| `__TEXT.__cstring` | `0x3b64` | `0x3b63` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2858.0.0.0.0
+2858.1.3.0.0

-  Symbols:   307
-  CStrings:  1227
+  Symbols:   306
+  CStrings:  1228
Symbols:
- _xpc_transaction_exit_clean
Functions:
~ sub_1000014d0 : 400 -> 396
~ sub_10000f364 -> sub_10000f360 : 692 -> 776
CStrings:
+ "DMMigratorProxy did end transaction for event %p msgID %@ from client pid %@."
+ "DMMigratorProxy did send response for event %p msgID %@ to client pid %@. will end transaction."
+ "Terminating Preboard in mode: %@"
- "DMMigratorProxy did end transaction for event %p msgID %@ from client pid %@. will attempt to exit clean."
- "DMMigratorProxy did send response for event %p msgID %@ to client pid %@. will attempt to exit clean."
```
