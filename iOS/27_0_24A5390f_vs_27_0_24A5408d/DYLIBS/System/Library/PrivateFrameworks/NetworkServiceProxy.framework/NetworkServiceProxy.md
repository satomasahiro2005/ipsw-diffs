## NetworkServiceProxy

> `/System/Library/PrivateFrameworks/NetworkServiceProxy.framework/NetworkServiceProxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x631cc` | `0x63560` | **`+0x394`** |
| `__AUTH_CONST.__objc_const` | `0x80a0` | `0x80e0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x5fec` | `0x601c` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x51a0` | `0x51c0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x29d8` | `0x29f8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5acb` | `0x5ae2` | **`+0x17`** |
| `__DATA_DIRTY.__objc_ivar` | `0x2d8` | `0x2dc` | **`+0x4`** |

### Other Changes

```diff

-980.0.0.0.0
+985.0.0.0.0

-  - /usr/lib/libboringssl.dylib

-  Functions: 2124
-  Symbols:   3298
-  CStrings:  1222
+  Functions: 2128
+  Symbols:   3302
+  CStrings:  1223
Symbols:
+ -[NSPPrivacyProxyConfiguration hasMaxRebootFetchesPerDay]
+ -[NSPPrivacyProxyConfiguration maxRebootFetchesPerDay]
+ -[NSPPrivacyProxyConfiguration setHasMaxRebootFetchesPerDay:]
+ -[NSPPrivacyProxyConfiguration setMaxRebootFetchesPerDay:]
CStrings:
+ "maxRebootFetchesPerDay"
```
