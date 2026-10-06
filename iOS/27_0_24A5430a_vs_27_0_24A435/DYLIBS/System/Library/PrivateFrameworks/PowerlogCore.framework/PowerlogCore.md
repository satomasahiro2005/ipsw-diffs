## PowerlogCore

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/PowerlogCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__objc_arraydata` | `0x441d8` | `0x45e58` | **`+0x1c80`** |
| `__AUTH_CONST.__cfstring` | `0x6c560` | `0x6cf60` | **`+0xa00`** |
| `__TEXT.__cstring` | `0x43086` | `0x4387e` | **`+0x7f8`** |
| `__TEXT.__text` | `0xe8568` | `0xe8af4` | **`+0x58c`** |
| `__AUTH_CONST.__objc_dictobj` | `0xf910` | `0xfcf8` | **`+0x3e8`** |
| `__AUTH_CONST.__objc_intobj` | `0x4a70` | `0x4cb0` | **`+0x240`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x13a0` | `0x14d0` | **`+0x130`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x1188` | `0x1230` | **`+0xa8`** |
| `__TEXT.__const` | `0x1b98` | `0x1c38` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x25f0` | `0x2600` | **`+0x10`** |

### Other Changes

```diff

-  Symbols:   7264
-  CStrings:  15193
+  Symbols:   7265
+  CStrings:  15273
Symbols:
+ _kPLBB25
Functions:
~ +[PLPlatform kPLDeviceMap] : 40288 -> 41560
~ ___29+[PLPlatform isBasebandProto]_block_invoke : 60 -> 72
~ ___28+[PLPlatform isBasebandDSDS]_block_invoke : 124 -> 132
~ +[PLModelingUtilities defaultBatteryEnergyCapacity] : 6528 -> 6656
CStrings:
+ "1006036"
+ "ActiveMMW"
+ "Angle"
+ "AutoEntryCounterCase2"
+ "AutoEntryCounterCase3"
+ "ButtonPressExitCounter"
+ "ChargerAccumEfficiencyCount"
+ "ChargerAccumulatedEfficiency"
+ "ChargerConnectExitCounter"
+ "ChargerEfficiency"
+ "ChargerHwIlimBackoffReason"
+ "ChargerIBUS"
+ "ChargerPower"
+ "ChargerVBUS"
+ "DisplayDynamicX"
+ "Flip"
+ "LastSLMExitType"
+ "LiftToWake"
+ "PLBatteryAgent_EventBackward_BatteryPack0"
+ "PLBatteryAgent_EventBackward_BatteryPack1"
+ "PLBatteryAgent_EventBackward_ChargerData0"
+ "PLBatteryAgent_EventBackward_ChargerData1"
+ "PLBatteryAgent_EventBackward_RebalanceData"
+ "PLBatteryAgent_EventBackward_ShelfLifeModeAutoEntry"
+ "PLBatteryAgent_EventBackward_ShelfLifeModeAutoEntryX"
+ "PLBatteryAgent_EventBackward_ShelfLifeModeExitCounters"
+ "PLBatteryAgent_EventBackward_ShelfLifeModeExitCountersX"
+ "PLBatteryAgent_EventBackward_TrustedBatteryHealth0"
+ "PLBatteryAgent_EventBackward_TrustedBatteryHealth1"
+ "PLBatteryAgent_EventNone_BatteryConfigPack0"
+ "PLBatteryAgent_EventNone_BatteryConfigPack1"
+ "PLBatteryAgent_EventPoint_BatteryShutdownPack0"
+ "PLBatteryAgent_EventPoint_BatteryShutdownPack1"
+ "PLDisplayAgent_EventBackward_APLStatsX"
+ "PLDisplayAgent_EventForward_DisplayX"
+ "PLDisplayAgent_EventPoint_DisplayX"
+ "PLIOReportAgent_EventBackward_DCPSECscanout"
+ "PLIOReportAgent_EventBackward_DCPSECscanoutstats"
+ "PLIOReportAgent_EventBackward_DCPSECswap"
+ "PLIOReportAgent_EventBackward_Multitouch2Multitouchhighlevelstats"
+ "PLIOReportAgent_EventBackward_Multitouch2touch"
+ "PLScreenStateAgent_EventBackward_BacklightStateChangeX"
+ "PLScreenStateAgent_EventForward_ScreenStateX"
+ "RebalanceEnableStatus"
+ "RebalanceErrorFlags"
+ "RebalanceHWBypassFETStatus0"
+ "RebalanceHWBypassFETStatus1"
+ "RebalanceInrushCurrentDebug"
+ "RebalanceNotRebalancingReason"
+ "RebalanceOutputStruct"
+ "RebalanceTimeSeconds"
+ "V63"
+ "V64"
+ "V64s"
+ "V68"
+ "actmmw"
+ "bb25"
+ "cnfgmmw"
+ "configType"
+ "curAngle"
+ "curGravityX"
+ "curGravityY"
+ "curGravityZ"
+ "flipDetectedTimestamp"
+ "flipReason"
+ "flipReasonPrevious"
+ "flipState"
+ "flipStatePrevious"
+ "gestureDuration"
+ "hingeIdentifier"
+ "intervalLastEvent"
+ "isAPAwake"
+ "maxHingeRotationRate"
+ "meanHingeRotationRate"
+ "prevAngle"
+ "prevGravityX"
+ "prevGravityY"
+ "prevGravityZ"
+ "timeSinceLastGesture"
+ "wasPrevAngleAmbiguous"
```
