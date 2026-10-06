## WatchListKit

> `/System/Library/PrivateFrameworks/WatchListKit.framework/WatchListKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66cf4` | `0x66b60` | **`-0x194`** |

### Other Changes

```diff

-950.0.0.0.0
+951.0.0.0.0
Functions:
~ ___48-[WLKSettingsStore _loadFromDiskWithCompletion:]_block_invoke_2 : 1396 -> 1392
~ _WLKFetchNotificationCategories : 472 -> 468
~ -[WLKUserEnvironment _queryPostV3] : 1104 -> 1096
~ ___44+[WLKFeatureEnablement tvAppEnabledFeatures]_block_invoke : 1652 -> 1648
~ -[NSString(WLKAdditions) wlk_stringByAppendingPathComponents:] : 428 -> 424
~ _WLKSortDictionaries : 580 -> 576
~ ___41-[WLKAppLibrary dictionaryRepresentation]_block_invoke : 564 -> 560
~ ___33-[WLKSettingsStore watchListApps]_block_invoke : 284 -> 280
~ -[WLKServerConfigurationResponse _requiredRequestKVPMap:] : 1464 -> 1440
~ +[NSURL(WLKAdditions) wlk_sortedQueryItemsFromDictionary:] : 684 -> 680
~ +[NSURLRequest(WLKAdditions) wlk_requestWithURL:httpMethod:httpBody:httpHeaders:cachePolicy:timeout:] : 876 -> 872
~ -[WLKDictionaryResponseProcessor processResponseData:options:error:] : 608 -> 604
~ ___41-[WLKNotificationsImpl_iOS _fetchTopics:]_block_invoke.49 : 1196 -> 1192
~ -[WLKSiriBestPlayablesResponse initWithDictionary:] : 684 -> 680
~ -[WLKFavoritesRequestOperation processResponse] : 380 -> 376
~ +[WLKPlayableUtilities _playNonITunesPlayableUsingAssociatedApp:] : 672 -> 668
~ -[WLKOfferManager sendBadgeActionMetricsEvents:] : 1308 -> 1304
~ -[WLKPushNotificationMetricsManager initWithNotificationSettings:notificationSettingsForTopic:] : 552 -> 548
~ -[WLKNetworkRequestOperation(ResponseHeaders) httpHeaderMaxAge] : 552 -> 548
~ -[WLKAppLibraryCore containsAppOfInterest:] : 388 -> 384
~ ___49-[WLKAppLibraryCore _fetchApplicationsInProcess:]_block_invoke : 1944 -> 1956
~ -[WLKUpNextItemCollection initWithDictionary:context:] : 584 -> 580
~ -[WLKSettingsAMSBagTracker updateTrackedBagValues] : 348 -> 344
~ -[WLKSettingsAMSBagTracker updateTrackedBagValuesWithChangedKeys:] : 388 -> 384
~ -[WLKSettingsAMSBagTracker _updateKeys:] : 244 -> 240
~ -[WLKSettingsAMSBagTracker _removeInactiveKeys:] : 420 -> 416
~ -[WLKArtworkVariantListing bestArtworkVariantOfType:forSize:] : 544 -> 540
~ -[WLKArtworkVariantListing artworkVariantOfType:] : 300 -> 296
~ +[WLKChannel channelsWithDictionaries:context:] : 384 -> 380
~ +[WLKChannel channelsWithDictionaries:context:seasons:] : 732 -> 728
~ +[WLKBadgingUtilities processStoredODJBadgingRequestActions] : 588 -> 584
~ -[WLKPostPlayAutoPlayCache invalidateAllCaches] : 392 -> 388
~ -[WLKPostPlayAutoPlayCache _postNotificationForType:] : 280 -> 276
~ +[WLKBasicEpisodeMetadata episodesWithDictionaries:context:] : 384 -> 380
~ -[WLKBasicEpisodeMetadata initWithDictionary:context:playablesDict:playablesId:seasonsDict:] : 984 -> 980
~ -[WLKCanonicalPlayablesSiriResponse initWithDictionary:] : 1120 -> 1116
~ +[WLKComingSoonInfo comingSoonItemsWithDictionaries:] : 344 -> 340
~ +[WLKSettingsLanguageUtilities userFacingAudioLanguageTitles:] : 352 -> 348
~ +[WLKSettingsLanguageUtilities availableAudioLanguageCodes] : 792 -> 784
~ +[WLKVideo videosWithDictionaries:] : 348 -> 344
~ +[WLKBasicSeasonMetadata seasonsWithDictionaries:] : 364 -> 360
~ +[WLKPlayable playablesWithDictionaries:context:] : 400 -> 396
~ +[WLKContinueWatchingRequestOperation donateMediaItems:] : 2776 -> 2772
~ +[WLKSettingsCloudUtilities _syncDictionaryForLocalStore] : 584 -> 580
~ ___50+[WLKSettingsCloudUtilities _fetchSyncDictionary:]_block_invoke : 1140 -> 1132
~ -[WLKStoreOffer initWithSubscriptionDictionary:] : 552 -> 548
~ +[WLKStoreOffer offersWithSubscriptionDictionaries:] : 368 -> 364
~ +[WLKStoreOffer offersWithMAPIDictionaries:] : 368 -> 364
~ -[WLKUserEnvironment _entitlementsQuery] : 796 -> 792
~ -[WLKSportsFavoriteResponse initWithDictionary:] : 432 -> 428
~ -[WLKOfferListing _storeOffersFromMAPIDictionaries:] : 368 -> 364
~ +[WLKBrowseItem browseItemsWithDictionaries:context:] : 388 -> 384
~ -[WLKBrowseItem preferredComingSoonInfo] : 364 -> 360
~ -[_WLKAppInstallSession _doPurchaseWithAppAdamID:offerBuyParams:] : 1120 -> 1116
~ +[_WLKAppInstallSession _matchingAppProxyFromProxies:forInstallable:] : 368 -> 364
~ -[WLKContinueWatchingResponse initWithDictionary:] : 668 -> 664
~ -[WLKContinueWatchingCollection initWithDictionary:] : 524 -> 520
~ -[WLKSiriSearchResponse initWithDictionary:] : 728 -> 724
~ ___43-[WLKAppLibrary subscriptionInfoForBundle:]_block_invoke : 348 -> 344
~ -[WLKAppLibrary _bundleIdentifiersfromProxies:] : 336 -> 332
~ -[WLKAppLibrary applicationsDidInstall:] : 424 -> 420
~ -[WLKSearchWatchListResponse initWithDictionary:] : 532 -> 528
~ -[WLKFavoritesRequest convertToWLKFavorite:] : 428 -> 424
~ -[WLKChannelUtilities channelForBundleID:] : 444 -> 440
~ -[WLKSettingsStore consentedBrands] : 380 -> 376
~ -[WLKSettingsStore deniedBrands] : 380 -> 376
~ ___52-[WLKSettingsStore settingsForChannelID:externalID:]_block_invoke : 424 -> 420
~ -[WLKSettingsStore _copyAppsForChannelID:apps:] : 384 -> 380
~ -[WLKSettingsStore setStatus:forChannelID:externalID:] : 744 -> 740
~ ___54-[WLKSettingsStore setStatus:forChannelID:externalID:]_block_invoke : 496 -> 492
~ -[WLKSettingsStore _watchListAppsFiltered] : 940 -> 936
~ ___45-[WLKSettingsStore _updateDisplayNamesForUI:]_block_invoke : 636 -> 632
~ ___38-[WLKSettingsStore _appsForChannelID:]_block_invoke : 316 -> 312
~ -[WLKCanonicalPlayablesResponse initWithDictionary:] : 1100 -> 1096
~ -[WLKSiriBestPlayableForStatsIDsOperation initWithStatsIDs:caller:] : 780 -> 776
~ +[WLKGenre genresWithDictionaries:] : 364 -> 360
~ -[WLKBasicContentRequestResponse initWithDictionary:] : 448 -> 444
~ -[WLKSchedule eventForDate:] : 372 -> 368
~ -[WLKSchedule eventForDate:fuzziness:] : 388 -> 384
~ -[WLKSchedule adjacentEventsForDate:fuzziness:] : 460 -> 456
~ -[WLKSchedule eventAfterDate:] : 340 -> 336
~ -[WLKChannelDetails initWithDictionary:] : 1232 -> 1228
~ -[WLKAMSMediaProxy _initializeProperties:] : 644 -> 640
~ +[WLKMovieClip movieClipsWithArray:] : 416 -> 412
~ +[WLKMovieClipAsset movieClipAssetsWithArray:] : 416 -> 412
~ -[WLKUpNextDelta initWithDictionary:] : 560 -> 556
~ -[WLKUpNextDelta _deltaByMergingItemsFromDelta:] : 760 -> 748
~ ___58-[WLKSportsFavoriteCache deleteLegacyCacheWithCompletion:]_block_invoke : 616 -> 608
~ ___71-[WLKSportsFavoriteCache setCache:overrideLastModifiedDate:completion:]_block_invoke : 392 -> 388
~ ___53-[WLKSportsFavoriteCache getFavoritesWithCompletion:]_block_invoke : 480 -> 476
~ ___50-[WLKSportsFavoriteCache addFavorites:completion:]_block_invoke : 464 -> 460
~ ___53-[WLKSportsFavoriteCache removeFavorites:completion:]_block_invoke : 464 -> 460
~ ___69-[WLKSportsFavoriteManager _performAction:withIDs:caller:completion:]_block_invoke.181 : 396 -> 392
~ __WLKDeepReplacement : 700 -> 696
```
