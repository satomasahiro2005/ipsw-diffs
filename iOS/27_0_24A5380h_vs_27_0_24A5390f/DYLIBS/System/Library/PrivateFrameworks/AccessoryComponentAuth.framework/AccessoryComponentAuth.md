## AccessoryComponentAuth

> `/System/Library/PrivateFrameworks/AccessoryComponentAuth.framework/AccessoryComponentAuth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1240c` | `0x1241c` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x4e4` | `0x4ec` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1203.0.0.0.0
+1210.0.0.502.1

-  Symbols:   1479
+  Symbols:   1480
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
CStrings:
+ "+[ACCHWComponentAuthService _verifyModuleFDR:forModuleType:]"
- "-[ACCHWComponentAuthService _verifyModuleFDR:forModuleType:]"
```
