## PersonalizedSensingService

> `/System/Library/PrivateFrameworks/PersonalizedSensing.framework/XPCServices/PersonalizedSensingService.xpc/PersonalizedSensingService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x139678` | `0x138ecc` | **`-0x7ac`** |
| `__TEXT.__cstring` | `0xeff0` | `0xecf0` | **`-0x300`** |
| `__DATA_CONST.__cfstring` | `0xecc0` | `0xeae0` | **`-0x1e0`** |
| `__TEXT.__objc_stubs` | `0xb240` | `0xb200` | **`-0x40`** |
| `__DATA.__objc_selrefs` | `0x3c50` | `0x3c40` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x135fa` | `0x1360a` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3778` | `0x3768` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xd00` | `0xcf8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Symbols:   15609
-  CStrings:  6083
+  Symbols:   15606
+  CStrings:  6085
Symbols:
+ -[MOEventBundleRankingInput peopleCountMaxNormalized]
+ -[MOEventBundleRankingInput peopleCountWeightedAverageNormalized]
+ -[MOEventBundleRankingInput peopleCountWeightedSumNormalized]
+ -[MOEventBundleRankingInput setPeopleCountMaxNormalized:]
+ -[MOEventBundleRankingInput setPeopleCountWeightedAverageNormalized:]
+ -[MOEventBundleRankingInput setPeopleCountWeightedSumNormalized:]
+ OBJC_IVAR_$_MOEventBundleRankingInput._peopleCountMaxNormalized
+ OBJC_IVAR_$_MOEventBundleRankingInput._peopleCountWeightedAverageNormalized
+ OBJC_IVAR_$_MOEventBundleRankingInput._peopleCountWeightedSumNormalized
+ _objc_msgSend$peopleCountMaxNormalized
+ _objc_msgSend$peopleCountWeightedAverageNormalized
+ _objc_msgSend$peopleCountWeightedSumNormalized
+ _objc_msgSend$setPeopleCountMaxNormalized:
+ _objc_msgSend$setPeopleCountWeightedAverageNormalized:
+ _objc_msgSend$setPeopleCountWeightedSumNormalized:
- -[MOEventBundleRankingInput pCountMaxNormalized]
- -[MOEventBundleRankingInput pCountWeightedAverageNormalized]
- -[MOEventBundleRankingInput pCountWeightedSumNormalized]
- -[MOEventBundleRankingInput setPCountMaxNormalized:]
- -[MOEventBundleRankingInput setPCountWeightedAverageNormalized:]
- -[MOEventBundleRankingInput setPCountWeightedSumNormalized:]
- OBJC_IVAR_$_MOEventBundleRankingInput._pCountMaxNormalized
- OBJC_IVAR_$_MOEventBundleRankingInput._pCountWeightedAverageNormalized
- OBJC_IVAR_$_MOEventBundleRankingInput._pCountWeightedSumNormalized
- _OBJC_CLASS_$_NSAssertionHandler
- _objc_msgSend$currentHandler
- _objc_msgSend$handleFailureInMethod:object:file:lineNumber:description:
- _objc_msgSend$pCountMaxNormalized
- _objc_msgSend$pCountWeightedAverageNormalized
- _objc_msgSend$pCountWeightedSumNormalized
- _objc_msgSend$setPCountMaxNormalized:
- _objc_msgSend$setPCountWeightedAverageNormalized:
- _objc_msgSend$setPCountWeightedSumNormalized:
Functions:
~ -[MODefaultsManager objectForKey:] : 332 -> 248
~ -[MODefaultsManager objectForKeyWithoutLog:] : 260 -> 164
~ -[MODefaultsManager deleteObjectForKey:] : 312 -> 236
~ -[MODefaultsManager setObject:forKey:] : 348 -> 264
~ -[MODefaultsManager setObjectWithoutLog:forKey:] : 216 -> 100
~ -[MOEventBundleLabelFormat initWithFormat:capitalizationType:] : 268 -> 200
~ +[MODictionaryEncoder encodeDictionary:] : 408 -> 320
~ +[MODictionaryEncoder decodeToDictionary:] : 408 -> 320
~ -[MOResource initWithIdentifier:] : 248 -> 172
~ +[MOPlatformInfo isSeedBuild] : 8 -> 112
~ -[MOEventBundleLabelTemplate initWithConditionStrings:labels:context:] : 336 -> 276
~ -[MOEventBundleLabelTemplate initWithConditions:labels:context:] : 520 -> 460
~ -[MOEventBundleLabelTemplate initWithConditions:formats:context:] : 324 -> 264
~ +[MOEventBundleLabelLocalizer _Moments_LocalizedStringForKey:withTable:] : 668 -> 604
~ +[MOEventBundleLabelLocalizer _Moments_LocalizedStringWithFormat:arguments:] : 952 -> 884
~ -[MOTime initWithIdentifier:] : 288 -> 204
~ -[MOPlace initWithIdentifier:] : 268 -> 192
~ -[MOEventBundleRanking initWithUniverse:] : 232 -> 164
~ -[MOEventBundleRanking initWithConfigurationManager:] : 17140 -> 17080
~ -[MOEventBundleRanking _calculateRankingScore:withMinRecommendedBundleCountRequirement:] : 31368 -> 31272
~ -[MOEventBundleRanking _mergeScoresToBundles:usingScore:] : 1776 -> 1664
~ -[MOEventBundleRanking _submitEventBundleRankingAnalytics:withRankingInput:andSubmissionDate:] : 8980 -> 8852
~ -[MOEventBundleRanking updateTripMetaDataForRank:] : 1200 -> 1036
~ -[MOStringArrayTransformer transformedValue:] : 380 -> 284
~ -[MOStringArrayTransformer reverseTransformedValue:] : 352 -> 256
CStrings:
+ "PlatformInfoOverrideIsSeedBuild"
+ "Tf,N,V_peopleCountMaxNormalized"
+ "Tf,N,V_peopleCountWeightedAverageNormalized"
+ "Tf,N,V_peopleCountWeightedSumNormalized"
+ "_peopleCountMaxNormalized"
+ "_peopleCountWeightedAverageNormalized"
+ "_peopleCountWeightedSumNormalized"
+ "peopleCountMaxNormalized"
+ "peopleCountWeightedAverageNormalized"
+ "peopleCountWeightedSumNormalized"
+ "setPeopleCountMaxNormalized:"
+ "setPeopleCountWeightedAverageNormalized:"
+ "setPeopleCountWeightedSumNormalized:"
- "Tf,N,V_pCountMaxNormalized"
- "Tf,N,V_pCountWeightedAverageNormalized"
- "Tf,N,V_pCountWeightedSumNormalized"
- "_pCountMaxNormalized"
- "_pCountWeightedAverageNormalized"
- "_pCountWeightedSumNormalized"
- "currentHandler"
- "handleFailureInMethod:object:file:lineNumber:description:"
- "setPCountMaxNormalized:"
- "setPCountWeightedAverageNormalized:"
- "setPCountWeightedSumNormalized:"
```
