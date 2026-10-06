## MetricKitServices

> `/System/Library/PrivateFrameworks/MetricKitServices.framework/MetricKitServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xae0c` | `0xadd4` | **`-0x38`** |
| `__AUTH_CONST.__auth_got` | `0x430` | `0x438` | **`+0x8`** |

### Other Changes

```diff

-353.0.0.0.0
+356.0.0.0.0

-  Symbols:   434
+  Symbols:   435
Symbols:
+ _objc_retain_x23
Functions:
~ -[MXHangTracerService unarchiveHangTracerDataForDateString:] : 1288 -> 1280
~ -[MXHangTracerService getDiagnosticsForClient:dateString:] : 852 -> 844
~ -[MXPowerlogService getMetricsForClient:] : 720 -> 716
~ -[MXPowerlogService unarchivePowerlogData] : 1624 -> 1644
~ -[MXReportCrashService unarchiveReportCrashDataForDateString:] : 1652 -> 1648
~ -[MXReportCrashService getDiagnosticsForClient:dateString:] : 852 -> 844
~ -[MXService pruneSourceData:] : 1096 -> 1092
~ -[MXSpaceAttributionService unarchiveSpaceAttributionData] : 1004 -> 1008
~ -[MXSpaceAttributionService getMetricsForClient:] : 720 -> 716
~ -[MXSpinTracerService unarchiveSpinTracerDataForDateString:] : 1288 -> 1280
~ -[MXSpinTracerService getDiagnosticsForClient:dateString:] : 852 -> 844
~ sub_287f7602c -> sub_289bf200c : 956 -> 932
```
