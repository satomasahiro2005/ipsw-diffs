## ExchangeSyncExpress

> `/System/Library/PrivateFrameworks/ExchangeSyncExpress.framework/ExchangeSyncExpress`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc5d0` | `0xc5a4` | **`-0x2c`** |

### Other Changes

```diff

-2075.0.0.0.0
+2076.0.0.0.0
Functions:
~ -[ESDConnection _tearDownInFlightObjects] : 2704 -> 2680
~ ___45-[ESDConnection _getStatusReportsFromClient:]_block_invoke : 476 -> 472
~ -[ESDConnection _downloadProgress:] : 636 -> 632
~ -[ESDConnection _downloadFinished:] : 608 -> 604
~ -[ESDConnection _cancelDownloadsWithIDs:error:] : 520 -> 516
~ ___65-[ESDConnection externalIdentificationForAccountID:resultsBlock:]_block_invoke : 264 -> 260
```
