## HearingAppPlugin

> `/System/Library/Health/FeedItemPlugins/HearingAppPlugin.healthplugin/HearingAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81ffc` | `0xa3f3c` | **`+0x21f40`** |
| `__DATA.__bss` | `0x2e20` | `0x43e0` | **`+0x15c0`** |
| `__DATA_CONST.__got` | `0x0` | `0x12b0` | **`+0x12b0`** |
| `__TEXT.__const` | `0x4534` | `0x5664` | **`+0x1130`** |
| `__TEXT.__eh_frame` | `0xdd4` | `0x1a44` | **`+0xc70`** |
| `__AUTH_CONST.__objc_const` | `0x2400` | `0x2de0` | **`+0x9e0`** |
| `__AUTH_CONST.__const` | `0x26dc` | `0x308c` | **`+0x9b0`** |
| `__TEXT.__unwind_info` | `0x1990` | `0x21a8` | **`+0x818`** |
| `__DATA.__data` | `0x1498` | `0x1bd8` | **`+0x740`** |
| `__AUTH_CONST.__auth_got` | `0x1c68` | `0x2360` | **`+0x6f8`** |
| `__TEXT.__swift5_reflstr` | `0x13e9` | `0x1a59` | **`+0x670`** |
| `__AUTH.__objc_data` | `0x1190` | `0x1750` | **`+0x5c0`** |
| `__AUTH.__data` | `0x1618` | `0x1b78` | **`+0x560`** |
| `__TEXT.__swift5_fieldmd` | `0x125c` | `0x1780` | **`+0x524`** |
| `__TEXT.__swift5_typeref` | `0x1590` | `0x1ab4` | **`+0x524`** |
| `__TEXT.__cstring` | `0x2d25` | `0x3205` | **`+0x4e0`** |
| `__TEXT.__oslogstring` | `0x1741` | `0x1b01` | **`+0x3c0`** |
| `__TEXT.__constg_swiftt` | `0x221c` | `0x2574` | **`+0x358`** |
| `__TEXT.__swift5_capture` | `0x700` | `0xa44` | **`+0x344`** |
| `__TEXT.__swift5_assocty` | `0x290` | `0x3c0` | **`+0x130`** |
| `__TEXT.__swift5_proto` | `0x308` | `0x3b0` | **`+0xa8`** |
| `__TEXT.__objc_methlist` | `0x2e4` | `0x384` | **`+0xa0`** |
| `__TEXT.__swift_as_cont` | `0x58` | `0xd4` | **`+0x7c`** |
| `__DATA.__common` | `0x178` | `0x1e8` | **`+0x70`** |
| `__TEXT.__swift5_types` | `0x1a8` | `0x1f8` | **`+0x50`** |
| `__DATA_CONST.__objc_classlist` | `0xf8` | `0x138` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x5c` | `0x90` | **`+0x34`** |
| `__DATA_DIRTY.__data` | `0xf80` | `0xf50` | **`-0x30`** |
| `__TEXT.__swift_as_entry` | `0x50` | `0x80` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x8d0` | `0x8e8` | **`+0x18`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/HealthContent.framework/HealthContent
+  - /System/Library/PrivateFrameworks/HealthContentUI.framework/HealthContentUI

+  - /System/Library/PrivateFrameworks/HealthFacts.framework/HealthFacts

+  - /System/Library/PrivateFrameworks/HealthFoundationUI.framework/HealthFoundationUI

+  - /System/Library/PrivateFrameworks/HealthOntologyKit.framework/HealthOntologyKit

+  - /System/Library/PrivateFrameworks/HealthReport.framework/HealthReport
+  - /System/Library/PrivateFrameworks/HealthReportCoreUI.framework/HealthReportCoreUI
+  - /System/Library/PrivateFrameworks/HealthReportPlatform.framework/HealthReportPlatform
+  - /System/Library/PrivateFrameworks/HealthReportUI.framework/HealthReportUI

+  - /System/Library/PrivateFrameworks/HealthUtilities.framework/HealthUtilities

+  - /System/Library/PrivateFrameworks/SurveyKitUI.framework/SurveyKitUI

+  - /usr/lib/swift/libswiftObservation.dylib

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 2352
-  Symbols:   342
-  CStrings:  357
+  Functions: 2988
+  Symbols:   361
+  CStrings:  397
Symbols:
+ _OBJC_CLASS_$_OS_os_log
+ _OBJC_CLASS_$_UIAction
+ _UIApp
+ _objc_setAssociatedObject
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_getEnumCaseMultiPayload
+ _swift_projectBox
+ _swift_retain_x23
+ _swift_retain_x9
+ _swift_task_create
+ _swift_task_deinitOnExecutor
- _objc_retain_x2
CStrings:
+ "Edit Your Responses"
+ "HEARING_TEST_AUGMENTATION_SURVEY_DONE"
+ "HEARING_TEST_AUGMENTATION_SURVEY_NO"
+ "HEARING_TEST_AUGMENTATION_SURVEY_QUESTION_DETAIL"
+ "HEARING_TEST_AUGMENTATION_SURVEY_QUESTION_TITLE"
+ "HEARING_TEST_AUGMENTATION_SURVEY_SAVE_ERROR_ALERT_MESSAGE"
+ "HEARING_TEST_AUGMENTATION_SURVEY_SAVE_ERROR_ALERT_TITLE"
+ "HEARING_TEST_AUGMENTATION_SURVEY_YES"
+ "HEARING_TEST_REVIEW_HEARING_TEST"
+ "HEARING_TEST_REVIEW_START_NEW_EVALUATION"
+ "HEARING_TEST_REVIEW_TITLE"
+ "HEARING_TEST_VIDEO_NEXT"
+ "Hearing"
+ "Hearing Augmentation"
+ "HearingAppPlugin.HearingTestAugmentationSurveyCoordinator"
+ "HearingAppPlugin.HearingTestExperienceCoordinator"
+ "HearingAppPlugin.HearingTestFlowChildCoordinator"
+ "HearingAppPlugin.HearingTestResultsCoordinator"
+ "HearingAppPlugin.HearingTestVideoCoordinator"
+ "HearingAppPlugin/HearingTestAugmentationSurveyCoordinator.swift"
+ "HearingAppPlugin/HearingTestAugmentationSurveyView.swift"
+ "HearingAppPlugin/HearingTestExperienceCoordinator.swift"
+ "HearingAppPlugin/HearingTestFlowChildCoordinator.swift"
+ "HearingAppPlugin/HearingTestResultsCoordinator.swift"
+ "HearingAppPlugin/HearingTestResultsReviewView.swift"
+ "HearingAppPlugin/HearingTestVideoCoordinator.swift"
+ "Question Hearing Augmentation"
+ "Start New Assessment"
+ "View Results Modal"
+ "[%s] Cannot start survey-only flow without an audiogram"
+ "[%s] Could not find view controller for %s"
+ "[%s] Deleting prior augmentation survey fact %{public}s before saving answer"
+ "[%s] Error creating detail view controller: %@"
+ "[%s] Failed to check augmentation survey need: %{public}@"
+ "[%s] Failed to store augmentation survey answer: %{public}@"
+ "[%s] Successfully stored augmentation survey answer"
+ "[%{public}s] Failed to build snapshot for new evaluation"
+ "[%{public}s] Failed to fetch associated facts: %{public}@"
+ "[HearingTestResultsCoordinator] No hearing results; results screen will be empty."
+ "[HearingTestResultsReview] Deleting prior augmentation survey fact %{public}s before saving update"
+ "[HearingTestResultsReview] Failed to save updated augmentation survey answer: %{public}@"
+ "[HearingTestResultsReview] Successfully saved updated augmentation survey answer"
+ "_createCheckedThrowingContinuation(_:)"
+ "augmentationSurvey"
+ "hearingClassification"
- "HearingAppPlugin/AudiogramDataManagementComponent.swift"
- "HearingAppPlugin/AudiogramPDFComponent.swift"
- "HearingAppPlugin/AudiogramPDFItem.swift"
- "HearingAppPlugin/DataTypeDetailConfiguration+InlineChartComponent.swift"
- "HearingAppPlugin/NoiseNotificationsDataTypeDetailConfigurationProvider.swift"
```
