## CoreAccessories

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/CoreAccessories`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26334` | `0x26e4c` | **`+0xb18`** |
| `__AUTH_CONST.__cfstring` | `0x3b00` | `0x3c00` | **`+0x100`** |
| `__TEXT.__cstring` | `0x3ccf` | `0x3dbf` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0x4087` | `0x4146` | **`+0xbf`** |
| `__DATA_CONST.__const` | `0x1fb8` | `0x2038` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x1954` | `0x19bc` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0xf30` | `0xf58` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xa38` | `0xa60` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x2348` | `0x2368` | **`+0x20`** |
| `__DATA.__data` | `0x758` | `0x760` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 821
-  Symbols:   1872
-  CStrings:  866
+  Functions: 832
+  Symbols:   1897
+  CStrings:  879
Symbols:
+ -[ACCHWComponentAuth authenticateRCAMWithChallenge:completionHandler:updateRegistry:]
+ -[ACCHWComponentAuth authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:]
+ -[ACCHWComponentAuth signRCAMChallenge:completionHandler:]
+ -[ACCHWComponentAuth signRCAMChallenge:completionHandler:componentIndex:]
+ -[ACCTransportPlugin endpointForConnectionWithUUID:forProtocol:]
+ _ACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _ACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _ACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _ACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _ACCUserDefaultsKey_PlatformIDOverride
+ _ACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ ___100-[ACCHWComponentAuth authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:]_block_invoke
+ ___100-[ACCHWComponentAuth authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:]_block_invoke_2
+ ___73-[ACCHWComponentAuth signRCAMChallenge:completionHandler:componentIndex:]_block_invoke
+ ___73-[ACCHWComponentAuth signRCAMChallenge:completionHandler:componentIndex:]_block_invoke_2
+ _kACCProperties_Connection_OOBPairingEarlyInfoBDADDR
+ _kACCProperties_Connection_OOBPairingEarlyInfoSessionState
+ _kCFACCProperties_Connection_OOBPairingEarlyInfoBDADDR
+ _kCFACCProperties_Connection_OOBPairingEarlyInfoSessionState
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _kCFACCUserDefaultsKey_TestCreateBLEPairingOnInductive
CStrings:
+ "Authenticating RCAM... (completionHandler: %s)"
+ "BLEPairingConfigRequestDelayMs"
+ "BLEPairingDisableOOBPPlusFlow"
+ "BLEPairingDontEarlyInfoAsDeviceUID"
+ "BLEPairingIgnoreZeroEarlyInfo"
+ "OOBPairingEarlyInfoBDADDR"
+ "OOBPairingEarlyInfoSessionState"
+ "PlatformIDOverride"
+ "RCAM"
+ "RCAM authPassed = %d, fdrValidationStatus %d, authError %d"
+ "Signing RCAM challenge... (completionHandler: %s)"
+ "TestCreateBLEPairingOnInductive"
+ "signed RCAM challenge authError %d"
```
