## networkserviceproxy

> `/usr/libexec/networkserviceproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbcd34` | `0xc17fc` | **`+0x4ac8`** |
| `__TEXT.__oslogstring` | `0x11036` | `0x11613` | **`+0x5dd`** |
| `__TEXT.__objc_stubs` | `0xcc80` | `0xd200` | **`+0x580`** |
| `__TEXT.__objc_methname` | `0xffe0` | `0x103e2` | **`+0x402`** |
| `__TEXT.__gcc_except_tab` | `0x3554` | `0x3828` | **`+0x2d4`** |
| `__TEXT.__cstring` | `0xdd4b` | `0xdeda` | **`+0x18f`** |
| `__DATA.__objc_selrefs` | `0x39d0` | `0x3b28` | **`+0x158`** |
| `__DATA_CONST.__cfstring` | `0x8ae0` | `0x8ba0` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x2250` | `0x22e0` | **`+0x90`** |
| `__DATA.__objc_const` | `0xb0f8` | `0xb158` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1968` | `0x19b8` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x810` | `0x848` | **`+0x38`** |
| `__TEXT.__const` | `0x285` | `0x2a0` | **`+0x1b`** |
| `__TEXT.__objc_methlist` | `0x5034` | `0x5044` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x2a69` | `0x2a77` | **`+0xe`** |
| `__DATA.__objc_ivar` | `0x9f0` | `0x9fc` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-976.0.0.0.0
+980.0.0.0.0

-  Functions: 2150
-  Symbols:   638
-  CStrings:  6229
+  Functions: 2161
+  Symbols:   645
+  CStrings:  6312
Symbols:
+ _OBJC_CLASS_$_NSMapTable
+ _OBJC_CLASS_$_NSPJSONWebToken
+ _OBJC_CLASS_$_NSPPrivacyProxyAggregatorRequest
+ _OBJC_CLASS_$_NSPPrivacyProxyAggregatorResponse
+ _OBJC_CLASS_$_NSPPrivacyProxyBlindRSARequests
+ _OBJC_CLASS_$_NSPPrivacyProxyCostJWTToBlindRSARequest
+ _OBJC_CLASS_$_NSValue
CStrings:
+ "%s called with null (localWaitingTokens.count > 0)"
+ "%s called with null issuer"
+ "-[NSPServer enqueuePendingTokenAggregationForCacheKey:issuer:]"
+ "?0@"
+ "@32@0:8d16@24"
+ "Adding Cost JWT %@"
+ "Aggregating %u cost tokens (total value %f) for issuer %@ via %@"
+ "Arming token aggregation timer to fire in %u seconds"
+ "Configuration has no aggregator config for issuer %@"
+ "Cost JWT bucketized_cost_unit (%.2f) exceeds maxValue (%.2f) for issuer %@"
+ "Cost JWT for issuer %@ has unexpected type for bucketized_cost_unit"
+ "Cost JWT for issuer %@ missing bucketized_cost_unit"
+ "Cost JWT for issuer %@: bucketized_cost_unit=%.2f maxValue=%.2f remainder=%.2f"
+ "Cost JWT issuer %@ has no aggregator token config"
+ "CostTokenAggregation"
+ "Could not parse aggregator URL %@"
+ "Failed to create token aggregation timer"
+ "Failed to parse cost JWT, cannot add auxiliary authentication data to cache"
+ "Failed to parse token aggregator response from %@"
+ "No aggregator service found for issuer %@"
+ "No aggregator token config found for issuer %@"
+ "Requesting %u tokens of denomination value %@ from aggregator"
+ "Saving %u activated tokens from aggregator"
+ "Sending %u auxiliary tokens from aggregator for %@"
+ "Sending auxiliary data for %@"
+ "Stale on-disk config disk version (%ld is not current); clearing etag at load to force refetch"
+ "Token aggregation timer fired"
+ "Token aggregator batch %u status: %@"
+ "Token aggregator received HTTP response code %ld for %@ with request UUID %@"
+ "Token aggregator reported %u failed cost tokens (reason %d, reusable %d)"
+ "Token aggregator request to %@ failed with error %@"
+ "Token aggregator request to %@ returned no data"
+ "Token aggregator summary for %@: aggregated %u cost JWTs (value %f); rejected %lu (reusable %lu value %f, lost %lu value %f)"
+ "TokenAggregationDate"
+ "TokenAggregatorFetch"
+ "Too few tokens to aggregate (%u/%u), skipping"
+ "_pendingTokenAggregations"
+ "_tokenAggregationDate"
+ "_tokenAggregationTimer"
+ "addBlindRSARequests:"
+ "addCostTokens:"
+ "addTokenRequests:"
+ "aggregateTokensForIssuer:forCacheKey:aggregator:aggregatorTokenConfig:attesterConfigs:completionHandler:"
+ "aggregatedCount"
+ "aggregatorServices"
+ "aggregatorTokenConfig"
+ "batchSize"
+ "blindRSAResponses"
+ "bucketized_cost_unit"
+ "com.apple.NetworkServiceProxy.AuxiliaryAuth.Aggregator"
+ "com.apple.NetworkServiceProxy.AuxiliaryAuth.OriginNeedsAggregation"
+ "com.apple.networkserviceproxy.tokenAggregationTimerFired"
+ "com.apple.networkserviceproxy.tokenAggregator"
+ "costJWTToBlindRSARequest"
+ "costJWTToBlindRSAResponse"
+ "costTokens"
+ "dataUsingEncoding:"
+ "denominationTokenConfigs"
+ "encodedString"
+ "exchangeObjectAtIndex:withObjectAtIndex:"
+ "failedCostTokens"
+ "hasAggregatedCount"
+ "hasAggregatorTokenConfig"
+ "hasCostJWTToBlindRSAResponse"
+ "hasTokenCacheConfig"
+ "indexOfObject:"
+ "initWithString:requireSignature:"
+ "isEqualToNumber:"
+ "lowWatermark"
+ "mapTableWithKeyOptions:valueOptions:"
+ "maxValue"
+ "pat_issuer"
+ "payload"
+ "rangeValue"
+ "removeObjectsInRange:"
+ "reusable"
+ "selectDenominationTokensToRequestForCostTokenTotal:denominationValues:"
+ "setAggregatedCount:"
+ "setCostJWTToBlindRSARequest:"
+ "setIssuerName:"
+ "sortUsingDescriptors:"
+ "sortedArrayUsingDescriptors:"
+ "subarrayWithRange:"
+ "tokenCacheConfig"
+ "tokenResponses"
+ "valueWithRange:"
- "%s called with null (waitingTokenList.count > 0)"
- "Configuration disk version changed, forcing a configuration fetch"
- "Sending auxiliary data with for %@"
```
