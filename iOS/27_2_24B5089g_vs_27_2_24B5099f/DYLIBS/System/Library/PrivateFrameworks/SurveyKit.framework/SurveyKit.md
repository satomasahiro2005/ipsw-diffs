## SurveyKit

> `/System/Library/PrivateFrameworks/SurveyKit.framework/SurveyKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfef34` | `0x105fbc` | **`+0x7088`** |
| `__TEXT.__oslogstring` | `0x125d` | `0x1775` | **`+0x518`** |
| `__DATA.__bss` | `0x1d410` | `0x1d890` | **`+0x480`** |
| `__TEXT.__const` | `0xffe2` | `0x1028c` | **`+0x2aa`** |
| `__TEXT.__eh_frame` | `0x9690` | `0x9920` | **`+0x290`** |
| `__TEXT.__cstring` | `0x3502` | `0x3762` | **`+0x260`** |
| `__TEXT.__unwind_info` | `0x4a00` | `0x4b08` | **`+0x108`** |
| `__AUTH.__data` | `0x2910` | `0x2990` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x92e8` | `0x9368` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x3834` | `0x3890` | **`+0x5c`** |
| `__DATA.__data` | `0x3278` | `0x32d0` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x22f7` | `0x2342` | **`+0x4b`** |
| `__TEXT.__swift5_reflstr` | `0x2331` | `0x2378` | **`+0x47`** |
| `__TEXT.__constg_swiftt` | `0x2f00` | `0x2f44` | **`+0x44`** |
| `__AUTH_CONST.__auth_got` | `0x11c8` | `0x11f8` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0xf18` | `0xf3c` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x398` | `0x388` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x590` | `0x5a0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x2b0` | `0x2bc` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x2fc` | `0x308` | **`+0xc`** |
| `__DATA_DIRTY.__data` | `0x368` | `0x360` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x534` | `0x53c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4c0` | `0x4c8` | **`+0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 6332
-  Symbols:   1518
-  CStrings:  424
+  Functions: 6412
+  Symbols:   1525
+  CStrings:  444
Symbols:
+ _HKSensitiveLogItem
+ _associated conformance 9SurveyKit0A15QuestionAnswersV6AnswerVSHAASQ
+ _symbolic B0
+ _symbolic SDy_____SayAAGG 17HealthOntologyKit0B17ConceptIdentifierV
+ _symbolic SS16surveyIdentifier_t
+ _symbolic Say_____G 9SurveyKit0A15QuestionAnswersV6AnswerV
+ _symbolic Si6offset______Sg6surveytIeAgHr_ 9SurveyKit0A0V
+ _symbolic _____ 9SurveyKit0A10ScoreIndexV
+ _symbolic _____ 9SurveyKit0A15QuestionAnswersV
+ _symbolic _____ 9SurveyKit0A15QuestionAnswersV6AnswerV
+ _type_layout_string 9SurveyKit0A10ScoreIndexV
+ _type_layout_string 9SurveyKit0A15QuestionAnswersV6AnswerV
- _OBJC_CLASS_$__HKBehavior
- _symbolic So11_HKBehaviorC
- _symbolic _____ 9SurveyKit0aB7FeatureV
- _symbolic _____SgIeAgHr_ 9SurveyKit0A16ConceptLocalizerV
- _type_layout_string 9SurveyKit0aB7FeatureV
CStrings:
+ "%{public}s error fetching proxy: %{public}@"
+ "%{public}s should only receive SurveyStoreServerInterface from `fetchProxy()`, but got %{public}s"
+ "Could not decode HKSurveyResponse.answerData, error: %{public}s"
+ "Failed to load surveys from %{private}s: %{public}s"
+ "Failed to submit %{private}s analytics event: %{public}@"
+ "HealthKitIntegrator:scoredAssessment"
+ "SurveyHealthFactsInputSignal:startObserving"
+ "Unable to fetch surveys to initialize anchor: %{public}s"
+ "[%{public}s.%{public}s] Could not write to url: %{public}@"
+ "[%{public}s.%{public}s] Failed to evaluate skipIfExpression with error: %{public}@"
+ "[%{public}s.%{public}s] Missing answer for question %{private}s. Returning nil."
+ "[%{public}s.%{public}s] choice %{public}s, attempting to use it for an answer suggestion"
+ "[%{public}s.%{public}s] did not find a fact for concept %{private}s"
+ "[%{public}s.%{public}s] fact value for concept %{private}s is not a quantity"
+ "[%{public}s.%{public}s] found unknown file %{public}s during extraction"
+ "[%{public}s.%{public}s] have fact for %{private}s but its concept value %{public}s doesn't match any possible answer"
+ "[%{public}s.%{public}s] have fact to suggest answer to %{public}s but don't know how to handle its concept value %{public}s"
+ "[%{public}s.%{public}s] have fact to suggest answer to %{public}s but don't know how to handle its quantity value %{public}s"
+ "[%{public}s.%{public}s] have fact to suggest answer to %{public}s but don't know how to handle unknown fact value type"
+ "[%{public}s.%{public}s] prefetching multiple choice answer suggestion for question concept %{private}s"
+ "[%{public}s.%{public}s] prefetching single choice answer suggestion for question concept %{private}s"
+ "[%{public}s.%{public}s] question concept ID does not have a corresponding data type, cannot suggest blood pressure answer"
+ "[%{public}s.%{public}s] question concept ID does not have a corresponding data type, cannot suggest boolean answer"
+ "[%{public}s.%{public}s] question concept ID does not have a corresponding data type, cannot suggest date answer"
+ "[%{public}s.%{public}s] question concept ID does not have a corresponding data type, cannot suggest multiple choice answers"
+ "[%{public}s.%{public}s] question concept ID does not have a corresponding data type, cannot suggest numeric answer"
+ "[%{public}s.%{public}s] question concept ID does not have a corresponding data type, cannot suggest single choice answers"
+ "[%{public}s.%{public}s] question concept ID does not have a corresponding read data type, cannot fetch answer"
+ "[%{public}s.%{public}s] unknown enum value, will not suggest an answer"
+ "[%{public}s.%{public}s] unsupported data type %{public}s"
+ "[%{public}s.%{public}s] will return multiple choice answer suggestion for question concept %{private}s"
+ "[%{public}s] Aborting observation, survey load failed: %{public}s"
+ "[%{public}s] Action is in progress for survey %{private}s"
+ "[%{public}s] Action is not started for survey %{private}s"
+ "[%{public}s] All questions skipped for survey %{private}s, action is complete"
+ "[%{public}s] Attempting to resume observation on server reconnection"
+ "[%{public}s] Complete answers in date interval for survey %{private}s, action is complete"
+ "[%{public}s] Could not fetch GAD7 assessment, error: %{public}@"
+ "[%{public}s] Could not fetch PHQ9 assessment, error: %{public}@"
+ "[%{public}s] Could not fetch answer for question %{private}s, error: %{public}@"
+ "[%{public}s] Determining action state for survey %{private}s %{public}s snapshot"
+ "[%{public}s] Failed to delete snapshot after saving answers, error: %{public}@"
+ "[%{public}s] Failed to fetch survey %{public}s: %{public}@"
+ "[%{public}s] Failed to initialize HKScoredAssessmentType for identifier: %{public}s"
+ "[%{public}s] Making snapshot for survey action %{private}s"
+ "[%{public}s] No registered observers, not restarting observation"
+ "[%{public}s] No survey offers question %{public}ld"
+ "[%{public}s] Observation beginning"
+ "[%{public}s] Observation ending"
+ "[%{public}s] Partial recent answers for survey %{private}s, action is in progress"
+ "[%{public}s] Question %{public}ld is not choice-shaped; it has no answers to lay out"
+ "[%{public}s] Response was added for %{private}s"
+ "[%{public}s] Snapshot was added for %{private}s"
+ "[%{public}s] Status was updated for a response associated with %{private}s, status: %{private}s"
+ "[%{public}s] Survey JSON not UTF-8 for %{public}s"
+ "[%{public}s] Unable to suggest date answer for %{private}s"
+ "[%{public}s] Unable to suggest multiple choice answer for %{private}s"
+ "[%{public}s] Unable to suggest numeric answer for %{private}s"
+ "[%{public}s] Unable to suggest single choice answer for %{private}s"
+ "[%{public}s]: Connection invalidated"
+ "[%{public}s]: Could not establish connection with SurveyStoreTaskServer, error: %{public}s"
+ "[%{public}s]: Deleted all survey data"
+ "[%{public}s]: Deleted all survey responses"
+ "[%{public}s]: Deleted all survey responses for %{private}s"
+ "[%{public}s]: Failed to decode SecureCodableSurveyResponseStatusModel, could not notify observers"
+ "[%{public}s]: Failed to decode SecureCodableSurveySnapshot, could not notify observers"
+ "[%{public}s]: Querying survey from test surveys in SwiftData container"
+ "[%{public}s]: Saved %{public}ld surveys"
+ "[%{public}s]: Saved survey response %{private}s for %{private}s"
+ "[%{public}s]: Successfully notified clients with clientRemote_responseWasAdded"
+ "[%{public}s]: Successfully notified clients with clientRemote_snapshotWasAdded"
+ "[%{public}s]: Successfully notified clients with clientRemote_statusDidChange"
+ "[%{public}s]: SurveyStore is nil, could not notify observers"
+ "[%{public}s]: serving %{private}s against medical history shard v%{public}lld, behind the manifest's advertised v%{public}lld"
+ "cannotAverageZeroScores("
+ "invalidAnswerChoice(question: "
+ "invalidAnswerFormat("
+ "invalidNumberOfAnswers"
+ "invalidOntologyID("
+ "invalidQuestionFormat("
+ "invalidScoreValue("
+ "missingAnswer(question: "
+ "missingQuestion("
+ "missingQuestionStep(question: "
+ "missingScore(question: "
+ "missingScoreValue("
+ "offset survey "
+ "survey.hasBalanceLevel"
+ "survey.hasRecentClassification"
+ "unsupportedAnswerFormatAndAnswerPair(question: "
- "%s error fetching proxy: %@"
- "%s should only receive SurveyStoreServerInterface from `fetchProxy()`, but got %s"
- "Could not decode HKSurveyResponse.answerData, error: %s"
- "Failed to load surveys from %s: %s"
- "Failed to submit %s analytics event: %@"
- "Unable to fetch surveys to initialize anchor: %s"
- "[%s.%s] Could not write to url: %@"
- "[%s.%s] Failed to evaluate skipIfExpression with error: %@"
- "[%s.%s] Missing answer for question %s. Returning nil."
- "[%s.%s] choice %ld, attempting to use it for an answer suggestion"
- "[%s.%s] did not find a fact for concept %s"
- "[%s.%s] fact value for concept %s is not a quantity"
- "[%s.%s] found unknown file %s during extraction"
- "[%s.%s] have fact %s to suggest answer to %s but don't know how to handle its concept value %s"
- "[%s.%s] have fact %s to suggest answer to %s but don't know how to handle its quantity value %@"
- "[%s.%s] have fact %s to suggest answer to %s but don't know how to handle unknown fact value type"
- "[%s.%s] have fact %s to suggest answer to %s but its concept value %s doesn't match any possible answer"
- "[%s.%s] prefetching multiple choice answer suggestion for question concept %s"
- "[%s.%s] prefetching single choice answer suggestion for question concept %s"
- "[%s.%s] question concept ID does not have a corresponding data type, cannot suggest blood pressure answer"
- "[%s.%s] question concept ID does not have a corresponding data type, cannot suggest boolean answer"
- "[%s.%s] question concept ID does not have a corresponding data type, cannot suggest date answer"
- "[%s.%s] question concept ID does not have a corresponding data type, cannot suggest multiple choice answers"
- "[%s.%s] question concept ID does not have a corresponding data type, cannot suggest numeric answer"
- "[%s.%s] question concept ID does not have a corresponding data type, cannot suggest single choice answers"
- "[%s.%s] question concept ID does not have a corresponding read data type, cannot fetch answer"
- "[%s.%s] unknown enum value, will not suggest an answer"
- "[%s.%s] unsupported data type %s"
- "[%s.%s] will return multiple choice answer suggestion for question concept %s"
- "[%s] Aborting observation, survey load failed: %s"
- "[%s] Action is in progress for survey %s"
- "[%s] Action is not started for survey %s"
- "[%s] All questions skipped for survey %s, action is complete"
- "[%s] Attempting to resume observation on server reconnection"
- "[%s] Complete answers in date interval for survey %s, action is complete"
- "[%s] Could not fetch GAD7 assessment, error: %@"
- "[%s] Could not fetch PHQ9 assessment, error: %@"
- "[%s] Could not fetch answer for question %s, error: %@"
- "[%s] Determining action state for survey %s %s snapshot"
- "[%s] Failed to delete snapshot after saving answers, error: %@"
- "[%s] Failed to fetch survey %s: %@"
- "[%s] Failed to initialize HKScoredAssessmentType for identifier: %s"
- "[%s] Making snapshot for survey action %s"
- "[%s] No registered observers, not restarting observation"
- "[%s] Observation beginning"
- "[%s] Observation ending"
- "[%s] Partial recent answers for survey %s, action is in progress"
- "[%s] Response was added for %s"
- "[%s] Snapshot was added for %s"
- "[%s] Status was updated for a response associated with %s, status: %s"
- "[%s] Survey JSON not UTF-8 for %s"
- "[%s] Unable to suggest date answer for %s"
- "[%s] Unable to suggest multiple choice answer for %s"
- "[%s] Unable to suggest numeric answer for %s"
- "[%s] Unable to suggest single choice answer for %s"
- "[%s]: Connection invalidated"
- "[%s]: Could not establish connection with SurveyStoreTaskServer, error: %s"
- "[%s]: Deleted all survey data"
- "[%s]: Deleted all survey responses"
- "[%s]: Deleted all survey responses for %s"
- "[%s]: Failed to decode SecureCodableSurveyResponseStatusModel, could not notify observers"
- "[%s]: Failed to decode SecureCodableSurveySnapshot, could not notify observers"
- "[%s]: Querying survey from test surveys in SwiftData container"
- "[%s]: Saved %ld surveys"
- "[%s]: Saved survey response: %s"
- "[%s]: Successfully notified clients with clientRemote_responseWasAdded"
- "[%s]: Successfully notified clients with clientRemote_snapshotWasAdded"
- "[%s]: Successfully notified clients with clientRemote_statusDidChange"
- "[%s]: SurveyStore is nil, could not notify observers"
- "[%s]: serving %s against medical history shard v%{public}lld, behind the manifest's advertised v%{public}lld"
```
