## corespeechd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18652c` | `0x185700` | **`-0xe2c`** |
| `__TEXT.__objc_methname` | `0x47e93` | `0x4806b` | **`+0x1d8`** |
| `__TEXT.__gcc_except_tab` | `0x3274` | `0x30e8` | **`-0x18c`** |
| `__DATA_CONST.__const` | `0x6638` | `0x64d8` | **`-0x160`** |
| `__TEXT.__objc_stubs` | `0x22940` | `0x22840` | **`-0x100`** |
| `__DATA.__objc_const` | `0x2b9c8` | `0x2bab8` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x1bbfc` | `0x1bce4` | **`+0xe8`** |
| `__TEXT.__cstring` | `0x3109c` | `0x30fcb` | **`-0xd1`** |
| `__DATA_CONST.__cfstring` | `0x9700` | `0x9640` | **`-0xc0`** |
| `__TEXT.__oslogstring` | `0x27685` | `0x27722` | **`+0x9d`** |
| `__TEXT.__objc_methtype` | `0x9713` | `0x9791` | **`+0x7e`** |
| `__DATA.__data` | `0x4444` | `0x44a4` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x1760` | `0x1700` | **`-0x60`** |
| `__DATA_CONST.__auth_got` | `0xbc8` | `0xb98` | **`-0x30`** |
| `__TEXT.__objc_classname` | `0x3928` | `0x3948` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x21d0` | `0x21e0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6020` | `0x6010` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0xd128` | `0xd130` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x5b0` | `0x5b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-3600.70.20.1.1
+3600.70.32.0.0

-  Functions: 10557
-  Symbols:   1060
+  Functions: 10563
+  Symbols:   1054
Symbols:
+ _AVAudioSessionPortBuiltInMic
+ _CSIsWatchWithPHS
+ _NSStringFromLBRuntimeType
+ _OBJC_CLASS_$_CSRemoteAudioController
- _OBJC_CLASS_$_BMDictationUserEdit
- _XPC_ACTIVITY_INTERVAL_1_DAY
- _loadBookmark
- _objc_begin_catch
- _objc_end_catch
- _objc_exception_rethrow
- _objc_terminate
- _saveBookmark
- _xpc_activity_add_eligibility_changed_handler
- _xpc_activity_remove_eligibility_changed_handler
CStrings:
+ "%s #stream Audio streaming stopping"
+ "%s #stream Client stopped streaming"
+ "%s Ignore SpkrId Score updates for HS/JS on communal device"
+ "%s Re-anchored audio start to exclave sampleCount %llu via hostTime %llu"
+ "%s RuntimeFinalizedContext: %@"
+ "%s _handleClientDidStopWithOption; shouldStartAttending: %{public}@, shouldStartAttendingAtUserTurnEnded: %{public}@, receivedSelectedRuntimeFinalized: %{public}@"
+ "%s client stop after runtime finalized; resolving attending decision"
+ "%s handleRuntimeFinalizedForRequest; called for inactive runtime (%@). Bail out!"
+ "%s received a runtimeFinalized for both the standalone and companion, but neither runtime was selected!"
+ "%s received requestId:%@ for runtime %{public}@ doesn't match current requestId:%@. Bail out!"
+ "%s received requestId:%@ for runtime %{public}@ doesn't match the current request:%@. Bail out!"
+ "%s requestId %@, trpId: %@, runtimeType: %{public}@, selectedRuntime: %{public}@, attendingDecisionReceived: %{public}@, _startAttendingSampleCount: %lld"
+ "%s requestId: %@, trpId: %@, attendingModePreference: %i, runtimeType: %{public}@"
+ "%s requestId: %@, trpId: %@, turnEndReason: %i, runtimeType: %{public}@, shouldStartAttendingAtUserTurnEnded: %{public}@"
+ "%s rootRequestId : %@, shouldStartAttending : %{public}@"
+ "%s rootRequestId: %@, shouldStartAttending: %{public}@, _startAttendingSampleCount: %lld"
+ "%s runtime finalized before client stop; deferring attending decision to client stop"
+ "%s scdaContext = %@"
+ "%s shouldStartAttending: %d"
+ "%s trpId:%@ lastTransitionTimeMs: %f, trailingSilenceDurationMs:%f, turnEndReason:%lu, runtimeType:%{public}@"
+ "%s turnMessageHandler update requestId: %@ for runtimeType: %{public}@"
+ "%s voiceTriggerInfo[\"%@\"] was not set, scdaContext will not have a value for this property."
+ "-[CSAttSiriBridgeMessageHandler runtimeFinalizedwithContext:]"
+ "-[CSAttSiriTurnMessageHandler runtimeFinalizedwithContext:]_block_invoke"
+ "-[CSAudioStreamProviderServiceHandler _stopStreamingWithCompletion:]"
+ "-[CSIntuitiveConvRequest setShouldStartAttending:]"
+ "-[CSIntuitiveConvRequestHandler _resolveAttendingDecisionWithRequestReset:]"
+ "-[CSIntuitiveConvRequestHandler _resolveAttendingDecisionWithRequestReset:]_block_invoke_2"
+ "-[CSIntuitiveConvRequestHandler handleRuntimeFinalizedForRequest:trpId:runtimeType:selectedRuntime:]_block_invoke"
+ "@\"CSRemoteAudioController\""
+ "CSRemoteAudioControllerDelegate"
+ "T@\"CSRemoteAudioController\",&,N,V_remoteAudioController"
+ "T@\"NSString\",&,N,V_recordRoute"
+ "TB,N,V_recordingFromExclave"
+ "TB,V_receivedRuntimeFinalized"
+ "TB,V_shouldIgnoreLocalVoiceTriggerActivation"
+ "Vv24@0:8@\"LBLocalSpeechRecognizerRuntimeFinalizedContext\"16"
+ "_attendingDecisionReceived"
+ "_deliverRuntimeFinalizedEvent:trpId:runtimeType:selectedRuntime:"
+ "_handleClientStoppedStreaming"
+ "_receivedRuntimeFinalized"
+ "_receivedSelectedRuntimeFinalized"
+ "_recordingFromExclave"
+ "_remoteAudioController"
+ "_resolveAttendingDecisionWithRequestReset:"
+ "_shouldIgnoreLocalVoiceTriggerActivation"
+ "_shouldStartAttending"
+ "_startRemoteAudioControllerIfNeeded"
+ "_stopStreamingWithCompletion:"
+ "attendingDecisionReceived"
+ "audioStartHostTime"
+ "handleRuntimeFinalizedForRequest:trpId:runtimeType:selectedRuntime:"
+ "initWithProviderSelector:"
+ "receivedRuntimeFinalized"
+ "receivedRuntimeFinalized:"
+ "receivedSelectedRuntimeFinalized"
+ "recordingFromExclave"
+ "remoteAudioController"
+ "remoteAudioController:didChangeReadiness:"
+ "runtimeFinalizedwithContext:"
+ "setReceivedRuntimeFinalized:"
+ "setReceivedRuntimeFinalized:runtimeType:"
+ "setReceivedSelectedRuntimeFinalized:"
+ "setRecordingFromExclave:"
+ "setRemoteAudioController:"
+ "setShouldIgnoreLocalVoiceTriggerActivation:"
+ "setShouldStartAttending:"
+ "shouldIgnoreLocalVoiceTriggerActivation"
+ "shouldStartAttending"
+ "stopStreamingWithCompletion:"
+ "v28@0:8@\"CSRemoteAudioController\"16B24"
- "%s User Edit: BMDictatinoUserEdit reading completed successfully, saving bookmark"
- "%s User Edit: BMDictatinoUserEdit reading completed, saving bookmark"
- "%s User Edit: Deferred:%d"
- "%s User Edit: Error with confusion pair generation: %@"
- "%s User Edit: Started building"
- "%s User Edit: alignmentInfo: %@"
- "%s User Edit: eligibilityHandler deferred: %d"
- "%s User Edit: enumerating %luu event from Biome"
- "%s User Edit: failed to read from Biome, %@"
- "%s User Edit: generating confusion pairs with nbest result, n=%lu"
- "%s User Edit: process Biome event is successful, saving bookmark and logging edit events"
- "%s User Edit: xpc_transaction_exit_clean"
- "%s _handleClientDidStopWithOption; shouldStartAttending: %i"
- "%s handleTurnFinalizedForRequest; called for inactive runtime (%i). Bail out!"
- "%s received a userTurnFinalized for both the standalone and companion, but neither runtime was selected!"
- "%s received requestId:%@ for runtime %i doesn't match current requestId:%@. Bail out!"
- "%s received requestId:%@ for runtime %i doesn't match the current request:%@. Bail out!"
- "%s requestId %@, trpId: %@, runtimeType: %i, selectedRuntime: %i, shouldStartAttending: %i, _startAttendingSampleCount: %lld"
- "%s requestId: %@, trpId: %@, attendingModePreference: %i, runtimeType: %i"
- "%s requestId: %@, trpId: %@, turnEndReason: %i, runtimeType: %i, shouldStartAttendingAtUserTurnEnded: %i"
- "%s rootRequestId : %@, shouldStartAttending : %@"
- "%s streamProvider is not set!"
- "%s trpId:%@ lastTransitionTimeMs: %f, trailingSilenceDurationMs:%f, turnEndReason:%lu, runtimeType:%lu"
- "%s turnMessageHandler update requestId: %@ for runtimeType: %i"
- "-[CSIntuitiveConvRequest _holdAudioStream]"
- "-[CSIntuitiveConvRequest releaseAudioStreamHold]"
- "-[CSIntuitiveConvRequestHandler _handleClientDidStopWithOption:]_block_invoke_2"
- "-[CSIntuitiveConvRequestHandler handleTurnFinalizedForRequest:trpId:runtimeType:selectedRuntime:]_block_invoke"
- "-[CSSiriLauncher notifyBuiltInVoiceTrigger:myriadPHash:completion:]_block_invoke_2"
- "6\"12B"
- "B16@?0@\"BMStoreEvent\"8"
- "CSClassifyUserEdit"
- "CSClassifyUserEdit_block_invoke"
- "CSClassifyUserEdit_block_invoke_2"
- "T@\"<CSAudioStreamProviding>\",W,N,V_streamProvider"
- "TB,V_receivedUserTurnEnded"
- "TB,V_receivedUserTurnFinalized"
- "Td,N,V_firstAudioSampleSensorTimestamp"
- "UserEdit"
- "_holdAudioStream"
- "_receivedUserTurnEnded"
- "_receivedUserTurnFinalized"
- "_streamProvider"
- "alternativeSelections"
- "asrID"
- "com.apple.siri.speech-user-edit-classification"
- "com.apple.siri.xpc_activity.speech-user-edit"
- "drivableSinkWithBookmark:completion:shouldContinue:"
- "editMethod"
- "errorType"
- "isDictationUserEditClassificationEnabled"
- "originalText"
- "populateAlignmentInfo"
- "populateAlignmentInfo_block_invoke"
- "preItnNbest"
- "publisher"
- "receivedUserTurnEnded"
- "receivedUserTurnEnded:"
- "receivedUserTurnFinalized"
- "receivedUserTurnFinalized:"
- "recognizedText"
- "releaseAudioStreamHold"
- "replacementText"
- "sampling_rate"
- "setCSAudioStreamProviding:"
- "setReceivedUserTurnEnded:"
- "setReceivedUserTurnEnded:runtimeType:"
- "setReceivedUserTurnFinalized:"
- "setReceivedUserTurnFinalized:runtimeType:"
- "setStreamProvider:"
- "v24@?0@\"BPSCompletion\"8@\"<BMBookmark>\"16"
```
