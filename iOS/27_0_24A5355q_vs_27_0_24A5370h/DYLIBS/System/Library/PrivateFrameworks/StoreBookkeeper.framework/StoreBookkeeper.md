## StoreBookkeeper

> `/System/Library/PrivateFrameworks/StoreBookkeeper.framework/StoreBookkeeper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dd10` | `0x1dd30` | **`+0x20`** |

### Other Changes

```text
Functions:
~ +[NSData(SBKAdditions) SBKStringFromDigestData:] : 236 -> 248
~ +[NSData(SBKAdditions) SBKStringByMD5HashingString:] : 4588 -> 4648
~ -[SBKTransactionController dealloc] : 408 -> 404
~ -[SBKTransactionController _onQueue_cancelAllPendingTransactions:] : 400 -> 396
~ ___63-[SBKSyncResponseData _deserializeResponseDictionary:response:]_block_invoke : 796 -> 792
~ -[SBKSyncRequestData serializableRequestBodyPropertyList] : 1028 -> 1020
~ _storageItemIdentifierForProperties : 572 -> 568
~ ___78-[SBKPlaybackPositionSyncRequestHandler _mergeConflictedItemFromSyncResponse:]_block_invoke : 196 -> 192
~ ___77-[SBKSyncRequestHandler transaction:processUpdatedKey:data:conflict:isDirty:]_block_invoke : 160 -> 156
~ _SBKStoreAccountIdentifiers : 404 -> 400
~ _SBKStoreAccountIdentifierFromDatabasePath : 440 -> 436
```
