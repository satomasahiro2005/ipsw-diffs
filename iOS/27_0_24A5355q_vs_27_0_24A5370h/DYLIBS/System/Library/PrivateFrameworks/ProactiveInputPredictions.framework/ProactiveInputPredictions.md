## ProactiveInputPredictions

> `/System/Library/PrivateFrameworks/ProactiveInputPredictions.framework/ProactiveInputPredictions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11eb8` | `0x11e70` | **`-0x48`** |
| `__TEXT.__gcc_except_tab` | `0x71c` | `0x724` | **`+0x8`** |

### Other Changes

```diff

-1331.0.1.0.0
+1334.0.1.0.0
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE16__init_with_sizeB9fqe220106IPjS5_EEvT_T0_m
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorIjNS_9allocatorIjEEE16__init_with_sizeB9fqe220100IPjS5_EEvT_T0_m
- __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ -[PSGInputSuggestionsRequest initWithResponseContext:conversationTurns:adaptationContextID:shouldDisableAutoCaps:isResponseContextBlacklisted:contextBeforeInput:markedText:selectedText:contextAfterInput:selectedRangeInMarkedText:localeIdentifier:bundleIdentifier:recipients:recipientNames:textContentType:availableApps:textualResponseLimit:structuredInfoLimit:totalSuggestionsLimit:] : 776 -> 772
~ -[PSGInputSuggesterClient _cachedStructuredSuggestionsForContext:localeIdentifier:maxSuggestions:] : 444 -> 440
~ ___49-[PSGUtilities prewarmCacheForLocale:usingQueue:]_block_invoke_2 : 256 -> 252
~ -[PSGInputSuggesterClient _combineMLAndRKItems:mlItems:] : 1180 -> 1176
~ +[PSGInputSuggesterClient _zkwItemsContainsOnlyTextualResponses:] : 500 -> 496
~ -[PSGWordBoundaryFSTGrammar triggerAttributesForContext:localeIdentifier:] : 2532 -> 2572
~ -[PSGInputSuggester logMetricForEventType:externalMetadata:predictedValues:] : 1424 -> 1420
~ -[PSGInputSuggestionsRequest initWithResponseContext:conversationTurns:adaptationContextID:shouldDisableAutoCaps:isResponseContextBlacklisted:contextBeforeInput:markedText:selectedText:contextAfterInput:selectedRangeInMarkedText:localeIdentifier:bundleIdentifier:recipients:textContentType:availableApps:textualResponseLimit:structuredInfoLimit:] : 744 -> 740
~ -[PSGInputSuggestionsRequest initWithCoder:] : 2104 -> 2100
~ -[PSGInputSuggestionsRequest description] : 1168 -> 1152
~ ___48-[PSGInputSuggestionsExplanationSet description]_block_invoke : 328 -> 324
~ -[PSGInputSuggestionsResponse description] : 404 -> 400
~ -[PSGProactiveTriggerHandler _handleOperationalTrigger:localeIdentifier:bundleIdentifier:recipientNames:availableApps:limit:explanationSet:results:] : 2632 -> 2628
~ -[PSGProactiveTriggerHandler _handlePortraitTrigger:localeIdentifier:bundleIdentifier:recipients:limit:timeoutSeconds:explanationSet:results:] : 1768 -> 1764
~ -[PSGNameMentionsHandler getNameMentionsTriggerForContext:recipientNames:availableApps:localeIdentifier:explanationSet:] : 1436 -> 1432
~ -[PSGNameMentionsHandler getPredictedItemsForTrigger:recipientNames:bundleIdentifier:maxItems:] : 1096 -> 1092
~ -[PSGInputSuggesterClient _responseKitPredictionsForContext:bundleIdentifier:conversationTurns:languageID:adaptationContextID:shouldDisableAutoCaps:maximumResponses:isBlacklisted:] : 1292 -> 1284
~ -[PSGInputSuggesterClient _rewriteMoneyAttributes:] : 724 -> 720
~ -[PSGInputSuggesterClient _fillSuggestionsForResponseItems:localeIdentifier:recipients:recipientNames:bundleIdentifier:timeoutSeconds:structuredInfoFetchLimit:availableApps:textualResponseLimit:structuredInfoLimit:totalSuggestionsLimit:explanationSet:error:] : 1304 -> 1300
~ -[PSGInputSuggesterClient _logTriggerForItems:request:] : 384 -> 380
~ -[PSGStructuredInfoSuggestionCache searchWithTrigger:localeIdentifier:maxSuggestions:] : 1212 -> 1204
~ -[PSGStructuredInfoSuggestionCache searchWithContext:localeIdentifier:maxSuggestions:] : 556 -> 552
~ +[PSGStructuredInfoSuggestionCache _matchesPredictedValue:prefixValue:] : 432 -> 428
~ ___72-[PSGUtilities localizedStringForKey:withLocale:onlyIfCached:wasCached:]_block_invoke.18 : 724 -> 720
```
