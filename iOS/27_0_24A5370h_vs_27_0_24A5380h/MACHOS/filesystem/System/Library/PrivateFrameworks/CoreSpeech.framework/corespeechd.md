## corespeechd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18605c` | `0x18652c` | **`+0x4d0`** |
| `__TEXT.__oslogstring` | `0x274ba` | `0x27685` | **`+0x1cb`** |
| `__TEXT.__objc_methname` | `0x47d34` | `0x47e93` | **`+0x15f`** |
| `__DATA_CONST.__got` | `0x14c8` | `0x15c8` | **`+0x100`** |
| `__DATA.__objc_const` | `0x2bab0` | `0x2b9c8` | **`-0xe8`** |
| `__TEXT.__objc_stubs` | `0x228a0` | `0x22940` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x31007` | `0x3109c` | **`+0x95`** |
| `__DATA.__data` | `0x44a4` | `0x4444` | **`-0x60`** |
| `__DATA.__objc_data` | `0x6450` | `0x6400` | **`-0x50`** |
| `__TEXT.__objc_classname` | `0x396d` | `0x3928` | **`-0x45`** |
| `__DATA.__objc_selrefs` | `0xd0e8` | `0xd128` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x6678` | `0x6638` | **`-0x40`** |
| `__TEXT.__objc_methtype` | `0x96d8` | `0x9713` | **`+0x3b`** |
| `__DATA_CONST.__cfstring` | `0x9720` | `0x9700` | **`-0x20`** |
| `__DATA.__bss` | `0x720` | `0x710` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x1750` | `0x1760` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xbc0` | `0xbc8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xa08` | `0xa00` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x5b8` | `0x5b0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x838` | `0x830` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x1bc04` | `0x1bbfc` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x6018` | `0x6020` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-3600.70.8.0.0
+3600.70.20.1.1

-  Functions: 10556
-  Symbols:   1058
-  CStrings:  17361
+  Functions: 10557
+  Symbols:   1060
+  CStrings:  17377
Symbols:
+ _LBSpeechRecognitionModeDescription
+ _OBJC_CLASS_$_CSPhraseSpotterEnabledMonitor
CStrings:
+ "%s Audio stream consuming during deferred teardown for requestId: %@ - ignore callback"
+ "%s Companion mode — disabling standalone processing for requestId: %@"
+ "%s DEBUG: _siriClientStream:%@, startStreamOption:%@, rootRequestId:%@, stopReason=%lu, supportsMagus=%d, _dismissedRequestId:%@, isDismissed=%d, _attendingDisabledRootRequestId:%@, isDisabled=%d, blockAttending=%d"
+ "%s defer to didProcessTRPCandidatePackage for sending trpCandidate when external signal is active"
+ "%s handle speechRecognition start with requestId: %@, mode: %{public}@"
+ "%s isRequestSampled:%d extraDelayMs:%.1f"
+ "%s requestId: %@, currentRequestId: %@"
+ "%s speechRecognitionMode = %{public}@; Force disabling local speech recognition"
+ "%s startCompanionRequestId: %@ — ignored: standaloneDisabled is NO"
+ "%s startCompanionRequestId: %@, standaloneDisabled: %d"
+ "%s startLogging for %@ called with previous file %@ in flight; forcing teardown"
+ "+[CSEndpointDetectedSelfLogger emitEndpointDetectedEventWithEndpointerMetrics:eventType:trpId:mhId:collisionExtraDelayMs:]"
+ "-[CSAttSiriBridgeMessageHandler startCompanionRequestId:withStandaloneDisabled:inputOrigin:]"
+ "-[CSAttSiriSpeechPresenceMessageBuilder requestSampledForCollisionDetection:extraDelayMs:]"
+ "-[CSEndpointDetectedSelfLogger requestSampledForCollisionDetection:extraDelayMs:]_block_invoke"
+ "-[CSIntuitiveConvRequest releaseAudioStreamHold]"
+ "-[CSIntuitiveConvRequestHandler _handleStopProcessingForRequestId:requestEnded:]"
+ "-[CSIntuitiveConvRequestHandler handleExternallyTriggeredLinwoodRequestCancelled:]"
+ "Td,N,V_collisionExtraDelayMs"
+ "Vv36@0:8@\"NSString\"16B24@\"NSString\"28"
+ "Vv36@0:8@16B24@28"
+ "_collisionExtraDelayMs"
+ "_evaluateAsrEndTurnSignals"
+ "_evaluateNoTRPArrivalThreshold"
+ "_evaluateTrailingSilenceThresholds"
+ "_handleStopProcessingForRequestId:requestEnded:"
+ "_runDailyEuclidProfileMaintenance"
+ "_runDailyEuclidProfileMaintenance_block_invoke"
+ "_stopProcessingNodesIncludingAudioSrcNode:"
+ "blockAttending"
+ "collisionExtraDelayMs"
+ "companionSettingsWithRequestId:inputOrigin:"
+ "configureForRecordRoute:preferUseSelfTap:"
+ "emitEndpointDetectedEventWithEndpointerMetrics:eventType:trpId:mhId:collisionExtraDelayMs:"
+ "handleExternallyTriggeredLinwoodRequestCancelled:"
+ "releaseAudioStreamHold"
+ "requestSampledForCollisionDetection:extraDelayMs:"
+ "setCollisionExtraDelayMs:"
+ "setExpectedDuration:"
+ "startCompanionRequestId:withStandaloneDisabled:inputOrigin:"
+ "v56@0:8@16q24@32@40d48"
- "%s DEBUG: _siriClientStream:%@, startStreamOption:%@, rootRequestId:%@, stopReason=%lu, supportsMagus=%d, _dismissedRequestId:%@, isDismissed=%d, _attendingDisabledRootRequestId:%@, isDisabled=%d, isRequestCancelled=%d"
- "%s Ignore TRP candidate package since external signal is active"
- "%s PhraseSpotter enabled = %{public}@"
- "%s PhraseSpotter is already %{public}@, received duplicated notification!"
- "%s handle speechRecognition start with requestId: %@"
- "+[CSEndpointDetectedSelfLogger emitEndpointDetectedEventWithEndpointerMetrics:eventType:trpId:mhId:]"
- "-[CSAttSiriSpeechPresenceMessageBuilder requestSampledForCollisionDetection:]"
- "-[CSIntuitiveConvRequestHandler _handleStopProcessingForRequestId:]"
- "-[CSPhraseSpotterEnabledMonitor _checkPhraseSpotterEnabled]"
- "-[CSPhraseSpotterEnabledMonitor _phraseSpotterEnabledDidChange]"
- "CSPhraseSpotterEnabledMonitor"
- "CSPhraseSpotterEnabledMonitor:didReceiveEnabled:"
- "CSPhraseSpotterEnabledMonitorProviding"
- "_checkPhraseSpotterEnabled"
- "_didReceivePhraseSpotterSettingChangedInQueue:"
- "_evaluateThresholds"
- "_isPhraseSpotterEnabled"
- "_phraseSpotterEnabledDidChange"
- "_runDailyEuclidProfileMaintenanceWithPermitMonitor"
- "_runDailyEuclidProfileMaintenanceWithPermitMonitor_block_invoke"
- "configureForRecordRoute:"
- "emitEndpointDetectedEventWithEndpointerMetrics:eventType:trpId:mhId:"
- "kVTPreferencesPhraseSpotterEnabledDidChangeDarwinNotification"
- "requestSampledForCollisionDetection:"
- "v48@0:8@16q24@32@40"
```
