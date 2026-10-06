## trustd

> `/usr/libexec/trustd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0xbd90` | `0xde40` | **`+0x20b0`** |
| `__TEXT.__text` | `0x58e00` | `0x59b58` | **`+0xd58`** |
| `__TEXT.__oslogstring` | `0x5b4b` | `0x5d96` | **`+0x24b`** |
| `__DATA_CONST.__cfstring` | `0x5b80` | `0x5d40` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x5fa4` | `0x60c3` | **`+0x11f`** |
| `__TEXT.__objc_stubs` | `0x32a0` | `0x3360` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x2f08` | `0x2fbe` | **`+0xb6`** |
| `__TEXT.__auth_stubs` | `0x2380` | `0x23d0` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0xe28` | `0xe58` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x11d0` | `0x11f8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x3da0` | `0x3dc8` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0xab8` | `0xae0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xdf4` | `0xe14` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xff8` | `0x1018` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x918` | `0x930` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0xc5d` | `0xc6b` | **`+0xe`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`

### Other Changes

```diff

-62460.0.55.0.1
+62460.2.1.0.0

+  - /System/Library/PrivateFrameworks/CoreTime.framework/CoreTime

-  Functions: 1197
-  Symbols:   881
-  CStrings:  2179
+  Functions: 1202
+  Symbols:   889
+  CStrings:  2210
Symbols:
+ _CFUUIDCreate
+ _CFUUIDCreateString
+ _SecGetBestEffortTime
+ _access
+ _inet_pton
+ _kSecTrustInfoEvaluationIDKey
+ _kSecTrustInfoOCSPFetchFailedKey
+ _kSecTrustInfoOCSPTimedOutKey
CStrings:
+ "CAIssuerSSRFBadPort"
+ "CAIssuerSSRFLinkLocal"
+ "CAIssuerSSRFLoopback"
+ "CAIssuerSSRFOtherReserved"
+ "CAIssuerSSRFRFC1918"
+ "OCSPSSRFBadPort"
+ "OCSPSSRFLinkLocal"
+ "OCSPSSRFLoopback"
+ "OCSPSSRFOtherReserved"
+ "OCSPSSRFRFC1918"
+ "TrustStore.sqlite3-journal"
+ "TrustStore.sqlite3-shm"
+ "TrustStore.sqlite3-wal"
+ "[]"
+ "[refTime] eval freshnessTime=%.0f sysTime=%.0f delta=%.0fs verifyTime=%.0f"
+ "arrayByAddingObjectsFromArray:"
+ "builder %p, eval %@, cert %ld: OCSP status revoked=%@ definitive=%@ fetchFailed=%d timedOut=%d"
+ "builder %p, eval %@, cert %ld: evaluating OCSP signer chain in child builder"
+ "builder %p, eval %@, cert %ld: failed to download ocsp response from %@, timeout=%d, error %@"
+ "builder %p, eval %@, cert %ld: response from %@ was not a valid OCSP response (treating as fetch failure)"
+ "builder %p, evaluationID %@, completed trust evaluation"
+ "builder %p, evaluationID %@, starting trust evaluation (attribution %llu)"
+ "cannot write %s: %s"
+ "characterSetWithCharactersInString:"
+ "failed to stat %s: %s"
+ "port"
+ "protocolClasses"
+ "recordSSRFShadowBuckets:forContext:"
+ "setProtocolClasses:"
+ "stringByTrimmingCharactersInSet:"
+ "timeIntervalSinceReferenceDate"
+ "trustRefTime"
+ "v28@0:8I16@20"
+ "wrong owner for %s"
- "Failed to download ocsp response %@, with error %@"
- "date"
- "timeIntervalSinceNow"
```
