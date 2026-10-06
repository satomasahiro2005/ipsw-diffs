## NPTKit

> `/System/Library/PrivateFrameworks/NPTKit.framework/NPTKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51d98` | `0x5214c` | **`+0x3b4`** |
| `__TEXT.__cstring` | `0x3e09` | `0x3f79` | **`+0x170`** |
| `__AUTH_CONST.__cfstring` | `0x6520` | `0x6680` | **`+0x160`** |
| `__DATA_CONST.__objc_selrefs` | `0x35e0` | `0x3600` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x2e8` | `0x300` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xc58` | `0xc70` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xc98` | `0xcb0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x9d8` | `0x9e0` | **`+0x8`** |

### Other Changes

```diff

-202.14.0.0.0
+202.18.0.0.0

-  Symbols:   2883
-  CStrings:  1008
+  Symbols:   2887
+  CStrings:  1019
Symbols:
+ _NPTAdditionalMetadataKey_DownloadBackgrounded
+ _NPTAdditionalMetadataKey_PingBackgrounded
+ _NPTAdditionalMetadataKey_UploadBackgrounded
+ _nw_path_monitor_cancel
Functions:
~ -[NPTCellularCollector dealloc] : 84 -> 132
~ -[NPTCellularCollector wrmBasebandMetrics] : 1140 -> 1136
~ ___43-[NPTCellularCollector getCellInfoForSlot:]_block_invoke : 376 -> 372
~ -[NPTCellularCollector stopCollecting] : 184 -> 244
~ +[NPTCellularCollector getPreferredDataSlot] : 580 -> 576
~ -[NPTCellularCollector setUpPathMonitor:] : 212 -> 272
~ +[NPTCellularCollector calculateMaxCellularTPutEstimates:] : 776 -> 772
~ -[NPTUpload startTasks] : 288 -> 284
~ -[NPTUpload realTimeSpeedMetricOverall] : 444 -> 440
~ -[NPTUpload aggregateResults] : 2696 -> 2664
~ -[NPTUpload finishedAllTasks] : 304 -> 300
~ -[NPTUpload cleanUp] : 312 -> 308
~ -[CWFAutoJoinStatus(Dictionary) dictionary] : 824 -> 820
~ -[W5BluetoothStatus(Strings) dictionary] : 884 -> 880
~ -[NPTPerformanceTest metadata] : 1024 -> 1020
~ -[NPTPerformanceTest getFlattenedMetadataDictionary:] : 412 -> 408
~ -[NPTPerformanceTest getFlattenedDictionary] : 4416 -> 5112
~ -[NPTPerformanceTest getTransformedDataForCoreAnalytics] : 784 -> 780
~ ___49-[NPTVPNCollector startCollectingWithCompletion:]_block_invoke_2 : 1320 -> 1316
~ -[NPTDownload startTasks] : 288 -> 284
~ -[NPTDownload realTimeSpeedMetricOverall] : 444 -> 440
~ -[NPTDownload aggregateResults] : 2696 -> 2664
~ -[NPTDownload finishedAllTasks] : 304 -> 300
~ -[NPTPingResult populateFields] : 680 -> 676
~ -[NPTPingResult calculateStandardDeviation] : 420 -> 416
~ -[NPTPingResult asDictionary] : 904 -> 900
~ ___54-[NPTCDNDebugCollector startCollectingWithCompletion:]_block_invoke : 632 -> 628
~ +[NPTWiFiCollector convertPowerStateToString:] : 176 -> 172
~ +[NPTMetadataCollector fetch] : 944 -> 1128
~ -[NPTMetadataCollector initWithCollectorTypes:] : 404 -> 400
~ ___54-[NPTMetadataCollector startCollectingWithCompletion:]_block_invoke : 1448 -> 1436
~ ___54-[NPTMetadataCollector startCollectingWithCompletion:]_block_invoke.91 -> ___54-[NPTMetadataCollector startCollectingWithCompletion:]_block_invoke.103 : 836 -> 832
~ ___38-[NPTMetadataCollector stopCollecting]_block_invoke : 292 -> 288
~ +[AWDNetworkPerformanceMetricInitializer createPerformanceMetricFromDictionary:] : 18540 -> 18536
~ sub_28aedfb64 -> sub_28c4aaec8 : 420 -> 416
~ sub_28aee9be4 -> sub_28c4b4f44 : 5456 -> 5476
~ sub_28aeeb134 -> sub_28c4b64a8 : 372 -> 380
~ sub_28aeedc60 -> sub_28c4b8fdc : 280 -> 276
~ sub_28aeee7ec -> sub_28c4b9b64 : 256 -> 264
~ sub_28aeee8ec -> sub_28c4b9c6c : 256 -> 276
~ sub_28aeee9ec -> sub_28c4b9d80 : 244 -> 268
~ ___swift_closure_destructorTm : 140 -> 148
CStrings:
+ "INSTANT_PHY_ACTIVE_DURATION_ELNA_HP"
+ "INSTANT_PHY_ACTIVE_DURATION_TOTAL"
+ "download_backgrounded"
+ "elna_highPower_download_duration_percentage"
+ "elna_highPower_upload_duration_percentage"
+ "elna_lowPower_download_duration_percentage"
+ "elna_lowPower_duration_upload_percentage"
+ "ping_backgrounded"
+ "upload_backgrounded"
+ "wifi_phy_active_duration_elna_hp"
+ "wifi_phy_active_duration_total"
```
