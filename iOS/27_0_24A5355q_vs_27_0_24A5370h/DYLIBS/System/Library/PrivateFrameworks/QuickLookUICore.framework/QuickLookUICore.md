## QuickLookUICore

> `/System/Library/PrivateFrameworks/QuickLookUICore.framework/QuickLookUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21390` | `0x213b0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x20f0` | `0x20f8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x313c` | `0x3144` | **`+0x8`** |

### Other Changes

```diff

-1027.1.0.0.0
+1029.0.0.0.0

-  Functions: 1028
-  Symbols:   2146
+  Functions: 1029
+  Symbols:   2147
Symbols:
+ +[QLTextItemTransformer preferredEncodingForData:guessedEncoding:]
Functions:
~ -[QLToolbarButton handleLongPress:] : 904 -> 900
~ -[QLTextItemTransformer transformedContentsFromURL:context:error:] : 204 -> 244
~ -[QLTextItemTransformer transformedContentsFromData:context:error:] : 200 -> 224
+ +[QLTextItemTransformer preferredEncodingForData:guessedEncoding:]
~ +[QLTextItemTransformer wrapperFromData:encoding:typeIdentifier:error:] : 2256 -> 2200
~ -[QLPreviewConverterParts computePreviewInThread] : 2212 -> 2208
~ -[QLPreviewConverterParts startDataRepresentationWithContentType:properties:] : 1328 -> 1324
~ +[UIScreen(_QLUtilities) maxScreenScale] : 272 -> 268
~ ___33-[QLItemFetcher _notifyObservers]_block_invoke : 268 -> 264
~ _QLIWorkCalculatePreview : 1812 -> 1808
~ -[NSURL(_QL_Utilities) _QLUrlFileSize] : 892 -> 888
~ -[QLNetworkStateObserver _updateCompletionBlocks] : 352 -> 348
~ -[AVAsset(_QLUtilities) ql_hasValidVideoTrack] : 356 -> 352
~ ___38+[QLPreviewConverter convertibleTypes]_block_invoke : 360 -> 356
~ -[QLPreviewConverter appendDataArray:] : 752 -> 744
~ -[QLPreviewConverter _writeDataArrayIntoStream:] : 516 -> 512
~ ___57-[QLUbiquitousItemFetcher subscribeToPreviewItemProgress]_block_invoke : 616 -> 612
~ -[QLUbiquitousItemFetcher cancelFetch] : 340 -> 336
~ -[QLUbiquitousItemFetcher observeValueForKeyPath:ofObject:change:context:] : 640 -> 636
~ ___49+[QLItem(PreviewInfo) contentTypesToPreviewTypes]_block_invoke : 1828 -> 1816
~ -[QLItemViewController performCompletionBlocksWithError:] : 296 -> 292
~ _QLOfficeCalculatePreview : 1316 -> 1312
```
