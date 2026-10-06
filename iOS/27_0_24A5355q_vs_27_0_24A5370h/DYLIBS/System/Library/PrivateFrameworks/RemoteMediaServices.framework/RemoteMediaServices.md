## RemoteMediaServices

> `/System/Library/PrivateFrameworks/RemoteMediaServices.framework/RemoteMediaServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8af5c` | `0x8aed4` | **`-0x88`** |

### Other Changes

```diff

-2024.100.4.0.0
+2024.100.5.0.0
Functions:
~ -[RMSFairPlaySession _hexStringForData:] : 192 -> 200
~ -[RMSIDSClient _isCompanionAvailable] : 304 -> 300
~ +[RMSService servicesFromProtobufs:] : 328 -> 324
~ +[RMSService protobufsFromServices:] : 316 -> 312
~ -[RMSTouchRemoteSocket sendTouchCode:timeInMilliseconds:location:] : 672 -> 664
~ -[RMSTouchRemoteSocket _encryptData:] : 212 -> 216
~ -[RMSAvailableServicesDidUpdateMessage dictionaryRepresentation] : 484 -> 480
~ -[RMSAvailableServicesDidUpdateMessage writeTo:] : 324 -> 320
~ -[RMSAvailableServicesDidUpdateMessage copyWithZone:] : 372 -> 368
~ -[RMSAvailableServicesDidUpdateMessage mergeFrom:] : 336 -> 332
~ -[RMSPairingServiceProvider setPairedNetworkNames:] : 388 -> 384
~ -[RMSPairingServer _parsedQueryParametersWithQueryString:] : 464 -> 460
~ ___47-[RMSDAAPNowPlayingManager _requestAudioRoutes]_block_invoke : 684 -> 680
~ -[RMSDAAPNowPlayingManager _audioRoutes:equalAudioRoutes:] : 496 -> 492
~ -[RMSTVRemoteCoreServiceProvider deviceQueryDidUpdateDevices:] : 496 -> 488
~ ___43-[RMSDAAPParser parseListingHeader:length:]_block_invoke : 2020 -> 2016
~ -[RMSUpdatePairedNetworNamesMessage writeTo:] : 324 -> 320
~ -[RMSUpdatePairedNetworNamesMessage copyWithZone:] : 372 -> 368
~ -[RMSUpdatePairedNetworNamesMessage mergeFrom:] : 336 -> 332
~ -[RMSTVRemoteCoreDeviceController deviceQueryDidUpdateDevices:] : 292 -> 288
~ -[RMSIDSServer _cleanupStaleSessions:] : 452 -> 448
~ +[RMSAudioRoute audioRoutesFromProtobufs:] : 328 -> 324
~ +[RMSAudioRoute protobufsFromAudioRoutes:] : 316 -> 312
~ -[RMSAudioRoutesDidUpdateMessage dictionaryRepresentation] : 484 -> 480
~ -[RMSAudioRoutesDidUpdateMessage writeTo:] : 324 -> 320
~ -[RMSAudioRoutesDidUpdateMessage copyWithZone:] : 372 -> 368
~ -[RMSAudioRoutesDidUpdateMessage mergeFrom:] : 336 -> 332
~ ___50-[RMSDAAPTouchRemoteManager _requestPromptUpdate:]_block_invoke : 668 -> 664
~ -[RMSDAAPTouchRemoteManager _parsePortInfoItems:] : 504 -> 500
~ -[RMSTVRemoteCoreControlSession sendTouchMoveWithDirection:repeatCount:] : 400 -> 396
~ -[RMSTVRemoteCoreControlSession sendNavigationCommand:] : 352 -> 348
~ -[RMSBeginDiscoveryMessage writeTo:] : 368 -> 364
~ -[RMSBeginDiscoveryMessage copyWithZone:] : 424 -> 420
~ -[RMSBeginDiscoveryMessage mergeFrom:] : 380 -> 376
~ -[RMSLocalDiscoverySession beginDiscovery] : 272 -> 268
~ -[RMSLocalDiscoverySession endDiscovery] : 260 -> 256
~ -[RMSLocalDiscoverySession setPairedNetworkNames:] : 332 -> 328
```
