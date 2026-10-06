## MediaToolbox

> `/System/Library/Frameworks/MediaToolbox.framework/MediaToolbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__lazy_helpers` | `0x24c` | `0x3600` | **`+0x33b4`** |
| `__TEXT.__text` | `0x1035654` | `0x10369c8` | **`+0x1374`** |
| `__TEXT.__oslogstring` | `0x169e22` | `0x16a743` | **`+0x921`** |
| `__AUTH_CONST.__const` | `0x47378` | `0x47c38` | **`+0x8c0`** |
| `__AUTH_CONST.__lazy_load_got` | `0x30` | `0x4d8` | **`+0x4a8`** |
| `__AUTH_CONST.__auth_got` | `0x5fd0` | `0x5d00` | **`-0x2d0`** |
| `__TEXT.__const` | `0x29bb0` | `0x298e0` | **`-0x2d0`** |
| `__DATA_CONST.__const` | `0x24ae0` | `0x24868` | **`-0x278`** |
| `__AUTH_CONST.__cfstring` | `0x53680` | `0x534c0` | **`-0x1c0`** |
| `__DATA_CONST.__got` | `0x4950` | `0x4900` | **`-0x50`** |
| `__TEXT.__cstring` | `0x13f1e7` | `0x13f227` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x5990` | `0x59c8` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x2490` | `0x24c0` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x1e7c` | `0x1e4c` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x15630` | `0x15658` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x2b64` | `0x2b84` | **`+0x20`** |
| `__DATA.__data` | `0x3370` | `0x338c` | **`+0x1c`** |
| `__DATA.__bss` | `0x5378` | `0x5368` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x518` | `0x520` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3bc` | `0x3c0` | **`+0x4`** |

### Other Changes

```diff

-3350.58.3.11.1
+3350.63.2.11.1

-  - /System/Library/Frameworks/CoreHaptics.framework/CoreHaptics

-  - /System/Library/Frameworks/CoreTelephony.framework/CoreTelephony

-  - /System/Library/Frameworks/ImageIO.framework/ImageIO
-  - /System/Library/Frameworks/MediaAccessibility.framework/MediaAccessibility
-  - /System/Library/Frameworks/Metal.framework/Metal
-  - /System/Library/Frameworks/MetalPerformanceShaders.framework/MetalPerformanceShaders

-  - /System/Library/Frameworks/OpenGLES.framework/OpenGLES

-  - /System/Library/Frameworks/WirelessInsights.framework/WirelessInsights

-  - /System/Library/PrivateFrameworks/AppleJPEG.framework/AppleJPEG

-  - /System/Library/PrivateFrameworks/CMPhoto.framework/CMPhoto

-  - /System/Library/PrivateFrameworks/CoreWiFi.framework/CoreWiFi

-  - /System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/IOMobileFramebuffer

-  - /System/Library/PrivateFrameworks/IdleTimerServices.framework/IdleTimerServices

-  - /usr/lib/libAudioStatistics.dylib
-  - /usr/lib/libCTGreenTeaLogger.dylib

-  Functions: 53221
-  Symbols:   45271
-  CStrings:  57278
+  Functions: 53312
+  Symbols:   45647
+  CStrings:  57289
Symbols:
+ -[FigTranslationModelAvailabilityState lastListenerCreationTime_ns]
+ GCC_except_table135
+ GCC_except_table142
+ GCC_except_table152
+ GCC_except_table188
+ GCC_except_table194
+ GCC_except_table197
+ GCC_except_table198
+ GCC_except_table205
+ GCC_except_table216
+ GCC_except_table217
+ GCC_except_table253
+ GCC_except_table265
+ GCC_except_table273
+ GCC_except_table277
+ GCC_except_table300
+ GCC_except_table301
+ GCC_except_table303
+ GCC_except_table307
+ GCC_except_table310
+ GCC_except_table319
+ GCC_except_table329
+ GCC_except_table339
+ GCC_except_table340
+ GCC_except_table343
+ GCC_except_table367
+ GCC_except_table382
+ GCC_except_table419
+ _CAReportingClientRequestMessage$lazyAuthGOT_IA_ad_0
+ _CAReportingClientRequestMessage$lazyLoadStub
+ _CAReportingClientSendMessage$lazyAuthGOT_IA_0
+ _CAReportingClientSendMessage$lazyAuthGOT_IA_0$loadHelper_x8
+ _CAReportingClientSendMessage$lazyAuthGOT_IA_ad_0
+ _CAReportingClientSendMessage$lazyLoadStub
+ _CHHapticEngineOptionKeyLocality$lazyGOT
+ _CHHapticEngineOptionKeyLocality$lazyGOT$loadHelper_x8
+ _CHHapticLocalityDefault$lazyGOT
+ _CHHapticLocalityDefault$lazyGOT$loadHelper_x8
+ _CHHapticLocalityDefaultWithFullStrength$lazyGOT
+ _CHHapticLocalityDefaultWithFullStrength$lazyGOT$loadHelper_x8
+ _CHHapticLocalityFullGamut$lazyGOT
+ _CHHapticLocalityFullGamut$lazyGOT$loadHelper_x8
+ _CMPhotoJPEGPreload$lazyAuthGOT_IA_0
+ _CMPhotoJPEGPreload$lazyAuthGOT_IA_0$loadHelper_x8
+ _CMPhotoJPEGPreload$lazyAuthGOT_IA_ad_0
+ _CMPhotoJPEGPreload$lazyLoadStub
+ _CWFEventLinkQualityMetricKey$lazyGOT
+ _CWFEventLinkQualityMetricKey$lazyGOT$loadHelper_x8
+ _CreateFormatReaderWithTimeout
+ _EnsurePlaylistCache
+ _FigAssetCacheInspectorStartServer.callbacks
+ _FigAssetDownloaderStartServer.callbacks
+ _FigAssetImageGeneratorServerStart.callbacks
+ _FigAssetServerStart.callbacks
+ _FigCPEProtectorServerStart.callbacks
+ _FigCPEServerStart.callbacks
+ _FigControlCommandsStartServer.callbacks
+ _FigEndpointStreamAudioEngineStartServer.callbacks
+ _FigFormatReaderServerStart.callbacks
+ _FigFormatReaderServerStartLoopbackServerAndCopyXPCEndpoint.callbacks
+ _FigFormatReaderServerStartWithConnection
+ _FigFreeAndStrndup
+ _FigInMemoryDeserializerCopyCFData
+ _FigMutableCompositionServerStart.callbacks
+ _FigMutableMovieServerStart.callbacks
+ _FigNeroidStartServer.callbacks
+ _FigPlayerServerStart.callbacks
+ _FigRemakerServerStart.callbacks
+ _FigReportingSubmitPlayEndCAEvent
+ _FigReportingSubmitTranslationLanguageCAEvents
+ _FigReportingSubmitVariantEndedCAEvent
+ _FigSampleBufferConsumerStartServer.callbacks
+ _FigSampleBufferProviderStartServer.callbacks
+ _FigSampleGeneratorServerStart.callbacks
+ _FigShouldForceTranscription
+ _FigStreamingCacheDisableStreamDiskAccess
+ _FigStreamingCacheIsMediaPlaylistCached
+ _FigTelemetryColorPrimariesToInteger
+ _FigTelemetryTransferFunctionToInteger
+ _FigTelemetryYCbCrMatrixToInteger
+ _FigVideoCompositorServerStart.callbacks
+ _FigVirtualDisplaySessionServerStart.callbacks
+ _FigVisualContextServerStart.callbacks
+ _FigXPCRemoteClientCreateWithXPCService
+ _FigXPCServerStartWithClientXPCConnection
+ _IOMobileFramebufferCopyProperty$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferCopyProperty$lazyLoadStub
+ _IOMobileFramebufferCreateDisplayList$lazyAuthGOT_IA_0
+ _IOMobileFramebufferCreateDisplayList$lazyAuthGOT_IA_0$loadHelper_x8
+ _IOMobileFramebufferCreateDisplayList$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferCreateDisplayList$lazyLoadStub
+ _IOMobileFramebufferDisableHotPlugDetectNotifications$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferDisableHotPlugDetectNotifications$lazyLoadStub
+ _IOMobileFramebufferDisableVSyncNotifications$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferDisableVSyncNotifications$lazyLoadStub
+ _IOMobileFramebufferEnableHotPlugDetectNotifications$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferEnableHotPlugDetectNotifications$lazyLoadStub
+ _IOMobileFramebufferEnableVSyncNotifications$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferEnableVSyncNotifications$lazyLoadStub
+ _IOMobileFramebufferGetDigitalOutState$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferGetDigitalOutState$lazyLoadStub
+ _IOMobileFramebufferGetDisplaySize$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferGetDisplaySize$lazyLoadStub
+ _IOMobileFramebufferGetHotPlugRunLoopSource$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferGetHotPlugRunLoopSource$lazyLoadStub
+ _IOMobileFramebufferGetID$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferGetID$lazyLoadStub
+ _IOMobileFramebufferGetProtectionOptions$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferGetProtectionOptions$lazyLoadStub
+ _IOMobileFramebufferGetSecondaryDisplay$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferGetSecondaryDisplay$lazyLoadStub
+ _IOMobileFramebufferGetSupportedDigitalOutModes$lazyAuthGOT_IA_0
+ _IOMobileFramebufferGetSupportedDigitalOutModes$lazyAuthGOT_IA_0$loadHelper_x8
+ _IOMobileFramebufferGetSupportedDigitalOutModes$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferGetSupportedDigitalOutModes$lazyLoadStub
+ _IOMobileFramebufferGetVSyncRunLoopSource$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferGetVSyncRunLoopSource$lazyLoadStub
+ _IOMobileFramebufferInstallVirtualDisplays$lazyAuthGOT_IA_0
+ _IOMobileFramebufferInstallVirtualDisplays$lazyAuthGOT_IA_0$loadHelper_x8
+ _IOMobileFramebufferInstallVirtualDisplays$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferInstallVirtualDisplays$lazyLoadStub
+ _IOMobileFramebufferOpenByName$lazyAuthGOT_IA_0
+ _IOMobileFramebufferOpenByName$lazyAuthGOT_IA_0$loadHelper_x22
+ _IOMobileFramebufferOpenByName$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferOpenByName$lazyLoadStub
+ _IOMobileFramebufferSetDigitalOutMode$lazyAuthGOT_IA_0
+ _IOMobileFramebufferSetDigitalOutMode$lazyAuthGOT_IA_0$loadHelper_x8
+ _IOMobileFramebufferSetDigitalOutMode$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferSetDigitalOutMode$lazyLoadStub
+ _IOMobileFramebufferSetDisplayDevice$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferSetDisplayDevice$lazyLoadStub
+ _IOMobileFramebufferSwapBegin$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferSwapBegin$lazyLoadStub
+ _IOMobileFramebufferSwapEnd$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferSwapEnd$lazyLoadStub
+ _IOMobileFramebufferSwapSetBackgroundColor$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferSwapSetBackgroundColor$lazyLoadStub
+ _IOMobileFramebufferSwapSetLayer$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferSwapSetLayer$lazyLoadStub
+ _IOMobileFramebufferSwapWait$lazyAuthGOT_IA_ad_0
+ _IOMobileFramebufferSwapWait$lazyLoadStub
+ _MAAudibleMediaCopyPreferredCharacteristics$lazyAuthGOT_IA_0
+ _MAAudibleMediaCopyPreferredCharacteristics$lazyAuthGOT_IA_0$loadHelper_x8
+ _MAAudibleMediaCopyPreferredCharacteristics$lazyAuthGOT_IA_ad_0
+ _MAAudibleMediaCopyPreferredCharacteristics$lazyLoadStub
+ _MACaptionAppearanceCopyBackgroundColor$lazyAuthGOT_IA_0
+ _MACaptionAppearanceCopyBackgroundColor$lazyAuthGOT_IA_0$loadHelper_x2$for$_FigStringConformerCreateResolvedBackgroundARGBColorArrayUsingMAXColorAndOpacity+0
+ _MACaptionAppearanceCopyBackgroundColor$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceCopyBackgroundColor$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceCopyBackgroundColor$lazyLoadStub
+ _MACaptionAppearanceCopyFontDescriptorForLanguage$lazyAuthGOT_IA_0
+ _MACaptionAppearanceCopyFontDescriptorForLanguage$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceCopyFontDescriptorForLanguage$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceCopyFontDescriptorForLanguage$lazyLoadStub
+ _MACaptionAppearanceCopyFontDescriptorForStyle$lazyAuthGOT_IA_0
+ _MACaptionAppearanceCopyFontDescriptorForStyle$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceCopyFontDescriptorForStyle$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceCopyFontDescriptorForStyle$lazyLoadStub
+ _MACaptionAppearanceCopyForegroundColor$lazyAuthGOT_IA_0
+ _MACaptionAppearanceCopyForegroundColor$lazyAuthGOT_IA_0$loadHelper_x2$for$_FigStringConformerCreateResolvedForegroundARGBColorArrayUsingMAXColorAndOpacity+0
+ _MACaptionAppearanceCopyForegroundColor$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceCopyForegroundColor$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceCopyForegroundColor$lazyLoadStub
+ _MACaptionAppearanceCopyPreferredCaptioningMediaCharacteristics$lazyAuthGOT_IA_0
+ _MACaptionAppearanceCopyPreferredCaptioningMediaCharacteristics$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceCopyPreferredCaptioningMediaCharacteristics$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceCopyPreferredCaptioningMediaCharacteristics$lazyLoadStub
+ _MACaptionAppearanceCopySelectedLanguages$lazyAuthGOT_IA_0
+ _MACaptionAppearanceCopySelectedLanguages$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceCopySelectedLanguages$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceCopySelectedLanguages$lazyLoadStub
+ _MACaptionAppearanceCopyStrokeColor$lazyAuthGOT_IA_0
+ _MACaptionAppearanceCopyStrokeColor$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceCopyStrokeColor$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceCopyStrokeColor$lazyLoadStub
+ _MACaptionAppearanceCopyWindowColor$lazyAuthGOT_IA_0
+ _MACaptionAppearanceCopyWindowColor$lazyAuthGOT_IA_0$loadHelper_x2$for$_FigStringConformerCreateResolvedWindowARGBColorArrayUsingMAXColorAndOpacity+0
+ _MACaptionAppearanceCopyWindowColor$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceCopyWindowColor$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceCopyWindowColor$lazyLoadStub
+ _MACaptionAppearanceExecuteBlockForProfileID$lazyAuthGOT_IA_0
+ _MACaptionAppearanceExecuteBlockForProfileID$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceExecuteBlockForProfileID$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceExecuteBlockForProfileID$lazyLoadStub
+ _MACaptionAppearanceGetBackgroundOpacity$lazyAuthGOT_IA_0
+ _MACaptionAppearanceGetBackgroundOpacity$lazyAuthGOT_IA_0$loadHelper_x3$for$_FigStringConformerCreateResolvedBackgroundARGBColorArrayUsingMAXColorAndOpacity+8
+ _MACaptionAppearanceGetBackgroundOpacity$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceGetBackgroundOpacity$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceGetBackgroundOpacity$lazyLoadStub
+ _MACaptionAppearanceGetDisplayType$lazyAuthGOT_IA_0
+ _MACaptionAppearanceGetDisplayType$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceGetDisplayType$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceGetDisplayType$lazyLoadStub
+ _MACaptionAppearanceGetForegroundOpacity$lazyAuthGOT_IA_0
+ _MACaptionAppearanceGetForegroundOpacity$lazyAuthGOT_IA_0$loadHelper_x3$for$_FigStringConformerCreateResolvedForegroundARGBColorArrayUsingMAXColorAndOpacity+8
+ _MACaptionAppearanceGetForegroundOpacity$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceGetForegroundOpacity$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceGetForegroundOpacity$lazyLoadStub
+ _MACaptionAppearanceGetRelativeCharacterSize$lazyAuthGOT_IA_0
+ _MACaptionAppearanceGetRelativeCharacterSize$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceGetRelativeCharacterSize$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceGetRelativeCharacterSize$lazyLoadStub
+ _MACaptionAppearanceGetRelativeCharacterSizeForLanguage$lazyAuthGOT_IA_0
+ _MACaptionAppearanceGetRelativeCharacterSizeForLanguage$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceGetRelativeCharacterSizeForLanguage$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceGetRelativeCharacterSizeForLanguage$lazyLoadStub
+ _MACaptionAppearanceGetStrokeWidth$lazyAuthGOT_IA_0
+ _MACaptionAppearanceGetStrokeWidth$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceGetStrokeWidth$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceGetStrokeWidth$lazyLoadStub
+ _MACaptionAppearanceGetStrokeWidthForProfileID$lazyAuthGOT_IA_0
+ _MACaptionAppearanceGetStrokeWidthForProfileID$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceGetStrokeWidthForProfileID$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceGetStrokeWidthForProfileID$lazyLoadStub
+ _MACaptionAppearanceGetTextEdgeStyle$lazyAuthGOT_IA_0
+ _MACaptionAppearanceGetTextEdgeStyle$lazyAuthGOT_IA_0$loadHelper_x23
+ _MACaptionAppearanceGetTextEdgeStyle$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceGetTextEdgeStyle$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceGetTextEdgeStyle$lazyLoadStub
+ _MACaptionAppearanceGetWindowOpacity$lazyAuthGOT_IA_0
+ _MACaptionAppearanceGetWindowOpacity$lazyAuthGOT_IA_0$loadHelper_x3$for$_FigStringConformerCreateResolvedWindowARGBColorArrayUsingMAXColorAndOpacity+8
+ _MACaptionAppearanceGetWindowOpacity$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceGetWindowOpacity$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceGetWindowOpacity$lazyLoadStub
+ _MACaptionAppearanceGetWindowRoundedCornerRadius$lazyAuthGOT_IA_0
+ _MACaptionAppearanceGetWindowRoundedCornerRadius$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearanceGetWindowRoundedCornerRadius$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearanceGetWindowRoundedCornerRadius$lazyLoadStub
+ _MACaptionAppearancePrefCopyActiveProfileID$lazyAuthGOT_IA_0
+ _MACaptionAppearancePrefCopyActiveProfileID$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearancePrefCopyActiveProfileID$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearancePrefCopyActiveProfileID$lazyLoadStub
+ _MACaptionAppearancePrefCopyDisplayTypeEnumForBundleID$lazyAuthGOT_IA_0
+ _MACaptionAppearancePrefCopyDisplayTypeEnumForBundleID$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearancePrefCopyDisplayTypeEnumForBundleID$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearancePrefCopyDisplayTypeEnumForBundleID$lazyLoadStub
+ _MACaptionAppearancePrefCopyPreferAccessibleCaptions$lazyAuthGOT_IA_0
+ _MACaptionAppearancePrefCopyPreferAccessibleCaptions$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearancePrefCopyPreferAccessibleCaptions$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearancePrefCopyPreferAccessibleCaptions$lazyLoadStub
+ _MACaptionAppearancePrefCopyProfileName$lazyAuthGOT_IA_0
+ _MACaptionAppearancePrefCopyProfileName$lazyAuthGOT_IA_0$loadHelper_x8
+ _MACaptionAppearancePrefCopyProfileName$lazyAuthGOT_IA_ad_0
+ _MACaptionAppearancePrefCopyProfileName$lazyLoadStub
+ _MTAudioProcessingTapServerStart.callbacks
+ _MovieInformationCopyConstituentFileURLs
+ _OBJC_CLASS_$_CHHapticEngine$lazyGOT
+ _OBJC_CLASS_$_CHHapticEngine$lazyGOT$loadHelper_x24
+ _OBJC_CLASS_$_CHHapticPattern$lazyGOT
+ _OBJC_CLASS_$_CHHapticPattern$lazyGOT$loadHelper_x20
+ _OBJC_CLASS_$_CTBundle$lazyGOT
+ _OBJC_CLASS_$_CTBundle$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_CTXPCServiceSubscriptionContext$lazyGOT
+ _OBJC_CLASS_$_CTXPCServiceSubscriptionContext$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_CWFInterface$lazyGOT
+ _OBJC_CLASS_$_CWFInterface$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_CoreTelephonyClient$lazyGOT
+ _OBJC_CLASS_$_CoreTelephonyClient$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_EAGLContext$lazyGOT
+ _OBJC_CLASS_$_EAGLContext$lazyGOT$loadHelper_x21
+ _OBJC_CLASS_$_EAGLContext$lazyGOT$loadHelper_x24
+ _OBJC_CLASS_$_EAGLContext$lazyGOT$loadHelper_x25
+ _OBJC_CLASS_$_EAGLContext$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_ITIdleTimerState$lazyGOT
+ _OBJC_CLASS_$_ITIdleTimerState$lazyGOT$loadHelper_x21
+ _OBJC_CLASS_$_NSRegularExpression
+ _OBJC_CLASS_$_WISServicePredictionProvider$lazyGOT
+ _OBJC_CLASS_$_WISServicePredictionProvider$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$__LTTextInput$lazyGOT$loadHelper_x20
+ _OBJC_IVAR_$_FigTranslationModelAvailabilityState._lastListenerCreationTime_ns
+ _URLAssetFormatReaderCreationTimeout
+ ___fpic_PerformPrimaryItemJoin_block_invoke
+ ___fpic_WrappedPlayerDidChange_block_invoke_2
+ ___remoteFormatReaderClient_setOrCheckClientPrivateServerOS_block_invoke
+ __block_invoke.serverCallbacks
+ _ckCreateStringWithBalancedLineBreakIfNeeded
+ _ct_green_tea_logger_create$lazyAuthGOT_IA_ad_0
+ _ct_green_tea_logger_create$lazyLoadStub
+ _dqs_StartServer.sFigDataQueueServerCallbacks
+ _fanoutconsumer_evictAudioBuffersAfterL1TimeAndMaybeTransitionID
+ _fbapspManager_copyFlushRangeEndSbufMarkerCallback
+ _figPlayerInterstitialEvent_hash
+ _figXPC_ServerTimeout_Asset
+ _figXPC_ServerTimeout_AssetCacheInspector
+ _figXPC_ServerTimeout_AssetDownloader
+ _figXPC_ServerTimeout_AssetImageGenerator
+ _figXPC_ServerTimeout_BufferedAirPlayGlobalRoutingRegistry
+ _figXPC_ServerTimeout_ByteStream
+ _figXPC_ServerTimeout_CPE
+ _figXPC_ServerTimeout_CPEProtector
+ _figXPC_ServerTimeout_CaptionGroupConverterFromSampleBuffer
+ _figXPC_ServerTimeout_ContentKeySession
+ _figXPC_ServerTimeout_ControlCommands
+ _figXPC_ServerTimeout_DataQueue
+ _figXPC_ServerTimeout_FairplayPSSHAtomParser
+ _figXPC_ServerTimeout_FormatReader
+ _figXPC_ServerTimeout_JSONParser
+ _figXPC_ServerTimeout_MTAudioProcessingTap
+ _figXPC_ServerTimeout_Manifold
+ _figXPC_ServerTimeout_MediaparserdUtilities
+ _figXPC_ServerTimeout_MutableComposition
+ _figXPC_ServerTimeout_MutableMovie
+ _figXPC_ServerTimeout_Neroid
+ _figXPC_ServerTimeout_PlaylistFileParser
+ _figXPC_ServerTimeout_Remaker
+ _figXPC_ServerTimeout_SampleBufferConsumer
+ _figXPC_ServerTimeout_SampleBufferProvider
+ _figXPC_ServerTimeout_SampleBufferRenderSynchronizer
+ _figXPC_ServerTimeout_SampleGenerator
+ _figXPC_ServerTimeout_SessionDataPlistParser
+ _figXPC_ServerTimeout_SteeringParser
+ _figXPC_ServerTimeout_StreamPlaylistParser
+ _figXPC_ServerTimeout_VideoCompositor
+ _figXPC_ServerTimeout_VideoQueue
+ _figXPC_ServerTimeout_VideoReceiver
+ _figXPC_ServerTimeout_VideoTarget
+ _figXPC_ServerTimeout_VirtualDisplaySession
+ _figXPC_ServerTimeout_VirtualFramebuffer
+ _figXPC_ServerTimeout_VisualContext
+ _figXPC_ServerTimeout_XMLService
+ _formatReaderServer_CreateOptions
+ _fpfsi_RefreshTracksFromCacheOrPump
+ _fpic_EventAtMomentInList
+ _fpic_EventStraddlesPrimaryMoment
+ _fpic_IsItemBufferedToMoment
+ _fpic_SwapToInterstitialPlayerLayerOnJoinIfIndicated
+ _fvfbserv_startServer.callbacks
+ _gFigCaptionGroupConverterServerTrace_block_invoke.serverCallbacks
+ _gFigContentKeyBossServerTrace_block_invoke.serverCallbacks
+ _gFigFairplayPSSHAtomParserServerTrace_block_invoke.serverCallbacks
+ _gFigJSONParserServerTrace_block_invoke.serverCallbacks
+ _gFigManifoldServerTrace_block_invoke.serverCallbacks
+ _gFigManifoldServerTrace_block_invoke_2.class
+ _gFigMediaparserdUtilitiesServerTrace_block_invoke.serverCallbacks
+ _gFigSteeringParserServerTrace_block_invoke.serverCallbacks
+ _gFigStreamPlaylistParserServerTrace_block_invoke.serverCallbacks
+ _gFigStreamPlaylistParserServerTrace_block_invoke_2.class
+ _gFigXMLServiceServerTrace_block_invoke.serverCallbacks
+ _gSessionDataParserServerTrace_block_invoke.serverCallbacks
+ _getCTGreenTeaOsLogHandle$lazyAuthGOT_IA_ad_0
+ _getCTGreenTeaOsLogHandle$lazyLoadStub
+ _glActiveTexture$lazyAuthGOT_IA_ad_0
+ _glActiveTexture$lazyLoadStub
+ _glAttachShader$lazyAuthGOT_IA_ad_0
+ _glAttachShader$lazyLoadStub
+ _glBindFramebuffer$lazyAuthGOT_IA_ad_0
+ _glBindFramebuffer$lazyLoadStub
+ _glBindTexture$lazyAuthGOT_IA_ad_0
+ _glBindTexture$lazyLoadStub
+ _glBlendColor$lazyAuthGOT_IA_ad_0
+ _glBlendColor$lazyLoadStub
+ _glBlendEquation$lazyAuthGOT_IA_ad_0
+ _glBlendEquation$lazyLoadStub
+ _glBlendFunc$lazyAuthGOT_IA_ad_0
+ _glBlendFunc$lazyLoadStub
+ _glBlendFuncSeparate$lazyAuthGOT_IA_ad_0
+ _glBlendFuncSeparate$lazyLoadStub
+ _glCheckFramebufferStatus$lazyAuthGOT_IA_ad_0
+ _glCheckFramebufferStatus$lazyLoadStub
+ _glClear$lazyAuthGOT_IA_ad_0
+ _glClear$lazyLoadStub
+ _glClearColor$lazyAuthGOT_IA_ad_0
+ _glClearColor$lazyLoadStub
+ _glCompileShader$lazyAuthGOT_IA_ad_0
+ _glCompileShader$lazyLoadStub
+ _glCreateProgram$lazyAuthGOT_IA_ad_0
+ _glCreateProgram$lazyLoadStub
+ _glCreateShader$lazyAuthGOT_IA_ad_0
+ _glCreateShader$lazyLoadStub
+ _glDeleteFramebuffers$lazyAuthGOT_IA_ad_0
+ _glDeleteFramebuffers$lazyLoadStub
+ _glDeleteProgram$lazyAuthGOT_IA_ad_0
+ _glDeleteProgram$lazyLoadStub
+ _glDeleteRenderbuffers$lazyAuthGOT_IA_ad_0
+ _glDeleteRenderbuffers$lazyLoadStub
+ _glDeleteShader$lazyAuthGOT_IA_ad_0
+ _glDeleteShader$lazyLoadStub
+ _glDeleteTextures$lazyAuthGOT_IA_ad_0
+ _glDeleteTextures$lazyLoadStub
+ _glDisable$lazyAuthGOT_IA_ad_0
+ _glDisable$lazyLoadStub
+ _glDrawArrays$lazyAuthGOT_IA_ad_0
+ _glDrawArrays$lazyLoadStub
+ _glEnable$lazyAuthGOT_IA_ad_0
+ _glEnable$lazyLoadStub
+ _glEnableVertexAttribArray$lazyAuthGOT_IA_ad_0
+ _glEnableVertexAttribArray$lazyLoadStub
+ _glFinish$lazyAuthGOT_IA_ad_0
+ _glFinish$lazyLoadStub
+ _glFlush$lazyAuthGOT_IA_ad_0
+ _glFlush$lazyLoadStub
+ _glFramebufferTexture2D$lazyAuthGOT_IA_ad_0
+ _glFramebufferTexture2D$lazyLoadStub
+ _glGenFramebuffers$lazyAuthGOT_IA_ad_0
+ _glGenFramebuffers$lazyLoadStub
+ _glGenRenderbuffers$lazyAuthGOT_IA_ad_0
+ _glGenRenderbuffers$lazyLoadStub
+ _glGenTextures$lazyAuthGOT_IA_ad_0
+ _glGenTextures$lazyLoadStub
+ _glGetAttribLocation$lazyAuthGOT_IA_ad_0
+ _glGetAttribLocation$lazyLoadStub
+ _glGetProgramiv$lazyAuthGOT_IA_ad_0
+ _glGetProgramiv$lazyLoadStub
+ _glGetShaderiv$lazyAuthGOT_IA_ad_0
+ _glGetShaderiv$lazyLoadStub
+ _glGetString$lazyAuthGOT_IA_ad_0
+ _glGetString$lazyLoadStub
+ _glGetUniformLocation$lazyAuthGOT_IA_ad_0
+ _glGetUniformLocation$lazyLoadStub
+ _glLinkProgram$lazyAuthGOT_IA_ad_0
+ _glLinkProgram$lazyLoadStub
+ _glScissor$lazyAuthGOT_IA_ad_0
+ _glScissor$lazyLoadStub
+ _glShaderSource$lazyAuthGOT_IA_ad_0
+ _glShaderSource$lazyLoadStub
+ _glTexImage2D$lazyAuthGOT_IA_ad_0
+ _glTexImage2D$lazyLoadStub
+ _glTexParameteri$lazyAuthGOT_IA_ad_0
+ _glTexParameteri$lazyLoadStub
+ _glUniform1f$lazyAuthGOT_IA_ad_0
+ _glUniform1f$lazyLoadStub
+ _glUniform1i$lazyAuthGOT_IA_ad_0
+ _glUniform1i$lazyLoadStub
+ _glUniform2f$lazyAuthGOT_IA_ad_0
+ _glUniform2f$lazyLoadStub
+ _glUniformMatrix3fv$lazyAuthGOT_IA_ad_0
+ _glUniformMatrix3fv$lazyLoadStub
+ _glUniformMatrix4fv$lazyAuthGOT_IA_ad_0
+ _glUniformMatrix4fv$lazyLoadStub
+ _glUseProgram$lazyAuthGOT_IA_ad_0
+ _glUseProgram$lazyLoadStub
+ _glVertexAttribPointer$lazyAuthGOT_IA_ad_0
+ _glVertexAttribPointer$lazyLoadStub
+ _glViewport$lazyAuthGOT_IA_ad_0
+ _glViewport$lazyLoadStub
+ _itemairplay_publishPlaybackModeSwitchEvent
+ _itemfig_PostNotificationAndReleaseItem
+ _kCMTextMarkupAttribute_GeneratedCaptionType
+ _kCMTextMarkupGeneratedCaptionIndicator_SFSymbolCodePointKey
+ _kCMTextMarkupGeneratedCaptionIndicator_SFSymbolNameKey
+ _kCMTextMarkupGeneratedCaptionType_Transcribed
+ _kCMTextMarkupGeneratedCaptionType_Translated
+ _kCTRegistrationStatusNotRegistered$lazyGOT
+ _kCTRegistrationStatusNotRegistered$lazyGOT$loadHelper_x8
+ _kCTRegistrationStatusSearching$lazyGOT
+ _kCTRegistrationStatusSearching$lazyGOT$loadHelper_x8
+ _kEAGLContextPropertyAccelerated$lazyGOT
+ _kEAGLContextPropertyAccelerated$lazyGOT$loadHelper_x8
+ _kFVDSourceNotificationKey_Error
+ _kFigAssetReaderCreationOption_UseCloudMediaServices
+ _kFigBufferedAirPlayGlobalRoutingRegistryXPCMsgParam_RemoteClientID_block_invoke.callbacks
+ _kFigBufferedAirPlaySubPipeManagerCreateOption_SourceToken
+ _kFigBufferedAirPlaySubPipeManagerParameter_SourceToken
+ _kFigByteStreamXPCMsgParam_OtherProcessPID_block_invoke.callbacks
+ _kFigByteStreamXPCMsgParam_OtherProcessPID_block_invoke_2.sFigServedByteStreamStateClass
+ _kFigCAStatsReportingEventName_FilePlayEnd
+ _kFigCAStatsReportingEventName_HLSPlayEnd
+ _kFigCKSXPCMsgParam_ExternalProtectionStatusForCryptor_block_invoke.serverCallbacks
+ _kFigCaptionGeneratedCaptionType_Transcribed
+ _kFigCaptionGeneratedCaptionType_Translated
+ _kFigCaptionProperty_GeneratedCaptionType
+ _kFigFormatReaderInstantiationOption_UseCloudMediaParserService
+ _kFigTrialFactor_LiveActivityCooldown100PercentMS
+ _kFigVideoQueueXPCMsgParam_VideoTargetIDArray_block_invoke.callbacks
+ _kFigVideoTargetXPCMsgParam_LoggingIdentifier_block_invoke.callbacks
+ _kMAAudibleMediaSettingsChangedNotification$lazyGOT
+ _kMAAudibleMediaSettingsChangedNotification$lazyGOT$loadHelper_x19
+ _kMACaptionAppearanceSettingsChangedNotification$lazyGOT
+ _kMACaptionAppearanceSettingsChangedNotification$lazyGOT$loadHelper_x19
+ _kVTCompressionPropertyKey_EnableResumableEncoding
+ _kVTDecompressionSessionOption_UseCloudVideocodecService
+ _kVideoMediaConverter2Option_ClientPrivateServerOS
+ _lazyLoadFlag$CMPhoto
+ _lazyLoadFlag$CoreHaptics
+ _lazyLoadFlag$CoreTelephony
+ _lazyLoadFlag$CoreWiFi
+ _lazyLoadFlag$IOMobileFramebuffer
+ _lazyLoadFlag$IdleTimerServices
+ _lazyLoadFlag$MediaAccessibility
+ _lazyLoadFlag$OpenGLES
+ _lazyLoadFlag$WirelessInsights
+ _lazyLoadFlag$libAudioStatistics.dylib
+ _lazyLoadFlag$libCTGreenTeaLogger.dylib
+ _noop
+ _pcmToCaptionRP_sendOneCaptionDownstream
+ _sbcbq_evictAudioBuffersAfterL1TimeAndMaybeTransitionID
+ _segPumpAlternateForStream
+ _segPumpGetCurrentEstimatedMediaBitrate
- GCC_except_table134
- GCC_except_table143
- GCC_except_table153
- GCC_except_table187
- GCC_except_table193
- GCC_except_table195
- GCC_except_table196
- GCC_except_table203
- GCC_except_table214
- GCC_except_table215
- GCC_except_table252
- GCC_except_table264
- GCC_except_table269
- GCC_except_table274
- GCC_except_table298
- GCC_except_table299
- GCC_except_table302
- GCC_except_table305
- GCC_except_table308
- GCC_except_table311
- GCC_except_table318
- GCC_except_table328
- GCC_except_table33
- GCC_except_table336
- GCC_except_table337
- GCC_except_table341
- GCC_except_table366
- GCC_except_table381
- GCC_except_table417
- _EnsureStreamingCache
- _FigStreamingCacheClearExclusiveWriter
- _FigStreamingCacheSetExclusiveWriter
- _FreeStreamingCacheTransferRec
- _ITIdleTimerStateClass
- _InternalURLAssetEnsurePersistentStreamingCacheCreated
- _InternalURLAssetTransferPersistentStreamingCacheAsync
- _OBJC_CLASS_$__LTTextInput$lazyGOT$loadHelper_x19
- _OUTLINED_FUNCTION_2023
- _OUTLINED_FUNCTION_2024
- _OUTLINED_FUNCTION_2025
- _OUTLINED_FUNCTION_2026
- _OUTLINED_FUNCTION_2027
- _OUTLINED_FUNCTION_2028
- _OUTLINED_FUNCTION_2029
- _OUTLINED_FUNCTION_2030
- _PerformCompleteTransferStreamingCache
- _PerformTransferStreamingCacheAsync
- _URLAssetTransferPersistentStreamingCacheAsync
- ___copy_constructor_8_8_t0w8_pa0_45604_8_pa0_22587_16_pa0_57319_24_pa0_49646_32_pa0_60888_40_pa0_27920_48
- ___copy_helper_block_8_32n85_8_8_t0w8_pa0_45604_8_pa0_22587_16_pa0_57319_24_pa0_49646_32_pa0_60888_40_pa0_27920_48
- ___destroy_helper_block_8_32
- ___dworch_downloadMedia_validateDownloadIsPlayableOfflineOnQueue_block_invoke
- ___fbapop_requestForRetransmissionToRenderPipeline_block_invoke
- ___fpic_ConfigureLiveJoinPreloads_block_invoke
- ___remoteFormatReaderClient_maybeSetAndCopyXPCInstanceUUIDForAllFormatReaders_block_invoke
- _dworch_downloadMedia_validateDownloadIsPlayableOffline
- _dworch_downloadMedia_validateDownloadIsPlayableOfflineDispatch
- _dworch_downloadMedia_validateDownloadIsPlayableOfflineOnQueue
- _dworch_downloadMetadata_proceedAfterCheckingDestinationURLDispatch
- _dworch_downloadMetadata_proceedAfterCheckingDestinationURLOnQueue
- _dworch_persistMetadata_gotAccessToDestinationURLCallbackGuts
- _dworch_persistMetadata_gotAccessToDestinationURLDispatch
- _dworch_persistMetadata_gotAccessToDestinationURLOnQueue
- _dworch_selectAlternates_getPumpReady
- _dworch_selectAlternates_getPumpReadyDispatch
- _dworch_selectAlternates_getPumpReadyOnQueue
- _dworch_transferPersistentStreamingCacheWithCallback
- _figAssetExportSession_CRFModeEnabled.isCRFModeEnabled
- _figAssetExportSession_CRFModeEnabled.onceToken
- _figAssetExportSession_audioCodecTypeToInteger.kTable
- _figAssetExportSession_colorPrimariesToInteger.kTable
- _figAssetExportSession_createVideoCompressionPropertiesForVideoSetting
- _figAssetExportSession_hasConstantQualityModeOverride.onceToken
- _figAssetExportSession_hasConstantQualityModeOverride.valueRef
- _figAssetExportSession_lookAheadOverride.lookAheadValue
- _figAssetExportSession_lookAheadOverride.onceToken
- _figAssetExportSession_transferFunctionToInteger.kTable
- _figAssetExportSession_videoCodecTypeToInteger.kTable
- _figAssetExportSession_yCbCrMatrixToInteger.kTable
- _fpSupport_shouldCheckColorGamutToDecideVideoRangeForMode
- _fpfs_PreserveResumeTag
- _fpfs_SubstreamNeedsFlowControl
- _fpfsi_SeekToCurrentTime
- _fpfsi_SetupManagedStreamingCache
- _fpfsi_SetupManagedStreamingCacheCallback
- _fpfsi_StartDownloadingToURLCallback
- _fpic_DoListsContainPreroll
- _fpic_SwapToInterstitialPlayerLayerIfPrerollDetected
- _fpic_SwapToPrimaryItemPlayerLayerUponPrerollCancelation
- _gFigManifoldServerTrace_block_invoke.class
- _gFigStreamPlaylistParserServerTrace_block_invoke.class
- _itemfig_DeferredPostNotificationOnDispatchQueue
- _kCMTextMarkupGeneratedCaptionIndicatorSFSymbolCodePointKey
- _kCMTextMarkupGeneratedCaptionIndicatorSFSymbolNameKey
- _kFigAssetOptionKey_XPCInstanceUUIDForMediaDaemons
- _kFigAssetProperty_DiskBackedStreamingCache
- _kFigAssetReaderCreationOption_XPCInstanceUUIDForMediaDaemons
- _kFigByteStreamXPCMsgParam_OtherProcessPID_block_invoke.sFigServedByteStreamStateClass
- _kFigFormatReaderInstantiationOption_XPCInstanceUUIDForMediaDaemons
- _kFigReportingEventKey_Export_SourceAudioCodecTypeEnum
- _kFigReportingEventKey_Export_SourceVideoCodecTypeEnum
- _kFigTrialFactor_LiveActivityCooldownMS
- _kFigXPCRemoteClientOption_XPCInstanceUUID
- _kVTDecompressionSessionOption_XPCInstanceUUIDForMediaDaemons
- _kVideoMediaConverter2Option_XPCInstanceUUIDForMediaDaemons
- _playerfig_teardownAudioRenderPipelinesForAudioSessionChange
- _remoteFormatReaderClient_maybeSetAndCopyXPCInstanceUUIDForAllFormatReaders
- _remoteFormatReaderClient_maybeSetAndCopyXPCInstanceUUIDForAllFormatReaders.onceToken
- _remoteFormatReaderClient_maybeSetAndCopyXPCInstanceUUIDForAllFormatReaders.sXPCInstanceUUID
- _sad_getPumpReadySchedulerCallbackGuts
- _segPumpEnsurePlaylistCache
- _segPumpStreamHasMediaFiles
CStrings:
+ "%@: Illegal attribute value"
+ "<< FigSBAudioRenderer >> %s: [%p] %{public}s Skipping spurious underrun begin; gap to firstEnqueuedOPTR = %1.6f s"
+ "<< StreamingCache >> %s: [%p] streamInfo disk access disabled."
+ "<<< FigAutoGeneratedCaptionIndicatorPolicy >>> %s: auto caption generation ALT text: %@ for %@ (generatedCaptionType=%@)"
+ "<<< FigAutoGeneratedCaptionIndicatorPolicy >>> %s: unexpected generatedCaptionType %@"
+ "<<< FigCaptionTranslator >>> %s: Skip creating LanguageStatusListener because installed language count > 0"
+ "<<< FigCaptionTranslator >>> %s: Skip creating LanguageStatusListener even if installed language count is 0"
+ "<<< FigCaptionTranslator >>> %s: Translation succeeded: [%@] %@ --> [%@] %@"
+ "<<< FigMediaSelectionGroups >>> %s: First user preferred language %@ lacks region code - using current user locale %@"
+ "<<< URLAsset >>> %s: [%p %{public}s] FigStreamingCacheCreate returned err %d, failed to create sessionDataPersistentCache."
+ "<<< URLAsset >>> %s: [%p %{public}s] Will not be creating a sessionDataPersistentCache."
+ "<<<< FAQ >>>> %s: [%p:%p] %s durationEnqueued = %.6f last PTS consumed = %.3f"
+ "<<<< FAQ >>>> %s: [%p:%p] %{public}s Determining whether to discard sample buffer... sbufIsOld: %d; unsupportedCombinedPlayRate: %d. %{public}s currentAQTime(scaled): %.3f currentMediaTime: %.3f startPTS: %.3f endPTS: %.3f last PTS consumed by AQ: %.3f"
+ "<<<< FAQ Offline Mixer >>>> %s: [%p] %{public}s Drain has already completed: currentTime %1.3f >= drainTime %1.3f"
+ "<<<< Fig Legible Output >>>> %s: auto caption generation: err=%d, extendedLanguageTag=%@, captionIndicatorPolicy=%p"
+ "<<<< Fig Legible Output >>>> %s: auto caption generation: generatedCaptionType from captionData=%@"
+ "<<<< FigBufferedAirPlayOutputProxy >>>> %s: [%p] %{public}s RequestForRetransmission token %u has no matching RP, ignoring (stale notification)"
+ "<<<< FigBufferedAirPlayOutputProxy >>>> %s: [%p] %{public}s rpID[%@]%s processRequestForRetransmission token=%u time=%1.3f"
+ "<<<< FigBufferedAirPlaySubPipeManager >>>> %s: [%p] %{public}@ Found FlushRangeEnd marker sbuf: %p"
+ "<<<< FigBufferedAirPlaySubPipeManager >>>> %s: [%p] %{public}@ Preserve FlushRangeEnd sbuf marker %p in input buffer queue"
+ "<<<< FigBufferedAirPlaySubPipeManager >>>> %s: [%p] %{public}@ SourceToken not found in creation options"
+ "<<<< FigBufferedAirPlaySubPipeManager >>>> %s: [%p] %{public}@ SubPipeManager in WaitingForMixStart - FlushFromTime received. Resetting to Idle so isReadyToMix returns false."
+ "<<<< FigCaptionRendererCaption >>>> %s: ckCreateStringWithBalancedLineBreakIfNeeded result: %@"
+ "<<<< FigCaptionRendererSession >>>> %s: Purging %ld stale captions from timeline on player item change"
+ "<<<< FigFilePlayer >>>> %s: <%p|%{public}s> item cancelled; suppressing PlayableRangeChanged"
+ "<<<< FigFilePlayer >>>> %s: <%p|%{public}s> item cancelled; suppressing deferred BufferFull"
+ "<<<< FigFilePlayer >>>> %s: <%p|%{public}s> player gone; suppressing deferred BufferFull"
+ "<<<< FigPlaybackCoordinator >>>> %s: %p [%d]: group time falls after end of last segment. player time for stream %f"
+ "<<<< FigPlaybackCoordinator >>>> %s: %p [%d]: group time falls before start of first segment. player time for stream %f. original time %f"
+ "<<<< FigPlayerInterstitial >>>> %s: %p: event %@ - seekTime %f past duration - cancel initiated seekID %d"
+ "<<<< FigPlayerInterstitial >>>> %s: %p: possible event detected at join, swapping to interstitial player layer"
+ "<<<< FigPlayerInterstitial >>>> %s: %p:%s event at join;%s flip to primary"
+ "<<<< FigPlayerInterstitial >>>> %s: created coordinationMediaSelectionCriteria %@ from selectedMediaOptions %@"
+ "<<<< FigPlayerInterstitial >>>> %s: joined after event %p with primary timeline end of %f"
+ "<<<< FigPlayerOverlap >>>> %s: [%p|%{public}s] Overlap is not scheduled, nothing to do"
+ "<<<< FigPlayer_AP >>>> %s: [%p] %{public}s Skipping redundant setRateAirPlay: rate %.3f unchanged in coordinated playback"
+ "<<<< FigPlayer_AP >>>> %s: [%p] %{public}s cannot create MetricPlaybackModeSwitchEvent with mode %d, err = %d"
+ "<<<< FigPlayer_AP >>>> %s: [%p] %{public}s cannot publish MetricPlaybackModeSwitchEvent with mode %d, err = %d"
+ "<<<< FigPlayer_AP >>>> %s: [%p] %{public}s published MetricPlaybackModeSwitchEvent with mode %d"
+ "<<<< FigStreamPlayer >>>> %s: [%p|%{public}s] <%p|%{public}s>: jumping from L2 {%lld/%d=%1.3f} (L3 {%lld/%d=%1.3f}) to L2 zero (L3 {%lld/%d=%1.3f}) before start"
+ "<<<< SBufConsumerInputForBufferedAirPlayOutput >>>> %s: [%p][%p][%@](avsync) Discontinuity(diff %1.3f(%lld/%d)). SampleBuffer %p, lastSbufEndOPTS %1.3f(%lld/%d), sbufOPts %1.3f(%lld/%d)"
+ "<<<< SampleBufferConsumerBQ >>>> %s: (%p) evicting audio buffers after L1 time %1.3f transitionID %ld"
+ "<<<< fbarprocessor >>>> %s: [%p] %{public}@ (avsync) Discontinuity(diff %1.3f(%lld/%d)). lastSbufEndOPTS %1.3f(%lld/%d) sendingOPTS %1.3f(%lld/%d)"
+ "<SEGPUMP> %s: %{public}@: dropped %zu stranded accumBB bytes at new request prepare"
+ "<SEGPUMP> %s: %{public}@:%ld: %s cache id is %ld %{public}@"
+ "<SEGPUMP> %s: %{public}@:%ld: oldMediaStreamCacheID: %ld no read access for stream on new cache: %@"
+ "<SEGPUMP> %s: %{public}@:%ld: oldMediaStreamCacheID: %ld, newMediaStreamCacheID: %ld"
+ "<dw-media> %s: %p %{public}@: created persistent pump cache %p."
+ "<dw-orch> %s: %p %{public}@: invalidating pump cache: %p"
+ "AssetReader_UseCloudMediaServices"
+ "CA"
+ "ClientPrivateServerOS"
+ "Could not allocate constituentFileURLs"
+ "CreateFormatReaderWithTimeout"
+ "CreateSessionDataPersistentCacheIfNeeded"
+ "EnsurePlaylistCache"
+ "FigFormatReaderServerStartWithConnection"
+ "FigStreamingCacheDisableStreamDiskAccess"
+ "FigStreamingCacheIsMediaPlaylistCached"
+ "FormatReader creation took longer than 110 seconds"
+ "FormatReader server already started"
+ "Instantiation_UseCloudMediaParserService"
+ "MovieInformationCopyConstituentFileURLs"
+ "NULL consumer"
+ "NULL outConstituentFileURLs"
+ "SMD_Complete"
+ "SourceToken"
+ "StreamingAssetPropertyLoader %s: playlistCache is NULL, falling back to network for playlist loading"
+ "StreamingAssetPropertyLoader %s: sessionDataPersistentCache is NULL, falling back to network for session data"
+ "Transcribed: "
+ "Transcription"
+ "Translated: "
+ "Translation"
+ "URLAssetFormatReaderCreationTimeoutQueue"
+ "US"
+ "\\n+"
+ "ckCreateStringWithBalancedLineBreakIfNeeded"
+ "clientPrivateServerOS=true requested but process already committed to false"
+ "com.apple.coremedia.cloudmediaparserservice-formatreader"
+ "com.apple.coremedia.cloudmediaparserservice.formatreader.xpc"
+ "fbapop_requestForRetransmissionToRenderPipeline"
+ "fbapspManager_copyFlushRangeEndSbufMarkerCallback"
+ "fpic_ConfigureLiveJoinPreloads"
+ "fpic_EventAtMomentInList"
+ "fpic_PerformPrimaryItemJoin_block_invoke"
+ "fpic_SwapToInterstitialPlayerLayerOnJoinIfIndicated"
+ "invalid unknown cache"
+ "isPlaylistCachedOut NULL"
+ "itemairplay_publishPlaybackModeSwitchEvent"
+ "itemfig_PostNotificationAndReleaseItem"
+ "kFigAssetError_FormatReaderCreationTimedOut"
+ "kFigBytePumpError_InternalError"
+ "liveActivityCooldown100PercentMS"
+ "multiNewlineRegex compilation failed"
+ "no persistent cache ID for stream"
+ "no playlist cache ID for stream"
+ "playlist"
+ "playlistCacheCreateOptions alloc failed"
+ "propertyValue for kCMTextMarkupAttribute_GeneratedCaptionType is not supported"
+ "received numSampleSizeEntries is out of expected range"
+ "received numSampleSizeEntries is too big"
+ "received numSampleSizeEntries times sizeof(size_t) overflows"
+ "received numSampleTimingEntries is out of expected range"
+ "received numSampleTimingEntries is too big"
+ "received numSampleTimingEntries times sizeof(CMSampleTimingInfo) overflows"
+ "received numSamplesIncluded is out of expected range"
+ "received sampleSizeEntriesLengthInAdditionalData exceeds reply additionalData"
+ "received sampleTimingEntriesLengthInAdditionalData exceeds reply additionalData"
+ "remoteFormatReaderClient_setOrCheckClientPrivateServerOS"
+ "sad_getPumpReadySchedulerCallback"
+ "sbcbq_evictAudioBuffersAfterL1TimeAndMaybeTransitionID"
+ "segPumpPrepareMediaConnectionForNewRequest"
+ "streamInfo disk access disabled."
+ "streamURL NULL"
+ "translationModelAvailabilityState is nil"
+ "trun sample count accumulation would overflow int32_t"
- "<< StreamingCache >> %s: [%p] clearing writer %p, current writer %p"
- "<< StreamingCache >> %s: [%p] setting writer %p, current writer %p"
- "<<< FigAutoGeneratedCaptionIndicatorPolicy >>> %s: auto caption generation ALT text: %@ for %@"
- "<<< FigCaptionTranslator >>> %s: [%@] Translation succeeded: %@ --> [%@] %@"
- "<<< FigMediaSelectionGroups >>> %s: suppressing transcription because asset is audio-only"
- "<<< URLAsset >>> %s: Copying disk cache %p from asset %p"
- "<<< URLAsset >>> %s: [%p %{public}s] FigStreamingCacheCreate returned err %d, will fall back to network"
- "<<<< DISPLAYSLEEPSUPPORT >>>> %s: Cannot do assertions since IdleTimerAssertion framework does not exist \n"
- "<<<< FAQ >>>> %s: [%p:%p] %s durationEnqueued = %.6f"
- "<<<< FAQ >>>> %s: [%p:%p] %{public}s Determining whether to discard sample buffer... sbufIsOld: %d; unsupportedCombinedPlayRate: %d. %{public}s currentMediaTime: %.3f startPTS: %.3f endPTS: %.3f"
- "<<<< Fig Legible Output >>>> %s: auto caption generation: propErr=%d, extendedLanguageTag=%@, captionIndicatorPolicy=%p"
- "<<<< Fig Legible Output >>>> %s: auto caption generation: propErr=%d, isAutoGenerated=%d, stringsToPush count=%ld"
- "<<<< FigAssetExportSession >>>> %s: [EXP]:Unknown color primaries: %{public}@"
- "<<<< FigAssetExportSession >>>> %s: [EXP]:Unknown transfer function: %{public}@"
- "<<<< FigAssetExportSession >>>> %s: [EXP]:Unknown yCbCrMatrix: %{public}@"
- "<<<< FigAssetExportSession >>>> %s: [EXP]:Unrecognized audio format ID: %c%c%c%c"
- "<<<< FigAssetExportSession >>>> %s: [EXP]:Unrecognized video codec type: %c%c%c%c"
- "<<<< FigBufferedAirPlayOutputProxy >>>> %s: [%p] %{public}s rpID[%@]%s processRequestForRetransmission for subpipeManager[%@], time=%1.3f"
- "<<<< FigPlaybackCoordinator >>>> %s: %p [%d]: group time falls after end of last segment. player time for live stream %f"
- "<<<< FigPlaybackCoordinator >>>> %s: %p [%d]: group time falls before start of first segment. player time for live stream %f. original time %f"
- "<<<< FigPlayerInterstitial >>>> %s: %p: preroll event detected, swapping to interstitial player layer"
- "<<<< FigPlayerInterstitial >>>> %s: %p: preroll event encountered an error condition, swapping back to primary item player layer"
- "<<<< FigPlayerInterstitial >>>> %s: joined past event %p with resumptionOffset %f"
- "<<<< FigPlayer_AP >>>> %s: [%p] %{public}s Return, rate == 0.0"
- "<<<< FigStreamPlayer >>>> %s: Preserve resume tag: jumpseed = %p"
- "<<<< FigStreamPlayer >>>> %s: Steal ReleasePlayResourceAfterDecoding marker sample"
- "<<<< FigStreamPlayer >>>> %s: [%p|%{public}s]: Using SampleBufferConsumer to remove buffers"
- "<<<< SBufConsumerInputForBufferedAirPlayOutput >>>> %s: [%p][%p][%@](avsync) Discontinuity(diff %1.3f). SampleBuffer %p, lastSbufEndOPTS %1.3f, sbufOPts %1.3f"
- "<SEGPUMP> %s: %{public}@:%ld: cache id is %ld %{public}@"
- "<SEGPUMP> %s: %{public}@:%ld: oldStreamCache: %ld no read access for stream on new cache: %@"
- "<SEGPUMP> %s: %{public}@:%ld: oldStreamCache: %ld, newStreamCache: %ld"
- "<dw-media> %s: %p %@: created persistent pump cache %p."
- "AssetReader_XPCInstanceUUIDForMediaDaemons"
- "AsyncTransferOfFigStreamingCache"
- "Auto-Generated: "
- "Could not allocate job for streaming cache transfer"
- "DCI_P3"
- "EBU_3213"
- "EnsureStreamingCache"
- "FigStreamingCacheClearExclusiveWriter"
- "FigStreamingCacheSetExclusiveWriter"
- "GeneratedCaptionALTText"
- "IEC_sRGB"
- "IPT"
- "IPT_C2"
- "ITIdleTimerStateInitialize"
- "ITU_R_2020"
- "ITU_R_2100_HLG"
- "ITU_R_2100_ICtCp"
- "ITU_R_601_4"
- "ITU_R_709_2"
- "Instantiation_XPCInstanceUUIDForMediaDaemons"
- "InternalURLAssetEnsurePersistentStreamingCacheCreated"
- "InternalURLAssetTransferPersistentStreamingCacheAsync"
- "NULL downloadDestinationURL"
- "NULL inputQueue"
- "P22"
- "P3_D65"
- "SMPTE_240M_1995"
- "SMPTE_C"
- "SMPTE_ST_2084_PQ"
- "SMPTE_ST_428_1"
- "SourceAudioCodecTypeEnum"
- "SourceVideoCodecTypeEnum"
- "Speech transcription result string unexpectedly empty"
- "StreamingAssetPropertyLoader %s: streaming cache is NULL, falling back to network for property loading"
- "UseGamma"
- "XPCInstanceUUIDForMediaDaemons"
- "aYCC"
- "assetOption_XPCInstanceUUIDForMediaDaemons"
- "assetProperty_DiskBackedStreamingCache"
- "dworch_downloadMedia_validateDownloadIsPlayableOfflineDispatch"
- "dworch_downloadMedia_validateDownloadIsPlayableOfflineOnQueue"
- "dworch_downloadMetadata_proceedAfterCheckingDestinationURLDispatch"
- "dworch_downloadMetadata_proceedAfterCheckingDestinationURLOnQueue"
- "dworch_persistMetadata_gotAccessToDestinationURLCallbackGuts"
- "dworch_persistMetadata_gotAccessToDestinationURLDispatch"
- "dworch_persistMetadata_gotAccessToDestinationURLOnQueue"
- "dworch_selectAlternates_getPumpReadyDispatch"
- "dworch_selectAlternates_getPumpReadyOnQueue"
- "fbapop_requestForRetransmissionToRenderPipeline_block_invoke"
- "figAssetExportSession_audioCodecTypeToInteger"
- "figAssetExportSession_colorPrimariesToInteger"
- "figAssetExportSession_transferFunctionToInteger"
- "figAssetExportSession_videoCodecTypeToInteger"
- "figAssetExportSession_yCbCrMatrixToInteger"
- "fpfs_PreserveResumeTag"
- "fpfs_StealBackReleasePlayResourceFromActiveRenderPipeline"
- "fpfsi_SetupManagedStreamingCacheCallback"
- "fpfsi_StartDownloadingToURLCallback"
- "fpic_ConfigureLiveJoinPreloads_block_invoke"
- "fpic_SwapToInterstitialPlayerLayerIfPrerollDetected"
- "fpic_SwapToPrimaryItemPlayerLayerUponPrerollCancelation"
- "fpic_mediaAccessibilityChanged_block_invoke"
- "hls_use_sbc"
- "itemfig_DeferredPostNotificationOnDispatchQueue"
- "liveActivityCooldownMS"
- "no cache for stream"
- "numSampleSizeEntries is too big"
- "numSampleTimingEntries is too big"
- "remoteFormatReaderClient_setOrCheckXPCInstanceUUIDForAllFormatReaders"
- "sad_getPumpReadySchedulerCallbackGuts"
- "sourceCaptionText is NULL"
- "sourceCaptionText is empty"
- "xpcInstanceUUIDForAllFormatReaders was already set."
```
