## fm

> `/usr/bin/fm`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa8030` | `0xa8ebc` | **`+0xe8c`** |
| `__TEXT.__eh_frame` | `0x3720` | `0x3914` | **`+0x1f4`** |
| `__TEXT.__cstring` | `0x4faa` | `0x509a` | **`+0xf0`** |
| `__TEXT.__auth_stubs` | `0x2d50` | `0x2d10` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x17f0` | `0x1830` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x2d10` | `0x2ce8` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x660` | `0x688` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x1200` | `0x11d8` | **`-0x28`** |
| `__DATA_CONST.__auth_got` | `0x16b0` | `0x1690` | **`-0x20`** |
| `__TEXT.__const` | `0x3d5c` | `0x3d3c` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0xdc7` | `0xda7` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0xc98` | `0xc80` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0x78` | **`-0x14`** |
| `__TEXT.__swift5_typeref` | `0x1135` | `0x1147` | **`+0x12`** |
| `__DATA.__data` | `0x1f90` | `0x1f80` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x788` | `0x778` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x160` | `0x15c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2.0.51.3.0
+2.0.55.1.102

-  Functions: 1705
-  Symbols:   1093
-  CStrings:  459
+  Functions: 1713
+  Symbols:   1092
+  CStrings:  464
Symbols:
+ _$s16FoundationModels16GenerationSchemaV011makeDynamicD0AA0fcD0VyF
+ _$s16FoundationModels19SystemLanguageModelC12AvailabilityO17UnavailableReasonO13modelNotReadyyA2GmFWC
+ _$s16FoundationModels19SystemLanguageModelC12AvailabilityO17UnavailableReasonO17deviceNotEligibleyA2GmFWC
+ _$s16FoundationModels19SystemLanguageModelC12AvailabilityO17UnavailableReasonO27appleIntelligenceNotEnabledyA2GmFWC
+ _$s16FoundationModels32PrivateCloudComputeLanguageModelC12AvailabilityO17UnavailableReasonO14systemNotReadyyA2GmFWC
+ _$s16FoundationModels32PrivateCloudComputeLanguageModelC12AvailabilityO17UnavailableReasonO17deviceNotEligibleyA2GmFWC
+ _$s16FoundationModels9GenerablePAAE20promptRepresentationAA6PromptVvg
+ _$s16FoundationModels9GenerablePAAE26instructionsRepresentationAA12InstructionsVvg
+ _swift_allocBox
+ _swift_makeBoxUnique
- _$s15Synchronization5_CellVMn
- _$s16FoundationModels19SystemLanguageModelC12AvailabilityO17UnavailableReasonO16errorDescriptionSSvg
- _$s16FoundationModels23DynamicGenerationSchemaV11referenceToACSS_tcfC
- _$s16FoundationModels23DynamicGenerationSchemaV12dependenciesSayACGvg
- _$s16FoundationModels23DynamicGenerationSchemaV4nameSSvg
- _$s16FoundationModels23DynamicGenerationSchemaV4walk04jsonE4JSONACSS_tKFZ
- _$s16FoundationModels29ConvertibleToGeneratedContentPAAE20promptRepresentationAA6PromptVvg
- _$s16FoundationModels29ConvertibleToGeneratedContentPAAE26instructionsRepresentationAA12InstructionsVvg
- _$s16FoundationModels32PrivateCloudComputeLanguageModelC12AvailabilityO17UnavailableReasonO16errorDescriptionSSvg
- _$sSp12deinitialize5countSvSi_tF
- _$ss6UInt32VMn
CStrings:
+ "Apple Intelligence is not enabled."
+ "Model unavailable."
+ "The model is not available. Try again later."
+ "The system is not ready. Try again later."
+ "This device does not support Apple Intelligence."
```
