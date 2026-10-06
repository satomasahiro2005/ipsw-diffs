## PromotedContentProxy

> `/System/Library/PrivateFrameworks/PromotedContentProxy.framework/PromotedContentProxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55dc` | `0x4a78` | **`-0xb64`** |
| `__AUTH_CONST.__cfstring` | `0x560` | `0x220` | **`-0x340`** |
| `__AUTH_CONST.__objc_const` | `0x1180` | `0xfd8` | **`-0x1a8`** |
| `__TEXT.__cstring` | `0x3b8` | `0x227` | **`-0x191`** |
| `__TEXT.__objc_methlist` | `0x9ec` | `0x8a4` | **`-0x148`** |
| `__DATA_CONST.__objc_selrefs` | `0x908` | `0x7f0` | **`-0x118`** |
| `__DATA_CONST.__const` | `0x198` | `0x140` | **`-0x58`** |
| `__DATA_DIRTY.__objc_data` | `0x320` | `0x2d0` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x1e0` | `0x1a0` | **`-0x40`** |
| `__DATA_CONST.__objc_catlist` | `0x20` | `0x8` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x1a0` | `0x190` | **`-0x10`** |
| `__TEXT.__const` | `0xf0` | `0xe2` | **`-0xe`** |
| `__AUTH_CONST.__auth_got` | `0x1b8` | `0x1b0` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x48` | **`-0x8`** |

### Other Changes

```diff

-557.1.21.0.0
+557.1.24.0.0

-  Functions: 172
-  Symbols:   134
-  CStrings:  70
+  Functions: 148
+  Symbols:   129
+  CStrings:  44
Symbols:
+ _ErrorProxyAuthenticationRequired
+ _OBJC_CLASS_$_APProxyURLUtilities
+ _kVideoURLSchemeHTTP
+ _kVideoURLSchemeHTTPS
+ _kWebViewProxyURLSchemeHTTP
+ _kWebViewProxyURLSchemeHTTPS
- _NSInvalidArgumentException
- _OBJC_CLASS_$_APSystemInternal
- _OBJC_CLASS_$_NSException
- _OBJC_CLASS_$_NSMutableURLRequest
- _OBJC_CLASS_$_NSPredicate
- _OBJC_CLASS_$_NSURLComponents
- _OBJC_CLASS_$_NSURLQueryItem
- _OBJC_CLASS_$_NSURLRequest
- _OBJC_CLASS_$_NSUserDefaults
- ___kCFBooleanTrue
- _objc_retain
Functions:
- sub_294aee558
CStrings:
- ""
- "##"
- "##%@##%@##%@##%ld"
- "%@ key cannot be nil"
- "%@ value cannot be nil"
- ".apple.com"
- ".mzstatic.com"
- ".qwapi.com"
- "APProxyURLMockSettings.proxyDisabled"
- "ad-x-identifier"
- "adIdentifier"
- "apple.com"
- "com.apple.ap.pc.proxy-is-recursive"
- "localhost"
- "max-request-count"
- "maximumRequestCount"
- "mzstatic.com"
- "name != %@"
- "name = %@"
- "pc-video-http"
- "pc-video-https"
- "pc-x-tag-http"
- "pc-x-tag-https"
- "qwapi.com"
- "requestType"
- "videoAdvertisingIdentifier"
```
