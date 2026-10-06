## AXSoundDetectionUI

> `/System/Library/PrivateFrameworks/AXSoundDetectionUI.framework/AXSoundDetectionUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x562f8` | `0x56248` | **`-0xb0`** |

### Other Changes

```diff

-527.0.0.0.0
+530.0.0.0.0
Functions:
~ -[AXSDDetectorStore _areStandardDetectorsReady] : 428 -> 424
~ -[AXSDDetectorStore _areKShotDetectorsReady] : 380 -> 376
~ -[AXSDDetectorStore _createSDDetectors] : 540 -> 536
~ -[AXSDDetectorStore _removeCustomDetectors] : 312 -> 308
~ -[AXSDDetectorStore _reloadCustomDetectors] : 364 -> 360
~ -[AXSDDetectorStore downloadDetectors] : 424 -> 420
~ -[AXSDDetectorStore _downloadAssetsFromDetectors:] : 884 -> 880
~ -[AXSDDetectorStore _purgeAssetsFromDetectors:] : 796 -> 788
~ -[AXSDDetectorStore _detectorsNeedingUpgrade] : 736 -> 732
~ -[AXSDDetectorStore detectorWithIdentifier:] : 580 -> 576
~ -[AXSDDetectorStore _detectorWithIdentifier:] : 588 -> 580
~ -[AXSDDetectorStore _detectorWithName:] : 372 -> 368
~ -[AXSDDetectorStore allDetectorsByIdentifier] : 416 -> 412
~ -[AXSDDetectorStore detectorsByIdentifier] : 416 -> 412
~ -[AXSDDetectorStore localizedNamesByIdentifier] : 588 -> 580
~ -[AXSDDetectorStore _enumerateObserversWithBlock:] : 320 -> 316
~ -[AXSDDetectorStore assetManager:didFinishRefreshingAssets:wasSuccessful:error:] : 1044 -> 1040
~ -[AXSDDetectorStore assetManager:didFinishPurgingAssets:wasSuccessful:error:] : 544 -> 540
~ +[AXSDUltronInternalRecordingManager _cleanupUltronFiles:] : 456 -> 452
~ ___58-[AXSDUltronInternalRecordingManager _recordResultToFile:]_block_invoke : 2800 -> 2784
~ +[AXSDUltronInternalRecordingManager _reduceFileDirectorySize] : 2100 -> 2092
~ -[AXSDKShotController savedTrainingRecordingForDetector:] : 428 -> 424
~ +[AXSDKShotRecordingManager _cleanupKShotFiles:] : 548 -> 544
~ +[AXSDKShotRecordingManager _retrieveFilesOlderThan:] : 904 -> 896
~ ___54-[AXSDKShotRecordingManager _recordCachedResultToFile]_block_invoke : 2180 -> 2176
~ -[AXSDKShotRecordingManager updateShouldSendSimilarityWarning:] : 824 -> 820
~ -[AXSDKShotRecordingManager request:didProduceResult:] : 368 -> 364
~ -[AXSDListenEngine _notifyListeningStartedWithError:] : 500 -> 492
~ ___52-[AXSDListenEngine notifyListeningEncounteredError:]_block_invoke : 320 -> 316
~ -[AXSDListenEngine notifyListeningReceivedAudioFile:] : 400 -> 396
~ -[AXSDListenEngine notifyListeningFinishedAudioFile:] : 400 -> 396
~ -[AXSDListenEngine _shouldResumeListening] : 256 -> 252
~ ___51-[AXSDAudioLevelsHelper updateListenersWithBuffer:]_block_invoke : 600 -> 596
~ -[AXUltronModelAssetManager notifyAssetsReady] : 352 -> 348
~ -[AXUltronModelAssetManager notifyAssetsNotReady] : 260 -> 256
~ -[AXUltronModelAssetManager notifyDownloadProgress:totalSizeExpected:totalRemainingTime:isStalled:] : 348 -> 344
~ -[AXUltronModelAssetManager notifyRefreshAssets:wasSuccessful:error:] : 440 -> 436
~ -[AXUltronModelAssetManager notifyPurgeAssets:wasSuccessful:error:] : 440 -> 436
~ -[AXUltronModelAssetManager totalSizeOccupied] : 328 -> 324
~ -[AXUltronModelAssetManager totalSizeExpected] : 328 -> 324
~ -[AXUltronModelAssetManager stopDownloadingAssets] : 380 -> 376
~ ___44-[AXUltronModelAssetManager downloadAssets:]_block_invoke_2 : 464 -> 460
~ -[AXUltronModelAssetManager _downloadAssets] : 944 -> 940
~ -[AXUltronModelAssetManager _totalBytesOfAllAssetsWritten] : 304 -> 300
~ -[AXUltronModelAssetManager _expectedCurrentlyDownloadingSize] : 364 -> 360
~ -[AXUltronModelAssetManager _totalExpectedTimeOfAllAssets] : 304 -> 300
~ -[AXUltronModelAssetManager isAssetDownloadStalled] : 300 -> 296
~ ___91-[AXUltronModelAssetManager assetController:didFinishRefreshingAssets:wasSuccessful:error:]_block_invoke : 544 -> 540
~ -[AXUltronModelAssetManager _filterAssetsToCache:] : 500 -> 496
~ -[AXUltronModelAssetManager _supportedTypesFromAssets:] : 856 -> 848
~ -[AXSDDetectorManager _startDetectionWithFormat:] : 884 -> 880
~ -[AXSDKShotDetectorQueueManager assetsNotReadyForUltronManager:] : 504 -> 500
~ -[AXSDKShotModelManager startDetectionWithFormat:] : 788 -> 784
~ ___59-[AXSDDetectorQueueManager detectorsReadyForDetectorStore:]_block_invoke : 1020 -> 1012
~ -[AXSDDetectorQueueManager detectorStore:detectorsNeedUpdate:toDetectors:] : 688 -> 680
~ sub_2491541d0 -> sub_24a2240c4 : 280 -> 276
~ sub_249155f28 -> sub_24a225e18 : 152 -> 164
~ sub_2491566d8 -> sub_24a2265d4 : 188 -> 200
~ sub_24916579c -> sub_24a2356a4 : 488 -> 492
~ sub_249165a64 -> sub_24a235970 : 264 -> 276
~ sub_249165f5c -> sub_24a235e74 : 252 -> 276
~ sub_249166058 -> sub_24a235f88 : 240 -> 248
~ sub_249166148 -> sub_24a236080 : 244 -> 252
~ sub_249167bc4 -> sub_24a237b04 : 72 -> 88
~ sub_249171018 -> sub_24a240f68 : 2188 -> 2196
~ sub_2491737b0 -> sub_24a243708 : 1712 -> 1716
~ sub_249173e60 -> sub_24a243dbc : 1868 -> 1856
~ sub_249176af4 -> sub_24a246a44 : 552 -> 560
~ sub_24917e724 -> sub_24a24e67c : 344 -> 340
~ sub_249180fe0 -> sub_24a250f34 : 304 -> 300
```
