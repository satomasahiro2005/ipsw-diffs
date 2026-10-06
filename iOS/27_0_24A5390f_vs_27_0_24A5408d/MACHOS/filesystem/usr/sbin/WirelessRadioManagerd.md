## WirelessRadioManagerd

> `/usr/sbin/WirelessRadioManagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1713d8` | `0x17171c` | **`+0x344`** |
| `__TEXT.__cstring` | `0x5a193` | `0x5a21d` | **`+0x8a`** |
| `__TEXT.__objc_methname` | `0x346a6` | `0x346f4` | **`+0x4e`** |
| `__DATA_CONST.__cfstring` | `0x32f60` | `0x32f80` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x21720` | `0x21740` | **`+0x20`** |
| `__DATA.__common` | `0x632` | `0x63a` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xa038` | `0xa040` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x11bf4` | `0x11bfc` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x50f0` | `0x50e8` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x8b16` | `0x8b17` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-1937.1.0.0.0
+1939.2.0.0.0

-  Functions: 7810
+  Functions: 7811

-  CStrings:  16874
+  CStrings:  16876
CStrings:
+ "^{WRMMetricsCellTriggerDisconnect=d@@IIIIIIIIIIIIIIiBdBBd}16@0:8"
+ "handleStreamingStateChange skip stop detection, some apps are still active %@"
+ "handleVoIPStateChange skip stop detection, some apps are still active %@"
+ "handleVoIPStateChangeConference skip stop detection, some apps are still active %@"
+ "handleVoIPandStreamingStateChange skip stop detection, some apps are still active %@"
+ "hasAnyForegroundApps: VoIP (%lu), Streaming (%lu), VoIPAndStreaming (%lu), WebKit (%lu) apps are running in foreground"
+ "maybeNotifyStreamingStop: mStreamingConnectionReferenceCount: %llu, mWebkitStreamingActiveRefCnt: %d, mBBStateStreamingActive: %s"
+ "maybeTriggerCellularDisconnectForApp app running for %.2fs (<= %.2fs), skip cell disconnect for app: %@"
+ "maybeTriggerCellularDisconnectForApp:nwDeltaStatsIndex:minDataRateKbps:appRunningDuration:"
+ "startMonitoringAppSessions invalid NWStatsManager object"
+ "startMonitoringAppSessions suspicious txRate: %.2f for txBytes: %llu"
+ "startMonitoringAppSessions:interval:iRATHandler:"
+ "statsMonitorPeriodForApp:"
+ "stopMonitoringAppSessions"
+ "updateCellTriggerDisconnectMetric:genericCellScore:wifiScore:wrmWifiScore:statsMonitorPeriodicity:"
+ "v44@0:8@16C24d28d36"
+ "v48@0:8^{?=@QQQQQQQffB@Idd}16i24q28i36d40"
+ "{WRMMetricsCellTriggerDisconnect=\"timestamp\"d\"applicationId\"@\"NSString\"\"protocols\"@\"NSString\"\"txThroughputBefore\"I\"rxThroughputBefore\"I\"txThroughputAfter\"I\"rxThroughputAfter\"I\"rttMinBefore\"I\"rttMinAfter\"I\"rttAvgBefore\"I\"rttAvgAfter\"I\"cellScoreBefore\"I\"cellScoreAfter\"I\"wrmWifiScoreBefore\"I\"wrmWifiScoreAfter\"I\"wifiScoreBefore\"I\"wifiScoreAfter\"I\"dataLQM\"i\"didFallbackToWiFiOnCellDisconnect\"B\"postDisconnectMeasurementInterval\"d\"appRunsForeground\"B\"metricReportPending\"B\"metricSubmissionDeferInterval\"d}"
- "VoIP (%lu), Streaming (%lu), VoIPAndStreaming (%lu), WebKit (%lu) apps are running in foreground"
- "^{WRMMetricsCellTriggerDisconnect=d@@IIIIIIIIIIIIIIiBdBBC}16@0:8"
- "handleStreamingStateChange skip rxVoIPAppNotification %@"
- "handleVoIPStateChange skip rxVoIPAppNotification %@"
- "handleVoIPStateChangeConference skip rxVoIPAppNotification %@"
- "handleVoIPandStreamingStateChange skip, some apps are still active %@"
- "maybeNotifyStreamingStop: mStreamingConnectionReferenceCount: %llu, mWebkitStreamingActiveRefCnt: %d, mForegroundRunningVoipAndStreamingApps.count: %lu, mForegroundRunningStreamingApps.count: %lu"
- "maybeTriggerCellularDisconnectForApp:nwDeltaStatsIndex:minDataRateKbps:"
- "startStatsCollectionForApp invalid NWStatsManager object"
- "startStatsCollectionForApp suspicious txRate: %.2f for txBytes: %llu"
- "startStatsCollectionForApp:interval:iRATHandler:"
- "stopPeriodicTask"
- "updateCellTriggerDisconnectMetric:genericCellScore:wifiScore:wrmWifiScore:"
- "v36@0:8@16C24d28"
- "v40@0:8^{?=@QQQQQQQffB@Idd}16i24q28i36"
- "{WRMMetricsCellTriggerDisconnect=\"timestamp\"d\"applicationId\"@\"NSString\"\"protocols\"@\"NSString\"\"txThroughputBefore\"I\"rxThroughputBefore\"I\"txThroughputAfter\"I\"rxThroughputAfter\"I\"rttMinBefore\"I\"rttMinAfter\"I\"rttAvgBefore\"I\"rttAvgAfter\"I\"cellScoreBefore\"I\"cellScoreAfter\"I\"wrmWifiScoreBefore\"I\"wrmWifiScoreAfter\"I\"wifiScoreBefore\"I\"wifiScoreAfter\"I\"dataLQM\"i\"didFallbackToWiFiOnCellDisconnect\"B\"postDisconnectMeasurementInterval\"d\"appRunsForeground\"B\"metricReportPending\"B\"deferUntilAdditionalNwStatsReports\"C}"
```
