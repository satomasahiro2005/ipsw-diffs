## CPMS

> `/System/Library/PrivateFrameworks/CPMS.framework/CPMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b20` | `0x9818` | **`+0xcf8`** |
| `__AUTH_CONST.__cfstring` | `0x1120` | `0x1300` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0xc75` | `0xcd1` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0x1a8` | `0x1e8` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x390` | `0x3c0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4ac` | `0x4c4` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x270` | `0x280` | **`+0x10`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x10` | `—` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x90` | `0x98` | **`+0x8`** |
| `__TEXT.__const` | `0x9c` | `0xa0` | **`+0x4`** |

### Other Changes

```diff

-1177.0.0.502.4
+1191.0.4.502.1

-  Functions: 181
-  Symbols:   270
-  CStrings:  274
+  Functions: 184
+  Symbols:   275
+  CStrings:  291
Symbols:
+ +[CPMSStateReader copyCPMSControlStateSnapshotDictionaries]
+ +[CPMSStateReader flattenSnapshot:index:into:]
+ _OBJC_CLASS_$_NSArray
+ _flattenSnapshot:index:into:.batteryPowerDataNames
+ _objc_retain_x25
+ _objc_retain_x4
- _OBJC_CLASS_$_NSConstantDoubleNumber
CStrings:
+ ""
+ " "
+ "%@_%d_%d"
+ "%@_%s_%@_%d"
+ "%@_Battery%d_%d"
+ "BrownoutRiskEngaged"
+ "BrownoutRiskPu"
+ "BrownoutRiskSysCap"
+ "DroopCE"
+ "DroopIS"
+ "Gauge10s"
+ "Gauge1s"
+ "HFE RCCurrent"
+ "IBat"
+ "LaneCE"
+ "LastDisengagedCritDroopTS"
+ "LastDisengagedPolicyTS"
+ "LastEngagedCritDroopTS"
+ "LastEngagedPolicyTS"
+ "OperationMode"
+ "OverrideFlags"
+ "PMU100ms"
+ "PMU10ms"
+ "PMU10s"
+ "PMU1s"
+ "PeakPowerPressureLevel"
+ "Reason"
+ "RemainingCapacity"
+ "SecondaryPICE"
+ "SecondaryPIIS"
+ "ServoCE"
+ "SnapshotTimestamp"
+ "SystemCapabilitySource"
+ "SystemStressLevel"
+ "VddMon"
+ "_%d"
+ "grant"
+ "req"
+ "telephony"
+ "unknown"
+ "waterejection"
- "brownoutRiskNotificationEngaged"
- "brownoutRiskPu"
- "brownoutRiskSysCap"
- "droopCE"
- "droopIS"
- "laneCEs"
- "lastDisengagedCriticalDroopTimeStamp"
- "lastDisengagedPolicyTimeStamp"
- "lastEngagedCriticalDroopTimeStamp"
- "lastEngagedPolicyTimeStamp"
- "mode"
- "overrideFlags"
- "peakPowerPressureLevel"
- "reason"
- "remCapCEFloors"
- "remainingCapacity"
- "servoCEs"
- "systemCapability"
- "systemCapabilitySource"
- "systemStressLevel"
- "timestamp"
- "undroopCE"
- "undroopIS"
- "zeroSumCE"
```
