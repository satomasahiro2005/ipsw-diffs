## trustd

> `/usr/libexec/trustd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a680` | `0x5be04` | **`+0x1784`** |
| `__DATA_CONST.__cfstring` | `0x5ea0` | `0x6740` | **`+0x8a0`** |
| `__DATA.__bss` | `0x540` | `0xc50` | **`+0x710`** |
| `__TEXT.__cstring` | `0x621e` | `0x6650` | **`+0x432`** |
| `__TEXT.__oslogstring` | `0x5f18` | `0x6120` | **`+0x208`** |
| `__TEXT.__objc_stubs` | `0x3400` | `0x3520` | **`+0x120`** |
| `__TEXT.__auth_stubs` | `0x23c0` | `0x2490` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x3e70` | `0x3f38` | **`+0xc8`** |
| `__TEXT.__objc_methname` | `0x307d` | `0x312e` | **`+0xb1`** |
| `__DATA_CONST.__auth_got` | `0x11f0` | `0x1258` | **`+0x68`** |
| `__DATA.__objc_selrefs` | `0xe88` | `0xed0` | **`+0x48`** |
| `__DATA_CONST.__objc_intobj` | `0x120` | `0x138` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1040` | `0x1050` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-62460.40.74.0.0
+62460.40.78.0.0

-  Functions: 1210
-  Symbols:   884
-  CStrings:  2240
+  Functions: 1214
+  Symbols:   897
+  CStrings:  2335
Symbols:
+ ___strlcpy_chk
+ _dirname_r
+ _pread
+ _rename
+ _sqlite3_close_v2
+ _statfs
+ _strcmp
+ _strlcpy
+ _strncmp
+ _strstr
+ _sysctl
+ _time
+ _unlink
CStrings:
+ "%02x"
+ "%s-wal"
+ "%s.%d.tmp"
+ "(%d) %s"
+ "-corruption-log.plist"
+ "-wal"
+ ":memory:"
+ "B16@?0^{__OpaqueSecDbConnection={__CFRuntimeBase=QAQ}^{__OpaqueSecDb}BBQBiB^{__CFError}{?=CCCCBBiiiiiCI[4[160c]][128c][256c][192c]}^{sqlite3}i^{__CFArray}}8"
+ "SELECT count(*) FROM cert"
+ "SELECT count(*) FROM genp"
+ "SELECT count(*) FROM inet"
+ "SELECT count(*) FROM keys"
+ "SecDBCheckCorrupted integrity_check returned %{public}s"
+ "SecDbCorruptionLog: close failed (%{darwin.errno}d)"
+ "SecDbCorruptionLog: log at %{public}@ was unusable, starting over"
+ "SecDbCorruptionLog: path too long: %{public}@"
+ "SecDbCorruptionLog: unable (%{darwin.errno}d) to create %s"
+ "SecDbCorruptionLog: unable (%{darwin.errno}d) to rename into place"
+ "SecDbCorruptionLog: unable (%{darwin.errno}d) to set protection class"
+ "SecDbCorruptionLog: unable to serialize log for %{public}@"
+ "SecDbCorruptionLog: write failed (%{darwin.errno}d)"
+ "SecDbHandleCorrupt: Tried to write corruption marker %{public}s but one already exists"
+ "SecDbSecDbProcessCorruptionMarker: found corruption marker %{public}s"
+ "appendFormat:"
+ "bytesRead"
+ "completed"
+ "corruptionError"
+ "couldNotRun"
+ "dataWithContentsOfFile:options:error:"
+ "dbDeleted"
+ "dbMtime"
+ "dbSize"
+ "dbUnlinkFailed"
+ "detectedAt"
+ "entries"
+ "episode"
+ "failingSQL"
+ "file:"
+ "fileChangeCounter"
+ "fileExistsAtPath:"
+ "fileHeader"
+ "fileURLWithPath:"
+ "filesAtDetection"
+ "genp"
+ "hadPriorIOFailure"
+ "headerFirst32Hex"
+ "immutable=1"
+ "inet"
+ "integerValue"
+ "integrityCheck"
+ "integrityCheckRowsTotal"
+ "integrityCheckStatus"
+ "kern.osversion"
+ "keys"
+ "lastWriterSqliteVersion"
+ "magicValid"
+ "markerAgeSeconds"
+ "markerOutcome"
+ "migrationFailure"
+ "noSuccessor"
+ "openErrmsg"
+ "openFailed"
+ "openResultCode"
+ "origin"
+ "osVersion"
+ "pageSize"
+ "postMortem"
+ "preexisted"
+ "priorLogUnreadable"
+ "ranAndFailed"
+ "readErrno"
+ "remediation"
+ "removeObjectsInRange:"
+ "resetOnly"
+ "schemaVersionNew"
+ "schemaVersionOld"
+ "setQuery:"
+ "sizeInPages"
+ "sqlite3: (%d) %{public}s"
+ "sqliteCorrupt"
+ "sqliteErrmsg"
+ "sqliteExtendedCode"
+ "sqliteLog"
+ "sqliteNotADb"
+ "sqliteSystemErrno"
+ "staleWalLeftBehind"
+ "stringByAppendingString:"
+ "stringWithCapacity:"
+ "tableRowCounts"
+ "totalEpisodes"
+ "unknown"
+ "uptimeAtDetection"
+ "versionValidFor"
+ "volumeFreeBytes"
+ "volumeReadOnly"
+ "walBytesNotCounted"
+ "walSize"
+ "writeFailed"
+ "written"
- "B16@?0^{__OpaqueSecDbConnection={__CFRuntimeBase=QAQ}^{__OpaqueSecDb}BBQBiB^{__CFError}^{sqlite3}i^{__CFArray}}8"
- "SecDBCheckCorrupted integrity_check returned %s"
- "SecDbHandleCorrupt: Tried to write corruption marker %s but one already exists"
- "SecDbSecDbProcessCorruptionMarker: found corruption marker %s"
```
