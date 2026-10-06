## wirelessinsightsd

> `/System/Library/Frameworks/WirelessInsights.framework/Support/wirelessinsightsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x344dfc` | `0x34a1ac` | **`+0x53b0`** |
| `__TEXT.__oslogstring` | `0x2e8d2` | `0x2ed62` | **`+0x490`** |
| `__TEXT.__cstring` | `0x15a4b` | `0x15ecb` | **`+0x480`** |
| `__TEXT.__objc_methname` | `0x183ac` | `0x187ac` | **`+0x400`** |
| `__TEXT.__gcc_except_tab` | `0x29ed0` | `0x2a274` | **`+0x3a4`** |
| `__DATA.__objc_const` | `0x14410` | `0x14570` | **`+0x160`** |
| `__DATA_CONST.__const` | `0x17258` | `0x17388` | **`+0x130`** |
| `__TEXT.__objc_stubs` | `0xf860` | `0xf980` | **`+0x120`** |
| `__TEXT.__eh_frame` | `0x6a10` | `0x6b00` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x103b8` | `0x10448` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x77b4` | `0x783c` | **`+0x88`** |
| `__TEXT.__auth_stubs` | `0x4f70` | `0x4ff0` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x72c0` | `0x7320` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x1ca8` | `0x1d04` | **`+0x5c`** |
| `__DATA.__objc_selrefs` | `0x4478` | `0x44d0` | **`+0x58`** |
| `__DATA_CONST.__auth_got` | `0x27d0` | `0x2810` | **`+0x40`** |
| `__DATA.__data` | `0x6778` | `0x67a8` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0x680` | `0x6b0` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x404c` | `0x4074` | **`+0x28`** |
| `__TEXT.__const` | `0x17e73` | `0x17e93` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x9fc` | `0xa18` | **`+0x1c`** |
| `__DATA.__bss` | `0x8118` | `0x8128` | **`+0x10`** |
| `__DATA.__objc_data` | `0x5558` | `0x5568` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x45da` | `0x45ea` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x5d63` | `0x5d73` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x838` | `0x848` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x416c` | `0x4160` | **`-0xc`** |
| `__TEXT.__swift_as_entry` | `0x430` | `0x43c` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x2c8` | `0x2cc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-344.0.0.0.0
+348.0.0.0.0

-  Functions: 14376
-  Symbols:   2048
-  CStrings:  10291
+  Functions: 14414
+  Symbols:   2056
+  CStrings:  10374
Symbols:
+ _$s16WirelessInsights17ServicePredictionV15ConfidenceScoreV10predictionAC0E0Ovg
+ _$s16WirelessInsights17ServicePredictionV15ConfidenceScoreV8durationAC0E0Ovg
+ _$s16WirelessInsights17ServicePredictionV15ConfidenceScoreV9startTimeAC0E0Ovg
+ _$s16WirelessInsights17ServicePredictionV15confidenceScoreAC010ConfidenceF0Vvg
+ _$s16WirelessInsights17ServicePredictionV17predictedIntervalSdvg
+ _$s16WirelessInsights17ServicePredictionV18predictedStartTime10Foundation4DateVvg
+ _$s16WirelessInsights17ServicePredictionV6impactAC6ImpactOvg
+ _CFDateGetAbsoluteTime
CStrings:
+ " end_reason:"
+ " has_connected:"
+ " is_incoming:"
+ " lower_bound:"
+ " num_subs:"
+ " start_telephony_transport_type:"
+ " upper_bound:"
+ ", confidenceScore: "
+ ", filterCriteriaFailReason: "
+ ", filterResult: "
+ ", numPrevPredictions: "
+ ", predictedInterval: "
+ ", startTimeConfidence: "
+ "348"
+ "348~11"
+ "@64@0:8@16Q24@32@40B48B52Q56"
+ "APACSInfoBasebandMetric(radius: "
+ "CFRE"
+ "ConfidenceScore(prediction: "
+ "ConfidenceScore(predictionConfidence: "
+ "FMTSCongestionAnomalyCombinationWindow"
+ "FMTSLowSignalStrengthAnomalyCombinationWindow"
+ "FMTSOutOfServiceAnomalyCombinationWindow"
+ "Failed to start monitoring known network profile change events: %@"
+ "FederatedMobility[FMTimeSeriesModel]:Anomaly of type %@ already active or in combination window (%@)"
+ "FederatedMobility[FMTimeSeriesModel]:Cleaning up %lu anomalies if beyond the combination window at timestamp %llu"
+ "FederatedMobility[FMTimeSeriesModel]:Multiple candidate predictions on anomaly end: %@, %@"
+ "FederatedMobility[FMTimeSeriesModel]:Not ending existing anomaly due to combination window: %@"
+ "PhoneApp Call Failure"
+ "PredictionFilterResult(didPassFilterCriteria: "
+ "PrivateServicePrediction(type: "
+ "Received %ld new upcoming flight predictions, in total %ld predictions"
+ "SSID Intelligent Connectivity"
+ "Sending API prediction %s"
+ "Sending prediction %s"
+ "ServicePrediction(impact: "
+ "SigLocation oos rate %d in 0.01 percent, valid visit count %d, valid duration %lld sec"
+ "SigLocation skipping sigLocOutage cloud telemetry: mcc=0, gci='%s', isOutage=%{bool}d"
+ "Spotlight query: %s"
+ "TB,R,V_isClientEverActiveDuringCombinationWindow"
+ "TB,R,V_isClientEverImpactedDuringCombinationWindow"
+ "TQ,R,N,V_combinationWindow"
+ "TQ,R,N,V_preliminaryEndTimestamp"
+ "TQ,R,V_FMTSCongestionAnomalyCombinationWindow"
+ "TQ,R,V_FMTSLowSignalStrengthAnomalyCombinationWindow"
+ "TQ,R,V_FMTSOutOfServiceAnomalyCombinationWindow"
+ "VoLTE"
+ "VoNR"
+ "WISABC:Context: cellularCfreRangeInfo [%s]"
+ "WISABC:Rule satisfied and triggering ABC for event: cellularCfreRangeInfo"
+ "WISABC:Skipping ABC for %s, end_reason %d is not in trigger list"
+ "WISABC:Skipping ABC for %s, is_relay is true"
+ "WISABC:Skipping ABC for %s, provider_id is not com.apple.coretelephony"
+ "WISABC:Skipping ABC for %s, telephony_transport_type %d is not in trigger list"
+ "WISABC:Skipping ABC, criteria not met for event: cellularCfreRangeInfo"
+ "WISABC:Skipping ABC, unable to read report_type for event: cellularCfreRangeInfo"
+ "WiFi"
+ "_FMTSCongestionAnomalyCombinationWindow"
+ "_FMTSLowSignalStrengthAnomalyCombinationWindow"
+ "_FMTSOutOfServiceAnomalyCombinationWindow"
+ "_combinationWindow"
+ "_isClientEverActiveDuringCombinationWindow"
+ "_isClientEverImpactedDuringCombinationWindow"
+ "_preliminaryEndTimestamp"
+ "basebandInsightRadius"
+ "cellularLearning"
+ "com.apple.Baseband.cellularCfreRangeInfo"
+ "com.apple.Callservicesd.callEndStatus"
+ "combinationWindow"
+ "endAnomaliesBeyondCombinationWindowForState:atTimestamp:"
+ "end_reason"
+ "has_connected"
+ "initWithTime:timestamp:location:events:isClientActive:isClientImpacted:combinationWindow:"
+ "isClientEverActiveDuringCombinationWindow"
+ "isClientEverImpactedDuringCombinationWindow"
+ "isConnectivityAssistEnabled"
+ "is_incoming"
+ "is_relay"
+ "lower_bound_cfre_excursion_ppm"
+ "maybeCombineAnomalyAtTimestamp:"
+ "maybeEndAtTimestamp:"
+ "num_subs"
+ "plmn:"
+ "preliminaryEndTimestamp"
+ "provider_id"
+ "report_type"
+ "startTime %@, startTimestamp %llu, startLocation %@, preliminaryEndTimestamp %llu, endTimestamp %llu, hasEnded %@, combinationWindow %lu, events %@"
+ "start_telephony_transport_type"
+ "supressSettingsNotification"
+ "telephony_transport_type"
+ "updateHasEndedAtTimestamp:"
+ "upper_bound_cfre_excursion_ppm"
+ "userDataLearning"
+ "\xf0\x91!\xf0\xf0A"
- "344"
- "344~46"
- "@56@0:8@16Q24@32@40B48B52"
- "APACSInfoBasebandMetric(didUseInsight: "
- "FederatedMobility[FMTimeSeriesModel]:Anomaly of type %@ already active"
- "Received %ld new upcoming flight predictions"
- "SigLocation oos rate %d in 0.01 percent and valid visit count %d"
- "endAtTimestamp:"
- "initWithTime:timestamp:location:events:isClientActive:isClientImpacted:"
- "startTime %@, startTimestamp %llu, startLocation %@, endTimestamp %llu, hasEnded %@, events %@"
- "suppressSettingNotification"
```
