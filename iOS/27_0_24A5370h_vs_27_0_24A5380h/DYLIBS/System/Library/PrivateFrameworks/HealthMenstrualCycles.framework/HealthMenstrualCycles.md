## HealthMenstrualCycles

> `/System/Library/PrivateFrameworks/HealthMenstrualCycles.framework/HealthMenstrualCycles`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2dc58` | `0x2debc` | **`+0x264`** |
| `__TEXT.__cstring` | `0x3f56` | `0x3fe6` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x6858` | `0x68c0` | **`+0x68`** |
| `__AUTH_CONST.__cfstring` | `0x3380` | `0x33e0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x3794` | `0x37d4` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2130` | `0x2150` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x2566` | `0x2580` | **`+0x1a`** |
| `__DATA_CONST.__got` | `0x5b8` | `0x5d0` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xf98` | `0xfa8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x480` | `0x488` | **`+0x8`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 1333
-  Symbols:   2581
-  CStrings:  603
+  Functions: 1337
+  Symbols:   2589
+  CStrings:  606
Symbols:
+ -[HKMCAnalysisQuery initWithForceAnalysis:userInitiated:needsInitialResult:needsCycles:updateHandler:]
+ -[HKMCAnalysisQuery needsCycles]
+ -[HKMCAnalysisQueryConfiguration needsCycles]
+ -[HKMCAnalysisQueryConfiguration setNeedsCycles:]
+ -[HKMenstrualCyclesStore confirmAndSaveDeviationWithMenstrualFlowByDayIndex:intermenstrualBleedingByDayIndex:addedCycleFactors:deletedCycleFactors:initialAnalysisWindow:overridePerimenopauseContextState:overrideUserDeclinedMenopauseStage:completion:]
+ _HKMCAddMenopauseStageOnboardingEligibilityDateKey
+ _HKMCPrivateMetadataKeyConfirmedDeviationUserDeclinedMenopauseStageAtConfirmation
+ _OBJC_IVAR_$_HKMCAnalysisQuery._needsCycles
+ _OBJC_IVAR_$_HKMCAnalysisQueryConfiguration._needsCycles
+ ___250-[HKMenstrualCyclesStore confirmAndSaveDeviationWithMenstrualFlowByDayIndex:intermenstrualBleedingByDayIndex:addedCycleFactors:deletedCycleFactors:initialAnalysisWindow:overridePerimenopauseContextState:overrideUserDeclinedMenopauseStage:completion:]_block_invoke
+ ___250-[HKMenstrualCyclesStore confirmAndSaveDeviationWithMenstrualFlowByDayIndex:intermenstrualBleedingByDayIndex:addedCycleFactors:deletedCycleFactors:initialAnalysisWindow:overridePerimenopauseContextState:overrideUserDeclinedMenopauseStage:completion:]_block_invoke_2
+ ___block_descriptor_104_e8_32s40s48s56s64s72s80bs_e50_v16?0"<HDMenstrualCyclesPluginServerInterface>"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8
- -[HKMenstrualCyclesStore confirmAndSaveDeviationWithMenstrualFlowByDayIndex:intermenstrualBleedingByDayIndex:addedCycleFactors:deletedCycleFactors:initialAnalysisWindow:overridePerimenopauseContextState:completion:]
- ___215-[HKMenstrualCyclesStore confirmAndSaveDeviationWithMenstrualFlowByDayIndex:intermenstrualBleedingByDayIndex:addedCycleFactors:deletedCycleFactors:initialAnalysisWindow:overridePerimenopauseContextState:completion:]_block_invoke
- ___215-[HKMenstrualCyclesStore confirmAndSaveDeviationWithMenstrualFlowByDayIndex:intermenstrualBleedingByDayIndex:addedCycleFactors:deletedCycleFactors:initialAnalysisWindow:overridePerimenopauseContextState:completion:]_block_invoke_2
- ___block_descriptor_96_e8_32s40s48s56s64s72bs_e50_v16?0"<HDMenstrualCyclesPluginServerInterface>"8ls32l8s40l8s48l8s56l8s64l8s72l8
CStrings:
+ "HKMCAddMenopauseStageOnboardingEligibilityDate"
+ "NeedsCycles"
+ "[%{public}@:%{public}@] Configured with forced analysis: %{public}@, user initiated: %{public}@, needs initial result: %{public}@, needs cycles: %{public}@"
+ "_HKPrivateMetadataKeyHKMCConfirmedDeviationUserDeclinedMenopauseStageAtConfirmation"
- "[%{public}@:%{public}@] Configured with forced analysis: %{public}@, user initiated: %{public}@, needs initial result: %{public}@"
```
