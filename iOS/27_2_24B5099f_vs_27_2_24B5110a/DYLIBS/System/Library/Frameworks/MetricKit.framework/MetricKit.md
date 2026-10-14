## MetricKit

> `/System/Library/Frameworks/MetricKit.framework/MetricKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x86524` | `0x86dd0` | **`+0x8ac`** |
| `__TEXT.__cstring` | `0x1ed2` | `0x1f82` | **`+0xb0`** |
| `__AUTH_CONST.__const` | `0x4681` | `0x4719` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0x1ba0` | `0x1c00` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x1938` | `0x1990` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0xa20` | `0xa58` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x67f0` | `0x6820` | **`+0x30`** |
| `__TEXT.__const` | `0x94b6` | `0x94e6` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x290c` | `0x293c` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x148` | `0x170` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1220` | `0x1240` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2570` | `0x2590` | **`+0x20`** |
| `__DATA.__data` | `0x13c0` | `0x13d0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x43c` | `0x440` | **`+0x4`** |

### Other Changes

```diff

-369.40.1.0.0
+369.40.2.0.0

-  Functions: 3495
-  Symbols:   2461
-  CStrings:  355
+  Functions: 3509
+  Symbols:   2482
+  CStrings:  360
Symbols:
+ -[MXMetricManager _memoryExceptionDiagnosticCountForPayloads:]
+ -[MXMetricManager _reportMemoryDiagnosticsDeliveredForPayloads:]
+ -[MXMetricManager setStateAware:]
+ -[MXMetricManager stateAware]
+ _OBJC_IVAR_$_MXMetricManager._stateAware
+ __Block_copy
+ __Block_release
+ ___33-[MXMetricManager addSubscriber:]_block_invoke_2
+ ___64-[MXMetricManager _reportMemoryDiagnosticsDeliveredForPayloads:]_block_invoke
+ ___block_descriptor_40_e8_32s_e19_"NSDictionary"8?0ls32l8
+ ___swift_closure_destructor
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _swift_deallocObject
+ _swift_initStackObject
+ _swift_retain_x2
+ _symbolic SDySSSo8NSObjectCGIego_
+ _symbolic SS_So8NSObjectCt
+ _symbolic _____ySSSo8NSObjectCG s18_DictionaryStorageC
+ _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
CStrings:
+ "com.apple.metrickit.legacyManagerAdopted"
+ "com.apple.metrickit.memoryDiagnosticsDelivered"
+ "com.apple.metrickit.swiftManagerAdopted"
+ "stateReportingDomainCount"
+ "unknown"
```
