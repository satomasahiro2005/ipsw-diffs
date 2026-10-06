## NPTKit

> `/System/Library/PrivateFrameworks/NPTKit.framework/NPTKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5214c` | `0x52ce4` | **`+0xb98`** |
| `__AUTH_CONST.__objc_const` | `0xc010` | `0xc0c0` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x4b7c` | `0x4bd4` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x3600` | `0x3648` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x6680` | `0x66c0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3f79` | `0x3fb9` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x9e0` | `0xa00` | **`+0x20`** |
| `__DATA.__data` | `0x6b0` | `0x6d0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xd60` | `0xd80` | **`+0x20`** |
| `__TEXT.__const` | `0x650` | `0x668` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x748` | `0x75c` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x388` | `0x390` | **`+0x8`** |

### Other Changes

```diff

-202.18.0.0.0
+202.21.0.0.0

-  Functions: 2011
-  Symbols:   2887
-  CStrings:  1019
+  Functions: 2021
+  Symbols:   2904
+  CStrings:  1021
Symbols:
+ +[NPTPerformanceTestConfiguration isWiFiAvailable]
+ -[NPTDownload accumulateInterfaceBytesFromMetrics:]
+ -[NPTDownload cellularFallbackPercentageForFileSize:]
+ -[NPTMetricResult cellularFallbackPercentage]
+ -[NPTMetricResult setCellularFallbackPercentage:]
+ -[NPTUpload accumulateInterfaceBytesFromMetrics:]
+ -[NPTUpload cellularFallbackPercentageForFileSize:]
+ _OBJC_IVAR_$_NPTDownload.cellularBytesReceived
+ _OBJC_IVAR_$_NPTDownload.wifiObserved
+ _OBJC_IVAR_$_NPTMetricResult._cellularFallbackPercentage
+ _OBJC_IVAR_$_NPTUpload.cellularBytesSent
+ _OBJC_IVAR_$_NPTUpload.wifiObserved
+ _RPOptionStatusFlags
+ _nw_data_transfer_report_copy_path_interface
+ _nw_data_transfer_report_get_path_count
+ _nw_data_transfer_report_get_received_application_byte_count
+ _nw_data_transfer_report_get_sent_application_byte_count
CStrings:
+ "cellularFallbackPercentage"
+ "cellular_fallback_percentage"
+ "\xf0\xa1"
+ "\xf0\xb1"
- "\xf0\x81"
- "\xf0\x91"
```
