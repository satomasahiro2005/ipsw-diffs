## SPOwner

> `/System/Library/PrivateFrameworks/SPOwner.framework/SPOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77470` | `0x77954` | **`+0x4e4`** |
| `__AUTH_CONST.__objc_const` | `0x14178` | `0x14370` | **`+0x1f8`** |
| `__TEXT.__objc_methlist` | `0xbb2c` | `0xbc0c` | **`+0xe0`** |
| `__AUTH_CONST.__cfstring` | `0x5e80` | `0x5f00` | **`+0x80`** |
| `__TEXT.__cstring` | `0x6a49` | `0x6ac9` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d98` | `0x3df8` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x48` | `0x98` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x2168` | `0x2190` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2738` | `0x2760` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0xefc` | `0xf14` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x5f8` | `0x600` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x448` | `0x450` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x378` | `0x380` | **`+0x8`** |

### Other Changes

```diff

-449.30.6.14.15
+449.30.6.14.26

-  Functions: 4392
-  Symbols:   7320
-  CStrings:  1572
+  Functions: 4411
+  Symbols:   7356
+  CStrings:  1577
Symbols:
+ +[SPCommand playSoundWithBeaconUUID:withContext:options:]
+ +[SPPlaySoundOptions supportsSecureCoding]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface collectionDifferenceSerialQueue]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface setCollectionDifferenceSerialQueue:]
+ -[SPCommand initWithBeaconUUID:type:expiration:duration:playSoundContext:playSoundOptions:handle:lostModeEmail:lostModeMessage:lostModePhoneNumber:obfuscatedIdentifier:identifier:enableLostMode:lockModePasscode:emailUpdates:]
+ -[SPCommand playSoundOptions]
+ -[SPCommand setPlaySoundOptions:]
+ -[SPInternalSimpleBeacon isPairingIncomplete]
+ -[SPInternalSimpleBeacon setIsPairingIncomplete:]
+ -[SPPlaySoundOptions classicTimeout]
+ -[SPPlaySoundOptions copyWithZone:]
+ -[SPPlaySoundOptions encodeWithCoder:]
+ -[SPPlaySoundOptions initWithCoder:]
+ -[SPPlaySoundOptions setClassicTimeout:]
+ -[SPPlaySoundOptions setUseClassicIndividual:]
+ -[SPPlaySoundOptions useClassicIndividual]
+ -[SPUnifiedBeacon isPairingIncomplete]
+ -[SPUnifiedBeacon setIsPairingIncomplete:]
+ GCC_except_table47
+ _OBJC_CLASS_$_SPPlaySoundOptions
+ _OBJC_IVAR_$_SPBeaconManagerSimpleBeaconUpdateInterface._collectionDifferenceSerialQueue
+ _OBJC_IVAR_$_SPCommand._playSoundOptions
+ _OBJC_IVAR_$_SPInternalSimpleBeacon._isPairingIncomplete
+ _OBJC_IVAR_$_SPPlaySoundOptions._classicTimeout
+ _OBJC_IVAR_$_SPPlaySoundOptions._useClassicIndividual
+ _OBJC_IVAR_$_SPUnifiedBeacon._isPairingIncomplete
+ _OBJC_METACLASS_$_SPPlaySoundOptions
+ __OBJC_$_CLASS_METHODS_SPPlaySoundOptions
+ __OBJC_$_CLASS_PROP_LIST_SPPlaySoundOptions
+ __OBJC_$_INSTANCE_METHODS_SPPlaySoundOptions
+ __OBJC_$_INSTANCE_VARIABLES_SPPlaySoundOptions
+ __OBJC_$_PROP_LIST_SPPlaySoundOptions
+ __OBJC_CLASS_PROTOCOLS_$_SPPlaySoundOptions
+ __OBJC_CLASS_RO_$_SPPlaySoundOptions
+ __OBJC_METACLASS_RO_$_SPPlaySoundOptions
+ ___77-[SPBeaconManagerSimpleBeaconUpdateInterface setSimpleBeaconDifferenceBlock:]_block_invoke
+ ___77-[SPBeaconManagerSimpleBeaconUpdateInterface setSimpleBeaconDifferenceBlock:]_block_invoke_2
+ ___block_descriptor_48_e8_32bs40w_e51_v24?0"NSOrderedCollectionDifference"8"NSError"16lw40l8s32l8
- -[SPCommand initWithBeaconUUID:type:expiration:duration:playSoundContext:handle:lostModeEmail:lostModeMessage:lostModePhoneNumber:obfuscatedIdentifier:identifier:enableLostMode:lockModePasscode:emailUpdates:]
- GCC_except_table45
CStrings:
+ "classicTimeout"
+ "com.apple.icloud.searchpartyd.simpleBeaconUpdate.collection"
+ "isPairingIncomplete"
+ "playSoundOptions"
+ "useClassicIndividual"
```
