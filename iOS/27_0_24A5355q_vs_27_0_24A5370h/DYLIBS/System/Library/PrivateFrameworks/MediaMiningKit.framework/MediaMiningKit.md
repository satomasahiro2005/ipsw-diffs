## MediaMiningKit

> `/System/Library/PrivateFrameworks/MediaMiningKit.framework/MediaMiningKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x82f2c` | `0x82b84` | **`-0x3a8`** |
| `__TEXT.__unwind_info` | `0x21f8` | `0x21f0` | **`-0x8`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0
Functions:
~ -[CLSPublicEventCacheCreator createCacheForTimeLocationTuples:cachingOptions:progressBlock:error:] : 2352 -> 2336
~ -[CLSHolidayCalendarEventRule initWithEventDescription:deviceRegionCode:] : 1100 -> 1096
~ -[CLSHolidayCalendarEventRule _localeOverrideForDescription:uppercaseLocaleCode:] : 784 -> 780
~ -[CLSHolidayCalendarEventRule _dateRuleForDate:supportedLocale:] : 696 -> 692
~ -[CLSHolidayCalendarEventRule _enumerateDatesFromStartDate:toEndDate:supportedLocale:usingBlock:] : 392 -> 388
~ -[CLSHolidayCalendarEventRule _scoreForEventOverride:sceneNames:] : 404 -> 400
~ -[CLSHolidayCalendarEventRule backfillForLanguageCodes:] : 304 -> 300
~ +[CLSHolidayCalendarEventRule localizedSynonymsForHolidayName:] : 460 -> 456
~ -[CLSHolidayCalendarEventRule setDateRuleDelegate:] : 600 -> 592
~ -[CLSSocialServiceCalendar eventFromProxyEvent:] : 1720 -> 1708
~ +[CLSSocialServiceCalendar relevantCalendars:] : 336 -> 332
~ +[CLSSocialServiceCalendar eventAtLocation:withAttendeeNames:matchesClueCollection:] : 640 -> 636
~ -[CLSSocialServiceCalendar _hasAlreadyPrefetchedEventsFromUniversalDate:toUniversalDate:] : 404 -> 400
~ -[CLSSocialServiceCalendar personsFromEventParticipants:excludeCurrentUser:serviceManager:] : 684 -> 680
~ -[CLSServiceManager invalidatePersonsCacheForPersonsWithNames:] : 368 -> 364
~ -[CLSServiceManager invalidatePersonsCacheForPersonsWithContactIdentifiers:] : 368 -> 364
~ +[CLSHolidayCalendarEventRuleRequiredTraits _locationTraitDebugStringForTrait:] : 572 -> 568
~ +[CLSHolidayCalendarEventRuleRequiredTraits _peopleTraitDebugStringForTrait:] : 592 -> 588
~ -[CLSInspector init] : 816 -> 808
~ -[CLSInspector profileIdentifierForHash:] : 344 -> 340
~ -[CLSInspector performInvestigation:options:progressBlock:] : 6060 -> 6036
~ -[CLSLocationQueryPerformer initWithRegions:precision:locationCache:] : 704 -> 700
~ -[CLSLocationQueryPerformer shouldQueryItemsForRegion:selectedRegions:] : 320 -> 316
~ -[CLSLocationCache nearestEntryForCoordinate:entries:] : 376 -> 372
~ ___59-[CLSLocationCache insertBatchesOfPlacemarks:forLocations:]_block_invoke : 548 -> 544
~ -[CLSLocationCache _stringifyAddressDictionaryValues:] : 428 -> 424
~ ___64-[CLSLocationCache invalidateCacheItemsBeforeDateWithTimestamp:]_block_invoke : 488 -> 484
~ ___73-[CLSLocationCache _setPlacemarks:forEntryWithPredicate:entrySetupBlock:]_block_invoke : 592 -> 588
~ -[CLSLocationCache _litePlacemarksFromManagedPlacemarks:] : 368 -> 364
~ -[CLSLocationCache _insertManagedPlacemarksForLitePlacemarks:inContext:] : 376 -> 372
~ -[CLSLocationCache _litePlacemarkFromManagedPlacemark:] : 1440 -> 1436
~ ___73-[CLSLocationCache invalidateCacheForGeoServiceProviderChangeToProvider:]_block_invoke : 1404 -> 1392
~ ___74-[CLSCachedGeocoderOperation performSynchronouslyWithLocationCache:error:]_block_invoke : 428 -> 424
~ -[CLSPartOfDayInformant gatherCluesForInvestigation:progressBlock:] : 504 -> 500
~ -[CLSFocusPeopleCache _collectValidPersonLocalIdentifiers] : 544 -> 540
~ -[CLSPersonIdentity _enumerateAddresses:as:withBlock:] : 672 -> 668
~ __numberOfRelationshipForPersons : 276 -> 272
~ -[CLSPersonIdentity relationshipHintFromNameUsingLocales:] : 712 -> 708
~ -[CLSRegionItemCacheUpdater createCacheForRegions:progressBlock:error:] : 2168 -> 2156
~ -[CLSAssetsBeautifier sampledItemsInSortedItems:maximumNumberOfItemsToChoose:debugInfo:progressBlock:] : 4516 -> 4512
~ -[CLSAssetsBeautifier performWithItems:maximumNumberOfItemsToChoose:debugInfo:progressBlock:] : 3112 -> 3108
~ -[CLSAssetsBeautifier deduplicateItems:withDuration:andSimilarity:debugInfo:] : 780 -> 776
~ -[CLSAssetsBeautifier _clustersBySplittingZeroDiameterClustersInClusters:targetingNumberOfClusters:] : 844 -> 840
~ -[CLSAssetsBeautifier bestItemInItems:] : 1152 -> 1148
~ -[CLSAssetsBeautifier _naturalClusteringBestItemInItems:] : 776 -> 772
~ -[CLSAssetsBeautifier _naturalClusteringWithItems:withSimilarity:timestampSupport:debugInfo:] : 716 -> 712
~ -[CLSAssetsBeautifier requiredItemsInItems:] : 404 -> 400
~ ___81-[CLSBusinessCategoryCache invalidateCacheForGeoServiceProviderChangeToProvider:]_block_invoke : 1404 -> 1392
~ -[CLSBusinessCategoryCache _fetchedBusinessItemByMUIDForBusinessItems:] : 608 -> 600
~ ___68-[CLSBusinessCategoryCache insertBatchesOfBusinessItems:forRegions:]_block_invoke : 776 -> 772
~ -[CLSBusinessCategoryCache nearestItemForRegion:inItems:] : 412 -> 408
~ ___51-[CLSBusinessCategoryCache businessItemsForRegion:]_block_invoke : 692 -> 688
~ ___77-[CLSBusinessCategoryCache businessItemsInRegion:categories:maximumDistance:]_block_invoke : 736 -> 732
~ -[CLSBusinessCategoryCache _businessItemInRegion:matchingCategories:maximumDistance:forBusinessItems:] : 648 -> 644
~ ___50-[CLSBusinessCategoryCache businessItemsForMuids:]_block_invoke : 516 -> 512
~ ___48-[CLSBusinessCategoryCache updateBusinessItems:]_block_invoke : 1008 -> 988
~ +[CLSDBCache urlWithParentURL:] : 376 -> 372
~ ___34-[CLSDBCache invalidateDiskCaches]_block_invoke : 864 -> 860
~ -[CLSInvestigationFeeder _enumerateLocationClustersWithGaussians:enumerationBlock:] : 976 -> 972
~ ___83-[CLSInvestigationFeeder _enumerateLocationClustersWithGaussians:enumerationBlock:]_block_invoke : 432 -> 428
~ -[CLSInvestigationFeeder enumeratePersonNames:withGaussiansUsingBlock:] : 656 -> 652
~ ___87-[CLSInvestigationFeeder _prepareFeederWithServiceManager:locationCache:progressBlock:]_block_invoke : 508 -> 500
~ -[CLSInvestigationFeeder locationClustersWithProgressBlock:] : 1492 -> 1488
~ -[NSCountedSet(CLSNSCountedSet) enumerateObjectsSortedByCountUsingBlock:ascending:] : 600 -> 596
~ _CLSCosineSimilarityBetweenSceneprints : 264 -> 280
~ -[CLSSimilarStacker stackSimilarItems:withSimilarity:timestampSupport:progressBlock:] : 792 -> 788
~ ___85-[CLSSimilarStacker stackSimilarItems:withSimilarity:timestampSupport:progressBlock:]_block_invoke : 472 -> 468
~ -[CLSSimilarStacker adaptiveStackSimilarItems:progressBlock:] : 788 -> 784
~ -[CLSSimilarStacker overrideDistanceThreshold:forSimilarity:] : 20 -> 24
~ ___124-[CLSNewLocationInformant outputLocationCluesForOuputClueKey:inputClue:region:traits:categories:exactMatch:precision:cache:]_block_invoke : 980 -> 976
~ ___124-[CLSNewLocationInformant outputLocationCluesForOuputClueKey:inputClue:region:traits:categories:exactMatch:precision:cache:]_block_invoke_2 : 452 -> 448
~ -[CLSInvestigationPhotoKitFeeder _shouldPrefetchCurationInformation] : 656 -> 652
~ -[CLSInvestigationPhotoKitFeeder hasPeople] : 332 -> 328
~ -[CLSInvestigationPhotoKitFeeder hasFavoritedAssets] : 332 -> 328
~ -[CLSInvestigationPhotoKitFeeder hasBestScoringAssets] : 304 -> 300
~ -[CLSInvestigationPhotoKitFeeder hasNonJunkAssets] : 288 -> 284
~ -[CLSInvestigationPhotoKitFeeder numberOfAllPeople] : 724 -> 720
~ ___51-[CLSPublicEventGeoServiceQuery submitWithHandler:]_block_invoke.7 : 560 -> 556
~ -[CLSPublicEventGeoServiceQuery _publicEventsForGeoEvent:matchingParameters:] : 2628 -> 2616
~ -[CLSPublicEventGeoServiceQuery _parametersByTimeLocationTupleIdentifierForTimeLocationTuples:] : 492 -> 488
~ -[CLSInvestigation description:] : 512 -> 508
~ -[CLSInvestigation tracesDescription] : 788 -> 784
~ +[CLSPartOfDayCalculation partsOfDayForFeeder:] : 784 -> 780
~ -[CLSInputTimeClue _prepareWithProgressBlock:] : 1004 -> 1000
~ -[CLSInputTimeClue _computeDateProperties] : 664 -> 660
~ +[CLSInputLocationClue cluesWithLocations:locationCache:] : 360 -> 356
~ +[CLSInputPeopleClue cluesWithPeoples:serviceManager:] : 360 -> 356
~ +[CLSInputPeopleClue cluesWithPersonLocalIdentifiers:inPhotoLibrary:serviceManager:] : 380 -> 376
~ +[CLSInputPeopleClue cluesWithConsolidatedPersonLocalIdentifiers:inPhotoLibrary:serviceManager:] : 380 -> 376
~ -[CLSFaceIdentificationFetch requestIdentificationOfFaces:error:] : 432 -> 428
~ -[CLSTestInvestigationFeeder approximateLocation] : 292 -> 288
~ -[NSArray(CLSNSArrayExtensions) map:] : 340 -> 336
~ -[CLSLRUMemoryCache loadFromURL:] : 796 -> 788
~ -[CLSBusinessCacheUpdater enrichedBusinessItemsByMuidsForBusinessItems:progressBlock:] : 2276 -> 2268
~ ___86-[CLSBusinessCacheUpdater enrichedBusinessItemsByMuidsForBusinessItems:progressBlock:]_block_invoke : 716 -> 712
~ -[CLSBusinessCacheUpdater enrichedBusinessItemsByMuidsForMuids:progressBlock:] : 1932 -> 1924
~ ___78-[CLSBusinessCacheUpdater enrichedBusinessItemsByMuidsForMuids:progressBlock:]_block_invoke : 712 -> 708
~ ___70-[CLSBusinessCacheUpdater _resolvedBusinessMUIDs:progressBlock:error:]_block_invoke_2 : 472 -> 468
~ -[NSData(CLSNSDataCryptoExtensions) cls_hexString] : 268 -> 264
~ -[CLSBusinessItemGenericQueryPerformer initWithRegions:categories:precision:businessCategoryCache:locationCache:] : 680 -> 676
~ ___58-[CLSBusinessItemGenericQueryPerformer submitWithHandler:]_block_invoke : 1164 -> 1160
~ -[CLSBusinessItemGenericQueryPerformer shouldQueryItemsForRegion:selectedRegions:] : 444 -> 440
~ -[CLSBusinessItemGenericQueryPerformer cacheItems:] : 1452 -> 1448
~ -[CLSAreaOfInterestQueryPerformer shouldQueryItemsForRegion:selectedRegions:] : 368 -> 364
~ -[CLSRoutineService isRemoteLocation:inDateInterval:] : 756 -> 752
~ -[CLSRoutineService predominantTransportationModeForDateInterval:confidence:] : 792 -> 784
~ -[CLSRoutineService _buildLocationsOfInterestCache] : 1752 -> 1744
~ -[CLSRoutineService _pinPendingVisits] : 1148 -> 1140
~ -[CLSRoutineService _placemarksFromLocationsOfInterest:] : 368 -> 364
~ -[CLSEKEvent initWithEKEvent:] : 824 -> 820
~ -[CLSEKCalendar initWithEKCalendar:] : 480 -> 476
~ -[CLSClueCollection description] : 3228 -> 3212
~ -[CLSClueCollection inputClues] : 348 -> 344
~ -[CLSClueCollection uniqueInputClues] : 388 -> 384
~ -[CLSClueCollection outputCluesForKey:] : 360 -> 356
~ -[CLSClueCollection uniqueOutputCluesForKey:] : 400 -> 396
~ -[CLSClueCollection uniqueOutputClueForKey:andValue:] : 548 -> 544
~ -[CLSClueCollection uniqueOutputClues] : 348 -> 344
~ -[CLSClueCollection outputClues] : 492 -> 488
~ -[CLSClueCollection hasOutputClueWithKey:value:andMinimumScore:] : 376 -> 372
~ -[CLSClueCollection meaningClues] : 348 -> 344
~ -[CLSClueCollection uniqueMeaningClues] : 348 -> 344
~ -[CLSClueCollection meaningCluesForKey:] : 360 -> 356
~ -[CLSClueCollection uniqueMeaningCluesForKey:] : 400 -> 396
~ -[CLSClueCollection uniqueMeaningClueForKey:andValue:] : 548 -> 544
~ -[CLSClueCollection hasMeaningClueWithKey:value:andMinimumScore:] : 376 -> 372
~ -[CLSClueCollection prepareWithProgressBlock:] : 256 -> 252
~ -[CLSClueCollection mergeClues:] : 568 -> 576
~ -[CLSInvestigationHelper enumerateTaxonomyNodesLevelsAndWeightsStartingWithNode:usingBlock:] : 988 -> 980
~ __maxTaxonomyNodeLevel : 404 -> 400
~ -[CLSPublicEventManager publicEventsByTimeLocationTupleIdentifierForTimeLocationTuples:cachingOptions:progressBlock:error:] : 2000 -> 1996
~ -[CLSPublicEventManager loadInvalidationTokensAndInvalidateCachesIfNeeded] : 1316 -> 1312
~ -[CLSPublicEventManager _invalidateStaleTimeLocationTuplesInResult:allCachedTimeLocationTuples:analyticsPayload:error:] : 1656 -> 1648
~ -[CLSLocationOfInterestCache addLocationOfInterest:] : 1212 -> 1204
~ -[CLSLocationOfInterestCache closestLocationOfInterestVisitToLocation:withinDistance:inDateInterval:] : 580 -> 576
~ -[CLSLocationOfInterestCache locationOfInterestAtLocation:] : 432 -> 428
~ -[CLSLocationOfInterestCache locationsOfInterestVisitsAtLocation:inDateInterval:] : 2012 -> 2008
~ -[CLSLocationOfInterestCache mergeHighConfidenceVisits:withLowConfidenceVisits:] : 344 -> 340
~ -[CLSLocationOfInterestCache addLocationOfInterestTransition:] : 940 -> 936
~ -[CLSLocationOfInterestCache locationsOfInterestTransitionInDateInterval:] : 868 -> 864
~ -[CLSSocialServiceContacts _personResultsForfullName:] : 1036 -> 1032
~ -[CLSSocialServiceContacts __newPersonWithContact:viewPerson:] : 2024 -> 2012
~ -[CLSSocialServiceContacts _addMissingPropertiesToPerson:withViewPerson:] : 1152 -> 1144
~ -[CLSSocialServiceContacts _addAddressesToPerson:withContact:] : 540 -> 536
~ -[CLSSocialServiceContacts _relationshipForContact:] : 936 -> 932
~ -[CLSSocialServiceContacts enumerateAllPersonsUsingBlock:] : 740 -> 736
~ -[CLSSocialServiceContacts personsInContactStoreForContactIdentifiers:needsRefetching:progressBlock:] : 1260 -> 1248
~ -[CLSSocialServiceContacts enumeratePersonsForIdentifiers:usingBlock:] : 1004 -> 992
~ ___92-[CLSSocialServiceContacts personLocalIdentifierMatchingContactPictureForContactIdentifier:]_block_invoke.281 : 904 -> 900
~ -[CLSSocialServiceContacts enumeratePersonsForFullName:usingBlock:] : 588 -> 584
~ -[CLSSocialServiceContacts _personsMatchingPredicate:] : 640 -> 636
~ -[CLSSocialServiceContacts enumeratePersonsAndPotentialBirthdayDateForContactIdentifiers:usingBlock:] : 420 -> 416
~ -[CLSSocialServiceContacts potentialBirthdayDateForCNIdentifier:fullName:] : 1068 -> 1060
~ ___76-[CLSCalendarEventsCache enumerateEventsFromStartDate:toEndDate:usingBlock:]_block_invoke : 452 -> 448
~ +[CLSCalculation calculateStandardDeviationForItems:valueBlock:result:] : 464 -> 460
~ +[CLSSummaryClustering scoreForItems:] : 296 -> 292
~ +[CLSSummaryClustering meanScoreForItems:] : 280 -> 276
~ +[CLSSummaryClustering maximumScoreForItems:] : 268 -> 264
~ -[CLSSummaryClustering densityClustersWithItems:progressBlock:] : 364 -> 360
~ -[CLSSummaryClustering _densityClustersWithItems:progressBlock:] : 1416 -> 1408
~ -[CLSSummaryClustering performWithItems:identifiersOfEligibleItems:maximumNumberOfItemsToElect:debugInfo:progressBlock:] : 2048 -> 2044
~ -[CLSSummaryClustering adaptiveElection:identifiersOfEligibleItems:maximumNumberOfItemsToElect:debugInfo:progressBlock:] : 2948 -> 2928
~ +[CLSLitePlacemark popularityScoresOrderedByAOIFromAdditionalPlaceInfos:areasOfInterest:] : 832 -> 824
~ +[CLSLitePlacemark _isIslandForGeoMapItem:] : 360 -> 356
~ -[CLSTimeZones _importDataBaseFromFile:] : 664 -> 660
~ -[CLSTimeZones closestZoneInfoWithLocation:source:] : 388 -> 384
~ +[CLSHolidayCalendarEventRulesFactory allSupportedCountryCodesInDeviceRegion:] : 412 -> 408
~ +[CLSHolidayCalendarEventRulesFactory _allEventRulesForEventRulesDictionaries:deviceRegionCode:] : 360 -> 356
~ -[CLSHolidayDetectedScenes recordDetectedSceneImportance:] : 32 -> 36
~ -[CLSSocialServiceCoreNameParser _normalizeName:] : 572 -> 568
~ -[CLSSocialServiceCoreNameParser relationshipHintForPerson:usingLocales:] : 1036 -> 1028
~ -[CLSHolidayCalendarEventService initWithEventRules:locale:] : 352 -> 348
~ -[CLSHolidayCalendarEventService sceneNamesForHolidayName:] : 364 -> 360
~ -[CLSHolidayCalendarEventService peopleTraitForHolidayName:] : 336 -> 332
~ -[CLSHolidayCalendarEventService eventRulesForLocalDate:] : 364 -> 360
~ -[CLSHolidayCalendarEventService eventRuleForHolidayName:localDate:] : 416 -> 412
~ -[CLSHolidayCalendarEventService _enumerateEventRulesWithNames:betweenLocalDate:andLocalDate:supportedCountryCode:usingBlock:] : 1028 -> 1024
~ -[CLSHolidayCalendarEventService triggerHolidaysForCountryCode:] : 324 -> 320
~ -[CLSHolidayCalendarEventService eventRuleForHolidayName:] : 352 -> 348
~ -[CLSHolidayCalendarEventService supportedLanguageCodes] : 356 -> 352
~ -[CLSHolidayCalendarEventService _ruleWithUUID:countryCode:] : 552 -> 548
~ -[CLSCurationDebugObject dictionaryRepresentation] : 692 -> 688
~ -[CLSCurationDebugCluster allDebugItems] : 340 -> 336
~ -[CLSCurationDebugCluster setDebugClusters:] : 412 -> 408
~ -[CLSCurationDebugCluster addDebugClusters:] : 376 -> 372
~ -[CLSCurationDebugCluster resetWithReason:agent:stage:] : 392 -> 388
~ -[CLSCurationDebugCluster dictionaryRepresentation] : 1212 -> 1200
~ -[CLSCurationDebugCluster timestamp] : 540 -> 532
~ -[CLSCurationDebugInfo initWithItems:] : 472 -> 468
~ -[CLSCurationDebugInfo initWithDebugCluster:] : 396 -> 392
~ -[CLSCurationDebugInfo debugItemsForItems:] : 332 -> 328
~ -[CLSCurationDebugInfo setClusters:withReason:] : 556 -> 552
~ -[CLSCurationDebugInfo addClusters:withReason:] : 480 -> 476
~ -[CLSCurationDebugInfo setState:ofCluster:withReason:] : 452 -> 448
~ -[CLSCurationDebugInfo setState:ofItems:withReason:] : 292 -> 288
~ -[CLSCurationDebugInfo setUnclusteredItemsState:withReason:] : 312 -> 308
~ -[CLSCurationDebugInfo chooseItems:inItems:withReason:] : 364 -> 360
~ -[CLSCurationDebugInfo requireItems:inItems:] : 360 -> 356
~ -[CLSCurationDebugInfo _dedupItems:toItems:chosenState:withDedupingType:] : 776 -> 768
~ -[CLSCurationDebugInfo beginTentativeSection] : 244 -> 240
~ -[CLSCurationDebugInfo endTentativeSectionWithSuccess:] : 252 -> 248
~ -[CLSCurationDebugInfo dictionaryRepresentationWithAppendExtraItemInfoBlock:] : 744 -> 740
~ ___73-[CLSPublicEventCache invalidateCacheItemsBeforeDateWithTimestamp:error:]_block_invoke_2 : 484 -> 476
~ -[CLSPublicEventCache updateTimeLocationTuples:withTimestamp:error:] : 996 -> 992
~ ___68-[CLSPublicEventCache updateTimeLocationTuples:withTimestamp:error:]_block_invoke_2 : 248 -> 244
~ ___97-[CLSPublicEventCache insertBatchesOfPublicEventsByTimeLocationIdentifier:forTimeLocationTuples:]_block_invoke : 1156 -> 1152
~ -[CLSPublicEventCache _updateManagedEvent:withEvent:inContext:] : 1640 -> 1624
~ ___43-[CLSPublicEventCache publicEventsForMuid:]_block_invoke : 568 -> 564
~ ___56-[CLSPublicEventCache publicEventsForTimeLocationTuple:]_block_invoke : 636 -> 632
~ -[CLSPublicEventCache publicEventFromManagedObject:] : 1268 -> 1260
~ ___36-[CLSPublicEventCache readAllEvents]_block_invoke : 556 -> 552
~ ___60-[CLSPublicEventCache timeLocationTuplesFromCacheWithError:]_block_invoke : 516 -> 512
~ -[CLSPublicEventCache _removeQueryLocationsForTimeLocationTuples:inContext:error:] : 896 -> 892
~ ___82-[CLSPublicEventCache _removeQueryLocationsForTimeLocationTuples:inContext:error:]_block_invoke : 480 -> 472
~ +[CLSBusinessItem _businessCategoriesFromGeoMapItems:] : 708 -> 704
~ -[CLSClassificationInformant _gatherSceneCluesForInvestigation:signalModelProviderBlock:informantKey:progressBlock:] : 2032 -> 2028
~ ___116-[CLSClassificationInformant _gatherSceneCluesForInvestigation:signalModelProviderBlock:informantKey:progressBlock:]_block_invoke : 1456 -> 1448
~ sub_287842bdc -> sub_2891d77a8 : 3520 -> 3544
~ sub_28784399c -> sub_2891d8580 : 1428 -> 1452
~ sub_287845b50 -> sub_2891da74c : 6724 -> 6832
~ sub_2878486fc -> sub_2891dd364 : 280 -> 276
~ sub_287848bf4 -> sub_2891dd858 : 1412 -> 1436
~ sub_28784934c -> sub_2891ddfc8 : 524 -> 508
~ sub_287849920 -> sub_2891de58c : 692 -> 688
~ sub_28784b088 -> sub_2891dfcf0 : 652 -> 648
~ sub_28784b314 -> sub_2891dff78 : 368 -> 360
~ sub_28784b484 -> sub_2891e00e0 : 412 -> 388
~ sub_28784b620 -> sub_2891e0264 : 368 -> 360
~ sub_28784b790 -> sub_2891e03cc : 368 -> 360
~ sub_28784c9a0 -> sub_2891e15d4 : 272 -> 296
~ sub_28784cab0 -> sub_2891e16fc : 472 -> 468
~ sub_28784cc88 -> sub_2891e18d0 : 272 -> 296
~ sub_28784cd98 -> sub_2891e19f8 : 1848 -> 1840
~ sub_287850538 -> sub_2891e5190 : 568 -> 584
~ sub_287851010 -> sub_2891e5c78 : 476 -> 480
~ sub_287851ec0 -> sub_2891e6b2c : 1424 -> 1416
~ sub_287852568 -> sub_2891e71cc : 1368 -> 1356
```
