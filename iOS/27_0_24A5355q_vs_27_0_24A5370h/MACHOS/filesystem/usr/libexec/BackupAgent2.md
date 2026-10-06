## BackupAgent2

> `/usr/libexec/BackupAgent2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0x9820` | `0x99f0` | **`+0x1d0`** |
| `__TEXT.__text` | `0x906c4` | `0x90610` | **`-0xb4`** |
| `__DATA.__objc_data` | `0x22b0` | `0x2350` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0xde37` | `0xde9d` | **`+0x66`** |
| `__TEXT.__objc_stubs` | `0xc900` | `0xc960` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x9520` | `0x94e0` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x5fa4` | `0x5fe4` | **`+0x40`** |
| `__TEXT.__cstring` | `0x18e7c` | `0x18eab` | **`+0x2f`** |
| `__TEXT.__objc_methtype` | `0x1e71` | `0x1e9d` | **`+0x2c`** |
| `__TEXT.__objc_classname` | `0x9ee` | `0xa09` | **`+0x1b`** |
| `__TEXT.__gcc_except_tab` | `0x2104` | `0x2118` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x3c88` | `0x3c98` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1428` | `0x1418` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x378` | `0x388` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x220` | `0x230` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1950` | `0x1940` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x54c` | `0x558` | **`+0xc`** |
| `__TEXT.__objc_methname` | `0xe7b4` | `0xe7ac` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`

### Other Changes

```diff

-3033.0.0.0.0
+3036.0.0.0.0

-  Functions: 2446
+  Functions: 2450

-  CStrings:  5746
+  CStrings:  5756
CStrings:
+ "@\"MBErrorInjector\""
+ "AQ"
+ "B20@0:8B16"
+ "Failed to set kMBNotUploadedDatabaseIndexFlag for %@:%@: %@"
+ "Ignoring SQLite compaction failure for %@"
+ "MBAtomicBool"
+ "MBAtomicULong"
+ "Q24@0:8Q16"
+ "Simulated SQLite compaction error"
+ "T@\"MBErrorInjector\",&,N,V_sqliteErrorInjector"
+ "_markDatabaseWithSQLiteCompactionFailure:error:"
+ "_sqliteErrorInjector"
+ "backupPathsToFailSQLiteCompactionRegex"
+ "exchange:"
+ "fetchAdd:"
+ "increment"
+ "initWithInitialValue:"
+ "setSqliteErrorInjector:"
+ "setValue:"
+ "sqliteErrorInjector"
- "Unexpected container type: %d"
- "_failedToCompactSQLiteDatabase:"
- "background app group restore"
- "background app plugin restore"
- "backgroundAppGroupRestoreModeWithBundleID:"
- "backgroundAppPluginRestoreModeWithBundleID:"
- "backgroundAppRestoreModeWithBundleID:errorCode:"
- "backgroundContainerRestoreModeWithContainer:"
- "restoreModeWithType:value:"
- "restoreTypeForContainerType:"
```
