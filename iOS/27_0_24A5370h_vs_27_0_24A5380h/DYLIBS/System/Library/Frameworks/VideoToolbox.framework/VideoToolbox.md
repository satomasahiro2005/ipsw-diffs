## VideoToolbox

> `/System/Library/Frameworks/VideoToolbox.framework/VideoToolbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x723900` | `0x720a48` | **`-0x2eb8`** |
| `__TEXT.__cstring` | `0x44205` | `0x44375` | **`+0x170`** |
| `__TEXT.__eh_frame` | `0x7b44` | `0x7a5c` | **`-0xe8`** |
| `__AUTH_CONST.__cfstring` | `0x25d00` | `0x25dc0` | **`+0xc0`** |
| `__DATA.__bss` | `0x1130` | `0x10e0` | **`-0x50`** |
| `__DATA.__data` | `0x944` | `0x8f4` | **`-0x50`** |
| `__DATA_DIRTY.__bss` | `0x4b0` | `0x500` | **`+0x50`** |
| `__DATA_DIRTY.__data` | `0x2c0` | `0x310` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x5fc8` | `0x5f80` | **`-0x48`** |
| `__DATA.__common` | `0x308` | `0x338` | **`+0x30`** |
| `__DATA_DIRTY.__common` | `0x1b0` | `0x180` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x3650` | `0x3670` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x16c` | `0x154` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2098` | `0x20a8` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x4e078` | `0x4e088` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x41c8` | `0x41d8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x8f0` | `0x8f8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xecc` | `0xed4` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x240` | `0x244` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0xc` | `0x10` | **`+0x4`** |

### Other Changes

```diff

-3350.63.2.11.1
+3350.67.2.0.0

-  Functions: 10559
-  Symbols:   10980
-  CStrings:  10681
+  Functions: 10570
+  Symbols:   10992
+  CStrings:  10690
Symbols:
+ -[VTFrameProcessor captureTelemetryFromParametersIfNeeded:]
+ GCC_except_table16
+ GCC_except_table20
+ GCC_except_table27
+ GCC_except_table86
+ _CMTimeMake
+ _FigCFNumberGetSInt64
+ _OBJC_IVAR_$_VTFrameProcessor._sourcePixelFormat
+ _VTMetalTransferSessionInitialize
+ _VTPixelTransferSessionInitialize
+ _kVTCompressionPropertyKey_DebugMetadataSEI
+ _kVTCompressionPropertyKey_EnableVUIBitstreamRestriction
+ _kVTCompressionPropertyKey_EnableVUITiming
+ _kVTCompressionPropertyKey_EnableWeightedPrediction
+ _kVTDecompressionPropertyKey_ParavirtualizationReplyTimeoutInMillisecondsForTestingOnly
+ _kVTDecompressionPropertyKey_PreferEventLinkForTestingXPCEmitFrame
+ _paravirtualizedVideoDecoder_handleParavirtualizationReplyTimeoutInMillisecondsForTestingOnlySetPropertyAndCopyReplacementValue
- GCC_except_table15
- GCC_except_table19
- GCC_except_table26
- GCC_except_table85
- ___block_descriptor_72_e8_32o40o48o56b64r_e44_v24?0"VEMotionBlurParameters"8"NSError"16ls32l8r64l8s40l8s56l8s48l8
CStrings:
+ "DebugMetadataSEI"
+ "EnableVUIBitstreamRestriction"
+ "EnableVUITiming"
+ "EnableWeightedPrediction"
+ "GainCurveControlPointM inner array missing or wrong type"
+ "GainCurveControlPointX inner array missing or wrong type"
+ "GainCurveControlPointY inner array missing or wrong type"
+ "GainCurveNumControlPoints element is not a number"
+ "ParavirtualizationReplyTimeoutInMillisecondsForTestingOnly"
+ "PreferEventLinkForTestingXPCEmitFrame"
+ "PreferEventLinkForTestingXPCEmitFrame requires a CFBoolean"
+ "description=CoreMedia_VideoToolbox-3350.67.2"
- "GainCurveControlPointX inner array missing"
- "GainCurveControlPointY inner array missing"
- "description=CoreMedia_VideoToolbox-3350.63.2.11.1"
```
