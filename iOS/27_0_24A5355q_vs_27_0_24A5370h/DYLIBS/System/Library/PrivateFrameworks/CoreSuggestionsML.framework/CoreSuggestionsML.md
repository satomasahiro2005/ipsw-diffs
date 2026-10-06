## CoreSuggestionsML

> `/System/Library/PrivateFrameworks/CoreSuggestionsML.framework/CoreSuggestionsML`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x318f4` | `0x317dc` | **`-0x118`** |

### Other Changes

```diff

-1331.0.1.0.0
+1334.0.1.0.0
Functions:
~ +[SGModelHyperparameters strategyForString:modelTypeName:] : 340 -> 336
~ +[SGQuickResponsesReplyModel semanticClassesForArray:] : 1056 -> 1052
~ +[SGQuickResponsesRepliesFlattened countReplyTextsForArray:] : 440 -> 436
~ +[SGQuickResponsesRepliesFlattened normalizedReplyTextsSetForArray:] : 688 -> 684
~ +[SGQuickResponsesRepliesNested nestedArrayFromModels:] : 316 -> 312
~ +[SGQuickResponsesRepliesNested nestedArrayFromFlatArray:nestedIndexes:] : 520 -> 516
~ +[SGQuickResponsesRepliesNested isZeroBasedAndContiguous:] : 492 -> 488
~ +[SGQuickResponsesRepliesNested replyModelsForArray:] : 764 -> 760
~ +[SGQuickResponsesRepliesNested subclassesFromClasses:subclassArray:] : 1116 -> 1112
~ +[SGQuickResponsesRepliesNested selectedPseudocountsFromModels:] : 316 -> 312
~ -[SGQuickResponsesConfig initWithLanguage:mode:dictionary:lazyVocab:] : 3000 -> 2992
~ +[SGModelAsset _invokeOnUpdateBlock] : 324 -> 320
~ +[SGNestedArray traversalWithNestedArray:depthCallback:itemCallback:] : 888 -> 884
~ +[SGQuickResponsesReplyOption totalDisplayedCountForRecords:] : 272 -> 268
~ +[SGQuickResponsesReplyOption imputedDisplayedForRecords:config:] : 452 -> 448
~ -[SGQuickResponsesPersonalization sortedReplyPositionsForSemanticClass:config:] : 568 -> 564
~ +[SGQuickResponsesPersonalization deduplicatedReplyTextsForReplyPositions:semanticClass:responseCount:config:] : 1040 -> 1036
~ -[SGQuickResponsesPersonalization registerDisplayedResponses:config:] : 532 -> 528
~ -[SGStringPreprocessingTransformer transformBatch:] : 652 -> 644
~ -[SGStringPreprocessor separateCharacter:withValue:] : 888 -> 892
~ -[SGStringPreprocessor separateFrenchElisions:] : 768 -> 760
~ -[SGStringPreprocessor removeDuplicateWhitespace:] : 572 -> 568
~ -[SGStringPreprocessor replaceLinksWithString:withValue:] : 876 -> 864
~ -[SGStringPreprocessor removeNonBasicMultilingualPlane:] : 552 -> 540
~ -[SGStringPreprocessor replaceAllWhitespaceWithSpaces:] : 488 -> 484
~ -[SGStringPreprocessor transformHalfwidthToFullwidthCJK:] : 592 -> 584
~ -[SGStringPreprocessor combineDakutenAndHandakuten:] : 868 -> 840
~ +[SGQuickResponsesInference stringsForQuickResponses:] : 328 -> 324
~ -[SGQuickResponsesInference quickResponsesForMessage:maximumResponses:conversationHistory:context:time:language:locale:recipients:useContactNames:includeCustomResponses:includeResponsesToRobots:] : 3700 -> 3696
~ -[SGQuickResponsesInference replyPositionsFromSemanticClasses:config:] : 852 -> 844
~ -[SGQuickResponsesInference randomizedReplyPositionsForSemanticClass:responseCount:config:] : 860 -> 856
~ -[SGQuickResponsesInference quickResponsesFromReplyPositions:isConfident:config:] : 1252 -> 1244
~ -[SGQuickResponsesInference addCustomResponsesToCommonResponses:language:locale:recipient:modelScores:maxResponses:customResponsesParams:] : 1160 -> 1156
~ -[SGModelSampler shouldSampleForLabel:isDynamicLabel:] : 136 -> 132
~ ___55-[SGQuickResponsesStore _recordsForResponses:language:]_block_invoke : 940 -> 936
~ ___58-[SGQuickResponsesStore addDisplayedToResponses:language:]_block_invoke_2 : 580 -> 576
~ ___63-[SGQuickResponsesStore addWrittenToResponse:language:isMatch:]_block_invoke : 388 -> 384
~ -[SGQuickResponsesStore filterBatchWithMinimumDistinctRecipients:minimumReplyOccurences:] : 784 -> 780
~ -[SGQuickResponsesStore prunePerRecipientTableWithMaxRows:] : 1640 -> 1632
~ -[SGQuickResponsesStore nearestCustomResponsesAndScoresToPromptEmbedding:recipient:limit:withinRadius:responseCountExponent:minimumDecayedCount:compatibilityVersion:language:locale:allowProfanity:minimumTimeInterval:usageSpreadExponent:] : 1888 -> 1884
~ -[SGQuickResponsesStore nearestCustomResponsesToPromptEmbedding:recipient:limit:withinRadius:responseCountExponent:minimumDecayedCount:compatibilityVersion:language:locale:allowProfanity:minimumTimeInterval:usageSpreadExponent:] : 328 -> 324
~ +[SGQuickResponsesStore isProfane:inLocales:] : 316 -> 312
~ -[SGMultiHeadInference initWithLanguage:inputName:plistPath:espressoModelPath:vocabPath:] : 1136 -> 1132
~ -[SGMultiHeadInference predictForVector:heads:] : 1068 -> 1064
~ +[SGLexiconML profanityInTokens:forLocaleIdentifier:] : 676 -> 672
~ +[SGDeduperML dedupe:bucketer:resolver:] : 960 -> 952
~ ___35+[SGDeduperML bucketerWithMapping:]_block_invoke : 456 -> 452
~ ___42+[SGDeduperML bucketerWithLabeledBuckets:]_block_invoke : 404 -> 400
~ ___40+[SGDeduperML bucketerWithEqualityTest:]_block_invoke : 576 -> 572
~ ___30+[SGDeduperML resolveByPairs:]_block_invoke : 372 -> 368
~ ___50+[SGDeduperML resolveByScoreBreakTiesArbitrarily:]_block_invoke : 384 -> 380
~ +[SGStringLabelingTransformer convertLabelsToMapping:] : 628 -> 624
~ +[SGLanguageDetection dominantLanguageTagFromLanguageTags:withMinimumCount:withMinimumAgreement:] : 576 -> 572
~ +[SGLanguageDetection languageTagsFromText:withMaxLength:withMaxTags:] : 1488 -> 1484
~ +[SGMultiHeadEspressoModel makeStringForShape:] : 160 -> 168
~ +[SGMultiHeadEspressoModel getNumParametersFromShape:rank:] : 48 -> 56
~ +[SGMultiHeadEspressoModel classifierWithEspressoModelFile:inputName:headDimensionality:] : 2600 -> 2592
~ -[SGMultiHeadEspressoModel predict:heads:] : 1840 -> 1836
~ -[SGQuickResponsesRanking semanticClassesForResults:scores:numResponses:config:] : 908 -> 904
```
