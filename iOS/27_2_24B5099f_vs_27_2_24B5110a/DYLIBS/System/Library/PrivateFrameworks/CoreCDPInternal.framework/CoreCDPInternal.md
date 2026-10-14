## CoreCDPInternal

> `/System/Library/PrivateFrameworks/CoreCDPInternal.framework/CoreCDPInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x9940` | `0x9960` | **`+0x20`** |
| `__TEXT.__cstring` | `0xe6a5` | `0xe6b5` | **`+0x10`** |
| `__TEXT.__text` | `0x907d4` | `0x907e0` | **`+0xc`** |

### Other Changes

```diff

-448.125.9.0.0
+448.125.10.0.0

-  CStrings:  2863
+  CStrings:  2864
Functions:
~ ___47+[CDPDAnalyticsTransport getAllowedErrorDomain]_block_invoke : 808 -> 820
CStrings:
+ "kSecurityRTCErrorDomain"
```
