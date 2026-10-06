## VisualGeneration

> `/System/Library/PrivateFrameworks/VisualGeneration.framework/VisualGeneration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c599c` | `0x2c9280` | **`+0x38e4`** |
| `__DATA_DIRTY.__data` | `0x5160` | `0x83c8` | **`+0x3268`** |
| `__AUTH.__data` | `0x3ea8` | `0x1210` | **`-0x2c98`** |
| `__DATA.__data` | `0x41b8` | `0x3c80` | **`-0x538`** |
| `__AUTH.__objc_data` | `0x6e0` | `0x320` | **`-0x3c0`** |
| `__DATA_DIRTY.__objc_data` | `0x6e0` | `0xaa0` | **`+0x3c0`** |
| `__TEXT.__const` | `0x21f78` | `0x22278` | **`+0x300`** |
| `__AUTH_CONST.__const` | `0x154d0` | `0x156b0` | **`+0x1e0`** |
| `__DATA.__bss` | `0x26760` | `0x26940` | **`+0x1e0`** |
| `__DATA_DIRTY.__bss` | `0x7e80` | `0x8030` | **`+0x1b0`** |
| `__TEXT.__cstring` | `0x76b3` | `0x7853` | **`+0x1a0`** |
| `__TEXT.__swift5_reflstr` | `0x8e21` | `0x8ec1` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x8f54` | `0x8fec` | **`+0x98`** |
| `__DATA.__common` | `0x138` | `0xc8` | **`-0x70`** |
| `__DATA_DIRTY.__common` | `0x190` | `0x200` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x7fd6` | `0x8038` | **`+0x62`** |
| `__TEXT.__oslogstring` | `0x58c9` | `0x5929` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x9320` | `0x9370` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x2e38` | `0x2e80` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x1140` | `0x1188` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x7b3c` | `0x7b7c` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x17a80` | `0x17ac0` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x119c` | `0x1160` | **`-0x3c`** |
| `__TEXT.__swift5_proto` | `0x1b24` | `0x1b40` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x500` | `0x510` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x9f4` | `0x9fc` | **`+0x8`** |

### Other Changes

```diff

-134.0.0.0.0
+136.0.0.0.0

-  Functions: 11337
-  Symbols:   4086
-  CStrings:  1219
+  Functions: 11370
+  Symbols:   4097
+  CStrings:  1229
Symbols:
+ ___swift_memcpy131_8
+ ___swift_memcpy57_8
+ _associated conformance 16VisualGeneration0A9GeneratorC20RequestConfigurationV09ImageTileE0V10CodingKeys33_4363F95EF468E3AB4B33E46020323F78LLOSHAASQ
+ _associated conformance 16VisualGeneration0A9GeneratorC20RequestConfigurationV09ImageTileE0V10CodingKeys33_4363F95EF468E3AB4B33E46020323F78LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 16VisualGeneration0A9GeneratorC20RequestConfigurationV09ImageTileE0V10CodingKeys33_4363F95EF468E3AB4B33E46020323F78LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _get_enum_tag_for_layout_string 16VisualGeneration0A9GeneratorC20RequestConfigurationV09ImageTileE0VSg
+ _symbolic _____ 16VisualGeneration0A9GeneratorC20RequestConfigurationV09ImageTileE0V
+ _symbolic _____ 16VisualGeneration0A9GeneratorC20RequestConfigurationV09ImageTileE0V10CodingKeys33_4363F95EF468E3AB4B33E46020323F78LLO
+ _symbolic _____Sg 15ModelInterfaces32VisualGenerationInferenceRequestV08MirkwoodF7OptionsV
+ _symbolic _____Sg 15ModelInterfaces32VisualGenerationInferenceRequestV22ImageTileConfigurationV
+ _symbolic _____Sg 15ModelInterfaces32VisualGenerationInferenceRequestV6CGRectV
+ _symbolic _____Sg 16VisualGeneration0A9GeneratorC20RequestConfigurationV09ImageTileE0V
+ _symbolic _____Sg_ABt 15ModelInterfaces32VisualGenerationInferenceRequestV08MirkwoodF7OptionsV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 16VisualGeneration0D9GeneratorC20RequestConfigurationV09ImageTileH0V10CodingKeys33_4363F95EF468E3AB4B33E46020323F78LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 16VisualGeneration0D9GeneratorC20RequestConfigurationV09ImageTileH0V10CodingKeys33_4363F95EF468E3AB4B33E46020323F78LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15ModelInterfaces32VisualGenerationInferenceRequestV0f9GeneratorI4TypeO
+ _type_layout_string 16VisualGeneration0A9GeneratorC20RequestConfigurationV09ImageTileE0V
- ___swift_memcpy67_8
- _get_type_metadata 15Synchronization5MutexVySDySSSgs6ResultOySo7MLModelCs5Error_pGGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySiG noncopyable
- _get_type_metadata 15Synchronization5MutexVySo20SPSentencePieceModelCG noncopyable
- _get_type_metadata 15Synchronization6AtomicVySbG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "Canvas for image tile should have positive non-zero dimensions"
+ "Canvas image must be "
+ "FeatureFlag enabled for inFill 3K"
+ "FeatureFlag enabled for outFill 3K"
+ "Image tile bounds should be within the canvas dimensions"
+ "PCCLargeImageGenerationInfill"
+ "PCCLargeImageGenerationOutfill"
+ "Please enable PCCLargeImageGenerationInfill FF for 3K/4K Inpainting"
+ "Please enable PCCLargeImageGenerationOutfill FF for 3K/4K Outpainting"
+ "picture_frame_1024_alpha"
+ "picture_frame_320_alpha"
- "picture_frame_384_alpha"
```
