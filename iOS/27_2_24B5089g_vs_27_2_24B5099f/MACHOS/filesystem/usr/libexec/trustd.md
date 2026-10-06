## trustd

> `/usr/libexec/trustd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59cec` | `0x5a680` | **`+0x994`** |
| `__TEXT.__oslogstring` | `0x5d96` | `0x5f18` | **`+0x182`** |
| `__TEXT.__cstring` | `0x6139` | `0x621e` | **`+0xe5`** |
| `__DATA_CONST.__cfstring` | `0x5dc0` | `0x5ea0` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x3de8` | `0x3e70` | **`+0x88`** |
| `__TEXT.__objc_methname` | `0x3003` | `0x307d` | **`+0x7a`** |
| `__TEXT.__objc_stubs` | `0x33a0` | `0x3400` | **`+0x60`** |
| `__DATA.__objc_const` | `0x1750` | `0x1780` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x930` | `0x908` | **`-0x28`** |
| `__DATA.__bss` | `0x520` | `0x540` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xe68` | `0xe88` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1020` | `0x1040` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xe14` | `0xe2c` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x23d0` | `0x23c0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x11f8` | `0x11f0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xd0` | `0xd4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
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
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-62460.40.56.502.1
+62460.40.74.0.0

-  Functions: 1204
-  Symbols:   889
-  CStrings:  2216
+  Functions: 1210
+  Symbols:   884
+  CStrings:  2240
Symbols:
+ _CCDigest
+ _CCDigestGetOutputSize
+ _NSURLErrorFailingURLErrorKey
+ _SecKeyVerifySignature
+ _freeaddrinfo
+ _getaddrinfo
+ _kSecKeyAlgorithmECDSASignatureMessageX962SHA1
+ _kSecKeyAlgorithmECDSASignatureMessageX962SHA256
+ _kSecKeyAlgorithmECDSASignatureMessageX962SHA384
+ _kSecKeyAlgorithmRSASignatureMessagePKCS1v15SHA1
+ _kSecKeyAlgorithmRSASignatureMessagePKCS1v15SHA256
+ _kSecKeyAlgorithmRSASignatureMessagePKCS1v15SHA384
+ _readdir
- _CC_SHA224
- _CC_SHA256
- _CC_SHA384
- _CC_SHA512
- _CFPropertyListCreateXMLData
- _CFURLCreateDataAndPropertiesFromResource
- _CSSMOID_ECDSA_WithSHA1
- _CSSMOID_ECDSA_WithSHA256
- _CSSMOID_ECDSA_WithSHA384
- _CSSMOID_SHA1WithRSA
- _CSSMOID_SHA256WithRSA
- _CSSMOID_SHA384WithRSA
- _NSURLErrorFailingURLStringErrorKey
- _SecDigestCreate
- _inet_pton
- _readdir_r
- _xpc_transaction_begin
- _xpc_transaction_end
CStrings:
+ "0.4.0.194112.1.4"
+ "0.4.0.194112.1.5"
+ "CAIssuerSSRFBadPortAlt"
+ "CAIssuerSSRFBadPortSvc"
+ "OCSPExtraSingleResponses"
+ "OCSPResponse: duplicate certID, preferring revoked"
+ "OCSPResponse: more than %d certificates in the response"
+ "OCSPResponse: no request to scope the validity interval to"
+ "OCSPSSRFBadPortAlt"
+ "OCSPSSRFBadPortSvc"
+ "TB,V_responseTooLarge"
+ "Unable to get data from \"%s\": %@"
+ "UseSSRFLiteralEnforcement"
+ "UseSSRFPortEnforcement"
+ "_responseTooLarge"
+ "cancel"
+ "com.apple.trustd.analytics"
+ "dataWithContentsOfURL:options:error:"
+ "ocspcache"
+ "ocspcache: no request to scope the cache write to, not caching"
+ "response does not answer the request, not caching"
+ "response for taskId %@ from %@ passed %d bytes, cancelling"
+ "responseTooLarge"
+ "setResponseTooLarge:"
+ "skipping SSRF-denied destination for %@ (buckets 0x%x)"
- "Unable to get data from \"%s\": error %ld"
```
