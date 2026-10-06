## ProactiveEventTracker

> `/System/Library/PrivateFrameworks/ProactiveEventTracker.framework/ProactiveEventTracker`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28a6c` | `0x28a14` | **`-0x58`** |

### Other Changes

```text
Functions:
~ +[PETEventStringValidator stringIsValid:] : 488 -> 484
~ ___lookupBlockCreatingIfNotExists_block_invoke : 928 -> 936
~ _getBucketPtr : 108 -> 104
~ ___80-[PETAggregateState updateDistributionWithValue:forKey:keyLength:maxSampleSize:]_block_invoke : 632 -> 636
~ ___57-[PET2LoggingOutlet _dispatchBatchForKey:value:isUpdate:]_block_invoke : 880 -> 872
~ _setBucketPtr : 136 -> 132
~ -[PETEventTracker _trackEvent:withPropertyValues:value:overwrite:] : 808 -> 804
~ +[PETEventStringValidator sanitizedString:] : 580 -> 572
~ -[PET2LoggingOutlet _findBucketsForKey:] : 324 -> 320
~ -[PETConfig bucketsForMessageName:] : 344 -> 340
~ +[PETConfigValidator configIsValid:] : 668 -> 664
~ +[PETConfigValidator _groupConfigIsValid:] : 1376 -> 1372
~ +[PETConfigValidator _messageConfigIsValid:] : 2112 -> 2100
~ _readVarint : 100 -> 104
~ -[PETEventEnumMappedProperty longestValueString] : 332 -> 328
~ -[PETEventStringValuedProperty longestValueString] : 328 -> 324
~ +[PETEventStringValidator dictionaryContainsValidStrings:] : 380 -> 376
~ +[PETEventStringValidator setContainsValidStrings:] : 272 -> 268
~ +[PETEventStringValidator sanitizedDictionary:] : 512 -> 508
~ +[PETEventStringValidator sanitizedSet:] : 368 -> 364
~ -[PETEventTracker _checkCardinalityForEvent:] : 408 -> 404
~ -[PETEventTracker _checkKeyLengthForEvent:metaData:] : 684 -> 680
~ -[PETEventTracker _checkPropertySubsets:] : 844 -> 840
~ -[PETUpload dictionaryRepresentation] : 872 -> 864
~ -[PETUpload writeTo:] : 592 -> 584
~ -[PETUpload copyWithZone:] : 680 -> 672
~ -[PETUpload mergeFrom:] : 604 -> 596
~ ___35+[PETAggregateState hashForString:]_block_invoke : 72 -> 80
~ _displayStringForKey : 128 -> 132
~ ___32-[PETAggregateState description]_block_invoke_2 : 404 -> 400
~ _visitDistribution : 828 -> 820
~ -[PETReservoirSamplingLog log:] : 512 -> 528
~ -[PETReservoirSamplingLog _gc] : 348 -> 372
~ -[PETEventTracker2 assertionWillInvalidate:] : 336 -> 332
~ -[PETEventTracker2 enumerateMessageGroups:] : 472 -> 468
~ -[PETStringPairs subsetForKeys:] : 472 -> 468
~ sub_29324c890 -> sub_29461e83c : 268 -> 264
```
