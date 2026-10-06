## cloudphotod

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/Support/cloudphotod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cca40` | `0x1cd73c` | **`+0xcfc`** |
| `__TEXT.__oslogstring` | `0x126d8` | `0x128bf` | **`+0x1e7`** |
| `__TEXT.__objc_methname` | `0x2ad81` | `0x2ae51` | **`+0xd0`** |
| `__DATA_CONST.__cfstring` | `0x13460` | `0x13520` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0x1cb40` | `0x1cc00` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x1c0f2` | `0x1c18c` | **`+0x9a`** |
| `__TEXT.__objc_methlist` | `0x1094c` | `0x109cc` | **`+0x80`** |
| `__DATA.__objc_const` | `0x1eea8` | `0x1eee8` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x2e68` | `0x2e28` | **`-0x40`** |
| `__TEXT.__objc_methtype` | `0x8cea` | `0x8d26` | **`+0x3c`** |
| `__DATA.__objc_selrefs` | `0x8d88` | `0x8dc0` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x6df0` | `0x6e10` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xb070` | `0xb088` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xe78` | `0xe70` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x13f4` | `0x13f8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
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
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-910.33.102.0.0
+912.0.111.0.0

-  Functions: 10165
-  Symbols:   1061
-  CStrings:  11469
+  Functions: 10187
+  Symbols:   1060
+  CStrings:  11493
Symbols:
- _CPLSyncSessionPredictionTypeTurboMode
CStrings:
+ "%@ tried to discard a downloaded resource for a manager that is not present"
+ "B32@0:8@\"CPLResource\"16^@24"
+ "DELETE FROM %@ WHERE itemIdentifier = %@ AND resourceType = %i AND scopeIndex = %ld AND status = %i"
+ "Database encountered an unexpected IO error: %@"
+ "Database encountered continuous IO errors - marking the database as corrupted"
+ "Database faced IO error twice - requiring emergency exit"
+ "Failed to discard downloaded %@: %@"
+ "Failed to remove previous I/O error info at %@: %@"
+ "Failed to write marker at %@: %@"
+ "Requested forced backup failed for %@ - continuing: %@"
+ "Trying to discard downloaded %@ but scope is invalid"
+ "_corruptionInfoFromError:db:"
+ "_ioErrorInTransaction"
+ "_shouldContinueBackupAfterError:"
+ "countOfDownloadedResources"
+ "desiredQOS"
+ "discardDownloadedResource:"
+ "io_error_marker"
+ "maintenance"
+ "removeDownloadedResource:error:"
+ "shouldUseTurboMode"
+ "user-initiated"
+ "utility"
+ "v24@0:8@\"CPLResource\"16"
+ "writeToURL:error:"
+ "\xf0\xf0\xd1"
- "predictedValueForType:"
- "\xf0\xf0\xc1"
```
