## com.apple.driver.ApplePPMCPMS

> `com.apple.driver.ApplePPMCPMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x548f0` | `0x54bf4` | **`+0x304`** |
| `__TEXT.__os_log` | `0x3e7e` | `0x3f85` | **`+0x107`** |
| `__TEXT.__cstring` | `0xf8a2` | `0xf907` | **`+0x65`** |
| `__DATA_CONST.__const` | `0x5b20` | `0x5b70` | **`+0x50`** |

### Other Changes

```diff

-1191.40.25.0.0
-  Functions: 2176
+1191.40.27.0.1
+  Functions: 2185

-  CStrings:  1858
+  CStrings:  1866
CStrings:
+ "%s::%s:failed to get array entry from key gPPMBatteryKey_Soc1Vcut\n"
+ "%s::%s:failed to get number from key gPPMBatteryKey_AlgoTemperature\n"
+ "%s::%s:failed to get number from key gPPMBatteryKey_Soc1Vcut\n"
+ "%s::%s:function-btm-vthr callFunction failed with error 0x%08x\n\n"
+ "12222112222222222112222222222222222222222222222222222221111222222122112"
+ "12222112222222222112222222222222222222222222222222222221111222222122112111212211122212222222211"
+ "OverrideSoc1Voltage"
+ "UseOverrideSoc1Voltage"
+ "getTemperatureFromBatteryDict"
+ "updatePMUVoltageThreshold"
- "1222211222222222211222222222222222222222222222222222221111222222122112"
- "1222211222222222211222222222222222222222222222222222221111222222122112111212211122212222222211"
```
