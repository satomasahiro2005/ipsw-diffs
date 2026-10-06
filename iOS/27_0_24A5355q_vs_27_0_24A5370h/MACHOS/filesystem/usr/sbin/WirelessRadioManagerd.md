## WirelessRadioManagerd

> `/usr/sbin/WirelessRadioManagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x170234` | `0x1709e4` | **`+0x7b0`** |
| `__TEXT.__cstring` | `0x598ad` | `0x59bf8` | **`+0x34b`** |
| `__DATA_CONST.__cfstring` | `0x32b20` | `0x32d60` | **`+0x240`** |
| `__TEXT.__objc_methname` | `0x344b6` | `0x34567` | **`+0xb1`** |
| `__DATA_CONST.__const` | `0x5800` | `0x5858` | **`+0x58`** |
| `__TEXT.__objc_methtype` | `0x8ab4` | `0x8b0c` | **`+0x58`** |
| `__DATA.__objc_const` | `0x1ced8` | `0x1cf18` | **`+0x40`** |
| `__DATA_CONST.__objc_dictobj` | `0x820` | `0x848` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x215e0` | `0x21600` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x6328` | `0x6344` | **`+0x1c`** |
| `__DATA_CONST.__objc_arraydata` | `0x10100` | `0x10110` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x26d0` | `0x26e0` | **`+0x10`** |
| `__TEXT.__const` | `0x11df8` | `0x11e08` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1e74` | `0x1e7c` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x9fe8` | `0x9ff0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1380` | `0x1388` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x11b3c` | `0x11b44` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1930.3.0.0.0
+1933.0.0.0.0

-  Functions: 7788
-  Symbols:   872
-  CStrings:  16822
+  Functions: 7793
+  Symbols:   873
+  CStrings:  16846
Symbols:
+ _CFAbsoluteTimeGetCurrent
CStrings:
+ "BTCS_ %s B18: no BT channel masking"
+ "BTCS_ %s B20: no BT channel masking"
+ "BTCS_ %s B40A (UL<=2370): blocking BT channels 0-19"
+ "BTCS_ %s B40B (UL>2370): blocking BT channels 0-29"
+ "BTCS_ %s B41: blocking BT channels 59-78"
+ "BTCS_ %s B7: no BT channel masking"
+ "BTCS_ No BTCS-specific rule for %s band %u, using legacy BT AFH policy table"
+ "BTCS_ Resolved RAT=%s, band=%u (ulCenter=%.1f, dlCenter=%.1f)"
+ "Coex ARI driver: Invalid SubId(%u) in enableFeatureFrameSyncForBTClkAlgn"
+ "DRIVER_AVAILABLE"
+ "DRIVER_AVAILABLE_REASON_STRING"
+ "DextCrashed"
+ "FullChipReset-"
+ "ICE IBINetRadioSignalIndCbHandle LTE cell_id = %u, earfcn=%u, pci=%u, bandwidth=%u, rssnr=%f"
+ "WiFiS: callbackWiFiDeviceClientDeviceAvailable %@"
+ "WiFiS: callbackWiFiDeviceClientDeviceAvailable Power OFF due to DextCrash"
+ "WiFiS: callbackWiFiDeviceClientDeviceAvailable Power ON due to DextCrash recovery"
+ "^{WRMMetricsCellTriggerDisconnect=d@@IIIIIIIIIIIIIIiBdBBC}16@0:8"
+ "^{WRMMetricsGenericCellularScore=dIQIdddIIIIBB}16@0:8"
+ "app: %@, cellThroughput (tx, rx): (%.2f, %.2f), wifiThroughput (tx, rx): (%.2f, %.2f)"
+ "app: %@, cellThroughputBefore (tx, rx): (%u, %u), wifiThroughputAfter (tx, rx): (%u, %u)"
+ "app: %@, rttMinAfter: %u, rttAvgAfter: %u"
+ "app: %@, rttMinBefore: %u, rttAvgBefore: %u"
+ "app: %@, rttMinBeforeAfter: (%u, %u), rttAvgBeforeAfter: (%u, %u)"
+ "appRunsForeground"
+ "com.apple.WirelessRadioManager.BwEvaluation"
+ "evaluateGenericCellularScore RRC idle historicalInfo: %d, fr2OrStrongRSRP: %d, highRate: %d, currentLocationQuality: %s, locDBBW: %d, FR1Count: %d, FR2Count: %d, RSRP: %.2f, signalQuality: %s"
+ "invalidateDiscoveryAndDeviceManager"
+ "mCachedIsWiFiCaptive"
+ "mCachedIsWiFiCaptiveExpiry"
+ "maybeSubmitCellTriggerDisconnectMetricsForApp: abc trigger due to no WiFi fallback %@"
+ "maybeSubmitCellTriggerDisconnectMetricsForApp: abc trigger due to rtt degradation %@"
+ "maybeSubmitCellTriggerDisconnectMetricsForApp: abc trigger due to rtt min, avg mismatch %@"
+ "maybeSubmitCellTriggerDisconnectMetricsForApp: abc trigger due to throughput degradation %@"
+ "maybeSubmitCellTriggerDisconnectMetricsForApp: app mismatch, metric appId: %@, current appId: %@, skip"
+ "maybeSubmitCellTriggerDisconnectMetricsForApp: buffer[%hhu], appId: %@, appRunsForeground: %s, measInterval: %.2f s, fallbacktoWifi: %s, cellThroughputBefore (tx, rx): (%u, %u), wifiThroughputAfter (tx, rx): (%u, %u) Kbps, rttMinBeforeAfter: (%u, %u), rttAvgBeforeAfter: (%u, %u), cellScoreBeforeAfter: (%s, %s), wifiScoreBeforeAfter: (%@, %@), wrmWifiScoreBeforeAfter: (%s, %s)"
+ "maybeSubmitCellTriggerDisconnectMetricsForApp:nwDeltaStatsIndex:appRunsForeground:"
+ "processSessionStatusUpdate:timeHorizon:stallDetected:fatalError:stallDuration:"
+ "redacted"
+ "updateCellTriggerDisconnectMetric: abc trigger due to rtt min, avg mismatch %@"
+ "v32@0:8@16C24B28"
+ "v56@0:8Q16Q24Q32Q40Q48"
+ "wifiPrimary"
+ "{WRMMetricsCellTriggerDisconnect=\"timestamp\"d\"applicationId\"@\"NSString\"\"protocols\"@\"NSString\"\"txThroughputBefore\"I\"rxThroughputBefore\"I\"txThroughputAfter\"I\"rxThroughputAfter\"I\"rttMinBefore\"I\"rttMinAfter\"I\"rttAvgBefore\"I\"rttAvgAfter\"I\"cellScoreBefore\"I\"cellScoreAfter\"I\"wrmWifiScoreBefore\"I\"wrmWifiScoreAfter\"I\"wifiScoreBefore\"I\"wifiScoreAfter\"I\"dataLQM\"i\"didFallbackToWiFiOnCellDisconnect\"B\"postDisconnectMeasurementInterval\"d\"appRunsForeground\"B\"metricReportPending\"B\"deferUntilAdditionalNwStatsReports\"C}"
+ "{WRMMetricsGenericCellularScore=\"timestamp\"d\"lastCellScore\"I\"lastCellScoreDuration\"Q\"currentCellScore\"I\"rsrp\"d\"rsrq\"d\"snr\"d\"dataLQM\"I\"dlConf\"I\"dlBw\"I\"rrcState\"I\"wifiPrimary\"B\"historicalInfoGood\"B}"
- "BTCS_ B40B frequency range detected (freq=[%.1f MHz, %.1f MHz]), blocking BT channels 0-19"
- "BTCS_ Not B40B, using policy table (same as regular BT AFH)"
- "BTCS_ConditionId_ BTCSConditionIdConfig: bandInfoType=0x%x, DL(%.1f~%.1f MHz), UL(%.1f~%.1f MHz), B40 range(%.1f~%.1f MHz), csEnabled=%d"
- "^{WRMMetricsCellTriggerDisconnect=d@@IIIIIIIIIIIIIIiBdBC}16@0:8"
- "^{WRMMetricsGenericCellularScore=dIQIdddIIIB}16@0:8"
- "cellThroughput (tx, rx): (%.2f, %.2f), wifiThroughput (tx, rx): (%.2f, %.2f)"
- "cellThroughputBefore (tx, rx): (%u, %u), wifiThroughputAfter (tx, rx): (%u, %u)"
- "evaluateGenericCellularScore RRC idle historicalInfo: %d, highRate: %d, currentLocationQuality: %d, locDBBW: %d, FR1Count: %d, FR2Count: %d, signalQuality: %s"
- "maybeSubmitCellTriggerDisconnectMetrics:"
- "maybeSubmitCellTriggerDisconnectMetrics: Mismatch in app category now: %@, before cell disconnect: %@"
- "maybeSubmitCellTriggerDisconnectMetrics: abc trigger due to no WiFi fallback %@"
- "maybeSubmitCellTriggerDisconnectMetrics: abc trigger due to rtt degradation %@"
- "maybeSubmitCellTriggerDisconnectMetrics: abc trigger due to rtt min, avg mismatch %@"
- "maybeSubmitCellTriggerDisconnectMetrics: abc trigger due to throughput degradation %@"
- "maybeSubmitCellTriggerDisconnectMetrics: buffer[%hhu], appId: %@, measInterval: %.2f s, fallbacktoWifi: %s, cellThroughputBefore (tx, rx): (%u, %u), wifiThroughputAfter (tx, rx): (%u, %u) Kbps, rttMinBeforeAfter: (%u, %u), rttAvgBeforeAfter: (%u, %u), cellScoreBeforeAfter: (%s, %s), wifiScoreBeforeAfter: (%@, %@), wrmWifiScoreBeforeAfter: (%s, %s)"
- "processSessionStatusUpdate:"
- "rttMinAfter: %u, rttAvgAfter: %u"
- "rttMinBefore: %u, rttAvgBefore: %u"
- "rttMinBeforeAfter: (%u, %u), rttAvgBeforeAfter: (%u, %u)"
- "{WRMMetricsCellTriggerDisconnect=\"timestamp\"d\"applicationId\"@\"NSString\"\"protocols\"@\"NSString\"\"txThroughputBefore\"I\"rxThroughputBefore\"I\"txThroughputAfter\"I\"rxThroughputAfter\"I\"rttMinBefore\"I\"rttMinAfter\"I\"rttAvgBefore\"I\"rttAvgAfter\"I\"cellScoreBefore\"I\"cellScoreAfter\"I\"wrmWifiScoreBefore\"I\"wrmWifiScoreAfter\"I\"wifiScoreBefore\"I\"wifiScoreAfter\"I\"dataLQM\"i\"didFallbackToWiFiOnCellDisconnect\"B\"postDisconnectMeasurementInterval\"d\"metricReportPending\"B\"deferUntilAdditionalNwStatsReports\"C}"
- "{WRMMetricsGenericCellularScore=\"timestamp\"d\"lastCellScore\"I\"lastCellScoreDuration\"Q\"currentCellScore\"I\"rsrp\"d\"rsrq\"d\"snr\"d\"dataLQM\"I\"dlConf\"I\"dlBw\"I\"historicalInfoGood\"B}"
```
