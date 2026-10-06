## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/AirPlaySender`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x245384` | `0x24708c` | **`+0x1d08`** |
| `__DATA.__bss` | `0xe70` | `0x670` | **`-0x800`** |
| `__TEXT.__cstring` | `0x8f4b4` | `0x8fbcf` | **`+0x71b`** |
| `__AUTH_CONST.__cfstring` | `0x14c20` | `0x14e40` | **`+0x220`** |
| `__TEXT.__const` | `0x6090` | `0x6150` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x7778` | `0x7818` | **`+0xa0`** |
| `__DATA.__data` | `0x187d0` | `0x18770` | **`-0x60`** |
| `__DATA_DIRTY.__data` | `0xf18` | `0xf78` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x2ea0` | `0x2ee8` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x58a0` | `0x58e8` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x78e0` | `0x78c0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x2350` | `0x2368` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xa98` | `0xaa0` | **`+0x8`** |

### Other Changes

```diff

-980.63.2.0.0
+980.67.2.0.0

-  Functions: 11502
-  Symbols:   8648
-  CStrings:  11661
+  Functions: 11546
+  Symbols:   8686
+  CStrings:  11706
Symbols:
+ GCC_except_table128
+ GCC_except_table48
+ GCC_except_table49
+ _APEndpointCreateDecoratedName
+ _APTNANDataSessionGetRSSI
+ _APTransportDeviceCopyNANDataSession
+ _APTransportDeviceIsTransportRecommended
+ _APTransportTrafficCaptureFlushForSysdiagnose
+ _CFAppendPrintF
+ _CFDateFormatterCreateISO8601Formatter
+ _CFDateFormatterCreateStringWithAbsoluteTime
+ _CFDateFormatterSetProperty
+ _CFTimeZoneCopySystem
+ _OUTLINED_FUNCTION_271
+ _OUTLINED_FUNCTION_272
+ _OUTLINED_FUNCTION_273
+ _OUTLINED_FUNCTION_274
+ _OUTLINED_FUNCTION_275
+ _OUTLINED_FUNCTION_276
+ _OUTLINED_FUNCTION_277
+ _OUTLINED_FUNCTION_278
+ _OUTLINED_FUNCTION_279
+ _OUTLINED_FUNCTION_280
+ ___APEndpointManagerCarPlayCreate_block_invoke_4
+ ___apsession_startNANRSSISamplingIfNeeded_block_invoke
+ ___apsession_startNANRSSISamplingIfNeeded_block_invoke_2
+ ___block_descriptor_41_e5_v8?0l
+ ___carEndpoint_Activate_block_invoke_4
+ ___copy_assignment_8_8_pa0_25192_0_pa0_56546_8_pa0_42274_16
+ ___screenstreamudp_handleClearScreen_block_invoke
+ _apsession_connectionTypeToTransportDeviceAddressType
+ _apsession_copyNANRSSIHistogramString
+ _apsession_getNANRSSI
+ _bufferedAudioEngine_maybeTriggerTerminusAcquisitionMissedTTR.sNextDialogTicks
+ _carEndpoint_shouldPublishDiagnosticInfo
+ _carManager_ensuredDictionarySetValue
+ _endpointCluster_copyDecoratedName
+ _endpoint_copyDecoratedName
+ _kAPEndpointCarPlayCreationOption_TransportTrafficCapture
+ _kAPEndpointStreamAudioEngineCreationOption_IsCarPlay
+ _kAPSAudioProtocolDriverHoseProperty_SupportsTerminus
+ _kAPSenderSessionCreationOption_IsAuxiliaryScreenSession
+ _kAPSenderSessionProperty_NANRSSIHistogram
+ _kAPSenderSessionStreamKey_MulticastGroupInfo
+ _kAPTransportTrafficCaptureCreationOption_CaptureDirectory
+ _kCFDateFormatterTimeZone
- GCC_except_table127
- GCC_except_table23
- GCC_except_table46
- GCC_except_table47
- ___carEndpoint_getTrafficCaptureFileName_block_invoke
- _carEndpoint_getTrafficCaptureFileName.fullFileName
- _carEndpoint_getTrafficCaptureFileName.once
- _carEndpoint_getTrafficCaptureFileName.tempDir
CStrings:
+ "%@ [%@]"
+ "980.67.2"
+ "APEndpointManagerCarPlayCreate_block_invoke_3"
+ "APEndpointManagerCarPlayTrafficCapture"
+ "APTransportTrafficCaptureCreate failed: %#m\n"
+ "Activation failed, endpointStatus error or dissociate"
+ "AirPlay Issue"
+ "BAE [%{ptr}] %sInvoking TTR for terminus acquisition missed\n"
+ "BAE [%{ptr}] %sThrottling terminus acquisition missed TTR\n"
+ "BAE [%{ptr}] %speriodic measured latencies - frontLatency: %u rearLatency: %u; current configured HAL latencies frontMs: %u rearMs: %u\n"
+ "BES [%{ptr}] isTerminusSupported=%s supportsTerminusAPAT=%s\n"
+ "Boolean apsession_isTransportRecommended(APSenderSessionRef, APSenderSessionConnectionType)"
+ "CarPlaySnoops"
+ "DeviceID: %llu\n"
+ "Endpoint: %@\n"
+ "Error: %#m\n"
+ "Failed to attach traffic capture to sender session (continuing): %#m\n"
+ "IsAuxiliaryScreenSession"
+ "NAN connection attempt failed causing Infra fallback\n\n"
+ "NANRSSIHistogram"
+ "Name: %@\n"
+ "OSStatus APEndpointManagerCarPlayCreate(CFAllocatorRef, CFDictionaryRef, FigEndpointManagerRef *)_block_invoke_3"
+ "OSStatus carEndpoint_Activate(FigEndpointRef, FigEndpointFeatures, CFDictionaryRef, FigEndpointActivationCompletionCallback, void *)_block_invoke_4"
+ "PairedSessionEnded"
+ "Reason: %#{flags}\n"
+ "Sender: %@\n"
+ "Session: %{ptr}\n"
+ "TTR: APSenderSessionAirPlay: NAN Failure with Infra Fallback"
+ "TTR: Terminus Acquisition Missed"
+ "Terminus acquisition missed"
+ "Time: %@\n"
+ "Traffic capture session not started (continuing without capture): %#m\n"
+ "[%{ptr}] %@ is%s recommended?{end} with err=%#m"
+ "[%{ptr}] NAN RSSI sample: %lld dBm (count=%ld)\n"
+ "[%{ptr}] Should perform key exchange: %s\n"
+ "[%{ptr}] Skipping transport recommendation check as usage is not mirroring"
+ "[%{ptr}] Sysdiagnose block is called\n"
+ "[%{ptr}] endpointStatus error or dissociate occurred during Activation: %d\n"
+ "airPlayDescription_isCarPlaySpatialAudioSupported"
+ "apsession_isTransportRecommended"
+ "apsession_startNANRSSISamplingIfNeeded"
+ "bufferedAudioEngine_maybeTriggerTerminusAcquisitionMissedTTR"
+ "discoveryNANRSSI"
+ "includeTransportTypeInEndpointName"
+ "isAuxiliaryScreenSession"
+ "isCarPlay"
+ "multicastGroupInfo"
+ "nanRSSIHist"
+ "nanRSSIHistogram"
+ "screenstreamudp_handleClearScreenInternal"
+ "setupMulticastGroupInfo"
+ "trafficCapture"
+ "void apsession_sampleNANRSSI(APSenderSessionRef)"
+ "void bufferedAudioEngine_maybeTriggerTerminusAcquisitionMissedTTR(FigEndpointStreamAudioEngineRef)"
+ "void screenstreamudp_handleClearScreenInternal(CFTypeRef, Boolean)"
- "%s%s"
- "980.63.2"
- "APEndpointManagerCarPlayCreate_block_invoke_2"
- "Activation failed, endpointStatus error "
- "AirPlayCarPlaySnoop.atslite"
- "BAE [%{ptr}] %speriodic measured latencies - frontLatency: %u rearLatency: %u\n"
- "OSStatus carEndpoint_Activate(FigEndpointRef, FigEndpointFeatures, CFDictionaryRef, FigEndpointActivationCompletionCallback, void *)_block_invoke_2"
- "[%{ptr}] endpointStatus error occured during Activation: %d\n"
- "screenstreamudp_handleClearScreen"
- "void screenstreamudp_handleClearScreen(CFTypeRef, Boolean)"
```
