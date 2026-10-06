## WatchKit

> `/System/Library/Frameworks/WatchKit.framework/WatchKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36b1c` | `0x36a6c` | **`-0xb0`** |

### Other Changes

```text
Functions:
~ -[WKInterfaceObject(WKAccessibility) setAccessibilityImageRegions:] : 556 -> 552
~ ____WKValidatedAttributedString_block_invoke : 2140 -> 2136
~ +[SPAssetCacheAssets toProto:] : 340 -> 336
~ +[SPAssetCacheAssets fromProto:] : 364 -> 360
~ -[SPProtoCacheAssets dictionaryRepresentation] : 404 -> 400
~ -[SPProtoCacheAssets writeTo:] : 276 -> 272
~ -[SPProtoCacheAssets copyWithZone:] : 316 -> 312
~ -[SPProtoCacheAssets mergeFrom:] : 260 -> 256
~ -[SPColorWrapper encodeWithCoder:] : 668 -> 660
~ __RunLoopHandler : 940 -> 932
~ ___54+[SPRemoteInterface setController:key:property:value:]_block_invoke : 1832 -> 1824
~ +[SPRemoteInterface reloadRootControllersWithNames:contexts:] : 408 -> 404
~ +[SPRemoteInterface insertPageControllerAtIndexes:withNames:contexts:] : 388 -> 384
~ +[SPRemoteInterface controller:presentInterfaceControllers:contexts:] : 420 -> 416
~ ___45-[SPRemoteInterface _dumpInterfaceDictionary]_block_invoke : 620 -> 616
~ -[SPRemoteInterface removeInterfaceControllersForClient:] : 572 -> 568
~ +[SPRemoteInterface controller:setupProperties:viewControllerID:tableIndex:rowIndex:classForType:] : 1364 -> 1356
~ ___58-[SPRemoteInterface handlePlistDictionary:fromIdentifier:]_block_invoke : 360 -> 356
~ -[SPRemoteInterface controllerMethods:] : 244 -> 240
~ +[WKApplicationProxy applicationsForContainerProxy:] : 752 -> 748
~ ___77-[SPDeviceConnection showUserNotification:applicationName:extensionBundleID:]_block_invoke_2 : 328 -> 324
~ -[SPDeviceConnection _enumerateObserversSafely:] : 280 -> 276
~ ___SPLaunchSockPuppetAppForCompanionAppWithIdentifier_block_invoke : 852 -> 848
~ -[WKInterfaceController didRegisterWithRemoteInterface] : 240 -> 236
~ -[SPProtoAudioFileQueuePlayerSetItems writeTo:] : 300 -> 296
~ -[SPProtoAudioFileQueuePlayerSetItems copyWithZone:] : 356 -> 352
~ -[SPProtoAudioFileQueuePlayerSetItems mergeFrom:] : 308 -> 304
~ +[SPProtoSerializer spPlistWithArray:] : 1008 -> 1004
~ +[SPProtoSerializer spPlistWithDictionary:] : 1028 -> 1024
~ -[SPProtoSockPuppetPlist dictionaryRepresentation] : 404 -> 400
~ -[SPProtoSockPuppetPlist writeTo:] : 276 -> 272
~ -[SPProtoSockPuppetPlist copyWithZone:] : 316 -> 312
~ -[SPProtoSockPuppetPlist mergeFrom:] : 260 -> 256
~ -[SPAssetCacheClientCache syncAssets:] : 788 -> 780
~ -[SPAssetCacheClientCache clearSpaceForAsset:] : 344 -> 340
~ -[SPAssetCacheClientCache deleteAllAssets] : 484 -> 480
~ -[SPAssetCacheClientCache cachedImages] : 400 -> 396
~ -[SPCompanionAssetCache clearedCache:] : 240 -> 236
~ -[WKInterfaceTable resequenceRowControllerPropertyIndexes] : 400 -> 396
```
