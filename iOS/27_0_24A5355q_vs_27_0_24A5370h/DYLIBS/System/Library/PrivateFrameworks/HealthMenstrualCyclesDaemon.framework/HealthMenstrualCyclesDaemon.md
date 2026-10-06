## HealthMenstrualCyclesDaemon

> `/System/Library/PrivateFrameworks/HealthMenstrualCyclesDaemon.framework/HealthMenstrualCyclesDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8bd78` | `0x8d880` | **`+0x1b08`** |
| `__TEXT.__oslogstring` | `0x6a2c` | `0x6b0c` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0xfa8` | `0x1020` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x366c` | `0x36cc` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x2da0` | `0x2df8` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x17a8` | `0x17f8` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0xd94` | `0xde0` | **`+0x4c`** |
| `__AUTH_CONST.__cfstring` | `0x23c0` | `0x2400` | **`+0x40`** |
| `__TEXT.__cstring` | `0x38c1` | `0x38f1` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x68c0` | `0x68d0` | **`+0x10`** |
| `__DATA.__data` | `0x1748` | `0x1758` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x11b0` | `0x11b8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xd28` | `0xd30` | **`+0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Functions: 2334
-  Symbols:   2926
-  CStrings:  821
+  Functions: 2352
+  Symbols:   2948
+  CStrings:  827
Symbols:
+ +[HAMenstrualAlgorithmsDeviationInput(HKMenstrualCycles) hdmc_deviationInputWithProfile:enabledSetExplicitly:calendar:ignoreDeviationDismissalDayIndex:]
+ -[HDMCAnalysisManager _analysisWithAlgorithmsAnalysis:algorithmsCycles:recentSymptoms:mostRecentBasalBodyTemperature:lastLoggedDayIndex:lastMenstrualFlowDayIndex:currentDayIndex:numberOfDailySleepHeartRateStatisticsForPast100Days:numberOfDailyAwakeHeartRateStatisticsForPast100Days:featureSettings:useHeartRateInput:useWristTemperatureInput:deviationsFeatureSettings:addedCycleFactors:deletedCycleFactors:forPreview:]
+ -[HDMCAnalysisManager _processorConfigurationForTodayIndex:deviationsFeatureStatus:calendar:forPreview:]
+ -[HDMCAnalysisManager _queue_computeAnalysisWithDatabaseAccessibilityAssertion:forceIncludeCycles:forceAnalyzeCompleteHistory:addedCycleFactors:deletedCycleFactors:forPreview:error:]
+ -[HDMCAnalysisManager previewAnalysisWithAddedCycleFactors:deletedCycleFactors:error:]
+ -[HDMCPluginServer remote_previewDeviationAnalysisWithAddedCycleFactors:deletedCycleFactors:completion:]
+ GCC_except_table36
+ GCC_except_table44
+ GCC_except_table47
+ GCC_except_table71
+ GCC_except_table81
+ _HDMCAppendCycleFactorsPhaseFromSamples
+ _HDMCCycleFactorSampleDayIndexRange
+ _HDMCCycleFactorSampleShouldBeIncluded
+ _HDMCDaySummaryByFilteringDeletedCycleFactorPhases
+ _HDMCFilteredCycleFactorPhases
+ _HDMCRemoveCycleFactorsMatchingSamples
+ _OBJC_CLASS_$_HDMetadataManager
+ _OBJC_CLASS_$_HKMCMutableDaySummary
+ _OUTLINED_FUNCTION_12
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HKMCMenopauseModelProviding
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIdEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorIdNS_9allocatorIdEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIdNS_9allocatorIdEEE16__init_with_sizeB9fqe220106IPdS5_EEvT_T0_m
+ __ZNSt3__16vectorIdNS_9allocatorIdEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___104-[HDMCPluginServer remote_previewDeviationAnalysisWithAddedCycleFactors:deletedCycleFactors:completion:]_block_invoke
+ ___152+[HAMenstrualAlgorithmsDeviationInput(HKMenstrualCycles) hdmc_deviationInputWithProfile:enabledSetExplicitly:calendar:ignoreDeviationDismissalDayIndex:]_block_invoke
+ ___182-[HDMCAnalysisManager _queue_computeAnalysisWithDatabaseAccessibilityAssertion:forceIncludeCycles:forceAnalyzeCompleteHistory:addedCycleFactors:deletedCycleFactors:forPreview:error:]_block_invoke
+ ___417-[HDMCAnalysisManager _analysisWithAlgorithmsAnalysis:algorithmsCycles:recentSymptoms:mostRecentBasalBodyTemperature:lastLoggedDayIndex:lastMenstrualFlowDayIndex:currentDayIndex:numberOfDailySleepHeartRateStatisticsForPast100Days:numberOfDailyAwakeHeartRateStatisticsForPast100Days:featureSettings:useHeartRateInput:useWristTemperatureInput:deviationsFeatureSettings:addedCycleFactors:deletedCycleFactors:forPreview:]_block_invoke
+ ___417-[HDMCAnalysisManager _analysisWithAlgorithmsAnalysis:algorithmsCycles:recentSymptoms:mostRecentBasalBodyTemperature:lastLoggedDayIndex:lastMenstrualFlowDayIndex:currentDayIndex:numberOfDailySleepHeartRateStatisticsForPast100Days:numberOfDailyAwakeHeartRateStatisticsForPast100Days:featureSettings:useHeartRateInput:useWristTemperatureInput:deviationsFeatureSettings:addedCycleFactors:deletedCycleFactors:forPreview:]_block_invoke_2
+ ___86-[HDMCAnalysisManager previewAnalysisWithAddedCycleFactors:deletedCycleFactors:error:]_block_invoke
+ ___86-[HDMCAnalysisManager previewAnalysisWithAddedCycleFactors:deletedCycleFactors:error:]_block_invoke_2
+ ___HDMCRemoveCycleFactorsMatchingSamples_block_invoke
+ ___block_descriptor_163_e8_32s40s48s56s64s72s80r88r96r104r112r120r128r_e28_v24?0"HKMCDaySummary"8^B16ls32l8r80l8s40l8r88l8s48l8s56l8r96l8r104l8r112l8r120l8s64l8r128l8s72l8
+ ___block_descriptor_40_e8_32s_e33_B32?0"HKCategorySample"8Q16^B24ls32l8
+ ___block_descriptor_72_e8_32s40s48s56r64r_e5_v8?0ls32l8r56l8r64l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56s64r_e9_B16?0^8lr64l8s32l8s40l8s48l8s56l8
+ _objc_opt_respondsToSelector
- -[HDMCAnalysisManager _analysisWithAlgorithmsAnalysis:algorithmsCycles:recentSymptoms:mostRecentBasalBodyTemperature:lastLoggedDayIndex:lastMenstrualFlowDayIndex:currentDayIndex:numberOfDailySleepHeartRateStatisticsForPast100Days:numberOfDailyAwakeHeartRateStatisticsForPast100Days:featureSettings:useHeartRateInput:useWristTemperatureInput:deviationsFeatureSettings:]
- -[HDMCAnalysisManager _processorConfigurationForTodayIndex:deviationsFeatureStatus:calendar:]
- GCC_except_table41
- GCC_except_table43
- GCC_except_table68
- GCC_except_table78
- _OBJC_CLASS_$_NSNotificationCenter
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIdEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorIdNS_9allocatorIdEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIdNS_9allocatorIdEEE16__init_with_sizeB9fqe220100IPdS5_EEvT_T0_m
- __ZNSt3__16vectorIdNS_9allocatorIdEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- ___119+[HAMenstrualAlgorithmsDeviationInput(HKMenstrualCycles) hdmc_deviationInputWithProfile:enabledSetExplicitly:calendar:]_block_invoke
- ___133-[HDMCAnalysisManager _queue_computeAnalysisWithDatabaseAccessibilityAssertion:forceIncludeCycles:forceAnalyzeCompleteHistory:error:]_block_invoke
- ___368-[HDMCAnalysisManager _analysisWithAlgorithmsAnalysis:algorithmsCycles:recentSymptoms:mostRecentBasalBodyTemperature:lastLoggedDayIndex:lastMenstrualFlowDayIndex:currentDayIndex:numberOfDailySleepHeartRateStatisticsForPast100Days:numberOfDailyAwakeHeartRateStatisticsForPast100Days:featureSettings:useHeartRateInput:useWristTemperatureInput:deviationsFeatureSettings:]_block_invoke
- ___368-[HDMCAnalysisManager _analysisWithAlgorithmsAnalysis:algorithmsCycles:recentSymptoms:mostRecentBasalBodyTemperature:lastLoggedDayIndex:lastMenstrualFlowDayIndex:currentDayIndex:numberOfDailySleepHeartRateStatisticsForPast100Days:numberOfDailyAwakeHeartRateStatisticsForPast100Days:featureSettings:useHeartRateInput:useWristTemperatureInput:deviationsFeatureSettings:]_block_invoke_2
- ___block_descriptor_155_e8_32s40s48s56s64s72r80r88r96r104r112r120r_e28_v24?0"HKMCDaySummary"8^B16ls32l8r72l8s40l8r80l8s48l8s56l8r88l8r96l8r104l8r112l8r120l8s64l8
CStrings:
+ "B32@?0@\"HKCategorySample\"8Q16^B24"
+ "[%s] Cannot derive menopause model synchronously: profile not available"
+ "[%s] Synchronous menopause derivation failed: %@"
+ "[%{public}@] Did %@ analysis: %@"
+ "[%{public}@] Preview deviation analysis with %@ added and %@ deleted cycle factors"
+ "preview"
+ "update"
- "[%{public}@] Did update analysis: %@"
```
