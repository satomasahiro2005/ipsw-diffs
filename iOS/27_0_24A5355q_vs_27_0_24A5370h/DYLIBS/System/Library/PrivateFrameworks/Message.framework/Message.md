## Message

> `/System/Library/PrivateFrameworks/Message.framework/Message`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xad9b50` | `0xae1880` | **`+0x7d30`** |
| `__AUTH_CONST.__const` | `0xaa0b0` | `0xaaab0` | **`+0xa00`** |
| `__TEXT.__swift5_capture` | `0x32888` | `0x32c9c` | **`+0x414`** |
| `__TEXT.__oslogstring` | `0x276a0` | `0x277f0` | **`+0x150`** |
| `__AUTH_CONST.__objc_const` | `0x22bf8` | `0x22cb0` | **`+0xb8`** |
| `__TEXT.__gcc_except_tab` | `0x36b38` | `0x36be0` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x31226` | `0x312c6` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x185c8` | `0x18660` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x1e828` | `0x1e8b0` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0x1434c` | `0x143c4` | **`+0x78`** |
| `__DATA.__bss` | `0x52da0` | `0x52d30` | **`-0x70`** |
| `__TEXT.__const` | `0x6ade8` | `0x6ae58` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0xf180` | `0xf120` | **`-0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xb7d0` | `0xb808` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x10998` | `0x10966` | **`-0x32`** |
| `__DATA.__data` | `0xe708` | `0xe738` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x40c0` | `0x40e8` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0xd34` | `0xd5c` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x18640` | `0x18660` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x1cc0` | `0x1cd8` | **`+0x18`** |
| `__AUTH.__data` | `0xb1c8` | `0xb1b8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x2ee8` | `0x2ef8` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x520` | `0x530` | **`+0x10`** |
| `__DATA.__common` | `0xeb9` | `0xeb1` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xd824` | `0xd82c` | **`+0x8`** |
| `__TEXT.__swift5_fieldmd` | `0x151b8` | `0x151b0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1380` | `0x1384` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x29d8` | `0x29d4` | **`-0x4`** |

### Other Changes

```diff

-3891.100.17.2.4
+3893.100.7.0.0

-  Functions: 47962
+  Functions: 48072

-  CStrings:  8491
+  CStrings:  8496
Symbols:
+ -[MFAttachment fetchFileWrapperAsynchronously:inAttachmentContext:]
+ -[MFMailMessageLibrary _writeEmlxData:toFile:protectionClass:purgeable:dateReceived:]
+ -[MFMailMessageLibrary _writeEmlxFile:withData:protectionClass:purgeable:dateReceived:]
+ -[MFMailMessageLibrary _writeEmlxFileOfType:forAccount:toDirectory:withData:protectionClass:dateReceived:]
+ -[MFSearchableIndexManager_iOS downloadStatisticsPersistence]
+ _OBJC_CLASS_$_EDAddResetSearchIndexReasonColumn
+ _OBJC_CLASS_$_EDResetSpotlightIndexStateUpgradeStep
+ _OBJC_IVAR_$_MFSearchableIndexManager_iOS._downloadStatisticsPersistence
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_EDSearchableIndexHookResponder
+ __OBJC_$_PROTOCOL_METHOD_TYPES_EDSearchableIndexHookResponder
+ __OBJC_$_PROTOCOL_REFS_EDSearchableIndexHookResponder
+ __OBJC_LABEL_PROTOCOL_$_EDSearchableIndexHookResponder
+ __OBJC_PROTOCOL_$_EDSearchableIndexHookResponder
+ __ZNKSt3__114default_deleteIA_11DetailEntryEclB9fqe220106IS1_Li0EEEvPT_
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__113unordered_mapIPKc8Encoding20CStringAlnumCaseHash21CStringAlnumCaseEqualNS_9allocatorINS_4pairIKS2_S3_EEEEED1B9fqe220106Ev
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIPKc8EncodingEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S4_EE20CStringAlnumCaseHash21CStringAlnumCaseEqualEENS_21__unordered_map_equalIS3_S9_SB_SA_EENS_9allocatorIS9_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJOS3_EEENSM_IJEEEEEENS7_INS_15__hash_iteratorIPNS_11__hash_nodeIS5_PvEEEEbEEDpOT_ENKUlRS8_SL_OSO_OSP_E_clES10_SL_S11_S12_
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIPKc8EncodingEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S4_EE20CStringAlnumCaseHash21CStringAlnumCaseEqualEENS_21__unordered_map_equalIS3_S9_SB_SA_EENS_9allocatorIS9_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS8_EEENSM_IJEEEEEENS7_INS_15__hash_iteratorIPNS_11__hash_nodeIS5_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
+ ___67-[MFAttachment fetchFileWrapperAsynchronously:inAttachmentContext:]_block_invoke
+ ___67-[MFAttachment fetchFileWrapperAsynchronously:inAttachmentContext:]_block_invoke_2
+ __resetIndexedBodiesForBackfill
+ _associated conformance 16IMAP2Persistence11SyncRequestV4KindO08BackFillE0OSHAASQ
+ _associated conformance 7Message10CheckpointOSHAASQ
+ _associated conformance So38MFBackFillingMessageBodyDownloadStatusVSHSCSQ
+ _log2
+ _symbolic Say_____G So38MFBackFillingMessageBodyDownloadStatusV
+ _symbolic Sayy_____cG So38MFBackFillingMessageBodyDownloadStatusV
+ _symbolic _____ 16IMAP2Persistence11SyncRequestV4KindO08BackFillE0O
+ _symbolic _____ 7Message10CheckpointO
+ _symbolic _____ So36MFBackFillingMessageBodyDownloadKindV
+ _symbolic _____ So38MFBackFillingMessageBodyDownloadStatusV
+ _symbolic _____Iegy_ So38MFBackFillingMessageBodyDownloadStatusV
+ _symbolic _____Sg So38MFBackFillingMessageBodyDownloadStatusV
+ _symbolic __________Iegyy_ So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC2IDV So0a7FillingcD14DownloadStatusV
+ _symbolic _____ySayy_____cGG s16IndexingIteratorV So38MFBackFillingMessageBodyDownloadStatusV
+ _symbolic _____ytIegnr_ So38MFBackFillingMessageBodyDownloadStatusV
+ _symbolic y___________tc 7Message9AccountID33_8C94728D29B9D9CACC7F5FFB5564322BLLV So013MFBackFillingA18BodyDownloadStatusV
+ _symbolic y_____c So38MFBackFillingMessageBodyDownloadStatusV
- -[MFMailMessageLibrary _writeEmlxData:toFile:protectionClass:purgeable:]
- -[MFMailMessageLibrary _writeEmlxFile:withData:protectionClass:purgeable:]
- -[MFMailMessageLibrary _writeEmlxFileOfType:forAccount:toDirectory:withData:protectionClass:]
- -[MFPersistenceDatabase_iOS mailMessageLibraryMigratorScheduleSpotlightReindex:]
- _EDSearchableIndexSchedulerActivityTypeBudgeted
- _EDSearchableIndexSchedulerActivityTypeMaintenance
- _EMPersistenceStatisticsKeyIndexPaused
- _EMPersistenceStatisticsKeyIndexingEnabledForBudgeted
- _EMPersistenceStatisticsKeyIndexingEnabledForMaintenance
- _EMPersistenceStatisticsKeyMessagesInLargestRemoteAccount
- _EMPersistenceStatisticsKeyRemoteMessagesToIndex
- __ZNKSt3__114default_deleteIA_11DetailEntryEclB9fqe220100IS1_Li0EEEvPT_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__113unordered_mapIPKc8Encoding20CStringAlnumCaseHash21CStringAlnumCaseEqualNS_9allocatorINS_4pairIKS2_S3_EEEEED1B9fqe220100Ev
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIPKc8EncodingEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S4_EE20CStringAlnumCaseHash21CStringAlnumCaseEqualEENS_21__unordered_map_equalIS3_S9_SB_SA_EENS_9allocatorIS9_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJOS3_EEENSM_IJEEEEEENS7_INS_15__hash_iteratorIPNS_11__hash_nodeIS5_PvEEEEbEEDpOT_ENKUlRS8_SL_OSO_OSP_E_clES10_SL_S11_S12_
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIPKc8EncodingEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S4_EE20CStringAlnumCaseHash21CStringAlnumCaseEqualEENS_21__unordered_map_equalIS3_S9_SB_SA_EENS_9allocatorIS9_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS8_EEENSM_IJEEEEEENS7_INS_15__hash_iteratorIPNS_11__hash_nodeIS5_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
- ___47-[MFAttachment fetchFileWrapperAsynchronously:]_block_invoke
- ___47-[MFAttachment fetchFileWrapperAsynchronously:]_block_invoke_2
- _associated conformance 15IMAP2Connection0B13ConfigurationV21SourceApplicationKindOSHAASQ
- _associated conformance 16IMAP2Persistence11SyncRequestV4KindO15BackFillPurposeOSHAASQ
- _associated conformance 16IMAP2Persistence23ConnectionConfigurationV21SourceApplicationKindOSHAASQ
- _associated conformance So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC6StatusOSHACSQ
- _swift_release_x11
- _symbolic Say_____G So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC6StatusO
- _symbolic Sayy_____cG So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC6StatusO
- _symbolic So12BGSystemTaskC_____Ieggy_ So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC6StatusO
- _symbolic _____ 15IMAP2Connection0B13ConfigurationV21SourceApplicationKindO
- _symbolic _____ 16IMAP2Persistence11SyncRequestV4KindO15BackFillPurposeO
- _symbolic _____ 16IMAP2Persistence23ConnectionConfigurationV21SourceApplicationKindO
- _symbolic _____ So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC6StatusO
- _symbolic _____7purpose_t 16IMAP2Persistence11SyncRequestV4KindO15BackFillPurposeO
- _symbolic _____Iegy_ So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC6StatusO
- _symbolic _____Sg So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC6StatusO
- _symbolic __________Iegyy_ So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC2IDV AF6StatusO
- _symbolic _____ySayy_____cGG s16IndexingIteratorV So30MFBackFillMessageBodySchedulerC0E0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC6StatusO
- _symbolic _____ytIegnr_ So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC6StatusO
- _symbolic _____z_Xx 7Message12BackFillInfo33_8C94728D29B9D9CACC7F5FFB5564322BLLV
- _symbolic y_____c So30MFBackFillMessageBodySchedulerC0C0E8Activity33_8C94728D29B9D9CACC7F5FFB5564322BLLC6StatusO
CStrings:
+ "%hx: %ld out of %ld are still running after %ld minute(s): %{public}s"
+ "%hx: All %ld requests completed. Aggregate status: %{public}d. Firing %ld completion handlers."
+ "%hx: Completed with status: %{public}d"
+ "%hx: Failed to set completion status to %{public}d"
+ "2 years"
+ "BOOL _writeDataHolderForMessageAndPart(MFMailMessageLibrary *__strong, EDPersistenceDatabaseConnection *__strong, EMDatabaseID, EMGlobalMessageID, NSString *__strong, NSString *__strong, MFDataHolder *__strong, BOOL, BOOL, MailAccount *__strong, NSDate *__strong)"
+ "Error adding source column to indexing_analytics_dropped_index_events: %{public}@"
+ "Error resetting spotlight index state: %{public}@"
+ "Finished database query for newest undonated message date"
+ "Indexing message %@ (data: %{iec-bytes}ld, is persisted? %{bool}d)"
+ "RaveAddIndexStatusFieldsToProgressStatistics"
+ "RaveResetIndexedBodiesForBackfill"
+ "Resetting message_body_indexed for backfill"
+ "SELECT COUNT(*) AS indexable_messages,       SUM(CASE WHEN messages.searchable_message IS NOT NULL then 1 ELSE 0 END) as indexed_messages       FROM messages LEFT OUTER JOIN searchable_messages ON messages.searchable_message = searchable_messages.ROWID       WHERE deleted = '0' AND (date_received > unixepoch('now','start of day','-%lu days')) %@"
+ "Searchable index is resetting"
+ "Starting database query for newest undonated message date"
+ "UPDATE searchable_messages SET message_body_indexed = 0 WHERE message_body_indexed = 1 AND message IN (SELECT ROWID FROM messages WHERE date_received >= %lld AND date_received < %lld AND mailbox IN (SELECT ROWID FROM mailboxes WHERE %s));"
+ "[%.*hhx-%.*X] Canceling back-fill sync because server is unavailable (sync: #%u, id: %hu)."
+ "[%.*hhx-%.*X] Completing back-fill sync (sync: #%u, id: %hu, isOverQuota: %{bool}d."
+ "[%{public}s] Completed with status %{public}s."
+ "[%{public}s] Server unavailable (consecutive: %ld); deferring %ld min."
+ "backFill(purpose: "
+ "mime-attachment"
+ "overQuota"
+ "updateStages(_:)"
+ "url LIKE 'imap://%q/%%'"
+ "user-initiated"
- "%hx: %ld out of %ld are still running after %ld minute(s): %s"
- "%hx: All %ld requests completed. Aggregate status: %{public}s. Firing %ld completion handlers."
- "%hx: Completed with status: %{public}s"
- "%hx: Failed to set completion status to %{public}s"
- "BOOL _writeDataHolderForMessageAndPart(MFMailMessageLibrary *__strong, EDPersistenceDatabaseConnection *__strong, EMDatabaseID, EMGlobalMessageID, NSString *__strong, NSString *__strong, MFDataHolder *__strong, BOOL, BOOL, MailAccount *__strong)"
- "Deferring initial sync."
- "Did complete."
- "Did defer."
- "Did fail."
- "Encounted an error. Deferring initial sync.."
- "Finished database query for messages to reindex"
- "Indexing message %@ data: %{iec-bytes}ld"
- "Initial backfill is complete."
- "Nothing to do."
- "SELECT COUNT(*) AS indexable_messages,       SUM(CASE WHEN messages.searchable_message IS NULL THEN 1 ELSE 0 END) AS messages_to_index,       SUM(CASE WHEN messages.searchable_message IS NOT NULL then 1 ELSE 0 END) as indexed_messages       FROM messages LEFT OUTER JOIN searchable_messages ON messages.searchable_message = searchable_messages.ROWID       WHERE deleted = '0' AND (date_received > unixepoch('now','start of day','-%lu days')) %@"
- "SELECT MAX(messages.date_received)   FROM messages WHERE messages.deleted = '0'        AND messages.searchable_message IS NULL        AND messages.date_received <= unixepoch('now', '-1 day') %@"
- "Starting database query for messages to reindex"
- "[%.*hhx-%.*X] Completing back-fill sync (sync: #%u, id: %hu)."
- "backFillMessageBodies"
- "backFillMessageBodies(purpose: "
- "error"
- "noWork"
```
