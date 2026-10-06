## MediaConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/MediaConversionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e05c` | `0x1ec24` | **`+0xbc8`** |
| `__TEXT.__cstring` | `0x5970` | `0x5ae4` | **`+0x174`** |
| `__AUTH_CONST.__objc_const` | `0x2f88` | `0x30d8` | **`+0x150`** |
| `__TEXT.__objc_methlist` | `0x1eec` | `0x1ff4` | **`+0x108`** |
| `__AUTH_CONST.__cfstring` | `0x3460` | `0x3520` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1638` | `0x16f0` | **`+0xb8`** |
| `__TEXT.__oslogstring` | `0x28ca` | `0x292c` | **`+0x62`** |
| `__TEXT.__unwind_info` | `0x778` | `0x7b0` | **`+0x38`** |
| `__DATA_CONST.__objc_arraydata` | `0x578` | `0x5a8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xcd8` | `0xcf8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x5a0` | `0x5c0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x250` | `0x26c` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x3b8` | `0x3d0` | **`+0x18`** |

### Other Changes

```diff

-912.0.235.0.0
+916.40.110.0.0

-  Functions: 708
-  Symbols:   1496
-  CStrings:  623
+  Functions: 732
+  Symbols:   1536
+  CStrings:  631
Symbols:
+ -[PAMediaConversionServiceContentProvenanceValidationResult certificateChainDERData]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setCertificateChainDERData:]
+ -[PHMediaFormatConversionCompositeRequest requiresStarRatingMetadataChange]
+ -[PHMediaFormatConversionCompositeRequest requiresTitleMetadataChange]
+ -[PHMediaFormatConversionRequest requiresStarRatingMetadataChange]
+ -[PHMediaFormatConversionRequest requiresTitleMetadataChange]
+ -[PHMediaFormatConversionRequest setStarRatingMetadataBehavior:withStarRating:]
+ -[PHMediaFormatConversionRequest setTitleMetadataBehavior:withTitle:]
+ -[PHMediaFormatConversionRequest starRatingMetadataBehavior]
+ -[PHMediaFormatConversionRequest starRating]
+ -[PHMediaFormatConversionRequest titleMetadataBehavior]
+ -[PHMediaFormatConversionRequest title]
+ -[PHMediaFormatConversionSource checkForStarRatingData]
+ -[PHMediaFormatConversionSource checkForTitleData]
+ -[PHMediaFormatConversionSource markStarRatingMetadataAsCheckedWithStatus:]
+ -[PHMediaFormatConversionSource markTitleMetadataAsCheckedWithStatus:]
+ -[PHMediaFormatConversionSource setStarRatingMetadataStatus:]
+ -[PHMediaFormatConversionSource setTitleMetadataStatus:]
+ -[PHMediaFormatConversionSource sourceStarRatingMetadataStatus]
+ -[PHMediaFormatConversionSource sourceTitleMetadataStatus]
+ -[PHMediaFormatConversionSource starRatingMetadataStatus]
+ -[PHMediaFormatConversionSource titleMetadataStatus]
+ GCC_except_table139
+ GCC_except_table158
+ GCC_except_table161
+ GCC_except_table171
+ GCC_except_table177
+ GCC_except_table424
+ GCC_except_table426
+ GCC_except_table428
+ GCC_except_table430
+ GCC_except_table432
+ GCC_except_table434
+ GCC_except_table436
+ GCC_except_table438
+ GCC_except_table440
+ GCC_except_table442
+ GCC_except_table557
+ GCC_except_table565
+ GCC_except_table595
+ GCC_except_table597
+ GCC_except_table685
+ GCC_except_table687
+ GCC_except_table690
+ GCC_except_table692
+ GCC_except_table705
+ GCC_except_table96
+ _OBJC_CLASS_$_PFImageMetadataChangePolicySetKeywords
+ _OBJC_CLASS_$_PFImageMetadataChangePolicySetStarRating
+ _OBJC_CLASS_$_PFImageMetadataChangePolicySetTitle
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._certificateChainDERData
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._starRating
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._starRatingMetadataBehavior
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._title
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._titleMetadataBehavior
+ _OBJC_IVAR_$_PHMediaFormatConversionSource._starRatingMetadataStatus
+ _OBJC_IVAR_$_PHMediaFormatConversionSource._titleMetadataStatus
+ _PAMediaConversionServiceOptionAVMetadataIncludeRatingKey
+ _PAMediaConversionServiceOptionAVMetadataIncludeTitleKey
+ _PAMediaConversionServiceOptionAVMetadataRatingKey
+ _PAMediaConversionServiceProvenanceCertificateChainDataKey
+ ___70-[PHMediaFormatConversionCompositeRequest requiresTitleMetadataChange]_block_invoke
+ ___75-[PHMediaFormatConversionCompositeRequest requiresStarRatingMetadataChange]_block_invoke
- GCC_except_table137
- GCC_except_table152
- GCC_except_table159
- GCC_except_table169
- GCC_except_table175
- GCC_except_table404
- GCC_except_table406
- GCC_except_table408
- GCC_except_table410
- GCC_except_table412
- GCC_except_table414
- GCC_except_table416
- GCC_except_table418
- GCC_except_table533
- GCC_except_table541
- GCC_except_table571
- GCC_except_table573
- GCC_except_table661
- GCC_except_table663
- GCC_except_table666
- GCC_except_table668
- GCC_except_table681
- GCC_except_table92
CStrings:
+ "#q"
+ "PAMediaConversionServiceOptionAVMetadataIncludeRatingKey"
+ "PAMediaConversionServiceOptionAVMetadataIncludeTitleKey"
+ "PAMediaConversionServiceOptionAVMetadataRatingKey"
+ "PAMediaConversionServiceProvenanceCertificateChainDataKey"
+ "Read star rating metadata status: %ld from file: %@"
+ "Read title metadata status: %ld from file: %@"
+ "starRating must not be nil if behavior is PHMediaFormatMetadataBehaviorApply"
+ "title must not be nil if behavior is PHMediaFormatMetadataBehaviorApply"
- "#Q"
```
