## Speech

> `/System/Library/Frameworks/Speech.framework/Speech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x230d38` | `0x2313e4` | **`+0x6ac`** |
| `__TEXT.__eh_frame` | `0x14978` | `0x14a60` | **`+0xe8`** |
| `__TEXT.__const` | `0xfbc0` | `0xfc20` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xa330` | `0xa380` | **`+0x50`** |
| `__TEXT.__cstring` | `0x9ec1` | `0x9f01` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x6e48` | `0x6e7c` | **`+0x34`** |
| `__TEXT.__swift5_acfuncs` | `0x5b4` | `0x5c8` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x1570` | `0x1584` | **`+0x14`** |
| `__DATA.__data` | `0x3450` | `0x3460` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x4fad` | `0x4f9d` | **`-0x10`** |
| `__AUTH_CONST.__objc_const` | `0xe758` | `0xe760` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xf88` | `0xf80` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x30d8` | `0x30e0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x4bec` | `0x4bf4` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5034` | `0x503c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xb50` | `0xb58` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xaec` | `0xaf0` | **`+0x4`** |

### Other Changes

```diff

-3605.18.1.0.0
+3605.21.1.0.0

-  Functions: 15550
-  Symbols:   26391
-  CStrings:  1484
+  Functions: 15558
+  Symbols:   26412
+  CStrings:  1485
Symbols:
+ _$s11Distributed18RemoteCallArgumentVyShySSGGMR
+ _$s11Distributed18RemoteCallArgumentVyShySSGGMd
+ _$s6Speech0A16RecognizerWorkerC16updateEARContext7context12recompileJityAA15AnalysisContextC_SbtYaKFTQ21_
+ _$s6Speech0A16RecognizerWorkerC16updateEARContext7context12recompileJityAA15AnalysisContextC_SbtYaKFTY24_
+ _$s6Speech0A16RecognizerWorkerC16updateEARContext7context12recompileJityAA15AnalysisContextC_SbtYaKFTY25_
+ _$s6Speech19EARSpeechRecognizerC16updateJitProfile11jitEntitiesyShySSG_tF
+ _$s6Speech19EARSpeechRecognizerC16updateJitProfile11jitEntitiesyShySSG_tFTq
+ _$s6Speech19EARSpeechRecognizerC16updateJitProfile11jitEntitiesyShySSG_tYaKFTE
+ _$s6Speech19EARSpeechRecognizerC16updateJitProfile11jitEntitiesyShySSG_tYaKFTETF
+ _$s6Speech19EARSpeechRecognizerC16updateJitProfile11jitEntitiesyShySSG_tYaKFTETFTQ0_
+ _$s6Speech19EARSpeechRecognizerC16updateJitProfile11jitEntitiesyShySSG_tYaKFTETFTu
+ _$s6Speech19EARSpeechRecognizerC16updateJitProfile11jitEntitiesyShySSG_tYaKFTETQ1_
+ _$s6Speech19EARSpeechRecognizerC16updateJitProfile11jitEntitiesyShySSG_tYaKFTETY0_
+ _$s6Speech19EARSpeechRecognizerC16updateJitProfile11jitEntitiesyShySSG_tYaKFTETY2_
+ _$s6Speech19EARSpeechRecognizerC16updateJitProfile11jitEntitiesyShySSG_tYaKFTETY3_
+ _$s6Speech19EARSpeechRecognizerC16updateJitProfile11jitEntitiesyShySSG_tYaKFTETY4_
+ _$s6Speech19EARSpeechRecognizerC16updateJitProfile11jitEntitiesyShySSG_tYaKFTETu
+ _$s6Speech27NSXPCActorInvocationEncoderV14recordArgumentyy11Distributed010RemoteCallF0VyxGKAA0B12SerializableRzlFShySSG_Tg5
+ _$sSa5countSivgSo36_SFContextualNamedEntityCodingObjectC_Tg5
+ _$sSh9formUnionyyqd__n7ElementQyd__RszSTRd__lFSS_SaySSGTg5
+ _$sShySSGmMR
+ _$sShySSGmMd
+ ___swift_closure_destructor.131Tm
+ ___swift_closure_destructor.200Tm
+ ___swift_closure_destructor.220Tm
+ ___swift_closure_destructor.226Tm
+ _symbolic ShySSG___________pIetMHgTgzo_ 6Speech19EARSpeechRecognizerC s5ErrorP
+ _symbolic ShySSGm
+ _symbolic _____yShySSGG 11Distributed18RemoteCallArgumentV
- _$s6Speech0A16RecognizerWorkerC16updateEARContext7context12recompileJityAA15AnalysisContextC_SbtYaKFTY21_
- _$s6Speech17SelfLoggingHelperC02isC10Prohibited33_A8614503E4C1A97297441D4FA720007FLLySbSo30SISchemaInstrumentationMessageC_SSSgtFZ
- _$s6Speech17SelfLoggingHelperC15nonTier1Message33_A8614503E4C1A97297441D4FA720007FLLySbSo023SISchemaInstrumentationG0CFZ
- _OBJC_CLASS_$_ASRSchemaASRAssetLoadContext
- ___swift_closure_destructor.127Tm
- ___swift_closure_destructor.196Tm
- ___swift_closure_destructor.216Tm
- ___swift_closure_destructor.222Tm
CStrings:
+ "Logging prohibited for task: %s"
+ "Speech.EARSpeechRecognizer.updateJitProfile(jitEntities:)"
- "Logging prohibited for event:%@ task:%s"
```
