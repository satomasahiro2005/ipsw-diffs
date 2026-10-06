## MediaConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/MediaConversionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b4d4` | `0x1b520` | **`+0x4c`** |
| `__TEXT.__objc_methlist` | `0x1c2c` | `0x1c3c` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x390` | `0x398` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x14a8` | `0x14b0` | **`+0x8`** |

### Other Changes

```diff

-910.33.102.0.0
+912.0.111.0.0

-  Functions: 639
-  Symbols:   1360
+  Functions: 640
+  Symbols:   1362
Symbols:
+ -[PHMediaFormatConversionImplementation_MediaConversionService _conversionErrorForStatus:underlyingError:]
+ GCC_except_table506
+ GCC_except_table508
+ GCC_except_table594
+ GCC_except_table596
+ GCC_except_table599
+ GCC_except_table601
+ GCC_except_table614
+ ___NSDictionary0__struct
+ ___block_descriptor_64_e8_32s40s48bs56w_e37_v32?0q8"NSDictionary"16"NSError"24ls32l8w56l8s40l8s48l8
- GCC_except_table505
- GCC_except_table507
- GCC_except_table593
- GCC_except_table595
- GCC_except_table598
- GCC_except_table600
- GCC_except_table613
- ___block_descriptor_56_e8_32s40bs48w_e37_v32?0q8"NSDictionary"16"NSError"24ls32l8w48l8s40l8
Functions:
~ -[PHMediaFormatConversionRequest _calculateRequiresFormatConversion] : 1108 -> 1128
~ ___136-[PHMediaFormatConversionImplementation_MediaConversionService submitNonSinglePassVideoConversionRequest:destination:completionHandler:]_block_invoke : 400 -> 268
~ -[PHMediaFormatConversionImplementation_MediaConversionService submitSinglePassVideoConversionRequest:destination:completionHandler:] : 720 -> 732
~ ___133-[PHMediaFormatConversionImplementation_MediaConversionService submitSinglePassVideoConversionRequest:destination:completionHandler:]_block_invoke : 396 -> 264
~ ___112-[PHMediaFormatConversionImplementation_MediaConversionService performImageConversionRequest:completionHandler:]_block_invoke : 228 -> 260
+ -[PHMediaFormatConversionImplementation_MediaConversionService _conversionErrorForStatus:underlyingError:]
```
