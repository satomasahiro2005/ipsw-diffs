## CloudKeychainProxy

> `/System/Library/Frameworks/Security.framework/CloudKeychainProxy.bundle/CloudKeychainProxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc2f4` | `0xc5d4` | **`+0x2e0`** |
| `__TEXT.__objc_stubs` | `0x1800` | `0x1920` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x1ca2` | `0x1d70` | **`+0xce`** |
| `__DATA.__objc_const` | `0x10c0` | `0x1150` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0x850` | `0x8a8` | **`+0x58`** |
| `__DATA.__objc_data` | `0x1e0` | `0x230` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x4a0` | `0x4e0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xc1c` | `0xc54` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x4eb` | `0x51b` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1e0` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x150` | `0x161` | **`+0x11`** |
| `__TEXT.__unwind_info` | `0x3b8` | `0x3c8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x87c` | `0x887` | **`+0xb`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__const` | `0xf8` | `0xf0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-62460.0.55.0.1
+62460.2.1.0.0

-  Functions: 302
-  Symbols:   260
-  CStrings:  657
+  Functions: 306
+  Symbols:   263
+  CStrings:  674
Symbols:
+ _NSURLErrorDomain
+ _OBJC_CLASS_$_NSError
+ _OBJC_CLASS_$_NSURLComponents
CStrings:
+ "%s Result from [Proxy requestSynchronization:]: %@"
+ "@40@0:8r*16Q24^@32"
+ "B32@0:8@16Q24"
+ "SecXPCNetworkURL"
+ "URL"
+ "allowedURLFromCString:options:error:"
+ "componentsWithString:"
+ "errorWithDomain:code:userInfo:"
+ "host"
+ "http"
+ "https"
+ "initWithUTF8String:"
+ "isAllowedURL:options:"
+ "lowercaseString"
+ "requestSynchronization:"
+ "scheme"
+ "scheme:isAllowedByOptions:"
+ "setError:code:"
+ "v32@0:8^@16q24"
- "%s Result from [Proxy waitForSynchronization:]: %@"
- "waitForSynchronization:"
```
