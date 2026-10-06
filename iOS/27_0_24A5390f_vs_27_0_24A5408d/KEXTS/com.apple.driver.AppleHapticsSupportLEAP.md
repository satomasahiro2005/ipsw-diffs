## com.apple.driver.AppleHapticsSupportLEAP

> `com.apple.driver.AppleHapticsSupportLEAP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x7aa0` | `0x7440` | **`-0x660`** |
| `__TEXT_EXEC.__text` | `0x3b780` | `0x3b8d8` | **`+0x158`** |
| `__TEXT.__cstring` | `0x78b7` | `0x7811` | **`-0xa6`** |
| `__TEXT.__os_log` | `0x985` | `0x9e6` | **`+0x61`** |

### Other Changes

```diff

-11.4.0.0.0
+11.6.0.0.0

-  CStrings:  1300
+  CStrings:  1299
CStrings:
+ "12121122212111111121222222"
+ "1222221"
+ "AHSTemperaturePowerSMCReporter::%s SMC sensor-exchange unavailable; SMC thermal writes disabled\n"
+ "AppleHapticsSupportTemperatureReporter"
+ "failed to create HID temperature reporter"
+ "failed to create SMC thermal reporter"
+ "initReporter"
- "1211111212221212111111121212222221"
- "121211222121111112122222"
- "AHSTemperaturePowerSMCReporter::%s Failed to find SMC driver!\n"
- "AHSTemperaturePowerSMCReporter::%s SMC driver not available!\n"
- "AppleHapticsSupportTemperaturePowerSMCReporter"
- "failed to create temperature power SMC reporter"
- "initTemperaturePowerSMCReporter"
- "writeSensorDataToSMC"
```
