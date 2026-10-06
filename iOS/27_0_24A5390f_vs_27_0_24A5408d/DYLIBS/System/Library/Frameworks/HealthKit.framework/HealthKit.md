## HealthKit

> `/System/Library/Frameworks/HealthKit.framework/HealthKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x15bc4c` | `0x16218c` | **`+0x6540`** |
| `__TEXT.__text` | `0x3f7cc8` | `0x3f8274` | **`+0x5ac`** |
| `__TEXT.__cstring` | `0x37c82` | `0x37d02` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x33820` | `0x33880` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x534d0` | `0x53528` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0xd8b3` | `0xd8f3` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x7ac8` | `0x7b00` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x31794` | `0x317c4` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x3f58` | `0x3f80` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x13430` | `0x13458` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x13dc9` | `0x13de9` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x12050` | `0x12070` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x4698` | `0x46b0` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x10468` | `0x10478` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1e18` | `0x1e08` | **`-0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x69d0` | `0x69e0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x5314` | `0x5320` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x2f84` | `0x2f88` | **`+0x4`** |

### Other Changes

```diff

-7027.0.67.2.1
+7027.0.72.2.5

-  Functions: 29654
-  Symbols:   35799
-  CStrings:  9191
+  Functions: 29661
+  Symbols:   35805
+  CStrings:  9195
Symbols:
+ -[HKMCPregnancyModel initWithState:pregnancyStartDate:pregnancyEndDate:estimatedDueDate:pregnancyDuration:physiologicalWashoutEndDate:behavioralWashoutEndDate:trimesters:sample:educationalStepsCompletedDate:staleOngoingPregnancySample:]
+ -[HKMCPregnancyModel staleOngoingPregnancySample]
+ GCC_except_table256
+ GCC_except_table260
+ _HKCategoryTypeIdentifierFitzpatrickSkinType
+ _OBJC_IVAR_$_HKMCPregnancyModel._staleOngoingPregnancySample
+ __HKDaemonPreferencesTCCReportUseThrottleDayOverrideKey
+ __OBJC_$_PROP_LIST__HKAuthorizationPresentationController
+ ___93-[HKHealthStoreImplementation clientRemote_presentAuthorizationWithRequestRecord:completion:]_block_invoke_3
+ ___93-[HKHealthStoreImplementation clientRemote_presentAuthorizationWithRequestRecord:completion:]_block_invoke_4
+ ___93-[HKHealthStoreImplementation clientRemote_presentAuthorizationWithRequestRecord:completion:]_block_invoke_5
- GCC_except_table192
- GCC_except_table244
- GCC_except_table257
- _NSLocaleMeasurementSystem
- _NSLocaleMeasurementSystemMetric
CStrings:
+ "<%@:%p state:%@ | startDate:%@ | endDate:%@ | estimatedDueDate:%@ | duration:%@ | physiologicalWashoutEndDate:%@ | behavioralWashoutEndDate:%@ | trimesters:%@ | educationalStepsCompletedDate:%@ | sample:%@ | staleOngoingPregnancySample:%@ "
+ "Failed to end authorization session after presentation failure: %{public}@"
+ "HKCategoryTypeIdentifierFitzpatrickSkinType"
+ "HKTCCReportUseThrottleDayOverride"
+ "StaleOngoingPregnancySample"
- "<%@:%p state:%@ | startDate:%@ | endDate:%@ | estimatedDueDate:%@ | duration:%@ | physiologicalWashoutEndDate:%@ | behavioralWashoutEndDate:%@ | trimesters:%@ | educationalStepsCompletedDate:%@ | sample:%@ "
```
