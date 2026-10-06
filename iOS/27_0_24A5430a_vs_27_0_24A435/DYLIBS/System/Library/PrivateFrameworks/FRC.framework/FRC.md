## FRC

> `/System/Library/PrivateFrameworks/FRC.framework/FRC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x40244` | `0x402b4` | **`+0x70`** |

### Other Changes

```text
Functions:
~ _loadTextureInterleaved : 332 -> 336
~ _saveTextureInterleaved : 328 -> 332
~ _compareBGRAPixelBuffers : 648 -> 656
~ _readYUVPlanar : 472 -> 476
~ _writeYUVPlanar : 480 -> 484
~ _readYUV10bit : 480 -> 488
~ _writeYUV10bit : 472 -> 480
~ ___71-[OpticalFlowE5 encodeConvertLinearBuffer:toPixelBuffer:commandBuffer:]_block_invoke : 488 -> 508
~ -[FlowConsistencyMap maxValueInTexture:] : 336 -> 340
~ -[OpticalFlowAnalyzer processGPUOutputsHistogramsForDeformation:blockWidth:blockHeight:] : 1076 -> 1092
~ _interleave4 : 116 -> 120
~ _deinterleave4 : 108 -> 112
~ _interleave2 : 92 -> 100
~ _deinterleave2 : 92 -> 100
~ -[Normalization calcAnchorParamsFromNormParams:anchor:] : 148 -> 156
```
