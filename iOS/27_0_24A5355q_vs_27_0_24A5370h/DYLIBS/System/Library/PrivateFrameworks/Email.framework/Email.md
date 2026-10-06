## Email

> `/System/Library/PrivateFrameworks/Email.framework/Email`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd28a0` | `0xd3e58` | **`+0x15b8`** |
| `__TEXT.__cstring` | `0xbc8f` | `0xc0cf` | **`+0x440`** |
| `__TEXT.__gcc_except_tab` | `0x1ab90` | `0x1ad64` | **`+0x1d4`** |
| `__TEXT.__unwind_info` | `0x7f38` | `0x8008` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0xcf34` | `0xcfac` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x6513` | `0x6583` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x4530` | `0x4598` | **`+0x68`** |
| `__AUTH_CONST.__cfstring` | `0xa3a0` | `0xa360` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x16d48` | `0x16d88` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x6208` | `0x6248` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0xb00` | `0xb20` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x1b90` | `0x1bb0` | **`+0x20`** |
| `__DATA.__data` | `0x2990` | `0x2978` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0xc34` | `0xc44` | **`+0x10`** |

### Other Changes

```diff

-3891.100.17.2.4
+3893.100.7.0.0

-  Functions: 5004
-  Symbols:   8865
-  CStrings:  2118
+  Functions: 5026
+  Symbols:   8894
+  CStrings:  2130
Symbols:
+ -[EMActivity mailboxObjectID]
+ -[EMDaemonInterface interactiveDiagnosticInfoGatherer]
+ -[EMDiagnosticInfoGatherer gatherIndexingDiagnosticsWithRedaction:includeHDBStatus:completionHandler:]
+ -[EMMessageRepository _fetchMessagesForObjectIDs:requestID:promiseForObjectID:completionHandler:]
+ -[EMMessageRepository _messagePromiseForObjectID:]
+ -[EMMessageRepository messagesForObjectIDs:]
+ -[EMUbiquitouslyPersistedDictionary _currentInitialMergeSnapshot]
+ -[EMUbiquitouslyPersistedDictionary _invalidateInitialMergeSnapshot]
+ -[EMUbiquitouslyPersistedDictionary _logAndWritePlistAfterMergeWithChanges:]
+ -[EMUbiquitouslyPersistedDictionary _mergeRemotelyChangedKeys:]
+ -[EMUbiquitouslyPersistedDictionary _performFullCloudMerge]
+ -[EMUbiquitouslyPersistedDictionary _scheduleKVStoreSynchronize]
+ -[EMUbiquitouslyPersistedDictionary _waitForPendingMutationsForTesting]
+ -[EMUbiquitouslyPersistedDictionary dealloc]
+ -[EMUbiquitouslyPersistedDictionary synchronizeQueue]
+ -[NSURL(EMNSURLAdditions) em_documentID]
+ GCC_except_table181
+ GCC_except_table183
+ GCC_except_table195
+ GCC_except_table196
+ GCC_except_table197
+ GCC_except_table200
+ GCC_except_table201
+ GCC_except_table202
+ GCC_except_table204
+ GCC_except_table214
+ GCC_except_table216
+ GCC_except_table219
+ GCC_except_table224
+ GCC_except_table236
+ GCC_except_table237
+ GCC_except_table239
+ GCC_except_table242
+ GCC_except_table243
+ GCC_except_table249
+ _EMUserDefaultQueryEntitiesByStableID
+ _OBJC_IVAR_$_EMActivity._mailboxObjectID
+ _OBJC_IVAR_$_EMDaemonInterface._interactiveDiagnosticInfoGatherer
+ _OBJC_IVAR_$_EMUbiquitouslyPersistedDictionary._initialMergeSnapshot
+ _OBJC_IVAR_$_EMUbiquitouslyPersistedDictionary._synchronizeQueue
+ ___44-[EMMessageRepository messagesForObjectIDs:]_block_invoke
+ ___44-[EMMessageRepository messagesForObjectIDs:]_block_invoke_2
+ ___44-[EMMessageRepository messagesForObjectIDs:]_block_invoke_3
+ ___59-[EMUbiquitouslyPersistedDictionary _performFullCloudMerge]_block_invoke
+ ___64-[EMUbiquitouslyPersistedDictionary _scheduleKVStoreSynchronize]_block_invoke
+ ___71-[EMUbiquitouslyPersistedDictionary _waitForPendingMutationsForTesting]_block_invoke
+ ___85-[EMUbiquitouslyPersistedDictionary initWithPlistPath:identifier:encrypted:delegate:]_block_invoke
+ ___97-[EMMessageRepository _fetchMessagesForObjectIDs:requestID:promiseForObjectID:completionHandler:]_block_invoke
+ ___97-[EMMessageRepository _fetchMessagesForObjectIDs:requestID:promiseForObjectID:completionHandler:]_block_invoke_2
+ ___97-[EMMessageRepository _fetchMessagesForObjectIDs:requestID:promiseForObjectID:completionHandler:]_block_invoke_3
+ ___block_descriptor_40_ea8_32s_e31_"EFPromise"16?0"EMObjectID"8ls32l8
+ ___block_descriptor_40_ea8_32s_e38_v32?0"EMObjectID"8"EFPromise"16^B24ls32l8
+ ___block_descriptor_48_ea8_32s40bs_e36_v32?0"EMObjectID"8"NSError"16^B24ls32l8s40l8
+ ___block_descriptor_48_ea8_32s40s_e39_v32?0"NSString"8"NSDictionary"16^B24ls32l8s40l8
+ ___block_descriptor_56_ea8_32s40bs48bs_e34_v24?0"NSArray"8"NSDictionary"16ls32l8s40l8s48l8
+ ___block_descriptor_56_ea8_32s40s48s_e30_"EFFuture"16?0"EMObjectID"8ls32l8s40l8s48l8
+ __errorForMissedObjectID
- -[EMDiagnosticInfoGatherer gatherIndexingDiagnosticsWithRedaction:completionHandler:]
- -[EMUbiquitouslyPersistedDictionary _mergeKVStoreChangedKeys:]
- GCC_except_table175
- GCC_except_table176
- GCC_except_table177
- GCC_except_table178
- GCC_except_table179
- GCC_except_table182
- GCC_except_table184
- GCC_except_table192
- GCC_except_table205
- GCC_except_table208
- GCC_except_table213
- GCC_except_table215
- GCC_except_table225
- GCC_except_table228
- GCC_except_table238
- _EMPersistenceStatisticsKeyIndexPaused
- _EMPersistenceStatisticsKeyIndexableRemoteAttachments
- _EMPersistenceStatisticsKeyIndexingEnabledForBudgeted
- _EMPersistenceStatisticsKeyIndexingEnabledForMaintenance
- _EMPersistenceStatisticsKeyMessagesInLargestRemoteAccount
- _EMPersistenceStatisticsKeyRemoteAttachmentsIndexed
- _EMPersistenceStatisticsKeyRemoteAttachmentsToIndex
- _EMPersistenceStatisticsKeyRemoteMessagesToIndex
- ___62-[EMUbiquitouslyPersistedDictionary _mergeKVStoreChangedKeys:]_block_invoke
- ___block_descriptor_48_ea8_32s40r_e39_v32?0"NSString"8"NSDictionary"16^B24ls32l8r40l8
- ___block_descriptor_56_ea8_32s40s_e34_v24?0"NSArray"8"NSDictionary"16ls32l8s40l8
CStrings:
+ "%@.synchronize"
+ "-[EMMessageRepository messagesForObjectIDs:]"
+ "@\"EFPromise\"16@?0@\"EMObjectID\"8"
+ "EMActivity.m"
+ "EMActivityMailboxObjectIDKey is immutable after init"
+ "Invalid object ID type"
+ "QueryEntitiesByStableID"
+ "Request finished"
+ "Requesting messages %{public, name=count}u"
+ "Time window in search-indexing status text, e.g. 'Some results older than 1 month may not appear…'."
+ "Time window in search-indexing status text, e.g. 'Some results older than 1 week may not appear…'."
+ "Time window in search-indexing status text, e.g. 'Some results older than 1 year may not appear…'."
+ "Time window in search-indexing status text, e.g. 'Some results older than 2 months may not appear…'."
+ "Time window in search-indexing status text, e.g. 'Some results older than 2 weeks may not appear…'."
+ "Time window in search-indexing status text, e.g. 'Some results older than 2 years may not appear…'."
+ "Time window in search-indexing status text, e.g. 'Some results older than 3 months may not appear…'."
+ "Time window in search-indexing status text, e.g. 'Some results older than 3 weeks may not appear…'."
+ "Time window in search-indexing status text, e.g. 'Some results older than 5 years may not appear…'."
+ "Time window in search-indexing status text, e.g. 'Some results older than 6 months may not appear…'."
+ "document"
- "indexableRemoteAttachments"
- "indexingEnabledForBudgeted"
- "indexingEnabledForMaintenance"
- "indexingPaused"
- "messagesinLargestRemoteAccount"
- "remoteAttachmentsIndexed"
- "remoteAttachmentsToIndex"
- "remoteMessagesToIndex"
```
