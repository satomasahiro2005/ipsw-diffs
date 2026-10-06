## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16c570` | `0x171b1c` | **`+0x55ac`** |
| `__AUTH_CONST.__objc_const` | `0x33890` | `0x35760` | **`+0x1ed0`** |
| `__TEXT.__const` | `0x16a08` | `0x15828` | **`-0x11e0`** |
| `__TEXT.__oslogstring` | `0x1990d` | `0x19e7d` | **`+0x570`** |
| `__TEXT.__objc_methlist` | `0xd1f4` | `0xd5f4` | **`+0x400`** |
| `__AUTH_CONST.__cfstring` | `0xe5c0` | `0xe840` | **`+0x280`** |
| `__TEXT.__cstring` | `0xcd15` | `0xcf85` | **`+0x270`** |
| `__AUTH.__objc_data` | `0x2680` | `0x2860` | **`+0x1e0`** |
| `__TEXT.__unwind_info` | `0x55d8` | `0x5700` | **`+0x128`** |
| `__DATA_CONST.__objc_selrefs` | `0x5958` | `0x5a60` | **`+0x108`** |
| `__TEXT.__gcc_except_tab` | `0x2804` | `0x28cc` | **`+0xc8`** |
| `__DATA_CONST.__const` | `0x2f60` | `0x2ff0` | **`+0x90`** |
| `__DATA.__objc_ivar` | `0x1718` | `0x179c` | **`+0x84`** |
| `__DATA.__data` | `0x34fb8` | `0x35018` | **`+0x60`** |
| `__TEXT.__dlopen_cstrs` | `0x1d5` | `0x218` | **`+0x43`** |
| `__DATA.__bss` | `0x66c0` | `0x66f0` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0xcc8` | `0xcf8` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x6f8` | `0x728` | **`+0x30`** |
| `__DATA_CONST.__objc_superrefs` | `0x5c0` | `0x5f0` | **`+0x30`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x408` | `0x420` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0xdb0` | `0xd98` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1370` | `0x1368` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x7b0` | `0x7b8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x368` | `0x370` | **`+0x8`** |

### Other Changes

```diff

-2300.0.18.502.1
+2300.2.7.0.0

-  Functions: 8711
-  Symbols:   10139
-  CStrings:  4696
+  Functions: 8830
+  Symbols:   10314
+  CStrings:  4746
Symbols:
+ +[CBAnalytics illuminanceHistogram:displayID:alsID:]
+ +[CBAnalytics luminanceHistogram:withName:displayID:]
+ +[CBCE5 URLOfModelInThisBundle]
+ +[CBCE5 loadContentsOfURL:configuration:completionHandler:]
+ +[CBCE5 loadWithConfiguration:completionHandler:]
+ +[CBDisplayStateUtilities isActiveDisplayMode:]
+ -[AABCHistograms displayID]
+ -[AABCHistograms pushIlluminance:weight:forAlsID:]
+ -[AABCHistograms setDisplayID:]
+ -[BacklightdExportedObj clientSetProperty:forKey:andHandle:]
+ -[BrightnessSystemClient setSyncProperty:forKey:withHandle:error:]
+ -[BrightnessSystemClientInternal setSyncProperty:forKey:handle:error:]
+ -[CBALSEvent channelAveragedColorVendorData]
+ -[CBALSEvent copyChannelAveragedColorDataFromEvent:]
+ -[CBALSEvent setChannelAveragedColorVendorData:]
+ -[CBAODModule isDesignatedAODSensor:]
+ -[CBAODThresholdModule resetPushedThresholds]
+ -[CBBrightnessBroadcaster activate]
+ -[CBBrightnessBroadcaster cancel]
+ -[CBBrightnessBroadcaster dealloc]
+ -[CBBrightnessBroadcaster displayModeProvidersUpdate:]
+ -[CBBrightnessBroadcaster encodeBrightnessState:]
+ -[CBBrightnessBroadcaster initWithDisplayManager:]
+ -[CBBrightnessBroadcaster initWithDisplayManager:notifier:]
+ -[CBBrightnessBroadcaster reevaluateAndNotify]
+ -[CBBrightnessBroadcaster sendNotificationForKey:value:origin:]
+ -[CBCE5 .cxx_destruct]
+ -[CBCE5 initWithConfiguration:error:]
+ -[CBCE5 initWithContentsOfURL:configuration:error:]
+ -[CBCE5 initWithContentsOfURL:error:]
+ -[CBCE5 initWithMLModel:]
+ -[CBCE5 init]
+ -[CBCE5 model]
+ -[CBCE5 predictionFromFeatures:error:]
+ -[CBCE5 predictionFromFeatures:options:error:]
+ -[CBCE5 predictionFromInput:error:]
+ -[CBCE5 predictionsFromInputs:options:error:]
+ -[CBCE5Input .cxx_destruct]
+ -[CBCE5Input featureNames]
+ -[CBCE5Input featureValueForName:]
+ -[CBCE5Input initWithInput:]
+ -[CBCE5Input input]
+ -[CBCE5Input setInput:]
+ -[CBCE5Output .cxx_destruct]
+ -[CBCE5Output CBCE5_Q0_output]
+ -[CBCE5Output CBCE5_Q1_output]
+ -[CBCE5Output CBCE5_Q2_output]
+ -[CBCE5Output CBCE5_Q3_output]
+ -[CBCE5Output CBCE5_Q4_output]
+ -[CBCE5Output featureNames]
+ -[CBCE5Output featureValueForName:]
+ -[CBCE5Output initWithCBCE5_Q0_output:CBCE5_Q1_output:CBCE5_Q2_output:CBCE5_Q3_output:CBCE5_Q4_output:strength_output:uncertainty:]
+ -[CBCE5Output setCBCE5_Q0_output:]
+ -[CBCE5Output setCBCE5_Q1_output:]
+ -[CBCE5Output setCBCE5_Q2_output:]
+ -[CBCE5Output setCBCE5_Q3_output:]
+ -[CBCE5Output setCBCE5_Q4_output:]
+ -[CBCE5Output setStrength_output:]
+ -[CBCE5Output setUncertainty:]
+ -[CBCE5Output strength_output]
+ -[CBCE5Output uncertainty]
+ -[CBCEModule _paramsFromAlsEvent:]
+ -[CBCEModule copyInferenceForEvent:]
+ -[CBCEModule setModelInputWithParameters:]
+ -[CBColorFilter activeALSServices]
+ -[CBColorPolicyFilter biLinearInterpBetweenIndices:forPoint1:andPoint2:strengthLUT:luxCount:luxArray:nitsArray:]
+ -[CBDarwinStateNotifier dealloc]
+ -[CBDarwinStateNotifier initWithNotificationName:logCategory:]
+ -[CBDarwinStateNotifier publishState:]
+ -[CBDisplayBrightnessClient isRingLightEnabledWithError:]
+ -[CBDisplayContaineriOS isExternalWired]
+ -[CBDisplayStatusBroadcaster activate]
+ -[CBDisplayStatusBroadcaster cancel]
+ -[CBDisplayStatusBroadcaster dealloc]
+ -[CBDisplayStatusBroadcaster displayModeProvidersUpdate:]
+ -[CBDisplayStatusBroadcaster initWithDisplayManager:]
+ -[CBDisplayStatusBroadcaster reevaluateAndNotify]
+ -[CBDisplayStatusBroadcaster sendNotificationForKey:value:origin:]
+ -[CBRingLight isActive]
+ -[CBSliderCommitTelemetry initWithQueue:andDisplayContainer:andVariant:andContext:]
+ GCC_except_table228
+ GCC_except_table242
+ GCC_except_table36
+ _CBU_IsDisplayStatusAggregationEnabled
+ _CBU_IsDisplayStatusAggregationEnabled.once
+ _CBU_IsDisplayStatusAggregationEnabled.result
+ _DisplayGetBrightnessAfterForcedDynamicSliderRestriction
+ _OBJC_CLASS_$_CBBrightnessBroadcaster
+ _OBJC_CLASS_$_CBCE5
+ _OBJC_CLASS_$_CBCE5Input
+ _OBJC_CLASS_$_CBCE5Output
+ _OBJC_CLASS_$_CBDarwinStateNotifier
+ _OBJC_CLASS_$_CBDisplayStatusBroadcaster
+ _OBJC_IVAR_$_AABCHistograms._EPerAls
+ _OBJC_IVAR_$_AABCHistograms._displayID
+ _OBJC_IVAR_$_AABCHistograms._eBins
+ _OBJC_IVAR_$_BLControl._brightnessBroadcaster
+ _OBJC_IVAR_$_BLControl._displayStatusBroadcaster
+ _OBJC_IVAR_$_CBALSEvent._channelAveragedColorVendorData
+ _OBJC_IVAR_$_CBBrightnessBroadcaster._brightnessByDisplay
+ _OBJC_IVAR_$_CBBrightnessBroadcaster._hasPublished
+ _OBJC_IVAR_$_CBBrightnessBroadcaster._lastPublishedRawState
+ _OBJC_IVAR_$_CBBrightnessBroadcaster._logHandle
+ _OBJC_IVAR_$_CBBrightnessBroadcaster._manager
+ _OBJC_IVAR_$_CBBrightnessBroadcaster._notifier
+ _OBJC_IVAR_$_CBCE5._model
+ _OBJC_IVAR_$_CBCE5Input._input
+ _OBJC_IVAR_$_CBCE5Output._CBCE5_Q0_output
+ _OBJC_IVAR_$_CBCE5Output._CBCE5_Q1_output
+ _OBJC_IVAR_$_CBCE5Output._CBCE5_Q2_output
+ _OBJC_IVAR_$_CBCE5Output._CBCE5_Q3_output
+ _OBJC_IVAR_$_CBCE5Output._CBCE5_Q4_output
+ _OBJC_IVAR_$_CBCE5Output._strength_output
+ _OBJC_IVAR_$_CBCE5Output._uncertainty
+ _OBJC_IVAR_$_CBColorFilter._activeALSServices
+ _OBJC_IVAR_$_CBDarwinStateNotifier._logHandle
+ _OBJC_IVAR_$_CBDarwinStateNotifier._name
+ _OBJC_IVAR_$_CBDarwinStateNotifier._token
+ _OBJC_IVAR_$_CBDisplayContaineriOS._cbpm
+ _OBJC_IVAR_$_CBDisplayStatusBroadcaster._displayOnByDisplay
+ _OBJC_IVAR_$_CBDisplayStatusBroadcaster._hasPublished
+ _OBJC_IVAR_$_CBDisplayStatusBroadcaster._lastPublishedState
+ _OBJC_IVAR_$_CBDisplayStatusBroadcaster._logHandle
+ _OBJC_IVAR_$_CBDisplayStatusBroadcaster._manager
+ _OBJC_IVAR_$_CBDisplayStatusBroadcaster._notifier
+ _OBJC_IVAR_$_CBSliderCommitTelemetry._displayID
+ _OBJC_METACLASS_$_CBBrightnessBroadcaster
+ _OBJC_METACLASS_$_CBCE5
+ _OBJC_METACLASS_$_CBCE5Input
+ _OBJC_METACLASS_$_CBCE5Output
+ _OBJC_METACLASS_$_CBDarwinStateNotifier
+ _OBJC_METACLASS_$_CBDisplayStatusBroadcaster
+ __CLASS_METHODS_CBCoexTracker
+ __OBJC_$_CLASS_METHODS_CBCE5
+ __OBJC_$_INSTANCE_METHODS_CBBrightnessBroadcaster
+ __OBJC_$_INSTANCE_METHODS_CBCE5
+ __OBJC_$_INSTANCE_METHODS_CBCE5Input
+ __OBJC_$_INSTANCE_METHODS_CBCE5Output
+ __OBJC_$_INSTANCE_METHODS_CBDarwinStateNotifier
+ __OBJC_$_INSTANCE_METHODS_CBDisplayStatusBroadcaster
+ __OBJC_$_INSTANCE_VARIABLES_CBBrightnessBroadcaster
+ __OBJC_$_INSTANCE_VARIABLES_CBCE5
+ __OBJC_$_INSTANCE_VARIABLES_CBCE5Input
+ __OBJC_$_INSTANCE_VARIABLES_CBCE5Output
+ __OBJC_$_INSTANCE_VARIABLES_CBDarwinStateNotifier
+ __OBJC_$_INSTANCE_VARIABLES_CBDisplayStatusBroadcaster
+ __OBJC_$_PROP_LIST_CBBrightnessBroadcaster
+ __OBJC_$_PROP_LIST_CBCE5
+ __OBJC_$_PROP_LIST_CBCE5Input
+ __OBJC_$_PROP_LIST_CBCE5Output
+ __OBJC_$_PROP_LIST_CBDarwinStateNotifier
+ __OBJC_$_PROP_LIST_CBDisplayStatusBroadcaster
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBStateNotifier
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBStateNotifier
+ __OBJC_$_PROTOCOL_REFS_CBStateNotifier
+ __OBJC_CLASS_PROTOCOLS_$_CBBrightnessBroadcaster
+ __OBJC_CLASS_PROTOCOLS_$_CBCE5Input
+ __OBJC_CLASS_PROTOCOLS_$_CBCE5Output
+ __OBJC_CLASS_PROTOCOLS_$_CBDarwinStateNotifier
+ __OBJC_CLASS_PROTOCOLS_$_CBDisplayStatusBroadcaster
+ __OBJC_CLASS_RO_$_CBBrightnessBroadcaster
+ __OBJC_CLASS_RO_$_CBCE5
+ __OBJC_CLASS_RO_$_CBCE5Input
+ __OBJC_CLASS_RO_$_CBCE5Output
+ __OBJC_CLASS_RO_$_CBDarwinStateNotifier
+ __OBJC_CLASS_RO_$_CBDisplayStatusBroadcaster
+ __OBJC_LABEL_PROTOCOL_$_CBStateNotifier
+ __OBJC_METACLASS_RO_$_CBBrightnessBroadcaster
+ __OBJC_METACLASS_RO_$_CBCE5
+ __OBJC_METACLASS_RO_$_CBCE5Input
+ __OBJC_METACLASS_RO_$_CBCE5Output
+ __OBJC_METACLASS_RO_$_CBDarwinStateNotifier
+ __OBJC_METACLASS_RO_$_CBDisplayStatusBroadcaster
+ __OBJC_PROTOCOL_$_CBStateNotifier
+ __Z22shouldDarwinReactivatefff
+ __ZL13getVendorDataI32CBChannelAveragedColorVendorDataENSt3__18optionalIPT_EEP12__IOHIDEvent
+ __ZL14enabled_80_100
+ __ZL15enabled_100_135
+ __ZL15enabled_135_180
+ __ZL15reenable_80_100
+ __ZL16reenable_100_135
+ __ZL16reenable_135_180
+ __ZN4AABC20logTrustedALSSummaryEPNS_3ALSE
+ ___24-[AABCHistograms submit]_block_invoke_2
+ ___52+[CBAnalytics illuminanceHistogram:displayID:alsID:]_block_invoke
+ ___52+[CBAnalytics illuminanceHistogram:displayID:alsID:]_block_invoke_2
+ ___53+[CBAnalytics luminanceHistogram:withName:displayID:]_block_invoke
+ ___53+[CBAnalytics luminanceHistogram:withName:displayID:]_block_invoke_2
+ ___59+[CBCE5 loadContentsOfURL:configuration:completionHandler:]_block_invoke
+ ___60-[BacklightdExportedObj clientSetProperty:forKey:andHandle:]_block_invoke
+ ___66-[BrightnessSystemClientInternal setProperty:forKey:handle:error:]_block_invoke_2
+ ___67-[CBDisplayManager observeValueForKeyPath:ofObject:change:context:]_block_invoke
+ ___70-[BrightnessSystemClientInternal setSyncProperty:forKey:handle:error:]_block_invoke
+ ___CBU_IsDisplayStatusAggregationEnabled_block_invoke
+ ___DisplayApplyDynamicSliderRestriction
+ ____ZN4AABC20logTrustedALSSummaryEPNS_3ALSE_block_invoke
+ ___block_descriptor_40_e8_32bs_e27_v24?0"CBCE5"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32o_e45_v32?0"NSNumber"8"CBHistogramBuilder"16^B24ls32l8
+ ___block_descriptor_40_e8_32o_e45_v32?0"NSString"8"CBHistogramBuilder"16^B24ls32l8
+ ___block_descriptor_56_e8_32o40o48o_e34_v32?0Q8"NSString"16"NSNumber"24ls32l8s40l8s48l8
+ ___block_descriptor_56_e8_32o_e35_v24?0^{__IOHIDServiceClient=}8^v16ls32l8
+ ___block_descriptor_72_e8_32o40o48o56o64r_e5_v8?0ls32l8r64l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32o40o48o56o_e26_"NSMutableDictionary"8?0ls32l8s40l8s48l8s56l8
- +[CBAnalytics illuminanceHistogram:]
- +[CBAnalytics luminanceHistogram:withName:]
- -[BLControl newPowerManagement:]
- -[CBCEModule setModelInputWithXtalkArr:alsArr:alsRatioArr:X:Y:Z:CCT:u:v:lux:nits:iTime:gain:x:y:a:b:ceInput:]
- -[CBColorPolicyFilter biLinearInterpBetweenIndices:forPoint1:andPoint2:]
- -[CBColorPolicyFilter interpolateBetweenX1:Y1:X2:Y2:X:]
- -[CBRingLight getTargetMinNits]
- -[CBSliderCommitTelemetry initWithQueue:andDisplayContainer:andVariant:]
- GCC_except_table190
- GCC_except_table227
- GCC_except_table241
- GCC_except_table48
- GCC_except_table55
- GCC_except_table59
- _IOMobileFramebufferGetMainDisplay
- __DisplayGetDeviceBrightnessAfterDynamicSliderAdjustment
- __ZZ14isDarwinStableE6map_80
- __ZZ14isDarwinStableE7map_100
- __ZZ14isDarwinStableE7map_180
- ___36+[CBAnalytics illuminanceHistogram:]_block_invoke
- ___36+[CBAnalytics illuminanceHistogram:]_block_invoke_2
- ___43+[CBAnalytics luminanceHistogram:withName:]_block_invoke
- ___43+[CBAnalytics luminanceHistogram:withName:]_block_invoke_2
- ___block_descriptor_32_e45_v32?0"NSString"8"CBHistogramBuilder"16^B24l
- ___block_descriptor_40_e8_32o_e34_v32?0Q8"NSString"16"NSNumber"24ls32l8
- ___block_descriptor_48_e8_32o40o_e34_v32?0Q8"NSString"16"NSNumber"24ls32l8s40l8
- ___block_descriptor_56_e8_32o40o_e19_"NSDictionary"8?0ls32l8s40l8
- ___block_descriptor_64_e8_32o40o48o_e19_"NSDictionary"8?0ls32l8s40l8s48l8
CStrings:
+ "%s: key=%@ error=%@"
+ "-[BacklightdExportedObj clientSetProperty:forKey:andHandle:]_block_invoke"
+ "AOP thresholds: DEDUP-SKIP (HL, band unchanged) brighten = %f, dim = %f; current lux = %f, current nits = %f"
+ "AOP thresholds: reset dedup memory (filter torn down) -> next AOD entry will re-push"
+ "BrightnessLevelNotifier"
+ "CBBrightnessBroadcaster - init"
+ "CBBrightnessBroadcaster init failed; UIBacklightLevelChangedNotification takeover disabled for this boot"
+ "CBCE5"
+ "CBCE_Q0_output"
+ "CBCE_Q1_output"
+ "CBCE_Q2_output"
+ "CBCE_Q3_output"
+ "CBCE_Q4_output"
+ "CBDisplayStatusBroadcaster init failed; nothing publishes the com.apple.iokit.hid.displayStatus notification for this boot"
+ "CBPM initialized in DisplayContainer"
+ "CBUIBrightnessNotificationTakenOver"
+ "CE"
+ "Clock has shifted backwards, adjusting the ramp"
+ "Could not load CBCE5.mlmodelc in the bundle resource"
+ "DisplayStatusNotifier"
+ "IlluminanceToLuminanceAggregated_AOD: E(Lux) = %f | normal L(Nits) = %f | restricted normal L(Nits) = %f | AOD L(Nits) = %f >>> L %f"
+ "Input features: %@"
+ "MinNitsPanel"
+ "Per-ALS mitigation: serviceID=%@ model=%u threshold=%f"
+ "SIL OFF @ %llu us (was ON for %llu us)"
+ "SIL ON @ %llu us"
+ "Trusted ALS updated: %{public}@"
+ "UIBacklightLevelChangedNotification"
+ "Unable to read kern.darkboot!"
+ "WARN: CBCE model %@ failed to load — copyInference will return nil"
+ "[Color Mitigation] Aggregated (active set): anyTriggered=%d minFilteredStrength=%f"
+ "[Color Mitigation] active ALS orientation=%d placement=%d triggered=%d filteredStrength=%f"
+ "[Color Mitigation] lux=%.1f nits=%.1f mitigated=%d ceEnabled=%d ceAttempted=%d source=%s confidence=%.3f threshold=%.3f crossedThreshold=%d strength=%.3f"
+ "[SIL Hint] Received MIB while SIL OFF, turning SIL ON... (mibTs=%llu, lastSILOffTs=%llu)"
+ "_model is nil, skipping inference"
+ "alsID"
+ "baseline"
+ "colorTargetX"
+ "colorTargetY"
+ "colorTargetZ"
+ "com.apple.CoreBrightness.BrightnessBroadcaster"
+ "com.apple.CoreBrightness.DisplayStatusBroadcaster"
+ "com.apple.CoreBrightness.SliderCommitTelemetry.%d"
+ "dropping departed display %{public}@"
+ "internal-%u"
+ "kern.darkboot"
+ "no valid token for %@; dropping state=%llu"
+ "non-AARMBL init: darkBoot=%d factor=%f current=%f"
+ "notify_post failed for %@ (status=%u)"
+ "notify_register_check failed for %{public}@ (status=%u)"
+ "notify_set_state failed for %@ (status=%u)"
+ "orient=%d lux=%.2f coex=%@"
+ "orientation = %d, placement = %d, color mitigation = %d, ce-model = %d, ce-threshold = %f"
+ "publishing brightness state=%llu"
+ "publishing display status state=%llu"
+ "seeding displayID=%lu on=%d"
+ "setSyncProperty"
+ "trusted={%@} "
+ "using legacy Display.m path for the com.apple.iokit.hid.displayStatus notification"
+ "v24@?0@\"CBCE5\"8@\"NSError\"16"
+ "v32@?0@\"NSNumber\"8@\"CBHistogramBuilder\"16^B24"
+ "{%@} "
- "CBDisplayIsExternal"
- "IlluminanceToLuminanceAggregated_AOD: E(Lux) = %f | normal L(Nits) = %f | AOD L(Nits) = %f >>> L %f"
- "Per-ALS CE: serviceID=%@ model=%u threshold=%f"
- "SIL OFF @ %f us (was ON for %f us)"
- "SIL ON @ %f us"
- "[Color Mitigation] ALS orientation=%d placement=%d triggered=%d filteredStrength=%f"
- "[Color Mitigation] Aggregated mitigation: count=%lu anyTriggered=%d minFilteredStrength=%f"
- "[New Event] MIB dcpRoleID mismatch! Expected: %d, Received: %d"
- "[SIL Hint] Received MIB while SIL OFF, turning SIL ON..."
- "[SIL Hint] now=%f motMet=%d shouldUseHint=%d"
- "[V2.1] Input features: %@"
- "brightness.device.current %f -> factor %f"
```
