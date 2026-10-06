## com.apple.driver.AppleSmartBatteryManagerEmbedded

> `com.apple.driver.AppleSmartBatteryManagerEmbedded`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x3968` | `0x52e0` | **`+0x1978`** |
| `__DATA.__common` | `0x1b58` | `0x3c0` | **`-0x1798`** |
| `__TEXT_EXEC.__text` | `0x31a3c` | `0x303ec` | **`-0x1650`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x7a0` | **`+0x7a0`** |
| `__DATA_CONST.__const` | `0x5768` | `0x5d58` | **`+0x5f0`** |
| `__TEXT.__cstring` | `0x79ed` | `0x7d34` | **`+0x347`** |
| `__TEXT.__const` | `0x2130` | `0x2410` | **`+0x2e0`** |
| `__DATA_CONST.__kalloc_var` | `0x5f0` | `0x8c0` | **`+0x2d0`** |
| `__TEXT.__os_log` | `0x2b29` | `0x2937` | **`-0x1f2`** |
| `__DATA.__data` | `0x230` | `0x1f0` | **`-0x40`** |
| `__DATA_CONST.__kalloc_type` | `0x6c0` | `0x700` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x3c8` | `0x3d0` | **`+0x8`** |
| `__DATA_CONST.__mod_term_func` | `0x70` | `0x78` | **`+0x8`** |

### Other Changes

```diff

-2015.0.0.0.1
-  Functions: 678
+2041.0.0.502.1
+  Functions: 689

-  CStrings:  1227
+  CStrings:  1253
CStrings:
+ "%s%u"
+ "1211111212221212111111111211111122212"
+ "121111121222121211211"
+ "121111121222121211211111112222"
+ "121111121222121212111111111111111111111111212212122112111111211112212121122"
+ "2221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212"
+ "AlgoCycleCountDbgData"
+ "AppleSmartBatteryBank"
+ "AppleSmartBatteryBank.cpp"
+ "AppleSmartBatteryBank: DBG: Pack ID: %d Bank ID: %d WriteSMCKey attempt %lu/%u"
+ "AppleSmartBatteryBank: Pack ID: %d Bank ID: %d failed to write key '%c%c%c%c' rc:%u=%s\n"
+ "AppleSmartBatteryBank: Pack ID: %d Bank ID: %d failed to write key '%c%c%c%c', retry:%zu\n"
+ "AppleSmartBatteryCell"
+ "AppleSmartBatteryPack: ID: %d failed to enable Carrier Mode(%d) %x=%s\n"
+ "AppleSmartBatteryPack: ID: %d failed to set Carrier Mode lower limit(%d) %x=%s\n"
+ "AppleSmartBatteryPack: ID: %d failed to set Carrier Mode lower voltage(%d) %x=%s\n"
+ "AppleSmartBatteryPack: ID: %d failed to set Carrier Mode upper limit(%d) %x=%s\n"
+ "AppleSmartBatteryPack: ID: %d failed to set Carrier Mode upper voltage(%d) %x=%s\n"
+ "Attached"
+ "BatteryInstalled=%u packs:%zu\n"
+ "BatteryModelID"
+ "BatteryNeedsRest"
+ "BatteryPfCommsFailure"
+ "CellCurrent"
+ "CellCurrentRatio"
+ "CellData"
+ "CellDisconnect"
+ "CellID"
+ "Charger efficiency key failed to create\n"
+ "Charger efficiency key failed to read. rc:0x%x=%s\n"
+ "EPTDelay"
+ "Failed to read bank configuration\n"
+ "FaultType"
+ "FullChargeCapacity"
+ "IsCharging"
+ "RebalanceData"
+ "RebalanceEnableStatus"
+ "RebalanceErrorFlags"
+ "RebalanceHWBypassFETStatus"
+ "RebalanceInrushCurrentDebug"
+ "RebalanceNotRebalancingReason"
+ "RebalanceOutputStruct"
+ "RebalanceTimeSeconds"
+ "ShelfLifeModeAutoEntry"
+ "ShelfLifeModeExitCounters"
+ "failed to read pack count (%#x: %s)\n"
+ "site.AppleSmartBatteryBank*"
+ "site.AppleSmartBatteryCell"
+ "site.AppleSmartBatteryCell*"
- "1111211"
- "12111112122212121121222212"
- "1211111212221212121111111111111111111111112122121221121111112111122121211222"
- "1211111212221212121211111211211112122212"
- "222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212222122221222212"
- "AppleSmartBatteryLPEM"
- "AppleSmartBatteryLPEM.cpp"
- "AppleSmartBatteryLPEM: DBG: WriteSMCKey attempt %lu/%u"
- "AppleSmartBatteryLPEM: failed to write key '%c%c%c%c' rc:%u=%s\n"
- "AppleSmartBatteryLPEM: failed to write key '%c%c%c%c', retry:%zu\n"
- "AppleSmartBatteryPack: ID: %d Set DOFU:%llu\n"
- "BatteryInstalled=%u cells:%zu\n"
- "Failed to instantiate PPM node\n"
- "Fetched new PPM Params Dict\n"
- "ResistanceUpdatedDisabledCount"
- "UISoc"
- "failed to enable Carrier Mode(%d) %x=%s\n"
- "failed to set Carrier Mode lower limit(%d) %x=%s\n"
- "failed to set Carrier Mode lower voltage(%d) %x=%s\n"
- "failed to set Carrier Mode upper limit(%d) %x=%s\n"
- "failed to set Carrier Mode upper voltage(%d) %x=%s\n"
- "site.AppleSmartBatteryLPEM"
- "site.smcToRegistry*"
```
