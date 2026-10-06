## SensorKitWriting

> `/System/Library/PrivateFrameworks/SensorKitWriting.framework/SensorKitWriting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf2ec` | `0xf268` | **`-0x84`** |

### Other Changes

```diff

-1025.0.0.0.0
+1027.0.0.0.0
Functions:
~ -[SRSensorWriter chooseAuthStore] : 540 -> 536
~ -[SRSensorsCache descriptionForSensor:] : 1036 -> 1032
~ ___44-[SRAuthorizationClient initWithConnection:]_block_invoke : 536 -> 528
~ ___76-[SRAuthorizationClient updateInitialAuthorizationStateIfNeededForBundleId:]_block_invoke : 1252 -> 1240
~ -[SRAuthorizationClient updatePrerequisites] : 536 -> 528
~ -[SRAuthorizationClient authorizedServicesDidChange:deniedServices:prerequisites:lastModifiedTimes:bundleIdentifier:] : 920 -> 916
~ -[SRAuthorizationStore initWithSensors:withAuthorizationTimes:] : 936 -> 932
~ +[SRAuthorizationStore allSensorsStore] : 332 -> 328
~ -[SRAuthorizationStore listenForAuthorizationUpdates:] : 1164 -> 1156
~ -[SRAuthorizationStore updateAuthorizations] : 4264 -> 4236
~ -[SRAuthorizationStore updateToNewAuthorizations:fromOldAuthorizations:delegates:] : 1300 -> 1284
~ -[SRAuthorizationStore sensorHasReaderAuthorization:] : 268 -> 264
~ -[SRAuthorizationStore updateOverrideOnAuthorizationChangeForService:withPendingValue:forBundleId:] : 652 -> 648
~ -[SRAuthorizationStore resetAllAuthorizationsForBundleId:] : 432 -> 428
~ -[SRAuthorizationStore resetAllAuthorizations] : 492 -> 488
~ ___46-[SRAuthorizationStore resetAllAuthorizations]_block_invoke : 472 -> 468
~ -[SRAuthorizationStore readerAuthorizationBundleIdValues] : 336 -> 332
~ +[SRSensorDescription sensorDescriptionsForAuthorizationService:] : 316 -> 312
~ _writeMetadataBytesForFrameStore : 740 -> 736
```
