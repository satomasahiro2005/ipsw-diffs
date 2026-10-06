## VoiceTriggerUI

> `/System/Library/PrivateFrameworks/VoiceTriggerUI.framework/VoiceTriggerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bb18` | `0x6bc20` | **`+0x108`** |
| `__TEXT.__cstring` | `0x5da5` | `0x5e15` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x2435` | `0x2465` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xa20` | `0xa30` | **`+0x10`** |

### Other Changes

```diff

-3600.16.1.0.0
+3600.16.3.0.0

-  CStrings:  851
+  CStrings:  855
Functions:
~ -[VTUIEnrollTrainingViewController dealloc] : 228 -> 316
~ -[VTUIEnrollTrainingViewController _cleanupTrainingManagerWithCompletion:] : 168 -> 300
~ -[VTUIAudioHintPlayer speakConfirmationDialog:] : 1004 -> 1024
~ -[VTUISpeechSynthesizer isSpeaking] : 396 -> 420
CStrings:
+ "%s Training manager cleanup needed=%d"
+ "%s dealloc"
+ "-[VTUIEnrollTrainingViewController _cleanupTrainingManagerWithCompletion:]"
+ "-[VTUIEnrollTrainingViewController dealloc]"
```
