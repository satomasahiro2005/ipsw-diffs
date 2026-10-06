## ACCHWComponentAuthService

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/XPCServices/ACCHWComponentAuthService.xpc/ACCHWComponentAuthService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38310` | `0x3958c` | **`+0x127c`** |
| `__TEXT.__oslogstring` | `0x62e8` | `0x6675` | **`+0x38d`** |
| `__TEXT.__objc_methname` | `0x1626` | `0x1676` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x1620` | `0x1660` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1f6d` | `0x1f3d` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x64f8` | `0x6518` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xe00` | `0xe20` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xe40` | `0xe60` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x7f8` | `0x818` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x25c` | `0x274` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x604` | `0x61c` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x5f2` | `0x607` | **`+0x15`** |
| `__DATA.__objc_selrefs` | `0x598` | `0x5a8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x710` | `0x720` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Functions: 1204
-  Symbols:   2745
-  CStrings:  1213
+  Functions: 1216
+  Symbols:   2756
+  CStrings:  1239
Symbols:
+ -[ACCHWComponentAuthService _signChallengeForModuleType:challenge:componentIndex:completionHandler:]
+ -[ACCHWComponentAuthServiceParams dealloc]
+ GCC_except_table67
+ _ACCUserDefaultsKey_EnableManager2ForTransport
+ _ACCUserDefaultsKey_OverrideMPPAuthSupported
+ _CFDataCreateWithBytesNoCopy
+ _OUTLINED_FUNCTION_63
+ _OUTLINED_FUNCTION_64
+ _kCFACCUserDefaultsKey_EnableManager2ForTransport
+ _kCFACCUserDefaultsKey_OverrideMPPAuthSupported
+ _objc_msgSend$_signChallengeForModuleType:challenge:componentIndex:completionHandler:
+ _objc_msgSend$createVeridianNonce:withChallenge:
+ _objc_msgSendSuper2
- GCC_except_table66
- _objc_msgSend$createNoAuthICNonce:withChallenge:
CStrings:
+ "ERROR No auth io_service_t is found!"
+ "EnableManager2ForTransport"
+ "IDSN length %zu exceeds buffer"
+ "NVMReadResponse: paramID %d exceeds maximum expected value"
+ "OverrideMPPAuthSupported"
+ "UserPublicKey %@"
+ "_replyGetNVMKey: !dictionary"
+ "_signChallengeForModuleType Replying with signature=%@, deviceNonce=%@, authError = %d"
+ "_signChallengeForModuleType:challenge:componentIndex:completionHandler:"
+ "copyUserPrivateKey: error:%d"
+ "cpClearCertificate failed: 0x%x"
+ "createVeridianNonce:withChallenge:"
+ "dealloc"
+ "handle_NVMAuthFinish: paramID %d exceeds maximum expected value"
+ "handle_NVMAuthStart: !serialNumberString"
+ "handle_NVMAuthStart: !userKey"
+ "handle_NVMAuthStart: !userPublicKey"
+ "handle_NVMAuthStart: U_c0: %@"
+ "handle_NVMAuthStart: U_sig: %@"
+ "handle_NVMAuthStart: ccsigma_seal error"
+ "handle_NVMAuthStart: ccsigma_sign: error"
+ "handle_NVMAuthStart: initMessage_RequestNVMAuthFinish error"
+ "handle_NVMAuthStart: paramID %d exceeds maximum expected value"
+ "handle_NVMEraseResponse: paramID %d exceeds maximum expected value"
+ "handle_NVMOperationResponse: paramID %d exceeds maximum expected value"
+ "handle_NVMPublicKeyChallenge: paramID %d exceeds maximum expected value"
+ "initSigmaContextNvm: !userKey"
+ "initSigmaContextNvm: ccsigma_export_key_share: error"
+ "initSigmaContextNvm: ccsigma_set_signing_function"
+ "initSigmaContextNvm: key_share_size != 33"
+ "nvmDhPublicKeyX %@"
+ "nvmDhPublicKeyY %@"
+ "v44@0:8i16@20@28@?36"
- "###ELEE###: %s:%d: idsnStringRef: %@"
- "###ELEE###: %s:%d: test multiInstanceDataArray: %@"
- "-[ACCHWComponentAuthService _findFDRCertData:forModuleType:withAuthParams:hasDeviceCert:withError:]"
- "ERROR No batteryAuth io_service_t is found!"
- "_convertNVMReadResponse: Unsupported read response ID: %d"
- "createNoAuthICNonce:withChallenge:"
- "signVeridianChallenge Replying with signature=%@, deviceNonce=%@, authError = %d"
```
