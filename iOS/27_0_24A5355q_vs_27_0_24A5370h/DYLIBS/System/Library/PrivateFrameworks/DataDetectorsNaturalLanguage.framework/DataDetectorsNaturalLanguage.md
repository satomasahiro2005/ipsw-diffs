## DataDetectorsNaturalLanguage

> `/System/Library/PrivateFrameworks/DataDetectorsNaturalLanguage.framework/DataDetectorsNaturalLanguage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2689c` | `0x265a4` | **`-0x2f8`** |

### Other Changes

```text
Functions:
~ -[IPMessageUnit setFeatures:] : 632 -> 628
~ -[IPMessageUnit features] : 708 -> 704
~ -[IPMessageUnit rejectionRanges] : 672 -> 668
~ -[IPMessageUnit neutralRanges] : 676 -> 672
~ -[IPMessageUnit proposalAndAcceptationRanges] : 676 -> 672
~ -[IPFeatureScanner featuresForTextString:inMessageUnit:extractors:context:] : 1288 -> 1284
~ -[IPFeatureScanner _nearbyFeatureDatas:fromFeatureAtIndex:messageUnit:] : 768 -> 748
~ -[IPFeatureScanner _nearbyFeatureSentences:fromFeatureAtIndex:messageUnit:] : 492 -> 488
~ -[IPFeatureScanner augmentDetectedDatesWithEndDates:] : 572 -> 568
~ -[IPFeatureScanner dataFeaturesInTheFutureFromDataFeatures:messageUnitSentDate:] : 416 -> 412
~ -[IPFeatureScanner dataFeatures:containDateOlderThan:preciseTimeOnly:] : 608 -> 604
~ -[IPFeatureScanner isEventProposalOrConfirmationFromFeatures:fromFeatureAtIndex:messageUnit:eventIsTenseDependent:extractedFromSubject:extractedPolarity:polarityInfluencedByIpsosPlistRef:] : 3952 -> 3968
~ -[IPFeatureScanner _stitchedEventsFromEvents:] : 1948 -> 1944
~ -[IPFeatureScanner _regroupEventsWithSpreadTimeAsAllDayEvents:] : 808 -> 800
~ -[IPFeatureScanner adjustTimeForEvents:] : 244 -> 240
~ -[IPFeatureScanner filteredEventsForDetectedEvents:referenceDate:] : 4720 -> 4708
~ -[IPFeatureScanner normalizedEvents:] : 388 -> 384
~ -[IPFeatureScanner bestEventsFromEvents:] : 364 -> 360
~ -[IPFeatureScanner stringsFromDataFeatures:matchingTypes:] : 428 -> 424
~ -[IPFeatureScanner enrichEvents:messageUnits:dateInSubject:dataFeatures:] : 2376 -> 2344
~ -[IPFeatureScanner confidenceForEvents:] : 296 -> 292
~ ___71-[IPFeatureScanner analyzeFeatures:messageUnit:checkPolarity:polarity:]_block_invoke_2 : 2504 -> 2500
~ -[IPFeatureMailScanner featuresForTextString:inMessageUnit:] : 1448 -> 1440
~ -[IPFeatureMailScanner doSynchronousScanWithCompletionHandler:] : 4516 -> 4500
~ -[IPFeatureMailScanner processScanOfMessageUnit:] : 3360 -> 3348
~ -[IPFeatureMailScanner enrichEvents:messageUnits:dateInSubject:dataFeatures:] : 2348 -> 2380
~ -[IPFeatureMailScanner confidenceForEvent:baseConfidence:] : 1280 -> 1276
~ -[IPFeatureMailScanner emailParticipantNames] : 432 -> 428
~ -[IPFeatureTextMessageScanner mainSentencePolarityFrom:] : 508 -> 504
~ -[IPFeatureTextMessageScanner processScanOfMainMessageUnit:contextMessageUnits:] : 2132 -> 2116
~ -[IPFeatureTextMessageScanner confidenceForEvents:] : 800 -> 796
~ -[IPFeatureTextMessageScanner confidenceForEvent:baseConfidence:] : 640 -> 636
~ -[IPFeatureTextMessageScanner experimentalConfidenceForEvents:] : 612 -> 608
~ -[IPFeatureTextMessageScanner eventSpecificComponentsForConfidence:] : 880 -> 872
~ -[IPFeatureTextMessageScanner commonComponentsForConfidence] : 2368 -> 2348
~ +[IPQuoteParser strippedQuoteBlockWithHtml:] : 4560 -> 4264
~ -[IPMessage initWithSGIPMessage:] : 712 -> 708
~ -[IPMessage setMessageUnits:] : 268 -> 264
~ -[IPKeywordFeatureExtractor featuresForTextString:inMessageUnit:context:] : 968 -> 964
~ -[IPKeywordFeatureExtractor matchesForTextString:inMessageUnit:eventType:] : 1008 -> 1000
~ -[IPKeywordFeatureExtractor _matchingKeywordsForRegex:inText:message:eventType:keywordType:] : 796 -> 792
~ -[IPDataDetectorsFeatureExtractor featuresForTextString:inMessageUnit:context:] : 3308 -> 3300
~ ___79-[IPDataDetectorsFeatureExtractor featuresForTextString:inMessageUnit:context:]_block_invoke : 6080 -> 6012
~ -[IPDataDetectorsFeatureExtractor standardizeTimezonesForDetectedFeatures:] : 540 -> 536
~ -[IPDataDetectorsFeatureExtractor setTimeZone:forDateFeatures:] : 684 -> 680
~ -[IPDataDetectorsFeatureExtractor stringByReplacingDetectedDataWithNGramMarkersInString:] : 516 -> 512
~ -[IPCircularBufferArray countByEnumeratingWithState:objects:count:] : 200 -> 196
~ _lengthOfPatternAfterUncapturing : 476 -> 488
~ ___90-[IPTextMessageConversation _scanEventsInLastMessageOnly:synchronously:completionHandler:]_block_invoke_2 : 1556 -> 1552
~ ___90-[IPTextMessageConversation _scanEventsInLastMessageOnly:synchronously:completionHandler:]_block_invoke_3 : 420 -> 416
~ +[IPTextMessageConversation collapsedMessagesFromMessages:] : 680 -> 644
~ -[IPFeatureSentence clusterType] : 584 -> 576
~ -[IPFeatureSentence polarityForRange:confidence:] : 868 -> 864
~ -[IPFeatureSentence isQuoteAttributionLine] : 836 -> 832
~ -[IPFeatureKeyword humandReadableEventTypes] : 344 -> 340
~ -[IPEventClassificationType addEventPatterns:] : 792 -> 788
~ -[IPEventClassificationType description] : 916 -> 908
~ +[IPEventClassificationType eventClassificationTypeFromMessageUnit:keywordFeatures:datafeatures:] : 4344 -> 4328
~ +[IPEventClassificationType eventClassificationTypeFromMessageUnit:features:] : 608 -> 600
~ +[IPEventClassificationType eventClassificationTypeFromMessageUnit:features:datafeatures:] : 404 -> 400
~ +[IPEventClassificationType _averageDistanceBetweenFeatureKeyword:featureDates:subjectLength:inSubject:] : 720 -> 716
~ +[IPEventClassificationType _loadTaxonomyForLanguageID:clusterIdentifier:error:] : 7212 -> 7180
~ +[IPEventClassificationType _identifiersForClusters:] : 360 -> 356
~ -[IPEventClassificationType _mealClassificationTypeUsingStartDate:] : 820 -> 816
~ +[IPEventClassificationType eventTypeForMoviesAndLanguageID:] : 364 -> 360
~ +[IPEventClassificationType eventTypeForSportAndLanguageID:] : 364 -> 360
~ +[IPEventClassificationType eventTypeForCultureAndLanguageID:] : 364 -> 360
~ +[IPEventClassificationType eventTypeForMealsAndLanguageID:] : 364 -> 360
```
