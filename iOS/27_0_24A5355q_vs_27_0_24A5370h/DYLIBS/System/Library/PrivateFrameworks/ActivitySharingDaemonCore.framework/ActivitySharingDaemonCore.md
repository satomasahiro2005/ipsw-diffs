## ActivitySharingDaemonCore

> `/System/Library/PrivateFrameworks/ActivitySharingDaemonCore.framework/ActivitySharingDaemonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x711a0` | `0x70f78` | **`-0x228`** |

### Other Changes

```diff

-2027.0.11.0.0
+2027.0.12.0.0
Functions:
~ _ASAllRelationshipsByRecordIDForCloudType : 600 -> 596
~ _ASResolveDuplicateRelationshipByCloudKitAddress : 536 -> 532
~ _ASContactsPreferringPlaceholders : 544 -> 536
~ _ASAllContactsByRecordID : 688 -> 684
~ _ASReconcileRelationshipsAgainstAddressBook : 968 -> 964
~ ___ASReconcileRelationshipsAgainstAddressBook_block_invoke_2 : 3108 -> 3140
~ +[ASActivityDataValidator validatedSamplesFromAchievements:workouts:activitySnapshots:friendListManager:isInvitationData:] : 1712 -> 1700
~ _ASSendRichMessagePayloadToDestination : 1496 -> 1492
~ +[ASDatabaseSampleEntity enumerateSamplesOfTypes:predicate:healthStore:anchor:error:handler:] : 344 -> 340
~ -[ASActivityDataManager _ckQueue_processActivitySnapshotsForSelf:] : 808 -> 804
~ -[ASActivityDataManager _queue_deleteAllActivitySharingData] : 888 -> 884
~ -[ASActivityDataManager activitySnapshotsFromFitnessFriendSamples:] : 452 -> 448
~ -[ASActivityDataManager achievementsFromFitnessFriendSamples:] : 540 -> 536
~ -[ASActivityDataManager workoutsFromFitnessFriendSamples:] : 540 -> 536
~ -[ASActivityDataManager _queue_samplesAdded:] : 832 -> 828
~ ___98-[ASActivityDataManager currentActivitySummaryHelper:didUpdateTodayActivitySummary:changedFields:]_block_invoke.436 -> ___98-[ASActivityDataManager currentActivitySummaryHelper:didUpdateTodayActivitySummary:changedFields:]_block_invoke.442 : 256 -> 252
~ -[ASActivityDataManager _workoutsForActivitySnapshot:anchor:completion:] : 1584 -> 1576
~ -[ASActivityDataManager _workoutsAfterAnchor:withPredicate:] : 536 -> 532
~ -[ASActivityDataManager _queue_activitySnapshotsToPushWithYesterdaySnapshot:todaySnapshot:] : 464 -> 460
~ -[ASActivityDataManager _achievementsToPushWithYesterdaySnapshot:todaySnapshot:currentTodayAchievementAnchorToken:currentYesterdayAchievementAnchorToken:] : 1748 -> 1732
~ -[ASActivityDataManager recordsFromActivityDataCodables:recordEncryptionType:] : 444 -> 440
~ -[ASActivityDataManager recordsToSave] : 1696 -> 1692
~ -[ASActivityDataManager recordIDsToDelete] : 1300 -> 1296
~ -[ASActivityDataManager _ckQueue_handleDeletedWorkoutEvents:completion:] : 620 -> 616
~ -[ASRelationshipFinalizationStore insertPlaceholderForEventTypes:contactUUID:] : 888 -> 884
~ ___81-[ASRelationshipFinalizationStore removePlaceholderWithContactUUID:shouldNotify:]_block_invoke : 380 -> 376
~ ___39-[ASContactsManager loadCachedContacts]_block_invoke : 880 -> 876
~ ___40-[ASContactsManager placeholderContacts]_block_invoke : 320 -> 316
~ ___50-[ASContactsManager contactMatchingCriteriaBlock:]_block_invoke : 304 -> 300
~ _ASFindContactWithDestinationsInContacts : 524 -> 520
~ __DestinationsForContactStoreContact : 596 -> 588
~ ___55-[ASContactsManager removePlaceholderContactWithToken:]_block_invoke : 848 -> 844
~ ___55-[ASContactsManager removePlaceholderContactWithToken:]_block_invoke_2 : 348 -> 344
~ -[ASContactsManager _setContacts:waitForTransaction:] : 660 -> 656
~ -[ASContactsManager _contactsToBeRemovedFromOldContacts:newContacts:] : 408 -> 404
~ ___43-[ASContactsManager _queue_notifyObservers]_block_invoke : 364 -> 360
~ -[ASContactsManager _findMatchingContactStoreContactForDestinations:] : 680 -> 676
~ _ASFindContactWithDestinationsOrIdentifierInContacts : 580 -> 576
~ _ASWriteContactsToDiskCache : 288 -> 284
~ _ASDeleteContactsFromDiskCache : 664 -> 660
~ ___84-[ASPeriodicUpdateManager _queue_performUpdateForActivity:cloudKitGroup:completion:]_block_invoke.381 -> ___84-[ASPeriodicUpdateManager _queue_performUpdateForActivity:cloudKitGroup:completion:]_block_invoke.387 : 628 -> 624
~ ___84-[ASPeriodicUpdateManager _queue_performUpdateForActivity:cloudKitGroup:completion:]_block_invoke_3 : 556 -> 552
~ -[ASCompanionBulletinPostingManager enqueueBulletins:withPostingSyle:] : 420 -> 416
~ ___67-[ASFriendListManager fetchCodableFriendWithRemoteUUID:completion:]_block_invoke : 352 -> 348
~ -[ASFriendListManager _queue_friendWithUUID:] : 360 -> 356
~ -[ASFriendListManager _queue_updateFriendList] : 1636 -> 1616
~ ___78-[ASFriendListManager updateFriendListWithNewSnapshots:achievements:workouts:]_block_invoke : 2500 -> 2480
~ ___64-[ASFriendListManager updateFriendListWithDeletedWorkoutEvents:]_block_invoke : 896 -> 892
~ -[ASFriendListManager _queue_hasFriendsToShareWithForContacts:defaultsKey:] : 1252 -> 1248
~ -[ASFriendListManager _queue_notifyObserversOfFriendListChanges] : 684 -> 680
~ ___64-[ASFriendListManager _queue_notifyObserversOfFriendListChanges]_block_invoke : 252 -> 248
~ ___65-[ASFriendListManager _queue_notifyObserversOfCompetitionsLoaded]_block_invoke : 244 -> 240
~ ___56-[ASFriendListManager contactsManagerDidUpdateContacts:]_block_invoke : 744 -> 752
~ ___67-[ASFriendListManager competitionManagerDidLoadCachedCompetitions:]_block_invoke : 500 -> 496
~ ___83-[ASFriendListManager competitionManager:didUpdateCompetitionsForFriendsWithUUIDs:]_block_invoke : 524 -> 520
~ -[ASFriendListManager badgeCount] : 384 -> 380
~ -[ASFriendListManager _allContactsPreferringPlaceholderContacts] : 856 -> 840
~ -[ASAchievementManager removeAllUnusedTemplates] : 708 -> 704
~ ___53-[ASCloudKitManager _queue_cancelAllExecutingFetches]_block_invoke : 292 -> 288
~ -[ASCloudKitManager _queue_callFetchCompletionBlocksWithSuccess:error:] : 428 -> 424
~ -[ASCloudKitManager _subscribeToChangesInDatabase:subscriptionPrefix:recordTypes:zoneNames:recordTypesToDelete:completion:] : 1396 -> 1384
~ ___107-[ASCloudKitManager _observerQueue_performNotificationStep:onRecords:dispatchGroup:activity:cloudKitGroup:]_block_invoke : 840 -> 836
~ ___107-[ASCloudKitManager _observerQueue_performNotificationStep:onRecords:dispatchGroup:activity:cloudKitGroup:]_block_invoke_2 : 716 -> 708
~ -[ASCloudKitManager _observerQueue_notifyOfPrivateDatabaseDeletedRecordIDs:sharedDatabaseDeletedRecordIDs:] : 608 -> 604
~ -[ASCloudKitManager _observerQueue_notifyObserversOfBeginUpdatesForFetchWithType:] : 380 -> 376
~ -[ASCloudKitManager _queue_notifyObserversOfStatusChanged:] : 372 -> 368
~ -[ASCloudKitManager _observerQueue_notifyObserversOfEndUpdatesForFetchWithType:activity:cloudKitGroup:] : 552 -> 548
~ -[ASCloudKitManager _observerQueue_notifyObserversOfServerPushHandledWithCloudKitGroup:] : 388 -> 384
~ -[ASActivitySharingManager _mainQueue_notifySubmanagersOfManagerReady] : 1020 -> 1016
~ -[ASActivitySharingManager _mainQueue_notifyObserversOfActivation] : 248 -> 244
~ -[ASActivitySharingManager _mainQueue_notifyObserversOfDeactivation] : 248 -> 244
~ ___44-[ASCompetitionStore loadCachedCompetitions]_block_invoke : 1448 -> 1444
~ ___50-[ASCompetitionStore _saveCompetitionLists:owner:]_block_invoke : 968 -> 972
~ -[ASCompetitionStore _queue_saveCompetitionListsToCache:owner:] : 476 -> 472
~ -[ASActivityDataNotificationManager samplesAdded:anchor:] : 748 -> 736
~ -[ASActivityDataNotificationManager samplesOfTypesWereRemoved:anchor:] : 480 -> 476
~ -[ASActivityDataNotificationManager _notifyAboutWorkoutsDetectionIfRequired:] : 472 -> 468
~ -[ASFriendInviteBulletinManager processPendingResponses] : 336 -> 332
~ -[ASIDSMessageCenter _idsIdentifiersForDestinations:] : 372 -> 368
~ -[ASCompetitionAwardingSource _queue_earnedInstancesForInterval:selectingCompetitionsUsingFilter:] : 1800 -> 1796
~ -[ASCompetitionAwardingSource _allCompetitionsOrderedByEndDate] : 380 -> 376
~ ___74-[ASGizmoBulletinPostingManager _postQueuedNotificationRequestsIfPossible]_block_invoke_3 : 1484 -> 1480
~ -[ASGizmoBulletinPostingManager _queue_postNotificationRequests:] : 364 -> 360
~ ___72-[ASCompetitionManager cloudKitManager:didBeginUpdatesForFetchWithType:]_block_invoke : 1100 -> 1096
~ ___112-[ASCompetitionManager cloudKitManager:didReceiveNewCompetitionListsForSelf:moreComing:changesProcessedHandler:]_block_invoke : 1528 -> 1524
~ ___105-[ASCompetitionManager cloudKitManager:didReceiveNewCompetitionLists:moreComing:changesProcessedHandler:]_block_invoke : 740 -> 736
~ ___117-[ASCompetitionManager cloudKitManager:didEndUpdatesForFetchWithType:activity:cloudKitGroup:changesProcessedHandler:]_block_invoke : 2216 -> 2232
~ -[ASCompetitionManager _queue_updateScoresWithTodaySummary:yesterdaySummary:activity:cloudKitGroup:] : 2868 -> 2828
~ ___86-[ASCompetitionManager _queue_notifyObserversOfCompetitionUpdatesForFriendsWithUUIDs:]_block_invoke : 252 -> 248
~ ___65-[ASCompetitionManager _loadCachedCompetitionsAndNotifyObservers]_block_invoke : 252 -> 248
~ -[ASDatabaseClient dealloc] : 312 -> 308
~ ___74-[ASDatabaseClient _handleProtectedDataAvailabilityDidChangeNotification:]_block_invoke : 268 -> 264
~ ___74-[ASDatabaseClient _handleProtectedDataAvailabilityDidChangeNotification:]_block_invoke_2 : 256 -> 252
~ ___50-[ASDatabaseClient _handleCurrentActivitySummary:]_block_invoke : 260 -> 256
~ -[ASDatabaseClient _observerQueue_handleYesterdayActivitySummaryUpdate] : 416 -> 412
~ -[ASDatabaseClient addSampleObserver:sampleTypes:] : 776 -> 772
~ -[ASDatabaseClient removeSampleObserver:sampleTypes:] : 452 -> 448
~ ___71-[ASDatabaseClient _handleNanoAlertSuppressionInvalidatedNotification:]_block_invoke : 252 -> 248
~ -[ASDatabaseClient daemonReady:] : 416 -> 412
~ -[ASRelationshipManager initWithIsWatch:] : 668 -> 664
~ -[ASRelationshipManager beginReceivingMessages] : 308 -> 304
~ -[ASRelationshipManager endReceivingMessages] : 296 -> 292
~ ___106-[ASRelationshipManager updateRelationshipsForCurrentFeatureSupportWithActivity:cloudKitGroup:completion:]_block_invoke : 1004 -> 1000
~ ___106-[ASRelationshipManager updateRelationshipsForCurrentFeatureSupportWithActivity:cloudKitGroup:completion:]_block_invoke_2 : 592 -> 588
~ ___124-[ASRelationshipManager cloudKitManager:didReceiveNewRelationships:fromRecordZoneWithID:moreComing:changesProcessedHandler:]_block_invoke : 728 -> 724
~ ___153-[ASRelationshipManager cloudKitManager:didReceiveNewRemoteRelationships:fromRecordZoneWithID:moreComing:activity:cloudKitGroup:changesProcessedHandler:]_block_invoke : 724 -> 720
~ ___96-[ASRelationshipManager saveRelationships:extraRecordsToSave:cloudKitGroup:activity:completion:]_block_invoke_2 : 740 -> 736
~ ___84-[ASRelationshipManager _queue_fetchSharesForRelationship:cloudKitGroup:completion:]_block_invoke : 252 -> 248
~ ___84-[ASRelationshipManager _queue_fetchSharesForRelationship:cloudKitGroup:completion:]_block_invoke.479 -> ___84-[ASRelationshipManager _queue_fetchSharesForRelationship:cloudKitGroup:completion:]_block_invoke.485 : 252 -> 248
~ ___104-[ASRelationshipManager _queue_saveRelationshipAndFetchOrCreateShares:contact:cloudKitGroup:completion:]_block_invoke_2.484 -> ___104-[ASRelationshipManager _queue_saveRelationshipAndFetchOrCreateShares:contact:cloudKitGroup:completion:]_block_invoke_2.490 : 428 -> 424
~ ___93-[ASRelationshipManager _queue_processRemoteRelationships:activity:cloudKitGroup:completion:]_block_invoke : 972 -> 964
~ -[ASGatewayManager _shouldFilterBlacklistContactDestinations:] : 504 -> 500
~ -[ASGatewayManager _queue_notifyObservers] : 316 -> 312
~ -[ASCloudKitUtility createRecordZonesWithIDs:priority:useZoneWideSharing:group:completion:] : 728 -> 724
~ -[ASCloudKitUtility _saveRecordsIntoPrivateDatabaseCreatingZones:recordIDsToDelete:savePolicy:priority:activity:useZoneWideSharing:group:completion:] : 664 -> 660
~ ___149-[ASCloudKitUtility _saveRecordsIntoPrivateDatabaseCreatingZones:recordIDsToDelete:savePolicy:priority:activity:useZoneWideSharing:group:completion:]_block_invoke : 736 -> 732
~ ___108-[ASCloudKitUtility createShareAndAssociatedZoneWithShareRecordID:rootRecord:otherRecordsToSave:completion:]_block_invoke : 552 -> 548
~ -[ASCloudKitUtility addParticipant:toShares:group:completion:] : 704 -> 700
~ __ASRecordIDsForRecords : 328 -> 324
~ ___86-[ASCloudKitUtility removeParticipantWithCloudKitAddress:fromShares:group:completion:]_block_invoke : 680 -> 676
~ ___46-[ASCloudKitUtility cancelAllExecutingFetches]_block_invoke : 424 -> 420
~ -[ASCloudKitUtility _fetchChangesInZones:additionalZonesToFetch:fetchConfigurations:inDatabase:serverChangeTokenCache:priority:allowRetry:activity:group:completion:] : 2164 -> 2160
~ ___165-[ASCloudKitUtility _fetchChangesInZones:additionalZonesToFetch:fetchConfigurations:inDatabase:serverChangeTokenCache:priority:allowRetry:activity:group:completion:]_block_invoke.407 -> ___165-[ASCloudKitUtility _fetchChangesInZones:additionalZonesToFetch:fetchConfigurations:inDatabase:serverChangeTokenCache:priority:allowRetry:activity:group:completion:]_block_invoke.413 : 1400 -> 1396
```
