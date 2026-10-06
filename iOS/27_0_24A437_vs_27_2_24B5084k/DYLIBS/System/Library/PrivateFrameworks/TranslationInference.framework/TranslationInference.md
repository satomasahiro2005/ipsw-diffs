## TranslationInference

> `/System/Library/PrivateFrameworks/TranslationInference.framework/TranslationInference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80e20` | `0x898fc` | **`+0x8adc`** |
| `__TEXT.__const` | `0x3af8` | `0x3fd8` | **`+0x4e0`** |
| `__DATA.__bss` | `0x45a0` | `0x49a0` | **`+0x400`** |
| `__TEXT.__eh_frame` | `0x3ca8` | `0x3f70` | **`+0x2c8`** |
| `__TEXT.__swift5_fieldmd` | `0x1264` | `0x148c` | **`+0x228`** |
| `__TEXT.__swift5_reflstr` | `0x12bd` | `0x149d` | **`+0x1e0`** |
| `__AUTH_CONST.__const` | `0x2c98` | `0x2e10` | **`+0x178`** |
| `__TEXT.__unwind_info` | `0x17a8` | `0x1908` | **`+0x160`** |
| `__TEXT.__constg_swiftt` | `0xe34` | `0xf88` | **`+0x154`** |
| `__TEXT.__swift5_typeref` | `0x1580` | `0x167a` | **`+0xfa`** |
| `__TEXT.__cstring` | `0x175e` | `0x182e` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0x1e8` | `0x2b8` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0xf2d` | `0xfed` | **`+0xc0`** |
| `__DATA.__data` | `0x8d8` | `0x970` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0xbf8` | `0xbb8` | **`-0x40`** |
| `__TEXT.__swift5_proto` | `0x268` | `0x29c` | **`+0x34`** |
| `__DATA.__common` | `0x50` | `0x80` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x210` | `0x240` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x5a8` | `0x5d0` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0x1400` | `0x13d8` | **`-0x28`** |
| `__TEXT.__swift_as_cont` | `0x290` | `0x2b4` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0x11e0` | `0x1200` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x120` | `0x13c` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0xc8` | `0xe0` | **`+0x18`** |
| `__DATA_DIRTY.__common` | `0xd8` | `0xc0` | **`-0x18`** |
| `__TEXT.__swift_as_ret` | `0x120` | `0x130` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xc4` | `0xd0` | **`+0xc`** |
| `__AUTH.__data` | `0x550` | `0x558` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x28` | `0x30` | **`+0x8`** |

### Other Changes

```diff

-389.1.0.0.0
+393.1.0.0.0

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftCoreImage.dylib
+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Functions: 1747
-  Symbols:   725
-  CStrings:  251
+  Functions: 1896
+  Symbols:   764
+  CStrings:  260
Symbols:
+ _NSStringTransformToLatin
+ ___swift_exist.box.addr_destructor
+ ___swift_exist.box.addr_destructorTm
+ ___swift_memcpy120_8
+ ___swift_memcpy35_8
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAVFoundation_$_TranslationInference
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreImage_$_TranslationInference
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftCoreMIDI_$_TranslationInference
+ _associated conformance 20TranslationInference0A17ExecutionLocationOSHAASQ
+ _associated conformance 20TranslationInference0A17ExecutionLocationOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 20TranslationInference0A18ModelVersionSourceOSHAASQ
+ _associated conformance 20TranslationInference0A8LanguageVSHAASQ
+ _associated conformance 20TranslationInference0A8ModalityOSHAASQ
+ _associated conformance 20TranslationInference0A8ModalityOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 20TranslationInference0A9ModelTypeOSHAASQ
+ _swift_getExistentialTypeMetadata
+ _swift_release_x12
+ _symbolic $s20TranslationInference0A5ModelP
+ _symbolic $s20TranslationInference13ModelProviderP
+ _symbolic Say_____G 12ModelCatalog17UseCaseIdentifierV
+ _symbolic Say_____G 20TranslationInference0A17ExecutionLocationO
+ _symbolic Say_____G 20TranslationInference0A8ModalityO
+ _symbolic Say______pG 20TranslationInference0A5ModelP
+ _symbolic _____ 20TranslationInference0A17ExecutionLocationO
+ _symbolic _____ 20TranslationInference0A18ModelVersionSourceO
+ _symbolic _____ 20TranslationInference0A8LanguageV
+ _symbolic _____ 20TranslationInference0A8ModalityO
+ _symbolic _____ 20TranslationInference0A9ModelTypeO
+ _symbolic _____ 20TranslationInference12AFMLoRAModelV
+ _symbolic _____ 20TranslationInference12IFPLoRAModelV
+ _symbolic _____ 20TranslationInference13MTExpertModelV
+ _symbolic _____ 20TranslationInference18UnownedBundleModelV
+ _symbolic _____ 20TranslationInference20DefaultModelProviderV
+ _symbolic _____Sg 20TranslationInference0B11AssetStatusV0D0O
+ _symbolic _____Sg 20TranslationInference0B11AssetStatusV7VariantO
+ _symbolic ______p 20TranslationInference0A5ModelP
+ _symbolic _____y_____G s11_SetStorageC 10Foundation6LocaleV
+ _symbolic _____y_____G s11_SetStorageC 12ModelCatalog17UseCaseIdentifierV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 20TranslationInference0D8LanguageV
+ _symbolic _____y______pG s23_ContiguousArrayStorageC 20TranslationInference0D5ModelP
+ _type_layout_string 20TranslationInference12AFMLoRAModelV
+ _type_layout_string 20TranslationInference12IFPLoRAModelV
+ _type_layout_string 20TranslationInference13MTExpertModelV
+ _type_layout_string 20TranslationInference18UnownedBundleModelV
+ _type_layout_string 20TranslationInference20DefaultModelProviderV
- ___swift_memcpy104_8
- _associated conformance 20TranslationInference0A9ModelInfoV0C4TypeOSHAASQ
- _associated conformance 20TranslationInference0B13SessionConfigV16LanguageModalityOSHAASQ
- _associated conformance 20TranslationInference0B13SessionConfigV16LanguageModalityOs12CaseIterableAA8AllCasessAFP_Sl
- _symbolic Say_____G 20TranslationInference0B13SessionConfigV16LanguageModalityO
- _symbolic _____ 20TranslationInference0A9ModelInfoV0C4TypeO
- _symbolic _____ 20TranslationInference0B11AssetStatusV16ModelBundleEntry33_F94B06A51136F8D68580D6CD990CE9FALLV
- _symbolic _____ 20TranslationInference0B13SessionConfigV16LanguageModalityO
- _symbolic _____y_____G s23_ContiguousArrayStorageC 20TranslationInference0E11AssetStatusV16ModelBundleEntry33_F94B06A51136F8D68580D6CD990CE9FALLV
CStrings:
+ "Execution location %{public}s is not available in this build."
+ "No romanization produced for %{public}s: %{sensitive}s"
+ "Romanization"
+ "Skipping romanization, %{public}s is not supported"
+ "SpeechToSpeechNPYAudioFilePath"
+ "SpeechToSpeechSaveDetokenizedAudioToFile"
+ "SpeechToSpeechSaveOutputAudioToNPY"
+ "mt_expert_server"
+ "mt_expert_speech"
+ "on-device"
+ "private-cloud-compute"
+ "romanization_duration_ms"
+ "useCaseIdentifierOverride="
- "afm-lora+unknown"
- "ai_adapter_inference"
- "ifp-lora+unknown"
- "mt-expert+unknown"
```
