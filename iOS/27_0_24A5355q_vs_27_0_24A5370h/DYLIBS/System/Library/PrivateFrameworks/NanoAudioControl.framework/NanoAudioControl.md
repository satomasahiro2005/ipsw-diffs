## NanoAudioControl

> `/System/Library/PrivateFrameworks/NanoAudioControl.framework/NanoAudioControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26398` | `0x26344` | **`-0x54`** |

### Other Changes

```diff

-2024.100.38.0.0
+2024.100.44.0.0
Functions:
~ -[NACRoutingControllerLocal pickAudioRoute:] : 416 -> 412
~ -[NACRoutingControllerLocal availableAudioRoutes] : 324 -> 320
~ -[NACProxyVolumeControlTarget description] : 128 -> 124
~ -[NACXPCClient _resumeVolumeObservingIfNecessary] : 248 -> 244
~ -[NACXPCClient _resumeListeningModesObservingIfNecessary] : 248 -> 244
~ -[NACXPCClient _resumeRouteObservingIfNecessary] : 272 -> 268
~ -[NACIDSServer _handlePlayTone:] : 1000 -> 996
~ -[NACIDSServer _handleStopTone:] : 468 -> 464
~ -[NACIDSServer _nacVolumeControllerForTarget:createIfNeeded:] : 224 -> 220
~ ___38-[NACIDSServer _handlePickAudioRoute:]_block_invoke : 568 -> 564
~ -[NACIDSServer _beginObservingSystemVolume] : 1076 -> 1088
~ -[NACIDSServer _sendCurrentObservingSystemVolumeValues] : 568 -> 564
~ ___54-[NACIDSServer volumeController:volumeValueDidChange:]_block_invoke : 308 -> 304
~ -[NACIDSServer _sendAvailableListeningModes:currentListeningMode:error:forTarget:] : 724 -> 720
~ -[NACXPCServer _persistVolumeRecords] : 496 -> 492
~ -[NACXPCServer _cleanupConnection:] : 456 -> 448
~ ___50-[NACRoutingControllerProxy _audioRoutesDidChange]_block_invoke : 424 -> 420
~ -[NACAudioRoutesMessage dictionaryRepresentation] : 440 -> 436
~ -[NACAudioRoutesMessage writeTo:] : 308 -> 304
~ -[NACAudioRoutesMessage copyWithZone:] : 356 -> 352
~ -[NACAudioRoutesMessage mergeFrom:] : 308 -> 304
~ ___74-[_NACAVRoutingDiscoverySession fetchRouteForOriginIdentifier:completion:]_block_invoke : 504 -> 500
~ -[NACListeningModesMessage writeTo:] : 428 -> 424
~ -[NACListeningModesMessage copyWithZone:] : 500 -> 496
~ -[NACListeningModesMessage mergeFrom:] : 420 -> 416
~ +[NACAudioRoute audioRoutesFromBuffers:] : 324 -> 320
~ +[NACAudioRoute buffersFromAudioRoutes:] : 316 -> 312
~ -[MediaControlsVolumeController imageForRouteType:] : 80 -> 84
~ -[MediaControlsVolumeController currentBluetoothListeningModeForRouteType:] : 64 -> 72
~ -[MediaControlsVolumeController setCurrentBluetoothListeningModeForRouteType:bluetoothListeningMode:error:] : 152 -> 156
~ -[MediaControlsVolumeController availableBluetoothListeningModeForRouteType:] : 96 -> 92
~ -[MediaControlsVolumeController volumeControlAvailableForRouteType:] : 28 -> 32
~ -[MediaControlsVolumeController setVolume:forRouteType:] : 32 -> 36
~ ___59-[MediaControlsVolumeController routeDidChangeNotification]_block_invoke : 276 -> 272
~ -[MediaControlsVolumeController _notifyVolumeChangedForVolumeController:volumeControlAvailable:effectiveVolume:] : 328 -> 324
```
