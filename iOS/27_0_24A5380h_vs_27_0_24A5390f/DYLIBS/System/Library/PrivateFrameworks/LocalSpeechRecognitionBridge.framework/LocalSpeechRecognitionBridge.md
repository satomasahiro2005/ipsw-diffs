## LocalSpeechRecognitionBridge

> `/System/Library/PrivateFrameworks/LocalSpeechRecognitionBridge.framework/LocalSpeechRecognitionBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d314` | `0x1db4c` | **`+0x838`** |
| `__AUTH_CONST.__objc_const` | `0x3cc0` | `0x3e68` | **`+0x1a8`** |
| `__TEXT.__cstring` | `0x4981` | `0x4acc` | **`+0x14b`** |
| `__TEXT.__objc_methlist` | `0x24ac` | `0x256c` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x2c72` | `0x2d14` | **`+0xa2`** |
| `__AUTH_CONST.__cfstring` | `0x1a20` | `0x1ac0` | **`+0xa0`** |
| `__AUTH.__objc_data` | `0x5a0` | `0x5f0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x6e8` | `0x720` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x208` | `0x230` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x2c0` | `0x2d0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1308` | `0x1318` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xe0` | `0xe8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xc8` | `0xd0` | **`+0x8`** |

### Other Changes

```diff

-3600.70.20.1.1
+3600.70.32.0.0

-  Functions: 734
-  Symbols:   1471
-  CStrings:  603
+  Functions: 749
+  Symbols:   1501
+  CStrings:  611
Symbols:
+ +[LBLocalSpeechRecognizerRuntimeFinalizedContext supportsSecureCoding]
+ -[LBLocalSpeechRecognizerClient runtimeFinalizedwithContext:]
+ -[LBLocalSpeechRecognizerRuntimeFinalizedContext .cxx_destruct]
+ -[LBLocalSpeechRecognizerRuntimeFinalizedContext copyWithZone:]
+ -[LBLocalSpeechRecognizerRuntimeFinalizedContext description]
+ -[LBLocalSpeechRecognizerRuntimeFinalizedContext encodeWithCoder:]
+ -[LBLocalSpeechRecognizerRuntimeFinalizedContext initWithCoder:]
+ -[LBLocalSpeechRecognizerRuntimeFinalizedContext initWithRequestId:selectedTrpId:runtimeType:selectedRuntime:]
+ -[LBLocalSpeechRecognizerRuntimeFinalizedContext requestId]
+ -[LBLocalSpeechRecognizerRuntimeFinalizedContext runtimeType]
+ -[LBLocalSpeechRecognizerRuntimeFinalizedContext selectedRuntime]
+ -[LBLocalSpeechRecognizerRuntimeFinalizedContext selectedTrpId]
+ GCC_except_table169
+ GCC_except_table309
+ GCC_except_table323
+ GCC_except_table446
+ GCC_except_table450
+ GCC_except_table456
+ GCC_except_table463
+ GCC_except_table556
+ GCC_except_table672
+ GCC_except_table707
+ GCC_except_table712
+ GCC_except_table717
+ _NSStringFromLBRuntimeType
+ _OBJC_CLASS_$_LBLocalSpeechRecognizerRuntimeFinalizedContext
+ _OBJC_IVAR_$_LBLocalSpeechRecognizerRuntimeFinalizedContext._requestId
+ _OBJC_IVAR_$_LBLocalSpeechRecognizerRuntimeFinalizedContext._runtimeType
+ _OBJC_IVAR_$_LBLocalSpeechRecognizerRuntimeFinalizedContext._selectedRuntime
+ _OBJC_IVAR_$_LBLocalSpeechRecognizerRuntimeFinalizedContext._selectedTrpId
+ _OBJC_METACLASS_$_LBLocalSpeechRecognizerRuntimeFinalizedContext
+ __OBJC_$_CLASS_METHODS_LBLocalSpeechRecognizerRuntimeFinalizedContext
+ __OBJC_$_CLASS_PROP_LIST_LBLocalSpeechRecognizerRuntimeFinalizedContext
+ __OBJC_$_INSTANCE_METHODS_LBLocalSpeechRecognizerRuntimeFinalizedContext
+ __OBJC_$_INSTANCE_VARIABLES_LBLocalSpeechRecognizerRuntimeFinalizedContext
+ __OBJC_$_PROP_LIST_LBLocalSpeechRecognizerRuntimeFinalizedContext
+ __OBJC_CLASS_PROTOCOLS_$_LBLocalSpeechRecognizerRuntimeFinalizedContext
+ __OBJC_CLASS_RO_$_LBLocalSpeechRecognizerRuntimeFinalizedContext
+ __OBJC_METACLASS_RO_$_LBLocalSpeechRecognizerRuntimeFinalizedContext
+ ___39-[LBAudioStreamProvider _stopStreaming]_block_invoke
+ ___61-[LBLocalSpeechRecognizerClient runtimeFinalizedwithContext:]_block_invoke
- GCC_except_table167
- GCC_except_table320
- GCC_except_table443
- GCC_except_table447
- GCC_except_table453
- GCC_except_table460
- GCC_except_table541
- GCC_except_table657
- GCC_except_table692
- GCC_except_table697
- GCC_except_table702
CStrings:
+ "%s #stream ignoring didStopStreamingWithError. currently in state %{public}@"
+ "%s LBLocalSpeechRecognizerClient[%@], xpcConnection[%@]:RuntimeFinalizedContext : %@"
+ "-[LBLocalSpeechRecognizerClient runtimeFinalizedwithContext:]_block_invoke"
+ "<%@: %p> requestId=%@, selectedTrpId=%@, runtimeType=%@, attendingModePreference=%lu"
+ "<%@: %p> requestId=%@, selectedTrpId=%@, runtimeType=%@, selectedRuntime=%@"
+ "<%@: %p> requestId=%@, trpId=%@, selectedTrpId=%@, turnEndReason=%@, processedAudioDuration=%f, trailingSilenceDurationMs=%f, runtimeType=%@"
+ "LBLocalSpeechRecognizerRuntimeFinalizedContext:::requestId"
+ "LBLocalSpeechRecognizerRuntimeFinalizedContext:::runtimeType"
+ "LBLocalSpeechRecognizerRuntimeFinalizedContext:::selectedRuntime"
+ "LBLocalSpeechRecognizerRuntimeFinalizedContext:::selectedTrpId"
+ "Standalone"
- "<%@: %p> requestId=%@, selectedTrpId=%@, runtimeType=%lu, attendingModePreference=%lu"
- "<%@: %p> requestId=%@, selectedTrpId=%@, runtimeType=%lu, selectedRuntime=%i"
- "<%@: %p> requestId=%@, trpId=%@, selectedTrpId=%@, turnEndReason=%@, processedAudioDuration=%f, trailingSilenceDurationMs=%f, runtimeType=%lu"
```
