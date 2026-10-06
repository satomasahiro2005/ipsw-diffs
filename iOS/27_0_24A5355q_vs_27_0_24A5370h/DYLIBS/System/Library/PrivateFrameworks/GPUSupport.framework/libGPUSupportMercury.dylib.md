## libGPUSupportMercury.dylib

> `/System/Library/PrivateFrameworks/GPUSupport.framework/libGPUSupportMercury.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x268` | `0x260` | **`-0x8`** |
| `__TEXT.__text` | `0x8614` | `0x8610` | **`-0x4`** |

### Other Changes

```text
Functions:
~ _gpusLoadTransformFeedbackBuffers : 200 -> 204
~ _gpumUpdateUniformBuffers : 308 -> 320
~ _gpumCompCreateFence : 240 -> 236
~ _gpumCompDestroyFence : 52 -> 48
~ _gpusQueueSubmitDataBuffers : 420 -> 428
~ _gpusComputeSubmitDataBuffers : 452 -> 460
~ _gpusSubmitDataBuffers : 512 -> 520
~ _gldClearFence : 124 -> 116
~ _gpulAllocFenceIndexOnQueue : 604 -> 600
~ _gldSetFenceOnContext : 352 -> 348
~ _gpumChoosePixelFormat : 1720 -> 1732
~ _gpumInitializeIOData : 592 -> 540
~ _gldObjectUnpurgeable : 772 -> 780
~ _gpumCreateQuery : 780 -> 776
~ _gpumDestroyQuery : 152 -> 148
~ _gpumLoadCurrentQueries : 228 -> 232
~ _gpusLoadCurrentSamplers : 412 -> 392
~ _gldDestroyShareGroup : 160 -> 176
~ _gpulDeleteKernelTexture : 184 -> 204
~ _gpumGetTextureLevelInfo : 820 -> 832
~ _gpusLoadCurrentTextures : 892 -> 872
~ _gpusCreateZeroTexture : 856 -> 848
~ _gldGetTextureAllocationIdentifiers : 308 -> 316
~ _gpusGetKernelTextureIOSurface : 860 -> 868
```
