## networkserviceproxy

> `/usr/libexec/networkserviceproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbc650` | `0xbcd34` | **`+0x6e4`** |
| `__DATA_CONST.__got` | `0x708` | `0x810` | **`+0x108`** |
| `__TEXT.__oslogstring` | `0x10fcd` | `0x11036` | **`+0x69`** |
| `__TEXT.__objc_methname` | `0xff9a` | `0xffe0` | **`+0x46`** |
| `__TEXT.__cstring` | `0xdd0b` | `0xdd4b` | **`+0x40`** |
| `__DATA.__objc_const` | `0xb0d0` | `0xb0f8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1948` | `0x1968` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2238` | `0x2250` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x501c` | `0x5034` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x39c8` | `0x39d0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x9ec` | `0x9f0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-974.0.0.0.0
+976.0.0.0.0

-  Functions: 2147
+  Functions: 2150

-  CStrings:  6223
+  CStrings:  6229
CStrings:
+ "-[NSPPrivacyTokenManager fetchQuotaResponseForIssuerName:quotaService:auditToken:bundleID:accessToken:completionHandler:]"
+ "-[NSPPrivateAccessTokenFetcher checkCurrentQuotaStatusWithQueue:completionHandler:]"
+ "Configuration data has been cleared before agent data is copied"
+ "Failed to fetch current quota status: %@"
+ "NSPServerQuotaStatus"
+ "_relatedConfigurationHash"
+ "_selfConfigurationHash"
+ "checkCurrentQuotaStatusWithFetcher:allowRetry:completionHandler:"
+ "checkCurrentQuotaStatusWithQueue:completionHandler:"
+ "fetchQuotaResponseForIssuerName:quotaService:auditToken:bundleID:accessToken:completionHandler:"
- "-[NSPPrivacyTokenManager checkQuotaInnerForIssuerName:quotaService:auditToken:bundleID:accessToken:completionHandler:]"
- "checkCostQuotaForIssuerName:quotaService:auditToken:bundleID:accessToken:completionHandler:"
- "fetchDeviceQuotaConfigForIssuerName:quotaService:auditToken:bundleID:accessToken:completionHandler:"
- "v56@?0d8d16Q24q32@\"NSString\"40@\"NSString\"48"
```
