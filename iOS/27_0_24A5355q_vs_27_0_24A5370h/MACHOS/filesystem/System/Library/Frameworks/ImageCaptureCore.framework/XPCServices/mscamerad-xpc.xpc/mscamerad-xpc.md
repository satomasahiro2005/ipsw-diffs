## mscamerad-xpc

> `/System/Library/Frameworks/ImageCaptureCore.framework/XPCServices/mscamerad-xpc.xpc/mscamerad-xpc`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15850` | `0x15964` | **`+0x114`** |
| `__DATA_CONST.__cfstring` | `0x1da0` | `0x1dc0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1117` | `0x1136` | **`+0x1f`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2112.0.0.0.0
+2113.0.0.0.0

-  CStrings:  989
+  CStrings:  990
Functions:
~ -[MSCameraDevice itemsInFolder:] : 812 -> 804
~ ___43-[MSCameraDevice sendContentsNotification:]_block_invoke : 1448 -> 1440
~ -[MSCameraDevice preflight:] : 2044 -> 2040
~ -[MSCameraDevice preflight] : 652 -> 648
~ -[MSCameraDevice reflight:error:] : 1088 -> 1084
~ ___26-[MSCameraDevice reflight]_block_invoke : 2868 -> 2848
~ -[MSCameraDevice enumerateContentWithOptions:] : 1008 -> 1004
~ -[MSCameraDevice copyIndexedFoldersAndFilesURLs] : 760 -> 752
~ -[ICBufferCache dealloc] : 308 -> 304
~ ___62-[AVAsset(VideoOrientation) decodableVideoNamed:width:height:]_block_invoke : 1244 -> 1240
~ -[MSCameraFile rawImageMinimumProperties] : 1508 -> 1504
~ -[MSCameraFile subImageDictForPixelWidth:] : 1252 -> 1248
~ ___28-[MSCameraFile metadataDict]_block_invoke : 1924 -> 1920
~ -[NSArray(ImageCaptureAdditions) copyGroupIntoDictionary:] : 416 -> 412
~ ___46-[MSCameraFolder enumerateContentWithOptions:]_block_invoke : 3328 -> 3724
~ _IsSupportedMassStorageCameraVolume : 992 -> 984
~ ___57-[MSRemoteCameraDeviceManager startMSDeviceNotifications]_block_invoke : 988 -> 984
~ -[MSRemoteCameraDeviceManager processMountURLs:] : 640 -> 632
~ -[MSRemoteCameraDeviceManager processRemovedURLs:] : 560 -> 556
~ -[MSRemoteCameraDeviceManager processAddedURLs:] : 2296 -> 2292
~ -[MSRemoteCameraDeviceManager updatedWithAddedMountPoints:andRemovedMountPoints:] : 1128 -> 1120
CStrings:
+ "[%18s] - Symbolic link ignored"
```
