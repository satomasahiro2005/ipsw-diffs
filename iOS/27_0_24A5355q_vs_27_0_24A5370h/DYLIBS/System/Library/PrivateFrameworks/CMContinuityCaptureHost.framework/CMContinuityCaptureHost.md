## CMContinuityCaptureHost

> `/System/Library/PrivateFrameworks/CMContinuityCaptureHost.framework/CMContinuityCaptureHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa1448` | `0xa57b0` | **`+0x4368`** |
| `__TEXT.__eh_frame` | `0x20c0` | `0x2440` | **`+0x380`** |
| `__AUTH_CONST.__const` | `0x1440` | `0x15f0` | **`+0x1b0`** |
| `__TEXT.__const` | `0x12f0` | `0x1420` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0x2708` | `0x2828` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0x9540` | `0x9630` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0x69c` | `0x764` | **`+0xc8`** |
| `__AUTH.__objc_data` | `0x19a8` | `0x1a38` | **`+0x90`** |
| `__DATA.__bss` | `0xbf0` | `0xc80` | **`+0x90`** |
| `__DATA.__data` | `0x1300` | `0x1390` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x344` | `0x3d0` | **`+0x8c`** |
| `__TEXT.__swift5_typeref` | `0x8bb` | `0x947` | **`+0x8c`** |
| `__TEXT.__swift5_reflstr` | `0x3f2` | `0x476` | **`+0x84`** |
| `__TEXT.__swift5_capture` | `0x60c` | `0x688` | **`+0x7c`** |
| `__TEXT.__gcc_except_tab` | `0x2e30` | `0x2ea8` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x10d0` | `0x1138` | **`+0x68`** |
| `__DATA_CONST.__got` | `0x940` | `0x980` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1e48` | `0x1e70` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x4df0` | `0x4dcc` | **`-0x24`** |
| `__TEXT.__swift_as_entry` | `0x10c` | `0x128` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x12c` | `0x144` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x28` | `0x34` | **`+0xc`** |
| `__DATA.__common` | `0xe0` | `0xd8` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x1b0` | `0x1b4` | **`+0x4`** |
| `__TEXT.__cstring` | `0x98c7` | `0x98c5` | **`-0x2`** |

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3

-  Functions: 2807
-  Symbols:   4084
-  CStrings:  1713
+  Functions: 2860
+  Symbols:   4113
+  CStrings:  1723
Symbols:
+ -[CMContinuityCaptureNWClient _handleSynchronizedClockIdentifier:fromSession:]
+ _OBJC_IVAR_$_CMContinuityCaptureNWClient._lastActivationTime
+ __IVARS__TtC23CMContinuityCaptureHost23CancellableContinuation
+ ___78-[CMContinuityCaptureNWClient _handleSynchronizedClockIdentifier:fromSession:]_block_invoke
+ ___79-[CMContinuityCaptureNWClient _setupNetworkSessionForConfiguration:completion:]_block_invoke_3
+ ___block_descriptor_48_e8_32s40w_e8_v16?0Q8lw40l8s32l8
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e5_v8?0ls32l8s56l8s40l8s48l8w64l8
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
+ _swift_retain_x27
+ _swift_retain_x8
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
+ _symbolic SDy__________y_____GG So27ContinuityCaptureEntityTypeV 012CMContinuityB4Host23CancellableContinuationC AC0eb5MediaA6StreamC
+ _symbolic ScSy_____G s6UInt64V
+ _symbolic _____ 23CMContinuityCaptureHost23CancellableContinuationC
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ s6UInt32V
+ _symbolic _____Ieghy_ s6UInt64V
+ _symbolic _____IeyBhy_ s6UInt64V
+ _symbolic _____ySbG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySb_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____yScCyx______pGSgG 2os21OSAllocatedUnfairLockV s5ErrorP
+ _symbolic _____y_____G 23CMContinuityCaptureHost23CancellableContinuationC AA0aB21MediaContinuityStreamC
+ _symbolic _____y______G ScS12ContinuationV s6UInt64V
+ _symbolic _____y______G ScS8IteratorV s6UInt64V
+ _symbolic _____y_______G ScS12ContinuationV11YieldResultO s6UInt64V
+ _symbolic _____y_______G ScS12ContinuationV15BufferingPolicyO s6UInt64V
+ _symbolic _____y__________y_____GG s18_DictionaryStorageC So27ContinuityCaptureEntityTypeV 012CMContinuityD4Host23CancellableContinuationC AE0gd5MediaC6StreamC
+ _symbolic _____yytG 23CMContinuityCaptureHost23CancellableContinuationC
+ _symbolic _____yytGSg 23CMContinuityCaptureHost23CancellableContinuationC
+ _symbolic y_____YbcSg s6UInt64V
+ _type_layout_string So16os_unfair_lock_sV
- -[CMContinuityCaptureNWClient session:didReceiveSynchronizedClockIdentifier:]
- _OBJC_IVAR_$_CMContinuityCaptureNWClient.lastActivationTime
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CMContinuityCaptureTransportMessaging
- ___77-[CMContinuityCaptureNWClient session:didReceiveSynchronizedClockIdentifier:]_block_invoke
- ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
- ___swift_closure_destructor.116Tm
- ___swift_closure_destructor.47Tm
- ___swift_closure_destructor.84Tm
- ___swift_closure_destructor.87Tm
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_retain_x26
- _symbolic SDy_____ScCy___________pGG So27ContinuityCaptureEntityTypeV 012CMContinuityB4Host0eb5MediaA6StreamC s5ErrorP
- _symbolic ScCy___________pG 23CMContinuityCaptureHost0aB21MediaContinuityStreamC s5ErrorP
- _symbolic ScCy___________pGSg 23CMContinuityCaptureHost0aB21MediaContinuityStreamC s5ErrorP
- _symbolic ______ScCy___________pGt So27ContinuityCaptureEntityTypeV 012CMContinuityB4Host0eb5MediaA6StreamC s5ErrorP
- _symbolic _____y_____ScCy___________pGG s18_DictionaryStorageC So27ContinuityCaptureEntityTypeV 012CMContinuityD4Host0gd5MediaC6StreamC s5ErrorP
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
+ "MediaContinuitySession error: "
+ "MediaContinuitySession interrupted: "
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
- "[SERVER] Received incoming MediaContinuitySession"
- "[SERVER] Sending endpoint ("
- "[SERVER] Session cancelled, notifying delegate"
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
- "createReceivingVideoStream should only be called on client-side"
- "createSendingVideoStream should only be called on server-side"
- "init(device:session:actorSystem:streams:)"
- "yyyy-MM-dd hh:mm:ss.SSS"
```
