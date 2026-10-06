## MPSNDArray

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSNDArray.framework/MPSNDArray`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x928b0` | `0x9c9b0` | **`+0xa100`** |
| `__TEXT.__text` | `0x10d2bc` | `0x1131a4` | **`+0x5ee8`** |
| `__DATA_CONST.__const` | `0x1fd08` | `0x20c68` | **`+0xf60`** |
| `__TEXT.__cstring` | `0x1231c` | `0x126c1` | **`+0x3a5`** |
| `__TEXT.__gcc_except_tab` | `0x4bac` | `0x4ed8` | **`+0x32c`** |
| `__AUTH_CONST.__cfstring` | `0x9260` | `0x9520` | **`+0x2c0`** |
| `__AUTH_CONST.__const` | `0x45c0` | `0x4800` | **`+0x240`** |
| `__TEXT.__unwind_info` | `0x1b28` | `0x1b78` | **`+0x50`** |
| `__DATA.__data` | `0x9c4` | `0x9ec` | **`+0x28`** |
| `__DATA.__bss` | `0x638` | `0x650` | **`+0x18`** |

### Other Changes

```diff

-  Functions: 2453
-  Symbols:   5067
-  CStrings:  1688
+  Functions: 2477
+  Symbols:   5103
+  CStrings:  1718
Symbols:
+ GCC_except_table106
+ GCC_except_table117
+ GCC_except_table52
+ GCC_except_table60
+ GCC_except_table73
+ GCC_except_table90
+ GCC_except_table91
+ __Z30MPSNDArrayScanA19BehaviorsCtorP9MPSDevicey
+ __Z30MPSNDArraySortA19BehaviorsCtorP9MPSDevicey
+ __Z30ndArrayA19MatMulDeviceBehaviorP9MPSDevicey
+ __ZL15directA19GTable
+ __ZL17winogradA19GTable
+ __ZL36MPSNDArrayA19Int4FunctionConstructorPU21objcproto10MTLLibrary11objc_objectPK13MPSKernelInfoRK23MPSFunctionConstantListRK33MPSFunctionConstructorExtraParamsPP7NSError
+ __ZN32MPSNDArrayScanDeviceBehaviorsA19D0Ev
+ __ZN32MPSNDArrayScanDeviceBehaviorsA19D1Ev
+ __ZN32MPSNDArraySortDeviceBehaviorsA19D0Ev
+ __ZN32MPSNDArraySortDeviceBehaviorsA19D1Ev
+ __ZN33MPSNDArrayMatMulA18DeviceBehaviorC2EP9MPSDevicey
+ __ZN33MPSNDArrayMatMulA19DeviceBehaviorD0Ev
+ __ZN33MPSNDArrayMatMulA19DeviceBehaviorD1Ev
+ __ZNK32MPSNDArrayScanDeviceBehaviorsA1910getThreadsEv
+ __ZNK32MPSNDArrayScanDeviceBehaviorsA1917EncodeNDArrayScanEPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfoP9MPSDeviceP10MPSLibraryP8NSStringm23MPSNDArrayScanOperationmbb
+ __ZNK32MPSNDArraySortDeviceBehaviorsA1910getThreadsEv
+ __ZNK32MPSNDArraySortDeviceBehaviorsA1917EncodeNDArraySortEP14MPSNDArraySortPU19objcproto9MTLDevice11objc_objectPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfoP9MPSDeviceP10MPSLibraryP8NSStringmP14MPSNDArrayScanmbb
+ __ZNK32MPSNDArraySortDeviceBehaviorsA1918isArgsortSupportedEv
+ __ZNK32MPSNDArraySortDeviceBehaviorsA1923isSortGradientSupportedEv
+ __ZNK33MPSNDArrayMatMulA19DeviceBehavior17IsMatMulSupportedEPKvPK23NDArrayMultiaryCallInfoPNSt3__18optionalIbEE
+ __ZNK33MPSNDArrayMatMulA19DeviceBehavior30EncodeArrayMultiplyI4I2IntoF16EPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfo
+ __ZNK33MPSNDArrayMatMulA19DeviceBehavior32IsQuantizedVectorKernelPreferredEP46NDArrayQuantizedMatrixMultiplicationEncodeData
+ __ZNK33MPSNDArrayMatMulA19DeviceBehavior33GetKernelDispatchParametersForKeyEP9MPSKernelR22MPSNDArrayA18MatMulKeyP32MPSMatMulAutoTuningParametersA18
+ __ZNK33MPSNDArrayMatMulA19DeviceBehavior35_A18GEMMHeuristicForLowCoreCountGPUER22MPSNDArrayA18MatMulKeyP32MPSMatMulAutoTuningParametersA18m
+ __ZTV32MPSNDArrayScanDeviceBehaviorsA19
+ __ZTV32MPSNDArraySortDeviceBehaviorsA19
+ __ZTV33MPSNDArrayMatMulA19DeviceBehavior
+ __ZZNK33MPSNDArrayMatMulA19DeviceBehavior30EncodeArrayMultiplyI4I2IntoF16EPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfoE9predicate
+ ____ZNK32MPSNDArrayScanDeviceBehaviorsA1917EncodeNDArrayScanEPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfoP9MPSDeviceP10MPSLibraryP8NSStringm23MPSNDArrayScanOperationmbb_block_invoke
+ ____ZNK33MPSNDArrayMatMulA19DeviceBehavior30EncodeArrayMultiplyI4I2IntoF16EPKvPU35objcproto24MTLComputeCommandEncoder11objc_objectPU27objcproto16MTLCommandBuffer11objc_objectPK23NDArrayMultiaryCallInfo_block_invoke
+ ___block_descriptor_44_e5_v8?0l
+ _matmulA20PTable
- GCC_except_table57
- GCC_except_table58
- GCC_except_table68
CStrings:
+ "At least one of the matrix should be quantized to i4"
+ "At most one of the matrix should be quantized to i4"
+ "MPS_MATMUL_NMT_KSPLITS"
+ "MPS_MATMUL_NMT_REGISTER_VEC"
+ "MPS_MATMUL_NMT_SIMDM"
+ "MPS_MATMUL_NMT_UNROLLK"
+ "MPS_MATMUL_NMT_UNROLLM"
+ "MPS_ONESWEEP_RADIX_SORT_USE_YIELD"
+ "MPS_SFE_SCAN_USE_YIELD"
+ "MPS_USE_MULTI_PASS_RADIX_SORT"
+ "Matrix should be int4 quantized"
+ "Onesweep radix sort requries simd group parallel forward progress guarantee, which is not supported by this device."
+ "Vector should be half/fp16"
+ "decoupledLookbackScanInitializeDispatch"
+ "decoupledLookback_scan_add"
+ "decoupledLookback_scan_max"
+ "decoupledLookback_scan_min"
+ "decoupledLookback_scan_mul"
+ "gemv_nmt"
+ "min value and zero point is not yet supported"
+ "onesweep_histogram"
+ "onesweep_histogram_initialize"
+ "onesweep_scatter"
+ "onesweep_scatter_initialize"
+ "q4q8_gemv"
+ "scale buffer missing"
+ "scale missing for quantized matrix"
+ "simdM * kSplits must be <= 32"
+ "unrollFactorK must be <= 32"
+ "unrollFactorK must be <= 8"
```
