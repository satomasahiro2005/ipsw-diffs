## EmbeddingCore

> `/System/Library/PrivateFrameworks/EmbeddingCore.framework/EmbeddingCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d880` | `0x69e50` | **`-0x3a30`** |
| `__AUTH_CONST.__objc_const` | `0x4080` | `0x3988` | **`-0x6f8`** |
| `__TEXT.__cstring` | `0x5ce6` | `0x5816` | **`-0x4d0`** |
| `__TEXT.__objc_methlist` | `0x1d0c` | `0x1954` | **`-0x3b8`** |
| `__DATA_DIRTY.__objc_data` | `0x1300` | `0x1120` | **`-0x1e0`** |
| `__AUTH_CONST.__cfstring` | `0x1ba0` | `0x19e0` | **`-0x1c0`** |
| `__DATA_CONST.__objc_selrefs` | `0xec0` | `0xd28` | **`-0x198`** |
| `__TEXT.__oslogstring` | `0x19af` | `0x184f` | **`-0x160`** |
| `__TEXT.__gcc_except_tab` | `0x7260` | `0x7184` | **`-0xdc`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x258` | `0x1f8` | **`-0x60`** |
| `__DATA.__data` | `0x2d4` | `0x274` | **`-0x60`** |
| `__DATA_CONST.__objc_arraydata` | `0x3a8` | `0x350` | **`-0x58`** |
| `__TEXT.__unwind_info` | `0x2ab0` | `0x2a60` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x5b0` | `0x568` | **`-0x48`** |
| `__DATA.__objc_ivar` | `0x2b8` | `0x284` | **`-0x34`** |
| `__DATA_CONST.__objc_classlist` | `0x1b0` | `0x180` | **`-0x30`** |
| `__DATA_CONST.__objc_superrefs` | `0xd0` | `0xa0` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x3d8` | `0x3b8` | **`-0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x150` | `0x168` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x18` | **`-0x8`** |

### Other Changes

```diff

-435.73.2.0.0
+435.79.1.4.0

-  Functions: 2200
-  Symbols:   3452
-  CStrings:  743
+  Functions: 2075
+  Symbols:   3307
+  CStrings:  717
Symbols:
+ GCC_except_table78
+ _MADComputeConfigIOSurfaceMemoryPoolIDKey
+ __ZL40MADDownloadableAemVersionForE5MLRevision39MADTextEncoderE5MLConfigurationRevision
- +[nemo_5m_md3_2026_04_qformer URLOfModelInThisBundle]
- +[nemo_5m_md3_2026_04_qformer loadContentsOfURL:configuration:completionHandler:]
- +[nemo_5m_md3_2026_04_qformer loadWithConfiguration:completionHandler:]
- +[nemo_5m_md3_2026_04_vision URLOfModelInThisBundle]
- +[nemo_5m_md3_2026_04_vision loadContentsOfURL:configuration:completionHandler:]
- +[nemo_5m_md3_2026_04_vision loadWithConfiguration:completionHandler:]
- -[nemo_5m_md3_2026_04_qformer .cxx_destruct]
- -[nemo_5m_md3_2026_04_qformer initWithConfiguration:error:]
- -[nemo_5m_md3_2026_04_qformer initWithContentsOfURL:configuration:error:]
- -[nemo_5m_md3_2026_04_qformer initWithContentsOfURL:error:]
- -[nemo_5m_md3_2026_04_qformer initWithMLModel:]
- -[nemo_5m_md3_2026_04_qformer init]
- -[nemo_5m_md3_2026_04_qformer model]
- -[nemo_5m_md3_2026_04_qformer predictionFromFeatures:completionHandler:]
- -[nemo_5m_md3_2026_04_qformer predictionFromFeatures:error:]
- -[nemo_5m_md3_2026_04_qformer predictionFromFeatures:options:completionHandler:]
- -[nemo_5m_md3_2026_04_qformer predictionFromFeatures:options:error:]
- -[nemo_5m_md3_2026_04_qformer predictionFromSpatial_embedding:final_embedding:error:]
- -[nemo_5m_md3_2026_04_qformer predictionsFromInputs:options:error:]
- -[nemo_5m_md3_2026_04_qformerInput .cxx_destruct]
- -[nemo_5m_md3_2026_04_qformerInput featureNames]
- -[nemo_5m_md3_2026_04_qformerInput featureValueForName:]
- -[nemo_5m_md3_2026_04_qformerInput final_embedding]
- -[nemo_5m_md3_2026_04_qformerInput initWithSpatial_embedding:final_embedding:]
- -[nemo_5m_md3_2026_04_qformerInput setFinal_embedding:]
- -[nemo_5m_md3_2026_04_qformerInput setSpatial_embedding:]
- -[nemo_5m_md3_2026_04_qformerInput spatial_embedding]
- -[nemo_5m_md3_2026_04_qformerOutput .cxx_destruct]
- -[nemo_5m_md3_2026_04_qformerOutput featureNames]
- -[nemo_5m_md3_2026_04_qformerOutput featureValueForName:]
- -[nemo_5m_md3_2026_04_qformerOutput initWithOutput_embedding:]
- -[nemo_5m_md3_2026_04_qformerOutput output_embedding]
- -[nemo_5m_md3_2026_04_qformerOutput setOutput_embedding:]
- -[nemo_5m_md3_2026_04_vision .cxx_destruct]
- -[nemo_5m_md3_2026_04_vision initWithConfiguration:error:]
- -[nemo_5m_md3_2026_04_vision initWithContentsOfURL:configuration:error:]
- -[nemo_5m_md3_2026_04_vision initWithContentsOfURL:error:]
- -[nemo_5m_md3_2026_04_vision initWithMLModel:]
- -[nemo_5m_md3_2026_04_vision init]
- -[nemo_5m_md3_2026_04_vision model]
- -[nemo_5m_md3_2026_04_vision predictionFromFeatures:completionHandler:]
- -[nemo_5m_md3_2026_04_vision predictionFromFeatures:error:]
- -[nemo_5m_md3_2026_04_vision predictionFromFeatures:options:completionHandler:]
- -[nemo_5m_md3_2026_04_vision predictionFromFeatures:options:error:]
- -[nemo_5m_md3_2026_04_vision predictionFromY:uv:error:]
- -[nemo_5m_md3_2026_04_vision predictionsFromInputs:options:error:]
- -[nemo_5m_md3_2026_04_visionInput .cxx_destruct]
- -[nemo_5m_md3_2026_04_visionInput featureNames]
- -[nemo_5m_md3_2026_04_visionInput featureValueForName:]
- -[nemo_5m_md3_2026_04_visionInput initWithY:uv:]
- -[nemo_5m_md3_2026_04_visionInput setUv:]
- -[nemo_5m_md3_2026_04_visionInput setY:]
- -[nemo_5m_md3_2026_04_visionInput uv]
- -[nemo_5m_md3_2026_04_visionInput y]
- -[nemo_5m_md3_2026_04_visionOutput .cxx_destruct]
- -[nemo_5m_md3_2026_04_visionOutput embed]
- -[nemo_5m_md3_2026_04_visionOutput featureNames]
- -[nemo_5m_md3_2026_04_visionOutput featureValueForName:]
- -[nemo_5m_md3_2026_04_visionOutput initWithS1_feature:s2_feature:s3_feature:s4_feature:spatial_embed:embed:]
- -[nemo_5m_md3_2026_04_visionOutput s1_feature]
- -[nemo_5m_md3_2026_04_visionOutput s2_feature]
- -[nemo_5m_md3_2026_04_visionOutput s3_feature]
- -[nemo_5m_md3_2026_04_visionOutput s4_feature]
- -[nemo_5m_md3_2026_04_visionOutput setEmbed:]
- -[nemo_5m_md3_2026_04_visionOutput setS1_feature:]
- -[nemo_5m_md3_2026_04_visionOutput setS2_feature:]
- -[nemo_5m_md3_2026_04_visionOutput setS3_feature:]
- -[nemo_5m_md3_2026_04_visionOutput setS4_feature:]
- -[nemo_5m_md3_2026_04_visionOutput setSpatial_embed:]
- -[nemo_5m_md3_2026_04_visionOutput spatial_embed]
- _OBJC_CLASS_$_MLArrayBatchProvider
- _OBJC_CLASS_$_MLFeatureValue
- _OBJC_CLASS_$_NSUserDefaults
- _OBJC_CLASS_$_nemo_5m_md3_2026_04_qformer
- _OBJC_CLASS_$_nemo_5m_md3_2026_04_qformerInput
- _OBJC_CLASS_$_nemo_5m_md3_2026_04_qformerOutput
- _OBJC_CLASS_$_nemo_5m_md3_2026_04_vision
- _OBJC_CLASS_$_nemo_5m_md3_2026_04_visionInput
- _OBJC_CLASS_$_nemo_5m_md3_2026_04_visionOutput
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_qformer._model
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_qformerInput._final_embedding
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_qformerInput._spatial_embedding
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_qformerOutput._output_embedding
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_vision._model
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_visionInput._uv
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_visionInput._y
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_visionOutput._embed
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_visionOutput._s1_feature
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_visionOutput._s2_feature
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_visionOutput._s3_feature
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_visionOutput._s4_feature
- _OBJC_IVAR_$_nemo_5m_md3_2026_04_visionOutput._spatial_embed
- _OBJC_METACLASS_$_nemo_5m_md3_2026_04_qformer
- _OBJC_METACLASS_$_nemo_5m_md3_2026_04_qformerInput
- _OBJC_METACLASS_$_nemo_5m_md3_2026_04_qformerOutput
- _OBJC_METACLASS_$_nemo_5m_md3_2026_04_vision
- _OBJC_METACLASS_$_nemo_5m_md3_2026_04_visionInput
- _OBJC_METACLASS_$_nemo_5m_md3_2026_04_visionOutput
- __OBJC_$_CLASS_METHODS_nemo_5m_md3_2026_04_qformer
- __OBJC_$_CLASS_METHODS_nemo_5m_md3_2026_04_vision
- __OBJC_$_INSTANCE_METHODS_nemo_5m_md3_2026_04_qformer
- __OBJC_$_INSTANCE_METHODS_nemo_5m_md3_2026_04_qformerInput
- __OBJC_$_INSTANCE_METHODS_nemo_5m_md3_2026_04_qformerOutput
- __OBJC_$_INSTANCE_METHODS_nemo_5m_md3_2026_04_vision
- __OBJC_$_INSTANCE_METHODS_nemo_5m_md3_2026_04_visionInput
- __OBJC_$_INSTANCE_METHODS_nemo_5m_md3_2026_04_visionOutput
- __OBJC_$_INSTANCE_VARIABLES_nemo_5m_md3_2026_04_qformer
- __OBJC_$_INSTANCE_VARIABLES_nemo_5m_md3_2026_04_qformerInput
- __OBJC_$_INSTANCE_VARIABLES_nemo_5m_md3_2026_04_qformerOutput
- __OBJC_$_INSTANCE_VARIABLES_nemo_5m_md3_2026_04_vision
- __OBJC_$_INSTANCE_VARIABLES_nemo_5m_md3_2026_04_visionInput
- __OBJC_$_INSTANCE_VARIABLES_nemo_5m_md3_2026_04_visionOutput
- __OBJC_$_PROP_LIST_MLFeatureProvider
- __OBJC_$_PROP_LIST_nemo_5m_md3_2026_04_qformer
- __OBJC_$_PROP_LIST_nemo_5m_md3_2026_04_qformerInput
- __OBJC_$_PROP_LIST_nemo_5m_md3_2026_04_qformerOutput
- __OBJC_$_PROP_LIST_nemo_5m_md3_2026_04_vision
- __OBJC_$_PROP_LIST_nemo_5m_md3_2026_04_visionInput
- __OBJC_$_PROP_LIST_nemo_5m_md3_2026_04_visionOutput
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_MLFeatureProvider
- __OBJC_$_PROTOCOL_METHOD_TYPES_MLFeatureProvider
- __OBJC_CLASS_PROTOCOLS_$_nemo_5m_md3_2026_04_qformerInput
- __OBJC_CLASS_PROTOCOLS_$_nemo_5m_md3_2026_04_qformerOutput
- __OBJC_CLASS_PROTOCOLS_$_nemo_5m_md3_2026_04_visionInput
- __OBJC_CLASS_PROTOCOLS_$_nemo_5m_md3_2026_04_visionOutput
- __OBJC_CLASS_RO_$_nemo_5m_md3_2026_04_qformer
- __OBJC_CLASS_RO_$_nemo_5m_md3_2026_04_qformerInput
- __OBJC_CLASS_RO_$_nemo_5m_md3_2026_04_qformerOutput
- __OBJC_CLASS_RO_$_nemo_5m_md3_2026_04_vision
- __OBJC_CLASS_RO_$_nemo_5m_md3_2026_04_visionInput
- __OBJC_CLASS_RO_$_nemo_5m_md3_2026_04_visionOutput
- __OBJC_LABEL_PROTOCOL_$_MLFeatureProvider
- __OBJC_METACLASS_RO_$_nemo_5m_md3_2026_04_qformer
- __OBJC_METACLASS_RO_$_nemo_5m_md3_2026_04_qformerInput
- __OBJC_METACLASS_RO_$_nemo_5m_md3_2026_04_qformerOutput
- __OBJC_METACLASS_RO_$_nemo_5m_md3_2026_04_vision
- __OBJC_METACLASS_RO_$_nemo_5m_md3_2026_04_visionInput
- __OBJC_METACLASS_RO_$_nemo_5m_md3_2026_04_visionOutput
- __OBJC_PROTOCOL_$_MLFeatureProvider
- __ZZL15ForcedBatchSizevE9batchSize
- ___71-[nemo_5m_md3_2026_04_vision predictionFromFeatures:completionHandler:]_block_invoke
- ___72-[nemo_5m_md3_2026_04_qformer predictionFromFeatures:completionHandler:]_block_invoke
- ___79-[nemo_5m_md3_2026_04_vision predictionFromFeatures:options:completionHandler:]_block_invoke
- ___80+[nemo_5m_md3_2026_04_vision loadContentsOfURL:configuration:completionHandler:]_block_invoke
- ___80-[nemo_5m_md3_2026_04_qformer predictionFromFeatures:options:completionHandler:]_block_invoke
- ___81+[nemo_5m_md3_2026_04_qformer loadContentsOfURL:configuration:completionHandler:]_block_invoke
- ___block_descriptor_40_e8_32bs_e29_v24?0"MLModel"8"NSError"16ls32l8
- ___block_descriptor_40_e8_32bs_e41_v24?0"<MLFeatureProvider>"8"NSError"16ls32l8
CStrings:
+ "ForceMD8Download"
+ "MADComputeConfigIOSurfaceMemoryPoolID"
+ "Q"
+ "md8-text-encoder.mlmodelc"
+ "md8-token-encoder.mlmodelc"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis_Embedding/EmbeddingCore/Common/CNNModelEspressoV2.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis_Embedding/EmbeddingCore/Common/CNNModelEspressoV2Data.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis_Embedding/EmbeddingCore/Text/MADCrossEncoder.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis_Embedding/EmbeddingCore/Text/MADTextEmbeddingSafety.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis_Embedding/EmbeddingCore/Text/MADTextEmbeddingThreshold.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis_Embedding/EmbeddingCore/Text/MADTextLexiconSafety.mm"
- "Could not load nemo_5m_md3_2026_04_qformer.mlmodelc in the bundle resource"
- "Could not load nemo_5m_md3_2026_04_vision.mlmodelc in the bundle resource"
- "CrossEncoderBatchSize"
- "ForceMD7Download"
- "TextSigmoidCutoff"
- "[Cross-Encoder] Batch size %@ set by defaults not supported, ignoring"
- "[Cross-Encoder] Batch size forced to %@ by defaults"
- "[LOG_ERROR] %s[%d]: code %d\n"
- "[Text|Threshold] Overriding sigmoid cutoff (%@)"
- "embed"
- "final_embedding"
- "nemo_5m_md3_2026_04_qformer"
- "nemo_5m_md3_2026_04_vision"
- "output_embedding"
- "s1_feature"
- "s2_feature"
- "s3_feature"
- "s4_feature"
- "spatial_embed"
- "spatial_embedding"
- "token_md7_6bit"
- "uv"
- "v24@?0@\"<MLFeatureProvider>\"8@\"NSError\"16"
- "v24@?0@\"MLModel\"8@\"NSError\"16"
- "y"
```
