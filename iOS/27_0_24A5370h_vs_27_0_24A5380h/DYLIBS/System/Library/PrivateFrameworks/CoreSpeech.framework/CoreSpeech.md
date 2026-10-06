## CoreSpeech

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/CoreSpeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3f20` | `0x3b10` | **`-0x410`** |
| `__DATA_DIRTY.__objc_data` | `0x13b0` | `0x1770` | **`+0x3c0`** |
| `__TEXT.__text` | `0x149b80` | `0x149944` | **`-0x23c`** |
| `__AUTH_CONST.__objc_const` | `0x20cd8` | `0x20c20` | **`-0xb8`** |
| `__DATA_CONST.__objc_selrefs` | `0xad00` | `0xad48` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x1fd55` | `0x1fd23` | **`-0x32`** |
| `__TEXT.__objc_methlist` | `0x14bec` | `0x14c1c` | **`+0x30`** |
| `__TEXT.__cstring` | `0x28a0d` | `0x289e7` | **`-0x26`** |
| `__AUTH_CONST.__cfstring` | `0x9680` | `0x9660` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0x1e60` | `0x1e40` | **`-0x20`** |
| `__DATA.__bss` | `0x678` | `0x660` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x4f28` | `0x4f18` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x4268` | `0x4260` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x848` | `0x840` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x680` | `0x678` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x150` | `0x158` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1940` | `0x193c` | **`-0x4`** |

### Other Changes

```diff

-3600.70.8.0.0
+3600.70.20.1.1

-  Functions: 8087
-  Symbols:   14093
-  CStrings:  5577
+  Functions: 8082
+  Symbols:   14077
+  CStrings:  5574
Symbols:
+ +[CSEndpointDetectedSelfLogger emitEndpointDetectedEventWithEndpointerMetrics:eventType:trpId:mhId:collisionExtraDelayMs:]
+ -[CSEndpointDetectedSelfLogger collisionExtraDelayMs]
+ -[CSEndpointDetectedSelfLogger requestSampledForCollisionDetection:extraDelayMs:]
+ -[CSEndpointDetectedSelfLogger setCollisionExtraDelayMs:]
+ -[CSSiriSpeechRecorder _stopRecordingWithReason:hostTime:blockAttending:]
+ -[CSSiriSpeechRecorder stopSpeechCaptureForEvent:suppressAlert:hostTime:blockAttending:]
+ GCC_except_table7112
+ GCC_except_table7148
+ GCC_except_table7221
+ GCC_except_table7275
+ GCC_except_table7298
+ GCC_except_table7339
+ GCC_except_table7350
+ GCC_except_table7493
+ GCC_except_table7501
+ GCC_except_table7617
+ GCC_except_table7618
+ GCC_except_table7619
+ GCC_except_table7620
+ GCC_except_table7621
+ GCC_except_table7689
+ GCC_except_table7735
+ GCC_except_table7743
+ GCC_except_table7749
+ GCC_except_table7774
+ GCC_except_table7780
+ GCC_except_table7786
+ GCC_except_table7924
+ _OBJC_IVAR_$_CSEndpointDetectedSelfLogger._collisionExtraDelayMs
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CSAttSiriSpeechPresenceCoordinatorDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSAttSiriSpeechPresenceCoordinatorDelegate
+ __OBJC_$_PROTOCOL_REFS_CSAttSiriSpeechPresenceCoordinatorDelegate
+ __OBJC_LABEL_PROTOCOL_$_CSAttSiriSpeechPresenceCoordinatorDelegate
+ __OBJC_PROTOCOL_$_CSAttSiriSpeechPresenceCoordinatorDelegate
+ ___73-[CSSiriSpeechRecorder _stopRecordingWithReason:hostTime:blockAttending:]_block_invoke
+ ___81-[CSEndpointDetectedSelfLogger requestSampledForCollisionDetection:extraDelayMs:]_block_invoke
- +[CSEndpointDetectedSelfLogger emitEndpointDetectedEventWithEndpointerMetrics:eventType:trpId:mhId:]
- +[CSPhraseSpotterEnabledMonitor sharedInstance]
- -[CSPhraseSpotterEnabledMonitor _checkPhraseSpotterEnabled]
- -[CSPhraseSpotterEnabledMonitor _didReceivePhraseSpotterSettingChangedInQueue:]
- -[CSPhraseSpotterEnabledMonitor _notifyObserver:withEnabled:]
- -[CSPhraseSpotterEnabledMonitor _phraseSpotterEnabledDidChange]
- -[CSPhraseSpotterEnabledMonitor _startMonitoringWithQueue:]
- -[CSPhraseSpotterEnabledMonitor _stopMonitoring]
- -[CSPhraseSpotterEnabledMonitor init]
- -[CSPhraseSpotterEnabledMonitor isEnabled]
- GCC_except_table7120
- GCC_except_table7156
- GCC_except_table7229
- GCC_except_table7283
- GCC_except_table7306
- GCC_except_table7347
- GCC_except_table7358
- GCC_except_table7498
- GCC_except_table7506
- GCC_except_table7622
- GCC_except_table7623
- GCC_except_table7624
- GCC_except_table7625
- GCC_except_table7631
- GCC_except_table7694
- GCC_except_table7740
- GCC_except_table7748
- GCC_except_table7754
- GCC_except_table7779
- GCC_except_table7785
- GCC_except_table7791
- GCC_except_table7929
- _OBJC_IVAR_$_CSPhraseSpotterEnabledMonitor._isPhraseSpotterEnabled
- _OBJC_IVAR_$_CSPhraseSpotterEnabledMonitor._notifyToken
- _OBJC_METACLASS_$_CSPhraseSpotterEnabledMonitor
- __OBJC_$_CLASS_METHODS_CSPhraseSpotterEnabledMonitor
- __OBJC_$_INSTANCE_METHODS_CSPhraseSpotterEnabledMonitor
- __OBJC_$_INSTANCE_VARIABLES_CSPhraseSpotterEnabledMonitor
- __OBJC_$_PROP_LIST_CSPhraseSpotterEnabledMonitor
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSPhraseSpotterEnabledMonitorProviding
- __OBJC_$_PROTOCOL_METHOD_TYPES_CSPhraseSpotterEnabledMonitorProviding
- __OBJC_$_PROTOCOL_REFS_CSPhraseSpotterEnabledMonitorProviding
- __OBJC_CLASS_PROTOCOLS_$_CSPhraseSpotterEnabledMonitor
- __OBJC_CLASS_RO_$_CSPhraseSpotterEnabledMonitor
- __OBJC_LABEL_PROTOCOL_$_CSPhraseSpotterEnabledMonitorProviding
- __OBJC_METACLASS_RO_$_CSPhraseSpotterEnabledMonitor
- __OBJC_PROTOCOL_$_CSPhraseSpotterEnabledMonitorProviding
- __PhraseSpotterEnabledDidChange
- ___47+[CSPhraseSpotterEnabledMonitor sharedInstance]_block_invoke
- ___58-[CSSiriSpeechRecorder _stopRecordingWithReason:hostTime:]_block_invoke
- ___79-[CSPhraseSpotterEnabledMonitor _didReceivePhraseSpotterSettingChangedInQueue:]_block_invoke
- _kCSPhraseSpotterEnabledDidChangeDarwinNotification
CStrings:
+ "%s (event = %ld, suppressAlert = %d, hostTime = %llu, blockAttending = %d)"
+ "%s isRequestSampled:%d extraDelayMs:%.1f"
+ "+[CSEndpointDetectedSelfLogger emitEndpointDetectedEventWithEndpointerMetrics:eventType:trpId:mhId:collisionExtraDelayMs:]"
+ "-[CSEndpointDetectedSelfLogger requestSampledForCollisionDetection:extraDelayMs:]_block_invoke"
+ "-[CSSiriSpeechRecorder _stopRecordingWithReason:hostTime:blockAttending:]"
+ "-[CSSiriSpeechRecorder stopSpeechCaptureForEvent:suppressAlert:hostTime:blockAttending:]"
- "%s (event = %ld, suppressAlert = %d, hostTime = %llu)"
- "%s PhraseSpotter enabled = %{public}@"
- "%s PhraseSpotter is already %{public}@, received duplicated notification!"
- "+[CSEndpointDetectedSelfLogger emitEndpointDetectedEventWithEndpointerMetrics:eventType:trpId:mhId:]"
- "-[CSPhraseSpotterEnabledMonitor _checkPhraseSpotterEnabled]"
- "-[CSPhraseSpotterEnabledMonitor _phraseSpotterEnabledDidChange]"
- "-[CSSiriSpeechRecorder _stopRecordingWithReason:hostTime:]"
- "-[CSSiriSpeechRecorder stopSpeechCaptureForEvent:suppressAlert:hostTime:]"
- "kVTPreferencesPhraseSpotterEnabledDidChangeDarwinNotification"
```
