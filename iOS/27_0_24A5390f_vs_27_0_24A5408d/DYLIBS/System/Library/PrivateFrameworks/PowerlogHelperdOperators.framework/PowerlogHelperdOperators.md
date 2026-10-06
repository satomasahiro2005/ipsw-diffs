## PowerlogHelperdOperators

> `/System/Library/PrivateFrameworks/PowerlogHelperdOperators.framework/PowerlogHelperdOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d96a8` | `0x1dc330` | **`+0x2c88`** |
| `__AUTH_CONST.__objc_const` | `0x15ac8` | `0x15dd0` | **`+0x308`** |
| `__TEXT.__cstring` | `0x26211` | `0x2641e` | **`+0x20d`** |
| `__TEXT.__objc_methlist` | `0x10928` | `0x10ae0` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0x14a8b` | `0x14c39` | **`+0x1ae`** |
| `__AUTH_CONST.__cfstring` | `0x335c0` | `0x33740` | **`+0x180`** |
| `__DATA_CONST.__objc_selrefs` | `0xac90` | `0xad78` | **`+0xe8`** |
| `__TEXT.__gcc_except_tab` | `0x24e8` | `0x258c` | **`+0xa4`** |
| `__DATA_CONST.__objc_arraydata` | `0x15990` | `0x159f0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x3b30` | `0x3b88` | **`+0x58`** |
| `__AUTH.__objc_data` | `0xaf0` | `0xb40` | **`+0x50`** |
| `__AUTH_CONST.__objc_dictobj` | `0x3a20` | `0x3a70` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x4448` | `0x4480` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x15cc` | `0x15f8` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0x1a20` | `0x1a40` | **`+0x20`** |
| `__DATA.__bss` | `0x2098` | `0x20b8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xf50` | `0xf70` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x2898` | `0x28b0` | **`+0x18`** |
| `__TEXT.__const` | `0x6f0` | `0x700` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x388` | `0x390` | **`+0x8`** |

### Other Changes

```diff

-3486.0.81.502.4
+3486.2.4.0.0

+  - /System/Library/PrivateFrameworks/AttentionAwareness.framework/AttentionAwareness

-  Functions: 8565
-  Symbols:   11637
-  CStrings:  8920
+  Functions: 8612
+  Symbols:   11704
+  CStrings:  8944
Symbols:
+ +[PLBatteryAgent entryEventPointDefinitionBatteryShutdownPack]
+ +[PLDisplayAgent _entryEventBackwardDefinitionAPLStatsWithLogSelector:]
+ +[PLUtilities getHardwarePerfKind:]
+ -[KernelTaskMonitorStats cpu_energy_m]
+ -[KernelTaskMonitorStats setCpu_energy_m:]
+ -[PLBatteryAgent logBatteryShutdownToCA:forBatteryPack:]
+ -[PLBatteryAgent logEventPointBatteryShutdownWithRawData:packID:systemShutdownData:]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility .cxx_destruct]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility cleanUp]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility coalesce]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility configure:]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility criticalDays]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility dependencies]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility end]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility responderService]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility result]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility run]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility setCriticalDays:]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility setEnd:]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility setResponderService:]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility setStart:]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility setUiLevelEntries:]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility start]
+ -[PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility uiLevelEntries]
+ -[PLContextualizedMetricData reducedAccuracySeconds]
+ -[PLContextualizedMetricData setReducedAccuracySeconds:]
+ -[PLPowerMetricMonitorService processWideAgentSetupDone]
+ -[PLPowerMetricMonitorService setProcessWideAgentSetupDone:]
+ -[PLSpringBoardAgent attentionAwarenessClient]
+ -[PLSpringBoardAgent lastUserEventMediaTime]
+ -[PLSpringBoardAgent setAttentionAwarenessClient:]
+ -[PLSpringBoardAgent setLastUserEventMediaTime:]
+ -[PLSpringBoardAgent startAttentionAwarenessClient]
+ -[PLSpringBoardAgent stopAttentionAwarenessClient]
+ -[PLStateMetricsInput locationReducedAccuracySeconds]
+ -[PLStateMetricsInput setLocationReducedAccuracySeconds:]
+ GCC_except_table119
+ GCC_except_table136
+ GCC_except_table140
+ GCC_except_table158
+ GCC_except_table175
+ GCC_except_table187
+ GCC_except_table193
+ GCC_except_table203
+ GCC_except_table248
+ GCC_except_table257
+ GCC_except_table260
+ GCC_except_table262
+ GCC_except_table271
+ GCC_except_table278
+ GCC_except_table283
+ GCC_except_table325
+ GCC_except_table328
+ GCC_except_table332
+ _OBJC_CLASS_$_AWAttentionAwarenessClient
+ _OBJC_CLASS_$_AWAttentionAwarenessConfiguration
+ _OBJC_CLASS_$_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility
+ _OBJC_IVAR_$_KernelTaskMonitorStats._cpu_energy_m
+ _OBJC_IVAR_$_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility._criticalDays
+ _OBJC_IVAR_$_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility._end
+ _OBJC_IVAR_$_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility._responderService
+ _OBJC_IVAR_$_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility._start
+ _OBJC_IVAR_$_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility._uiLevelEntries
+ _OBJC_IVAR_$_PLContextualizedMetricData._reducedAccuracySeconds
+ _OBJC_IVAR_$_PLPowerMetricMonitorService._processWideAgentSetupDone
+ _OBJC_IVAR_$_PLSpringBoardAgent._attentionAwarenessClient
+ _OBJC_IVAR_$_PLSpringBoardAgent._lastUserEventMediaTime
+ _OBJC_IVAR_$_PLStateMetricsInput._locationReducedAccuracySeconds
+ _OBJC_METACLASS_$_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility
+ __OBJC_$_INSTANCE_METHODS_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility
+ __OBJC_$_INSTANCE_VARIABLES_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility
+ __OBJC_$_PROP_LIST_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility
+ __OBJC_CLASS_PROTOCOLS_$_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility
+ __OBJC_CLASS_RO_$_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility
+ __OBJC_METACLASS_RO_$_PLBatteryUIResponseTypeOptimizeBatteryPromptEligibility
+ ___35+[PLUtilities getHardwarePerfKind:]_block_invoke
+ ___51-[PLSpringBoardAgent startAttentionAwarenessClient]_block_invoke
+ ___56-[PLBatteryAgent logBatteryShutdownToCA:forBatteryPack:]_block_invoke
+ ___84-[PLBatteryAgent logEventPointBatteryShutdownWithRawData:packID:systemShutdownData:]_block_invoke
+ ___84-[PLBatteryAgent logEventPointBatteryShutdownWithRawData:packID:systemShutdownData:]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e26_v16?0"AWAttentionEvent"8lw32l8
+ ___snprintf_chk
+ _getHardwarePerfKind:.cache
+ _getHardwarePerfKind:.cacheOnce
+ _kCLLocationAccuracyReduced
+ _kPLBatteryAgentEventPointNameBatteryShutdownPack0
+ _kPLBatteryAgentStringLastShutdownSystemTimestamp0
+ _kPLBatteryAgentStringLastShutdownSystemTimestampSystem
+ _logEventPointBatteryShutdownWithRawData:packID:systemShutdownData:.classDebugEnabled
+ _logEventPointBatteryShutdownWithRawData:packID:systemShutdownData:.defaultOnce
+ _startAttentionAwarenessClient.classDebugEnabled
+ _startAttentionAwarenessClient.defaultOnce
- -[PLBatteryAgent logBatteryShutdownToCA:]
- GCC_except_table117
- GCC_except_table135
- GCC_except_table139
- GCC_except_table157
- GCC_except_table174
- GCC_except_table186
- GCC_except_table192
- GCC_except_table247
- GCC_except_table256
- GCC_except_table259
- GCC_except_table261
- GCC_except_table269
- GCC_except_table275
- GCC_except_table281
- GCC_except_table323
- GCC_except_table326
- GCC_except_table330
- _BKSHIDServicesLastUserEventTime
- ___41-[PLBatteryAgent logBatteryShutdownToCA:]_block_invoke
- ___46-[PLBatteryAgent logEventPointBatteryShutdown]_block_invoke
- ___46-[PLBatteryAgent logEventPointBatteryShutdown]_block_invoke_2
- _kPLBatteryAgentStringLastShutdownSystemTimestamp
- _logEventPointBatteryShutdown.classDebugEnabled
- _logEventPointBatteryShutdown.defaultOnce
CStrings:
+ "-[PLBatteryAgent logEventPointBatteryShutdownWithRawData:packID:systemShutdownData:]"
+ "-[PLSpringBoardAgent startAttentionAwarenessClient]"
+ "AppleSmartBatteryPack"
+ "AttentionAwareness unavailable on this image; autolock energy will use fallback timing"
+ "Battery metrics already set up."
+ "BatteryShutdown: Failed to get AppleSmartBatteryPack data with result=%x"
+ "BatteryShutdown: log entry for pack=%@"
+ "BatteryShutdownPack0"
+ "CPUEnergyM"
+ "Failed to configure AttentionAwareness client: %{public}@"
+ "Failed to resume AttentionAwareness client: %{public}@"
+ "Failed to retrieve power sources list handle."
+ "LastShutdownSystemTimestampSystem"
+ "No data in battUI for dormancy eligibility"
+ "Not enough data for dormancy eligibility (need %d days)"
+ "Number of critical days: %d"
+ "PDTP"
+ "ReducedAccuracy"
+ "com.apple.ImagePlaygroundPoster.ImagePlaygroundPosterExtension"
+ "com.apple.powerlog.autolock"
+ "hw.perflevel%u.name"
+ "locationReducedAccuracySeconds"
+ "optimizeBatteryPromptEligibility"
+ "reducedAccuracy"
+ "reducedAccuracySeconds"
+ "v16@?0@\"AWAttentionEvent\"8"
+ "\xbd"
+ "\xf0\xf0Ec"
- "-[PLBatteryAgent logEventPointBatteryShutdown]"
- "A"
- "\xad"
- "\xf0\xf05c"
```
