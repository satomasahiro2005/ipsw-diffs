## NetworkServiceProxy

> `/System/Library/PrivateFrameworks/NetworkServiceProxy.framework/NetworkServiceProxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63570` | `0x67310` | **`+0x3da0`** |
| `__AUTH_CONST.__objc_const` | `0x80e0` | `0x8660` | **`+0x580`** |
| `__TEXT.__objc_methlist` | `0x601c` | `0x654c` | **`+0x530`** |
| `__AUTH_CONST.__cfstring` | `0x51c0` | `0x5340` | **`+0x180`** |
| `__AUTH.__objc_data` | `0x1450` | `0x1590` | **`+0x140`** |
| `__DATA_CONST.__objc_selrefs` | `0x29f8` | `0x2b20` | **`+0x128`** |
| `__TEXT.__unwind_info` | `0x1228` | `0x1328` | **`+0x100`** |
| `__TEXT.__cstring` | `0x5ae2` | `0x5b9c` | **`+0xba`** |
| `__DATA_CONST.__const` | `0xc90` | `0xcd0` | **`+0x40`** |
| `__DATA_DIRTY.__objc_ivar` | `0x2dc` | `0x310` | **`+0x34`** |
| `__DATA_CONST.__objc_classlist` | `0x220` | `0x240` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x208` | `0x228` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x468` | `0x478` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x6d0` | `0x6c8` | **`-0x8`** |

### Other Changes

```diff

-985.0.0.0.0
+990.0.0.0.0

-  Functions: 2128
-  Symbols:   3303
-  CStrings:  1223
+  Functions: 2236
+  Symbols:   3446
+  CStrings:  1235
Symbols:
+ +[NSPPrivacyProxyDenominationResult tokenResponsesType]
+ +[NSPPrivacyProxyFailedExpiringTokens privacyPassTokensType]
+ +[NSPPrivacyProxyTokenRefundRequest denominationRequestsType]
+ +[NSPPrivacyProxyTokenRefundRequest privacyPassTokensType]
+ +[NSPPrivacyProxyTokenRefundResponse failedType]
+ +[NSPPrivacyProxyTokenRefundResponse resultsType]
+ -[NSPPrivacyProxyDenominationResult .cxx_destruct]
+ -[NSPPrivacyProxyDenominationResult StringAsStatus:]
+ -[NSPPrivacyProxyDenominationResult addTokenResponses:]
+ -[NSPPrivacyProxyDenominationResult clearTokenResponses]
+ -[NSPPrivacyProxyDenominationResult copyTo:]
+ -[NSPPrivacyProxyDenominationResult copyWithZone:]
+ -[NSPPrivacyProxyDenominationResult denominationIssuer]
+ -[NSPPrivacyProxyDenominationResult description]
+ -[NSPPrivacyProxyDenominationResult dictionaryRepresentation]
+ -[NSPPrivacyProxyDenominationResult hasDenominationIssuer]
+ -[NSPPrivacyProxyDenominationResult hasStatus]
+ -[NSPPrivacyProxyDenominationResult hash]
+ -[NSPPrivacyProxyDenominationResult isEqual:]
+ -[NSPPrivacyProxyDenominationResult mergeFrom:]
+ -[NSPPrivacyProxyDenominationResult readFrom:]
+ -[NSPPrivacyProxyDenominationResult setDenominationIssuer:]
+ -[NSPPrivacyProxyDenominationResult setHasStatus:]
+ -[NSPPrivacyProxyDenominationResult setStatus:]
+ -[NSPPrivacyProxyDenominationResult setTokenResponses:]
+ -[NSPPrivacyProxyDenominationResult statusAsString:]
+ -[NSPPrivacyProxyDenominationResult status]
+ -[NSPPrivacyProxyDenominationResult tokenResponsesAtIndex:]
+ -[NSPPrivacyProxyDenominationResult tokenResponsesCount]
+ -[NSPPrivacyProxyDenominationResult tokenResponses]
+ -[NSPPrivacyProxyDenominationResult writeTo:]
+ -[NSPPrivacyProxyFailedExpiringTokens .cxx_destruct]
+ -[NSPPrivacyProxyFailedExpiringTokens StringAsReason:]
+ -[NSPPrivacyProxyFailedExpiringTokens addPrivacyPassTokens:]
+ -[NSPPrivacyProxyFailedExpiringTokens clearPrivacyPassTokens]
+ -[NSPPrivacyProxyFailedExpiringTokens copyTo:]
+ -[NSPPrivacyProxyFailedExpiringTokens copyWithZone:]
+ -[NSPPrivacyProxyFailedExpiringTokens description]
+ -[NSPPrivacyProxyFailedExpiringTokens dictionaryRepresentation]
+ -[NSPPrivacyProxyFailedExpiringTokens hasReason]
+ -[NSPPrivacyProxyFailedExpiringTokens hasReusable]
+ -[NSPPrivacyProxyFailedExpiringTokens hash]
+ -[NSPPrivacyProxyFailedExpiringTokens isEqual:]
+ -[NSPPrivacyProxyFailedExpiringTokens mergeFrom:]
+ -[NSPPrivacyProxyFailedExpiringTokens privacyPassTokensAtIndex:]
+ -[NSPPrivacyProxyFailedExpiringTokens privacyPassTokensCount]
+ -[NSPPrivacyProxyFailedExpiringTokens privacyPassTokens]
+ -[NSPPrivacyProxyFailedExpiringTokens readFrom:]
+ -[NSPPrivacyProxyFailedExpiringTokens reasonAsString:]
+ -[NSPPrivacyProxyFailedExpiringTokens reason]
+ -[NSPPrivacyProxyFailedExpiringTokens reusable]
+ -[NSPPrivacyProxyFailedExpiringTokens setHasReason:]
+ -[NSPPrivacyProxyFailedExpiringTokens setHasReusable:]
+ -[NSPPrivacyProxyFailedExpiringTokens setPrivacyPassTokens:]
+ -[NSPPrivacyProxyFailedExpiringTokens setReason:]
+ -[NSPPrivacyProxyFailedExpiringTokens setReusable:]
+ -[NSPPrivacyProxyFailedExpiringTokens writeTo:]
+ -[NSPPrivacyProxyTokenRefundRequest .cxx_destruct]
+ -[NSPPrivacyProxyTokenRefundRequest addDenominationRequests:]
+ -[NSPPrivacyProxyTokenRefundRequest addPrivacyPassTokens:]
+ -[NSPPrivacyProxyTokenRefundRequest clearDenominationRequests]
+ -[NSPPrivacyProxyTokenRefundRequest clearPrivacyPassTokens]
+ -[NSPPrivacyProxyTokenRefundRequest copyTo:]
+ -[NSPPrivacyProxyTokenRefundRequest copyWithZone:]
+ -[NSPPrivacyProxyTokenRefundRequest denominationRequestsAtIndex:]
+ -[NSPPrivacyProxyTokenRefundRequest denominationRequestsCount]
+ -[NSPPrivacyProxyTokenRefundRequest denominationRequests]
+ -[NSPPrivacyProxyTokenRefundRequest description]
+ -[NSPPrivacyProxyTokenRefundRequest dictionaryRepresentation]
+ -[NSPPrivacyProxyTokenRefundRequest expiringTokenIssuerName]
+ -[NSPPrivacyProxyTokenRefundRequest hasExpiringTokenIssuerName]
+ -[NSPPrivacyProxyTokenRefundRequest hash]
+ -[NSPPrivacyProxyTokenRefundRequest isEqual:]
+ -[NSPPrivacyProxyTokenRefundRequest mergeFrom:]
+ -[NSPPrivacyProxyTokenRefundRequest privacyPassTokensAtIndex:]
+ -[NSPPrivacyProxyTokenRefundRequest privacyPassTokensCount]
+ -[NSPPrivacyProxyTokenRefundRequest privacyPassTokens]
+ -[NSPPrivacyProxyTokenRefundRequest readFrom:]
+ -[NSPPrivacyProxyTokenRefundRequest setDenominationRequests:]
+ -[NSPPrivacyProxyTokenRefundRequest setExpiringTokenIssuerName:]
+ -[NSPPrivacyProxyTokenRefundRequest setPrivacyPassTokens:]
+ -[NSPPrivacyProxyTokenRefundRequest writeTo:]
+ -[NSPPrivacyProxyTokenRefundResponse .cxx_destruct]
+ -[NSPPrivacyProxyTokenRefundResponse addFailed:]
+ -[NSPPrivacyProxyTokenRefundResponse addResults:]
+ -[NSPPrivacyProxyTokenRefundResponse clearFaileds]
+ -[NSPPrivacyProxyTokenRefundResponse clearResults]
+ -[NSPPrivacyProxyTokenRefundResponse copyTo:]
+ -[NSPPrivacyProxyTokenRefundResponse copyWithZone:]
+ -[NSPPrivacyProxyTokenRefundResponse description]
+ -[NSPPrivacyProxyTokenRefundResponse dictionaryRepresentation]
+ -[NSPPrivacyProxyTokenRefundResponse failedAtIndex:]
+ -[NSPPrivacyProxyTokenRefundResponse failedsCount]
+ -[NSPPrivacyProxyTokenRefundResponse faileds]
+ -[NSPPrivacyProxyTokenRefundResponse hash]
+ -[NSPPrivacyProxyTokenRefundResponse isEqual:]
+ -[NSPPrivacyProxyTokenRefundResponse mergeFrom:]
+ -[NSPPrivacyProxyTokenRefundResponse readFrom:]
+ -[NSPPrivacyProxyTokenRefundResponse resultsAtIndex:]
+ -[NSPPrivacyProxyTokenRefundResponse resultsCount]
+ -[NSPPrivacyProxyTokenRefundResponse results]
+ -[NSPPrivacyProxyTokenRefundResponse setFaileds:]
+ -[NSPPrivacyProxyTokenRefundResponse setResults:]
+ -[NSPPrivacyProxyTokenRefundResponse writeTo:]
+ _NSPPrivacyProxyDenominationResultReadFrom
+ _NSPPrivacyProxyFailedExpiringTokensReadFrom
+ _NSPPrivacyProxyTokenRefundRequestReadFrom
+ _NSPPrivacyProxyTokenRefundResponseReadFrom
+ _OBJC_CLASS_$_NSPPrivacyProxyDenominationResult
+ _OBJC_CLASS_$_NSPPrivacyProxyFailedExpiringTokens
+ _OBJC_CLASS_$_NSPPrivacyProxyTokenRefundRequest
+ _OBJC_CLASS_$_NSPPrivacyProxyTokenRefundResponse
+ _OBJC_METACLASS_$_NSPPrivacyProxyDenominationResult
+ _OBJC_METACLASS_$_NSPPrivacyProxyFailedExpiringTokens
+ _OBJC_METACLASS_$_NSPPrivacyProxyTokenRefundRequest
+ _OBJC_METACLASS_$_NSPPrivacyProxyTokenRefundResponse
+ __OBJC_$_CLASS_METHODS_NSPPrivacyProxyDenominationResult
+ __OBJC_$_CLASS_METHODS_NSPPrivacyProxyFailedExpiringTokens
+ __OBJC_$_CLASS_METHODS_NSPPrivacyProxyTokenRefundRequest
+ __OBJC_$_CLASS_METHODS_NSPPrivacyProxyTokenRefundResponse
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyDenominationResult
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyFailedExpiringTokens
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyTokenRefundRequest
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyTokenRefundResponse
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyDenominationResult
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyFailedExpiringTokens
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyTokenRefundRequest
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyTokenRefundResponse
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyDenominationResult
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyFailedExpiringTokens
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyTokenRefundRequest
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyTokenRefundResponse
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyDenominationResult
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyFailedExpiringTokens
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyTokenRefundRequest
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyTokenRefundResponse
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyDenominationResult
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyFailedExpiringTokens
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyTokenRefundRequest
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyTokenRefundResponse
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyDenominationResult
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyFailedExpiringTokens
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyTokenRefundRequest
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyTokenRefundResponse
- _os_variant_has_internal_content
CStrings:
+ "DENOMINATION_TOO_SMALL"
+ "FULFILLED"
+ "INSUFFICIENT_VALUE"
+ "INVALID_KEY"
+ "KEY_EXPIRED"
+ "SERVER_ERROR"
+ "denominationIssuer"
+ "denominationRequests"
+ "expiringTokenIssuerName"
+ "failed"
+ "privacyPassTokens"
+ "results"
```
