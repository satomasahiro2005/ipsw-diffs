## VirtualGarage

> `/System/Library/PrivateFrameworks/VirtualGarage.framework/VirtualGarage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a60c` | `0x3a4f4` | **`-0x118`** |

### Other Changes

```diff

-2429.30.5.14.3
+2433.30.6.5.1
Functions:
~ -[VGVirtualGarage _vehicleWithIdentifier:] : 1028 -> 1024
~ -[VGVirtualGarage _garageCopy] : 456 -> 452
~ -[VGVehicle initWithMapsSyncVehicle:] : 1636 -> 1632
~ ___37-[VGVehicle initWithMapsSyncVehicle:]_block_invoke : 1088 -> 1084
~ -[VGVehicle _pruneStaleVehicleStates] : 476 -> 472
~ ___48-[_VGOEMExtensionConnection initWithConnection:]_block_invoke : 620 -> 616
~ ___50-[_VGOEMExtensionConnection resumeWithCompletion:]_block_invoke : 840 -> 836
~ ___50-[_VGOEMExtensionConnection resumeWithCompletion:]_block_invoke.27 : 656 -> 652
~ -[VGDataCoordinator _updateGarageWithVehicle:syncAcrossDevices:] : 3076 -> 3068
~ ___45-[VGDataCoordinator finishOnboardingVehicle:]_block_invoke : 1164 -> 1160
~ ___35-[VGDataCoordinator unpairVehicle:]_block_invoke : 1140 -> 1136
~ ___44-[VGDataCoordinator endAllContinuousUpdates]_block_invoke : 388 -> 384
~ ___52-[VGDataCoordinator _refreshStateForTrackedVehicles]_block_invoke : 1012 -> 1004
~ -[VGDataCoordinator _applicationForVehicle:] : 360 -> 356
~ -[VGDataCoordinator _loadAllOEMVehiclesForApps:completion:] : 876 -> 872
~ ___59-[VGDataCoordinator _loadAllOEMVehiclesForApps:completion:]_block_invoke.86 : 520 -> 516
~ ___41-[VGDataCoordinator vehicleStateUpdated:]_block_invoke : 1164 -> 1160
~ -[VGDataCoordinator vehicleWithIdentifier:] : 520 -> 516
~ ___49-[VGDataCoordinator accessoryUpdatedWithVehicle:]_block_invoke : 988 -> 984
~ -[VGDataCoordinator _removeUnpairedIapVehicleIfNeeded] : 636 -> 632
~ ___36-[VGDataCoordinator OEMAppsUpdated:]_block_invoke : 2608 -> 2596
~ ___36-[VGDataCoordinator OEMAppsUpdated:]_block_invoke.91 : 812 -> 808
~ -[VGExternalAccessoryState _updateWithVehicleInfo:] : 2132 -> 2128
~ ___66-[VGExternalAccessory _checkAvailableAccessoriesAndAttachIfNeeded]_block_invoke : 884 -> 868
~ -[VGExternalAccessory _isConnectedToCarPlayAccessory] : 260 -> 256
~ _VGDictionaryFromVGVehicleArguments : 732 -> 728
~ _VGFilter : 408 -> 404
~ _VGChargingConnectorTypeOptionsUnpacked : 312 -> 308
~ _VGChargingConnectorTypeOptionsPacked : 256 -> 252
~ ___56-[VGChargingNetworkAvailabilityProvider _reloadNetworks]_block_invoke : 648 -> 644
~ -[VGChargingNetwork initWithBrandInfoMapping:] : 772 -> 768
~ -[VGDenylistEntry description] : 1780 -> 1768
~ -[VGExternalAccessoryModelFilter _initializeAllowAndDenylists] : 2160 -> 2152
~ ___62-[VGExternalAccessoryModelFilter _initializeAllowAndDenylists]_block_invoke.41 : 332 -> 328
~ -[VGExternalAccessoryModelFilter allowsVehicleWithModelId:firmwareId:year:model:] : 1452 -> 1448
~ -[VGVirtualGarage description] : 812 -> 808
~ -[VGVirtualGarage _saveVehicle:syncAcrossDevices:] : 1216 -> 1212
~ -[VGVirtualGarage _onboardVehicle:] : 1316 -> 1312
~ -[VGVirtualGarage _executeQueuedCompletionHandlersIfNeeded] : 564 -> 560
~ -[VGVirtualGarage _removeVehiclesWithUninstalledAppsIfNeeded] : 780 -> 776
~ -[VGVirtualGarage _forceUpdateWithVehicles:] : 2236 -> 2224
~ -[VGChargingNetworksStorage dictionaryRepresentation] : 492 -> 488
~ -[VGChargingNetworksStorage writeTo:] : 332 -> 328
~ -[VGChargingNetworksStorage copyWithZone:] : 380 -> 376
~ -[VGChargingNetworksStorage mergeFrom:] : 336 -> 332
~ -[VGOEMApplicationFinder allowlist] : 772 -> 768
~ ___54-[VGOEMApplicationFinder valueChangedForGEOConfigKey:]_block_invoke : 588 -> 584
~ ___45-[VGOEMApplicationFinder findOEMApplications]_block_invoke : 1404 -> 1400
~ ___49-[VGOEMApplicationFinder applicationsDidInstall:]_block_invoke : 552 -> 548
~ ___51-[VGOEMApplicationFinder applicationsDidUninstall:]_block_invoke : 528 -> 524
~ -[VGOEMApplication _VGChargingConnectorTypeOptionsFromINCarChargingConnectorTypes:] : 396 -> 392
~ -[VGOEMApplication _vehiclesFromListCarsIntentResponse:] : 1508 -> 1504
~ -[VGOEMApplication _powerByConnectorDictionaryFromCar:] : 1252 -> 1248
~ -[VGVirtualGarageServer _cleanUp] : 280 -> 276
~ ___48-[VGVirtualGarageServer virtualGarageDidUpdate:]_block_invoke_2 : 404 -> 400
~ -[VGVirtualGarageServer virtualGarage:didUpdateUnpairedVehicles:] : 1180 -> 1176
~ ___65-[VGVirtualGarageServer virtualGarage:didUpdateUnpairedVehicles:]_block_invoke_2 : 404 -> 400
~ -[VGVirtualGarageService virtualGarage:didUpdateUnpairedVehicles:] : 800 -> 796
```
