## HomeAI

> `/System/Library/PrivateFrameworks/HomeAI.framework/HomeAI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17f344` | `0x17f8ac` | **`+0x568`** |
| `__AUTH_CONST.__cfstring` | `0x8ae0` | `0x8c40` | **`+0x160`** |
| `__TEXT.__cstring` | `0xda5c` | `0xdb8d` | **`+0x131`** |
| `__AUTH_CONST.__objc_const` | `0x16420` | `0x16480` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xa67c` | `0xa6b4` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0xe87d` | `0xe8b0` | **`+0x33`** |
| `__DATA_CONST.__objc_selrefs` | `0x4820` | `0x4848` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0xc210` | `0xc234` | **`+0x24`** |
| `__AUTH_CONST.__objc_intobj` | `0x588` | `0x570` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x5108` | `0x5118` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xd64` | `0xd6c` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x3998` | `0x39a0` | **`+0x8`** |

### Other Changes

```diff

-381.0.0.0.0
+382.0.0.0.0

-  Functions: 5516
-  Symbols:   10264
-  CStrings:  3222
+  Functions: 5524
+  Symbols:   10272
+  CStrings:  3233
Symbols:
+ +[NSError(HMIError) hmiErrorWithCode:reason:]
+ -[HMIVideoAnalyzerConfiguration fragmentBufferDuration]
+ -[HMIVideoAnalyzerConfiguration setFragmentBufferDuration:]
+ -[HMIVideoGenerativeAnalysisResult initWithRequestUUID:clipUUID:embeddingsByVersion:caption:histogramsByEventType:modelIdentifier:isHistogramDuplicate:isEmbeddingDuplicate:isDegraded:error:]
+ -[HMIVideoGenerativeAnalysisResult isDegraded]
+ _HMIFragmentBufferDurationKey
+ _OBJC_IVAR_$_HMIVideoAnalyzerConfiguration._fragmentBufferDuration
+ _OBJC_IVAR_$_HMIVideoGenerativeAnalysisResult._isDegraded
+ ___block_descriptor_104_e8_32s40r48r56r64r72r80r88r96r_e28_v24?0"MADHKSVCaption"8^B16lr40l8s32l8r48l8r56l8r64l8r72l8r80l8r88l8r96l8
- ___block_descriptor_96_e8_32s40r48r56r64r72r80r88r_e28_v24?0"MADHKSVCaption"8^B16lr40l8s32l8r48l8r56l8r64l8r72l8r80l8r88l8
CStrings:
+ "Caption flagged as sensitive content"
+ "Caption flagged as unsafe content"
+ "Caption parsing failed"
+ "Fragment Buffer Duration"
+ "HMIErrorCodeCaptionNoActivity"
+ "HMIErrorCodeCaptionParsingFailed"
+ "HMIErrorCodeCaptionSensitiveContent"
+ "HMIErrorCodeCaptionUnsafeContent"
+ "Is Degraded"
+ "Result is degraded"
+ "[%{public}@] Result is degraded"
+ "fragmentBufferDurationSeconds"
- "fragmentBufferSize"
```
