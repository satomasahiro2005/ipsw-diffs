## CMContinuityCaptureRemote

> `/System/Library/PrivateFrameworks/CMContinuityCaptureRemote.framework/CMContinuityCaptureRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xabb50` | `0xaf9c8` | **`+0x3e78`** |
| `__TEXT.__eh_frame` | `0x2148` | `0x24c0` | **`+0x378`** |
| `__AUTH_CONST.__const` | `0x13e0` | `0x15b8` | **`+0x1d8`** |
| `__TEXT.__const` | `0x12b0` | `0x13e0` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0x29a8` | `0x2ab8` | **`+0x110`** |
| `__TEXT.__swift5_capture` | `0x5f0` | `0x69c` | **`+0xac`** |
| `__TEXT.__swift5_typeref` | `0x883` | `0x905` | **`+0x82`** |
| `__TEXT.__gcc_except_tab` | `0x3370` | `0x33ec` | **`+0x7c`** |
| `__DATA.__bss` | `0xc30` | `0xca0` | **`+0x70`** |
| `__DATA.__data` | `0x1550` | `0x15c0` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x730` | `0x798` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0xac18` | `0xac70` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x38c` | `0x3dc` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1018` | `0x1058` | **`+0x40`** |
| `__TEXT.__cstring` | `0xa9f7` | `0xa9c5` | **`-0x32`** |
| `__DATA_CONST.__const` | `0x1f00` | `0x1f28` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xb70` | `0xb98` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x432` | `0x456` | **`+0x24`** |
| `__TEXT.__swift_as_entry` | `0x110` | `0x12c` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x134` | `0x14c` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x2ec0` | `0x2ed0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x28` | `0x34` | **`+0xc`** |
| `__TEXT.__oslogstring` | `0xb8f1` | `0xb8fc` | **`+0xb`** |
| `__AUTH.__objc_data` | `0x1d38` | `0x1d40` | **`+0x8`** |
| `__DATA.__common` | `0xf8` | `0xf0` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x1bc` | `0x1c0` | **`+0x4`** |

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3

-  Functions: 3127
-  Symbols:   4583
-  CStrings:  1868
+  Functions: 3181
+  Symbols:   4609
+  CStrings:  1877
Symbols:
+ -[CMContinuityCaptureNWServer _handleSynchronizedClockIdentifier:fromSession:]
+ -[CMContinuityCaptureNWServer notifyUserDisconnect]
+ -[CMContinuityCaptureRapportServer notifyUserDisconnect]
+ -[CMContinuityCaptureRemoteSessionManager notifyUserDisconnectOnActiveSession]
+ -[CMContinuityCaptureSidecarServer notifyUserDisconnect]
+ GCC_except_table40
+ __IVARS__TtC25CMContinuityCaptureRemote23CancellableContinuation
+ ___60-[CMContinuityCaptureNWServer initWithNetworkSession:queue:]_block_invoke
+ ___78-[CMContinuityCaptureNWServer _handleSynchronizedClockIdentifier:fromSession:]_block_invoke
+ ___block_descriptor_48_e8_32s40w_e8_v16?0Q8lw40l8s32l8
+ ___swift_closure_destructor.125Tm
+ ___swift_closure_destructor.13Tm
+ ___swift_closure_destructor.42Tm
+ ___swift_closure_destructor.79Tm
+ ___swift_closure_destructor.82Tm
+ ___swift_instantiateGenericMetadata
+ ___swift_memcpy4_4
+ ___unnamed_7
+ _swift_allocateGenericClassMetadata
+ _swift_deallocClassInstance
+ _swift_getGenericMetadata
+ _swift_initClassMetadata2
+ _swift_release_x1
+ _swift_retain_x1
+ _swift_retain_x10
+ _swift_retain_x22
+ _swift_retain_x27
+ _swift_retain_x8
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
+ _symbolic SDy__________y_____GG So27ContinuityCaptureEntityTypeV 012CMContinuityB6Remote23CancellableContinuationC AC0eb5MediaA6StreamC
+ _symbolic Say_____G 7Network10NWListenerC7ServiceV5ScopeV
+ _symbolic ScSy_____G s6UInt64V
+ _symbolic _____ 25CMContinuityCaptureRemote23CancellableContinuationC
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ s6UInt32V
+ _symbolic _____Ieghy_ s6UInt64V
+ _symbolic _____IeyBhy_ s6UInt64V
+ _symbolic _____SgXw 25CMContinuityCaptureRemote0aB23TransportDeviceNWStreamC
+ _symbolic _____SgXwz_Xx 25CMContinuityCaptureRemote0aB23TransportDeviceNWStreamC
+ _symbolic _____ySbG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySb_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____yScCyx______pGSgG 2os21OSAllocatedUnfairLockV s5ErrorP
+ _symbolic _____y_____G 25CMContinuityCaptureRemote23CancellableContinuationC AA0aB21MediaContinuityStreamC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 7Network10NWListenerC7ServiceV5ScopeV
+ _symbolic _____y______G ScS12ContinuationV s6UInt64V
+ _symbolic _____y______G ScS8IteratorV s6UInt64V
+ _symbolic _____y_______G ScS12ContinuationV11YieldResultO s6UInt64V
+ _symbolic _____y_______G ScS12ContinuationV15BufferingPolicyO s6UInt64V
+ _symbolic _____y__________y_____GG s18_DictionaryStorageC So27ContinuityCaptureEntityTypeV 012CMContinuityD6Remote23CancellableContinuationC AE0gd5MediaC6StreamC
+ _symbolic _____yytG 25CMContinuityCaptureRemote23CancellableContinuationC
+ _symbolic _____yytGSg 25CMContinuityCaptureRemote23CancellableContinuationC
+ _symbolic y_____YbcSg s6UInt64V
+ _type_layout_string So16os_unfair_lock_sV
- -[CMContinuityCaptureNWServer didReceiveSessionInfo:]
- -[CMContinuityCaptureNWServer session:didReceiveSynchronizedClockIdentifier:]
- GCC_except_table31
- GCC_except_table54
- GCC_except_table58
- _OBJC_CLASS_$_OS_dispatch_queue
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CMContinuityCaptureTransportMessaging
- ___53-[CMContinuityCaptureNWServer didReceiveSessionInfo:]_block_invoke
- ___61-[CMContinuityCaptureRemoteServer _disconnectSession:reason:]_block_invoke_2
- ___77-[CMContinuityCaptureNWServer session:didReceiveSynchronizedClockIdentifier:]_block_invoke
- ___swift_closure_destructor.116Tm
- ___swift_closure_destructor.47Tm
- ___swift_closure_destructor.84Tm
- ___swift_closure_destructor.87Tm
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_retain_n
- _swift_retain_x26
- _symbolic SDy_____ScCy___________pGG So27ContinuityCaptureEntityTypeV 012CMContinuityB6Remote0eb5MediaA6StreamC s5ErrorP
- _symbolic Say_____G So17OS_dispatch_queueC8DispatchE10AttributesV
- _symbolic ScCy___________pG 25CMContinuityCaptureRemote0aB21MediaContinuityStreamC s5ErrorP
- _symbolic ScCy___________pGSg 25CMContinuityCaptureRemote0aB21MediaContinuityStreamC s5ErrorP
- _symbolic So17OS_dispatch_queueC
- _symbolic _____Sg 25CMContinuityCaptureRemote0aB23TransportDeviceNWStreamC
- _symbolic _____Sg 25CMContinuityCaptureRemote0aB8NWDeviceC
- _symbolic _____Sg 8Dispatch0A8WorkItemC
- _symbolic ______ScCy___________pGt So27ContinuityCaptureEntityTypeV 012CMContinuityB6Remote0eb5MediaA6StreamC s5ErrorP
- _symbolic _____y_____ScCy___________pGG s18_DictionaryStorageC So27ContinuityCaptureEntityTypeV 012CMContinuityD6Remote0gd5MediaC6StreamC s5ErrorP
CStrings:
+ " Activating MediaContinuity audio stream"
+ " Activating MediaContinuity video stream"
+ " Activating MediaContinuityServer"
+ " Activating MediaContinuitySession"
+ " Adding stream to session, current count: "
+ " Buffering incoming video stream for entity "
+ " Calling start() on RemoteActor"
+ " Cannot send sample buffer on inactive stream"
+ " Cannot send sample buffer on receiving stream"
+ " Clearing actors"
+ " Connection established, actors ready"
+ " Could not find default stream with hostActor to send endpoint"
+ " Created MediaContinuityStream "
+ " Created VideoStream: "
+ " Creating HostActor with handler and session"
+ " Creating MediaContinuityServer"
+ " Creating MediaContinuitySession"
+ " Creating sending video stream for entity "
+ " Creating stream"
+ " Decoded endpoint for device: "
+ " Default stream has no hostActor"
+ " Deinitializing MediaContinuity "
+ " Disconnecting connection"
+ " Endpoint sent successfully"
+ " Exporting HostActor"
+ " Failed to get synchronizedClockIdentifier: "
+ " Failed to send sample buffer: "
+ " Failed to setup MediaContinuityServer: "
+ " Failed to setup MediaContinuitySession: "
+ " Failing pending createReceivingVideoStream continuation for entity "
+ " Got synchronizedClockIdentifier: "
+ " HostActor exported with ID: "
+ " Ignoring endpoint, session already cancelled"
+ " Incoming video stream received for entity "
+ " Invalid stream type for sending"
+ " LocalInterface received, session assigned: "
+ " MediaContinuity "
+ " MediaContinuity audio stream activated"
+ " MediaContinuity audio stream event error: "
+ " MediaContinuity video stream activated"
+ " MediaContinuity video stream event error: "
+ " MediaContinuity video stream invalidated by ["
+ " MediaContinuityServer activated, got endpoint"
+ " MediaContinuitySession activated"
+ " MediaContinuitySession activation wait completed"
+ " MediaContinuitySession event stream error: "
+ " MediaContinuitySession interrupted: "
+ " MediaContinuitySession not available"
+ " MediaContinuitySession stream error: "
+ " NetworkSession created (host-side) for device: "
+ " NetworkSession created (remote-side) for device: "
+ " NetworkSession deallocating"
+ " Processing MediaContinuityEndpoint ("
+ " Received audio sample buffer"
+ " Received changed video attributes "
+ " Received first video sample buffer"
+ " Received incoming MediaContinuitySession"
+ " Received incoming audio stream, activating"
+ " Received incoming control stream: "
+ " Received incoming video stream: "
+ " Received unexpected second endpoint while MediaContinuitySession already exists"
+ " Received video sample buffer"
+ " RemoteActor imported with ID: "
+ " RemoteActor.start() failed: "
+ " RemoteActor.start() returned: "
+ " RemoteInterface received, importing RemoteActor"
+ " Resuming continuation for entity "
+ " Returning buffered incoming video stream for entity "
+ " Send message timed out after "
+ " Send sample buffer timed out after 1 second"
+ " Sending endpoint ("
+ " Server acknowledged start, signaling continuation"
+ " Server start() returned false"
+ " Session cancelled"
+ " Session cancelled, notifying delegate"
+ " Session connecting to device: "
+ " Session ended with error: "
+ " Stopping MediaContinuity "
+ " Stream added to session, new count: "
+ " Stream received start() [sessionID:"
+ " Stream startHandler not set yet, buffering sessionID"
+ " Unexpected activation result"
+ " Unexpected endpoint on server side"
+ " Waiting for MediaContinuitySession activation ("
+ " Waiting for MediaContinuitySession activation failed: "
+ " Waiting for connection ready ("
+ " Waiting for connection ready failed: "
+ " Waiting for incoming video stream for entity "
+ " Waiting for session cancellation..."
+ " createReceivingVideoStream should only be called on client-side"
+ " createSendingVideoStream should only be called on server-side"
+ " handleMediaContinuityEndpoint returning (activation continues in background)"
+ " received start() call with [sessionID:"
+ "%{public}@ [sessionID:%llx] Received synchronized clock identifier: %llu"
+ "%{public}@ notifyUserDisconnectOnActiveSession activeSession:%{public}@"
+ "-[CMContinuityCaptureNWServer notifyUserDisconnect]"
+ "-[CMContinuityCaptureRapportServer notifyUserDisconnect]"
+ "MediaContinuitySession error: "
+ "MediaContinuitySession interrupted: "
+ "[SERVER] Registered startHandler for "
+ "[SERVER] start() received, notifying delegate of session from "
+ "[sessionID:%llx]"
+ "failPendingContinuations(with:)"
+ "init(device:session:actorSystem:streams:sessionID:)"
+ "s for identifier: "
+ "v16@?0Q8"
+ "yyyy-MM-dd HH:mm:ss.SSS"
- " Stream delegate already set, passing session info immediately"
- " Stream delegate not set yet, buffering session info"
- " Stream passing session info to delegate - sessionID: "
- " Stream received session info - sessionID: "
- " received start() call with sessionID: "
- "%{public}@ Session %@ [sessionID:%llx] Received synchronized clock identifier: %llu"
- "%{public}@ [sessionID:%llx] Received session info"
- ", hasSessionInfo: "
- "Cannot send sample buffer on inactive stream"
- "Cannot send sample buffer on receiving stream"
- "Disconnecting connection"
- "Failed to send sample buffer: "
- "Invalid stream type for sending"
- "MediaContinuity "
- "MediaContinuitySession activation wait completed"
- "MediaContinuitySession not available"
- "Send sample buffer timed out after 1 second"
- "Session connecting to device: "
- "Waiting for MediaContinuitySession activation"
- "[CLIENT] Adding stream to session, current count: "
- "[CLIENT] Calling start() on RemoteActor with sessionID: "
- "[CLIENT] Connection established, actors ready"
- "[CLIENT] Creating HostActor with handler and session"
- "[CLIENT] Creating MediaContinuitySession"
- "[CLIENT] Creating stream"
- "[CLIENT] Decoded endpoint for device: "
- "[CLIENT] Exporting HostActor"
- "[CLIENT] Failed to setup MediaContinuitySession: "
- "[CLIENT] HostActor exported with ID: "
- "[CLIENT] Incoming video stream received for entity "
- "[CLIENT] Invalidating existing MediaContinuitySession before creating new one"
- "[CLIENT] LocalInterface received, session assigned: "
- "[CLIENT] NetworkSession created (host-side) for device: "
- "[CLIENT] Processing MediaContinuityEndpoint ("
- "[CLIENT] RemoteActor imported with ID: "
- "[CLIENT] RemoteActor.start() failed: "
- "[CLIENT] RemoteActor.start() returned: "
- "[CLIENT] RemoteInterface received, importing RemoteActor"
- "[CLIENT] Returning buffered incoming video stream for entity "
- "[CLIENT] Server acknowledged start, signaling continuation"
- "[CLIENT] Server start() returned false"
- "[CLIENT] Session cancelled"
- "[CLIENT] Session ended with error: "
- "[CLIENT] Stream added to session, new count: "
- "[CLIENT] Unexpected endpoint on server side"
- "[CLIENT] Waiting for connection ready (10s timeout)..."
- "[CLIENT] Waiting for incoming video stream for entity "
- "[CLIENT] Waiting for session cancellation..."
- "[CLIENT] handleMediaContinuityEndpoint returning (activation continues in background)"
- "[SERVER] Activating MediaContinuityServer"
- "[SERVER] Cached connection info for "
- "[SERVER] Could not find default stream with hostActor to send endpoint"
- "[SERVER] Created MediaContinuityStream "
- "[SERVER] Created VideoStream: "
- "[SERVER] Creating MediaContinuityServer"
- "[SERVER] Creating sending video stream for entity "
- "[SERVER] Default stream has no hostActor"
- "[SERVER] Endpoint sent successfully"
- "[SERVER] Failed to setup MediaContinuityServer: "
- "[SERVER] MediaContinuityServer activated, got endpoint"
- "[SERVER] MediaContinuitySession stream error: "
- "[SERVER] NetworkSession created (remote-side) for device: "
- "[SERVER] No timer running, starting 1s timer"
- "[SERVER] Received incoming MediaContinuitySession"
- "[SERVER] Sending endpoint ("
- "[SERVER] Session cancelled, notifying delegate"
- "[SERVER] Timer already running, updated cached connection info"
- "[SERVER] Timer fired, notifying delegate of session from "
- "[SERVER] Unexpected activation result"
- "] Activating MediaContinuity audio stream"
- "] Activating MediaContinuity video stream"
- "] Activating MediaContinuitySession"
- "] Buffering incoming video stream for entity "
- "] Created MediaContinuityStream "
- "] Deinitializing MediaContinuity "
- "] Got synchronizedClockIdentifier: "
- "] MediaContinuity audio stream activated"
- "] MediaContinuity audio stream event error: "
- "] MediaContinuity video stream activated"
- "] MediaContinuity video stream event error: "
- "] MediaContinuity video stream invalidated by ["
- "] MediaContinuitySession activated"
- "] MediaContinuitySession event stream error: "
- "] MediaContinuitySession interrupted: "
- "] NetworkSession deallocating"
- "] Received audio sample buffer"
- "] Received changed video attributes "
- "] Received first video sample buffer"
- "] Received incoming audio stream, activating"
- "] Received incoming control stream: "
- "] Received incoming video stream: "
- "] Received video sample buffer"
- "] Resuming continuation for entity "
- "com.apple.CMContinuityCapture.NWListener.timer"
- "createReceivingVideoStream should only be called on client-side"
- "createSendingVideoStream should only be called on server-side"
- "init(device:session:actorSystem:streams:)"
- "yyyy-MM-dd hh:mm:ss.SSS"
```
