## DistributedEvaluation

> `/System/Library/PrivateFrameworks/DistributedEvaluation.framework/DistributedEvaluation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e76c` | `0x1e6a0` | **`-0xcc`** |

### Other Changes

```diff
Symbols:
+ __ZNKSt9type_infoeqB9fqe220106ERKS_
+ __ZNSt3__110__function12__value_funcIFddEED2B9fqe220106Ev
+ __ZNSt3__125__throw_bad_function_callB9fqe220106Ev
- __ZNKSt9type_infoeqB9fqe220100ERKS_
- __ZNSt3__110__function12__value_funcIFddEED2B9fqe220100Ev
- __ZNSt3__125__throw_bad_function_callB9fqe220100Ev
Functions:
~ -[DESSparsification splitResultToChunksWithResult:recipe:baseKey:error:] : 2396 -> 2364
~ +[DESAdaptiveClipping computeClippingIndicator:clippingBound:scale:clippingIndicator:] : 704 -> 700
~ -[NSArray(DESExtensions) _fides_objectByReplacingValue:withValue:] : 352 -> 348
~ -[DESDediscoUploader donateResult:dediscoMetadata:recorder:] : 1764 -> 1760
~ -[DESDediscoUploader scaleData:withScalingFactor:] : 200 -> 196
~ +[DESDediscoUploader hasAllZeroData:] : 132 -> 128
~ -[DESDecimalEncoder encodeDecimalData:forKey:withSchemas:errorOut:] : 1716 -> 1712
~ +[DESJSONPredicate fetchObjectAtPath:from:] : 484 -> 480
~ +[DESJSONPredicate parsePath:] : 532 -> 528
~ +[DESJSONPredicate evaluateArrayOp:onObj:] : 616 -> 612
~ +[DESJSONPredicate evaluateAnd:onObj:] : 304 -> 300
~ +[DESJSONPredicate evaluateOr:onObj:] : 300 -> 296
~ -[DESCategoricalMetadataEncoder encodeNumber:toLength:] : 452 -> 448
~ -[DESCategoricalMetadataEncoder encodeStringVector:toLength:] : 416 -> 404
~ -[DESCategoricalMetadataEncoder encodeNumberVector:toLength:] : 600 -> 592
~ _GarbageCollectOldRecords : 956 -> 948
~ _GarbageCollectAllRecords : 832 -> 828
~ -[DESNumericStatsRecorder record:data:dataTypeContent:metadata:errorOut:] : 1216 -> 1200
~ +[DESFedStatsDataType extractFedStatsDataTypeFrom:forKey:] : 728 -> 724
~ -[DESGaussianAlgorithmParameters initWith:epsilon:delta:clippingBound:momentsAccountantParameters:] : 1376 -> 1372
~ -[DESGaussianAlgorithmParameters calculateAndVerifyPerChunkClippingBoundsIn:withOverallClippingBound:] : 624 -> 620
~ _DESSubmissionLogGarbageCollect : 1720 -> 1708
~ -[DESMetadataSchema initWith:key:attachments:error:] : 3076 -> 3072
~ +[DESSandBoxManager sandboxExtensionsToXPCConnection:fileURLs:requireWrite:outError:] : 896 -> 892
~ -[DESSandBoxManager consumeExtensionsWithError:] : 688 -> 684
~ -[DESSandBoxManager releaseExtensions] : 484 -> 480
~ -[DESDebugRecord description] : 592 -> 588
~ -[DESDodMLTaskSchedulingPolicy initWithPolicyDict:] : 2124 -> 2120
~ -[DESBinary32Transport writeTo:] : 164 -> 160
~ -[DESBinary64Transport writeTo:] : 164 -> 160
~ -[DESPFLNoisable writeTo:] : 484 -> 476
~ +[DESUserDefaultsStoreRecord purgeObsoleted] : 292 -> 288
~ +[DESAggregatableMetadata encodeMetadata:recipe:error:] : 3280 -> 3276
~ +[DESServiceAccess hasOnDemandLaunchEntitlement:] : 592 -> 588
```
