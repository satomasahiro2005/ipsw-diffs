## OpusFoundation

> `/System/Library/PrivateFrameworks/SlideshowKit.framework/Frameworks/OpusFoundation.framework/OpusFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d2e4` | `0x2d1ac` | **`-0x138`** |

### Other Changes

```text
Functions:
~ -[NSArray(OFNSArrayExtensions) containsObjects:] : 248 -> 244
~ -[NSArray(OFNSArrayExtensions) containsAnyObjects:] : 252 -> 248
~ -[NSArray(OFNSArrayExtensions) indexesOfObjects:] : 292 -> 288
~ -[NSData(OFNSDataCryptoExtensions) hexaStringRepresentation] : 276 -> 272
~ -[NSData(OFNSDataExtensions) searchDataByXPathQuery:query:] : 448 -> 444
~ -[NSDictionary(OFNSDictionaryExtensions) postFormData] : 396 -> 392
~ -[NSFileManager(OFNSFileManagerExtensions) unarchiveItemAtPath:toDirectory:withProgressionBlock:] : 2068 -> 2060
~ +[NSURL(NSURLExtensions) parseURLParams:] : 368 -> 364
~ _OFABRecordMobileMeUsernames : 612 -> 604
~ __OFAVAssetTranscodeCreateSession : 980 -> 972
~ -[CALayer(OFCALayerExtensions) sublayerNamed:] : 268 -> 264
~ -[CALayer(OFCALayerExtensions) containsLayer:] : 260 -> 256
~ +[CLRegion(OFCLRegionExtensions) regionWithLocations:andIdentifier:] : 892 -> 884
~ -[MKMapView(OFMKMapViewExtensions) regionToFitAnnotations] : 408 -> 404
~ -[MKMapView(OFMKMapViewExtensions) regionToFitLocations:] : 408 -> 404
~ -[OFRescaler initWithSegments:] : 832 -> 828
~ -[UIImage(OFUIImageExtensions) applyBlurWithRadius:tintColor:saturationDeltaFactor:maskImage:] : 1628 -> 1636
~ -[UIPasteboard(OFUIPasteboardExtension) objectsForPasteboardType:] : 392 -> 388
~ __ParseNumbers : 388 -> 392
~ -[OFNSOperationQueue cancelAllOperationsWithContext:] : 292 -> 288
~ -[OFNSOperationQueue cancelAllOperationsWithIdentifier:] : 296 -> 292
~ -[OFNSOperationQueue cancelAllOperationsWithContext:andIdentifier:] : 324 -> 320
~ -[OFNSOperation cancelOperation] : 508 -> 504
~ -[OFNSOperation cleanupOperation] : 416 -> 412
~ -[OFLRUCache loadFromURL:] : 612 -> 608
~ -[OFImageCache _diskCacheResolutionsForURL:] : 464 -> 460
~ -[OFImageCache purgeDiskCache:progressBlock:] : 972 -> 968
~ ___39-[OFLocationCache invalidateDiskCaches]_block_invoke_2 : 540 -> 536
~ ___101-[OFLocationCache placemarksForLocationCoordinate:andAccuracy:closestResultDistance:numberOfResults:]_block_invoke : 920 -> 916
~ -[OFViewProxy runMagicLayout] : 480 -> 472
~ -[OFUIDismissalView hitTest:withEvent:] : 436 -> 432
~ -[OFUIWindow sendEvent:] : 704 -> 700
~ -[OFUIWindowDraggingSession initWithWindow:items:position:source:] : 448 -> 444
~ -[OFUIWindowDraggingSession _updatePresentationViewWithCompletion:] : 1296 -> 1300
~ ___67-[OFUIWindowDraggingSession _updatePresentationViewWithCompletion:]_block_invoke : 896 -> 892
~ -[OFUIWindowDraggingSession _finishPresentationViewWithCompletion:] : 1420 -> 1412
~ ___67-[OFUIWindowDraggingSession _finishPresentationViewWithCompletion:]_block_invoke : 332 -> 328
~ ___67-[OFUIWindowDraggingSession _finishPresentationViewWithCompletion:]_block_invoke_3 : 888 -> 884
~ -[OFUIWindowDraggingSession itemsContainObject:] : 256 -> 252
~ -[OFUIWindowDraggingSession updateDragging] : 768 -> 764
~ +[OFTextConversion attributedStringWithCTAttributesFromStringAttributes:scaleFactor:] : 1868 -> 1836
~ -[OFUIGridViewController updateDisplayedCellsOperationsPriority] : 244 -> 240
~ -[OFUIGridView _layoutSubviews] : 708 -> 704
~ -[OFUIGridView cleanupDisplayedCells] : 508 -> 504
~ -[OFUIGridView _updateCells] : 1072 -> 1068
~ -[OFUIGridView dequeueReusableCellWithIdentifier:] : 324 -> 320
~ -[OFUIGridView cellAtIndex:] : 276 -> 272
~ -[OFUIGridView displayedCellWithItem:] : 280 -> 276
~ -[OFUIGridView indexesForDisplayedCells] : 280 -> 276
~ -[OFUIGridView visibleCells] : 300 -> 296
~ -[OFUIGridView indexesForVisibleCells] : 308 -> 304
~ -[OFUIGridView insertCellsAtIndexes:animated:] : 932 -> 928
~ ___46-[OFUIGridView insertCellsAtIndexes:animated:]_block_invoke : 592 -> 588
~ ___46-[OFUIGridView insertCellsAtIndexes:animated:]_block_invoke_2 : 324 -> 320
~ -[OFUIGridView deleteCellsAtIndexes:animated:] : 1164 -> 1160
~ ___46-[OFUIGridView deleteCellsAtIndexes:animated:]_block_invoke : 332 -> 328
~ ___46-[OFUIGridView deleteCellsAtIndexes:animated:]_block_invoke_2 : 528 -> 524
~ -[OFUIGridView moveCellsAtIndexes:toIndexes:animated:] : 1204 -> 1196
~ ___54-[OFUIGridView moveCellsAtIndexes:toIndexes:animated:]_block_invoke_2 : 812 -> 804
~ ___54-[OFUIGridView moveCellsAtIndexes:toIndexes:animated:]_block_invoke_3 : 760 -> 752
~ -[OFUIGridViewCell enumerateOperations:] : 360 -> 356
~ -[OFUIGridViewCell setOperationsPriority:] : 308 -> 304
~ -[OFUIGridViewCell cancelAllOperations] : 316 -> 312
~ -[OFUIPagingView reloadData] : 356 -> 352
~ -[OFUIPagingView viewForPageAtIndex:] : 276 -> 272
~ -[OFUIPagingView configurePages] : 1276 -> 1272
~ -[OFUIPagingView willAnimateRotation] : 484 -> 480
~ -[OFUIPagingView didRotate] : 364 -> 360
~ ___47-[OFAudioCaptureManager initWithOutputFileURL:]_block_invoke : 444 -> 440
~ -[OFAudioCaptureManager meanAudioLevel] : 628 -> 632
~ -[OFAudioRecorder _connectionWithMediaType:] : 408 -> 404
```
