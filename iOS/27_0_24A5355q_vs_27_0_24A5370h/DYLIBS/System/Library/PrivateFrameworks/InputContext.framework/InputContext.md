## InputContext

> `/System/Library/PrivateFrameworks/InputContext.framework/InputContext`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x143e0` | `0x1434c` | **`-0x94`** |

### Other Changes

```text
Functions:
~ -[_ICPredictionManager searchForMeCardRegions] : 844 -> 840
~ -[_ICPortraitPredictionSource searchForMeCardRegionsWithTimeout:handler:] : 1428 -> 1420
~ -[_ICPredictionManager warmUp] : 324 -> 320
~ -[_ICResultCache searchWithTrigger:] : 396 -> 392
~ -[_ICPredictionManager _quickTypePredictionWithTrigger:searchContext:timeoutInMilliseconds:error:] : 1404 -> 1400
~ -[_ICInputSuggesterPredictionSource predictedItemsWithProactiveTrigger:searchContext:limit:timeoutInMilliseconds:handler:] : 1064 -> 1060
~ -[_ICNamedEntityStore addEntity:isDurable:] : 1112 -> 1104
~ ___43-[_ICNamedEntityStore addEntity:isDurable:]_block_invoke_2 : 372 -> 368
~ -[_ICNamedEntityStore _addEntity:tokens:] : 376 -> 372
~ -[_ICLexiconManager _notifyNamedEntitiesUpdateObservers] : 352 -> 348
~ +[_ICProactiveTrigger isEquivalentDictionary:second:] : 532 -> 528
~ -[_ICPredictionManager searchForMeCardEmailAddresses] : 836 -> 832
~ -[_ICPredictionManager hibernate] : 284 -> 280
~ ___60-[_ICPredictionManager provideFeedbackForString:type:style:]_block_invoke : 332 -> 328
~ ___46-[_ICPredictionManager propogateMetrics:data:]_block_invoke : 324 -> 320
~ -[_ICContact flatten] : 904 -> 896
~ -[_ICPortraitPredictionSource predictedItemsWithProactiveTrigger:searchContext:limit:timeoutInMilliseconds:handler:] : 752 -> 748
~ -[_ICPortraitPredictionSource searchForMeCardEmailAddressesWithTimeout:handler:] : 616 -> 612
~ -[_ICLexiconManager doLoadLexicon] : 340 -> 336
~ ___37-[_ICLexiconManager completeContacts]_block_invoke : 632 -> 624
~ ___43-[_ICLexiconManager completeRecentContacts]_block_invoke : 708 -> 700
~ -[_ICLexiconManager warmUp] : 240 -> 236
~ -[_ICLexiconManager hibernate] : 240 -> 236
~ -[_ICLexiconManager provideFeedbackForString:type:style:] : 320 -> 316
~ -[_ICInternalSource localizedStringForKey:withLocale:] : 788 -> 784
~ -[_ICTransientLexicon addEntity:asAliasOfEntity:] : 344 -> 340
~ -[_ICTransientLexicon removeEntity:] : 388 -> 384
~ +[_ICPortraitUtilities excludedAlgorithms] : 364 -> 360
~ -[_ICResultCache fuzzyMatchItem:withValue:] : 416 -> 412
~ -[_ICResultCache searchWithValue:] : 500 -> 496
~ __createExemplarSetForLocales : 584 -> 580
~ -[_ICNamedEntityStore reloadRecents] : 388 -> 384
```
