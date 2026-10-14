## SpeakerRecognition

> `/System/Library/PrivateFrameworks/SpeakerRecognition.framework/SpeakerRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xba5c4` | `0xba8d0` | **`+0x30c`** |
| `__TEXT.__oslogstring` | `0xef41` | `0xefa8` | **`+0x67`** |
| `__AUTH_CONST.__auth_got` | `0x1028` | `0x1030` | **`+0x8`** |
| `__DATA.__bss` | `0x700` | `0x6f8` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x70` | `0x78` | **`+0x8`** |

### Other Changes

```diff

-3605.31.3.0.0
+3605.32.1.0.0

-  Symbols:   5009
-  CStrings:  2658
+  Symbols:   5010
+  CStrings:  2662
Symbols:
+ _CSIsJ265
Functions:
~ -[SSRVTUITrainingManager initWithLocaleIdentifier:withAppDomain:withSiriSharedUserId:withAudioProviderSelector:shouldTrainViaXPC:] : 532 -> 552
~ -[SSRVTUITrainingManager createKeywordDetector] : 464 -> 1104
~ ___106-[SSRVTUITrainingManager _trainUtteranceLocally:shouldUseASR:mhUUID:referenceString:completionWithResult:]_block_invoke_2 : 1152 -> 1172
~ -[SSRVTUITrainingManager CSVTUITrainingSession:hasTrainUtterance:languageCode:payload:] : 340 -> 432
~ +[SSRUtils isMphVTUIKeywordDetectorSupportedPlatform] : 56 -> 64
CStrings:
+ "%s _currentSecureAsset: %@"
+ "%s keywordDetector: %@"
+ "%s useRecognizerCombination: %u"
+ "%s useSecureAsset:%u"
```
