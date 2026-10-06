## HealthMenstrualCyclesDaemon

> `/System/Library/PrivateFrameworks/HealthMenstrualCyclesDaemon.framework/HealthMenstrualCyclesDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x919ac` | `0x9203c` | **`+0x690`** |
| `__DATA.__bss` | `0x13e0` | `0x1260` | **`-0x180`** |
| `__DATA_DIRTY.__bss` | `0x1200` | `0x1380` | **`+0x180`** |
| `__DATA.__data` | `0x1968` | `0x18f8` | **`-0x70`** |
| `__DATA_DIRTY.__data` | `0xcc0` | `0xd20` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1050` | `0x10a0` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0xdec` | `0xe28` | **`+0x3c`** |
| `__AUTH_CONST.__objc_const` | `0x6a28` | `0x6a48` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e38` | `0x2e58` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1880` | `0x18a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x37d4` | `0x37ec` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x4b8` | `0x4bc` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 2419
-  Symbols:   2998
-  CStrings:  831
+  Functions: 2424
+  Symbols:   3006
+  CStrings:  832
Symbols:
+ +[HDMCRecentBasalBodyTemperatureRangeQuery recentRangeForAnalysisWithProfile:latestEndDate:]
+ -[HDMCAnalysisManager _analysisWithAlgorithmsAnalysis:algorithmsCycles:recentSymptoms:mostRecentBasalBodyTemperature:lastLoggedDayIndex:lastMenstrualFlowDayIndex:currentDayIndex:numberOfDailySleepHeartRateStatisticsForPast100Days:numberOfDailyAwakeHeartRateStatisticsForPast100Days:featureSettings:useHeartRateInput:useWristTemperatureInput:deviationsFeatureSettings:addedCycleFactors:deletedCycleFactors:forPreview:replayingEarlierDay:]
+ -[HDMCAnalysisManager _queue_computeAnalysisWithDatabaseAccessibilityAssertion:forceIncludeCycles:forceAnalyzeCompleteHistory:addedCycleFactors:deletedCycleFactors:mode:error:]
+ -[HDMCAnalysisManager analysisAsOfDayIndex:forceIncludeCycles:error:]
+ -[HDMCRecentBasalBodyTemperatureRangeQuery initWithProfile:sampleLimit:upperQuantileBound:lowerQuantileBound:latestEndDate:]
+ GCC_except_table14
+ GCC_except_table19
+ GCC_except_table22
+ GCC_except_table25
+ GCC_except_table39
+ GCC_except_table50
+ _OBJC_IVAR_$_HDMCRecentBasalBodyTemperatureRangeQuery._latestEndDate
+ ___176-[HDMCAnalysisManager _queue_computeAnalysisWithDatabaseAccessibilityAssertion:forceIncludeCycles:forceAnalyzeCompleteHistory:addedCycleFactors:deletedCycleFactors:mode:error:]_block_invoke
+ ___437-[HDMCAnalysisManager _analysisWithAlgorithmsAnalysis:algorithmsCycles:recentSymptoms:mostRecentBasalBodyTemperature:lastLoggedDayIndex:lastMenstrualFlowDayIndex:currentDayIndex:numberOfDailySleepHeartRateStatisticsForPast100Days:numberOfDailyAwakeHeartRateStatisticsForPast100Days:featureSettings:useHeartRateInput:useWristTemperatureInput:deviationsFeatureSettings:addedCycleFactors:deletedCycleFactors:forPreview:replayingEarlierDay:]_block_invoke
+ ___437-[HDMCAnalysisManager _analysisWithAlgorithmsAnalysis:algorithmsCycles:recentSymptoms:mostRecentBasalBodyTemperature:lastLoggedDayIndex:lastMenstrualFlowDayIndex:currentDayIndex:numberOfDailySleepHeartRateStatisticsForPast100Days:numberOfDailyAwakeHeartRateStatisticsForPast100Days:featureSettings:useHeartRateInput:useWristTemperatureInput:deviationsFeatureSettings:addedCycleFactors:deletedCycleFactors:forPreview:replayingEarlierDay:]_block_invoke_2
+ ___69-[HDMCAnalysisManager analysisAsOfDayIndex:forceIncludeCycles:error:]_block_invoke
+ ___69-[HDMCAnalysisManager analysisAsOfDayIndex:forceIncludeCycles:error:]_block_invoke_2
+ ___block_descriptor_174_e8_32s40s48s56s64s72s80r88r96r104r112r120r128r_e28_v24?0"HKMCDaySummary"8^B16lr80l8s32l8r88l8s40l8s48l8r96l8r104l8r112l8r120l8s56l8s64l8r128l8s72l8
+ ___block_descriptor_65_e8_32s40r48r_e5_v8?0ls32l8r40l8r48l8
+ ___block_descriptor_65_e8_32s40s48r_e9_B16?0^8lr48l8s32l8s40l8
- -[HDMCAnalysisManager _analysisWithAlgorithmsAnalysis:algorithmsCycles:recentSymptoms:mostRecentBasalBodyTemperature:lastLoggedDayIndex:lastMenstrualFlowDayIndex:currentDayIndex:numberOfDailySleepHeartRateStatisticsForPast100Days:numberOfDailyAwakeHeartRateStatisticsForPast100Days:featureSettings:useHeartRateInput:useWristTemperatureInput:deviationsFeatureSettings:addedCycleFactors:deletedCycleFactors:forPreview:]
- -[HDMCAnalysisManager _queue_computeAnalysisWithDatabaseAccessibilityAssertion:forceIncludeCycles:forceAnalyzeCompleteHistory:addedCycleFactors:deletedCycleFactors:forPreview:error:]
- GCC_except_table11
- GCC_except_table18
- GCC_except_table20
- GCC_except_table23
- GCC_except_table27
- GCC_except_table44
- ___182-[HDMCAnalysisManager _queue_computeAnalysisWithDatabaseAccessibilityAssertion:forceIncludeCycles:forceAnalyzeCompleteHistory:addedCycleFactors:deletedCycleFactors:forPreview:error:]_block_invoke
- ___417-[HDMCAnalysisManager _analysisWithAlgorithmsAnalysis:algorithmsCycles:recentSymptoms:mostRecentBasalBodyTemperature:lastLoggedDayIndex:lastMenstrualFlowDayIndex:currentDayIndex:numberOfDailySleepHeartRateStatisticsForPast100Days:numberOfDailyAwakeHeartRateStatisticsForPast100Days:featureSettings:useHeartRateInput:useWristTemperatureInput:deviationsFeatureSettings:addedCycleFactors:deletedCycleFactors:forPreview:]_block_invoke
- ___417-[HDMCAnalysisManager _analysisWithAlgorithmsAnalysis:algorithmsCycles:recentSymptoms:mostRecentBasalBodyTemperature:lastLoggedDayIndex:lastMenstrualFlowDayIndex:currentDayIndex:numberOfDailySleepHeartRateStatisticsForPast100Days:numberOfDailyAwakeHeartRateStatisticsForPast100Days:featureSettings:useHeartRateInput:useWristTemperatureInput:deviationsFeatureSettings:addedCycleFactors:deletedCycleFactors:forPreview:]_block_invoke_2
- ___block_descriptor_166_e8_32s40s48s56s64s72s80r88r96r104r112r120r128r_e28_v24?0"HKMCDaySummary"8^B16lr80l8s32l8r88l8s40l8s48l8r96l8r104l8r112l8r120l8s56l8s64l8r128l8s72l8
CStrings:
+ "A"
```
