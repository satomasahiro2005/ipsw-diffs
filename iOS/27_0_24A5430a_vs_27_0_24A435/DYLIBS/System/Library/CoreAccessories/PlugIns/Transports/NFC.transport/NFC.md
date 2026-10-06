## NFC

> `/System/Library/CoreAccessories/PlugIns/Transports/NFC.transport/NFC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x18ec` | `0x1c8c` | **`+0x3a0`** |
| `__TEXT.__text` | `0x9540` | `0x975c` | **`+0x21c`** |
| `__AUTH_CONST.__cfstring` | `0x1060` | `0x1120` | **`+0xc0`** |
| `__TEXT.__cstring` | `0xdbb` | `0xe6c` | **`+0xb1`** |
| `__DATA_CONST.__const` | `0x8f0` | `0x950` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x200` | `0x208` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 148
-  Symbols:   647
-  CStrings:  272
+  Functions: 150
+  Symbols:   667
+  CStrings:  278
Symbols:
+ _ACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _ACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _ACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _ACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _ACCUserDefaultsKey_PlatformIDOverride
+ _ACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ _colorWashTable0x8B
+ _colorWashTable0x8BSize
+ _colorWashTable0x8C
+ _colorWashTable0x8CSize
+ _colorWashTable0x8D
+ _colorWashTable0x8DSize
+ _colorWashTable0x8E
+ _colorWashTable0x8ESize
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _kCFACCUserDefaultsKey_TestCreateBLEPairingOnInductive
CStrings:
+ "BLEPairingConfigRequestDelayMs"
+ "BLEPairingDisableOOBPPlusFlow"
+ "BLEPairingDontEarlyInfoAsDeviceUID"
+ "BLEPairingIgnoreZeroEarlyInfo"
+ "PlatformIDOverride"
+ "TestCreateBLEPairingOnInductive"
```
