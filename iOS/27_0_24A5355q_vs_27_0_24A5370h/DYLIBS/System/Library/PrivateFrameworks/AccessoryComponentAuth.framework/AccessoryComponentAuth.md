## AccessoryComponentAuth

> `/System/Library/PrivateFrameworks/AccessoryComponentAuth.framework/AccessoryComponentAuth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x121c8` | `0x12380` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0x1171` | `0x11f1` | **`+0x80`** |
| `__TEXT.__cstring` | `0x146a` | `0x14e6` | **`+0x7c`** |
| `__AUTH_CONST.__cfstring` | `0x13c0` | `0x13e0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1600` | `0x1620` | **`+0x20`** |
| `__TEXT.__const` | `0xd700` | `0xd710` | **`+0x10`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1

-  Functions: 474
-  Symbols:   1467
-  CStrings:  332
+  Functions: 475
+  Symbols:   1471
+  CStrings:  337
Symbols:
+ _ACCUserDefaultsKey_PretendWirelessCTAMatch
+ __oidSmtpUTF8Mailbox
+ _kCFACCUserDefaultsKey_PretendWirelessCTAMatch
+ _oidSmtpUTF8Mailbox
Functions:
~ -[ACCHWComponentAuthService _authenticateModuleWithChallenge:completionHandler:moduleType:updateRegistry:updateUIProperty:logToAnalytics:componentIndex:] : 10256 -> 10248
~ -[ACCHWComponentAuthService _readCertificate:] : 376 -> 348
~ -[ACCHWComponentAuthService _findFDRCertData:forModuleType:withAuthParams:hasDeviceCert:withError:] : 772 -> 1160
~ ___init_logging_modules_block_invoke : 608 -> 588
~ ___init_logging_signpost_modules_block_invoke : 608 -> 588
~ _verify_chain_img4_v1 : 720 -> 724
~ _verify_chain_img4_ec_v1 : 432 -> 436
~ _parse_ec_chain : 592 -> 588
+ -[ACCHWComponentAuthService _readCertificate:].cold.1
~ _cpGetInternalComponents : 988 -> 1048
CStrings:
+ "###ELEE###: %s:%d: idsnStringRef: %@"
+ "###ELEE###: %s:%d: test multiInstanceDataArray: %@"
+ "(moduleType=%d) authError = %d after verifyModuleCertificate"
+ "-[ACCHWComponentAuthService _findFDRCertData:forModuleType:withAuthParams:hasDeviceCert:withError:]"
+ "Flags indicate battery...do not call cpCopyCertificate()"
+ "PretendWirelessCTAMatch"
+ "device nonce = %@"
+ "signature = %@"
- "(moduleType=%d) authError = %d after _verifyModuleCertificate"
- "Battery device nonce = %@"
- "Battery signature = %@"
```
