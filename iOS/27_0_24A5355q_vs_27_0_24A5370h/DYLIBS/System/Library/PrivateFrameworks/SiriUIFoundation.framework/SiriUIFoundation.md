## SiriUIFoundation

> `/System/Library/PrivateFrameworks/SiriUIFoundation.framework/SiriUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8f6e8` | `0x910dc` | **`+0x19f4`** |
| `__AUTH_CONST.__objc_const` | `0x8e00` | `0x8f90` | **`+0x190`** |
| `__AUTH_CONST.__cfstring` | `0x22a0` | `0x2420` | **`+0x180`** |
| `__TEXT.__cstring` | `0x6656` | `0x6796` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x45e8` | `0x46b0` | **`+0xc8`** |
| `__TEXT.__eh_frame` | `0x24b0` | `0x23f0` | **`-0xc0`** |
| `__AUTH.__objc_data` | `0x1238` | `0x12e8` | **`+0xb0`** |
| `__AUTH_CONST.__auth_got` | `0xe98` | `0xf20` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e90` | `0x2f10` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x3ab1` | `0x3b21` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x2648` | `0x26b0` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x6fab` | `0x700b` | **`+0x60`** |
| `__TEXT.__dlopen_cstrs` | `—` | `0x58` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x1488` | `0x14d4` | **`+0x4c`** |
| `__TEXT.__gcc_except_tab` | `0x990` | `0x9dc` | **`+0x4c`** |
| `__DATA_CONST.__const` | `0x1960` | `0x19a0` | **`+0x40`** |
| `__AUTH.__data` | `0xc28` | `0xc58` | **`+0x30`** |
| `__TEXT.__const` | `0x383c` | `0x386c` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x10ca` | `0x10fa` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xf54` | `0xf7c` | **`+0x28`** |
| `__DATA.__bss` | `0x46f0` | `0x4710` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x404` | `0x420` | **`+0x1c`** |
| `__DATA_DIRTY.__data` | `0x948` | `0x960` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x724` | `0x734` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x328` | `0x330` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x158a` | `0x1590` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x12c` | `0x130` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xec` | `0xe8` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x100` | `0xfc` | **`-0x4`** |

### Other Changes

```diff

-3600.49.31.1.6
+3600.55.10.0.0

+  - /System/Library/Frameworks/SwiftUI.framework/SwiftUI

+  - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking

-  Functions: 3332
-  Symbols:   3699
-  CStrings:  1117
+  Functions: 3364
+  Symbols:   3744
+  CStrings:  1134
Symbols:
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isSiriReadThisV3Enabled]
+ -[SRUIFAudioPowerLevelUpdater _isObserving]
+ -[SRUIFAudioPowerLevelUpdater _observeFrequencyBands]
+ -[SRUIFAudioPowerLevelUpdater audioPowerDidUpdateWithType:averagePower:peakPower:frequencyBands:]
+ -[SRUIFAudioPowerLevelUpdater observeFrequencyBands:]
+ -[SRUIFAudioPowerLevelUpdater setIsObserving:]
+ -[SRUIFAudioPowerLevelUpdater setObserveFrequencyBands:]
+ -[SRUIFInstrumentationManager _emitCoreAnalyticsRequestEventAtTime:requestStatusOverride:dismissalReason:]
+ -[SRUIFInstrumentationManager _lastCoreAnalyticsEventDict]
+ -[SRUIFInstrumentationManager recordRequestStartForCoreAnalytics]
+ -[SRUIFInstrumentationManager setRequestErrorForCoreAnalytics:]
+ -[SRUIFSpeechSynthesizer _enqueueText:audioData:identifier:sessionId:preferredVoice:language:gender:promptStyle:isPhonetic:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:streamId:playbackVolume:preparationIdentifier:shouldCache:completion:analyticsContext:speakableContextInfo:]
+ -[SRUIFSpeechSynthesizer enqueueStreamText:streamId:identifier:sessionId:preferredVoice:language:gender:promptStyle:isPhonetic:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:playbackVolume:preparationIdentifier:completion:analyticsContext:speakableContextInfo:]
+ GCC_except_table100
+ GCC_except_table113
+ GCC_except_table116
+ GCC_except_table119
+ GCC_except_table126
+ GCC_except_table85
+ GCC_except_table86
+ GCC_except_table90
+ GCC_except_table92
+ GCC_except_table95
+ GCC_except_table97
+ _CoreAnalyticsLibraryCore.frameworkLibrary
+ _OBJC_CLASS_$_SRUIFAudioMeterConfiguration
+ _OBJC_IVAR_$_SRUIFAudioPowerLevelUpdater._isObserving
+ _OBJC_IVAR_$_SRUIFAudioPowerLevelUpdater._observeFrequencyBands
+ _OBJC_IVAR_$_SRUIFInstrumentationManager._caRequestError
+ _OBJC_IVAR_$_SRUIFInstrumentationManager._hasRequestStartTime
+ _OBJC_IVAR_$_SRUIFInstrumentationManager._lastCoreAnalyticsEventDictBacking
+ _OBJC_IVAR_$_SRUIFInstrumentationManager._requestErrorMachTime
+ _OBJC_IVAR_$_SRUIFInstrumentationManager._requestStartMachTime
+ _OBJC_METACLASS_$_SRUIFAudioMeterConfiguration
+ _SRUIFSiriStateFeedbackTypeGetDescription
+ __CLASS_METHODS_SRUIFAudioMeterConfiguration
+ __CLASS_PROPERTIES_SRUIFAudioMeterConfiguration
+ __DATA_SRUIFAudioMeterConfiguration
+ __INSTANCE_METHODS_SRUIFAudioMeterConfiguration
+ __METACLASS_DATA_SRUIFAudioMeterConfiguration
+ ___106-[SRUIFInstrumentationManager _emitCoreAnalyticsRequestEventAtTime:requestStatusOverride:dismissalReason:]_block_invoke
+ ___291-[SRUIFSpeechSynthesizer _enqueueText:audioData:identifier:sessionId:preferredVoice:language:gender:promptStyle:isPhonetic:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:streamId:playbackVolume:preparationIdentifier:shouldCache:completion:analyticsContext:speakableContextInfo:]_block_invoke
+ ___52-[SRUIFAudioPowerLevelUpdater startObservingUpdates]_block_invoke
+ ___63-[SRUIFInstrumentationManager setRequestErrorForCoreAnalytics:]_block_invoke
+ ___65-[SRUIFInstrumentationManager recordRequestStartForCoreAnalytics]_block_invoke
+ ___CoreAnalyticsLibraryCore_block_invoke
+ ___block_descriptor_62_e8_32s40s_e19_"NSDictionary"8?0ls32l8s40l8
+ ___getAnalyticsSendEventLazySymbolLoc_block_invoke
+ ___swift_closure_destructor.192Tm
+ ___swift_closure_destructor.199Tm
+ ___swift_closure_destructor.30Tm
+ ___swift_closure_destructor.40Tm
+ ___swift_closure_destructor.45Tm
+ ___swift_closure_destructor.57Tm
+ __emitCoreAnalyticsRequestEventAtTime:requestStatusOverride:dismissalReason:.onceToken
+ __emitCoreAnalyticsRequestEventAtTime:requestStatusOverride:dismissalReason:.timebaseInfo
+ __sl_dlopen
+ _abort_report_np
+ _audit_stringCoreAnalytics
+ _dlerror
+ _dlsym
+ _free
+ _getAnalyticsSendEventLazySymbolLoc.ptr
+ _mach_timebase_info
+ _symbolic SSz_Xx
+ _symbolic _____ 16SiriUIFoundation28SRUIFAudioMeterConfigurationC
+ _symbolic ______pSgIegg_ s5ErrorP
- -[SRUIFSpeechSynthesizer _enqueueText:audioData:identifier:sessionId:preferredVoice:language:gender:promptStyle:isPhonetic:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:optInNextGenVoice:streamId:playbackVolume:preparationIdentifier:shouldCache:completion:analyticsContext:speakableContextInfo:]
- -[SRUIFStateFeedbackManager _playSuccessFeedback]
- GCC_except_table112
- GCC_except_table115
- GCC_except_table118
- GCC_except_table125
- GCC_except_table19
- GCC_except_table84
- GCC_except_table91
- GCC_except_table94
- GCC_except_table99
- ___309-[SRUIFSpeechSynthesizer _enqueueText:audioData:identifier:sessionId:preferredVoice:language:gender:promptStyle:isPhonetic:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:optInNextGenVoice:streamId:playbackVolume:preparationIdentifier:shouldCache:completion:analyticsContext:speakableContextInfo:]_block_invoke
- ___49-[SRUIFStateFeedbackManager _playSuccessFeedback]_block_invoke
- ___swift_closure_destructor.195Tm
- ___swift_closure_destructor.202Tm
- ___swift_closure_destructor.29Tm
- ___swift_closure_destructor.33Tm
- ___swift_closure_destructor.41Tm
- ___swift_closure_destructor.43Tm
- ___swift_closure_destructor.58Tm
- _symbolic So8NSStringCSg
- _symbolic ______p 12FeatureFlags0aB3KeyP
CStrings:
+ "%@.%ld"
+ "%s #Choreography - didFinalizeUserTurn; UUID:%@ does not match current UUID:%@. Not resuming TTS."
+ "%s #instrumentation CoreAnalytics com.apple.siri.ui.uufrLatency status=%{public}@ latency=%f error=%{private}@"
+ "%s\\%s enabled=%{bool}d"
+ "-[SRUIFInstrumentationManager _emitCoreAnalyticsRequestEventAtTime:requestStatusOverride:dismissalReason:]"
+ "-[SRUIFSpeechSynthesizer _enqueueText:audioData:identifier:sessionId:preferredVoice:language:gender:promptStyle:isPhonetic:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:streamId:playbackVolume:preparationIdentifier:shouldCache:completion:analyticsContext:speakableContextInfo:]"
+ "-[SRUIFSpeechSynthesizer _enqueueText:audioData:identifier:sessionId:preferredVoice:language:gender:promptStyle:isPhonetic:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:streamId:playbackVolume:preparationIdentifier:shouldCache:completion:analyticsContext:speakableContextInfo:]_block_invoke"
+ "@\"NSDictionary\"8@?0"
+ "AnalyticsSendEventLazy"
+ "SRUIFSiriStateFeedbackTypeDelay"
+ "SRUIFSiriStateFeedbackTypeLatencyResponse"
+ "SRUIFSiriStateFeedbackTypeSuccess"
+ "cancelled"
+ "com.apple.siri.ui.uufrLatency"
+ "dismissalReason"
+ "error"
+ "failure"
+ "listenthinktoUUFR_ms"
+ "requestStatus"
+ "siri_read_this_v3"
+ "softlink:r:path:/System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics"
+ "success"
- "%s #Choreography - didFinalizeUserTurn; UUID:%@ does not match current UUID:%@. Bypassing TTS resuming."
- "%s #statefeedback started, should inform delegate"
- "-[SRUIFSpeechSynthesizer _enqueueText:audioData:identifier:sessionId:preferredVoice:language:gender:promptStyle:isPhonetic:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:optInNextGenVoice:streamId:playbackVolume:preparationIdentifier:shouldCache:completion:analyticsContext:speakableContextInfo:]"
- "-[SRUIFSpeechSynthesizer _enqueueText:audioData:identifier:sessionId:preferredVoice:language:gender:promptStyle:isPhonetic:provisionally:eligibleAfterDuration:delayed:canUseServerTTS:optInNextGenVoice:streamId:playbackVolume:preparationIdentifier:shouldCache:completion:analyticsContext:speakableContextInfo:]_block_invoke"
- "-[SRUIFStateFeedbackManager _playSuccessFeedback]_block_invoke"
```
