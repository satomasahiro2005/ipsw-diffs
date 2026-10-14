## MPSNDArray

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSNDArray.framework/MPSNDArray`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x113508` | `0x114130` | **`+0xc28`** |

### Other Changes

```diff

-130.1.3.0.0
+130.1.4.0.0
Functions:
~ -[MPSNDArrayLinearAttention buildParamsForQueries:keys:values:decayGates:betaValues:initialState:outputState:output:g_exp:shapes:] : 2516 -> 4632
~ -[MPSNDArrayLinearAttention dispatchExponentiationWithEncoder:decayGates:expGatesPso:shapes:] : 196 -> 468
~ -[MPSNDArrayLinearAttention dispatchChunkParallelWithEncoder:commandBuffer:params:A_chunks:B_chunks:initialState:S_state:shapes:laHash:] : 2300 -> 2336
~ -[MPSNDArrayLinearAttention encodeImpl:commandBuffer:queries:keys:values:decayGates:betaValues:initialState:outputState:output:] : 2884 -> 3572
```
