## HybridDatabase

> `/System/Library/PrivateFrameworks/HybridDatabase.framework/HybridDatabase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7fc0d8` | `0x803554` | **`+0x747c`** |
| `__TEXT.__gcc_except_tab` | `0x54a70` | `0x5552c` | **`+0xabc`** |
| `__TEXT.__cstring` | `0x222eb` | `0x22915` | **`+0x62a`** |
| `__TEXT.__const` | `0xe9980` | `0xe9b40` | **`+0x1c0`** |
| `__TEXT.__unwind_info` | `0x1a900` | `0x1aa90` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x3e50` | `0x3f08` | **`+0xb8`** |
| `__TEXT.__oslogstring` | `0x3158` | `0x31e3` | **`+0x8b`** |
| `__AUTH_CONST.__objc_const` | `0xbd0` | `0xb70` | **`-0x60`** |
| `__DATA_DIRTY.__bss` | `0x4630` | `0x4690` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x70d` | `0x6ad` | **`-0x60`** |
| `__AUTH_CONST.__const` | `0x395b8` | `0x39610` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0x1008` | `0x1040` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0xac8` | `0xa98` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x200` | `0x1e0` | **`-0x20`** |
| `__DATA.__common` | `0x18` | `0x30` | **`+0x18`** |
| `__DATA.__data` | `0x494` | `0x4ac` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x528` | `0x540` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x8e0` | `0x8f6` | **`+0x16`** |
| `__DATA.__bss` | `0x3e78` | `0x3e68` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x38ac0` | `0x38ab0` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xd8` | `0xc8` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x988` | `0x978` | **`-0x10`** |
| `__AUTH.__data` | `0xd0` | `0xc8` | **`-0x8`** |

### Other Changes

```diff

-46.0.1.0.0
+49.0.1.0.0

-  Functions: 22193
-  Symbols:   470
-  CStrings:  5599
+  Functions: 22234
+  Symbols:   475
+  CStrings:  5623
Symbols:
+ _CFRelease
+ _CFStringCreateMutableCopy
+ _CFStringNormalize
+ _CFStringTransform
+ _objc_retain
+ _objc_retain_x19
- _objc_release_x28
CStrings:
+ " ..."
+ " RETURN COUNT(*);"
+ " is out of the representable range for a Kuzu timestamp."
+ ") RETURN num_terms_processed, num_new_terms, last_cursor"
+ "49.0.1"
+ "ANALYZE_FTS_INDEX"
+ "BufferReader: attempted to read {} bytes from buffer with only {} bytes remaining (buffer size {})."
+ "COPY `{}` FROM (MATCH (b:`{}`) WITH b.term as term, {}, CAST(count(*) as UINT32) as tf, {} as dense_positions_lists RETURN term, {}, tf, list_transform(list_filter(dense_positions_lists, x -> x.lst IS NOT NULL), x -> list_sort(x.lst)), list_transform(list_filter(dense_positions_lists, x -> x.lst IS NOT NULL), x -> x.idx));"
+ "CREATE (:`{}` {fts_index_name: '{}', table_name: '{}', start_term_offset: 0, max_term_offset: {}});"
+ "CREATE NODE TABLE IF NOT EXISTS `{}` (id INT64 PRIMARY KEY, state INT64);"
+ "CREATE NODE TABLE `{}` (fts_index_name STRING PRIMARY KEY, table_name STRING, start_term_offset INT64, max_term_offset INT64);"
+ "DATABASE_UUID"
+ "Deserialized std::vector length {} exceeds remaining input bytes {}."
+ "Deserialized string length {} exceeds remaining input bytes {}."
+ "Failed to count vacuum hard failures."
+ "Failed to count vacuum interruption failures."
+ "Failed to create _VACUUM_FAILURE_LOG table."
+ "Failed to record vacuum failure for type "
+ "HDB:checkpoint_on_close"
+ "HDBTokenizer: segment: sanitized input still failed UTF-8 decode (original %llu bytes)"
+ "HDBTokenizer::splitFusedTerm: called on invalid tokenizer (moved-from or init failed); returning empty"
+ "Incremental FTS retokenize: %s [%llu, %llu)/%llu, processed %llu terms, added %llu new terms, cursor %llu."
+ "Integrity check failed on FTS index {}. Position values in sublist {} are not sorted ascendingly: positions[{}]={} <= positions[{}]={} for term offset {} and doc offset {}."
+ "MATCH (:`{}`)-[:`{}`]->(:`{}`) RETURN count(*)"
+ "MATCH (a:`_VACUUM_FAILURE_LOG`) WHERE a.type = "
+ "MATCH (a:`{}`) RETURN a.state;"
+ "MATCH (n:`{}`) RETURN count(*)"
+ "Mismatch between null segment and null column existance."
+ "Rare case: FSST-compressed string data was larger than the uncompressed data. %{public}lu/%{public}llu strings with total size %{public}llu were compressed into a %{public}llu byte buffer"
+ "Retokenize progress table was not initialized. The database may need to be re-opened."
+ "Segment page range [{}, {}) is beyond the end of the DB file (numPages={})."
+ "String index {} at position {} is out of bounds (max {})! "
+ "String offsets for lookup are invalid or fall outside the bounds of the data! String: [{}, {}), max offset in segment: {}"
+ "String offsets to be scanned ({}/{}) are invalid or fall outside the bounds of the data! String: [{}, {}), max offset in segment: {}"
+ "String offsets {}, {} are decreasing instead of increasing. Length of compressed string was {}"
+ "String segment has no null segment!"
+ "Term alternatives shouldn't be generated for a stopword only query fragment."
+ "_VACUUM_FAILURE_LOG"
+ "_VACUUM_STATE"
+ "`(\n    id SERIAL,\n    type INT64,\n    progress DOUBLE,\n    PRIMARY KEY(id)\n)"
+ "checkpoint_on_close failed: %s"
+ "checkpoint_on_close: time_ms=%{public}llu"
+ "columnID < dataTypes.size()"
+ "com.apple.hybriddatabase.retokenize"
+ "createInternalRetokenizeTable: failed with unknown error"
+ "createInternalRetokenizeTable: failed: %{public}s"
+ "interruptionCount"
+ "numTermsProcessed"
+ "num_new_terms"
+ "uuid"
- "',\n    start_term_offset: 0,\n    max_term_offset: "
- "',\n    table_name: '"
- ") RETURN num_terms_processed, last_cursor"
- "46.0.1"
- "COPY `{}` FROM (MATCH (b:`{}`) WITH b.term as term, {}, CAST(count(*) as UINT32) as tf, {} as dense_positions_lists RETURN term, {}, tf, list_transform(list_filter(dense_positions_lists, x -> x.lst IS NOT NULL), x -> x.lst), list_transform(list_filter(dense_positions_lists, x -> x.lst IS NOT NULL), x -> x.idx));"
- "CREATE NODE TABLE IF NOT EXISTS `_VACUUM_STATE`(id INT64 PRIMARY KEY, state INT64);"
- "CREATE NODE TABLE `"
- "Checkpoint during database destruction failed with error %{public}s "
- "Checkpoint during database destruction failed with unknown error"
- "Failed to create _INCREMENTAL_FTS_RETOKENIZE_PROGRESS table."
- "Failed to create retokenize progress entry for "
- "HDB:deinit_db"
- "HDBTokenizer: segment: sanitized input still failed UTF-8 decode (original %zu bytes)"
- "Incremental FTS retokenize: %s [%llu, %llu)/%llu, processed %llu terms, cursor %llu."
- "Incremental FTS retokenize: registered %s/%s (max offset: %lld)"
- "Incremental FTS retokenize: skipping %s/%s (empty terms table)"
- "Ingested failure."
- "MATCH (a:`_VACUUM_STATE`) RETURN a.state;"
- "No vacuum is in progress."
- "No vacuum to resume."
- "Vacuum was interrupted."
- "` {\n    fts_index_name: '"
- "`(\n    fts_index_name STRING PRIMARY KEY,\n    table_name STRING,\n    start_term_offset INT64,\n    max_term_offset INT64\n)"
- "checkpoint_on_close: finished"
- "deinit_db: starting"
- "deinit_db: time_ms=%{public}llu"
```
