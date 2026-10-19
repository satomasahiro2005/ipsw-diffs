## MTLToolsDeviceSupport

> `/System/Library/PrivateFrameworks/MTLToolsDeviceSupport.framework/MTLToolsDeviceSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x32702` | `0x328c2` | **`+0x1c0`** |
| `__TEXT.__text` | `0x314c0` | `0x31568` | **`+0xa8`** |
| `__TEXT.__const` | `0x3a0` | `0x3b0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xb18` | `0xb20` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 809
+  Functions: 810

-  CStrings:  5374
+  CStrings:  5388
Functions:
~ __ZN8GPUTools3MTL24GetMTLFeatureSetAsStringEyb : 744 -> 892
~ __ZN8GPUTools3MTL23GetMTLGPUFamilyAsStringEyb : 588 -> 548
+ sub_2953fe83c
~ __ZN8GPUTools3MTL25GetMTLPixelFormatAsStringEyb : 5740 -> 5760
CStrings:
+ "Apple8"
+ "MTLFeatureSet_tvOS_GPUFamily2_v1"
+ "MTLFeatureSet_tvOS_GPUFamily2_v2"
+ "MTLFeatureSet_watchOS_GPUFamily1_v1"
+ "MTLFeatureSet_watchOS_GPUFamily2_v1"
+ "MTLGPUFamilyApple8"
+ "MTLPixelFormatYCBCRA8_444_1P"
+ "YCBCRA8_444_1P"
+ "[%@ computeCommandEncoderWithParallelExecution]"
+ "[%@ dispatchBarrier]"
+ "kDYFEMTLCommandBuffer_computeCommandEncoderWithParallelExecution"
+ "kDYFEMTLComputeCommandEncoder_dispatchBarrier"
+ "tvOS_GPUFamily2_v1"
+ "tvOS_GPUFamily2_v2"
+ "watchOS_GPUFamily1_v1"
+ "watchOS_GPUFamily2_v1"
- "0xffffc0e9"
- "0xffffc0ea"
```
