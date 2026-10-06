## NotesSupport

> `/System/Library/PrivateFrameworks/NotesSupport.framework/NotesSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55ce0` | `0x58404` | **`+0x2724`** |
| `__TEXT.__oslogstring` | `0x3e86` | `0x4496` | **`+0x610`** |
| `__AUTH_CONST.__cfstring` | `0x4460` | `0x4640` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x4589` | `0x4749` | **`+0x1c0`** |
| `__AUTH_CONST.__objc_const` | `0x5ed0` | `0x5f90` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x3178` | `0x3230` | **`+0xb8`** |
| `__AUTH_CONST.__auth_got` | `0x1050` | `0x1100` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x4378` | `0x43f8` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x120` | `0x170` | **`+0x50`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x120` | `0x150` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1380` | `0x13a8` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x188` | `0x1a8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xed8` | `0xef0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x888` | `0x898` | **`+0x10`** |
| `__TEXT.__const` | `0xb6c` | `0xb5c` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0xde` | `0xec` | **`+0xe`** |
| `__DATA_CONST.__objc_classlist` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1d38` | `0x1d40` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x220` | `0x224` | **`+0x4`** |

### Other Changes

```diff

-2996.0.0.0.0
+2998.0.0.0.0

+  - /usr/lib/libsqlite3.dylib

-  Functions: 2539
-  Symbols:   3737
-  CStrings:  1031
+  Functions: 2570
+  Symbols:   3778
+  CStrings:  1080
Symbols:
+ +[ICPersistentContainer isOutOfSpaceError:]
+ +[ICPersistentContainer isSHMOpenError:]
+ +[ICSQLiteRecovery recoverDatabaseAtURL:toURL:error:]
+ -[ICPersistentContainer allowsDatabaseRecovery]
+ -[ICPersistentContainer attemptSQLiteRecoveryWithError:]
+ -[ICPersistentContainer failureCountFileURL]
+ -[ICPersistentContainer readFailureCount]
+ -[ICPersistentContainer resetFailureCount]
+ -[ICPersistentContainer setAllowsDatabaseRecovery:]
+ -[ICPersistentContainer writeFailureCount:]
+ _ICArchiveReaderResolveURL
+ _NSUnderlyingErrorKey
+ _OBJC_CLASS_$_ICSQLiteRecovery
+ _OBJC_IVAR_$_ICPersistentContainer._allowsDatabaseRecovery
+ _OBJC_METACLASS_$_ICSQLiteRecovery
+ __OBJC_$_CLASS_METHODS_ICSQLiteRecovery
+ __OBJC_CLASS_RO_$_ICSQLiteRecovery
+ __OBJC_METACLASS_RO_$_ICSQLiteRecovery
+ ___block_descriptor_40_e8_32r_e50_v24?0"NSPersistentStoreDescription"8"NSError"16lr32l8
+ _archive_read_free
+ _archive_read_support_filter_all
+ _archive_write_add_filter_bzip2
+ _archive_write_add_filter_none
+ _archive_write_disk_set_options
+ _archive_write_free
+ _sqlite3_bind_blob
+ _sqlite3_bind_double
+ _sqlite3_bind_int64
+ _sqlite3_bind_null
+ _sqlite3_bind_text
+ _sqlite3_close
+ _sqlite3_column_blob
+ _sqlite3_column_bytes
+ _sqlite3_column_count
+ _sqlite3_column_double
+ _sqlite3_column_int64
+ _sqlite3_column_text
+ _sqlite3_column_type
+ _sqlite3_errmsg
+ _sqlite3_exec
+ _sqlite3_finalize
+ _sqlite3_free
+ _sqlite3_open_v2
+ _sqlite3_prepare_v2
+ _sqlite3_reset
+ _sqlite3_step
- _archive_read_finish
- _archive_read_support_compression_all
- _archive_write_finish
- _archive_write_set_compression_bzip2
- _archive_write_set_compression_none
CStrings:
+ "%@-recovered-%@.sqlite"
+ ", ?"
+ ".failurecount"
+ "Attempting SQLite recovery after %lu consecutive failures"
+ "BEGIN TRANSACTION"
+ "Beginning SQLite recovery from %@ to %@"
+ "COMMIT"
+ "Crashing to allow relaunch. Failure count: %lu"
+ "Database open failed after all retries. Failure count: %lu"
+ "Database open failed after retries during unit tests; replacing store instead of relaunching. Failure count: %lu"
+ "Database open failed and would exit; surfacing error instead during unit tests: %@"
+ "Database open succeeded on retry attempt %lu"
+ "Entry path '%@' escapes destination directory"
+ "Error reading row from table %@: %s (code %d)"
+ "Failed to create deferred schema object: %s"
+ "Failed to create destination database for recovery: %s (code %d)"
+ "Failed to create destination database: %s"
+ "Failed to create table %@: %s"
+ "Failed to insert row into table %@: %s"
+ "Failed to move recovered database into place: %@"
+ "Failed to open corrupt database for recovery: %s (code %d)"
+ "Failed to open corrupt database: %s"
+ "Failed to prepare INSERT for table %@: %s"
+ "Failed to prepare SELECT for table %@: %s"
+ "Failed to read sqlite_master: %s"
+ "Failed to read sqlite_master: %s (code %d)"
+ "Failed to remove failure count file: %@"
+ "Failed to write failure count file: %@"
+ "INSERT INTO \"%@\" VALUES (?"
+ "No schema entries found in corrupt database"
+ "ROLLBACK"
+ "Recovered database is now in place at %@"
+ "Retry attempt %lu failed: %@"
+ "Retrying database open (attempt %lu of 3)"
+ "SELECT * FROM \"%@\""
+ "SELECT type, name, tbl_name, sql FROM sqlite_master WHERE sql IS NOT NULL ORDER BY rowid"
+ "SQLITE_IOERR_SHMOPEN persisted after retries; not destroying the store. Failure count: %lu"
+ "SQLite recovery completed successfully"
+ "SQLite recovery failed: %@"
+ "SQLite recovery failed: %@. Falling back to database move."
+ "SQLite recovery produced no data"
+ "SQLite recovery succeeded"
+ "SQLite recovery succeeded. Backing up corrupt database and replacing with recovered database."
+ "Table %@: recovered %lu rows, failed %lu rows"
+ "private"
+ "sql"
+ "table"
+ "type"
+ "unknown error"
+ "var"
- "Entry path '%@' contains directory traversal"
```
