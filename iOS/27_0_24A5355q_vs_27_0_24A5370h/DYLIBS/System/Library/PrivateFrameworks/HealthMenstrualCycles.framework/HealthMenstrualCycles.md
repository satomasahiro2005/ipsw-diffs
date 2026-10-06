## HealthMenstrualCycles

> `/System/Library/PrivateFrameworks/HealthMenstrualCycles.framework/HealthMenstrualCycles`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x2685` | `0x2566` | **`-0x11f`** |
| `__TEXT.__text` | `0x2db54` | `0x2dc58` | **`+0x104`** |
| `__TEXT.__cstring` | `0x3ed6` | `0x3f56` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x373c` | `0x3794` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x6818` | `0x6858` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2100` | `0x2130` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x33a0` | `0x3380` | **`-0x20`** |
| `__DATA_CONST.__const` | `0xf88` | `0xf98` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x5a8` | `0x5b8` | **`+0x10`** |
| `__TEXT.__const` | `0x58e` | `0x59e` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xc98` | `0xca8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x388` | `0x390` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x47c` | `0x480` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x1c4` | `0x1c0` | **`-0x4`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

+  - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib

-  Functions: 1326
-  Symbols:   2564
-  CStrings:  610
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 1333
+  Symbols:   2581
+  CStrings:  603
Symbols:
+ +[HKCategorySample(HKMenstrualCycles) hkmc_perimenopauseCategorySampleWithStartDate:endDate:startDateSource:]
+ -[HKCategorySample(HKMenstrualCycles) hkmc_menopauseStartDateSource]
+ -[HKMCViewModelProvider _fertileWindowLevelWithDayIndex:cycleFactors:]
+ -[HKMCViewModelProvider _menstruationLevelWithDayIndex:menstrualFlow:cycleFactors:partiallyLoggedPeriod:]
+ -[HKMCViewModelProvider menopauseAvailableInCurrentRegion]
+ -[HKMCViewModelProvider setMenopauseAvailableInCurrentRegion:]
+ -[HKMenstrualCyclesStore previewDeviationAnalysisWithAddedCycleFactors:deletedCycleFactors:completion:]
+ _OBJC_IVAR_$_HKMCViewModelProvider._menopauseAvailableInCurrentRegion
+ __HKPrivateMetadataKeyMenopauseStartDateSource
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HKMCMenopauseModelProviding
+ ___103-[HKMenstrualCyclesStore previewDeviationAnalysisWithAddedCycleFactors:deletedCycleFactors:completion:]_block_invoke
+ ___103-[HKMenstrualCyclesStore previewDeviationAnalysisWithAddedCycleFactors:deletedCycleFactors:completion:]_block_invoke_2
+ ___105-[HKMCViewModelProvider _menstruationLevelWithDayIndex:menstrualFlow:cycleFactors:partiallyLoggedPeriod:]_block_invoke
+ ___70-[HKMCViewModelProvider _fertileWindowLevelWithDayIndex:cycleFactors:]_block_invoke
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftMetal_$_HealthMenstrualCycles
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftOSLog_$_HealthMenstrualCycles
+ __swift_FORCE_LOAD_$_swiftsimd
+ __swift_FORCE_LOAD_$_swiftsimd_$_HealthMenstrualCycles
+ _objc_retain_x9
- -[HKMCViewModelProvider _fertileWindowLevelWithDayIndex:]
- -[HKMCViewModelProvider _menstruationLevelWithDayIndex:menstrualFlow:partiallyLoggedPeriod:]
- ___57-[HKMCViewModelProvider _fertileWindowLevelWithDayIndex:]_block_invoke
- ___92-[HKMCViewModelProvider _menstruationLevelWithDayIndex:menstrualFlow:partiallyLoggedPeriod:]_block_invoke
CStrings:
+ "<%@:%p Model Query>"
+ "<%@:%p menstruationLevel:%@ fertileWindowLevel:%@ pregnancyState:%@ bleedingInPregnancyLevel:%@ bleedingAfterPregnancyLevel:%@ bleedingAfterMenopauseLevel:%@ supplementaryDataLogged summary:%@ cycleFactors:%lu partialPeriod:%@ fetched:%@>"
+ "[%{public}@] Supported menopause onboarding completion already present"
+ "menstruationLevel:%@|fertileWindowLevel:%@|supplementaryDataLogged:%@|pregnancyState:%@|bleedingInPregnancyLevel:%@|bleedingAfterPregnancyLevel:%@|bleedingAfterMenopauseLevel:%@"
- "<%@:%p Menopause Query>"
- "<%@:%p menstruationLevel:%@ fertileWindowLevel:%@ pregnancyState:%@ supplementaryDataLogged summary:%@ cycleFactors:%lu partialPeriod:%@ fetched:%@>"
- "[%{public}@:%p] Notifying new observer with current model"
- "[%{public}@:%p] Query already running"
- "[%{public}@:%p] Refreshing menopause model after %{public}@"
- "[%{public}@:%p] Registering observer: %{public}@"
- "[%{public}@:%p] Starting menopause query"
- "[%{public}@:%p] Unregistering observer: %{public}@"
- "[%{public}@] Menopause onboarding completion already present"
- "com.apple.private.health.menstrual-cycles"
- "menstruationLevel:%@|fertileWindowLevel:%@|supplementaryDataLogged:%@|pregnancyState:%@"
```
