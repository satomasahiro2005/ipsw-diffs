## USBHost

> `/System/Library/CoreAccessories/PlugIns/Transports/USBHost.transport/USBHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18870` | `0x18944` | **`+0xd4`** |
| `__AUTH_CONST.__cfstring` | `0x17e0` | `0x17c0` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x9b8` | `0x9d8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x528` | `0x538` | **`+0x10`** |
| `__TEXT.__cstring` | `0x19bb` | `0x19ac` | **`-0xf`** |
| `__TEXT.__gcc_except_tab` | `0x3b8` | `0x3c4` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x538` | `0x540` | **`+0x8`** |
| `__DATA.__bss` | `0xd8` | `0xe0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x270` | `0x278` | **`+0x8`** |

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Functions: 594
-  Symbols:   1233
-  CStrings:  497
+  Functions: 596
+  Symbols:   1242
+  CStrings:  495
Symbols:
+ _ACCTransportEANative_SessionSocketReadyNotification
+ _ACCUserDefaultsKey_EnableManager2ForTransport
+ _ACCUserDefaultsKey_OverrideMPPAuthSupported
+ _CFUUIDCreate
+ _CFUUIDCreateString
+ __gDeviceUUID
+ _kCFACCUserDefaultsKey_EnableManager2ForTransport
+ _kCFACCUserDefaultsKey_OverrideMPPAuthSupported
+ _platform_systemInfo_copyDeviceUUID
+ _platform_systemInfo_resetDeviceUUID
+ _usbUtil_copyInterfaceAndNameString
- _MGGetStringAnswer
- _usbUtil_getInterfaceAndNameString
CStrings:
+ "EnableManager2ForTransport"
+ "OverrideMPPAuthSupported"
+ "usbUtil_copyInterfaceAndNameString"
- "Accessory Manufacturer"
- "Accessory Model"
- "Accessory Name"
- "iAP Interface"
- "usbUtil_getInterfaceAndNameString"
```
