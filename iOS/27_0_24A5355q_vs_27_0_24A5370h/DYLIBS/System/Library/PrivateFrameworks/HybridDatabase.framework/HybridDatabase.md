## HybridDatabase

> `/System/Library/PrivateFrameworks/HybridDatabase.framework/HybridDatabase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85d6c8` | `0x83d550` | **`-0x20178`** |
| `__TEXT.__const` | `0xea900` | `0xe9540` | **`-0x13c0`** |
| `__TEXT.__oslogstring` | `0x2956` | `0x2ed4` | **`+0x57e`** |
| `__AUTH_CONST.__const` | `0x394f8` | `0x39048` | **`-0x4b0`** |
| `__TEXT.__cstring` | `0x262c1` | `0x26673` | **`+0x3b2`** |
| `__TEXT.__eh_frame` | `0x39d0` | `0x3be0` | **`+0x210`** |
| `__TEXT.__unwind_info` | `0x1a698` | `0x1a818` | **`+0x180`** |
| `__DATA.__bss` | `0x4098` | `0x4118` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x54574` | `0x54508` | **`-0x6c`** |
| `__AUTH_CONST.__auth_got` | `0x1030` | `0xfd8` | **`-0x58`** |
| `__AUTH.__thread_vars` | `0x30` | `0x60` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x862` | `0x890` | **`+0x2e`** |
| `__DATA.__data` | `0x4c8` | `0x4e8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x38a60` | `0x38a80` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0xa4c` | `0xa68` | **`+0x1c`** |
| `__AUTH.__thread_bss` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xe8` | `0xd8` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x66d` | `0x65d` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x518` | `0x520` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x928` | `0x920` | **`-0x8`** |
| `__TEXT.__swift5_fieldmd` | `0xa2c` | `0xa30` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x1d8` | `0x1dc` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xe0` | `0xe4` | **`+0x4`** |

### Other Changes

```diff

-40.0.0.0.0
+44.0.1.0.0

-  Functions: 22111
-  Symbols:   478
-  CStrings:  5560
+  Functions: 22044
+  Symbols:   464
+  CStrings:  5590
Symbols:
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6assignERKS5_mm
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6assignEmc
+ _dispatch_apply
+ _objc_retain_x21
+ _objc_retain_x23
+ _pwritev
- __ZNSt3__115__thread_structC1Ev
- __ZNSt3__115__thread_structD1Ev
- __ZNSt3__118condition_variable10notify_allEv
- __ZNSt3__118condition_variable15__do_timed_waitERNS_11unique_lockINS_5mutexEEENS_6chrono10time_pointINS5_12system_clockENS5_8durationIxNS_5ratioILl1ELl1000000000EEEEEEE
- __ZNSt3__118condition_variable4waitERNS_11unique_lockINS_5mutexEEE
- __ZNSt3__119__shared_mutex_base8try_lockEv
- __ZNSt3__119__thread_local_dataEv
- __ZNSt3__120__throw_system_errorEiPKc
- __ZNSt3__16thread4joinEv
- __ZNSt3__16threadD1Ev
- _os_release
- _pthread_create
- _pthread_override_qos_class_end_np
- _pthread_override_qos_class_start_np
- _pthread_self
- _pthread_set_qos_class_self_np
- _pthread_setspecific
- _swift_getTupleTypeMetadata2
- _voucher_adopt
- _voucher_copy
CStrings:
+ "!done()"
+ "#%{public}llx checkpoint: merge delta CSR, delta_size=%{public}llu, delta_threshold=%{public}llu, main_size=%{public}llu"
+ "%{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1171: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:434: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:438: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:446: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:509: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/extension/fts/src/function/parsed_fts_query.cpp"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/table/column_chunk_scan_cursor.cpp"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/table/csr_column_chunk_checkpoint_cursor.cpp"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/table/node_group.cpp"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/table/segment_split_streamer.cpp"
+ "44.0.1"
+ "ALTER TABLE `{}` ADD `{}` UINT32 default cast(0, 'UINT32');"
+ "Catalog entry for table {}: property {} has column ID {} but the table only has {} columns."
+ "Catalog entry for table {}: property {} has type {} in the catalog but type {} in the table."
+ "Connection or prepared statement is null or invalid"
+ "Contiguous preallocation request for file %{public}s of %{public}llu bytes partially allocated %{public}llu bytes."
+ "Deserialized multiple tables with table ID {}"
+ "Duplicate index {} in the phrase_idx parameter; each index must be unique."
+ "FTS failed to allocate the '{}' stemmer."
+ "Failed to execute prepared statement with params"
+ "Failed to execute query with params"
+ "Failed to preallocate space for file. path: {} fileDescriptor: {} numBytes: {}. Error: {}"
+ "HDBTokenizer: failed to extract UTF-8 bytes for normalized string of length %llu"
+ "HDBTokenizer::naturalTokenCount: called on invalid tokenizer (moved-from or init failed); returning 0"
+ "HDBTokenizer::streamIngestionTerms: called on invalid tokenizer (moved-from or init failed); returning 0"
+ "Index {} in the phrase_idx parameter is out of range; each index must be in the range [0, {})."
+ "ListSegment::integrityCheck: list[{}] end offset {} < start offset {}"
+ "ListSegment::write - trying to read range [startOffset={}, listSize={}] from srcListSegment data segment with numValues={}"
+ "MATCH (indexTable:`{}`) SET indexTable.`{}` = CAST({} AS UINT32);"
+ "Mismatch between segment data type {} and expected data type for column {}."
+ "Non-empty column chunks should never have empty segments"
+ "OnDiskListSegment::sanityCheck: list segment's numValues %{public}llu is not equal to the offset segment's numValues %{public}llu."
+ "OnDiskListSegment::sanityCheck: list segment's offset segment has type %{public}s instead of UINT64."
+ "OnDiskSegment::sanityCheck: null segment's numValues %{public}llu is not equal to the parent segment's numValues %{public}llu."
+ "OnDiskStringSegment::sanityCheck: string segment's index segment has type %{public}s instead of UINT32."
+ "OnDiskStringSegment::sanityCheck: string segment's numValues %{public}llu is not equal to the index segment's numValues %{public}llu."
+ "OnDiskStringSegment::sanityCheck: string segment's offset segment has type %{public}s instead of UINT64."
+ "OnDiskStringSegment::sanityCheck: string segment's string data segment has type %{public}s instead of UINT8."
+ "Preallocation request for file %{public}s of size %{public}llu bytes. File size is now %{public}llu bytes. Successfully managed to allocate %{public}llu bytes."
+ "Segment sanity check failed"
+ "Struct segment has {} children but the column has {} children"
+ "TOKENIZER_GET_NUM_TOKENS"
+ "The query parameter must be a list of phrase groups, where each phrase group is itself a list of terms (e.g. [['quantum mechanics'], ['exploration']]). A flat list of terms (e.g. ['quantum', 'exploration']) is no longer accepted."
+ "coalesce(TOKENIZER_GET_NUM_TOKENS(CAST(indexTable.`{}` AS STRING)), 0)"
+ "columnChunk.getNumSegments() > 0"
+ "columnChunk.getResidencyState() == ResidencyState::ON_DISK"
+ "columnID != NBR_ID_COLUMN_ID && columnID != REL_ID_COLUMN_ID"
+ "columnID + 1 >= chunks.size()"
+ "columnID + 1 >= columnStats.size()"
+ "columnID + 1 >= columns.size()"
+ "columnID + 1 >= dataTypes.size()"
+ "currentSegmentIdx == oldSegmentsIterator.segments.getNumSegments() - 1"
+ "dbPageCount=%llu success=%d"
+ "ftsMatchedDocCount"
+ "ftsQueryTerms"
+ "init_db: starting: buildVersion=%{public}s storageVersion=%{public}llu DEFAULT_VECTOR_CAPACITY=%{public}llu PAGE_SIZE_LOG2=%{public}llu TEMP_PAGE_SIZE_LOG2=%{public}llu NODE_GROUP_SIZE_LOG2=%{public}llu CHUNKED_NODE_GROUP_CAPACITY=%{public}llu MAX_SEGMENT_SIZE_LOG2=%{public}llu SEGMENT_GAP_FACTOR=%{public}.2f readOnly=%{bool}d bufferPoolSize=%{public}llu evictionLimit=%{public}llu maxParallelism=%{public}llu enableMultiWrites=%{bool}d enableCompression=%{bool}d autoCheckpoint=%{bool}d checkpointThreshold=%{public}llu forceCheckpointOnClose=%{bool}d checkpointOnCloseWALSizeThreshold=%{public}llu enableChecksums=%{bool}d"
+ "isStopword"
+ "libhybriddatabase/src/include/storage/stats/table_stats.h"
+ "newNumDocs >= undoRecord.numInsertedDocs"
+ "nodeGroup"
+ "persistentColumnChunk.getNumSegments() > 0"
+ "queryWithParams does not support multiple statements."
+ "segment->getNumValues() > 0"
+ "segmentIdx < segments.size()"
+ "segmentIdx <= getNumSegments()"
+ "segmentOffsetToFlushUntil <= segment->getNumValues()"
+ "segments.getNumSegments() > 1"
+ "segments.getNumSegments() >= 1"
+ "segments.getSegment(i).getNumValues() > 0"
+ "segments.getSegment(segmentIdx).getResidencyState() == ResidencyState::ON_DISK"
+ "segments.size() == 1"
+ "task->maxParallelism > 0"
+ "v16@?0Q8"
+ "wal_dry_replay: WAL file appears corrupted: %{public}s, offsetDeserialized %{public}llu, isLastRecordCheckpoint %{public}b"
+ "wal_dry_replay: WAL file appears corrupted: unknown error, offsetDeserialized %{public}llu, isLastRecordCheckpoint %{public}b"
- "!remainingUncheckpointedValues"
- "#%{public}llx checkpoint: merge delta CSR, delta_size=%{public}llu, main_size=%{public}llu"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1146: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1156: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:413: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:418: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:433: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:437: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:441: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:445: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:494: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/deque:2341: libc++ Hardening assertion __f != end() failed: deque::erase(iterator) called with a non-dereferenceable iterator\n"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/extension/fts/src/function/query_fts_bind_data.cpp"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/table/column_chunk_checkpoint_cursor.cpp"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/table/segment_checkpoint_flusher.cpp"
- "40"
- "A phrase with multiple terms is not allowed in negated_terms parameter."
- "A prefix phrase must be provided for prefix search."
- "ALTER TABLE `{}` ADD `{}` UINT32;"
- "CALL enable_internal_catalog = false;"
- "CALL enable_internal_catalog = true;"
- "Checkpoint timed out"
- "Connection, prepared statement, or bound values are null or invalid"
- "Failed to bind value: "
- "Failed to execute prepared statement"
- "HDBTokenizer: failed to extract UTF-8 bytes for token at UTF-16 range [%llu, %llu) within normalized string of length %llu"
- "ListSegment (ON_DISK): list[{}] end offset {} < start offset {}"
- "ListSegment: list[{}] end offset {} < start offset {}"
- "MATCH (indexTable:`{}`), (appearsInfo:`{}`) WHERE {} WITH indexTable, {} as len SET indexTable.`{}` = len;"
- "Segment sanity check failed."
- "String segment's numValues is not equal to the index segment's numValues."
- "[TaskScheduler] currQoS %{public}i. setQoS to %{public}i"
- "` = appearsInfo.docID"
- "cachedWrites.empty()"
- "checkpointingLastExistingSegment() || newCachedWrites.startRow + newCachedWrites.numRows <= getNewEndOffsetForCurrentSegment()"
- "count(DISTINCT appearsInfo.`{}`)"
- "indexTable.`"
- "init_db: starting: buildVersion=%{public}s storageVersion=%{public}llu DEFAULT_VECTOR_CAPACITY=%{public}llu PAGE_SIZE_LOG2=%{public}llu TEMP_PAGE_SIZE_LOG2=%{public}llu NODE_GROUP_SIZE_LOG2=%{public}llu CHUNKED_NODE_GROUP_CAPACITY=%{public}llu MAX_SEGMENT_SIZE_LOG2=%{public}llu SEGMENT_GAP_FACTOR=%{public}.2f readOnly=%{bool}d maxDBSize=%{public}llu bufferPoolSize=%{public}llu evictionLimit=%{public}llu maxNumThreads=%{public}llu enableMultiWrites=%{bool}d enableCompression=%{bool}d autoCheckpoint=%{bool}d checkpointThreshold=%{public}llu forceCheckpointOnClose=%{bool}d checkpointOnCloseWALSizeThreshold=%{public}llu throwOnWalReplayFailure=%{bool}d enableChecksums=%{bool}d enableSpillingToDisk=%{bool}d threadQos=%{public}u"
- "key value "
- "list segment's numValues is not equal to the offset segment's numValues."
- "list segment's offset segment has type {} instead of UINT64."
- "newWorkerThread"
- "null segment's numValues is not equal to the parent segment's numValues."
- "segmentIt.segmentIdxFromEnd <= 1"
- "string segment's index segment has type {} instead of UINT32."
- "string segment's offset segment has type {} instead of UINT64."
- "string segment's string data segment has type {} instead of UINT8."
- "thread constructor failed"
- "unique_lock::lock: already locked"
- "unique_lock::lock: references null mutex"
- "unique_lock::try_lock: references null mutex"
- "unique_lock::unlock: not locked"
```
