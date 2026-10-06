## MFAAuthentication

> `/System/Library/PrivateFrameworks/MFAAuthentication.framework/MFAAuthentication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x429ac` | `0x42b50` | **`+0x1a4`** |
| `__AUTH_CONST.__cfstring` | `0x1ba0` | `0x1c80` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x1af8` | `0x1bba` | **`+0xc2`** |
| `__DATA_CONST.__const` | `0x56f8` | `0x57a0` | **`+0xa8`** |
| `__TEXT.__oslogstring` | `0x4e24` | `0x4e68` | **`+0x44`** |
| `__DATA_CONST.__objc_selrefs` | `0x4d0` | `0x4e8` | **`+0x18`** |
| `__TEXT.__const` | `0x6de03` | `0x6de13` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x494` | `0x4a4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7d8` | `0x7e0` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 853
-  Symbols:   1871
-  CStrings:  724
+  Functions: 855
+  Symbols:   1885
+  CStrings:  733
Symbols:
+ -[MFAACertificateManager createVillanovaNonce:IDSN:challenge:]
+ GCC_except_table35
+ GCC_except_table40
+ _ACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _ACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _ACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _ACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _ACCUserDefaultsKey_PlatformIDOverride
+ _ACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ _createVillanovaNonce:IDSN:challenge:.kAuthPrefix
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _kCFACCUserDefaultsKey_TestCreateBLEPairingOnInductive
- GCC_except_table34
- GCC_except_table39
Functions:
~ -[MFAACertificateManager verifyModuleCertificate:forModule:forAuthFlags:] : 1096 -> 1136
+ -[MFAACertificateManager createVillanovaNonce:IDSN:challenge:]
~ _OUTLINED_FUNCTION_13 : 20 -> 12
~ _OUTLINED_FUNCTION_14 : 12 -> 20
+ _OUTLINED_FUNCTION_1
~ _cpGetInternalComponents : 1048 -> 1032
CStrings:
+ "BLEPairingConfigRequestDelayMs"
+ "BLEPairingDisableOOBPPlusFlow"
+ "BLEPairingDontEarlyInfoAsDeviceUID"
+ "BLEPairingIgnoreZeroEarlyInfo"
+ "PlatformIDOverride"
+ "RCAM"
+ "TestCreateBLEPairingOnInductive"
+ "createVillanovaNonce: nonce=%@ idsn=%@ challenge=%@ -> msg=%@ -> %@"
+ "iPhone RCAM"
```
