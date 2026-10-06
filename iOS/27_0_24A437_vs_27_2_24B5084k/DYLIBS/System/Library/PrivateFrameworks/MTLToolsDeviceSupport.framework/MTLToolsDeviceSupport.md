## MTLToolsDeviceSupport

> `/System/Library/PrivateFrameworks/MTLToolsDeviceSupport.framework/MTLToolsDeviceSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x328c2` | `0x32702` | **`-0x1c0`** |
| `__TEXT.__text` | `0x31568` | `0x314c0` | **`-0xa8`** |
| `__TEXT.__const` | `0x3b0` | `0x3a0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xb20` | `0xb18` | **`-0x8`** |

### Other Changes

```diff

-  Functions: 810
+  Functions: 809

-  CStrings:  5388
+  CStrings:  5374
Functions:
~ __ZN8GPUTools3MTL24GetMTLFeatureSetAsStringEyb : 892 -> 744
~ __ZN8GPUTools3MTL23GetMTLGPUFamilyAsStringEyb : 548 -> 588
- sub_28e49683c
~ __ZN8GPUTools3MTL25GetMTLPixelFormatAsStringEyb : 5760 -> 5740
CStrings:
+ "0xffffc0e9"
+ "0xffffc0ea"
- "Apple8"
- "MTLFeatureSet_tvOS_GPUFamily2_v1"
- "MTLFeatureSet_tvOS_GPUFamily2_v2"
- "MTLFeatureSet_watchOS_GPUFamily1_v1"
- "MTLFeatureSet_watchOS_GPUFamily2_v1"
- "MTLGPUFamilyApple8"
- "MTLPixelFormatYCBCRA8_444_1P"
- "YCBCRA8_444_1P"
- "[%@ computeCommandEncoderWithParallelExecution]"
- "[%@ dispatchBarrier]"
- "kDYFEMTLCommandBuffer_computeCommandEncoderWithParallelExecution"
- "kDYFEMTLComputeCommandEncoder_dispatchBarrier"
- "tvOS_GPUFamily2_v1"
- "tvOS_GPUFamily2_v2"
- "watchOS_GPUFamily1_v1"
- "watchOS_GPUFamily2_v1"
```
