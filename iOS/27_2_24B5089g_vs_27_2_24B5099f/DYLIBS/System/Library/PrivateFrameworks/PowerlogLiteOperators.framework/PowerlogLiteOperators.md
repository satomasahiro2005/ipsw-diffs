## PowerlogLiteOperators

> `/System/Library/PrivateFrameworks/PowerlogLiteOperators.framework/PowerlogLiteOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f791c` | `0x4f8f78` | **`+0x165c`** |
| `__TEXT.__cstring` | `0x60a1f` | `0x60bab` | **`+0x18c`** |
| `__AUTH_CONST.__cfstring` | `0x784a0` | `0x78600` | **`+0x160`** |
| `__AUTH_CONST.__objc_const` | `0x38bb0` | `0x38c70` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x2f7dc` | `0x2f854` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x14e18` | `0x14e70` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x16ad3` | `0x16b24` | **`+0x51`** |
| `__DATA_CONST.__objc_arraydata` | `0x16dc0` | `0x16da0` | **`-0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3168` | `0x3180` | **`+0x18`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x1310` | `0x1320` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x9730` | `0x9740` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2d84` | `0x2d90` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x1fa4` | `0x1fac` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x4790` | `0x4798` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1388` | `0x1390` | **`+0x8`** |

### Other Changes

```diff

-3486.40.98.0.0
+3486.40.112.0.0

-  Functions: 19892
-  Symbols:   25896
-  CStrings:  19910
+  Functions: 19904
+  Symbols:   25910
+  CStrings:  19924
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
+ _OBJC_IVAR_$_PLSleepWakeAgent._kaIDMax
+ _OBJC_IVAR_$_PLSleepWakeAgent._kaIDMin
+ ___52+[PLUrsaUtilities diagnosticExtensionIDsForProcess:]_block_invoke
+ ___83-[PLAppTimeService updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:]_block_invoke
+ ___block_descriptor_57_e8_32s40s48s_e25_v32?0"NSString"8Q16^B24ls32l8s40l8s48l8
+ _kPLAppTimeServiceAggregateNameDisplayID
+ _kPLAppTimeServiceAggregateNameDisplayUsage
- +[PLUrsaUtilities shouldCollectCPLDiagnosticExtensionForProcess:]
- GCC_except_table35
- ___65+[PLUrsaUtilities shouldCollectCPLDiagnosticExtensionForProcess:]_block_invoke
- ___block_descriptor_49_e8_32s40s_e25_v32?0"NSString"8Q16^B24ls32l8s40l8
CStrings:
+ "%@: rail is OFF, timestamp=%u, entry=%d"
+ "%@: reached end of buffer, timestamp=%u, entry=%d"
+ "-[PLAppTimeService updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:]"
+ "AccumSystemEffectiveTotalLoad"
+ "AccumSystemEffectiveTotalLoadCount"
+ "AccumulatedBatteryPower"
+ "BatteryPowerAccumulatorCount"
+ "DisplayID"
+ "DisplayUsage"
+ "For bundleID '%@' and display ID %@, added foreground %@"
+ "Kernel assertions entry: kaID=%llu, duration=%f, count=%zu"
+ "Log Power Delivery Keys to CA, payload=%@"
+ "PLUrsaUtilities: requesting diagnostic extensions %{public}@ for %{public}@"
+ "SystemEffectiveTotalLoad"
+ "adding timeDifference=%f for bundleID=%@ and displayID=%lu"
+ "com.apple.DiagnosticExtensions.IMDiagnosticExtension"
+ "com.apple.power.powerDeliveryKeys"
+ "imagent"
+ "imdpersistence.imdpersistenceagent"
+ "imdpersistenceagent"
+ "rail = %@, payload = %@"
- "%@: manually increment timestamp %u at entry %d"
- "%@: reached the end of buffer at entry %d"
- "%@: reached the end of buffer at entry %d due to timestamp jump %u"
- ",%@"
- "Kernel assertions entry: paID=%llu, duration=%f, count=%zu"
- "PLUrsaUtilities: requesting CPL diagnostic extension for %{public}@"
- "PMUMetricsStatic: rail = %@, payload = %@"
```
