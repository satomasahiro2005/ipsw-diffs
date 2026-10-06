## FeedbackLogger

> `/System/Library/PrivateFrameworks/FeedbackLogger.framework/FeedbackLogger`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d754` | `0x1dd5c` | **`+0x608`** |
| `__TEXT.__oslogstring` | `0x1dd7` | `0x2027` | **`+0x250`** |
| `__AUTH_CONST.__objc_const` | `0x1a60` | `0x1ad0` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x11fc` | `0x124c` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xc88` | `0xcc0` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x2a4` | `0x2dc` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x450` | `0x478` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xa80` | `0xa98` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x12c` | `0x138` | **`+0xc`** |
| `__TEXT.__cstring` | `0x2081` | `0x2079` | **`-0x8`** |

### Other Changes

```diff

-3600.56.26.11.2
+3605.21.1.1.1

-  Functions: 929
-  Symbols:   1047
-  CStrings:  344
+  Functions: 935
+  Symbols:   1063
+  CStrings:  352
Symbols:
+ -[FLLogger _cancelTerminationWatcher]
+ -[FLLogger _handleTermination]
+ -[FLLogger _setupTerminationWatcher]
+ -[FLLogger _tryRelinquishForTerminationWithAttemptsRemaining:]
+ -[FLLogger setTerminationWatcher:]
+ -[FLLogger terminationWatcher]
+ -[FLSQLitePersistence(BatchManager) firstPayloadForBatch:]
+ -[FLSQLitePersistence(UploadManager) doUploadHousekeeping:]
+ GCC_except_table109
+ GCC_except_table121
+ GCC_except_table124
+ GCC_except_table130
+ GCC_except_table192
+ GCC_except_table261
+ GCC_except_table286
+ GCC_except_table360
+ GCC_except_table49
+ GCC_except_table59
+ GCC_except_table74
+ GCC_except_table80
+ GCC_except_table87
+ GCC_except_table91
+ GCC_except_table94
+ _OBJC_IVAR_$_FLLogger._terminating
+ _OBJC_IVAR_$_FLLogger._terminationWatcher
+ _OBJC_IVAR_$_FLLogger._terminationWatcherResolved
+ ___36-[FLLogger _setupTerminationWatcher]_block_invoke
+ ___62-[FLLogger _tryRelinquishForTerminationWithAttemptsRemaining:]_block_invoke
+ ___block_descriptor_48_e8_32w_e5_v8?0lw32l8
+ __dispatch_source_type_signal
+ _os_unfair_lock_trylock
- -[FLSQLitePersistence(UploadManager) doUploadHousekeeping]
- GCC_except_table105
- GCC_except_table122
- GCC_except_table183
- GCC_except_table252
- GCC_except_table277
- GCC_except_table351
- GCC_except_table47
- GCC_except_table57
- GCC_except_table66
- GCC_except_table78
- GCC_except_table83
- GCC_except_table89
- GCC_except_table92
- _MGCopyAnswer
CStrings:
+ "Gave up relinquishing the write transaction after SIGTERM: lock held throughout. Falling back to the TTL."
+ "Got SIGTERM while holding a write transaction; relinquishing it now."
+ "Got SIGTERM with no write transaction held; later writes get the shortened TTL."
+ "Installed SIGTERM watcher (dispatch source only; signal disposition untouched)."
+ "Managed process: not installing a SIGTERM watcher (RBSAssertion path)."
+ "SELECT payload FROM records WHERE batchId=? ORDER BY rowId ASC LIMIT 1;"
+ "SELECT s.batchId, s.timestampRefId, COALESCE(sum(length(r.payload)), 0), s.status, s.processedAttempts, s.dateCreated, s.dateUploaded, s.dateLastProcessed, COUNT(DISTINCT(r.rowId)) FROM batchStatus s LEFT JOIN records r ON s.batchId = r.batchId WHERE s.batchId=? GROUP BY s.batchId;"
+ "SIGTERM watcher fired in a managed process; ignoring."
+ "SQLite first payload read for batch (%s) failed: %d"
+ "Write arrived after SIGTERM; not re-punting the write transaction TTL deadline."
- "RegulatoryModelNumber"
- "SELECT s.batchId, s.timestampRefId, COALESCE(sum(length(r.payload)), 0), s.status, s.processedAttempts, s.dateCreated, s.dateUploaded, s.dateLastProcessed, COUNT(DISTINCT(r.rowId)), first_value(r.payload) OVER (ORDER BY r.rowId) FROM batchStatus s LEFT JOIN records r ON s.batchId = r.batchId WHERE s.batchId=? GROUP BY s.batchId;"
```
