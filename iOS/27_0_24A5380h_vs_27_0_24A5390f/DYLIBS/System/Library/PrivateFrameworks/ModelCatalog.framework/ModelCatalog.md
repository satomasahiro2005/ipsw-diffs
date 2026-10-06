## ModelCatalog

> `/System/Library/PrivateFrameworks/ModelCatalog.framework/ModelCatalog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42fa0c` | `0x40ef24` | **`-0x20ae8`** |
| `__DATA.__bss` | `0x4f780` | `0x4df80` | **`-0x1800`** |
| `__AUTH_CONST.__const` | `0xc91d8` | `0xc7a58` | **`-0x1780`** |
| `__TEXT.__cstring` | `0x4a35e` | `0x48cfe` | **`-0x1660`** |
| `__TEXT.__const` | `0x2f52c` | `0x2e25c` | **`-0x12d0`** |
| `__TEXT.__eh_frame` | `0x2c354` | `0x2b1dc` | **`-0x1178`** |
| `__AUTH.__data` | `0x90a0` | `0x8540` | **`-0xb60`** |
| `__AUTH_CONST.__objc_const` | `0x68f8` | `0x5f18` | **`-0x9e0`** |
| `__TEXT.__swift5_capture` | `0x103dc` | `0xfa2c` | **`-0x9b0`** |
| `__TEXT.__constg_swiftt` | `0xd0c0` | `0xc728` | **`-0x998`** |
| `__TEXT.__swift5_fieldmd` | `0xdd28` | `0xd3dc` | **`-0x94c`** |
| `__TEXT.__unwind_info` | `0x10d60` | `0x10488` | **`-0x8d8`** |
| `__DATA_CONST.__const` | `0x1bd8` | `0x1858` | **`-0x380`** |
| `__TEXT.__swift5_typeref` | `0x902e` | `0x8e3c` | **`-0x1f2`** |
| `__DATA.__data` | `0x7058` | `0x6e68` | **`-0x1f0`** |
| `__TEXT.__swift5_proto` | `0x2e24` | `0x2d64` | **`-0xc0`** |
| `__TEXT.__swift5_assocty` | `0x1b10` | `0x1ab0` | **`-0x60`** |
| `__TEXT.__swift5_reflstr` | `0x646f` | `0x64bf` | **`+0x50`** |
| `__TEXT.__swift5_types` | `0xda8` | `0xd70` | **`-0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x218` | `0x1f8` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x410` | `0x404` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0xf40` | `0xf48` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x280` | `0x278` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x318` | `0x31c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x2dc` | `0x2d8` | **`-0x4`** |

### Other Changes

```diff

-298.3.0.0.0
+302.1.0.2.0

-  Functions: 34406
+  Functions: 33008

-  CStrings:  4805
+  CStrings:  4718
CStrings:
+ "CarKeyDataExtract"
+ "FMFramework.PIP.AppleInternal"
+ "IntelligentRouting.RoomClassification"
+ "Invalid configuration for com.apple.fm.language.instruct_3b.car_key_data_extract.adapter_metadata_override: "
+ "Invalid configuration for com.apple.fm.language.instruct_3b.shared_experts_cost_placeholder_1b: "
+ "Invalid configuration for com.apple.fm.language.instruct_3b.shared_experts_cost_placeholder_2b: "
+ "Invalid configuration for com.apple.fm.language.instruct_3b.shared_experts_cost_placeholder_3b: "
+ "Invalid configuration for com.apple.fm.language.instruct_server_v2.autograder_pro: "
+ "LLM.SharedExpertsCostPlaceholder"
+ "LLMBundle sharedExpertsCostPlaceholder is wrong type"
+ "ServerV2AutograderPro"
+ "SharedExpertsCostPlaceholder1B"
+ "SharedExpertsCostPlaceholder2B"
+ "SharedExpertsCostPlaceholder3B"
+ "com.apple.fm.language.instruct_3b.car_key_data_extract"
+ "com.apple.fm.language.instruct_3b.car_key_data_extract.adapter_metadata_override"
+ "com.apple.fm.language.instruct_3b.car_key_data_extract.adapter_metadata_override.generic"
+ "com.apple.fm.language.instruct_3b.car_key_data_extract.adapter_metadata_override.generic_sparse"
+ "com.apple.fm.language.instruct_3b.car_key_data_extract.adapter_metadata_override?variant=generic_sparse"
+ "com.apple.fm.language.instruct_3b.shared_experts_cost_placeholder_1b"
+ "com.apple.fm.language.instruct_3b.shared_experts_cost_placeholder_1b.generic_sparse"
+ "com.apple.fm.language.instruct_3b.shared_experts_cost_placeholder_1b?variant=generic_sparse"
+ "com.apple.fm.language.instruct_3b.shared_experts_cost_placeholder_2b"
+ "com.apple.fm.language.instruct_3b.shared_experts_cost_placeholder_2b.generic_sparse"
+ "com.apple.fm.language.instruct_3b.shared_experts_cost_placeholder_2b?variant=generic_sparse"
+ "com.apple.fm.language.instruct_3b.shared_experts_cost_placeholder_3b"
+ "com.apple.fm.language.instruct_3b.shared_experts_cost_placeholder_3b.generic_sparse"
+ "com.apple.fm.language.instruct_3b.shared_experts_cost_placeholder_3b?variant=generic_sparse"
+ "com.apple.fm.language.instruct_server_v2.autograder_pro"
+ "sharedExpertsCostPlaceholder"
+ "sharedExpertsCostPlaceholderVariant"
+ "shared_experts_cost_placeholder"
+ "textUnderstanding.CarKeyDataExtraction"
- "ImagePlaygroundEditSuggestionsInputDenyList"
- "ImagePlaygroundEditSuggestionsOutputDenyList"
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.alpha_mask_decoder_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.anfr_encoder_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.autoencoder: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.autoencoder_v10: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.direct_manipulation.small_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.drawing_conditioner.small_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.inpainting.small_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.messages_background.small_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.noise_predictor_v10: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.noise_predictor_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.outpainting.small_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.personalization.small_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.spatial_reframing.small_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.spatial_reframing_vae_decoder_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.textencoder_v10: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.textencoder_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.tokenizer_v10: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.tokenizer_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.up_resolution.small_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.vae_decoder_v11_1: "
- "Invalid configuration for com.apple.fm.visual.server_diffusion_v1.vae_encoder_v11_1: "
- "Invalid configuration for com.apple.gm.safety_deny.input.image_playground.edit_suggestions: "
- "Invalid configuration for com.apple.gm.safety_deny.output.image_playground.edit_suggestions: "
- "ServerDiffusion.AutoEncoder"
- "ServerDiffusionANFREncoderV11_1"
- "ServerDiffusionAlphaMaskDecoderV11_1"
- "ServerDiffusionAutoEncoder"
- "ServerDiffusionAutoEncoderV10"
- "ServerDiffusionBundle safetyPostprocessorAdapter is wrong type"
- "ServerDiffusionBundle safetyPreprocessorAdapter is wrong type"
- "ServerDiffusionDirectManipulationSmallV11_1"
- "ServerDiffusionDrawingConditionerSmallV11_1"
- "ServerDiffusionInpaintingSmallV11_1"
- "ServerDiffusionMessagesBackgroundSmallV11_1"
- "ServerDiffusionNoisePredictorV10"
- "ServerDiffusionNoisePredictorV11_1"
- "ServerDiffusionOutpaintingSmallV11_1"
- "ServerDiffusionPersonalizationSmallV11_1"
- "ServerDiffusionSpatialReframingSmallV11_1"
- "ServerDiffusionSpatialReframingVAEDecoderV11_1"
- "ServerDiffusionTextEncoderV10"
- "ServerDiffusionTextEncoderV11_1"
- "ServerDiffusionTokenizerV10"
- "ServerDiffusionTokenizerV11_1"
- "ServerDiffusionUpResolutionSmallV11_1"
- "ServerDiffusionV10Bundle autoencoder is wrong type"
- "ServerDiffusionV10Bundle missing 'autoencoder' key from json: "
- "ServerDiffusionV10Bundle missing 'noise_predictor' key from json: "
- "ServerDiffusionV10Bundle missing 'textencoder' key from json: "
- "ServerDiffusionV10Bundle missing 'tokenizer' key from json: "
- "ServerDiffusionV10Bundle missing ServerDiffusionAutoEncoder with id "
- "ServerDiffusionV10Bundle missing ServerDiffusionNoisePredictor with id "
- "ServerDiffusionV10Bundle missing ServerDiffusionTextEncoder with id "
- "ServerDiffusionV10Bundle missing ServerDiffusionTokenizer with id "
- "ServerDiffusionV10Bundle noisePredictor is wrong type"
- "ServerDiffusionV10Bundle textencoder is wrong type"
- "ServerDiffusionV10Bundle tokenizer is wrong type"
- "ServerDiffusionV11_1Bundle alphaMaskDecoder is wrong type"
- "ServerDiffusionV11_1Bundle anfrEncoder is wrong type"
- "ServerDiffusionV11_1Bundle diffusionAdapter is wrong type"
- "ServerDiffusionV11_1Bundle missing 'noise_predictor' key from json: "
- "ServerDiffusionV11_1Bundle missing 'textencoder' key from json: "
- "ServerDiffusionV11_1Bundle missing 'tokenizer' key from json: "
- "ServerDiffusionV11_1Bundle missing 'vae_decoder' key from json: "
- "ServerDiffusionV11_1Bundle missing ServerDiffusionNoisePredictor with id "
- "ServerDiffusionV11_1Bundle missing ServerDiffusionTextEncoder with id "
- "ServerDiffusionV11_1Bundle missing ServerDiffusionTokenizer with id "
- "ServerDiffusionV11_1Bundle missing ServerDiffusionVAEDecoder with id "
- "ServerDiffusionV11_1Bundle noisePredictor is wrong type"
- "ServerDiffusionV11_1Bundle safetyAdapterMiscSafety is wrong type"
- "ServerDiffusionV11_1Bundle safetyAdapterPromptRewrite is wrong type"
- "ServerDiffusionV11_1Bundle safetyBaseModel is wrong type"
- "ServerDiffusionV11_1Bundle safetyImageTokenizer is wrong type"
- "ServerDiffusionV11_1Bundle safetyTokenizer is wrong type"
- "ServerDiffusionV11_1Bundle textencoder is wrong type"
- "ServerDiffusionV11_1Bundle tokenizer is wrong type"
- "ServerDiffusionV11_1Bundle vaeDecoder is wrong type"
- "ServerDiffusionV11_1Bundle vaeEncoder is wrong type"
- "ServerDiffusionVAEDecoderV11_1"
- "ServerDiffusionVAEEncoderV11_1"
- "VisualGeneration.ServerDiffusionV10"
- "VisualGeneration.ServerDiffusionV11_1"
- "autoencoderVariant"
- "com.apple.fm.visual.server_diffusion_v1.alpha_mask_decoder_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.anfr_encoder_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.autoencoder"
- "com.apple.fm.visual.server_diffusion_v1.autoencoder_v10"
- "com.apple.fm.visual.server_diffusion_v1.base"
- "com.apple.fm.visual.server_diffusion_v1.base_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.direct_manipulation.small_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.drawing_conditioner.small_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.genmoji_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.inpainting.small_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.messages_background.small_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.noise_predictor_v10"
- "com.apple.fm.visual.server_diffusion_v1.noise_predictor_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.outpainting.small_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.personalization.small_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.personalization_genmoji_small_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.spatial_reframing.small_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.spatial_reframing_vae_decoder_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.textencoder_v10"
- "com.apple.fm.visual.server_diffusion_v1.textencoder_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.tokenizer_v10"
- "com.apple.fm.visual.server_diffusion_v1.tokenizer_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.up_resolution.small_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.vae_decoder_v11_1"
- "com.apple.fm.visual.server_diffusion_v1.vae_encoder_v11_1"
- "com.apple.gm.safety_deny.input.image_playground.edit_suggestions"
- "com.apple.gm.safety_deny.input.image_playground.edit_suggestions.generic"
- "com.apple.gm.safety_deny.output.image_playground.edit_suggestions"
- "com.apple.gm.safety_deny.output.image_playground.edit_suggestions.generic"
- "safetyPostprocessorAdapter"
- "safetyPostprocessorAdapterVariant"
- "safetyPreprocessorAdapter"
- "safetyPreprocessorAdapterVariant"
- "safety_postprocessor_adapter"
- "safety_preprocessor_adapter"
```
