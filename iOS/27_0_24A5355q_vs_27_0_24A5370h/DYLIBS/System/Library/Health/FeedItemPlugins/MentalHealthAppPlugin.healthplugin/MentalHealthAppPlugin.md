## MentalHealthAppPlugin

> `/System/Library/Health/FeedItemPlugins/MentalHealthAppPlugin.healthplugin/MentalHealthAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb0010` | `0xb74fc` | **`+0x74ec`** |
| `__TEXT.__cstring` | `0x31af` | `0x3b4e` | **`+0x99f`** |
| `__TEXT.__eh_frame` | `0x1a1c` | `0x1d6c` | **`+0x350`** |
| `__AUTH_CONST.__const` | `0x3d20` | `0x3f00` | **`+0x1e0`** |
| `__TEXT.__unwind_info` | `0x23f8` | `0x2588` | **`+0x190`** |
| `__DATA_DIRTY.__data` | `0x10c8` | `0xfa8` | **`-0x120`** |
| `__TEXT.__swift5_capture` | `0x96c` | `0xa30` | **`+0xc4`** |
| `__TEXT.__swift5_typeref` | `0x2138` | `0x2178` | **`+0x40`** |
| `__TEXT.__const` | `0x5ec4` | `0x5ef4` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1558` | `0x1573` | **`+0x1b`** |
| `__AUTH_CONST.__auth_got` | `0x2788` | `0x27a0` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x90` | `0xa4` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x1520` | `0x1510` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1644` | `0x1650` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x160` | `0x16c` | **`+0xc`** |
| `__AUTH.__data` | `0x1468` | `0x1470` | **`+0x8`** |
| `__DATA.__data` | `0x2930` | `0x2928` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x94` | `0x9c` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x14fe` | `0x14fb` | **`-0x3`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Functions: 3246
+  Functions: 3313

-  CStrings:  370
+  CStrings:  406
Symbols:
+ _swift_getErrorValue
+ _swift_isEscapingClosureAtFileLocation
+ _swift_task_getMainExecutor
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
- _objc_retain_x3
- _objc_retain_x4
- _swift_continuation_throwingResume
- _swift_continuation_throwingResumeWithError
- _swift_retain_x1
CStrings:
+ "Incorrect actor executor assumption; Expected same executor as "
+ "MentalHealthAppPlugin/AnxietyRiskRoomViewController.swift"
+ "MentalHealthAppPlugin/ArticlesResourcesSection.swift"
+ "MentalHealthAppPlugin/AssessmentPDFExportSection.swift"
+ "MentalHealthAppPlugin/AssessmentQuestionFlow.swift"
+ "MentalHealthAppPlugin/AssessmentResultsArticlesSection.swift"
+ "MentalHealthAppPlugin/AssessmentResultsResourcesSection.swift"
+ "MentalHealthAppPlugin/AssessmentResultsView.swift"
+ "MentalHealthAppPlugin/AssessmentResultsViewController.swift"
+ "MentalHealthAppPlugin/AssessmentsOptionsDataSource.swift"
+ "MentalHealthAppPlugin/AssessmentsPDFExportDataSource.swift"
+ "MentalHealthAppPlugin/ContentConfigurationItem+MentalHealth.swift"
+ "MentalHealthAppPlugin/DataTypeDetailUpdatesComponent.swift"
+ "MentalHealthAppPlugin/DepressionRiskRoomViewController.swift"
+ "MentalHealthAppPlugin/LoggingPatternEscalationLearnMoreView.swift"
+ "MentalHealthAppPlugin/LoggingPatternEscalationLearnMoreViewController.swift"
+ "MentalHealthAppPlugin/MentalHealthAppDelegate+Routing.swift"
+ "MentalHealthAppPlugin/MentalHealthAssessmentsAgeEligibilityView.swift"
+ "MentalHealthAppPlugin/MentalHealthAssessmentsViewController.swift"
+ "MentalHealthAppPlugin/MentalHealthDaySummaryComponent.swift"
+ "MentalHealthAppPlugin/MentalHealthNotificationSettingsGeneratorPipeline.swift"
+ "MentalHealthAppPlugin/MentalHealthOptionsComponent.swift"
+ "MentalHealthAppPlugin/MentalHealthPPT.swift"
+ "MentalHealthAppPlugin/MentalHealthResourceAccessControls.swift"
+ "MentalHealthAppPlugin/MentalHealthResourceButton.swift"
+ "MentalHealthAppPlugin/MentalHealthResourceSMSButton.swift"
+ "MentalHealthAppPlugin/MentalHealthResourceView.swift"
+ "MentalHealthAppPlugin/NoCellularMentalHealthAccessControls.swift"
+ "MentalHealthAppPlugin/PinnedHeader.swift"
+ "MentalHealthAppPlugin/QuestionPlatterView.swift"
+ "MentalHealthAppPlugin/RiskClassificationView.swift"
+ "MentalHealthAppPlugin/StateOfMindLoggingPromotionActionHandler.swift"
+ "MentalHealthAppPlugin/StateOfMindRoomViewController+PPT.swift"
+ "MentalHealthAppPlugin/StateOfMindRoomViewController.swift"
+ "ScrollViewReader<<<opaque return type of onChange<A where A1: Equatable>(of: A1, initial: Bool, _: () -> ()) -> some>>.0>.ScrollView"
+ "_createCheckedThrowingContinuation(_:)"
```
