## HealthMedicationsVision

> `/System/Library/PrivateFrameworks/HealthMedicationsVision.framework/HealthMedicationsVision`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaba0` | `0xab30` | **`-0x70`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2
Functions:
~ -[HKMedicationsNumberToNumberPairListMap enumerateIntegersForKey:block:] : 372 -> 368
~ -[HKMedicationsResolutionEngine hkctl_resolveMedicationsUsing:resultLimit:error:] : 936 -> 932
~ -[HKMedicationsResolver processNgramLine:n:] : 884 -> 880
~ -[HKMedicationsResolver resolveText:error:] : 1276 -> 1264
~ -[HKMedicationsResolver filterAndAddGenerics:transcripts:criterion:limit:error:] : 1904 -> 1896
~ -[HKMedicationsResolver consecutiveLCSUsingTranscript:prediction:] : 416 -> 420
~ -[HKMedicationsTokenConceptResolver _collectAllMedicationCandidatesUsingTokens:] : 608 -> 604
~ -[HKMedicationsTokenConceptResolver _expandedMedicationsFromCandidates:] : 740 -> 736
~ -[HKMedicationsTokenConceptResolver removeMedicationsFromNoisyTokensUsingTokens:candidates:] : 1196 -> 1188
~ -[HKMedicationsTokenConceptResolver removeStowawayIngredientsUsingTokens:candidates:] : 756 -> 752
~ -[HKMedicationsTokenConceptResolver _tokenMatchScoreForMedication:usingTokens:] : 468 -> 464
~ +[HKMedicationsBarcodeExtractor extractedBarcodesFromRequestHandler:error:] : 512 -> 508
~ -[HKMedicationsImageFeatureExtractor extractFeaturesFrom:completionHandler:] : 916 -> 912
~ -[HKGenericMedicationSearchResult dictionaryRepresentation] : 504 -> 500
~ -[HKFullMedicationSearchResult dictionaryRepresentation] : 688 -> 684
~ +[HKMedicationsBarcodeNDCParser parsedNDCCodesFromCMSampleBuffer:error:] : 356 -> 352
~ +[HKMedicationsBarcodeNDCParser parsedGTIN14CodesFromCMSampleBuffer:error:] : 356 -> 352
~ -[HKMedicationsTextNDCParser parsedNDCCodeFromString:] : 920 -> 916
~ _HKTextBlockFromDocumentsClosestToPoint : 512 -> 508
~ -[HKMedicationsResolver checkLCSCriterion:transcripts:strings:normalizationType:tolerance:] : 564 -> 560
~ -[HKMedicationsResolver ngramsFrom:minLength:maxLength:] : 332 -> 328
~ -[HKMedicationsResolver fillNgramsForText:n:] : 264 -> 260
~ -[HKMedicationsResolver looksLikeGenericInText:] : 388 -> 384
~ -[HKMedicationsResolver abbreviate:] : 760 -> 752
~ -[HKMedicationsResolver updateIdGroup:ingredientMatched:tradeNameMatched:matchingTradeNames:] : 632 -> 628
```
