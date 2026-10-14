## SiriActivationFoundation

> `/System/Library/PrivateFrameworks/SiriActivationFoundation.framework/SiriActivationFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3aff8` | `0x3b4f8` | **`+0x500`** |
| `__TEXT.__cstring` | `0x450b` | `0x46eb` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x5a98` | `0x5c18` | **`+0x180`** |
| `__AUTH_CONST.__cfstring` | `0x3bc0` | `0x3d00` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x285c` | `0x291c` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1110` | `0x1150` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x360` | `0x380` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x950` | `0x958` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x8a8` | `0x8b0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x11f8` | `0x1200` | **`+0x8`** |

### Other Changes

```diff

-3605.30.1.0.0
+3605.31.1.11.2

-  Functions: 1911
-  Symbols:   2092
-  CStrings:  606
+  Functions: 1927
+  Symbols:   2117
+  CStrings:  616
Symbols:
+ -[SAFRequestOptions isOdeonProxyVoiceTrigger]
+ -[SAFRequestOptions setIsOdeonProxyVoiceTrigger:]
+ -[SAFRequestOptions setTriggerDuration:]
+ -[SAFRequestOptions setTriggeredPhrase:]
+ -[SAFRequestOptions setTwoShotFeedbackDelay:]
+ -[SAFRequestOptions triggerDuration]
+ -[SAFRequestOptions triggeredPhrase]
+ -[SAFRequestOptions twoShotFeedbackDelay]
+ -[SAFTVLongPressButtonContext isOdeonProxyVoiceTrigger]
+ -[SAFTVLongPressButtonContext setIsOdeonProxyVoiceTrigger:]
+ -[SAFTVLongPressButtonContext setTriggerDuration:]
+ -[SAFTVLongPressButtonContext setTriggeredPhrase:]
+ -[SAFTVLongPressButtonContext setTwoShotFeedbackDelay:]
+ -[SAFTVLongPressButtonContext triggerDuration]
+ -[SAFTVLongPressButtonContext triggeredPhrase]
+ -[SAFTVLongPressButtonContext twoShotFeedbackDelay]
+ _AFIsATVOnly
+ _OBJC_IVAR_$_SAFRequestOptions._isOdeonProxyVoiceTrigger
+ _OBJC_IVAR_$_SAFRequestOptions._triggerDuration
+ _OBJC_IVAR_$_SAFRequestOptions._triggeredPhrase
+ _OBJC_IVAR_$_SAFRequestOptions._twoShotFeedbackDelay
+ _OBJC_IVAR_$_SAFTVLongPressButtonContext._isOdeonProxyVoiceTrigger
+ _OBJC_IVAR_$_SAFTVLongPressButtonContext._triggerDuration
+ _OBJC_IVAR_$_SAFTVLongPressButtonContext._triggeredPhrase
+ _OBJC_IVAR_$_SAFTVLongPressButtonContext._twoShotFeedbackDelay
CStrings:
+ ";isOdeonProxyVoiceTrigger=%i;triggerDuration=%.3f;twoShotFeedbackDelay=%.3f;triggeredPhrase=%@"
+ "<SiriTVLongPressButtonContext contextOverride:%@ buttonDownTimestamp:%@,activeDeviceBluetoothIdentifier:%@,remoteType:%@,isListening:%d,isSourcePTTEligible:%d,isOdeonProxyVoiceTrigger:%d,triggerDuration:%f,twoShotFeedbackDelay:%f,triggeredPhrase:%@>"
+ "SAFRequestOptionsIsOdeonProxyVoiceTriggerCodingKey"
+ "SAFRequestOptionsTriggerDurationCodingKey"
+ "SAFRequestOptionsTriggeredPhraseCodingKey"
+ "SAFRequestOptionsTwoShotFeedbackDelayCodingKey"
+ "SAFTVRemoteTypeSiriRemote2026"
+ "isOdeonProxyVoiceTrigger"
+ "triggerDuration"
+ "triggeredPhrase"
+ "twoShotFeedbackDelay"
- "<SiriTVLongPressButtonContext contextOverride:%@ buttonDownTimestamp:%@,activeDeviceBluetoothIdentifier:%@,remoteType:%@,isListening:%d,isSourcePTTEligible:%d>"
```
