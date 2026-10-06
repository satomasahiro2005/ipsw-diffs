## HealthKit

> `/System/Library/Frameworks/HealthKit.framework/HealthKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x158b3c` | `0x15bc4c` | **`+0x3110`** |
| `__TEXT.__text` | `0x3f61dc` | `0x3f7cc8` | **`+0x1aec`** |
| `__AUTH_CONST.__cfstring` | `0x33540` | `0x33820` | **`+0x2e0`** |
| `__TEXT.__oslogstring` | `0xd683` | `0xd8b3` | **`+0x230`** |
| `__TEXT.__cstring` | `0x37b12` | `0x37c82` | **`+0x170`** |
| `__TEXT.__ustring` | `0x78` | `0x1d8` | **`+0x160`** |
| `__TEXT.__eh_frame` | `0x7a30` | `0x7ac8` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x133b8` | `0x13430` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0x53468` | `0x534d0` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x31744` | `0x31794` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x13d81` | `0x13dc9` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x3f24` | `0x3f58` | **`+0x34`** |
| `__DATA_CONST.__objc_selrefs` | `0x12020` | `0x12050` | **`+0x30`** |
| `__DATA.__data` | `0xfda0` | `0xfdb0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x348` | `0x354` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x2f7c` | `0x2f84` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1ac` | `0x1b0` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x1b4` | `0x1b8` | **`+0x4`** |

### Other Changes

```diff

-7027.0.64.0.0
+7027.0.67.2.1

-  Functions: 29622
-  Symbols:   35787
-  CStrings:  9160
+  Functions: 29654
+  Symbols:   35799
+  CStrings:  9191
Symbols:
+ -[HKFeatureStatusManager _dataSourceIfAvailable]
+ -[HKHealthStore _setCharacteristic:forDataType:date:error:]
+ -[HKHealthStoreImplementation _setCharacteristic:forDataType:date:error:]
+ -[HKSource _researchStudyIconData]
+ -[HKSource _setResearchStudyIconData:]
+ -[HKStatistics discrepancyDescriptionComparedTo:]
+ -[_HKFeatureFlags timeBoundedAuthorizationInLineButtons]
+ GCC_except_table253
+ GCC_except_table257
+ _HKQuantityDeltaDescription
+ _OBJC_IVAR_$_HKSource._researchStudyIconData
+ _OBJC_IVAR_$__HKFeatureFlags._timeBoundedAuthorizationInLineButtons
+ ___56-[_HKFeatureFlags timeBoundedAuthorizationInLineButtons]_block_invoke
+ ___73-[HKHealthStoreImplementation _setCharacteristic:forDataType:date:error:]_block_invoke
+ ___73-[HKHealthStoreImplementation _setCharacteristic:forDataType:date:error:]_block_invoke_2
- -[HKFeatureStatusManager _requirementSatisfactionOverrides]
- GCC_except_table254
- GCC_except_table93
CStrings:
+ "#### (180749116) 01. (HKLiveWorkoutBuilder *)associatedWorkoutBuilder"
+ "#### (180749116) 02. - (HKLiveWorkoutBuilder *)associatedWorkoutBuilderWithDevice:(nullable HKDevice *)device..."
+ "#### (180749116) 03. - (void)_setupTaskServerWithCompletion:(void (^)(BOOL success, NSError * _Nullable error))completion"
+ "#### (180749116) 15. - (void)clientRemote_didUpdateStatistics:(HKWorkoutBuilderStatistics *)builderStatistics"
+ "%@: %@→%@"
+ "%@: %g→%g %@ (Δ=%g, %.4f%%)"
+ "%@: date may not be nil in %@"
+ "<no differences>"
+ "Feature status data source is unavailable"
+ "TimeBoundedAuthorizationInLineButtons"
+ "VitalsDaySummaryDemoMode"
+ "[%{public}@] Data source unavailable; skipping feature status update"
+ "[%{public}@] Data source unavailable; skipping observation-driven update"
+ "avg"
+ "avgBySource differs"
+ "categoryValue: %@→%@"
+ "dataCount: %lu→%lu"
+ "dataCountBySource differs"
+ "dataType: %@→%@"
+ "durationBySource differs"
+ "earliestInterval: %@→%@"
+ "endDate: %@→%@"
+ "maxBySource differs"
+ "minBySource differs"
+ "mostRecentBySource differs"
+ "mostRecentInterval: %@→%@"
+ "other=nil"
+ "researchStudyIconData"
+ "sources differ"
+ "startDate: %@→%@"
+ "sumBySource differs"
```
