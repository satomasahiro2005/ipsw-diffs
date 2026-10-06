## corespeechd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x181cd0` | `0x1833e0` | **`+0x1710`** |
| `__TEXT.__objc_methname` | `0x48a91` | `0x49237` | **`+0x7a6`** |
| `__TEXT.__oslogstring` | `0x27ae9` | `0x280c5` | **`+0x5dc`** |
| `__DATA.__objc_const` | `0x2c4b0` | `0x2c900` | **`+0x450`** |
| `__TEXT.__objc_stubs` | `0x22340` | `0x22660` | **`+0x320`** |
| `__TEXT.__cstring` | `0x30f03` | `0x3116b` | **`+0x268`** |
| `__TEXT.__objc_methlist` | `0x1c178` | `0x1c3a0` | **`+0x228`** |
| `__DATA.__objc_selrefs` | `0xd0f8` | `0xd210` | **`+0x118`** |
| `__TEXT.__objc_methtype` | `0x973d` | `0x97e8` | **`+0xab`** |
| `__DATA.__objc_data` | `0x64a0` | `0x6540` | **`+0xa0`** |
| `__DATA_CONST.__cfstring` | `0x9100` | `0x9180` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x6128` | `0x61a0` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x30f8` | `0x3138` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x226c` | `0x22a8` | **`+0x3c`** |
| `__TEXT.__objc_classname` | `0x3a44` | `0x3a7f` | **`+0x3b`** |
| `__DATA_CONST.__const` | `0x5e50` | `0x5e80` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `0xd38` | `0xd50` | **`+0x18`** |
| `__DATA.__bss` | `0x6f8` | `0x708` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1540` | `0x1550` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xa10` | `0xa20` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x838` | `0x848` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`

### Other Changes

```diff

-3605.25.1.0.0
+3605.31.3.0.0

-  Functions: 10579
-  Symbols:   1035
-  CStrings:  17362
+  Functions: 10623
+  Symbols:   1037
+  CStrings:  17449
Symbols:
+ _OBJC_CLASS_$_CSFModelConfigDecoder
+ _OBJC_CLASS_$_LBLocalSpeechRecognizerTurnEndContext
CStrings:
+ "#Bab"
+ "%s Cancel received for retired requestId:%{public}@, currentRequestId:%{public}@. Bail out!"
+ "%s Coordinator discarding speech recognition task %lu for stale requestId: %@ (active: %@)"
+ "%s Coordinator received ASR first pass features - wordCount: %lu, trailingSilence: %ldms, processedAudio: %ldms"
+ "%s Coordinator speech recognition task set to %lu (isSiriDictation=%d)"
+ "%s Dropping pending attending decision for disabled rootRequestId: %@"
+ "%s Dropping pending attending start for disabled rootRequestId: %@"
+ "%s Evicting ctx for requestId:%{public}@ ageMs:%llu"
+ "%s Failed to delete uncommitted leading utterance: %{public}@"
+ "%s Inference profile: appDomain=%{public}@ profileID=%{public}@ locale=%{public}@"
+ "%s Multiple requests in progress - %@"
+ "%s Newer request (%@) is active, skipping completion tail for drained request %@"
+ "%s Resolved turn-end metrics: speechEndHostTime=%llu trailingSilence=%.1fms"
+ "%s Skipping cc session-end cleanup: leading-utterance recording in flight"
+ "%s Trailing silence threshold met via NoTRPArrival (%.1fms): trailingSilence=%.1fms (processedAudio=%ldms - trpSilStart=%.1fms)"
+ "%s Trailing silence threshold met: trailingSilence=%.1fms (processedAudio=%ldms - trpSilStart=%.1fms)"
+ "%s Triggering TRP timeout since %.1f ms have elapsed since last TCU/Speech and ASR decoded %.1f ms with no wordCount change (threshold: %.1f), wordCount: %lu, asrProcessedAudioAtLastWordCountChangeMs: %.1ld, totalProcessAudioDurationMs: %.1ld and startAnchorPoint: %.1f"
+ "%s Triggering TRP timeout since %.1f ms have elapsed since last TCU/Speech and no wordCount change, totalProcessAudioDurationMs: %.1ld and startAnchorPoint: %.1f"
+ "%s not stopping audio stream; requestId:%{public}@ retired, currentRequestId:%{public}@"
+ "%s open turn-based audio gate for requestId: %@"
+ "%s received requestId:%{public}@ doesn't match currentRequest's %{public}@ requestId:%{public}@. Bail out!"
+ "%s requestId: %@, trpId: %@, turnEndReason: %{public}@, processedAudioDurationMs: %f, trailingSilenceDurationMs: %f, runtimeType: %{public}@, shouldStartAttendingAtUserTurnEnded: %{public}@"
+ "%s requestId: %{public}@ turn Ended at sample count: %.3llu, trailingSilenceDurationMs: %f (not subtracted)"
+ "%s trpId:%@ lastTransitionTimeMs: %f, trailingSilenceDurationMs:%f, turnEndReason:%{public}@, runtimeType:%{public}@"
+ "%s tryReplayingFromBufferStart: gate already open, skipping replay"
+ "-[CSAttSiriSSRNode _beginLeadingUtteranceCapture]"
+ "-[CSAttSiriSpeechPresenceCoordinator turnEndMetricsForTRPId:turnEndReason:processedAudioDurationMs:]"
+ "-[CSAttSiriSpeechPresenceCoordinator updateSpeechRecognitionTask:forRequestId:]_block_invoke"
+ "-[CSAttSiriSpeechRecognitionNode _releaseDrainingSpeechRecognition]"
+ "-[CSAttSiriUresNode _removeExpiredRequestsExcluding:now:]"
+ "-[CSIntuitiveConvRequestHandler disableAttendingRequestedForRootRequestId:]_block_invoke"
+ "-[CSIntuitiveConvRequestHandler openTurnBasedAudioGateForRequestId:]_block_invoke"
+ "<%@: speechEndHostTime=%llu trailingSilenceMs=%.1f>"
+ "@\"CSAttSiriDrainingSpeechRecognition\""
+ "@32@0:8Q16d24"
+ "@40@0:8@16Q24d32"
+ "B40@0:8@16^@24^@32"
+ "B56@0:8Q16Q24@\"NSString\"32^@40^@48"
+ "B56@0:8Q16Q24@32^@40^@48"
+ "CSAttSiriDrainingSpeechRecognition"
+ "CSAttSiriTurnEndMetrics"
+ "MHId %@ recordType %@ ageMs %llu"
+ "T@\"<CoreEmbeddedSpeechRecognizerProvider>\",R,N,V_recognizer"
+ "T@\"CSAttSiriDrainingSpeechRecognition\",&,N,V_drainingSpeechRecognition"
+ "T@\"NSString\",R,N,V_recognizerLanguage"
+ "T@,&,N,V_analytics"
+ "T@,&,N,V_selfLoggingStream"
+ "TB,N,V_committedLeadingUtterance"
+ "TB,V_requestExclaveAudio"
+ "TQ,N,V_speechRecognitionTask"
+ "TQ,R,N,V_creationHostTime"
+ "TQ,R,N,V_speechEndHostTime"
+ "Td,R,N,V_trailingSilenceMs"
+ "Tq,N,V_asrProcessedAudioAtLastWordCountChangeMs"
+ "Tq,R,N,V_endpointMode"
+ "_analytics"
+ "_asrProcessedAudioAtLastWordCountChangeMs"
+ "_audioBufferForWriting"
+ "_beginLeadingUtteranceCapture"
+ "_committedLeadingUtterance"
+ "_creationHostTime"
+ "_drainingSpeechRecognition"
+ "_isSiriDictationTask"
+ "_newestRequestCtx"
+ "_recognizer"
+ "_releaseDrainingSpeechRecognition"
+ "_removeExpiredRequestsExcluding:"
+ "_removeExpiredRequestsExcluding:now:"
+ "_requestExclaveAudio"
+ "_selfLoggingStream"
+ "_sendMessageAndReplySync:reply:error:"
+ "_sendReplyMessageWithResult:audioDeviceInfo:error:event:client:"
+ "_speechEndHostTime"
+ "_speechRecognitionTask"
+ "_trailingSilenceMs"
+ "activateAudioSessionWithReason:dynamicAttribute:bundleID:audioDeviceInfo:error:"
+ "analytics"
+ "asrNoWordCountChangeTimeoutMs"
+ "asrProcessedAudioAtLastWordCountChangeMs"
+ "canCreateContinuousConversationProfile"
+ "committedLeadingUtterance"
+ "creationHostTime"
+ "decodeJsonFromFile:"
+ "defaultOptionWithTimeout:requestExclaveAudio:"
+ "drainingLocalSpeechRecognizer"
+ "drainingSpeechRecognition"
+ "initWithLanguage:requestIdentifier:dictationUIInteractionIdentifier:task:loggingContext:applicationName:profile:overrides:modelOverrideURL:originalAudioFileURL:codec:narrowband:detectUtterances:censorSpeech:farField:secureOfflineOnly:shouldStoreAudioOnDevice:continuousListening:shouldHandleCapitalization:isSpeechAPIRequest:maximumRecognitionDuration:endpointStart:inputOrigin:location:jitGrammar:deliverEagerPackage:disableDeliveringAsrFeatures:enableEmojiRecognition:enableAutoPunctuation:enableVoiceCommands:disableEagerLimit:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:recognitionStart:shouldGenerateVoiceCommandCandidates:asrId:activeUserInfo:messagesContext:sessionIdentifier:applicationProcessIdentifier:isAudioSourceRemote:"
+ "initWithRecognizer:requestId:endpointMode:recognizerLanguage:"
+ "initWithSpeechEndHostTime:trailingSilenceMs:"
+ "initWithTimeout:clientIdentity:requireRecordModeLock:requireListeningMicIndicatorLock:requestExclaveAudio:"
+ "isAudioSourceRemote"
+ "openTurnBasedAudioGateForRequestId:"
+ "purgeCachedConfigs"
+ "recognizer"
+ "requestAudioDeviceInfo"
+ "requestExclaveAudio"
+ "selfLoggingStream"
+ "setAnalytics:"
+ "setAsrProcessedAudioAtLastWordCountChangeMs:"
+ "setCommittedLeadingUtterance:"
+ "setDrainingSpeechRecognition:"
+ "setSelfLoggingStream:"
+ "setSpeechRecognitionTask:"
+ "trailingSilenceDurationThresholdMsExtendedSiriDictation"
+ "trailingSilenceDurationThresholdMsMaximumSiriDictation"
+ "trailingSilenceMs"
+ "turnEndMetricsForTRPId:turnEndReason:processedAudioDurationMs:"
+ "turnEndReasonString:"
+ "updateSpeechRecognitionTask:forRequestId:"
+ "v52@0:8B16@20@28@36@44"
+ "\xa5"
- "#2aR"
- "%s Coordinator received ASR first pass features - wordCount: %lu, trailingSilence: %ldms"
- "%s ERR: metaData is nil, defaulting to NO for %@"
- "%s ERR: read metafile %@ failed with %{public}@ - defaulting to NO"
- "%s Triggering TRP timeout since %.1f ms have elapsed since last TCU/Speech, totalProcessAudioDurationMs: %.1ld and startAnchorPoint: %.1f"
- "%s not stopping audio stream; received requestId:%@ doesn't match the current requestId:%@"
- "%s requestId: %@, trpId: %@, turnEndReason: %i, processedAudioDurationMs: %f, runtimeType: %{public}@, shouldStartAttendingAtUserTurnEnded: %{public}@"
- "%s trailingSilence(%f) >= baseNoTRPThreshold(%f)?"
- "%s trailingSilence=%.1f"
- "%s trpId:%@ lastTransitionTimeMs: %f, trailingSilenceDurationMs:%f, turnEndReason:%lu, runtimeType:%{public}@"
- "%s turn Ended at sample count: %.3llu, turnEndSampleCountMinusTrailingSilence: %.3llu"
- "-[CSAttSiriSSRNode _setupLeadingUtteranceLogger]"
- "-[CSAttSiriUresNode _decodeJsonFromFile:]"
- "-[CSEndpointAnalyzerBase getHybridEndpointerConfigForAsset:]"
- "MHId %@ recordType %@"
- "_decodeJsonFromFile:"
- "_setupLeadingUtteranceLogger"
- "companionSettingsWithRequestId:inputOrigin:"
- "configureForRecordRoute:preferUseSelfTap:"
- "deactivate"
- "initWithLanguage:requestIdentifier:dictationUIInteractionIdentifier:task:loggingContext:applicationName:profile:overrides:modelOverrideURL:originalAudioFileURL:codec:narrowband:detectUtterances:censorSpeech:farField:secureOfflineOnly:shouldStoreAudioOnDevice:continuousListening:shouldHandleCapitalization:isSpeechAPIRequest:maximumRecognitionDuration:endpointStart:inputOrigin:location:jitGrammar:deliverEagerPackage:disableDeliveringAsrFeatures:enableEmojiRecognition:enableAutoPunctuation:enableVoiceCommands:disableEagerLimit:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:recognitionStart:shouldGenerateVoiceCommandCandidates:asrId:activeUserInfo:messagesContext:sessionIdentifier:applicationProcessIdentifier:"
- "isTriggerlessAnnounce"
- "processAudioChunkForTV:"
- "\xa3"
```
