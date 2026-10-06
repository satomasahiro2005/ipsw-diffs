## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/AVConference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ba4c0` | `0x7d1200` | **`+0x16d40`** |
| `__TEXT.__oslogstring` | `0x137748` | `0x13dc25` | **`+0x64dd`** |
| `__TEXT.__cstring` | `0x9e07b` | `0x9e6f4` | **`+0x679`** |
| `__AUTH_CONST.__objc_const` | `0x6ca08` | `0x6cd68` | **`+0x360`** |
| `__TEXT.__objc_methlist` | `0x3a6f0` | `0x3a8b0` | **`+0x1c0`** |
| `__TEXT.__gcc_except_tab` | `0x2b54` | `0x2d08` | **`+0x1b4`** |
| `__TEXT.__unwind_info` | `0x12268` | `0x123e0` | **`+0x178`** |
| `__AUTH_CONST.__cfstring` | `0x29680` | `0x297e0` | **`+0x160`** |
| `__DATA_CONST.__objc_selrefs` | `0x18af0` | `0x18bc0` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x7608` | `0x7660` | **`+0x58`** |
| `__DATA.__objc_ivar` | `0x7654` | `0x76a8` | **`+0x54`** |
| `__TEXT.__const` | `0xc670` | `0xc6c0` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x2c08` | `0x2c38` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x4448` | `0x4468` | **`+0x20`** |
| `__DATA.__bss` | `0xee0` | `0xef8` | **`+0x18`** |

### Other Changes

```diff

-2235.48.1.0.0
+2235.52.1.11.1

-  Functions: 35201
-  Symbols:   41753
-  CStrings:  33446
+  Functions: 35303
+  Symbols:   41836
+  CStrings:  33800
Symbols:
+ +[VCCapabilities isRelayDeviceRole:]
+ +[VCHardwareSettings supportsCameraPreview]
+ +[VCHardwareSettings supportsCompressedPixelFormatForDecoder]
+ -[AVConferencePreview _updateCameraUIDMappingForSession:newUID:]
+ -[VCAVFoundationCapture safeStartRunning:]
+ -[VCAVFoundationCapture safeStopRunning:]
+ -[VCAudioHALController startHealthMonitor]
+ -[VCAudioHALController stopHealthMonitor]
+ -[VCAudioRedBuilder samplesPerFrame]
+ -[VCAudioRedBuilder setSamplesPerFrame:]
+ -[VCAudioStream shouldEnableInactiveFramesDetection:streamConfig:]
+ -[VCAudioStream updateReportingConfigForHomeKitV3]
+ -[VCHardwareSettingsEmbedded supportsCameraPreview]
+ -[VCHardwareSettingsEmbedded supportsCompressedPixelFormatForDecoder]
+ -[VCHardwareSettingsMac supportsCompressedPixelFormatForDecoder]
+ -[VCInterframeDelayMonitor _buildReportFromStats:histogramDescription:]
+ -[VCInterframeDelayMonitor _classifyFreeze:avgFrameDurationMs:]
+ -[VCInterframeDelayMonitor _recordFirstFrameWithPresentationTime:hostTime:frameSequenceNumber:]
+ -[VCInterframeDelayMonitor _recordSubsequentFrameWithPresentationTime:hostTime:frameSequenceNumber:]
+ -[VCInterframeDelayMonitor _resetSegmentState]
+ -[VCInterframeDelayMonitor _updateRollingWindow:]
+ -[VCInterframeDelayMonitor recordFrameWithPresentationTime:frameSequenceNumber:]
+ -[VCInterframeDelayReport freezeCountDisruptive]
+ -[VCInterframeDelayReport freezeCountNoticeable]
+ -[VCInterframeDelayReport setFreezeCountDisruptive:]
+ -[VCInterframeDelayReport setFreezeCountNoticeable:]
+ -[VCInterframeDelayReport setTotalFreezeDurationMs:]
+ -[VCInterframeDelayReport totalFreezeDurationMs]
+ -[VCMediaStreamConfig detectInactiveAudioFramesACC24]
+ -[VCMediaStreamConfig setDetectInactiveAudioFramesACC24:]
+ -[VCMockQRServer copyChannelForParticipantId:idsDatagramChannels:]
+ -[VCSessionParticipantConfig detectInactiveAudioFramesACC24]
+ -[VCSessionParticipantConfig setDetectInactiveAudioFramesACC24:]
+ -[VCTransportSession isMTULargerThanMaxIPMTUSupported]
+ -[VCTransportSessionNW isMTULargerThanMaxIPMTUSupported]
+ -[VCVideoCaptureServer dualCaptureEnabled]
+ -[VCVideoStream gatherInterframeDelayStats:]
+ -[VCVideoStreamRateAdaptation sendTMMBRImmediately]
+ -[VCVideoStreamReceiver gatherInterframeDelayStats:]
+ GCC_except_table104
+ GCC_except_table155
+ GCC_except_table183
+ GCC_except_table185
+ GCC_except_table187
+ GCC_except_table202
+ GCC_except_table205
+ GCC_except_table230
+ GCC_except_table239
+ GCC_except_table242
+ GCC_except_table245
+ GCC_except_table285
+ GCC_except_table313
+ GCC_except_table367
+ GCC_except_table451
+ GCC_except_table63
+ GCC_except_table88
+ GCC_except_table95
+ _OBJC_IVAR_$_AVConferencePreview._cameraUIDToSession
+ _OBJC_IVAR_$_VCAudioHALController._periodicHealthPrintDispatchSource
+ _OBJC_IVAR_$_VCAudioStream._appAdvisoryNotificationsEnabled
+ _OBJC_IVAR_$_VCAudioStream._isHomeKitV3
+ _OBJC_IVAR_$_VCEffectsManager._framesWithFaceMetadataCount
+ _OBJC_IVAR_$_VCEffectsManager._totalFaceMetadataCount
+ _OBJC_IVAR_$_VCImageQueue._isPaused
+ _OBJC_IVAR_$_VCInterframeDelayMonitor._prevSequenceNumber
+ _OBJC_IVAR_$_VCInterframeDelayMonitor._rollingCount
+ _OBJC_IVAR_$_VCInterframeDelayMonitor._rollingFrameDurations
+ _OBJC_IVAR_$_VCInterframeDelayMonitor._rollingHead
+ _OBJC_IVAR_$_VCInterframeDelayMonitor._rollingSum
+ _OBJC_IVAR_$_VCInterframeDelayReport._freezeCountDisruptive
+ _OBJC_IVAR_$_VCInterframeDelayReport._freezeCountNoticeable
+ _OBJC_IVAR_$_VCInterframeDelayReport._totalFreezeDurationMs
+ _OBJC_IVAR_$_VCMediaStreamConfig._detectInactiveAudioFramesACC24
+ _OBJC_IVAR_$_VCNetworkFeedbackController._isWiFiRoamHandoverEnabled
+ _OBJC_IVAR_$_VCSession._detectInactiveAudioFramesACC24
+ _OBJC_IVAR_$_VCSessionParticipantConfig._detectInactiveAudioFramesACC24
+ _OBJC_IVAR_$_VCSessionParticipantLocal._dualCaptureReceiverEnabled
+ _OBJC_IVAR_$_VCSessionParticipantRemote._detectInactiveAudioFramesACC24
+ _OBJC_IVAR_$_VCVideoCaptureServer._supportsCameraPreview
+ _OBJC_IVAR_$_VCVideoStreamReceiver._interframeDelayMonitor
+ _VCAbTestDetectInactiveAudioFramesACC24
+ _VCAudioPowerEstimator_Create
+ _VCAudioPowerEstimator_Destroy
+ _VCAudioPowerEstimator_GetAveragePower
+ _VCAudioPowerEstimator_ProcessAudioBuffer
+ _VCAudioPowerEstimator_Reset
+ _VCAudioUtil_ComputeRMSPower
+ _VCEffectsManager_ReportFaceMetadataCount
+ _VCHardwareSettings_supportsCompressedPixelFormatForDecoder
+ _VCReporting_SetClientType
+ _VCUtil_BlockBufferHasImgDesc
+ _VCVideoCaptureServer_OnFaceMetadataReceived
+ _VCWiFiRoamHandoverEnableThreshold
+ _VideoUtil_GetFrameSequenceNumber
+ __VCImageQueue_RecordInterframeDelay
+ __VCVideoPacketBuffer_AssembleProResFrame
+ __VRLogfileGetSharedTargetQueue.onceToken
+ __VRLogfileGetSharedTargetQueue.sharedTargetQueue
+ __VTPWithCMFMetadata
+ __ZNSt12length_errorC1B9nqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9nqe220106INS_9allocatorI32tagVCAudioHALPluginTimestampInfoEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9nqe220106EPKc
+ __ZNSt3__16vectorI32tagVCAudioHALPluginTimestampInfoNS_9allocatorIS1_EEE11__vallocateB9nqe220106Em
+ __ZNSt3__16vectorI32tagVCAudioHALPluginTimestampInfoNS_9allocatorIS1_EEE20__throw_length_errorB9nqe220106Ev
+ __ZNSt3__16vectorI32tagVCAudioHALPluginTimestampInfoNS_9allocatorIS1_EEEC2B9nqe220106EmRKS1_
+ __ZSt28__throw_bad_array_new_lengthB9nqe220106v
+ ___42-[VCAudioHALController startHealthMonitor]_block_invoke
+ ___48-[VCNetworkFeedbackController initializeWRMInfo]_block_invoke
+ ___59-[VCSessionParticipantRemote remoteMediaStateForMediaType:]_block_invoke
+ ___VTP_PrepareReceiveBuffer_block_invoke
+ ___VTP_PrepareSendBuffer_block_invoke
+ ____VRLogfileGetSharedTargetQueue_block_invoke
+ ___block_descriptor_48_e8_32o_e46_i20?0"NSObject<OS_nw_protocol_metadata>"8i16ls32l8
+ _fuzz_packet
+ _kVCExperimentEnableInactiveACC24FrameDetection
+ _kVCExperimentEnableWiFiRoamHandover
+ _nw_cmf_metadata_prepare_receive_buffers
+ _nw_cmf_metadata_prepare_send_buffers
+ _nw_connection_copy_protocol_metadata
+ _nw_protocol_copy_cmf_definition
+ _nw_protocol_metadata_is_cmf
- +[VCCallSession isRelayDeviceRole:]
- -[AVConferencePreview cameraSessionForUID:]
- -[VCAudioStream shouldEnableAACELDInactiveFrames:streamConfig:]
- -[VCInterframeDelayMonitor _snapshotReport]
- -[VCInterframeDelayMonitor recordFrameWithPresentationTime:]
- -[VCMockQRServer channelForParticipantId:idsDatagramChannels:]
- -[VCSessionParticipant dualCaptureReceiverEnabled]
- GCC_except_table103
- GCC_except_table116
- GCC_except_table121
- GCC_except_table154
- GCC_except_table182
- GCC_except_table184
- GCC_except_table186
- GCC_except_table201
- GCC_except_table204
- GCC_except_table229
- GCC_except_table238
- GCC_except_table241
- GCC_except_table244
- GCC_except_table283
- GCC_except_table314
- GCC_except_table368
- GCC_except_table452
- GCC_except_table58
- GCC_except_table89
- GCC_except_table92
- GCC_except_table97
- _OBJC_IVAR_$_VCAudioStream._downlinkAudioQualityAdvisoryNotificationsEnabled
- _OBJC_IVAR_$_VCSessionParticipant._dualCaptureReceiverEnabled
- _VCAudioBufferList_ComputeRMSPowerPerChannel
- __ZNSt12length_errorC1B9nqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9nqe220100INS_9allocatorI32tagVCAudioHALPluginTimestampInfoEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9nqe220100EPKc
- __ZNSt3__16vectorI32tagVCAudioHALPluginTimestampInfoNS_9allocatorIS1_EEE11__vallocateB9nqe220100Em
- __ZNSt3__16vectorI32tagVCAudioHALPluginTimestampInfoNS_9allocatorIS1_EEE20__throw_length_errorB9nqe220100Ev
- __ZNSt3__16vectorI32tagVCAudioHALPluginTimestampInfoNS_9allocatorIS1_EEEC2B9nqe220100EmRKS1_
- __ZSt28__throw_bad_array_new_lengthB9nqe220100v
CStrings:
+ " [%s] %s:%d %@(%p)  { VCAudioTierPickerConfig: supportedAudioPayloadConfig=(%@)}"
+ " [%s] %s:%d %@(%p) ('vp client input format' inFormat=%@)"
+ " [%s] %s:%d %@(%p) ('vp client operation mode' opModeNumber=%u)"
+ " [%s] %s:%d %@(%p) ('vp client output format' outFormat=%@)"
+ " [%s] %s:%d %@(%p) AVCDashboard Participant DisplayURL=%@"
+ " [%s] %s:%d %@(%p) AVCDashboard Serial DisplayURL=%@"
+ " [%s] %s:%d %@(%p) Adding streamGroupID=%s for mediaType=%@ mediaState=%@"
+ " [%s] %s:%d %@(%p) Audio redundancy percentage change due to packet loss: %2.3f, new threshold: %2.3f [%d to %d] plrEnvelope=%2.3f"
+ " [%s] %s:%d %@(%p) Batch set properties=%@"
+ " [%s] %s:%d %@(%p) Bitrate = %d. received connection for %s, connectionType = %d, constraint %d, expensive %d, videoFullHD %d"
+ " [%s] %s:%d %@(%p) Cancelling encryption key roll timer"
+ " [%s] %s:%d %@(%p) Cancelling pruneTimer"
+ " [%s] %s:%d %@(%p) Capable of streaming 16x9 cellular!"
+ " [%s] %s:%d %@(%p) Checking for cached WRM notification _isWRMNotificationPending=%d isDuplicationAllowed=%d _isUserMoving=%d earlyAllowed=%d"
+ " [%s] %s:%d %@(%p) Computed capture frame rate: %d"
+ " [%s] %s:%d %@(%p) ConnectionSelectionPolicy updated: preferRelayOverP2P=%d preferIPv6OverIPv4=%d preferNonVPN=%d e2eCriteriaEnabled=%d preferE2E=%d preferWired=%d"
+ " [%s] %s:%d %@(%p) Consumer thread stopped!"
+ " [%s] %s:%d %@(%p) CoreMotion: Starting motion activity monitor"
+ " [%s] %s:%d %@(%p) CoreMotion: Stopping motion activity monitor"
+ " [%s] %s:%d %@(%p) CoreMotion: Updated motion activity value=%d confidence=%ld"
+ " [%s] %s:%d %@(%p) Creating an instance of NetworkAgent and asserting it"
+ " [%s] %s:%d %@(%p) Cryptor for keyIndex:%@ is updated"
+ " [%s] %s:%d %@(%p) Current bag settings: %s\n"
+ " [%s] %s:%d %@(%p) Current ioBufferDuration=%f Desired duration=%f Error=%f"
+ " [%s] %s:%d %@(%p) Device invalidated while still started; caller skipped -stop"
+ " [%s] %s:%d %@(%p) Disabling SRTP encryption. isEncryptionDisabled=%d, sframeCipherSuite=%d"
+ " [%s] %s:%d %@(%p) Do not load emulated network"
+ " [%s] %s:%d %@(%p) Enabling AVAssetReader preparesMediaDataForRealTimeConsumption"
+ " [%s] %s:%d %@(%p) Failed to allocate delay monitor"
+ " [%s] %s:%d %@(%p) Failed to create health monitor"
+ " [%s] %s:%d %@(%p) Failed to create stream group U1 config for groupID=%s"
+ " [%s] %s:%d %@(%p) Failed to initialize AssetReader"
+ " [%s] %s:%d %@(%p) Failed to set path from PFL file!"
+ " [%s] %s:%d %@(%p) Failed to set property=%@ value=%@"
+ " [%s] %s:%d %@(%p) Failed to set up the power estimator"
+ " [%s] %s:%d %@(%p) Generated audio stream token=%@"
+ " [%s] %s:%d %@(%p) Generated video stream token=%@"
+ " [%s] %s:%d %@(%p) Get negotiated results for stream group groupID=%s"
+ " [%s] %s:%d %@(%p) Getting: preferredOutputSampleRate currentPreferredSampleRate=%f -> wanted sampleRate=%f"
+ " [%s] %s:%d %@(%p) HandoverReport: Check if primary connection needs to be updated - isCurrentPrimaryUsingRelay=%d isPreferRelayOverP2PEnabled=%d"
+ " [%s] %s:%d %@(%p) HandoverReport: Primary connection health allowed delay = %.2f"
+ " [%s] %s:%d %@(%p) HandoverReport: Update cellBitrateCap for pending iRAT notification purpose: %d"
+ " [%s] %s:%d %@(%p) HandoverReport: VCConnectionHealthMonitor is running"
+ " [%s] %s:%d %@(%p) HandoverReport: oneToOneMode %s for isInitiator: %d"
+ " [%s] %s:%d %@(%p) HandoverReport: setting connection selection version=%d localFrameworkVersion=%@ remoteFrameworkVersion=%@"
+ " [%s] %s:%d %@(%p) HandoverReport: shouldForceRelayLinksWhenScreenEnabled=%d"
+ " [%s] %s:%d %@(%p) HandoverReport: startConnectionHealthMonitoring=%d"
+ " [%s] %s:%d %@(%p) History is empty"
+ " [%s] %s:%d %@(%p) IC featureEnabled=%d userEnabled=%d userPreferred=%d"
+ " [%s] %s:%d %@(%p) IDS datagramChannel has been invalidated"
+ " [%s] %s:%d %@(%p) Immersive Video maxBitrate=%u for connectionType %d"
+ " [%s] %s:%d %@(%p) Initialize stream group U1 config for groupID=%s"
+ " [%s] %s:%d %@(%p) Initializing media recorder rule collections with HEIF and HEVC enabled:%d and the storebag settings value was: %d"
+ " [%s] %s:%d %@(%p) Invalid client token"
+ " [%s] %s:%d %@(%p) Key material is not yet available"
+ " [%s] %s:%d %@(%p) LinkProbing: Loaded storebag values linkProbingInterval=%d linkProbingTimeout=%d linkProbingQueryResultsInterval=%d exponentialMovingMeanFactor=%f plrEnvelopeAttackFactor=%f plrEnvelopeDecayFactor=%f plrBuckets=%@ minSentRequestCountThreshold=%d _linkProbingDuplicationWaitTimeout=%d _consecutiveIdenticalQueryResultMax=%d _linkProbingLockdownPeriod=%f _linkProbingQRStatFrequency=%d _linkProbingQRStatRequestMaxCount=%d _inkProbingQRStatRequestMaxRTT=%f"
+ " [%s] %s:%d %@(%p) LinkSwitchSync: linkID=%u: NO - multiway session, not U+1"
+ " [%s] %s:%d %@(%p) LinkSwitchSync: linkID=%u: wouldBecomePrimary=%d (compared against current primary)"
+ " [%s] %s:%d %@(%p) Load switch heifHevcLivePhotosEnabled %d"
+ " [%s] %s:%d %@(%p) Load switch hevcWifiTiersEnabled %d"
+ " [%s] %s:%d %@(%p) Load switch highFecEnabled %d"
+ " [%s] %s:%d %@(%p) Load switch vplrFecEnabled %d"
+ " [%s] %s:%d %@(%p) Load switch wifiAssistBudgetStatusEnabled %d"
+ " [%s] %s:%d %@(%p) Local preferredAudioCodec=%u, allowAudioSwitching=%{BOOL}d"
+ " [%s] %s:%d %@(%p) MKI '%@' has already been configured for this session. Ignoring duplicate"
+ " [%s] %s:%d %@(%p) Mock IDS channel context forced _networkType=%u _remoteNetworkType=%u _localLinkFlags=%u _linkID=%u [sourcePort=%u]"
+ " [%s] %s:%d %@(%p) Model or control group set by PFL"
+ " [%s] %s:%d %@(%p) NetworkAgent assertion added"
+ " [%s] %s:%d %@(%p) NetworkAgent assertion removed"
+ " [%s] %s:%d %@(%p) NetworkAgent has been asserted, result=%d"
+ " [%s] %s:%d %@(%p) NetworkAgent refcount is '%d'"
+ " [%s] %s:%d %@(%p) No feature flag/HW support or enrollment default"
+ " [%s] %s:%d %@(%p) No ranks received"
+ " [%s] %s:%d %@(%p) Not capable of streaming 16x9 cellular!"
+ " [%s] %s:%d %@(%p) Not respecting the budget restrictions as directed by the storebag settings: isInBudget = YES"
+ " [%s] %s:%d %@(%p) Notified of new keyMaterial '%@'"
+ " [%s] %s:%d %@(%p) One to one config not supported for groupID=%s"
+ " [%s] %s:%d %@(%p) Overriding %@ for connection type %d isExpensive %d with storebag value of %d"
+ " [%s] %s:%d %@(%p) ParticipantID=%@: Found duplicate message with transactionID=%@ and expiration time=%@"
+ " [%s] %s:%d %@(%p) ParticipantID=%@: Purging message with transactionID=%llu and expiration time=%f. Current time=%f, replayProtectionThreshold=%llu"
+ " [%s] %s:%d %@(%p) Payload=%d cannot be negotiated."
+ " [%s] %s:%d %@(%p) Producer thread stopped!"
+ " [%s] %s:%d %@(%p) Re-applying mute=%d"
+ " [%s] %s:%d %@(%p) Re-setting connection stat timers to now=%f"
+ " [%s] %s:%d %@(%p) Received IDS data channel event=%d with keyIndex=%s"
+ " [%s] %s:%d %@(%p) Received connection type %d"
+ " [%s] %s:%d %@(%p) Redundancy controllers are created"
+ " [%s] %s:%d %@(%p) Redundancy level _packetLossPercentage=%2.2f _plrEnvelope=%2.2f "
+ " [%s] %s:%d %@(%p) Redundancy level changed from _redundancyPercentage=%d to newRedundancyPercentage=%d _packetLossPercentage=%3.3f _plrEnvelope=%3.3f"
+ " [%s] %s:%d %@(%p) Register for Darwin %@"
+ " [%s] %s:%d %@(%p) Registered MediaHealthStatisticsHandlerIndex=%d"
+ " [%s] %s:%d %@(%p) Releasing AVAudioSession=%@, _audioSessionId=%u"
+ " [%s] %s:%d %@(%p) Remote device framework version IDS is unknown"
+ " [%s] %s:%d %@(%p) Remote device framework version IDS selected '%d'"
+ " [%s] %s:%d %@(%p) Removing notification=%@ observer for avAudioSession=%@"
+ " [%s] %s:%d %@(%p) Reported path MTU=%u"
+ " [%s] %s:%d %@(%p) Route or AvailableSampleRate Changed: AVAudioSession CurrentHardwareSampleRate=%f"
+ " [%s] %s:%d %@(%p) Scheduled encryption roll timeout delta=%f seconds"
+ " [%s] %s:%d %@(%p) Sender side redundancy changed to[%d]"
+ " [%s] %s:%d %@(%p) Set VCRateControl baseband congestion detector to all audio streams"
+ " [%s] %s:%d %@(%p) Set link flags='%08x'"
+ " [%s] %s:%d %@(%p) Set previous link flags='%08x'"
+ " [%s] %s:%d %@(%p) Set previous remote link flags='%08x'"
+ " [%s] %s:%d %@(%p) Set properties on self=%@ modelPath=%@ recipeID=%@ nIteration=%u reportingGroup=%u trialModelID=%@"
+ " [%s] %s:%d %@(%p) Set remote link flags='%08x'"
+ " [%s] %s:%d %@(%p) Setting kCAImageQueueProtected to CAImageQueue"
+ " [%s] %s:%d %@(%p) Setting up Audio Tier Picker with config %@"
+ " [%s] %s:%d %@(%p) Setting width: %d height: %d"
+ " [%s] %s:%d %@(%p) Setup U1 config for stream group for groupID=%s"
+ " [%s] %s:%d %@(%p) Succeeded in setting property=%@ value=%@"
+ " [%s] %s:%d %@(%p) Successfully created stream group U1 config for groupID=%s"
+ " [%s] %s:%d %@(%p) SwitchManager: Setting individual local switches for the purpose of QA testing"
+ " [%s] %s:%d %@(%p) Unit Test: Invalidated VCMockIDSDatagramChannel"
+ " [%s] %s:%d %@(%p) Unregistered handler with clientToken=%u"
+ " [%s] %s:%d %@(%p) Updating operatingMode=%d"
+ " [%s] %s:%d %@(%p) Using plist for audio tier table for config.mode=%d isIPv4=%{BOOL}d isCellular=%{BOOL}d redNumPayloads=%lu"
+ " [%s] %s:%d %@(%p) VCAudioSessionProperty_ClientPID processId=%d, success=%{BOOL}d"
+ " [%s] %s:%d %@(%p) VCBitrateArbiter: Bitrate rules %s"
+ " [%s] %s:%d %@(%p) VCBitrateArbiter: no carrier bundle values found"
+ " [%s] %s:%d %@(%p) VCBitrateArbiter: received connectionType %d"
+ " [%s] %s:%d %@(%p) VCCM: Setting up network condition monitor with the following settings badWifiChannelQualityScoreThreshold=%.2f badCellSignalStrengthBarsThresholdFactor=%.2f badCellSignalStrengthBarsThresholdOffset=%.2f wifiChannelQualityScoreEnvelopeAttackFactor=%.2f wifiChannelQualityScoreEnvelopeDecayFactor=%.2f cellSignalStrengthBarsEnvelopeAttackFactor=%.2f cellSignalStrengthBarsEnvelopeDecayFactor=%.2f _brokenBackhaulDetectionTriggerThreshold=%.2f"
+ " [%s] %s:%d %@(%p) VCControlChannelDelegate receivedMessage callback with message '%@%@'"
+ " [%s] %s:%d %@(%p) VCCryptor_Encrypt failed with error '%d'"
+ " [%s] %s:%d %@(%p) VCDatagramChannelManager: added datagram channel with token %d"
+ " [%s] %s:%d %@(%p) VCDatagramChannelManager: removed datagram channel with token=%d"
+ " [%s] %s:%d %@(%p) VCFeatureExperimentSetting: AB Test for experiment %@=%u. forceDisable=%d Experiment is %s"
+ " [%s] %s:%d %@(%p) VCFeatureExperimentSetting: Experiment value not found for %@"
+ " [%s] %s:%d %@(%p) VCFeatureExperimentSetting: Forcing AB Test for experiment=%@ from treatmentGroup=%u to control. result=%d"
+ " [%s] %s:%d %@(%p) VCFeatureExperimentSetting: Found experiment group. decayFactorExperimentGroup=%d"
+ " [%s] %s:%d %@(%p) VCFeatureExperimentSetting: Local rtxVersion=%d"
+ " [%s] %s:%d %@(%p) VCFeatureExperimentSetting: Using fecHeaderVersion=%d"
+ " [%s] %s:%d %@(%p) VCFeatureExperimentSetting: Using plrDecayFactor=%f"
+ " [%s] %s:%d %@(%p) VCMediaRecorder set capabilities %d"
+ " [%s] %s:%d %@(%p) VCNetworkFeedbackController already stopped"
+ " [%s] %s:%d %@(%p) VCRCML enrollment disabled through storebags"
+ " [%s] %s:%d %@(%p) VCRCML enrollment forced by user default rateControlMLAlgorithmMode"
+ " [%s] %s:%d %@(%p) VCRealTimeThread_Start for session stats controller %s"
+ " [%s] %s:%d %@(%p) VCRedundancyControllerVideo using statistics _type=%d for receiving statistics"
+ " [%s] %s:%d %@(%p) VCRemoteVideoManager: queue %s --> get slot# %lu for streamToken %u(%d)"
+ " [%s] %s:%d %@(%p) VCSessionMessageTopic with topic %s dealloc"
+ " [%s] %s:%d %@(%p) VCSessionMessaging dealloc"
+ " [%s] %s:%d %@(%p) VCSessionMessaging: sendMessage:%@ for participantID:%llu, %@, %@"
+ " [%s] %s:%d %@(%p) VCSessionMessaging: sendMessageDictionary=%@ for participantID=%llu, topicKey=%@, topic=%@"
+ " [%s] %s:%d %@(%p) VCTransportSession: Setting connection selection version: local='%@', remote='%@'"
+ " [%s] %s:%d %@(%p) Video redundancy percentage changed from %d to %d with mode %d"
+ " [%s] %s:%d %@(%p) WRM reporting metrics callID=%llu callType=%llu linkType=%llu videoPause=%llu playBackCount=%llu erasureCount=%llu erasureCountSpeech=%llu packetsReceivedSilence=%llu nominalJitterBufferDelay=%llu primaryVideoPacketsReceived=%llu primaryAudioPacketsReceived=%llu totalVideoPacketsReceived=%llu totalAudioPacketsReceived=%llu totalVideoPacketsExpected=%llu totalAudioPacketsExpected=%llu"
+ " [%s] %s:%d %@(%p) WRM: Get iRAT Coex Metrics %s"
+ " [%s] %s:%d %@(%p) WRMClient cleanup start."
+ " [%s] %s:%d %@(%p) WRMClient setup start."
+ " [%s] %s:%d %@(%p) We have received the first active connection, we can now start OneToOne"
+ " [%s] %s:%d %@(%p) [RDAR] _orientationMismatchFullScreenAspectRatioLandscape=%fx%f _frontCameraFullScreenSupported=%d _backCameraFullScreenSupported=%d _deviceInitialOrientation=%d"
+ " [%s] %s:%d %@(%p) [RDAR] frontCameraFullScreenSupported=%d backCameraFullScreenSupported=%d"
+ " [%s] %s:%d %@(%p) _caQueue=%x, imageQueueProtected=%d"
+ " [%s] %s:%d %@(%p) _operatingMode=%d, _vpOperatingMode=%d"
+ " [%s] %s:%d %@(%p) _powerPolicy=%@ _captureFrameRate=%d _captureSource=%d"
+ " [%s] %s:%d %@(%p) _videoPriorityEnabled=%d, maxMediaBitrate=%u, encodingMode=%d"
+ " [%s] %s:%d %@(%p) _vpOperatingMode=%d, priority=%d"
+ " [%s] %s:%d %@(%p) cannedVideoType = %d"
+ " [%s] %s:%d %@(%p) conferenceMode=%d, deviceRole=%d, vpOperatingMode=%d"
+ " [%s] %s:%d %@(%p) currentRedundancyPercentage before abTestSwitch %d"
+ " [%s] %s:%d %@(%p) enableCoreMotionDetection=%d enableMotionBasedDuplication=%d"
+ " [%s] %s:%d %@(%p) frame rate is %f, video contains %d frames"
+ " [%s] %s:%d %@(%p) isFastLQMReportingEnabled=%u isWiFiRoamHandoverEnabled=%u"
+ " [%s] %s:%d %@(%p) isTetheredDisplayMode[%d]"
+ " [%s] %s:%d %@(%p) kCMSessionProperty_VPBlockConfiguration sampleRateIn=%f, sampleRateOut=%f"
+ " [%s] %s:%d %@(%p) kCMSessionProperty_VPBlockConfiguration vpBlockDict=%s, success=%{BOOL}d"
+ " [%s] %s:%d %@(%p) layer host mode=%d slot=%u context=%u"
+ " [%s] %s:%d %@(%p) linkSwitchSyncEnabled=%d cadence=%ums timeout=%ums; earlyDuplicationEnabled=%d wifiAssistCouplingEnabled=%d icAvailable=%d icState=%d"
+ " [%s] %s:%d %@(%p) maxAllowedRedundancyPercentage after abTestSwitch %d"
+ " [%s] %s:%d %@(%p) non-LTE RAT not supported."
+ " [%s] %s:%d %@(%p) oneToOneMode=%s"
+ " [%s] %s:%d %@(%p) oneToOneScreenEnabled=%s"
+ " [%s] %s:%d %@(%p) passMessage: Participant '%@': Added message ID '%@' to message history '%@', expireTime '%@'"
+ " [%s] %s:%d %@(%p) passMessage: ParticipantID '%@': Ignoring duplicate message '%@' with transactionID '%@' for topic '%@'"
+ " [%s] %s:%d %@(%p) passMessage: ParticipantID '%@': Passing message '%@' with transactionID '%@' for topic '%@'"
+ " [%s] %s:%d %@(%p) priority %hhu"
+ " [%s] %s:%d %@(%p) reportAndReset returned nil"
+ " [%s] %s:%d %@(%p) requestRedundancy %s"
+ " [%s] %s:%d %@(%p) requested frameIndex smaller than previously decoded frame index, rewind the video to the beginning"
+ " [%s] %s:%d %@(%p) result=%d"
+ " [%s] %s:%d %@(%p) sendMessage topic=%@ reliable=%d, concurent=%d, outgoingIndex=%d, lastOutgoingIndex=%d, retries=%d"
+ " [%s] %s:%d %@(%p) skipping IFD stats: monitor=%p, param=%p"
+ " [%s] %s:%d %@(%p) start local session stats update"
+ " [%s] %s:%d %@(%p) starting audioIO=%p"
+ " [%s] %s:%d %@(%p) streamID %d"
+ " [%s] %s:%d %@(%p) streamToken=%u"
+ " [%s] %s:%d %@(%p) supportsPSVoiceOnAP=%d, radioVendor=%u"
+ " [%s] %s:%d %@(%p) switched streamID %hu -> %hu"
+ " [%s] %s:%d %@(%p) token[%ld] state[%s]"
+ " [%s] %s:%d %@(%p) useIDSLinkSuggestionFeatureFlag=%d"
+ " [%s] %s:%d %@(%p) useIDSLinkSuggestionFeatureFlag=%d enableNetworkConditionMonitoring=%d shouldForceRelayLinksWhenScreenEnabled=%d, _useMediaDrivenDuplicationFeatureFlag=%d _disallowAlternateConnectionForRTXSupportWhenVideoDegraded=%d"
+ " [%s] %s:%d %@(%p) useOptimizedHandoversForTelephony=%d deferredNetworkUplinkClockEnabled=%d"
+ " [%s] %s:%d %@(%p) video payload types=%@, audio payload types=%@"
+ " [%s] %s:%d %@(%p) videoBufferDescription=%@"
+ " [%s] %s:%d %@(%p) videoFeatureStringsFixedPosition=%@"
+ " [%s] %s:%d %@(%p) { VCAudioTierPickerConfig: mode=%d headerSize=%lu usingCellular=%d isUseCaseWatchContinuity=%d defaultMaxCap=%lu alwaysOnAudioRedundancyEnabled=%d cellularAllowRedLowBitratesEnabled=%d wifiAllowRedLowBitratesEnabled=%d supportedPacketsPerBundle=(%@) supportedRedNumPayloads=(%@) }"
+ " [%s] %s:%d %s: self=%p hardware does not support 2G, ignored storebag value of %d"
+ " [%s] %s:%d %s: self=%p hardware does not support 3G, ignored storebag value of %d"
+ " [%s] %s:%d %s: self=%p hardware does not support 5G, ignored storebag value of %d"
+ " [%s] %s:%d %s: self=%p hardware does not support LTE, ignored storebag value of %d"
+ " [%s] %s:%d %s: self=%p hardware does not support Wi-Fi, ignored storebag value of %d"
+ " [%s] %s:%d %s: self=%p max bitrate for constrained wifi set to %d, enabled setting=%d"
+ " [%s] %s:%d %s: self=%p overriding 2G AppleCalling bitrate with storebag value of %d"
+ " [%s] %s:%d %s: self=%p overriding 2G bitrate with storebag value of %d"
+ " [%s] %s:%d %s: self=%p overriding 3G AppleCalling bitrate with storebag value of %d"
+ " [%s] %s:%d %s: self=%p overriding 3G ScreenShare bitrate with storebag value of %d"
+ " [%s] %s:%d %s: self=%p overriding 3G bitrate with storebag value of %d"
+ " [%s] %s:%d %s: self=%p overriding 5G AppleCalling bitrate with storebag value of %d"
+ " [%s] %s:%d %s: self=%p overriding 5G bitrate with storebag value of %d"
+ " [%s] %s:%d %s: self=%p overriding LTE AppleCalling bitrate with storebag value of %d"
+ " [%s] %s:%d %s: self=%p overriding LTE ScreenShare bitrate with storebag value of %d"
+ " [%s] %s:%d %s: self=%p overriding LTE bitrate with storebag value of %d"
+ " [%s] %s:%d %s: self=%p overriding ScreenShare 2G bitrate with storebag value of %d"
+ " [%s] %s:%d %s: self=%p overriding TCP Relay bitrate with storebag value of %d"
+ " [%s] %s:%d %s: self=%p overriding Wi-Fi bitrate with storebag value of %d"
+ " [%s] %s:%d (%p)"
+ " [%s] %s:%d (%p) ### VCRealTimeThread_Start(%s) called!"
+ " [%s] %s:%d (%p) ### VCRealTimeThread_Stop(%s) called!"
+ " [%s] %s:%d (%p) ### VCRealTimeThread_ThreadProc(%s) pausing!"
+ " [%s] %s:%d (%p) ### VCRealTimeThread_ThreadProc(%s) running!"
+ " [%s] %s:%d (%p) ### VCRealTimeThread_ThreadProc(%s) start!"
+ " [%s] %s:%d (%p) ### VCRealTimeThread_ThreadProc(%s) stop!"
+ " [%s] %s:%d (%p) %s Timescale successfully initialized "
+ " [%s] %s:%d (%p) %s Unexpected timestamp received: %u, expected:%u hostTimeDelta=%f lastTimestamp=%llu -> timestamp=%llu"
+ " [%s] %s:%d (%p) Adding kVTCompressionSessionOption_AllowClientProcessEncode=%@ to encoderSpecification"
+ " [%s] %s:%d (%p) Configuring Crypto Set"
+ " [%s] %s:%d (%p) Configuring queue discard threshold=%f"
+ " [%s] %s:%d (%p) Connection is not on cellular context=%@ isLocal=%d"
+ " [%s] %s:%d (%p) Cryptor is valid, nothing to do here"
+ " [%s] %s:%d (%p) Entering OWRD SPIKE %.4f - %.4f > %.4f"
+ " [%s] %s:%d (%p) Failed due to encryption material not being ready"
+ " [%s] %s:%d (%p) Failed to start due to failing to get new instance"
+ " [%s] %s:%d (%p) First packet received"
+ " [%s] %s:%d (%p) Generated a key frame for FIR(%d)"
+ " [%s] %s:%d (%p) HandoverReport: Ignoring iRAT notification because the reason for recommendation is WiFi link going down"
+ " [%s] %s:%d (%p) HandoverReport: send - last received packet with index %d, %u, bucket [%u %u %u] ratios [%u %u]"
+ " [%s] %s:%d (%p) HandoverReport: set _isPreWarmStateEnabled state to %d. Do %s duplicate the RTCP packets. %s active probing on links"
+ " [%s] %s:%d (%p) HandoverReport: updateConnectionForDuplication check connection %@"
+ " [%s] %s:%d (%p) HandoverReport: updateConnectionForDuplication isLocalPreferWiFi %d isRemotePreferWiFi: %d duplicationEnhancementEnabled: %d duplicationReason: %d useLinkPriorityForSelection: %d secondary connection %@"
+ " [%s] %s:%d (%p) HandoverReport: updateDuplicationStateWithAlertInfo - isOnLocal: %d isAlertEnabled: %d connectionWiFiCount: %d connectionCellCount: %d isDuplicationDisabledDueToAlert: %d"
+ " [%s] %s:%d (%p) Invalid capture height"
+ " [%s] %s:%d (%p) Invalid capture width"
+ " [%s] %s:%d (%p) Invalid key material passed in callback"
+ " [%s] %s:%d (%p) Invalid key material received '%@'"
+ " [%s] %s:%d (%p) Invalid visible rect"
+ " [%s] %s:%d (%p) Jitter Buffer Created Successfully"
+ " [%s] %s:%d (%p) Jitter Queue was reset"
+ " [%s] %s:%d (%p) Jitter buffer configured with mode=%d"
+ " [%s] %s:%d (%p) Just picked a new reference. OWRD should have been reset. OWRD = %f"
+ " [%s] %s:%d (%p) Key material with MKI=%s is not ready yet"
+ " [%s] %s:%d (%p) Leaving OWRD SPIKE due to flatness"
+ " [%s] %s:%d (%p) Leaving OWRD SPIKE due to recovery"
+ " [%s] %s:%d (%p) MKI has changed from '%s' to '%s'"
+ " [%s] %s:%d (%p) New instance created=%p incompleteFrameBufferDuration=%f"
+ " [%s] %s:%d (%p) PSOLA is enabled, Sample Rate = %d, "
+ " [%s] %s:%d (%p) Parameter '%@' is currently not set for packet filter"
+ " [%s] %s:%d (%p) RTP(%d): recv started(%X,%X, %d) SeqNum = %u, TimeStamp = %u"
+ " [%s] %s:%d (%p) RTPSetCellularUniqueTag vfd = %d tag = 0x%X(%u)"
+ " [%s] %s:%d (%p) RTPSetRemoteSSRC: SSRC = 0x%X(%u)"
+ " [%s] %s:%d (%p) RTPTransport: done waiting for SRTP to init. (%d/%d)"
+ " [%s] %s:%d (%p) RTPTransport: need to wait for SRTP to init? (%d/%d)"
+ " [%s] %s:%d (%p) Remote SSRC not set on filter"
+ " [%s] %s:%d (%p) Requesting kVTEncodeFrameOptionKey_ForceKeyFrame"
+ " [%s] %s:%d (%p) SSRC:%X"
+ " [%s] %s:%d (%p) Setting priority %d on encoder"
+ " [%s] %s:%d (%p) Setting vadfilteringEnabled=%d"
+ " [%s] %s:%d (%p) Should resize frames for media recording:%d"
+ " [%s] %s:%d (%p) Successful thread state transition: %d -> %d"
+ " [%s] %s:%d (%p) Successfully removed vfd set with id: %d"
+ " [%s] %s:%d (%p) Target boosting has changed: targetBoostMode=%s, minQueueSize=%.2f, currentTargetSize=%.2f, targetBoostingInSec=%.2f"
+ " [%s] %s:%d (%p) Thread state transition failed: %d -> %d"
+ " [%s] %s:%d (%p) Timescale algorithm selected is %d"
+ " [%s] %s:%d (%p) Updated DTMF sampleRate=%d isOctedAligned=%d convertedSamples=%d"
+ " [%s] %s:%d (%p) Using Hardware Video Decoder"
+ " [%s] %s:%d (%p) VCCryptorCommon_EnsureCryptorIsReady failed to find key material from '%@' with disableMKI array '%@'"
+ " [%s] %s:%d (%p) VCCryptor_SetupCryptor failed for key material '%@'"
+ " [%s] %s:%d (%p) VCSecurityKeyHolder_CopyKeyMaterialForKeyIndex failed, MKI=%s"
+ " [%s] %s:%d (%p) VCSecurityKeyHolder_RegisterForKeyMaterialChangeNotification failed"
+ " [%s] %s:%d (%p) VCTransportStreamCopyProperty %@ failed %d"
+ " [%s] %s:%d (%p) VCVideoCaptureServer_InCallServicePID: clientPID=%d"
+ " [%s] %s:%d (%p) VTP_SetPayloadList for vfd=%d: nPlList=%i payloads=%s"
+ " [%s] %s:%d (%p) [AR_RX] AspectRatio fromVisibleRect=%.3f, fromContentRect=%.3f"
+ " [%s] %s:%d (%p) [AR_RX] frameWidth=%d, frameHeight=%d secondaryCameraStream=%d"
+ " [%s] %s:%d (%p) [AR_RX] participantUUID=%@ visibleRect=%s remoteVideoAttributes=%@ "
+ " [%s] %s:%d (%p) callID = %u, network status bar request, useCellPrimayInterface = %d"
+ " [%s] %s:%d (%p) encodedFormat=%s internalFormat=%s codecSecondsPerFrame=%f internalBlockSize=%d useRTC=%d amrOctetAligned=%d payload=%d selectedPayload=%d networkPayload=%d flags=%d codecBlockSize=%d forceEVSWideBandforAMR=%d headerFormat=%d"
+ " [%s] %s:%d (%p) isCellular[%d] localCellTech[%d] remoteCellTech[%d]"
+ " [%s] %s:%d (%p) kVCPacketFilterRTCPProperty_RemoteSSRC not set"
+ " [%s] %s:%d (%p) kVTDecompressionSessionOption_ClientPID=%@, clientPID=%d"
+ " [%s] %s:%d (%p) mediaType=%@ trackID=%d trackLength=%f"
+ " [%s] %s:%d (%p) mediaURL=%@ trackCount=%lu fileSize=%.2f%cB fileLength=%f"
+ " [%s] %s:%d (%p) new vfd=%d->fd=%d, and add to list"
+ " [%s] %s:%d (%p) payloadType=%d, sourceRate=%u"
+ " [%s] %s:%d (%p) qrExperiment Dictionary=nil"
+ " [%s] %s:%d (%p) removed vfd (%d) from the list"
+ " [%s] %s:%d (%p) streamToken[%ld]"
+ " [%s] %s:%d (%p) streamToken[%ld] screenAttributes[%s]"
+ " [%s] %s:%d (%p) streamToken[%ld] videoAttributes[%s]"
+ " [%s] %s:%d (%p) targetScreenAttributes ratio=%fx%f"
+ " [%s] %s:%d (%p) vfd=%d protocol=%s closed."
+ " [%s] %s:%d (%p) width=%d, height=%d, encodingMode=%d"
+ " [%s] %s:%d @:@ VCRemoteVideoManager-newQueueForStreamToken self=%p streamToken=%ld mode=%d imageQueueProtected=%d"
+ " [%s] %s:%d @:@ VCRemoteVideoManager-resetDidReceiveFirstFrame self=%p streamToken=%ld"
+ " [%s] %s:%d @=@ Health: VCAudioHALController (%p) callbackCount=%llu, averagePower=%f"
+ " [%s] %s:%d @=@ Health: VCAudioStreamReceiveGroup self=%p %@ speakerProcsCalled=%ld, averageOutputPower=%f, syncTargetCalled=%ld"
+ " [%s] %s:%d @=@ Health: VCEffectsManager Frames[Sent=%d (%f FPS), Received=%d (%f FPS), Dropped=%d, Failed=%d, WithFace=%d] TotalFaceObjects=%d"
+ " [%s] %s:%d @=@ Health: VideoTransmitter (%p) streamID=%d, streamGroupId=%s, toBeBufferedFrameCount=%d, bufferedFrameCount=%d, encoderProcCount=%d, transmitterProcCount=%d toBeEncodedFrameCount=%d, encodedFullFrameCount=%d, encodedFullFrameRate=%f, encodedFrameCount=%d, encodedFrameRate=%f, transmittedFrameCount=%d, transmittedNonFECFrameCount=%d, singlePacketFrameCount=%d, currentMediaBitrate=%f, currentHeaderBitrate=%f, currentFECBitrate=%f, currentTotalBitrate=%f, currentFECOverhead=%2.4f targetBitrate=%d deltaKeyFramesSent=%d"
+ " [%s] %s:%d Audio buffer is NULL"
+ " [%s] %s:%d Audio buffer size is 0"
+ " [%s] %s:%d Configuration is NULL"
+ " [%s] %s:%d Device invalidated while still started; caller skipped -stop"
+ " [%s] %s:%d Exception starting capture session context=%@, reason=%@"
+ " [%s] %s:%d Exception stopping capture session context=%@, reason=%@"
+ " [%s] %s:%d Failed to allocate delay monitor"
+ " [%s] %s:%d Failed to allocate the buffer list"
+ " [%s] %s:%d Failed to create health monitor"
+ " [%s] %s:%d Failed to create power estimator"
+ " [%s] %s:%d Failed to create power estimator block allocator"
+ " [%s] %s:%d Failed to create power estimator block header allocator"
+ " [%s] %s:%d Failed to send immediate TMMBR - result:%d"
+ " [%s] %s:%d Failed to set up the power estimator"
+ " [%s] %s:%d FigSampleBufferGetFormatDescription: show format desc, encoderArgs=%p useSPS=%d"
+ " [%s] %s:%d Generated audio stream token=%@"
+ " [%s] %s:%d Generated video stream token=%@"
+ " [%s] %s:%d Invalid channel index=%u count=%u"
+ " [%s] %s:%d Invalid estimator ref parameter"
+ " [%s] %s:%d Max channel count should be bigger than 0"
+ " [%s] %s:%d Not float format, formatFlags=0x%x"
+ " [%s] %s:%d Notified of new keyMaterial '%@'"
+ " [%s] %s:%d Period should be bigger than 0"
+ " [%s] %s:%d VCFeatureExperimentSetting: (%p) Failed to get experiment value. Experiment value not found. name=%s"
+ " [%s] %s:%d [HKSV3] Using empty FLS for groupID=%u in HomeKit mode"
+ " [%s] %s:%d [VCOverlayManager] (%p) overlay created with token=%ld"
+ " [%s] %s:%d [VCOverlayManager] (%p) releasing overlay with token=%ld"
+ " [%s] %s:%d cmf definition is NULL"
+ " [%s] %s:%d format is nil"
+ " [%s] %s:%d frame rate is %f, video contains %d frames"
+ " [%s] %s:%d isFastLQMReportingEnabled=%u isWiFiRoamHandoverEnabled=%u"
+ " [%s] %s:%d nw_cmf_metadata_prepare_receive_buffers failed, vfd=%d error=%@"
+ " [%s] %s:%d nw_cmf_metadata_prepare_send_buffers failed, vfd=%d error=%@"
+ " [%s] %s:%d nw_protocol_copy_cmf_definition returned NULL"
+ " [%s] %s:%d reportAndReset returned nil"
+ " [%s] %s:%d shouldAddDepthData=%d, _depthDataOutput=%p, needsAdd=%d, needsRemove=%d"
+ " [%s] %s:%d skipping IFD stats: monitor=%p, param=%p"
+ " [%s] %s:%d starting audioIO=%p"
+ " [%s] %s:%d token[%ld] state[%s]"
+ " [%s] %s:%d vfd=%d has NULL nw_connection"
+ " [%s] %s:%d vfd=%d has no CMF protocol metadata"
+ " [%s] %s:%d vfd=%d is not NW mode"
+ " [%s] %s:%d vfd=%d not found"
+ "%s(%p) HandoverReport: connection array %s has %lu connections"
+ "%s(%p) Received IDS data channel event=%d with payload=%s"
+ "%s(%p) Updating screen capture with screenShareDict=%s"
+ "%s(%p) source=%d, client=%p, sourceConfig=%s"
+ "%s, %u, %u, %d, %d, %d, %d, %d, %d, %u, %d, %d, %d, %d, %d, %d, %s, %f, %d, %d, %d, %d, %d, %d, %d, %s, %s, %s, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %f, %d, %f, %f, %f, %f, %f, %d, %d, %d, %d, %f, %f, %d, %d, %d, %f, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %f, %f, %f, %f, %f, %f, %f, %f, %f, %f, %f, %d \n"
+ "%s: self=%p hardware does not support 2G, ignored storebag value of %d\n"
+ "%s: self=%p hardware does not support 3G, ignored storebag value of %d\n"
+ "%s: self=%p hardware does not support 5G, ignored storebag value of %d\n"
+ "%s: self=%p hardware does not support LTE, ignored storebag value of %d\n"
+ "%s: self=%p hardware does not support Wi-Fi, ignored storebag value of %d\n"
+ "%s: self=%p max bitrate for constrained wifi set to %d, enabled setting=%d\n"
+ "%s: self=%p overriding 2G AppleCalling bitrate with storebag value of %d\n"
+ "%s: self=%p overriding 2G bitrate with storebag value of %d\n"
+ "%s: self=%p overriding 3G AppleCalling bitrate with storebag value of %d\n"
+ "%s: self=%p overriding 3G ScreenShare bitrate with storebag value of %d\n"
+ "%s: self=%p overriding 3G bitrate with storebag value of %d\n"
+ "%s: self=%p overriding 5G AppleCalling bitrate with storebag value of %d\n"
+ "%s: self=%p overriding 5G bitrate with storebag value of %d\n"
+ "%s: self=%p overriding LTE AppleCalling bitrate with storebag value of %d\n"
+ "%s: self=%p overriding LTE ScreenShare bitrate with storebag value of %d\n"
+ "%s: self=%p overriding LTE bitrate with storebag value of %d\n"
+ "%s: self=%p overriding ScreenShare 2G bitrate with storebag value of %d\n"
+ "%s: self=%p overriding TCP Relay bitrate with storebag value of %d\n"
+ "%s: self=%p overriding Wi-Fi bitrate with storebag value of %d\n"
+ "(%p) A/B testing: %s"
+ "(%p) Experiment Manger created with clientExperiments=%s"
+ "(%p) Register screen config=%s"
+ "(%p) _fecLevelPerBlockSizeVector=\n%s\n"
+ "-[VCAVFoundationCapture safeStartRunning:]"
+ "-[VCAVFoundationCapture safeStopRunning:]"
+ "-[VCAudioHALController startHealthMonitor]"
+ "-[VCAudioHALMicDevice invalidate]_block_invoke"
+ "-[VCAudioRedBuilder setSamplesPerFrame:]"
+ "-[VCAudioStream shouldEnableInactiveFramesDetection:streamConfig:]"
+ "-[VCAudioStream updateReportingConfigForHomeKitV3]"
+ "-[VCInterframeDelayMonitor _recordFirstFrameWithPresentationTime:hostTime:frameSequenceNumber:]"
+ "-[VCNetworkFeedbackController initializeWRMInfo]_block_invoke"
+ "-[VCTransportSessionNW copyCMFProtocolMetadataForConnectionInfo:]"
+ "-[VCVideoStreamRateAdaptation sendTMMBRImmediately]"
+ "-[VCVideoStreamReceiver gatherInterframeDelayStats:]"
+ "2235.52.1.11.1"
+ "AUIO [%s] %s:%d (%p) AUIO Closed Handle."
+ "AUIO [%s] %s:%d (%p) AUIO Stop!"
+ "AUIO [%s] %s:%d (%p) AudioUnitInitialize succeeded"
+ "AUIO [%s] %s:%d (%p) Changed mute to %u"
+ "AUIO [%s] %s:%d (%p) Creating \"%s\" Component Instance"
+ "AUIO [%s] %s:%d (%p) MutedTalker feature enabled"
+ "AUIO [%s] %s:%d (%p) Registering mutedTalker feature"
+ "AUIO [%s] %s:%d (%p) Unregistering mutedTalker feature"
+ "AUIO [%s] %s:%d IO Proc health monitor called with invalid handle=%p"
+ "AVCRC [%s] %s:%d %@(%p) Server bag dictionary is empty."
+ "AVCRC [%s] %s:%d %@(%p) VCRC Experiment groupIndex=%d populationDistribution=%@ randomValue=%f"
+ "AVCRC [%s] %s:%d %@(%p) operatingMode=%d, experimentEnabled=%d, keys=%s"
+ "AVConferencePreview [%s] %s:%d AVConferencePreview: Failed to allocate _cameraUIDToSession"
+ "AVConferenceXPCServer [%s] %s:%d %@(%p) VCXPCServer: AVConferenceXPCServer _xpc_handle_connection incoming request"
+ "AVConferenceXPCServer [%s] %s:%d %@(%p) VCXPCServer: _xpc_add_connection_to_list PID %d"
+ "AdditionalOffset"
+ "STime,FrameSeqNum,FrameTimestamp,SampleRate,FrameSPF,FrameDtx,FrameSize,IsREDFrame,InSilence (low energy),SilencePredicted,FrameCodec,QueuedSamples,LeftOverSamples,AvgQSize,DesiredQSize,IsTargetCovered,TargetBoostingMode,TargetBoostingInSec,SpeechOnsetProtected,SpeechOffsetProtected,SamplesToAdjust,SamplesAdjusted,SamplesRequested,LeftOverSamplesOutput,SamplesNeed,PlayerMode,QueueGrowthMode,DecodeType,SamplesDecoded,DecSkip:Adjust,DecSkip:SamplesOut,SamplesIn,SamplesOut,InputBufferSampleCount,OutputBufferSampleCount,InputBufferTS,OutputBufferTS,IsNilDecode,NilDecodeCount,IsErasure,ErasuresCount,PacketLifeTime,PacketLifetimeCDFBin,PacketLifeTime5Perc,PacketLifeTime10Perc,PacketLifeTimeAvg,PacketLifeTime90Perc,InterArrivalTime,PacketLifetimeIsTrendingUp,PacketLifetimeIsTrendingDown,PacketLifetimeZeroCount,NumberOfPacketsWithHighInterarrival,AvgQSizeInSec,DesiredQSizeInSec,Underflow,ErasuresCountShortWindow,ErasuresCountLongWindow,QueueSteeringOffset,ShouldGrowQueue,ShouldShrinkQueue,ShouldProactivelyShrinkQueue,CurrentIndex,packetLifetimeIsLow,SpikeNeedsProtection,MinimumQueueSizeProtected,QueueSteeringIsPositive,NewSpikeDetected,ExitedSpike,FrequentSpikes,queueGrewDueToSpike,SpikeDetected,SteeringNegativeWithErasures,LowQueueSize,HighQueueSize,ErasuresLongTermIsZero,ErasuresShortTermIsZero,ErasureReduced,TenPercentileHigherThanMin,FivePercentileHigherThanMin,NinetyPercentileHigherThanTarget,PacketLifetimeAvgHigherThanTarget,NegativeQueueSteeringWithErasures,SomePacketsHadZeroPacketLifetime,HasHighInterarrivalFrames,FirstSpeechPacketLifetime,IsNormalPacketFlow,JitterIsLow,MinQueueSizeBuildThreshold,IsMinQueueRebuilt,QueueSizeThresholdMet,PacketLifetimeThresholdMet,ShouldExitQueueGrowth,Channel1Rms,Channel2Rms,Channel1RmsAvg,Channel2RmsAvg,EnergyDecayFactor,Rms,RmsAvg,SilenceAvgFrameSize,SilenceMaxFrameSizeLimit,AudioAvgFrameSize,AudioMinFrameSizeLimit,SilencePredictionEnabled,\n"
+ "VCAudioPlayer [%s] %s:%d (%p) Audio Player initialized with format=%s samplesPerFrame=%u useFloats=%{BOOL}d bufferQueueManagementMode=%d timescaleAlgorithm=%d dtmfTonePlaybackEnabled=%d minJitterBufferQueueSize=%d dtmfEventCallbacksEnabled=%d enableEnhancedJBAdaptations=%d isFixedJitterBufferInitialOvershootResiliencyEnabled=%{bool}d"
+ "VCAudioPlayer [%s] %s:%d (%p) Finalizing Audio Player"
+ "VCAudioPlayer [%s] %s:%d (%p) Late packets played=%d currentTimestamp=%u currentSeqNum=%d"
+ "VCAudioPlayer [%s] %s:%d (%p) New Stream"
+ "VCAudioPlayer [%s] %s:%d (%p) Queue steering callbacks configured"
+ "VCAudioPlayer [%s] %s:%d NO queueSize=%d desiredQSize=%d queuedSamples=%u"
+ "VCAudioPlayer [%s] %s:%d YES queueSize=%d desiredQSize=%d queuedSamples=%u"
+ "VCAudioPowerEstimatorBlock"
+ "VCAudioPowerEstimatorBlockHeader"
+ "VCAudioPowerEstimator_Create"
+ "VCAudioReceiver [%s] %s:%d VCAudioReceiver[%p] Initialized with JitterBuffer=%p for direction=%d enableAACELDInactiveFrameDetection=%d %s"
+ "VCAudioRedBuilder [%s] %s:%d VCAudioRedBuilder setSamplesPerFrame: ignoring zero value; retaining samplesPerFrame=%u"
+ "VCAudioStream [%s] %s:%d %@(%p) Setting audioTransmitterConfig.operatingMode=%d streamConfig.multiwayConfig.isOneToOne=%d streamConfig.oneToOneOperatingMode=%d _operatingMode=%d"
+ "VCAudioStream [%s] %s:%d %@(%p) alreadyStarted = %d"
+ "VCAudioStream [%s] %s:%d %@(%p) created audioIO=%p operatingMode:%d deviceRole:%d direction:%d"
+ "VCAudioStream [%s] %s:%d %@(%p) operatingMode=%d based on audioStreamMode defaultConfig.audioStreamMode=%ld"
+ "VCAudioStream [%s] %s:%d %@(%p) pausing audioIO=%p"
+ "VCAudioStream [%s] %s:%d %@(%p) reconfigured audioIO=%p operatingMode:%d deviceRole:%d direction:%d"
+ "VCAudioStream [%s] %s:%d %@(%p) resume audioIO=%p"
+ "VCAudioStream [%s] %s:%d %@(%p) starting audioIO=%p"
+ "VCAudioStream [%s] %s:%d %@(%p) streamCount=%u reached or exceeded max=%u, dropping excess streams"
+ "VCAudioStream [%s] %s:%d (%p) Abnormal OWRD Verification: rtt=%f, owrd=%f, _abnormalOWRDCount=%d"
+ "VCAudioStream [%s] %s:%d (%p) RTT=%.3f, TxBW=%ub/sec, PLR=%.2f%%, PLaMR=%.2f%%"
+ "VCAudioStream [%s] %s:%d created audioIO=%p operatingMode:%d deviceRole:%d direction:%d"
+ "VCAudioStream [%s] %s:%d pausing audioIO=%p"
+ "VCAudioStream [%s] %s:%d reconfigured audioIO=%p operatingMode:%d deviceRole:%d direction:%d"
+ "VCAudioStream [%s] %s:%d resume audioIO=%p"
+ "VCAudioStream [%s] %s:%d self=%p, streamToken=%ld, updated reporting config for HomeKitV3 audio"
+ "VCAudioStream [%s] %s:%d starting audioIO=%p"
+ "VCAudioStream [%s] %s:%d streamCount=%u reached or exceeded max=%u, dropping excess streams"
+ "VCAudioUtil_ComputeRMSPower"
+ "VCBandwidth [%s] %s:%d %@(%p) bitrate=%d, selectedMediaEntries"
+ "VCMediaQueue [%s] %s:%d (%p) IDR frame sent out. Reset lastIDRTimestamp for mediaQueueStreamId=%u, frameSizeInPackets=%u"
+ "VCMediaQueue [%s] %s:%d (%p) IN/OUT RealTime stats are ENABLED"
+ "VCMediaQueue [%s] %s:%d (%p) IN/OUT RealTime stats cannot be malloced"
+ "VCMediaQueue [%s] %s:%d (%p) Refresh frame counter=%d, time=%.4f"
+ "VCMediaQueue [%s] %s:%d (%p) Set internalQueue timestampRateHz=%u for packetType=%d, mediaQueueStreamId=%u"
+ "VCMediaQueue [%s] %s:%d (%p) VCMediaQueue set ECNEnabled=%u"
+ "VCMediaQueue [%s] %s:%d (%p) VCMediaQueue set isFrameBasedRedundancyEnabled=%u"
+ "VCMediaQueue [%s] %s:%d (%p) VCMediaQueue set oneToOne=%u"
+ "VCMediaQueue [%s] %s:%d (%p) VCMediaQueue set with MTU bytes = %u"
+ "VCMediaQueue [%s] %s:%d (%p) VCMediaQueue set with peak bitrate = %u"
+ "VCMediaQueue [%s] %s:%d (%p) VCMediaQueueSendProc thread ended"
+ "VCMediaQueue [%s] %s:%d (%p) VCMediaQueueSendProc thread started"
+ "VCMediaQueue [%s] %s:%d (%p) created successfully with 1 main queue, %d internal queues isRTXEnabled=%d schedulePolicy=%d"
+ "VCMediaQueue [%s] %s:%d (%p) register mediaQueueStreamId=%u with internal queue index=%d"
+ "VCMediaStream [%s] %s:%d %@(%p) Generated _streamToken=%u streamTokenUplink=%u streamTokenDownlink=%u"
+ "VCMediaStream [%s] %s:%d %@(%p) Resetting decryption status"
+ "VCMediaStream [%s] %s:%d %@(%p) UseTransportStreamsForProxy feature flag set"
+ "VCMediaStream [%s] %s:%d %@(%p) _transportArray does not have a oneToOne stream configuration."
+ "VCMediaStream [%s] %s:%d %@(%p) _transportArray is empty, and we are trying to get the default stream config, which does not exist."
+ "VCMediaStream [%s] %s:%d Generated _streamToken=%u streamTokenUplink=%u streamTokenDownlink=%u"
+ "VCRC [%s] %s:%d %@(%p) Detected out of order at send timestamp %X, previousTS:%X, timestampDiff:%d, current owrd:%f"
+ "VCRC [%s] %s:%d %@(%p) Detected spike at receive timestamp %X, previousTS:%X, timestampDiff:%d, average send interval:%f, current owrd:%f"
+ "VCRC [%s] %s:%d %@(%p) Detected spike at send timestamp %X, previousTS:%X, timestampDiff:%d, average send interval:%f, current owrd:%f"
+ "VCRC [%s] %s:%d %@(%p) Detected spike before send timestamp %X, previousTS:%X, timestampDiff:%d, average send interval:%f, current owrd:%f"
+ "VCRC [%s] %s:%d %@(%p) No consecutive out of order with %sTimestamp=%u, previous%sTimestamp=%u, increment oooContinuousRecoveredCount=%d"
+ "VCRC [%s] %s:%d %@(%p) Repeated or out of order timestamp detected when calculating OWRD, sendTime=%f, receiveTime=%f"
+ "VCRC [%s] %s:%d %@(%p) Reset OWRD from %f to 0"
+ "VCRC [%s] %s:%d %@(%p) Reset oooContinuousRecoveredCount, since consecutively out of order with %sTimestamp=%u, previous%sTimestamp=%u"
+ "VCRC [%s] %s:%d %@(%p) Start VCStatisticsCollectorQueue without VCRateControlStatisticsProc thread"
+ "VCRC [%s] %s:%d %@(%p) Stop VCStatisticsCollectorQueue without VCRateControlStatisticsProc thread"
+ "VCRC [%s] %s:%d %@(%p) VCRateControlMediaController init"
+ "VCRC [%s] %s:%d %@(%p) dealloc called"
+ "VCRC [%s] %s:%d %@(%p) start"
+ "VCRC [%s] %s:%d %@(%p) stop"
+ "VCRC [%s] %s:%d (%p) Bandwidth Estimation: Update bandwidth estimator qualification parameters with RAT=%d, mode=%d. [maxBW:%f, minWin:%f, maxOverRange:%d, minPacketCount:%d]"
+ "VCRC [%s] %s:%d (%p) Configuring VCRateControl algorithm with targetBitrate=%d, minBitrate=%d, maxBitrate=%d"
+ "VCRC [%s] %s:%d (%p) Create bandwidth estimator for estimator id: %d"
+ "VCRC [%s] %s:%d start"
+ "VCRC [%s] %s:%d stop"
+ "VCSession [%s] %s:%d %@(%p) Broadcasting initial state. audioEnabled=%d videoEnabled=%d screenEnabled=%d"
+ "VCSession [%s] %s:%d %@(%p) Fixed label '%s' is being used due to default"
+ "VCSession [%s] %s:%d %@(%p) Load switch useMediaDrivenDuplication %d"
+ "VCSession [%s] %s:%d %@(%p) New uplink expected bitrate:%u"
+ "VCSession [%s] %s:%d %@(%p) Participant count:%d"
+ "VCSession [%s] %s:%d %@(%p) Participant:%@ requestKeyFrameGenerationWithStreamID:%d FIRType:%d"
+ "VCSession [%s] %s:%d %@(%p) Security key material with key index '%@' added"
+ "VCSession [%s] %s:%d %@(%p) Session DRTN=%fsec"
+ "VCSession [%s] %s:%d %@(%p) Session will use [%@] data path"
+ "VCSession [%s] %s:%d %@(%p) Tearing down session"
+ "VCSession [%s] %s:%d %@(%p) Using the following path - oneToOneModeEnabled=%d sessionMode=%ld serviceName=%@, oneToOneAuthenticationTagEnabled=%d, gftTLEEnabled=%d, p2pEncryptionEnabled=%d, detectInactiveAudioFramesAACELD=%d %s"
+ "VCSession [%s] %s:%d %@(%p) [AVC SPATIAL AUDIO] Presentation info is nil"
+ "VCSession [%s] %s:%d %@(%p) alwaysHDCaptureScreenEnabled=%d"
+ "VCSession [%s] %s:%d %@(%p) maxActiveVideoDecodes=%d"
+ "VCSession [%s] %s:%d %@(%p) uuid:%@"
+ "VCSession [%s] %s:%d (%p) remoteScreenAttributes=%@"
+ "VCSession [%s] %s:%d @=@ Health: VCSession-remote self=%p remoteParticipant=%@, videoStreamID=%@, audioStreamID=%@, videoRxBitrate=%u kbps, videoRxFrameRate=%3.1f, audioRxBitrate=%u kbps, videoRxResolution=%@, captionsRxBitrate=%u kbps"
+ "VCSession [%s] %s:%d Session DRTN=%fsec"
+ "VCSession [%s] %s:%d Using the following path - oneToOneModeEnabled=%d sessionMode=%ld serviceName=%@, oneToOneAuthenticationTagEnabled=%d, gftTLEEnabled=%d, p2pEncryptionEnabled=%d, detectInactiveAudioFramesAACELD=%d %s"
+ "VCSessionParticipantRemote [%s] %s:%d %@(%p) Add one to one stream config to media stream info for groupID=%s"
+ "VCSessionParticipantRemote [%s] %s:%d %@(%p) Added one to one stream config to %s streamGroup"
+ "VCSessionParticipantRemote [%s] %s:%d %@(%p) Connection timing for participantID=%llu clocked by %@ for this call"
+ "VCSessionParticipantRemote [%s] %s:%d %@(%p) Remote participantID=%llu V2 connection timing=%f, connection timing started=%f clocked by '%s' streamGroup"
+ "VCSessionParticipantRemote [%s] %s:%d %@(%p) Skipping streamGroupID=%s"
+ "VCSessionParticipantRemote [%s] %s:%d %@(%p) VCExperimentManager GFT override RTCReporting for experimentName=%@ value=%u result=%d"
+ "VCSessionParticipantRemote [%s] %s:%d %@(%p) VCExperimentManager U+1 override RTCReporting for experimentName=%@ value=%u result=%d"
+ "VCSoundDec [%s] %s:%d (%p) AudioConverterSetProperty succeeded to set kAudioConverterSampleRateConverterComplexity=%u"
+ "VCSoundDec [%s] %s:%d (%p) AudioConverterSetProperty succeeded to set kAudioConverterSampleRateConverterQuality=%u"
+ "VCSoundDec [%s] %s:%d (%p) AudioConverterSetProperty succeeded to set property kAudioCodecPrivatePropertyEVSCMRSettingInSDPOffer evsCMRMode=%d "
+ "VCSoundDec [%s] %s:%d (%p) AudioConverterSetProperty succeeded to set property kAudioCodecPrivatePropertyEVSFormatHandling evsFormatHandling=%u"
+ "VCSoundDec [%s] %s:%d (%p) AudioConverterSetProperty succeeded to set property kAudioCodecPrivatePropertyEVSSIDPeriod evsSIDPeriod=%u "
+ "VCSoundDec [%s] %s:%d (%p) AudioConverterSetProperty succeeded to set property kAudioCodecPrivatePropertyEnableSAD dtxEnabled=%u"
+ "VCSoundDec [%s] %s:%d (%p) AudioConverterSetProperty succeeded to set property kAudioCodecPrivatePropertySBRHeaderInterval sbrInterval=%u"
+ "VCSoundDec [%s] %s:%d (%p) AudioConverterSetProperty succeeded to set property kAudioCodecPropertyConcealmentMode plcMode=%u"
+ "VCSoundDec [%s] %s:%d (%p) AudioConverterSetProperty succeeded to set property kAudioCodecPropertyCurrentTargetBitRate bitrate=%u"
+ "VCSoundDec [%s] %s:%d (%p) AudioConverterSetProperty succeeded to set property kAudioConverterPropertyUseMessengerForBundleData=%s useMessengerForBundleData=%u"
+ "VCSoundDec [%s] %s:%d (%p) Configuring Ramstad SRC"
+ "VCSoundDec [%s] %s:%d (%p) Leaving SoundDec_Create"
+ "VCSoundDec [%s] %s:%d (%p) NEW AUDIO BITRATE (vbr)=%d fvbrcodec=%d enablePacketSizeLimit=%d"
+ "VCSoundDec [%s] %s:%d (%p) SoundDec_Create: %08x --> %08x"
+ "VCSoundDec [%s] %s:%d (%p) SoundDec_EnableShortRED Requested shortREDEnabled=%d shortREDBytesPerFrame=%u shortREDBitrate=%u"
+ "VCSoundDec [%s] %s:%d (%p) SoundDec_SetBitrate Requested bitrate: %d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) All client stopped; can stop preview"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Setting both front queue framerate %d and back queue framerate %d to %d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Setting current camera framerate currentFrameRate=%d, cappedFrameRate=%d, thermalLevel=%d, peakPowerPressureLevel=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) [AR_RX] localExpectedLandscapeAspectRatio=(%f, %f)"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) [AR_RX] localExpectedPortraitAspectRatio=(%f, %f)"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) [AR_RX] localScreenLandscapeAspectRatio=(%f, %f)"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) [AR_RX] localScreenPortraitAspectRatio=(%f, %f)"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) _defaultPortraitAspectRatio=%@ _defaultLandscapeAspectRatio=%@"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) _remoteSupportsFullScreenReceive=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) isFullScreen=%s"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) localDeviceOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) videoPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d (%p) Invalid camera, cameraSessionType=%d has nil cameraUID"
+ "VCVideoCaptureServer [%s] %s:%d (%p) Unexpected capture frame duration expectedFrameDurationWithThreshold=%f and currentFrameDuration=%f"
+ "VCVideoCaptureServer [%s] %s:%d (%p) notifying clients of first preview frame, cameraSessionType=%d"
+ "VCVideoCaptureServer [%s] %s:%d @:@ VCVideoCaptureServer-connect layers self=%p reconnectClientLayerFront=%d(1-front), slot=%u layerHostMode=%d"
+ "VCVideoCaptureServer [%s] %s:%d @:@ VCVideoCaptureServer-setLocalVideoDestination self=%p previewSlot=%u, front=%d layerHostMode=%d"
+ "VCVideoCaptureServer [%s] %s:%d @=@ Health: VideoCapture-FaceMetadata Front: frames=%d total=%d, Back: frames=%d total=%d"
+ "VCVideoCaptureServer [%s] %s:%d _defaultPortraitAspectRatio=%@ _defaultLandscapeAspectRatio=%@"
+ "VCVideoCaptureServer [%s] %s:%d _supportsCameraPreview=NO"
+ "VCVideoJitterBuffer [%s] %s:%d (%p) Found new lowest minLag of %f for RTPTimestamp=%u"
+ "VCVideoJitterBuffer [%s] %s:%d (%p) Video Jitter Buffer: Created Successfully"
+ "VCVideoStream [%s] %s:%d %@(%p) Loaded storebag values for VCNackGenerator: nackGeneratorStorebagConfigVersion=%u nackSeqNumAgingDuration=%f isExtraDelayForPacketRetransmissionsEnabled=%d nackThrottlingBitRateLimitingMaxRatio=%f nackThrottlingPlrBuckets[%@] nackThrottlingFactorBuckets[%@] nackGenerationMaxPLR=%f nackGenerationMaxRTT=%f rttForRTxFulfillmentWaitTime=%.2f rttForRTxFulfillmentMultiplier=%.2f VCNackGeneratorRtxIncompleteFrameBufferDurationMultiplier=%.2f adaptiveRTTWaitMaxTime=%.2f adaptiveRTTWaitSafetyMargin=%.2f"
+ "VCVideoStream [%s] %s:%d %@(%p) streamCount=%u reached or exceeded max=%u, dropping excess stream"
+ "VCVideoStream [%s] %s:%d (%p) VideoStallTimeTotal=%.2f"
+ "VCVideoStream [%s] %s:%d streamCount=%u reached or exceeded max=%u, dropping excess stream"
+ "VRVIQIFDFCD"
+ "VRVIQIFDFCN"
+ "VRVIQIFDFD"
+ "VTP_PrepareReceiveBuffer_block_invoke"
+ "VTP_PrepareSendBuffer_block_invoke"
+ "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] Failed to assemble ProRes frame result=%d error.reason=%s"
+ "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] ProRes frame without imgDesc and no previous imgDesc received"
+ "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] failed to create ProRes data frame status=%d"
+ "VideoReceiver [%s] %s:%d VideoReceiver[%p] Suppressing FIR increment: waiting for SFrame key (streamIndex=%d)"
+ "VideoReceiver [%s] %s:%d sframeKeyPending=1 streamIndex=%d"
+ "_VCAudioHALController_HealthPrintCallback"
+ "_VCVideoCaptureServer_EnqueuePreviewFrame"
+ "_VCVideoPacketBuffer_AssembleProResFrame"
+ "_VTPWithCMFMetadata"
+ "com.apple.VideoConference.VRLogfile"
+ "detectInactiveAudioFramesACC24=%d"
+ "enableInactiveACC24FrameDetection"
+ "enableWiFiRoamHandover"
+ "i20@?0@\"NSObject<OS_nw_protocol_metadata>\"8i16"
+ "isEnabledACC24InactiveFrameDetection=%d"
+ "kWRMDisWiFiRoamHO"
+ "runtimeErrorRecovery"
+ "setUpSecondaryCamera"
+ "startPreview"
+ "tearDownSecondaryCamera"
+ "vc-ab-testing-detect-inactive-audio-frames-ACC24"
+ "vc-experiment-wifi-roam-handover"
- " [%s] %s:%d ### VCRealTimeThread_Start(%s) called!"
- " [%s] %s:%d ### VCRealTimeThread_Stop(%s) called!"
- " [%s] %s:%d ### VCRealTimeThread_ThreadProc(%s) pausing!"
- " [%s] %s:%d ### VCRealTimeThread_ThreadProc(%s) running!"
- " [%s] %s:%d ### VCRealTimeThread_ThreadProc(%s) start!"
- " [%s] %s:%d ### VCRealTimeThread_ThreadProc(%s) stop!"
- " [%s] %s:%d %@(%p) isFastLQMReportingEnabled=%u"
- " [%s] %s:%d %s Timescale successfully initialized "
- " [%s] %s:%d %s Unexpected timestamp received: %u, expected:%u hostTimeDelta=%f lastTimestamp=%llu -> timestamp=%llu"
- " [%s] %s:%d %s: hardware does not support 2G, ignored storebag value of %d"
- " [%s] %s:%d %s: hardware does not support 3G, ignored storebag value of %d"
- " [%s] %s:%d %s: hardware does not support 5G, ignored storebag value of %d"
- " [%s] %s:%d %s: hardware does not support LTE, ignored storebag value of %d"
- " [%s] %s:%d %s: hardware does not support Wi-Fi, ignored storebag value of %d"
- " [%s] %s:%d %s: max bitrate for constrained wifi set to %d, enabled setting=%d"
- " [%s] %s:%d %s: overriding 2G AppleCalling bitrate with storebag value of %d"
- " [%s] %s:%d %s: overriding 2G bitrate with storebag value of %d"
- " [%s] %s:%d %s: overriding 3G AppleCalling bitrate with storebag value of %d"
- " [%s] %s:%d %s: overriding 3G ScreenShare bitrate with storebag value of %d"
- " [%s] %s:%d %s: overriding 3G bitrate with storebag value of %d"
- " [%s] %s:%d %s: overriding 5G AppleCalling bitrate with storebag value of %d"
- " [%s] %s:%d %s: overriding 5G bitrate with storebag value of %d"
- " [%s] %s:%d %s: overriding LTE AppleCalling bitrate with storebag value of %d"
- " [%s] %s:%d %s: overriding LTE ScreenShare bitrate with storebag value of %d"
- " [%s] %s:%d %s: overriding LTE bitrate with storebag value of %d"
- " [%s] %s:%d %s: overriding ScreenShare 2G bitrate with storebag value of %d"
- " [%s] %s:%d %s: overriding TCP Relay bitrate with storebag value of %d"
- " [%s] %s:%d %s: overriding Wi-Fi bitrate with storebag value of %d"
- " [%s] %s:%d (%p) Generated audio stream token=%@"
- " [%s] %s:%d (%p) Generated video stream token=%@"
- " [%s] %s:%d (%p) streamToken=%u"
- " [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/AVConference.subproj/Sources/VCRemoteVideoManager.m:%d: token[%ld] state[%s]"
- " [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/AVConference.subproj/Sources/VCSecurityKeyManager.m:%d: Notified of new keyMaterial '%@'"
- " [%s] %s:%d @:@ VCRemoteVideoManager-newQueueForStreamToken streamToken=%ld mode=%d imageQueueProtected=%d"
- " [%s] %s:%d @:@ VCRemoteVideoManager-resetDidReceiveFirstFrame streamToken=%ld"
- " [%s] %s:%d @=@ Health: VCAudioStreamReceiveGroup %@ speakerProcsCalled=%ld, averageOutputPower=%f, syncTargetCalled=%ld"
- " [%s] %s:%d @=@ Health: VCEffectsManager Frames Sent: %d (%f FPS) Frames Received: %d (%f FPS) Frames Dropped: %d Frames Failed: %d"
- " [%s] %s:%d @=@ Health: VideoTransmitter streamID=%d, streamGroupId=%s, toBeBufferedFrameCount=%d, bufferedFrameCount=%d, encoderProcCount=%d, transmitterProcCount=%d toBeEncodedFrameCount=%d, encodedFullFrameCount=%d, encodedFullFrameRate=%f, encodedFrameCount=%d, encodedFrameRate=%f, transmittedFrameCount=%d, transmittedNonFECFrameCount=%d, singlePacketFrameCount=%d, currentMediaBitrate=%f, currentHeaderBitrate=%f, currentFECBitrate=%f, currentTotalBitrate=%f, currentFECOverhead=%2.4f targetBitrate=%d deltaKeyFramesSent=%d"
- " [%s] %s:%d Adding kVTCompressionSessionOption_AllowClientProcessEncode=%@ to encoderSpecification"
- " [%s] %s:%d Configuring Crypto Set"
- " [%s] %s:%d Configuring queue discard threshold=%f"
- " [%s] %s:%d Connection is not on cellular context=%@ isLocal=%d"
- " [%s] %s:%d Cryptor is valid, nothing to do here"
- " [%s] %s:%d Entering OWRD SPIKE %.4f - %.4f > %.4f"
- " [%s] %s:%d FigSampleBufferGetFormatDescription: show format desc, %d"
- " [%s] %s:%d Generated a key frame for FIR(%d)"
- " [%s] %s:%d HandoverReport: Ignoring iRAT notification because the reason for recommendation is WiFi link going down"
- " [%s] %s:%d HandoverReport: send - last received packet with index %d, %u, bucket [%u %u %u] ratios [%u %u]"
- " [%s] %s:%d HandoverReport: set _isPreWarmStateEnabled state to %d. Do %s duplicate the RTCP packets. %s active probing on links"
- " [%s] %s:%d HandoverReport: updateConnectionForDuplication check connection %@"
- " [%s] %s:%d HandoverReport: updateConnectionForDuplication isLocalPreferWiFi %d isRemotePreferWiFi: %d duplicationEnhancementEnabled: %d duplicationReason: %d useLinkPriorityForSelection: %d secondary connection %@"
- " [%s] %s:%d HandoverReport: updateDuplicationStateWithAlertInfo - isOnLocal: %d isAlertEnabled: %d connectionWiFiCount: %d connectionCellCount: %d isDuplicationDisabledDueToAlert: %d"
- " [%s] %s:%d Invalid audio buffer list"
- " [%s] %s:%d Invalid capture height"
- " [%s] %s:%d Invalid capture width"
- " [%s] %s:%d Invalid channel index"
- " [%s] %s:%d Invalid key material passed in callback"
- " [%s] %s:%d Jitter Queue was reset"
- " [%s] %s:%d Jitter buffer configured with mode=%d"
- " [%s] %s:%d Just picked a new reference. OWRD should have been reset. OWRD = %f"
- " [%s] %s:%d Key material with MKI=%s is not ready yet"
- " [%s] %s:%d Leaving OWRD SPIKE due to flatness"
- " [%s] %s:%d Leaving OWRD SPIKE due to recovery"
- " [%s] %s:%d MKI has changed from '%s' to '%s'"
- " [%s] %s:%d New instance created=%p incompleteFrameBufferDuration=%f"
- " [%s] %s:%d PSOLA is enabled, Sample Rate = %d, "
- " [%s] %s:%d RTP(%d): recv started(%X,%X, %d) SeqNum = %u, TimeStamp = %u"
- " [%s] %s:%d RTPSetCellularUniqueTag vfd = %d tag = 0x%X(%u)"
- " [%s] %s:%d RTPSetRemoteSSRC: SSRC = 0x%X(%u)"
- " [%s] %s:%d RTPTransport: done waiting for SRTP to init. (%d/%d)"
- " [%s] %s:%d RTPTransport: need to wait for SRTP to init? (%d/%d)"
- " [%s] %s:%d Remote SSRC not set on filter"
- " [%s] %s:%d Requesting kVTEncodeFrameOptionKey_ForceKeyFrame"
- " [%s] %s:%d SSRC:%X"
- " [%s] %s:%d Setting priority %d on encoder"
- " [%s] %s:%d Setting vadfilteringEnabled=%d"
- " [%s] %s:%d Should resize frames for media recording:%d"
- " [%s] %s:%d Successful thread state transition: %d -> %d"
- " [%s] %s:%d Successfully removed vfd set with id: %d"
- " [%s] %s:%d Target boosting has changed: targetBoostMode=%s, minQueueSize=%.2f, currentTargetSize=%.2f, targetBoostingInSec=%.2f"
- " [%s] %s:%d Thread state transition failed: %d -> %d"
- " [%s] %s:%d Timescale algorithm selected is %d"
- " [%s] %s:%d Updated DTMF sampleRate=%d isOctedAligned=%d convertedSamples=%d"
- " [%s] %s:%d Using Hardware Video Decoder"
- " [%s] %s:%d VCCryptorCommon_EnsureCryptorIsReady failed to find key material from '%@' with disableMKI array '%@'"
- " [%s] %s:%d VCCryptor_SetupCryptor failed for key material '%@'"
- " [%s] %s:%d VCFeatureExperimentSetting: Failed to get experiment value. Experiment value not found. name=%s"
- " [%s] %s:%d VCSecurityKeyHolder_RegisterForKeyMaterialChangeNotification failed"
- " [%s] %s:%d VCTransportStreamCopyProperty %@ failed %d"
- " [%s] %s:%d VCVideoCaptureServer_InCallServicePID: clientPID=%d"
- " [%s] %s:%d VTP_SetPayloadList for vfd=%d: nPlList=%i payloads=%s"
- " [%s] %s:%d [AR_RX] AspectRatio fromVisibleRect=%.3f, fromContentRect=%.3f"
- " [%s] %s:%d [AR_RX] frameWidth=%d, frameHeight=%d secondaryCameraStream=%d"
- " [%s] %s:%d [AR_RX] participantUUID=%@ visibleRect=%s remoteVideoAttributes=%@ "
- " [%s] %s:%d [HKSV3] Using empty FLS for came stream group in HomeKit mode"
- " [%s] %s:%d [VCOverlayManager] overlay created with token=%ld"
- " [%s] %s:%d [VCOverlayManager] releasing overlay with token=%ld"
- " [%s] %s:%d callID = %u, network status bar request, useCellPrimayInterface = %d"
- " [%s] %s:%d encodedFormat=%s internalFormat=%s codecSecondsPerFrame=%f internalBlockSize=%d useRTC=%d amrOctetAligned=%d payload=%d selectedPayload=%d networkPayload=%d flags=%d codecBlockSize=%d forceEVSWideBandforAMR=%d headerFormat=%d"
- " [%s] %s:%d frame rate is %f"
- " [%s] %s:%d isCellular[%d] localCellTech[%d] remoteCellTech[%d]"
- " [%s] %s:%d isFastLQMReportingEnabled=%u"
- " [%s] %s:%d isMKIChanged must not be NULL"
- " [%s] %s:%d kVCPacketFilterRTCPProperty_RemoteSSRC not set"
- " [%s] %s:%d kVTDecompressionSessionOption_ClientPID=%@, clientPID=%d"
- " [%s] %s:%d mediaType=%@ trackID=%d trackLength=%f"
- " [%s] %s:%d mediaURL=%@ trackCount=%lu fileSize=%.2f%cB fileLength=%f"
- " [%s] %s:%d payloadType=%d, sourceRate=%u"
- " [%s] %s:%d qrExperiment Dictionary=nil"
- " [%s] %s:%d removed vfd (%d) from the list"
- " [%s] %s:%d shouldAddDepthData=%d, _depthDataOutput=%p"
- " [%s] %s:%d streamToken[%ld]"
- " [%s] %s:%d streamToken[%ld] screenAttributes[%s]"
- " [%s] %s:%d streamToken[%ld] videoAttributes[%s]"
- " [%s] %s:%d targetScreenAttributes ratio=%fx%f"
- " [%s] %s:%d vfd=%d protocol=%s closed."
- " [%s] %s:%d video contains %d frames"
- " [%s] %s:%d width=%d, height=%d, encodingMode=%d"
- " _fecLevelPerBlockSizeVector=\n%s\n"
- "%s, %u, %u, %d, %d, %d, %d, %d, %d, %u, %d, %d, %d, %d, %d, %d, %s, %f, %d, %d, %d, %d, %d, %d, %d, %s, %s, %s, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %f, %d, %f, %f, %f, %f, %f, %d, %d, %d, %d, %f, %f, %d, %d, %d, %f, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %d, %f, %f, %f, %f, %f, %f, %f, %f, %f, %f, %f, %d \n"
- "%s: hardware does not support 2G, ignored storebag value of %d\n"
- "%s: hardware does not support 3G, ignored storebag value of %d\n"
- "%s: hardware does not support 5G, ignored storebag value of %d\n"
- "%s: hardware does not support LTE, ignored storebag value of %d\n"
- "%s: hardware does not support Wi-Fi, ignored storebag value of %d\n"
- "%s: max bitrate for constrained wifi set to %d, enabled setting=%d\n"
- "%s: overriding 2G AppleCalling bitrate with storebag value of %d\n"
- "%s: overriding 2G bitrate with storebag value of %d\n"
- "%s: overriding 3G AppleCalling bitrate with storebag value of %d\n"
- "%s: overriding 3G ScreenShare bitrate with storebag value of %d\n"
- "%s: overriding 3G bitrate with storebag value of %d\n"
- "%s: overriding 5G AppleCalling bitrate with storebag value of %d\n"
- "%s: overriding 5G bitrate with storebag value of %d\n"
- "%s: overriding LTE AppleCalling bitrate with storebag value of %d\n"
- "%s: overriding LTE ScreenShare bitrate with storebag value of %d\n"
- "%s: overriding LTE bitrate with storebag value of %d\n"
- "%s: overriding ScreenShare 2G bitrate with storebag value of %d\n"
- "%s: overriding TCP Relay bitrate with storebag value of %d\n"
- "%s: overriding Wi-Fi bitrate with storebag value of %d\n"
- "-[VCAudioStream shouldEnableAACELDInactiveFrames:streamConfig:]"
- "-[VCInterframeDelayMonitor recordFrameWithPresentationTime:]"
- "-[VCNetworkFeedbackController initializeWRMInfo]"
- "2235.48.1"
- "AUIO [%s] %s:%d AUIO Closed Handle."
- "AUIO [%s] %s:%d AUIO Stop!"
- "AUIO [%s] %s:%d AudioUnitInitialize succeeded"
- "AUIO [%s] %s:%d Changed mute to %u"
- "AUIO [%s] %s:%d Creating \"%s\" Component Instance"
- "AUIO [%s] %s:%d IO Proc health monitor called with invalid HANDLE"
- "AUIO [%s] %s:%d MutedTalker feature enabled"
- "AUIO [%s] %s:%d Registering mutedTalker feature"
- "AUIO [%s] %s:%d Unregistering mutedTalker feature"
- "Experiment Manger created with clientExperiments=%s"
- "Register screen config=%s"
- "STime,FrameSeqNum,FrameTimestamp,SampleRate,FrameSPF,FrameDtx,FrameSize,IsREDFrame,InSilence (low energy),SilencePredicted,FrameCodec,QueuedSamples,LeftOverSamples,AvgQSize,DesiredQSize,IsTargetCovered,TargetBoostingMode,TargetBoostingInSec,SpeechOnsetProtected,SpeechOffsetProtected,SamplesToAdjust,SamplesAdjusted,SamplesRequested,LeftOverSamplesOutput,SamplesNeed,PlayerMode,QueueGrowthMode,DecodeType,SamplesDecoded,DecSkip:Adjust,DecSkip:SamplesOut,SamplesIn,SamplesOut,InputBufferSampleCount,OutputBufferSampleCount,InputBufferTS,OutputBufferTS,IsNilDecode,NilDecodeCount,IsErasure,ErasuresCount,PacketLifeTime,PacketLifetimeCDFBin,PacketLifeTime5Perc,PacketLifeTime10Perc,PacketLifeTimeAvg,PacketLifeTime90Perc,InterArrivalTime,PacketLifetimeIsTrendingUp,PacketLifetimeIsTrendingDown,PacketLifetimeZeroCount,NumberOfPacketsWithHighInterarrival,AvgQSizeInSec,DesiredQSizeInSec,Underflow,ErasuresCountShortWindow,ErasuresCountLongWindow,QueueSteeringOffset,ShouldGrowQueue,ShouldShrinkQueue,ShouldProactivelyShrinkQueue,CurrentIndex,packetLifetimeIsLow,SpikeNeedsProtection,MinimumQueueSizeProtected,QueueSteeringIsPositive,NewSpikeDetected,ExitedSpike,queueGrewDueToSpike,SpikeDetected,SteeringNegativeWithErasures,LowQueueSize,HighQueueSize,ErasuresLongTermIsZero,ErasuresShortTermIsZero,ErasureReduced,TenPercentileHigherThanMin,FivePercentileHigherThanMin,NinetyPercentileHigherThanTarget,PacketLifetimeAvgHigherThanTarget,NegativeQueueSteeringWithErasures,SomePacketsHadZeroPacketLifetime,HasHighInterarrivalFrames,FirstSpeechPacketLifetime,IsNormalPacketFlow,JitterIsLow,MinQueueSizeBuildThreshold,IsMinQueueRebuilt,QueueSizeThresholdMet,PacketLifetimeThresholdMet,ShouldExitQueueGrowth,Channel1Rms,Channel2Rms,Channel1RmsAvg,Channel2RmsAvg,EnergyDecayFactor,Rms,RmsAvg,SilenceAvgFrameSize,SilenceMaxFrameSizeLimit,AudioAvgFrameSize,AudioMinFrameSizeLimit,SilencePredictionEnabled,\n"
- "VCAudioBufferList_ComputeRMSPowerPerChannel"
- "VCAudioPlayer [%s] %s:%d Audio Player initialized with format=%s samplesPerFrame=%u useFloats=%{BOOL}d bufferQueueManagementMode=%d timescaleAlgorithm=%d dtmfTonePlaybackEnabled=%d minJitterBufferQueueSize=%d dtmfEventCallbacksEnabled=%d enableEnhancedJBAdaptations=%d isFixedJitterBufferInitialOvershootResiliencyEnabled=%{bool}d"
- "VCAudioPlayer [%s] %s:%d Finalizing Audio Player"
- "VCAudioPlayer [%s] %s:%d Late packets played=%d currentTimestamp=%u currentSeqNum=%d"
- "VCAudioPlayer [%s] %s:%d NO queueSize=%d desiredQSize=%d queuedSamples=%u shouldCheckForQueueSizeUnderTarget=%d"
- "VCAudioPlayer [%s] %s:%d New Stream"
- "VCAudioPlayer [%s] %s:%d Queue steering callbacks configured"
- "VCAudioPlayer [%s] %s:%d YES queueSize=%d desiredQSize=%d queuedSamples=%u shouldCheckForQueueSizeUnderTarget=%d"
- "VCAudioReceiver [%s] %s:%d VCAudioReceiver[%p] Initialized with JitterBuffer=%p for direction=%d enableAACELDInactiveFrameDetection=%d"
- "VCAudioStream [%s] %s:%d (%p) created audioIO=%p operatingMode:%d deviceRole:%d direction:%d"
- "VCAudioStream [%s] %s:%d (%p) pausing audioIO=%p"
- "VCAudioStream [%s] %s:%d (%p) reconfigured audioIO=%p operatingMode:%d deviceRole:%d direction:%d"
- "VCAudioStream [%s] %s:%d (%p) resume audioIO=%p"
- "VCAudioStream [%s] %s:%d (%p) starting audioIO=%p"
- "VCAudioStream [%s] %s:%d Abnormal OWRD Verification: rtt=%f, owrd=%f, _abnormalOWRDCount=%d"
- "VCAudioStream [%s] %s:%d RTT=%.3f, TxBW=%ub/sec, PLR=%.2f%%, PLaMR=%.2f%%"
- "VCMediaQueue [%s] %s:%d IDR frame sent out. Reset lastIDRTimestamp for mediaQueueStreamId=%u, frameSizeInPackets=%u"
- "VCMediaQueue [%s] %s:%d Refresh frame counter=%d, time=%.4f"
- "VCMediaQueue [%s] %s:%d Set internalQueue timestampRateHz=%u for packetType=%d, mediaQueueStreamId=%u"
- "VCMediaQueue [%s] %s:%d VCMediaQueue IN/OUT RealTime stats are ENABLED"
- "VCMediaQueue [%s] %s:%d VCMediaQueue IN/OUT RealTime stats cannot be malloced"
- "VCMediaQueue [%s] %s:%d VCMediaQueue created successfully with 1 main queue, %d internal queues isRTXEnabled=%d schedulePolicy=%d"
- "VCMediaQueue [%s] %s:%d VCMediaQueue register mediaQueueStreamId=%u with internal queue index=%d"
- "VCMediaQueue [%s] %s:%d VCMediaQueue set ECNEnabled=%u"
- "VCMediaQueue [%s] %s:%d VCMediaQueue set isFrameBasedRedundancyEnabled=%u"
- "VCMediaQueue [%s] %s:%d VCMediaQueue set oneToOne=%u"
- "VCMediaQueue [%s] %s:%d VCMediaQueue set with MTU bytes = %u"
- "VCMediaQueue [%s] %s:%d VCMediaQueue set with peak bitrate = %u"
- "VCMediaQueue [%s] %s:%d VCMediaQueueSendProc thread ended"
- "VCMediaQueue [%s] %s:%d VCMediaQueueSendProc thread started"
- "VCMediaStream [%s] %s:%d (%p) Generated _streamToken=%u streamTokenUplink=%u streamTokenDownlink=%u"
- "VCRC [%s] %s:%d Bandwidth Estimation: Update bandwidth estimator qualification parameters with RAT=%d, mode=%d. [maxBW:%f, minWin:%f, maxOverRange:%d, minPacketCount:%d]"
- "VCRC [%s] %s:%d Create bandwidth estimator for estimator id: %d"
- "VCRC [%s] %s:%d start=%@"
- "VCRC [%s] %s:%d stop=%@"
- "VCSession [%s] %s:%d @=@ Health: VCSession-remote remoteParticipant=%@, videoStreamID=%@, audioStreamID=%@, videoRxBitrate=%u kbps, videoRxFrameRate=%3.1f, audioRxBitrate=%u kbps, videoRxResolution=%@, captionsRxBitrate=%u kbps"
- "VCSession [%s] %s:%d Using the following path - oneToOneModeEnabled=%d sessionMode=%ld serviceName=%@, oneToOneAuthenticationTagEnabled=%d, gftTLEEnabled=%d, p2pEncryptionEnabled=%d, detectInactiveAudioFramesAACELD=%d"
- "VCSession [%s] %s:%d remoteScreenAttributes=%@"
- "VCSoundDec [%s] %s:%d AudioConverterSetProperty succeeded to set kAudioConverterSampleRateConverterComplexity=%u"
- "VCSoundDec [%s] %s:%d AudioConverterSetProperty succeeded to set kAudioConverterSampleRateConverterQuality=%u"
- "VCSoundDec [%s] %s:%d AudioConverterSetProperty succeeded to set property kAudioCodecPrivatePropertyEVSCMRSettingInSDPOffer evsCMRMode=%d "
- "VCSoundDec [%s] %s:%d AudioConverterSetProperty succeeded to set property kAudioCodecPrivatePropertyEVSFormatHandling evsFormatHandling=%u"
- "VCSoundDec [%s] %s:%d AudioConverterSetProperty succeeded to set property kAudioCodecPrivatePropertyEVSSIDPeriod evsSIDPeriod=%u "
- "VCSoundDec [%s] %s:%d AudioConverterSetProperty succeeded to set property kAudioCodecPrivatePropertyEnableSAD dtxEnabled=%u"
- "VCSoundDec [%s] %s:%d AudioConverterSetProperty succeeded to set property kAudioCodecPrivatePropertySBRHeaderInterval sbrInterval=%u"
- "VCSoundDec [%s] %s:%d AudioConverterSetProperty succeeded to set property kAudioCodecPropertyConcealmentMode plcMode=%u"
- "VCSoundDec [%s] %s:%d AudioConverterSetProperty succeeded to set property kAudioCodecPropertyCurrentTargetBitRate bitrate=%u"
- "VCSoundDec [%s] %s:%d AudioConverterSetProperty succeeded to set property kAudioConverterPropertyUseMessengerForBundleData=%s useMessengerForBundleData=%u"
- "VCSoundDec [%s] %s:%d Configuring Ramstad SRC"
- "VCSoundDec [%s] %s:%d Leaving SoundDec_Create"
- "VCSoundDec [%s] %s:%d NEW AUDIO BITRATE (vbr)=%d fvbrcodec=%d enablePacketSizeLimit=%d"
- "VCSoundDec [%s] %s:%d SoundDec_Create(%08x --> %08x)"
- "VCSoundDec [%s] %s:%d SoundDec_EnableShortRED Requested shortREDEnabled=%d shortREDBytesPerFrame=%u shortREDBitrate=%u"
- "VCSoundDec [%s] %s:%d SoundDec_SetBitrate Requested bitrate: %d"
- "VCVideoCaptureServer [%s] %s:%d @:@ VCVideoCaptureServer-connect layers reconnectClientLayerFront=%d(1-front), slot=%u layerHostMode=%d"
- "VCVideoCaptureServer [%s] %s:%d @:@ VCVideoCaptureServer-setLocalVideoDestination previewSlot=%u, front=%d layerHostMode=%d"
- "VCVideoCaptureServer [%s] %s:%d Invalid camera, cameraSessionType=%d has nil cameraUID"
- "VCVideoCaptureServer [%s] %s:%d Unexpected capture frame duration expectedFrameDurationWithThreshold=%f and currentFrameDuration=%f"
- "VCVideoCaptureServer [%s] %s:%d _defaultLandscapeAspectRatio=%@"
- "VCVideoCaptureServer [%s] %s:%d _defaultPortraitAspectRatio=%@"
- "VCVideoCaptureServer [%s] %s:%d notifying clients of first preview frame, cameraSessionType=%d"
- "VCVideoJitterBuffer [%s] %s:%d Found new lowest minLag of %f for RTPTimestamp=%u"
- "VCVideoJitterBuffer [%s] %s:%d Video Jitter Buffer Created Successfully"
- "VCVideoStream [%s] %s:%d VideoStallTimeTotal=%.2f"
- "VideoPacketBuffer [%s] %s:%d VideoPacketBuffer[%p] Expected FRAMEHEADER_IMGDESC frameInfoType=%d, got %d"
```
