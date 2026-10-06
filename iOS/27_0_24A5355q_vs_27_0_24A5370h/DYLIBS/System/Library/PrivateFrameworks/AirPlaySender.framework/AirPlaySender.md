## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/AirPlaySender`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2445f0` | `0x245384` | **`+0xd94`** |
| `__TEXT.__cstring` | `0x8edbf` | `0x8f4b4` | **`+0x6f5`** |
| `__AUTH_CONST.__cfstring` | `0x14ac0` | `0x14c20` | **`+0x160`** |
| `__DATA_CONST.__const` | `0x7708` | `0x7778` | **`+0x70`** |
| `__TEXT.__dlopen_cstrs` | `0x671` | `0x61d` | **`-0x54`** |
| `__TEXT.__const` | `0x6050` | `0x6090` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0xa80` | `0xa48` | **`-0x38`** |
| `__AUTH_CONST.__const` | `0x78b0` | `0x78e0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x58d0` | `0x58a0` | **`-0x30`** |
| `__DATA.__bss` | `0xe90` | `0xe70` | **`-0x20`** |

### Other Changes

```diff

-980.58.1.11.1
+980.63.2.0.0

-  Functions: 11492
-  Symbols:   8631
-  CStrings:  11633
+  Functions: 11502
+  Symbols:   8648
+  CStrings:  11661
Symbols:
+ _APTransportGetCMBaseObject
+ _APTransportSessionGetCMBaseObject
+ _APTransportStreamConfigureEncryption
+ _APTransportStreamGetCMBaseObject
+ _APTransportStreamGetTypeID
+ _APTransportStreamResume
+ _APTransportStreamSendBatchSlow
+ _APTransportStreamSetMessageCallbacks
+ _APTransportStreamSetProperty
+ _APTransportStreamSetReadyToSendBatchCallback
+ _APTransportStreamSetReadyToSendCallback
+ _APTransportStreamWaitUntilConnected
+ _FigEndpointStreamDissociate
+ _OUTLINED_FUNCTION_260
+ _OUTLINED_FUNCTION_261
+ _OUTLINED_FUNCTION_262
+ _OUTLINED_FUNCTION_263
+ _OUTLINED_FUNCTION_264
+ _OUTLINED_FUNCTION_265
+ _OUTLINED_FUNCTION_266
+ _OUTLINED_FUNCTION_267
+ _OUTLINED_FUNCTION_268
+ _OUTLINED_FUNCTION_269
+ _OUTLINED_FUNCTION_270
+ ___apsession_TeardownStreams_block_invoke
+ ___apsession_TeardownStreams_block_invoke_2
+ ___block_descriptor_48_e15_v24?0r^v8r^v16l
+ ___block_descriptor_65_e5_v8?0l
+ ___endpoint_addStreamDescriptors_block_invoke
+ ___endpoint_prepareLocalTeardown_block_invoke
+ ___endpoint_prepareLocalTeardown_block_invoke_2
+ ___endpoint_prepareLocalTeardown_block_invoke_3
+ ___endpoint_setupStreams_block_invoke
+ ___endpoint_setupStreams_block_invoke_2
+ _apsession_TeardownStreams
+ _apsession_handleMediaTerminationMetricsIfNeeded
+ _coreUtilsPairing_validateMFiCertificate
+ _endpoint_dissociateStreamAndReportMetrics
+ _endpoint_performRemoteTeardown
+ _kAPEndpointClusterAuthorizationOptionKey_SubEndpointID
+ _kAPEndpointPlaybackSessionInvalidateOptionKey_SkipTeardown
+ _kAPSenderSessionInvalidationOption_CallerRef
+ _kAPTransportSessionNotification_Disconnected
+ _kAPTransportSessionNotification_KeepAliveResponseReceived
+ _kAPTransportSessionProperty_KeepAliveType
+ _kAPTransportSessionProperty_UUID
+ _kAPTransportSessionStreamOption_DelegatedID
+ _kAPTransportSessionStreamOption_Type
+ _session_InvalidateEx
+ _wrapper_TeardownStreams
- _FigTransportGetCMBaseObject
- _FigTransportSessionGetCMBaseObject
- _FigTransportStreamConfigureEncryption
- _FigTransportStreamGetCMBaseObject
- _FigTransportStreamGetTypeID
- _FigTransportStreamResume
- _FigTransportStreamSendBatchSlow
- _FigTransportStreamSetMessageCallbacks
- _FigTransportStreamSetProperty
- _FigTransportStreamSetReadyToSendBatchCallback
- _FigTransportStreamSetReadyToSendCallback
- _FigTransportStreamWaitUntilConnected
- ___endpoint_addEndpointStreamDescriptors_block_invoke
- ___endpoint_suspendDissociateAndReleaseStreamsAndStopSenderSession_block_invoke
- ___getkMRMediaRemoteNowPlayingInfoTypeAudioSymbolLoc_block_invoke
- ___getkMRMediaRemoteNowPlayingInfoTypeVideoSymbolLoc_block_invoke
- _apsession_updateSenderSessionMetricsForRTCStats
- _bufferedAudioEngine_applyTargetLatencyIfNeeded
- _endpoint_suspendAndDissociateStreamsDictionaryEntry
- _endpoint_suspendDissociateAndReleaseStreamsAndStopSenderSession
- _getkMRMediaRemoteNowPlayingInfoMediaType
- _getkMRMediaRemoteNowPlayingInfoTypeAudioSymbolLoc.ptr
- _getkMRMediaRemoteNowPlayingInfoTypeVideo
- _getkMRMediaRemoteNowPlayingInfoTypeVideoSymbolLoc.ptr
- _kAPSenderSessionProperty_ActivationTimingInformation
- _kAPSenderSessionProperty_InitialRTCStats
- _kAPSenderSessionProperty_UpgradeActivationTimingInformation
- _kFigTransportSessionNotification_Disconnected
- _kFigTransportSessionNotification_KeepAliveResponseReceived
- _kFigTransportSessionProperty_KeepAliveType
- _kFigTransportSessionProperty_UUID
- _kFigTransportSessionStreamOption_DelegatedID
- _kFigTransportSessionStreamOption_Type
CStrings:
+ "980.63.2"
+ "AuthorizationOption_ClusterSubEndpointID"
+ "BAE [%{ptr}] %s[0x%04X] (avsync) previous sbufEndOutputPTS %1.3f(%lld/%d), current sbufOutputPTS %1.3f(%lld/%d), sbufOutputDuration%1.3f(%lld/%d),  (diff=%1.3f(%lld/%d)), nextRemoteMediaTimestamp %1.3f(%lld/%d), new nextRemoteMediaTimestamp %1.3f(%lld/%d). [ Sbuf=%p. sbufPTS=%1.3f(%lld/%d) sbufDuration=%1.3f(%lld/%d) sbufOuptutPTS=%1.3f(%lld/%d) sbufOutputDuration=%1.3f(%lld/%d) ] \n"
+ "CFDictionaryRef APSenderSessionUtilityCopyGetInfoResponseWithUGLAddressesUpdatedFromTransportStream(APTransportStreamRef, CFDictionaryRef, LogCategory *, void *)"
+ "CFDictionaryRef endpoint_buildTeardownOptions(APEndpointDeactivationContext *)"
+ "Invalidation:CallerRef"
+ "OSStatus APAuthenticationClientFairPlayCreate(CFAllocatorRef, APTransportStreamRef, APAuthenticationClientRef *)"
+ "OSStatus APAuthenticationClientMFiCreate(CFAllocatorRef, APTransportStreamRef, APAuthenticationClientRef *)"
+ "OSStatus APAuthenticationClientMFiMutualAuthCreate(CFAllocatorRef, APTransportStreamRef, APAccTransportClientConnectionRef, CFDataRef, APAuthenticationClientRef *)"
+ "OSStatus APAuthenticationClientRSACreate(CFAllocatorRef, APTransportStreamRef, CFDataRef, APAuthenticationClientRef *)"
+ "OSStatus APAuthenticationClientTokenCreate(CFAllocatorRef, APTransportStreamRef, APAuthenticationClientRef *)"
+ "OSStatus APPairingClientCoreUtilsCreate(CFAllocatorRef, CFStringRef, Boolean, Boolean, Boolean, Boolean, Boolean, Boolean, Boolean, Boolean, Boolean, CFStringRef, CFStringRef, CFDataRef, APTransportStreamRef, APPairingClientRef *)"
+ "OSStatus APPairingClientLegacyCreate(CFAllocatorRef, CFStringRef, CFDataRef, APTransportStreamRef, APPairingClientRef *)"
+ "OSStatus APSenderSessionUtilityFetchInitialVolume(APTransportStreamRef, float *)"
+ "OSStatus apEndpointRemoteControlSession_createTransportStreams(FigEndpointRemoteControlSessionRef, APTransportStreamRef *, APTransportStreamRef *)"
+ "OSStatus apEndpointRemoteControlSession_startMessageHandling(APTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)"
+ "OSStatus apPlayback_handleMessageCreatingReply(APTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)"
+ "OSStatus apsession_SetEventCallbacks(APSenderSessionRef, CFTypeRef, void *, APTransportStreamMessageCallback, APTransportStreamMessageCreatingReplyCallback)"
+ "OSStatus apsession_TeardownStreams(APSenderSessionRef, CFArrayRef)_block_invoke"
+ "OSStatus apsession_connectTransportEventStream(APSenderSessionRef, APTransportStreamRef)"
+ "OSStatus apsession_createTransportSession(APSenderSessionRef, APSenderSessionConnectionType, Boolean, Boolean, APTransportSessionRef *)"
+ "OSStatus apsession_eventStreamCreateReplyCallback(APTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)"
+ "OSStatus apsession_eventStreamCreateReplyCallback(APTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)_block_invoke"
+ "OSStatus apsession_eventStreamCreateReplyCallback_callClient(APSenderSessionRef, APTransportStreamRef, OSType, CMBlockBufferRef, CMBlockBufferRef *, APSenderSessionEventClientRef)"
+ "OSStatus audioStream_createAndResumeTransportBufferedAudioDataStream(FigEndpointStreamRef, APSenderSessionRef, int, APTransportStreamType, APTransportConnectionTransportProtocol, Boolean, CFStringRef, CFStringRef, APTransportStreamRef *)"
+ "OSStatus audioStream_createTransportAudioDataStream(APSenderSessionRef, APSNetworkClockRef, APTransportStreamSendBackingProviderRef, CFStringRef, APTransportStreamRef *)"
+ "OSStatus audioStream_preWarmNANDataSession(FigEndpointStreamRef, APTransportStreamRef)"
+ "OSStatus audioStream_suspendInternal(FigEndpointStreamRef, CFDictionaryRef, Boolean)"
+ "OSStatus carAudioStream_getTransportStreamIDAndQuality(APStreamType, Boolean, APTransportStreamID *, APTransportStreamQualityOfService *)"
+ "OSStatus carEndpoint_handleEventCreatingReply(APTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)"
+ "OSStatus coreUtilsPairing_validateMFiCertificate(APPairingClientRef, PairingSessionRef, CFDataRef *)"
+ "OSStatus endpoint_handleEventMessageCreatingReply(APTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)"
+ "OSStatus endpoint_setupStreams(FigEndpointRef, FigEndpointFeatures, FigEndpointFeatures, CFDictionaryRef, FigEndpointFeatures *)_block_invoke"
+ "OSStatus endpoint_setupStreams(FigEndpointRef, FigEndpointFeatures, FigEndpointFeatures, CFDictionaryRef, FigEndpointFeatures *)_block_invoke_2"
+ "OSStatus metadataSender_sendAPArtworkMetadata(APTransportStreamRef, Boolean, CMTime, CFDictionaryRef)"
+ "OSStatus metadataSender_sendAPProgressMetadata(APTransportStreamRef, CMTime, CFDictionaryRef)"
+ "OSStatus metadataSender_sendAPTextMetadata(APTransportStreamRef, CMTime, CFDictionaryRef)"
+ "OSStatus sdpsession_EnsureStarted(APSenderSessionRef, CFDictionaryRef *)"
+ "OSStatus session_InvalidateEx(FigEndpointPlaybackSessionRef, CFDictionaryRef)"
+ "OSStatus spendpoint_handleEventMessageCreatingReply(APTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)"
+ "SkipTeardown"
+ "[%{ptr}] %lu mis-fires occured\n"
+ "[%{ptr}] %lu write failures due to empty timestamp queue\n"
+ "[%{ptr}] %lu write failures due to full ring buffer\n"
+ "[%{ptr}] APAudioSourceCarPlay created.\n"
+ "[%{ptr}] Activation %s over %@ for %@. Duration: %llu ms%?@, correlationID: %'@, %s, %s\n"
+ "[%{ptr}] Audio converter error occurred (resetting): %#m\n"
+ "[%{ptr}] Batch TEARDOWN failed (err=%#m); receiver will retain stream state until the next reconfig or session end\n"
+ "[%{ptr}] Calling Activate callback with err: %#m\n"
+ "[%{ptr}] CarPlay audio source readiness callback fired %u nanoseconds early\n"
+ "[%{ptr}] Certificate check failed for AirPlay during pair-setup\n"
+ "[%{ptr}] Certificate check failed for AirPlay during pair-verify\n"
+ "[%{ptr}] Deactivating %@ complete (teardown duration: %llu ms)\n"
+ "[%{ptr}] Failed to allocate teardown options\n"
+ "[%{ptr}] Failed to validate MFA cert for pairing session [%{ptr}]%?{end} with features 0x%llx\n"
+ "[%{ptr}] Gathered %ld descriptor(s) for batch teardown\n"
+ "[%{ptr}] Next readiness callback seems to be very far off; %llu ms from now\n"
+ "[%{ptr}] Posting failed notification with error %#m callerRef [%{ptr}], due to forced invalidation"
+ "[%{ptr}] Resuming CarPlay audio source\n"
+ "[%{ptr}] Returning timestamp to free queue - st: %lu, fc: %lu\n"
+ "[%{ptr}] Stream teardown failed: %#m\n"
+ "[%{ptr}] Suspending CarPlay audio source\n"
+ "[%{ptr}] Validated MFA cert for pairing session [%{ptr}] with features 0x%llx\n"
+ "[%{ptr}] Validating MFA cert for pairing session [%{ptr}] with features 0x%llx\n"
+ "[%{ptr}] WritePackets failed: %#m, last ready callback invocation was %llu ms ago\n"
+ "[%{ptr}] dissociateRemovedStream: type=%@, stream=[%{ptr}]\n"
+ "[%{ptr}] dissociateStream: type=%@, stream=[%{ptr}]\n"
+ "[%{ptr}] performRemoteTeardown: senderSession=[%{ptr}], teardownSemaphore=[%{ptr}]\n"
+ "activationTiming"
+ "airPlayCount"
+ "airPlayTotalDurationSecs"
+ "apsession_TeardownStreams_block_invoke"
+ "apsession_copyRTCStatsForEnsureStart"
+ "apsession_createReceiverDeviceInfoMetrics"
+ "connectionType"
+ "coreUtilsPairing_validateMFiCertificate"
+ "downgradeMs"
+ "endpoint_buildTeardownOptions"
+ "initial"
+ "isFinalTermination"
+ "isInitialActivation"
+ "nanOperationsRequiredForActivation"
+ "networkClockType"
+ "senderSessionType"
+ "setupType"
+ "upgrade"
+ "void apEndpointRemoteControlSession_sendDiagnosticDataForTransportStreamIfNeeded(FigEndpointRemoteControlSessionRef, APTransportStreamRef, int64_t, CFStringRef)"
+ "void apsession_eventStreamMessageCallback(APTransportStreamRef, OSType, CMBlockBufferRef, void *)"
+ "void apsession_eventStreamMessageCallback_callClient(APSenderSessionRef, APTransportStreamRef, OSType, CMBlockBufferRef, APSenderSessionEventClientRef)"
+ "void apsession_handleTransportStreamDisconnected(APSenderSessionRef, APTransportStreamRef)"
+ "void apsession_setTransportSession(APSenderSessionRef, APTransportSessionRef)"
+ "void audioStream_receivedAudioDataMessage(APTransportStreamRef, OSType, CMBlockBufferRef, void *)"
+ "void audioStream_receivedMediaDataEventMessage(APTransportStreamRef, OSType, CMBlockBufferRef, void *)"
+ "void carAudioStream_handleIncomingInputDataMessage(APTransportStreamRef, OSType, CMBlockBufferRef, void *)_block_invoke"
+ "void carAudioStream_handleOutputControlMessage(APTransportStreamRef, OSType, CMBlockBufferRef, void *)_block_invoke"
+ "void carAudioStream_handleOutputControlMessage(APTransportStreamRef, OSType, CMBlockBufferRef, void *)_block_invoke_2"
+ "void carAudioStream_processAllPendingPackets(FigEndpointStreamRef, APSRTPPacketHandlerRef, FigEndpointAudioSinkRef, APSCryptorRef, APTransportStreamRef, OSType)"
+ "void carEndpoint_handleEvent(APTransportStreamRef, OSType, CMBlockBufferRef, void *)"
+ "void carplaysource_scheduleReadinessCallbackAfterTimeNs(FigEndpointAudioSourceRef, uint64_t)"
+ "void endpoint_handleEventMessage(APTransportStreamRef, OSType, CMBlockBufferRef, void *)"
+ "void endpoint_invalidatePlaybackSession(FigEndpointPlaybackSessionRef, FigEndpointRef, Boolean, APSRTCReportingAgentRef, CFDictionaryRef)"
+ "void endpoint_performRemoteTeardown(void *)"
+ "void endpoint_prepareLocalTeardown(APEndpointDeactivationContext *)_block_invoke"
+ "void screenstream_teardownTransportStream(FigEndpointStreamRef, Boolean)"
+ "void screenstreamudp_teardownStream(FigEndpointStreamRef, Boolean)"
+ "void spendpoint_handleEventMessage(APTransportStreamRef, OSType, CMBlockBufferRef, void *)"
+ "wrapper_InvalidateEx"
- "%lu mis-fires occured\n"
- "%lu write failures due to empty timestamp queue\n"
- "%lu write failures due to full ring buffer\n"
- ", upgrade"
- "980.58.1.11.1"
- "APAudioSourceCarPlay created.\n"
- "ActivationTimingInformation"
- "Audio converter error occurred (resetting): %#m\n"
- "BAE [%{ptr}] %s[0x%04X] (avsync) previous sbufEndOutputPTS %1.3f, current sbufOutputPTS %1.3f (diff=%1.3f), nextRemoteMediaTimestamp %1.3f, new nextRemoteMediaTimestamp %1.3f. [ Sbuf=%p. sbufPTS=%1.3f sbufDuration=%1.3f sbufOuptutPTS=%1.3f sbufOutputDuration=%1.3f ] \n"
- "CFDictionaryRef APSenderSessionUtilityCopyGetInfoResponseWithUGLAddressesUpdatedFromTransportStream(FigTransportStreamRef, CFDictionaryRef, LogCategory *, void *)"
- "CFStringRef getkMRMediaRemoteNowPlayingInfoTypeAudio(void)"
- "CFStringRef getkMRMediaRemoteNowPlayingInfoTypeVideo(void)"
- "CarPlay audio source readiness callback fired %u nanoseconds early\n"
- "InitialRTCStats"
- "OSStatus APAuthenticationClientFairPlayCreate(CFAllocatorRef, FigTransportStreamRef, APAuthenticationClientRef *)"
- "OSStatus APAuthenticationClientMFiCreate(CFAllocatorRef, FigTransportStreamRef, APAuthenticationClientRef *)"
- "OSStatus APAuthenticationClientMFiMutualAuthCreate(CFAllocatorRef, FigTransportStreamRef, APAccTransportClientConnectionRef, CFDataRef, APAuthenticationClientRef *)"
- "OSStatus APAuthenticationClientRSACreate(CFAllocatorRef, FigTransportStreamRef, CFDataRef, APAuthenticationClientRef *)"
- "OSStatus APAuthenticationClientTokenCreate(CFAllocatorRef, FigTransportStreamRef, APAuthenticationClientRef *)"
- "OSStatus APPairingClientCoreUtilsCreate(CFAllocatorRef, CFStringRef, Boolean, Boolean, Boolean, Boolean, Boolean, Boolean, Boolean, Boolean, Boolean, CFStringRef, CFStringRef, CFDataRef, FigTransportStreamRef, APPairingClientRef *)"
- "OSStatus APPairingClientLegacyCreate(CFAllocatorRef, CFStringRef, CFDataRef, FigTransportStreamRef, APPairingClientRef *)"
- "OSStatus APSenderSessionUtilityFetchInitialVolume(FigTransportStreamRef, float *)"
- "OSStatus apEndpointRemoteControlSession_createTransportStreams(FigEndpointRemoteControlSessionRef, FigTransportStreamRef *, FigTransportStreamRef *)"
- "OSStatus apEndpointRemoteControlSession_startMessageHandling(FigTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)"
- "OSStatus apPlayback_handleMessageCreatingReply(FigTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)"
- "OSStatus apsession_SetEventCallbacks(APSenderSessionRef, CFTypeRef, void *, FigTransportStreamMessageCallback, FigTransportStreamMessageCreatingReplyCallback)"
- "OSStatus apsession_connectTransportEventStream(APSenderSessionRef, FigTransportStreamRef)"
- "OSStatus apsession_createTransportSession(APSenderSessionRef, APSenderSessionConnectionType, Boolean, Boolean, FigTransportSessionRef *)"
- "OSStatus apsession_eventStreamCreateReplyCallback(FigTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)"
- "OSStatus apsession_eventStreamCreateReplyCallback(FigTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)_block_invoke"
- "OSStatus apsession_eventStreamCreateReplyCallback_callClient(APSenderSessionRef, FigTransportStreamRef, OSType, CMBlockBufferRef, CMBlockBufferRef *, APSenderSessionEventClientRef)"
- "OSStatus audioStream_createAndResumeTransportBufferedAudioDataStream(FigEndpointStreamRef, APSenderSessionRef, int, APTransportStreamType, APTransportConnectionTransportProtocol, Boolean, CFStringRef, CFStringRef, FigTransportStreamRef *)"
- "OSStatus audioStream_createTransportAudioDataStream(APSenderSessionRef, APSNetworkClockRef, APTransportStreamSendBackingProviderRef, CFStringRef, FigTransportStreamRef *)"
- "OSStatus audioStream_preWarmNANDataSession(FigEndpointStreamRef, FigTransportStreamRef)"
- "OSStatus audioStream_suspendInternal(FigEndpointStreamRef, CFDictionaryRef)"
- "OSStatus carAudioStream_getTransportStreamIDAndQuality(APStreamType, Boolean, FigTransportStreamID *, APTransportStreamQualityOfService *)"
- "OSStatus carEndpoint_handleEventCreatingReply(FigTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)"
- "OSStatus endpoint_handleEventMessageCreatingReply(FigTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)"
- "OSStatus metadataSender_sendAPArtworkMetadata(FigTransportStreamRef, Boolean, CMTime, CFDictionaryRef)"
- "OSStatus metadataSender_sendAPProgressMetadata(FigTransportStreamRef, CMTime, CFDictionaryRef)"
- "OSStatus metadataSender_sendAPTextMetadata(FigTransportStreamRef, CMTime, CFDictionaryRef)"
- "OSStatus sdpsession_EnsureStarted(APSenderSessionRef)"
- "OSStatus session_Invalidate(CMBaseObjectRef)"
- "OSStatus spendpoint_handleEventMessageCreatingReply(FigTransportStreamRef, OSType, CMBlockBufferRef, void *, CMBlockBufferRef *)"
- "Resuming CarPlay audio source\n"
- "Returning timestamp to free queue - st: %lu, fc: %lu\n"
- "Suspending CarPlay audio source\n"
- "UpgradeActivationTimingInformation"
- "WritePackets failed: %#m, last ready callback invocation was %llu ms ago\n"
- "[%{ptr}] %s: type=%@, stream=[%{ptr}]\n"
- "[%{ptr}] Activation %s over %@ for %@. Duration: %llu ms%?@, correlationID: %'@%s\n"
- "[%{ptr}] Calling Activate callback...\n"
- "[%{ptr}] Cerificate check failed for AirPlay during Setup\n"
- "[%{ptr}] Cerificate check failed for AirPlay during pair-verify\n"
- "[%{ptr}] Gathered %ld stream(s) for teardown\n"
- "[%{ptr}] Overriding media type from video to audio.\n"
- "[%{ptr}] Posting failed notification with error %#m, due to forced invalidation"
- "apsession_createInitialRTCStats"
- "kMRMediaRemoteNowPlayingInfoTypeAudio"
- "kMRMediaRemoteNowPlayingInfoTypeVideo"
- "void apEndpointRemoteControlSession_sendDiagnosticDataForTransportStreamIfNeeded(FigEndpointRemoteControlSessionRef, FigTransportStreamRef, int64_t, CFStringRef)"
- "void apsession_eventStreamMessageCallback(FigTransportStreamRef, OSType, CMBlockBufferRef, void *)"
- "void apsession_eventStreamMessageCallback_callClient(APSenderSessionRef, FigTransportStreamRef, OSType, CMBlockBufferRef, APSenderSessionEventClientRef)"
- "void apsession_handleTransportStreamDisconnected(APSenderSessionRef, FigTransportStreamRef)"
- "void apsession_setTransportSession(APSenderSessionRef, FigTransportSessionRef)"
- "void audioStream_receivedAudioDataMessage(FigTransportStreamRef, OSType, CMBlockBufferRef, void *)"
- "void audioStream_receivedMediaDataEventMessage(FigTransportStreamRef, OSType, CMBlockBufferRef, void *)"
- "void carAudioStream_handleIncomingInputDataMessage(FigTransportStreamRef, OSType, CMBlockBufferRef, void *)_block_invoke"
- "void carAudioStream_handleOutputControlMessage(FigTransportStreamRef, OSType, CMBlockBufferRef, void *)_block_invoke"
- "void carAudioStream_handleOutputControlMessage(FigTransportStreamRef, OSType, CMBlockBufferRef, void *)_block_invoke_2"
- "void carAudioStream_processAllPendingPackets(FigEndpointStreamRef, APSRTPPacketHandlerRef, FigEndpointAudioSinkRef, APSCryptorRef, FigTransportStreamRef, OSType)"
- "void carEndpoint_handleEvent(FigTransportStreamRef, OSType, CMBlockBufferRef, void *)"
- "void endpoint_handleEventMessage(FigTransportStreamRef, OSType, CMBlockBufferRef, void *)"
- "void endpoint_invalidatePlaybackSession(FigEndpointPlaybackSessionRef, FigEndpointRef, APSRTCReportingAgentRef, CFDictionaryRef)"
- "void endpoint_suspendAndDissociateStreamsDictionaryEntry(const void *, const void *, void *)"
- "void endpoint_suspendDissociateAndReleaseStreamsAndStopSenderSession(void *)"
- "void screenstream_teardownTransportStream(FigEndpointStreamRef)"
- "void screenstreamudp_teardownStream(FigEndpointStreamRef)"
- "void spendpoint_handleEventMessage(FigTransportStreamRef, OSType, CMBlockBufferRef, void *)"
```
