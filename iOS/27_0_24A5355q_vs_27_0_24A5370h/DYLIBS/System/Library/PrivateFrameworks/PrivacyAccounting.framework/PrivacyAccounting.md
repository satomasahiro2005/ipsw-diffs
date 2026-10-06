## PrivacyAccounting

> `/System/Library/PrivateFrameworks/PrivacyAccounting.framework/PrivacyAccounting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c498` | `0x1c44c` | **`-0x4c`** |

### Other Changes

```text
Functions:
~ -[PAAccessLogger handleConnectionInterrupted] : 868 -> 856
~ -[PAAccessLogger resyncState] : 984 -> 980
~ _PAAuthenticatedClientIdentityWithClientProperties : 1348 -> 1352
~ -[PABasicAssetIdentifierPool addAssetIdentifiers:accessEventCount:] : 624 -> 620
~ -[PAAggregateVisibilityStateMonitorHandle recomputeCurrentState] : 372 -> 368
~ -[PAAccessReader publisherForAllSince:until:reversed:error:] : 556 -> 552
~ -[PAAccessReader getOrCreateStreamsWithError:] : 612 -> 608
~ -[PAPBAccess writeTo:] : 468 -> 464
~ -[PAPBAccess copyWithZone:] : 548 -> 544
~ -[PAPBAccess mergeFrom:] : 504 -> 500
~ -[PACoalescingIntervalTracker invalidate] : 340 -> 336
~ _PAAssociatedBundleIdentifiersForApplication : 520 -> 516
~ ___64+[PAAccessPublisherPipelines ongoingAccessRecordsFromPublisher:]_block_invoke_2 : 464 -> 460
~ _coalesceGroupedRecordsToRepublish : 688 -> 684
~ -[PAApplication proto] : 156 -> 152
~ sub_201deef74 -> sub_20285cf38 : 1152 -> 1164
~ sub_201def8d4 -> sub_20285d8a4 : 1640 -> 1636
~ sub_201df1248 -> sub_20285f214 : 476 -> 480
~ sub_201df1444 -> sub_20285f414 : 472 -> 476
~ sub_201df1754 -> sub_20285f728 : 2172 -> 2076
~ sub_201df1fd0 -> sub_20285ff44 : 584 -> 600
~ sub_201df2218 -> sub_20286019c : 684 -> 704
~ sub_201df24c4 -> sub_20286045c : 1528 -> 1536
~ sub_201df32b4 -> sub_202861254 : 256 -> 276
```
