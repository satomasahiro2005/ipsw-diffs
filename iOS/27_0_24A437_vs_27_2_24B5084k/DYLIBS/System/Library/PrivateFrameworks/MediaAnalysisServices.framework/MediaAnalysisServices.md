## MediaAnalysisServices

> `/System/Library/PrivateFrameworks/MediaAnalysisServices.framework/MediaAnalysisServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c80c` | `0x3dad4` | **`+0x12c8`** |
| `__TEXT.__cstring` | `0x38be` | `0x3ba5` | **`+0x2e7`** |
| `__AUTH_CONST.__cfstring` | `0x4ce0` | `0x4de0` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0xa248` | `0xa328` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x4fa4` | `0x5024` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x1978` | `0x19d0` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x2309` | `0x2326` | **`+0x1d`** |
| `__DATA.__objc_ivar` | `0x5a4` | `0x5b4` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x4448` | `0x4458` | **`+0x10`** |
| `__TEXT.__const` | `0xf8` | `0x100` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1c58` | `0x1c60` | **`+0x8`** |

### Other Changes

```diff

-435.79.1.5.0
+460.7.1.0.0

-  Functions: 1698
-  Symbols:   3465
-  CStrings:  858
+  Functions: 1743
+  Symbols:   3476
+  CStrings:  871
Symbols:
+ -[MADTextTokenizationRequest computeOffsets]
+ -[MADTextTokenizationRequest setComputeOffsets:]
+ -[MADTextTokenizationResult initWithTokenIDs:tokenOffsets:error:]
+ -[MADTextTokenizationResult tokenOffsets]
+ -[MADVideoSafetyClassificationRequest goreFrameCountThreshold]
+ -[MADVideoSafetyClassificationRequest setGoreFrameCountThreshold:]
+ -[MADVideoSafetyClassificationRequest setViolentFrameCountThreshold:]
+ -[MADVideoSafetyClassificationRequest violentFrameCountThreshold]
+ _OBJC_IVAR_$_MADTextTokenizationRequest._computeOffsets
+ _OBJC_IVAR_$_MADTextTokenizationResult._tokenOffsets
+ _OBJC_IVAR_$_MADVideoSafetyClassificationRequest._goreFrameCountThreshold
+ _OBJC_IVAR_$_MADVideoSafetyClassificationRequest._violentFrameCountThreshold
- -[MADTextTokenizationResult initWithTokenIDs:error:]
CStrings:
+ ", goreFrameCountThreshold: %@"
+ ", tokenOffsets: %@"
+ ", violentFrameCountThreshold: %@"
+ "./Utilities/CGUtilities.h"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/MediaAnalysisServices/ComputeService/MADCoreMLResult.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/MediaAnalysisServices/MADVideoSession/MADVideoSession.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/MediaAnalysisServices/MADVideoSession/Utilities/MADPixelBufferProcesser.mm"
+ "ComputeOffsets"
+ "GoreFrameCountThreshold"
+ "TokenOffsets"
+ "ViolentFrameCountThreshold"
+ "[LOG_ERROR] %s[%d]: code %d\n"
+ "computeOffsets: %d, "
```
