## EmbeddedAcousticRecognition

> `/System/Library/PrivateFrameworks/EmbeddedAcousticRecognition.framework/EmbeddedAcousticRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x818` | `0x1020` | **`+0x808`** |
| `__DATA.__data` | `0x1760` | `0xf90` | **`-0x7d0`** |
| `__TEXT.__text` | `0xb84bc0` | `0xb84f60` | **`+0x3a0`** |
| `__AUTH.__objc_data` | `0x2e0` | `—` | **`-0x2e0`** |
| `__DATA_DIRTY.__objc_data` | `0x3520` | `0x3800` | **`+0x2e0`** |
| `__TEXT.__cstring` | `0x804b7` | `0x80537` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0xc2fb0` | `0xc3018` | **`+0x68`** |
| `__AUTH_CONST.__const` | `0x4aca8` | `0x4acd8` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0xeca0` | `0xecd0` | **`+0x30`** |
| `__AUTH.__data` | `0x28` | `—` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0x6ec4` | `0x6edc` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3850` | `0x3860` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2278` | `0x2280` | **`+0x8`** |
| `__DATA.__common` | `0x185` | `0x17d` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x378` | `0x380` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3c540` | `0x3c548` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xa78` | `0xa7c` | **`+0x4`** |

### Other Changes

```diff

-3605.8.1.0.0
+3605.9.1.0.0

-  Functions: 40404
-  Symbols:   60649
-  CStrings:  20134
+  Functions: 40410
+  Symbols:   60657
+  CStrings:  20137
Symbols:
+ -[_EARSpeechRecognizer isAudioSourceRemote]
+ -[_EARSpeechRecognizer setIsAudioSourceRemote:]
+ GCC_except_table476
+ GCC_except_table501
+ GCC_except_table667
+ GCC_except_table902
+ _OBJC_IVAR_$__EARSpeechRecognizer._isAudioSourceRemote
+ __ZN5kaldi6quasar14EspressoV2Plan9SetAneQosE11qos_class_t
+ __ZN5kaldi6quasar16ComputeEngineItf9SetAneQosE11qos_class_t
+ __ZN5kaldi6quasar22CEFusedAcousticEncoder9SetAneQosE11qos_class_t
+ __ZN6quasar14RunAsyncParams9setAneQosE11qos_class_t
+ _e5rt_execution_stream_set_quality_of_service
- GCC_except_table1077
- GCC_except_table864
- GCC_except_table883
- GCC_except_table994
CStrings:
+ "CEAttnEncoderDecoder::Decode engine run duration="
+ "CEFusedAcousticEncoder::Encode engine run duration="
+ "v2 model ANE QoS: "
```
