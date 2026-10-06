## NetworkServiceProxy

> `/System/Library/PrivateFrameworks/NetworkServiceProxy.framework/NetworkServiceProxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x60d7c` | `0x631cc` | **`+0x2450`** |
| `__AUTH_CONST.__objc_const` | `0x7ce8` | `0x80a0` | **`+0x3b8`** |
| `__TEXT.__objc_methlist` | `0x5dcc` | `0x5fec` | **`+0x220`** |
| `__TEXT.__oslogstring` | `0x310f` | `0x32c4` | **`+0x1b5`** |
| `__AUTH_CONST.__cfstring` | `0x5000` | `0x51a0` | **`+0x1a0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2898` | `0x29d8` | **`+0x140`** |
| `__TEXT.__cstring` | `0x5a00` | `0x5acb` | **`+0xcb`** |
| `__AUTH.__objc_data` | `0x13b0` | `0x1450` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x11c8` | `0x1228` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x448` | `0x468` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x31c` | `0x334` | **`+0x18`** |
| `__DATA_DIRTY.__objc_ivar` | `0x2c0` | `0x2d8` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x210` | `0x220` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1f8` | `0x208` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x6c0` | `0x6c8` | **`+0x8`** |
| `__TEXT.__const` | `0x368` | `0x370` | **`+0x8`** |

### Other Changes

```diff

-976.0.0.0.0
+980.0.0.0.0

-  Functions: 2079
-  Symbols:   3229
-  CStrings:  1199
+  Functions: 2124
+  Symbols:   3298
+  CStrings:  1222
Symbols:
+ +[NSPJSONWebToken base64URLStringFromData:]
+ +[NSPJSONWebToken dataFromBase64URLString:]
+ +[NSPJSONWebToken jsonDictionaryFromBase64URLString:]
+ +[NSPPrivateAccessTokenFetcher selectDenominationTokensToRequestForCostTokenTotal:denominationValues:]
+ -[NSPJSONWebToken .cxx_destruct]
+ -[NSPJSONWebToken derEncodedSignatureFromRaw:]
+ -[NSPJSONWebToken derIntegerFromUnsigned:]
+ -[NSPJSONWebToken descriptionWithIndent:options:]
+ -[NSPJSONWebToken description]
+ -[NSPJSONWebToken encodedString]
+ -[NSPJSONWebToken headerSegment]
+ -[NSPJSONWebToken header]
+ -[NSPJSONWebToken initWithHeader:payload:]
+ -[NSPJSONWebToken initWithString:requireSignature:]
+ -[NSPJSONWebToken payloadSegment]
+ -[NSPJSONWebToken payload]
+ -[NSPJSONWebToken signatureData]
+ -[NSPJSONWebToken signatureVerified]
+ -[NSPJSONWebToken verifyWithKey:]
+ -[NSPPrivacyProxyAuxiliaryAuthInfo aggregatedCount]
+ -[NSPPrivacyProxyAuxiliaryAuthInfo hasAggregatedCount]
+ -[NSPPrivacyProxyAuxiliaryAuthInfo setAggregatedCount:]
+ -[NSPPrivacyProxyAuxiliaryAuthInfo setHasAggregatedCount:]
+ -[NSPPrivacyProxyCacheConfig batchSize]
+ -[NSPPrivacyProxyCacheConfig copyTo:]
+ -[NSPPrivacyProxyCacheConfig copyWithZone:]
+ -[NSPPrivacyProxyCacheConfig description]
+ -[NSPPrivacyProxyCacheConfig dictionaryRepresentation]
+ -[NSPPrivacyProxyCacheConfig hasBatchSize]
+ -[NSPPrivacyProxyCacheConfig hasLowWatermark]
+ -[NSPPrivacyProxyCacheConfig hash]
+ -[NSPPrivacyProxyCacheConfig isEqual:]
+ -[NSPPrivacyProxyCacheConfig lowWatermark]
+ -[NSPPrivacyProxyCacheConfig mergeFrom:]
+ -[NSPPrivacyProxyCacheConfig readFrom:]
+ -[NSPPrivacyProxyCacheConfig setBatchSize:]
+ -[NSPPrivacyProxyCacheConfig setHasBatchSize:]
+ -[NSPPrivacyProxyCacheConfig setHasLowWatermark:]
+ -[NSPPrivacyProxyCacheConfig setLowWatermark:]
+ -[NSPPrivacyProxyCacheConfig writeTo:]
+ -[NSPPrivacyProxyTokenIssuer hasTokenCacheConfig]
+ -[NSPPrivacyProxyTokenIssuer setTokenCacheConfig:]
+ -[NSPPrivacyProxyTokenIssuer tokenCacheConfig]
+ _NSPPrivacyProxyCacheConfigReadFrom
+ _OBJC_CLASS_$_NSPJSONWebToken
+ _OBJC_CLASS_$_NSPPrivacyProxyCacheConfig
+ _OBJC_CLASS_$_NSSortDescriptor
+ _OBJC_IVAR_$_NSPJSONWebToken._header
+ _OBJC_IVAR_$_NSPJSONWebToken._headerSegment
+ _OBJC_IVAR_$_NSPJSONWebToken._payload
+ _OBJC_IVAR_$_NSPJSONWebToken._payloadSegment
+ _OBJC_IVAR_$_NSPJSONWebToken._signatureData
+ _OBJC_IVAR_$_NSPJSONWebToken._signatureVerified
+ _OBJC_METACLASS_$_NSPJSONWebToken
+ _OBJC_METACLASS_$_NSPPrivacyProxyCacheConfig
+ __OBJC_$_CLASS_METHODS_NSPJSONWebToken
+ __OBJC_$_INSTANCE_METHODS_NSPJSONWebToken
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyCacheConfig
+ __OBJC_$_INSTANCE_VARIABLES_NSPJSONWebToken
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyCacheConfig
+ __OBJC_$_PROP_LIST_NSPJSONWebToken
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyCacheConfig
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyCacheConfig
+ __OBJC_CLASS_RO_$_NSPJSONWebToken
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyCacheConfig
+ __OBJC_METACLASS_RO_$_NSPJSONWebToken
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyCacheConfig
+ ___NSArray0__struct
+ _arc4random_uniform
CStrings:
+ "\t"
+ "%@.%@"
+ "%@.%@.%@"
+ "%s called with null (!requireSignature || segments.count >= 3)"
+ "%s called with null (jwtString.length > 0)"
+ "%s called with null (localWaitingTokens.count > 0)"
+ "%s called with null (segments.count >= 2 && segments.count <= 3)"
+ "%s called with null [NSJSONSerialization isValidJSONObject:header]"
+ "%s called with null [NSJSONSerialization isValidJSONObject:payload]"
+ "%s called with null [header isKindOfClass:[NSDictionary class]]"
+ "%s called with null [payload isKindOfClass:[NSDictionary class]]"
+ "+"
+ "-"
+ "-[NSPJSONWebToken initWithHeader:payload:]"
+ "-[NSPJSONWebToken initWithString:requireSignature:]"
+ "/"
+ "Header"
+ "Payload"
+ "_"
+ "aggregatedCount"
+ "batchSize"
+ "doubleValue"
+ "lowWatermark"
+ "tokenCacheConfig"
- "%s called with null (waitingTokenList.count > 0)"
```
