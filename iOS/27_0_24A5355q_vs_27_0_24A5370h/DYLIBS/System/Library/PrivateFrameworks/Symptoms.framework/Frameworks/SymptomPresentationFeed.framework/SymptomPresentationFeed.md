## SymptomPresentationFeed

> `/System/Library/PrivateFrameworks/Symptoms.framework/Frameworks/SymptomPresentationFeed.framework/SymptomPresentationFeed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f134` | `0x1f0e4` | **`-0x50`** |

### Other Changes

```diff

-2357.0.0.0.2
+2374.0.0.0.0
Functions:
~ ___53-[NWNetworkOfInterestManager proxyHaveNOIs:tornDown:]_block_invoke : 1744 -> 1752
~ -[NetworkPerformanceFeed _normalizedOpts:toNetwork:] : 548 -> 540
~ -[UsageFeed _processLiveUsageWithUsages:attributesBlock:outcomeBlock:] : 468 -> 464
~ ___57-[NetworkPerformanceFeed fullScorecardFor:options:reply:]_block_invoke.58 : 1080 -> 1076
~ ___57-[NetworkPerformanceFeed fullScorecardFor:options:reply:]_block_invoke.202 : 2520 -> 2516
~ +[ProcessNetStatsIndividualEntity rawCounts:forType:txBytes:rxBytes:] : 316 -> 312
~ -[UsageFeed _performRollUp:andMetadata:from:until:] : 432 -> 428
~ -[UsageFeed _processLiveUsageWithPredicate:attributesBlock:outcomeBlock:] : 620 -> 616
~ -[UsageFeed typicalUsageFor:nameKind:intervalKind:reply:] : 1704 -> 1700
~ ___57-[UsageFeed typicalUsageFor:nameKind:intervalKind:reply:]_block_invoke.470 : 680 -> 676
~ -[UsageFeed calendarUsageFor:nameKind:dayResolution:daySlot:weekSlot:reply:] : 2764 -> 2760
~ ___76-[UsageFeed calendarUsageFor:nameKind:dayResolution:daySlot:weekSlot:reply:]_block_invoke.482 : 1400 -> 1392
~ ___77-[UsageFeed algosScoreToDateWithOptionsFor:nameKind:startTime:options:reply:]_block_invoke.492 : 996 -> 992
~ -[UsageFeed(NetworkDomains) groupRecordsByBundleId:] : 2224 -> 2192
```
