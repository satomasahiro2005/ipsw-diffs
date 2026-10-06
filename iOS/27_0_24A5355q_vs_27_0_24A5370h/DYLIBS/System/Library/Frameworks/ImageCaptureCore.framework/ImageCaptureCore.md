## ImageCaptureCore

> `/System/Library/Frameworks/ImageCaptureCore.framework/ImageCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2cc04` | `0x2cb14` | **`-0xf0`** |
| `__TEXT.__unwind_info` | `0xa08` | `0xa10` | **`+0x8`** |

### Other Changes

```diff

-2112.0.0.0.0
+2113.0.0.0.0
Functions:
~ -[ICPrefManager invalidateQueries] : 552 -> 548
~ ___29-[ICCameraDeviceBrowser init]_block_invoke_3 : 316 -> 312
~ -[ICCameraDeviceBrowser start:] : 616 -> 596
~ -[ICCameraDeviceBrowser notifySuspension:] : 436 -> 432
~ -[ICCameraDeviceBrowser stop:] : 684 -> 668
~ -[ICCameraDeviceBrowser handleImageCaptureEventNotification:] : 948 -> 940
~ -[ICCameraDeviceBrowser deviceWithDelegate:] : 340 -> 336
~ -[ICCameraFolder description] : 440 -> 436
~ -[ICCameraFolder deleteFolderWithID:] : 368 -> 364
~ -[ICCameraFolder deleteFileWithID:] : 368 -> 364
~ -[ICCameraFolder getFolderWithID:] : 336 -> 332
~ -[ICCameraFolder getFileWithID:] : 496 -> 488
~ -[NSMutableArray(ImageCaptureCoreAdditions) addItemsMatchingType:fromFolder:] : 600 -> 592
~ -[NSMutableArray(ImageCaptureCoreAdditions) addItemsMatchingTypes:fromFolder:] : 276 -> 272
~ ___47-[MSCameraDeviceManager startDeviceWithHandle:]_block_invoke : 1020 -> 1016
~ ___42-[MSCameraDeviceManager notifyAddedItems:]_block_invoke : 696 -> 692
~ ___44-[MSCameraDeviceManager notifyUpdatedItems:]_block_invoke : 352 -> 348
~ -[ICDeviceHardwareHandler addDeviceContext:] : 1436 -> 1432
~ -[ICDeviceHardwareHandler removeDeviceContext:] : 1960 -> 1948
~ -[ICDeviceBrowser preferredDevice] : 280 -> 276
~ -[ICDeviceBrowser deviceWithRef:] : 368 -> 364
~ ___43-[PTPCameraDeviceManager notifyAddedItems:]_block_invoke : 692 -> 688
~ ___45-[PTPCameraDeviceManager notifyUpdatedItems:]_block_invoke : 352 -> 348
~ ___48-[PTPCameraDeviceManager startDeviceWithHandle:]_block_invoke : 1732 -> 1728
~ -[ICCameraFile debugIdentity] : 352 -> 348
~ ___54-[ICCameraFile requestDownloadWithOptions:completion:]_block_invoke.299 : 400 -> 396
~ ___36-[ICCameraDevice relateLegacyMedia:]_block_invoke : 616 -> 612
~ ___37-[ICCameraDevice relateGroupedMedia:]_block_invoke : 292 -> 288
~ -[ICCameraDevice stitchMedia:withMedia:] : 704 -> 700
~ -[ICCameraDevice grindMedia:index:file:] : 344 -> 332
~ -[ICCameraDevice removeCameraFileFromIndex:] : 564 -> 560
~ -[ICCameraDevice filesOfType:] : 348 -> 344
~ -[ICCameraDevice containsRestrictedStorage] : 344 -> 340
~ -[ICCameraDevice removeItems:] : 752 -> 748
~ ___61-[ICCameraDevice requestDeleteFiles:deleteFailed:completion:]_block_invoke_2 : 700 -> 696
~ -[ICCameraDevice cameraFilesContentSizeInBytes] : 312 -> 308
~ _ICCreateRotatedImageFromCGImage : 556 -> 564
~ -[NSArray(ImageCaptureCoreAdditions) copyGroupIntoDictionary:] : 440 -> 436
~ ___28-[ICDevice notifyObservers:]_block_invoke : 272 -> 268
~ -[ICDevice addCapability:] : 648 -> 644
~ -[ICDevice removeCapability:] : 412 -> 408
~ -[ICDevice updateCapabilities:] : 736 -> 732
~ -[ICDeviceManager stopRunning] : 336 -> 332
~ ___32-[ICDeviceManager getDeviceList]_block_invoke_3 : 248 -> 244
~ -[ICDeviceManager notifyAddedDevice:] : 692 -> 688
~ -[ICDeviceManager notifyRemovedDevice:] : 432 -> 428
~ ___42-[ICDeviceManager openRemoteDeviceManager]_block_invoke : 864 -> 860
~ -[ICDeviceManager deviceForConnection:] : 376 -> 372
~ -[ICDeviceManager deviceForUUID:] : 376 -> 372
```
