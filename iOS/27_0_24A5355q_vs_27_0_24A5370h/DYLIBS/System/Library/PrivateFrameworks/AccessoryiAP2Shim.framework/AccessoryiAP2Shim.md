## AccessoryiAP2Shim

> `/System/Library/PrivateFrameworks/AccessoryiAP2Shim.framework/AccessoryiAP2Shim`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc0a8` | `0xc050` | **`-0x58`** |
| `__AUTH_CONST.__cfstring` | `0x15e0` | `0x1600` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1039` | `0x1051` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x928` | `0x938` | **`+0x10`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1

-  Symbols:   825
-  CStrings:  329
+  Symbols:   826
+  CStrings:  330
Symbols:
+ _ACCUserDefaultsKey_PretendWirelessCTAMatch
+ _kCFACCUserDefaultsKey_PretendWirelessCTAMatch
- _objc_retain_x26
Functions:
~ -[ACCiAP2ShimServer _iterateAccessories:] : 580 -> 576
~ -[ACCiAP2ShimServer addClientWithCapabilities:auditToken:currentClientID:xpcConnection:eaProtocols:notifyOfAlreadyConnectedAccessories:andBundleId:] : 1836 -> 1832
~ ___init_logging_signpost_modules_block_invoke : 608 -> 588
~ _acc_policies_endpointRequiresChargingCurrentLimit : 1948 -> 1960
~ -[ACCiAP2ShimServer _iterateDelegates:] : 552 -> 548
~ -[ACCiAP2ShimServer _findAccessoryForConnectionID:] : 304 -> 300
~ -[ACCiAP2ShimServer _takeClientAssertionsForAccessoryDisconnection] : 296 -> 292
~ -[ACCiAP2ShimServer findClientWithXPCConnection:] : 560 -> 556
~ -[ACCiAP2ShimServer removeClientWithID:] : 816 -> 812
~ -[ACCiAP2ShimServer removeClientForXPCConnection:] : 892 -> 888
~ -[ACCiAP2ShimServer removeAllClients] : 440 -> 436
~ -[ACCiAP2ShimServer _takeClientAssertionsForAccessoryConnection] : 560 -> 548
~ ___63-[ACCiAP2ShimServer notifyEAClientsOfAccessoryEvent:accessory:]_block_invoke : 316 -> 312
~ ___75-[ACCiAP2ShimServer sendToInterestedClientsACCBLENotification:withPayload:]_block_invoke : 344 -> 340
~ +[ACCiAP2ShimServer markClientAsInterestedInBleNotifications:] : 1240 -> 1236
~ ___init_logging_modules_block_invoke : 608 -> 588
CStrings:
+ "PretendWirelessCTAMatch"
```
