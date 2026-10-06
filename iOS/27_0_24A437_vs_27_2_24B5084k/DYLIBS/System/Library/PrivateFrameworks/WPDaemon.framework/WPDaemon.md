## WPDaemon

> `/System/Library/PrivateFrameworks/WPDaemon.framework/WPDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5e514` | `0x5fd64` | **`+0x1850`** |
| `__AUTH_CONST.__cfstring` | `0x3860` | `0x3a00` | **`+0x1a0`** |
| `__AUTH_CONST.__objc_const` | `0x8a88` | `0x8b98` | **`+0x110`** |
| `__TEXT.__cstring` | `0x4a6d` | `0x4b73` | **`+0x106`** |
| `__AUTH_CONST.__const` | `0x6e08` | `0x6f08` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x45a4` | `0x4654` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x28b0` | `0x2938` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x2060` | `0x20c8` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0xaf97` | `0xafe0` | **`+0x49`** |
| `__TEXT.__gcc_except_tab` | `0x1294` | `0x12cc` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x510` | `0x540` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x12f8` | `0x1320` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x578` | `0x598` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x180` | `0x198` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x4b8` | `0x4c8` | **`+0x10`** |
| `__DATA.__bss` | `0x4` | `0xc` | **`+0x8`** |

### Other Changes

```diff

-2700.51.1.3.0
+2701.3.0.0.0

-  Functions: 3595
-  Symbols:   2974
-  CStrings:  1559
+  Functions: 3636
+  Symbols:   3011
+  CStrings:  1576
Symbols:
+ +[LeAdvertisingMetric getAdvReportDictFromXPC:]
+ -[LeAdvertisingMetric getAdvReportMetricCBv1]
+ -[LeAdvertisingMetric getAdvReportTimestamps]
+ -[LeAdvertisingMetric getAdvReportXPCRepresentation]
+ -[LeAdvertisingMetric setAdvReportTimestamps:]
+ -[LeAdvertisingMetric setDaemonXPCSendAt]
+ -[LeAdvertisingMetric setGapRxAt:]
+ -[LeAdvertisingMetric setHciRxAt:]
+ -[LeAdvertisingMetric setObserverRxAt]
+ -[LeAdvertisingMetric setPreNotifyAt]
+ -[LeAdvertisingMetric setScanMgrRxAt]
+ -[LeAdvertisingMetric setWPDClientAt]
+ -[WPDClient advReportMetricSet]
+ -[WPDClient setAdvReportMetricSet:]
+ -[WPDStatsManager sendStatsToCoreAnalytics:stats:]
+ GCC_except_table30
+ GCC_except_table43
+ _CBAdvReportMetricHeySiri
+ _OBJC_IVAR_$_LeAdvertisingMetric.daemonXPCSendAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.gapRxAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.hciRxAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.observerRxAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.preNotifyAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.scanMgrRxAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.wpdClientAt
+ _OBJC_IVAR_$_WPDClient._advReportMetricSet
+ ___32-[WPDStatsManager reportPLStats]_block_invoke_3
+ ___45-[LeAdvertisingMetric getAdvReportMetricCBv1]_block_invoke
+ ___47+[LeAdvertisingMetric getAdvReportDictFromXPC:]_block_invoke
+ ___50-[WPDStatsManager sendStatsToCoreAnalytics:stats:]_block_invoke
+ ___50-[WPDStatsManager sendStatsToCoreAnalytics:stats:]_block_invoke_2
+ ___block_descriptor_56_e8_32r_e37_B24?0r*8"NSObject<OS_xpc_object>"16lr32l8
+ __xpc_type_dictionary
+ _objc_release_x10
+ _reportPLStats.onceToken
+ _xpc_dictionary_apply
+ _xpc_dictionary_get_count
+ _xpc_dictionary_set_uint64
+ _xpc_get_type
+ _xpc_uint64_get_value
- GCC_except_table33
- GCC_except_table35
- ___sendWPStatsToCoreAnalytics_block_invoke
CStrings:
+ "B24@?0r*8@\"NSObject<OS_xpc_object>\"16"
+ "DaemonXPCToScanMgr"
+ "GapRxToObserver"
+ "GapToObserver"
+ "HCIToGap"
+ "HeySiriAdvReportDurationWiProx"
+ "ObserverToPreNotify"
+ "PreNotifyToDaemonXPC"
+ "ScanMgrToWPDClient"
+ "W!f$"
+ "WPDaemon iOS 27.2 (24B5083s) (WirelessProximity-2701.3) (Release) built on 2026-09-05 05:41:45"
+ "[LeAdvMetric] getAdvReportMetricCBv1 (ms) %@"
+ "[LeAdvMetric] inXPC not a dict"
+ "com.apple.Bluetooth.%@"
+ "daemonXPCSendAt"
+ "gapRxAt"
+ "hciRxAt"
+ "observerRxAt"
+ "preNotifyAt"
+ "scanMgrRxAt"
+ "wpdClientAt"
- "%@%@"
- "W!f#"
- "WPDaemon iOS 27.0 (24A425) (WirelessProximity-2700.51.1.3) (Release) built on 2026-08-21 20:41:23"
- "com.apple.Bluetooth."
```
