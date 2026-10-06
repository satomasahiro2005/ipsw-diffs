## TVRemoteCore

> `/System/Library/PrivateFrameworks/TVRemoteCore.framework/TVRemoteCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__lazy_helpers` | `—` | `0x580` | **`+0x580`** |
| `__TEXT.__text` | `0x483e4` | `0x487b4` | **`+0x3d0`** |
| `__AUTH_CONST.__lazy_load_got` | `—` | `0x80` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x4f0` | `0x470` | **`-0x80`** |
| `__TEXT.__oslogstring` | `0x6b0e` | `0x6b4c` | **`+0x3e`** |
| `__TEXT.__unwind_info` | `0x1230` | `0x1218` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x64d0` | `0x64e0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3090` | `0x3098` | **`+0x8`** |
| `__DATA.__data` | `0xa30` | `0xa34` | **`+0x4`** |

### Other Changes

```diff

-627.0.14.0.0
+627.0.19.0.0

-  - /System/Library/Frameworks/HomeKit.framework/HomeKit

-  Functions: 2137
-  Symbols:   3669
-  CStrings:  1300
+  Functions: 2138
+  Symbols:   3705
+  CStrings:  1301
Symbols:
+ -[TVRCMatchPointDeviceQuery _cachedHomeInManager:]
+ _HMAccessoryCategoryTypeTelevisionSetTopBox$lazyGOT
+ _HMAccessoryCategoryTypeTelevisionSetTopBox$lazyGOT$loadHelper_x8
+ _HMAccessoryCategoryTypeTelevisionStreamingStick$lazyGOT
+ _HMAccessoryCategoryTypeTelevisionStreamingStick$lazyGOT$loadHelper_x8
+ _HMCharacteristicTypeActive$lazyGOT
+ _HMCharacteristicTypeActive$lazyGOT$loadHelper_x8
+ _HMCharacteristicTypeActiveIdentifier$lazyGOT
+ _HMCharacteristicTypeActiveIdentifier$lazyGOT$loadHelper_x8
+ _HMCharacteristicTypeMute$lazyGOT
+ _HMCharacteristicTypeMute$lazyGOT$loadHelper_x8
+ _HMCharacteristicTypeRemoteKey$lazyGOT
+ _HMCharacteristicTypeRemoteKey$lazyGOT$loadHelper_x8
+ _HMCharacteristicTypeVolume$lazyGOT
+ _HMCharacteristicTypeVolume$lazyGOT$loadHelper_x8
+ _HMCharacteristicTypeVolumeSelector$lazyGOT
+ _HMCharacteristicTypeVolumeSelector$lazyGOT$loadHelper_x8
+ _HMErrorDomain$lazyGOT
+ _HMErrorDomain$lazyGOT$loadHelper_x8
+ _HMServiceTypeSpeaker$lazyGOT
+ _HMServiceTypeSpeaker$lazyGOT$loadHelper_x8
+ _HMServiceTypeTelevision$lazyGOT
+ _HMServiceTypeTelevision$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_HMCharacteristicBatchRequest$lazyGOT
+ _OBJC_CLASS_$_HMCharacteristicBatchRequest$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_HMCharacteristicReadRequest$lazyGOT
+ _OBJC_CLASS_$_HMCharacteristicReadRequest$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_HMCharacteristicWriteRequest$lazyGOT
+ _OBJC_CLASS_$_HMCharacteristicWriteRequest$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_HMCharacteristicWriteRequest$lazyGOT$loadHelper_x8$for$-[TVRCHMServiceWrapper _writeRequestForCharacteristic:withValue:]+0
+ _OBJC_CLASS_$_HMHomeManager$lazyGOT
+ _OBJC_CLASS_$_HMHomeManager$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_HMMutableHomeManagerConfiguration$lazyGOT
+ _OBJC_CLASS_$_HMMutableHomeManagerConfiguration$lazyGOT$loadHelper_x8
+ __dyld_lazy_load
+ _lazyLoadFlag$HomeKit
Functions:
~ -[TVRCMatchPointDeviceQuery stop] : 304 -> 272
~ -[TVRCMatchPointDeviceQuery homeManagerDidUpdateHomes:] : 292 -> 312
~ -[TVRCMatchPointDeviceQuery homeManagerDidUpdateCurrentHome:] : 428 -> 452
+ -[TVRCMatchPointDeviceQuery _cachedHomeInManager:]
~ ___75-[TVRCRPCompanionLinkClientWrapper sendEvent:options:shouldRetry:response:]_block_invoke : 556 -> 608
~ ___82-[TVRCRPCompanionLinkClientWrapper fetchUpNextInfoWithPaginationToken:completion:]_block_invoke : 276 -> 336
~ ___80-[TVRCRPCompanionLinkClientWrapper markAsWatchedWithMediaIdentifier:completion:]_block_invoke : 200 -> 260
~ ___74-[TVRCRPCompanionLinkClientWrapper addItemWithMediaIdentifier:completion:]_block_invoke : 200 -> 260
~ ___77-[TVRCRPCompanionLinkClientWrapper removeItemWithMediaIdentifier:completion:]_block_invoke : 200 -> 260
~ ___56-[TVRCRPCompanionLinkClientWrapper playItem:completion:]_block_invoke : 200 -> 260
~ ___76-[TVRCRPCompanionLinkClientWrapper fetchLaunchableAppsWithRange:completion:]_block_invoke : 204 -> 264
~ ___69-[TVRCRPCompanionLinkClientWrapper launchAppWithBundleID:completion:]_block_invoke : 200 -> 260
CStrings:
+ "Received request response with ID %@, responseKeyCount %lu, keys %@, error %@"
+ "currentHome is nil, reusing cached home: %@"
- "Received request response with ID %@, response %@, error %@"
```
