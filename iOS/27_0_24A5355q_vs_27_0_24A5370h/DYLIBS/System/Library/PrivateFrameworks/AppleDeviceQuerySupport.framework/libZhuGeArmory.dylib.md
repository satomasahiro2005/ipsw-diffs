## libZhuGeArmory.dylib

> `/System/Library/PrivateFrameworks/AppleDeviceQuerySupport.framework/libZhuGeArmory.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23fe8` | `0x23f90` | **`-0x58`** |
| `__TEXT.__unwind_info` | `0x3e8` | `0x3f0` | **`+0x8`** |

### Other Changes

```diff

-458.0.0.0.0
+459.0.2.0.0
Functions:
~ +[ZhuGeMobileEquipmentInfoArmory getMobileEquipInfoIn:ofSlot:] : 308 -> 304
~ -[ZhuGeMobileEquipmentInfoArmory query:ofSlot:isCachable:withError:] : 604 -> 600
~ +[NSArray(ZhuGe) graphicInfoArrayFromArray:] : 660 -> 656
~ +[NSArray(ZhuGe) arrayFromShellCommandString:] : 612 -> 596
~ -[ZhuGeArmory convertReturnValue:ByItselfAndError:AndRevalues:] : 1884 -> 1880
~ -[ZhuGeArmory checkDependency:withError:] : 1780 -> 1808
~ -[ZhuGeArmory runForKey:andOptions:andPreferences:withError:] : 3376 -> 3372
~ -[ZhuGeArmoryHelperArmory unionizeRawConfig:withError:] : 1208 -> 1204
~ -[ZhuGeArmoryHelperArmory sortAliasFromUnionizedConfig:withError:] : 1232 -> 1228
~ -[ZhuGeArmoryHelperArmory pickFlexibleFromUnionizedConfig:withError:] : 708 -> 704
~ -[ZhuGeArmoryHelperArmory propertiesOfKey:withError:] : 2420 -> 2412
~ -[ZhuGeArmoryHelperArmory getPropertiesOfKey:withError:] : 2436 -> 2416
~ +[ZhuGeKeysActionArmory queryIOPropertyFromPath:andCriteria:withError:] : 3288 -> 3284
~ +[ZhuGeKeysActionArmory queryIOProperty:fromCriteria:withError:] : 8052 -> 8064
~ +[ZhuGeKeysActionArmory queryIOCameraByProperty:withError:] : 688 -> 676
~ _listSecureElementsCallback : 628 -> 568
~ +[NSString(ZhuGe) isDataConvertibleToVisibleString:] : 164 -> 160
~ +[NSString(ZhuGe) hexStringFromData:] : 180 -> 188
~ +[NSString(ZhuGe) macAddressStringFromData:] : 208 -> 224
~ +[NSString(ZhuGe) macAddressStringFromSysconfigDataSixByte:] : 232 -> 248
~ -[NSString(ZhuGe) stringByLeftTrimmingCharacter:] : 148 -> 144
~ -[NSString(ZhuGe) stringByRightTrimmingCharacter:] : 140 -> 136
~ _getMesaFDRIdentifier : 844 -> 840
```
