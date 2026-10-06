## StoreServices

> `/System/Library/PrivateFrameworks/StoreServices.framework/StoreServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x5050` | `0x5000` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x24e0` | `0x2530` | **`+0x50`** |
| `__TEXT.__text` | `0x2a1b3c` | `0x2a1b78` | **`+0x3c`** |
| `__DATA_CONST.__got` | `0xea8` | `0xec0` | **`+0x18`** |

### Other Changes

```text
Functions:
~ -[SSDownload addAsset:forType:] : 380 -> 388
~ _SSDownloadKindForAssetType : 68 -> 76
~ _SSGetPersistentStringForAssetType : 68 -> 76
~ +[SSProtocolCondition newConditionWithDictionary:] : 424 -> 432
~ -[SSDevice _diskCapacityString] : 272 -> 260
~ -[SSDevice _newLegacyUserAgent:] : 532 -> 536
~ -[SSDevice _newModernUserAgentWithClientName:version:isCachable:] : 612 -> 616
~ +[SSItemContentRating ratingSystemFromString:] : 108 -> 116
~ -[SSRestoreContentItem _restoreKeyForAssetProperty:] : 196 -> 204
~ -[SSRestoreContentItem _restoreKeyForDownloadProperty:] : 236 -> 244
~ -[SSVCookieStorage _columnNameForCookieProperty:] : 404 -> 412
```
