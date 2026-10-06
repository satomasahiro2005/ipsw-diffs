## PowerlogCore

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/PowerlogCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe7c60` | `0xe8568` | **`+0x908`** |
| `__AUTH_CONST.__cfstring` | `0x6be60` | `0x6c560` | **`+0x700`** |
| `__DATA_CONST.__objc_arraydata` | `0x43d08` | `0x441d8` | **`+0x4d0`** |
| `__TEXT.__cstring` | `0x42c16` | `0x43086` | **`+0x470`** |
| `__AUTH_CONST.__objc_dictobj` | `0xf7f8` | `0xf910` | **`+0x118`** |
| `__AUTH_CONST.__const` | `0x24e0` | `0x2540` | **`+0x60`** |
| `__DATA.__bss` | `0x16b1` | `0x1709` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x9758` | `0x97a8` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x29f0` | `0x2a38` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x5968` | `0x59a0` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0xaa00` | `0xaa30` | **`+0x30`** |
| `__DATA_DIRTY.__bss` | `0x11c0` | `0x1198` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x30e0` | `0x3108` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0xdb8` | `0xdc0` | **`+0x8`** |
| `__TEXT.__const` | `0x1ba0` | `0x1b98` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x7cc` | `0x7d0` | **`+0x4`** |

### Other Changes

```diff

-3486.0.81.502.4
+3486.2.4.0.0

-  Functions: 4940
-  Symbols:   7246
-  CStrings:  15136
+  Functions: 4953
+  Symbols:   7264
+  CStrings:  15193
Symbols:
+ +[PLSQLiteConnection tableColumnPresenceCacheSem]
+ +[PLSQLiteConnection tableColumnPresenceCache]
+ +[PLUtilities getHardwarePerfKind:]
+ -[PLContextualizedMetricData reducedAccuracySeconds]
+ -[PLContextualizedMetricData setReducedAccuracySeconds:]
+ -[PLSQLiteConnection clearTableColumnPresenceCache]
+ -[PLSQLiteConnection tableHasColumn:inTable:]
+ GCC_except_table100
+ GCC_except_table107
+ GCC_except_table116
+ GCC_except_table139
+ GCC_except_table141
+ GCC_except_table203
+ _OBJC_IVAR_$_PLContextualizedMetricData._reducedAccuracySeconds
+ ___35+[PLUtilities getHardwarePerfKind:]_block_invoke
+ ___46+[PLSQLiteConnection tableColumnPresenceCache]_block_invoke
+ ___49+[PLSQLiteConnection tableColumnPresenceCacheSem]_block_invoke
+ ___snprintf_chk
+ _getHardwarePerfKind:.cache
+ _getHardwarePerfKind:.cacheOnce
+ _tableColumnPresenceCache.onceToken
+ _tableColumnPresenceCache.tableColumnPresenceCache
+ _tableColumnPresenceCacheSem.onceToken
+ _tableColumnPresenceCacheSem.tableColumnPresenceCacheSem
- GCC_except_table101
- GCC_except_table105
- GCC_except_table133
- GCC_except_table72
- GCC_except_table94
- GCC_except_table96
CStrings:
+ "%@|%@|%@"
+ "CPUEnergyM"
+ "CoreSpeech"
+ "DaySinceAccountChange"
+ "DaySinceReset"
+ "DaySinceSetup"
+ "DaySinceUpgrade"
+ "Indexing"
+ "MailProgress"
+ "MessagesDonated"
+ "MessagesIndexable"
+ "OneMonthDonatedPercentage"
+ "OneMonthHeaderDonationPercentage"
+ "OneMonthIndexableCount"
+ "OneYearDonatedPercentage"
+ "OneYearHeaderDonationPercentage"
+ "OneYearIndexableCount"
+ "PDEB"
+ "PDTP"
+ "RedonationCount"
+ "ReducedAccuracy"
+ "SiriTools"
+ "SixMonthDonatedPercentage"
+ "SixMonthHeaderDonationPercentage"
+ "SixMonthIndexableCount"
+ "SuppressionType2ClientStateChange"
+ "ThreeMonthDonatedPercentage"
+ "ThreeMonthHeaderDonationPercentage"
+ "ThreeMonthIndexableCount"
+ "TotalDonatedMessageBodies"
+ "TotalDonatedMessages"
+ "TotalIndexableMessages"
+ "TotalPendingRedonationsCount"
+ "ViewObstructedType2StateChange"
+ "batteryPackIndex"
+ "bookmarkFailureCount"
+ "bookmarkRecoveryCount"
+ "cascadeEntitiesQueriedCount"
+ "embeddingsCount"
+ "embeddingsSizeBytes"
+ "entitiesExtractionCount"
+ "entitiesProcessedCount"
+ "entityCount"
+ "enumCount"
+ "hw.perflevel%u.name"
+ "intentCount"
+ "lmeSlotEntityCount"
+ "lmeSlotUpdatedCount"
+ "profileRebuildCount"
+ "profileRebuildReason"
+ "profileSizeBytes"
+ "rankingEventCount"
+ "rankingEventType"
+ "rankingItemsPerEventAvg"
+ "rankingItemsPerEventMax"
+ "reducedAccuracy"
+ "totalItemCount"
+ "\xf0\xf0Ec"
- "\xf0\xf05c"
```
