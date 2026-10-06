## LocalSpeechRecognitionBridge

> `/System/Library/PrivateFrameworks/LocalSpeechRecognitionBridge.framework/LocalSpeechRecognitionBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d9f4` | `0x1dab0` | **`+0xbc`** |
| `__AUTH_CONST.__cfstring` | `0x1ae0` | `0x1b80` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x4a7f` | `0x4b12` | **`+0x93`** |
| `__AUTH_CONST.__objc_const` | `0x3d58` | `0x3d88` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x860` | `0x870` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2514` | `0x2524` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1360` | `0x1368` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x720` | `0x728` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2cc` | `0x2d0` | **`+0x4`** |

### Other Changes

```diff

-3605.25.1.0.0
+3605.31.3.0.0

-  Functions: 744
-  Symbols:   1485
-  CStrings:  612
+  Functions: 745
+  Symbols:   1487
+  CStrings:  617
Symbols:
+ -[LBLocalSpeechRecognitionSettings initWithRequestId:inputOrigin:speechRecognitionTaskName:speechRecognitionMode:location:jitGrammar:overrideModelPath:applicationName:detectUtterances:continuousListening:shouldHandleCapitalization:secureOfflineOnly:maximumRecognitionDuration:recognitionOverrides:shouldStoreAudioOnDevice:deliverEagerPackage:enableEmojiRecognition:enableAutoPunctuation:UILanguage:enableVoiceCommands:dictationUIInteractionId:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:shouldStartAudioCapture:audioCaptureStartHostTime:audioRecordType:audioRecordDeviceId:shouldGenerateVoiceCommandCandidates:asrLocale:activeUserInfo:messagesContext:sessionId:isLinwoodEnabled:applicationProcessIdentifier:isAudioSourceRemote:]
+ -[LBLocalSpeechRecognitionSettings isAudioSourceRemote]
+ GCC_except_table668
+ GCC_except_table703
+ GCC_except_table708
+ GCC_except_table713
+ _OBJC_IVAR_$_LBLocalSpeechRecognitionSettings._isAudioSourceRemote
- +[LBLocalSpeechRecognitionSettings companionSettingsWithRequestId:inputOrigin:]
- GCC_except_table667
- GCC_except_table702
- GCC_except_table707
- GCC_except_table712
Functions:
~ -[LBLocalSpeechRecognitionSettings description] : 1100 -> 1132
~ -[LBLocalSpeechRecognitionSettings encodeWithCoder:] : 1252 -> 1296
~ -[LBLocalSpeechRecognitionSettings initWithCoder:] : 2200 -> 2256
- +[LBLocalSpeechRecognitionSettings companionSettingsWithRequestId:inputOrigin:]
~ -[LBLocalSpeechRecognitionSettings initWithRequestId:inputOrigin:speechRecognitionTaskName:speechRecognitionMode:location:jitGrammar:overrideModelPath:applicationName:detectUtterances:continuousListening:shouldHandleCapitalization:secureOfflineOnly:maximumRecognitionDuration:recognitionOverrides:shouldStoreAudioOnDevice:deliverEagerPackage:enableEmojiRecognition:enableAutoPunctuation:UILanguage:enableVoiceCommands:dictationUIInteractionId:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:shouldStartAudioCapture:audioCaptureStartHostTime:audioRecordType:audioRecordDeviceId:shouldGenerateVoiceCommandCandidates:asrLocale:activeUserInfo:messagesContext:sessionId:isLinwoodEnabled:applicationProcessIdentifier:] : 1088 -> 260
+ -[LBLocalSpeechRecognitionSettings initWithRequestId:inputOrigin:speechRecognitionTaskName:speechRecognitionMode:location:jitGrammar:overrideModelPath:applicationName:detectUtterances:continuousListening:shouldHandleCapitalization:secureOfflineOnly:maximumRecognitionDuration:recognitionOverrides:shouldStoreAudioOnDevice:deliverEagerPackage:enableEmojiRecognition:enableAutoPunctuation:UILanguage:enableVoiceCommands:dictationUIInteractionId:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:shouldStartAudioCapture:audioCaptureStartHostTime:audioRecordType:audioRecordDeviceId:shouldGenerateVoiceCommandCandidates:asrLocale:activeUserInfo:messagesContext:sessionId:isLinwoodEnabled:applicationProcessIdentifier:isAudioSourceRemote:]
+ -[LBLocalSpeechRecognitionSettings applicationProcessIdentifier]
CStrings:
+ "ContinuityEndReceived"
+ "LBLocalSpeechRecognitionSettings:::isAudioSourceRemote"
+ "NoTRPArrived"
+ "SpeechRecognitionDelayedStart"
+ "[isAudioSourceRemote = %@]"
```
