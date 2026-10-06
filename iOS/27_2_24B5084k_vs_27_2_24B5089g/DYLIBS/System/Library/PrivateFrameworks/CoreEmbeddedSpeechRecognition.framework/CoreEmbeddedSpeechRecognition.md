## CoreEmbeddedSpeechRecognition

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/CoreEmbeddedSpeechRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3433d8` | `0x345780` | **`+0x23a8`** |
| `__DATA_DIRTY.__data` | `0x3e70` | `0x42d0` | **`+0x460`** |
| `__AUTH.__data` | `0xd98` | `0xb60` | **`-0x238`** |
| `__AUTH.__objc_data` | `0x12b8` | `0x1128` | **`-0x190`** |
| `__DATA.__data` | `0x27b0` | `0x2620` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `0x1b78` | `0x1d08` | **`+0x190`** |
| `__DATA.__bss` | `0x5a88` | `0x5958` | **`-0x130`** |
| `__DATA_DIRTY.__bss` | `0x3f38` | `0x4068` | **`+0x130`** |
| `__AUTH_CONST.__const` | `0x233d8` | `0x234a0` | **`+0xc8`** |
| `__AUTH_CONST.__cfstring` | `0x5140` | `0x51a0` | **`+0x60`** |
| `__TEXT.__cstring` | `0xe7ad` | `0xe80d` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xd065` | `0xd0c5` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0xb978` | `0xb9d0` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0xc994` | `0xc9e4` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x4ec0` | `0x4ee8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x1ae0` | `0x1ac0` | **`-0x20`** |
| `__TEXT.__const` | `0x8d48` | `0x8d28` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3878` | `0x3890` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2360` | `0x2358` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x528` | `0x530` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1d88` | `0x1d90` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x43ae` | `0x43a6` | **`-0x8`** |

### Other Changes

```diff

-3605.10.1.0.0
+3605.12.1.0.0

-  Functions: 11201
-  Symbols:   4952
-  CStrings:  2504
+  Functions: 11211
+  Symbols:   4956
+  CStrings:  2508
Symbols:
+ -[CESRSpeechParameters initWithLanguage:requestIdentifier:dictationUIInteractionIdentifier:task:loggingContext:applicationName:profile:overrides:modelOverrideURL:originalAudioFileURL:codec:narrowband:detectUtterances:censorSpeech:farField:secureOfflineOnly:shouldStoreAudioOnDevice:continuousListening:shouldHandleCapitalization:isSpeechAPIRequest:maximumRecognitionDuration:endpointStart:inputOrigin:location:jitGrammar:deliverEagerPackage:disableDeliveringAsrFeatures:enableEmojiRecognition:enableAutoPunctuation:enableVoiceCommands:disableEagerLimit:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:recognitionStart:shouldGenerateVoiceCommandCandidates:asrId:activeUserInfo:messagesContext:sessionIdentifier:applicationProcessIdentifier:isAudioSourceRemote:]
+ -[CESRSpeechParameters isAudioSourceRemote]
+ -[CESRSpeechParameters(InterfaceCompatibility) initWithLanguage:requestIdentifier:dictationUIInteractionIdentifier:task:loggingContext:applicationName:profile:overrides:modelOverrideURL:originalAudioFileURL:codec:narrowband:detectUtterances:censorSpeech:farField:secureOfflineOnly:shouldStoreAudioOnDevice:continuousListening:shouldHandleCapitalization:isSpeechAPIRequest:maximumRecognitionDuration:endpointStart:inputOrigin:location:jitGrammar:deliverEagerPackage:disableDeliveringAsrFeatures:enableEmojiRecognition:enableAutoPunctuation:enableVoiceCommands:disableEagerLimit:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:recognitionStart:shouldGenerateVoiceCommandCandidates:asrId:activeUserInfo:messagesContext:sessionIdentifier:applicationProcessIdentifier:]
+ -[_CESRSpeechParametersMutation setIsAudioSourceRemote:]
+ _OBJC_IVAR_$_CESRSpeechParameters._isAudioSourceRemote
+ _OBJC_IVAR_$__CESRSpeechParametersMutation._isAudioSourceRemote
- -[CESRSpeechParameters initWithLanguage:requestIdentifier:dictationUIInteractionIdentifier:task:loggingContext:applicationName:profile:overrides:modelOverrideURL:originalAudioFileURL:codec:narrowband:detectUtterances:censorSpeech:farField:secureOfflineOnly:shouldStoreAudioOnDevice:continuousListening:shouldHandleCapitalization:isSpeechAPIRequest:maximumRecognitionDuration:endpointStart:inputOrigin:location:jitGrammar:deliverEagerPackage:disableDeliveringAsrFeatures:enableEmojiRecognition:enableAutoPunctuation:enableVoiceCommands:disableEagerLimit:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:recognitionStart:shouldGenerateVoiceCommandCandidates:asrId:activeUserInfo:messagesContext:sessionIdentifier:applicationProcessIdentifier:]
- _symbolic _____Sg 6Speech26FoundationModelTranscriberC15ReportingOptionO
CStrings:
+ "CESRSpeechParameters::isAudioSourceRemote"
+ "Skipping on-screen context entity retrieval — audio source is remote for requestId %s"
+ "isAudioSourceRemote"
+ "isAudioSourceRemote = %@"
```
