## SiriAssetUtilities

> `/System/Library/PrivateFrameworks/SiriAssetUtilities.framework/SiriAssetUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf3dc` | `0xf470` | **`+0x94`** |
| `__TEXT.__gcc_except_tab` | `0x468` | `0x490` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x470` | `0x480` | **`+0x10`** |

### Other Changes

```diff

-3600.70.1.0.0
+3600.74.1.0.0

-  Symbols:   693
+  Symbols:   695
Symbols:
+ GCC_except_table12
+ GCC_except_table26
+ ___block_descriptor_56_e8_32s40s48w_e36_v24?0"UAFAssetStatus"8"NSError"16ls32l8w48l8s40l8
- ___block_descriptor_48_e8_32s40w_e36_v24?0"UAFAssetStatus"8"NSError"16lw40l8s32l8
Functions:
~ -[SAUAssetUtilities refreshUnderstandingOnDeviceAssetsAvailableAsync] : 172 -> 232
~ ___69-[SAUAssetUtilities refreshUnderstandingOnDeviceAssetsAvailableAsync]_block_invoke : 92 -> 104
~ -[SAUAssetUtilities refreshUAFAssetStatusAsync] : 136 -> 200
~ ___47-[SAUAssetUtilities refreshUAFAssetStatusAsync]_block_invoke : 232 -> 228
~ ___47-[SAUAssetUtilities refreshUAFAssetStatusAsync]_block_invoke_2 : 356 -> 352
~ ___47-[SAUAssetUtilities refreshUAFAssetStatusAsync]_block_invoke_3 : 412 -> 432
```
