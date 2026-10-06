## ExternalAccessory

> `/System/Library/Frameworks/ExternalAccessory.framework/ExternalAccessory`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10070` | `0x10018` | **`-0x58`** |

### Other Changes

```text
Functions:
~ -[EAAccessoryManager _initFromSingletonCreationMethod] : 1364 -> 1360
~ -[EAAccessoryManager _checkForConnectedAccessories:backgroundTaskIdentifier:] : 988 -> 976
~ -[EAAccessoryManager _findExtraAccessoriesContainedOnlyIniAP:] : 532 -> 528
~ -[EAAccessoryManager _findExtraAccessoriesContainedOnlyInEA:] : 676 -> 672
~ -[EAAccessory protocolStrings] : 340 -> 336
~ -[EAAccessoryManager stopLocationForConnectedAccessories] : 324 -> 320
~ +[EAPostAlert CopyLocalizedString:] : 528 -> 524
~ ___EAAuthSerialStringGetterCB : 288 -> 284
~ ___convertIAPAccessoryToEAAccessory : 2576 -> 2572
~ -[EAAccessoryManager initialEAAccessoriesAttachedAfterClientConnection:] : 452 -> 448
~ ___findAccessoryByUUID : 384 -> 380
~ ___findAccessory : 388 -> 384
~ -[EAAccessoryManager _cleanUpForTaskSuspendWithTaskIdentifier:] : 684 -> 676
~ -[EAAccessoryManager _externalAccessoryDisconnected:] : 884 -> 876
~ -[EAAccessoryManager appDeclaresProtocol:] : 376 -> 372
~ -[EAAccessoryManager devicePicker:didSelectAddress:errorCode:] : 1072 -> 1064
~ -[EAAccessoryManager startLocationForConnectedAccessories] : 360 -> 356
~ -[EAAccessory _openCompleteForSession:] : 276 -> 272
~ -[EAAccessory _endSession:] : 292 -> 288
~ -[EAAccessory allPublicProtocolStrings] : 556 -> 552
~ -[EAAccessory dictionaryWithLowercaseKeys:] : 312 -> 308
~ sub_22ffa5dc4 -> sub_22ff9dd5c : 380 -> 376
~ sub_22ffa5f40 -> sub_22ff9ded4 : 236 -> 256
```
