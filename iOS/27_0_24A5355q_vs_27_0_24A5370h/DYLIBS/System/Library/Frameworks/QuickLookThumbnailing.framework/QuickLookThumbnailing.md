## QuickLookThumbnailing

> `/System/Library/Frameworks/QuickLookThumbnailing.framework/QuickLookThumbnailing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31964` | `0x31968` | **`+0x4`** |

### Other Changes

```diff

-215.0.0.0.0
+216.0.0.0.0
Functions:
~ -[QLThumbnailGenerator _handleThumbnailGenerationCompletionWithUUID:images:metadata:contentRect:iconFlavor:thumbnailType:clientShouldTakeOwnership:error:] : 1744 -> 1736
~ ___QLTInitLogging_block_invoke : 108 -> 112
~ sub_20edcd948 -> sub_20fa89944 : 256 -> 276
~ -[QLThumbnailGenerationRequest externalThumbnailGeneratorDataHash] : 320 -> 316
~ ___52-[QLThumbnailGenerator _finishAllRequestsWithError:]_block_invoke : 368 -> 364
~ ___77-[QLExternalThumbnailCacheDatabase oldestThumbnailsToFreeAtLeastSpace:error:]_block_invoke : 588 -> 584
~ +[QLThumbnailAddition associateThumbnailImagesDictionary:serializedQuickLookMetadata:withImmutableDocument:atURL:error:] : 1616 -> 1612
~ +[QLThumbnailAddition imageContainsAlpha:] : 388 -> 384
~ -[QLThumbnailAddition allImageURLs] : 568 -> 564
~ -[QLThumbnailAddition additionSize] : 520 -> 516
~ -[QLServiceThumbnailRenderer _drawMultipleImages] : 652 -> 640
~ -[QLExternalThumbnailCache removeAllThumbnails:] : 772 -> 768
~ -[QLExternalThumbnailCache _freeDiskSpaceToSaveThumbnailRepresentingFPItem:withFileAtURL:error:] : 1020 -> 1016
~ ___61+[QLExternalThumbnailCache writeThumbnailImage:inInboxAtURL:]_block_invoke : 700 -> 696
~ _QLSetContainsContentType : 392 -> 388
~ ___120-[QLThumbnailGenerationQueue enqueueThumbnailGenerationIfNeededForDocumentAtURL:atBackgroundPriority:completionHandler:]_block_invoke.6 : 316 -> 312
~ -[NSURL(_QLUtilities) _QLUrlFileSize] : 864 -> 860
~ sub_20edf1364 -> sub_20faad334 : 204 -> 212
~ sub_20edf2948 -> sub_20faae920 : 456 -> 464
~ sub_20edf3fe4 -> sub_20faaffc4 : 384 -> 388
~ sub_20edf6374 -> sub_20fab2358 : 476 -> 480
~ sub_20edf8040 -> sub_20fab4028 : 408 -> 428
~ sub_20edf81d8 -> sub_20fab41d4 : 256 -> 264
```
