## com.apple.driver.AppleBluetoothDebug

> `com.apple.driver.AppleBluetoothDebug`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x440` | **`+0x440`** |
| `__TEXT_EXEC.__text` | `0xa268` | `0xa3f4` | **`+0x18c`** |

### Other Changes

```text
Functions:
~ __ZN7BTDebug5startEP9IOService : 2140 -> 2144
~ sub_fffffff0089ac528 -> sub_fffffff0089c037c : 1164 -> 1240
~ __ZN7BTDebug26initCoreCaptureForLogFlowsEv : 1580 -> 1652
~ __ZN7BTDebug18enableLoggingGatedEjjPK13LogFlowParamsj : 1576 -> 1684
~ __ZN7BTDebug21enableLoggingInternalEv : 1696 -> 1760
~ __ZN7BTDebug22disableLoggingInternalEv : 588 -> 616
~ __ZN7BTDebug16readLogsCompleteEPviPN14BTDebugService7LogDataEj : 1640 -> 1684
~ sub_fffffff0089b3a50 -> sub_fffffff0089c7a2c : 368 -> 376
~ __ZN15BTDebugReporter12addReportersEP9IOServiceP14IOReportLegend : 1208 -> 1196
~ sub_fffffff0089b4108 -> sub_fffffff0089c80e0 : 44 -> 40
~ sub_fffffff0089b5008 -> sub_fffffff0089c8fdc : 116 -> 124
```
