## InfoQueryPersonalizationFeatures

> `/System/Library/PrivateFrameworks/InfoQueryPersonalizationFeatures.framework/InfoQueryPersonalizationFeatures`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51e4` | `0x51b4` | **`-0x30`** |

### Other Changes

```diff

-3600.35.13.0.0
+3600.38.2.0.0
Functions:
~ +[IQFMapsCoreAnalyticsLogger logCoreAnalyticsEventsWithResults:locations:] : 856 -> 852
~ +[IQFMapsCoreAnalyticsLogger _createCoreAnalyticsEventForLocation:index:muidsToResults:] : 1428 -> 1420
~ -[IQFMapsPersonalizationLookup eventsAtLocations:completionHandler:] : 644 -> 640
~ ___68-[IQFMapsPersonalizationLookup eventsAtLocations:completionHandler:]_block_invoke : 1152 -> 1148
~ ___89+[IQFMapsPersonalizationLookup _fetchResultsForEntityIds:knosisServer:completionHandler:]_block_invoke : 528 -> 524
~ +[IQFMapsPersonalizationLookup _parseKnosisAnswer:entityIDToMuid:] : 1736 -> 1728
~ +[IQFMapsPersonalizationLookup _aggregateLifeEvents:] : 860 -> 852
~ +[IQFMapsPersonalizationLookup _muidForKnosisAnswer:entityIDToMuid:] : 716 -> 712
~ -[IQFMapsPersonalizationRanker rankedEventsForLocations:completionHandler:] : 928 -> 924
```
