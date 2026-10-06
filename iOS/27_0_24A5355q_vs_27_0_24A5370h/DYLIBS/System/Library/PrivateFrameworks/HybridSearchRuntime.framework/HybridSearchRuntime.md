## HybridSearchRuntime

> `/System/Library/PrivateFrameworks/HybridSearchRuntime.framework/HybridSearchRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22e254` | `0x252548` | **`+0x242f4`** |
| `__TEXT.__eh_frame` | `0x1b100` | `0x1e4bc` | **`+0x33bc`** |
| `__TEXT.__const` | `0xab40` | `0xbb90` | **`+0x1050`** |
| `__AUTH_CONST.__const` | `0xe0d0` | `0xd0a0` | **`-0x1030`** |
| `__TEXT.__unwind_info` | `0x8100` | `0x8fd0` | **`+0xed0`** |
| `__DATA.__bss` | `0x5aa0` | `0x66a0` | **`+0xc00`** |
| `__TEXT.__swift5_capture` | `0x43b4` | `0x3be8` | **`-0x7cc`** |
| `__TEXT.__swift_as_cont` | `0x26a8` | `0x2c88` | **`+0x5e0`** |
| `__DATA.__data` | `0x2538` | `0x2988` | **`+0x450`** |
| `__AUTH_CONST.__auth_got` | `0x2660` | `0x2a88` | **`+0x428`** |
| `__TEXT.__swift5_typeref` | `0x5700` | `0x5aa2` | **`+0x3a2`** |
| `__TEXT.__oslogstring` | `0x6a7d` | `0x6dfd` | **`+0x380`** |
| `__AUTH.__data` | `0x1dc8` | `0x2110` | **`+0x348`** |
| `__AUTH_CONST.__objc_const` | `0x22d0` | `0x25d8` | **`+0x308`** |
| `__TEXT.__swift5_fieldmd` | `0x275c` | `0x2a50` | **`+0x2f4`** |
| `__TEXT.__constg_swiftt` | `0x3564` | `0x3848` | **`+0x2e4`** |
| `__TEXT.__cstring` | `0xe574` | `0xe801` | **`+0x28d`** |
| `__TEXT.__swift_as_ret` | `0x115c` | `0x13d4` | **`+0x278`** |
| `__TEXT.__swift5_reflstr` | `0x1e20` | `0x1fb0` | **`+0x190`** |
| `__DATA_CONST.__got` | `0x1bb0` | `0x1cd0` | **`+0x120`** |
| `__TEXT.__swift_as_entry` | `0xcfc` | `0xdf8` | **`+0xfc`** |
| `__TEXT.__swift5_proto` | `0x588` | `0x5e8` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x1f0` | `0x240` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0xb58` | `0xba0` | **`+0x48`** |
| `__TEXT.__swift5_types` | `0x410` | `0x448` | **`+0x38`** |
| `__DATA.__common` | `0x60` | `0x80` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0xd0` | `0xe8` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x2e90` | `0x2e78` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1428` | `0x1438` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x678` | `0x684` | **`+0xc`** |
| `__TEXT.__swift5_protos` | `0x84` | `0x7c` | **`-0x8`** |

### Other Changes

```diff

-53.0.0.0.0
+57.0.1.0.0

-  Functions: 11383
-  Symbols:   372
-  CStrings:  928
+  Functions: 12043
+  Symbols:   374
+  CStrings:  942
Symbols:
+ _NSURLCreationDateKey
+ _objc_release_x12
+ _swift_unknownObjectRelease_n
+ _sysconf
- _OBJC_CLASS_$_NSFileHandle
- _ffsctl
CStrings:
+ "\n)\nRETURN\nscore,\nmetadata,\nnode."
+ " AS has_embeddings"
+ " AS stable_id,\n       n."
+ " AS versioned_id,\n       n.payload AS payload,\n       "
+ "%s: Cancelled. Elapsed time: %{public}s."
+ "%{public}s: Complete. Elapsed time: %{public}s."
+ "%{public}s: Elapsed time: %{public}s. Error: %{public}@"
+ "%{public}s: Started. Task priority: %{public}s→%{public}hhu, qos: %{public}s, thread priority: %{public}s"
+ "%{public}s: failed to read creation date for %{public}s: %{public}@ — removing"
+ "%{public}s: no creation date for %{public}s — removing"
+ "%{public}s: removed %{public}s (created %{public}s)"
+ "%{public}sDonationStore is managed by spotlightknowledged"
+ "%{public}sDonationStore: Batch #%{public}ld containing %{public}ld change sets, instances: +%{public}ld/-%{public}ld, source: %{public}s)"
+ "%{public}sDonationStore: Beginning Cascade enumeration for set: %s"
+ "%{public}sDonationStore: Cache miss for donation %{public}s; indexing partial record without text content"
+ "%{public}sDonationStore: Change #%{public}ld, elapsed: %{public}ss, instances: +%{public}ld/-%{public}ld, devices: +%{public}ld/-%{public}ld, source: %{public}s)"
+ "%{public}sDonationStore: Counting entities by display identifier"
+ "%{public}sDonationStore: Does not support set for identifier: %{public}s"
+ "%{public}sDonationStore: Dropping invalid bookmark for set: %s"
+ "%{public}sDonationStore: Failed to create document cache retriever for identifier: %{public}s, error: %{public}@"
+ "%{public}sDonationStore: Failed to donate %{public}ld items, error: %{public}@"
+ "%{public}sDonationStore: Failed to generate bookmark"
+ "%{public}sDonationStore: Failed to process added instances: %{public}ld and removed instances: %{public}ld. Error: %{public}@"
+ "%{public}sDonationStore: Failed to render and chunk schematized record: %{public}@"
+ "%{public}sDonationStore: Failed to retrieve item with identifier: %{public}s"
+ "%{public}sDonationStore: Failed to schematize donation %{public}s: %{public}@"
+ "%{public}sDonationStore: Failed to schematize remote donation %{public}s: %{public}@"
+ "%{public}sDonationStore: Force backfill complete"
+ "%{public}sDonationStore: Force backfill requested"
+ "%{public}sDonationStore: Ignoring duplicate request to startLiveListening"
+ "%{public}sDonationStore: Ignoring duplicate request to stopLiveListening"
+ "%{public}sDonationStore: Invariant violation — multiple remote schematizers produced a record for shared item %{public}s. Only one remote schematizer should handle a given shared item."
+ "%{public}sDonationStore: Invariant violation — multiple schematizers produced a record for item %{public}s. Only one schematizer should handle a given item."
+ "%{public}sDonationStore: Live listeners active"
+ "%{public}sDonationStore: Processing cascade data with identifier: %{public}s"
+ "%{public}sDonationStore: Processing donation: %{public}s"
+ "%{public}sDonationStore: Processing remote donation: %{public}s"
+ "%{public}sDonationStore: Processing status, invalid bookmark"
+ "%{public}sDonationStore: Raw changes%{public}s"
+ "%{public}sDonationStore: Resolved changes for indexing %{public}s"
+ "%{public}sDonationStore: Resolved changes for staleness%{public}s"
+ "%{public}sDonationStore: Retrying in %{public}ss"
+ "%{public}sDonationStore: Schematization broke provenance (deviceIdentifier)"
+ "%{public}sDonationStore: Schematization broke provenance (devicePlatform)"
+ "%{public}sDonationStore: Schematization broke provenance (itemInstanceUUID)"
+ "%{public}sDonationStore: Schematization broke provenance (sharedItemUUID)"
+ "%{public}sDonationStore: Schematization broke provenance (sourceItemUUID)"
+ "%{public}sDonationStore: Schematization returned nil for donation %{public}s"
+ "%{public}sDonationStore: Schematization returned nil for remote donation %{public}s"
+ "%{public}sDonationStore: Set processing attempt %{public}ld failed: %{public}@"
+ "%{public}sDonationStore: Set processing cancelled"
+ "%{public}sDonationStore: Set processing failed after exponential backoff. Final error: %{public}@"
+ "%{public}sDonationStore: Skipping removal of: %{public}s as an update will be coming."
+ "%{public}sDonationStore: Stopped live listeners"
+ "%{public}sDonationStore: Successfully deleted %{public}ld items"
+ "%{public}sDonationStore: Successfully donated %{public}ld items"
+ "%{public}sDonationStore: Warning: skipping remote items, no remote data schematizer"
+ "%{public}sDonationStore: cooldown(): document processing session warmup/cooldown failure"
+ "%{public}sDonationStore: createEmbeddings called"
+ "%{public}sDonationStore: createEmbeddings outcome for %{public}s: %s"
+ "%{public}sDonationStore: deleteEmbeddings: batch delete failed: %@"
+ "%{public}sDonationStore: deleteEmbeddings: item %{public}s already removed from Cascade, treating as already deleted"
+ "%{public}sDonationStore: deleteEmbeddings: set not found for %{public}s, nothing to delete"
+ "%{public}sDonationStore: deleteItems: batch delete failed: %{public}@"
+ "%{public}sDonationStore: deleting %{public}ld items"
+ "%{public}sDonationStore: document processing session warmup/cooldown failure"
+ "%{public}sDonationStore: forceBackfill() not supported"
+ "%{public}sDonationStore: index(items:) failed to create set key: %{public}@"
+ "%{public}sDonationStore: performBackfill() not supported"
+ "%{public}sDonationStore: processingStatus() not supported"
+ "%{public}sDonationStore: startLiveListening() not supported"
+ "%{public}sDonationStore: startup task cancelled during backfill"
+ "%{public}sDonationStore: startup task completed backfill"
+ "%{public}sDonationStore: startup task failed to backfill: %{public}@"
+ "%{public}sDonationStore: startup task performing backfill"
+ "%{public}sDonationStore: startup task starting live listeners"
+ "%{public}sDonationStore: stopLiveListening() not supported"
+ "%{public}sDonationStore: updateItems: batch update failed: %{public}@"
+ "%{public}sDonationStore: updateItems: failed to create document cache retriever: %{public}@"
+ "%{public}sDonationStore: updateItems: failed to retrieve item %{public}s: %@"
+ "%{public}sDonationStore: updateItems: item %{public}s not found in set"
+ "%{public}sDonationStore: updating %{public}ld items"
+ "%{public}sDonationStore: warmup(): document processing session warmup/cooldown failure"
+ ",\n    prefix_search := "
+ ", phrase_idx := $phraseIdx"
+ "CollectorRef should not be encoded directly"
+ "Created new database for path: %{private}s"
+ "EXISTS { MATCH (n)-[:"
+ "Failed to decode content: "
+ "HybridIndex deinit for path: %{private}s"
+ "HybridIndexMigrator: Found %{public}ld previously applied migration(s) (latest: '%{public}s' applied_at=%{public}s), %{public}ld pending."
+ "HybridIndexMigrator: No previously applied migrations found, %{public}ld pending."
+ "HybridSearchRuntime/JSONOrderedEncoder.swift"
+ "IndexingServer.updateEmbeddingsByReference"
+ "IngestionManager: updateEmbeddingsByReference called for %{public}ld reference(s)"
+ "IngestionManager: updateEmbeddingsByReference stage 2 — %{public}ld reference(s) flagged documentNotFound, attempting recovery"
+ "IngestionManager: updateEmbeddingsByReference stage 2 — recovered %{public}ld/%{public}ld reference(s)"
+ "SearchServer.dumpDomain"
+ "Started %{public}sDonationStore"
+ "Starting %{public}sDonationStore"
+ "Stopped %{public}sDonationStore"
+ "Stopping %{public}sDonationStore"
+ "[[]], prefix_search:= true, conjunctive := true, compute_bm25 := false, negated_terms := $"
+ "com.apple.GenerativeSearch.PeriodicTasks.CorruptDatabasesCleanupTask"
+ "embedQueryUsingSafety: starting embedding generation (timeout=%{public}s, priority=%{public}hhu, checkSafety=%{bool,public}d, contextLength=%{public}s)"
+ "hybridIndexCorruption: "
+ "hybridIndexDatabaseError: "
+ "hybridIndexKuzuDatabaseError: "
+ "hybridIndexMigrationFailed: "
+ "hybridIndexMissingMigrationTable: "
+ "hybridIndexOther: "
+ "hybridIndexSchemaMismatch: "
+ "hybridIndexVersionMismatch: "
+ "perform(text:checkSafety:safetyThreshold:embeddingModelProperties:contextLength:allowTruncation:)"
+ "prewarm(contextLength:allowTruncation:)"
+ "referencesCount: %ld"
+ "retrieveDomain"
+ "searchDomain"
+ "searchGlobal"
+ "updateEmbeddingsByReference"
+ "yyyy-MM-dd HH:mm:ssZ"
- "\nRETURN\nscore,\nmetadata,\nnode."
- "%s: Cancelled. Elapsed time: %s."
- "%sDonationStore is managed by spotlightknowledged"
- "%sDonationStore: Batch #%ld containing %ld change sets, instances: +%ld/-%ld, source: %s)"
- "%sDonationStore: Beginning Cascade enumeration for set: %s"
- "%sDonationStore: Cache miss for donation %s; indexing partial record without text content"
- "%sDonationStore: Change #%ld, elapsed: %ss, instances: +%ld/-%ld, devices: +%ld/-%ld, source: %s)"
- "%sDonationStore: Counting entities by display identifier"
- "%sDonationStore: Does not support set for identifier: %{private}s"
- "%sDonationStore: Dropping invalid bookmark for set: %s"
- "%sDonationStore: Failed to create document cache retriever for identifier: %{private}s, error: %@"
- "%sDonationStore: Failed to donate %ld items, error: %@"
- "%sDonationStore: Failed to generate bookmark"
- "%sDonationStore: Failed to process added instances: %ld and removed instances: %ld. Error: %@"
- "%sDonationStore: Failed to render and chunk schematized record: %@"
- "%sDonationStore: Failed to retrieve item with identifier: %{private}s"
- "%sDonationStore: Failed to schematize donation %s: %@"
- "%sDonationStore: Failed to schematize remote donation %s: %@"
- "%sDonationStore: Force backfill complete"
- "%sDonationStore: Force backfill requested"
- "%sDonationStore: Ignoring duplicate request to startLiveListening"
- "%sDonationStore: Ignoring duplicate request to stopLiveListening"
- "%sDonationStore: Invariant violation — multiple remote schematizers produced a record for shared item %s. Only one remote schematizer should handle a given shared item."
- "%sDonationStore: Invariant violation — multiple schematizers produced a record for item %s. Only one schematizer should handle a given item."
- "%sDonationStore: Live listeners active"
- "%sDonationStore: Processing cascade data with identifier: %{private}s"
- "%sDonationStore: Processing donation: %s"
- "%sDonationStore: Processing remote donation: %s"
- "%sDonationStore: Processing status, invalid bookmark"
- "%sDonationStore: Raw changes%s"
- "%sDonationStore: Remove bookmark complete"
- "%sDonationStore: Remove bookmark requested"
- "%sDonationStore: Resolved changes for indexing %s"
- "%sDonationStore: Resolved changes for staleness%s"
- "%sDonationStore: Retrying in %ss"
- "%sDonationStore: Schematization broke provenance (deviceIdentifier)"
- "%sDonationStore: Schematization broke provenance (devicePlatform)"
- "%sDonationStore: Schematization broke provenance (itemInstanceUUID)"
- "%sDonationStore: Schematization broke provenance (sharedItemUUID)"
- "%sDonationStore: Schematization broke provenance (sourceItemUUID)"
- "%sDonationStore: Schematization returned nil for donation %s"
- "%sDonationStore: Schematization returned nil for remote donation %s"
- "%sDonationStore: Set processing attempt %ld failed: %@"
- "%sDonationStore: Set processing cancelled"
- "%sDonationStore: Set processing failed after exponential backoff. Final error: %@"
- "%sDonationStore: Skipping removal of: %s as an update will be coming."
- "%sDonationStore: Stopped live listeners"
- "%sDonationStore: Successfully deleted %ld items"
- "%sDonationStore: Successfully donated %ld items"
- "%sDonationStore: Warning: skipping remote items, no remote data schematizer"
- "%sDonationStore: cooldown(): document processing session warmup/cooldown failure"
- "%sDonationStore: createEmbeddings called"
- "%sDonationStore: createEmbeddings outcome for %{private}s: %s"
- "%sDonationStore: deleteEmbeddings: batch delete failed: %@"
- "%sDonationStore: deleteEmbeddings: item %{private}s already removed from Cascade, treating as already deleted"
- "%sDonationStore: deleteEmbeddings: set not found for %{private}s, nothing to delete"
- "%sDonationStore: deleteItems: batch delete failed: %@"
- "%sDonationStore: deleting %ld items"
- "%sDonationStore: document processing session warmup/cooldown failure"
- "%sDonationStore: forceBackfill() not supported"
- "%sDonationStore: index(items:) failed to create set key: %@"
- "%sDonationStore: performBackfill() not supported"
- "%sDonationStore: processingStatus() not supported"
- "%sDonationStore: removeBookmark() not supported"
- "%sDonationStore: startLiveListening() not supported"
- "%sDonationStore: startup task cancelled during backfill"
- "%sDonationStore: startup task completed backfill"
- "%sDonationStore: startup task failed to backfill: %@"
- "%sDonationStore: startup task performing backfill"
- "%sDonationStore: startup task starting live listeners"
- "%sDonationStore: stopLiveListening() not supported"
- "%sDonationStore: updateItems: batch update failed: %@"
- "%sDonationStore: updateItems: failed to create document cache retriever: %@"
- "%sDonationStore: updateItems: failed to retrieve item %{private}s: %@"
- "%sDonationStore: updateItems: item %{private}s not found in set"
- "%sDonationStore: updating %ld items"
- "%sDonationStore: warmup(): document processing session warmup/cooldown failure"
- "%{public}sDonationStore: Successfully donated %ld items"
- "',\n    $queryTerms,\n    prefix_search := "
- ") DETACH DELETE e;"
- "CALL show_tables() WHERE type = 'NODE' AND lower(name) <> lower('"
- "CNContainResolver:resolveContact: Could not resolve contact for identifier: %s. Error: %@. Falling back to nil"
- "Created new database for path: %{public}s"
- "Deleted all documents and chunks from database in %s"
- "Failed to mark preserved corrupt database as purgeable: %{public}@"
- "HybridIndex deinit for path: %{public}s"
- "HybridIndexMigrator: Found %ld previously applied migration(s) (latest: '%s' applied_at=%s), %ld pending."
- "HybridIndexMigrator: No previously applied migrations found, %ld pending."
- "IndexingServer.reset"
- "Preserved corrupt database marked as purgeable: %{public}s"
- "Started %sDonationStore"
- "Starting %sDonationStore"
- "Stopped %sDonationStore"
- "Stopping %sDonationStore"
- "Unable to mark file purgeable: %{public}s"
- "WHERE score >= $bm25Threshold"
- "[], prefix_search:= true, conjunctive := true, compute_bm25 := false, negated_terms := $"
- "applyMaxQoSIfChanged: unrecognized qos_class_t raw value %{public}u"
- "com_apple_mail_flagged"
- "com_apple_mail_read"
- "deleteAll"
- "embedQueryUsingSafety: starting embedding generation (timeout=%{public}s, checkSafety=%{bool,public}d)"
- "perform(text:checkSafety:safetyThreshold:embeddingModelProperties:contextLength:)"
- "performFTSRetrieval: bm25Threshold is not supported on the retrieval path (compute_bm25 is disabled); threshold will be ignored"
- "performFTSRetrieval: returning empty results"
- "prewarm(contextLength:)"
- "setAllThreadsQoS failed: %{public}@"
```
