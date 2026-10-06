## wirelessinsightsd

> `/System/Library/Frameworks/WirelessInsights.framework/Support/wirelessinsightsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3391e4` | `0x33e4d8` | **`+0x52f4`** |
| `__TEXT.__oslogstring` | `0x2ded4` | `0x2e622` | **`+0x74e`** |
| `__TEXT.__gcc_except_tab` | `0x299b0` | `0x29ecc` | **`+0x51c`** |
| `__TEXT.__cstring` | `0x1544b` | `0x1592b` | **`+0x4e0`** |
| `__DATA.__objc_data` | `0x51c8` | `0x5528` | **`+0x360`** |
| `__TEXT.__const` | `0x17b53` | `0x17e03` | **`+0x2b0`** |
| `__DATA_CONST.__const` | `0x16f08` | `0x17140` | **`+0x238`** |
| `__DATA.__objc_const` | `0x14200` | `0x143f0` | **`+0x1f0`** |
| `__TEXT.__unwind_info` | `0x101b8` | `0x10350` | **`+0x198`** |
| `__DATA.__data` | `0x68f8` | `0x6798` | **`-0x160`** |
| `__TEXT.__objc_methname` | `0x1803c` | `0x1817c` | **`+0x140`** |
| `__DATA.__bss` | `0x7fe8` | `0x8118` | **`+0x130`** |
| `__TEXT.__objc_methtype` | `0x448a` | `0x45ba` | **`+0x130`** |
| `__TEXT.__objc_methlist` | `0x76f4` | `0x77b4` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x3f94` | `0x4030` | **`+0x9c`** |
| `__TEXT.__swift5_reflstr` | `0x5c53` | `0x5ce3` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x1c34` | `0x1ca4` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x408c` | `0x40f0` | **`+0x64`** |
| `__TEXT.__swift5_typeref` | `0x25b0` | `0x2602` | **`+0x52`** |
| `__DATA_CONST.__got` | `0x1300` | `0x12b0` | **`-0x50`** |
| `__TEXT.__eh_frame` | `0x6990` | `0x69e0` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x1bfe` | `0x1c4e` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x7300` | `0x72c0` | **`-0x40`** |
| `__DATA.__common` | `0x5e8` | `0x608` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x1a0` | `0x1b0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x4f50` | `0x4f60` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x420` | `0x430` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x9f0` | `0x9fc` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x27c0` | `0x27c8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x5f0` | `0x5f8` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xa0` | `0xa8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2e0` | `0x2e8` | **`+0x8`** |
| `__TEXT.__init_offsets` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x520` | `0x528` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x2b8` | `0x2c0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2d4` | `0x2d8` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x850` | `0x854` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-335.0.0.0.0
+341.0.0.0.0

-  Functions: 14254
-  Symbols:   2035
-  CStrings:  10151
+  Functions: 14348
+  Symbols:   2026
+  CStrings:  10247
Symbols:
+ _kCellularDiagnosticsAnomalyCarrierNameKey
+ _kCellularDiagnosticsAnomalyLearnMoreKey
+ _kCellularDiagnosticsAnomalyStateKey
+ _swift_deallocUninitializedObject
- __ZN3wis18kWISInsightTypeKeyE
- __ZN3wis19kWISInsightStateKeyE
- __ZN3wis20kWISInsightTypeVoiceE
- __ZN3wis22kWISAnomalyCategoryKeyE
- __ZN3wis22kWISInsightStateNormalE
- __ZN3wis22kWISInsightTypeServiceE
- __ZN3wis23kWISAnomalyLearnMoreKeyE
- __ZN3wis23kWISInsightStateAnomalyE
- __ZN3wis25kWISAnomalyCarrierNameKeyE
- __ZN3wis25kWISAnomalySubCategoryKeyE
- __ZN3wis26kWISAnomalyCategoryNetworkE
- __ZN3wis37kWISAnomalySubCategoryOutageConfirmedE
- __ZN3wis37kWISAnomalySubCategoryOutagePotentialE
CStrings:
+ " deployment: "
+ " dst_band:"
+ " dst_cell_quality:"
+ " dst_rat:"
+ " failed_si_periodicity:"
+ " fr:"
+ " ip_type:"
+ " leg:"
+ " p_action:"
+ " plmn: "
+ " recovery_type:"
+ " rej_cause:"
+ " s_action:"
+ " sibs_failed:"
+ " src_band:"
+ " src_cell_quality:"
+ " src_rat:"
+ " trigger:"
+ "341"
+ "341~13"
+ "@\"<WISBasebandMetricsAdaptorDelegate>\""
+ "APACSInfoBasebandMetric(didUseInsight: "
+ "Baseband notification with data %s. curState: %s"
+ "Both micro and intermediate tiles are nil, resetting tile information at baseband"
+ "CASanitizerEventNameMap is nil, could not sanitize metric list"
+ "Cannot submit, no prepared payload available"
+ "Converting current country MCC to hex: %u"
+ "DEPLOYMENT_"
+ "EE_EXIT_REASON_"
+ "EE_REASON_"
+ "MEAS_CELL_QUALITY_LVL_"
+ "MOBILITY_STATE_"
+ "Metric wait timer was cancelled"
+ "Not submitting payload, baseband data not available"
+ "PDP Failures"
+ "PROC_TYPE_CELL_SELECTION"
+ "PduActivationFailure"
+ "RECOV_SUB_TRIGGER_"
+ "RECOV_TYPE_"
+ "RESEL_CAUSE_"
+ "RESEL_FAILURE_"
+ "RESEL_TRIGGER_"
+ "RRC_RECOV_TRIGGER_"
+ "Received baseband metric %s with payload %s"
+ "Received baseband metric but basebandMetricData already set, returning"
+ "Received baseband metric while still in airplane mode, ignoring"
+ "Reselection"
+ "Reset already sent to baseband, skipping until a useful insight is sent"
+ "SCG Removal Failure"
+ "SCG_RLC_MAX_RETX_FAILURE"
+ "SI Acquisition Failure"
+ "SM_ACTIVATION_REJECTED_BY_GGSN"
+ "SM_INSUFFICIENT_RESOURCES"
+ "SM_INVALID_CAUSE"
+ "SM_MISSING_OR_UNKNOWN_APN"
+ "SM_NETWORK_FAILURE"
+ "SM_OPERATOR_DETERMINED_BARRING"
+ "SM_PDN_CONNECTION_DOES_NOT_EXIST"
+ "SM_REQ_SERVICE_NOT_SUBSCRIBED"
+ "SM_SERVICE_OPT_NOT_SUPPORTED"
+ "SM_SERVICE_TEMP_OUT_OF_ORDER"
+ "SM_USER_AUTH_FAILED"
+ "Submitted payload %s"
+ "T@\"<WISBasebandMetricsAdaptorDelegate>\",W,V_delegate"
+ "T{shared_ptr<WISTelemetryObserver>=^{WISTelemetryObserver}^{__shared_weak_count}},V_observer"
+ "Unexpected is_data_preferred, status, or proc_type, ignoring"
+ "WISABC:Context: cellularPduActivationFailure [%s]"
+ "WISABC:Context: cellularSIAcquisitionFailure [%s]"
+ "WISABC:Rule satisfied and triggering ABC for event: cellularNrScgRemoval"
+ "WISABC:Rule satisfied and triggering ABC for event: cellularPduActivationFailure"
+ "WISABC:Rule satisfied and triggering ABC for event: cellularSIAcquisitionFailure"
+ "WISABC:Skipping ABC, criteria not met for event: cellularPduActivationFailure"
+ "WISABC:Skipping ABC, criteria not met for event: cellularSIAcquisitionFailure"
+ "WISABC:Skipping ABC, rej_cause not present for event: cellularPduActivationFailure"
+ "WISABC:Skipping ABC, unable to read rej_cause for event: cellularPduActivationFailure"
+ "WISABC:Skipping ABC, unable to read sinr_db for event: cellularSIAcquisitionFailure"
+ "WISBasebandMetricsAdaptor"
+ "WISBasebandMetricsAdaptor:Deallocating"
+ "WISBasebandMetricsAdaptor:Failed to convert event name"
+ "WISBasebandMetricsAdaptor:Failed to convert incoming metric: %@"
+ "WISBasebandMetricsAdaptor:Failed to get ConversionController"
+ "WISBasebandMetricsAdaptor:Failed to initialize parent"
+ "WISBasebandMetricsAdaptor:Failed to initialize queue"
+ "WISBasebandMetricsAdaptor:Initialized successfully"
+ "WISBasebandMetricsAdaptor:Metric name: %@, payload %@"
+ "WISBasebandMetricsAdaptor:Received event %s"
+ "WISBasebandMetricsAdaptor:Received metric callback for metric %@"
+ "WISBasebandMetricsAdaptor:Registering for metric: %@"
+ "WISBasebandMetricsAdaptorDelegate"
+ "band_ind"
+ "band_ind: "
+ "basebandDuration"
+ "basebandMetricData"
+ "basebandMetricDataWaitTask"
+ "basebandMetricsAdaptor"
+ "body"
+ "cellularCongestionData"
+ "com.apple.Baseband.cellularApacsPerfInfo"
+ "com.apple.Baseband.cellularPduActivationFailure"
+ "com.apple.Baseband.cellularSIAcquisitionFailure"
+ "com.apple.wirelessinsightsd.WISBasebandMetricsAdaptor"
+ "didBasebandUsePrediction"
+ "dl_buffer_drain_duration"
+ "dl_rlgs_score_before_mitigation"
+ "dl_score_before_mitigation"
+ "failed_si_periodicity"
+ "heap_data_core_id"
+ "heap_data_heap_id"
+ "heap_data_peak_heap_usage_percentage"
+ "initWithDelegate:withSubscribedMetrics:"
+ "ip_type"
+ "mobility:"
+ "preparedMetricPayload"
+ "recovery_type"
+ "rej_cause"
+ "req_type"
+ "req_type:"
+ "sibs_failed"
+ "sinr_db"
+ "source_cell_band"
+ "source_cell_cell_quality_level"
+ "source_cell_rat"
+ "target_cell_band"
+ "target_cell_cell_quality_level"
+ "target_cell_rat"
+ "target_cell_sinr"
+ "ul_rlgs_score_before_mitigation"
+ "ul_score_before_mitigation"
+ "v32@0:8@\"NSString\"16@\"NSDictionary\"24"
+ "v32@0:8@16{dict={object=@}}24"
+ "v32@0:8{shared_ptr<WISTelemetryObserver>=^{WISTelemetryObserver}^{__shared_weak_count}}16"
+ "wirelessinsightsd.RoamingPLMNPredictionController"
+ "{shared_ptr<WISTelemetryObserver>=\"__ptr_\"^{WISTelemetryObserver}\"__cntrl_\"^{__shared_weak_count}}"
+ "{shared_ptr<WISTelemetryObserver>=^{WISTelemetryObserver}^{__shared_weak_count}}16@0:8"
- " cell_group:"
- " failure_rat:"
- " freq_range:"
- " primary_action:"
- " resel_cause:"
- " resel_trigger:"
- " resel_type:"
- " secondary_action:"
- " source_cell_band:"
- " source_cell_cell_quality_level:"
- " source_cell_rat:"
- " target_cell_band:"
- " target_cell_cell_quality_level:"
- " target_cell_rat:"
- "&client_id="
- "&client_secret="
- "&scope="
- "335"
- "335~31"
- "WISABC:Skipping ABC, non-dict element in event: cellularHeapStats"
- "WISABC:Skipping ABC, non-dict element in event: cellularIpcDlBuf"
- "WISABC:Skipping ABC, unable to read context fields for event: cellularReselectionInfo"
- "buildBaseDict:state:"
- "cell_quality_level"
- "client_id"
- "client_secret"
- "core_id"
- "dl_buffer_drain"
- "grant_type"
- "grant_type="
- "heap_data"
- "heap_id"
- "mobility_state:"
- "peak_heap_usage_percentage"
- "scope"
- "source_cell"
- "target_cell"
- "{CFSharedRef<__CFDictionary>=^{__CFDictionary}}32@0:8^{__CFString=}16^{__CFString=}24"
```
