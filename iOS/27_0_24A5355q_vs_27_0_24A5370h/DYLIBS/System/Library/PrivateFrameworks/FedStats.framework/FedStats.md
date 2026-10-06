## FedStats

> `/System/Library/PrivateFrameworks/FedStats.framework/FedStats`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17a90` | `0x179e0` | **`-0xb0`** |

### Other Changes

```text
Functions:
~ +[FedStatsCategoricalTypeHuffmanEncoder instanceWithParameters:error:] : 3148 -> 3136
~ -[FedStatsCategoricalTypeHuffmanEncoder preEncode:] : 880 -> 876
~ -[FedStatsCategoricalTypeIPv4Encoder preEncode:] : 624 -> 620
~ -[FedStatsCategoricalTypeIPv6Encoder preEncode:] : 652 -> 648
~ -[FedStatsCategoricalTypeSampleTokenizer tokenize:] : 656 -> 652
~ -[FedStatsDataSampler addItems:] : 244 -> 240
~ -[NSError(FedStatsErrorStringify) describe] : 644 -> 640
~ +[FedStatsBucketedType createFromDict:possibleError:] : 1204 -> 1200
~ +[FedStatsCategoricalType createFromDict:possibleError:] : 5012 -> 4996
~ -[FedStatsCategoricalType encodeToIndex:possibleError:] : 1768 -> 1764
~ -[FedStatsCategoricalTypeAssetSpecifier parameters] : 472 -> 468
~ +[NSArray(FloatArithmetic) arrayWithData:] : 276 -> 292
~ -[NSArray(FloatArithmetic) arrayByScalingWith:] : 436 -> 432
~ +[NSData(FloatArrayInitializer) dataWithArray:] : 300 -> 296
~ -[NSDictionary(FlatDescription) flatDescription] : 444 -> 440
~ +[FedStatsUtils SHA1AsBitString:] : 264 -> 272
~ +[FedStatsUtils normL2:] : 360 -> 356
~ -[FedStatsCombinationType initWithCombinationSpec:] : 792 -> 784
~ +[FedStatsCombinationType createFromDict:possibleError:] : 1480 -> 1468
~ -[FedStatsCombinationType decodeFromIndex:possibleError:] : 836 -> 828
~ -[FedStatsCombinationType sampleForIndex:] : 476 -> 472
~ -[FedStatsGeoHashType encodeToIndex:possibleError:] : 504 -> 500
~ -[FedStatsGeoHashType decodeFromIndex:possibleError:] : 324 -> 320
~ -[FedStatsSQLiteCategoryDatabase encodeCategories:error:] : 828 -> 824
~ +[FedStatsSQLiteCategoryDatabase categoryDatabaseAt:withCategories:tableName:categoryColumnName:indexColumnName:error:] : 1156 -> 1152
~ -[FedStatsDataEncoder initWithDataTypes:combinationTypes:] : 732 -> 728
~ +[FedStatsDataEncoder createWithDataTypeContent:possibleError:] : 1996 -> 1968
~ -[FedStatsDataEncoder encodeToIndex:withType:error:] : 916 -> 912
~ -[FedStatsDataEncoder encodeToBitVector:withType:possibleError:] : 720 -> 716
~ -[FedStatsDataEncoder isVectorDimensionAllowed] : 336 -> 332
~ -[FedStatsDataEncoder encodeToBitVector:possibleError:] : 680 -> 676
~ -[FedStatsDataEncoder encodeToIndex:error:] : 824 -> 820
~ -[FedStatsDataEncoder encodeDataArray:error:] : 1624 -> 1612
~ +[FedStatsDataEncoder encodeDataArrayAndRecord:dataTypeContent:metadata:baseKey:errorOut:] : 3772 -> 3764
~ +[FedStatsDataEncoder mutateDataTypeContent:usingFieldValues:assetURLs:requiredFields:assetNames:error:] : 3948 -> 3952
~ +[FedStatsDataEncoder defaultDataPointForDataTypeContent:] : 420 -> 416
```
