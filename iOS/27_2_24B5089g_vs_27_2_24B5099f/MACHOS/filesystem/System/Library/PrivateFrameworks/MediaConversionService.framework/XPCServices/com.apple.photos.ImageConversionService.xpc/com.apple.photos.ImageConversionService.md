## com.apple.photos.ImageConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/XPCServices/com.apple.photos.ImageConversionService.xpc/com.apple.photos.ImageConversionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x224b4` | `0x23aec` | **`+0x1638`** |
| `__TEXT.__objc_methname` | `0x79be` | `0x7d70` | **`+0x3b2`** |
| `__TEXT.__cstring` | `0x38dc` | `0x3bad` | **`+0x2d1`** |
| `__TEXT.__objc_stubs` | `0x5a60` | `0x5c00` | **`+0x1a0`** |
| `__DATA_CONST.__cfstring` | `0x27c0` | `0x28e0` | **`+0x120`** |
| `__TEXT.__gcc_except_tab` | `0x968` | `0x854` | **`-0x114`** |
| `__TEXT.__oslogstring` | `0x2bb3` | `0x2cc7` | **`+0x114`** |
| `__TEXT.__objc_methlist` | `0x18dc` | `0x197c` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x1a90` | `0x1af8` | **`+0x68`** |
| `__TEXT.__objc_methtype` | `0xc8d` | `0xcd8` | **`+0x4b`** |
| `__DATA_CONST.__objc_intobj` | `0x48` | `0x30` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x6f0` | `0x6e0` | **`-0x10`** |
| `__DATA_CONST.__objc_doubleobj` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x768` | `0x778` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x327` | `0x332` | **`+0xb`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

-  Functions: 670
-  Symbols:   435
-  CStrings:  1773
+  Functions: 683
+  Symbols:   434
+  CStrings:  1802
Symbols:
- _OBJC_CLASS_$_NSConstantDoubleNumber
CStrings:
+ "%@ is not honoured by provenance requests"
+ "%@ is required by provenance requests that can transcode"
+ "@48@0:8@16@24@32^@40"
+ "@64@0:8@16@24@32@40@48^@56"
+ "@64@0:8@16@24@32@40^@48^@56"
+ "B48@0:8@16^@24@32^@40"
+ "Couldn't prepare stripped-provenance data for its destination"
+ "Couldn't read source image data for provenance metadata stripping"
+ "Destination %{public}@ for role %{public}@ states no format, leaving the container (%{public}@) its output is written in unnamed."
+ "Destination %{public}@ states no format for the stripped output, leaving it in the container (%{public}@) the source is in."
+ "Failed to read a processed provenance image payload to embed from the original regular image at %@"
+ "ImageConversionService+Provenance.m"
+ "Missing regular image URL in source URL collection for provenance metadata stripping request"
+ "Output for role %@ is written in its source's container (%@) but destination %@ calls for %@"
+ "PAMediaConversionServiceProvenanceRetryableKey"
+ "Provenance"
+ "Provenance cannot be embedded into %@, the container the source resource for role %@ is in"
+ "Provenance cannot be embedded into %@, the format destination %@ calls for"
+ "Provenance stripping reported success but produced no data"
+ "Q20@0:8B16"
+ "Source URL collection has a full-size render to share but the destination URL collection has no full-size render role to write it to"
+ "Unable to create output image destination of type %{public}@"
+ "Unable to transcode the file containing provenance at %@ to %@"
+ "Unable to write transformed provenance data to temporary file %@"
+ "_applyMetadataConversionsToProvenanceFile:sourceContainerType:destinationType:options:temporaryFilesParentDirectoryURL:error:"
+ "_handleContentProvenanceMetadataStrippingRequestForSourceURLCollection:destinationURLCollection:options:temporaryFilesParentDirectoryURL:mutableOutputImageInfo:error:"
+ "_handleContentProvenanceProcessedEmbeddingRequestForSourceURLCollection:destinationURLCollection:options:temporaryFilesParentDirectoryURL:mutableOutputImageInfo:error:"
+ "_handleContentProvenanceProcessingRequestForSourceURLCollection:destinationURLCollection:options:temporaryFilesParentDirectoryURL:mutableOutputImageInfo:queueEntry:error:"
+ "_handleContentProvenanceUnprocessedEmbeddingRequestForSourceURLCollection:destinationURL:options:mutableOutputImageInfo:error:"
+ "_handleContentProvenanceValidationRequestForSourceURLCollection:options:outputData:mutableOutputImageInfo:error:"
+ "_isContentProvenanceMetadataStrippingRequest:"
+ "_isContentProvenanceProcessedEmbeddingRequest:"
+ "_isContentProvenanceProcessingRequest:"
+ "_isContentProvenanceRequestEligibleInCurrentRegion:"
+ "_isContentProvenanceUnprocessedEmbeddingRequest:"
+ "_isContentProvenanceValidationRequest:"
+ "_processedProvenanceJPEGDataForImageAtURL:regularImageURL:options:queueEntry:outProcessingMetadata:error:"
+ "_processingResultMetadataForProcessedImageAtURL:processingMetadata:"
+ "_rejectProvenanceRequestOption:error:"
+ "_requestMayRequireTranscoding:"
+ "_requireProvenanceRequestOption:error:"
+ "_temporaryProvenanceFileURLWithData:pathExtension:parentDirectoryURL:error:"
+ "_transcodeOutputTypeForContainerType:destinationType:"
+ "_transcodedDataForFileAtURL:options:outputType:metadataPolicy:error:"
+ "_unprocessedProvenanceImageURLForSourceURLCollection:regularImageURL:temporaryFilesParentDirectoryURL:error:"
+ "_validateProvenanceContainerType:matchesDestinationForRole:destinationURLCollection:error:"
+ "_validatedNamedDestinationTypeForRole:destinationURLCollection:options:error:"
+ "_validatedSharedStillDestinationTypeForSourceURLCollection:destinationURLCollection:options:error:"
+ "_validationResultMetadataForProcessedImageInfo:"
+ "_validationSkipOptionsForInternalBuild:"
+ "_writeCombinedProvenanceImagesForSourceURLCollection:destinationURLCollection:processedImageJPEGData:sharedStillDestinationType:options:temporaryFilesParentDirectoryURL:error:"
+ "handleContentProvenanceRequestForQueueEntry:outputData:mutableOutputImageInfo:error:"
+ "outputContentTypeForRegularImageContentType:"
+ "outputFileTypeForRole:destinationURLCollection:options:"
+ "queueEntry"
+ "transformed-provenance-%@.%@"
- "B80@0:8@16@24@32@40^@48@56@64^@72"
- "Couldn't apply metadata policy to stripped-provenance data"
- "Failed to read processed provenance image data from original regular image at %@"
- "Unable to create output image destination"
- "Unable to transcode RAW provenance file at %@ to apply metadata policy"
- "Unable to write metadata-applied provenance data to temporary file %@"
- "Unexpected nil unprocessed provenance image source URL"
- "_isRAWImageFileAtURL:"
- "_provenanceFileURLWithMetadataPolicyAppliedFromOptions:toFileURLContainingProvenance:destinationURL:temporaryFilesParentDirectoryURL:error:"
- "_temporaryProvenanceFileWriteFailureErrorForURL:underlyingError:"
- "_transcodeAndApplyMetadataPolicy:toRawFileURL:outputType:temporaryFilesParentDirectoryURL:error:"
- "dataWithContentsOfURL:"
- "handleContentProvenanceMetadataStrippingRequestForSourceURLCollection:destinationURL:options:temporaryFilesParentDirectoryURL:mutableOutputImageInfo:error:"
- "handleContentProvenanceProcessedEmbeddingRequestForSourceURLCollection:destinationURL:options:temporaryFilesParentDirectoryURL:mutableOutputImageInfo:error:"
- "handleContentProvenanceProcessingRequestForSourceURLCollection:destinationURLCollection:options:temporaryFilesParentDirectoryURL:mutableOutputImageInfo:queueEntry:error:"
- "handleContentProvenanceRequestWithSourceURLCollection:destinationURLCollection:options:temporaryFilesParentDirectoryURL:outputData:mutableOutputImageInfo:queueEntry:error:"
- "handleContentProvenanceUnprocessedEmbeddingRequestForSourceURLCollection:destinationURL:options:mutableOutputImageInfo:error:"
- "handleContentProvenanceValidationRequestForSourceURLCollection:options:outputData:mutableOutputImageInfo:error:"
- "heic"
- "isContentProvenanceMetadataStrippingRequest:"
- "isContentProvenanceProcessedEmbeddingRequest:"
- "isContentProvenanceProcessingRequest:"
- "isContentProvenanceRequestEligibleInCurrentRegion:"
- "isContentProvenanceUnprocessedEmbeddingRequest:"
- "isContentProvenanceValidationRequest:"
- "metadata-applied-%@.%@"
- "transcoded-provenance-file-%@.%@"
```
