## ACCHWComponentAuthService

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/XPCServices/ACCHWComponentAuthService.xpc/ACCHWComponentAuthService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3958c` | `0x39518` | **`-0x74`** |
| `__TEXT.__objc_methlist` | `0x61c` | `0x624` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1203.0.0.0.0
+1210.0.0.502.1

-  Symbols:   2756
+  Symbols:   2757
Symbols:
+ +[ACCHWComponentAuthService _findFDRCertData:forModuleType:withAuthParams:hasDeviceCert:withError:]
+ +[ACCHWComponentAuthService _validateDeviceAndFDRCert:forModuleType:withAuthParams:]
+ +[ACCHWComponentAuthService _verifyModuleFDR:forModuleType:]
+ __OBJC_$_CLASS_METHODS_ACCHWComponentAuthService
- -[ACCHWComponentAuthService _findFDRCertData:forModuleType:withAuthParams:hasDeviceCert:withError:]
- -[ACCHWComponentAuthService _validateDeviceAndFDRCert:forModuleType:withAuthParams:]
- -[ACCHWComponentAuthService _verifyModuleFDR:forModuleType:]
Functions:
~ -[ACCHWComponentAuthService _authenticateModuleWithChallenge:completionHandler:moduleType:updateRegistry:updateUIProperty:logToAnalytics:componentIndex:] : 10520 -> 10536
~ _mfi4Auth_protocol_handle_AuthCert : 6940 -> 6808
CStrings:
+ "+[ACCHWComponentAuthService _verifyModuleFDR:forModuleType:]"
- "-[ACCHWComponentAuthService _verifyModuleFDR:forModuleType:]"
```
