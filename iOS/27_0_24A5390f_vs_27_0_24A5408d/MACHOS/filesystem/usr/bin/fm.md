## fm

> `/usr/bin/fm`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbe35c` | `0xc0d6c` | **`+0x2a10`** |
| `__DATA_CONST.__const` | `0x30b0` | `0x32d8` | **`+0x228`** |
| `__DATA.__bss` | `0x5180` | `0x5300` | **`+0x180`** |
| `__DATA.__objc_const` | `0xcd0` | `0xdc8` | **`+0xf8`** |
| `__TEXT.__const` | `0x405c` | `0x412c` | **`+0xd0`** |
| `__DATA.__data` | `0x20b8` | `0x2180` | **`+0xc8`** |
| `__TEXT.__eh_frame` | `0x3ea0` | `0x3f48` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x5ada` | `0x5b6a` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0xd08` | `0xd84` | **`+0x7c`** |
| `__TEXT.__swift5_fieldmd` | `0x13bc` | `0x1434` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x19b8` | `0x1a30` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0x12a9` | `0x1303` | **`+0x5a`** |
| `__TEXT.__swift5_reflstr` | `0x1046` | `0x1096` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x3190` | `0x31d0` | **`+0x40`** |
| `__DATA_CONST.__auth_ptr` | `0x7d8` | `0x800` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x18d0` | `0x18f0` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x141` | `0x161` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x260` | `0x240` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x2c8` | `0x2d4` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x164` | `0x170` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x138` | `0x130` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1a4` | `0x1a8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-2.0.63.0.0
+2.0.68.1.101

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

+  - /usr/lib/swift/libswift_DarwinFoundation1.dylib

-  Functions: 1819
-  Symbols:   1203
-  CStrings:  509
+  Functions: 1852
+  Symbols:   1210
+  CStrings:  516
Symbols:
+ _$s12FeatureFlags02isA7EnabledySbAA0aB3Key_pF
+ _$s12FeatureFlags0aB3KeyMp
+ _$s12FeatureFlags0aB3KeyP6domains12StaticStringVvgTq
+ _$s12FeatureFlags0aB3KeyP7features12StaticStringVvgTq
+ _$s16FoundationModels10TranscriptV8ToolCallV2id8metadata8toolName12rawArgumentsAESS_SDySSAA29ConvertibleToGeneratedContent_pGS2StKcfC
+ _$s16FoundationModels20LanguageModelSessionC27GenerationStepConfigurationV16generationSchema0I7Options07contextK08metadataAeA0fJ0VSg_AA0fK0VAA07ContextK0VSDySSAA29ConvertibleToGeneratedContent_pGtcfC
+ _$s16FoundationModels20LanguageModelSessionC5UsageV5input6output8metadataA2E5InputV_AE6OutputVSDySSAA29ConvertibleToGeneratedContent_pGtcfC
+ _$s16FoundationModels21ChatCompletionsClientV0C7MessageV9hashValueSivg
+ _$s6Darwin4openys5Int32VSPys4Int8VG_ADtF
+ _$s6Darwin5errnos5Int32Vvg
- _$s16FoundationModels10TranscriptV8ToolCallV2id8metadata8toolName12rawArgumentsAESS_SDySSSe_SESQs8SendablepGS2StKcfC
- _$s16FoundationModels20LanguageModelSessionC27GenerationStepConfigurationV16generationSchema0I7Options07contextK08metadataAeA0fJ0VSg_AA0fK0VAA07ContextK0VSDySSSe_SESQs8SendablepGtcfC
- _$s16FoundationModels20LanguageModelSessionC5UsageV5input6output8metadataA2E5InputV_AE6OutputVSDySSSe_SESQs8SendablepGtcfC
CStrings:
+ "/dev/tty"
+ "Private Cloud Compute is not available in this context. Please use "
+ "The 'messages' array must not be empty."
+ "_TtC2fm12PCCModelPool"
+ "capacity"
+ "entries"
+ "pccGatekeeperV2"
+ "pccModelPool"
+ "the Terminal app."
- "PCC inference is not available in this context."
- "fileHandleForWritingAtPath:"
```
