## AccessoryComponentAuth

> `/System/Library/PrivateFrameworks/AccessoryComponentAuth.framework/AccessoryComponentAuth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12380` | `0x1240c` | **`+0x8c`** |
| `__AUTH_CONST.__cfstring` | `0x13e0` | `0x1420` | **`+0x40`** |
| `__TEXT.__cstring` | `0x14e6` | `0x14b6` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x1620` | `0x1640` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x11f1` | `0x11d7` | **`-0x1a`** |
| `__TEXT.__gcc_except_tab` | `0x25c` | `0x274` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x4cc` | `0x4e4` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x418` | `0x430` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x440` | `0x450` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x460` | `0x470` | **`+0x10`** |
| `__TEXT.__const` | `0xd710` | `0xd700` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Functions: 475
-  Symbols:   1471
-  CStrings:  337
+  Functions: 479
+  Symbols:   1479
+  CStrings:  338
Symbols:
+ -[ACCHWComponentAuthService _signChallengeForModuleType:challenge:componentIndex:completionHandler:]
+ -[ACCHWComponentAuthServiceParams dealloc]
+ GCC_except_table67
+ _ACCUserDefaultsKey_EnableManager2ForTransport
+ _ACCUserDefaultsKey_OverrideMPPAuthSupported
+ _kCFACCUserDefaultsKey_EnableManager2ForTransport
+ _kCFACCUserDefaultsKey_OverrideMPPAuthSupported
+ _objc_msgSendSuper2
+ _objc_retain_x3
- GCC_except_table66
CStrings:
+ "ERROR No auth io_service_t is found!"
+ "EnableManager2ForTransport"
+ "IDSN length %zu exceeds buffer"
+ "OverrideMPPAuthSupported"
+ "_signChallengeForModuleType Replying with signature=%@, deviceNonce=%@, authError = %d"
+ "cpClearCertificate failed: 0x%x"
- "###ELEE###: %s:%d: idsnStringRef: %@"
- "###ELEE###: %s:%d: test multiInstanceDataArray: %@"
- "-[ACCHWComponentAuthService _findFDRCertData:forModuleType:withAuthParams:hasDeviceCert:withError:]"
- "ERROR No batteryAuth io_service_t is found!"
- "signVeridianChallenge Replying with signature=%@, deviceNonce=%@, authError = %d"
```
