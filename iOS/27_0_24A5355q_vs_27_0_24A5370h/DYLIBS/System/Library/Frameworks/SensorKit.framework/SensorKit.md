## SensorKit

> `/System/Library/Frameworks/SensorKit.framework/SensorKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44db8` | `0x44cc8` | **`-0xf0`** |

### Other Changes

```diff

-1025.0.0.0.0
+1027.0.0.0.0
Functions:
~ -[SRAuthorizationStore updateAuthorizations] : 4264 -> 4236
~ +[SRSensorReader(DataExport) createExportDataWithCompletionHandler:] : 512 -> 504
~ -[SRSensorsCache descriptionForSensor:] : 1036 -> 1032
~ -[SRWristTemperatureEnumerator allObjects] : 428 -> 424
~ -[SRPPGSampleArray initWithBinarySampleRepresentation:metadata:timestamp:] : 400 -> 396
~ -[SRAuthorizationStore initWithSensors:withAuthorizationTimes:] : 936 -> 932
~ +[SRAuthorizationStore allSensorsStore] : 332 -> 328
~ -[SRAuthorizationStore listenForAuthorizationUpdates:] : 1164 -> 1156
~ -[SRAuthorizationStore updateToNewAuthorizations:fromOldAuthorizations:delegates:] : 1300 -> 1284
~ -[SRAuthorizationStore sensorHasReaderAuthorization:] : 268 -> 264
~ -[SRAuthorizationStore updateOverrideOnAuthorizationChangeForService:withPendingValue:forBundleId:] : 652 -> 648
~ -[SRAuthorizationStore resetAllAuthorizationsForBundleId:] : 432 -> 428
~ -[SRAuthorizationStore resetAllAuthorizations] : 492 -> 488
~ ___46-[SRAuthorizationStore resetAllAuthorizations]_block_invoke : 472 -> 468
~ -[SRAuthorizationStore readerAuthorizationBundleIdValues] : 336 -> 332
~ ___50-[SRDeviceUsageReport sr_dictionaryRepresentation]_block_invoke : 472 -> 468
~ ___50-[SRDeviceUsageReport sr_dictionaryRepresentation]_block_invoke_2 : 288 -> 284
~ -[SRApplicationUsage sr_dictionaryRepresentation] : 864 -> 856
~ +[SRSensorDescription sensorDescriptionsForAuthorizationService:] : 316 -> 312
~ -[SRSensorWriter chooseAuthStore] : 540 -> 536
~ -[NSBundle(SensorKit) _sr_validateRequiredFieldsForSensors:error:] : 688 -> 684
~ -[SRKeyboardProbabilityMetric distributionSampleValues] : 412 -> 408
~ -[SRKeyboardMetrics longWordUpErrorDistance] : 300 -> 296
~ -[SRKeyboardMetrics longWordDownErrorDistance] : 300 -> 296
~ -[SRKeyboardMetrics longWordTouchDownUp] : 300 -> 296
~ -[SRKeyboardMetrics longWordTouchDownDown] : 300 -> 296
~ -[SRKeyboardMetrics longWordTouchUpDown] : 300 -> 296
~ -[SRKeyboardMetrics deleteToDeletes] : 300 -> 296
~ -[SRKeyboardMetrics dictionaryRepresentation] : 5164 -> 5140
~ -[SRSpeechMetrics initWithSessionIdentifier:sessionFlags:timestamp:audioLevel:speechRecognition:soundClassification:speechExpression:] : 1212 -> 1208
~ ___44-[SRAuthorizationClient initWithConnection:]_block_invoke : 536 -> 528
~ ___76-[SRAuthorizationClient updateInitialAuthorizationStateIfNeededForBundleId:]_block_invoke : 1252 -> 1240
~ -[SRAuthorizationClient updatePrerequisites] : 536 -> 528
~ -[SRAuthorizationClient authorizedServicesDidChange:deniedServices:prerequisites:lastModifiedTimes:bundleIdentifier:] : 920 -> 916
~ +[NSArray(HAOpticalSamples) sr_arrayWithHAOpticalSamples:] : 308 -> 304
~ +[NSArray(HAAccelSamples) sr_arrayWithHAAccelSamples:] : 308 -> 304
~ ___31-[SRSensorReader fetchDevices:]_block_invoke : 424 -> 420
~ -[SRElectrocardiogramSample initWithHAECGSample:] : 580 -> 576
~ sub_232484814 -> sub_233607728 : 736 -> 748
~ sub_232485620 -> sub_233608540 : 280 -> 276
~ -[SRDatastore fetchSamplesFrom:to:callback:] : 504 -> 500
~ -[SRDatastore removeSamplesFrom:to:callback:] : 340 -> 336
~ _findClosestMetadataObjectInFrameStore : 444 -> 440
```
