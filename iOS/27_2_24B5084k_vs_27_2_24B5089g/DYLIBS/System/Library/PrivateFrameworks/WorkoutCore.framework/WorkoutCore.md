## WorkoutCore

> `/System/Library/PrivateFrameworks/WorkoutCore.framework/WorkoutCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63e6fc` | `0x63f694` | **`+0xf98`** |
| `__DATA.__bss` | `0x37240` | `0x36d40` | **`-0x500`** |
| `__DATA_DIRTY.__bss` | `0x6a50` | `0x6f50` | **`+0x500`** |
| `__TEXT.__unwind_info` | `0x15de8` | `0x16230` | **`+0x448`** |
| `__TEXT.__oslogstring` | `0x21979` | `0x21b59` | **`+0x1e0`** |
| `__DATA_DIRTY.__data` | `0x6258` | `0x62b8` | **`+0x60`** |
| `__DATA.__data` | `0xaf48` | `0xaef8` | **`-0x50`** |
| `__TEXT.__cstring` | `0x1004a` | `0x1006a` | **`+0x20`** |

### Other Changes

```diff

-2027.1.48.0.0
+2027.1.51.0.0

-  Functions: 39296
-  Symbols:   64860
-  CStrings:  3849
+  Functions: 39297
+  Symbols:   64862
+  CStrings:  3855
Symbols:
+ -[NLWorkout didFinishIntervalWorkout:date:completedStep:previousStepMetadata:]
+ GCC_except_table128
+ _$s11WorkoutCore19ReadinessWidgetKindO25extensionBundleIdentifierSSvgZ
+ _$s11WorkoutCore19ReadinessWidgetKindO25extensionBundleIdentifierSSvpZMV
+ _$s18AppIntentsServices0A20IntentPerformOptionsV19allowLiveActivities019allowsPrepareBeforeE024assistantDismissalPolicy21confirmationCondition26connectionOperationTimeout18donateToTranscript19executionIdentifier19exportedContentType15interactionMode4kind015preferredBundleY024preferNoticePresentation015processInstanceY021requestUnlockIfNeeded18snippetEnvironmentACSb_SbSo011LNAssistantnO0VSgSo029LNActionExecutionConfirmationQ0VSdSbSg10Foundation4UUIDVSg22UniformTypeIdentifiers6UTTypeVSgSo17LNInteractionModeVSo22LNTranscriptActionKindVSSSgSbA9_SbAA18SnippetEnvironmentVSgtcfC
+ _NLSessionActivityPauseEventSourceDescription
- -[NLWorkout didFinishIntervalWorkout:date:]
- GCC_except_table127
- _$s18AppIntentsServices0A20IntentPerformOptionsV19allowLiveActivities019allowsPrepareBeforeE024assistantDismissalPolicy21confirmationCondition26connectionOperationTimeout18donateToTranscript19executionIdentifier19exportedContentType15interactionMode4kind015preferredBundleY024preferNoticePresentation21requestUnlockIfNeeded18snippetEnvironmentACSb_SbSo011LNAssistantnO0VSgSo029LNActionExecutionConfirmationQ0VSdSbSg10Foundation4UUIDVSg22UniformTypeIdentifiers6UTTypeVSgSo17LNInteractionModeVSo22LNTranscriptActionKindVSSSgS2bAA18SnippetEnvironmentVSgtcfC
- __PauseEventSourceDescription
CStrings:
+ "[ReadinessService] computeReadinessModel AppliedSensingFitness returned no score after %.*fs"
+ "[ReadinessService] computeReadinessModel AppliedSensingFitness returned score=%.*f, classification=%s, elapsed=%.*fs"
+ "[ReadinessService] computeReadinessModel availability issues: %s"
+ "[ReadinessService] computeReadinessModel output error: %s"
+ "[ReadinessService] computeReadinessModel requesting score from AppliedSensingFitness for date: %s"
+ "com.apple.readiness.widgets"
```
