## Heart

> `/System/Library/Health/FeedItemPlugins/Heart.healthplugin/Heart`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x328aa0` | `0x32972c` | **`+0xc8c`** |
| `__TEXT.__cstring` | `0x1515e` | `0x1588e` | **`+0x730`** |
| `__TEXT.__eh_frame` | `0x8d78` | `0x9140` | **`+0x3c8`** |
| `__TEXT.__oslogstring` | `0x9e51` | `0x9c91` | **`-0x1c0`** |
| `__AUTH.__objc_data` | `0x7c18` | `0x7a78` | **`-0x1a0`** |
| `__AUTH_CONST.__objc_const` | `0xe5b8` | `0xe510` | **`-0xa8`** |
| `__AUTH.__data` | `0x86c0` | `0x8760` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x13738` | `0x137d8` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0xcd20` | `0xcc84` | **`-0x9c`** |
| `__TEXT.__swift5_capture` | `0x3a74` | `0x39e8` | **`-0x8c`** |
| `__DATA.__bss` | `0x142d8` | `0x14358` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x9450` | `0x94c8` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x4ec0` | `0x4f30` | **`+0x70`** |
| `__DATA.__data` | `0x8200` | `0x8190` | **`-0x70`** |
| `__TEXT.__swift5_reflstr` | `0x8526` | `0x84b6` | **`-0x70`** |
| `__TEXT.__const` | `0x19c74` | `0x19cd4` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x7a46` | `0x7aa4` | **`+0x5e`** |
| `__TEXT.__swift5_assocty` | `0x1038` | `0x1080` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x1e64` | `0x1e2c` | **`-0x38`** |
| `__TEXT.__swift_as_cont` | `0x5a8` | `0x5dc` | **`+0x34`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c70` | `0x1c98` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x7d48` | `0x7d20` | **`-0x28`** |
| `__TEXT.__swift_as_ret` | `0x2a4` | `0x2b8` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x248` | `0x254` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x2e08` | `0x2e10` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x5f8` | `0x5f0` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x988` | `0x990` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x11a8` | `0x11ac` | **`+0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 13215
+  Functions: 13242

-  CStrings:  2343
+  CStrings:  2362
CStrings:
+ "AFibBurdenLifeFactorsTileViewController:mostRecentEndDate"
+ "AFibBurdenLifeFactorsTileViewController:startObservingLifeFactorChanges"
+ "AFibBurdenPDFChartAverageQuery:chartPoints"
+ "AFibBurdenPDFChartDailyAverageQuery:queryForStatisticsCollection"
+ "AFibBurdenPDFChartDateIntervalProvider:computeAnchoredDateIntervals"
+ "AFibBurdenPDFChartJulianIndexedSampleQuery:chartPoints"
+ "AFibBurdenPDFExportPPTTestRunner:preWarmTachogramClassificationCache"
+ "BloodPressureJournalCreationCoordinator:hasReceivedHypertensionEventInPastThirtyDays"
+ "BloodPressureJournalLoggingAnalyticsUtilities:fetchDaysSinceLastHTNotification"
+ "BloodPressureJournalSummaryBuilder:fetchAverageStatistics"
+ "BloodPressureJournalSummaryBuilder:fetchBloodPressureJournalSummary"
+ "BloodPressurePDFIntervalDataSource:fetchPregnancySamples"
+ "BloodPressurePDFSectionProvider:collectionStatistics:"
+ "BloodPressurePDFSectionProvider:statistics:"
+ "BloodPressurePDFUtilities:fetchBloodPressureReadings"
+ "CardioFitnessOnboardingMostRecentValueProvider:lastSampleQueryPublisher"
+ "CardioFitnessReclassificationExecutor:hasVO2MaxSample"
+ "Failed to encode actionHandlerUserData: %s"
+ "Heart/AFibBurdenPDFChartDateIntervalProvider.swift"
+ "Heart/CardioFitnessRetroComputePromptTileView.swift"
+ "Heart/CardioFitnessRetroComputeTileActionHandler.swift"
+ "Heart/RelatedSampleTypesGenerator.swift"
+ "Heart/RelatedSampleTypesGeneratorPipeline.swift"
+ "HeartHealthPluginDelegate+EscalationViewProviding:latestHypertensionEvent"
+ "HypertensionNotificationsRoomViewController:presentHypertensionEventSampleMetadataView"
+ "[%{public}s] Failed to encode PromptTileViewModel for cardio fitness retrocompute tile"
+ "[%{public}s] Failed to update retrocompute tile presentation state: %{public}s"
+ "chevron.backward"
+ "completedDismissalDate or lastSeenRetroComputeCompleteDate"
+ "init(displayType:profile:mode:isDashboardEnabledProvider:)"
+ "💣 Could not create a room for the blood pressure escalation's readings!"
- "CardioFitnessRetroComputeTileViewController loaded"
- "Heart/CardioFitnessRetroComputeTipTileViewController.swift"
- "[%{public}s] Finished reset available dismissal states"
- "[%{public}s] Finished reset completed dismissal and last seen dates"
- "[%{public}s] Finished set last seen date"
- "[%{public}s] Resetting available dismissal states"
- "[%{public}s] Resetting completed dismissal and last seen dates"
- "[%{public}s] Setting available dismissal date"
- "[%{public}s] Setting completed dismissal date"
- "[%{public}s] Setting last seen date if needed"
- "[%{public}s] Setting last seen retrocompute complete date"
- "[%{public}s] Setting last seen retrocompute complete date if needed"
```
