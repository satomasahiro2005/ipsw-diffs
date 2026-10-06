## NanoMusicSync

> `/System/Library/PrivateFrameworks/NanoMusicSync.framework/NanoMusicSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4dfa0` | `0x4de74` | **`-0x12c`** |
| `__TEXT.__unwind_info` | `0x1350` | `0x1358` | **`+0x8`** |

### Other Changes

```diff

-2024.100.38.0.0
+2024.100.44.0.0
Functions:
~ -[NMSyncDefaults _migrateDataIfNecessary] : 3996 -> 3992
~ -[NMSMediaQuotaManager initWithItemEnumerators:estimatedItemSizes:quota:] : 496 -> 492
~ -[NMSMediaQuotaManager _newMutableItemEnumeratorDict] : 336 -> 332
~ -[NMSMediaQuotaManager _evaluateAddedItemsIfNecessary] : 3168 -> 3152
~ -[NMSPodcastsDownloadableContentController_Legacy _changeContainsRelevantEpisodeChanges:] : 452 -> 448
~ -[NMSPodcastsDownloadableContentController_Legacy _changeContainsRelevantShowChanges:] : 452 -> 448
~ -[NMSPodcastsDownloadableContentController_Legacy _changeContainsRelevantStationChanges:] : 452 -> 448
~ -[NMSPodcastsDownloadableContentController_Legacy _changeContainsRelevantChannelChanges:] : 452 -> 448
~ -[NMSPodcastsDownloadableContentController_Legacy _shouldMergeHistoryTransaction:] : 332 -> 328
~ ___88-[NMSPodcastsDownloadableContentController_Legacy _processLatestPersistenHistoryChanges]_block_invoke.22 : 488 -> 484
~ -[NMSInitialCloudLibraryImportObserver _performInitialImportBlocks] : 320 -> 316
~ -[NMSMediaQuotaManager_Legacy isItemGroupWithinQuota:] : 792 -> 788
~ -[NMSMediaQuotaManager_Legacy _evaluateAddedItemsIfNecessary] : 2816 -> 2804
~ -[NMSMusicRecommendationsRequestOperation _performLibraryRecentMusicRequestWithCompletion:] : 2936 -> 2928
~ -[NMSMusicRecommendationsRequestOperation _performLibraryImportChangeRequestWithModelObjects:completion:] : 1488 -> 1484
~ -[NMSMediaDownloadInfo totalItemSize] : 268 -> 264
~ ___55-[NMSMutableMediaSyncInfo _updateAggregateInfoIfNeeded]_block_invoke_2 : 588 -> 584
~ -[NMSMediaItemGroupIterator _generateItemListAndSizesDictIfNecessary] : 884 -> 880
~ -[NMSMediaItemGroupIterator identifiersForContainersOfType:] : 344 -> 340
~ -[NMSAlternatingMediaItemGroupIterator _resetMaxItemListSize] : 272 -> 268
~ -[NMSMediaSyncServiceKeepLocalResponse dictionaryRepresentation] : 416 -> 412
~ -[NMSMediaSyncServiceKeepLocalResponse writeTo:] : 184 -> 180
~ -[NMSMediaPinningManager _newMusicEnumeratorWithDownloadedItemsOnly:] : 2012 -> 1996
~ -[NMSMediaPinningManager _newAudiobooksEnumeratorWithDownloadedItemsOnly:] : 1380 -> 1368
~ -[NMSMediaPinningManager _quotaManagerWithDownloadedItemsOnly:] : 988 -> 984
~ -[NMSMediaPinningManager _refreshMusicIdentifiers] : 2668 -> 2656
~ -[NMSMediaPinningManager _legacy_newMusicGroupIteratorWithDownloadedItemsOnly:] : 1800 -> 1788
~ -[NMSMediaPinningManager _legacy_newPodcastsGroupIteratorWithDownloadedItemsOnly:] : 1228 -> 1220
~ -[NMSMediaPinningManager _legacy_newAudiobooksGroupIteratorWithDownloadedItemsOnly:] : 1288 -> 1276
~ -[NMSMediaPinningManager _legacy_quotaManagerWithDownloadedItemsOnly:] : 888 -> 884
~ -[NMSyncDefaults musicRecommendationDict] : 664 -> 656
~ -[NMSyncDefaults _notifyChangesForKey:] : 244 -> 240
~ -[NMSMediaSyncService _defaultPairedDeviceDestinations] : 344 -> 340
~ -[NMSMusicRecommendationManager persistRecommendationsSelections:] : 500 -> 496
~ -[NMSMusicRecommendationManager _reloadLibraryRecommendations] : 836 -> 832
~ -[NMSMusicRecommendationManager _sortedContainersBasedOnRecency] : 1732 -> 1724
~ -[NMSMusicRecommendationManager _updateWithRecommendations:] : 524 -> 520
~ -[NMSMusicRecommendationManager _updateRecommendationsSelections] : 524 -> 520
~ -[NMSMusicRecommendationManager _persistUpdatedRecommendationsWithResponse:] : 604 -> 600
~ -[NMSMusicRecommendationManager _removePreviousRecommendationDefaults] : 560 -> 556
~ -[NMSPodcastUpNextMediaItemGroup identifiersForContainerType:] : 456 -> 452
~ ___42-[NMSPodcastUpNextMediaItemGroup itemList]_block_invoke : 460 -> 456
~ ___49-[NMSPodcastSavedEpisodesMediaItemGroup itemList]_block_invoke : 596 -> 592
~ ___46-[NMSPodcastCustomShowMediaItemGroup itemList]_block_invoke : 636 -> 632
~ ___43-[NMSPodcastStationMediaItemGroup itemList]_block_invoke : 640 -> 636
~ -[NMSRecommendationMediaItemGroup identifiersForContainerType:] : 452 -> 448
~ -[NMSPodcastsDownloadableContentProvider _changeContainsRelevantEpisodeChanges:] : 448 -> 444
~ -[NMSPodcastsDownloadableContentProvider _changeContainsRelevantShowChanges:] : 448 -> 444
~ -[NMSPodcastsDownloadableContentProvider _changeContainsRelevantStationChanges:] : 448 -> 444
~ -[NMSPodcastsDownloadableContentProvider _changeContainsRelevantChannelChanges:] : 452 -> 448
~ -[NMSPodcastsDownloadableContentProvider _shouldMergeHistoryTransaction:] : 332 -> 328
~ ___79-[NMSPodcastsDownloadableContentProvider _processLatestPersistenHistoryChanges]_block_invoke.35 : 488 -> 484
~ +[MIPMultiverseIdentifier(NanoMusicSync) pidsFromMIDDataArray:] : 660 -> 656
~ +[MIPMultiverseIdentifier(NanoMusicSync) _multiverseIdentifiersWithPIDs:groupingType:] : 632 -> 628
~ +[MIPMultiverseIdentifier(NanoMusicSync) _pidsFromSyncIDs:containerClass:] : 744 -> 740
~ ___40-[NMSMusicRecommendation artworkCatalog]_block_invoke : 1000 -> 996
~ ___40-[NMSMusicRecommendation artworkCatalog]_block_invoke_2 : 1100 -> 1096
~ -[NMSMusicRecommendation _tiledArtworkRequestWithPersistentIDs:] : 412 -> 408
~ -[NMSSyncManager _stopObservingSyncSession] : 380 -> 376
~ -[NMSSyncManager _updateSyncProgress] : 1688 -> 1680
~ sub_28b3a8afc -> sub_28c9629b8 : 360 -> 352
~ sub_28b3a8f74 -> sub_28c962e28 : 244 -> 268
~ sub_28b3a9068 -> sub_28c962f34 : 256 -> 264
```
