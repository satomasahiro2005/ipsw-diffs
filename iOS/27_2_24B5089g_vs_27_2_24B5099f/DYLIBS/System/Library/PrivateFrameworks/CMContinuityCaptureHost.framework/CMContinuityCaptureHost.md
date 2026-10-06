## CMContinuityCaptureHost

> `/System/Library/PrivateFrameworks/CMContinuityCaptureHost.framework/CMContinuityCaptureHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa58d8` | `0xa129c` | **`-0x463c`** |
| `__TEXT.__oslogstring` | `0xa2ac` | `0x89c7` | **`-0x18e5`** |
| `__TEXT.__cstring` | `0x98c5` | `0x8c15` | **`-0xcb0`** |
| `__TEXT.__gcc_except_tab` | `0x2edc` | `0x2d24` | **`-0x1b8`** |
| `__AUTH_CONST.__objc_const` | `0x9630` | `0x96e0` | **`+0xb0`** |
| `__AUTH.__data` | `0x2c8` | `0x360` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0x4360` | `0x42e0` | **`-0x80`** |
| `__TEXT.__constg_swiftt` | `0x764` | `0x7a8` | **`+0x44`** |
| `__DATA.__common` | `0xd8` | `0xa8` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x4dcc` | `0x4dfc` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x1138` | `0x1110` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2570` | `0x2598` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x15f0` | `0x1610` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2830` | `0x2810` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x3d0` | `0x3e0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1e78` | `0x1e80` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x980` | `0x978` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x947` | `0x94e` | **`+0x7`** |
| `__DATA.__objc_ivar` | `0x7a8` | `0x7ac` | **`+0x4`** |
| `__TEXT.__const` | `0x1430` | `0x1434` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x34` | `0x38` | **`+0x4`** |

### Other Changes

```diff

-764.40.5.0.0
+764.40.7.0.0

+  - /System/Library/Frameworks/DeveloperToolsSupport.framework/DeveloperToolsSupport

-  Functions: 2861
-  Symbols:   4116
-  CStrings:  1723
+  Functions: 2854
+  Symbols:   4121
+  CStrings:  1626
Symbols:
+ -[CMContinuityCaptureDiscoverySession _activateDiscoveryClients]
+ -[CMContinuityCaptureDiscoverySession _continuityCaptureEnabledOnMacChangedTo:]
+ -[CMContinuityCaptureDiscoverySession _deactivateDiscoveryClients]
+ -[CMContinuityCaptureDiscoverySession _registerContinuityCaptureEnabledOnMacObserver]
+ GCC_except_table48
+ _FigCaptureProprietaryDefaultsContinuityCaptureEnabledOnMacKey
+ _OBJC_CLASS_$_AVCaptureProprietaryDefaultsSingleton
+ _OBJC_IVAR_$_CMContinuityCaptureDiscoverySession._lastKnownEnabledOnMac
+ __DATA__TtC23CMContinuityCaptureHostP33_404820D67256F8A81E69EC16897E191419ResourceBundleClass
+ __METACLASS_DATA__TtC23CMContinuityCaptureHostP33_404820D67256F8A81E69EC16897E191419ResourceBundleClass
+ ___64-[CMContinuityCaptureDiscoverySession _activateDiscoveryClients]_block_invoke
+ ___76-[CMContinuityCaptureAudioInputProvider listener:shouldAcceptNewConnection:]_block_invoke_3
+ ___76-[CMContinuityCaptureAudioInputProvider listener:shouldAcceptNewConnection:]_block_invoke_4
+ ___79-[CMContinuityCaptureDiscoverySession _continuityCaptureEnabledOnMacChangedTo:]_block_invoke
+ ___85-[CMContinuityCaptureDiscoverySession _registerContinuityCaptureEnabledOnMacObserver]_block_invoke
+ ___87-[CMContinuityCaptureAudioInputProvider getRemotelyCollectedLatencyMetricsForUniqueID:]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e21_v24?0"NSString"816lw32l8
+ _symbolic _____ 23CMContinuityCaptureHost19ResourceBundleClass33_404820D67256F8A81E69EC16897E1914LLC
- GCC_except_table40
- _CFPreferencesGetAppIntegerValue
- _CVPixelBufferGetIOSurface
- _IOSurfaceGetID
- ___47-[CMContinuityCaptureDiscoverySession activate]_block_invoke_2
- ___67-[CMContinuityCaptureTimeSyncClock startEmittingHeartBeatSignposts]_block_invoke
- ___block_descriptor_40_e5_v8?0l
- _dispatch_activate
- _gCMContinuityCaptureAudioXPCHelperTrace
- _gCMContinuityCaptureMetricsReporterTrace
- _gCMContinuityCaptureTimeSyncClockTrace
- _gGMFigKTraceEnabled
- _kdebug_trace
CStrings:
+ "%@ %s rpCompanionclient re-setup failed"
+ "%@ %s, skipping because Continuity Camera is disabled on the host side"
+ "-[CMContinuityCaptureDiscoverySession _activateDiscoveryClients]"
+ "-[CMContinuityCaptureDiscoverySession activate]_block_invoke"
+ "v24@?0@\"NSString\"8@16"
- "+[CMContinuityCaptureAudioInputProvider sharedInstance]_block_invoke"
- "-[CMContinuityCaptureAudioInputProvider enqueueSampleBuffer:forAudioDeviceUID:]"
- "-[CMContinuityCaptureAudioInputProvider enqueueSampleBuffer:forAudioDeviceUID:]_block_invoke"
- "-[CMContinuityCaptureAudioInputProvider getRemotelyCollectedLatencyMetricsForUniqueID:]_block_invoke"
- "-[CMContinuityCaptureAudioInputProvider listener:shouldAcceptNewConnection:]_block_invoke"
- "-[CMContinuityCaptureAudioInputProvider listener:shouldAcceptNewConnection:]_block_invoke_2"
- "-[CMContinuityCaptureAudioInputProvider publishDeviceForClientDeviceUID:audioDeviceUID:name:deviceModel:voiceAmplificationModeSupported:]_block_invoke"
- "-[CMContinuityCaptureAudioInputProvider receiverConnectedWithReply:]"
- "-[CMContinuityCaptureAudioInputProvider receiverConnectedWithReply:]_block_invoke_2"
- "-[CMContinuityCaptureAudioInputProvider startCollectingLatencyMetricsRemotelyWithUniqueID:forAudioDeviceUID:]"
- "-[CMContinuityCaptureAudioInputProvider startCollectingLatencyMetricsRemotelyWithUniqueID:forAudioDeviceUID:]_block_invoke"
- "-[CMContinuityCaptureAudioInputProvider startFillingSilenceAudioDataIfApplicableForAudioDeviceUID:]"
- "-[CMContinuityCaptureAudioInputProvider startFillingSilenceAudioDataIfApplicableForAudioDeviceUID:]_block_invoke"
- "-[CMContinuityCaptureAudioInputProvider terminateDeviceForClientDeviceUID:]_block_invoke"
- "-[CMContinuityCaptureAudioInputProvider updateAvailableAudioDeviceUIDs:]"
- "-[CMContinuityCaptureAudioInputProvider updateNetworkClockWithSynchronizedNetworkTime:forSampleTime:networkClockIdentifier:transportTypeIsUSB:forAudioDeviceUID:]"
- "-[CMContinuityCaptureAudioInputProvider updateNetworkClockWithSynchronizedNetworkTime:forSampleTime:networkClockIdentifier:transportTypeIsUSB:forAudioDeviceUID:]_block_invoke"
- "-[CMContinuityCaptureAudioInputProvider updateUSBActive:forAudioDeviceUID:]"
- "-[CMContinuityCaptureAudioInputProvider updateUSBActive:forAudioDeviceUID:]_block_invoke"
- "-[CMContinuityCaptureAudioInputProvider useCachedNetworkClockIfPossibleForAudioDeviceUID:]"
- "-[CMContinuityCaptureAudioInputProvider useCachedNetworkClockIfPossibleForAudioDeviceUID:]_block_invoke"
- "-[CMContinuityCaptureAudioXPCHelper _updateRemoteReceiver:]"
- "-[CMContinuityCaptureAudioXPCHelper listener:shouldAcceptNewConnection:]"
- "-[CMContinuityCaptureAudioXPCHelper providerConnectedWithListenerEndpoint:]"
- "-[CMContinuityCaptureAudioXPCHelper receiverConnected]"
- "-[CMContinuityCaptureFrameLatencyMetrics addLatencyNumberInMilliSeconds:]"
- "-[CMContinuityCaptureLocalFrameLatencyMetrics _finishCollectingMetrics]"
- "-[CMContinuityCaptureMetricsReporter _addLatencyMetrics:]"
- "-[CMContinuityCaptureMetricsReporter _clearAndSubmitAllMetrics]"
- "-[CMContinuityCaptureMetricsReporter _clearAndSubmitAllMetrics]_block_invoke"
- "-[CMContinuityCaptureMetricsReporter _submitMetricsToRTCReporting:]"
- "-[CMContinuityCaptureTimeSyncClock initWithClock:]"
- "-[CMContinuityCaptureTimeSyncClock startEmittingHeartBeatSignposts]"
- "-[CMContinuityCaptureTimeSyncClock startEmittingHeartBeatSignposts]_block_invoke"
- "-[CVPixelBufferCoder _createPixelBufferForImage:fillWidth:fillHeight:]"
- "-[CVPixelBufferCoder encodeWithCoder:]"
- "-[CVPixelBufferCoder initWithCoder:]"
- "-[NSCoder(CVPixelBuffer) decodeCVPixelBufferForKey:expectSourceMedia:]"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: %@ ContinuityCaptureMic feature flag not enabled"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Calling on receiver proxy %@ enqueue sbuf with pts %.3f"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Calling on receiver proxy %@ finish collecting latency metrics with uniqueID %lld"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Calling on receiver proxy %@ publish device for sidecar device UID %@ audio device UID %@ name %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Calling on receiver proxy %@ start collecting latency metrics with uniqueID %lld for UID %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Calling on receiver proxy %@ startFillingSilenceAudioDataIfApplicable for UID %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Calling on receiver proxy %@ terminate device for UID %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Calling on receiver proxy %@ to publish stored device UIDs %@, firstDeviceDiscoveryFinished %d "
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Calling on receiver proxy %@ update network clock with synchronized network time %llu sampleTime %llu clock identifier %llu transportTypeIsUSB %d for UID %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Calling on receiver proxy %@ updateUSBActive %d for UID %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Calling on receiver proxy %@ use cached network clock if possible for UID %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Received audio buffer from AVC without attached network timestamp. Dropping buffer."
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Receiver connected %@ delegate %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Receiver proxy %@ told me to start streaming for UID %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Receiver proxy %@ told me to stop streaming for UID %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Skip collecting latency metrics with nil UID"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Skip enqueueing sbuf %p UID %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Skip pause enqueuing audioData with nil UID"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Skip update USBActive with nil UID"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Skip updating synchronized network time with nil UID"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Skip updating using cached network clock with nil UID"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Trying to terminate audio device for sidecar device UID %@ but couldn't find audio device UID"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Update available audio device UIDs %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: Updated connection to receiver %@ -> %@ audioInputReceiver %@"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: connection interrupted %@, client should connect back again"
- "<<<< CMContinuityCaptureAudioInputProvider >>>> %s: connection invalidated %@"
- "<<<< CMContinuityCaptureAudioRouteManager >>>> %s: Failed to find audioDevice with UID %@ availableDevices %@"
- "<<<< CMContinuityCaptureAudioXPCHelper >>>> %s: Got new connection for unknown listener %@ connection %@"
- "<<<< CMContinuityCaptureAudioXPCHelper >>>> %s: Got new connection from audio provider %@ (expecting from ContinuityCaptureAgent)"
- "<<<< CMContinuityCaptureAudioXPCHelper >>>> %s: Got new connection from audio receiver %@ (expecting from coreaudiod)"
- "<<<< CMContinuityCaptureAudioXPCHelper >>>> %s: Provider connected with new listener endpoint %@ -> %@"
- "<<<< CMContinuityCaptureAudioXPCHelper >>>> %s: Provider listener endpoint is already available, sending it to remote receiver now. This might be a result from process crashing"
- "<<<< CMContinuityCaptureAudioXPCHelper >>>> %s: Remote receiver connected %@"
- "<<<< CMContinuityCaptureAudioXPCHelper >>>> %s: Update remote receiver %@ -> %@"
- "<<<< CMContinuityCaptureMetricsReporter >>>> %s: %@ RTCReporting %@ started successfully with sessionInfo %@"
- "<<<< CMContinuityCaptureMetricsReporter >>>> %s: %@ failed to submit RTCReporting payload for %@, error %@"
- "<<<< CMContinuityCaptureMetricsReporter >>>> %s: %@ finishing collecting metrics, collecting remotely:%d"
- "<<<< CMContinuityCaptureMetricsReporter >>>> %s: %@ sessionID %d submitting metrics %@"
- "<<<< CMContinuityCaptureMetricsReporter >>>> %s: %@ submit payload succeeded:%d error %@ %@"
- "<<<< CMContinuityCaptureMetricsReporter >>>> %s: %@:%llu trying to add an invalid latency number %d -- dropping"
- "<<<< CMContinuityCaptureMetricsReporter >>>> %s: Failed waiting for RTCReportingSession startConfiguration to complete after %f seconds"
- "<<<< CMContinuityCaptureMetricsReporter >>>> %s: Metric reporter %@ adding %@ with mediaID %d uniqueID:%llu. Current metrics count %lu"
- "<<<< CMContinuityCaptureMetricsReporter >>>> %s: RTCReporting failed to create with sessionInfo %@"
- "<<<< CMContinuityCaptureMetricsReporter >>>> %s: RTCReporting session startConfiguration completes, signalling startGroup %@"
- "<<<< CMContinuityCaptureMetricsReporter >>>> %s: RTCReporting startConfiguration completion handler called with nil backends, metrics won't be sent out"
- "<<<< CMContinuityCaptureTimeSyncClock >>>> %s: %@ %lld: (%lld) %lld -> %lld"
- "<<<< CMContinuityCaptureTimeSyncClock >>>> %s: %@ starting heart beat signposts with interval %lu seconds"
- "<<<< CMContinuityCaptureTimeSyncClock >>>> %s: Failed to create PTP clock with identifier %llu, available identifiers %@"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Could not create pixel buffer: %d"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Could not read source media %@, falling back to pixel buffer copy"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Could not serialize pixel buffer, error %d"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Error creating pixel buffer %zu x %zu: %d"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Expected source media but pixel buffer data was found instead (not fatal)"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Failed to create pixel buffer %zu x %zu"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: Fallback not using atom data, outdated peer connection for pixel buffer"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: No pixel data"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: bad source image offset"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: image planes don't match, encoded %d allocated %d"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: source image offset overrun"
- "<<<< NSCoding+CVPixelBufferRef >>>> %s: source image stride overrun"
- "cmcontinuitycaptureaudioxpchelper_trace"
- "cmcontinuitycapturemetricsreporter_trace"
- "cmcontinuitycapturetimesyncclock_trace"
- "continuitycapture_timesync_heartbeat_interval"
```
