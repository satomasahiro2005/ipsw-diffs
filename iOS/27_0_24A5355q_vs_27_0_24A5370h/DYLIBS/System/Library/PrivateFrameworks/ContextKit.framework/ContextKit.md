## ContextKit

> `/System/Library/PrivateFrameworks/ContextKit.framework/ContextKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf3e8` | `0xf3c0` | **`-0x28`** |

### Other Changes

```text
Functions:
~ ___63-[CKContextClient didReceiveCKContextServiceUpdateNotification]_block_invoke : 608 -> 604
~ -[CKContextCompleter resultsMatching:] : 984 -> 976
~ -[CKContextCompleter _resultsMatching:] : 1024 -> 1020
~ _normalizeForSearch : 724 -> 736
~ -[CKContextCompleter resultsMatchingTags:] : 468 -> 464
~ -[CKContextCompleter queriesMatching:] : 360 -> 356
~ -[CKContextFingerprintMinHash debugDescription] : 244 -> 248
~ +[CKContextFingerprintMinHash parse:] : 1096 -> 1084
~ -[CKContextFingerprintMinHash compareFingerprintWith:] : 304 -> 308
~ ___32+[CKContextXPCClient initialize]_block_invoke : 584 -> 580
~ -[CKContextResponse resultByQuery:] : 352 -> 348
~ -[CKContextResponse logEngagement:forInputLength:completion:likelyUnsolicited:] : 468 -> 464
~ -[CKContextResponse responseSummary:showHigherLevelTopics:maxPrefix:] : 2640 -> 2628
```
