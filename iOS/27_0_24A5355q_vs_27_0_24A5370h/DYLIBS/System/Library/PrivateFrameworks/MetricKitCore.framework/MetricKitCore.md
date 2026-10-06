## MetricKitCore

> `/System/Library/PrivateFrameworks/MetricKitCore.framework/MetricKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d8d0` | `0x1d7e0` | **`-0xf0`** |

### Other Changes

```diff

-353.0.0.0.0
+356.0.0.0.0
Functions:
~ -[MXDeliveryDataCacher saveMetrics:toDeliveryDirectoryForBundleID:] : 740 -> 736
~ -[MXDeliveryDataCacher _mergeDiagnostic:withExistingForClient:] : 1780 -> 1776
~ -[MXDeliveryDataCacher _metricsFromFilepaths:] : 636 -> 632
~ -[MXDeliveryDataCacher _diagnosticsFromFilepaths:] : 636 -> 632
~ -[MXCoreHandler _reportMetricKitUsage] : 252 -> 248
~ -[MXCoreHandler _successCountFromSavingMetricPayloadsToDeliveryDirectoryForClientMetrics:] : 412 -> 408
~ -[MXPayloadValidator _validatePowerlogData:] : 392 -> 388
~ -[MXPayloadValidator _validateHangTracerData:] : 464 -> 460
~ -[MXPayloadValidator _validateSpinTracerData:] : 464 -> 460
~ -[MXPayloadValidator _validateReportCrashData:] : 424 -> 420
~ -[MXPayloadValidator _validateSpaceAttributionData:] : 392 -> 388
~ -[MXDiagnosticServices cleanServiceDiagnosticsDirectoriesForClient:] : 508 -> 504
~ -[MXDiagnosticServices _createServicesForClient:] : 536 -> 532
~ -[MXDiagnosticServices _startServices] : 536 -> 532
~ -[MXDiagnosticServices _stopServices] : 496 -> 492
~ -[MXDiagnosticServices _diagnosticsFromServicesForClient:dateString:] : 512 -> 508
~ -[MXMetricServices _startServices] : 512 -> 508
~ -[MXMetricServices _stopServices] : 496 -> 492
~ -[MXMetricServices _cleanServiceMetricsDirectories] : 488 -> 484
~ -[MXMetricServices _isMetricSourceDataAvailable] : 468 -> 464
~ -[MXMetricServices _metricsFromServicesForClient:] : 488 -> 484
~ -[MXMetricServices _clientMetricsFromServices] : 440 -> 436
~ -[MXCleanUtil _cleanAllDeliveryDirectories] : 436 -> 428
~ -[MXCleanUtil _cleanAllSourceDirectories] : 508 -> 500
~ -[MXCleanUtil _cleanAllDataForSourceDirectory:] : 336 -> 332
~ -[MXCleanUtil _cleanDirectoriesForUninstalledClients] : 284 -> 280
~ -[MXCleanUtil _cleanSourceDirectoriesForClient:] : 308 -> 304
~ -[MXCleanUtil _cleanMetricDeliveryDirectoriesForStaleData] : 284 -> 280
~ -[MXCleanUtil _subdirectoriesFromDirectory:] : 484 -> 480
~ -[MXCleanUtil _filenamesFromDirectory:] : 544 -> 540
~ -[MXCleanUtil _datesFromMetricFilenames:] : 364 -> 360
~ -[MXCleanUtil _cleanDiagnosticDeliveryDirectoriesForStaleData] : 284 -> 280
~ -[MXCleanUtil _datesFromDiagnosticFilenames:] : 364 -> 360
~ -[MXCleanUtil _latestDateFromDates:] : 364 -> 360
~ -[MXCleanUtil _cleanClientlessSourceDirectoriesForStaleData] : 248 -> 244
~ -[MXCleanUtil _cleanStaleDataForSourceDirectory:] : 356 -> 352
~ -[MXCleanUtil _clientlessSourceDirectories] : 476 -> 472
~ -[MXCleanUtil _cleanClientfulSourceDirectoriesForStaleData] : 248 -> 244
~ -[MXCleanUtil _clientfulSourceDirectories] : 532 -> 528
~ -[MXDeliveryPathUtil _filepathsFromDirectory:withError:] : 372 -> 368
~ -[MXStorageUtil removeFiles:withFilenameContainsSubstring:fromDirectory:error:] : 468 -> 464
~ -[MXStorageUtil _removeFiles:fromDirectory:error:] : 388 -> 384
~ +[MXCorePayloadConstructor buildDiagnosticPayloadForClient:fromClientDiagnosticsDictionary:withDateString:withEventDate:] : 4020 -> 3996
~ +[MXCorePayloadConstructor buildMetricPayloadForClient:fromClientMetricsDictionary:] : 1152 -> 1148
~ +[MXCorePayloadConstructor _sampleReportedStatesForDomains:] : 452 -> 448
~ +[MXCorePayloadConstructor _sampleStateMetricsForReportedStates:] : 1068 -> 1060
~ sub_287f61024 -> sub_289bdcf4c : 956 -> 932
```
