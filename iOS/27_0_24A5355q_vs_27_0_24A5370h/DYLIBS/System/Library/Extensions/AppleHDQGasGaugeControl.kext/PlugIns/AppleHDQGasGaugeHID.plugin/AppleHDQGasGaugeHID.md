## AppleHDQGasGaugeHID

> `/System/Library/Extensions/AppleHDQGasGaugeControl.kext/PlugIns/AppleHDQGasGaugeHID.plugin/AppleHDQGasGaugeHID`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa000` | `0x9e30` | **`-0x1d0`** |

### Other Changes

```diff

-238.0.0.0.0
+240.0.0.0.0
Functions:
~ _dumpBuffer : 112 -> 120
~ _findRaWeightMulitplier : 52 -> 60
~ _parseShutdownReason : 1348 -> 1352
~ _updateThread : 14212 -> 13920
~ _readChargeTable : 808 -> 816
~ _readBatteryData : 180 -> 184
~ _calculateBatteryHealthMetric : 384 -> 392
~ _readChargerData : 740 -> 716
~ _dynamicATV : 448 -> 444
~ _determineVACVoltage : 796 -> 804
~ _parseBatteryData : 3712 -> 3532
~ _createStringWithBytes : 76 -> 72
~ _GGHIDCopyProperty : 784 -> 776
```
