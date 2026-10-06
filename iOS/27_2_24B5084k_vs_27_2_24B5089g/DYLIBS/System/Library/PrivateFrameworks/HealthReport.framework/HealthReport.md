## HealthReport

> `/System/Library/PrivateFrameworks/HealthReport.framework/HealthReport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x150d1c` | `0x159e80` | **`+0x9164`** |
| `__DATA.__bss` | `0x14368` | `0x14568` | **`+0x200`** |
| `__TEXT.__cstring` | `0x160a` | `0x145e` | **`-0x1ac`** |
| `__TEXT.__const` | `0xc0e6` | `0xc276` | **`+0x190`** |
| `__AUTH.__data` | `0x2898` | `0x2a18` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0x8b80` | `0x8c70` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0x18e3` | `0x19d3` | **`+0xf0`** |
| `__TEXT.__eh_frame` | `0x793c` | `0x7854` | **`-0xe8`** |
| `__TEXT.__swift5_fieldmd` | `0x2ab4` | `0x2b70` | **`+0xbc`** |
| `__AUTH_CONST.__auth_got` | `0x1f78` | `0x2018` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x2ea8` | `0x2f48` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x1568` | `0x15f8` | **`+0x90`** |
| `__DATA.__data` | `0x3838` | `0x38c8` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x20cb` | `0x214f` | **`+0x84`** |
| `__AUTH.__objc_data` | `0x340` | `0x398` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x42b8` | `0x4308` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x2ce8` | `0x2d1c` | **`+0x34`** |
| `__TEXT.__swift_as_cont` | `0x75c` | `0x73c` | **`-0x20`** |
| `__DATA.__common` | `0x40` | `0x58` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0xa98` | `0xab0` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x36c` | `0x380` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x218` | `0x208` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3f0` | `0x400` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xae0` | `0xaf0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x284` | `0x274` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xa8` | `0xb0` | **`+0x8`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 5705
-  Symbols:   1439
-  CStrings:  275
+  Functions: 5758
+  Symbols:   1447
+  CStrings:  265
Symbols:
+ __DATA__TtC12HealthReport29HealthFlowAnalyticsAppSession
+ __IVARS__TtC12HealthReport29HealthFlowAnalyticsAppSession
+ __METACLASS_DATA__TtC12HealthReport29HealthFlowAnalyticsAppSession
+ _associated conformance 12HealthReport0A17AgeResultCoverageO8DayStateOSHAASQ
+ _symbolic _____ 12HealthReport0A17AgeResultCoverageO
+ _symbolic _____ 12HealthReport0A17AgeResultCoverageO3RunV
+ _symbolic _____ 12HealthReport0A17AgeResultCoverageO8DayStateO
+ _symbolic _____ 12HealthReport0A23FlowAnalyticsAppSessionC
+ _symbolic _____ 12HealthReport0A26AssessmentEngagementRecordV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 10Foundation4UUIDV
- _HKSensitiveLogItem
- ___swift_project_boxed_opaque_existential_1Tm
CStrings:
+ "No date of birth on file; Mulberry unavailable."
+ "[HealthAgeQuery.%{public}s] CHR record has no extractable quantity"
+ "[HealthAgeQuery.%{public}s] Fetched %{private}ld samples (%{public}s)"
+ "[HealthAgeQuery.%{public}s] Yielding result: %{private}s (%{public}s)"
+ "[HealthAgeQuery.%{public}s] Yielding updated result: %{private}s (%{public}s)"
+ "[HealthAgeQuery.%{public}s] unrecognized sample type %{public}s"
+ "[HealthAgeQuery.HRV] Yielding result: %{private}s (%{public}s)"
+ "[HealthAgeQuery.SleepScore] Yielding critical-path result: %{private}s (%{public}s)"
+ "[HealthAgeQuery.SleepScore] Yielding result: %{private}s (%{public}s)"
+ "[HealthAgeQuery.VO2Max] Fetched %{private}ld samples (%{public}s)"
+ "[HealthAgeQuery.VO2Max] Yielding result: %{private}s (%{public}s)"
+ "[HealthAgeQuery] Coverage: %{public}s (%{public}s)"
+ "[HealthAgeQuery] Initial result calculated, has data: %{bool,public}d, duration: %{public}s (%{public}s)"
+ "[HealthAgeQuery] Query starting, days: %{public}s (%{public}s...%{public}s) (%{public}s)"
+ "[HealthAgeQuery] Result updated for %{public}s, has data: %{bool,public}d (%{public}s)"
+ "insufficient"
+ "sufficient"
- "[HealthAgeQuery.%{public}s] Fetched %{public}s samples (%{public}s)"
- "[HealthAgeQuery.%{public}s] Yielding result: %{public}s (%{public}s)"
- "[HealthAgeQuery.%{public}s] Yielding updated result: %{public}s (%{public}s)"
- "[HealthAgeQuery.HRV] Yielding result: %{public}s (%{public}s)"
- "[HealthAgeQuery.SleepScore] Yielding critical-path result: %{public}s (%{public}s)"
- "[HealthAgeQuery.SleepScore] Yielding result: %{public}s (%{public}s)"
- "[HealthAgeQuery.VO2Max] Fetched %{public}s samples (%{public}s)"
- "[HealthAgeQuery.VO2Max] Yielding result: %{public}s (%{public}s)"
- "[HealthAgeQuery] CHR record has no extractable quantity"
- "[HealthAgeQuery] Initial result calculated, %{public}s (%{public}s)"
- "[HealthAgeQuery] Query starting, days: %{public}s...%{public}s (%{public}s)"
- "[HealthAgeQuery] Result updated (%{public}s)"
- "[HealthAgeQuery] unrecognized sample type %{public}s"
- "assessmentsAvailable"
- "assessmentsCompleted"
- "assessmentsStarted"
- "categoriesAvailable"
- "categoriesCompleted"
- "categoriesStarted"
- "categoryCountsByLevel"
- "classificationsAvailable"
- "classificationsCompleted"
- "classificationsExpired"
- "dailyAnalyticsRunOnLaunch"
- "firstAssessmentStarted"
- "lastAssessmentCompleted"
- "lastAssessmentStarted"
```
