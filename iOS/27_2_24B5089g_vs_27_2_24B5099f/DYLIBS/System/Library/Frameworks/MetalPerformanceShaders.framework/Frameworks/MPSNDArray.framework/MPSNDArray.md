## MPSNDArray

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSNDArray.framework/MPSNDArray`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x113020` | `0x113508` | **`+0x4e8`** |
| `__DATA_CONST.__const` | `0x20c68` | `0x20db8` | **`+0x150`** |
| `__TEXT.__gcc_except_tab` | `0x4ed8` | `0x4f24` | **`+0x4c`** |
| `__AUTH_CONST.__cfstring` | `0x94e0` | `0x9500` | **`+0x20`** |
| `__TEXT.__cstring` | `0x125b3` | `0x125cb` | **`+0x18`** |

### Other Changes

```diff

-130.1.1.0.0
+130.1.3.0.0

-  Functions: 2477
-  Symbols:   5103
-  CStrings:  1716
+  Functions: 2478
+  Symbols:   5105
+  CStrings:  1717
Symbols:
+ __ZNSt3__16vectorINS_4pairIPKiPKjEENS_9allocatorIS6_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS_4pairIPKiPKjEENS_9allocatorIS6_EEE24__emplace_back_slow_pathIJS6_EEEPS6_DpOT_
Functions:
~ __ZL12EncodeDWConvPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfo : 6924 -> 6992
~ -[MPSNDArrayLinearAttention encodeImpl:commandBuffer:queries:keys:values:decayGates:betaValues:initialState:outputState:output:] : 2860 -> 2884
~ __ZL23EncodeQuantizedGatherNDPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfo : 18616 -> 19524
+ __ZNSt3__16vectorINS_4pairIPKiPKjEENS_9allocatorIS6_EEE24__emplace_back_slow_pathIJS6_EEEPS6_DpOT_
~ __ZL10EncodeSDPAPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfo : 3612 -> 3648
~ __ZNK38MPSNDArrayConvolutionDeviceBehaviorA1819GetKernelParametersEP9MPSKernelR50MPSNDArrayConvolutionGradientWithWeightsParametersPv11MPSDataTypeS5_S5_ : 2648 -> 2644
CStrings:
+ "depthwiseConv3d_cFirst4"
```
