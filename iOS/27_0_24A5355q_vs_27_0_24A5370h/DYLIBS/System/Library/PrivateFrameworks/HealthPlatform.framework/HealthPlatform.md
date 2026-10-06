## HealthPlatform

> `/System/Library/PrivateFrameworks/HealthPlatform.framework/HealthPlatform`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x190ac8` | `0x1ad8b8` | **`+0x1cdf0`** |
| `__DATA.__bss` | `0xbb30` | `0xf440` | **`+0x3910`** |
| `__TEXT.__const` | `0xe2e0` | `0xff20` | **`+0x1c40`** |
| `__AUTH_CONST.__const` | `0xfd68` | `0x110e0` | **`+0x1378`** |
| `__TEXT.__eh_frame` | `0x5b94` | `0x661c` | **`+0xa88`** |
| `__TEXT.__unwind_info` | `0x6070` | `0x67f8` | **`+0x788`** |
| `__TEXT.__swift5_fieldmd` | `0x4374` | `0x499c` | **`+0x628`** |
| `__TEXT.__constg_swiftt` | `0x5258` | `0x5830` | **`+0x5d8`** |
| `__DATA.__data` | `0x2320` | `0x2880` | **`+0x560`** |
| `__AUTH.__data` | `0x1080` | `0x15d8` | **`+0x558`** |
| `__TEXT.__swift5_typeref` | `0x4d6a` | `0x517e` | **`+0x414`** |
| `__TEXT.__swift5_reflstr` | `0x3a37` | `0x3d27` | **`+0x2f0`** |
| `__TEXT.__oslogstring` | `0x5dfc` | `0x60dc` | **`+0x2e0`** |
| `__TEXT.__swift5_capture` | `0x2ec0` | `0x30d0` | **`+0x210`** |
| `__TEXT.__cstring` | `0x59e5` | `0x5be5` | **`+0x200`** |
| `__AUTH_CONST.__auth_got` | `0x1cd8` | `0x1ea8` | **`+0x1d0`** |
| `__TEXT.__swift5_proto` | `0xab0` | `0xc78` | **`+0x1c8`** |
| `__AUTH_CONST.__objc_const` | `0x5c08` | `0x5d18` | **`+0x110`** |
| `__DATA_CONST.__got` | `0xf80` | `0x1050` | **`+0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0xfd8` | `0x10a8` | **`+0xd0`** |
| `__TEXT.__swift5_types` | `0x570` | `0x618` | **`+0xa8`** |
| `__TEXT.__swift_as_cont` | `0x174` | `0x1d4` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xa28` | `0xa48` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0xd0` | `0xf0` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0xd0` | `0xf0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xb08` | `0xb24` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x9b8` | `0x9d0` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x5e08` | `0x5df8` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2e8` | `0x2f0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x100` | `0x104` | **`+0x4`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

+  - /System/Library/PrivateFrameworks/HealthBalance.framework/HealthBalance

+  - /System/Library/PrivateFrameworks/SleepHealth.framework/SleepHealth

-  Functions: 9571
-  Symbols:   2463
-  CStrings:  916
+  Functions: 10232
+  Symbols:   2600
+  CStrings:  935
Symbols:
+ _HKApproximateSecondsInADay
+ _HKQuantityTypeIdentifierVO2Max
+ _OBJC_CLASS_$_HKCardioFitnessClassificationUtilities
+ _OBJC_CLASS_$_HKQuantitySample
+ _OBJC_CLASS_$_HKQuery
+ _OBJC_CLASS_$__HKActivityStatisticsQuantityInfo
+ _OBJC_CLASS_$__HKActivityStatisticsStandHourInfo
+ __DATA__TtC14HealthPlatform37DynamicChannelDispatcherConfiguration
+ __IVARS__TtC14HealthPlatform37DynamicChannelDispatcherConfiguration
+ __METACLASS_DATA__TtC14HealthPlatform37DynamicChannelDispatcherConfiguration
+ _associated conformance 14HealthPlatform17ActivityChartDataV10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOSHAASQ
+ _associated conformance 14HealthPlatform17ActivityChartDataV10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform17ActivityChartDataV10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform17ActivityChartDataV10StandPointV10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOSHAASQ
+ _associated conformance 14HealthPlatform17ActivityChartDataV10StandPointV10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform17ActivityChartDataV10StandPointV10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform17ActivityChartDataV10StandPointV5StateO10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOSHAASQ
+ _associated conformance 14HealthPlatform17ActivityChartDataV10StandPointV5StateO10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform17ActivityChartDataV10StandPointV5StateO10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform17ActivityChartDataV10StandPointV5StateO14IdleCodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform17ActivityChartDataV10StandPointV5StateO14IdleCodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform17ActivityChartDataV10StandPointV5StateO15StoodCodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform17ActivityChartDataV10StandPointV5StateO15StoodCodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform17ActivityChartDataV10StandPointV5StateOSHAASQ
+ _associated conformance 14HealthPlatform17ActivityChartDataV10StandPointVSHAASQ
+ _associated conformance 14HealthPlatform17ActivityChartDataV13QuantityPointV10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOSHAASQ
+ _associated conformance 14HealthPlatform17ActivityChartDataV13QuantityPointV10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform17ActivityChartDataV13QuantityPointV10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform17ActivityChartDataV13QuantityPointVSHAASQ
+ _associated conformance 14HealthPlatform17ActivityChartDataVSHAASQ
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV10CodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOSHAASQ
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV10CodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV10CodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV5LevelO10CodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOSHAASQ
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV5LevelO10CodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV5LevelO10CodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV5LevelO13LowCodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV5LevelO13LowCodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV5LevelO14HighCodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV5LevelO14HighCodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV5LevelO22AboveAverageCodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV5LevelO22AboveAverageCodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV5LevelO22BelowAverageCodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV5LevelO22BelowAverageCodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotV5LevelOSHAASQ
+ _associated conformance 14HealthPlatform21CardioFitnessSnapshotVSHAASQ
+ _associated conformance 14HealthPlatform22ByThisTimeAccumulationV10CodingKeys33_9F4BEBECD64728EBABBF3B6A1146FA61LLOSHAASQ
+ _associated conformance 14HealthPlatform22ByThisTimeAccumulationV10CodingKeys33_9F4BEBECD64728EBABBF3B6A1146FA61LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform22ByThisTimeAccumulationV10CodingKeys33_9F4BEBECD64728EBABBF3B6A1146FA61LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform22ByThisTimeAccumulationVSHAASQ
+ _associated conformance 14HealthPlatform31TwentyEightDayAverageStatisticsO17AccumulationPointV10CodingKeys33_302036210278F5C4EB14E704D285D946LLOSHAASQ
+ _associated conformance 14HealthPlatform31TwentyEightDayAverageStatisticsO17AccumulationPointV10CodingKeys33_302036210278F5C4EB14E704D285D946LLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform31TwentyEightDayAverageStatisticsO17AccumulationPointV10CodingKeys33_302036210278F5C4EB14E704D285D946LLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform31TwentyEightDayAverageStatisticsO17AccumulationPointVSHAASQ
+ _associated conformance 14HealthPlatform31TwentyEightDayAverageStatisticsO18AccumulationSeriesV10CodingKeys33_302036210278F5C4EB14E704D285D946LLOSHAASQ
+ _associated conformance 14HealthPlatform31TwentyEightDayAverageStatisticsO18AccumulationSeriesV10CodingKeys33_302036210278F5C4EB14E704D285D946LLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform31TwentyEightDayAverageStatisticsO18AccumulationSeriesV10CodingKeys33_302036210278F5C4EB14E704D285D946LLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform31TwentyEightDayAverageStatisticsO18AccumulationSeriesVSHAASQ
+ _associated conformance 14HealthPlatform37DynamicChannelDispatcherConfigurationC0A13Orchestration0deF0AA0D10IdentifierAdEP_SH
+ _associated conformance 14HealthPlatform37DynamicChannelDispatcherConfigurationC0D10IdentifierOSHAASQ
+ _associated conformance 14HealthPlatform9DailyMeanV10CodingKeys33_1FEAE2BCD9548C03AD50A55DB8219B1DLLOSHAASQ
+ _associated conformance 14HealthPlatform9DailyMeanV10CodingKeys33_1FEAE2BCD9548C03AD50A55DB8219B1DLLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthPlatform9DailyMeanV10CodingKeys33_1FEAE2BCD9548C03AD50A55DB8219B1DLLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthPlatform9DailyMeanVSHAASQ
+ _keypath_get_selector_dashboardPageID
+ _keypath_get_selector_startDate
+ _swift_projectBox
+ _symbolic $s14HealthPlatform20TabPopToRootHandlingP
+ _symbolic $s19HealthOrchestration30ChannelDispatcherConfigurationP
+ _symbolic SS16executorProvider_t
+ _symbolic SaySaySdGG
+ _symbolic SaySaySdGGz_Xx
+ _symbolic SaySdG
+ _symbolic Say_____G 14HealthPlatform17ActivityChartDataV10StandPointV
+ _symbolic Say_____G 14HealthPlatform17ActivityChartDataV13QuantityPointV
+ _symbolic Say_____G 14HealthPlatform31TwentyEightDayAverageStatisticsO17AccumulationPointV
+ _symbolic Say_____Gz_Xx 14HealthPlatform31TwentyEightDayAverageStatisticsO17AccumulationPointV
+ _symbolic SdSg
+ _symbolic Sdz_Xx
+ _symbolic Shy_____G 10Foundation4DateV
+ _symbolic Shy_____Gz_Xx 10Foundation4DateV
+ _symbolic Siz_Xx
+ _symbolic SnySiG
+ _symbolic So16HKQuantitySampleC
+ _symbolic So6HKUnitC
+ _symbolic _____ 10Foundation12DateIntervalV
+ _symbolic _____ 10Foundation14DateComponentsV
+ _symbolic _____ 10Foundation8CalendarV
+ _symbolic _____ 14HealthPlatform17ActivityChartDataV
+ _symbolic _____ 14HealthPlatform17ActivityChartDataV10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLO
+ _symbolic _____ 14HealthPlatform17ActivityChartDataV10StandPointV
+ _symbolic _____ 14HealthPlatform17ActivityChartDataV10StandPointV10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLO
+ _symbolic _____ 14HealthPlatform17ActivityChartDataV10StandPointV5StateO
+ _symbolic _____ 14HealthPlatform17ActivityChartDataV10StandPointV5StateO10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLO
+ _symbolic _____ 14HealthPlatform17ActivityChartDataV10StandPointV5StateO14IdleCodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLO
+ _symbolic _____ 14HealthPlatform17ActivityChartDataV10StandPointV5StateO15StoodCodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLO
+ _symbolic _____ 14HealthPlatform17ActivityChartDataV13QuantityPointV
+ _symbolic _____ 14HealthPlatform17ActivityChartDataV13QuantityPointV10CodingKeys33_0A7588528B8DC6E681F339EBD81CF098LLO
+ _symbolic _____ 14HealthPlatform19DailyMeanStatisticsO
+ _symbolic _____ 14HealthPlatform19DailyMeanStatisticsO10CumulativeO
+ _symbolic _____ 14HealthPlatform19DailyMeanStatisticsO8DiscreteO
+ _symbolic _____ 14HealthPlatform19DailyMeanStatisticsO9ConstantsO
+ _symbolic _____ 14HealthPlatform21CardioFitnessSnapshotV
+ _symbolic _____ 14HealthPlatform21CardioFitnessSnapshotV10CodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLO
+ _symbolic _____ 14HealthPlatform21CardioFitnessSnapshotV5LevelO
+ _symbolic _____ 14HealthPlatform21CardioFitnessSnapshotV5LevelO10CodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLO
+ _symbolic _____ 14HealthPlatform21CardioFitnessSnapshotV5LevelO13LowCodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLO
+ _symbolic _____ 14HealthPlatform21CardioFitnessSnapshotV5LevelO14HighCodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLO
+ _symbolic _____ 14HealthPlatform21CardioFitnessSnapshotV5LevelO22AboveAverageCodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLO
+ _symbolic _____ 14HealthPlatform21CardioFitnessSnapshotV5LevelO22BelowAverageCodingKeys33_A3CA060BE9900F3D391FB7F801459F13LLO
+ _symbolic _____ 14HealthPlatform22ByThisTimeAccumulationV
+ _symbolic _____ 14HealthPlatform22ByThisTimeAccumulationV10CodingKeys33_9F4BEBECD64728EBABBF3B6A1146FA61LLO
+ _symbolic _____ 14HealthPlatform23ActivityChartStatisticsO
+ _symbolic _____ 14HealthPlatform23CardioFitnessStatisticsO
+ _symbolic _____ 14HealthPlatform25ActivitySummaryStatisticsO
+ _symbolic _____ 14HealthPlatform28DailyCumulativeSumStatisticsO
+ _symbolic _____ 14HealthPlatform31TwentyEightDayAverageStatisticsO
+ _symbolic _____ 14HealthPlatform31TwentyEightDayAverageStatisticsO17AccumulationPointV
+ _symbolic _____ 14HealthPlatform31TwentyEightDayAverageStatisticsO17AccumulationPointV10CodingKeys33_302036210278F5C4EB14E704D285D946LLO
+ _symbolic _____ 14HealthPlatform31TwentyEightDayAverageStatisticsO18AccumulationSeriesV
+ _symbolic _____ 14HealthPlatform31TwentyEightDayAverageStatisticsO18AccumulationSeriesV10CodingKeys33_302036210278F5C4EB14E704D285D946LLO
+ _symbolic _____ 14HealthPlatform31TwentyEightDayAverageStatisticsO18QueryConfigurationV
+ _symbolic _____ 14HealthPlatform31TwentyEightDayAverageStatisticsO25CurrentAccumulationResultV
+ _symbolic _____ 14HealthPlatform31TwentyEightDayAverageStatisticsO9ConstantsO
+ _symbolic _____ 14HealthPlatform32ByThisTimeAccumulationStatisticsO
+ _symbolic _____ 14HealthPlatform37DynamicChannelDispatcherConfigurationC
+ _symbolic _____ 14HealthPlatform37DynamicChannelDispatcherConfigurationC0D10IdentifierO
+ _symbolic _____ 14HealthPlatform9DailyMeanV
+ _symbolic _____ 14HealthPlatform9DailyMeanV10CodingKeys33_1FEAE2BCD9548C03AD50A55DB8219B1DLLO
+ _symbolic _____ 19HealthOrchestration25CalendarChangeInputSignalC6AnchorV
+ _symbolic _____ 19HealthOrchestration25CalendarChangeInputSignalC6AnchorV0A8PlatformE19GregorianResolutionV
+ _symbolic _____ 9HealthKit8DayIndexV
+ _symbolic _____Sg 10Foundation4DateV
+ _symbolic _____Sgz_Xx 10Foundation4DateV
+ _symbolic _____ySo6HKUnitCG 9HealthKit10CodableBoxV
+ _type_layout_string 14HealthPlatform17ActivityChartDataV
+ _type_layout_string 14HealthPlatform37DynamicChannelDispatcherConfigurationC0D10IdentifierO
+ _type_layout_string 14HealthPlatform9DailyMeanV
- _swift_retain_x11
CStrings:
+ "06032026_rdar://178691245_24A_"
+ "ActivitySummaryStatistics:"
+ "ActivitySummaryStatistics:["
+ "ByThisTimeAccumulationStatistics:"
+ "CardioFitnessStatistics:vo2Max"
+ "DailyCumulativeSumStatistics:"
+ "HealthPlatform/CalendarChangeInputSignal+HealthPlatform.swift"
+ "[%{public}s] adjusted statistic index: %{public}s"
+ "[%{public}s] approximateStatisticsInterval is not greater than zero, cannot compute average accumulation. intervalComponents: %{public}s"
+ "[%{public}s] invalid DST transition range for anchor date: %{public}s, DST transition: %{public}s, offset: %{public}s (delta: %{public}s) / interval: %{public}s -> computed range: %{public}s, available end index: %{public}s"
+ "[%{public}s] invalid statistic index for statistic date: %{public}s, offset: %{public}s / interval: %{public}s -> computed index: %{public}s"
+ "[%{public}s] unexpectedly computed a DST transition delta of 0 seconds for anchor date: %{public}s, DST transition: %{public}s, offset: %{public}s"
+ "] Can't determine a date from calendar change anchor: "
+ "activeEnergyPoints"
+ "appleMoveTimePoints"
+ "contentTile"
+ "contributingDayCount"
+ "exerciseTimePoints"
+ "historicalAverage"
+ "mostRecentSampleDate"
- "05182026_rdar://175955977_24A_"
```
