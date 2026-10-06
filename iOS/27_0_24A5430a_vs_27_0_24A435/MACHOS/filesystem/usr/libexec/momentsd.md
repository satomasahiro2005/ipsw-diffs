## momentsd

> `/usr/libexec/momentsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x262534` | `0x263d48` | **`+0x1814`** |
| `__DATA_CONST.__cfstring` | `0x26820` | `0x27240` | **`+0xa20`** |
| `__TEXT.__oslogstring` | `0x336eb` | `0x33ebb` | **`+0x7d0`** |
| `__TEXT.__cstring` | `0x2797e` | `0x2805e` | **`+0x6e0`** |
| `__TEXT.__gcc_except_tab` | `0x82f4` | `0x83cc` | **`+0xd8`** |
| `__DATA_CONST.__const` | `0xc148` | `0xc1a8` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x39b38` | `0x39b78` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x5548` | `0x5560` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x1d00` | `0x1cf0` | **`-0x10`** |
| `__TEXT.__const` | `0x1480` | `0x1470` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xe98` | `0xe90` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 8959
-  Symbols:   20142
-  CStrings:  15945
+  Functions: 8967
+  Symbols:   20143
+  CStrings:  16067
Symbols:
+ -[MOEventBundleRankingInput peopleCountMaxNormalized]
+ -[MOEventBundleRankingInput peopleCountWeightedAverageNormalized]
+ -[MOEventBundleRankingInput peopleCountWeightedSumNormalized]
+ -[MOEventBundleRankingInput setPeopleCountMaxNormalized:]
+ -[MOEventBundleRankingInput setPeopleCountWeightedAverageNormalized:]
+ -[MOEventBundleRankingInput setPeopleCountWeightedSumNormalized:]
+ OBJC_IVAR_$_MOEventBundleRankingInput._peopleCountMaxNormalized
+ OBJC_IVAR_$_MOEventBundleRankingInput._peopleCountWeightedAverageNormalized
+ OBJC_IVAR_$_MOEventBundleRankingInput._peopleCountWeightedSumNormalized
+ ___62-[MOSignificantContactManager _conversationsFromInteractions:]_block_invoke
+ ___block_descriptor_40_e30_v32?0"MOInteraction"8Q16^B24l
+ _objc_msgSend$peopleCountMaxNormalized
+ _objc_msgSend$peopleCountWeightedAverageNormalized
+ _objc_msgSend$peopleCountWeightedSumNormalized
+ _objc_msgSend$setPeopleCountMaxNormalized:
+ _objc_msgSend$setPeopleCountWeightedAverageNormalized:
+ _objc_msgSend$setPeopleCountWeightedSumNormalized:
- -[MOEventBundleRankingInput pCountMaxNormalized]
- -[MOEventBundleRankingInput pCountWeightedAverageNormalized]
- -[MOEventBundleRankingInput pCountWeightedSumNormalized]
- -[MOEventBundleRankingInput setPCountMaxNormalized:]
- -[MOEventBundleRankingInput setPCountWeightedAverageNormalized:]
- -[MOEventBundleRankingInput setPCountWeightedSumNormalized:]
- OBJC_IVAR_$_MOEventBundleRankingInput._pCountMaxNormalized
- OBJC_IVAR_$_MOEventBundleRankingInput._pCountWeightedAverageNormalized
- OBJC_IVAR_$_MOEventBundleRankingInput._pCountWeightedSumNormalized
- _objc_msgSend$pCountMaxNormalized
- _objc_msgSend$pCountWeightedAverageNormalized
- _objc_msgSend$pCountWeightedSumNormalized
- _objc_msgSend$setPCountMaxNormalized:
- _objc_msgSend$setPCountWeightedAverageNormalized:
- _objc_msgSend$setPCountWeightedSumNormalized:
- _objc_retain_x10
CStrings:
+ " ---  Grouped Interactions Count  :%3lu"
+ " ---  Received Interactions Count :%3lu"
+ "#PhotoMemory,sortedasset,id,%d,asset,%@"
+ "%@, idx, %lu, interaction, %@"
+ "%s, media title, %@, event count, %lu"
+ "(%f)"
+ "CLLocation+MOExtensions.m"
+ "DailyAnnotation: Event, %@"
+ "MOAction.m"
+ "MOAggregationManager.m"
+ "MOAnnotationManager.m"
+ "MOBiomeManager.m"
+ "MOBookmarkStore.m"
+ "MOBundleClusteringManager.m"
+ "MOContextAnnotationUtilities.m"
+ "MOConversation.m"
+ "MODaemonAnalyticsManager.m"
+ "MODaemonClient.m"
+ "MODaemonUniverse.m"
+ "MODailyAnnotationManager.m"
+ "MODataDumpFormatter.m"
+ "MODefaultsManager.m"
+ "MODictionaryEncoder.m"
+ "MODictionaryTransformer.m"
+ "MODominantBundleCreationManager.m"
+ "MOEmbedding.m"
+ "MOEngagementHistoryManager.m"
+ "MOEvent.m"
+ "MOEventBundle.m"
+ "MOEventBundleLabelCondition.m"
+ "MOEventBundleLabelFormat.m"
+ "MOEventBundleLabelLocalizer.m"
+ "MOEventBundleLabelTemplate.m"
+ "MOEventBundleManager.m"
+ "MOEventBundleRanking.m"
+ "MOEventBundleStore.m"
+ "MOEventBundler.m"
+ "MOEventData.m"
+ "MOEventExtendedAtrributes.m"
+ "MOEventManager.m"
+ "MOEventPatternDetector.m"
+ "MOEventPatternDetectorFeatureTransformerAggregateEvents.m"
+ "MOEventRefreshScheduler.m"
+ "MOEventStore.m"
+ "MOFSMStore.m"
+ "MOGraph.m"
+ "MOHealthKitManager.m"
+ "MOInteraction+_CDInteraction.m"
+ "MOInteraction.m"
+ "MOLifeEventManager.m"
+ "MOManageServer.m"
+ "MOMeasurementTransformer.m"
+ "MOMediaPlay.m"
+ "MOMediaPlaySession.m"
+ "MOMetric.m"
+ "MOMotionManager.m"
+ "MONotifier.m"
+ "MONowPlayingMediaManager.m"
+ "MOPOICategoryStore.m"
+ "MOPeopleDiscoveryManager.m"
+ "MOPersistenceManager.m"
+ "MOPhotoManager.m"
+ "MOPlace.m"
+ "MOProactiveTravelManager.m"
+ "MOPromptMetrics.m"
+ "MORankingParams+CoreDataTransformable.m"
+ "MORankingParamsMO+CoreDataClass.m"
+ "MOResource.m"
+ "MORoutineServiceManager.m"
+ "MOSharedWithYouManager.m"
+ "MOSignificantContactManager.m"
+ "MOStringArrayTransformer.m"
+ "MOSuggestedEventManager.m"
+ "MOSummarizationParameters.m"
+ "MOSummarizationUtilities.m"
+ "MOTime.m"
+ "MOTimeAtHomeParams.m"
+ "MOTimeContextAnnotationManager.m"
+ "MOTopicManager.m"
+ "MOTrendBundler.m"
+ "MOTrendsAnalyzerOptions.m"
+ "MOTripAnnotationManager.m"
+ "MOUserData.m"
+ "MOXPCContext.m"
+ "Media sessions grouped for title and day: %@"
+ "PlatformInfoOverrideIsSeedBuild"
+ "Tf,N,V_peopleCountMaxNormalized"
+ "Tf,N,V_peopleCountWeightedAverageNormalized"
+ "Tf,N,V_peopleCountWeightedSumNormalized"
+ "TitleAndDayGrouping: media session with description: %@"
+ "["
+ "[generateBehavioralPatternBundles] bundle subtype=%lu, subbundlecount=%lu, phenotypes=%{private}@"
+ "[generateThematicSummarizationBundles] bundle subtype=%lu, subbundlecount=%lu, phenotypes=%{private}@"
+ "]"
+ "_peopleCountMaxNormalized"
+ "_peopleCountWeightedAverageNormalized"
+ "_peopleCountWeightedSumNormalized"
+ "label confidence, label confidence score, %f, actionNameConfidence, %f, concurrentMediaActionNameConfidence, %f, backgroundActionNameConfidence, %@, placeNameConfidence, %f, bundle, %@"
+ "label confidence, label confidence, %f, event bundle, %@"
+ "new conversation created for compound key: %@, for date %@, interaction count, %lu"
+ "peopleCountMaxNormalized"
+ "peopleCountWeightedAverageNormalized"
+ "peopleCountWeightedSumNormalized"
+ "setPeopleCountMaxNormalized:"
+ "setPeopleCountWeightedAverageNormalized:"
+ "setPeopleCountWeightedSumNormalized:"
+ "skipping fetching and rehydrating contact events"
+ "skipping fetching and rehydrating life events"
+ "skipping fetching and rehydrating music"
+ "skipping fetching and rehydrating people density events"
+ "skipping fetching and rehydrating photo memory"
+ "skipping fetching and rehydrating prox"
+ "skipping fetching and rehydrating state of mind"
+ "skipping fetching and rehydrating workouts"
+ "skipping fetching and saving motion events"
+ "skipping fetching and saving screentime events"
+ "skipping fetching and saving spotlight events"
+ "skipping training, fetching and rehydrating visits"
+ "spotlight event integration enablement param is set to %d"
+ "start fetching and rehydrating contact events"
+ "start fetching and rehydrating life events"
+ "start fetching and rehydrating motion events"
+ "start fetching and rehydrating music"
+ "start fetching and rehydrating people density events"
+ "start fetching and rehydrating photo memory"
+ "start fetching and rehydrating prox"
+ "start fetching and rehydrating screentime events"
+ "start fetching and rehydrating spotlight events"
+ "start fetching and rehydrating state of mind data"
+ "start fetching and rehydrating workouts"
+ "start training, fetching and rehydrating visits"
- "Tf,N,V_pCountMaxNormalized"
- "Tf,N,V_pCountWeightedAverageNormalized"
- "Tf,N,V_pCountWeightedSumNormalized"
- "_pCountMaxNormalized"
- "_pCountWeightedAverageNormalized"
- "_pCountWeightedSumNormalized"
- "setPCountMaxNormalized:"
- "setPCountWeightedAverageNormalized:"
- "setPCountWeightedSumNormalized:"
```
