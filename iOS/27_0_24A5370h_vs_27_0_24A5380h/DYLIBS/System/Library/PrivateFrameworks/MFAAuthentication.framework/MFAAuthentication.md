## MFAAuthentication

> `/System/Library/PrivateFrameworks/MFAAuthentication.framework/MFAAuthentication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4263c` | `0x429ac` | **`+0x370`** |
| `__TEXT.__oslogstring` | `0x4d7c` | `0x4e24` | **`+0xa8`** |
| `__AUTH_CONST.__cfstring` | `0x1b40` | `0x1b80` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1aa8` | `0x1adc` | **`+0x34`** |
| `__DATA_CONST.__const` | `0x5278` | `0x5298` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x7c8` | `0x7d0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x210` | `0x208` | **`-0x8`** |

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Functions: 850
-  Symbols:   1844
-  CStrings:  718
+  Functions: 853
+  Symbols:   1848
+  CStrings:  723
Symbols:
+ -[MFAACertificateManager createVeridianNonce:withChallenge:]
+ _ACCUserDefaultsKey_EnableManager2ForTransport
+ _ACCUserDefaultsKey_OverrideMPPAuthSupported
+ _CFErrorGetCode
+ _SecTrustGetTrustResult
+ _kCFACCUserDefaultsKey_EnableManager2ForTransport
+ _kCFACCUserDefaultsKey_OverrideMPPAuthSupported
- -[MFAACertificateManager createNoAuthICNonce:withChallenge:]
- _SecTrustEvaluate
- _kIOMainPortDefault
CStrings:
+ "EnableManager2ForTransport"
+ "MFAADeviceIdentity: _findValidIndex: Failed to create date objects\n"
+ "OverrideMPPAuthSupported"
+ "SecTrustEvaluateWithError failed: %@"
+ "SecTrustEvaluateWithError failed: %@\n"
+ "SecTrustGetTrustResult failed: %d"
+ "SecTrustGetTrustResult failed: %d\n"
+ "validateCertificateChain: SecTrustEvaluateWithError failed: %@\n"
+ "validateCertificateChain: SecTrustGetTrustResult failed: %d\n"
- "SecTrustEvaluate failed osStatus:%02X\n"
- "SecTrustSetAnchorCertificates fail osStatus:%02X\n"
- "trustError: %@"
- "validateCertificateChain: SecTrustEvaluate failed osStatus:%02X\n"
```
