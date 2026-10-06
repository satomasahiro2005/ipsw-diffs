## Futhark

> `/System/Library/PrivateFrameworks/Futhark.framework/Futhark`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12cc8` | `0x12e90` | **`+0x1c8`** |
| `__TEXT.__const` | `0xcb0` | `0xc70` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x78` | `0x7c` | **`+0x4`** |

### Other Changes

```text
Functions:
~ -[FKTextFeature initWithType:boundingBox:corners:featureID:session:backingIndex:scale:] : 612 -> 608
~ +[FKTextFeature featureFromSequenceIndex:session:scaling:createConcompFeatures:createDiacriticFeatures:featureID:] : 1248 -> 1244
~ -[FKTextDetector setRecognitionLanguages:] : 384 -> 380
~ _createOrResetSessions : 208 -> 200
~ -[FKTextDetector dealloc] : 144 -> 148
~ -[FKTextDetector createFeaturesForROI:originalSize:lastID:] : 472 -> 468
~ -[FKTextDetector runRecognizerOnFeatures:roi:size:lastID:] : 712 -> 708
~ _sortSequencesInSensibleOrder : 1044 -> 1036
~ -[FKTextDetector detectFeaturesInBuffer:withRegionOfInterest:error:] : 1944 -> 1968
~ _runDetectionOnSession : 1432 -> 1424
~ -[FKTextDetector getMemoryUsageOfLastOperation] : 56 -> 68
~ _FKRecognizeGetCandidates : 1424 -> 1500
~ _extractCandidates : 788 -> 780
~ _scaleCC : 480 -> 488
~ _FKRecognizeSetLanguage : 108 -> 100
~ _FKRecognizeSequence : 3060 -> 3092
~ _rcAddDiacritics : 2480 -> 2484
~ _computeSpaceLimit : 480 -> 476
~ _checkSpaceOne : 408 -> 416
~ _rsRemoveBadWords : 724 -> 732
~ _FKSeqMatchGetConfidence : 336 -> 332
~ _getConfusionScoreForCC : 368 -> 372
~ _orderDiacriticToClusterCenters : 764 -> 752
~ _vUpdate : 656 -> 668
~ _trySplit : 3428 -> 3396
~ _splitCCIfGood : 2416 -> 2464
~ _calculatePenaltiesForBestPath : 476 -> 492
~ _getPathStats : 920 -> 936
~ _filterSplits : 1152 -> 1196
~ ___getPathStats_block_invoke : 1000 -> 996
~ _cutsCreateBadConcomp : 1412 -> 1428
~ _findEndBlackPixelRowInColumn : 128 -> 140
~ _combineSlash : 916 -> 928
~ _relativeYPosPercent : 340 -> 336
~ _FKSessionGetMemoryUsage : 132 -> 148
~ _FKSessionDestroyRecognizer : 128 -> 160
~ _FKThresholdCalculateOtsuLimit : 468 -> 456
~ _FKThresholdBlockAverage : 724 -> 692
~ _FKThresholdCalculateContrast : 168 -> 176
~ _FKThresholdMinMaxBlock : 2828 -> 2752
~ _FKComponentPrint : 472 -> 480
~ _FKConcompRelease : 212 -> 228
~ _FKConcompCreateSubConcomp : 1144 -> 1148
~ _FKComponentsFind : 1028 -> 1044
~ _createConcompFromLineseg : 804 -> 808
~ _FKSequenceRemoveConcomp : 196 -> 188
~ _FKSequenceSortAndProcess : 312 -> 320
~ _sequenceSetSlope : 764 -> 772
~ _sequenceMarkup : 1448 -> 1464
~ _FKSequencesReplaceConcomp : 236 -> 244
~ _FKSequencesFind : 6080 -> 6244
~ _sequenceLinkFreeList : 100 -> 104
~ _mergeNeighboringSequences : 840 -> 856
~ _sequenceRemove : 148 -> 156
~ _histogramIsOK : 592 -> 584
~ _computeBeta : 416 -> 424
~ _sequenceMerge : 224 -> 236
```
