## nearbyd

> `/usr/libexec/nearbyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x3e6260` | `0x3fa810` | **`+0x145b0`** |
| `__TEXT.__text` | `0x54dce4` | `0x54fc54` | **`+0x1f70`** |
| `__TEXT.__oslogstring` | `0x62465` | `0x629c5` | **`+0x560`** |
| `__TEXT.__cstring` | `0x38cec` | `0x3890c` | **`-0x3e0`** |
| `__TEXT.__objc_methname` | `0x22e85` | `0x230e5` | **`+0x260`** |
| `__TEXT.__objc_stubs` | `0x16b80` | `0x16dc0` | **`+0x240`** |
| `__TEXT.__gcc_except_tab` | `0x54538` | `0x54774` | **`+0x23c`** |
| `__TEXT.__objc_methlist` | `0xf404` | `0xf504` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x1f160` | `0x1f240` | **`+0xe0`** |
| `__DATA.__bss` | `0xe720` | `0xe680` | **`-0xa0`** |
| `__TEXT.__objc_methtype` | `0x221fd` | `0x2229d` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x6f28` | `0x6fc0` | **`+0x98`** |
| `__DATA_CONST.__cfstring` | `0x171c0` | `0x17240` | **`+0x80`** |
| `__DATA.__objc_const` | `0x1b148` | `0x1b1b8` | **`+0x70`** |
| `__DATA.__objc_data` | `0x4978` | `0x4928` | **`-0x50`** |
| `__TEXT.__objc_classname` | `0x204e` | `0x202e` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x1cbf8` | `0x1cc18` | **`+0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0x210` | `0x228` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1994` | `0x19a8` | **`+0x14`** |
| `__DATA.__common` | `0xe60` | `0xe70` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x470` | `0x480` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x630` | `0x628` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x530` | `0x528` | **`-0x8`** |
| `__TEXT.__init_offsets` | `0x6fc` | `0x6f8` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-560.0.0.0.0
+564.0.0.0.0

-  Functions: 23361
+  Functions: 23388

-  CStrings:  19693
+  CStrings:  19733
CStrings:
+ "#btcs,needsRestrictedStateOperation: %@"
+ "#roseprovider,CMAM is disabled"
+ "#ses-btcs,Range not sent to update engine: range %.2f m, error code %d"
+ "#ses-btcs,Sending to update engine: range %.2f m, error code %d"
+ "@84@0:8@16d24@32@40@48^v56^{CSRange=dddidddddI}64^v72I80"
+ "@max.self"
+ "AppStateMonitor is required to check if client is on restricted state operation allowlist."
+ "B32@0:8@16d24"
+ "BTCSFusionConfig"
+ "BTCSFusionConfig initialized to: %ld (%s)"
+ "BTCSFusionConfig invalid value %ld, defaulting to SingleCalib"
+ "BTCSRangeAlgorithmSelect defaulting to: 3 (Fused)"
+ "BTCSRangeAlgorithmSelect initialized to: %ld (Fused)"
+ "Fused range %.4f m exceeds 30m, flagging RangeNotAvailable"
+ "LE"
+ "LE InputIQNotMatch — unexpected tone count, should not happen in production"
+ "LE uncertainty: %.4f (meanRSSI=%.1f dBm, maxRssi=%.1f dBm, d=%.2f m)"
+ "LE upper bound: range=%.4f m errorCode=%d"
+ "MedianCalib"
+ "MedianCalibTrans"
+ "Missing tones detected in active range [%u, %u) — measurement quality degraded"
+ "Near-field claim %.2f m rejected: maxRssi %.1f dBm < %.1f dBm threshold"
+ "RSSI calibration refined (median): rssi0=%.1f dBm [%.1f, %.1f, %.1f]"
+ "RSSI calibration sample 1: rssi0=%.1f dBm (leUBRange=%.2f m maxRssi=%.1f dBm)"
+ "SR"
+ "SR Engine: RSSIMismatch — RSSI %.1f dBm at %.2f m in bottom %.0f%% (CDF = %.4f, predicted mean %.1f dBm)"
+ "SR Engine: Rayleigh model at %.2f m — mean RSSI = %.1f dBm, CDF(%.1f dBm) = %.4f"
+ "SR Engine: mode0_rssi_max = %.1f dBm"
+ "SingleCalib"
+ "TQ,N,V_fusedErrorCode"
+ "TQ,N,V_fusionMode"
+ "TQ,N,V_leErrorCode"
+ "TQ,N,V_srErrorCode"
+ "TQ,N,V_srTrackerCategory"
+ "Td,N,V_eventTime"
+ "Td,N,V_fusedRange"
+ "Td,N,V_leUncertainty"
+ "Td,N,V_srUncertainty"
+ "_calib"
+ "_clientInterestedInDeviceAngleState"
+ "_eventTime"
+ "_fusedErrorCode"
+ "_fusedRange"
+ "_fusionMode"
+ "_isClientOnBTCSRestrictedStateOperationAllowlist"
+ "_lastMERange"
+ "_leErrorCode"
+ "_leUncertainty"
+ "_needsRestrictedStateOperation"
+ "_srErrorCode"
+ "_srTrackerCategory"
+ "_srUncertainty"
+ "calibrating (%lu samples): LE unavailable (leError=%d), falling through to post-cal"
+ "calibrating (%lu samples): fusedRange=leRange=%.4f m (leError=%d)"
+ "clientNeedsBTCSRestrictedStateOperation"
+ "computeWeightedBlend:leUpperBound:"
+ "eventTime"
+ "filteredArrayUsingPredicate:"
+ "fusedErrorCode"
+ "fusedRange"
+ "fusionMode"
+ "getRangeFromIQ: engines not initialized (mode not set), returning RNA"
+ "getUpdatesEngine"
+ "leErrorCode"
+ "leUncertainty"
+ "mode0_rssi_max"
+ "mode0_rssi_mean_predicted"
+ "mode0_rssi_rayleigh_cdf"
+ "needsRestrictedStateOperation"
+ "post-cal: RSSIMismatch, leUB also bad → RNA"
+ "post-cal: RSSIMismatch, need leUB for weighted blend"
+ "post-cal: fusedRange=%.4f m (%s, leError=%d srError=%d)"
+ "post-cal: leUB=HighInterference, use leRange=%.4f m"
+ "post-cal: weighted blend fusedRange=%.4f m (srWeight=%.2f srRange=%.4f leUB=%.4f rssi0=%.1f dBm uncertainty=%.4f)"
+ "pre-cal: fusedRange=leRange=%.4f m (leError=%d fusedError=%d)"
+ "predicateWithFormat:"
+ "rssi0_dbm"
+ "rssi_calib_samples"
+ "selectFusedRange:mode0MaxRssi:"
+ "self < 0"
+ "session:didChangeViewRotationAngle:"
+ "setEventTime:"
+ "setFusedErrorCode:"
+ "setFusedRange:"
+ "setFusionMode:"
+ "setLeErrorCode:"
+ "setLeUncertainty:"
+ "setSrErrorCode:"
+ "setSrTrackerCategory:"
+ "setSrUncertainty:"
+ "srErrorCode"
+ "srTrackerCategory"
+ "srUncertainty"
+ "strong-signal: fusedRange=srRange=%.4f m (maxRssi=%.1f dBm)"
+ "toneArr count %lu < required %u, skipping hasMissingTones check"
+ "v32@0:8@\"ARSession\"16d24"
+ "v32@0:8@16r^{RangeEstimate=dddQId}24"
+ "v32@0:8Q16^{CSRange=dddidddddI}24"
+ "valueForKeyPath:"
+ "{RSSICalibState=\"sampleCount\"Q\"samples\"{array<double, 3UL>=\"__elems_\"[3d]}\"rssi0Dbm\"d}"
+ "\x91"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\x91"
- "#btcs,initiator only channel=%d, sweepIndex=%@"
- "#dma,CMAM is disabled"
- "#dma,sending initial unknown cmam state"
- "#dma,starting monitoring"
- "#roseprovider,onCMDAStateChange,index,%u"
- "#ses-btcs,Raw range not sent to update engine: raw range %.2f m, error code %d"
- "#ses-btcs,Sending to update engine: raw range %.2f m, error code %d"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Proximity/Framework/BTCSEngine/src/ToA_wcs_algo/toa_wcs.c"
- "/System/Library/NearbyInteractionBundles/BTCSNeuralNetworkResources.bundle"
- "@84@0:8@16d24@32@40@48^v56^{CSRange=ddidddddI}64^v72I80"
- "Attempting to load network from: %s\n"
- "BTCS Neural Network initialized successfully"
- "BTCSRangeAlgorithmSelect defaulting to: 1 (Super Resolution)"
- "Building Espresso plan..."
- "CSEEngineLE.mm"
- "DMA"
- "ERROR: .weights file does not exist at: %s\n"
- "ERROR: Alternative path also failed (status=%d)\n"
- "ERROR: Failed to add network to Espresso plan (status=%d)\n"
- "ERROR: Failed to build Espresso plan (status=%d)\n"
- "ERROR: Failed to create Espresso context"
- "ERROR: Failed to create Espresso plan"
- "ERROR: Model file does not exist at: %s\n"
- "ERROR: Network path was: %s\n"
- "ERROR: Unable to locate model.espresso.net file in bundle"
- "Found .shape file at: %s\n"
- "Found .weights file at: %s\n"
- "Found N=%d zero-quality tones, power_sum=%lf, normalized by %lf"
- "Found model in system bundle: %s\n"
- "GetRange"
- "Initializing BTCS Neural Network from bundle: %s\n"
- "NOTE: No .shape file found, using inline shapes from .net file"
- "PRDeviceAngleStateMonitor"
- "PRDeviceAngleStateMonitor.mm"
- "Raw range %.4f m exceeds 30m, flagging RangeNotAvailable"
- "SUCCESS: Loaded network using base path"
- "Successfully located model .net file at: %s\n"
- "System bundle not found or resource missing at: %s\n"
- "TB,N,V_smoothingEnabled"
- "TQ,N,V_leAlgoVer"
- "Trying alternative base path: %s\n"
- "_lastRawRange"
- "_leAlgoVer"
- "_smoothingEnabled"
- "_stateInitialized"
- "angleStateToIndex:"
- "btcs ranging algorithm selection is %ld"
- "btcs_nn.isConfigured()"
- "cfr_input"
- "initDeviceAngleStateListener"
- "interpolated_output"
- "leAlgoVer"
- "result.output.size() == kNumFreqBin79*2"
- "setLeAlgoVer:"
- "setSmoothingEnabled:"
- "shape"
- "smoothingEnabled"
- "teardownDeviceAngleStateListener"
- "trimmedEvent:forBWMode:"
- "v96@0:8Q16{CSRange=ddidddddI}24"
- "weights"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\x81"
```
