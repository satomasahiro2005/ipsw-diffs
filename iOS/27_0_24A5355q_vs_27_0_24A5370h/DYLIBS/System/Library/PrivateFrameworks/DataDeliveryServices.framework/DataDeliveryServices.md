## DataDeliveryServices

> `/System/Library/PrivateFrameworks/DataDeliveryServices.framework/DataDeliveryServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2992c` | `0x29e48` | **`+0x51c`** |
| `__TEXT.__oslogstring` | `0x3c81` | `0x3d7d` | **`+0xfc`** |
| `__DATA_CONST.__const` | `0xf70` | `0x1010` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x1920` | `0x19a0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1671` | `0x16e5` | **`+0x74`** |
| `__AUTH_CONST.__objc_const` | `0x8de0` | `0x8e10` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x15e0` | `0x1608` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x2a3c` | `0x2a64` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x320` | `0x330` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xc68` | `0xc70` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x228` | `0x22c` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x618` | `0x61c` | **`+0x4`** |

### Other Changes

```diff

-110.0.0.0.0
+113.0.0.0.0

+  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels

-  Functions: 1035
-  Symbols:   1922
-  CStrings:  553
+  Functions: 1042
+  Symbols:   1937
+  CStrings:  561
Symbols:
+ -[DDSServer prewarmEmbeddingAssets]
+ -[DDSUAFManager operationQueue]
+ -[DDSUAFManager setOperationQueue:]
+ GCC_except_table23
+ GCC_except_table4
+ GCC_except_table8
+ _OBJC_CLASS_$_GMAvailabilityWrapper
+ _OBJC_IVAR_$_DDSUAFManager._operationQueue
+ ___58-[DDSUAFAssetProvider subscribe:subscriptions:completion:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40s_e27_v16?0"UAFAssetSetStatus"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40bs48r_e17_v16?0"NSError"8ls32l8r48l8s40l8
+ ___block_descriptor_64_e8_32s40s48bs56r_e5_v8?0ls32l8r56l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56s_e17_v16?0"NSError"8ls32l8s40l8s48l8s56l8
+ _dispatch_after
+ _dispatch_resume
+ _dispatch_suspend
+ _dispatch_time
- GCC_except_table22
- GCC_except_table7
- ___block_descriptor_56_e8_32s40s48r_e27_v16?0"UAFAssetSetStatus"8ls32l8s40l8r48l8
- ___block_descriptor_64_e8_32s40s48bs56r_e5_v8?0lr56l8s32l8s40l8s48l8
CStrings:
+ "Prewarming embedding assets for locales %{public}@ and %{public}@"
+ "Skipping embedding asset prewarm because Apple Intelligence is not available on this device"
+ "Subscribe for %{public}@ did not complete within %lus; invoking completion with timeout error"
+ "Subscribe timed out"
+ "com.apple.datadeliveryservices.uafmanager.operations"
+ "mul_Hani"
+ "mul_Latn"
+ "prewarm-embedding-assets"
```
