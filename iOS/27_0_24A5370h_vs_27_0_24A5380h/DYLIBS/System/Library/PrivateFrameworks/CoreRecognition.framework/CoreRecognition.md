## CoreRecognition

> `/System/Library/PrivateFrameworks/CoreRecognition.framework/CoreRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b7f0` | `0x5b654` | **`-0x19c`** |
| `__DATA_CONST.__got` | `0x5d8` | `0x5e0` | **`+0x8`** |

### Other Changes

```diff

-446.9.0.0.0
+446.10.0.0.0
Functions:
~ -[CRCameraReader viewDidLayoutSubviews] : 676 -> 712
~ __ZN3CNN9RecognizeEP6CorpusNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE : 4780 -> 4784
~ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERPFbRK8HeapPairIdjES5_EPS3_Lb0EEEvT1_SA_T0_NS_15iterator_traitsISA_E15difference_typeEb : 4172 -> 4156
~ __ZNSt3__127__insertion_sort_incompleteB9foe220106INS_17_ClassicAlgPolicyERPFbRK8HeapPairIdjES5_EPS3_EEbT1_SA_T0_ : 1172 -> 1116
~ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERPFbRK8HeapPairIjjES5_EPS3_Lb0EEEvT1_SA_T0_NS_15iterator_traitsISA_E15difference_typeEb : 3528 -> 3516
~ __ZNSt3__127__insertion_sort_incompleteB9foe220106INS_17_ClassicAlgPolicyERPFbRK8HeapPairIjjES5_EPS3_EEbT1_SA_T0_ : 992 -> 964
~ __ZN10CNNSignalsC2Ej : 1532 -> 1416
~ __ZNSt3__16vectorI6matrixIfENS_9allocatorIS2_EEE6resizeEm : 664 -> 584
~ __ZNSt3__16vectorI6matrixIfENS_9allocatorIS2_EEE16__destroy_vectorclB9foe220106Ev : 152 -> 144
~ __ZNSt3__16vectorI6matrixIjENS_9allocatorIS2_EEE16__destroy_vectorclB9foe220106Ev : 152 -> 144
~ +[ActivationMapTools fitSpacingModel:toActivationMap:codeMap:minWordLengthFractionForCorrelationPeak:cost:] : 7520 -> 7516
~ _extractDigitCodeImages : 4784 -> 4816
~ _createPlanar420PixelBufferFromImageFile : 1448 -> 1432
~ __ZL13indexGroupingNSt3__16vectorIiNS_9allocatorIiEEEERNS0_IS3_NS1_IS3_EEEEi : 860 -> 884
~ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERNS_6__lessIvvEENS_16reverse_iteratorINS_11__wrap_iterIPNS_4pairIfiEEEEEELb0EEEvT1_SC_T0_NS_15iterator_traitsISC_E15difference_typeEb : 4408 -> 4344
~ __ZNSt3__127__insertion_sort_incompleteB9foe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEENS_16reverse_iteratorINS_11__wrap_iterIPNS_4pairIfiEEEEEEEEbT1_SC_T0_ : 1136 -> 1128
~ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERZL33returnIndiciesOfSortedFloatVectorRKNS_6vectorIfNS_9allocatorIfEEEEE3$_0PiLb0EEEvT1_SB_T0_NS_15iterator_traitsISB_E15difference_typeEb : 4772 -> 4700
~ __ZNSt3__127__insertion_sort_incompleteB9foe220106INS_17_ClassicAlgPolicyERZL33returnIndiciesOfSortedFloatVectorRKNS_6vectorIfNS_9allocatorIfEEEEE3$_0PiEEbT1_SB_T0_ : 828 -> 804
~ __ZNSt3__19__reverseB9foe220106INS_17_ClassicAlgPolicyENS_11__wrap_iterIPNS_6vectorIfNS_9allocatorIfEEEEEES8_EEvT0_T1_ : 84 -> 88
```
