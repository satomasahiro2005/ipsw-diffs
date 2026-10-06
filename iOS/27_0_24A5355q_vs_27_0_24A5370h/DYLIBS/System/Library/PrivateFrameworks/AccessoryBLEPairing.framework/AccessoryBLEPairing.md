## AccessoryBLEPairing

> `/System/Library/PrivateFrameworks/AccessoryBLEPairing.framework/AccessoryBLEPairing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6cd0` | `0x7000` | **`+0x330`** |
| `__TEXT.__oslogstring` | `0x17c2` | `0x1915` | **`+0x153`** |
| `__TEXT.__cstring` | `0x713` | `0x767` | **`+0x54`** |
| `__TEXT.__objc_methlist` | `0x534` | `0x564` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x368` | `0x378` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x770` | `0x778` | **`+0x8`** |
| `__TEXT.__const` | `0xe8` | `0xf0` | **`+0x8`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1

-  Functions: 115
-  Symbols:   294
-  CStrings:  144
+  Functions: 117
+  Symbols:   296
+  CStrings:  149
Symbols:
+ -[ACCBLEPairingProvider updateResolvedAccessoryBTAddress:blePairingUUID:btAddress:]
+ -[ACCBLEPairingProviderInternal updateResolvedAccessoryBTAddress:blePairingUUID:btAddress:]
Functions:
~ ___51-[ACCBLEPairingProviderInternal initSharedInstance]_block_invoke.69 : 1200 -> 1196
~ -[ACCBLEPairingProviderInternal registerDelegate:provider:forUUID:] : 1708 -> 1704
~ -[ACCBLEPairingProviderInternal accessoryBLEPairingAttached:blePairingUUID:accInfoDict:supportedPairTypes:] : 1208 -> 1204
~ -[ACCBLEPairingProviderInternal accessoryBLEPairingDetached:blePairingUUID:] : 1072 -> 1068
~ -[ACCBLEPairingProviderInternal accessoryBLEPairingNoAccessories] : 664 -> 660
~ -[ACCBLEPairingProviderInternal accessoryBLEPairingDetachAll] : 1064 -> 1060
~ -[ACCBLEPairingProviderInternal accessoryBLEPairingStateUpdate:blePairingUUID:validMask:btRadioOn:pairingState:pairingModeOn:] : 1240 -> 1236
~ -[ACCBLEPairingProviderInternal accessoryBLEPairingInfoUpdate:blePairingUUID:pairType:pairInfoList:] : 1172 -> 1168
~ -[ACCBLEPairingProviderInternal accessoryBLEPairingDataUpdate:blePairingUUID:pairType:pairData:] : 1172 -> 1168
~ -[ACCBLEPairingProviderInternal accessoryBLEPairingFinished:blePairingUUID:] : 1404 -> 1400
+ -[ACCBLEPairingProviderInternal updateResolvedAccessoryBTAddress:blePairingUUID:btAddress:]
+ -[ACCBLEPairingProvider updateResolvedAccessoryBTAddress:blePairingUUID:btAddress:]
~ ___init_logging_modules_block_invoke : 608 -> 588
~ ___init_logging_signpost_modules_block_invoke : 608 -> 588
~ _accessoryServer_registerAvailabilityChangedHandlerForServiceEntry : 444 -> 436
~ __SetupAvailabilityChangedHandlerForServiceEntry : 864 -> 852
~ _accessoryServer_unregisterAvailabilityChangedHandlerForServiceEntry : 280 -> 268
~ _accessoryServer_isServerAvailableForServiceEntry : 368 -> 348
CStrings:
+ "%s: delegateUUID %@, updateResolvedAccessoryBTAddress: %@, blePairingUUID %@, resolvedAccessoryBTAddress length=%lu"
+ "-[ACCBLEPairingProvider updateResolvedAccessoryBTAddress:blePairingUUID:btAddress:]"
+ "updateResolvedAccessoryBTAddress: %@, _remoteObject nil, _providerUID=%@"
+ "updateResolvedAccessoryBTAddress: %@, blePairingUUID %@, resolvedAccessoryBTAddress=%@"
+ "updateResolvedAccessoryBTAddress: invalid btAddress length %lu"
```
