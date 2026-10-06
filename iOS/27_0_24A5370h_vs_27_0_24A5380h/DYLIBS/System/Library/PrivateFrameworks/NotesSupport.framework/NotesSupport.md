## NotesSupport

> `/System/Library/PrivateFrameworks/NotesSupport.framework/NotesSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x54b94` | `0x55ce0` | **`+0x114c`** |
| `__DATA.__bss` | `0x800` | `0x570` | **`-0x290`** |
| `__DATA_DIRTY.__bss` | `0x4b1` | `0x741` | **`+0x290`** |
| `__TEXT.__oslogstring` | `0x3c26` | `0x3e86` | **`+0x260`** |
| `__DATA_DIRTY.__data` | `0x24c` | `0x418` | **`+0x1cc`** |
| `__AUTH.__data` | `0x1e8` | `0xa0` | **`-0x148`** |
| `__TEXT.__objc_methlist` | `0x4288` | `0x4378` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x5e38` | `0x5ed0` | **`+0x98`** |
| `__DATA.__data` | `0x784` | `0x6f4` | **`-0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x3110` | `0x3178` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x1328` | `0x1380` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x170` | `0x120` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x1220` | `0x1270` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1cf0` | `0x1d38` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x4420` | `0x4460` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x1660` | `0x16a0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x4549` | `0x4589` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0xea4` | `0xed8` | **`+0x34`** |
| `__DATA.__common` | `0x8` | `—` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x218` | `0x220` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x880` | `0x888` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-2991.0.0.0.0
+2996.0.0.0.0

-  Functions: 2512
-  Symbols:   3707
-  CStrings:  1018
+  Functions: 2539
+  Symbols:   3737
+  CStrings:  1031
Symbols:
+ -[ICBaseSearchIndexerDataSource indexingScope]
+ -[ICBaseSearchIndexerDataSource setIndexingScope:]
+ -[ICBaseSearchIndexerDataSource waitForPendingChangeProcessing]
+ -[ICCDCSIReindexer reindexAllSearchableItemsWithScope:completionHandler:]
+ -[ICIndexItemsOperation _indexBatchItemCount]
+ -[ICIndexItemsOperation _indexBatchMaxTotalSize]
+ -[ICIndexItemsOperation _resetContextForDataSourceIfNeededInExtension:]
+ -[ICReindexAllItemsOperation indexingScope]
+ -[ICReindexAllItemsOperation setIndexingScope:]
+ -[ICSearchIndexer _startObservingChangesOnIndexingQueue]
+ -[ICSearchIndexer determineIfReindexIsNeededFromClientStateWithCompletionHandler:]
+ -[ICSearchIndexer finishObservedChangesAndRemainingOperationsWithCompletionHandler:]
+ -[ICSearchIndexer indexPendingItemsWithCompletionHandler:]
+ -[ICSearchIndexer reindexAllSearchableItemsInIndex:scope:completionHandler:]
+ -[ICSearchIndexer reindexAllSearchableItemsWithScope:completionHandler:]
+ -[ICSearchIndexer startObservingChangesAndWait]
+ GCC_except_table28
+ GCC_except_table34
+ GCC_except_table41
+ GCC_except_table45
+ GCC_except_table53
+ GCC_except_table63
+ GCC_except_table68
+ GCC_except_table70
+ GCC_except_table71
+ _OBJC_IVAR_$_ICBaseSearchIndexerDataSource._indexingScope
+ _OBJC_IVAR_$_ICReindexAllItemsOperation._indexingScope
+ ___47-[ICSearchIndexer startObservingChangesAndWait]_block_invoke
+ ___58-[ICSearchIndexer indexPendingItemsWithCompletionHandler:]_block_invoke
+ ___63-[ICBaseSearchIndexerDataSource waitForPendingChangeProcessing]_block_invoke
+ ___71-[ICIndexItemsOperation _resetContextForDataSourceIfNeededInExtension:]_block_invoke
+ ___76-[ICSearchIndexer reindexAllSearchableItemsInIndex:scope:completionHandler:]_block_invoke
+ ___82-[ICSearchIndexer determineIfReindexIsNeededFromClientStateWithCompletionHandler:]_block_invoke
+ ___84-[ICSearchIndexer finishObservedChangesAndRemainingOperationsWithCompletionHandler:]_block_invoke
+ ___84-[ICSearchIndexer finishObservedChangesAndRemainingOperationsWithCompletionHandler:]_block_invoke_2
+ ___block_descriptor_42_e8_32s_e17_v16?0"NSError"8ls32l8
+ ___block_descriptor_48_e8_32s40bs_e28_v24?0"NSData"8"NSError"16ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
+ _kICReindexAttachmentsOnLaunchKey
- -[ICSearchIndexer reindexAllSearchableItemsInIndex:completionHandler:]
- GCC_except_table13
- GCC_except_table36
- GCC_except_table51
- GCC_except_table56
- GCC_except_table59
- GCC_except_table69
- ___70-[ICSearchIndexer reindexAllSearchableItemsInIndex:completionHandler:]_block_invoke
- ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
CStrings:
+ "Client state from CoreSpotlight does not match defaults; reindex needed"
+ "Deferring large object %@ from in-extension indexing to avoid jetsam; the app will index it on next launch."
+ "Error fetching client state from CoreSpotlight: %@; assuming reindex needed"
+ "Finished indexing pending items, error: %@"
+ "Finished observed changes and remaining indexing operations"
+ "ICAttachment"
+ "Indexing %lu pending item(s) with a regular indexing operation"
+ "No client state in CoreSpotlight; reindex needed"
+ "No client state in defaults; reindex needed"
+ "No pending items to index"
+ "ReindexAttachmentsOnLaunch"
+ "Search indexing disabled. Not indexing pending items."
+ "Staging data source %@ for reindexing in operation %@ (scope %lu)"
+ "v24@?0@\"NSData\"8@\"NSError\"16"
- "Staging data source %@ for reindexing in operation %@"
```
