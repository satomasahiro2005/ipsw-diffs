## HomeAI

> `/System/Library/PrivateFrameworks/HomeAI.framework/HomeAI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17a178` | `0x17aa40` | **`+0x8c8`** |
| `__TEXT.__oslogstring` | `0xe3b8` | `0xe4cc` | **`+0x114`** |
| `__AUTH_CONST.__objc_const` | `0x15c50` | `0x15ce0` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x8a00` | `0x8a60` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xa214` | `0xa25c` | **`+0x48`** |
| `__TEXT.__cstring` | `0xd9b0` | `0xd9f1` | **`+0x41`** |
| `__DATA_CONST.__objc_selrefs` | `0x47d0` | `0x4800` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x5080` | `0x5090` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xcec` | `0xcf8` | **`+0xc`** |
| `__TEXT.__gcc_except_tab` | `0xc1ec` | `0xc1f8` | **`+0xc`** |

### Other Changes

```diff

-377.0.0.0.0
+378.0.0.0.0

-  Functions: 5422
-  Symbols:   10115
-  CStrings:  3188
+  Functions: 5428
+  Symbols:   10124
+  CStrings:  3199
Symbols:
+ -[HMIVCPHomeKitAnalysisSession hmiVideoGenerativeAnalysisResultFromMADHKSVClip:requestUUID:clipUUID:]
+ -[HMIVideoGenerativeAnalysisResult initWithRequestUUID:clipUUID:embeddingsByVersion:caption:histogramsByEventType:modelIdentifier:isHistogramDuplicate:isEmbeddingDuplicate:error:]
+ -[HMIVideoGenerativeAnalysisResult initWithRequestUUID:clipUUID:error:]
+ -[HMIVideoGenerativeAnalysisResult initWithRequestUUID:clipUUID:modelIdentifier:error:]
+ -[HMIVideoGenerativeAnalysisResult isEmbeddingDuplicate]
+ -[HMIVideoGenerativeAnalysisResult isHistogramDuplicate]
+ -[HMIVideoGenerativeAnalysisResult modelIdentifier]
+ _OBJC_IVAR_$_HMIVideoGenerativeAnalysisResult._isEmbeddingDuplicate
+ _OBJC_IVAR_$_HMIVideoGenerativeAnalysisResult._isHistogramDuplicate
+ _OBJC_IVAR_$_HMIVideoGenerativeAnalysisResult._modelIdentifier
+ ___101-[HMIVCPHomeKitAnalysisSession hmiVideoGenerativeAnalysisResultFromMADHKSVClip:requestUUID:clipUUID:]_block_invoke
+ ___block_descriptor_96_e8_32s40r48r56r64r72r80r88r_e28_v24?0"MADHKSVCaption"8^B16lr40l8s32l8r48l8r56l8r64l8r72l8r80l8r88l8
- -[HMIVCPHomeKitAnalysisSession hmiVideoGenerativeAnalysisResultFromMADHKSVClip:requestUUID:]
- ___92-[HMIVCPHomeKitAnalysisSession hmiVideoGenerativeAnalysisResultFromMADHKSVClip:requestUUID:]_block_invoke
- ___block_descriptor_72_e8_32s40r48r56r64r_e28_v24?0"MADHKSVCaption"8^B16lr40l8s32l8r48l8r56l8r64l8
CStrings:
+ "Caption flagged as unsafe"
+ "Is Embedding Duplicate"
+ "Is Histogram Duplicate"
+ "Model Identifier"
+ "Model identifier: %@"
+ "Result is a histogram duplicate"
+ "Result is an embedding duplicate"
+ "[%{public}@] Caption flagged as unsafe"
+ "[%{public}@] Model identifier: %@"
+ "[%{public}@] Result is a histogram duplicate"
+ "[%{public}@] Result is an embedding duplicate"
```
