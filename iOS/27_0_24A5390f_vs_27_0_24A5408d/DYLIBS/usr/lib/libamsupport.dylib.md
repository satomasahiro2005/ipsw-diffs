## libamsupport.dylib

> `/usr/lib/libamsupport.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x136d0` | `0x13928` | **`+0x258`** |
| `__TEXT.__cstring` | `0x2b06` | `0x2bbf` | **`+0xb9`** |
| `__AUTH_CONST.__cfstring` | `0xfa0` | `0x1000` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x368` | `0x3b8` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x4b0` | `0x4e0` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0xa48` | `0xa68` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x6f0` | `0x708` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x36c` | `0x37c` | **`+0x10`** |
| `__DATA.__bss` | `0x10` | `0x19` | **`+0x9`** |
| `__TEXT.__unwind_info` | `0x520` | `0x528` | **`+0x8`** |

### Other Changes

```diff

-475.0.2.0.0
+475.0.9.0.0

-  Functions: 535
-  Symbols:   1158
-  CStrings:  430
+  Functions: 540
+  Symbols:   1173
+  CStrings:  437
Symbols:
+ -[AMSupportOSURLSession shouldUpgrateToHTTPS]
+ _CFBundleGetInfoDictionary
+ _CFBundleGetMainBundle
+ _Img4EncodeItemCopyAndTransferBuffer
+ _Img4EncodeSet
+ _OBJC_CLASS_$_NSURLComponents
+ __AMSupportX509DecodeEcVerifySignatureDataWithOid
+ __NSConcreteGlobalBlock
+ ___45-[AMSupportOSURLSession shouldUpgrateToHTTPS]_block_invoke
+ ___block_descriptor_32_e5_v8?0l
+ ___block_literal_global
+ __oidSha1Ecdsa
+ _dispatch_once
+ _oidSha1Ecdsa
+ _shouldUpgrateToHTTPS.onceToken
+ _shouldUpgrateToHTTPS.usingATS
- _Img4EncodeDictionary
CStrings:
+ "-[AMSupportOSURLSession _urlRequestForHTTPMessage:]"
+ "Leaving custom port as is: %@"
+ "NSAppTransportSecurity"
+ "http"
+ "httpResponseData is NULL"
+ "https"
+ "using ATS, upgraded requestURL to https: %@"
```
