## SpotlightFoundation

> `/System/Library/PrivateFrameworks/SpotlightFoundation.framework/SpotlightFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8044` | `0x7fe4` | **`-0x60`** |

### Other Changes

```diff

-2444.104.0.0.0
+2448.100.0.0.0
Functions:
~ -[SPCacheManager updateRecentsWithBundleIdentifiers:] : 628 -> 604
~ -[SPCacheManager _createRecentsFromEngagedResults:maxCount:] : 1708 -> 1688
~ -[SPCacheManager enumerateRecentResultsUsingBlock:] : 2240 -> 2228
~ ___51-[SPCacheManager enumerateRecentResultsUsingBlock:]_block_invoke : 840 -> 836
~ ___72-[SPCacheManager enumerateRecentCompletionsWithSearchString:usingBlock:]_block_invoke : 576 -> 572
~ +[SPSpotlightRecentsCache topic:isSameAsTopic:] : 444 -> 440
~ +[SPSpotlightRecentsCache filteredTopics:] : 720 -> 716
~ _topicIdentifierWithPersonQueryIdentifierAndDetail : 760 -> 756
~ _attributesWithEntityIdentifier : 408 -> 404
~ _topicIdentifierWithContactInfoAndDetail : 924 -> 916
~ _attributesForTopicIdentifier : 488 -> 484
~ _attributesWithTopicIdentifier : 408 -> 404
```
