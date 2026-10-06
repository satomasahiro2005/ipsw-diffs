## MediaConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/MediaConversionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1eca8` | `0x1f210` | **`+0x568`** |
| `__TEXT.__cstring` | `0x5ae4` | `0x5c3d` | **`+0x159`** |
| `__AUTH_CONST.__cfstring` | `0x3520` | `0x35c0` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x292c` | `0x2985` | **`+0x59`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xc0` | `0xf0` | **`+0x30`** |
| `__AUTH_CONST.__objc_intobj` | `0x198` | `0x1c8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xcf8` | `0xd20` | **`+0x28`** |
| `__DATA.__bss` | `0x40` | `0x50` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x5a8` | `0x5b8` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x30` | `0x20` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1ff4` | `0x2004` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7b0` | `0x7c0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x16f0` | `0x16f8` | **`+0x8`** |

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

-  Functions: 732
-  Symbols:   1536
-  CStrings:  631
+  Functions: 736
+  Symbols:   1542
+  CStrings:  637
Symbols:
+ -[PHMediaFormatConversionImplementation_MediaConversionService _submitProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]
+ -[PHMediaFormatConversionRequest _provenanceRenderOutputType]
+ -[PHMediaFormatConversionRequest provenanceRenderSourceURL]
+ -[PHMediaFormatConversionRequest setProvenanceMetadataBehavior:withUnprocessedSourceRenderURL:processedOriginalDestinationURL:sidecarURL:]
+ GCC_except_table142
+ GCC_except_table157
+ GCC_except_table159
+ GCC_except_table164
+ GCC_except_table174
+ GCC_except_table180
+ GCC_except_table444
+ GCC_except_table446
+ GCC_except_table561
+ GCC_except_table569
+ GCC_except_table599
+ GCC_except_table601
+ GCC_except_table689
+ GCC_except_table691
+ GCC_except_table694
+ GCC_except_table696
+ GCC_except_table709
+ GCC_except_table97
+ GCC_except_table99
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceRenderSourceURL
+ _PAMediaConversionErrorIsProvenanceProcessingError
+ _PAMediaConversionIsProvenanceClientUpgradeRequiredError
+ _PAMediaConversionServiceProvenanceRetryableKey
+ _PAProvenanceCloudAppErrorIsTransient
+ _PFErrorOrUnderlyingErrorMatchesCodesByDomain
+ ___157-[PHMediaFormatConversionImplementation_MediaConversionService _submitProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]_block_invoke
- -[PHMediaFormatConversionImplementation_MediaConversionService _submitAdjustedProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]
- -[PHMediaFormatConversionRequest provenanceAdjustedRenderSourceURL]
- -[PHMediaFormatConversionRequest setProvenanceMetadataBehavior:withUnprocessedSourceAdjustedRenderURL:processedOriginalDestinationURL:sidecarURL:]
- GCC_except_table139
- GCC_except_table154
- GCC_except_table156
- GCC_except_table158
- GCC_except_table171
- GCC_except_table177
- GCC_except_table424
- GCC_except_table426
- GCC_except_table557
- GCC_except_table565
- GCC_except_table595
- GCC_except_table597
- GCC_except_table685
- GCC_except_table687
- GCC_except_table690
- GCC_except_table692
- GCC_except_table705
- GCC_except_table94
- GCC_except_table96
- _OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceAdjustedRenderSourceURL
- ___165-[PHMediaFormatConversionImplementation_MediaConversionService _submitAdjustedProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]_block_invoke
CStrings:
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppCaptureUnsupported"
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppClientVersionUnsupported"
+ "PAMediaConversionServiceErrorCodeProvenanceDestinationFormatUnsupported"
+ "PAMediaConversionServiceErrorCodeProvenanceRevocationCheckClientUpgradeRequired"
+ "PAMediaConversionServiceProvenanceRetryableKey"
+ "Render path extension (%@) is not a known UTType. Falling back to the conversion source's format."
+ "Requesting single-pass Provenance processing with render. Source: %@, destination: %@."
- "Requesting single-pass Provenance processing with adjusted render. Source: %@, destination: %@."
```
