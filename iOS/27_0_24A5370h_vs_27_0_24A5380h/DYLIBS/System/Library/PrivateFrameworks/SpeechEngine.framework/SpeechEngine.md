## SpeechEngine

> `/System/Library/PrivateFrameworks/SpeechEngine.framework/SpeechEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11a6cc` | `0x126dd4` | **`+0xc708`** |
| `__DATA_DIRTY.__data` | `0x4f40` | `0x5930` | **`+0x9f0`** |
| `__TEXT.__eh_frame` | `0xd1e8` | `0xdb10` | **`+0x928`** |
| `__TEXT.__const` | `0xddc0` | `0xe1e0` | **`+0x420`** |
| `__TEXT.__cstring` | `0x4feb` | `0x5401` | **`+0x416`** |
| `__AUTH_CONST.__objc_const` | `0x4ae0` | `0x4ef0` | **`+0x410`** |
| `__TEXT.__oslogstring` | `0x3a8f` | `0x3e5f` | **`+0x3d0`** |
| `__TEXT.__unwind_info` | `0x58b8` | `0x5c50` | **`+0x398`** |
| `__TEXT.__swift5_reflstr` | `0x3546` | `0x3876` | **`+0x330`** |
| `__TEXT.__constg_swiftt` | `0x4cf8` | `0x4fa8` | **`+0x2b0`** |
| `__AUTH.__data` | `0xdd0` | `0xb30` | **`-0x2a0`** |
| `__DATA.__bss` | `0x133b0` | `0x13630` | **`+0x280`** |
| `__AUTH_CONST.__const` | `0xbb48` | `0xbd70` | **`+0x228`** |
| `__TEXT.__swift5_fieldmd` | `0x4408` | `0x4618` | **`+0x210`** |
| `__AUTH_CONST.__auth_got` | `0x1778` | `0x18b8` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x36e8` | `0x37ee` | **`+0x106`** |
| `__AUTH.__objc_data` | `0xe8` | `0x48` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x648` | `0x6e8` | **`+0xa0`** |
| `__DATA.__data` | `0x29a0` | `0x2920` | **`-0x80`** |
| `__TEXT.__swift_as_ret` | `0x384` | `0x3fc` | **`+0x78`** |
| `__DATA.__common` | `0x310` | `0x378` | **`+0x68`** |
| `__TEXT.__swift_as_cont` | `0xafc` | `0xb60` | **`+0x64`** |
| `__TEXT.__swift_as_entry` | `0x384` | `0x3e8` | **`+0x64`** |
| `__DATA_DIRTY.__common` | `0x160` | `0x198` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x9d0` | `0x9e8` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x444` | `0x45c` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x1a4` | `0x1b8` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x1f8` | `0x208` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1b0` | `0x1c0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d8` | `0x3e0` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x19f0` | `0x19e8` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x58` | `0x60` | **`+0x8`** |

### Other Changes

```diff

-3600.60.1.0.0
+3600.69.1.0.0

+  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels

-  Functions: 8608
-  Symbols:   2265
-  CStrings:  843
+  Functions: 8931
+  Symbols:   2307
+  CStrings:  879
Symbols:
+ _BNNSGraphContextDestroy_v2
+ _BNNSGraphContextExecute_v2
+ _BNNSGraphContextGetWorkspaceSize_v2
+ _BNNSGraphContextMake
+ _BNNSGraphContextSetDynamicShapes_v2
+ _OUTLINED_FUNCTION_338
+ _OUTLINED_FUNCTION_339
+ _OUTLINED_FUNCTION_340
+ _OUTLINED_FUNCTION_341
+ __DATA__TtC12SpeechEngine25OneShotASRBackboneSession
+ __DATA__TtC12SpeechEngine32StreamingInputASRBackboneSession
+ __IVARS__TtC12SpeechEngine25OneShotASRBackboneSession
+ __IVARS__TtC12SpeechEngine32StreamingInputASRBackboneSession
+ __METACLASS_DATA__TtC12SpeechEngine25OneShotASRBackboneSession
+ __METACLASS_DATA__TtC12SpeechEngine32StreamingInputASRBackboneSession
+ ___swift_closure_destructor.160Tm
+ ___swift_closure_destructor.178Tm
+ ___swift_closure_destructor.200Tm
+ ___swift_closure_destructor.375Tm
+ ___swift_closure_destructor.507Tm
+ ___swift_closure_destructor.97Tm
+ ___swift_memcpy136_8
+ ___swift_memcpy185_8
+ ___swift_memcpy232_8
+ ___swift_memcpy456_8
+ ___swift_memcpy96_8
+ _accelerate_bnns_graph_dictation_dynamic_retriever_set_text_length
+ _associated conformance 12SpeechEngine15ASRBackboneKindOSHAASQ
+ _swift_getDynamicType
+ _swift_projectBox
+ _symbolic $s12SpeechEngine18ASRBackboneSessionP
+ _symbolic SaySdGSg
+ _symbolic ScsySS______pG s5ErrorP
+ _symbolic Scsy___________pG 15TokenGeneration29DictationStreamingDecodeEventV s5ErrorP
+ _symbolic _____ 12SpeechEngine11PreferencesV18SamplingParametersV
+ _symbolic _____ 12SpeechEngine14InputSanitizerV
+ _symbolic _____ 12SpeechEngine15ASRBackboneKindO
+ _symbolic _____ 12SpeechEngine25OneShotASRBackboneSessionC
+ _symbolic _____ 12SpeechEngine27InputSanitizerConfigurationV
+ _symbolic _____ 12SpeechEngine32StreamingInputASRBackboneSessionC
+ _symbolic _____ 15TokenGeneration31DictationStreamingPromptRequestC
+ _symbolic _____ 16GenerativeModels29StringRenderedPromptSanitizerV
+ _symbolic _____Sg 12SpeechEngine14InputSanitizerV
+ _symbolic _____Sg 12SpeechEngine15ASRBackboneKindO
+ _symbolic _____Sg 12SpeechEngine16FeatureExtractorC
+ _symbolic _____Sg 15TokenGeneration29DictationStreamingDecodeEventV
+ _symbolic _____Sg 16GenerativeModels29StringRenderedPromptSanitizerV10GuardrailsV
+ _symbolic _____Sg s5Int32V
+ _symbolic _____Sg s5Int64V
+ _symbolic _____SgyYaKc 15TokenGeneration29DictationStreamingDecodeEventV
+ _symbolic ______pSg 12ModelCatalog18TokenInputDenyListP
+ _symbolic _____ySS______p_G Scs12ContinuationV s5ErrorP
+ _symbolic _____ySS______p_G Scs8IteratorV s5ErrorP
+ _symbolic _____ySS______p__G Scs12ContinuationV11YieldResultO s5ErrorP
+ _symbolic _____ySS______p__G Scs12ContinuationV15BufferingPolicyO s5ErrorP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12SpeechEngine27AudioTokenizerResponseEventO
+ _symbolic _____y_____SSG 12SpeechEngine10PreferenceV AA0aB17PreferencesDomainO
+ _symbolic _____y___________p_G Scs8IteratorV 15TokenGeneration29DictationStreamingDecodeEventV s5ErrorP
+ _symbolic _____y_____ySf_G______p_GSg Scs8IteratorV 12SpeechEngine23AsyncThrowingDataStreamC6OutputO s5ErrorP
+ _tensor_size_in_bytes
+ _type_layout_string 12SpeechEngine11PreferencesV18SamplingParametersV
+ _update_tensor_shape_and_allocate_memory
- ___swift_closure_destructor.161Tm
- ___swift_closure_destructor.179Tm
- ___swift_closure_destructor.201Tm
- ___swift_closure_destructor.376Tm
- ___swift_closure_destructor.508Tm
- ___swift_closure_destructor.63Tm
- ___swift_memcpy112_8
- ___swift_memcpy248_8
- ___swift_memcpy320_8
- _get_enum_tag_for_layout_string 12SpeechEngine15ShortlistConfigVSg
- _get_type_metadata 15Synchronization5MutexVy12SpeechEngine0C21RecognizerAudioBufferC5State33_99DE25260918DD8DF03927C442D67CC9LLVG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic $s12SpeechEngine16MetricsReportingP
- _symbolic B0
- _symbolic _____Sg 12SpeechEngine0A18RecognitionMetricsC
- _symbolic _____Sg 12SpeechEngine15ShortlistConfigV
- _symbolic _____Sg_ABt 12SpeechEngine15ShortlistConfigV
- _symbolic _____XDXMT 12SpeechEngine14AudioTokenizerC
- _symbolic _____y_____G s23_ContiguousArrayStorageC 12SpeechEngine11TokenBufferC6OutputO
- _symbolic _____yxGSg 12SpeechEngine17ContextParametersV
CStrings:
+ "AudioInputStream not available after initialization"
+ "AudioTokenizer.%s: Total added frames %ld, removed frames %ld"
+ "AudioTokenizer.%s: Total added tokens %lu, removed tokens %lu"
+ "AudioTokenizer: Total added tokens %lu, removed tokens %lu"
+ "Configured OnDeviceAFM with sampling parameters: strategy:%s and temperature:%s"
+ "Done Serial AFM Inference"
+ "Error setting dictation dynamic retriever text length to %ld: %d"
+ "Failed to allocate dynamic retriever workspace of %zu Bytes\n"
+ "Failed to allocate shapes memory\n"
+ "Failed to allocate tensor data for tensor text of %zu Bytes\n"
+ "Failed to create context\n"
+ "Failed to get tensor for argument %zu\n"
+ "Failed to set dictation dynamic retriever text length"
+ "InputSanitizer modelUseCaseID is nil"
+ "InputSanitizer onBehalfOfPID is nil"
+ "InputSanitizer run cancelled"
+ "InputSanitizer run failed with error: %s"
+ "OneShotASRBackboneSession: first systemComponent must be the system prompt string"
+ "OneShotASRBackboneSession: ignoring non-token event: %s"
+ "Pause durations:    ["
+ "Proposed shortlist before sanitization: %{sensitive}s"
+ "Running step: numToks=%ld, dataSize=%ld"
+ "SamplingStrategyType"
+ "Sanitizer changed shortlist: %{sensitive}s != input: %{sensitive}s"
+ "Sanitizer failed or rejected shortlist: %{sensitive}s"
+ "Sanitizer output is empty, : %{sensitive}s"
+ "Serial decodeFrom: resetFrequencyMs=%ld flushWaitMs=%ld chunkSizeTokens=%ld"
+ "Should never receive discardCompletedWithFloatArrayPayload from featureStream"
+ "Should never receive flushCompletedWithFloatArrayPayload from featureStream"
+ "Silence reset triggered after %ld silent chunks"
+ "Skipping sanitization of shortlist since inputSanitizer is nil"
+ "SpeechEngine/SpeechRecognizer/UseOneShotBackbone"
+ "StrategyTopKCount"
+ "StrategyTopPValue"
+ "StreamingDecoder.streamingInput backbone requires afmConfig but none was provided"
+ "StreamingDecoder: Dropping %ld remaining tokens after serial decode loop. This should never happen."
+ "TemperatureValue"
+ "Time reset triggered as segment duration reached %ld ms"
+ "Tokenizer silence reset triggered at %ld ms"
+ "Tokenizer time reset triggered at %ld ms"
+ "Unexpected event from audioInputStream in serial mode"
+ "[step] audioRange=%ld-%ldms  inToks=%ld  outToks=%ld  dur=%sms  tokens=%{sensitive}s"
+ "dictation retriever failed to set dynamic shapes\n"
+ "missing text tensor\n"
+ "pauseDurationsSec"
+ "per pause-resume cycle: (resumeSampleCount - pauseSampleCount) / samplingRate"
+ "processNextBatch()"
+ "processNextBatch() not supported by this tokenizer"
+ "resetSerialProcessingState()"
+ "resetSerialProcessingState() not supported by this tokenizer"
+ "runStepBody: drain loop exited sawStepEnd=%{bool}d events=%ld"
+ "runStepBody: drain threw %@"
+ "runStepBody: received isStepEnd after %ld events; breaking"
+ "scores"
+ "setupForSerialProcessing() must be called before processNextBatch()"
+ "setupForSerialProcessing() not supported by this tokenizer"
+ "tetx length of %d is wrong\n"
+ "text_lengths"
- "AudioTokenizer task cancelled"
- "AudioTokenizer: Total added tokens %lu, removed tokens %ld"
- "Compacting: holes(%ldb) > live(%ldb)"
- "Done Chunked AFM Inference"
- "Failed to read from Tokenizer: %@"
- "Not append shortlist: %s"
- "Padding token chunk with zeros from %ld to %ld"
- "Retrieval data is missing"
- "Running AFM Inference: numToks=%ld, dataSize=%ld"
- "Should never receive discardCompletedWithFloatArrayPayload from localFeatureStream"
- "Should never receive flushCompletedWithFloatArrayPayload from localFeatureStream"
- "SpeechEngine/CumulativeTokenBuffer.swift"
- "SpeechEngine/TokenBuffer.swift"
- "StreamingDecoder: Ignoring chunk with different size. This should never happen."
- "[AFM chunk] audioRange=%ld-%ldms  inToks=%ld  outToks=%ld  dur=%sms  tokens=%{sensitive}s"
- "other afmEvent: %s"
- "other tokEvent: %s"
- "resetFrequencyMs=%ld flushWaitMs=%ld chunkSizeTokens=%ld"
- "shortlist config is nil"
- "switchS1 token not available"
- "waitForTokens(chunkSize:audioTokenChunkingMode:)"
- "waitForTokens(chunkSize:audioTokenChunkingMode:pad:)"
```
