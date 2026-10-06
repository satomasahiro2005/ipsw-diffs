## com.apple.driver.AppleSmartBatteryManagerEmbedded

> `com.apple.driver.AppleSmartBatteryManagerEmbedded`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x31e88` | `0x325e8` | **`+0x760`** |
| `__TEXT.__cstring` | `0x82e7` | `0x85e9` | **`+0x302`** |
| `__DATA.__bss` | `0x5580` | `0x5668` | **`+0xe8`** |
| `__DATA.__common` | `0x4c8` | `0x4d8` | **`+0x10`** |
| `__TEXT.__const` | `0x2640` | `0x2650` | **`+0x10`** |

### Other Changes

```diff

-2043.2.2.0.0
-  Functions: 695
+2043.40.43.0.0
+  Functions: 696

-  CStrings:  1282
+  CStrings:  1307
CStrings:
+ "12111112122212121111111112111111122221112"
+ "AppleSmartBatteryPack: DBG: ID: %d Gauge reports no lifetime failure counters\n"
+ "AppleSmartBatteryPack: DBG: ID: %d Lifetime failure counter mask has slots this kext does not publish:%#llx\n"
+ "AppleSmartBatteryPack: ID: %d Battery pack is pending/missing/bad\n"
+ "AppleSmartBatteryPack: ID: %d Lifetime failure counter payload is %u bytes, expected %zu\n"
+ "ChargeInhibit"
+ "ChargeSuspend"
+ "ChargingOverCurrentHW"
+ "ChargingOverCurrentLevel1"
+ "ChargingOverCurrentLevel2"
+ "ChargingOverTemperature"
+ "ChargingUnderTemperature"
+ "DischargingOverCurrentHW1"
+ "DischargingOverCurrentHW2"
+ "DischargingOverCurrentLevel1"
+ "DischargingOverCurrentLevel2"
+ "DischargingOverTemperature"
+ "DischargingShortCircuitHW"
+ "DischargingUnderTemperature"
+ "FETOverTemperature"
+ "FailureCounters"
+ "FeatureFlags"
+ "LTFailureCounterData"
+ "OverVoltage"
+ "PassedChargeHighVoltage"
+ "PassedChargeLowVoltage"
+ "UnderVoltage"
- "1211111212221212111111111211111112221112"
- "AppleSmartBatteryPack: ID: %d Battery pack is missing/bad\n"
```
