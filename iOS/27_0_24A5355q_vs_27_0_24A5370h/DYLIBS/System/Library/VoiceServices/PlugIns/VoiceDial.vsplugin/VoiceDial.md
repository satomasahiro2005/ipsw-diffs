## VoiceDial

> `/System/Library/VoiceServices/PlugIns/VoiceDial.vsplugin/VoiceDial`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa738` | `0xa714` | **`-0x24`** |

### Other Changes

```diff

-3060.100.14.2.1
+3064.100.8.0.0
Functions:
~ -[VoiceDialResultHandler _phoneticNames:fromDictionary:] : 412 -> 408
~ -[VoiceDialResultHandler actionForRecognitionResults:] : 7256 -> 7292
~ _VoiceDialMaidenNameDataSourceCreateMaidenNameFromLastName : 1216 -> 1204
~ __IsNamePrefixString : 288 -> 284
~ _VoiceDialCopyNamesLabelAndTypeFromRecognitionResults : 484 -> 480
~ _VoiceDialCopyMostLikelyNumberWithPersonAndLabel : 572 -> 560
~ _VoiceDialGetMostLikelyFacetimeContactWithPersonAndLabel : 940 -> 920
~ -[NSDictionary(VoiceDialResultHandlerMerge) mergeSetValuesIntoArray] : 352 -> 348
~ -[VoiceDialDataProvider getLabels:andWeightedLabels:ForABProperty:] : 1740 -> 1732
~ -[VoiceDialDataProvider getValue:weight:atIndex:forClassWithIdentifier:inModelWithIdentifier:] : 428 -> 424
```
