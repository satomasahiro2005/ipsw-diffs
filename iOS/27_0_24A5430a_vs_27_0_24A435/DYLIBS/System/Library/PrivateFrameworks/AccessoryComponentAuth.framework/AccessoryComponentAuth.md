## AccessoryComponentAuth

> `/System/Library/PrivateFrameworks/AccessoryComponentAuth.framework/AccessoryComponentAuth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1241c` | `0x129d4` | **`+0x5b8`** |
| `__AUTH_CONST.__cfstring` | `0x1440` | `0x1540` | **`+0x100`** |
| `__TEXT.__cstring` | `0x14d2` | `0x15c9` | **`+0xf7`** |
| `__DATA_CONST.__const` | `0x1650` | `0x1710` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x11d7` | `0x1248` | **`+0x71`** |
| `__TEXT.__objc_methlist` | `0x4ec` | `0x534` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x470` | `0x498` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xc48` | `0xc68` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x6d0` | `0x6f0` | **`+0x20`** |
| `__DATA.__bss` | `0x108` | `0x118` | **`+0x10`** |
| `__TEXT.__const` | `0xd700` | `0xd710` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x430` | `0x440` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x274` | `0x270` | **`-0x4`** |

### Other Changes

```diff

-  Functions: 479
-  Symbols:   1482
-  CStrings:  339
+  Functions: 488
+  Symbols:   1502
+  CStrings:  351
Symbols:
+ -[ACCHWComponentAuthService authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:]
+ -[ACCHWComponentAuthService signRCAMChallenge:completionHandler:componentIndex:]
+ GCC_except_table70
+ _ACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _ACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _ACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _ACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _ACCUserDefaultsKey_PlatformIDOverride
+ _ACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ _OUTLINED_FUNCTION_10
+ _OUTLINED_FUNCTION_11
+ ___107-[ACCHWComponentAuthService authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:]_block_invoke
+ ___107-[ACCHWComponentAuthService authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:]_block_invoke_2
+ _authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:.RCAMQueue
+ _authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:.onceToken
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _kCFACCUserDefaultsKey_TestCreateBLEPairingOnInductive
- GCC_except_table67
CStrings:
+ "(moduleType=%d) %s: cpGetDeviceIDSN failed: ret=%x len=%zu"
+ "BLEPairingConfigRequestDelayMs"
+ "BLEPairingDisableOOBPPlusFlow"
+ "BLEPairingDontEarlyInfoAsDeviceUID"
+ "BLEPairingIgnoreZeroEarlyInfo"
+ "ComponentBusyError"
+ "Flags indicate rcam...do not call cpCopyCertificate()"
+ "PlatformIDOverride"
+ "RCAM"
+ "TestCreateBLEPairingOnInductive"
+ "com.apple.ACCHWComponentAuthService.rcam"
+ "prpc"
```
