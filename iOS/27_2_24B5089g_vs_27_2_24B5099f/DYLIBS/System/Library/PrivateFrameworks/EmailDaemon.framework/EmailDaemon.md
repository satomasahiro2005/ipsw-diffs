## EmailDaemon

> `/System/Library/PrivateFrameworks/EmailDaemon.framework/EmailDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x1aa0` | `0x4bc0` | **`+0x3120`** |
| `__DATA.__data` | `0x3a10` | `0xcf0` | **`-0x2d20`** |
| `__TEXT.__text` | `0x297ce0` | `0x2999bc` | **`+0x1cdc`** |
| `__AUTH.__objc_data` | `0xcd8` | `—` | **`-0xcd8`** |
| `__DATA_DIRTY.__objc_data` | `0x5c28` | `0x6900` | **`+0xcd8`** |
| `__AUTH.__data` | `0x390` | `—` | **`-0x390`** |
| `__DATA.__bss` | `0x6990` | `0x67e0` | **`-0x1b0`** |
| `__DATA_DIRTY.__bss` | `0x1b98` | `0x1d38` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x2976a` | `0x2989a` | **`+0x130`** |
| `__TEXT.__gcc_except_tab` | `0x4aed4` | `0x4afc0` | **`+0xec`** |
| `__AUTH_CONST.__objc_const` | `0x228d0` | `0x229a0` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x114d8` | `0x11560` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0x13634` | `0x136b4` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x1b614` | `0x1b684` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0x7c03` | `0x7c58` | **`+0x55`** |
| `__TEXT.__swift5_typeref` | `0x1856` | `0x18a2` | **`+0x4c`** |
| `__AUTH_CONST.__cfstring` | `0xff60` | `0xffa0` | **`+0x40`** |
| `__TEXT.__const` | `0x53cc` | `0x53fc` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xb380` | `0xb3a8` | **`+0x28`** |
| `__DATA_CONST.__objc_protolist` | `0x430` | `0x450` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x880` | `0x89c` | **`+0x1c`** |
| `__DATA_CONST.__objc_protorefs` | `0x128` | `0x140` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1490` | `0x149c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1820` | `0x1828` | **`+0x8`** |

### Other Changes

```diff

-3901.200.41.0.0
+3901.200.66.2.1

-  Functions: 11686
-  Symbols:   15306
-  CStrings:  5539
+  Functions: 11707
+  Symbols:   15331
+  CStrings:  5546
Symbols:
+ +[EDFoundationModelContextGenerator originalContentMessageForMessage:limitOfInReplyToAncestors:condenseEmptyLines:messagePersistence:htmlStringFromMessage:error:]
+ -[EDDiagnosticInfoGatherer _copyIndexingDiagnosticsDatabaseIntoDirectoryURL:options:completionPromise:]
+ -[EDDiagnosticInfoGatherer _shouldCollectIndexingDiagnostics:]
+ -[EDMessageChangeManager hasCompletedInitialSyncForMailboxURL:]
+ -[EDPersistenceDatabaseConnection rowIDPropertyForKey:]
+ -[EDPersistenceDatabaseConnection selectLowestUnresolvedAttachmentID]
+ -[EDPersistenceDatabaseConnection setLowestUnresolvedAttachmentID:]
+ -[EDPersistenceDatabaseConnection setRowIDProperty:forKey:]
+ -[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:lastVisitedAttachmentID:lowestUnresolvedAttachmentID:cancelationToken:]
+ -[EDSearchableIndexPersistence _noteLowestUnresolvedAttachmentID:]
+ -[EDSearchableIndexPersistence _rewindAttachmentScanToRetryUnresolvedAttachments]
+ -[EDSearchableIndexPersistence lowestUnresolvedAttachmentID]
+ -[EDSearchableIndexPersistence setLowestUnresolvedAttachmentID:]
+ _OBJC_IVAR_$_EDSearchableIndexPersistence._lastAttachmentScanRewindDate
+ _OBJC_IVAR_$_EDSearchableIndexPersistence._lowestUnresolvedAttachmentID
+ _OBJC_IVAR_$_EDSearchableIndexPersistence._lowestUnresolvedAttachmentIDLock
+ __OBJC_$_INSTANCE_METHODS_EDMessageChangeManager(Swift)
+ __OBJC_$_PROP_LIST_EDServerSyncedMessage
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_EDServerSyncedMessage
+ __OBJC_$_PROTOCOL_METHOD_TYPES_EDServerSyncedMessage
+ __OBJC_$_PROTOCOL_REFS_EDServerSyncedMessage
+ __OBJC_LABEL_PROTOCOL_$_EDServerSyncedMessage
+ __OBJC_PROTOCOL_$_EDServerSyncedMessage
+ ___103-[EDDiagnosticInfoGatherer _copyIndexingDiagnosticsDatabaseIntoDirectoryURL:options:completionPromise:]_block_invoke
+ ___143-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:lastVisitedAttachmentID:lowestUnresolvedAttachmentID:cancelationToken:]_block_invoke
+ ___143-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:lastVisitedAttachmentID:lowestUnresolvedAttachmentID:cancelationToken:]_block_invoke_2
+ ___143-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:lastVisitedAttachmentID:lowestUnresolvedAttachmentID:cancelationToken:]_block_invoke_3
+ ___143-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:lastVisitedAttachmentID:lowestUnresolvedAttachmentID:cancelationToken:]_block_invoke_4
+ ___162+[EDFoundationModelContextGenerator originalContentMessageForMessage:limitOfInReplyToAncestors:condenseEmptyLines:messagePersistence:htmlStringFromMessage:error:]_block_invoke
+ ___60-[EDSearchableIndexPersistence lowestUnresolvedAttachmentID]_block_invoke
+ ___64-[EDSearchableIndexPersistence setLowestUnresolvedAttachmentID:]_block_invoke
+ ___85-[EDPersistenceDatabaseConnection(EDSearchableIndexPersistence) rowIDPropertyForKey:]_block_invoke
+ ___block_descriptor_72_ea8_32s40s48s56s64r_e53_v20?0"EDSearchableIndexAttachmentItemMetadatum"8B16ls32l8s40l8s48l8r64l8s56l8
+ _flat unique So21EDServerSyncedMessage_p
+ _swift_dynamicCastObjCProtocolConditional
+ _symbolic Say______pG So21EDServerSyncedMessageP
+ _symbolic So22EDMessageChangeManagerC
+ _symbolic ______p So21EDServerSyncedMessageP
- +[EDFoundationModelContextGenerator originalContentMessageForMessage:limitOfInReplyToAncestors:checkForForwardedMessages:condenseEmptyLines:messagePersistence:htmlStringFromMessage:error:]
- -[EDDiagnosticInfoGatherer _copyIndexingDiagnosticsDatabaseIntoDirectoryURL:completionPromise:]
- -[EDDiagnosticInfoGatherer _shouldCollectIndexingDiagnostics]
- -[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:cancelationToken:]
- __OBJC_$_INSTANCE_METHODS_EDMessageChangeManager
- ___188+[EDFoundationModelContextGenerator originalContentMessageForMessage:limitOfInReplyToAncestors:checkForForwardedMessages:condenseEmptyLines:messagePersistence:htmlStringFromMessage:error:]_block_invoke
- ___90-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:cancelationToken:]_block_invoke
- ___90-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:cancelationToken:]_block_invoke_2
- ___90-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:cancelationToken:]_block_invoke_3
- ___90-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:cancelationToken:]_block_invoke_4
- ___95-[EDDiagnosticInfoGatherer _copyIndexingDiagnosticsDatabaseIntoDirectoryURL:completionPromise:]_block_invoke
- ___96-[EDPersistenceDatabaseConnection(EDSearchableIndexPersistence) selectLastProcessedAttachmentID]_block_invoke
- ___block_descriptor_64_ea8_32s40s48s56s_e53_v20?0"EDSearchableIndexAttachmentItemMetadatum"8B16ls32l8s40l8s48l8s56l8
CStrings:
+ "-[EDMessageChangeManager hasCompletedInitialSyncForMailboxURL:]"
+ "-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:lastVisitedAttachmentID:lowestUnresolvedAttachmentID:cancelationToken:]"
+ "-[EDSearchableIndexPersistence lowestUnresolvedAttachmentID]"
+ "-[EDSearchableIndexPersistence setLowestUnresolvedAttachmentID:]"
+ "DELETE FROM properties WHERE key = :key"
+ "Reached the end of the attachment table, rewinding indexing cursor to %lld to retry attachments whose data was missing"
+ "SELECT ma.ROWID, m.ROWID, ma.mime_part_number, ma.name, m.mailbox FROM messages AS m LEFT OUTER JOIN message_attachments AS ma ON (ma.global_message_id = m.global_message_id) LEFT OUTER JOIN searchable_attachments AS s ON (ma.ROWID = s.attachment_id) WHERE ma.ROWID > %lld AND s.attachment_id IS NULL AND ma.attachment IS NOT NULL ORDER BY ma.ROWID"
+ "Selecting %@ property"
+ "Setting %@ property"
+ "com.apple.mail.IMAP.newMessageLatency"
+ "com.apple.mail.searchableIndex.lowestUnresolvedAttachmentIDKey"
+ "\xb1"
- "-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:cancelationToken:]"
- "Replying to forwarded message, failed to generate any original-content messages"
- "SELECT ma.ROWID, m.ROWID, ma.mime_part_number, ma.name, m.mailbox FROM messages AS m LEFT OUTER JOIN message_attachments AS ma ON (ma.global_message_id = m.global_message_id) LEFT OUTER JOIN searchable_attachments AS s ON (ma.ROWID = s.attachment_id) WHERE ma.ROWID > %lld AND s.attachment_id IS NULL AND ma.attachment IS NOT NULL ORDER BY m.ROWID"
- "Setting latest value for lastProcessAttachmentID"
- "\x81"
```
