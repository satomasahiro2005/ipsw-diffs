## HealthDaemonFoundation

> `/System/Library/PrivateFrameworks/HealthDaemonFoundation.framework/HealthDaemonFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x73c84` | `0x749ac` | **`+0xd28`** |
| `__AUTH_CONST.__const` | `0x2820` | `0x2960` | **`+0x140`** |
| `__TEXT.__cstring` | `0x49ba` | `0x4ada` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0x4060` | `0x4100` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x3696` | `0x3726` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0x3034` | `0x30a8` | **`+0x74`** |
| `__TEXT.__unwind_info` | `0x2940` | `0x2998` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0x494` | `0x4e4` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x14c8` | `0x1510` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x3d8c` | `0x3dc4` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0xc12` | `0xc40` | **`+0x2e`** |
| `__TEXT.__constg_swiftt` | `0xbb0` | `0xbdc` | **`+0x2c`** |
| `__DATA_CONST.__objc_selrefs` | `0x21c8` | `0x21e0` | **`+0x18`** |
| `__DATA.__bss` | `0x1f90` | `0x1fa0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x6d8` | `0x6e8` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xa80` | `0xa70` | **`-0x10`** |
| `__TEXT.__const` | `0x2322` | `0x2332` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x938` | `0x948` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1120` | `0x1128` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x2c` | `0x30` | **`+0x4`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  Functions: 3089
-  Symbols:   3969
-  CStrings:  901
+  Functions: 3118
+  Symbols:   3975
+  CStrings:  909
Symbols:
+ -[HDDatabaseAssertionManager _lock_releaseBackgroundAccessForFiles:]
+ -[HDSQLiteDatabase truncateWriteAheadLogWithBusyTimeout:contended:error:]
+ GCC_except_table109
+ GCC_except_table110
+ __CLASS_METHODS_HDFastPassBackgroundTask
+ __CLASS_METHODS_HDOneShotBackgroundTask
+ __ZZ25HDSQLiteEntityForPropertyE18propertyOwnerCache
+ __ZZ25HDSQLiteEntityForPropertyE23_propertyOwnerCacheLock
+ ___73-[HDSQLiteDatabase truncateWriteAheadLogWithBusyTimeout:contended:error:]_block_invoke
+ ___swift_project_boxed_opaque_existential_0
+ _symbolic $s22HealthDaemonFoundation0B14PluginProviderP
- GCC_except_table105
- GCC_except_table106
- GCC_except_table112
- GCC_except_table67
- ___swift_destroy_boxed_opaque_existential_1Tm
CStrings:
+ "\" entitlement: got "
+ "%{public}@: Failed to open a database file to release the assertion: %d"
+ "/locked-access"
+ "<%@ %@ %@ %@%@ ctx:%ld%@: %@>"
+ "Cannot resolve process identifier for empty application identifier."
+ "Failed to continue activity"
+ "Failed to open a database file to request the assertion: %d"
+ "Failed to publish XPC event for %llu with error: %d"
+ "Failed to request the assertion: %d"
+ "HDXPCClient connection is nil; cannot validate \""
+ "PRAGMA wal_checkpoint(truncate)"
+ "Published XPC event for %llu"
- "<%@ %@ %@ %@%@: %@>"
- "Failed to publish XPC event for %ld with error: %d"
- "Published XPC event for %ld"
- "\x91"
```
