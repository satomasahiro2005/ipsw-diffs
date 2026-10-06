## HealthToolbox

> `/System/Library/PrivateFrameworks/HealthToolbox.framework/HealthToolbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x7a69` | `0x7fa9` | **`+0x540`** |
| `__TEXT.__text` | `0x65ae4` | `0x65f90` | **`+0x4ac`** |
| `__AUTH_CONST.__cfstring` | `0x5500` | `0x58a0` | **`+0x3a0`** |
| `__AUTH_CONST.__objc_const` | `0xb280` | `0xb2e0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x4870` | `0x4898` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x6ff8` | `0x7020` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0xb0` | `0xcc` | **`+0x1c`** |
| `__TEXT.__unwind_info` | `0x1a30` | `0x1a48` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x808` | `0x7f8` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x6ac` | `0x6b4` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xc88` | `0xc90` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xc34` | `0xc3c` | **`+0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 2393
-  Symbols:   4558
-  CStrings:  1096
+  Functions: 2399
+  Symbols:   4562
+  CStrings:  1124
Symbols:
+ -[WDAtrialFibrillationEventOverviewViewController initWithDisplayType:profile:mode:isDashboardEnabledProvider:]
+ -[WDAtrialFibrillationEventOverviewViewController isDashboardEnabledProvider]
+ -[WDElectrocardiogramOverviewViewController initWithDisplayType:profile:mode:isDashboardEnabledProvider:]
+ -[WDElectrocardiogramOverviewViewController isDashboardEnabledProvider]
+ -[WDStoredDataByCategoryViewController _displayType:matchesCapturedSampleType:]
+ GCC_except_table34
+ _OBJC_CLASS_$_HKHealthFactSampleType
+ _OBJC_IVAR_$_WDAtrialFibrillationEventOverviewViewController._isDashboardEnabledProvider
+ _OBJC_IVAR_$_WDElectrocardiogramOverviewViewController._isDashboardEnabledProvider
- -[WDAtrialFibrillationEventOverviewViewController initWithDisplayType:profile:mode:]
- -[WDElectrocardiogramOverviewViewController initWithDisplayType:profile:mode:]
- GCC_except_table33
- _swift_release_x22
- _swift_release_x23
CStrings:
+ "SurveyKitAppPlugin.healthplugin"
+ "WDAtrialFibrillationEventOverviewViewController:recomputeTotalSampleCount"
+ "WDDisplayTypeDataSourcesTableViewController:_fetchDataSourcesForSampleType"
+ "WDDocumentListDataProvider:createQueryForSampleType"
+ "WDDocumentListDataProvider:refineSamplesWithCompletion"
+ "WDDocumentOverviewViewController:_recomputeTotalReportCount"
+ "WDElectrocardiogramFilterDataProvider:_countQueryForType"
+ "WDExertionDataFetcher:start"
+ "WDExportManager:_exportElectrocardiogramsWithName"
+ "WDExportManager:_exportHealthRecords"
+ "WDExportManager:_queryForSamplesOfType"
+ "WDExportManager:_writeActivitySummaries"
+ "WDExportManager:_writeAudiogramType"
+ "WDExportManager:_writeCategoryType"
+ "WDExportManager:_writeCorrelationType"
+ "WDExportManager:_writeDataForWorkoutRoutes"
+ "WDExportManager:_writeEffortScoresForWorkout"
+ "WDExportManager:_writeHRVAndTachograms"
+ "WDExportManager:_writeMedicalRecords"
+ "WDExportManager:_writePrescriptionType"
+ "WDExportManager:_writeWorkoutRouteForWorkout"
+ "WDExportManager:_writeWorkoutType"
+ "WDHeartEventListDataProvider:associatedHeartRatePerEvent"
+ "WDHeartEventListDataProvider:events:%@"
+ "WDHeartbeatSequenceListDataProvider:createQueryForSampleType"
+ "WDSampleListDataProvider:createQueryForSampleType:%@"
+ "WDSampleListStatisticsDataProvider:complete:%@"
+ "WDSampleListStatisticsDataProvider:partial:%@"
+ "WDWorkoutRouteListDataProvider:createQueryForSampleType"
- "!)"
```
