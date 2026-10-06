## com.apple.accessoryd.matching

> `/System/Library/UserEventPlugins/com.apple.accessoryd.matching.plugin/com.apple.accessoryd.matching`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__cfstring` | `0x39c0` | `0x3a80` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x4faa` | `0x505b` | **`+0xb1`** |
| `__DATA.__const` | `0x10f0` | `0x1150` | **`+0x60`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__got`
- `__DATA.__objc_arraydata`
- `__DATA.__objc_arrayobj`
- `__DATA.__objc_catlist`
- `__DATA.__objc_classlist`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_dictobj`
- `__DATA.__objc_protolist`
- `__DATA.__objc_protorefs`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   3149
-  CStrings:  2507
+  Symbols:   3161
+  CStrings:  2513
Symbols:
+ _ACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _ACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _ACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _ACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _ACCUserDefaultsKey_PlatformIDOverride
+ _ACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _kCFACCUserDefaultsKey_TestCreateBLEPairingOnInductive
Functions:
~ _OUTLINED_FUNCTION_13 : 12 -> 16
~ _OUTLINED_FUNCTION_14 : 16 -> 12
CStrings:
+ "BLEPairingConfigRequestDelayMs"
+ "BLEPairingDisableOOBPPlusFlow"
+ "BLEPairingDontEarlyInfoAsDeviceUID"
+ "BLEPairingIgnoreZeroEarlyInfo"
+ "PlatformIDOverride"
+ "TestCreateBLEPairingOnInductive"
```
