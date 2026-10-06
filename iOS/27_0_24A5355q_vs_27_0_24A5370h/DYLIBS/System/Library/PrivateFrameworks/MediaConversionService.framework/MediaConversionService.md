## MediaConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/MediaConversionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x250f` | `0x2564` | **`+0x55`** |
| `__TEXT.__text` | `0x1b3ac` | `0x1b3d4` | **`+0x28`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  CStrings:  552
+  CStrings:  553
Functions:
~ +[PAMediaConversionServiceResourceURLCollection getSignatureString:filenameSummary:forDictionaryRepresentation:] : 656 -> 652
~ -[PAMediaConversionServiceResourceURLCollection containsAllRoles:] : 380 -> 376
~ -[PAMediaConversionServiceResourceURLCollection containsAnyRole:] : 380 -> 376
~ -[PAMediaConversionServiceResourceURLCollection enumerateResourceURLReferences:] : 364 -> 360
~ -[PHMediaFormatConversionRequest sourceSupportsPassthroughConversion] : 408 -> 404
~ -[PHMediaFormatConversionRequest destinationCapabilitiesHintsIndicateSupportForSource] : 728 -> 720
~ -[PHMediaFormatAssetBundleConversionRequest enqueueSubrequestsOnConversionManager:] : 372 -> 368
~ -[PHMediaFormatAssetBundleConversionRequest enumerateSubrequests:] : 280 -> 276
~ ___44-[PHMediaFormatConversionManager invalidate]_block_invoke : 460 -> 456
~ +[PAMediaConversionServiceImagingUtilities imageDataForPassthroughConversionForSourceURL:metadataPolicy:outResultImageSize:] : 1028 -> 1132
~ +[PAMediaConversionServiceImagingUtilities logMissingPropertiesInCMPhotoOutputData:comparedToProcessedSourceImagePropertiesByIndex:] : 836 -> 832
~ -[ConversionOptionSet validateAndProcess] : 1136 -> 1132
~ -[ConversionOptionSet checkDestinationExists] : 540 -> 536
~ -[MediaConversionServiceCommandLineDriver hasConversionOfType:] : 304 -> 300
~ +[MediaConversionServiceCommandLineDriver replacementObjectForObject:valueConversionHandler:] : 780 -> 776
~ -[MediaConversionServiceCommandLineDriver validateAndProcessArgumentValues] : 300 -> 296
CStrings:
+ "Image source contains no decodable images, cannot perform passthrough conversion: %@"
```
