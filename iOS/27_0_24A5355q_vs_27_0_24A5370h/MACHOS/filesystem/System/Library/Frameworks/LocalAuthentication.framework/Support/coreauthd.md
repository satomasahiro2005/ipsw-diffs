## coreauthd

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/coreauthd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38044` | `0x381d4` | **`+0x190`** |
| `__TEXT.__objc_methname` | `0x472f` | `0x47b8` | **`+0x89`** |
| `__TEXT.__objc_stubs` | `0x3620` | `0x36a0` | **`+0x80`** |
| `__TEXT.__objc_methtype` | `0x1eef` | `0x1f44` | **`+0x55`** |
| `__TEXT.__oslogstring` | `0x1655` | `0x1699` | **`+0x44`** |
| `__DATA.__objc_selrefs` | `0x1150` | `0x1178` | **`+0x28`** |
| `__TEXT.__cstring` | `0x4ff1` | `0x5010` | **`+0x1f`** |
| `__TEXT.__unwind_info` | `0xd08` | `0xd20` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x5b8` | `0x5c8` | **`+0x10`** |
| `__TEXT.__const` | `0x13f0` | `0x13f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2305.0.0.0.1
+2319.0.16.502.1

-  Functions: 1557
-  Symbols:   423
-  CStrings:  1824
+  Functions: 1555
+  Symbols:   425
+  CStrings:  1833
Symbols:
+ _OBJC_CLASS_$_LACAnalyticsContextManagementReporterProvider
+ _OBJC_CLASS_$_LACApplePayBiometryToggleProcessor
CStrings:
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s cccurve25519 failed: small-order point used%s\n"
+ "credentialEncodingSeedWithOriginator:reply:"
+ "generate_wrapping_key_curve25519"
+ "initForStatusMonitoringWithEnvironment:device:workQueue:"
+ "parameterErrorForMissingOrInvalidObject:name:"
+ "receiverAuditTokenData"
+ "rejecting allowTransfer with nil receiverAuditTokenData from pid %d"
+ "reportAnomaly:"
+ "reportTransfer:"
+ "reporter"
+ "v32@0:8@\"<LACXPCClient>\"16@?<v@?@\"NSData\"@\"NSError\">24"
+ "v32@0:8@\"<LACXPCClient>\"16@?<v@?@\"NSUUID\"@\"NSError\">24"
+ "v40@0:8@\"NSUUID\"16@\"<LACXPCClient>\"24@?<v@?B@\"NSError\">32"
+ "v40@0:8q16@\"<LACXPCClient>\"24@?<v@?@\"NSData\"@\"NSError\">32"
+ "v40@0:8q16@\"<LACXPCClient>\"24@?<v@?B@\"NSError\">32"
+ "v56@0:8@\"NSData\"16q24@\"NSDictionary\"32@\"<LACXPCClient>\"40@?<v@?B@\"NSError\">48"
- "ACMCredential - ACMCredentialDataPKITokenValidated"
- "ACMCredential - ACMCredentialDataPKITokenValidated2"
- "initForStatusMonitoringWithEnvironment:workQueue:"
- "v32@0:8@\"<LACOriginatorProt>\"16@?<v@?@\"NSUUID\"@\"NSError\">24"
- "v40@0:8@\"NSUUID\"16@\"<LACOriginatorProt>\"24@?<v@?B@\"NSError\">32"
- "v40@0:8q16@\"<LACOriginatorProt>\"24@?<v@?@\"NSData\"@\"NSError\">32"
- "v56@0:8@\"NSData\"16q24@\"NSDictionary\"32@\"<LACOriginatorProt>\"40@?<v@?B@\"NSError\">48"
```
