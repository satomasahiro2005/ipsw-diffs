## ACCHWComponentAuthService

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/XPCServices/ACCHWComponentAuthService.xpc/ACCHWComponentAuthService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37f40` | `0x38310` | **`+0x3d0`** |
| `__TEXT.__oslogstring` | `0x6268` | `0x62e8` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1ef1` | `0x1f6d` | **`+0x7c`** |
| `__DATA_CONST.__cfstring` | `0x1600` | `0x1620` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x64d8` | `0x64f8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x800` | `0x7f8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1

-  Functions: 1202
-  Symbols:   2739
-  CStrings:  1208
+  Functions: 1204
+  Symbols:   2745
+  CStrings:  1213
Symbols:
+ _ACCUserDefaultsKey_PretendWirelessCTAMatch
+ _CTParseLeafSPKI
+ _OUTLINED_FUNCTION_62
+ __oidSmtpUTF8Mailbox
+ _kCFACCUserDefaultsKey_PretendWirelessCTAMatch
+ _objc_msgSend$createNoAuthICNonce:withChallenge:
+ _oidSmtpUTF8Mailbox
- _objc_msgSend$createVeridianNonce:withChallenge:
CStrings:
+ "###ELEE###: %s:%d: idsnStringRef: %@"
+ "###ELEE###: %s:%d: test multiInstanceDataArray: %@"
+ "(moduleType=%d) authError = %d after verifyModuleCertificate"
+ "-[ACCHWComponentAuthService _findFDRCertData:forModuleType:withAuthParams:hasDeviceCert:withError:]"
+ "Flags indicate battery...do not call cpCopyCertificate()"
+ "PretendWirelessCTAMatch"
+ "createNoAuthICNonce:withChallenge:"
+ "device nonce = %@"
+ "signature = %@"
- "(moduleType=%d) authError = %d after _verifyModuleCertificate"
- "Battery device nonce = %@"
- "Battery signature = %@"
- "createVeridianNonce:withChallenge:"
```
