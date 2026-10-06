## backupd

> `/System/Library/PrivateFrameworks/MobileBackup.framework/backupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0xd10` | `0xf30` | **`+0x220`** |
| `__TEXT.__text` | `0x2473c8` | `0x2471c8` | **`-0x200`** |
| `__DATA_CONST.__const` | `0x7e00` | `0x7da0` | **`-0x60`** |
| `__TEXT.__oslogstring` | `0x31219` | `0x31263` | **`+0x4a`** |
| `__TEXT.__objc_stubs` | `0x28060` | `0x280a0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x9d78` | `0x9d48` | **`-0x30`** |
| `__TEXT.__cstring` | `0x6863b` | `0x6860c` | **`-0x2f`** |
| `__DATA_CONST.__cfstring` | `0x1aee0` | `0x1aec0` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x15e84` | `0x15ea4` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xb798` | `0xb7a8` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x3775a` | `0x3774a` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x65ee` | `0x65e6` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x61f0` | `0x61f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3036.0.0.0.0
+3038.0.0.0.0

-  Functions: 8923
+  Functions: 8925
CStrings:
+ "=pqldb= Unexpected open success when creating empty DB at %@"
+ "Failed to create SQLite database"
+ "Starting NAND task scheduler with %llu MB"
+ "_isSQLiteCannotOpenError"
+ "mb_openAtURL:withFlags:error:"
+ "sendBackgroundRestoreCompletion:account:restoreSession:restorePlan:duration:error:"
+ "sendStatusRequestForBackgroundRestoreCompletionWithAccount:databaseManager:sourceDeviceID:snapshotUUID:snapshotIndex:snapshotFormat:snapshotPolicy:isRestoringUsingFileLists:fatalErrors:plan:duration:error:"
+ "v108@0:8@16@24@32@40Q48q56q64B72@76@84d92@100"
+ "v64@0:8@16@24@32@40d48@56"
- "Can't find the cache database"
- "Can't find the database: %@"
- "Creating system container domain for "
- "Creating system shared container domain for "
- "Starting NAND task scheduler"
- "sendBackgroundRestoreCompletion:snapshotIdentifier:snapshotFormat:isRestoringUsingFileLists:duration:error:fatalErrors:domainsTopNSizes:domainsTopNFileCount:failedDomains:"
- "sendStatusRequestForBackgroundRestoreCompletionWithAccount:databaseManager:sourceDeviceID:snapshotUUID:snapshotIndex:snapshotFormat:isRestoringUsingFileLists:fatalErrors:plan:duration:error:"
- "v100@0:8@16@24@32@40Q48q56B64@68@76d84@92"
- "v92@0:8Q16@24q32B40d44@52@60@68@76@84"
```
