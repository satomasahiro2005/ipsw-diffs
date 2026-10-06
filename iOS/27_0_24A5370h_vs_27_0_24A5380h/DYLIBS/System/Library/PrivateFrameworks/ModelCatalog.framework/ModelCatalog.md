## ModelCatalog

> `/System/Library/PrivateFrameworks/ModelCatalog.framework/ModelCatalog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4291b8` | `0x42fa0c` | **`+0x6854`** |
| `__AUTH_CONST.__const` | `0xc6eb0` | `0xc91d8` | **`+0x2328`** |
| `__TEXT.__cstring` | `0x4945e` | `0x4a35e` | **`+0xf00`** |
| `__DATA.__bss` | `0x4f000` | `0x4f780` | **`+0x780`** |
| `__TEXT.__eh_frame` | `0x2bcbc` | `0x2c354` | **`+0x698`** |
| `__TEXT.__unwind_info` | `0x107a8` | `0x10d60` | **`+0x5b8`** |
| `__DATA_DIRTY.__bss` | `0xaf80` | `0xab00` | **`-0x480`** |
| `__TEXT.__const` | `0x2f16c` | `0x2f52c` | **`+0x3c0`** |
| `__TEXT.__swift5_capture` | `0x1007c` | `0x103dc` | **`+0x360`** |
| `__TEXT.__swift5_fieldmd` | `0xdc78` | `0xdd28` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x63bf` | `0x646f` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0xd048` | `0xd0c0` | **`+0x78`** |
| `__AUTH.__data` | `0x9040` | `0x90a0` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x68b8` | `0x68f8` | **`+0x40`** |
| `__DATA.__data` | `0x7098` | `0x7058` | **`-0x40`** |
| `__DATA_DIRTY.__data` | `0x21b0` | `0x21f0` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x1ae0` | `0x1b10` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x9008` | `0x902e` | **`+0x26`** |
| `__DATA_CONST.__const` | `0x1bb8` | `0x1bd8` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x2e0c` | `0x2e24` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xf48` | `0xf40` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0xda0` | `0xda8` | **`+0x8`** |

### Other Changes

```diff

-295.0.1.0.0
+298.3.0.0.0

-  Functions: 34207
-  Symbols:   267
-  CStrings:  4753
+  Functions: 34406
+  Symbols:   266
+  CStrings:  4805
Symbols:
- _swift_willThrowTypedImpl
CStrings:
+ "ASRNaturalDictationSpeechInputDenyList"
+ "FitnessIntelligence.WorkoutVoice.Companion.TTSAlert"
+ "FitnessIntelligence.WorkoutVoice.TTSAlert"
+ "InstructFMApiGeneric1B"
+ "InstructFMApiGeneric2B"
+ "InstructFMApiGeneric3B"
+ "Invalid configuration for com.apple.fm.language.instruct_3b.fm_api_generic_1b: "
+ "Invalid configuration for com.apple.fm.language.instruct_3b.fm_api_generic_2b: "
+ "Invalid configuration for com.apple.fm.language.instruct_3b.fm_api_generic_3b: "
+ "Invalid configuration for com.apple.fm.language.instruct_server_v2.lw_planner_upgradeable: "
+ "Invalid configuration for com.apple.fm.language.instruct_server_v2.mail_draft_generation: "
+ "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.anfr_encoder_stylized: "
+ "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.personalization_stylized: "
+ "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.text_guided_edit_large_image.image_tokenizer: "
+ "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.text_guided_edit_large_image.noise_predictor: "
+ "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.text_guided_edit_large_image.text_encoder: "
+ "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.text_guided_edit_large_image.tokenizer: "
+ "Invalid configuration for com.apple.gm.safety_deny.input.asr_natural_dictation_speech: "
+ "Invalid configuration for com.apple.gm.safety_deny.input.mail_draft_generation.composition.payload: "
+ "Invalid configuration for com.apple.gm.safety_deny.input.mail_draft_generation.composition: "
+ "Invalid configuration for com.apple.gm.safety_deny.output.mail_draft_generation.composition: "
+ "LLMBundle safetyAdapter is wrong type"
+ "LWPlannerUpgradeable"
+ "MailDraftGenerationCompositionInputDenyList"
+ "MailDraftGenerationCompositionOutputDenyList"
+ "MailDraftGenerationCompositionPayloadDenyList"
+ "ServerDiffusionANFREncoderStylized"
+ "ServerDiffusionPersonalizationStylized"
+ "ServerDiffusionTextGuidedEditLargeImageImageTokenizer"
+ "ServerDiffusionTextGuidedEditLargeImageNoisePredictor"
+ "ServerDiffusionTextGuidedEditLargeImageTextEncoder"
+ "ServerDiffusionTextGuidedEditLargeImageTokenizer"
+ "ServerV2MailDraftGeneration"
+ "SubscriptionOptimizerTimingModels"
+ "VisualGeneration.ImagePlayground.SheetAPI.Creation.Base.1p"
+ "VisualGeneration.ImagePlayground.SheetAPI.Creation.Base.3p"
+ "VisualGeneration.ImagePlayground.SheetAPI.Creation.Personalized.1p"
+ "VisualGeneration.ImagePlayground.SheetAPI.Creation.Personalized.3p"
+ "VisualGeneration.ImagePlayground.SheetAPI.ImageWand.1p"
+ "allowVisualIntelligence"
+ "child"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_1b"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_1b.generic_sparse"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_1b?variant=generic_sparse"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_2b"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_2b.generic_sparse"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_2b?variant=generic_sparse"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_3b"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_3b.generic_sparse"
+ "com.apple.fm.language.instruct_3b.fm_api_generic_3b?variant=generic_sparse"
+ "com.apple.fm.language.instruct_server_v2.lw_planner_upgradeable"
+ "com.apple.fm.language.instruct_server_v2.mail_draft_generation"
+ "com.apple.fm.visual.server_diffusion_v1.anfr_encoder_stylized"
+ "com.apple.fm.visual.server_diffusion_v1.personalization_stylized"
+ "com.apple.fm.visual.server_diffusion_v1.text_guided_edit_large_image"
+ "com.apple.fm.visual.server_diffusion_v1.text_guided_edit_large_image.image_tokenizer"
+ "com.apple.fm.visual.server_diffusion_v1.text_guided_edit_large_image.noise_predictor"
+ "com.apple.fm.visual.server_diffusion_v1.text_guided_edit_large_image.text_encoder"
+ "com.apple.fm.visual.server_diffusion_v1.text_guided_edit_large_image.tokenizer"
+ "com.apple.gm.safety_deny.input.asr_natural_dictation_speech"
+ "com.apple.gm.safety_deny.input.asr_natural_dictation_speech.generic"
+ "com.apple.gm.safety_deny.input.mail_draft_generation.composition"
+ "com.apple.gm.safety_deny.input.mail_draft_generation.composition.generic"
+ "com.apple.gm.safety_deny.input.mail_draft_generation.composition.payload"
+ "com.apple.gm.safety_deny.input.mail_draft_generation.composition.payload.generic"
+ "com.apple.gm.safety_deny.output.mail_draft_generation.composition"
+ "com.apple.gm.safety_deny.output.mail_draft_generation.composition.generic"
+ "gatedByUseCaseAccess"
+ "gated_by_use_case_access"
+ "safetyAdapterVariant"
+ "teen"
- "VisualGeneration.ImagePlaygroundSheetAPI.Creation.Base.1p"
- "VisualGeneration.ImagePlaygroundSheetAPI.Creation.Base.3p"
- "VisualGeneration.ImagePlaygroundSheetAPI.Creation.Personalized.1p"
- "VisualGeneration.ImagePlaygroundSheetAPI.Creation.Personalized.3p"
- "VisualGeneration.ImagePlaygroundSheetAPI.ImageWand.1p"
- "com.apple.fm.code.generate_exp.base.generic"
- "com.apple.fm.code.generate_exp.tokenizer.generic"
- "com.apple.fm.code.generate_v1.base.draft.generic"
- "com.apple.fm.code.generate_v1.base.generic"
- "com.apple.fm.code.generate_v1.tokenizer.generic"
- "com.apple.fm.code.generate_v1_ane_3b.base.draft.generic"
- "com.apple.fm.code.generate_v1_ane_3b.base.generic"
- "com.apple.fm.code.generate_v1_ane_3b.tokenizer.generic"
- "com.apple.fm.code.generate_v2.base.generic"
- "com.apple.fm.code.generate_v2.tokenizer.generic"
- "com.apple.fm.code.generate_v3.base.generic"
- "com.apple.fm.code.generate_v3.tokenizer.generic"
- "com.apple.fm.code.generate_v4.base.generic"
- "com.apple.fm.code.generate_v4.tokenizer.generic"
```
