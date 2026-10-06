## Communications-iOS

> `/System/Library/CoreAccessories/PlugIns/Features/Communications-iOS.feature/Communications-iOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0xf00` | `0xf20` | **`+0x20`** |
| `__TEXT.__text` | `0xb108` | `0xb0ec` | **`-0x1c`** |
| `__TEXT.__cstring` | `0xae9` | `0xb01` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x800` | `0x810` | **`+0x10`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1

-  Symbols:   721
-  CStrings:  201
+  Symbols:   723
+  CStrings:  202
Symbols:
+ _ACCUserDefaultsKey_PretendWirelessCTAMatch
+ _kCFACCUserDefaultsKey_PretendWirelessCTAMatch
Functions:
~ _CFStringCreateFromCFData : 196 -> 204
~ ___init_logging_modules_block_invoke : 608 -> 588
~ _convertNSDataToNSString : 260 -> 256
~ _convertNSStringToNSData : 444 -> 440
~ _classImplementsMethodsInProtocol : 304 -> 300
~ _base64EncodeArray : 328 -> 324
~ _base64DecodeArray : 340 -> 336
~ +[NSDictionary(Utilities) dictionaryOfChangesBetween:and:] : 432 -> 428
~ _ascii_to_hex : 156 -> 160
~ _printBytes : 136 -> 156
~ -[ACCCommunicationsFeaturePlugin currentCallStates] : 360 -> 356
~ ___50-[ACCCommunicationsFeaturePlugin currentCallCount]_block_invoke : 296 -> 292
~ ___59-[ACCCommunicationsFeaturePlugin sendDTMF:forCallWithUUID:]_block_invoke.93 : 444 -> 440
~ -[ACCCommunicationsFeaturePlugin currentRecentsListWithCoalescing:limit:] : 1632 -> 1624
~ -[ACCCommunicationsFeaturePlugin currentFavoritesListWithLimit:] : 1420 -> 1440
~ _createHexString : 408 -> 400
~ -[ACCCommunicationsFeaturePlugin callStateDidChangeNotification:] : 1960 -> 1956
~ ____callStateDictionaryForCall_block_invoke : 1136 -> 1132
CStrings:
+ "PretendWirelessCTAMatch"
```
