## MPSNDArray

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSNDArray.framework/MPSNDArray`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12d188` | `0x10d2bc` | **`-0x1fecc`** |
| `__TEXT.__const` | `0x8ac30` | `0x928b0` | **`+0x7c80`** |
| `__TEXT.__gcc_except_tab` | `0x4794` | `0x4bac` | **`+0x418`** |
| `__TEXT.__cstring` | `0x121d6` | `0x1231c` | **`+0x146`** |
| `__TEXT.__unwind_info` | `0x1a88` | `0x1b28` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x13` | `0x27` | **`+0x14`** |
| `__DATA.__bss` | `0x648` | `0x638` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x78` | `0x88` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x5a8` | `0x5b0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x17c0` | `0x17c8` | **`+0x8`** |

### Other Changes

```diff

-130.0.15.0.0
+130.0.19.0.0

-  Functions: 2450
-  Symbols:   5061
-  CStrings:  1669
+  Functions: 2453
+  Symbols:   5067
+  CStrings:  1688
Symbols:
+ -[MPSNDArrayAffineInt4Dequantize workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayConvolution2D workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayConvolution2DGradientWithInput workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayConvolution2DGradientWithWeights workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayConvolution3D workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayConvolution3DGradientWithInput workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayConvolution3DGradientWithWeights workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayFourierTransform workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayFusedDepthwisePointwiseConvolution workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayHammingDistanceKernel workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayIdentity workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayLUTDequantize workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayLUTGEMV workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayMaterializeSparseTensor workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayMatrixMultiplication workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayMatrixMultiplicationGradient workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayMatrixMultiplicationSparse workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayMultiaryBase workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayPoolingKernel workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayQuantizedMatrixMultiplication workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayQuantizedScaledDotProductAttention workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayReduction workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayScaledDotProductAttention workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayStencilKernel workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayStitchedReduction workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ -[MPSNDArrayVectorLUTDequantize workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:encoder:]
+ GCC_except_table103
+ GCC_except_table112
+ GCC_except_table113
+ GCC_except_table123
+ GCC_except_table133
+ GCC_except_table144
+ GCC_except_table15
+ GCC_except_table34
+ GCC_except_table38
+ GCC_except_table39
+ GCC_except_table43
+ GCC_except_table57
+ GCC_except_table67
+ GCC_except_table68
+ GCC_except_table75
+ GCC_except_table77
+ GCC_except_table83
+ _.str
+ _MPSIsPerfTestCmdSignpostEnabled
+ __Z42MPSKernelEncodeSignpostPerfTestCommandlinePK24MPSNDArrayMultiaryKernelPK23NDArrayMultiaryCallInfoNSt3__112basic_stringIcNS5_11char_traitsIcEENS5_9allocatorIcEEEESB_PU35objcproto24MTLComputeCommandEncoder11objc_object
+ __ZL12getArrayType11MPSDataType
+ __ZL33MPSKernelBuildPerfTestCommandlinePK23NDArrayMultiaryCallInfoNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEES8_b
+ __ZL35MPSNDArrayConvolutionLogCommandLineP24MPSNDArrayMultiaryKernelR28NDArrayConvolutionEncodeDataPK23NDArrayMultiaryCallInfoNSt3__112basic_stringIcNS6_11char_traitsIcEENS6_9allocatorIcEEEEbPU35objcproto24MTLComputeCommandEncoder11objc_object
+ __ZL37MPSNDArrayConvolution3DLogCommandLineP24MPSNDArrayMultiaryKernelR30NDArrayConvolution3DEncodeDataPK23NDArrayMultiaryCallInfoNSt3__112basic_stringIcNS6_11char_traitsIcEENS6_9allocatorIcEEEEPU35objcproto24MTLComputeCommandEncoder11objc_object
+ __ZL44MPSNDArrayQuantizedConvolutionLogCommandLineP24MPSNDArrayMultiaryKernelR28NDArrayConvolutionEncodeDataPK23NDArrayMultiaryCallInfoNSt3__112basic_stringIcNS6_11char_traitsIcEENS6_9allocatorIcEEEEbPU35objcproto24MTLComputeCommandEncoder11objc_object
+ __ZN19MPSSignpostMetadata3addIyEERS_PKcT_
+ __ZN29MPSWorkloadStatsEventSignpostC2ERK19MPSSignpostMetadata
+ _matmulA18STable
- -[MPSNDArrayAffineInt4Dequantize workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayConvolution2D workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayConvolution2DGradientWithInput workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayConvolution2DGradientWithWeights workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayConvolution3D workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayConvolution3DGradientWithInput workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayConvolution3DGradientWithWeights workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayFourierTransform workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayFusedDepthwisePointwiseConvolution workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayHammingDistanceKernel workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayIdentity workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayLUTDequantize workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayLUTGEMV workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayMaterializeSparseTensor workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayMatrixMultiplication workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayMatrixMultiplicationGradient workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayMatrixMultiplicationSparse workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayMultiaryBase workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayPoolingKernel workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayQuantizedMatrixMultiplication workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayQuantizedScaledDotProductAttention workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayReduction workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayScaledDotProductAttention workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayStencilKernel workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayStitchedReduction workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- -[MPSNDArrayVectorLUTDequantize workloadStatisticsForSourceArrays:destArrays:kernel:kernelDAGObject:sourceState:]
- GCC_except_table102
- GCC_except_table114
- GCC_except_table122
- GCC_except_table132
- GCC_except_table143
- GCC_except_table16
- GCC_except_table25
- GCC_except_table32
- GCC_except_table35
- GCC_except_table55
- GCC_except_table60
- GCC_except_table66
- GCC_except_table74
- GCC_except_table76
- GCC_except_table84
- GCC_except_table92
- __ZL33EncodeTextureMatrixMultiplicationPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfo
- __ZL35MPSNDArrayConvolutionLogCommandLineP24MPSNDArrayMultiaryKernelR28NDArrayConvolutionEncodeDataPK23NDArrayMultiaryCallInfoNSt3__112basic_stringIcNS6_11char_traitsIcEENS6_9allocatorIcEEEEb
- __ZL37MPSNDArrayConvolution3DLogCommandLineP24MPSNDArrayMultiaryKernelR30NDArrayConvolution3DEncodeDataPK23NDArrayMultiaryCallInfoNSt3__112basic_stringIcNS6_11char_traitsIcEENS6_9allocatorIcEEEE
- __ZL44MPSNDArrayQuantizedConvolutionLogCommandLineP24MPSNDArrayMultiaryKernelR28NDArrayConvolutionEncodeDataPK23NDArrayMultiaryCallInfoNSt3__112basic_stringIcNS6_11char_traitsIcEENS6_9allocatorIcEEEEb
- __ZN28MPSKernelEncodeEventSignpostC2ERK19MPSSignpostMetadata
- __ZZL28EncodeMatrixMultiplyQ4IntoQ8PKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfoE9predicate
CStrings:
+ "AffineInt4Dequantize"
+ "EncoderID"
+ "FourierTransform"
+ "FusedDepthwisePointwiseConvolution"
+ "HammingDistance"
+ "Identity"
+ "LUTDequantize"
+ "LUTGEMV"
+ "MPSPerfTestCmdline"
+ "MPSWorkloadStats"
+ "MaterializeSparseTensor"
+ "MatrixMultiplicationSparse"
+ "PerfTestCmdline"
+ "Pooling"
+ "QuantizedMatrixMultiplication"
+ "QuantizedScaledDotProductAttention"
+ "Reduction"
+ "Stencil"
+ "StitchedReduction"
+ "VectorLUTDequantize"
- "MPSKernelEncode"
```
