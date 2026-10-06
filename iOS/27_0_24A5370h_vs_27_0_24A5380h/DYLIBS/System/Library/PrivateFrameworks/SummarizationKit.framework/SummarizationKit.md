## SummarizationKit

> `/System/Library/PrivateFrameworks/SummarizationKit.framework/SummarizationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16fcd0` | `0x1732f8` | **`+0x3628`** |
| `__TEXT.__unwind_info` | `0x4968` | `0x4d78` | **`+0x410`** |
| `__DATA_DIRTY.__bss` | `0x5480` | `0x5880` | **`+0x400`** |
| `__TEXT.__oslogstring` | `0x5015` | `0x5365` | **`+0x350`** |
| `__DATA.__bss` | `0x38f0` | `0x35f0` | **`-0x300`** |
| `__DATA_DIRTY.__data` | `0x4b20` | `0x4d90` | **`+0x270`** |
| `__TEXT.__cstring` | `0x59ba` | `0x5bfa` | **`+0x240`** |
| `__DATA.__data` | `0xc90` | `0xa58` | **`-0x238`** |
| `__TEXT.__const` | `0xa6a8` | `0xa7d0` | **`+0x128`** |
| `__TEXT.__swift5_reflstr` | `0x3488` | `0x3518` | **`+0x90`** |
| `__AUTH.__data` | `0x5a8` | `0x630` | **`+0x88`** |
| `__TEXT.__swift_as_cont` | `0x974` | `0x8f0` | **`-0x84`** |
| `__TEXT.__swift5_typeref` | `0x242c` | `0x2488` | **`+0x5c`** |
| `__TEXT.__eh_frame` | `0xc658` | `0xc600` | **`-0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x25fc` | `0x2654` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0x1f98` | `0x1fe8` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x5a70` | `0x5ac0` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x1fcc` | `0x1ff4` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x15d0` | `0x15f8` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x2098` | `0x20b8` | **`+0x20`** |
| `__DATA_DIRTY.__common` | `0x3a8` | `0x3c8` | **`+0x20`** |
| `__DATA.__common` | `0x68` | `0x49` | **`-0x1f`** |
| `__DATA_CONST.__got` | `0xbb8` | `0xba8` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a8` | `0x1b8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x520` | `0x528` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x214` | `0x218` | **`+0x4`** |

### Other Changes

```diff

-15.0.0.0.0
+18.0.0.0.0

-  Functions: 6450
-  Symbols:   1242
-  CStrings:  561
+  Functions: 6460
+  Symbols:   1251
+  CStrings:  578
Symbols:
+ ___swift_closure_destructor.195Tm
+ ___swift_closure_destructor.203Tm
+ ___swift_closure_destructor.49Tm
+ ___swift_closure_destructor.59Tm
+ ___swift_closure_destructor.62Tm
+ ___swift_closure_destructor.91Tm
+ ___swift_closure_destructor.97Tm
+ ___swift_mutable_project_boxed_opaque_existential_1
+ ___unnamed_67
+ _associated conformance 16SummarizationKit19ModelBundleOverrideVSHAASQ
+ _os_variant_has_internal_content
+ _swift_projectBox
+ _swift_unexpectedError
+ _symbolic SS_SSt
+ _symbolic _____ 16SummarizationKit19ModelBundleOverrideV
+ _symbolic _____Sg 16GenerativeModels23StringResponseSanitizerV
+ _symbolic _____Sg 16SummarizationKit19ModelBundleOverrideV
+ _symbolic _____ySDy_____yx_G_____y__________yx_GGGG 15Synchronization5MutexVAARi_zrlE 16SummarizationKit12SessionCacheC0F3Key33_04EA96F85C05F791A74FA4ED814E38A2LLV 19CollectionsInternal17OrderedDictionaryV 10Foundation4UUIDV AF0F5EntryAHLLV
+ _symbolic _____ySS_SStG s23_ContiguousArrayStorageC
+ _symbolic _____y_____SgG s9TaskLocalC 16SummarizationKit28FactualConsistencyClassifierC
- ___swift_closure_destructor.200Tm
- ___swift_closure_destructor.207Tm
- ___swift_closure_destructor.64Tm
- ___swift_closure_destructor.67Tm
- ___swift_closure_destructor.95Tm
- ___swift_closure_destructor.96Tm
- ___unnamed_66
- _get_type_metadata 15Synchronization5MutexVy4Sage27SummarySafetyClassificationVSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDys8Sendable_s10AnyKeyPathCXcsAD_pGG noncopyable
- _get_type_metadata 16SummarizationKit7SessionRzl15Synchronization5MutexVySDyAA0C5CacheC0F3Key33_04EA96F85C05F791A74FA4ED814E38A2LLVyx_G19CollectionsInternal17OrderedDictionaryVy10Foundation4UUIDVAG0F5EntryAILLVyx_GGGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "\n--------------------------------------------------------------------------------\n"
+ "\n--------------------------------------------------------------------------------\n# Inference details for summarization request %{public}s\n--------------------------------------------------------------------------------\n%{public}sAdapter: %{public}s\n%{public}s%{public}sTokenizer: %{public}s\nBase Model: %{public}s\nDraft Model: %{public}s\nDevice Locale: %{public}s\nInference Locale: %{public}s\n--------------------------------------------------------------------------------\n# Decoding Parameters\n--------------------------------------------------------------------------------\nmaximumTokens: %{public}s\nstrategy: %{public}s\ntemperature: %{public}s\nrandomSeed: %{public}s\ntimeout: %{public}s\npromptLookupDraftSteps: %{public}s\n--------------------------------------------------------------------------------"
+ "** MODEL BUNDLE OVERRIDE ACTIVE **\nBase URL: "
+ ".modelBundleOverride is not supported by PromptTemplate extensions"
+ ".modelBundleOverride("
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SummarizationKit/SummarizationKit/Internal/Extensions/TokenGenerator+Extensions.swift"
+ "Failed to create model bundle for model bundle override."
+ "Model bundle override '%{public}s': baseURL must be a valid HTTPS URL, got '%{public}s'"
+ "Model bundle override '%{public}s': missing baseURL"
+ "Model bundle override '%{public}s': missing modelName"
+ "Model bundle override '%{public}s': missing notaryToken"
+ "Model bundle override in effect: baseURL=%{public}s, modelName=%{public}s"
+ "Model bundle override requires a system prompt override for instructionID %{public}s"
+ "Model bundle override requires a user-turn template override for templateID %{public}s"
+ "Model bundle override requires turn-based prompt type"
+ "OpenAI-Compatible-Custom-Routing:"
+ "SummarizationKit/ModelBundleOverride.swift"
+ "User-turn template override active: modelBundleIdentifier=%{public}s, templateID=%{public}s, override=\"%{private}s\""
+ "additionalRequestParameters"
+ "header_Authorization"
+ "userTurnTemplateOverrides"
- "\n--------------------------------------------------------------------------------\n# Inference details for summarization request %{public}s\n--------------------------------------------------------------------------------\nAdapter: %{public}s\n%{public}s%{public}sTokenizer: %{public}s\nBase Model: %{public}s\nDraft Model: %{public}s\nDevice Locale: %{public}s\nInference Locale: %{public}s\n--------------------------------------------------------------------------------\n# Decoding Parameters\n--------------------------------------------------------------------------------\nmaximumTokens: %{public}s\nstrategy: %{public}s\ntemperature: %{public}s\nrandomSeed: %{public}s\ntimeout: %{public}s\npromptLookupDraftSteps: %{public}s\n--------------------------------------------------------------------------------"
- "SummarizationKit/PriorityModelSession.swift"
- "SummarizationKit/SummarizationSession.swift"
- "serverTextSummarizer_V2"
```
