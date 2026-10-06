## WirelessRadioManagerd

> `/usr/sbin/WirelessRadioManagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x59bf8` | `0x59fd1` | **`+0x3d9`** |
| `__TEXT.__text` | `0x1709e4` | `0x170d3c` | **`+0x358`** |
| `__DATA_CONST.__cfstring` | `0x32d60` | `0x32e80` | **`+0x120`** |
| `__DATA_CONST.__got` | `0x7b8` | `0x8b0` | **`+0xf8`** |
| `__TEXT.__objc_stubs` | `0x21600` | `0x216e0` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x34567` | `0x34630` | **`+0xc9`** |
| `__TEXT.__objc_methlist` | `0x11b44` | `0x11bdc` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x5088` | `0x50e8` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x9ff0` | `0xa028` | **`+0x38`** |
| `__DATA_CONST.__objc_arraydata` | `0x10110` | `0x10130` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x6344` | `0x6364` | **`+0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0x6768` | `0x6780` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x8b0c` | `0x8afe` | **`-0xe`** |
| `__DATA.__bss` | `0x7d8` | `0x7e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-1933.0.0.0.0
+1935.2.0.0.0

-  Functions: 7793
+  Functions: 7805

-  CStrings:  16846
+  CStrings:  16861
CStrings:
+ "AFH needs update to %@ (force=%d changed=%d)"
+ "BTCS_ %s B40B (UL>2370): blocking BT channels 0-19"
+ "BTCS_ %s B7: blocking BT channels 0-19"
+ "BTCS_ AFH needs update to %@ (force=%d changed=%d)"
+ "BTCS_EPA_ EPA disallowed needs update from %d to %d (force=%d changed=%d)"
+ "ConfigureWCI2 mode : RX=%lld, TX=%lld (force=%d changed=%d)"
+ "DLDebug_ BLE AFH newBLEMap_BitVector needs update to %@ (force=%d changed=%d)"
+ "HFAFHDebug_ Channel map needs update (force=%d changed=%d)"
+ "ICE IBINetRadioSignalIndCbHandle serving cell is LTE, skipping setServingCellRSRP/RSRQ from IBI_RAT_NR (NR RSRP %.1f RSRQ %.1f stored in nrCellRSRP/RSRQ only)"
+ "LTEWiFiTimeSharingBand41Ch1013"
+ "QMI.NAS.%d: serving cell is LTE, skipping setServingCellRSRP from NrSigInfo (NR RSRP %.1f stored in nrCellRSRP only)"
+ "QMI.NAS.%d: serving cell is LTE, skipping setServingCellRSRQ from NrSigInfoExt (NR RSRQ %.1f stored in nrCellRSRQ only)"
+ "Setting BT Agc Rx Coex Gain Mode %d (force=%d changed=%d)"
+ "Snapshot from buffer[%d] for app: %@, uses: %s, on: %s, activeDataSnapshotCount: %u, txRate: %.2f, rxRate: %.2f kbps, rx_dupe: %llu, re-tx: %llu, rx_ooo: %llu, rtt_min: %.2f, rtt_avg: %.2f ms"
+ "T@\"NSArray\",C,V_mAWDLChannelSequence"
+ "T@\"NSArray\",C,V_mNANMap0"
+ "T@\"NSArray\",C,V_mNANMap1"
+ "WCM_Session handling Stewie test inject, active=%d"
+ "app: %@, cellThroughput (tx, rx): (%.2f, %.2f), wifiThroughput (tx, rx): (%.2f, %.2f) Kbps"
+ "app: %@, cellThroughputBefore (tx, rx): (%u, %u), wifiThroughputAfter (tx, rx): (%u, %u) Kbps"
+ "app: %@, rttMinAfter: %u, rttAvgAfter: %u ms"
+ "app: %@, rttMinBefore: %u, rttAvgBefore: %u ms"
+ "app: %@, rttMinBeforeAfter: (%u, %u), rttAvgBeforeAfter: (%u, %u) ms"
+ "b26"
+ "handleWiFiLinkDown"
+ "handleWiFiLinkDown reset cooldown timer, allowing new disconnect requests"
+ "maybeSubmitCellTriggerDisconnectMetricsForApp: buffer[%hhu], appId: %@, appRunsForeground: %s, measInterval: %.2f s, fallbacktoWifi: %s, cellThroughputBefore (tx, rx): (%u, %u), wifiThroughputAfter (tx, rx): (%u, %u) Kbps, rttMinBeforeAfter: (%u, %u), rttAvgBeforeAfter: (%u, %u) ms, cellScoreBeforeAfter: (%s, %s), wifiScoreBeforeAfter: (%@, %@), wrmWifiScoreBeforeAfter: (%s, %s)"
+ "maybeTriggerCellularDisconnectForApp reset allowing new disconnect requests when wrmWiFiScore: %s, isBbh: %s"
+ "maybeTriggerCellularDisconnectForApp rx throughput %.2f Kbps exceeds 1 Mbps despite bad cell conditions, skip cell TD for app: %@"
+ "maybeTriggerCellularDisconnectForApp:nwDeltaStatsIndex:minDataRateKbps:"
+ "n26"
+ "sendBBCoexP2PSensorState: AWDL state: 0x%x, NAN state: 0x%x, combined P2P state changed: (0x%x -> 0x%x), update to BB"
+ "sendBBCoexP2PSensorState: AWDL state: 0x%x, NAN state: 0x%x, combined P2P state: 0x%x, no change in state. Skip the update to BB"
+ "sendBBCoexP2PSensorState:state:"
+ "updateCellTriggerDisconnectMetric: appId: %@, throughputBefore (tx, rx): (%u, %u) Kbps, rttMinBefore: %u, rttAvgBefore: %u ms, cellScoreBefore: %s, wrmWifiScoreBefore: %s, wifiScoreBefore: %@, dataLQM: %u (%s)"
+ "updateCoexRxGainMode:force:"
+ "updateEpaDisallowed:force:"
+ "updatePreferredAFHMap:force:"
+ "updatePreferredBTCSAFHMap:force:"
+ "updatePreferredHFBTChannelMap:force:"
+ "updateWCI2Mode:force:"
+ "v36@0:8@16C24d28"
- "AFH needs update to %@"
- "BTCS_ %s B20: no BT channel masking"
- "BTCS_ %s B40B (UL>2370): blocking BT channels 0-29"
- "BTCS_ %s B7: no BT channel masking"
- "BTCS_ AFH needs update to %@"
- "BTCS_EPA_ EPA disallowed needs update from %d to %d"
- "ConfigureWCI2 mode : RX=%lld, TX=%lld"
- "HFAFHDebug_ Channel map needs update"
- "Setting BT Agc Rx Coex Gain Mode %d"
- "Snapshot from buffer[%d] for app: %@, uses: %s, on: %s, activeDataSnapshotCount: %u, txRate: %.2f, rxRate: %.2f kbps, rx_dupe: %llu, re-tx: %llu, rx_ooo: %llu, rtt_min: %.2f, rtt_avg: %.2f s"
- "T@\"NSArray\",N,V_mAWDLChannelSequence"
- "T@\"NSArray\",N,V_mNANMap0"
- "T@\"NSArray\",N,V_mNANMap1"
- "app: %@, cellThroughput (tx, rx): (%.2f, %.2f), wifiThroughput (tx, rx): (%.2f, %.2f)"
- "app: %@, cellThroughputBefore (tx, rx): (%u, %u), wifiThroughputAfter (tx, rx): (%u, %u)"
- "app: %@, rttMinAfter: %u, rttAvgAfter: %u"
- "app: %@, rttMinBefore: %u, rttAvgBefore: %u"
- "app: %@, rttMinBeforeAfter: (%u, %u), rttAvgBeforeAfter: (%u, %u)"
- "maybeSubmitCellTriggerDisconnectMetricsForApp: buffer[%hhu], appId: %@, appRunsForeground: %s, measInterval: %.2f s, fallbacktoWifi: %s, cellThroughputBefore (tx, rx): (%u, %u), wifiThroughputAfter (tx, rx): (%u, %u) Kbps, rttMinBeforeAfter: (%u, %u), rttAvgBeforeAfter: (%u, %u), cellScoreBeforeAfter: (%s, %s), wifiScoreBeforeAfter: (%@, %@), wrmWifiScoreBeforeAfter: (%s, %s)"
- "maybeTriggerCellularDisconnectForApp reset allowing new disconnect requests when wifiScore: %@, isBbh: %s"
- "maybeTriggerCellularDisconnectForApp:nwDeltaStatsIndex:"
- "sendBBCoexP2PSensorState: AWDL state: 0x%x, NAN state: 0x%x, combined P2P state: 0x%x"
- "sendBBCoexP2PSensorState: WiFi Reset/PowerOn event, reset AWDL/NAN state"
- "sendBBCoexP2PSensorState:state:WiFiReset:"
- "updateCellTriggerDisconnectMetric: appId: %@, throughputBefore (tx, rx): (%u, %u) Kbps, rttMinBefore: %u, rttAvgBefore: %u, cellScoreBefore: %s, wrmWifiScoreBefore: %s, wifiScoreBefore: %@, dataLQM: %u (%s)"
- "v28@0:8@16C24"
- "v28@0:8I16I20B24"
```
