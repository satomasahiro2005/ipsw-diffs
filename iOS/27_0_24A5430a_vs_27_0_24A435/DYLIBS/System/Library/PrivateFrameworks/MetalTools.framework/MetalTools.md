## MetalTools

> `/System/Library/PrivateFrameworks/MetalTools.framework/MetalTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1463dc` | `0x147030` | **`+0xc54`** |
| `__AUTH_CONST.__objc_const` | `0x490c8` | `0x49460` | **`+0x398`** |
| `__TEXT.__cstring` | `0x3550d` | `0x356c6` | **`+0x1b9`** |
| `__AUTH_CONST.__cfstring` | `0xf720` | `0xf800` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x1a71c` | `0x1a7f4` | **`+0xd8`** |
| `__TEXT.__const` | `0x5a0` | `0x620` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x6ac8` | `0x6b20` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x5770` | `0x5780` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x6d0` | `0x6d8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x10f8` | `0x10fc` | **`+0x4`** |

### Other Changes

```diff

-  Functions: 8190
-  Symbols:   11968
-  CStrings:  3687
+  Functions: 8202
+  Symbols:   11979
+  CStrings:  3695
Symbols:
+ -[MTLGPUDebugComputeCommandEncoder setBufferUsageTable:textureUsageTable:tensorResidencyTable:bvhUsageTable:textureTypeTable:textureWriteUsageTable:]
+ -[MTLGPUDebugRenderCommandEncoder setBufferUsageTable:textureUsageTable:tensorResidencyTable:bvhUsageTable:textureTypeTable:textureWriteUsageTable:forStage:]
+ -[MTLToolsComputePipelineState forwardProgressUsage]
+ -[MTLToolsComputePipelineState recommendedPersistentThreadgroupsPerGridForThreadsPerThreadgroup:]
+ -[MTLToolsDevice supportsAtomicWaitNotify]
+ -[MTLToolsDevice supportsMXUNarrowTileSizes]
+ -[MTLToolsDevice supportsPackUnpackSmallInteger]
+ -[MTLToolsDevice supportsRGBTextureBuffers]
+ -[MTLToolsDevice supportsSIMDGroupParallelForwardProgress]
+ -[MTLToolsDevice supportsTextureViewMinLOD]
+ -[MTLToolsTexture minLOD]
+ OBJC_IVAR_$_MTLGPUDebugDevice.textureWriteUsageTable
+ _isRGBPixelFormat
- -[MTLGPUDebugComputeCommandEncoder setBufferUsageTable:textureUsageTable:tensorResidencyTable:bvhUsageTable:textureTypeTable:]
- -[MTLGPUDebugRenderCommandEncoder setBufferUsageTable:textureUsageTable:tensorResidencyTable:bvhUsageTable:textureTypeTable:forStage:]
CStrings:
+ "Device does not support textures with pixelFormat(%s)"
+ "MTL_SHADER_VALIDATION_YIELD_CHECK"
+ "Texture buffer with pixelFormat(%s) must be read-only"
+ "minLOD (%f) must be 0.0 because the device does not support TextureViewMinLOD."
+ "minLOD (%f) should be greater than or equal to 0.0."
+ "minLOD (%f) should be less than or equal to mipmapLevelCount (%lu) of the parent texture."
+ "pixelFormat(%s) can only be used with MTLTextureTypeTextureBuffer"
+ "yield-check"
```
