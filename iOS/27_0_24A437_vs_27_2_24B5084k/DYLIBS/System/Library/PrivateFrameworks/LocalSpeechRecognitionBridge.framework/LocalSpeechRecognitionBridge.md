## LocalSpeechRecognitionBridge

> `/System/Library/PrivateFrameworks/LocalSpeechRecognitionBridge.framework/LocalSpeechRecognitionBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dd64` | `0x1d774` | **`-0x5f0`** |
| `__AUTH_CONST.__objc_const` | `0x3ec8` | `0x3d28` | **`-0x1a0`** |
| `__TEXT.__cstring` | `0x4b44` | `0x4a1a` | **`-0x12a`** |
| `__TEXT.__objc_methlist` | `0x25a4` | `0x24ec` | **`-0xb8`** |
| `__AUTH_CONST.__cfstring` | `0x1b00` | `0x1aa0` | **`-0x60`** |
| `__TEXT.__oslogstring` | `0x2d90` | `0x2d3e` | **`-0x52`** |
| `__DATA_DIRTY.__objc_data` | `0x320` | `0x2d0` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x738` | `0x718` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x2d8` | `0x2c8` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x858` | `0x860` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x1e8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xe8` | `0xe0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1350` | `0x1348` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xd0` | `0xc8` | **`-0x8`** |

### Other Changes

```diff

-3600.70.47.11.1
+3605.23.1.0.0

-  Functions: 754
-  Symbols:   1508
-  CStrings:  615
+  Functions: 741
+  Symbols:   1481
+  CStrings:  610
Symbols:
+ GCC_except_table167
+ GCC_except_table312
+ GCC_except_table326
+ GCC_except_table449
+ GCC_except_table453
+ GCC_except_table459
+ GCC_except_table466
+ GCC_except_table548
+ GCC_except_table664
+ GCC_except_table699
+ GCC_except_table704
+ GCC_except_table709
- +[LBLocalSpeechRecognizerTurnFinalizedContext supportsSecureCoding]
- -[LBLocalSpeechRecognizerClient turnFinalizedwithContext:]
- -[LBLocalSpeechRecognizerTurnFinalizedContext .cxx_destruct]
- -[LBLocalSpeechRecognizerTurnFinalizedContext copyWithZone:]
- -[LBLocalSpeechRecognizerTurnFinalizedContext description]
- -[LBLocalSpeechRecognizerTurnFinalizedContext encodeWithCoder:]
- -[LBLocalSpeechRecognizerTurnFinalizedContext initWithCoder:]
- -[LBLocalSpeechRecognizerTurnFinalizedContext initWithRequestId:selectedTrpId:runtimeType:selectedRuntime:]
- -[LBLocalSpeechRecognizerTurnFinalizedContext requestId]
- -[LBLocalSpeechRecognizerTurnFinalizedContext runtimeType]
- -[LBLocalSpeechRecognizerTurnFinalizedContext selectedRuntime]
- -[LBLocalSpeechRecognizerTurnFinalizedContext selectedTrpId]
- GCC_except_table169
- GCC_except_table314
- GCC_except_table328
- GCC_except_table451
- GCC_except_table455
- GCC_except_table461
- GCC_except_table468
- GCC_except_table561
- GCC_except_table677
- GCC_except_table712
- GCC_except_table717
- GCC_except_table722
- _OBJC_CLASS_$_LBLocalSpeechRecognizerTurnFinalizedContext
- _OBJC_IVAR_$_LBLocalSpeechRecognizerTurnFinalizedContext._requestId
- _OBJC_IVAR_$_LBLocalSpeechRecognizerTurnFinalizedContext._runtimeType
- _OBJC_IVAR_$_LBLocalSpeechRecognizerTurnFinalizedContext._selectedRuntime
- _OBJC_IVAR_$_LBLocalSpeechRecognizerTurnFinalizedContext._selectedTrpId
- _OBJC_METACLASS_$_LBLocalSpeechRecognizerTurnFinalizedContext
- __OBJC_$_CLASS_METHODS_LBLocalSpeechRecognizerTurnFinalizedContext
- __OBJC_$_CLASS_PROP_LIST_LBLocalSpeechRecognizerTurnFinalizedContext
- __OBJC_$_INSTANCE_METHODS_LBLocalSpeechRecognizerTurnFinalizedContext
- __OBJC_$_INSTANCE_VARIABLES_LBLocalSpeechRecognizerTurnFinalizedContext
- __OBJC_$_PROP_LIST_LBLocalSpeechRecognizerTurnFinalizedContext
- __OBJC_CLASS_PROTOCOLS_$_LBLocalSpeechRecognizerTurnFinalizedContext
- __OBJC_CLASS_RO_$_LBLocalSpeechRecognizerTurnFinalizedContext
- __OBJC_METACLASS_RO_$_LBLocalSpeechRecognizerTurnFinalizedContext
- ___58-[LBLocalSpeechRecognizerClient turnFinalizedwithContext:]_block_invoke
CStrings:
+ "Dismissal"
- "%s LBLocalSpeechRecognizerClient[%@], xpcConnection[%@]:TurnFinalizedContext : %@"
- "-[LBLocalSpeechRecognizerClient turnFinalizedwithContext:]_block_invoke"
- "LBLocalSpeechRecognizerTurnFinalizedContext:::requestId"
- "LBLocalSpeechRecognizerTurnFinalizedContext:::runtimeType"
- "LBLocalSpeechRecognizerTurnFinalizedContext:::selectedRuntime"
- "LBLocalSpeechRecognizerTurnFinalizedContext:::selectedTrpId"
```
