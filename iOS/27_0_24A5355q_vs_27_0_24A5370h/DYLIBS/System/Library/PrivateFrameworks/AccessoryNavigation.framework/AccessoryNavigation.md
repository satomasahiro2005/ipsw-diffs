## AccessoryNavigation

> `/System/Library/PrivateFrameworks/AccessoryNavigation.framework/AccessoryNavigation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb30c` | `0xb22c` | **`-0xe0`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1
Functions:
~ -[ACCNavigationAccessory updateRouteGuidanceInfo:componentList:] : 392 -> 388
~ -[ACCNavigationAccessory iterateComponentIdList:block:] : 488 -> 480
~ -[ACCNavigationLaneGuidanceInfo copyDictionary] : 372 -> 368
~ -[ACCNavigationRoadObjectDetectionInfo description] : 688 -> 676
~ -[ACCNavigationRoadObjectDetectionInfo setInfoFromDictionary:] : 1020 -> 1008
~ -[ACCNavigationProvider detachAllAccessories] : 436 -> 432
~ -[ACCNavigationProvider delegatesImplementing:] : 452 -> 448
~ -[ACCNavigationProvider accessoryNavigationAttached:componentList:] : 2764 -> 2752
~ -[ACCNavigationProvider accessoryNavigationDetached:] : 2180 -> 2164
~ -[ACCNavigationProvider accessoryNavigationStartRouteGuidance:componentIdList:options:] : 1764 -> 1756
~ -[ACCNavigationProvider accessoryNavigationStopRouteGuidance:componentIdList:] : 1408 -> 1400
~ -[ACCNavigationProvider accessoryNavigationObjectDetection:componentIdList:updateInfo:] : 1500 -> 1496
~ -[ACCNavigationProvider objectDetection:startComponentIdList:objectTypes:] : 912 -> 908
~ -[ACCNavigationProvider objectDetection:stopComponentIdList:] : 748 -> 744
~ ___init_logging_signpost_modules_block_invoke : 608 -> 588
~ -[ACCNavigationAccessoryObjectDetectionComponent description] : 356 -> 352
~ -[ACCNavigationAccessory componentListForIdList:] : 436 -> 432
~ -[ACCNavigationAccessory updateManeuverInfo:componentList:] : 392 -> 388
~ -[ACCNavigationAccessory updateLaneGuidanceInfo:componentList:] : 392 -> 388
~ -[ACCNavigationAccessory objectDetectionComponentListForIdList:] : 636 -> 632
~ -[ACCNavigationAccessory objectDetectionComponentIdListIsEnabled:] : 1000 -> 992
~ ___init_logging_modules_block_invoke : 608 -> 588
~ _accessoryServer_registerAvailabilityChangedHandlerForServiceEntry : 444 -> 436
~ __SetupAvailabilityChangedHandlerForServiceEntry : 864 -> 852
~ _accessoryServer_unregisterAvailabilityChangedHandlerForServiceEntry : 280 -> 268
~ _accessoryServer_isServerAvailableForServiceEntry : 368 -> 348
```
