## EmailDaemon

> `/System/Library/PrivateFrameworks/EmailDaemon.framework/EmailDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27f6c0` | `0x283180` | **`+0x3ac0`** |
| `__TEXT.__gcc_except_tab` | `0x4a0c8` | `0x499d8` | **`-0x6f0`** |
| `__TEXT.__cstring` | `0x27eea` | `0x283aa` | **`+0x4c0`** |
| `__AUTH_CONST.__cfstring` | `0xfc60` | `0xf940` | **`-0x320`** |
| `__AUTH_CONST.__const` | `0x7013` | `0x728b` | **`+0x278`** |
| `__TEXT.__objc_methlist` | `0x1342c` | `0x131dc` | **`-0x250`** |
| `__TEXT.__eh_frame` | `0x12e8` | `0x14d0` | **`+0x1e8`** |
| `__AUTH_CONST.__objc_const` | `0x225d8` | `0x22408` | **`-0x1d0`** |
| `__TEXT.__oslogstring` | `0x1a99f` | `0x1aaef` | **`+0x150`** |
| `__DATA_CONST.__objc_selrefs` | `0xb108` | `0xafd0` | **`-0x138`** |
| `__TEXT.__unwind_info` | `0x11030` | `0x10f00` | **`-0x130`** |
| `__AUTH.__objc_data` | `0x15c0` | `0x16e8` | **`+0x128`** |
| `__TEXT.__swift5_capture` | `0x618` | `0x6fc` | **`+0xe4`** |
| `__DATA.__data` | `0x3bd0` | `0x3ca0` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0x167b` | `0x1733` | **`+0xb8`** |
| `__TEXT.__const` | `0x503c` | `0x50ec` | **`+0xb0`** |
| `__DATA.__bss` | `0x66c0` | `0x6740` | **`+0x80`** |
| `__DATA_DIRTY.__objc_data` | `0x5068` | `0x4ff8` | **`-0x70`** |
| `__DATA_DIRTY.__data` | `0x1110` | `0x1170` | **`+0x60`** |
| `__AUTH.__data` | `0x788` | `0x7e0` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x1020` | `0x1060` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x15bc` | `0x15f4` | **`+0x38`** |
| `__DATA_DIRTY.__bss` | `0x1b10` | `0x1ae0` | **`-0x30`** |
| `__DATA.__objc_ivar` | `0x14a0` | `0x1474` | **`-0x2c`** |
| `__TEXT.__swift5_reflstr` | `0x107f` | `0x109f` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1780` | `0x1798` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x9490` | `0x9478` | **`-0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x5e0` | `0x5d0` | **`-0x10`** |
| `__DATA.__common` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x9c0` | `0x9c8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x418` | `0x420` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x110` | `0x118` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x390` | `0x394` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1c4` | `0x1c8` | **`+0x4`** |

### Other Changes

```diff

-3891.100.17.2.4
+3893.100.7.0.0

-  Functions: 11354
-  Symbols:   15133
-  CStrings:  5406
+  Functions: 11376
+  Symbols:   15055
+  CStrings:  5401
Symbols:
+ +[EDSearchableIndexItem itemWithMessage:bodyData:fetchBody:isLocallyAvailable:]
+ +[EDSearchableIndexPersistence resetSearchableIndexTablesWithConnection:reason:]
+ -[EDActivityPersistence _addActivity:]
+ -[EDActivityPersistence _removeActivity:]
+ -[EDDiagnosticInfoGatherer gatherIndexingDiagnosticsWithRedaction:includeHDBStatus:completionHandler:]
+ -[EDMessagePersistence _globalIDForMessageWithDocumentID:mailboxScope:]
+ -[EDMessagePersistence _persistedMessagesForForGlobalMessageIDs:requireProtectedData:]
+ -[EDMessagePersistence globalIDsForMessageIDHeaders:]
+ -[EDMessagePersistence persistedMessagesForForMessageIDHeaders:]
+ -[EDSearchableIndex _transition]
+ -[EDSearchableIndex performMaintenanceWorkWithCompletion:]
+ -[EDSearchableIndexAttachmentItem isLocallyAvailable]
+ -[EDSearchableIndexItem initWithIdentifier:message:bodyData:fetchBody:isLocallyAvailable:]
+ -[EDSearchableIndexItem initWithMessage:bodyData:fetchBody:isLocallyAvailable:]
+ -[EDSearchableIndexItem isLocallyAvailable]
+ -[EDSearchableIndexPendingItem isLocallyAvailable]
+ -[EDSearchableIndexPersistence newestUndonatedMessageDateWithActiveMailboxesClause:]
+ -[EDSearchableIndexPersistence newestUndonatedMessageDateWithActiveMailboxesClause:chunkSize:threshold:]
+ -[EDSearchableIndexRichLinkItem isLocallyAvailable]
+ -[EDSearchableIndexState indexItem:evicted:]
+ -[EDSearchableIndexState initWithQueueSize:]
+ -[_EDThreadMigrationState verifyIsMigratingGeneration:andIsInState:orState:orState:logIdentifier:logAction:logCount:]
+ GCC_except_table316
+ GCC_except_table326
+ GCC_except_table336
+ GCC_except_table337
+ GCC_except_table338
+ GCC_except_table339
+ GCC_except_table340
+ GCC_except_table341
+ GCC_except_table342
+ GCC_except_table343
+ _OBJC_CLASS_$_EDAddResetSearchIndexReasonColumn
+ _OBJC_CLASS_$_EDResetSpotlightIndexStateUpgradeStep
+ _OBJC_IVAR_$_EDActivityPersistence._currentFetchActivitiesByMailbox
+ _OBJC_IVAR_$_EDSearchableIndexItem._locallyAvailable
+ _OBJC_IVAR_$_EDSearchableIndexState._queueSize
+ _OBJC_METACLASS_$_EDAddResetSearchIndexReasonColumn
+ _OBJC_METACLASS_$_EDResetSpotlightIndexStateUpgradeStep
+ __CLASS_METHODS_EDAddResetSearchIndexReasonColumn
+ __CLASS_METHODS_EDResetSpotlightIndexStateUpgradeStep
+ __CLASS_METHODS_EDSearchableIndexScheduler
+ __CLASS_PROPERTIES_EDSearchableIndexAnalyticsPersistence
+ __DATA_EDAddResetSearchIndexReasonColumn
+ __DATA_EDResetSpotlightIndexStateUpgradeStep
+ __DATA_EDSearchableIndexScheduler
+ __INSTANCE_METHODS_EDAddResetSearchIndexReasonColumn
+ __INSTANCE_METHODS_EDResetSpotlightIndexStateUpgradeStep
+ __INSTANCE_METHODS_EDSearchableIndexScheduler
+ __IVARS_EDSearchableIndexScheduler
+ __METACLASS_DATA_EDAddResetSearchIndexReasonColumn
+ __METACLASS_DATA_EDResetSpotlightIndexStateUpgradeStep
+ __METACLASS_DATA_EDSearchableIndexScheduler
+ __PROPERTIES_EDSearchableIndexScheduler
+ __PROTOCOLS_EDAddResetSearchIndexReasonColumn
+ __PROTOCOLS_EDResetSpotlightIndexStateUpgradeStep
+ __PROTOCOLS_EDSearchableIndexScheduler
+ ___104-[EDSearchableIndexPersistence newestUndonatedMessageDateWithActiveMailboxesClause:chunkSize:threshold:]_block_invoke
+ ___117-[_EDThreadMigrationState verifyIsMigratingGeneration:andIsInState:orState:orState:logIdentifier:logAction:logCount:]_block_invoke
+ ___32-[EDSearchableIndex _transition]_block_invoke
+ ___44-[EDSearchableIndexState indexItem:evicted:]_block_invoke
+ ___50-[EDSearchableIndexPendingItem isLocallyAvailable]_block_invoke
+ ___52-[EDThreadMigrator _migrateNextBatchWithGeneration:]_block_invoke_2
+ ___53-[EDMessagePersistence globalIDsForMessageIDHeaders:]_block_invoke
+ ___53-[EDMessagePersistence globalIDsForMessageIDHeaders:]_block_invoke_2
+ ___53-[EDMessagePersistence globalIDsForMessageIDHeaders:]_block_invoke_3
+ ___58-[EDSearchableIndex performMaintenanceWorkWithCompletion:]_block_invoke
+ ___71-[EDMessagePersistence _globalIDForMessageWithDocumentID:mailboxScope:]_block_invoke
+ ___71-[EDMessagePersistence _globalIDForMessageWithDocumentID:mailboxScope:]_block_invoke_2
+ ___block_descriptor_49_ea8_32r40r_e25_v32?0"EFSQLRow"8Q16^B24lr32l8r40l8
+ ___block_descriptor_56_ea8_32s40r_e33_v16?0"_EDThreadMigrationState"8ls32l8r40l8
+ ___block_descriptor_57_ea8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
+ ___block_descriptor_64_ea8_32s_e5_B8?0ls32l8
+ ___swift_closure_destructor.20Tm
+ __stringForThreadScopeMigrationState
+ _keypath_get_selector_schedulable
+ _sqlite3_column_int64
+ _swift_unknownObjectWeakAssign
+ _symbolic So12BGSystemTaskC
+ _symbolic So26EDSearchableIndexSchedulerC
+ _symbolic So26EDSearchableIndexSchedulerCSgXw
+ _symbolic So26EDSearchableIndexSchedulerCSgXwz_Xx
+ _symbolic So26EDSearchableIndexSchedulerCXDXMT
+ _symbolic _____ 11EmailDaemon35EDSearchableIndexDownloadStatisticsV10WindowSizeV
+ _symbolic _____ So31EDPersistenceDatabaseConnectionC11EmailDaemonE8SQLError33_CB77B56600C1C2F06AD7EC03F5899B4DLLV
+ _symbolic _____Sg 11EmailDaemon13IndexSnapshot33_2AAEEE8DC524D8C5EA96B451A41128B9LLV
- +[EDSearchableIndexItem itemWithIdentifier:message:bodyData:fetchBody:]
- +[EDSearchableIndexItem itemWithMessage:bodyData:fetchBody:]
- +[EDSearchableIndexScheduler activityTypes]
- +[EDSearchableIndexScheduler deferrableActivityTypes]
- +[EDSearchableIndexScheduler isDeferrableActivityType:]
- +[EDSearchableIndexScheduler isTurboModeIndexingEnabled]
- +[EDSearchableIndexScheduler log]
- -[EDDiagnosticInfoGatherer gatherIndexingDiagnosticsWithRedaction:completionHandler:]
- -[EDSearchableIndex _eventDataForTransitionState:]
- -[EDSearchableIndex _queueConsumeBudgetElapsedPeriod:]
- -[EDSearchableIndex _transitionWithBudgetTimeUsed:]
- -[EDSearchableIndex performMaintenancePreWork]
- -[EDSearchableIndexItem initWithIdentifier:]
- -[EDSearchableIndexItem initWithIdentifier:message:bodyData:fetchBody:]
- -[EDSearchableIndexItem initWithMessage:bodyData:fetchBody:]
- -[EDSearchableIndexManager needsToRedonate]
- -[EDSearchableIndexManager setNeedsToRedonate:]
- -[EDSearchableIndexManager setNeedsToRedonate]
- -[EDSearchableIndexScheduler .cxx_destruct]
- -[EDSearchableIndexScheduler _beginIndexingForTaskType:task:]
- -[EDSearchableIndexScheduler _deferActivitiesIfNecessary]
- -[EDSearchableIndexScheduler _disableIndexingForActivityType:defer:]
- -[EDSearchableIndexScheduler _disableIndexingForTaskType:]
- -[EDSearchableIndexScheduler _enableIndexingForActivityType:]
- -[EDSearchableIndexScheduler _enableIndexingForTaskType:]
- -[EDSearchableIndexScheduler _logIndexingPowerEventWithIdentifier:additionalEventData:usePersistentLog:]
- -[EDSearchableIndexScheduler _periodicallyCheckForDeferralIfNecessary]
- -[EDSearchableIndexScheduler _registerActivityForType:builder:runner:]
- -[EDSearchableIndexScheduler _startScheduling]
- -[EDSearchableIndexScheduler _stopAllIndexingBacklogComplete:]
- -[EDSearchableIndexScheduler _stopIndexingForActivityType:shouldDeferIfPossible:]
- -[EDSearchableIndexScheduler _stopIndexingForTaskType:requestRetry:backlogComplete:]
- -[EDSearchableIndexScheduler _stopScheduling]
- -[EDSearchableIndexScheduler _xpcActivityIdentifierForActivityType:]
- -[EDSearchableIndexScheduler _xpcCriteriaBuilderBlockForActivityType:]
- -[EDSearchableIndexScheduler activities]
- -[EDSearchableIndexScheduler beginIndexingForActivityType:activity:]
- -[EDSearchableIndexScheduler dealloc]
- -[EDSearchableIndexScheduler deferIndexingForActivityType:]
- -[EDSearchableIndexScheduler hasAvailableIndexingBudgetForSearchableIndexSchedulable:]
- -[EDSearchableIndexScheduler indexingDidFinishForSearchableIndexSchedulable:backlogComplete:]
- -[EDSearchableIndexScheduler indexingDidResumeForSearchableIndexSchedulable:]
- -[EDSearchableIndexScheduler indexingDidSuspendForSearchableIndexSchedulable:]
- -[EDSearchableIndexScheduler indexingStateQueue]
- -[EDSearchableIndexScheduler initWithSchedulable:]
- -[EDSearchableIndexScheduler isDataSourceIndexingPermitted]
- -[EDSearchableIndexScheduler isIndexingEnabledForActivityType:]
- -[EDSearchableIndexScheduler isIndexingEnabledForTaskType:]
- -[EDSearchableIndexScheduler isScheduling]
- -[EDSearchableIndexScheduler maintenanceIndexingTime]
- -[EDSearchableIndexScheduler otherIndexingTime]
- -[EDSearchableIndexScheduler requireClassA]
- -[EDSearchableIndexScheduler schedulable]
- -[EDSearchableIndexScheduler scheduledDeferralCheck]
- -[EDSearchableIndexScheduler searchableIndexSchedulable:didGenerateImportantPowerEventWithIdentifier:eventData:]
- -[EDSearchableIndexScheduler searchableIndexSchedulable:didGeneratePowerEventWithIdentifier:eventData:]
- -[EDSearchableIndexScheduler searchableIndexSchedulable:didIndexForTime:]
- -[EDSearchableIndexScheduler searchableIndexSchedulable:didIndexItemCount:lastItemDateReceived:]
- -[EDSearchableIndexScheduler setActivities:]
- -[EDSearchableIndexScheduler setIndexingStateQueue:]
- -[EDSearchableIndexScheduler setRequireClassA:]
- -[EDSearchableIndexScheduler setScheduledDeferralCheck:]
- -[EDSearchableIndexScheduler setScheduling:]
- -[EDSearchableIndexScheduler setState:]
- -[EDSearchableIndexScheduler setTasks:]
- -[EDSearchableIndexScheduler state]
- -[EDSearchableIndexScheduler tasks]
- -[EDSearchableIndexSchedulerState .cxx_destruct]
- -[EDSearchableIndexSchedulerState _isIndexingEnabledByActivitiesOrTasks]
- -[EDSearchableIndexSchedulerState didIndexForTime:]
- -[EDSearchableIndexSchedulerState didIndexItemCount:]
- -[EDSearchableIndexSchedulerState disableIndexingForActivityType:]
- -[EDSearchableIndexSchedulerState disableIndexingForTaskType:]
- -[EDSearchableIndexSchedulerState enableIndexingForActivityType:]
- -[EDSearchableIndexSchedulerState enableIndexingForTaskType:]
- -[EDSearchableIndexSchedulerState indexingEnabledForActivityTypes]
- -[EDSearchableIndexSchedulerState indexingEnabledForTaskTypes]
- -[EDSearchableIndexSchedulerState init]
- -[EDSearchableIndexSchedulerState isDataSourceIndexingPermitted]
- -[EDSearchableIndexSchedulerState isIndexingEnabledByActivities]
- -[EDSearchableIndexSchedulerState isIndexingEnabledForActivityType:]
- -[EDSearchableIndexSchedulerState isIndexingEnabledForTaskType:]
- -[EDSearchableIndexSchedulerState maintenanceIndexingTime]
- -[EDSearchableIndexSchedulerState otherIndexingTime]
- -[EDSearchableIndexSchedulerState powerEventData]
- -[EDSearchableIndexSchedulerState setDataSourceIndexingPermitted:]
- -[EDSearchableIndexSchedulerState setMaintenanceIndexingTime:]
- -[EDSearchableIndexSchedulerState setOtherIndexingTime:]
- -[EDSearchableIndexState indexItem:]
- GCC_except_table193
- GCC_except_table322
- _EDSearchableIndexSchedulerActivityTypeBudgeted
- _EDSearchableIndexSchedulerActivityTypeMaintenance
- _OBJC_CLASS_$_EDSearchableIndexSchedulerState
- _OBJC_IVAR_$_EDSearchableIndexManager._needsToRedonate
- _OBJC_IVAR_$_EDSearchableIndexScheduler._activities
- _OBJC_IVAR_$_EDSearchableIndexScheduler._indexingStateQueue
- _OBJC_IVAR_$_EDSearchableIndexScheduler._requireClassA
- _OBJC_IVAR_$_EDSearchableIndexScheduler._schedulable
- _OBJC_IVAR_$_EDSearchableIndexScheduler._scheduledDeferralCheck
- _OBJC_IVAR_$_EDSearchableIndexScheduler._scheduling
- _OBJC_IVAR_$_EDSearchableIndexScheduler._state
- _OBJC_IVAR_$_EDSearchableIndexScheduler._tasks
- _OBJC_IVAR_$_EDSearchableIndexSchedulerState._dataSourceIndexingPermitted
- _OBJC_IVAR_$_EDSearchableIndexSchedulerState._indexingEnabledForActivityTypes
- _OBJC_IVAR_$_EDSearchableIndexSchedulerState._indexingEnabledForTaskTypes
- _OBJC_IVAR_$_EDSearchableIndexSchedulerState._maintenanceIndexingTime
- _OBJC_IVAR_$_EDSearchableIndexSchedulerState._otherIndexingTime
- _OBJC_METACLASS_$_EDSearchableIndexSchedulerState
- _XPC_ACTIVITY_POWER_NAP
- _XPC_ACTIVITY_REQUIRES_CLASS_A
- __OBJC_$_CLASS_METHODS_EDSearchableIndexScheduler
- __OBJC_$_CLASS_PROP_LIST_EDSearchableIndexScheduler
- __OBJC_$_INSTANCE_METHODS_EDSearchableIndexScheduler
- __OBJC_$_INSTANCE_METHODS_EDSearchableIndexSchedulerState
- __OBJC_$_INSTANCE_VARIABLES_EDSearchableIndexScheduler
- __OBJC_$_INSTANCE_VARIABLES_EDSearchableIndexSchedulerState
- __OBJC_$_PROP_LIST_EDSearchableIndexScheduler
- __OBJC_$_PROP_LIST_EDSearchableIndexSchedulerState
- __OBJC_CLASS_PROTOCOLS_$_EDSearchableIndexScheduler
- __OBJC_CLASS_RO_$_EDSearchableIndexScheduler
- __OBJC_CLASS_RO_$_EDSearchableIndexSchedulerState
- __OBJC_METACLASS_RO_$_EDSearchableIndexScheduler
- __OBJC_METACLASS_RO_$_EDSearchableIndexSchedulerState
- ___103-[EDSearchableIndexScheduler searchableIndexSchedulable:didGeneratePowerEventWithIdentifier:eventData:]_block_invoke
- ___112-[EDSearchableIndexScheduler searchableIndexSchedulable:didGenerateImportantPowerEventWithIdentifier:eventData:]_block_invoke
- ___33+[EDSearchableIndexScheduler log]_block_invoke
- ___36-[EDSearchableIndexState indexItem:]_block_invoke
- ___43+[EDSearchableIndexScheduler activityTypes]_block_invoke
- ___45-[EDSearchableIndexScheduler _stopScheduling]_block_invoke
- ___46-[EDSearchableIndex performMaintenancePreWork]_block_invoke
- ___46-[EDSearchableIndexScheduler _startScheduling]_block_invoke
- ___47-[EDSearchableIndexScheduler otherIndexingTime]_block_invoke
- ___51-[EDSearchableIndex _transitionWithBudgetTimeUsed:]_block_invoke
- ___53+[EDSearchableIndexScheduler deferrableActivityTypes]_block_invoke
- ___53-[EDSearchableIndexScheduler maintenanceIndexingTime]_block_invoke
- ___57-[EDSearchableIndexScheduler _deferActivitiesIfNecessary]_block_invoke
- ___59-[EDSearchableIndex _doIndexItems:fromRefresh:immediately:]_block_invoke_3
- ___59-[EDSearchableIndexScheduler deferIndexingForActivityType:]_block_invoke
- ___59-[EDSearchableIndexScheduler isDataSourceIndexingPermitted]_block_invoke
- ___59-[EDSearchableIndexScheduler isIndexingEnabledForTaskType:]_block_invoke
- ___61-[EDSearchableIndexScheduler _beginIndexingForTaskType:task:]_block_invoke
- ___63-[EDSearchableIndexScheduler isIndexingEnabledForActivityType:]_block_invoke
- ___68-[EDSearchableIndexScheduler beginIndexingForActivityType:activity:]_block_invoke
- ___70-[EDSearchableIndexScheduler _periodicallyCheckForDeferralIfNecessary]_block_invoke
- ___70-[EDSearchableIndexScheduler _xpcCriteriaBuilderBlockForActivityType:]_block_invoke
- ___73-[EDSearchableIndexScheduler searchableIndexSchedulable:didIndexForTime:]_block_invoke
- ___77-[EDSearchableIndexScheduler indexingDidResumeForSearchableIndexSchedulable:]_block_invoke
- ___78-[EDSearchableIndexScheduler indexingDidSuspendForSearchableIndexSchedulable:]_block_invoke
- ___86-[EDSearchableIndexScheduler hasAvailableIndexingBudgetForSearchableIndexSchedulable:]_block_invoke
- ___89-[EDSearchableIndex searchableIndex:reindexAllSearchableItemsWithAcknowledgementHandler:]_block_invoke_2
- ___93-[EDSearchableIndexScheduler indexingDidFinishForSearchableIndexSchedulable:backlogComplete:]_block_invoke
- ___96-[EDSearchableIndexScheduler searchableIndexSchedulable:didIndexItemCount:lastItemDateReceived:]_block_invoke
- ___block_descriptor_40_ea8_32s_e50_v32?0"NSString"8"NSObject<OS_xpc_object>"16^B24ls32l8
- ___block_descriptor_48_ea8_32s40s_e33_v16?0"NSObject<OS_xpc_object>"8ls32l8s40l8
- ___block_descriptor_49_ea8_32s40r_e5_v8?0ls32l8r40l8
- ___block_descriptor_56_ea8_32s40bs48r_e5_v8?0lr48l8s32l8s40l8
- ___block_descriptor_65_ea8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
- ___swift_closure_destructor.14Tm
- _activityTypes.activityTypes
- _activityTypes.onceToken
- _deferrableActivityTypes.deferrableActivityTypes
- _deferrableActivityTypes.onceToken
- _xpc_activity_get_state
CStrings:
+ "%p[%lu]: Finished migration after pagination completed\n%{public}@"
+ "%p[%lu]: Migration queue empty; paging in more local results\n%{public}@"
+ "%p[%lu]: Migration queue empty; paging in more local results from query handler\n%{public}@"
+ "-[EDMessagePersistence _globalIDForMessageWithDocumentID:mailboxScope:]"
+ "-[EDMessagePersistence globalIDsForMessageIDHeaders:]"
+ "-[EDSearchableIndexPersistence newestUndonatedMessageDateWithActiveMailboxesClause:chunkSize:threshold:]"
+ "ALTER TABLE indexing_analytics_dropped_index_events\n  ADD COLUMN reason INTEGER NOT NULL DEFAULT 1;"
+ "CREATE TABLE messages (\n    id INTEGER PRIMARY KEY AUTOINCREMENT,\n    mail_id INTEGER NULL,\n    remote_id TEXT NULL,\n    mailbox INTEGER REFERENCES mailbox(id) NOT NULL,\n    date_received TEXT NULL,\n    have_body_locally INTEGER NOT NULL,\n    mail_status TEXT NOT NULL,\n    spotlight_status TEXT NOT NULL,\n    hdb_status TEXT,\n    mail_local_status TEXT NOT NULL,\n    mail_remote_status TEXT NOT NULL,\n    needs_reindex INTEGER NOT NULL,\n    subject TEXT,\n    senders TEXT,\n    UNIQUE(mail_id),\n    UNIQUE(mailbox, remote_id)\n);"
+ "Completed %{public}s task"
+ "Completing task %{public}s because indexing finished"
+ "Could not deregister throughput metrics '%{public}s': %{public}s"
+ "Could not find mailbox for message with document ID %{public}@"
+ "Could not register throughput metrics '%{public}s': %{public}s"
+ "Could not submit BGSystemTask for '%{public}s': %{public}s"
+ "Deferring %{public}s task"
+ "Deferring task %{public}s because indexing finished"
+ "EDSearchableIndexScheduler"
+ "EmailDaemon.EDSearchableIndexScheduler"
+ "EmailDaemon/EDSearchableIndexScheduler.swift"
+ "Failed to register BGSystemTask for '"
+ "Failed to register BGSystemTask for '%{public}s'"
+ "Finished indexing but no running task"
+ "Paging"
+ "Registered BGSystemTask for '%s'"
+ "Reindex requested due to %{public}@."
+ "Reported %ld messages for '%{public}s' metric"
+ "SELECT MAX(messages.date_received)  FROM messages       LEFT OUTER JOIN searchable_messages ON messages.searchable_message = searchable_messages.ROWID WHERE messages.deleted = '0'       AND messages.date_received <= %lld       AND (searchable_messages.message_body_indexed IS NULL OR searchable_messages.message_body_indexed = 0) %@"
+ "SELECT global_message_id FROM messages WHERE document_id = ? LIMIT 1"
+ "SELECT messages.date_received,       CASE WHEN searchable_messages.message_body_indexed = 1 THEN 1 ELSE 0 END AS donated  FROM messages       LEFT OUTER JOIN searchable_messages ON messages.searchable_message = searchable_messages.ROWID WHERE messages.deleted = '0'       AND messages.date_received <= unixepoch('now', '-1 day') %@ ORDER BY messages.date_received DESC"
+ "SELECT messages.global_message_id, mailboxes.url FROM messages LEFT JOIN mailboxes ON messages.mailbox = mailboxes.ROWID WHERE messages.document_id = ? LIMIT 1"
+ "Skipping transition from Paging to Finishing"
+ "Spotlight dropped index"
+ "Starting %{public}s task"
+ "Submitted BGSystemTask for '%{public}s'"
+ "Unable to add reason column to indexing_analytics_dropped_index_events"
+ "Unable to set retry: %{public}s"
+ "Unknown reason ("
+ "com.apple.email.SearchIndexer.statistics.daily"
+ "dataUsage_receivedByteCount"
+ "errors_dataUsageAboveQuotaCount"
+ "errors_serverUnavailableCount"
+ "spotlight_messageIndexCount"
- "%{public}@ : %{public}@"
- "%{public}@ task completed"
- "%{public}@ task expired with retry failed: %{public}@"
- "%{public}@ task requested more time"
- ".indexingStateQueue"
- "Attempted to begin indexing a task type (%{public}@) that already has a task: %@"
- "Attempted to begin indexing an activity type (%{public}@) that is already active - marking old ACTIVITY as DONE"
- "Attempting to find a criteria builder block indexing for an unsupported activity type: %@"
- "Attempting to register unsupported activity type: %@"
- "CREATE TABLE messages (\n    id INTEGER PRIMARY KEY AUTOINCREMENT,\n    mail_id INTEGER NULL,\n    remote_id TEXT NULL,\n    mailbox INTEGER REFERENCES mailbox(id) NOT NULL,\n    date_received TEXT NULL,\n    have_body_locally INTEGER NOT NULL,\n    mail_status TEXT NOT NULL,\n    spotlight_status TEXT NOT NULL,\n    hdb_status TEXT NOT NULL,\n    mail_local_status TEXT NOT NULL,\n    mail_remote_status TEXT NOT NULL,\n    needs_reindex INTEGER NOT NULL,\n    subject TEXT,\n    senders TEXT,\n    UNIQUE(mail_id),\n    UNIQUE(mailbox, remote_id)\n);"
- "Checking for XPC deferral"
- "Configuring %{public}@ actvitity with interval: %lld"
- "EDSearchableIndexScheduler.m"
- "Enabled indexing."
- "Failed to transition %{public}@ from state %ld to state %d."
- "Failed to transition %{public}@ from state %ld to state %ld."
- "Finished Indexing Batch"
- "Initializing scheduler"
- "Search fast pass task expired."
- "Setting needs to redonate"
- "Start Indexing Batch"
- "Starting scheduling"
- "Stopped indexing."
- "XPC Requested deferral of activity %@"
- "activityType"
- "already suspended"
- "budgeted"
- "countOfItemsIndexed"
- "deferred"
- "didDropIndex(at:)"
- "didIndexItemCount: %d lastItemDateReceived: %@"
- "elapsedTime"
- "extraIndexingTime"
- "itemsPerSecond"
- "maintenance"
- "maintenanceIndexingTime"
- "pending"
- "persistenceAvailable"
- "preprocessing"
- "preprocessingItemCount"
- "resume"
- "resumeCount"
- "still resumed"
- "suspend"
- "suspending"
- "taskType"
- "v32@?0@\"NSString\"8@\"NSObject<OS_xpc_object>\"16^B24"
```
