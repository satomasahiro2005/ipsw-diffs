## recentsd

> `/System/Library/PrivateFrameworks/CoreRecents.framework/recentsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x3a0f` | `0x3b40` | **`+0x131`** |
| `__TEXT.__text` | `0x177ac` | `0x178b0` | **`+0x104`** |
| `__TEXT.__objc_stubs` | `0x4000` | `0x40e0` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x142c` | `0x148c` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x1200` | `0x1240` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x133d` | `0x1373` | **`+0x36`** |
| `__TEXT.__unwind_info` | `0x7d0` | `0x7d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1237.200.11.0.0
+1237.200.21.0.0

-  Functions: 578
+  Functions: 587

-  CStrings:  1327
+  CStrings:  1336
CStrings:
+ "Unclassified sqlite error %d opening recents database"
+ "_abortForUnclassifiedSQLiteErrorCode:"
+ "_removeDatabaseForCannotOpenAndAbort"
+ "_removeDatabaseForCorruptDatabaseAndAbort"
+ "_removeDatabaseForDiskFullAndAbort"
+ "_removeDatabaseForMigrationFailureAndAbort"
+ "_removeDatabaseForNotADatabaseAndAbort"
+ "_removeDatabaseForPathAndAbort"
+ "_removeDatabaseForUnknownReasonAndAbort"
```
