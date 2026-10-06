## Sentry

> `/System/Library/PrivateFrameworks/Sentry.framework/Sentry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10460` | `0x10430` | **`-0x30`** |

### Other Changes

```text
Functions:
~ -[STYWorkflowResponsivenessMonitorHelper handleSignpost:] : 468 -> 456
~ -[STYUserScenarioCache loadWhitelist:platform:bundles:] : 468 -> 464
~ -[STYUserScenarioCache appNameFromBundleId:] : 344 -> 340
~ ___46-[STYWorkflowResponsivenessMonitorHelper init]_block_invoke_2 : 1260 -> 1256
~ -[STYWorkflowResponsivenessMonitorHelper resetState] : 256 -> 252
~ -[STYWorkflowResponsivenessMonitorHelper resetCounts] : 1204 -> 1200
~ -[STYWorkflowResponsivenessMonitorHelper resetPerDayCounts] : 1192 -> 1188
~ -[STYWorkflowResponsivenessMonitorHelper resetPerPeriodCounts] : 1192 -> 1188
~ -[STYWorkflowResponsivenessMonitorHelper updateAllowList] : 856 -> 852
~ -[STYSignpostStreamingStatistics _emitTelemetryLockedEndTime:] : 2012 -> 2008
```
