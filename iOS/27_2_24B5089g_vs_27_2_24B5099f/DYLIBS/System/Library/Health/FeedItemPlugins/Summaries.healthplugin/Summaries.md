## Summaries

> `/System/Library/Health/FeedItemPlugins/Summaries.healthplugin/Summaries`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x205ff8` | `0x200144` | **`-0x5eb4`** |
| `__DATA_DIRTY.__bss` | `0x6000` | `0x5680` | **`-0x980`** |
| `__DATA.__bss` | `0x9138` | `0x9828` | **`+0x6f0`** |
| `__DATA_DIRTY.__data` | `0x66a8` | `0x62d8` | **`-0x3d0`** |
| `__AUTH_CONST.__const` | `0x7078` | `0x6cb8` | **`-0x3c0`** |
| `__TEXT.__eh_frame` | `0xa7a4` | `0xab18` | **`+0x374`** |
| `__AUTH.__data` | `0x3088` | `0x3368` | **`+0x2e0`** |
| `__TEXT.__swift_as_cont` | `0xebc` | `0x1094` | **`+0x1d8`** |
| `__TEXT.__const` | `0xb614` | `0xb464` | **`-0x1b0`** |
| `__TEXT.__swift5_typeref` | `0x3f70` | `0x3de0` | **`-0x190`** |
| `__AUTH_CONST.__objc_const` | `0x3638` | `0x3780` | **`+0x148`** |
| `__TEXT.__cstring` | `0x67b9` | `0x68b9` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x305c` | `0x2f78` | **`-0xe4`** |
| `__TEXT.__swift5_reflstr` | `0x44ab` | `0x43cb` | **`-0xe0`** |
| `__TEXT.__oslogstring` | `0x57c1` | `0x5701` | **`-0xc0`** |
| `__AUTH_CONST.__auth_got` | `0x46d0` | `0x4648` | **`-0x88`** |
| `__TEXT.__constg_swiftt` | `0x49d8` | `0x4974` | **`-0x64`** |
| `__TEXT.__swift5_capture` | `0x123c` | `0x11d8` | **`-0x64`** |
| `__AUTH.__objc_data` | `0x8b8` | `0x908` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x56b8` | `0x5700` | **`+0x48`** |
| `__TEXT.__swift5_assocty` | `0x1188` | `0x1160` | **`-0x28`** |
| `__DATA.__common` | `0x230` | `0x250` | **`+0x20`** |
| `__DATA.__data` | `0x2978` | `0x2998` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1360` | `0x1340` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x874` | `0x860` | **`-0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x158` | `0x168` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x450` | `0x444` | **`-0xc`** |
| `__TEXT.__swift_as_ret` | `0x2f8` | `0x2fc` | **`+0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 6979
-  Symbols:   532
-  CStrings:  923
+  Functions: 6955
+  Symbols:   530
+  CStrings:  917
Symbols:
- _HKSampleSortIdentifierStartDate
- _OBJC_CLASS_$_HKSPSleepStore
CStrings:
+ "ActivitySummaryCurrentValueSharableModelStep:fetchActivitySummary"
+ "ChartSharableModelStep:fetchMostRecentSample"
+ "CorrelatedStatisticsCurrentValueSharableModelStep:fetchMostRecentUncorrelatedBloodPressureSample"
+ "MostRecentCumulativeTimePeriodCurrentValueSharableModelStep:fetchCumulativeTimePeriod"
+ "MostRecentSnippetSampleFetcher:fetchSamples:"
+ "OngoingFactorsMostRecentSampleCurrentValueSharableModelStep:makeCurrentValue"
+ "SampleCountMostRecentSampleCurrentValueSharableModelStep:makeCurrentValue"
+ "SleepDurationCurrentValueSharableModelStep:makeCurrentValue"
+ "StatisticsCurrentValueSharableModelStep:fetchLatestStatisticsCollection"
+ "StatisticsTrendSharableModelStep:fetchStatisticsCollection"
+ "Summaries/SummariesPromotionGeneratorPipeline.swift"
+ "TypicalDayActivityProgressFetcher:fetchFirstOnWristDateToday"
+ "dashboard-day-phase"
+ "registerDayPhaseProvider(context:)"
+ "summaries.derivedMeasureInputs"
- ".MultiValueLevelsDiagram"
- "DayPhaseProviderFetcher"
- "Failed to fetch cached activity dashboard model: %{public}s"
- "Failed to fetch cached sleep dashboard model: %{public}s"
- "Failed to fetch next scheduled occurrence: %{public}s"
- "Level End Height"
- "Level Start Height"
- "Level Start Width"
- "Summaries/BalanceSnidgetFeedItemProvider.swift"
- "Summaries/SnidgetMultiValueLevelChartView.swift"
- "VitalsSnidgetChartViewModel invariant failed"
- "VitalsSnidgetChartViewModel invariant failed, viewModel is of type "
- "arbitration-day-phase"
- "com.apple.HealthPlatform"
- "fetchCachedSleepModel(storage:)"
- "fetchCachedTypicalDayProgress(storage:)"
- "fetchSamples(of:limit:sortDescriptors:healthStore:)"
- "isMaximumInclusive"
- "isMinimumInclusive"
- "levelsAdjustedForValues"
- "multiValueLevelChartViewModel"
```
