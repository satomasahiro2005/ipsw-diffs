## SemanticStyleV1

> `/System/Library/VideoProcessors/SemanticStyleV1.bundle/SemanticStyleV1`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1070` | `0x1af1` | **`+0xa81`** |
| `__TEXT.__text` | `0xdda8` | `0xe704` | **`+0x95c`** |
| `__TEXT.__oslogstring` | `0xd4` | `0x215` | **`+0x141`** |
| `__DATA_CONST.__cfstring` | `0x520` | `0x580` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x500` | `0x530` | **`+0x30`** |
| `__DATA.__common` | `—` | `0x20` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x288` | `0x2a0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2f8` | `0x2e0` | **`-0x18`** |
| `__TEXT.__const` | `0xc80` | `0xc90` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-764.22.13.0.0
+764.40.4.122.1

-  Functions: 322
-  Symbols:   117
-  CStrings:  662
+  Functions: 337
+  Symbols:   120
+  CStrings:  737
Symbols:
+ _FigSignalErrorAt3
+ __os_log_send_and_compose_impl
+ _fig_log_call_emit_and_clean_up_after_send_and_compose
+ _fig_log_emitter_get_os_log_and_send_and_compose_flags_and_os_log_type
+ _fig_note_initialize_category_with_default_work_cf
- _FigSignalErrorAtGM
- _fig_log_get_emitter
CStrings:
+ "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
+ "( -73465 )"
+ "-[FigLKTIIRFilter allocateResourcesForMaskSize:]"
+ "-[FigLKTIIRFilter computeLKTIIRFilter:inputSegmentationMask:filteredSegmentationMask:]"
+ "-[FigLKTIIRFilter computeOpticalFlow:inputImage:]"
+ "-[FigLKTIIRFilter initWithMetalContext:]"
+ "-[FigSemanticStyleFilteringV1 _compileShaders]"
+ "-[FigSemanticStyleFilteringV1 _textureFromPixelBuffer:usage:]"
+ "-[FigSemanticStyleFilteringV1 initWithCommandQueue:]"
+ "-[FigSemanticStyleFilteringV1 prepareToProcess:]"
+ "-[FigSemanticStyleFilteringV1 prewarm]"
+ "-[FigSemanticStyleFilteringV1 process]"
+ "<<<< LKT IIR Filter >>>> %s: metalContext is nil"
+ "<<<< SemanticStyle Filtering >>>> %s: Could not init _metalContext"
+ "<<<< SemanticStyle Filtering >>>> %s: Init completed with no error"
+ "<<<< SemanticStyle Filtering >>>> %s: Mask interpolation is %@"
+ "<<<< SemanticStyle Filtering >>>> %s: Unsupported pixel format for caching"
+ "Could not allocate MPSImageGaussianBlur"
+ "Could not allocate MPSImageMultiply"
+ "Could not allocate _blurredMask"
+ "Could not allocate _featheredMask"
+ "Could not allocate _nonFeatheredMask"
+ "Could not allocate _resizedInputImageToMaskSize"
+ "Could not allocate _smoothedMask"
+ "Could not allocate command buffer"
+ "Could not allocate resources for FigLKTIIRFilter"
+ "Could not get displacementFWD from pixelbuffer"
+ "Could not get inputImageTexture from pixelbuffer"
+ "Could not get inputMaskTexture from pixelbuffer"
+ "Could not get outputMaskTexture from pixelbuffer"
+ "Could not init FigLKTIIRFilter"
+ "Input image pixel buffer is NULL"
+ "Input mask is not kCVPixelFormatType_OneComponent16Half"
+ "No command buffer provided"
+ "Optical flow is not available."
+ "Optical has already been computed. This should not happen"
+ "Output mask pixel buffer is NULL"
+ "SemanticStyleFilteringStatusFeatheringFailed"
+ "SemanticStyleFilteringStatusInputError"
+ "SemanticStyleFilteringStatusLKTFilterAllocationFailed"
+ "SemanticStyleFilteringStatusLKTFilterFailed"
+ "SemanticStyleFilteringStatusLKTFilterInitFailed"
+ "SemanticStyleFilteringStatusMPSAllocationFailed"
+ "SemanticStyleFilteringStatusMetalAllocationFailed"
+ "SemanticStyleFilteringStatusMetalTextureAllocationFailed"
+ "SemanticStyleFilteringStatusOtherError"
+ "Shaders compilation failed"
+ "Unable to create a metal texture cache"
+ "_applyFeathering failed"
+ "_copyAndCenterMask failed"
+ "_imageArray textures allocation failed"
+ "_inputSegmentationMaskF16 is nil."
+ "_keyFrameAndMask is nil."
+ "_maskArray textures allocation failed"
+ "_pipelineStates[COPY_AND_CENTER_MASK] is NULL"
+ "_pipelineStates[SMOOTH_STEP] is NULL"
+ "_previousMaskWarped is nil."
+ "_tempMaskTexture is nil."
+ "_tmpCoord is nil."
+ "_tmpDisplacementMap is nil."
+ "_warpedKeyFrameToCurrentFrameCoord is nil."
+ "_warpedKeyFrameToCurrentFrameDisplacementMap is nil."
+ "_warpedKeyFrameToCurrentFrameImage is nil."
+ "_warpedKeyFrameToCurrentFrameMask is nil."
+ "cacheInputMask failed"
+ "computeLKTIIRFilter failed"
+ "disabled"
+ "enabled"
+ "filteredSegmentationMask is nil."
+ "inputImage is nil."
+ "inputSegmentationMask is nil."
+ "kCMBaseObjectError_ParamErr"
+ "kCMBaseObjectError_UnsupportedOperation"
+ "maskToFilter is nil"
+ "opticalFlowDisplacementPixelBuffer is NULL"
+ "semstyle_filtering_trace"
- "%s signalled err=%d at <>:%d"
```
