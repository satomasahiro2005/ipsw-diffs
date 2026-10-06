## corespeechd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x186934` | `0x189b44` | **`+0x3210`** |
| `__TEXT.__objc_methname` | `0x48611` | `0x48eb4` | **`+0x8a3`** |
| `__DATA.__objc_const` | `0x2bc10` | `0x2c3b0` | **`+0x7a0`** |
| `__TEXT.__oslogstring` | `0x27a9e` | `0x27fa2` | **`+0x504`** |
| `__TEXT.__cstring` | `0x3124b` | `0x31719` | **`+0x4ce`** |
| `__TEXT.__objc_methlist` | `0x1be0c` | `0x1c1ec` | **`+0x3e0`** |
| `__TEXT.__objc_stubs` | `0x229e0` | `0x22c80` | **`+0x2a0`** |
| `__TEXT.__objc_methtype` | `0x97fa` | `0x9a30` | **`+0x236`** |
| `__DATA.__objc_data` | `0x6400` | `0x6590` | **`+0x190`** |
| `__DATA_CONST.__const` | `0x6540` | `0x6660` | **`+0x120`** |
| `__DATA.__objc_selrefs` | `0xd1e8` | `0xd2e8` | **`+0x100`** |
| `__TEXT.__objc_classname` | `0x3948` | `0x3a11` | **`+0xc9`** |
| `__TEXT.__gcc_except_tab` | `0x312c` | `0x31ec` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x6268` | `0x6308` | **`+0xa0`** |
| `__DATA.__objc_ivar` | `0x21fc` | `0x2250` | **`+0x54`** |
| `__DATA_CONST.__cfstring` | `0x9660` | `0x96a0` | **`+0x40`** |
| `__DATA_CONST.__objc_classlist` | `0xa00` | `0xa28` | **`+0x28`** |
| `__DATA_CONST.__objc_superrefs` | `0x830` | `0x858` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x15c8` | `0x15d0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-  Functions: 10589
-  Symbols:   1055
-  CStrings:  17436
+  Functions: 10695
+  Symbols:   1056
+  CStrings:  17547
Symbols:
+ _NSProcessInfoPowerStateDidChangeNotification
CStrings:
+ "%s Built-in voice triggered, can stay in AOP mode"
+ "%s Disabling VoiceTrigger on AOP as since LowPowerMode is enabled"
+ "%s Disabling VoiceTrigger on AOP as since SleepMode is enabled"
+ "%s Disabling VoiceTrigger on AOP as the watch is off wrist"
+ "%s Display is off, remain in AOP mode so all triggers are gated"
+ "%s External phrase spotter running, ignore AOP trigger notification"
+ "%s ForceAPModeNonExclaveWatch=YES, forcing listening enabled (AP mode always on)"
+ "%s Phrase spotter is disabled, ignore Siri AP/AOP activation"
+ "%s RTS on watch cannot be turned on since there is another non eligible app recording and we are not in a connected or outgoing call"
+ "%s Received Hearst event %{public}ld"
+ "%s Turn on AP mode since LPM enabled with backlight ON"
+ "%s Turn on AP mode since Sleep Mode is enabled with backLight ON"
+ "%s Turn on AP mode since watch is off wrist and back light is on"
+ "%s VAD is not present (%d) or Hearst routed without phone call (%d)"
+ "%s VoiceTrigger on watch cannot be turned on since HS is disabled"
+ "%s VoiceTrigger on watch cannot be turned on since system shell is not started"
+ "%s VoiceTrigger on watch cannot be turned on since there is another non eligible app recording and we are not in a connected or outgoing call"
+ "%s phraseSpotter bypassed, ignore AOP/AP trigger notification"
+ "-[CSAlwaysOnProcessorEnabledWatchExclave _addConditons]_block_invoke"
+ "-[CSRaiseToSpeakEnabledPolicyWatchExclave _addListeningEnabledConditions]_block_invoke"
+ "-[CSVoiceTriggerAPModeSuspendPolicyWatch _addVoiceTriggerAPModeSuspendConditions]_block_invoke"
+ "-[CSVoiceTriggerAPModeSuspendPolicyWatch _addVoiceTriggerAPModeSuspendConditions]_block_invoke_2"
+ "-[CSVoiceTriggerAPModeSuspendPolicyWatch _handleClientRecordStateDidChange:eventUUID:]"
+ "-[CSVoiceTriggerAPModeSuspendPolicyWatch _handleClientRecordStateDidChange:eventUUID:]_block_invoke"
+ "-[CSVoiceTriggerAPModeSuspendPolicyWatch _isAudioRouteIneligibleForAP]"
+ "-[CSVoiceTriggerAPModeSuspendPolicyWatch _isSpeechDetectionDevicePresent]"
+ "-[CSVoiceTriggerActivationPolicyExclaveWatch CSAudioRouteChangeMonitor:didReceiveAudioRouteChangeEvent:]_block_invoke"
+ "-[CSVoiceTriggerActivationPolicyExclaveWatch _addConditons]_block_invoke"
+ "-[CSVoiceTriggerActivationPolicyExclaveWatch _isExternalPhraseSpotterRunning:]"
+ "-[CSVoiceTriggerEnabledPolicyWatchExclave _addListeningEnabledConditions]_block_invoke"
+ "@\"<CSAttSiriStateMonitorProviding>\""
+ "@\"<CSAudioRouteChangeMonitorProviding>\""
+ "@\"<CSAudioStreamActivityMonitorProviding>\""
+ "@\"<CSBatteryMonitorProviding>\""
+ "@\"<CSBuiltinSpeakerStateMonitorProviding>\""
+ "@\"<CSCommandControlStreamEventMonitorProviding>\""
+ "@\"<CSPhoneCallStateMonitorProviding>\""
+ "@\"<CSPhraseSpotterEnabledMonitorProviding>\""
+ "@\"<CSPlaybackVolumeStatusMonitorProviding>\""
+ "@\"<CSSiriAssertionMonitorProviding>\""
+ "@\"<CSSiriClientBehaviorMonitorProviding>\""
+ "@\"<CSSleepModeMonitorProviding>\""
+ "@\"<CSSpeechDetectionDevicePresentMonitorProviding>\""
+ "@\"<CSWristStateMonitorProviding>\""
+ "CSAlwaysOnProcessorEnabledWatchExclave"
+ "CSRaiseToSpeakEnabledPolicyWatchExclave"
+ "CSVoiceTriggerAPModeSuspendPolicyWatch"
+ "CSVoiceTriggerAPModeSuspendPolicyWatch RecordState queue"
+ "CSVoiceTriggerActivationPolicyExclaveWatch"
+ "CSVoiceTriggerEnabledPolicyWatchExclave"
+ "T@\"<CSAttSiriStateMonitorProviding>\",&,N,V_attSiriStateMonitor"
+ "T@\"<CSAudioRouteChangeMonitorProviding>\",&,N,V_audioRouteChangeMonitor"
+ "T@\"<CSAudioStreamActivityMonitorProviding>\",&,N,V_audiostreamActivityMonitor"
+ "T@\"<CSBatteryMonitorProviding>\",&,N,V_batteryMonitor"
+ "T@\"<CSBuiltinSpeakerStateMonitorProviding>\",&,N,V_builtinSpeakerStateMonitor"
+ "T@\"<CSCommandControlStreamEventMonitorProviding>\",&,N,V_commandControlStreamEventMonitor"
+ "T@\"<CSPhoneCallStateMonitorProviding>\",&,N,V_phoneCallStateMonitor"
+ "T@\"<CSPhraseSpotterEnabledMonitorProviding>\",&,N,V_phraseSpotterEnabledMonitor"
+ "T@\"<CSPlaybackVolumeStatusMonitorProviding>\",&,N,V_playbackVolumeStatusMonitor"
+ "T@\"<CSSiriAssertionMonitorProviding>\",&,N,V_siriAssertionMonitor"
+ "T@\"<CSSiriClientBehaviorMonitorProviding>\",&,N,V_siriClientBehaviorMonitor"
+ "T@\"<CSSleepModeMonitorProviding>\",&,N,V_sleepModeMonitor"
+ "T@\"<CSSpeechDetectionDevicePresentMonitorProviding>\",&,N,V_speechDetectionDevicePresentMonitor"
+ "T@\"<CSWristStateMonitorProviding>\",&,N,V_wristStateMonitor"
+ "TB,N,V_isSiriClientConsideredAsRecord"
+ "_addConditons"
+ "_attSiriStateMonitor"
+ "_audiostreamActivityMonitor"
+ "_batteryMonitor"
+ "_builtinSpeakerStateMonitor"
+ "_commandControlStreamEventMonitor"
+ "_handlePowerStateChange:"
+ "_isExternalPhraseSpotterRunning:"
+ "_isHearstRoutedWithNoPhoneCall"
+ "_isInPhoneCallStateWithHeadset"
+ "_isSiriClientConsideredAsRecord"
+ "_phraseSpotterEnabledMonitor"
+ "_playbackVolumeStatusMonitor"
+ "_siriAssertionMonitor"
+ "_sleepModeMonitor"
+ "_speechDetectionDevicePresentMonitor"
+ "_subscribeToMonitors"
+ "_wristStateMonitor"
+ "attSiriStateMonitor"
+ "audiostreamActivityMonitor"
+ "batteryMonitor"
+ "builtinSpeakerStateMonitor"
+ "com.apple.corespeech.CSAOPActivationEventHandlingPolicyWatch.queue"
+ "com.apple.corespeech.CSAlwaysOnProcessorEnabledExcalveWatch.queue"
+ "commandControlStreamEventMonitor"
+ "forceAPModeNonExclaveWatch"
+ "isLowPowerModeEnabled"
+ "isSiriClientConsideredAsRecord"
+ "phraseSpotterEnabledMonitor"
+ "playbackVolumeStatusMonitor"
+ "setAttSiriStateMonitor:"
+ "setAudiostreamActivityMonitor:"
+ "setBatteryMonitor:"
+ "setBuiltinSpeakerStateMonitor:"
+ "setCommandControlStreamEventMonitor:"
+ "setIsSiriClientConsideredAsRecord:"
+ "setPhraseSpotterEnabledMonitor:"
+ "setPlaybackVolumeStatusMonitor:"
+ "setSiriAssertionMonitor:"
+ "setSleepModeMonitor:"
+ "setSpeechDetectionDevicePresentMonitor:"
+ "setWristStateMonitor:"
+ "siriAssertionMonitor"
+ "sleepModeMonitor"
+ "speechDetectionDevicePresentMonitor"
+ "wristStateMonitor"
```
