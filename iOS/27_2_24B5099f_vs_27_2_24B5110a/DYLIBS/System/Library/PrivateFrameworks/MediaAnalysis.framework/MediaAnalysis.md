## MediaAnalysis

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/MediaAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4d1c0c` | `0x4d1fc8` | **`+0x3bc`** |
| `__TEXT.__oslogstring` | `0x3312b` | `0x331eb` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x686bc` | `0x68700` | **`+0x44`** |
| `__TEXT.__const` | `0x16608` | `0x16638` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2cef1` | `0x2cf21` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0x12c8` | `0x12e8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x22d60` | `0x22d80` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xd08` | `0xd20` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x3930` | `0x3948` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x14100` | `0x14118` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x41de8` | `0x41df8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x7c90` | `0x7c98` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xf198` | `0xf1a0` | **`+0x8`** |

### Other Changes

```diff

-460.12.1.0.0
+460.14.1.1.0

-  Functions: 20216
-  Symbols:   28628
-  CStrings:  9033
+  Functions: 20221
+  Symbols:   28631
+  CStrings:  9036
Symbols:
+ -[MADServicePhotosVideoAsset isPhotosAsset]
+ -[MADServiceVideoAsset isPhotosAsset]
+ -[MADServiceVideoSafetyProcessingTask storeSafetyClassificationResults]
+ __ZL17shapeElementCountP7NSArrayIP8NSNumberE
- -[MADServiceVideoSafetyProcessingTask storeSafetyClassificationResultsForSharedAsset]
CStrings:
+ "Failed to generate MADImageEmbeddingResult: expected shape %@ (%lu fp16 elements), got %lu elements"
+ "Failed to populate the composition from the original asset (%@)"
+ "Missing video track (processed %lu, composition %lu)"
+ "VCPMADImageEmbeddingTask expected shape %@ (%lu fp16 elements) but got %lu elements"
+ "[%@] Failed to obtain analysis result for Photos asset."
- "Failed to generate MADImageEmbeddingResult"
- "[%@] Failed to obtain analysis result for shared Photos asset."
```
