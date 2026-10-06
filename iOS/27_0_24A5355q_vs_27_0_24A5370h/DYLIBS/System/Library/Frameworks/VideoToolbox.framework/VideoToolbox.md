## VideoToolbox

> `/System/Library/Frameworks/VideoToolbox.framework/VideoToolbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72c85c` | `0x723900` | **`-0x8f5c`** |
| `__TEXT.__cstring` | `0x43f45` | `0x44205` | **`+0x2c0`** |
| `__TEXT.__eh_frame` | `0x7904` | `0x7b44` | **`+0x240`** |
| `__AUTH_CONST.__cfstring` | `0x25c00` | `0x25d00` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x2d7ef` | `0x2d8b8` | **`+0xc9`** |
| `__DATA.__data` | `0x884` | `0x944` | **`+0xc0`** |
| `__DATA.__bss` | `0x10b0` | `0x1130` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x4e010` | `0x4e078` | **`+0x68`** |
| `__AUTH_CONST.__auth_got` | `0x2038` | `0x2098` | **`+0x60`** |
| `__DATA_DIRTY.__common` | `0x150` | `0x1b0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x4178` | `0x41c8` | **`+0x50`** |
| `__DATA.__common` | `0x2e8` | `0x308` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x4c8` | `0x4b0` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x5fe0` | `0x5fc8` | **`-0x18`** |
| `__DATA_DIRTY.__data` | `0x2b8` | `0x2c0` | **`+0x8`** |

### Other Changes

```diff

-3350.58.3.11.1
+3350.63.2.11.1

-  Functions: 10372
-  Symbols:   10933
-  CStrings:  10660
+  Functions: 10559
+  Symbols:   10980
+  CStrings:  10681
Symbols:
+ GCC_except_table85
+ _CGColorSpaceCreateWithICCData
+ _CGColorSpaceGetID
+ _FigHEVCBridge_GetSPSPCMEnabledFlag
+ _FigTelemetryColorPrimariesToInteger
+ _FigTelemetryCopyStringFromFourCC
+ _FigTelemetryTransferFunctionToInteger
+ _FigTelemetryYCbCrMatrixToInteger
+ _FigXPCCommonServerTimeoutHandler
+ _FigXPCConnectionSendSyncMessage
+ _FigXPCRemoteClientCreateSecondaryConnection
+ _FigXPCRemoteClientCreateWithXPCService
+ _FigXPCServerStartWithClientXPCConnection
+ _OUTLINED_FUNCTION_225
+ _OUTLINED_FUNCTION_226
+ _OUTLINED_FUNCTION_227
+ _OUTLINED_FUNCTION_228
+ _OUTLINED_FUNCTION_229
+ _OUTLINED_FUNCTION_230
+ _OUTLINED_FUNCTION_231
+ _OUTLINED_FUNCTION_232
+ _OUTLINED_FUNCTION_233
+ _OUTLINED_FUNCTION_234
+ _OUTLINED_FUNCTION_235
+ _VTDecompressionSessionServerStartXPC.callbacks
+ _VTDecompressionSessionServerStartXPCWithConnection
+ _VTMetalTransferSessionGetKind
+ _VTMetalTransferSessionGetKind.sKindOnce
+ _VTMetalTransferSessionRegisterKindOnce
+ _VTPixelSessionTelemetry_ColorSpaceIDFromICCProfile
+ _VTPixelSessionTelemetry_GetPathStat
+ _VTPixelSessionTelemetry_PathIndexFromChain
+ _VTPixelSessionTelemetry_ScalingModeIndexFromString
+ _VTPixelTransferNodeCelesteRotationGetKind
+ _VTPixelTransferNodeCelesteRotationGetKind.sKindOnce
+ _VTPixelTransferNodeCelesteRotationRegisterKindOnce
+ _VTPixelTransferNodeDynamicGetKind
+ _VTPixelTransferNodeDynamicGetKind.sKindOnce
+ _VTPixelTransferNodeDynamicRegisterKindOnce
+ _VTPixelTransferNodeGetKind
+ _VTPixelTransferNodeRotationGetKind
+ _VTPixelTransferNodeRotationGetKind.sKindOnce
+ _VTPixelTransferNodeRotationRegisterKindOnce
+ _VTPixelTransferNodeScalerGetKind
+ _VTPixelTransferNodeScalerGetKind.sKindOnce
+ _VTPixelTransferNodeScalerRegisterKindOnce
+ _VTPixelTransferNodeSoftwareGetKind
+ _VTPixelTransferNodeSoftwareGetKind.sKindOnce
+ _VTPixelTransferNodeSoftwareRegisterKindOnce
+ _checkMetalTransferTrace
+ _checkPixelRotationTrace
+ _checkPixelTransferTrace
+ _checkTileCompressionSessionTrace
+ _checkTileDecompressionSessionTrace
+ _checkVideoDecoderCapabilitiesTrace
+ _checkVideoDecoderSelectionTrace
+ _figXPC_ServerTimeout_VTDecompressionSession
+ _gVTDecompressionSessionXPCRemoteConnection2
+ _kFigReportingEventKey_VTDS_SourceHEVCPCMEnabled
+ _kFigReportingEventKey_VTPTR_DestinationColorPrimaries
+ _kFigReportingEventKey_VTPTR_DestinationYCbCrMatrix
+ _kFigReportingEventKey_VTPTR_ErrorCode
+ _kFigReportingEventKey_VTPTR_SourceColorPrimaries
+ _kFigReportingEventKey_VTPTR_SourceYCbCrMatrix
+ _kFigXPCServerOption_AllowSecondaryConnections
+ _kVTCompressionPropertyKey_EnableResumableEncoding
+ _kVTCompressionPropertyKey_FinalEncoderState
+ _kVTCompressionPropertyKey_InitialEncoderState
+ _kVTCompressionPropertyKey_RecommendedResumableSegmentMinimumDuration
+ _kVTCompressionPropertyKey_RecommendedResumableSegmentMinimumFrameCount
+ _kVTDecompressionSessionOption_UseCloudVideocodecService
+ _sVTMetalTransferSessionKind
+ _sVTPixelTransferNodeCelesteRotationKind
+ _sVTPixelTransferNodeDynamicKind
+ _sVTPixelTransferNodeRotationKind
+ _sVTPixelTransferNodeScalerKind
+ _sVTPixelTransferNodeSoftwareKind
+ _vtByteFillColumnY16
+ _vtCompressionSessionValidateEnableResumableEncoding
+ _vtMetalPixelFormatHasSubsampledHeight
+ _vtPixelTransferNodeRegisterKind
+ _vtPixelTransferNodeRegisterKind.sNextKind
- GCC_except_table82
- _hardwareSupportsYUVS.checked
- _hardwareSupportsYUVS.hasSupport
- _kFigXPCRemoteClientOption_XPCInstanceUUID
- _kVTDecompressionPropertyKey_XPCInstanceUUIDForMediaDaemons
- _kVTDecompressionSessionOption_XPCInstanceUUIDForMediaDaemons
- _scalerCapabilities.hasSupportIn_2plane10bit420
- _scalerCapabilities.hasSupportIn_2plane10bit422
- _scalerCapabilities.hasSupportIn_2plane10bit444
- _scalerCapabilities.hasSupportIn_2planePacked10bit420
- _scalerCapabilities.hasSupportIn_2planePacked10bit422
- _scalerCapabilities.hasSupportIn_2planePacked10bit444
- _scalerCapabilities.hasSupportIn_L008
- _scalerCapabilities.hasSupportIn_L016
- _scalerCapabilities.hasSupportIn_b3a8
- _scalerCapabilities.hasSupportIn_mediaCompression
- _scalerCapabilities.hasSupportIn_universalCompression
- _scalerCapabilities.hasSupportIn_w30r
- _scalerCapabilities.hasSupportOut_2plane10bit420
- _scalerCapabilities.hasSupportOut_2plane10bit422
- _scalerCapabilities.hasSupportOut_2plane10bit444
- _scalerCapabilities.hasSupportOut_2planePacked10bit420
- _scalerCapabilities.hasSupportOut_2planePacked10bit422
- _scalerCapabilities.hasSupportOut_2planePacked10bit444
- _scalerCapabilities.hasSupportOut_L008
- _scalerCapabilities.hasSupportOut_L016
- _scalerCapabilities.hasSupportOut_b3a8
- _scalerCapabilities.hasSupportOut_colorConversion
- _scalerCapabilities.hasSupportOut_mediaCompression
- _scalerCapabilities.hasSupportOut_w30r
- _scalerCapabilities.hasSupportsFractionalDimensions
- _scalerCapabilities.maxHDownscale
- _scalerCapabilities.maxHUpscale
- _scalerCapabilities.maxVDownscale
- _scalerCapabilities.maxVUpscale
CStrings:
+ "/System/Library/VideoDecoders/AVD.videodecoder_ps"
+ "<<<< DecompressionSessionXPCServer >>>> %s: VTDecompressionSessionXPCWithClientXPCConnection server starting."
+ "<<<< ParavirtualizedVideoDecoder >>>> %s: %p decoderSession %p guest %@ %c%c%c%c (%zd bytes)"
+ "<<<< ParavirtualizedVideoDecoder >>>> %s: decoder %p decoderSession %p %c%c%c%c %d x %d -> %d"
+ "<<<< ParavirtualizedVideoDecoder >>>> %s: decoder %p decoderSession %p frame %d: status %d decodeFlags 0x%x pixelBuffer %p -> %d"
+ "<<<< ParavirtualizedVideoDecoder >>>> %s: decoder %p frame %p: codecType %c%c%c%c sbuf PTS %1.3f, %zd bytes, decodeFlags 0x%x, frameOptions %@"
+ "<<<< ParavirtualizedVideoEncoder >>>> %s: encoder %p guest UUID %{private}@, codecType %c%c%c%c, encoderID %{private}@ -> %d, guestProtocolVersion %u hostProtocolVersion %u hostInfo %{public}@, guestBuildVersion %{public}@"
+ "<<<< VTParavirtualization >>>> %s: guest %@ %c%c%c%c (%zd bytes)%s%s"
+ "DVPEnhancements"
+ "EnableResumableEncoding"
+ "EnableResumableEncoding should be a CFBoolean"
+ "FinalEncoderState"
+ "InitialEncoderState"
+ "RecommendedResumableSegmentMinimumDuration"
+ "RecommendedResumableSegmentMinimumFrameCount"
+ "SourceColorPrimaries"
+ "SourceHEVCPCMEnabled"
+ "SourceYCbCrMatrix"
+ "UseCloudVideocodecService"
+ "VTCompression"
+ "VTDecompression"
+ "VTDecompressionSessionServerStartXPCWithConnection"
+ "VTPixelTransfer"
+ "VTUtilities"
+ "com.apple.coremedia.cloudvideocodecservice.decompressionsession.xpc"
+ "description=CoreMedia_VideoToolbox-3350.63.2.11.1"
+ "kVTCompressionPropertyKey_EnableResumableEncoding cannot be set after encoding has started"
+ "kVTCompressionPropertyKey_EnableResumableEncoding not supported"
+ "vtCompressionSessionValidateEnableResumableEncoding"
- "<<<< DecompressionSessionRemote >>>> %s: (%p) EventLink not used for UUID based XPC setup"
- "<<<< ParavirtualizedVideoDecoder >>>> %s: %p %c%c%c%c (%zd bytes)"
- "<<<< ParavirtualizedVideoDecoder >>>> %s: frame %d: status %d decodeFlags 0x%x pixelBuffer %p -> %d"
- "<<<< ParavirtualizedVideoDecoder >>>> %s: frame %p: codecType %c%c%c%c sbuf PTS %1.3f, %zd bytes, decodeFlags 0x%x, frameOptions %@"
- "<<<< ParavirtualizedVideoEncoder >>>> %s: guest UUID %{private}@, codecType %c%c%c%c, encoderID %{private}@ -> %d, guestProtocolVersion %u hostProtocolVersion %u hostInfo %{public}@, guestBuildVersion %{public}@"
- "<<<< VTParavirtualization >>>> %s: %c%c%c%c (%zd bytes)%s%s"
- "XPCInstanceUUIDForMediaDaemons"
- "description=CoreMedia_VideoToolbox-3350.58.3.11.1"
```
