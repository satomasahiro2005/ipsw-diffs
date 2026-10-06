## Radio

> `/System/Library/PrivateFrameworks/Radio.framework/Radio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21a10` | `0x219b4` | **`-0x5c`** |

### Other Changes

```text
Functions:
~ -[RadioArtworkCollection initWithArtworkVariants:] : 484 -> 480
~ -[RadioArtworkCollection bestArtworkForPixelSize:] : 340 -> 336
~ -[RadioModel convertObjects:] : 340 -> 336
~ -[RadioModel convertObjectsInSet:] : 340 -> 336
~ ___30-[RadioModel featuredStations]_block_invoke : 576 -> 572
~ -[RadioModel newStationWithDictionary:] : 4692 -> 4688
~ ___29-[RadioModel previewStations]_block_invoke : 552 -> 548
~ -[RadioModel reportProblemIssueTypes] : 436 -> 432
~ ___37-[RadioModel setStationSortOrdering:]_block_invoke_2 : 576 -> 568
~ -[RadioModel stationSortOrdering] : 368 -> 364
~ ___26-[RadioModel userStations]_block_invoke : 552 -> 548
~ -[RadioModel _arrayByReplacingManagedObjectsInArray:] : 428 -> 424
~ -[RadioModel _numberOfSkipsUsedWithSkipTimestamps:currentTimestamp:skipInterval:returningEarliestSkipTimestamp:] : 356 -> 352
~ -[RadioModel _postContextDidChangeNotification:] : 1016 -> 1008
~ -[RadioModel _resetModel] : 316 -> 312
~ -[RadioModel _setByReplacingManagedObjectsInSet:] : 428 -> 424
~ -[RadioRecentStationsController stations] : 356 -> 352
~ -[RadioRecentStationsController _handleRecentStationsResponse:fromRequest:pendingRecentStations:isInitialCacheLoad:] : 952 -> 948
~ ___116-[RadioRecentStationsController _handleRecentStationsResponse:fromRequest:pendingRecentStations:isInitialCacheLoad:]_block_invoke : 412 -> 408
~ ___63-[RadioAddStationRequest startWithAddStationCompletionHandler:]_block_invoke_2 : 800 -> 796
~ ___62-[RadioGetFeaturedStationsRequest startWithCompletionHandler:]_block_invoke : 988 -> 984
~ ___62-[RadioGetFeaturedStationsRequest startWithCompletionHandler:]_block_invoke.5 : 828 -> 812
~ -[RadioRecentStationsRequest _configureRequestPropertiesForCaching:returningCacheKey:] : 4656 -> 4716
~ -[RadioRecentStationsResponse stationGroups] : 424 -> 420
~ +[NSString(RadioRequestAdditions) queryStringForRadioRequestParameters:protocolVersion:error:] : 640 -> 636
~ ___47-[RadioSyncRequest startWithCompletionHandler:]_block_invoke.53 : 1000 -> 992
~ -[RadioSyncRequest _sortedChangesByType:] : 1084 -> 1068
~ -[RadioSyncRequest _stationSortOrderForChanges:] : 388 -> 384
~ -[RadioSyncRequest _updateModel:withChangeDictionary:changeType:loadArtworkSynchronously:] : 960 -> 956
~ _RadioGetArtworkURLFromVariantsForSize : 716 -> 712
```
