## LocalSpeechRecognitionBridge

> `/System/Library/PrivateFrameworks/LocalSpeechRecognitionBridge.framework/LocalSpeechRecognitionBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d774` | `0x1d9f4` | **`+0x280`** |
| `__AUTH.__objc_data` | `0x5f0` | `0x4b0` | **`-0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x2d0` | `0x410` | **`+0x140`** |
| `__TEXT.__cstring` | `0x4a1a` | `0x4a7f` | **`+0x65`** |
| `__AUTH_CONST.__cfstring` | `0x1aa0` | `0x1ae0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x3d28` | `0x3d58` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x24ec` | `0x2514` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1348` | `0x1360` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x718` | `0x720` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2c8` | `0x2cc` | **`+0x4`** |

### Other Changes

```diff

-3605.23.1.0.0
+3605.25.1.0.0

-  Functions: 741
-  Symbols:   1481
-  CStrings:  610
+  Functions: 744
+  Symbols:   1485
+  CStrings:  612
Symbols:
+ -[LBLocalSpeechRecognitionSettings applicationProcessIdentifier]
+ -[LBLocalSpeechRecognitionSettings initWithRequestId:inputOrigin:speechRecognitionTaskName:speechRecognitionMode:location:jitGrammar:overrideModelPath:applicationName:detectUtterances:continuousListening:shouldHandleCapitalization:secureOfflineOnly:maximumRecognitionDuration:recognitionOverrides:shouldStoreAudioOnDevice:deliverEagerPackage:enableEmojiRecognition:enableAutoPunctuation:UILanguage:enableVoiceCommands:dictationUIInteractionId:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:shouldStartAudioCapture:audioCaptureStartHostTime:audioRecordType:audioRecordDeviceId:shouldGenerateVoiceCommandCandidates:asrLocale:activeUserInfo:messagesContext:sessionId:applicationProcessIdentifier:]
+ -[LBLocalSpeechRecognitionSettings initWithRequestId:inputOrigin:speechRecognitionTaskName:speechRecognitionMode:location:jitGrammar:overrideModelPath:applicationName:detectUtterances:continuousListening:shouldHandleCapitalization:secureOfflineOnly:maximumRecognitionDuration:recognitionOverrides:shouldStoreAudioOnDevice:deliverEagerPackage:enableEmojiRecognition:enableAutoPunctuation:UILanguage:enableVoiceCommands:dictationUIInteractionId:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:shouldStartAudioCapture:audioCaptureStartHostTime:audioRecordType:audioRecordDeviceId:shouldGenerateVoiceCommandCandidates:asrLocale:activeUserInfo:messagesContext:sessionId:isLinwoodEnabled:applicationProcessIdentifier:]
+ GCC_except_table667
+ GCC_except_table702
+ GCC_except_table707
+ GCC_except_table712
+ _OBJC_IVAR_$_LBLocalSpeechRecognitionSettings._applicationProcessIdentifier
- GCC_except_table664
- GCC_except_table699
- GCC_except_table704
- GCC_except_table709
CStrings:
+ "LBLocalSpeechRecognitionSettings:::applicationProcessIdentifier"
+ "[applicationProcessIdentifier = %ld]"
```
