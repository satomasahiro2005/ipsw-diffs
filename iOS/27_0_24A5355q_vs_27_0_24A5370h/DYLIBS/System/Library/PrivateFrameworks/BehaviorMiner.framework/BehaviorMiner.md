## BehaviorMiner

> `/System/Library/PrivateFrameworks/BehaviorMiner.framework/BehaviorMiner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13584` | `0x13500` | **`-0x84`** |

### Other Changes

```text
Functions:
~ -[BMMiningTask mine] : 4972 -> 4964
~ -[BMAprioriPatternMiner initWithBaskets:] : 724 -> 720
~ -[BMAprioriPatternMiner supportOfItemIndexSet:] : 332 -> 328
~ -[BMAprioriPatternMiner getItemIndexSetsWithMinSupport:itemIndexSets:] : 412 -> 408
~ ___46+[BMItemType(Intents) appIntentAutomationHash]_block_invoke : 1164 -> 1160
~ ___46+[BMItemType(Intents) appIntentAutomationHash]_block_invoke.17 : 652 -> 648
~ ___39-[BMCoreRoutineProvider locationEvents]_block_invoke : 1044 -> 1052
~ -[BMRuleExtractor subsetsOfItemset:] : 496 -> 492
~ -[BMRuleExtractor supportOfItemSet:] : 472 -> 468
~ -[BMRuleExtractor extractRulesWithMinSupport:minConfidence:targetTypes:batchSize:currentDate:datedBaskets:handler:] : 2096 -> 2092
~ -[BMEventExtractor extractEventsFilteredByTypes:taskSpecificEventProviders:error:] : 3016 -> 2996
~ -[BMManagedObjectConverter convertItemMOs:error:] : 760 -> 748
~ -[BMManagedObjectConverter insertRules:inManagedObjectContext:] : 660 -> 656
~ -[BMManagedObjectConverter insertItems:inManagedObjectContext:] : 516 -> 512
~ _BMEventInterval : 504 -> 500
~ -[BMBasketExtractor extractDatedBasketsFromEvents:itemTypes:] : 1440 -> 1436
~ ___26+[BMItemType allItemTypes]_block_invoke : 1588 -> 1584
~ +[BMItemType allItemTypesDictionary] : 340 -> 336
~ -[BMBehaviorRetriever initWithURL:taskSpecificItemTypes:] : 376 -> 372
~ -[BMInteractionProvider batchFetchedPhotoSuggestionsForInteractions:] : 604 -> 600
~ -[BMInteractionProvider interactionEventsForTypes:error:] : 7596 -> 7564
~ ___157-[BMBehaviorStorage fetchRulesWithAbsoluteSupport:support:confidence:conviction:lift:rulePowerFactor:uniqueDaysLastWeek:uniqueDaysTotal:filters:limit:error:]_block_invoke : 1064 -> 1060
```
