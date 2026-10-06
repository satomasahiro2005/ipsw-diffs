## AirPlaySupport

> `/System/Library/PrivateFrameworks/AirPlaySupport.framework/AirPlaySupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc8b10` | `0xc9dd8` | **`+0x12c8`** |
| `__TEXT.__cstring` | `0x32d95` | `0x33138` | **`+0x3a3`** |
| `__DATA_CONST.__const` | `0x2ef8` | `0x3010` | **`+0x118`** |
| `__TEXT.__oslogstring` | `0x1d6` | `0x252` | **`+0x7c`** |
| `__AUTH_CONST.__cfstring` | `0x7060` | `0x70a0` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x3c50` | `0x3c68` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1dc0` | `0x1dd8` | **`+0x18`** |
| `__DATA.__bss` | `0xc20` | `0xc30` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x5c8` | `0x5b8` | **`-0x10`** |
| `__TEXT.__const` | `0xf08` | `0xf18` | **`+0x10`** |

### Other Changes

```diff

-980.58.1.11.1
+980.63.2.0.0

-  Functions: 2606
-  Symbols:   4948
-  CStrings:  4410
+  Functions: 2614
+  Symbols:   4958
+  CStrings:  4431
Symbols:
+ GCC_except_table1155
+ GCC_except_table1180
+ GCC_except_table1181
+ GCC_except_table1187
+ GCC_except_table1302
+ GCC_except_table1468
+ GCC_except_table1596
+ GCC_except_table1600
+ GCC_except_table1792
+ GCC_except_table1795
+ GCC_except_table1798
+ GCC_except_table1802
+ GCC_except_table1963
+ GCC_except_table2211
+ GCC_except_table2517
+ GCC_except_table2526
+ GCC_except_table2582
+ GCC_except_table2585
+ GCC_except_table2586
+ GCC_except_table552
+ GCC_except_table589
+ GCC_except_table974
+ _APSAdaptiveLatencyManagerCopyLatencyAnalyzer
+ _APSAdaptiveLatencyManagerUpdateTLOVAREstimateMs
+ _APSRTCPCCFBProcessorResetSendWindowRetransmissionRate
+ _APSRTCPCCFBProcessorTick
+ ___metricCollector_roundMetricsForPrivacyInternal_block_invoke
+ ___metricCollector_roundMetricsForPrivacyInternal_block_invoke_2
+ _hoseControllerAPAT_ResetRetransmissionRate
+ _kAPSAudioProtocolDriverReceiverProperty_RedundancyLevelHistogram
+ _kAPSAudioProtocolDriverReceiverProperty_RedundancyLevelHistogramCount
+ _kRoundingReportingKeys
+ _metricCollector_roundMetricsForPrivacyInternal
+ _metricCollector_roundMetricsForPrivacyInternal.sOnce
+ _metricCollector_roundMetricsForPrivacyInternal.sRoundingMap
+ _rtcpCCFBProcessor_updatePacketSendInfo
- GCC_except_table1152
- GCC_except_table1177
- GCC_except_table1178
- GCC_except_table1184
- GCC_except_table1299
- GCC_except_table1464
- GCC_except_table1594
- GCC_except_table1598
- GCC_except_table1790
- GCC_except_table1793
- GCC_except_table1796
- GCC_except_table1800
- GCC_except_table1960
- GCC_except_table2206
- GCC_except_table2507
- GCC_except_table2521
- GCC_except_table2574
- GCC_except_table2577
- GCC_except_table2578
- GCC_except_table549
- GCC_except_table586
- GCC_except_table971
- ___senderSupportsAirPlay1080p_block_invoke
- _senderSupportsAirPlay1080p.drivers
- _senderSupportsAirPlay1080p.once
- _senderSupportsAirPlay1080p.result
CStrings:
+ "%@ BusyNodeCount (%3d) BufferedMSecs (%4lld) %s\n"
+ "%@ Creating Audio HoseAU\n"
+ "%@ Creating streaming audio renderer"
+ "%@ Streaming audio renderer created [%{ptr}]"
+ "APSAdaptiveLatencyManagerCopyLatencyAnalyzer"
+ "APSAdaptiveLatencyManagerUpdateTLOVAREstimateMs"
+ "APSAudioProtocolDriverReceiverProperty_RedundancyLevelHistogram"
+ "APSAudioProtocolDriverReceiverProperty_RedundancyLevelHistogramCount"
+ "APSRTCPCCFBProcessorResetSendWindowRetransmissionRate"
+ "APSRTCPCCFBProcessorTick"
+ "APSSAR Streaming Audio Renderer Create"
+ "Error: %d"
+ "Failed to allocate rounding map"
+ "Failed to populate rounding map"
+ "HoseAU Audio Session Init"
+ "HoseAU Audio Unit Start"
+ "HoseAU Initialize Graph"
+ "No rounding map exists"
+ "OSStatus metricCollector_roundMetricsForPrivacyInternal(CFMutableDictionaryRef)"
+ "OSStatus metricCollector_roundMetricsForPrivacyInternal(CFMutableDictionaryRef)_block_invoke"
+ "ProcessLatencyReport endpointID: %@ inIsSessionReport: %s networkLatencyMs: %u prevMaxNetworkLatencyMs: %u outOfBoundsCount: %.0lf duringInitialRamp: %s tloVarEstimateMs: %llu"
+ "[%{ptr}] Failed to update LatencyManager TLOVAR estimate with err %d"
+ "metricCollector_roundMetricsForPrivacyInternal"
+ "metricCollector_roundMetricsForPrivacyInternal_block_invoke"
+ "metricCollector_roundMetricsForPrivacyInternal_block_invoke_2"
- "%@ BusyNodeCount (%3u) BufferedMSecs (%4llu) %s\n"
- "AppleAVE2Driver"
- "AppleAVEDriver"
- "ProcessLatencyReport endpointID: %@ inIsSessionReport: %s networkLatencyMs: %u outOfBoundsCount: %.0lf duringInitialRamp: %s"
```
