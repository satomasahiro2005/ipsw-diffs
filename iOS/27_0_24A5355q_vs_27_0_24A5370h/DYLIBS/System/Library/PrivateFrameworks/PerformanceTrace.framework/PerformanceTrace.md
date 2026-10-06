## PerformanceTrace

> `/System/Library/PrivateFrameworks/PerformanceTrace.framework/PerformanceTrace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11124` | `0x110dc` | **`-0x48`** |

### Other Changes

```diff

-262.0.0.0.0
+264.0.0.0.0
Functions:
~ +[PTTraceConfig configWithDictionary:] : 5004 -> 4996
~ _PTDefaultTraceDirectoryAvailableTraceFileURLs : 624 -> 620
~ +[PTTraceConfig(ControlCenter) userSpecifiedCustomTracePlanArguments] : 484 -> 480
~ -[PTPassiveCollectionConfig initWithDictionary:] : 404 -> 400
~ -[PTPassiveCollectionConfig dictionaryRepresentation] : 372 -> 368
~ -[PTPassiveTraceConfig fetchCollectionConfiguration:] : 1084 -> 1080
~ _PTCValidateDataSourceConfigFields : 1100 -> 1092
~ _PTCValidateCollectionConfigurationDict : 752 -> 736
~ ___118-[PTTraceSession displayTraceCompletedAlertWithTraceFileURL:additionalInfo:notificationTimeoutSecs:completionHandler:]_block_invoke : 1244 -> 1224
```
