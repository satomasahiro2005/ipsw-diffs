## TranslationInference

> `/System/Library/PrivateFrameworks/TranslationInference.framework/TranslationInference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6b3d4` | `0x75cc4` | **`+0xa8f0`** |
| `__TEXT.__eh_frame` | `0x3518` | `0x3af0` | **`+0x5d8`** |
| `__TEXT.__oslogstring` | `0xa91` | `0xddd` | **`+0x34c`** |
| `__AUTH.__data` | `0x718` | `0x8f8` | **`+0x1e0`** |
| `__TEXT.__swift5_reflstr` | `0xffd` | `0x11dd` | **`+0x1e0`** |
| `__TEXT.__const` | `0x3298` | `0x3418` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x1498` | `0x15e0` | **`+0x148`** |
| `__TEXT.__swift5_fieldmd` | `0xfd8` | `0x1104` | **`+0x12c`** |
| `__DATA.__bss` | `0x38a0` | `0x39a0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x14fe` | `0x15fe` | **`+0x100`** |
| `__DATA.__data` | `0x7c0` | `0x888` | **`+0xc8`** |
| `__TEXT.__swift5_typeref` | `0x1282` | `0x134a` | **`+0xc8`** |
| `__AUTH_CONST.__auth_got` | `0x10f8` | `0x11a8` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0xcfc` | `0xd84` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0x23b8` | `0x2428` | **`+0x70`** |
| `__TEXT.__swift_as_cont` | `0x240` | `0x2a8` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0xb78` | `0xbb8` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x4d0` | `0x510` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0xf4` | `0x120` | **`+0x2c`** |
| `__DATA_DIRTY.__data` | `0xf38` | `0xf10` | **`-0x28`** |
| `__DATA.__common` | `0x50` | `0x60` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x1ec` | `0x1fc` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x104` | `0x110` | **`+0xc`** |
| `__DATA_DIRTY.__common` | `0xb8` | `0xb0` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x1fc` | `0x204` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xc4` | `0xc8` | **`+0x4`** |

### Other Changes

```diff

-380.1.0.0.0
+384.1.0.0.0

-  Functions: 1511
-  Symbols:   662
-  CStrings:  212
+  Functions: 1588
+  Symbols:   682
+  CStrings:  231
Symbols:
+ ___swift_memcpy104_8
+ _objc_release_x9
+ _symbolic SaySiG
+ _symbolic _____ 20TranslationInference0A7AdapterC14PreparedPrompt33_87B230FEBB2A1DB2853CA5C3DF6191FBLLO
+ _symbolic _____ 20TranslationInference0B11AssetStatusV16ModelBundleEntry33_F94B06A51136F8D68580D6CD990CE9FALLV
+ _symbolic _____ 20TranslationInference21ResolvedSessionConfigV
+ _symbolic _____ 9PromptKit010CompletionA0V
+ _symbolic _____ 9PromptKit012ChatMessagesA0V
+ _symbolic _____Sg 12ModelCatalog17UseCaseIdentifierV
+ _symbolic _____Sg 12ModelCatalog23LLMAdapterAssetMetadataV34PromptPreprocessingTemplateVersionO
+ _symbolic _____Sg s15ContinuousClockV7InstantV
+ _symbolic _____Sg_ABt 10Foundation3URLV
+ _symbolic _____Sg_ABt 12ModelCatalog23LLMAdapterAssetMetadataV34PromptPreprocessingTemplateVersionO
+ _symbolic ______p 12ModelCatalog0B8ResourceP
+ _symbolic ______p 12ModelCatalog19AssetBackedLLMModelP
+ _symbolic ______pSg 12ModelCatalog14ResourceBundleP
+ _symbolic ______pSg 12ModelCatalog19AssetBackedLLMModelP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 20TranslationInference0E11AssetStatusV16ModelBundleEntry33_F94B06A51136F8D68580D6CD990CE9FALLV
+ _symbolic _____y__________ABG 19GenerativeFunctions0A21ConfigurationRunnableV 9PromptKit010CompletionE0V 15TokenGeneration0H9GeneratorC
+ _symbolic _____y__________G 12ModelCatalog0B5AssetV AA010LLMAdapterC8MetadataV AA0dC8ContentsV
+ _symbolic _____y__________G 12ModelCatalog0B5AssetV AA08LLMModelC8MetadataV AA0dC8ContentsV
+ _symbolic _____y______pG s23_ContiguousArrayStorageC 12ModelCatalog19AssetBackedLLMModelP
- ___swift_memcpy81_8
- _symbolic _____Sg 10Foundation4DateV
CStrings:
+ "Adapter prompt template version: %{public}s"
+ "Bundle %{public}s has no LLM.Model resource; uses_completion_prompt defaults to false"
+ "Bundle %{public}s not found; uses_completion_prompt defaults to false"
+ "Bundle %{public}s uses_completion_prompt: %{bool,public}d"
+ "Failed to resolve bundle %{public}s for uses_completion_prompt: %{public}@"
+ "InferenceSessionConfig("
+ "ResolvedSessionConfig("
+ "Session config: %{public}s"
+ "Session resolved: %{public}s"
+ "Using default decoding parameters (decoding_parameters.json not available at %{public}s)"
+ "Using default decoding parameters (failed to load and decode %{public}s: %{public}@)"
+ "[WARNING] EMTAligner out-of-range source text: %{sensitive}s"
+ "[WARNING] EMTAligner out-of-range target text: %{sensitive}s"
+ "[WARNING] EMTAligner returned out-of-range source indices; dropping them. droppedCount=%{public}ld sourcePieces=%{public}ld targetPieces=%{public}ld badIndices=%{sensitive}s"
+ "audioDetokenizer="
+ "com.apple.MachineTranslation.Translate.full"
+ "speechLanguages="
+ "token_count_call_count"
+ "token_count_duration_ms"
+ "useCaseIdentifier="
+ "uses_completion_prompt"
- "Failed to load decoding parameters from %{public}s: %{public}@. Using defaults."
- "SpeechToSpeechParagraphCompletionHandlingDisabled"
```
