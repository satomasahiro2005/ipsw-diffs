## ACCHWComponentAuthService

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/XPCServices/ACCHWComponentAuthService.xpc/ACCHWComponentAuthService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39530` | `0x39ae8` | **`+0x5b8`** |
| `__TEXT.__objc_methname` | `0x1676` | `0x1783` | **`+0x10d`** |
| `__DATA_CONST.__cfstring` | `0x1680` | `0x1780` | **`+0x100`** |
| `__TEXT.__cstring` | `0x1f59` | `0x2050` | **`+0xf7`** |
| `__DATA_CONST.__const` | `0x6978` | `0x6a58` | **`+0xe0`** |
| `__DATA.__objc_const` | `0xa70` | `0xb10` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x6675` | `0x66e6` | **`+0x71`** |
| `__TEXT.__objc_methlist` | `0x624` | `0x66c` | **`+0x48`** |
| `__DATA.__objc_selrefs` | `0x5a8` | `0x5d0` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0xe60` | `0xe80` | **`+0x20`** |
| `__DATA.__bss` | `0x120` | `0x130` | **`+0x10`** |
| `__TEXT.__const` | `0x1e1f3` | `0x1e203` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x818` | `0x828` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x274` | `0x270` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-  Functions: 1216
-  Symbols:   2780
-  CStrings:  1240
+  Functions: 1225
+  Symbols:   2799
+  CStrings:  1257
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
+ ___107-[ACCHWComponentAuthService authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:]_block_invoke
+ ___107-[ACCHWComponentAuthService authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:]_block_invoke_2
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _kCFACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ _objc_msgSend$createVillanovaNonce:IDSN:challenge:
+ authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:.RCAMQueue
+ authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:.onceToken
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
+ "authenticateRCAMWithChallenge:completionHandler:updateRegistry:"
+ "authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:"
+ "com.apple.ACCHWComponentAuthService.rcam"
+ "createVillanovaNonce:IDSN:challenge:"
+ "prpc"
+ "signRCAMChallenge:completionHandler:"
+ "signRCAMChallenge:completionHandler:componentIndex:"
```
