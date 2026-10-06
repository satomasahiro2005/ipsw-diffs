## CalendarDatabase

> `/System/Library/PrivateFrameworks/CalendarDatabase.framework/CalendarDatabase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc5b8` | `0xdc1d0` | **`-0x3e8`** |

### Other Changes

```diff

-1287.0.0.0.0
+1289.0.0.0.0
Functions:
~ __CalLoadRelation : 532 -> 512
~ -[EKCalendarFilter _UIDSetWithCalendars:] : 376 -> 372
~ -[EKCalendarFilter _UIDAntiSetWithCalendars:] : 436 -> 432
~ __CalDatabaseFaultDefaultRelationsForEvents : 540 -> 536
~ ___CalEventOccurrenceCacheCopyAllDaysAndOccurrenceCounts_block_invoke : 1356 -> 1352
~ -[EKCalendarFilter _visibleCalendarsWithOptions:] : 416 -> 412
~ __CalDatabaseTrimConsumedSequences : 944 -> 940
~ __CalDatabaseReportIntegrityErrors : 716 -> 712
~ +[CDBCommonEntityFunctionalityHandler _notifyDestructionObservers:] : 236 -> 232
~ __CalDatabaseMarkRangeAsImpacted : 36 -> 48
~ _CalDatabaseSaveInternalWithOptions : 10520 -> 10496
~ ___CalDatabasePerformMigrationIfNeeded_block_invoke : 5676 -> 5656
~ _CalDatabaseCopySourceStats : 532 -> 528
~ __CalDatabaseEnumerateAddedEntitiesOfType : 308 -> 304
~ __CalDatabaseValidateSchemaDeleteDBAndAbortOnFailure : 1016 -> 1000
~ __CalDatabaseCountEntitiesByType : 148 -> 144
~ __CalDatabaseLimitPropertyLengths : 700 -> 688
~ __CalDatabaseChangesOfTypeMayAffectWidgets : 2720 -> 2724
~ __CalDatabaseChangesOfTypeMayAffectAppEntities : 872 -> 856
~ __CalDatabaseDeleteDatabaseBecauseOfExcessiveFailedMigrationAttempts : 1100 -> 1096
~ __CalDatabaseCleanUpMovedAsideDatabaseFilesInDirectory : 592 -> 588
~ -[CalChangeFilteringMigrationAccountStore topLevelAccountsWithAccountTypeIdentifier:error:] : 680 -> 672
~ -[CalChangeFilteringMigrationAccountStore childAccountsForAccount:withTypeIdentifier:] : 880 -> 872
~ _CalRecurrenceGetPropertyIDWithPropertyName : 572 -> 556
~ __CalRecurrenceSpecifierParse : 2780 -> 2660
~ -[CaliTIPMessage event] : 900 -> 896
~ _CalCalendarItemGetPropertyIDWithPropertyName : 3108 -> 3092
~ _CalCalendarItemCopyGroupedCategories : 560 -> 556
~ _CalCalendarItemSetupOrganizerAndSelfAttendeeForImportedItem : 1148 -> 1144
~ _CalMigrationDropIndexes : 172 -> 180
~ _CalMigrationDropTriggers : 172 -> 168
~ _MoveTableData : 1052 -> 1108
~ _CalMigrationCreateTriggers : 292 -> 284
~ _MoveTableData2 : 1224 -> 1264
~ _MigrateRow : 1448 -> 1452
~ _CalDatabaseBackupCore : 2380 -> 2376
~ _CalDatabaseBackupToICBU : 2728 -> 2724
~ _CalDatabaseRestoreDatabaseCore : 6036 -> 6016
~ _CalDatabaseRestoreFromICBU : 4252 -> 4236
~ +[CADObjectChangeIDHelper makeObjectChangeEntityTypeMapToArray:] : 500 -> 496
~ +[CADObjectChangeIDHelper makeObjectChangeEntityTypeMapToSet:] : 500 -> 496
~ ___CalColorGetPropertyIDWithPropertyName_block_invoke : 348 -> 332
~ __CalColorHasValidParent : 260 -> 256
~ __CalColorGetStoreID : 380 -> 376
~ __CalDatabaseMigrateToMultipleDatabases : 5352 -> 5348
~ __CalDatabaseCopyToAuxDatabaseWithChanges : 596 -> 592
~ +[CDBAttachmentMigrator _infoForAttachmentsInLegacyAttachmentContainerForStore:newAttachmentContainerForStore:newCalendarDataContainer:database:] : 536 -> 532
~ +[CDBAttachmentMigrator migrateDataClassProtectionForAttachmentsInLegacyCalendarDataContainer:] : 628 -> 624
~ ___CalErrorGetPropertyIDWithPropertyName_block_invoke : 380 -> 364
~ _CalDatabaseSetupNewlyCreatedAuxDatabase : 292 -> 288
~ _CalDatabaseEnumerateDatabasesWithConfiguration : 428 -> 424
~ -[CalAttachmentFileCleanupContext cleanup] : 744 -> 740
~ _CalRecurrenceUpdateFromICSRecurrenceRule : 1192 -> 1184
~ __CreateIntArrayFromNSNumberArray : 312 -> 308
~ +[CDBiCalFixUps fixEndDates:] : 628 -> 624
~ +[CDBiCalFixUps _fixEndDateForEvent:withOriginalEvent:detachments:] : 1500 -> 1492
~ ___CalResourceChangeGetPropertyIDWithPropertyName_block_invoke : 700 -> 684
~ _CalAttachmentFilePropertyWillChange : 268 -> 264
~ __CalAttachmentFileGetStoreID : 444 -> 440
~ _CalDatabaseDeleteOrphanedAttachmentsInDirectory : 1764 -> 1760
~ _CalDatabaseCleanUpOrphanedLocalAttachments : 1736 -> 1732
~ __CalAttachmentFileHasValidParent : 260 -> 256
~ _CalCalendarGetPropertyIDWithPropertyName : 2000 -> 1984
~ _CalCalendarRemoveAllRecords : 508 -> 504
~ _CalCalendarMigrateSubscribedCalendarToStore : 1096 -> 1084
~ _CalDatabasePerformMigrationBetweenDirectoriesIfNeeded : 3580 -> 3576
~ +[CalStoreSetupAndTeardownUtils isLocalStoreEmptyInDatabase:] : 324 -> 320
~ +[CalStoreSetupAndTeardownUtils setLocalStoreEnabled:inDatabase:] : 716 -> 708
~ +[CalStoreSetupAndTeardownUtils _enableLocalStoreIfNecessaryIgnoringAccount:inDatabase:accountStore:] : 940 -> 936
~ +[CalStoreSetupAndTeardownUtils mergeEventsFromLocalStoreIntoStore:inDatabase:] : 456 -> 452
~ _CalParticipantSaveUnrecognizedPararmeters : 484 -> 480
~ _CalParticipantApplyExternalRepresentationToICSUser : 680 -> 676
~ __CalEventGetLargestPossibleAlarmOffsets : 596 -> 592
~ __CalRecurrenceApplyFiltersToSingleDate : 188 -> 192
~ ___CalAttendeeBasePropertiesMappingDict_block_invoke : 1004 -> 972
~ _CalDatabaseCopyAttendeeForEventWithAddress : 632 -> 628
~ ___CalOrganizerGetPropertyIDWithPropertyName_block_invoke : 336 -> 320
~ __CalMigrateExtractCommentLastModifiedDate : 676 -> 672
~ __CalDBCreatePropertyMap : 124 -> 128
~ __CalDBInsertPropertyMap : 92 -> 100
~ -[CDBDefaultAccountInfo addressURLIsAccountOwner:] : 304 -> 300
~ _CalEventHasOccurrenceInTheFuture : 604 -> 600
~ _CalEventNotifyInvitationIfNeededWithOptions : 744 -> 740
~ __CalCopyRecurringEventQueryRowHandler : 672 -> 660
~ _CalEventGetStartDateOfEarliestOccurrenceEndingAfterDateWithExclusions : 1344 -> 1336
~ _CalAttachmentUpdateFromICSAttachment : 1544 -> 1540
~ _ICSAttachmentFromCalAttachment : 1684 -> 1680
~ _CalDatabaseCopyUpdatedCalEventsFromICSDocumentWithOptionsAndBatchSize : 3220 -> 3212
~ _componentsWithPhantomMasterForICSCalendar : 1432 -> 1428
~ _CalAlarmGetPropertyIDWithPropertyName : 740 -> 724
~ _CalGetRealUIDFromRecurrenceUID : 348 -> 344
~ _CalCalendarItemUpdateFromICSComponent : 13504 -> 13460
~ _CalCalendarItemUpdateICSComponent : 4504 -> 4500
~ _CalIdentityMigrateTables : 1980 -> 1976
~ _CalExceptionDateGetPropertyIDWithPropertyName : 328 -> 312
~ -[CDBRecurrenceGenerator copyOccurrenceDatesWithInitialDate:calRecurrences:rangeStart:rangeEnd:timeZone:] : 512 -> 508
~ -[CDBRecurrenceGenerator nextOccurrenceDateWithCalRecurrences:exceptionDates:initialDate:afterDate:] : 1044 -> 1040
~ ___CalConferenceGetPropertyIDWithPropertyName_block_invoke : 400 -> 384
~ _CalStoreGetPropertyIDWithPropertyName : 1092 -> 1076
~ -[CalACMigrationAccountStore topLevelAccountsWithAccountTypeIdentifier:error:] : 460 -> 456
~ -[CalACMigrationAccountStore childAccountsForAccount:withTypeIdentifier:] : 500 -> 496
~ _CalEventUpdateFromICSEventWithOptions : 4288 -> 4276
~ -[CalItemMetadata initWithICSComponent:] : 1112 -> 1108
~ _CalLocationGetPropertyIDWithPropertyName : 644 -> 628
~ +[CalDAVNotificationHandler _handleResourceChanged:withUid:serverURL:syncKey:database:store:calendarHomeURL:notificationCalendar:notificationCalendarURL:recordIDMap:] : 2332 -> 2312
~ +[CalDAVNotificationHandler _changedAttributesFromCalendarChanges:] : 1048 -> 1044
~ -[EKCalendarFilter filteredCalendars] : 368 -> 364
~ -[EKCalendarFilter visibleCalendarCountWithOptions:] : 380 -> 376
~ +[EKCalendarFilter _addCalendarUIDsFromPrefs:toSet:database:] : 324 -> 320
~ -[EKCalendarFilter validate] : 384 -> 380
~ _CalNotificationGetPropertyIDWithPropertyName : 816 -> 800
~ __CalAlarmCacheProcessAddedEvent : 1680 -> 1676
~ __CalEventOccurrenceCacheCopyOccurrenceDatesForEvent : 804 -> 796
~ -[CalDatabaseChangeReport initWithCoder:] : 692 -> 708
~ -[CalDatabaseChangeReport encodeWithCoder:] : 760 -> 744
~ -[CalDatabaseChangeReport freeRecords] : 144 -> 136
~ -[CalDatabaseChangeReport changesSavedInDatabase:] : 344 -> 332
~ -[CalDatabaseChangeReport enumerateImpactedEvents:] : 136 -> 120
~ -[CalDatabaseChangeReport processChanges:ofType:] : 1100 -> 1088
~ _CalShareeGetPropertyIDWithPropertyName : 584 -> 568
~ _CalDatabaseCopyAlarmOccurrencesFromAlarmCache : 1064 -> 1060
~ _CalEventActionGetPropertyIDWithPropertyName : 456 -> 440
~ +[CalDatabaseInMemoryChangeTracking _setInterestedDatabasePaths:forContext:] : 664 -> 656
~ +[CalDatabaseInMemoryChangeTracking setInterestedDatabases:forContext:] : 360 -> 356
~ +[CalDatabaseInMemoryChangeTracking setInterestedDatabasePaths:forContext:] : 360 -> 356
~ -[CalDatabaseInMemoryChangeTracking _writeChanges:withTimestamp:flags:clientID:atIndex:] : 336 -> 332
~ ___194-[CalDatabaseInMemoryChangeTracking changedEntityIDsBetweenMinExternalTimestamp:minSelfTimestamp:maxExternalTimestamp:allowIntegrationChanges:latestSelfTimestamp:client:changeType:deleteOffset:]_block_invoke : 120 -> 116
~ _CalDatabaseCreateRecordIDSetFromRecordData : 172 -> 176
~ ___CalImageGetPropertyIDWithPropertyName_block_invoke : 348 -> 332
~ __CalImageHasValidParent : 432 -> 424
~ __CalImageGetStoreID : 616 -> 608
~ _CalSuggestedEventInfoGetPropertyIDWithPropertyName : 488 -> 472
~ __CalDatabaseGetChangedObjectIDsSinceSequenceNumberForClient : 3992 -> 3996
~ _generateNotInClause : 364 -> 360
~ ____CalDatabaseGetChangedObjectIDsSinceSequenceNumberForClient_block_invoke : 684 -> 680
~ _CalDatabaseGetChangedRecordIDsSinceSequenceNumberForClient : 512 -> 548
~ ___CalDatabaseGetChangedEKObjectsForClient_block_invoke : 1720 -> 1708
~ _CalDatabaseClearSuperfluousChanges : 2852 -> 2844
~ __CalDatabaseClearAllChangeHistoryForAllClients : 904 -> 908
~ _CalDatabaseEnumerateUnconsumedObjectChangesForClient : 836 -> 832
~ _CalDatabasePurgeIdlePersistentChangeTrackingClients : 1044 -> 1040
~ _CalDatabaseCountPersistentChangeRecords : 272 -> 284
~ ____buildDictionariesWithChangeTablePropertiesForEntityType_block_invoke : 824 -> 820
~ ____CalDatabaseEnumerateUnconsumedObjectChangesForClient_block_invoke : 512 -> 508
~ _CalAttachmentGetPropertyIDWithPropertyName : 752 -> 736
~ +[CaliTIPHandler processMessages:withDatabase:calStore:accountInfo:handledEventCallback:cancellationToken:options:] : 416 -> 412
~ +[CaliTIPHandler getOccurrenceChange:forEvent:inCalendar:] : 916 -> 912
~ +[CaliTIPHandler doScheduleChanges:applyToEvent:inCalendar:] : 524 -> 520
~ +[CaliTIPHandler myAddressWithAccountInfo:forEvent:] : 356 -> 352
~ +[CaliTIPHandler myStatusNeedsActionForEvent:withAccountInfo:] : 364 -> 360
~ +[CaliTIPHandler copyEventInStore:appropriateForHandlingMessageForEventUID:inDatabase:] : 404 -> 400
~ +[CaliTIPHandler processMessage:withDatabase:calStore:accountInfo:handledEventCallback:options:] : 2300 -> 2296
~ +[CaliTIPHandler handleEvent:calEvent:eventID:database:message:accountInfo:] : 2072 -> 2064
~ +[CaliTIPHandler _calculateDiffsForCalEvent:icsEvent:inMessage:] : 1044 -> 1040
```
