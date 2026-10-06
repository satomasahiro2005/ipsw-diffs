## CDDataAccessExpress

> `/System/Library/PrivateFrameworks/CDDataAccessExpress.framework/CDDataAccessExpress`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bc28` | `0x1bbd8` | **`-0x50`** |

### Other Changes

```diff

-4034.15.0.0.0
+4037.1.0.0.0
Functions:
~ -[CDDADConnection _tearDownInFlightObjects] : 2704 -> 2680
~ ___47-[CDDADConnection _getStatusReportsFromClient:]_block_invoke : 460 -> 456
~ -[CDDADConnection _downloadProgress:] : 636 -> 632
~ -[CDDADConnection _downloadFinished:] : 608 -> 604
~ -[CDDADConnection watchFoldersWithKeys:forAccountID:persistent:] : 372 -> 368
~ -[CDDADConnection resumeWatchingFoldersWithKeys:forAccountID:] : 364 -> 360
~ -[CDDADConnection _cancelDownloadsWithIDs:error:] : 520 -> 516
~ ___67-[CDDADConnection externalIdentificationForAccountID:resultsBlock:]_block_invoke : 264 -> 260
~ _setDALogLevel : 272 -> 268
~ _setDALogOutputLevel : 272 -> 268
~ ____initLogging_block_invoke : 1096 -> 1084
~ -[DACPLogDFile cullFilesMaxFileCount:] : 488 -> 484
~ ___44-[DACPLogShared _getUUIDForFolder:baseName:]_block_invoke.121 : 1020 -> 1016
~ +[DABehaviorOptions removeDAManagedDefaults:] : 320 -> 316
~ ___DACPLoggingSlurpFileIntoLogFile_block_invoke_2.cold.1 : 368 -> 372
```
