## CloudPhotoServices

> `/System/Library/PrivateFrameworks/CloudPhotoServices.framework/CloudPhotoServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b78` | `0x7b6c` | **`-0xc`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0
Functions:
~ +[CloudPhotoServices transcodeVideoAtURL:withAdjustments:destinationURL:partialResultsURL:options:reason:isCancellable:completionHandler:] : 1736 -> 1756
~ ___138+[CloudPhotoServices transcodeVideoAtURL:withAdjustments:destinationURL:partialResultsURL:options:reason:isCancellable:completionHandler:]_block_invoke -> ___CPLResumableDerivativeGenerationOSLogDomain : 496 -> 84
~ ___CPLResumableDerivativeGenerationOSLogDomain -> ___138+[CloudPhotoServices transcodeVideoAtURL:withAdjustments:destinationURL:partialResultsURL:options:reason:isCancellable:completionHandler:]_block_invoke : 84 -> 496
~ ___176+[CloudPhotoServices _generateImageDerivativeResourcesFromInputResource:destinationDirectory:fingerprintScheme:isAdjusted:derivativesFilter:recordChangeType:completionHandler:]_block_invoke_3 : 2232 -> 2224
~ +[CloudPhotoServices _createDerivativeResourcesFromInputURL:resourceTypes:withItemScopedIdentifier:destinationDirectory:fingerprintScheme:outputResources:convertToSRGB:] : 1400 -> 1384
~ +[CloudPhotoServices _createPosterFrameResourcesFromInputURL:withItemScopedIdentifier:includeDerivative:destinationDirectory:fingerprintScheme:outputResources:] : 588 -> 584
~ +[CloudPhotoServices _generateVideoDerivativeResourcesFromInputResource:withCPLAdjustments:destinationDirectory:fingerprintScheme:derivativesFilter:recordChangeType:includePosterFrame:completionHandler:] : 4396 -> 4392
```
