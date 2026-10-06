## PerfPowerServicesSignpostReader

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/XPCServices/PerfPowerServicesSignpostReader.xpc/PerfPowerServicesSignpostReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d8f0` | `0x1e340` | **`+0xa50`** |
| `__TEXT.__objc_methname` | `0x5cd3` | `0x5f36` | **`+0x263`** |
| `__DATA.__objc_const` | `0x2728` | `0x27b8` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x2f20` | `0x2fa0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x1740` | `0x17b8` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x14a0` | `0x14f0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x6c8` | `0x6f0` | **`+0x28`** |
| `__TEXT.__cstring` | `0x16ac` | `0x16d0` | **`+0x24`** |
| `__TEXT.__unwind_info` | `0x500` | `0x510` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x280` | `0x28c` | **`+0xc`** |
| `__TEXT.__objc_methtype` | `0xaa9` | `0xaab` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-3486.0.46.502.1
+3486.0.81.502.4

-  Functions: 589
+  Functions: 600

-  CStrings:  1429
+  CStrings:  1447
CStrings:
+ "J"
+ "T@\"NSMutableDictionary\",&,N,V_pendingAnimationIntervalsByBucket"
+ "T@\"NSMutableDictionary\",&,N,V_processedTotalDurationByBucket"
+ "T@\"NSMutableDictionary\",&,N,V_processedWeightedRatioSumByBucket"
+ "_bufferAnimationInterval:forBucketKey:"
+ "_pendingAnimationIntervalsByBucket"
+ "_processBatchForBucketKey:"
+ "_processedTotalDurationByBucket"
+ "_processedWeightedRatioSumByBucket"
+ "addAnimationHitchWithBundleID:interval:"
+ "addGlitchWithBundleID:timestamp:glitchDurationMs:scrollDurationMs:glitchCount:isScrollStart:"
+ "addGlitchWithDuration:scrollDuration:glitchCount:isScrollStart:"
+ "pendingAnimationIntervalsByBucket"
+ "processedTotalDurationByBucket"
+ "processedWeightedRatioSumByBucket"
+ "setAnimationHitchTotalAnimationDuration:weightedGlitchRatioSum:"
+ "setPendingAnimationIntervalsByBucket:"
+ "setProcessedTotalDurationByBucket:"
+ "setProcessedWeightedRatioSumByBucket:"
+ "v32@0:8d16d24"
+ "v32@?0@\"NSString\"8@\"NSNumber\"16^B24"
+ "v44@0:8d16d24Q32B40"
+ "v60@0:8@16d24d32d40Q48B56"
- "G"
- "addGlitchWithBundleID:timestamp:glitchDurationMs:scrollDurationMs:glitchCount:isScrollStart:glitchRatio:animationDuration:"
- "addGlitchWithDuration:scrollDuration:glitchCount:isScrollStart:glitchRatio:animationDuration:"
- "v60@0:8d16d24Q32B40d44d52"
- "v76@0:8@16d24d32d40Q48B56d60d68"
```
