## MediaConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/MediaConversionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b520` | `0x1e05c` | **`+0x2b3c`** |
| `__TEXT.__cstring` | `0x4c8c` | `0x5970` | **`+0xce4`** |
| `__AUTH_CONST.__cfstring` | `0x2da0` | `0x3460` | **`+0x6c0`** |
| `__AUTH_CONST.__objc_const` | `0x2a78` | `0x2f88` | **`+0x510`** |
| `__TEXT.__oslogstring` | `0x2564` | `0x28ca` | **`+0x366`** |
| `__TEXT.__objc_methlist` | `0x1c3c` | `0x1eec` | **`+0x2b0`** |
| `__DATA_CONST.__const` | `0xae0` | `0xcd8` | **`+0x1f8`** |
| `__DATA_CONST.__objc_selrefs` | `0x14b0` | `0x1638` | **`+0x188`** |
| `__DATA_CONST.__objc_arraydata` | `0x4c8` | `0x578` | **`+0xb0`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x710` | `0x778` | **`+0x68`** |
| `__DATA.__objc_ivar` | `0x200` | `0x250` | **`+0x50`** |
| `__DATA.__data` | `0x488` | `0x4a8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x398` | `0x3b8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x58c` | `0x5a0` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0xb8` | `0xc8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x58` | `0x60` | **`+0x8`** |

### Other Changes

```diff

-912.0.234.0.0
+912.0.235.0.0

-  Functions: 640
-  Symbols:   1362
-  CStrings:  553
+  Functions: 708
+  Symbols:   1496
+  CStrings:  623
Symbols:
+ -[ConversionOptionSet setSourcePathProvenanceUnprocessedImage:]
+ -[ConversionOptionSet sourcePathProvenanceUnprocessedImage]
+ -[PAImageConversionServiceClient(ContentProvenance) embedProcessedProvenanceFromRegularImageAtURL:intoRegularImageAtURL:destinationURL:options:completionHandler:]
+ -[PAImageConversionServiceClient(ContentProvenance) embedUnprocessedProvenanceImageAtURL:intoRegularImageAtURL:destinationURL:options:completionHandler:]
+ -[PAImageConversionServiceClient(ContentProvenance) processContentProvenanceForSourceURLCollection:destinationURL:options:completionHandler:]
+ -[PAImageConversionServiceClient(ContentProvenance) stripProvenanceMetadataFromOriginalProvenanceImageAtURL:destinationURL:options:completionHandler:]
+ -[PAImageConversionServiceClient(ContentProvenance) validateContentProvenanceForProcessedImageAtURL:options:completionHandler:]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult .cxx_destruct]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult diagnosticsRequested]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult setDiagnosticsRequested:]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult setUtcLowerBoundTimestamp:]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult setUtcProcessingTimestamp:]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult setUtcUpperBoundTimestamp:]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult utcLowerBoundTimestamp]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult utcProcessingTimestamp]
+ -[PAMediaConversionServiceContentProvenanceProcessingResult utcUpperBoundTimestamp]
+ -[PAMediaConversionServiceContentProvenanceValidationResult .cxx_destruct]
+ -[PAMediaConversionServiceContentProvenanceValidationResult certificateVerificationStatus]
+ -[PAMediaConversionServiceContentProvenanceValidationResult init]
+ -[PAMediaConversionServiceContentProvenanceValidationResult processedJPEGImageData]
+ -[PAMediaConversionServiceContentProvenanceValidationResult revocationCheckIdentifier]
+ -[PAMediaConversionServiceContentProvenanceValidationResult revocationStatus]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setCertificateVerificationStatus:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setProcessedJPEGImageData:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setRevocationCheckIdentifier:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setRevocationStatus:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setSignatureVerificationStatus:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setUtcLowerBoundTimestamp:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setUtcProcessingTimestamp:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setUtcUpperBoundTimestamp:]
+ -[PAMediaConversionServiceContentProvenanceValidationResult signatureVerificationStatus]
+ -[PAMediaConversionServiceContentProvenanceValidationResult utcLowerBoundTimestamp]
+ -[PAMediaConversionServiceContentProvenanceValidationResult utcProcessingTimestamp]
+ -[PAMediaConversionServiceContentProvenanceValidationResult utcUpperBoundTimestamp]
+ -[PAMediaConversionServiceContentProvenanceValidationResult validationStatus]
+ -[PHMediaFormatConversionCompositeRequest requiresProvenanceMetadataChange]
+ -[PHMediaFormatConversionImplementation_MediaConversionService _submitAdjustedProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]
+ -[PHMediaFormatConversionImplementation_MediaConversionService _submitProvenanceProcessedEmbedRequest:destination:options:completionHandler:]
+ -[PHMediaFormatConversionRequest _requiresNonProvenanceMetadataChange]
+ -[PHMediaFormatConversionRequest provenanceAdjustedRenderSourceURL]
+ -[PHMediaFormatConversionRequest provenanceMetadataBehavior]
+ -[PHMediaFormatConversionRequest provenanceProcessedOriginalDestinationURL]
+ -[PHMediaFormatConversionRequest provenanceProcessedSourceImageURL]
+ -[PHMediaFormatConversionRequest provenanceSidecarURL]
+ -[PHMediaFormatConversionRequest requiresProvenanceMetadataChange]
+ -[PHMediaFormatConversionRequest setProvenanceMetadataBehavior:withProcessedSourceImageURL:]
+ -[PHMediaFormatConversionRequest setProvenanceMetadataBehavior:withProvenanceSidecarURL:]
+ -[PHMediaFormatConversionRequest setProvenanceMetadataBehavior:withUnprocessedSourceAdjustedRenderURL:processedOriginalDestinationURL:sidecarURL:]
+ -[PHMediaFormatConversionRequest setShouldPreserveProvenance:]
+ -[PHMediaFormatConversionRequest shouldPreserveProvenance]
+ -[PHMediaFormatConversionSource checkForProvenanceData]
+ -[PHMediaFormatConversionSource markProvenanceMetadataAsCheckedWithStatus:]
+ -[PHMediaFormatConversionSource provenanceMetadataStatus]
+ -[PHMediaFormatConversionSource setProvenanceMetadataStatus:]
+ -[PHMediaFormatConversionSource sourceProvenanceMetadataStatus]
+ GCC_except_table137
+ GCC_except_table152
+ GCC_except_table154
+ GCC_except_table156
+ GCC_except_table159
+ GCC_except_table169
+ GCC_except_table175
+ GCC_except_table404
+ GCC_except_table406
+ GCC_except_table408
+ GCC_except_table410
+ GCC_except_table412
+ GCC_except_table414
+ GCC_except_table416
+ GCC_except_table418
+ GCC_except_table533
+ GCC_except_table541
+ GCC_except_table571
+ GCC_except_table573
+ GCC_except_table661
+ GCC_except_table663
+ GCC_except_table666
+ GCC_except_table668
+ GCC_except_table681
+ GCC_except_table92
+ GCC_except_table94
+ _OBJC_CLASS_$_NSBundle
+ _OBJC_CLASS_$_PAMediaConversionServiceContentProvenanceProcessingResult
+ _OBJC_CLASS_$_PAMediaConversionServiceContentProvenanceValidationResult
+ _OBJC_IVAR_$_ConversionOptionSet._sourcePathProvenanceUnprocessedImage
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceProcessingResult._diagnosticsRequested
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceProcessingResult._utcLowerBoundTimestamp
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceProcessingResult._utcProcessingTimestamp
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceProcessingResult._utcUpperBoundTimestamp
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._certificateVerificationStatus
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._processedJPEGImageData
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._revocationCheckIdentifier
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._revocationStatus
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._signatureVerificationStatus
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._utcLowerBoundTimestamp
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._utcProcessingTimestamp
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._utcUpperBoundTimestamp
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceAdjustedRenderSourceURL
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceMetadataBehavior
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceProcessedOriginalDestinationURL
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceProcessedSourceImageURL
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceSidecarURL
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._shouldPreserveProvenance
+ _OBJC_IVAR_$_PHMediaFormatConversionSource._provenanceMetadataStatus
+ _OBJC_METACLASS_$_PAMediaConversionServiceContentProvenanceProcessingResult
+ _OBJC_METACLASS_$_PAMediaConversionServiceContentProvenanceValidationResult
+ _PAMediaConversionIsProvenanceEligibilityError
+ _PAMediaConversionIsProvenanceProcessingTimeoutError
+ _PAMediaConversionResourceRoleProvenanceProcessedSourceImage
+ _PAMediaConversionResourceRoleProvenanceUnprocessed
+ _PAMediaConversionServiceOptionClientProcessNameKey
+ _PAMediaConversionServiceOptionIsContentProvenanceDryRunKey
+ _PAMediaConversionServiceOptionIsContentProvenanceMetadataStrippingConversionKey
+ _PAMediaConversionServiceOptionIsContentProvenanceProcessedEmbeddingConversionKey
+ _PAMediaConversionServiceOptionIsContentProvenanceProcessingConversionKey
+ _PAMediaConversionServiceOptionIsContentProvenanceUnprocessedEmbeddingConversionKey
+ _PAMediaConversionServiceOptionIsContentProvenanceValidationKey
+ _PAMediaConversionServiceOptionIsContentProvenanceValidationUnwrappedImageKey
+ _PAMediaConversionServiceOptionPreserveProvenanceKey
+ _PAMediaConversionServiceOptionProvenanceOriginalAssetLocalIdentifierKey
+ _PAMediaConversionServiceOptionUnitTestSupportUseMockProvenanceProcessingKey
+ _PAMediaConversionServiceProvenanceCertificateVerificationStatusKey
+ _PAMediaConversionServiceProvenanceCloudAppErrorDomain
+ _PAMediaConversionServiceProvenanceDiagnosticsRequestedKey
+ _PAMediaConversionServiceProvenanceProcessingDateAgeTimeIntervalKey
+ _PAMediaConversionServiceProvenanceProcessingResultMetadataKey
+ _PAMediaConversionServiceProvenanceRevocationCheckIdentifierKey
+ _PAMediaConversionServiceProvenanceRevocationStatusKey
+ _PAMediaConversionServiceProvenanceRoundTripDurationKey
+ _PAMediaConversionServiceProvenanceSignatureVerificationStatusKey
+ _PAMediaConversionServiceProvenanceUTCLowerBoundTimestampKey
+ _PAMediaConversionServiceProvenanceUTCProcessingTimestampKey
+ _PAMediaConversionServiceProvenanceUTCUpperBoundTimestampKey
+ _PAMediaConversionServiceProvenanceUploadDurationKey
+ _PAMediaConversionServiceProvenanceValidationResultMetadataKey
+ _UTTypeDNG
+ __OBJC_$_INSTANCE_METHODS_PAImageConversionServiceClient(ContentProvenance)
+ __OBJC_$_INSTANCE_METHODS_PAMediaConversionServiceContentProvenanceProcessingResult
+ __OBJC_$_INSTANCE_METHODS_PAMediaConversionServiceContentProvenanceValidationResult
+ __OBJC_$_INSTANCE_VARIABLES_PAMediaConversionServiceContentProvenanceProcessingResult
+ __OBJC_$_INSTANCE_VARIABLES_PAMediaConversionServiceContentProvenanceValidationResult
+ __OBJC_$_PROP_LIST_PAMediaConversionServiceContentProvenanceProcessingResult
+ __OBJC_$_PROP_LIST_PAMediaConversionServiceContentProvenanceValidationResult
+ __OBJC_CLASS_RO_$_PAMediaConversionServiceContentProvenanceProcessingResult
+ __OBJC_CLASS_RO_$_PAMediaConversionServiceContentProvenanceValidationResult
+ __OBJC_METACLASS_RO_$_PAMediaConversionServiceContentProvenanceProcessingResult
+ __OBJC_METACLASS_RO_$_PAMediaConversionServiceContentProvenanceValidationResult
+ ___127-[PAImageConversionServiceClient(ContentProvenance) validateContentProvenanceForProcessedImageAtURL:options:completionHandler:]_block_invoke
+ ___141-[PAImageConversionServiceClient(ContentProvenance) processContentProvenanceForSourceURLCollection:destinationURL:options:completionHandler:]_block_invoke
+ ___141-[PHMediaFormatConversionImplementation_MediaConversionService _submitProvenanceProcessedEmbedRequest:destination:options:completionHandler:]_block_invoke
+ ___150-[PAImageConversionServiceClient(ContentProvenance) stripProvenanceMetadataFromOriginalProvenanceImageAtURL:destinationURL:options:completionHandler:]_block_invoke
+ ___153-[PAImageConversionServiceClient(ContentProvenance) embedUnprocessedProvenanceImageAtURL:intoRegularImageAtURL:destinationURL:options:completionHandler:]_block_invoke
+ ___162-[PAImageConversionServiceClient(ContentProvenance) embedProcessedProvenanceFromRegularImageAtURL:intoRegularImageAtURL:destinationURL:options:completionHandler:]_block_invoke
+ ___165-[PHMediaFormatConversionImplementation_MediaConversionService _submitAdjustedProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]_block_invoke
+ ___75-[PHMediaFormatConversionCompositeRequest requiresProvenanceMetadataChange]_block_invoke
+ ___block_descriptor_40_e8_32bs_e37_v32?0q8"NSDictionary"16"NSError"24ls32l8
+ ___block_descriptor_56_e8_32s40s48bs_e20_v24?0q8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e20_v24?0q8"NSError"16ls32l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e37_v32?0q8"NSDictionary"16"NSError"24ls32l8s40l8s48l8s56l8s64l8s72l8
+ _getprogname
- GCC_except_table112
- GCC_except_table114
- GCC_except_table116
- GCC_except_table119
- GCC_except_table129
- GCC_except_table135
- GCC_except_table347
- GCC_except_table349
- GCC_except_table351
- GCC_except_table353
- GCC_except_table355
- GCC_except_table357
- GCC_except_table359
- GCC_except_table474
- GCC_except_table482
- GCC_except_table506
- GCC_except_table508
- GCC_except_table594
- GCC_except_table596
- GCC_except_table599
- GCC_except_table601
- GCC_except_table614
- GCC_except_table62
- GCC_except_table64
- GCC_except_table97
- __OBJC_$_INSTANCE_METHODS_PAImageConversionServiceClient
CStrings:
+ "#Q"
+ "--source-provenance-unprocessed-image is only valid for image conversions\n"
+ "-t|--type [%@] -s|--source <input media path> -d|--destination <output media path> [--source-video-complement <input media path>] [--destination-video-complement <output media path>] [--source-provenance-unprocessed-image <input provenance image path>] [--partial-results-cache-directory <cache directory path>] [--replace] [[-o|--option <key>=<value>], ...] [-r|--preset <preset>] [-c|--count <count>] [-v|--verbose] [--wait] [-p|--progress] [--pause] [--launch] [--launch-and-pause] [--next]"
+ "Invalid request using single pass encoding option and metadata changes (like location stripping, custom location, custom creation date, custom description, custom provenance) for video source %@"
+ "Network.NWError"
+ "PAMediaConversionResourceRoleProvenanceProcessedSourceImage"
+ "PAMediaConversionResourceRoleProvenanceUnprocessed"
+ "PAMediaConversionServiceErrorCodeMissingProvenanceProcessedMetadata"
+ "PAMediaConversionServiceErrorCodeMissingProvenanceUnprocessedMetadata"
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppInternalError"
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppManifestCertificateVerificationFailed"
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppSEPSignatureVerificationFailed"
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppSensorSignatureVerificationFailed"
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppUnknown"
+ "PAMediaConversionServiceErrorCodeProvenanceIneligible"
+ "PAMediaConversionServiceErrorCodeProvenanceMalformedResponse"
+ "PAMediaConversionServiceErrorCodeProvenanceMissingPayload"
+ "PAMediaConversionServiceErrorCodeProvenanceProcessedValidationFailure"
+ "PAMediaConversionServiceErrorCodeProvenanceProcessingDateExpired"
+ "PAMediaConversionServiceErrorCodeProvenanceRevocationCheckFailure"
+ "PAMediaConversionServiceErrorCodeProvenanceSourceDNGUnavailable"
+ "PAMediaConversionServiceErrorCodeProvenanceTemporaryFileWriteFailure"
+ "PAMediaConversionServiceErrorCodeProvenanceTimeout"
+ "PAMediaConversionServiceOptionClientProcessNameKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceDryRunKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceMetadataStrippingConversionKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceProcessedEmbeddingConversionKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceProcessingConversionKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceUnprocessedEmbeddingConversionKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceValidationKey"
+ "PAMediaConversionServiceOptionIsContentProvenanceValidationUnwrappedImageKey"
+ "PAMediaConversionServiceOptionPreserveProvenanceKey"
+ "PAMediaConversionServiceOptionProvenanceOriginalAssetLocalIdentifierKey"
+ "PAMediaConversionServiceOptionUnitTestSupportUseMockProvenanceProcessingKey"
+ "PAMediaConversionServiceProvenanceCertificateVerificationStatusKey"
+ "PAMediaConversionServiceProvenanceCloudAppErrorDomain"
+ "PAMediaConversionServiceProvenanceDiagnosticsRequestedKey"
+ "PAMediaConversionServiceProvenanceProcessingDateAgeTimeIntervalKey"
+ "PAMediaConversionServiceProvenanceProcessingResultMetadataKey"
+ "PAMediaConversionServiceProvenanceRevocationCheckIdentifierKey"
+ "PAMediaConversionServiceProvenanceRevocationStatusKey"
+ "PAMediaConversionServiceProvenanceRoundTripDurationKey"
+ "PAMediaConversionServiceProvenanceSignatureVerificationStatusKey"
+ "PAMediaConversionServiceProvenanceUTCLowerBoundTimestampKey"
+ "PAMediaConversionServiceProvenanceUTCProcessingTimestampKey"
+ "PAMediaConversionServiceProvenanceUTCUpperBoundTimestampKey"
+ "PAMediaConversionServiceProvenanceUploadDurationKey"
+ "PAMediaConversionServiceProvenanceValidationResultMetadataKey"
+ "PrivateCloudComputeError"
+ "Provenance embed processed failed: %@. Original: %@, Carrier: %@"
+ "Provenance embed processed succeeded. Destination: %@"
+ "Provenance processing failed: %@. Source: %@"
+ "Provenance processing succeeded. Destination URL: %@"
+ "Provenance provenanceSidecarURL is nil."
+ "Provenance stripping failed: %@. Source: %@"
+ "Provenance stripping succeeded. Destination: %@"
+ "Read provenance metadata status: %ld from file: %@"
+ "Requesting Provenance embed processed metadata from original: %@ into carrier: %@, destination: %@."
+ "Requesting Provenance processing with source: %@, destination: %@."
+ "Requesting Provenance strip metadata at URL: %@, destination: %@."
+ "Requesting single-pass Provenance processing with adjusted render. Source: %@, destination: %@."
+ "Single-pass Provenance processing failed: %@. Source: %@"
+ "Single-pass Provenance processing succeeded. Destination URL: %@"
+ "[sourceURLCollection resourceURLForRole:PAMediaConversionResourceRoleMainResource]"
+ "destinationURL"
+ "imageURL"
+ "originalProvenanceImageURL"
+ "processedProvenanceImageURL"
+ "regularImageURL"
+ "request.provenanceProcessedOriginalDestinationURL"
+ "source-provenance-unprocessed-image"
+ "unprocessedProvenanceImageURL"
+ "v24@?0q8@\"NSError\"16"
- "#A"
- "-t|--type [%@] -s|--source <input media path> -d|--destination <output media path> [--source-video-complement <input media path>] [--destination-video-complement <output media path>] [--partial-results-cache-directory <cache directory path>] [--replace] [[-o|--option <key>=<value>], ...] [-r|--preset <preset>] [-c|--count <count>] [-v|--verbose] [--wait] [-p|--progress] [--pause] [--launch] [--launch-and-pause] [--next]"
- "Invalid request using single pass encoding option and metadata changes (like location stripping, custom location, custom creation date, custom description) for video source %@"
```
