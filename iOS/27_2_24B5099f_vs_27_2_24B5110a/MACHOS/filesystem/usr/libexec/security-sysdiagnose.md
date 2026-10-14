## security-sysdiagnose

> `/usr/libexec/security-sysdiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3de0` | `0x5108` | **`+0x1328`** |
| `__DATA_CONST.__cfstring` | `0xc60` | `0x1660` | **`+0xa00`** |
| `__TEXT.__cstring` | `0xe28` | `0x1597` | **`+0x76f`** |
| `__TEXT.__objc_stubs` | `0x520` | `0x660` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x42d` | `0x529` | **`+0xfc`** |
| `__DATA.__objc_selrefs` | `0x198` | `0x1e8` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x7f0` | `0x830` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x120` | `0x148` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x408` | `0x428` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1a8` | `0x1b8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62460.40.74.0.0
+62460.40.78.0.0

-  Symbols:   175
-  CStrings:  212
+  Symbols:   184
+  CStrings:  305
Symbols:
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ _OBJC_CLASS_$_NSFileManager
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _strncmp
+ _strstr
Functions:
~ sub_1000013b0 -> sub_100001400 : 6368 -> 11272
CStrings:
+ "\n                       "
+ "\n  --- Episode %@ ---\n"
+ "\n  --- Episode %lu: not readable, skipping ---\n"
+ "\n  Database: %@\n"
+ "\n End of Keychain Database Corruption History\n"
+ "\n Keychain Database Corruption History \n"
+ "\nA corruption log exists at %@ but could not be read.\n"
+ "\nNo database corruption has ever been recorded.\n"
+ "                       %@\n"
+ "                       (%@ in the write-ahead log not counted)\n"
+ "                       could not open: (%@) %@\n"
+ "                       genp: %@   inet: %@   keys: %@   cert: %@\n"
+ "  At detection:      db %@, wal %@, volume free %@, read-only %@\n"
+ "  Declared corrupt:  %@\n"
+ "  Detected:          %@ (uptime %@s, OS %@)\n"
+ "  Episodes recorded: %ld (kept: %lu, dropped: %ld)\n"
+ "  Failing statement: %@\n"
+ "  File header:       not a SQLite database (first bytes: %@)\n"
+ "  File header:       page size %@, %@ pages, change counter %@/%@, last writer sqlite %@\n"
+ "  Integrity check:   %@ (%@ of %@ rows kept)\n"
+ "  Marker:            %@\n"
+ "  Note: an earlier log was unreadable and was restarted.\n"
+ "  Origin:            %@\n"
+ "  Post-mortem:       %@\n"
+ "  Prior I/O failure: YES\n"
+ "  Remediation:       %@%@\n"
+ "  SQLite error:      (%@) %@\n"
+ "  SQLite log:\n"
+ "  Schema upgrade:    %@ -> %@\n"
+ "  Stale WAL left:    YES\n"
+ " (marker age %@s)"
+ "%ld.%ld.%ld"
+ "-corruption-log.plist"
+ ":memory:"
+ "?"
+ "NO"
+ "YES"
+ "boolValue"
+ "corruptionError"
+ "dataWithContentsOfFile:options:error:"
+ "dbSize"
+ "defaultManager"
+ "detectedAt"
+ "entries"
+ "episode"
+ "failingSQL"
+ "file:"
+ "fileChangeCounter"
+ "fileExistsAtPath:"
+ "fileHeader"
+ "fileSystemRepresentation"
+ "filesAtDetection"
+ "hadPriorIOFailure"
+ "headerFirst32Hex"
+ "i"
+ "integerValue"
+ "integrityCheck"
+ "integrityCheckRowsTotal"
+ "integrityCheckStatus"
+ "lastWriterSqliteVersion"
+ "longLongValue"
+ "magicValid"
+ "markerAgeSeconds"
+ "markerOutcome"
+ "numberWithUnsignedInteger:"
+ "openErrmsg"
+ "openResultCode"
+ "origin"
+ "osVersion"
+ "pageSize"
+ "postMortem"
+ "priorLogUnreadable"
+ "propertyListWithData:options:format:error:"
+ "remediation"
+ "schemaVersionNew"
+ "schemaVersionOld"
+ "sizeInPages"
+ "sqliteErrmsg"
+ "sqliteExtendedCode"
+ "sqliteLog"
+ "staleWalLeftBehind"
+ "status"
+ "stringByReplacingOccurrencesOfString:withString:"
+ "tableRowCounts"
+ "totalEpisodes"
+ "unknown"
+ "unreadable"
+ "uptimeAtDetection"
+ "versionValidFor"
+ "volumeFreeBytes"
+ "volumeReadOnly"
+ "walBytesNotCounted"
+ "walSize"
```
