## APTransport

> `/System/Library/PrivateFrameworks/APTransport.framework/APTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb3810` | `0xb3f88` | **`+0x778`** |
| `__AUTH_CONST.__cfstring` | `0x63a0` | `0x6520` | **`+0x180`** |
| `__TEXT.__cstring` | `0x2f773` | `0x2f86d` | **`+0xfa`** |
| `__AUTH_CONST.__const` | `0x2d38` | `0x2db8` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x2c60` | `0x2cc8` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x3cc0` | `0x3d10` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x438` | `0x3e8` | **`-0x50`** |
| `__DATA_DIRTY.__bss` | `0x278` | `0x2b8` | **`+0x40`** |

### Other Changes

```diff

-980.58.1.11.1
+980.63.2.0.0

-  Functions: 5278
-  Symbols:   4347
-  CStrings:  4488
+  Functions: 5314
+  Symbols:   4363
+  CStrings:  4502
Symbols:
+ _APTransportGetCMBaseObject
+ _APTransportGetClassID
+ _APTransportGetTypeID
+ _APTransportServiceGetCMBaseObject
+ _APTransportServiceGetClassID
+ _APTransportServiceGetTypeID
+ _APTransportSessionGetCMBaseObject
+ _APTransportSessionGetClassID
+ _APTransportSessionGetTypeID
+ _APTransportStreamGetCMBaseObject
+ _APTransportStreamGetClassID
+ _APTransportStreamGetTypeID
+ _APTransportStreamSendBatchSlow
+ _kAPTransportService_APTransportServiceClass
+ _kAPTransportSessionNotification_Disconnected
+ _kAPTransportSessionNotification_KeepAliveResponseReceived
+ _kAPTransportSessionProperty_KeepAliveInterval
+ _kAPTransportSessionProperty_KeepAliveType
+ _kAPTransportSessionProperty_UUID
+ _kAPTransportSessionStreamOption_DelegatedID
+ _kAPTransportSessionStreamOption_GroupID
+ _kAPTransportSessionStreamOption_StreamPriority
+ _kAPTransportSessionStreamOption_Type
+ _kAPTransportSession_APTransportSessionClass
+ _kAPTransportStreamAggregate_APTransportStreamClass
+ _kAPTransportStreamProperty_ID
+ _kAPTransportStreamUnbuffered_APTransportStreamClass
+ _kAPTransportStream_APTransportStreamClass
+ _kAPTransport_APTransportClass
+ _service_copyFormattingDesc
+ _service_getClassID
+ _service_getClassID.sClassDesc
+ _session_copyFormattingDesc
+ _session_getClassID
+ _session_getClassID.sClassDesc
+ _stream_copyFormattingDesc
+ _stream_getClassID
+ _stream_getClassID.sClassDesc
+ _transport_copyFormattingDesc
+ _transport_getClassID
+ _transport_getClassID.sClassDesc
- GCC_except_table26
- _FigTransportGetCMBaseObject
- _FigTransportGetClassID
- _FigTransportServiceGetClassID
- _FigTransportSessionGetClassID
- _FigTransportStreamGetCMBaseObject
- _FigTransportStreamGetClassID
- _FigTransportStreamGetTypeID
- _kAPTransportService_FigTransportServiceClass
- _kAPTransportSession_FigTransportSessionClass
- _kAPTransportStreamAggregate_FigTransportStreamClass
- _kAPTransportStreamUnbuffered_FigTransportStreamClass
- _kAPTransportStream_FigTransportStreamClass
- _kAPTransport_FigTransportClass
- _kFigTransportSessionNotification_Disconnected
- _kFigTransportSessionNotification_KeepAliveResponseReceived
- _kFigTransportSessionProperty_KeepAliveInterval
- _kFigTransportSessionProperty_KeepAliveType
- _kFigTransportSessionProperty_UUID
- _kFigTransportSessionStreamOption_DelegatedID
- _kFigTransportSessionStreamOption_GroupID
- _kFigTransportSessionStreamOption_StreamPriority
- _kFigTransportSessionStreamOption_Type
- _kFigTransportStreamProperty_ID
- _objc_retain_x26
CStrings:
+ "980.63.2"
+ "APTransportStreamSendBatchSlow"
+ "Boolean session_canResumeWithRequestedInterface(APTransportSessionRef)"
+ "CFArrayRef APTransportStreamCopyConvertedLinkLocalIPv6Addresses(APTransportStreamRef, CFArrayRef)"
+ "CFStringRef stream_createConnectionAddressFromEventData(APTransportStreamRef, CFTypeRef)"
+ "KeepAliveType"
+ "OSStatus APTKeepAliveControllerLowPowerCreate(CFAllocatorRef, CFDictionaryRef, APTransportStreamRef, APTransportKeepAliveControllerRef *)"
+ "OSStatus APTransportKeepAliveControllerStandardCreate(CFAllocatorRef, CFDictionaryRef, APTransportStreamRef, APTransportKeepAliveControllerRef *)"
+ "OSStatus APTransportServiceCreate(CFAllocatorRef, CFStringRef, CFDictionaryRef, dispatch_queue_t, APTransportServiceEventCallback, void *, APTransportServiceRef *)"
+ "OSStatus APTransportSessionCreate(CFAllocatorRef, APTransportSessionType, CFStringRef, APTransportDeviceRef, CFDictionaryRef, APTransportSessionRef *)"
+ "OSStatus APTransportStreamAggregateAddSubStream(APTransportStreamRef, APTransportStreamRef, CFDictionaryRef)"
+ "OSStatus APTransportStreamAggregateCreate(CFAllocatorRef, CFDictionaryRef, APTransportStreamRef *)"
+ "OSStatus APTransportStreamAggregateRemoveSubStream(APTransportStreamRef, APTransportStreamRef, CFDictionaryRef)"
+ "OSStatus APTransportStreamCreate(CFAllocatorRef, CFTypeRef, APTransportStreamID, CFStringRef, FigThreadPriority, APTransportConnectionRef, uint64_t, CFDictionaryRef, APTransportStreamRef *)"
+ "OSStatus APTransportStreamSendBackingProviderCreateWithStreamID(CFAllocatorRef, APTransportStreamID, CFDictionaryRef, APTransportStreamSendBackingProviderRef *)"
+ "OSStatus APTransportStreamUnbufferedCreate(CFAllocatorRef, CFTypeRef, APTransportStreamID, CFStringRef, APTransportConnectionRef, CFDictionaryRef, APTransportStreamRef *)"
+ "OSStatus lowPowerKeepAliveController_sendKeepAlive(APTransportKeepAliveControllerRef, APTransportStreamRef)"
+ "OSStatus service_registerSession(APTransportServiceRef, APTransportSessionRef)"
+ "OSStatus session_activateNANDS(APTransportSessionRef, APSNANServiceType, APTNANDataSessionRef *)"
+ "OSStatus session_createConnectionForStream(APTransportSessionRef, APTransportStreamID, CFStringRef, FigThreadPriority, CFDictionaryRef, APTransportConnectionRef *)"
+ "OSStatus session_createStreamWithConnections(APTransportSessionRef, APTransportConnectionRef, APTransportConnectionRef, APTransportStreamID, CFStringRef, FigThreadPriority, CFDictionaryRef, APTransportStreamRef *)"
+ "OSStatus session_isConnectedOnWiFi(APTransportSessionRef, APTSessionWiFiCheckOption, Boolean *)"
+ "OSStatus session_setupEventRecorder(APTransportSessionRef, CFDictionaryRef, CFStringRef)"
+ "OSStatus streamAggregate_Resume(APTransportStreamRef)"
+ "OSStatus streamAggregate_SendBatch(APTransportStreamRef, OSType, CFArrayRef)"
+ "OSStatus streamAggregate_SendMessage(APTransportStreamRef, OSType, CMBlockBufferRef)"
+ "OSStatus streamAggregate_copyPropertyInternal(APTransportStreamRef, CFStringRef, CFAllocatorRef, void *)"
+ "OSStatus streamAggregate_createConnectionForInitialStream(APTransportStreamRef, APTransportStreamRef)"
+ "OSStatus streamAggregate_invalidateInternal(APTransportStreamRef)"
+ "OSStatus stream_ConfigureEncryption(APTransportStreamRef, CFTypeRef, CFStringRef)"
+ "OSStatus stream_SendMessageCreatingReply(APTransportStreamRef, OSType, CMBlockBufferRef, CMBlockBufferRef *)"
+ "OSStatus stream_SendMessageCreatingReply(APTransportStreamRef, OSType, CMBlockBufferRef, CMBlockBufferRef *)_block_invoke"
+ "OSStatus stream_SetMessageCallbacks(APTransportStreamRef, APTransportStreamMessageCallback, APTransportStreamMessageCreatingReplyCallback, void *)_block_invoke"
+ "OSStatus stream_createConnectionState(APTransportConnectionRef, APTransportConnectionEventCallback, APTransportStreamRef, APTransportStreamDirection, APTransportStreamConnectionStateRef *)"
+ "OSStatus stream_enableReverseControlInternal(APTransportStreamRef)"
+ "OSStatus stream_eventReceived(APTransportStreamRef, APTransportConnectionEvent, CFTypeRef)"
+ "OSStatus stream_eventReceived(APTransportStreamRef, APTransportConnectionEvent, CFTypeRef, APTransportStreamConnectionStateRef)"
+ "OSStatus stream_packageReceived(APTransportStreamRef, APTransportPackageRef)"
+ "OSStatus stream_resumeInternal(APTransportStreamRef)"
+ "OSStatus stream_waitUntilConnectionSetup(APTransportStreamRef, APTransportStreamConnectionType)_block_invoke"
+ "OSStatus stream_waitUntilConnectionSetup(APTransportStreamRef, APTransportStreamConnectionType)_block_invoke_2"
+ "OSStatus transport_create(CFAllocatorRef, APTransportRef *)"
+ "StreamGroupID"
+ "StreamPriority"
+ "StreamType"
+ "TransportControlStream is not a APTransportStream: [%{ptr}]\n"
+ "TransportSession_Disconnected"
+ "TransportSession_KeepAliveResponseReceived"
+ "TransportStreamProperty_ID"
+ "UUID"
+ "[%{ptr}] Warm peer [%{ptr}] and reset %d secs idle timer... \n"
+ "[APTransport %p]"
+ "[APTransportService %p]"
+ "[APTransportSession %p]"
+ "[APTransportStream %p]"
+ "void session_handleConnectionDroppedInternal(APTransportSessionRef, APTransportStreamRef, OSStatus)"
+ "void session_handleUSBInterfaceChangedEvent(APTransportSessionRef, CFDictionaryRef)"
+ "void session_handleWiFiAvailableEvent(APTransportSessionRef)"
+ "void session_handleWiFiPowerChangedEvent(APTransportSessionRef)"
+ "void stream_recordSuccessfulConnectionStartTime(APTransportStreamRef, CFTypeRef)"
+ "void stream_sendReplyMessage(APTransportStreamRef, uint64_t, uint32_t, OSStatus, CMBlockBufferRef)"
- "980.58.1.11.1"
- "Boolean session_canResumeWithRequestedInterface(FigTransportSessionRef)"
- "CFArrayRef APTransportStreamCopyConvertedLinkLocalIPv6Addresses(FigTransportStreamRef, CFArrayRef)"
- "CFStringRef stream_createConnectionAddressFromEventData(FigTransportStreamRef, CFTypeRef)"
- "OSStatus APTKeepAliveControllerLowPowerCreate(CFAllocatorRef, CFDictionaryRef, FigTransportStreamRef, APTransportKeepAliveControllerRef *)"
- "OSStatus APTransportKeepAliveControllerStandardCreate(CFAllocatorRef, CFDictionaryRef, FigTransportStreamRef, APTransportKeepAliveControllerRef *)"
- "OSStatus APTransportServiceCreate(CFAllocatorRef, CFStringRef, CFDictionaryRef, dispatch_queue_t, FigTransportServiceEventCallback, void *, FigTransportServiceRef *)"
- "OSStatus APTransportSessionCreate(CFAllocatorRef, APTransportSessionType, CFStringRef, APTransportDeviceRef, CFDictionaryRef, FigTransportSessionRef *)"
- "OSStatus APTransportStreamAggregateAddSubStream(FigTransportStreamRef, FigTransportStreamRef, CFDictionaryRef)"
- "OSStatus APTransportStreamAggregateCreate(CFAllocatorRef, CFDictionaryRef, FigTransportStreamRef *)"
- "OSStatus APTransportStreamAggregateRemoveSubStream(FigTransportStreamRef, FigTransportStreamRef, CFDictionaryRef)"
- "OSStatus APTransportStreamCreate(CFAllocatorRef, FigTransportSessionRef, FigTransportStreamID, CFStringRef, FigThreadPriority, APTransportConnectionRef, uint64_t, CFDictionaryRef, FigTransportStreamRef *)"
- "OSStatus APTransportStreamSendBackingProviderCreateWithStreamID(CFAllocatorRef, FigTransportStreamID, CFDictionaryRef, APTransportStreamSendBackingProviderRef *)"
- "OSStatus APTransportStreamUnbufferedCreate(CFAllocatorRef, FigTransportSessionRef, FigTransportStreamID, CFStringRef, APTransportConnectionRef, CFDictionaryRef, FigTransportStreamRef *)"
- "OSStatus lowPowerKeepAliveController_sendKeepAlive(APTransportKeepAliveControllerRef, FigTransportStreamRef)"
- "OSStatus service_registerSession(FigTransportServiceRef, FigTransportSessionRef)"
- "OSStatus session_activateNANDS(FigTransportSessionRef, APSNANServiceType, APTNANDataSessionRef *)"
- "OSStatus session_createConnectionForStream(FigTransportSessionRef, FigTransportStreamID, CFStringRef, FigThreadPriority, CFDictionaryRef, APTransportConnectionRef *)"
- "OSStatus session_createStreamWithConnections(FigTransportSessionRef, APTransportConnectionRef, APTransportConnectionRef, FigTransportStreamID, CFStringRef, FigThreadPriority, CFDictionaryRef, FigTransportStreamRef *)"
- "OSStatus session_isConnectedOnWiFi(FigTransportSessionRef, APTSessionWiFiCheckOption, Boolean *)"
- "OSStatus session_setupEventRecorder(FigTransportSessionRef, CFDictionaryRef, CFStringRef)"
- "OSStatus streamAggregate_Resume(FigTransportStreamRef)"
- "OSStatus streamAggregate_SendBatch(FigTransportStreamRef, OSType, CFArrayRef)"
- "OSStatus streamAggregate_SendMessage(FigTransportStreamRef, OSType, CMBlockBufferRef)"
- "OSStatus streamAggregate_copyPropertyInternal(FigTransportStreamRef, CFStringRef, CFAllocatorRef, void *)"
- "OSStatus streamAggregate_createConnectionForInitialStream(FigTransportStreamRef, FigTransportStreamRef)"
- "OSStatus streamAggregate_invalidateInternal(FigTransportStreamRef)"
- "OSStatus stream_ConfigureEncryption(FigTransportStreamRef, CFTypeRef, CFStringRef)"
- "OSStatus stream_SendMessageCreatingReply(FigTransportStreamRef, OSType, CMBlockBufferRef, CMBlockBufferRef *)"
- "OSStatus stream_SendMessageCreatingReply(FigTransportStreamRef, OSType, CMBlockBufferRef, CMBlockBufferRef *)_block_invoke"
- "OSStatus stream_SetMessageCallbacks(FigTransportStreamRef, FigTransportStreamMessageCallback, FigTransportStreamMessageCreatingReplyCallback, void *)_block_invoke"
- "OSStatus stream_createConnectionState(APTransportConnectionRef, APTransportConnectionEventCallback, FigTransportStreamRef, APTransportStreamDirection, APTransportStreamConnectionStateRef *)"
- "OSStatus stream_enableReverseControlInternal(FigTransportStreamRef)"
- "OSStatus stream_eventReceived(FigTransportStreamRef, APTransportConnectionEvent, CFTypeRef)"
- "OSStatus stream_eventReceived(FigTransportStreamRef, APTransportConnectionEvent, CFTypeRef, APTransportStreamConnectionStateRef)"
- "OSStatus stream_packageReceived(FigTransportStreamRef, APTransportPackageRef)"
- "OSStatus stream_resumeInternal(FigTransportStreamRef)"
- "OSStatus stream_waitUntilConnectionSetup(FigTransportStreamRef, APTransportStreamConnectionType)_block_invoke"
- "OSStatus stream_waitUntilConnectionSetup(FigTransportStreamRef, APTransportStreamConnectionType)_block_invoke_2"
- "OSStatus transport_create(CFAllocatorRef, FigTransportRef *)"
- "TransportControlStream is not a FigTransportStream: [%{ptr}]\n"
- "void session_handleConnectionDroppedInternal(FigTransportSessionRef, FigTransportStreamRef, OSStatus)"
- "void session_handleUSBInterfaceChangedEvent(FigTransportSessionRef, CFDictionaryRef)"
- "void session_handleWiFiAvailableEvent(FigTransportSessionRef)"
- "void session_handleWiFiPowerChangedEvent(FigTransportSessionRef)"
- "void stream_recordSuccessfulConnectionStartTime(FigTransportStreamRef, CFTypeRef)"
- "void stream_sendReplyMessage(FigTransportStreamRef, uint64_t, uint32_t, OSStatus, CMBlockBufferRef)"
```
