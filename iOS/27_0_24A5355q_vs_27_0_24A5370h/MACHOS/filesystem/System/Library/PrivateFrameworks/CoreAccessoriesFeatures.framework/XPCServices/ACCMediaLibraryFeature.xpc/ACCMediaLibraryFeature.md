## ACCMediaLibraryFeature

> `/System/Library/PrivateFrameworks/CoreAccessoriesFeatures.framework/XPCServices/ACCMediaLibraryFeature.xpc/ACCMediaLibraryFeature`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a510` | `0x2a410` | **`-0x100`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1
Functions:
~ ___init_logging_signpost_modules_block_invoke : 608 -> 588
~ _convertNSDataToNSString : 260 -> 256
~ _convertNSStringToNSData : 444 -> 440
~ _classImplementsMethodsInProtocol : 304 -> 300
~ _base64EncodeArray : 328 -> 324
~ _base64DecodeArray : 340 -> 336
~ -[MediaLibraryHelper applicationsDidInstall:] : 244 -> 240
~ -[MediaLibraryHelper applicationsWillUninstall:] : 244 -> 240
~ -[MediaLibraryHelper applicationsDidUninstall:] : 244 -> 240
~ ___48-[ACCMediaLibraryXPCService broadcastToClients:]_block_invoke : 300 -> 296
~ ___45-[ACCMediaLibraryXPCService markFeatureReady]_block_invoke : 464 -> 460
~ _ascii_to_hex : 156 -> 160
~ _printBytes : 136 -> 156
~ ___init_logging_modules_block_invoke : 608 -> 588
~ -[ACCMediaLibraryUpdatePlaylistContent initWithMediaLibrary:revision:dict:] : 872 -> 864
~ -[ACCMediaLibraryUpdatePlaylistContent copyContentDictList] : 576 -> 568
~ -[ACCMediaLibraryUpdatePlaylistContent iterateContentItems:] : 296 -> 292
~ -[ACCMediaLibraryUpdatePlaylistContent iterateContentPersistentIDs:] : 304 -> 300
~ +[ACCMediaLibraryShimInfo getMediaItemForContentItem:propertyList:playlistContent:] : 840 -> 836
~ -[ACCMediaLibraryShimInfo _handlePlaylistContentForEntify:style:revision:] : 2084 -> 2072
~ -[ACCMediaLibraryShimInfo _handleMediaLibraryPlaylistUpdate:forLibrary:forProperties:success:] : 1872 -> 1868
~ -[ACCMediaLibraryShimInfo _handleMediaLibraryItemUpdate:forLibrary:forProperties:success:forceDelete:] : 2072 -> 2068
~ -[ACCMediaLibraryShimInfo _beginMediaLibraryUpdatesWithAnchor:validity:] : 9276 -> 9268
~ -[ACCMediaLibraryShimInfo _sendRadioLibraryUpdates] : 2432 -> 2424
~ -[ACCMediaLibraryShimInfo playWithQuery:andFirstItem:] : 1552 -> 1548
~ -[ACCMediaLibraryShimInfo startPlaybackOfItems:withFirst:] : 1048 -> 1044
~ -[ACCMediaLibraryShim _updateSubscribedToAppleMusicStatus:] : 360 -> 356
~ -[ACCMediaLibraryShim _setupNewLibraries:forAccessory:] : 1440 -> 1436
~ ___35-[ACCMediaLibraryShim shuttingDown]_block_invoke : 340 -> 336
~ ___30-[ACCMediaLibraryShim dealloc]_block_invoke : 304 -> 300
~ -[ACCMediaLibraryShim _checkForDifferentMediaLibraries] : 568 -> 564
~ -[ACCMediaLibraryShim _sendLibraryInfoList] : 1508 -> 1504
~ -[ACCMediaLibraryShim _updateMediaLibraryInfomationUpdates:] : 504 -> 500
~ -[ACCMediaLibraryShim startMediaLibraryUpdate:lastRevision:requestedInfo:] : 1320 -> 1316
~ ___48-[ACCMediaLibraryShim stopAllMediaLibraryUpdate]_block_invoke : 664 -> 660
~ ___59-[ACCMediaLibraryProvider accessoryMediaLibraryAllDetached]_block_invoke : 860 -> 856
~ -[ACCMediaLibraryProvider _notifyRemoteOfAvailableLibraries] : 572 -> 568
~ ___52-[ACCMediaLibraryProvider notifyAvailableLibraries:]_block_invoke : 1044 -> 1036
~ ___73-[ACCMediaLibraryAccessory copyPendingNonContentUpdatesToSendForLibrary:]_block_invoke : 384 -> 380
~ ___78-[ACCMediaLibraryAccessory copyPendingPlaylistContentUpdatesToSendForLibrary:]_block_invoke : 1512 -> 1508
~ ___58-[ACCMediaLibraryAccessory confirmUpdates:revision:count:]_block_invoke : 1784 -> 1792
~ ___67-[ACCMediaLibraryAccessory confirmPlaylistContentUpdates:revision:]_block_invoke : 384 -> 380
~ _ACCMediaLibraryFeatureRequestedInfoDesc : 844 -> 832
~ _accessoryServer_registerAvailabilityChangedHandlerForServiceEntry : 444 -> 436
~ __SetupAvailabilityChangedHandlerForServiceEntry : 864 -> 852
~ _accessoryServer_unregisterAvailabilityChangedHandlerForServiceEntry : 280 -> 268
~ _accessoryServer_isServerAvailableForServiceEntry : 368 -> 348
~ _createHexString : 408 -> 400
```
