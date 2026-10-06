## com.apple.driver.AppleSmartBatteryManagerEmbedded

> `com.apple.driver.AppleSmartBatteryManagerEmbedded`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x304b8` | `0x315e4` | **`+0x112c`** |
| `__TEXT.__cstring` | `0x7bf6` | `0x8289` | **`+0x693`** |
| `__DATA.__bss` | `0x5350` | `0x5560` | **`+0x210`** |
| `__TEXT.__const` | `0x2440` | `0x2630` | **`+0x1f0`** |
| `__DATA.__common` | `0x3c0` | `0x4c8` | **`+0x108`** |
| `__DATA_CONST.__kalloc_var` | `0x8c0` | `0x960` | **`+0xa0`** |
| `__TEXT.__os_log` | `0x2970` | `0x28fb` | **`-0x75`** |
| `__TEXT_EXEC.__auth_stubs` | `0x7a0` | `0x7c0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x3d0` | `0x3e0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x100` | `0x108` | **`+0x8`** |

### Other Changes

```diff

-2043.0.31.0.0
-  Functions: 689
+2043.0.45.502.1
+  Functions: 695

-  CStrings:  1254
+  CStrings:  1280
CStrings:
+ "1211111212221212111111111211111112221112"
+ "ApplePPMCPMS"
+ "ApplePPMInterfaceAPIFunction"
+ "AppleSmartBatteryPack: ID: %d Failed to clear shutdown data. rc:0x%x=%s\n"
+ "AppleSmartBatteryPack: ID: %d Failed to create shutdown reason symbol\n"
+ "AppleSmartBatteryPack: ID: %d Failed to read shutdown data error flags\n"
+ "AppleSmartBatteryPack: ID: %d Failed to read shutdown nominal capacity\n"
+ "AppleSmartBatteryPack: ID: %d Failed to update Error Condition\n"
+ "AppleSmartBatteryPack: ID: %d No battery shutdown data for pack %d\n"
+ "AppleSmartBatteryPack: ID: %d failed to read shutdownData for pack %d\n"
+ "AppleSmartBatteryPack: ID: %d updateRebalanceData: PPM API call failed, ret=%d\n"
+ "AppleSmartBatteryPack: ID: %d updateRebalanceData: PPM returned all-zero impedance array, skipping SMC write\n"
+ "AppleSmartBatteryPack: ID: %d updateRebalanceData: failed to allocate dataIn\n"
+ "AppleSmartBatteryPack: ID: %d updateRebalanceData: failed to get impedance array from PPM output\n"
+ "AppleSmartBatteryPack: ID: %d updateRebalanceData: failed to get impedence key (%c%c%c%c) data, ret=%d\n"
+ "AppleSmartBatteryPack: ID: %d updateRebalanceData: failed to read DOD key, ret=%d\n"
+ "AppleSmartBatteryPack: ID: %d updateRebalanceData: failed to read temp key, ret=%d\n"
+ "AppleSmartBatteryPack: ID: %d updateRebalanceData: failed to write impedence key (%c%c%c%c), raw=%d,ret=%d\n"
+ "AppleSmartBatteryPack: ID: %d updateRebalanceData: no Algo chem ID in bank batteryData\n"
+ "AppleSmartBatteryPack: ID: %d updateRebalanceData: no bank instance\n"
+ "AppleSmartBatteryPack: ID: %d updateRebalanceData: no batteryData in bank\n"
+ "BatteryInstalled=%u packs:%d\n"
+ "Cell Check Fault"
+ "Charged Too Long"
+ "Charger Communication Failure"
+ "Ibatt MinFault"
+ "Ignoring SMC message type %#x while system is sleeping\n"
+ "Not restarting poll type %d while system is sleeping\n"
+ "Vbatt Fault"
+ "kPPMChemIdReq"
+ "kPPMDODInReq"
+ "kPPMInterfaceAPIReq"
+ "kPPMOutImpdDataR0"
+ "kPPMTempInReq"
- "1211111212221212111111111211111122212"
- "BatteryInstalled=%u packs:%zu\n"
- "Failed to clear shutdown data. rc:0x%x=%s\n"
- "Failed to read shutdown data error flags\n"
- "Failed to read shutdown nominal capacity\n"
- "Failed with permanent failure for cmd 0x%x\n"
- "No battery shutdown data\n"
- "failed to read shutdownData\n"
```
