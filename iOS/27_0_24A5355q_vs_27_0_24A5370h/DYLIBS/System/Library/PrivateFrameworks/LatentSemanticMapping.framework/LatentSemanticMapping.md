## LatentSemanticMapping

> `/System/Library/PrivateFrameworks/LatentSemanticMapping.framework/LatentSemanticMapping`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b85c` | `0x1b3ac` | **`-0x4b0`** |
| `__TEXT.__gcc_except_tab` | `0x1d38` | `0x1d40` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc48` | `0xc50` | **`+0x8`** |

### Other Changes

```diff
Symbols:
+ __ZNSt12length_errorC1B9nqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9nqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9nqe220106Em
+ __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE15__init_buf_ptrsB9nqe220106Ev
+ __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9nqe220106Ej
+ __ZNSt3__116__pad_and_outputB9nqe220106IcNS_11char_traitsIcEEEENS_19ostreambuf_iteratorIT_T0_EES6_PKS4_S8_S8_RNS_8ios_baseES4_
+ __ZNSt3__117__floyd_sift_downB9nqe220106INS_17_ClassicAlgPolicyER16LSMTupleIterCompPmEET1_S5_OT0_NS_15iterator_traitsIS5_E15difference_typeE
+ __ZNSt3__117__floyd_sift_downB9nqe220106INS_17_ClassicAlgPolicyER20LSMSparseRowIterCompPmEET1_S5_OT0_NS_15iterator_traitsIS5_E15difference_typeE
+ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9nqe220106Ev
+ __ZNSt3__120__throw_length_errorB9nqe220106EPKc
+ __ZNSt3__124__put_character_sequenceB9nqe220106IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
+ __ZNSt3__14pairI9LSMVectorIjES1_IdEEC2B9nqe220106Ev
+ __ZNSt3__14pairI9LSMVectorIjES1_IfEEC2B9nqe220106Ev
+ __ZNSt3__14pairI9LSMVectorIjES2_EC2B9nqe220106Ev
+ __ZNSt3__19__sift_upB9nqe220106INS_17_ClassicAlgPolicyER16LSMTupleIterCompPmEEvT1_S5_OT0_NS_15iterator_traitsIS5_E15difference_typeE
+ __ZNSt3__19__sift_upB9nqe220106INS_17_ClassicAlgPolicyER20LSMSparseRowIterCompPmEEvT1_S5_OT0_NS_15iterator_traitsIS5_E15difference_typeE
- __ZNSt12length_errorC1B9nqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9nqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9nqe220100Em
- __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE15__init_buf_ptrsB9nqe220100Ev
- __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9nqe220100Ej
- __ZNSt3__116__pad_and_outputB9nqe220100IcNS_11char_traitsIcEEEENS_19ostreambuf_iteratorIT_T0_EES6_PKS4_S8_S8_RNS_8ios_baseES4_
- __ZNSt3__117__floyd_sift_downB9nqe220100INS_17_ClassicAlgPolicyER16LSMTupleIterCompPmEET1_S5_OT0_NS_15iterator_traitsIS5_E15difference_typeE
- __ZNSt3__117__floyd_sift_downB9nqe220100INS_17_ClassicAlgPolicyER20LSMSparseRowIterCompPmEET1_S5_OT0_NS_15iterator_traitsIS5_E15difference_typeE
- __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9nqe220100Ev
- __ZNSt3__120__throw_length_errorB9nqe220100EPKc
- __ZNSt3__124__put_character_sequenceB9nqe220100IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
- __ZNSt3__14pairI9LSMVectorIjES1_IdEEC2B9nqe220100Ev
- __ZNSt3__14pairI9LSMVectorIjES1_IfEEC2B9nqe220100Ev
- __ZNSt3__14pairI9LSMVectorIjES2_EC2B9nqe220100Ev
- __ZNSt3__19__sift_upB9nqe220100INS_17_ClassicAlgPolicyER16LSMTupleIterCompPmEEvT1_S5_OT0_NS_15iterator_traitsIS5_E15difference_typeE
- __ZNSt3__19__sift_upB9nqe220100INS_17_ClassicAlgPolicyER20LSMSparseRowIterCompPmEEvT1_S5_OT0_NS_15iterator_traitsIS5_E15difference_typeE
Functions:
~ __ZL8FindWordPK11LSMWordDescPKjmPb : 140 -> 152
~ __ZN21LSMImmutableWordTable12RebuildIndexEv : 396 -> 408
~ __ZN19LSMMutableWordTableC2ERK21LSMImmutableWordTable : 292 -> 284
~ __ZN19LSMMutableWordTable12RebuildIndexEv : 252 -> 256
~ __ZN11LSMTupleMap5ScaleEv : 288 -> 284
~ __ZN13LSMMapCounterC2ERK22LSMImmutableMapCounter : 524 -> 508
~ __ZN13LSMMapCounter13AddCategoriesEj : 380 -> 372
~ __ZN13LSMMapCounterC2EP15LSMReadFileDescP12LSMWordTablel : 1732 -> 1716
~ __ZN22LSMImmutableMapCounterC2ERK13LSMMapCounterP12LSMWordTablemm : 1672 -> 1628
~ __ZN22LSMImmutableMapCounter12ProcessTupleEP12LSMWordTablejb : 256 -> 252
~ __ZN22LSMImmutableMapCounterC2EP15LSMReadFileDescRP12LSMWordTablel : 2204 -> 2156
~ __ZN9LSMVectorINSt3__14pairIS_IjES2_EEED2Ev : 148 -> 172
~ __ZNSt3__117__floyd_sift_downB9nqe220100INS_17_ClassicAlgPolicyER16LSMTupleIterCompPmEET1_S5_OT0_NS_15iterator_traitsIS5_E15difference_typeE -> __ZNSt3__117__floyd_sift_downB9nqe220106INS_17_ClassicAlgPolicyER16LSMTupleIterCompPmEET1_S5_OT0_NS_15iterator_traitsIS5_E15difference_typeE : 140 -> 144
~ __ZN13LSMClassifier9ComputeVVEv : 176 -> 172
~ __ZN13LSMClassifier9ComputeU2Eb : 360 -> 356
~ __ZN13LSMClassifierC2EP15LSMReadFileDescl : 1332 -> 1304
~ __ZN7LSMText10LookupWordEPK10__CFStringP12LSMWordTableb : 276 -> 280
~ __ZN7LSMText11LookupTokenEPK8__CFDataP12LSMWordTable : 432 -> 448
~ __ZN15LSMArrayBuilderD2Ev : 120 -> 116
~ __ZN14LSMTrainingMap14CreateClustersEPK13__CFAllocatorPK9__CFArraylm : 1160 -> 1156
~ __ZL16AddCFValuesToMapPK9__CFArrayR9LSMVectorIjEj : 232 -> 236
~ __ZN14LSMCompiledMap13WriteToStreamEP15__CFWriteStreamP9__LSMText : 2116 -> 2112
~ __ZN14LSMCompiledMap9CopyWordsEj : 316 -> 308
~ __ZN14LSMCompiledMap10CopyTokensEj : 320 -> 312
~ __ZN13LSMVectorBase6adviseEi : 120 -> 124
~ __ZN11LSMTreePage6InsertEiPKvRK15LSMTreeIterBase : 156 -> 160
~ __ZN11LSMTreePage9RebalanceEmb : 128 -> 132
~ __ZN11LSMTreePage11DoRebalanceEmmmb : 340 -> 352
~ __ZN11LSMTreePage5SplitEm : 152 -> 156
~ __ZN13LSMTreeBranchD2Ev : 216 -> 220
~ __ZN13LSMTreeBranch6InsertEiPKvRK15LSMTreeIterBase : 404 -> 420
~ __ZN13LSMTreeBranch11DoRebalanceEmmmb : 324 -> 332
~ __ZN13LSMTreeBranch5SplitEm : 228 -> 232
~ __ZN13LSMTreeBranch11SanityCheckEibPS_ : 144 -> 148
~ __ZN13LSMTreeBranch7SetTreeEP11LSMTreeBase : 112 -> 116
~ __ZNK11LSMTreeBase10LowerBoundEPKvR15LSMTreeIterBase : 132 -> 136
~ __ZN15LSMTreeIterBase5DerefEv : 44 -> 48
~ __ZNK11LSMTreeBase5BeginER15LSMTreeIterBase : 128 -> 132
~ __ZN15LSMTreeIterBaseppEv : 120 -> 124
~ __ZNK15LSMTreeIterBase5EqualERKS_ : 100 -> 108
~ __ZN6LSMSVD10ProcessMapERK22LSMImmutableMapCounter : 1188 -> 1160
~ __ZN6LSMSVD16ProcessMapLegacyERK22LSMImmutableMapCounter : 1128 -> 1108
~ __ZN6LSMSVD19ProcessClusteredMapERK22LSMImmutableMapCounter : 888 -> 860
~ __ZL15TransposeMatrixR9LSMVectorIfEii : 236 -> 224
~ __ZNSt3__117__floyd_sift_downB9nqe220100INS_17_ClassicAlgPolicyER20LSMSparseRowIterCompPmEET1_S5_OT0_NS_15iterator_traitsIS5_E15difference_typeE -> __ZNSt3__117__floyd_sift_downB9nqe220106INS_17_ClassicAlgPolicyER20LSMSparseRowIterCompPmEET1_S5_OT0_NS_15iterator_traitsIS5_E15difference_typeE : 140 -> 148
~ __ZN12LSMSVDSDImpl12StartColumnsEv : 144 -> 128
~ __ZN13LSMSVDSDTImpl12StartColumnsEv : 144 -> 128
~ __ZN12LSMSVDSDImpl4DumpEv : 652 -> 644
~ __ZN12LSMSVDSDImpl7ComputeEm : 1604 -> 1564
~ __Z6dsort2llPdS_ : 132 -> 116
~ __ZN12LSMSVDSDImpl5lansoEv : 976 -> 932
~ __ZN12LSMSVDSDImpl6ritvecEv : 668 -> 644
~ __ZN12LSMSVDSDImpl6imtql2EllPdS0_S0_ : 824 -> 796
~ __ZN12LSMSVDSDImpl12lanczos_stepEiiPiPb : 1044 -> 1040
~ __ZN12LSMSVDSDImpl6imtqlbElPdS0_S0_ : 824 -> 728
~ __ZN12LSMSVDSDImpl11error_boundEPb : 496 -> 500
~ __ZN12LSMSVDSDImpl6startvEv : 576 -> 572
~ __ZN12LSMSVDSDImpl5purgeElPdS0_S0_S0_ : 640 -> 636
~ __ZN9LSMVectorINSt3__14pairIS_IjES_IdEEEED2Ev : 148 -> 172
~ __ZN12LSMSVDSFImpl12StartColumnsEv : 144 -> 128
~ __ZN13LSMSVDSFTImpl12StartColumnsEv : 144 -> 128
~ __ZN12LSMSVDSFImpl4DumpEv : 664 -> 656
~ __ZN12LSMSVDSFImpl7ComputeEm : 1564 -> 1516
~ __Z6dsort2llPfS_ : 132 -> 116
~ __ZN12LSMSVDSFImpl5lansoEv : 976 -> 932
~ __ZN12LSMSVDSFImpl6ritvecEv : 664 -> 640
~ __ZN12LSMSVDSFImpl6imtql2EllPfS0_S0_ : 812 -> 784
~ __ZN12LSMSVDSFImpl6imtqlbElPfS0_S0_ : 812 -> 716
~ __ZN12LSMSVDSFImpl11error_boundEPb : 496 -> 500
~ __ZN12LSMSVDSFImpl6startvEv : 576 -> 572
~ __ZN12LSMSVDSFImpl5purgeElPfS0_S0_S0_ : 640 -> 636
~ __ZN9LSMVectorINSt3__14pairIS_IjES_IfEEEED2Ev : 148 -> 172
~ __ZN15LSMCommonParser8AddWordsEPK10__CFString : 588 -> 624
~ __ZN15LSMCommonParser16ParseEuroSegmentEPtmb : 1296 -> 1220
~ __ZN16LSMSVDDenseFloat14ProcessElementEmmd : 40 -> 32
~ __ZN16LSMSVDDenseFloat7ComputeEm : 1036 -> 1024
~ __ZN21LSMSVDDenseFloatTrans14ProcessElementEmmd : 40 -> 32
~ __ZN17LSMSVDDenseDouble14ProcessElementEmmd : 36 -> 28
~ __ZN17LSMSVDDenseDouble7ComputeEm : 1056 -> 1048
~ __ZN22LSMSVDDenseDoubleTrans14ProcessElementEmmd : 36 -> 28
~ __ZN12LSMClustererC2EPK13LSMClassifierlm : 220 -> 216
~ __ZN12LSMClustererD2Ev : 300 -> 252
~ __ZN12LSMClusterer7ComputeEv : 320 -> 308
~ __ZN12LSMClusterer20ComputeAgglomerativeER9LSMVectorIfE : 3176 -> 2896
~ __ZN12LSMClusterer13ComputeKMeansER9LSMVectorIfE : 1592 -> 1536
~ __ZN12LSMClusterer15ClosestCentroidEPKfRK9LSMVectorIfEmRf : 324 -> 320
~ __ZN16LSMClusterParserD2Ev : 300 -> 252
~ __ZN16LSMClusterParser11AddCFValuesEPK9__CFArrayP9LSMVectorIjE : 880 -> 892
```
