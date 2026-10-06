## NanoSystemSettings

> `/System/Library/PrivateFrameworks/NanoSystemSettings.framework/NanoSystemSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3754c` | `0x37440` | **`-0x10c`** |
| `__TEXT.__unwind_info` | `0xec8` | `0xec0` | **`-0x8`** |

### Other Changes

```diff

-374.0.0.0.0
+375.0.0.0.0
Functions:
~ -[NSSLegalDocumentsReqMsg writeTo:] : 532 -> 524
~ -[NSSLegalDocumentsReqMsg copyWithZone:] : 604 -> 596
~ -[NSSLegalDocumentsReqMsg mergeFrom:] : 540 -> 532
~ -[NSSUsageRespMsgBundleUsage dictionaryRepresentation] : 564 -> 560
~ -[NSSUsageRespMsgBundleUsage writeTo:] : 384 -> 380
~ -[NSSUsageRespMsgBundleUsage copyWithZone:] : 460 -> 456
~ -[NSSUsageRespMsgBundleUsage mergeFrom:] : 392 -> 388
~ -[NSSDiagnosticLogsInfoRespMsgFilesByCategory writeTo:] : 328 -> 324
~ -[NSSDiagnosticLogsInfoRespMsgFilesByCategory copyWithZone:] : 380 -> 376
~ -[NSSDiagnosticLogsInfoRespMsgFilesByCategory mergeFrom:] : 332 -> 328
~ -[NSSUsageBundle totalSize] : 260 -> 256
~ -[NSSAccountsInfoRespMsg dictionaryRepresentation] : 448 -> 444
~ -[NSSAccountsInfoRespMsg writeTo:] : 316 -> 312
~ -[NSSAccountsInfoRespMsg copyWithZone:] : 364 -> 360
~ -[NSSAccountsInfoRespMsg mergeFrom:] : 308 -> 304
~ -[NSSProfilesInfoRespMsg dictionaryRepresentation] : 540 -> 536
~ -[NSSProfilesInfoRespMsg writeTo:] : 380 -> 376
~ -[NSSProfilesInfoRespMsg copyWithZone:] : 444 -> 440
~ -[NSSProfilesInfoRespMsg mergeFrom:] : 388 -> 384
~ +[NSSUsageData createLegacyUsageDictionary:] : 1536 -> 1528
~ -[NSSLocalesInfoRespMsg dictionaryRepresentation] : 808 -> 800
~ -[NSSLocalesInfoRespMsg writeTo:] : 972 -> 952
~ -[NSSLocalesInfoRespMsg copyWithZone:] : 1084 -> 1064
~ -[NSSLocalesInfoRespMsg mergeFrom:] : 948 -> 928
~ -[NSSUsageRespMsg dictionaryRepresentation] : 2660 -> 2644
~ -[NSSUsageRespMsg writeTo:] : 1644 -> 1628
~ -[NSSUsageRespMsg copyWithZone:] : 1856 -> 1840
~ -[NSSUsageRespMsg mergeFrom:] : 1716 -> 1700
~ -[NSSLocalesInfoRespMsgNumberingSystemsForLocale writeTo:] : 300 -> 296
~ -[NSSLocalesInfoRespMsgNumberingSystemsForLocale copyWithZone:] : 356 -> 352
~ -[NSSLocalesInfoRespMsgNumberingSystemsForLocale mergeFrom:] : 308 -> 304
~ +[NSSUsageData(Proto) newAppBundleFromBundleUsageMsg:] : 408 -> 404
~ +[NSSUsageData(Proto) dedupeBundles:] : 444 -> 440
~ +[NSSUsageData(Proto) newUsageDataFromUsageRespMsg:] : 2672 -> 2656
~ +[NSSUsageData(Proto) setUsageRespMsgFrom:usageRespMsg:] : 704 -> 696
~ -[NSSDiagnosticLogsInfoRespMsg dictionaryRepresentation] : 440 -> 436
~ -[NSSDiagnosticLogsInfoRespMsg writeTo:] : 448 -> 440
~ -[NSSDiagnosticLogsInfoRespMsg copyWithZone:] : 504 -> 496
~ -[NSSDiagnosticLogsInfoRespMsg mergeFrom:] : 440 -> 432
~ sub_28b69d1d0 -> sub_28cc570a4 : 412 -> 388
~ sub_28b69d36c -> sub_28cc57228 : 256 -> 276
~ sub_28b69eff0 -> sub_28cc58ec0 : 404 -> 428
~ sub_28b6a04bc -> sub_28cc5a3a4 : 524 -> 532
~ sub_28b6a0f00 -> sub_28cc5adf0 : 476 -> 480
```
