## ButtonResolver

> `/System/Library/PrivateFrameworks/ButtonResolver.framework/ButtonResolver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9854` | `0x97b8` | **`-0x9c`** |

### Other Changes

```text
Functions:
~ -[BRButtonResolverController propertyList] : 372 -> 368
~ -[BRButtonResolverController isReady] : 240 -> 236
~ -[BRButtonResolverController maxAssetSlots] : 280 -> 276
~ -[BRButtonResolverController unusedAssetSlots] : 280 -> 276
~ -[BRButtonResolverController setGlobalConfigs:error:] : 608 -> 604
~ -[BRButtonResolverController setConfigs:withAssets:forStates:error:] : 708 -> 704
~ -[BRButtonResolverController enableStates:error:] : 568 -> 564
~ -[BRButtonResolverController disableStates:clearAsset:error:] : 584 -> 580
~ -[BRButtonResolverController playState:forSpeed:error:] : 584 -> 580
~ -[BRButtonResolverController scheduleReadyNotificationOnDispatchQueue:withBlock:] : 520 -> 516
~ -[BRStateData propertyList] : 688 -> 680
~ -[BRInterfaceAOP propertyList] : 796 -> 788
~ -[BRInterfaceAOP enableStates:error:] : 812 -> 808
~ -[BRInterfaceAOP disableStates:clearAsset:error:] : 1248 -> 1240
~ -[BRInterfaceAOP dataForSlot:fromArray:] : 292 -> 288
~ -[BRInterfaceAOP mergeStateChanges:into:] : 268 -> 264
~ -[BRInterfaceLegacy serviceRemovedHandler:] : 448 -> 444
~ ___49-[BRInterfaceLegacy _servicesSetProperty:forKey:]_block_invoke : 308 -> 304
~ -[BRInterfaceLegacy _setDefaultServicePropertiesOnService:] : 296 -> 292
~ -[BRInterfaceLegacy enableStates:error:] : 512 -> 508
~ -[BRInterfaceLegacy disableStates:clearAsset:error:] : 512 -> 508
~ -[BRInterfaceKeyboard enableStates:error:] : 456 -> 452
~ -[BRInterfaceKeyboard disableStates:clearAsset:error:] : 456 -> 452
~ ___51-[BRInterfaceKeyboard _servicesSetProperty:forKey:]_block_invoke : 336 -> 332
~ -[BRInterfaceKeyboard _setCachedPropertiesOnService:] : 476 -> 472
~ _serviceRemovedCallback : 436 -> 432
~ -[BRInterfaceAOP setConfigs:withAssets:forStates:error:] : 3128 -> 3100
~ -[BRInterfaceAOP _setStateAOPConfigsFromStateData:andSlotData:] : 1016 -> 1012
~ ___34-[BRInterfaceLegacy _findServices]_block_invoke : 304 -> 300
~ ___36-[BRInterfaceKeyboard _findServices]_block_invoke : 304 -> 300
```
