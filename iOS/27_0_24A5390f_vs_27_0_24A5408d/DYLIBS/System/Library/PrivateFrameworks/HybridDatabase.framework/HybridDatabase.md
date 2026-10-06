## HybridDatabase

> `/System/Library/PrivateFrameworks/HybridDatabase.framework/HybridDatabase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x803554` | `0x806780` | **`+0x322c`** |
| `__TEXT.__unwind_info` | `0x1aa90` | `0x1b0e0` | **`+0x650`** |
| `__TEXT.__cstring` | `0x22915` | `0x22e16` | **`+0x501`** |
| `__TEXT.__gcc_except_tab` | `0x5552c` | `0x558dc` | **`+0x3b0`** |
| `__DATA.__bss` | `0x3e68` | `0x4018` | **`+0x1b0`** |
| `__TEXT.__const` | `0xe9b40` | `0xe9cc0` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0x39610` | `0x39738` | **`+0x128`** |
| `__TEXT.__eh_frame` | `0x3f08` | `0x4010` | **`+0x108`** |
| `__TEXT.__swift5_fieldmd` | `0xa98` | `0xb30` | **`+0x98`** |
| `__TEXT.__swift5_reflstr` | `0x6ad` | `0x70d` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0xac8` | `0xb00` | **`+0x38`** |
| `__DATA_DIRTY.__bss` | `0x4690` | `0x4670` | **`-0x20`** |
| `__TEXT.__swift5_assocty` | `0x98` | `0xb0` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x8f6` | `0x90a` | **`+0x14`** |
| `__TEXT.__oslogstring` | `0x31e3` | `0x31d6` | **`-0xd`** |
| `__TEXT.__swift5_proto` | `0x1dc` | `0x1e8` | **`+0xc`** |
| `__DATA.__data` | `0x4ac` | `0x4b4` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xec` | `0xf4` | **`+0x8`** |

### Other Changes

```diff

-49.0.1.0.0
+54.0.0.0.0

-  Functions: 22234
+  Functions: 22278

-  CStrings:  5623
+  CStrings:  5659
CStrings:
+ "54"
+ "Assertion failed in \"#%{public}s:#%{public}d\": #%{public}s"
+ "Assertion failed in \"{}:{}\": {}"
+ "ChunkedCSRHeader::integrityCheck: CSR offset {} at index {} is less than offset {} at index {}"
+ "ChunkedCSRHeader::integrityCheck: Largest CSR offset {} is larger than the number of rows in the CSR {}."
+ "Found CHECKPOINT record in WAL but no shadow file"
+ "HybridSearch.IntegrityCheckCorruptionErrorSilenced"
+ "InMemChunkedCSRHeader::populateCSRLengthFromOffsets: CSR offset {} at index {} is less than offset {} at index {}"
+ "IntegrityCheck: Mismatch between existence of null column of column '{}' ({}) and null segment ({})."
+ "Predicate contains {} conjunctive expressions, which exceeds the maximum of {}."
+ "WAL file size {} is larger than the corruptWALSizeLimit {}."
+ "catalogSizeMB"
+ "com.apple.HybridSearch.index.errors"
+ "com.apple.hybriddatabase.retokenize.status"
+ "com.apple.hybriddatabase.storage.deletions"
+ "connectionConfigError"
+ "connectionInitializationFailed"
+ "currentLength >= numDeletedRows"
+ "dataFileSizeMB"
+ "databaseInitializationFailed"
+ "deletionPercent"
+ "entry"
+ "errorCode"
+ "errorDescription"
+ "errorDomain"
+ "errorMsg"
+ "fsmFreeSizeMB"
+ "getFlatTupleFailed"
+ "getNextQueryResultFailed"
+ "hnswIndexNotReady"
+ "i == 0 || csrOffsets[i] >= csrOffsets[i - 1]"
+ "metadataSizeMB"
+ "operation"
+ "pagesToVacuum"
+ "prepareStatmentFailed"
+ "queryExecutionFailed"
+ "shadowSizeMB"
+ "topKInputCount"
+ "totalPages"
+ "transactionManager"
+ "valueConversionFailed"
- "49.0.1"
- "Assertion failed in file \"#%{public}s\" on line #%{public}d: #%{public}s"
- "Assertion failed in file \"{}\" on line {}: {}"
- "Mismatch between null segment and null column existance."
- "encountered"
```
