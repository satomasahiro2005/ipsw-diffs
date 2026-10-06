## NetworkServiceProxy

> `/System/Library/PrivateFrameworks/NetworkServiceProxy.framework/NetworkServiceProxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x581b8` | `0x60604` | **`+0x844c`** |
| `__AUTH_CONST.__objc_const` | `0x6f08` | `0x7ce0` | **`+0xdd8`** |
| `__TEXT.__objc_methlist` | `0x520c` | `0x5da4` | **`+0xb98`** |
| `__AUTH.__objc_data` | `0xff0` | `0x1360` | **`+0x370`** |
| `__AUTH_CONST.__cfstring` | `0x4d00` | `0x5000` | **`+0x300`** |
| `__DATA_CONST.__objc_selrefs` | `0x25a0` | `0x2888` | **`+0x2e8`** |
| `__TEXT.__unwind_info` | `0xf58` | `0x11a8` | **`+0x250`** |
| `__TEXT.__cstring` | `0x57f6` | `0x5997` | **`+0x1a1`** |
| `__DATA_CONST.__objc_classlist` | `0x1b8` | `0x210` | **`+0x58`** |
| `__DATA_CONST.__objc_superrefs` | `0x1a0` | `0x1f8` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x400` | `0x448` | **`+0x48`** |
| `__DATA_DIRTY.__objc_ivar` | `0x27c` | `0x2c0` | **`+0x44`** |
| `__DATA.__objc_ivar` | `0x2f0` | `0x31c` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0xc68` | `0xc90` | **`+0x28`** |
| `__TEXT.__const` | `0x370` | `0x368` | **`-0x8`** |

### Other Changes

```diff

-964.0.0.502.1
+974.0.0.0.0

-  Functions: 1833
-  Symbols:   2878
-  CStrings:  1167
+  Functions: 2074
+  Symbols:   3226
+  CStrings:  1193
Symbols:
+ +[NSPPrivacyProxyAggregatorConfig aggregatorServicesType]
+ +[NSPPrivacyProxyAggregatorService supportedUseCaseIdentifiersType]
+ +[NSPPrivacyProxyAggregatorTokenConfig denominationTokenConfigType]
+ +[NSPPrivacyProxyBlindRSARequests tokenRequestsType]
+ +[NSPPrivacyProxyBlindRSAResponse tokenResponsesType]
+ +[NSPPrivacyProxyCostJWTToBlindRSARequest blindRSARequestsType]
+ +[NSPPrivacyProxyCostJWTToBlindRSARequest costTokensType]
+ +[NSPPrivacyProxyCostJWTToBlindRSAResponse blindRSAResponsesType]
+ +[NSPPrivacyProxyCostJWTToBlindRSAResponse failedCostTokensType]
+ +[NSPPrivacyProxyFailedCostTokens costTokensType]
+ -[NSPPrivacyProxyAggregatorConfig .cxx_destruct]
+ -[NSPPrivacyProxyAggregatorConfig addAggregatorServices:]
+ -[NSPPrivacyProxyAggregatorConfig aggregatorServicesAtIndex:]
+ -[NSPPrivacyProxyAggregatorConfig aggregatorServicesCount]
+ -[NSPPrivacyProxyAggregatorConfig aggregatorServices]
+ -[NSPPrivacyProxyAggregatorConfig clearAggregatorServices]
+ -[NSPPrivacyProxyAggregatorConfig copyTo:]
+ -[NSPPrivacyProxyAggregatorConfig copyWithZone:]
+ -[NSPPrivacyProxyAggregatorConfig description]
+ -[NSPPrivacyProxyAggregatorConfig dictionaryRepresentation]
+ -[NSPPrivacyProxyAggregatorConfig hash]
+ -[NSPPrivacyProxyAggregatorConfig isEqual:]
+ -[NSPPrivacyProxyAggregatorConfig mergeFrom:]
+ -[NSPPrivacyProxyAggregatorConfig readFrom:]
+ -[NSPPrivacyProxyAggregatorConfig setAggregatorServices:]
+ -[NSPPrivacyProxyAggregatorConfig writeTo:]
+ -[NSPPrivacyProxyAggregatorRequest .cxx_destruct]
+ -[NSPPrivacyProxyAggregatorRequest copyTo:]
+ -[NSPPrivacyProxyAggregatorRequest copyWithZone:]
+ -[NSPPrivacyProxyAggregatorRequest costJWTToBlindRSARequest]
+ -[NSPPrivacyProxyAggregatorRequest description]
+ -[NSPPrivacyProxyAggregatorRequest dictionaryRepresentation]
+ -[NSPPrivacyProxyAggregatorRequest hasCostJWTToBlindRSARequest]
+ -[NSPPrivacyProxyAggregatorRequest hash]
+ -[NSPPrivacyProxyAggregatorRequest isEqual:]
+ -[NSPPrivacyProxyAggregatorRequest mergeFrom:]
+ -[NSPPrivacyProxyAggregatorRequest readFrom:]
+ -[NSPPrivacyProxyAggregatorRequest setCostJWTToBlindRSARequest:]
+ -[NSPPrivacyProxyAggregatorRequest writeTo:]
+ -[NSPPrivacyProxyAggregatorResponse .cxx_destruct]
+ -[NSPPrivacyProxyAggregatorResponse copyTo:]
+ -[NSPPrivacyProxyAggregatorResponse copyWithZone:]
+ -[NSPPrivacyProxyAggregatorResponse costJWTToBlindRSAResponse]
+ -[NSPPrivacyProxyAggregatorResponse description]
+ -[NSPPrivacyProxyAggregatorResponse dictionaryRepresentation]
+ -[NSPPrivacyProxyAggregatorResponse hasCostJWTToBlindRSAResponse]
+ -[NSPPrivacyProxyAggregatorResponse hash]
+ -[NSPPrivacyProxyAggregatorResponse isEqual:]
+ -[NSPPrivacyProxyAggregatorResponse mergeFrom:]
+ -[NSPPrivacyProxyAggregatorResponse readFrom:]
+ -[NSPPrivacyProxyAggregatorResponse setCostJWTToBlindRSAResponse:]
+ -[NSPPrivacyProxyAggregatorResponse writeTo:]
+ -[NSPPrivacyProxyAggregatorService .cxx_destruct]
+ -[NSPPrivacyProxyAggregatorService addSupportedUseCaseIdentifiers:]
+ -[NSPPrivacyProxyAggregatorService clearSupportedUseCaseIdentifiers]
+ -[NSPPrivacyProxyAggregatorService copyTo:]
+ -[NSPPrivacyProxyAggregatorService copyWithZone:]
+ -[NSPPrivacyProxyAggregatorService description]
+ -[NSPPrivacyProxyAggregatorService dictionaryRepresentation]
+ -[NSPPrivacyProxyAggregatorService hasServiceURL]
+ -[NSPPrivacyProxyAggregatorService hash]
+ -[NSPPrivacyProxyAggregatorService isEqual:]
+ -[NSPPrivacyProxyAggregatorService mergeFrom:]
+ -[NSPPrivacyProxyAggregatorService readFrom:]
+ -[NSPPrivacyProxyAggregatorService serviceURL]
+ -[NSPPrivacyProxyAggregatorService setServiceURL:]
+ -[NSPPrivacyProxyAggregatorService setSupportedUseCaseIdentifiers:]
+ -[NSPPrivacyProxyAggregatorService supportedUseCaseIdentifiersAtIndex:]
+ -[NSPPrivacyProxyAggregatorService supportedUseCaseIdentifiersCount]
+ -[NSPPrivacyProxyAggregatorService supportedUseCaseIdentifiers]
+ -[NSPPrivacyProxyAggregatorService writeTo:]
+ -[NSPPrivacyProxyAggregatorTokenConfig .cxx_destruct]
+ -[NSPPrivacyProxyAggregatorTokenConfig addDenominationTokenConfig:]
+ -[NSPPrivacyProxyAggregatorTokenConfig clearDenominationTokenConfigs]
+ -[NSPPrivacyProxyAggregatorTokenConfig copyTo:]
+ -[NSPPrivacyProxyAggregatorTokenConfig copyWithZone:]
+ -[NSPPrivacyProxyAggregatorTokenConfig denominationTokenConfigAtIndex:]
+ -[NSPPrivacyProxyAggregatorTokenConfig denominationTokenConfigsCount]
+ -[NSPPrivacyProxyAggregatorTokenConfig denominationTokenConfigs]
+ -[NSPPrivacyProxyAggregatorTokenConfig description]
+ -[NSPPrivacyProxyAggregatorTokenConfig dictionaryRepresentation]
+ -[NSPPrivacyProxyAggregatorTokenConfig hasMaxValue]
+ -[NSPPrivacyProxyAggregatorTokenConfig hash]
+ -[NSPPrivacyProxyAggregatorTokenConfig isEqual:]
+ -[NSPPrivacyProxyAggregatorTokenConfig maxValue]
+ -[NSPPrivacyProxyAggregatorTokenConfig mergeFrom:]
+ -[NSPPrivacyProxyAggregatorTokenConfig readFrom:]
+ -[NSPPrivacyProxyAggregatorTokenConfig setDenominationTokenConfigs:]
+ -[NSPPrivacyProxyAggregatorTokenConfig setHasMaxValue:]
+ -[NSPPrivacyProxyAggregatorTokenConfig setMaxValue:]
+ -[NSPPrivacyProxyAggregatorTokenConfig writeTo:]
+ -[NSPPrivacyProxyBlindRSARequests .cxx_destruct]
+ -[NSPPrivacyProxyBlindRSARequests addTokenRequests:]
+ -[NSPPrivacyProxyBlindRSARequests clearTokenRequests]
+ -[NSPPrivacyProxyBlindRSARequests copyTo:]
+ -[NSPPrivacyProxyBlindRSARequests copyWithZone:]
+ -[NSPPrivacyProxyBlindRSARequests description]
+ -[NSPPrivacyProxyBlindRSARequests dictionaryRepresentation]
+ -[NSPPrivacyProxyBlindRSARequests hasIssuerName]
+ -[NSPPrivacyProxyBlindRSARequests hash]
+ -[NSPPrivacyProxyBlindRSARequests isEqual:]
+ -[NSPPrivacyProxyBlindRSARequests issuerName]
+ -[NSPPrivacyProxyBlindRSARequests mergeFrom:]
+ -[NSPPrivacyProxyBlindRSARequests readFrom:]
+ -[NSPPrivacyProxyBlindRSARequests setIssuerName:]
+ -[NSPPrivacyProxyBlindRSARequests setTokenKeyID:]
+ -[NSPPrivacyProxyBlindRSARequests setTokenRequests:]
+ -[NSPPrivacyProxyBlindRSARequests tokenKeyID]
+ -[NSPPrivacyProxyBlindRSARequests tokenRequestsAtIndex:]
+ -[NSPPrivacyProxyBlindRSARequests tokenRequestsCount]
+ -[NSPPrivacyProxyBlindRSARequests tokenRequests]
+ -[NSPPrivacyProxyBlindRSARequests writeTo:]
+ -[NSPPrivacyProxyBlindRSAResponse .cxx_destruct]
+ -[NSPPrivacyProxyBlindRSAResponse addTokenResponses:]
+ -[NSPPrivacyProxyBlindRSAResponse clearTokenResponses]
+ -[NSPPrivacyProxyBlindRSAResponse copyTo:]
+ -[NSPPrivacyProxyBlindRSAResponse copyWithZone:]
+ -[NSPPrivacyProxyBlindRSAResponse description]
+ -[NSPPrivacyProxyBlindRSAResponse dictionaryRepresentation]
+ -[NSPPrivacyProxyBlindRSAResponse hasIssuerName]
+ -[NSPPrivacyProxyBlindRSAResponse hasStatus]
+ -[NSPPrivacyProxyBlindRSAResponse hash]
+ -[NSPPrivacyProxyBlindRSAResponse isEqual:]
+ -[NSPPrivacyProxyBlindRSAResponse issuerName]
+ -[NSPPrivacyProxyBlindRSAResponse mergeFrom:]
+ -[NSPPrivacyProxyBlindRSAResponse readFrom:]
+ -[NSPPrivacyProxyBlindRSAResponse setIssuerName:]
+ -[NSPPrivacyProxyBlindRSAResponse setStatus:]
+ -[NSPPrivacyProxyBlindRSAResponse setTokenResponses:]
+ -[NSPPrivacyProxyBlindRSAResponse status]
+ -[NSPPrivacyProxyBlindRSAResponse tokenResponsesAtIndex:]
+ -[NSPPrivacyProxyBlindRSAResponse tokenResponsesCount]
+ -[NSPPrivacyProxyBlindRSAResponse tokenResponses]
+ -[NSPPrivacyProxyBlindRSAResponse writeTo:]
+ -[NSPPrivacyProxyConfiguration aggregatorConfig]
+ -[NSPPrivacyProxyConfiguration hasAggregatorConfig]
+ -[NSPPrivacyProxyConfiguration setAggregatorConfig:]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest .cxx_destruct]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest addBlindRSARequests:]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest addCostTokens:]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest blindRSARequestsAtIndex:]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest blindRSARequestsCount]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest blindRSARequests]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest clearBlindRSARequests]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest clearCostTokens]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest copyTo:]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest copyWithZone:]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest costTokensAtIndex:]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest costTokensCount]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest costTokens]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest description]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest dictionaryRepresentation]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest hash]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest isEqual:]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest mergeFrom:]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest readFrom:]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest setBlindRSARequests:]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest setCostTokens:]
+ -[NSPPrivacyProxyCostJWTToBlindRSARequest writeTo:]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse .cxx_destruct]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse addBlindRSAResponses:]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse addFailedCostTokens:]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse blindRSAResponsesAtIndex:]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse blindRSAResponsesCount]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse blindRSAResponses]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse clearBlindRSAResponses]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse clearFailedCostTokens]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse copyTo:]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse copyWithZone:]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse description]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse dictionaryRepresentation]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse failedCostTokensAtIndex:]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse failedCostTokensCount]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse failedCostTokens]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse hash]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse isEqual:]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse mergeFrom:]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse readFrom:]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse setBlindRSAResponses:]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse setFailedCostTokens:]
+ -[NSPPrivacyProxyCostJWTToBlindRSAResponse writeTo:]
+ -[NSPPrivacyProxyDenominationTokenConfig .cxx_destruct]
+ -[NSPPrivacyProxyDenominationTokenConfig copyTo:]
+ -[NSPPrivacyProxyDenominationTokenConfig copyWithZone:]
+ -[NSPPrivacyProxyDenominationTokenConfig description]
+ -[NSPPrivacyProxyDenominationTokenConfig dictionaryRepresentation]
+ -[NSPPrivacyProxyDenominationTokenConfig hasIssuer]
+ -[NSPPrivacyProxyDenominationTokenConfig hasValue]
+ -[NSPPrivacyProxyDenominationTokenConfig hash]
+ -[NSPPrivacyProxyDenominationTokenConfig isEqual:]
+ -[NSPPrivacyProxyDenominationTokenConfig issuer]
+ -[NSPPrivacyProxyDenominationTokenConfig mergeFrom:]
+ -[NSPPrivacyProxyDenominationTokenConfig readFrom:]
+ -[NSPPrivacyProxyDenominationTokenConfig setHasValue:]
+ -[NSPPrivacyProxyDenominationTokenConfig setIssuer:]
+ -[NSPPrivacyProxyDenominationTokenConfig setValue:]
+ -[NSPPrivacyProxyDenominationTokenConfig value]
+ -[NSPPrivacyProxyDenominationTokenConfig writeTo:]
+ -[NSPPrivacyProxyFailedCostTokens .cxx_destruct]
+ -[NSPPrivacyProxyFailedCostTokens StringAsReason:]
+ -[NSPPrivacyProxyFailedCostTokens addCostTokens:]
+ -[NSPPrivacyProxyFailedCostTokens clearCostTokens]
+ -[NSPPrivacyProxyFailedCostTokens copyTo:]
+ -[NSPPrivacyProxyFailedCostTokens copyWithZone:]
+ -[NSPPrivacyProxyFailedCostTokens costTokensAtIndex:]
+ -[NSPPrivacyProxyFailedCostTokens costTokensCount]
+ -[NSPPrivacyProxyFailedCostTokens costTokens]
+ -[NSPPrivacyProxyFailedCostTokens description]
+ -[NSPPrivacyProxyFailedCostTokens dictionaryRepresentation]
+ -[NSPPrivacyProxyFailedCostTokens hasReason]
+ -[NSPPrivacyProxyFailedCostTokens hasReusable]
+ -[NSPPrivacyProxyFailedCostTokens hash]
+ -[NSPPrivacyProxyFailedCostTokens isEqual:]
+ -[NSPPrivacyProxyFailedCostTokens mergeFrom:]
+ -[NSPPrivacyProxyFailedCostTokens readFrom:]
+ -[NSPPrivacyProxyFailedCostTokens reasonAsString:]
+ -[NSPPrivacyProxyFailedCostTokens reason]
+ -[NSPPrivacyProxyFailedCostTokens reusable]
+ -[NSPPrivacyProxyFailedCostTokens setCostTokens:]
+ -[NSPPrivacyProxyFailedCostTokens setHasReason:]
+ -[NSPPrivacyProxyFailedCostTokens setHasReusable:]
+ -[NSPPrivacyProxyFailedCostTokens setReason:]
+ -[NSPPrivacyProxyFailedCostTokens setReusable:]
+ -[NSPPrivacyProxyFailedCostTokens writeTo:]
+ -[NSPPrivacyProxyResolverInfo hasProxyURLPath]
+ -[NSPPrivacyProxyResolverInfo proxyURLPath]
+ -[NSPPrivacyProxyResolverInfo setProxyURLPath:]
+ -[NSPPrivacyProxyTokenIssuer aggregatorTokenConfig]
+ -[NSPPrivacyProxyTokenIssuer hasAggregatorTokenConfig]
+ -[NSPPrivacyProxyTokenIssuer setAggregatorTokenConfig:]
+ _NSPPrivacyProxyAggregatorConfigReadFrom
+ _NSPPrivacyProxyAggregatorRequestReadFrom
+ _NSPPrivacyProxyAggregatorResponseReadFrom
+ _NSPPrivacyProxyAggregatorServiceReadFrom
+ _NSPPrivacyProxyAggregatorTokenConfigReadFrom
+ _NSPPrivacyProxyBlindRSARequestsReadFrom
+ _NSPPrivacyProxyBlindRSAResponseReadFrom
+ _NSPPrivacyProxyCostJWTToBlindRSARequestReadFrom
+ _NSPPrivacyProxyCostJWTToBlindRSAResponseReadFrom
+ _NSPPrivacyProxyDenominationTokenConfigReadFrom
+ _NSPPrivacyProxyFailedCostTokensReadFrom
+ _OBJC_CLASS_$_NSPPrivacyProxyAggregatorConfig
+ _OBJC_CLASS_$_NSPPrivacyProxyAggregatorRequest
+ _OBJC_CLASS_$_NSPPrivacyProxyAggregatorResponse
+ _OBJC_CLASS_$_NSPPrivacyProxyAggregatorService
+ _OBJC_CLASS_$_NSPPrivacyProxyAggregatorTokenConfig
+ _OBJC_CLASS_$_NSPPrivacyProxyBlindRSARequests
+ _OBJC_CLASS_$_NSPPrivacyProxyBlindRSAResponse
+ _OBJC_CLASS_$_NSPPrivacyProxyCostJWTToBlindRSARequest
+ _OBJC_CLASS_$_NSPPrivacyProxyCostJWTToBlindRSAResponse
+ _OBJC_CLASS_$_NSPPrivacyProxyDenominationTokenConfig
+ _OBJC_CLASS_$_NSPPrivacyProxyFailedCostTokens
+ _OBJC_IVAR_$_NSPPrivacyProxyAggregatorConfig._aggregatorServices
+ _OBJC_IVAR_$_NSPPrivacyProxyAggregatorRequest._costJWTToBlindRSARequest
+ _OBJC_IVAR_$_NSPPrivacyProxyAggregatorResponse._costJWTToBlindRSAResponse
+ _OBJC_IVAR_$_NSPPrivacyProxyAggregatorService._serviceURL
+ _OBJC_IVAR_$_NSPPrivacyProxyAggregatorService._supportedUseCaseIdentifiers
+ _OBJC_IVAR_$_NSPPrivacyProxyBlindRSARequests._issuerName
+ _OBJC_IVAR_$_NSPPrivacyProxyBlindRSARequests._tokenKeyID
+ _OBJC_IVAR_$_NSPPrivacyProxyBlindRSARequests._tokenRequests
+ _OBJC_IVAR_$_NSPPrivacyProxyBlindRSAResponse._issuerName
+ _OBJC_IVAR_$_NSPPrivacyProxyBlindRSAResponse._status
+ _OBJC_IVAR_$_NSPPrivacyProxyBlindRSAResponse._tokenResponses
+ _OBJC_METACLASS_$_NSPPrivacyProxyAggregatorConfig
+ _OBJC_METACLASS_$_NSPPrivacyProxyAggregatorRequest
+ _OBJC_METACLASS_$_NSPPrivacyProxyAggregatorResponse
+ _OBJC_METACLASS_$_NSPPrivacyProxyAggregatorService
+ _OBJC_METACLASS_$_NSPPrivacyProxyAggregatorTokenConfig
+ _OBJC_METACLASS_$_NSPPrivacyProxyBlindRSARequests
+ _OBJC_METACLASS_$_NSPPrivacyProxyBlindRSAResponse
+ _OBJC_METACLASS_$_NSPPrivacyProxyCostJWTToBlindRSARequest
+ _OBJC_METACLASS_$_NSPPrivacyProxyCostJWTToBlindRSAResponse
+ _OBJC_METACLASS_$_NSPPrivacyProxyDenominationTokenConfig
+ _OBJC_METACLASS_$_NSPPrivacyProxyFailedCostTokens
+ __OBJC_$_CLASS_METHODS_NSPPrivacyProxyAggregatorConfig
+ __OBJC_$_CLASS_METHODS_NSPPrivacyProxyAggregatorService
+ __OBJC_$_CLASS_METHODS_NSPPrivacyProxyAggregatorTokenConfig
+ __OBJC_$_CLASS_METHODS_NSPPrivacyProxyBlindRSARequests
+ __OBJC_$_CLASS_METHODS_NSPPrivacyProxyBlindRSAResponse
+ __OBJC_$_CLASS_METHODS_NSPPrivacyProxyCostJWTToBlindRSARequest
+ __OBJC_$_CLASS_METHODS_NSPPrivacyProxyCostJWTToBlindRSAResponse
+ __OBJC_$_CLASS_METHODS_NSPPrivacyProxyFailedCostTokens
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyAggregatorConfig
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyAggregatorRequest
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyAggregatorResponse
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyAggregatorService
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyAggregatorTokenConfig
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyBlindRSARequests
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyBlindRSAResponse
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyCostJWTToBlindRSARequest
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyCostJWTToBlindRSAResponse
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyDenominationTokenConfig
+ __OBJC_$_INSTANCE_METHODS_NSPPrivacyProxyFailedCostTokens
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyAggregatorConfig
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyAggregatorRequest
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyAggregatorResponse
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyAggregatorService
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyAggregatorTokenConfig
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyBlindRSARequests
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyBlindRSAResponse
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyCostJWTToBlindRSARequest
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyCostJWTToBlindRSAResponse
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyDenominationTokenConfig
+ __OBJC_$_INSTANCE_VARIABLES_NSPPrivacyProxyFailedCostTokens
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyAggregatorConfig
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyAggregatorRequest
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyAggregatorResponse
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyAggregatorService
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyAggregatorTokenConfig
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyBlindRSARequests
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyBlindRSAResponse
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyCostJWTToBlindRSARequest
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyCostJWTToBlindRSAResponse
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyDenominationTokenConfig
+ __OBJC_$_PROP_LIST_NSPPrivacyProxyFailedCostTokens
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyAggregatorConfig
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyAggregatorRequest
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyAggregatorResponse
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyAggregatorService
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyAggregatorTokenConfig
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyBlindRSARequests
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyBlindRSAResponse
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyCostJWTToBlindRSARequest
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyCostJWTToBlindRSAResponse
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyDenominationTokenConfig
+ __OBJC_CLASS_PROTOCOLS_$_NSPPrivacyProxyFailedCostTokens
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyAggregatorConfig
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyAggregatorRequest
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyAggregatorResponse
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyAggregatorService
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyAggregatorTokenConfig
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyBlindRSARequests
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyBlindRSAResponse
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyCostJWTToBlindRSARequest
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyCostJWTToBlindRSAResponse
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyDenominationTokenConfig
+ __OBJC_CLASS_RO_$_NSPPrivacyProxyFailedCostTokens
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyAggregatorConfig
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyAggregatorRequest
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyAggregatorResponse
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyAggregatorService
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyAggregatorTokenConfig
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyBlindRSARequests
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyBlindRSAResponse
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyCostJWTToBlindRSARequest
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyCostJWTToBlindRSAResponse
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyDenominationTokenConfig
+ __OBJC_METACLASS_RO_$_NSPPrivacyProxyFailedCostTokens
CStrings:
+ "-[NSPPrivacyProxyBlindRSARequests writeTo:]"
+ "AD_ATTRIBUTION"
+ "Ad Attribution"
+ "COST_JWT"
+ "EXPIRED"
+ "INVALID"
+ "NSPPrivacyProxyBlindRSARequests.m"
+ "PRIVACY_PASS_TOKEN"
+ "REPLAYED"
+ "UNSPENT"
+ "aggregatorConfig"
+ "aggregatorServices"
+ "aggregatorTokenConfig"
+ "blindRSARequests"
+ "blindRSAResponses"
+ "costJWTToBlindRSARequest"
+ "costJWTToBlindRSAResponse"
+ "costTokens"
+ "denominationTokenConfig"
+ "failedCostTokens"
+ "issuer"
+ "maxValue"
+ "reason"
+ "reusable"
+ "status"
+ "tokenRequests"
+ "tokenResponses"
+ "value"
- "ATHM_TOKEN"
- "OAI_COST_JWT"
```
