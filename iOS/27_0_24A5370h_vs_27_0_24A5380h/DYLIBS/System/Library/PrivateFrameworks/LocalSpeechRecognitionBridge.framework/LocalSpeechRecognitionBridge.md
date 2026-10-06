## LocalSpeechRecognitionBridge

> `/System/Library/PrivateFrameworks/LocalSpeechRecognitionBridge.framework/LocalSpeechRecognitionBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bfb8` | `0x1d314` | **`+0x135c`** |
| `__TEXT.__oslogstring` | `0x297f` | `0x2c72` | **`+0x2f3`** |
| `__TEXT.__cstring` | `0x46e6` | `0x4981` | **`+0x29b`** |
| `__DATA_CONST.__const` | `0x728` | `0x858` | **`+0x130`** |
| `__AUTH_CONST.__cfstring` | `0x1980` | `0x1a20` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x80` | `0xc0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x1d0` | `0x208` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x6b0` | `0x6e8` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x12e0` | `0x1308` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x2494` | `0x24ac` | **`+0x18`** |
| `__DATA.__bss` | `0x10` | `—` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x48` | `0x58` | **`+0x10`** |
| `__TEXT.__const` | `0xa0` | `0xb0` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x3cb8` | `0x3cc0` | **`+0x8`** |

### Other Changes

```diff

-3600.70.8.0.0
+3600.70.20.1.1

-  Functions: 718
-  Symbols:   1454
-  CStrings:  582
+  Functions: 734
+  Symbols:   1471
+  CStrings:  603
Symbols:
+ +[LBLocalSpeechRecognitionSettings companionSettingsWithRequestId:inputOrigin:]
+ -[LBAudioStreamConsumer _serviceWithErrorHandler:]
+ -[LBLocalSpeechRecognizerClient startCompanionRequestId:withStandaloneDisabled:inputOrigin:recordType:audioDeviceId:hostTime:shouldStartCapture:]
+ GCC_except_table167
+ GCC_except_table320
+ GCC_except_table443
+ GCC_except_table447
+ GCC_except_table453
+ GCC_except_table460
+ GCC_except_table541
+ GCC_except_table657
+ GCC_except_table692
+ GCC_except_table697
+ GCC_except_table702
+ _LBSpeechRecognitionModeDescription
+ ___145-[LBLocalSpeechRecognizerClient startCompanionRequestId:withStandaloneDisabled:inputOrigin:recordType:audioDeviceId:hostTime:shouldStartCapture:]_block_invoke
+ ___145-[LBLocalSpeechRecognizerClient startCompanionRequestId:withStandaloneDisabled:inputOrigin:recordType:audioDeviceId:hostTime:shouldStartCapture:]_block_invoke_2
+ ___52-[LBAudioStreamConsumer _consumePackets:completion:]_block_invoke_2
+ ___54-[LBAudioStreamConsumer _stopConsumingWithCompletion:]_block_invoke
+ ___54-[LBAudioStreamConsumer _stopConsumingWithCompletion:]_block_invoke_2
+ ___block_descriptor_32_e17_v16?0"NSError"8l
+ ___block_descriptor_56_e8_32bs40r48w_e5_v8?0lw48l8r40l8s32l8
+ ___block_descriptor_57_e8_32s40s48s_e20_v20?0B8"NSError"12ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40bs48r56w_e17_v16?0"NSError"8ls32l8w56l8r48l8s40l8
+ ___block_descriptor_64_e8_32s40bs48r56w_e20_v20?0B8"NSError"12lw56l8r48l8s40l8s32l8
+ ___block_descriptor_64_e8_32s40bs48r56w_e5_v8?0lw56l8r48l8s32l8s40l8
+ ___block_descriptor_66_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_73_e8_32s40s48bs56r64w_e5_v8?0lw64l8r56l8s32l8s48l8s40l8
+ ___block_descriptor_82_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ _objc_unsafeClaimAutoreleasedReturnValue
- -[LBAudioStreamConsumer _service]
- GCC_except_table163
- GCC_except_table316
- GCC_except_table437
- GCC_except_table441
- GCC_except_table448
- GCC_except_table527
- GCC_except_table641
- GCC_except_table676
- GCC_except_table681
- GCC_except_table686
- ___block_descriptor_56_e8_32s40bs48w_e20_v20?0B8"NSError"12lw48l8s40l8s32l8
- ___block_descriptor_65_e8_32s40s48bs56w_e5_v8?0lw56l8s48l8s32l8s40l8
CStrings:
+ "%s #stream XPC connection error during consumePackets: %@"
+ "%s #stream XPC connection error during startConsuming: %@"
+ "%s #stream XPC connection error during stopConsuming: %@"
+ "%s #stream XPC connection error during updateManualModeEnabled: %@"
+ "%s #stream XPC connection error during updateStoppingWithHTTMode: %@"
+ "%s #stream configuration.streamInfo is nil"
+ "%s LBLocalSpeechRecognizerClient[%@], xpcConnection[%@]:Failed to start audio capture with error : %@"
+ "%s LBLocalSpeechRecognizerClient[%@], xpcConnection[%@]:requestId: %@ — ignored: standaloneDisabled is NO"
+ "%s LBLocalSpeechRecognizerClient[%@], xpcConnection[%@]:requestId: %@, shouldStartCapture: %d"
+ "%s LBLocalSpeechRecognizerClient[%@], xpcConnection[%@]:starting audio capture with hostTime: %llu"
+ "-[LBAudioStreamConsumer _consumePackets:completion:]_block_invoke_2"
+ "-[LBAudioStreamConsumer _stopConsumingWithCompletion:]_block_invoke_2"
+ "-[LBLocalSpeechRecognizerClient startCompanionRequestId:withStandaloneDisabled:inputOrigin:recordType:audioDeviceId:hostTime:shouldStartCapture:]"
+ "-[LBLocalSpeechRecognizerClient startCompanionRequestId:withStandaloneDisabled:inputOrigin:recordType:audioDeviceId:hostTime:shouldStartCapture:]_block_invoke"
+ "-[LBLocalSpeechRecognizerClient startCompanionRequestId:withStandaloneDisabled:inputOrigin:recordType:audioDeviceId:hostTime:shouldStartCapture:]_block_invoke_2"
+ "Classic"
+ "Companion"
+ "FullUOD"
+ "Hybrid"
+ "Unknown(%lu)"
+ "[speechRecognitionMode = %@]"
+ "v16@?0@\"NSError\"8"
- "[speechRecognitionMode = %lu]"
```
