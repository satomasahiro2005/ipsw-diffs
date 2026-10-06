## AirPlayRoutePrediction

> `/System/Library/PrivateFrameworks/AirPlayRoutePrediction.framework/AirPlayRoutePrediction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13920` | `0x13898` | **`-0x88`** |

### Other Changes

```diff

-1956.0.1.0.0
+1959.0.1.0.0
Functions:
~ -[ARPHomeControlSuggester suggestionsWithMaxSuggestions:referenceDate:correlationsFile:] : 2544 -> 2524
~ -[ARPHomeControlSuggester frequencybasedSuggestionsWitMaxSuggestions:events:useScenes:] : 3304 -> 3292
~ -[ARPHomeControlSuggester timeBasedSuggestionsWithMaxSuggestions:referenceDate:fallBackToFrequency:] : 1032 -> 1020
~ -[ARPHomeControlSuggester homeKitEventsWithLookbackDays:] : 1012 -> 1008
~ -[ARPHomeControlSuggester nextActionBasedsuggestionsWithMaxSuggestions:referenceDate:correlationsFile:] : 1876 -> 1872
~ +[ARPRoutingEvent mostRecentRoutingEventInDateInterval:knowledgeStore:eventLimit:longFormVideoFilter:] : 2864 -> 2848
~ _ARPExtractLongFormVideoOutputDeviceIDs : 588 -> 584
~ -[ARPHomeControlSuggester microlocationBasedsuggestionsWithMaxSuggestions:referenceDate:correlationsFile:] : 1724 -> 1720
~ -[ARPHomeControlSuggester timeBucketFrequencyBasedSuggestionsWithMaxSuggestions:events:referenceDate:] : 624 -> 620
~ -[ARPCorrelationTask longFormVideoAppBundleIDs] : 712 -> 708
~ ___84-[ARPHomeControlMicrolocationCorrelationTask registerARPHomeControlNotificationTask]_block_invoke : 456 -> 440
~ _ARPMicroLocationSimilarity : 656 -> 648
~ -[ARPRoutePredictor _reloadPersistedSessions] : 840 -> 836
~ -[ARPRoutePredictor predictionsForContext:] : 2388 -> 2380
~ +[ARPAnalyticsEvent feedbackEventsFromAppUsageEvents:playingEvents:microLocationEvents:feedbackEvents:] : 2284 -> 2280
~ _ARPDonateFeedbackToKnowledgeStore : 840 -> 836
~ _ARPCollectAndSendAnalyticsEvents : 5252 -> 5244
```
