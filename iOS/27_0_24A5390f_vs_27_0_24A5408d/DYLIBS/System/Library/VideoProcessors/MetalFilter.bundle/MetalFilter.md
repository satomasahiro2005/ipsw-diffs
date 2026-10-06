## MetalFilter

> `/System/Library/VideoProcessors/MetalFilter.bundle/MetalFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xaf9` | `0x3af` | **`-0x74a`** |
| `__TEXT.__text` | `0x3ecc` | `0x37b4` | **`-0x718`** |
| `__TEXT.__oslogstring` | `0x1ac` | `—` | **`-0x1ac`** |
| `__AUTH_CONST.__cfstring` | `0x100` | `0xc0` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x110` | `0xe8` | **`-0x28`** |
| `__DATA_DIRTY.__common` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__const` | `0x20` | `0x10` | **`-0x10`** |

### Other Changes

```diff

-761.0.0.0.3
+764.22.5.122.2

-  Functions: 115
-  Symbols:   75
-  CStrings:  91
+  Functions: 98
+  Symbols:   71
+  CStrings:  40
Symbols:
+ _FigSignalErrorAtGM
+ _fig_log_get_emitter
- _FigSignalErrorAt3
- __os_log_send_and_compose_impl
- _fig_log_call_emit_and_clean_up_after_send_and_compose
- _fig_log_emitter_get_os_log_and_send_and_compose_flags_and_os_log_type
- _fig_note_initialize_category_with_default_work_cf
- _os_log_type_enabled
CStrings:
+ "%s signalled err=%d at <>:%d"
- "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
- "( -73465 )"
- "+[FigColorCubeMetalFilter createCubeTexture:ofSize:cubesCount:textureType:withDevice:]"
- "+[FigColorCubeMetalFilter loadCube:ofSize:intoTexture:toSliceIndex:]"
- "-[FigColorCubeMetalFilter _prewarmWithTuningParameters:]"
- "-[FigColorCubeMetalFilter createPipelineStateWithVertexFunctionName:fragmentName:isLuma:useBgCube:manyFgCubes:colorSpace:mixInGammaDomain:]"
- "-[FigColorCubeMetalFilter createPipelineStatesForCubeConversionWithVertexFunctionName:]"
- "-[FigColorCubeMetalFilter createPipelineStatesWithFragmentName:vertexFunctionName:]"
- "-[FigColorCubeMetalFilter initWithCommandQueue:]"
- "-[FigColorCubeMetalFilter prepareToProcess:]"
- "-[FigColorCubeMetalFilter purgeResources]"
- "-[FigColorCubeMetalFilter resetState]"
- "-[FigColorCubeMetalFilter runWithInputPixelBuffer:mattePixelBuffer:outputPixelBuffer:targetRectangle:]"
- "-[FigColorCubeMetalFilter setBackgroundCubeWithName:data:]"
- "-[FigColorCubeMetalFilter setForegroundCubesWithNames:data:]"
- "3D cubes support only one slice"
- "<<<< FigColorCube >>>> %s: %s"
- "<<<< FigColorCube >>>> %s: FigColor doesn't implement purgeResources"
- "<<<< FigColorCube >>>> %s: FigColor doesn't implement resetState"
- "<<<< FigColorCube >>>> %s: FigColor prewarms shaders"
- "<<<< FigColorCube >>>> %s: Perform color Cube conversion for Background cube"
- "<<<< FigColorCube >>>> %s: Perform color Cube conversion for Foreground cube"
- "<<<< FigColorCube >>>> %s: background cube is set to nil"
- "Cube texture dimension mismatch"
- "FigColor failed allocateResources call"
- "FigColor failed createKernels call"
- "FigColor uses Single-pass"
- "FigColor uses Two-pass"
- "FigColorCubeMetalFilterStatusAllocationError"
- "FigColorCubeMetalFilterStatusCompilationError"
- "_colorCubePipelineStateUV[useBgCube][manyFgCubes][colorSpace][mix] is NULL"
- "_colorCubePipelineStateY[useBgCube][manyFgCubes][colorSpace][mix] is NULL"
- "_colorCubePipelineState[useBgCube][manyFgCubes][colorSpace][mix] is NULL"
- "_metal is NULL"
- "ccube_trace"
- "com.apple.coremedia"
- "commandBuffer is NULL"
- "constantValues is NULL"
- "device is NULL"
- "fullRangeVertexBuf is NULL"
- "inputTex is NULL"
- "inputTexUV is NULL"
- "kCMBaseObjectError_AllocationFailed"
- "kCMBaseObjectError_UnsupportedOperation"
- "matteTex is NULL"
- "outputTex is NULL"
- "outputTexUV is NULL"
- "renderPipelineColorAttachmentDescriptor is NULL"
- "texture is NULL"
- "textureDesc is NULL"
- "vd is NULL"
- "wrong-sized color cube"
```
