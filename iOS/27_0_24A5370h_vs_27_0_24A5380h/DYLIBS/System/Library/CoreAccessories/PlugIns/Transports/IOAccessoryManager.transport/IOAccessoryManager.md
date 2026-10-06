## IOAccessoryManager

> `/System/Library/CoreAccessories/PlugIns/Transports/IOAccessoryManager.transport/IOAccessoryManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d0a0` | `0x5d470` | **`+0x3d0`** |
| `__AUTH_CONST.__cfstring` | `0x4560` | `0x45a0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0xbc14` | `0xbc54` | **`+0x40`** |
| `__TEXT.__cstring` | `0x5faa` | `0x5fde` | **`+0x34`** |
| `__TEXT.__unwind_info` | `0xea0` | `0xec8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0xed8` | `0xef8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x8dc` | `0x8f4` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x2f64` | `0x2f7c` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xaf8` | `0xb00` | **`+0x8`** |
| `__DATA.__bss` | `0x120` | `0x128` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ef8` | `0x1f00` | **`+0x8`** |

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Functions: 1941
-  Symbols:   2832
-  CStrings:  1704
+  Functions: 1948
+  Symbols:   2842
+  CStrings:  1708
Symbols:
+ +[ACCTransportIOAccessoryManager isTransientPortLevelAccIDDetachForConnectionType:inductiveDeviceType:oobPairingEarlyInfoEndpoint:]
+ GCC_except_table62
+ _ACCUserDefaultsKey_EnableManager2ForTransport
+ _ACCUserDefaultsKey_OverrideMPPAuthSupported
+ _CFUUIDCreate
+ _CFUUIDCreateString
+ __OBJC_$_CLASS_METHODS_ACCTransportIOAccessoryManager
+ __gDeviceUUID
+ _kCFACCUserDefaultsKey_EnableManager2ForTransport
+ _kCFACCUserDefaultsKey_OverrideMPPAuthSupported
+ _platform_systemInfo_copyDeviceUUID
+ _platform_systemInfo_resetDeviceUUID
- GCC_except_table61
- _MGGetStringAnswer
CStrings:
+ "EnableManager2ForTransport"
+ "Failed to create IDSN String Ref"
+ "IDSN length %zu exceeds buffer"
+ "OverrideMPPAuthSupported"
```
