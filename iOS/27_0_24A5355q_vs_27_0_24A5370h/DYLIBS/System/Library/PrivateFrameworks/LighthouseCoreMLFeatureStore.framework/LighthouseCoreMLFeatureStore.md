## LighthouseCoreMLFeatureStore

> `/System/Library/PrivateFrameworks/LighthouseCoreMLFeatureStore.framework/LighthouseCoreMLFeatureStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb63c` | `0xb57c` | **`-0xc0`** |

### Other Changes

```text
Functions:
~ +[LCFELCoreAnalyticsHandler emitFeatureStatisticEvents:usageType:batchProviderInfo:] : 2932 -> 2896
~ +[LCFELCoreAnalyticsHandler emitFeatureImportanceEvent:] : 2224 -> 2204
~ +[LCFELCoreAnalyticsHandler emitChangePointDetectionEvent:] : 2072 -> 2056
~ -[LCFFeatureStore getFeatureVector:atTime:option:] : 612 -> 608
~ -[LCFFeatureStore getFeatureVectorWithStoreEvents:storeEventsInReversedOrder:option:] : 1788 -> 1776
~ -[LCFFeatureStore getFeatureSets:startDate:endDate:option:] : 1156 -> 1144
~ -[LCFFeatureStore featureProviderFromfeatureSet:featureNames:] : 928 -> 924
~ -[LCFFeatureStore getFeatureVectors:startDate:endDate:option:] : 1820 -> 1796
~ -[LCFCoreMLBatchProvider init:featureProviders:] : 548 -> 544
~ -[LCFFeatureValue isNullValue] : 44 -> 48
~ +[LCFFeatureConverter(LabeledDataStore) fromLabeledDataBiomeFeatureStore:timestamp:] : 1008 -> 1004
~ +[LCFFeatureConverter(LabeledDataStore) fromFeatureSetToLabeledData:] : 1080 -> 1076
~ +[LCFCoreMLFeatureProviderUtils toMultiArrayTypeFeatureProvider:srcFeatureNames:srcLabelName:destFeatureName:destLabelName:] : 1492 -> 1484
~ -[LCFDatabaseConnection writeFeatures:] : 1200 -> 1192
~ -[LCFDatabaseConnection isDoubleArray:] : 444 -> 440
~ -[LCFDatabaseConnection query:startDate:endDate:reversed:] : 1564 -> 1556
~ +[LCFELBatchProviderInfo meanOf:] : 360 -> 356
~ +[LCFELBatchProviderInfo standardDeviationOf:] : 404 -> 400
~ -[LCFELBatchProviderInfo init:labelFeatureName:] : 2716 -> 2700
~ -[LCFDatabaseColumnConnection writeFeatures:featureValueType:] : 588 -> 584
```
