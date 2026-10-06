## ContextKitPrediction

> `/System/Library/PrivateFrameworks/ContextKitPrediction.framework/ContextKitPrediction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9334` | `0x92ec` | **`-0x48`** |

### Other Changes

```text
Functions:
~ -[CKContextRecentsPredictionManager _recentsEligibleForDonationMatchingMode:fromRecents:uuidsToCounts:] : 1732 -> 1724
~ ___45-[CKContextRecentsCache allRecentsWithReply:]_block_invoke.29 : 380 -> 376
~ ___75-[CKContextRecentsCache retrieveRecentsBetweenStartDate:endDate:withReply:]_block_invoke_2 : 424 -> 420
~ ___75-[CKContextRecentsCache retrieveRecentsMatchingBundleIdentifier:withReply:]_block_invoke_3 : 372 -> 368
~ ___63-[CKContextRecentsCache retrieveRecentsMatchingMode:withReply:]_block_invoke : 384 -> 380
~ ___63-[CKContextRecentsCache retrieveRecentsForPredictionWithReply:]_block_invoke_2 : 536 -> 532
~ ___66-[CKContextRecentsCache retrieveRecentsMatchingStrings:withReply:]_block_invoke : 364 -> 360
~ ___74-[CKContextRecentsCache retrieveRecentsMatchingTopicIds:titles:withReply:]_block_invoke : 680 -> 676
~ -[CKContextRecentsCache _groupActivitiesByDateIntoSectionsWithRecents:limit:reply:] : 552 -> 548
~ -[CKContextRecentsCache _groupActivitiesByAppIntoSectionsWithRecents:limit:reply:] : 540 -> 536
~ ___92-[CKContextRecentsCache _groupActivitiesByConstellationIntoSectionsWithRecents:limit:reply:]_block_invoke : 1036 -> 1032
~ -[CKContextRecentsCache _groupActivitiesByModeIntoSectionsWithRecents:limit:reply:] : 580 -> 576
~ -[CKContextRecentsCache _recent:matchesKeywords:] : 392 -> 388
~ -[CKContextRecentsCache _associatedTopicIdsForRecent:] : 364 -> 360
~ -[CKContextRecentsCache _associatedTopicTitlesForRecent:] : 332 -> 328
~ -[CKContextRecentsCache _pruneRecentsFromUnusedAppsForRecents:] : 644 -> 636
```
