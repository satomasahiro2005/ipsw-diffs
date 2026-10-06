## SpeechEngine

> `/System/Library/PrivateFrameworks/SpeechEngine.framework/SpeechEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12f514` | `0x133470` | **`+0x3f5c`** |
| `__TEXT.__eh_frame` | `0xdf94` | `0xe394` | **`+0x400`** |
| `__TEXT.__cstring` | `0x5521` | `0x5771` | **`+0x250`** |
| `__TEXT.__swift5_reflstr` | `0x39c6` | `0x3b06` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x5038` | `0x5158` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x5df8` | `0x5f00` | **`+0x108`** |
| `__DATA.__data` | `0x2a68` | `0x2968` | **`-0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x4768` | `0x4838` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0xbec0` | `0xbe28` | **`-0x98`** |
| `__TEXT.__const` | `0xe380` | `0xe3f0` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x1ab8` | `0x1a48` | **`-0x70`** |
| `__TEXT.__swift_as_cont` | `0xb98` | `0xc00` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x412f` | `0x417f` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x218` | `0x258` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x390c` | `0x3948` | **`+0x3c`** |
| `__DATA.__common` | `0x3e0` | `0x400` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x59d0` | `0x59f0` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x410` | `0x424` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x404` | `0x414` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x5180` | `0x518c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1988` | `0x1990` | **`+0x8`** |

### Other Changes

```diff

-3600.76.1.0.0
+3600.85.2.0.0

-  Functions: 9065
-  Symbols:   2382
-  CStrings:  899
+  Functions: 9128
+  Symbols:   2380
+  CStrings:  914
Symbols:
+ _NSUnderlyingErrorKey
+ ___swift_closure_destructor.395Tm
+ ___swift_closure_destructor.44Tm
+ ___swift_closure_destructor.553Tm
+ ___swift_closure_destructor.98Tm
+ ___swift_memcpy196_8
+ ___swift_memcpy249_8
+ ___swift_memcpy88_8
+ _swift_release_x6
+ _symbolic SJ
+ _symbolic Say_____GSg s7Float16V
+ _symbolic ScTy__________G 12SpeechEngine0A18TokenPostProcessorC s5NeverO
+ _symbolic ScTy___________pGSg 12SpeechEngine0A22TranscriptionProcessorC s5ErrorP
+ _symbolic _____ 12SpeechEngine0A30TranscriptionProcessingOptionsV
+ _symbolic _____IeAgHr_ 12SpeechEngine0A18TokenPostProcessorC
+ _symbolic _____y__________G s17_NativeDictionaryV 12SpeechEngine12SystemConfigO20DetokenizerModelTypeO 10Foundation3URLV
- _OUTLINED_FUNCTION_369
- _OUTLINED_FUNCTION_370
- _OUTLINED_FUNCTION_371
- _OUTLINED_FUNCTION_372
- _OUTLINED_FUNCTION_373
- _OUTLINED_FUNCTION_374
- _OUTLINED_FUNCTION_375
- _OUTLINED_FUNCTION_376
- ___swift_closure_destructor.385Tm
- ___swift_closure_destructor.43Tm
- ___swift_closure_destructor.517Tm
- ___swift_closure_destructor.97Tm
- ___swift_memcpy185_8
- ___swift_memcpy232_8
- ___swift_memcpy96_8
- _symbolic _____Sg 12SpeechEngine0A22TranscriptionProcessorC
- _symbolic _____Sgz_Xx 12SpeechEngine0A22TranscriptionProcessorC
- _symbolic _____ySSG s10ArraySliceV
CStrings:
+ " ms  [accumulated retriever inference time]"
+ " ms  [max single Retriever.run]"
+ " ms  [retrieverTime / callCount]"
+ "%s: finish: adding %ld padding elements to %ld written elements to reach multiple of %ld elements"
+ "%s: finish: total written elements %ld"
+ "Final shortlist: %{sensitive}s, size: %{public}ld, retrievalCallCount: %{public}ld, accumulatedRetrieverMs: %{public}f"
+ "Model does not expect %s; skipping Gumbel noise preparation."
+ "Model expects gumbel_noise but gumbelFile is not configured"
+ "Model expects gumbel_noise but gumbelNoiseValues is nil"
+ "Retriever avg/call: "
+ "Retriever peak/call:"
+ "Retriever time:     "
+ "Tokenizer reset triggered at %ld ms"
+ "accumulated retriever inference time (Retriever.run)"
+ "aggregatedRetrievalLatencyMs"
+ "max duration of a single Retriever.run call"
+ "retrieverAvgCallMs"
+ "retrieverPeakCallMs"
+ "retrieverTime / retriever call count"
+ "retrieverTimeMs"
+ "retrieverValidInputCount"
+ "writePaddingChunkSize requires paddingProvider"
- " tokens at a time."
- "AudioTokenizer: endAudio: Adding %ld padding samples to %ld received samples to reach multiple of %ld samples"
- "Final shortlist: %{sensitive}s, size: %{public}ld"
- "Remove unrecognized command: %{private}s"
- "Tokenizer silence reset triggered at %ld ms"
- "Tokenizer time reset triggered at %ld ms"
- "Transcribe only the words heard in the audio. The audio might include the words"
```
