## MenstrualCyclesAppPlugin

> `/System/Library/Health/FeedItemPlugins/MenstrualCyclesAppPlugin.healthplugin/MenstrualCyclesAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x551fd4` | `0x586e10` | **`+0x34e3c`** |
| `__TEXT.__cstring` | `0x180e6` | `0x1a688` | **`+0x25a2`** |
| `__TEXT.__eh_frame` | `0xd870` | `0xf4e4` | **`+0x1c74`** |
| `__AUTH_CONST.__auth_got` | `0x5670` | `0x5cf0` | **`+0x680`** |
| `__TEXT.__unwind_info` | `0xe638` | `0xec20` | **`+0x5e8`** |
| `__DATA.__bss` | `0x22178` | `0x21c68` | **`-0x510`** |
| `__AUTH_CONST.__const` | `0x1a0c0` | `0x19c38` | **`-0x488`** |
| `__TEXT.__swift5_typeref` | `0xb4b2` | `0xb0ce` | **`-0x3e4`** |
| `__TEXT.__const` | `0x269d4` | `0x266a4` | **`-0x330`** |
| `__TEXT.__oslogstring` | `0xcb3c` | `0xce6c` | **`+0x330`** |
| `__AUTH.__data` | `0xccc8` | `0xcfd8` | **`+0x310`** |
| `__AUTH_CONST.__objc_const` | `0x1b560` | `0x1b840` | **`+0x2e0`** |
| `__DATA.__data` | `0xb808` | `0xb580` | **`-0x288`** |
| `__TEXT.__swift5_reflstr` | `0x116d6` | `0x11912` | **`+0x23c`** |
| `__TEXT.__constg_swiftt` | `0x11d94` | `0x11b60` | **`-0x234`** |
| `__DATA_DIRTY.__data` | `0x7698` | `0x7468` | **`-0x230`** |
| `__DATA_CONST.__got` | `0x3190` | `0x3380` | **`+0x1f0`** |
| `__TEXT.__swift5_capture` | `0x5000` | `0x51d4` | **`+0x1d4`** |
| `__AUTH.__objc_data` | `0xef10` | `0xf070` | **`+0x160`** |
| `__TEXT.__swift_as_cont` | `0x8dc` | `0x9f8` | **`+0x11c`** |
| `__TEXT.__swift5_fieldmd` | `0xe424` | `0xe350` | **`-0xd4`** |
| `__TEXT.__swift_as_ret` | `0x41c` | `0x4b0` | **`+0x94`** |
| `__DATA_CONST.__objc_selrefs` | `0x3578` | `0x34f0` | **`-0x88`** |
| `__DATA_DIRTY.__bss` | `0x8a00` | `0x8980` | **`-0x80`** |
| `__TEXT.__swift_as_entry` | `0x330` | `0x3a8` | **`+0x78`** |
| `__DATA.__common` | `0xb40` | `0xbb0` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x58d4` | `0x5884` | **`-0x50`** |
| `__DATA_DIRTY.__common` | `0x498` | `0x450` | **`-0x48`** |
| `__TEXT.__swift5_builtin` | `0x460` | `0x424` | **`-0x3c`** |
| `__TEXT.__swift5_proto` | `0x183c` | `0x1808` | **`-0x34`** |
| `__TEXT.__swift5_types` | `0xed4` | `0xea4` | **`-0x30`** |
| `__DATA_CONST.__objc_classlist` | `0xc20` | `0xc40` | **`+0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x2ed8` | `0x2ef0` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x1e88` | `0x1e98` | **`+0x10`** |
| `__DATA.__objc_stublist` | `0xd8` | `0xd0` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x78` | `0x70` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x18c` | `0x184` | **`-0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/HealthContent.framework/HealthContent
+  - /System/Library/PrivateFrameworks/HealthContentUI.framework/HealthContentUI

+  - /System/Library/PrivateFrameworks/HealthDomainsUI.framework/HealthDomainsUI

+  - /System/Library/PrivateFrameworks/HealthReport.framework/HealthReport
+  - /System/Library/PrivateFrameworks/HealthReportCoreUI.framework/HealthReportCoreUI
+  - /System/Library/PrivateFrameworks/HealthReportPlatform.framework/HealthReportPlatform
+  - /System/Library/PrivateFrameworks/HealthReportUI.framework/HealthReportUI

+  - /System/Library/PrivateFrameworks/HealthTopics.framework/HealthTopics
+  - /System/Library/PrivateFrameworks/HealthTopicsCore.framework/HealthTopicsCore

+  - /System/Library/PrivateFrameworks/HealthUtilities.framework/HealthUtilities

+  - /System/Library/PrivateFrameworks/SleepHealth.framework/SleepHealth

-  Functions: 20484
-  Symbols:   767
-  CStrings:  2982
+  Functions: 20519
+  Symbols:   763
+  CStrings:  3135
Symbols:
+ _HKCategoryTypeIdentifierFromDeviationType
+ _HKMCIsKnownDeviationPerimenopauseContextState
+ _OBJC_CLASS_$_HKRegulatoryDomainManager
+ _OBJC_CLASS_$_HKSleepHealthStore
+ _OBJC_CLASS_$_UNNotificationSettings
+ _swift_release_x10
- _HKFeatureAvailabilityRequirementIdentifierCurrentCountryIsSupportedOnActiveRemoteDevice
- _HKFeatureAvailabilityRequirementIdentifierCurrentCountryIsSupportedOnLocalDevice
- _OBJC_CLASS_$_HKFeatureAvailabilityRequirementEvaluationDataSource
- _OBJC_CLASS_$_HKOnboardingCompletion
- _OBJC_CLASS_$_NSTimer
- _OBJC_CLASS_$_UIApplication
- _objc_retain_x3
- _objc_retain_x4
- _objc_setAssociatedObject
- _swift_continuation_resume
CStrings:
+ "%{public}s Did not save samples for action %s"
+ "CycleHistoryDataSource"
+ "CycleTrackingDashboardExecutorDeviationCount"
+ "CycleTrackingInsights"
+ "MenstrualCyclesAppPlugin/AddDeviationView.swift"
+ "MenstrualCyclesAppPlugin/AddMenopauseStageHelpTileContentConfigurationProvider.swift"
+ "MenstrualCyclesAppPlugin/AddOngoingCycleFactorsViewController.swift"
+ "MenstrualCyclesAppPlugin/AddPregnancyHelpTileContentConfigurationProvider.swift"
+ "MenstrualCyclesAppPlugin/AllPregnanciesDataSource.swift"
+ "MenstrualCyclesAppPlugin/AnalysisModel.swift"
+ "MenstrualCyclesAppPlugin/BodyTemperatureLine.swift"
+ "MenstrualCyclesAppPlugin/CycleChartDayCell.swift"
+ "MenstrualCyclesAppPlugin/CycleChartDayProvider.swift"
+ "MenstrualCyclesAppPlugin/CycleChartsCollectionView+AX.swift"
+ "MenstrualCyclesAppPlugin/CycleChartsCollectionViewDataSource.swift"
+ "MenstrualCyclesAppPlugin/CycleChartsCollectionViewLayout.swift"
+ "MenstrualCyclesAppPlugin/CycleChartsEditView.swift"
+ "MenstrualCyclesAppPlugin/CycleChartsEditViewModel.swift"
+ "MenstrualCyclesAppPlugin/CycleChartsSettings.swift"
+ "MenstrualCyclesAppPlugin/CycleDeviationsDataSource.swift"
+ "MenstrualCyclesAppPlugin/CycleFactorsDataSource.swift"
+ "MenstrualCyclesAppPlugin/CycleFactorsImpactNotificationFactory.swift"
+ "MenstrualCyclesAppPlugin/CycleHistoryDataSource.swift"
+ "MenstrualCyclesAppPlugin/CycleLogDataSource.swift"
+ "MenstrualCyclesAppPlugin/CycleLogModelProvider.swift"
+ "MenstrualCyclesAppPlugin/CycleLogNavigationHandling.swift"
+ "MenstrualCyclesAppPlugin/CycleStatisticsDataSource.swift"
+ "MenstrualCyclesAppPlugin/CycleTrackingFinishSetupDataSource.swift"
+ "MenstrualCyclesAppPlugin/DashboardVisibilityController.swift"
+ "MenstrualCyclesAppPlugin/DeviationCustomDetailViewController.swift"
+ "MenstrualCyclesAppPlugin/DeviationHistoryContentView.swift"
+ "MenstrualCyclesAppPlugin/DeviationMenopauseConfirmationViewController.swift"
+ "MenstrualCyclesAppPlugin/DeviationPerimenopauseEscalationInterstitialViewController.swift"
+ "MenstrualCyclesAppPlugin/DeviationsFactorsConfirmationViewController.swift"
+ "MenstrualCyclesAppPlugin/DeviationsFeatureStatusModel.swift"
+ "MenstrualCyclesAppPlugin/DeviationsHistoryViewModel.swift"
+ "MenstrualCyclesAppPlugin/DeviationsIntroViewController.swift"
+ "MenstrualCyclesAppPlugin/DeviationsReviewCollectionViewWrapper.swift"
+ "MenstrualCyclesAppPlugin/DeviationsUnconfirmedViewController.swift"
+ "MenstrualCyclesAppPlugin/EditPregnancyView.swift"
+ "MenstrualCyclesAppPlugin/FeatureSettingsModel.swift"
+ "MenstrualCyclesAppPlugin/FeatureStatusModel.swift"
+ "MenstrualCyclesAppPlugin/HistoricalAnalysisDataSource.swift"
+ "MenstrualCyclesAppPlugin/HistoricalAnalysisHeaderDataSource.swift"
+ "MenstrualCyclesAppPlugin/InteractiveTimelineDataSource.swift"
+ "MenstrualCyclesAppPlugin/LastMenstrualPeriodTileViewController.swift"
+ "MenstrualCyclesAppPlugin/LastMenstrualPeriodViewController.swift"
+ "MenstrualCyclesAppPlugin/LegendView.swift"
+ "MenstrualCyclesAppPlugin/ListCell.swift"
+ "MenstrualCyclesAppPlugin/LoggingCardScrollableContainerView.swift"
+ "MenstrualCyclesAppPlugin/ManualEntryItem.swift"
+ "MenstrualCyclesAppPlugin/MenopausalStateEditBodyView.swift"
+ "MenstrualCyclesAppPlugin/MenopausalStateEditCoordinator.swift"
+ "MenstrualCyclesAppPlugin/MenopausalStateEditViewController.swift"
+ "MenstrualCyclesAppPlugin/MenopauseAgeBodyView.swift"
+ "MenstrualCyclesAppPlugin/MenopauseAgeRangeBodyView.swift"
+ "MenstrualCyclesAppPlugin/MenopauseAgeRangeViewController.swift"
+ "MenstrualCyclesAppPlugin/MenopauseAgeViewController.swift"
+ "MenstrualCyclesAppPlugin/MenopauseCellContentConfiguration.swift"
+ "MenstrualCyclesAppPlugin/MenopauseConflictResolving.swift"
+ "MenstrualCyclesAppPlugin/MenopauseDateOfBirthBodyView.swift"
+ "MenstrualCyclesAppPlugin/MenopauseDateOfBirthViewController.swift"
+ "MenstrualCyclesAppPlugin/MenopauseDefinitionBodyView.swift"
+ "MenstrualCyclesAppPlugin/MenopauseDefinitionViewController.swift"
+ "MenstrualCyclesAppPlugin/MenopauseOffboardingConfirmationViewController.swift"
+ "MenstrualCyclesAppPlugin/MenopauseOnboardingConfirmationViewController.swift"
+ "MenstrualCyclesAppPlugin/MenopauseOnboardingCoordinator.swift"
+ "MenstrualCyclesAppPlugin/MenopauseSelectionBodyView.swift"
+ "MenstrualCyclesAppPlugin/MenopauseSelectionViewController.swift"
+ "MenstrualCyclesAppPlugin/MenopauseStagesDetailView.swift"
+ "MenstrualCyclesAppPlugin/MenopauseStagesSharedListDataSource.swift"
+ "MenstrualCyclesAppPlugin/MenopauseStartDateConfirmViewController.swift"
+ "MenstrualCyclesAppPlugin/MenopauseSymptomLoggingViewController.swift"
+ "MenstrualCyclesAppPlugin/MenopauseTransitionEducationViewController.swift"
+ "MenstrualCyclesAppPlugin/MenopauseYearPickerBodyView.swift"
+ "MenstrualCyclesAppPlugin/MenopauseYearPickerViewController.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCycleAndBodyTemperatureChartWithLegend.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCycleSections.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesAppDelegate+Routing.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesHealthPluginDelegate+EscalationViewProvider.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesHighlightsRoomDataSource.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesHighlightsSearchTileViewController.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesNotificationSettingsDisclosureCellViewController.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesOnboardingCoordinator.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesOnboardingDataSource.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesOnboardingItemCell.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesOnboardingLastPeriodViewController.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesOnboardingPeriodLengthViewController.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesOnboardingPickerViewController.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesOnboardingTypicalCycleViewController.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesOnboardingWelcomeViewController.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesPPT.swift"
+ "MenstrualCyclesAppPlugin/MenstrualCyclesRoomViewController+PPT.swift"
+ "MenstrualCyclesAppPlugin/MenstruationDataEntryLoggingView.swift"
+ "MenstrualCyclesAppPlugin/NotificationAuthorizationManager.swift"
+ "MenstrualCyclesAppPlugin/OnboardingCycleTimelineInfoView.swift"
+ "MenstrualCyclesAppPlugin/OnboardingDataTypeLoggingCell.swift"
+ "MenstrualCyclesAppPlugin/OnboardingUserInfo.swift"
+ "MenstrualCyclesAppPlugin/OptionsModel.swift"
+ "MenstrualCyclesAppPlugin/OptionsView.swift"
+ "MenstrualCyclesAppPlugin/OvulationConfirmationHelpTileContentConfigurationProvider.swift"
+ "MenstrualCyclesAppPlugin/PDFCycleChartView.swift"
+ "MenstrualCyclesAppPlugin/PhaseWindows.swift"
+ "MenstrualCyclesAppPlugin/PickerSelectLoggingCardViewController.swift"
+ "MenstrualCyclesAppPlugin/PregnancyOffboardingConfirmationViewController.swift"
+ "MenstrualCyclesAppPlugin/PregnancyOffboardingReviewMedicalIDViewController.swift"
+ "MenstrualCyclesAppPlugin/PregnancyOnboardedIntroductionViewController.swift"
+ "MenstrualCyclesAppPlugin/PregnancyOnboardingAddPastPregnancyViewController.swift"
+ "MenstrualCyclesAppPlugin/PregnancyOnboardingConfirmationViewController.swift"
+ "MenstrualCyclesAppPlugin/PregnancyOnboardingCoordinator.swift"
+ "MenstrualCyclesAppPlugin/PregnancyOnboardingCustomizeHealthViewController.swift"
+ "MenstrualCyclesAppPlugin/PregnancyOnboardingEstimationMethodSelectionViewController.swift"
+ "MenstrualCyclesAppPlugin/PregnancyOnboardingRecordDetailsViewController.swift"
+ "MenstrualCyclesAppPlugin/PregnancyOnboardingReviewMedicationsViewController.swift"
+ "MenstrualCyclesAppPlugin/PregnancyOnboardingReviewMentalHealthViewController.swift"
+ "MenstrualCyclesAppPlugin/PregnancyOnboardingSuggestedFeatureAdjustmentViewController.swift"
+ "MenstrualCyclesAppPlugin/PregnancySuggestedFeatureAdjustmentTile.swift"
+ "MenstrualCyclesAppPlugin/PregnancyTileView.swift"
+ "MenstrualCyclesAppPlugin/ProjectionHighlightTileViewController.swift"
+ "MenstrualCyclesAppPlugin/QuantityRow.swift"
+ "MenstrualCyclesAppPlugin/RoomDataSource.swift"
+ "MenstrualCyclesAppPlugin/RoundedShadowView.swift"
+ "MenstrualCyclesAppPlugin/ScheduleDeviationView.swift"
+ "MenstrualCyclesAppPlugin/SensorFeatureStatusModel.swift"
+ "MenstrualCyclesAppPlugin/SexualActivityDataEntryLoggingView.swift"
+ "MenstrualCyclesAppPlugin/SingleCycleViewDataSource.swift"
+ "MenstrualCyclesAppPlugin/SingleSelectLoggingCardViewController.swift"
+ "MenstrualCyclesAppPlugin/SleepingWristTemperatureDataTypeDetailDebugActionProvider.swift"
+ "MenstrualCyclesAppPlugin/SleepingWristTemperatureHelpTileViewController.swift"
+ "MenstrualCyclesAppPlugin/SummaryTileViewController.swift"
+ "MenstrualCyclesAppPlugin/SuppressibleRoomDataSource.swift"
+ "MenstrualCyclesAppPlugin/TextItemCell.swift"
+ "MenstrualCyclesAppPlugin/TimelineDayCell.swift"
+ "MenstrualCyclesAppPlugin/UIView.swift"
+ "MenstrualCyclesAppPlugin/VaginalBleedingAlertView.swift"
+ "MenstrualCyclesAppPlugin/ViewModelProviderLoadTest.swift"
+ "MenstrualCyclesProjectionHighlights"
+ "SHOW_IN_DASHBOARD_CELL_TITLE"
+ "Unsupported type: "
+ "[%s] Failed to fetch Medical ID: %s"
+ "[%{public}s] Caching dashboard model: %s"
+ "[%{public}s] Error fetching country code"
+ "[%{public}s] Failed to clear dashboard items: %@"
+ "[%{public}s] Failed to count confirmed deviations: %s; defaulting to 0"
+ "[%{public}s] Failed to create cycle tracking insights arbitration provider: %@"
+ "[%{public}s] Failed to fetch Medical ID: %s"
+ "[%{public}s] Failed to fetch menopause onboarding country code"
+ "[%{public}s] Failed to fetch most recent sample: %s"
+ "[%{public}s] Failed to reset key %s: %s"
+ "[%{public}s] Missing calendar-change anchor; skipping"
+ "[%{public}s] Missing cycle analysis anchor; skipping"
+ "[%{public}s] Missing menstrualCycles feature status anchor; skipping"
+ "[%{public}s] Missing pregnancy state anchor; skipping"
+ "[%{public}s] Pregnancy/menopause state did not load in time; presenting logging carousel anyway"
+ "[%{public}s] Pregnancy/menopause state not yet loaded; deferring logging carousel presentation until it updates"
+ "[%{public}s] Submitting %ld projection insight(s) for arbitration"
+ "[%{public}s]: Failed observing deviation samples: %s"
+ "[%{public}s]: Failed to fetch menopause onboarding country code"
+ "[ExportDayDataWaiter] Cycle PDF: day data not delivered within timeout; proceeding without full day data"
+ "[ExportDayDataWaiter] Cycle PDF: day data reported after %{public}.*fs, fullyFetched=%{bool,public}d"
+ "_createCheckedContinuation(_:)"
+ "_createCheckedThrowingContinuation(_:)"
+ "acknowledgeNotification(response:)"
+ "candidate isLongTerm "
+ "com.apple.health.MenstrualCycles"
+ "contentKindRawValue == %@"
+ "cycle-tracking-projection-insights"
+ "dashboard-cycle-tracking"
+ "deviationHistory"
+ "ensureTodayIsFetched()"
+ "handleHealthSharingNotification(response:)"
+ "init(_:layoutProvider:clipsToBounds:)"
+ "isMenopauseAvailableInCurrentRegion()"
+ "item realStartDate "
+ "openCycleFactors"
+ "openMenopauseOnboarding"
+ "projection item "
+ "queryConfirmedDeviationCount(dayIndex:currentCalendar:gregorianCalendar:)"
+ "samples detailsDescriptions "
+ "sendDismissNotificationInstruction(for:)"
+ "statistics"
+ "userNotificationCenter(_:didReceive:)"
- "HKObjectType_CycleTrackingCustom"
- "MenstrualCyclesAppPlugin.CycleFactorsLearnMoreHostingController"
- "PREGNANCY_DUE_DATE_COLON_%@"
- "PREGNANCY_SECTION_DUE_DATE_TEXT"
- "PREGNANCY_START_DATE_COLON_%@"
- "PregnancyModeTimelineSection"
- "PregnancyModeTimelineSection.Gauge"
- "PregnancyModeTimelineSection.GestationalAge"
- "PregnancyModeTimelineSection.LegendDueDate"
- "PregnancyModeTimelineSection.LegendStartDate"
- "PregnancyModeTimelineSection.Trimester"
- "PregnancySectionBackground"
- "PregnancySectionBackground-highlighted"
- "UNKNOWN_TRIMESTER"
- "[%{public}s] Cycle PDF: day data not delivered within timeout; proceeding without full day data"
- "[%{public}s] Cycle PDF: day data ready after %{public}.*fs"
- "[%{public}s] Cycle PDF: day-summary data delivered after %{public}.*fs"
- "[%{public}s] Cycle PDF: wrist-temperature data delivered after %{public}.*fs"
- "[%{public}s] Error fetching country code: %s"
- "[%{public}s] Failed to fetch menopause onboarding country code: %{public}s"
- "[%{public}s] Re-entry with no changes to save; skipping redundant commit and advancing."
- "[%{public}s] Unchanged terminal reached in a result-presenting flow; advancing without a result."
- "[%{public}s]: Failed to fetch menopause onboarding country code: %{public}s"
- "acknowledgeNotification(response:completionHandler:)"
- "awaitFirstDayData(activeRange:timeout:)"
- "handleHealthSharingNotification(response:completionHandler:)"
- "init(_:layoutProvider:)"
- "sendDismissNotificationInstruction(for:completionHandler:)"
- "userNotificationCenter(_:didReceive:withCompletionHandler:)"
```
