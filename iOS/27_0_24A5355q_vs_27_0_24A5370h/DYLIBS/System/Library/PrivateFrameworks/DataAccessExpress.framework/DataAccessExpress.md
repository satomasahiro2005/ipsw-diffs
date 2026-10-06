## DataAccessExpress

> `/System/Library/PrivateFrameworks/DataAccessExpress.framework/DataAccessExpress`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28704` | `0x2869c` | **`-0x68`** |

### Other Changes

```diff

-2703.0.0.0.0
+2704.0.0.0.0
Functions:
~ -[DADConnection _tearDownInFlightObjects] : 5624 -> 5572
~ ___45-[DADConnection _getStatusReportsFromClient:]_block_invoke : 460 -> 456
~ -[DADConnection _downloadProgress:] : 636 -> 632
~ -[DADConnection _downloadFinished:] : 608 -> 604
~ -[DADConnection _cancelDownloadsWithIDs:error:] : 436 -> 432
~ _setDALogLevel : 272 -> 268
~ _setDALogOutputLevel : 272 -> 268
~ ____initLogging_block_invoke : 1096 -> 1084
~ -[DACPLogDFile cullFilesMaxFileCount:] : 488 -> 484
~ ___44-[DACPLogShared _getUUIDForFolder:baseName:]_block_invoke.115 : 1020 -> 1016
~ +[CalDAVOfficeHour officeHoursFromICS:] : 2160 -> 2156
~ +[DABehaviorOptions addDAManagedDefaults:] : 292 -> 288
~ +[DABehaviorOptions removeDAManagedDefaults:] : 252 -> 248
~ ___DACPLoggingSlurpFileIntoLogFile_block_invoke_2.cold.1 : 368 -> 372
```
