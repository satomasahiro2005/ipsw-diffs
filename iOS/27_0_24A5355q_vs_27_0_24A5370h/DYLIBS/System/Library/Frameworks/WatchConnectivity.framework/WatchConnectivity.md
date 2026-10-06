## WatchConnectivity

> `/System/Library/Frameworks/WatchConnectivity.framework/WatchConnectivity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x271a4` | `0x27018` | **`-0x18c`** |

### Other Changes

```text
Functions:
~ _LZ4_loadDict : 216 -> 212
~ _LZ4_compress_fast_continue : 396 -> 400
~ _LZ4_decompress_safe : 596 -> 588
~ _LZ4_decompress_safe_partial : 616 -> 608
~ _LZ4_decompress_fast_withPrefix64k : 556 -> 548
~ _LZ4_decompress_safe_continue : 1608 -> 1592
~ _LZ4_decompress_fast_continue : 1452 -> 1436
~ _LZ4_decompress_safe_usingDict : 2280 -> 2252
~ _LZ4_decompress_fast_usingDict : 1988 -> 1956
~ _LZ4_decompress_safe_withPrefix64k : 588 -> 580
~ _LZ4_compress_destSize_generic : 1468 -> 1404
~ -[WCSession onqueue_loadFileTransferProgress] : 396 -> 392
~ _generate : 1288 -> 1208
~ _parse : 408 -> 396
~ _PizBufParse : 576 -> 572
~ _collectValuesRecursively : 2216 -> 2200
~ -[WCFileStorage enumerateIncomingFilesWithBlock:] : 1136 -> 1132
~ -[WCFileStorage enumerateIncomingUserInfosWithBlock:] : 1076 -> 1072
~ -[WCFileStorage enumerateUserInfoResultsWithBlock:] : 1580 -> 1568
~ -[WCFileStorage cleanUpWatchContentDirectoryWithCurrentAppInstallationID:] : 564 -> 560
~ -[WCFileStorage cleanUpOldPairingIDFolderInFolder:pairedDevicesPairingIDs:] : 628 -> 624
~ -[WCQueueManager onqueue_cancelQueuedMessages] : 1004 -> 996
~ _LZ4_compress_generic : 1792 -> 1736
```
