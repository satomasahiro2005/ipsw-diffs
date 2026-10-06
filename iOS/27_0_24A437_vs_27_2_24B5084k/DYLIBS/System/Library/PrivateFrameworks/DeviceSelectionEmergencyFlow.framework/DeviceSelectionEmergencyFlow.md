## DeviceSelectionEmergencyFlow

> `/System/Library/PrivateFrameworks/DeviceSelectionEmergencyFlow.framework/DeviceSelectionEmergencyFlow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18de4` | `0x19348` | **`+0x564`** |
| `__TEXT.__unwind_info` | `0xa68` | `0xaa8` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x688` | `0x6b8` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1078` | `0x10a8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x4c2` | `0x4ed` | **`+0x2b`** |
| `__DATA_CONST.__objc_selrefs` | `0x290` | `0x2b8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x374` | `0x38c` | **`+0x18`** |
| `__DATA.__bss` | `0x1290` | `0x12a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x168` | `0x178` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x30` | `0x38` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x38` | `0x3c` | **`+0x4`** |

### Other Changes

```diff

-3600.49.15.0.0
+3605.22.1.0.0

-  Functions: 928
-  Symbols:   536
-  CStrings:  74
+  Functions: 937
+  Symbols:   558
+  CStrings:  76
Symbols:
+ -[WiProxDeviceInfo idsDeviceID]
+ -[WiProxDeviceInfo initWithDeviceUUID:deviceAddress:idsDeviceID:heySiriPerceptualHash:heySiriSNR:heySiriConfidence:heySiriDeviceGroup:heySiriDeviceClass:heySiriRandom:heySiriProductType:]
+ -[WiProxDiscoveryAdapter startScanningAndAdvertisingWithPhash:snr:random:confidence:]
+ GCC_except_table30
+ GCC_except_table31
+ GCC_except_table42
+ _MakeHeySiriPayload
+ _OBJC_CLASS_$_NSString
+ _OBJC_IVAR_$_WiProxDeviceInfo._idsDeviceID
+ _WirelessProximityLibrary
+ ___85-[WiProxDiscoveryAdapter startScanningAndAdvertisingWithPhash:snr:random:confidence:]_block_invoke
+ ___getWPHeySiriNeedsIdentitySymbolLoc_block_invoke
+ ___getWPHeySiriRPIdentitySymbolLoc_block_invoke
+ ___kCFBooleanTrue
+ _getWPHeySiriAdvertisingData
+ _getWPHeySiriNeedsIdentity
+ _getWPHeySiriNeedsIdentitySymbolLoc.ptr
+ _getWPHeySiriRPIdentitySymbolLoc.ptr
+ _objc_autoreleaseReturnValue
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _objc_retainAutoreleaseReturnValue
+ _objc_retain_x21
+ _objc_retain_x24
+ _objc_retain_x27
- -[WiProxDeviceInfo initWithDeviceUUID:deviceAddress:heySiriPerceptualHash:heySiriSNR:heySiriConfidence:heySiriDeviceGroup:heySiriDeviceClass:heySiriRandom:heySiriProductType:]
- GCC_except_table27
- _objc_retain_x25
CStrings:
+ "WPHeySiriNeedsIdentity"
+ "WPHeySiriRPIdentity"
```
