## PersonalizationPortrait

> `/System/Library/PrivateFrameworks/PersonalizationPortrait.framework/PersonalizationPortrait`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c69c` | `0x5c49c` | **`-0x200`** |

### Other Changes

```diff

-1331.0.1.0.0
+1334.0.1.0.0
Functions:
~ ___90-[PPSocialHighlightStore iterRankedHighlightsWithLimit:client:variant:reason:error:block:]_block_invoke_2 : 540 -> 536
~ ___90-[PPSocialHighlightStore iterRankedHighlightsWithLimit:client:variant:reason:error:block:]_block_invoke : 532 -> 528
~ ___87-[PPConnectionsStore iterRecentLocationsForConsumer:criteria:limit:client:error:block:]_block_invoke : 296 -> 292
~ ___58-[PPContactStore iterRankedContactsWithQuery:error:block:]_block_invoke : 296 -> 292
~ -[PPQuickTypeExplanationSet initWithCoder:] : 604 -> 600
~ -[PPNotificationHandler _executeBlocksWithGuardedData:] : 632 -> 628
~ -[PPRecordMonitoringHelper sendChangesToDelegatesWithChangeGenerator:recordGenerator:] : 604 -> 600
~ ___94-[PPRecordMonitoringHelper _handleRecentChangesWithDelegates:changeGenerator:recordGenerator:]_block_invoke : 1112 -> 1108
~ +[PPQuickTypeQuery _fieldsFromStrings:] : 340 -> 336
~ ___60-[PPLocationStore iterRankedLocationsWithQuery:error:block:]_block_invoke : 328 -> 324
~ ___60-[PPLocationStore iterLocationRecordsWithQuery:error:block:]_block_invoke : 328 -> 324
~ ___85-[PPTemporalClusterStore iterRankedTemporalClustersForStartDate:endDate:error:block:]_block_invoke : 296 -> 292
~ ___70-[PPXPCNamedEntityStore iterRankedNamedEntitiesWithQuery:error:block:]_block_invoke : 296 -> 292
~ -[PPXPCNamedEntityStore rankedNamedEntitiesWithQuery:error:] : 772 -> 768
~ ___69-[PPXPCNamedEntityStore iterNamedEntityRecordsWithQuery:error:block:]_block_invoke : 296 -> 292
~ -[PPXPCNamedEntityStore namedEntityRecordsWithQuery:error:] : 772 -> 768
~ ___50-[PPXPCNamedEntityStore _recordGeneratorForQuery:]_block_invoke.40 : 344 -> 340
~ ___50-[PPXPCNamedEntityStore unloadMonitoringDelegate:]_block_invoke : 276 -> 272
~ -[PPAttendee initWithName:emailAddress:urlString:isCurrentUser:status:] : 668 -> 632
~ -[PPEvent initWithEventIdentifier:objectID:title:location:calendar:startDate:endDate:availability:externalURIString:attendees:organizerName:eventFlags:notes:urlString:structuredLocationTitle:structuredLocationAddress:structuredLocationCoordinates:suggestedEventCategory:] : 1964 -> 1872
~ -[PPEvent isEqual:] : 660 -> 656
~ ___57-[PPXPCTopicStore iterRankedTopicsWithQuery:error:block:]_block_invoke : 296 -> 292
~ -[PPXPCTopicStore rankedTopicsWithQuery:error:] : 772 -> 768
~ ___63-[PPXPCTopicStore iterScoresForTopicMapping:query:error:block:]_block_invoke : 356 -> 352
~ -[PPXPCTopicStore scoresForTopicMapping:query:error:] : 1012 -> 1008
~ ___57-[PPXPCTopicStore iterTopicRecordsWithQuery:error:block:]_block_invoke : 296 -> 292
~ -[PPXPCTopicStore topicRecordsWithQuery:error:] : 772 -> 768
~ -[PPNamedEntityMetadata featureValueForName:] : 148 -> 144
~ -[PPTemporalCluster longDescription] : 2240 -> 2224
~ +[PPUtils hexOfBytes:size:] : 228 -> 240
~ +[PPUtils coordinatesToGeoHashWithLength:latitude:longitude:] : 444 -> 448
~ ___41+[PPUtils jaroSimilarityForString:other:]_block_invoke_2 : 536 -> 532
~ +[PPUtils sqliteGlobEscape:] : 804 -> 796
~ ___62-[PPContactStore iterContactNameRecordsForClient:error:block:]_block_invoke : 296 -> 292
~ -[PPFeedback initWithExplicitlyEngagedStrings:explicitlyRejectedStrings:implicitlyEngagedStrings:implicitlyRejectedStrings:offeredStrings:] : 1172 -> 1152
~ -[PPRecordMonitoringHelper loadRecordsWithDelegate:recordGenerator:] : 892 -> 888
~ -[PPRecordMonitoringHelper sendResetToAllDelegatesWithRecordGenerator:] : 520 -> 516
~ ___58-[PPEventStore iterEventNameRecordsForClient:error:block:]_block_invoke : 296 -> 292
~ ___63-[PPEventStore iterEventHighlightsFrom:to:options:error:block:]_block_invoke : 364 -> 360
~ ___54-[PPEventStore iterScoredEventsWithQuery:error:block:]_block_invoke : 364 -> 360
~ ___53-[PPEventStore interactionSummaryMetricsError:block:]_block_invoke : 296 -> 292
~ -[PPSpotlightScoringFeatureVector encodeAsData] : 456 -> 452
~ ___46-[PPReranker _lazyLoadEntityRankMapWithError:]_block_invoke : 516 -> 512
~ ___87-[PPSocialHighlightStore iterRankedCollaborationsWithLimit:client:variant:error:block:]_block_invoke : 296 -> 292
~ ___88-[PPSocialHighlightStore iterRankedHighlightsForSyncedItems:client:variant:error:block:]_block_invoke : 296 -> 292
~ +[PPCustomDonation donateSiriQuery:results:error:] : 1408 -> 1404
~ -[PPEventHighlight hash] : 436 -> 432
~ _PPStringLooksLikeNumber : 480 -> 476
~ _PPStringFirstNumber : 716 -> 620
~ -[PPBaseFeedback description] : 496 -> 492
~ -[PPContact initWithContactsContact:] : 2588 -> 2572
~ -[PPContact initWithFoundInAppsContact:] : 1580 -> 1568
~ -[PPContact hash] : 916 -> 900
~ -[PPTripEvent destinations] : 312 -> 308
~ ___78-[PPConnectionsStore iterRecentLocationDonationsSinceDate:client:error:block:]_block_invoke : 296 -> 292
~ ___102-[PPConnectionsStore iterRecentLocationsForConsumer:criteria:limit:explanationSet:client:error:block:]_block_invoke : 296 -> 292
~ -[PPContactQuery hash] : 424 -> 420
~ -[PPMappedFeedback initWithExplicitlyEngagedStrings:explicitlyRejectedStrings:implicitlyEngagedStrings:implicitlyRejectedStrings:offeredStrings:mappingId:] : 1192 -> 1172
~ -[PPContactNameRecord hash] : 1148 -> 1136
```
