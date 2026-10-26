## EmbeddingCore

> `/System/Library/PrivateFrameworks/EmbeddingCore.framework/EmbeddingCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bd94` | `0x6a9a0` | **`-0x13f4`** |
| `__TEXT.__cstring` | `0x5df2` | `0x59d2` | **`-0x420`** |
| `__TEXT.__oslogstring` | `0x195f` | `0x188f` | **`-0xd0`** |
| `__TEXT.__gcc_except_tab` | `0x7330` | `0x7268` | **`-0xc8`** |
| `__AUTH_CONST.__cfstring` | `0x1a60` | `0x1a00` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x2aa8` | `0x2a70` | **`-0x38`** |
| `__DATA.__bss` | `0x1c1` | `0x1b1` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xd38` | `0xd28` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x3c0` | `0x3b8` | **`-0x8`** |

### Other Changes

```diff

-460.14.1.1.0
+460.14.1.2.0

-  Functions: 2127
-  Symbols:   3314
-  CStrings:  741
+  Functions: 2079
+  Symbols:   3312
+  CStrings:  729
Symbols:
- _OBJC_CLASS_$_NSUserDefaults
- __ZZL15ForcedBatchSizevE9batchSize
CStrings:
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis_Embedding/EmbeddingCore/Common/CNNModelEspressoV2.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis_Embedding/EmbeddingCore/Common/CNNModelEspressoV2Data.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis_Embedding/EmbeddingCore/Text/MADCrossEncoder.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis_Embedding/EmbeddingCore/Text/MADTextEmbeddingSafety.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis_Embedding/EmbeddingCore/Text/MADTextEmbeddingThreshold.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis_Embedding/EmbeddingCore/Text/MADTextLexiconSafety.mm"
- "CrossEncoderBatchSize"
- "TextSigmoidCutoff"
- "[Cross-Encoder] Batch size %@ set by defaults not supported, ignoring"
- "[Cross-Encoder] Batch size forced to %@ by defaults"
- "[LOG_ERROR] %s[%d]: code %d\n"
- "[Text|Threshold] Overriding sigmoid cutoff (%@)"
```
