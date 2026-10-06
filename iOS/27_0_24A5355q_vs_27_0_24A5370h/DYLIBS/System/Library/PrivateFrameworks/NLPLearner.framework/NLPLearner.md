## NLPLearner

> `/System/Library/PrivateFrameworks/NLPLearner.framework/NLPLearner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe3e4` | `0xe3b0` | **`-0x34`** |

### Other Changes

```diff
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220106EmRKf
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220100EmRKf
- __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ -[NLPLearnerExtensionWorker coreAnalyticsDonationFromEvaluationResults:] : 724 -> 720
~ +[NLPLearnerUtils getAttachmentURLByName:attachments:error:] : 728 -> 724
~ -[NLPLearnerEmojiClassificationData(Testing) addExamples:] : 676 -> 672
~ __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220100EmRKf -> __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220106EmRKf : 132 -> 128
~ -[NLPLearnerTextData loadFromCoreDuet:limitSamplesTo:] : 628 -> 624
~ -[NLPLearnerTextData loadFromCoreDuet:limitSamplesTo:withLocale:andLMStreamTokenizationBlock:] : 752 -> 748
~ +[NLPLearnerMontrealShadowEvaluator isInTopKPredictions:scores:total:topK:] : 372 -> 364
~ -[NLPLearnerLanguageModelingData addPreprocessedExample:] : 548 -> 544
~ -[NLPLearnerCharacterLanguageModelingData loadFromCoreDuet:limitSamplesTo:] : 1116 -> 1112
~ -[NLPLearnerLanguageModelingData(Testing) addExamples:] : 780 -> 776
~ -[QuickTypePFLTrainerMLP getWeightUpdatesAddNoise:encryptionKey:recipe:] : 1828 -> 1832
~ +[NLPLearnerACTShadowEvaluator actParamFilesAtPath:] : 572 -> 568
~ -[NLPLearnerACTShadowEvaluator evaluateModel:onRecords:options:completion:error:] : 1636 -> 1628
~ +[NLPLearnerACTShadowEvaluator processACTResults:metric:] : 796 -> 800
~ ___64-[NLPLearnerACTShadowEvaluator runACTWithParams:modelPath:data:]_block_invoke_2 : 352 -> 348
```
