## HealthRecordsPlugin

> `/System/Library/PrivateFrameworks/HealthRecordsPlugin.framework/HealthRecordsPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb6428` | `0xb6420` | **`-0x8`** |

### Other Changes

```diff

-  Functions: 3548
+  Functions: 3549
Functions:
~ -[HDClinicalDailyAnalyticsManager _fetchAccountAnalyticsCollectsClinicalOptInData:collectsImproveHealthAndActivityData:error:] : 1552 -> 1548
+ _OUTLINED_FUNCTION_0
~ -[HDHealthRecordsProfileExtension _ivarLock_updateHealthRecordsSupportedStatus].cold.1 : 60 -> 56
~ -[HDHealthRecordsProfileExtension _supportedFHIRConfiguration].cold.1 : 60 -> 56
~ ___76-[HDHealthRecordsProfileExtension didUpdateSourcesForAccountWithIdentifier:]_block_invoke.cold.1 : 76 -> 64
~ -[HDHealthRecordsProfileExtension notificationSyncClient:didReceiveInstructionWithAction:].cold.1 : 104 -> 100
~ -[HDHealthRecordsProfileExtension _deleteSignedClinicalDataRecords].cold.1 : 60 -> 56
```
