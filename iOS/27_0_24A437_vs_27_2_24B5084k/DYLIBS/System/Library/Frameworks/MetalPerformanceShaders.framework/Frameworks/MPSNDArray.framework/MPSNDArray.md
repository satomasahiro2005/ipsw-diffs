## MPSNDArray

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSNDArray.framework/MPSNDArray`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1131a4` | `0x113020` | **`-0x184`** |
| `__TEXT.__cstring` | `0x126c1` | `0x125b3` | **`-0x10e`** |
| `__AUTH_CONST.__cfstring` | `0x9520` | `0x94e0` | **`-0x40`** |

### Other Changes

```diff

-130.0.19.0.0
+130.1.1.0.0

-  CStrings:  1718
+  CStrings:  1716
Functions:
~ __ZL36EncodeConstantInitializationInternalPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfob : 1768 -> 1716
~ -[MPSNDArrayLinearAttention extractShapesFromQueries:keys:values:decayGates:betaValues:initialState:outputState:output:] : 2736 -> 2888
~ __ZL18validateArrayShapeP10MPSNDArrayP8NSStringSt16initializer_listImE : 284 -> 328
~ __ZL24is_qmm_generic_supportedRK46NDArrayQuantizedMatrixMultiplicationEncodeDataP14QmmGenericArgs : 2032 -> 2048
~ __ZL23EncodeQuantizedGatherNDPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfo : 18592 -> 18616
~ __ZL15EncodeReductionPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfo : 11600 -> 11212
~ __ZL19EncodeArrayIdentityPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfo : 2868 -> 2872
~ __ZL34EncodeQuantizedSDPATileBasedCommonPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfoP9MPSDeviceP10MPSLibraryPK44MPSNDArrayQuantizedScaledDotProductAttention7MTLSize : 10764 -> 10840
~ __ZL19EncodeSDPACommonNewPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfoP9MPSDeviceP10MPSLibraryPK35MPSNDArrayScaledDotProductAttentionj : 5992 -> 5784
~ __ZL30EncodeQuantizedSDPAVectorBasedPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfoP9MPSDeviceP10MPSLibraryPK44MPSNDArrayQuantizedScaledDotProductAttention : 6828 -> 6704
~ __ZL32MPSNDArraySDPACreateUserConstantR36MPSNDArraySDPAStateFunctionConstants : 524 -> 568
~ __ZNK38MPSNDArrayConvolutionDeviceBehaviorA1819GetKernelParametersEP9MPSKernelR50MPSNDArrayConvolutionGradientWithWeightsParametersPv11MPSDataTypeS5_S5_ : 2644 -> 2648
~ __ZL12getArrayType11MPSDataType : 536 -> 556
CStrings:
+ "%@ %p \"%@\" Only MPSDataTypeInt32 destinations are supported for Argument Reductions.\n"
+ "Float8e8m0 inputs cannot be dequantized into Float16 outputs."
- "%@ %p \"%@\" For a MPSDataTypeInt32 source, detination must also be MPSDataTypeInt32.\n"
- "%@ %p \"%@\" For a MPSDataTypeUInt32 source, detination must also be MPSDataTypeUInt32.\n"
- "%@ %p \"%@\" Only MPSDataTypeUInt32 or MPSDataTypeInt32 destinations are supported for Argument Reductions.\n"
- "%@ %p \"%@\" This combination of data types is only supported for MPSNDArrayReduction where the operation is an argument minimum or maximum\n"
```
