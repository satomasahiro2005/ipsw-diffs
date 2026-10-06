## ActivitySharing

> `/System/Library/PrivateFrameworks/ActivitySharing.framework/ActivitySharing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43868` | `0x436c8` | **`-0x1a0`** |

### Other Changes

```diff

-2027.0.11.0.0
+2027.0.12.0.0
Functions:
~ -[ASCompetition _scoresForParticipant:] : 28 -> 24
~ __ConsolidatedEvents : 2920 -> 2916
~ -[ASRelationshipStorage updateRelationship:cloudType:] : 88 -> 84
~ -[ASRelationship _updateCurrentRelationshipState] : 1492 -> 1488
~ -[ASCodableActivityDataPreview dictionaryRepresentation] : 800 -> 792
~ -[ASCodableActivityDataPreview writeTo:] : 528 -> 520
~ -[ASCodableActivityDataPreview copyWithZone:] : 600 -> 592
~ -[ASCodableActivityDataPreview mergeFrom:] : 548 -> 540
~ __ASCreateRecordsFromCloudKitCodablesAndRecordZoneID : 368 -> 364
~ _ASCodableAchievementsFromAchievements : 340 -> 336
~ _ASAchievementsFromCodableAchievements : 376 -> 372
~ _ASCodableWorkoutsFromWorkouts : 340 -> 336
~ _ASWorkoutsFromCodableWorkouts : 376 -> 372
~ -[ASRelationship(CloudKitCodingSupport) codableRelationship] : 992 -> 984
~ +[ASRelationship(CloudKitCodingSupport) _relationshipWithRecord:relationshipEventRecords:completion:] : 2064 -> 2060
~ +[ASRelationship(CloudKitCodingSupport) relationshipWithCodableRelationship:version:] : 1052 -> 1048
~ +[ASRelationship(CloudKitCodingSupport) relationshipsWithRelationshipAndEventRecords:] : 660 -> 652
~ -[ASCompetition(CloudKitCoding) codableCompetition] : 808 -> 796
~ -[ASReachabilityManager _addDestinationsToQuery:updateHandler:completionHandler:] : 956 -> 952
~ -[ASFriend(DomainCodable) codableFriendIncludingCloudKitFields:] : 924 -> 916
~ _ASCodableFriendListFromFriends : 324 -> 320
~ _ASCodableContactListFromContacts : 324 -> 320
~ -[ASCodableCloudKitCompetition writeTo:] : 476 -> 464
~ -[ASCodableContact writeTo:] : 588 -> 584
~ -[ASCodableContact copyWithZone:] : 700 -> 696
~ -[ASCodableContact mergeFrom:] : 632 -> 628
~ -[ASCodableFriend dictionaryRepresentation] : 1224 -> 1208
~ -[ASCodableFriend writeTo:] : 808 -> 792
~ -[ASCodableFriend copyWithZone:] : 904 -> 888
~ -[ASCodableFriend mergeFrom:] : 812 -> 796
~ -[ASRelationship timestampForMostRecentRelationshipEvent] : 372 -> 368
~ -[ASRelationship currentRelationshipEventAnchor] : 268 -> 264
~ -[ASCodableCloudKitCompetitionList dictionaryRepresentation] : 528 -> 524
~ -[ASCodableCloudKitCompetitionList writeTo:] : 364 -> 360
~ -[ASCodableCloudKitCompetitionList copyWithZone:] : 420 -> 416
~ -[ASCodableCloudKitCompetitionList mergeFrom:] : 364 -> 360
~ _ASSanitizedContactDestinations : 320 -> 316
~ __FindIntersectingDestination : 316 -> 312
~ _ASPreferredCompetitionVictoryBadgeStylesForFriend : 2232 -> 2220
~ _ASBestCompetitionVictoryBadgeStyleForPreferredStyles : 832 -> 828
~ -[ASRelationshipStorage relationshipForCloudType:] : 28 -> 24
~ -[ASRelationshipStorage remoteRelationshipForCloudType:] : 28 -> 24
~ -[ASRelationshipStorage updateRemoteRelationship:cloudType:] : 88 -> 84
~ -[ASReachabilityQueryOperation start] : 1600 -> 1596
~ __FindQueryItemValue : 388 -> 384
~ _ASUniqueItemsInArrayPreferringLastOccurance : 376 -> 372
~ _ASCompetitionWinningDayWithHighestScoreForParticipant : 508 -> 504
~ _ASFriendsSortedByCompetitionEndDateForFirstGlanceType : 396 -> 392
~ _ASPairedDeviceSupportsCompetitions : 296 -> 292
~ +[ASCompetition(DatabaseCodingSupport) codableDatabaseCompetitionsFromCompetitions:withFriendWithUUID:withType:] : 448 -> 444
~ +[ASCompetitionList(DatabaseCodingSupport) competitionListFromCodableDatabaseCompetitionList:codableCompetitions:withType:] : 588 -> 584
~ +[ASSampleCollector sampleDictionaryByIndex:sampleIndexBlock:] : 560 -> 556
~ _ASSnapshotDictionaryByIndex : 476 -> 472
~ -[NSSet(ActivitySharing) as_autoreleasingCompactMap:] : 384 -> 380
~ -[ASCodableDatabaseCompetitionPreferredVictoryBadgeStyles writeTo:] : 104 -> 100
~ -[ASCodableDatabaseCompetitionScore writeTo:] : 104 -> 100
~ -[ASActivityDataNotificationRulesEngine _filterNotificationGroup:ruleset:] : 1832 -> 1820
~ -[ASBulletinStore removeBulletinsMatchingCriteria:] : 540 -> 536
~ -[ASCodableCloudKitRelationship dictionaryRepresentation] : 1060 -> 1056
~ -[ASCodableCloudKitRelationship writeTo:] : 908 -> 900
~ -[ASCodableCloudKitRelationship copyWithZone:] : 1068 -> 1060
~ -[ASCodableCloudKitRelationship mergeFrom:] : 896 -> 888
~ ___53-[ASReachabilityStatusCache statusesForDestinations:]_block_invoke : 352 -> 348
~ -[ASCodableFriendList dictionaryRepresentation] : 404 -> 400
~ -[ASCodableFriendList writeTo:] : 276 -> 272
~ -[ASCodableFriendList copyWithZone:] : 316 -> 312
~ -[ASCodableFriendList mergeFrom:] : 260 -> 256
~ -[ASFriend earliestCompetitionVictoryOrPotentialVictoryDate] : 468 -> 464
~ -[ASFriend estimatedIsStandaloneForSnapshotIndex:] : 652 -> 648
~ -[ASCodableContactList dictionaryRepresentation] : 404 -> 400
~ -[ASCodableContactList writeTo:] : 276 -> 272
~ -[ASCodableContactList copyWithZone:] : 316 -> 312
~ -[ASCodableContactList mergeFrom:] : 260 -> 256
~ _ASAnalyticsUpdateWithFriends : 632 -> 628
```
