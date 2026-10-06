## PowerlogHelperdOperators

> `/System/Library/PrivateFrameworks/PowerlogHelperdOperators.framework/PowerlogHelperdOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d6d48` | `0x1d96a8` | **`+0x2960`** |
| `__AUTH_CONST.__objc_const` | `0x157a8` | `0x15ac8` | **`+0x320`** |
| `__TEXT.__objc_methlist` | `0x10738` | `0x10928` | **`+0x1f0`** |
| `__DATA_CONST.__objc_selrefs` | `0xab28` | `0xac90` | **`+0x168`** |
| `__AUTH_CONST.__cfstring` | `0x33480` | `0x335c0` | **`+0x140`** |
| `__TEXT.__cstring` | `0x26160` | `0x26211` | **`+0xb1`** |
| `__TEXT.__unwind_info` | `0x3aa0` | `0x3b30` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0x247c` | `0x24e8` | **`+0x6c`** |
| `__AUTH.__objc_data` | `0xaa0` | `0xaf0` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x1598` | `0x15cc` | **`+0x34`** |
| `__DATA_CONST.__const` | `0x4428` | `0x4448` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x14a6b` | `0x14a8b` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x2880` | `0x2898` | **`+0x18`** |
| `__DATA.__bss` | `0x20b0` | `0x2098` | **`-0x18`** |
| `__DATA_CONST.__got` | `0xf40` | `0xf50` | **`+0x10`** |
| `__TEXT.__const` | `0x6e0` | `0x6f0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xdf0` | `0xdf8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x380` | `0x388` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2c0` | `0x2c8` | **`+0x8`** |

### Other Changes

```diff

-3486.0.46.502.1
+3486.0.81.502.4

-  Functions: 8520
-  Symbols:   11569
-  CStrings:  8908
+  Functions: 8565
+  Symbols:   11637
+  CStrings:  8920
Symbols:
+ +[PLBatteryAgent entryEventBackwardDefinitionRebalance]
+ +[PLBatteryAgent fusePackCurrentAccumulators:fusedAccumulator:fusedCount:]
+ +[PLUrsaUtilities compareBuildVersion:withBuildVersion:]
+ -[PLAppTimeService addForegroundTimeAtDate:withNewLayoutElementsArray:forScreenContext:]
+ -[PLAppTimeService flushForegroundTimeAtDate:]
+ -[PLAppTimeService globalDisplayState]
+ -[PLAppTimeService handleDisplayCallback:forScreenContext:]
+ -[PLAppTimeService handleScreenStateCallback:forScreenContext:]
+ -[PLAppTimeService recomputeGlobalUnionSets]
+ -[PLAppTimeService screenActiveOrAOD]
+ -[PLAppTimeService screenActive]
+ -[PLAppTimeService screenContexts]
+ -[PLAppTimeService setGlobalDisplayState:]
+ -[PLAppTimeService setScreenContexts:]
+ -[PLBatteryAgent logEventBackwardChargerDataWithRawData:]
+ -[PLBatteryAgent prevRebalanceErrorFlags]
+ -[PLBatteryAgent prevRebalanceNotRebalancingReason]
+ -[PLBatteryAgent setPrevRebalanceErrorFlags:]
+ -[PLBatteryAgent setPrevRebalanceNotRebalancingReason:]
+ -[PLContextualizedMetricData addGlitchWithDuration:scrollDuration:glitchCount:isScrollStart:]
+ -[PLContextualizedMetricData setAnimationHitchTotalAnimationDuration:weightedGlitchRatioSum:]
+ -[PLDisplayAgent modelDisplayPowerFromIOMFB:withRootNodeID:]
+ -[PLDisplayAgent modelDynamicDisplayPowerFromAPL:withRootNodeID:]
+ -[PLPowerMetricMonitorService _primeSystemAgents]
+ -[PLPowerMetricMonitorService _runFullSetup]
+ -[PLPowerMetricMonitorService fullSetupCompleted]
+ -[PLPowerMetricMonitorService isSetUp]
+ -[PLPowerMetricMonitorService setFullSetupCompleted:]
+ -[PLPowerMetricMonitorService setUpForMonitoringWithLiteMode:]
+ -[PLPowerMetricMonitorService upgradeToFullSetup]
+ -[PLProcessNetworkAgent setTransaction:]
+ -[PLProcessNetworkAgent transaction]
+ -[PLScreenAccountingContext .cxx_destruct]
+ -[PLScreenAccountingContext contextAppsOnScreen]
+ -[PLScreenAccountingContext contextPiPModeApps]
+ -[PLScreenAccountingContext displayEntryKey]
+ -[PLScreenAccountingContext displayState]
+ -[PLScreenAccountingContext initWithScreenIndex:screenStateEntryKey:displayEntryKey:storage:]
+ -[PLScreenAccountingContext lastLayoutEntries]
+ -[PLScreenAccountingContext lastScreenOnTime]
+ -[PLScreenAccountingContext screenIndex]
+ -[PLScreenAccountingContext screenStateEntryKey]
+ -[PLScreenAccountingContext setContextAppsOnScreen:]
+ -[PLScreenAccountingContext setContextPiPModeApps:]
+ -[PLScreenAccountingContext setDisplayState:]
+ -[PLScreenAccountingContext setLastLayoutEntries:]
+ -[PLScreenAccountingContext setLastScreenOnTime:]
+ -[PLStreamingMetricAggregator _bufferAnimationInterval:forBucketKey:]
+ -[PLStreamingMetricAggregator _processBatchForBucketKey:]
+ -[PLStreamingMetricAggregator addAnimationHitchWithBundleID:interval:]
+ -[PLStreamingMetricAggregator addGlitchWithBundleID:timestamp:glitchDurationMs:scrollDurationMs:glitchCount:isScrollStart:]
+ -[PLStreamingMetricAggregator pendingAnimationIntervalsByBucket]
+ -[PLStreamingMetricAggregator processedTotalDurationByBucket]
+ -[PLStreamingMetricAggregator processedWeightedRatioSumByBucket]
+ -[PLStreamingMetricAggregator setPendingAnimationIntervalsByBucket:]
+ -[PLStreamingMetricAggregator setProcessedTotalDurationByBucket:]
+ -[PLStreamingMetricAggregator setProcessedWeightedRatioSumByBucket:]
+ GCC_except_table135
+ GCC_except_table139
+ GCC_except_table141
+ GCC_except_table153
+ GCC_except_table167
+ GCC_except_table172
+ GCC_except_table192
+ GCC_except_table218
+ GCC_except_table220
+ GCC_except_table261
+ GCC_except_table269
+ GCC_except_table270
+ GCC_except_table276
+ GCC_except_table277
+ GCC_except_table281
+ GCC_except_table323
+ GCC_except_table326
+ GCC_except_table330
+ GCC_except_table85
+ GCC_except_table88
+ GCC_except_table91
+ _OBJC_CLASS_$_PLScreenAccountingContext
+ _OBJC_CLASS_$_SignpostAnimationInterval
+ _OBJC_IVAR_$_PLAppTimeService._globalDisplayState
+ _OBJC_IVAR_$_PLAppTimeService._screenContexts
+ _OBJC_IVAR_$_PLBatteryAgent._prevRebalanceErrorFlags
+ _OBJC_IVAR_$_PLBatteryAgent._prevRebalanceNotRebalancingReason
+ _OBJC_IVAR_$_PLPowerMetricMonitorService._fullSetupCompleted
+ _OBJC_IVAR_$_PLProcessNetworkAgent._transaction
+ _OBJC_IVAR_$_PLScreenAccountingContext._contextAppsOnScreen
+ _OBJC_IVAR_$_PLScreenAccountingContext._contextPiPModeApps
+ _OBJC_IVAR_$_PLScreenAccountingContext._displayEntryKey
+ _OBJC_IVAR_$_PLScreenAccountingContext._displayState
+ _OBJC_IVAR_$_PLScreenAccountingContext._lastLayoutEntries
+ _OBJC_IVAR_$_PLScreenAccountingContext._lastScreenOnTime
+ _OBJC_IVAR_$_PLScreenAccountingContext._screenIndex
+ _OBJC_IVAR_$_PLScreenAccountingContext._screenStateEntryKey
+ _OBJC_IVAR_$_PLStreamingMetricAggregator._pendingAnimationIntervalsByBucket
+ _OBJC_IVAR_$_PLStreamingMetricAggregator._processedTotalDurationByBucket
+ _OBJC_IVAR_$_PLStreamingMetricAggregator._processedWeightedRatioSumByBucket
+ _OBJC_METACLASS_$_PLScreenAccountingContext
+ __OBJC_$_INSTANCE_METHODS_PLScreenAccountingContext
+ __OBJC_$_INSTANCE_VARIABLES_PLScreenAccountingContext
+ __OBJC_$_PROP_LIST_PLScreenAccountingContext
+ __OBJC_CLASS_RO_$_PLScreenAccountingContext
+ __OBJC_METACLASS_RO_$_PLScreenAccountingContext
+ ___123-[PLStreamingMetricAggregator addGlitchWithBundleID:timestamp:glitchDurationMs:scrollDurationMs:glitchCount:isScrollStart:]_block_invoke
+ ___123-[PLStreamingMetricAggregator addGlitchWithBundleID:timestamp:glitchDurationMs:scrollDurationMs:glitchCount:isScrollStart:]_block_invoke_2
+ ___38-[PLPowerMetricMonitorService isSetUp]_block_invoke
+ ___44-[PLPowerMetricMonitorService _runFullSetup]_block_invoke
+ ___46-[PLStreamingMetricAggregator finalizeResults]_block_invoke
+ ___49-[PLPowerMetricMonitorService upgradeToFullSetup]_block_invoke
+ ___49-[PLPowerMetricMonitorService upgradeToFullSetup]_block_invoke_2
+ ___59-[PLAppTimeService handleDisplayCallback:forScreenContext:]_block_invoke
+ ___62-[PLPowerMetricMonitorService setUpForMonitoringWithLiteMode:]_block_invoke
+ ___62-[PLPowerMetricMonitorService setUpForMonitoringWithLiteMode:]_block_invoke_2
+ ___65-[PLDisplayAgent modelDynamicDisplayPowerFromAPL:withRootNodeID:]_block_invoke
+ ___block_descriptor_57_e36_v16?0"PLContextualizedMetricData"8l
+ ___block_descriptor_64_e8_32s40s48r56r_e5_v8?0lr48l8s32l8r56l8s40l8
+ _handleDisplayCallback:forScreenContext:.classDebugEnabled
+ _handleDisplayCallback:forScreenContext:.defaultOnce
+ _kPLBatteryAgentEventBackwardNameChargerData0
+ _kPLBatteryAgentEventBackwardNameHoldName
+ _kPLBatteryAgentEventBackwardNameIsEoc
+ _kPLBatteryAgentEventBackwardNameSocLimit
+ _modelDynamicDisplayPowerFromAPL:withRootNodeID:.classDebugEnabled
+ _modelDynamicDisplayPowerFromAPL:withRootNodeID:.defaultOnce
+ _objc_retain_x9
+ _parseBuildVersion
- -[PLAppTimeService addForegroundTimeAtDate:withNewLayoutElementsArray:]
- -[PLAppTimeService chunkAppsOnScreenAtDate:]
- -[PLAppTimeService displayState]
- -[PLAppTimeService entryKeyPLScreenStateAgentScreenState]
- -[PLAppTimeService handleDisplayCallback:]
- -[PLAppTimeService handleScreenStateCallback:]
- -[PLAppTimeService lastLayoutEntries]
- -[PLAppTimeService lastScreenOnTime]
- -[PLAppTimeService resetLayoutElementsPLEntryArray:withNowDate:]
- -[PLAppTimeService setDisplayState:]
- -[PLAppTimeService setLastLayoutEntries:]
- -[PLAppTimeService setLastScreenOnTime:]
- -[PLAppTimeService updatePiPModeAppsSet:withAppRole:]
- -[PLContextualizedMetricData addGlitchWithDuration:scrollDuration:glitchCount:isScrollStart:glitchRatio:animationDuration:]
- -[PLDisplayAgent modelDisplayPowerFromIOMFB:]
- -[PLDisplayAgent modelDynamicDisplayPowerFromAPL:]
- -[PLPowerMetricMonitorService setUpForMonitoring]
- -[PLStreamingMetricAggregator addGlitchWithBundleID:timestamp:glitchDurationMs:scrollDurationMs:glitchCount:isScrollStart:glitchRatio:animationDuration:]
- GCC_except_table132
- GCC_except_table134
- GCC_except_table138
- GCC_except_table144
- GCC_except_table158
- GCC_except_table163
- GCC_except_table191
- GCC_except_table202
- GCC_except_table209
- GCC_except_table257
- GCC_except_table267
- GCC_except_table268
- GCC_except_table273
- GCC_except_table274
- GCC_except_table279
- GCC_except_table321
- GCC_except_table324
- GCC_except_table328
- _OBJC_IVAR_$_PLAppTimeService._displayState
- _OBJC_IVAR_$_PLAppTimeService._entryKeyPLScreenStateAgentScreenState
- _OBJC_IVAR_$_PLAppTimeService._lastLayoutEntries
- _OBJC_IVAR_$_PLAppTimeService._lastScreenOnTime
- _OUTLINED_FUNCTION_20
- _OUTLINED_FUNCTION_21
- ___153-[PLStreamingMetricAggregator addGlitchWithBundleID:timestamp:glitchDurationMs:scrollDurationMs:glitchCount:isScrollStart:glitchRatio:animationDuration:]_block_invoke
- ___153-[PLStreamingMetricAggregator addGlitchWithBundleID:timestamp:glitchDurationMs:scrollDurationMs:glitchCount:isScrollStart:glitchRatio:animationDuration:]_block_invoke_2
- ___42-[PLAppTimeService handleDisplayCallback:]_block_invoke
- ___49-[PLPowerMetricMonitorService setUpForMonitoring]_block_invoke
- ___49-[PLPowerMetricMonitorService setUpForMonitoring]_block_invoke_2
- ___50-[PLDisplayAgent modelDynamicDisplayPowerFromAPL:]_block_invoke
- ___71-[PLAppTimeService addForegroundTimeAtDate:withNewLayoutElementsArray:]_block_invoke
- ___block_descriptor_56_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
- ___block_descriptor_73_e36_v16?0"PLContextualizedMetricData"8l
- _addForegroundTimeAtDate:withNewLayoutElementsArray:.classDebugEnabled
- _addForegroundTimeAtDate:withNewLayoutElementsArray:.defaultOnce
- _handleDisplayCallback:.classDebugEnabled
- _handleDisplayCallback:.defaultOnce
- _modelDynamicDisplayPowerFromAPL:.classDebugEnabled
- _modelDynamicDisplayPowerFromAPL:.defaultOnce
- _setUpForMonitoring.onceToken
CStrings:
+ "-[PLAppTimeService handleDisplayCallback:forScreenContext:]"
+ "-[PLDisplayAgent modelDynamicDisplayPowerFromAPL:withRootNodeID:]"
+ "AppleChargerData"
+ "BatteryPackID"
+ "ChargerData0"
+ "Failed to subscribe to IOReport %{public}@ display stats"
+ "Failed to subscribe to IOReport %{public}@ scanout"
+ "Failed to subscribe to IOReport %{public}@ swap"
+ "Invalid build string buildA: %{public}@, buildB: %{public}@"
+ "J"
+ "Lite mode setup complete — agent init skipped"
+ "MULTI_BATTERY: Logging charger entry %@"
+ "Primed IOReport and %lu system agents after full setup upgrade"
+ "Setting up to monitor liteMode=%d"
+ "Single-display init: missing %@, skipping observer registration"
+ "Upgrading from lite mode to full agent setup"
+ "^([0-9]+)([A-Z]+)([0-9]+)([a-z]*)$"
+ "com.apple.powerlog.pl_process_network_agent"
+ "context.displayState=%d, newDisplayState=%d"
+ "holds"
+ "isEoc"
+ "primaryDisplayRef"
+ "promptExpertLoadLatency"
+ "sharedBacklight"
+ "socLimit"
+ "totalExpertsNeedingNANDLoad"
+ "totalExpertsPurgedCount"
- "-[PLAppTimeService addForegroundTimeAtDate:withNewLayoutElementsArray:]"
- "-[PLAppTimeService handleDisplayCallback:]"
- "-[PLDisplayAgent modelDynamicDisplayPowerFromAPL:]"
- "Failed to subscribe to IOReport DCP display stats"
- "Failed to subscribe to IOReport DCP scanout"
- "Failed to subscribe to IOReport DCP swap"
- "G"
- "Pulling up last screen on time %@ %@"
- "Screen On: Periodic Update - Updating On Screen time for %@ with %f added seconds"
- "Screen On: Tried updating On Screen time, but couldn't retrieve apps on screen"
- "Screen On: Updating On Screen time for %@ with %f added seconds"
- "Setting up to monitor"
- "lastScreenEventAccountingTime=%@"
- "self.displayState=%d, newDisplayState=%d"
- "setting lastScreenEventAccountingTime to self.lastScreenOnTime=%@"
```
