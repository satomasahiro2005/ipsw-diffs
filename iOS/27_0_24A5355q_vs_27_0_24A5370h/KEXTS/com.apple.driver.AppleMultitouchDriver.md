## com.apple.driver.AppleMultitouchDriver

> `com.apple.driver.AppleMultitouchDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x6a0` | **`+0x6a0`** |
| `__TEXT_EXEC.__text` | `0x1ccf8` | `0x1ccc0` | **`-0x38`** |
| `__TEXT.__const` | `0x1b8` | `0x1a8` | **`-0x10`** |

### Other Changes

```diff

-9170.34.1.0.0
+10100.39.0.0.0
Functions:
~ __ZN37AppleMultitouchCriticalErrorsReporter15_createReporterEv : 576 -> 568
~ sub_fffffff00921874c -> sub_fffffff00924f5c4 : 112 -> 108
~ __ZN21AppleMultitouchDevice17_handleTouchFrameEPhPjP31AppleMultitouchDeviceUserClient : 1716 -> 1708
~ __ZN21AppleMultitouchDevice27_initializeCachedReportInfoEv : 312 -> 316
~ __ZN21AppleMultitouchDevice15driverLogStringEP8OSObjectPKcz : 352 -> 356
~ __ZN25AppleMultitouchPowerStats16_createReportersEv : 1040 -> 1020
~ __ZN25AppleMultitouchPowerStats16_parseDescriptorEv : 1412 -> 1404
~ __ZN25AppleMultitouchPowerStats12updateReportEv : 1016 -> 996
~ __ZN17AMDOpaqueReporter15parseDescriptorEP12OSDictionary : 2020 -> 2032
~ __ZN20AMDNonOpaqueReporter15parseDescriptorEP12OSDictionary : 1396 -> 1408
~ __ZN20AMDNonOpaqueReporter12updateReportEP21AppleMultitouchDevice : 804 -> 796
~ sub_fffffff009234bec -> sub_fffffff00926ba40 : 128 -> 124
~ __ZN18AMDReporterManager15configureReportEP19IOReportChannelListjPvS2_ : 148 -> 144
~ __ZN18AMDReporterManager12updateReportEP19IOReportChannelListjPvS2_ : 140 -> 136
```
