## Summaries

> `/System/Library/Health/FeedItemPlugins/Summaries.healthplugin/Summaries`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b594c` | `0x203be0` | **`+0x4e294`** |
| `__TEXT.__eh_frame` | `0x47a0` | `0xa62c` | **`+0x5e8c`** |
| `__DATA_CONST.__got` | `0x2248` | `0x0` | **`-0x2248`** |
| `__TEXT.__unwind_info` | `0x3eb8` | `0x5668` | **`+0x17b0`** |
| `__TEXT.__const` | `0xa6d4` | `0xb6b4` | **`+0xfe0`** |
| `__DATA.__bss` | `0x86b8` | `0x9458` | **`+0xda0`** |
| `__TEXT.__swift_as_cont` | `0x15c` | `0xe90` | **`+0xd34`** |
| `__TEXT.__cstring` | `0x5b10` | `0x6779` | **`+0xc69`** |
| `__AUTH.__data` | `0x2948` | `0x3230` | **`+0x8e8`** |
| `__DATA.__data` | `0x2338` | `0x2c18` | **`+0x8e0`** |
| `__AUTH_CONST.__auth_got` | `0x3f00` | `0x4678` | **`+0x778`** |
| `__AUTH_CONST.__objc_const` | `0x2fe0` | `0x3638` | **`+0x658`** |
| `__TEXT.__oslogstring` | `0x5271` | `0x5761` | **`+0x4f0`** |
| `__TEXT.__swift5_reflstr` | `0x4033` | `0x44ab` | **`+0x478`** |
| `__TEXT.__swift5_fieldmd` | `0x2d10` | `0x305c` | **`+0x34c`** |
| `__TEXT.__constg_swiftt` | `0x46d4` | `0x49d8` | **`+0x304`** |
| `__TEXT.__swift_as_ret` | `0x8c` | `0x2ec` | **`+0x260`** |
| `__TEXT.__swift_as_entry` | `0x68` | `0x284` | **`+0x21c`** |
| `__AUTH.__objc_data` | `0x6a0` | `0x8b8` | **`+0x218`** |
| `__DATA_DIRTY.__data` | `0x64a8` | `0x62a8` | **`-0x200`** |
| `__TEXT.__swift5_capture` | `0x13f4` | `0x11fc` | **`-0x1f8`** |
| `__TEXT.__swift5_typeref` | `0x3ddc` | `0x3f52` | **`+0x176`** |
| `__TEXT.__swift5_assocty` | `0x1028` | `0x1188` | **`+0x160`** |
| `__AUTH_CONST.__const` | `0x7089` | `0x6f38` | **`-0x151`** |
| `__DATA_CONST.__objc_selrefs` | `0x1210` | `0x1360` | **`+0x150`** |
| `__DATA.__common` | `0x158` | `0x278` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x2f0` | `0x3f0` | **`+0x100`** |
| `__DATA_DIRTY.__common` | `0x238` | `0x1c8` | **`-0x70`** |
| `__TEXT.__swift5_proto` | `0x808` | `0x874` | **`+0x6c`** |
| `__TEXT.__swift5_types` | `0x408` | `0x450` | **`+0x48`** |
| `__DATA_CONST.__objc_classlist` | `0x120` | `0x158` | **`+0x38`** |
| `__DATA_CONST.__objc_protolist` | `0x70` | `0x80` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x60` | `0x5c` | **`-0x4`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

+  - /System/Library/PrivateFrameworks/HealthDomains.framework/HealthDomains

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 5575
-  Symbols:   515
-  CStrings:  839
+  Functions: 6956
+  Symbols:   531
+  CStrings:  921
Symbols:
+ _CGBitmapContextCreate
+ _CGColorSpaceCreateDeviceGray
+ _CGImageCreateWithImageInRect
+ _CGImageGetHeight
+ _CGImageGetWidth
+ _FITypicalDayActivityModelDaysOfActivityHistory
+ _HKFeatureIdentifierSleepApneaNotifications
+ _HKQuantityTypeIdentifierAppleMoveTime
+ _HKQuantityTypeIdentifierAppleSleepingBreathingDisturbances
+ _HKQuantityTypeIdentifierHeartRate
+ _OBJC_CLASS_$_FITypicalDayActivityModel
+ _OBJC_CLASS_$_HKBilateralQuantitySample
+ _OBJC_CLASS_$_HKCodableSummaryBilateralQuantityValue
+ _OBJC_CLASS_$_HKCorrelationType
+ _OBJC_CLASS_$_HKOverheadSquatSample
+ _OBJC_CLASS_$_HKSPSleepStore
+ _OBJC_CLASS_$_UIGraphicsImageRenderer
+ __HKCategoryTypeIdentifierWristEvent
+ _objc_release_x9
+ _swift_allocateMetadataPack
+ _swift_allocateWitnessTablePack
+ _swift_asyncLet_get
+ _swift_deletedAsyncMethodErrorTu
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
- _HKSampleSortIdentifierStartDate
- _OBJC_CLASS_$_HKSource
- _OBJC_CLASS_$_UIApplication
- _OBJC_CLASS_$_UIScene
- __os_feature_enabled_impl
- _swift_continuation_throwingResume
- _swift_continuation_throwingResumeWithError
- _swift_isUniquelyReferenced_nonNull_bridgeObject
- _swift_retain_x9
CStrings:
+ "%{public}s Additional input signals provider declined the work plan for sample type %{public}s"
+ "%{public}s Sent dismiss instruction for %s successfully"
+ ":heartRateDistribution"
+ ":mostRecentSleepSample"
+ ":sleepDaySummaries"
+ "Cell.DataTypeDetail."
+ "DATA_TYPE_DETAIL_HEIGHT_AND_WEIGHT_SECTION_TITLE"
+ "DATA_TYPE_DETAIL_WAIST_AND_HEIGHT_SECTION_TITLE"
+ "DATA_TYPE_DETAIL_WAIST_AND_HIP_SECTION_TITLE"
+ "DayPhaseProviderFetcher"
+ "DerivedMeasureInputsSection_"
+ "Failed to fetch cached activity dashboard model: %{public}s"
+ "Failed to fetch cached sleep dashboard model: %{public}s"
+ "Failed to fetch next scheduled occurrence: %{public}s"
+ "HKBilateralQuantityTypeIdentifierAnkleDorsiflexion"
+ "HKBilateralQuantityTypeIdentifierElbowFlexion"
+ "HKBilateralQuantityTypeIdentifierHipFlexionKneeExtension"
+ "HKBilateralQuantityTypeIdentifierHipFlexionKneeFlexion"
+ "HKBilateralQuantityTypeIdentifierKneeFlexion"
+ "HKBilateralQuantityTypeIdentifierShoulderFlexion"
+ "HKBilateralQuantityTypeIdentifierSingleLegStanceTime"
+ "Quick log title text"
+ "Section header listing the data types BMI is calculated from"
+ "Section header listing the data types waist-to-height ratio is calculated from"
+ "Section header listing the data types waist-to-hip ratio is calculated from"
+ "Summaries.DerivedMeasureInputsDataSource"
+ "Summaries.TypicalDayDelegate"
+ "Summaries/ActivityDataTypeDetailChartCell.swift"
+ "Summaries/ActivityDataTypeDetailChartDataSource.swift"
+ "Summaries/BloodGlucoseDataEntryLoggingView.swift"
+ "Summaries/BodyMassIndexDataEntryLoggingView.swift"
+ "Summaries/CategoryDurationDataEntryLoggingView.swift"
+ "Summaries/DataEntryHeightValueView.swift"
+ "Summaries/DataEntryWorkoutActivityView.swift"
+ "Summaries/DerivedMeasureInputsComponent.swift"
+ "Summaries/HeightDataEntryLoggingView.swift"
+ "Summaries/InsulinDeliveryDataEntryLoggingView.swift"
+ "Summaries/MindfulMinutesDataEntryLoggingView.swift"
+ "Summaries/ProfileUserDataObserver.swift"
+ "Summaries/ProminentQuantityDataEntryLoggingView.swift"
+ "Summaries/SignificantChangesNotificationSwitchCellViewController.swift"
+ "Summaries/SnidgetLevelChartView.swift"
+ "Summaries/SnidgetMultiValueLevelChartView.swift"
+ "Summaries/StateOfMindSnidgetFeedItemProvider.swift"
+ "Summaries/SummariesInternalSettingsView.swift"
+ "Summaries/SummaryAlertTileViewController.swift"
+ "Summaries/SummaryTrendTileView.swift"
+ "Summaries/SummaryTrendView.swift"
+ "Summaries/UVExposureDataEntryLoggingView.swift"
+ "Summaries/WorkoutsDataEntryLoggingView.swift"
+ "Summaries/WorkoutsDataTypeDetailConfigurationProvider.swift"
+ "[%s] Could not create data type detail view controller for %s: %s"
+ "[%s] Failed to build the trimmed set-up icon; falling back to untrimmed symbol"
+ "[%s] Failed to create trend arbitration providers: %@"
+ "[%s] Failed to delete trend feed items: %@"
+ "[%s] Failed to load body composition classification: %s"
+ "[%s] Failed to write trend feed items: %@"
+ "[%s] No display type for %s"
+ "[%s] Unable to resolve HKHealthStore"
+ "[%s] Wrote %ld, deleted %ld trend feed items"
+ "[%s]: Bilateral sample carries neither side: %s"
+ "[%{public}s] Can't make a work plan due to unexpected missing calendar change anchor"
+ "[%{public}s] Can't make a work plan due to unexpected missing cardio-fitness feature status anchor"
+ "[%{public}s] Daytime vitals anchor has no summary matching today; using a no-data daytime summary"
+ "[%{public}s] Missing calendar-change anchor; skipping"
+ "[%{public}s] Missing overnight vitals anchor; skipping Balance work plan"
+ "[%{public}s] No daytime vitals anchor; using a no-data daytime summary"
+ "[%{public}s] Overnight vitals anchor has no summary for today; skipping Balance work plan"
+ "[%{public}s] Submitting %ld item(s) for arbitration (%{public}s)"
+ "[%{public}s] Work plan has no overnight vitals summary"
+ "[%{public}s]: %{public}s is not a sample type"
+ "[%{public}s]: No bilateral measure mapped for %s"
+ "[%{public}s]: No detail-room measure for %s"
+ "[%{public}s]: Unable to format the %{public}s value"
+ "[TypicalDayActivityProgressFetcher] Activity summary prefetch failed: %{public}@"
+ "[TypicalDayActivityProgressFetcher] Failed to derive history range; skipping."
+ "[TypicalDayActivityProgressFetcher] Wrist-on prefetch failed: %{public}@"
+ "_createCheckedThrowingContinuation(_:)"
+ "acknowledgeNotification(response:notificationContentStateManager:)"
+ "arbitration-day-phase"
+ "com.apple.HealthPlatform"
+ "dashboard-activity-tile"
+ "dashboard-heart-tile"
+ "dashboard-trends-"
+ "didReceiveHealthSharingNotification(response:notificationContentStateManager:)"
+ "fetchActivitySummary(sample:)"
+ "fetchCachedSleepModel(storage:)"
+ "fetchCachedTypicalDayProgress(storage:)"
+ "fetchCumulativeTimePeriod(sample:)"
+ "fetchLatestStatisticsCollection(mostRecentDataDate:samplePredicate:)"
+ "fetchMostRecentSample()"
+ "fetchPreviousModels()"
+ "fetchStatisticsCollection()"
+ "hasImageAttachment(for:)"
+ "makeChartSharableModel(audience:)"
+ "makeCurrentValue()"
+ "makeCurrentValue(sample:supplementaryValue:)"
+ "makeTransactionBuilder()"
+ "plus.circle.fill"
+ "run(currentResult:)"
+ "saveCachedModelIfNecessary(from:)"
+ "sendDismissNotificationInstruction(for:notificationSyncStore:)"
+ "updateFeedItem(currentResult:)"
+ "updateFeedItem(currentResult:audience:)"
+ "updateFeedItems(currentResult:)"
+ "userNotificationCenter(_:didReceive:)"
+ "yesterday today "
- "%s could not query for latest sample, predicate is nil"
- "%s unable to create Blood Oxygen App HKSource"
- "%s unable to create Cycle Tracking App HKSource"
- "%s unable to create Health App HKSource"
- "%s unable to create Medications App HKSource"
- "%s unable to create Shortcuts HKSource"
- "%s unable to create Siri HKSource"
- "%s: Unexpectedly received more than one sample."
- "%{public}s Can not find connected scene. Something is really wrong!"
- "%{public}s Delegate released before dismiss instruction could be sent; fulfilling completion handler without sending"
- "%{public}s Sent dismiss instruction for %s successfully: %{bool}d"
- "%{public}s Work for work plan with sample type %{public}s failed with error: %{public}s"
- "DaytimeMetrics"
- "Health"
- "VitalsEnhancements"
- "[%{public}s] Failed to update %s: %{public}s"
- "[%{public}s] Updated %s"
- "[%{public}s] query found %s summarie(s)."
- "acknowledgeNotification(response:notificationContentStateManager:completionHandler:)"
- "activitySummary hasHadWatch activityResumeDate "
- "com.apple.health.vitals.demodata"
- "didReceiveHealthSharingNotification(response:notificationContentStateManager:completionHandler:)"
- "fetchLatestCorrelationSample()"
- "sendDismissNotificationInstruction(for:notificationSyncStore:completionHandler:)"
- "userNotificationCenter(_:didReceive:withCompletionHandler:)"
```
