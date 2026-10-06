## Heart

> `/System/Library/Health/FeedItemPlugins/Heart.healthplugin/Heart`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ed080` | `0x3235a0` | **`+0x36520`** |
| `__TEXT.__cstring` | `0x1318e` | `0x1511e` | **`+0x1f90`** |
| `__TEXT.__eh_frame` | `0x7034` | `0x8940` | **`+0x190c`** |
| `__TEXT.__const` | `0x19204` | `0x19ad4` | **`+0x8d0`** |
| `__TEXT.__unwind_info` | `0x8a30` | `0x92f8` | **`+0x8c8`** |
| `__DATA.__bss` | `0x13d78` | `0x144b8` | **`+0x740`** |
| `__DATA.__data` | `0x7b40` | `0x8250` | **`+0x710`** |
| `__AUTH_CONST.__auth_got` | `0x49d0` | `0x4e78` | **`+0x4a8`** |
| `__AUTH_CONST.__const` | `0x131c8` | `0x13658` | **`+0x490`** |
| `__TEXT.__swift5_typeref` | `0x7642` | `0x798a` | **`+0x348`** |
| `__TEXT.__oslogstring` | `0x9a41` | `0x9d81` | **`+0x340`** |
| `__TEXT.__swift5_capture` | `0x3780` | `0x3a70` | **`+0x2f0`** |
| `__AUTH.__data` | `0x8728` | `0x89d8` | **`+0x2b0`** |
| `__TEXT.__swift5_reflstr` | `0x8216` | `0x8476` | **`+0x260`** |
| `__TEXT.__swift5_fieldmd` | `0x7aac` | `0x7cf0` | **`+0x244`** |
| `__AUTH.__objc_data` | `0x7cf0` | `0x7ef0` | **`+0x200`** |
| `__DATA_CONST.__got` | `0x2be8` | `0x2de8` | **`+0x200`** |
| `__DATA_DIRTY.__data` | `0x4898` | `0x4748` | **`-0x150`** |
| `__TEXT.__objc_methlist` | `0x1f9c` | `0x1e64` | **`-0x138`** |
| `__TEXT.__constg_swiftt` | `0xcbe8` | `0xccec` | **`+0x104`** |
| `__DATA_DIRTY.__bss` | `0xa900` | `0xa800` | **`-0x100`** |
| `__TEXT.__swift_as_cont` | `0x4a4` | `0x580` | **`+0xdc`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d30` | `0x1c70` | **`-0xc0`** |
| `__TEXT.__swift5_assocty` | `0xf70` | `0x1008` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0xe518` | `0xe578` | **`+0x60`** |
| `__TEXT.__swift_as_entry` | `0x1dc` | `0x238` | **`+0x5c`** |
| `__DATA.__common` | `0x978` | `0x9c0` | **`+0x48`** |
| `__TEXT.__swift_as_ret` | `0x250` | `0x290` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x1160` | `0x1198` | **`+0x38`** |
| `__DATA_DIRTY.__objc_data` | `0x1370` | `0x13a0` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0x954` | `0x984` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x5d8` | `0x5f8` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x244` | `0x258` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x1e8` | `0x1d8` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x130` | `0x138` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xf0` | `0xe8` | **`-0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  - /System/Library/PrivateFrameworks/HealthExpressions.framework/HealthExpressions

+  - /System/Library/PrivateFrameworks/HealthMenstrualCycles.framework/HealthMenstrualCycles

+  - /System/Library/PrivateFrameworks/HealthReportCoreUI.framework/HealthReportCoreUI

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 12654
-  Symbols:   689
-  CStrings:  2195
+  Functions: 13133
+  Symbols:   690
+  CStrings:  2339
Symbols:
+ _HKBloodPressureClassificationCategoryAHASevereHypertension
+ _HKCardioFitnessAgeUpperBound
+ _HKUIDeviceSpecificLocStr
+ _OBJC_CLASS_$_HKCardioFitnessClassificationUtilities
+ _OBJC_CLASS_$_HKCardioFitnessLevelData
+ _OBJC_CLASS_$_HKCardioFitnessThresholdCoefficientRow
+ _OBJC_CLASS_$_HKCardioFitnessThresholdModelSource
+ _OBJC_CLASS_$_HKMCPregnancyModelProvider
+ _OBJC_CLASS_$_HKRegulatoryDomainManager
+ _OBJC_CLASS_$_NSError
+ _swift_checkMetadataState
+ _swift_getDynamicType
+ _swift_release_x10
+ _swift_task_deinitOnExecutor
+ _swift_task_reportUnexpectedExecutor
- _HKBloodPressureClassificationCategoryAHAHypertensiveCrisis
- _OBJC_CLASS_$_HKMobileCountryCodeManager
- _OBJC_CLASS_$_HKSeparatorLineView
- _OBJC_CLASS_$_HKSleepDaySummaryCacheSettings
- _OBJC_CLASS_$_HKSleepDaySummaryCollection
- _OBJC_CLASS_$_HKSleepDaySummaryCollectionQuery
- _OBJC_CLASS_$_UIApplication
- _OBJC_CLASS_$_UIDevice
- _OBJC_CLASS_$_WDAddDataViewController
- _objc_release_x1
- _objc_retainAutoreleaseReturnValue
- _objc_retain_x4
- _swift_continuation_resume
- _swift_isaMask
CStrings:
+ "%.1f / %.1f / %.1f"
+ "%.4f × age + %.4f"
+ "Active Criteria — Legacy Table (mL/kg/min)"
+ "CARDIO_FITNESS_RECLASSIFICATION_TILE_ACTION"
+ "CARDIO_FITNESS_RECLASSIFICATION_TILE_BODY"
+ "CARDIO_FITNESS_RECLASSIFICATION_TILE_TITLE"
+ "Cardio Fitness Classification"
+ "CardioFitnessClassificationItem"
+ "CardioFitnessReclassificationDismissalDateInputSignal"
+ "CardioFitnessReclassificationTile"
+ "Coefficient Source"
+ "Escalation.HighBloodPressureNotifications.Description.AHA.SevereHypertension"
+ "Escalation.HighBloodPressureNotifications.Description.AHA.SevereHypertension.SingleMeasurement"
+ "Escalation.HighBloodPressureNotifications.Description.AHA.Stage1Hypertension"
+ "Escalation.HighBloodPressureNotifications.Description.AHA.Stage1Hypertension.SingleMeasurement"
+ "Escalation.HighBloodPressureNotifications.Description.AHA.Stage2Hypertension"
+ "Escalation.HighBloodPressureNotifications.Description.AHA.Stage2Hypertension.SingleMeasurement"
+ "Escalation.HighBloodPressureNotifications.Description.ESC.Hypertension"
+ "Escalation.HighBloodPressureNotifications.Description.ESC.Hypertension.SingleMeasurement"
+ "Escalation.HighBloodPressureNotifications.Description.ESC.HypertensiveEmergency"
+ "Escalation.HighBloodPressureNotifications.Description.ESC.HypertensiveEmergency.SingleMeasurement"
+ "Escalation.HighBloodPressureNotifications.Description.FIGO.MildlyElevated"
+ "Escalation.HighBloodPressureNotifications.Description.FIGO.MildlyElevated.SingleMeasurement"
+ "Escalation.HighBloodPressureNotifications.Description.FIGO.SeverelyElevated"
+ "Escalation.HighBloodPressureNotifications.Description.FIGO.SeverelyElevated.SingleMeasurement"
+ "Escalation.HypertensionNotifications.Description"
+ "Evaluated Thresholds (mL/kg/min)"
+ "Fallback Defaults"
+ "Guidance.DiscussWithYourDoctorIfUnexpected.Body"
+ "Guidance.DiscussWithYourDoctorIfUnexpected.Title"
+ "HYPERTENSION_NOTIFICATIONS_DETAILS_NEXT_STEPS_ABBREVIATED_SUBTITLE"
+ "Heart.BloodPressureJournalSevereHypertensionViewController"
+ "Heart.CardioFitnessReclassificationDismissalDateInputSignal"
+ "Heart/AFibBurdenAddDataView.swift"
+ "Heart/AFibBurdenChartSection.swift"
+ "Heart/AFibBurdenDataTypeDetailViewController.swift"
+ "Heart/AFibBurdenEducationSectionGenerator.swift"
+ "Heart/AFibBurdenGetStartedDataSource.swift"
+ "Heart/AFibBurdenHideableOnboardingDataSource.swift"
+ "Heart/AFibBurdenLifeFactorDetailViewController.swift"
+ "Heart/AFibBurdenLifeFactorsTileViewController.swift"
+ "Heart/AFibBurdenNotificationSettingsDisclosureCellViewController.swift"
+ "Heart/AFibBurdenOnboardingGetStartedViewController.swift"
+ "Heart/AFibBurdenOnboardingHowItWorksViewController.swift"
+ "Heart/AFibBurdenOnboardingLifeFactorsViewController.swift"
+ "Heart/AFibBurdenOnboardingModel.swift"
+ "Heart/AFibBurdenOnboardingResultsViewController.swift"
+ "Heart/AFibBurdenOnboardingSetupCompleteViewController.swift"
+ "Heart/AFibBurdenOnboardingShouldKnowViewController.swift"
+ "Heart/AFibBurdenOnboardingStartViewController.swift"
+ "Heart/AFibBurdenPDFComponent.swift"
+ "Heart/AFibBurdenPDFExportPPTTestRunner.swift"
+ "Heart/AFibBurdenPDFItem.swift"
+ "Heart/AFibBurdenRescindedTileViewController.swift"
+ "Heart/AFibFeaturesOnboardingViewController.swift"
+ "Heart/AFibFeaturesPromotionTileViewController.swift"
+ "Heart/AtrialFibrillationPromotionTileViewController.swift"
+ "Heart/BPCameraScannerFlowViewController.swift"
+ "Heart/BloodPressureClassificationDataManagementDataSource.swift"
+ "Heart/BloodPressureDataEntryLoggingView.swift"
+ "Heart/BloodPressureDataTypeDetailViewController.swift"
+ "Heart/BloodPressureJournalCreationBestPracticesViewController.swift"
+ "Heart/BloodPressureJournalExportPDFComponent.swift"
+ "Heart/BloodPressureJournalHideableDataSource.swift"
+ "Heart/BloodPressureJournalHighlightsDataSource.swift"
+ "Heart/BloodPressureJournalLoggingBestPracticesViewController.swift"
+ "Heart/BloodPressureJournalNotificationSettingsGeneratorPipeline.swift"
+ "Heart/BloodPressureJournalOnboardingBPCuffAccessViewController.swift"
+ "Heart/BloodPressureJournalOnboardingIntroViewController.swift"
+ "Heart/BloodPressureJournalOnboardingNeedWayToMeasureViewController.swift"
+ "Heart/BloodPressureJournalOnboardingViewControllerFactory.swift"
+ "Heart/BloodPressureJournalSetUpOrSummaryComponent.swift"
+ "Heart/BloodPressureJournalSettingsView.swift"
+ "Heart/BloodPressureJournalSevereHypertensionViewController.swift"
+ "Heart/BloodPressurePDFChart.swift"
+ "Heart/BloodPressurePDFHistoryTable.swift"
+ "Heart/BloodPressurePDFPregnancyChart.swift"
+ "Heart/CardioFitnessClassificationInternalSettingsView.swift"
+ "Heart/CardioFitnessDataTypeDetailDataSourceProvider.swift"
+ "Heart/CardioFitnessOnboardingAboutHealthDetailsViewController.swift"
+ "Heart/CardioFitnessOnboardingConfirmDetailsViewController.swift"
+ "Heart/CardioFitnessOnboardingFactorsViewController.swift"
+ "Heart/CardioFitnessOnboardingModel.swift"
+ "Heart/CardioFitnessOnboardingMostRecentValueProvider.swift"
+ "Heart/CardioFitnessOnboardingSetupCompleteSymbolView.swift"
+ "Heart/CardioFitnessOnboardingSetupCompleteViewController.swift"
+ "Heart/CardioFitnessOnboardingStartViewController.swift"
+ "Heart/CardioFitnessRetroComputeTipTileViewController.swift"
+ "Heart/CardioFitnessSpinnerComponent.swift"
+ "Heart/CenteredLabelWithSpinnerCell.swift"
+ "Heart/CompletedBloodPressureJournalTileContentConfigurationProvider.swift"
+ "Heart/ConfirmDetailsDataSource.swift"
+ "Heart/ConfirmDetailsModel.swift"
+ "Heart/ElectrocardiogramDataEntryLoggingView.swift"
+ "Heart/ElectrocardiogramFeatureStatusActionHandler.swift"
+ "Heart/ElectrocardiogramPromotionTileViewController.swift"
+ "Heart/ElectrocardiogramUpdateViewController.swift"
+ "Heart/HealthCalendarDayView.swift"
+ "Heart/HealthCalendarDaysOfWeekRow.swift"
+ "Heart/HealthCalendarView.swift"
+ "Heart/HeartAppDelegate+PPT.swift"
+ "Heart/HeartAppDelegate.swift"
+ "Heart/HeartFeatureStatusSupport.swift"
+ "Heart/HeartHealthPluginDelegate+EscalationViewProviding.swift"
+ "Heart/HeartRateStreamView.swift"
+ "Heart/HypertensionNotificationDetailView.swift"
+ "Heart/HypertensionNotificationSampleMetadataView.swift"
+ "Heart/HypertensionNotificationsCompleteViewController.swift"
+ "Heart/HypertensionNotificationsConfirmDetailsViewController.swift"
+ "Heart/HypertensionNotificationsDataTypeDetailDataSourceProvider.swift"
+ "Heart/HypertensionNotificationsHeartAttackWarning.swift"
+ "Heart/HypertensionNotificationsHowTheyWorkViewController.swift"
+ "Heart/HypertensionNotificationsHypertensionWarning.swift"
+ "Heart/HypertensionNotificationsOnboardingModel.swift"
+ "Heart/HypertensionNotificationsPregnancyWarning.swift"
+ "Heart/HypertensionNotificationsSampleListHideableDataSource.swift"
+ "Heart/HypertensionNotificationsSettingsCellViewController.swift"
+ "Heart/HypertensionNotificationsThingsToKnowViewController.swift"
+ "Heart/IRNInternalSettingsViewController.swift"
+ "Heart/IrregularRhythmNotificationsFeatureStatusActionHandler.swift"
+ "Heart/LearnHypertensionJournalSummaryView.swift"
+ "Heart/LocalizedImageView.swift"
+ "Heart/MonitorHypertensionJournalSummaryView.swift"
+ "Heart/SummariesAtrialFibrillationListDataProvider.swift"
+ "Heart/TemporaryHealthStorePPTTestRunner.swift"
+ "Injected For Testing"
+ "Legacy CoreMotion Table"
+ "Lower / Middle / Upper — the boundaries between Low, Below Average, Above Average, and High."
+ "No authored HighBloodPressureNotifications description for classification level %{public}s, falling back to the hypertension description"
+ "No classification data available."
+ "SevereHypertension"
+ "VO2MaxMigration Flag"
+ "View.task @ Heart/HeartHealthPluginDelegate+EscalationViewProviding.swift:"
+ "[%{public}s] Couldn't get date for reclassification tile dismissal, %s"
+ "[%{public}s] Dismissing cardio fitness reclassification tile"
+ "[%{public}s] Error observing life factor changes: %{public}s"
+ "[%{public}s] Failed to encode PromptTileViewModel for reclassification tile"
+ "[%{public}s] Failed to persist dismissal date: %{public}s"
+ "[%{public}s] No VO2 Max samples, removing feed items"
+ "[%{public}s] No feed item to submit"
+ "[%{public}s] Submitting reclassification feed item"
+ "[%{public}s] Tile dismissed, removing feed items"
+ "[%{public}s] VO2Max migration is not enabled, removing feed items"
+ "[%{public}s] didTapActionButton is not set and needs to be set to provide an action for the MessageWithSeparatedActionTileView link"
+ "] Unable to determine country code"
+ "_createCheckedContinuation(_:)"
+ "_createCheckedThrowingContinuation(_:)"
+ "cardio-fitness-reclassification-executor"
+ "com.apple.health.Heart.CardioFitnessReclassification"
+ "threshold = slope × age + intercept, evaluated at the age clamped to the domain and rounded to one decimal."
+ "💣 Could not create a DTDR for "
- "CardioFitnessOnboardingMostRecentValueProvider queue"
- "Heart.BloodPressureJournalHypertensiveCrisisViewController"
- "Heart/BloodPressureJournalHypertensiveCrisisViewController.swift"
- "HypertensiveCrisis"
- "[%{public}s] didTapActionButton is not set and needs to be set to provide an action for the MessageWithActionTileView link"
- "] FeatureSource found nil when committing enablement"
- "] Unable to determine country code with error: "
```
