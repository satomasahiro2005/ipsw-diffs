## PowerlogHelperdOperators

> `/System/Library/PrivateFrameworks/PowerlogHelperdOperators.framework/PowerlogHelperdOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e78c8` | `0x1e9064` | **`+0x179c`** |
| `__TEXT.__cstring` | `0x26afd` | `0x26c67` | **`+0x16a`** |
| `__TEXT.__oslogstring` | `0x15e78` | `0x15fdd` | **`+0x165`** |
| `__AUTH_CONST.__cfstring` | `0x34240` | `0x34380` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x16a40` | `0x16b00` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x11288` | `0x11300` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0xb270` | `0xb2d8` | **`+0x68`** |
| `__DATA_CONST.__objc_arraydata` | `0x16498` | `0x16478` | **`-0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3048` | `0x3060` | **`+0x18`** |
| `__AUTH_CONST.__objc_doubleobj` | `0xb90` | `0xba0` | **`+0x10`** |
| `__DATA.__bss` | `0x20c8` | `0x20d8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x16dc` | `0x16ec` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x45a8` | `0x45b8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2598` | `0x25a4` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x3c78` | `0x3c80` | **`+0x8`** |

### Other Changes

```diff

-3486.40.98.0.0
+3486.40.112.0.0

-  Functions: 8852
-  Symbols:   11974
-  CStrings:  9119
+  Functions: 8864
+  Symbols:   11993
+  CStrings:  9134
Symbols:
+ +[PLAppTimeService entryAggregateDefinitionDisplayUsage]
+ +[PLUrsaUtilities diagnosticExtensionIDsForProcess:]
+ -[PLAppTimeService aggregateEntryKeyForDisplayUsage]
+ -[PLAppTimeService setAggregateEntryKeyForDisplayUsage:]
+ -[PLAppTimeService updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:]
+ -[PLBatteryAgent batteryPackCount]
+ -[PLBatteryAgent setBatteryPackCount:]
+ -[PLSleepWakeAgent kaIDMax]
+ -[PLSleepWakeAgent kaIDMin]
+ -[PLSleepWakeAgent setKaIDMax:]
+ -[PLSleepWakeAgent setKaIDMin:]
+ _OBJC_IVAR_$_PLAppTimeService._aggregateEntryKeyForDisplayUsage
+ _OBJC_IVAR_$_PLBatteryAgent._batteryPackCount
+ _OBJC_IVAR_$_PLSleepWakeAgent._kaIDMax
+ _OBJC_IVAR_$_PLSleepWakeAgent._kaIDMin
+ ___52+[PLUrsaUtilities diagnosticExtensionIDsForProcess:]_block_invoke
+ ___83-[PLAppTimeService updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:]_block_invoke
+ _diagnosticExtensionIDsForProcess:.mapping
+ _diagnosticExtensionIDsForProcess:.onceToken
+ _kPLAppTimeServiceAggregateNameDisplayID
+ _kPLAppTimeServiceAggregateNameDisplayID_block_invoke.classDebugEnabled
+ _kPLAppTimeServiceAggregateNameDisplayID_block_invoke.defaultOnce
+ _kPLAppTimeServiceAggregateNameDisplayID_block_invoke_2.classDebugEnabled
+ _kPLAppTimeServiceAggregateNameDisplayID_block_invoke_2.defaultOnce
+ _kPLAppTimeServiceAggregateNameDisplayUsage
+ _updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:.classDebugEnabled
+ _updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:.defaultOnce
- +[PLUrsaUtilities shouldCollectCPLDiagnosticExtensionForProcess:]
- ___65+[PLUrsaUtilities shouldCollectCPLDiagnosticExtensionForProcess:]_block_invoke
- _kPLAppTimeServiceAggregateNameHasAudioUsage_block_invoke.classDebugEnabled
- _kPLAppTimeServiceAggregateNameHasAudioUsage_block_invoke.defaultOnce
- _kPLAppTimeServiceAggregateNameHasAudioUsage_block_invoke_2.classDebugEnabled
- _kPLAppTimeServiceAggregateNameHasAudioUsage_block_invoke_2.defaultOnce
- _shouldCollectCPLDiagnosticExtensionForProcess:.cplDiagnosticExtensionProcesses
- _shouldCollectCPLDiagnosticExtensionForProcess:.onceToken
CStrings:
+ "-[PLAppTimeService updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:]"
+ "AccumSystemEffectiveTotalLoad"
+ "AccumSystemEffectiveTotalLoadCount"
+ "AccumulatedBatteryPower"
+ "BatteryPowerAccumulatorCount"
+ "Chunk interval memory: average suspended memory is zero (sampleCount: %ld, peakBytes: %lu)"
+ "DisplayID"
+ "DisplayUsage"
+ "For bundleID '%@' and display ID %@, added foreground %@"
+ "Kernel assertions entry: kaID=%llu, duration=%f, count=%zu"
+ "PLUrsaUtilities: requesting diagnostic extensions %{public}@ for %{public}@"
+ "SystemEffectiveTotalLoad"
+ "adding timeDifference=%f for bundleID=%@ and displayID=%lu"
+ "com.apple.DiagnosticExtensions.IMDiagnosticExtension"
+ "getSignpostMetricsWithStartDate returned launchDurations=%lu extendedLaunchDurations=%lu launchesTimeSeries=%lu bundleIDs(launchDurations)=%@"
+ "imagent"
+ "imdpersistence.imdpersistenceagent"
+ "imdpersistenceagent"
- ",%@"
- "Kernel assertions entry: paID=%llu, duration=%f, count=%zu"
- "PLUrsaUtilities: requesting CPL diagnostic extension for %{public}@"
```
