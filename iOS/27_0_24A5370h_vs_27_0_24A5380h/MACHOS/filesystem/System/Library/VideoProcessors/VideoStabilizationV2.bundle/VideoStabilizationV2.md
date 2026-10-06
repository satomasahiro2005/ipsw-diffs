## VideoStabilizationV2

> `/System/Library/VideoProcessors/VideoStabilizationV2.bundle/VideoStabilizationV2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59308` | `0x59f58` | **`+0xc50`** |
| `__TEXT.__oslogstring` | `0xf0c3` | `0xf2d4` | **`+0x211`** |
| `__TEXT.__objc_methname` | `0x5bb7` | `0x5c7f` | **`+0xc8`** |
| `__DATA.__objc_const` | `0x4508` | `0x4598` | **`+0x90`** |
| `__TEXT.__cstring` | `0x9725` | `0x9784` | **`+0x5f`** |
| `__TEXT.__objc_methlist` | `0x1c04` | `0x1c44` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x32c0` | `0x3300` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x898` | `0x8c0` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0xff0` | `0x1008` | **`+0x18`** |
| `__TEXT.__const` | `0x700` | `0x6f0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x8a8` | `0x8b8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4b0` | `0x4bc` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-753.0.0.122.3
+758.0.0.122.2

-  Functions: 1424
-  Symbols:   2231
-  CStrings:  2774
+  Functions: 1430
+  Symbols:   2242
+  CStrings:  2789
Symbols:
+ -[VISConfigurationV2 setUndistortedOverscanEnabled:]
+ -[VISConfigurationV2 undistortedOverscanEnabled]
+ -[affineGPUMetal setUndistortedDimensions:height:]
+ GCC_except_table10
+ GCC_except_table18
+ GCC_except_table22
+ GCC_except_table27
+ GCC_except_table39
+ OBJC_IVAR_$_VISConfigurationV2._undistortedOverscanEnabled
+ OBJC_IVAR_$_affineGPUMetal._undistortedInputHeight
+ OBJC_IVAR_$_affineGPUMetal._undistortedInputWidth
+ _AffineTransformSetUndistortedInputSize
+ _kCVImageBufferColorPrimaries_ITU_R_2020
+ _kCVImageBufferYCbCrMatrix_ITU_R_2020
+ _kFigCaptureStreamGDCCoefficientsKey_PolynomialMax
+ _kFigVideoStabilizationSampleBufferAttachmentKey_StabilizationTransformsParameters
+ _kFigVideoStabilizationSampleBufferProcessorOption_UndistortedOverscanEnabled
+ _objc_msgSend$setUndistortedDimensions:height:
+ _objc_msgSend$undistortedOverscanEnabled
- GCC_except_table17
- GCC_except_table21
- GCC_except_table26
- GCC_except_table38
- GCC_except_table9
- _OUTLINED_FUNCTION_178
- _OUTLINED_FUNCTION_179
- _kFigVideoStabilizationSampleBufferAttachmentKey_GPUTransformsParameters
CStrings:
+ "-[affineGPUMetal setUndistortedDimensions:height:]"
+ "<<<< GyroVideoStabilizationV2 >>>> %s: Configuration: Overscan < 0, undistorted overscan enabled."
+ "<<<< GyroVideoStabilizationV2 >>>> %s: Options: UndistortedOverscanEnabled: %s"
+ "<<<< GyroVideoStabilizationV2 >>>> %s: Undistorted input dimensions: ( %d x %d ) derived from ( %d x %d )"
+ "<<<< GyroVideoStabilizationV2 >>>> %s: Undistorted overscan (per side): %d x %d"
+ "<<<< GyroVideoStabilizationV2 >>>> %s: Updated panning speed threshold: %f"
+ "<<<< affineGPUMetalV2 >>>> %s: Undistorted input width = %d, Undistorted input height = %d"
+ "TB,N,V_undistortedOverscanEnabled"
+ "_attachStabilizationParameters"
+ "_extractStabilizationParameters"
+ "_undistortedInputHeight"
+ "_undistortedInputWidth"
+ "_undistortedOverscanEnabled"
+ "sbp_computeUndistortedOverscanFromDistortionModel"
+ "setUndistortedDimensions:height:"
+ "setUndistortedOverscanEnabled:"
+ "storage->tmpStabilizationXformsParams"
+ "storage->undistortedOverscanRectEnabled"
+ "undistortedOverscanEnabled"
- "( overscanWidth >= 0 ) && ( overscanHeight >= 0 )"
- "_attachGPUStabilizationParameters"
- "_extractGPUStabilizationParameters"
- "storage->tmpGPUXformsParams"
```
