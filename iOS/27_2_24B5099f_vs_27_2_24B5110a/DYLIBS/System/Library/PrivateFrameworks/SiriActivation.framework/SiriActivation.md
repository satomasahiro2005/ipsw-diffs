## SiriActivation

> `/System/Library/PrivateFrameworks/SiriActivation.framework/SiriActivation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76d6c` | `0x77668` | **`+0x8fc`** |
| `__TEXT.__cstring` | `0xd0d2` | `0xd2a2` | **`+0x1d0`** |
| `__AUTH_CONST.__objc_const` | `0xb640` | `0xb7c0` | **`+0x180`** |
| `__AUTH_CONST.__cfstring` | `0x50a0` | `0x51c0` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x72dc` | `0x73f4` | **`+0x118`** |
| `__DATA_CONST.__objc_selrefs` | `0x3658` | `0x36a0` | **`+0x48`** |
| `__DATA.__objc_ivar` | `0x750` | `0x770` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1f60` | `0x1f70` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xbf0` | `0xbf8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1910` | `0x1918` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2e0` | `0x2e8` | **`+0x8`** |

### Other Changes

```diff

-3605.30.1.0.0
+3605.31.1.11.2

-  Functions: 2988
-  Symbols:   4764
-  CStrings:  1867
+  Functions: 3011
+  Symbols:   4796
+  CStrings:  1876
Symbols:
+ -[SASRequestOptions isOdeonProxyVoiceTrigger]
+ -[SASRequestOptions setIsOdeonProxyVoiceTrigger:]
+ -[SASRequestOptions setTriggerDuration:]
+ -[SASRequestOptions setTriggeredPhrase:]
+ -[SASRequestOptions setTwoShotFeedbackDelay:]
+ -[SASRequestOptions triggerDuration]
+ -[SASRequestOptions triggeredPhrase]
+ -[SASRequestOptions twoShotFeedbackDelay]
+ -[SASSystemState _inNanoPressDemoMode]
+ -[SiriTVActivationSource _clearOdeonProxyVoiceTriggerState]
+ -[SiriTVActivationSource didRecognizeButtonSinglePressUp]
+ -[SiriTVActivationSource didRecognizeLongPressInteraction:]
+ -[SiriTVActivationSource setIsOdeonProxyVoiceTrigger:]
+ -[SiriTVActivationSource setTriggerDuration:]
+ -[SiriTVActivationSource setTriggeredPhrase:]
+ -[SiriTVActivationSource setTwoShotFeedbackDelay:]
+ -[SiriTVLongPressButtonContext isOdeonProxyVoiceTrigger]
+ -[SiriTVLongPressButtonContext setIsOdeonProxyVoiceTrigger:]
+ -[SiriTVLongPressButtonContext setTriggerDuration:]
+ -[SiriTVLongPressButtonContext setTriggeredPhrase:]
+ -[SiriTVLongPressButtonContext setTwoShotFeedbackDelay:]
+ -[SiriTVLongPressButtonContext triggerDuration]
+ -[SiriTVLongPressButtonContext triggeredPhrase]
+ -[SiriTVLongPressButtonContext twoShotFeedbackDelay]
+ _AFIsATVOnly
+ _OBJC_IVAR_$_SASRequestOptions._isOdeonProxyVoiceTrigger
+ _OBJC_IVAR_$_SASRequestOptions._triggerDuration
+ _OBJC_IVAR_$_SASRequestOptions._triggeredPhrase
+ _OBJC_IVAR_$_SASRequestOptions._twoShotFeedbackDelay
+ _OBJC_IVAR_$_SiriTVLongPressButtonContext._isOdeonProxyVoiceTrigger
+ _OBJC_IVAR_$_SiriTVLongPressButtonContext._triggerDuration
+ _OBJC_IVAR_$_SiriTVLongPressButtonContext._triggeredPhrase
+ _OBJC_IVAR_$_SiriTVLongPressButtonContext._twoShotFeedbackDelay
- -[SASSystemState _inPressDemoMode]
CStrings:
+ ";isOdeonProxyVoiceTrigger=%i;triggerDuration=%.3f;twoShotFeedbackDelay=%.3f;triggeredPhrase=%@"
+ "<SiriTVLongPressButtonContext contextOverride:%@ buttonDownTimestamp:%@,activeDeviceBluetoothIdentifier:%@,remoteType:%@,isListening:%d,isSourcePTTEligible:%d,isOdeonProxyVoiceTrigger:%d,triggerDuration:%f,twoShotFeedbackDelay:%f,triggeredPhrase:%@>"
+ "SASRequestOptionsIsOdeonProxyVoiceTriggerCodingKey"
+ "SASRequestOptionsTriggerDurationCodingKey"
+ "SASRequestOptionsTriggeredPhraseCodingKey"
+ "SASRequestOptionsTwoShotFeedbackDelayCodingKey"
+ "SiriTVRemoteTypeSiriRemote2026"
+ "isOdeonProxyVoiceTrigger"
+ "triggerDuration"
+ "triggeredPhrase"
+ "twoShotFeedbackDelay"
- "<SiriTVLongPressButtonContext contextOverride:%@ buttonDownTimestamp:%@,activeDeviceBluetoothIdentifier:%@,remoteType:%@,isListening:%d,isSourcePTTEligible:%d>"
- "PressDemoMode"
```
