## libamsupport.dylib

> `/usr/lib/libamsupport.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13918` | `0x1389c` | **`-0x7c`** |
| `__TEXT.__cstring` | `0x2bbf` | `0x2bff` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3b8` | `0x388` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1000` | `0xfe0` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0xa68` | `0xa48` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x4e0` | `0x4c8` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x708` | `0x6f8` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x37c` | `0x36c` | **`-0x10`** |
| `__DATA.__bss` | `0x19` | `0x10` | **`-0x9`** |
| `__TEXT.__const` | `0xd2c0` | `0xd2c8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x528` | `0x520` | **`-0x8`** |

### Other Changes

```diff

-475.0.9.0.0
+475.40.6.0.0

-  Functions: 540
-  Symbols:   1173
+  Functions: 537
+  Symbols:   1167
Symbols:
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _kAMSupportHttpOptionRequestHTTPAllowed
+ _kImg4TagStr_srvc
+ _os_variant_has_internal_content
- -[AMSupportOSURLSession shouldUpgrateToHTTPS]
- _CFBundleGetInfoDictionary
- _CFBundleGetMainBundle
- _OBJC_CLASS_$_NSURLComponents
- __NSConcreteGlobalBlock
- ___45-[AMSupportOSURLSession shouldUpgrateToHTTPS]_block_invoke
- ___block_descriptor_32_e5_v8?0l
- ___block_literal_global
- _dispatch_once
- _shouldUpgrateToHTTPS.onceToken
- _shouldUpgrateToHTTPS.usingATS
CStrings:
+ "-[AMSupportOSURLSession _defaultSessionConfigurationWithIdentifier:]"
+ "ATS: OS is internal."
+ "ATS: disabled per request on allowed build type."
+ "NSAllowsArbitraryLoads"
+ "RequestHTTPAllowed"
+ "com.apple.libamsupport.amsupporturlsession"
- "-[AMSupportOSURLSession _urlRequestForHTTPMessage:]"
- "Leaving custom port as is: %@"
- "NSAppTransportSecurity"
- "http"
- "https"
- "using ATS, upgraded requestURL to https: %@"
```
