## JetCore

> `/System/Library/PrivateFrameworks/JetCore.framework/JetCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x23c90` | `0x23690` | **`-0x600`** |
| `__DATA_DIRTY.__bss` | `0x5910` | `0x5f10` | **`+0x600`** |
| `__TEXT.__cstring` | `0xaa01` | `0xac71` | **`+0x270`** |
| `__DATA_DIRTY.__data` | `0x3748` | `0x3928` | **`+0x1e0`** |
| `__DATA.__data` | `0x66a0` | `0x6550` | **`-0x150`** |
| `__AUTH_CONST.__const` | `0x1aa98` | `0x1abd8` | **`+0x140`** |
| `__AUTH.__data` | `0x2848` | `0x2798` | **`-0xb0`** |

### Other Changes

```diff

-10.1.8.0.0
+10.1.9.0.0

-  CStrings:  1000
+  CStrings:  1019
CStrings:
+ "firstContentfulPaint"
+ "largestContentfulPaint"
+ "w3cNavConnectEnd"
+ "w3cNavConnectStart"
+ "w3cNavDomContentLoadedEventEnd"
+ "w3cNavDomContentLoadedEventStart"
+ "w3cNavDomainLookupEnd"
+ "w3cNavDomainLookupStart"
+ "w3cNavFetchStart"
+ "w3cNavLoadEventEnd"
+ "w3cNavLoadEventStart"
+ "w3cNavRedirectEnd"
+ "w3cNavRedirectStart"
+ "w3cNavRequestStart"
+ "w3cNavResponseEnd"
+ "w3cNavResponseStart"
+ "w3cNavSecureConnectionStart"
+ "w3cNavUnloadEventEnd"
+ "w3cNavUnloadEventStart"
```
