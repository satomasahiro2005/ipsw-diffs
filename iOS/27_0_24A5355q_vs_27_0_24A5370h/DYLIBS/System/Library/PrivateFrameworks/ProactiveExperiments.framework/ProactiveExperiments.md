## ProactiveExperiments

> `/System/Library/PrivateFrameworks/ProactiveExperiments.framework/ProactiveExperiments`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20f3c` | `0x20ed8` | **`-0x64`** |

### Other Changes

```diff

-1331.0.1.0.0
+1334.0.1.0.0
Functions:
~ -[PRELocaleDetection initWithLanguageLimit:withPreferredLocales:] : 568 -> 564
~ -[PRELocaleDetection _userLanguageDetectedFromString:preferredLocales:] : 768 -> 764
~ -[PRELocaleDetection _bestLocaleForLanguageTag:] : 320 -> 316
~ -[PREUMEngagedResponseList dictionaryRepresentation] : 892 -> 888
~ -[PREUMEngagedResponseList writeTo:] : 520 -> 516
~ -[PREUMEngagedResponseList copyWithZone:] : 608 -> 604
~ -[PREUMEngagedResponseList mergeFrom:] : 588 -> 584
~ +[PREResponseItem responseItemArrayFromResponseKitArray:forLocale:] : 452 -> 448
~ -[PREUMResponseList dictionaryRepresentation] : 784 -> 780
~ -[PREUMResponseList writeTo:] : 480 -> 476
~ -[PREUMResponseList copyWithZone:] : 560 -> 556
~ -[PREUMResponseList mergeFrom:] : 540 -> 536
~ -[NSString(ExemptTermsDetector) removeApostrophes] : 312 -> 308
~ -[PREResponsesMetricsPET _responseListFromGeneratedEvent:] : 988 -> 984
~ -[PREResponsesMetricsPET registerResponseTapped:] : 1536 -> 1532
~ -[PREExperimentResolver init] : 860 -> 856
~ +[PREResponsesExperiment _getConversationHistoryFromRequest:] : 1096 -> 1088
~ +[PREResponsesExperiment stringArrayFromPreResponseItems:] : 624 -> 620
~ -[PREResponsesExperiment handlesFromRecipients:] : 692 -> 688
~ +[PREResponsesExperiment _cannedRepliesForLanguage:inputPreferences:] : 448 -> 444
~ +[PREResponsesExperiment _shouldInsertSuggestion:forExistingSuggestions:] : 364 -> 360
~ +[PREResponsesExperiment _suggestionsWithDynamicResponseItems:cannedResponseItems:inputPreferences:] : 1212 -> 1200
```
