## InAppMessages

> `/System/Library/PrivateFrameworks/InAppMessages.framework/InAppMessages`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x123fc` | `0x12360` | **`-0x9c`** |

### Other Changes

```text
Functions:
~ -[IAMMessageEntryManager setMessageEntries:] : 384 -> 380
~ -[IAMMessageEntryManager messageEntriesForContextPropertiesContext:] : 772 -> 768
~ -[IAMMessageEntryManager messageEntriesByTriggerForEventContext:] : 1708 -> 1700
~ +[IAMMessageEntryManager targetIdentifiersForMessageEntries:] : 356 -> 352
~ +[IAMMessageEntryManager messageEntries:withSatisfiedPresentationTriggerForTriggerContext:] : 772 -> 768
~ +[IAMMessageEntryManager uniqueMessageEntriesInMessageEntriesByTrigger:] : 340 -> 336
~ -[IAMMessageEntryManager _updateMessageIndexes] : 2696 -> 2688
~ ___47-[IAMMessageEntryManager _updateMessageIndexes]_block_invoke : 240 -> 236
~ ___111-[IAMMessageCoordinator reportMessageWithIdentifier:actionWasPerformedWithIdentifier:fromTargetWithIdentifier:]_block_invoke : 752 -> 748
~ -[IAMMessageCoordinator _setMessageGroups:] : 472 -> 468
~ -[IAMMessageCoordinator _handleUpdatedMessageEntries:andMetadata:] : 648 -> 636
~ -[IAMMessageCoordinator _evaluateMessagesForAllActiveTargets] : 392 -> 388
~ -[IAMMessageCoordinator _calculateMessagesProximityAndDownloadResourcesIfNeeded:] : 708 -> 704
~ -[IAMMessageCoordinator _reevaluateTargetsWithIdentifiers:forTriggerContext:shouldNotifyTargetsIfPriorityMessageNonNil:] : 632 -> 628
~ -[IAMMessageCoordinator _notifyMessageTargets:withTargetIdentifier:didUpdatePriorityMessageFromEntry:observedEventName:] : 632 -> 628
~ -[IAMMessageCoordinator _processObservedEventCallbacksforEventName:willTriggerPresentation:messageIdentifier:] : 340 -> 336
~ +[IAMMessageCoordinator _createMessageFromMessageEntry:replacingResourcePathsWithCachedResourceLocations:] : 1512 -> 1504
~ -[IAMMessageCoordinator _filterActiveTargetIdentifiers:] : 372 -> 368
~ -[IAMMessageCoordinator _updateMetadataOfMessageEntriesByTrigger:forReceivedEvent:] : 760 -> 756
~ -[IAMImpressionManager _startImpressionForMessageEntry:fromTargetWithIdentifier:displayStartTime:] : 372 -> 368
~ -[IAMImpressionManager _endImpressionForMessageWithIdentifier:fromTargetWithIdentifier:displayEndTime:] : 300 -> 296
~ -[IAMImpressionManager _transitionToActiveState] : 524 -> 520
~ -[IAMImpressionManager _transitionToInactiveState] : 520 -> 516
~ +[IAMModalTarget isAnyModalTargetPresentingMessage] : 260 -> 256
~ ___77-[IAMWebMessageController _createJSOContentPages:fromMessageEntry:withBlock:]_block_invoke : 732 -> 728
~ -[IAMEvaluator computePassingMessageEntries] : 768 -> 764
~ -[IAMEvaluator computeMessagesCloseToPassingWithProximityThreshold:] : 376 -> 372
~ -[IAMEvaluator _doesPresentationPolicyAllowPresentationOfMessage:] : 252 -> 248
~ -[IAMEvaluator _evaluateCompoundRule:forMessageEntry:] : 568 -> 560
~ -[IAMEvaluator _calculateCompoundRuleProximity:forMessageEntry:] : 1056 -> 1044
~ ___64-[IAMEvaluator _calculateCompoundRuleProximity:forMessageEntry:]_block_invoke : 80 -> 76
```
