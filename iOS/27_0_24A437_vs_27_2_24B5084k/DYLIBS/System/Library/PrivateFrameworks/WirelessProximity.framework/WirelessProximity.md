## WirelessProximity

> `/System/Library/PrivateFrameworks/WirelessProximity.framework/WirelessProximity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32e2c` | `0x343c4` | **`+0x1598`** |
| `__AUTH_CONST.__auth_got` | `0x0` | `0x3d8` | **`+0x3d8`** |
| `__AUTH_CONST.__cfstring` | `0x2f80` | `0x3120` | **`+0x1a0`** |
| `__AUTH_CONST.__const` | `0x3728` | `0x3828` | **`+0x100`** |
| `__TEXT.__cstring` | `0x3bcb` | `0x3cb8` | **`+0xed`** |
| `__AUTH_CONST.__objc_const` | `0x3198` | `0x3278` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x2c0c` | `0x2c9c` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x1720` | `0x1788` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x15c8` | `0x1628` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x478f` | `0x47db` | **`+0x4c`** |
| `__TEXT.__gcc_except_tab` | `0x698` | `0x6d0` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x7a8` | `0x7d0` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x220` | `0x23c` | **`+0x1c`** |
| `__AUTH_CONST.__objc_intobj` | `0x1e0` | `0x1f8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1b0` | `0x1b8` | **`+0x8`** |

### Other Changes

```diff

-2700.51.1.3.0
+2701.3.0.0.0

-  Functions: 1969
-  Symbols:   1870
-  CStrings:  957
+  Functions: 2005
+  Symbols:   1902
+  CStrings:  974
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
+ _OBJC_IVAR_$_LeAdvertisingMetric.daemonXPCSendAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.gapRxAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.hciRxAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.observerRxAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.preNotifyAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.scanMgrRxAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.wpdClientAt
+ ___45-[LeAdvertisingMetric getAdvReportMetricCBv1]_block_invoke
+ ___47+[LeAdvertisingMetric getAdvReportDictFromXPC:]_block_invoke
+ ___block_descriptor_56_e8_32r_e37_B24?0r*8"NSObject<OS_xpc_object>"16lr32l8
+ ___chkstk_darwin
+ __xpc_type_dictionary
+ _bzero
+ _objc_release_x10
+ _xpc_dictionary_apply
+ _xpc_dictionary_create
+ _xpc_dictionary_get_count
+ _xpc_dictionary_set_uint64
+ _xpc_get_type
+ _xpc_uint64_get_value
CStrings:
+ "B24@?0r*8@\"NSObject<OS_xpc_object>\"16"
+ "DaemonXPCToScanMgr"
+ "GapRxToObserver"
+ "GapToObserver"
+ "HCIToGap"
+ "ObserverToPreNotify"
+ "PreNotifyToDaemonXPC"
+ "ScanMgrToWPDClient"
+ "[LeAdvMetric] getAdvReportMetricCBv1 (ms) %@"
+ "[LeAdvMetric] inXPC not a dict"
+ "daemonXPCSendAt"
+ "gapRxAt"
+ "hciRxAt"
+ "observerRxAt"
+ "preNotifyAt"
+ "scanMgrRxAt"
+ "wpdClientAt"
```
