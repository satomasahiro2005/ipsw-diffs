## ProactiveInputPredictionsInternals

> `/System/Library/PrivateFrameworks/ProactiveInputPredictionsInternals.framework/ProactiveInputPredictionsInternals`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2428c` | `0x24270` | **`-0x1c`** |

### Other Changes

```diff

-1331.0.1.0.0
+1334.0.1.0.0
Functions:
~ +[PSGDPDeviceMetricsCollector recordEngagementMetrics:selectedRecorder:ignoredRecorder:] : 876 -> 872
~ +[PSGDPDeviceMetricsCollector getActiveTrialInformationWithWithXPCActivityManager:activity:] : 852 -> 860
~ ___122+[PSGDPDeviceMetricsCollector onCompletionWithXPCActivityManager:activity:engagementMetrics:idsService:destinationDevice:]_block_invoke : 2084 -> 2080
~ ___57-[PSGDPDeviceMetricsCollector collectDeviceQREngagement:]_block_invoke : 712 -> 708
~ +[PSGDPDeviceMetricsCollector sendEngagementToDPUsingData:] : 2848 -> 2844
~ +[PSGDiagnostics getDiagnosticsInfoForReportCrash] : 632 -> 628
~ -[PSGInternalRequestHandler sysdiagnoseInformationWithCompletion:] : 644 -> 640
~ -[PSGExperimentResolver init] : 1316 -> 1308
~ -[PSGInputSuggesterMetricsLogger _populatePredictionItems:proto:] : 600 -> 596
```
