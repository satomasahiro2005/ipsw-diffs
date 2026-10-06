## ScreenshotServices

> `/System/Library/PrivateFrameworks/ScreenshotServices.framework/ScreenshotServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e5ac` | `0x1e570` | **`-0x3c`** |

### Other Changes

```diff

-437.100.0.0.0
+440.0.0.0.0
Functions:
~ -[SSHarvestedApplicationMetadata loggableDescription] : 532 -> 528
~ +[SSScreenshotMetadataHarvester _crawlViewController:executingBlock:] : 368 -> 364
~ +[SSScreenshotMetadataHarvester _crawlView:executingBlock:] : 308 -> 304
~ +[SSScreenshotMetadataHarvester screenshotServiceWithIdentifier:] : 500 -> 496
~ -[SSSnapshotter captureSnapshotsForScreenshotCapturingContexts:withOptionsCollection:didFindOnenessScreens:] : 528 -> 524
~ -[SSEnvironmentDescription takeElementsFromDisplayLayout:] : 356 -> 352
~ -[SSEnvironmentDescription loggableDescription] : 1168 -> 1164
~ -[SSScreenCapturer _captureAndSendMetadataAndDocumentForEnvironmentDescription:metadataCaptureCompletion:] : 1204 -> 1196
~ +[SSXPCEncodableRectWrapper encodedRectsInDictionary:forKey:] : 388 -> 384
~ +[SSXPCEncodableRectWrapper encodeRects:inDictionary:forKey:] : 396 -> 392
~ __SSHDRCaptureSupported : 320 -> 316
~ -[SSEnvironmentElementMetadata loggableDescription] : 408 -> 404
~ -[SSEnvironmentElementMetadata _encodableRects] : 348 -> 344
~ -[SSEnvironmentElementMetadata _decodedRectsForEncodedRects:] : 336 -> 332
```
