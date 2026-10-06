## MattingV2

> `/System/Library/VideoProcessors/MattingV2.bundle/MattingV2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b5c` | `0xe36c` | **`-0x27f0`** |
| `__TEXT.__oslogstring` | `0x104a` | `0xca` | **`-0xf80`** |
| `__TEXT.__cstring` | `0x2d61` | `0x2862` | **`-0x4ff`** |
| `__TEXT.__const` | `0xdf0` | `0xdc0` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x288` | `0x268` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x2e0` | `0x2c8` | **`-0x18`** |
| `__DATA.__common` | `0x10` | `—` | **`-0x10`** |

### Other Changes

```diff

-764.40.5.0.0
+764.40.7.0.0

-  Functions: 401
-  Symbols:   116
-  CStrings:  362
+  Functions: 378
+  Symbols:   112
+  CStrings:  298
Symbols:
+ _FigSignalErrorAtGM
+ _objc_retain_x5
- _FigSignalErrorAt3
- __os_log_send_and_compose_impl
- _fig_log_call_emit_and_clean_up_after_send_and_compose
- _fig_log_emitter_get_os_log_and_send_and_compose_flags_and_os_log_type
- _objc_retain_x25
- _objc_retain_x28
CStrings:
+ "%s signalled err=%d at <>:%d"
- "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
- "( -73465 )"
- "-[FigMatting _allocateResources]"
- "-[FigMatting _prewarmMPSKernels]"
- "-[FigMatting encodeAddTexturesToCommandBuffer:sourceTextureA:sourceTextureB:destinationTexture:thresholdBeginValue:thresholdEndValue:]"
- "-[FigMatting encodeComposeRGBAGuideToCommandBuffer:rgbTexture:alphaTexture:destinationTexture:rgbWeight:]"
- "-[FigMatting encodePreprocessSkinToCommandBuffer:inputSkinTexture:faceNonSkinTextures:outputSkinTexture:]"
- "-[FigMatting initWithCommandQueue:]"
- "-[FigMatting process]"
- "-[FigMatting setOptions:]"
- "-[FocalPlaneV2 encodeDisparityRefinementPreprocessingOn:alphaTexture:inputDisparityTexture:outputDisparityTexture:configuration:]"
- "-[FocalPlaneV2 encodeFocalPlaneCalcOn:disparityTexture:]"
- "-[FocalPlaneV2 encodeMinMaxOn:inputTexture:]"
- "-[MattingV2TuningParameters getSemanticConfigurationsFor:mattingConfiguration:]"
- "-[MattingV2TuningParameters initWithTuningDictionary:]"
- "-[MattingV2TuningParameters parseSemanticConfiguration:semanticKey:mattingConfiguration:]"
- "-[Texture2DWrapper initWithTexture:textureArray:]"
- "<<<< MattingV2 >>>> %s: Allocating %lux%lu constraints texture for %@"
- "<<<< MattingV2 >>>> %s: Allocating disparity refinement guide (%lux%lu)"
- "<<<< MattingV2 >>>> %s: Allocating resources. Enabled outputs: %@"
- "<<<< MattingV2 >>>> %s: Allocation of resources succeeded. Size of allocated intermediates: %lu KB"
- "<<<< MattingV2 >>>> %s: Breach of integration contract. Disparity refinement configurationVersion was 0, but FigMattingOutputRefinedDisparity was enabled. Performing disparity refinement anyway."
- "<<<< MattingV2 >>>> %s: Depth filter is enabled. Composing RGBD guide"
- "<<<< MattingV2 >>>> %s: Disparity refinement enabled using version: %d."
- "<<<< MattingV2 >>>> %s: Enabled outputs: %@"
- "<<<< MattingV2 >>>> %s: Encoding _addTexturesKernel (%lux%lu) + (%lux%lu) -> (%lux%lu)"
- "<<<< MattingV2 >>>> %s: Encoding _composeRGBAGuideKernel rgb (%lux%lu), a (%lux%lu) -> rgba (%lux%lu)"
- "<<<< MattingV2 >>>> %s: Encoding constraints computation for: %@"
- "<<<< MattingV2 >>>> %s: Encoding disparity preprocessing"
- "<<<< MattingV2 >>>> %s: Encoding disparity refinement (version: %d)"
- "<<<< MattingV2 >>>> %s: Encoding disparity refinement guide (%lux%lu)"
- "<<<< MattingV2 >>>> %s: Encoding exclusion of non-skin for faceObservation: %@"
- "<<<< MattingV2 >>>> %s: Encoding matting for collection: %@"
- "<<<< MattingV2 >>>> %s: Encoding skin preprocessing"
- "<<<< MattingV2 >>>> %s: Face observation had no faceSegments property. Maybe inference failed? Skipping this face!"
- "<<<< MattingV2 >>>> %s: Face segment observations provided: %lu"
- "<<<< MattingV2 >>>> %s: Failed to add semantic output %d to output collection. Output will not be computed."
- "<<<< MattingV2 >>>> %s: Failed to create non-skin pixelBuffer for faceSegmentObservation (error: %@)"
- "<<<< MattingV2 >>>> %s: Failed to find key %@ in tuning parameters dictionary. Available keys: %@. Trying to continue parsing with the first key: %@ "
- "<<<< MattingV2 >>>> %s: Failed to perform disparity refinement. _refinedDisparityFilter or _preprocessedDisparity was nil"
- "<<<< MattingV2 >>>> %s: Failed to preallocate faceNonSkinTexture intermediate. Texture will be allocated on the fly."
- "<<<< MattingV2 >>>> %s: Incomplete or missing plist. Going with defaults."
- "<<<< MattingV2 >>>> %s: Matting tuning dictionary is not the same for %@ and %@. This is not supported. Will always use tuning parameters for: %@"
- "<<<< MattingV2 >>>> %s: Parsed unexpected tuning structure. The key %@ was not found in any of the specified dictionaries: %@. Defaulting to the value: %@"
- "<<<< MattingV2 >>>> %s: Parsing semantic tuning parameters for outputKey: %@ "
- "<<<< MattingV2 >>>> %s: Performance note: Creating MTLTextureType2DArray texture view."
- "<<<< MattingV2 >>>> %s: Performance problem: Failed to bind MTLTexture to faceSegmentProbabilityPixelBuffer. Allocating intermediate texture and copying data on the CPU."
- "<<<< MattingV2 >>>> %s: Performance problem: No matching preallocated faceNonSkinTexture available. New texture will be allocated."
- "<<<< MattingV2 >>>> %s: Provided configurationVersion is negative. Defaulting to configuration 0."
- "<<<< MattingV2 >>>> %s: Provided configurationVersion is unsupported. Defaulting to configuration 0."
- "<<<< MattingV2 >>>> %s: Tuning parameters from plist received"
- "<<<< MattingV2 >>>> %s: Unexpected FigMattingTuningConfiguration. Defaulting to FigMattingTuningConfigurationFine"
- "<<<< MattingV2 >>>> %s: Unexpected semantic output identifier: %u; no output configuration will be returned"
- "<<<< MattingV2 >>>> %s: Unsupported resolution mode %u. Falling back to %ux%u"
- "<<<< MattingV2 >>>> %s: Using provided metal command queue %p"
- "<<<< MattingV2 >>>> %s: Using syntheticFocusRectangle: (%.2f, %.2f), %.2f x %.2f"
- "<<<< MattingV2 >>>> %s: WARNING: Failed to parse disparity refinement version from SDOFRenderingParameters. Falling back to disparity refinement version 0; options dictionary had following keys: %@"
- "<<<< MattingV2 >>>> %s: syntheticFocusRectangle was not set -- falling back to default value: (%.2f, %.2f), %.2f x %.2f"
- "_readKeyWithDefault"
- "commandBuffer is NULL"
- "encoder is NULL"
- "inputDisparity has incorrect pixel format"
- "inputDisparityTexture.height != outputDisparityTexture.height"
- "inputDisparityTexture.width != outputDisparityTexture.width"
- "kCMBaseObjectError_ParamErr"
```
