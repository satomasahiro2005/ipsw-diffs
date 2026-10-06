## trustd

> `/usr/libexec/trustd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x593f4` | `0x59e4c` | **`+0xa58`** |
| `__DATA_CONST.__cfstring` | `0x5d80` | `0x5a60` | **`-0x320`** |
| `__TEXT.__oslogstring` | `0x5739` | `0x590c` | **`+0x1d3`** |
| `__DATA_CONST.__got` | `0x810` | `0x920` | **`+0x110`** |
| `__TEXT.__cstring` | `0x5ddc` | `0x5d59` | **`-0x83`** |
| `__TEXT.__const` | `0xbd50` | `0xbd90` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1000` | `0x1030` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x41b0` | `0x41a0` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x2390` | `0x23a0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x2f89` | `0x2f93` | **`+0xa`** |
| `__DATA_CONST.__auth_got` | `0x11d8` | `0x11e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-62426.0.0.0.4
+62460.0.22.0.0

-  Functions: 1219
-  Symbols:   851
-  CStrings:  2171
+  Functions: 1220
+  Symbols:   886
+  CStrings:  2163
Symbols:
+ _SecPolicyIsKnown
+ ___kCFBooleanFalse
+ _kSecTrustInfoCRLiteGenerationUsedKey
+ _kSecTrustInfoCRLiteIsDefinitiveKey
+ _kSecTrustInfoCRLiteIsRevokedKey
+ _kSecTrustInfoCRLiteStatusKey
+ _kSecTrustInfoCRLiteVersionUsedKey
+ _kSecTrustInfoOCSPIsDefinitiveKey
+ _kSecTrustInfoOCSPIsRevokedKey
+ _kSecTrustInfoOCSPNextUpdateKey
+ _kSecTrustInfoOCSPThisUpdateKey
+ _kSecTrustInfoRevocationInfoCRLiteKey
+ _kSecTrustInfoRevocationInfoOCSPKey
+ _kSecTrustInfoRevocationInfoValidKey
+ _kSecTrustInfoValidAnchorHashKey
+ _kSecTrustInfoValidCertHashKey
+ _kSecTrustInfoValidCheckOCSPKey
+ _kSecTrustInfoValidCompleteKey
+ _kSecTrustInfoValidFormatKey
+ _kSecTrustInfoValidHasDateConstraintsKey
+ _kSecTrustInfoValidHasNameConstraintsKey
+ _kSecTrustInfoValidHasPolicyConstraintsKey
+ _kSecTrustInfoValidIsDefinitiveKey
+ _kSecTrustInfoValidIsOnListKey
+ _kSecTrustInfoValidIsRevokedKey
+ _kSecTrustInfoValidIsValidKey
+ _kSecTrustInfoValidIssuerHashKey
+ _kSecTrustInfoValidKnownOnlyKey
+ _kSecTrustInfoValidNameConstraintsKey
+ _kSecTrustInfoValidNoCACheckKey
+ _kSecTrustInfoValidNotAfterDateKey
+ _kSecTrustInfoValidNotBeforeDateKey
+ _kSecTrustInfoValidOverridableKey
+ _kSecTrustInfoValidPolicyConstraintsKey
+ _kSecTrustInfoValidRequireCTKey
CStrings:
+ "1.2.840.113635.100.6.1.10"
+ "Ignoring RevocationDb for Apple BNI chain"
+ "Ignoring RevocationDb for Apple store chain"
+ "SecDbConnectionRelease"
+ "Unable to create reply for XPC event"
+ "Unknown policy OID for system trust store lookup: %@"
+ "com.apple.securityd.idle-dbconnections-cleanup"
+ "error processing filter params at index %zu"
+ "idle connections more than baseline, kicking off cleanup"
+ "idle read dbconnections cleanup timer fired: %ld idle, baseline %d"
+ "idle read dbconnections cleanup: reached baseline, stopping timer"
+ "idle read dbconnections cleanup: starting timer (idle=%ld > baseline=%d)"
+ "idle read dbconnections cleanup: trimmed %ld, %ld remaining"
+ "inMemoryCacheEnabled"
+ "initWithURL:creationAllowed:isDaemon:error:"
+ "no need to cleanup"
+ "onQueueScheduleIdleReadConnectionsCleanupIfNeeded"
+ "unknown policy: %@"
- "Ignoring RevocationDb for Apple code signing chain"
- "anchorHash"
- "certHash"
- "checkOCSP"
- "complete"
- "crlite"
- "enableInMemoryCache"
- "error processing filter params at index %ld"
- "format"
- "hasDateConstraints"
- "hasNameConstraints"
- "hasPolicyConstraints"
- "initWithURL:creationAllowed:error:"
- "isDefinitive"
- "isOnList"
- "isRevoked"
- "issuerHash"
- "knownOnly"
- "nameConstraints"
- "noCACheck"
- "notAfterDate"
- "notBeforeDate"
- "overridable"
- "policyConstraints"
- "requireCT"
- "thisUpdate"
```
