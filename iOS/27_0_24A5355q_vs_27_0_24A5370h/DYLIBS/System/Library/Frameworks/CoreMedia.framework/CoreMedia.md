## CoreMedia

> `/System/Library/Frameworks/CoreMedia.framework/CoreMedia`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2dc60c` | `0x2dd758` | **`+0x114c`** |
| `__TEXT.__cstring` | `0x5fb4a` | `0x5ff2a` | **`+0x3e0`** |
| `__AUTH_CONST.__const` | `0xcb18` | `0xce80` | **`+0x368`** |
| `__AUTH_CONST.__cfstring` | `0x1d2a0` | `0x1d360` | **`+0xc0`** |
| `__TEXT.__const` | `0xa718` | `0xa798` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x7890` | `0x78e8` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0x2658` | `0x26a8` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xbc40` | `0xbc70` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x1a70` | `0x1aa0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x32d41` | `0x32d67` | **`+0x26`** |
| `__TEXT.__swift5_proto` | `0x768` | `0x780` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2468` | `0x2460` | **`-0x8`** |
| `__DATA.__data` | `0x2cf8` | `0x2d00` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x278` | `0x27c` | **`+0x4`** |

### Other Changes

```diff

-3350.58.3.11.1
+3350.63.2.11.1

-  Functions: 17220
-  Symbols:   12696
-  CStrings:  15255
+  Functions: 17263
+  Symbols:   12742
+  CStrings:  15272
Symbols:
+ _FigAudioDeviceClockServerStart.callbacks
+ _FigCustomURLLoaderServerStart.callbacks
+ _FigEndpointManagerStartServerEx.callbacks
+ _FigEndpointMessengerStartServer.callbacks
+ _FigEndpointPlaybackSessionRemoteXPC_InvalidateEx
+ _FigEndpointPlaybackSessionStartServer.callbacks
+ _FigEndpointRemoteControlSessionStartServer.callbacks
+ _FigEndpointStartServerEx.callbacks
+ _FigEndpointStreamStartServer.callbacks
+ _FigHEVCBridge_CreateLHVCFromHEVCParameterSets
+ _FigHEVCBridge_GetPPSInitQPMinus26
+ _FigHEVCBridge_GetSPSPCMEnabledFlag
+ _FigHEVCBridge_GetSliceQPDelta
+ _FigReportingSubmitPlayEndCAEvent
+ _FigReportingSubmitTranslationLanguageCAEvents
+ _FigReportingSubmitVariantEndedCAEvent
+ _FigTelemetryColorPrimariesToInteger
+ _FigTelemetryCopyStringFromFourCC
+ _FigTelemetryTransferFunctionToInteger
+ _FigTelemetryYCbCrMatrixToInteger
+ _FigTransportXPCConnectionServerStart.callbacks
+ _FigVideoFormatDescriptionCreateFromMultiLayerHEVCParameterSets
+ _OUTLINED_FUNCTION_213
+ _OUTLINED_FUNCTION_214
+ _OUTLINED_FUNCTION_215
+ _figDispatch_createRootQueueWithMachPriority.sContextKey
+ _figXPC_ServerTimeout_AudioDeviceClock
+ _figXPC_ServerTimeout_CustomURLHandler
+ _figXPC_ServerTimeout_CustomURLLoader
+ _figXPC_ServerTimeout_EndpointManager
+ _figXPC_ServerTimeout_EndpointMessenger
+ _figXPC_ServerTimeout_EndpointRemoteControlSession
+ _figXPC_ServerTimeout_MemoryOrigin
+ _figXPC_ServerTimeout_MetricEventTimeline
+ _figXPC_ServerTimeout_NeroTransportConnection
+ _figXPC_ServerTimeout_PixelBufferOrigin
+ _figXPC_ServerTimeout_ProcessStateMonitor
+ _figXPC_ServerTimeout_SandboxRegistration
+ _gFigMetricEventTimelineServerTrace_block_invoke.serverCallbacks
+ _hevcbridgeGetPPSInitQPMinus26CallbackSigned
+ _hevcbridgeGetSPSPCMEnabledCallbackFlag
+ _hevcbridgeGetSPSPCMEnabledCallbackUnsigned
+ _hevcbridgeGetSliceQPDeltaCallbackSigned
+ _kCMTextMarkupAttribute_GeneratedCaptionType
+ _kCMTextMarkupGeneratedCaptionIndicator_SFSymbolCodePointKey
+ _kCMTextMarkupGeneratedCaptionIndicator_SFSymbolNameKey
+ _kCMTextMarkupGeneratedCaptionType_Transcribed
+ _kCMTextMarkupGeneratedCaptionType_Translated
+ _kFigCAStatsReportingEventName_HLSVariantEnded
+ _kFigCAStatsReporting_PayloadKey_VariantFrameRate
+ _kFigCPECryptorXPCMsgParam_CryptorType_block_invoke.serverCallbacks
+ _kFigCaptionGeneratedCaptionType_Transcribed
+ _kFigCaptionGeneratedCaptionType_Translated
+ _kFigCaptionProperty_GeneratedCaptionType
+ _kFigProcessStateMonitorXPCMsgParam_LastPurgeEvent_block_invoke.callbacks
- _FigCopyCGColorSRGBAsArray
- _FigCreateCGColorSRGBFromArray
- _figDispatch_copyRootQueueWithPriorityAndClientPID.sFigDispatchRootQueueContextKey
- _hevcbridgeCreateLHVCFromHEVCParameterSets
- _kCMTextMarkupGeneratedCaptionIndicatorSFSymbolCodePointKey
- _kCMTextMarkupGeneratedCaptionIndicatorSFSymbolNameKey
- _kFigXPCRemoteClientOption_XPCInstanceUUID
- _kFigXPCServerOption_XPCInstanceUUIDForMediaDaemons
- _xpc_connection_set_oneshot_instance
CStrings:
+ "<< FigReadScheduler >> %s: RS %s committed batch %p expedite: reads already in-flight, nothing to expedite"
+ "Attempting to remove a buffer queue trigger during a trigger callback -- this is prohibited because it's impossible to satisfy the postcondition of CMBufferQueueRemoveTrigger that the trigger callback will not be running.  Generally this indicates that it's necessary to dispatch so that the removal begins after the trigger callback returns."
+ "CMGeneratedCaptionIndicator_SFSymbolCodePoint"
+ "CMGeneratedCaptionIndicator_SFSymbolName"
+ "CMGeneratedCaptionType"
+ "CMGeneratedCaptionType_Transcribed"
+ "CMGeneratedCaptionType_Translated"
+ "FigHEVCBridge_CreateLHVCFromHEVCParameterSets"
+ "FigVideoFormatDescriptionCreateFromMultiLayerHEVCParameterSets"
+ "GeneratedCaptionType"
+ "GeneratedCaptionType_Transcribed"
+ "GeneratedCaptionType_Translated"
+ "com.apple.streaming.HLSVariantEnded"
+ "eventCountByClassXPCArray count does not match maxNoOfClasses"
+ "frameRate"
+ "hevcbridgeGetPPSInitQPMinus26CallbackSigned"
+ "hevcbridgeGetSPSPCMEnabledCallbackFlag"
+ "hevcbridgeGetSPSPCMEnabledCallbackUnsigned"
+ "hevcbridgeGetSliceQPDeltaCallbackSigned"
+ "maxNoOfClasses out of range"
+ "no lhvCDataOut"
+ "not a kFigCaptionGeneratedCaptionType_Transcribed or kFigCaptionGeneratedCaptionType_Translated"
+ "poly_order_minus1 expected to be 0 or 1"
+ "{hevcbridgeParseVPSExtension} ERROR: layer_id_in_nuh out of range"
- "<<<< HEVCBridge >>>> %s: poly_order_minus1 %d, expected to be 0 or 1"
- "CMGeneratedCaptionIndicatorSFSymbolCodePoint"
- "CMGeneratedCaptionIndicatorSFSymbolName"
- "hevcbridgeCreateLHVCFromHEVCParameterSets"
- "null value is not serializable"
- "xpcRemoteClientOption_XPCInstanceUUID"
- "xpcServerOption_XPCInstanceUUIDForMediaDaemons"
```
