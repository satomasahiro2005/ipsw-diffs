## libswiftDemangle.dylib

> `/usr/lib/swift/libswiftDemangle.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a128` | `0x59ef4` | **`-0x234`** |

### Other Changes

```diff

-6.4.0.19.103
+6.4.0.23.102
Symbols:
+ __ZNKSt3__110__function12__value_funcIFNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEyyEEclB9fqn220106EOySA_
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_out_of_rangeB9fqn220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqn220106EPKcm
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqn220106IN4llvm9StringRefELi0EEERKT_
+ __ZNSt3__125__throw_bad_function_callB9fqn220106Ev
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorIPN5swift8Demangle4NodeENS_9allocatorIS4_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__1plB9fqn220106IcNS_11char_traitsIcEENS_9allocatorIcEEEENS_12basic_stringIT_T0_T1_EERKS9_OS9_
+ __ZSt28__throw_bad_array_new_lengthB9fqn220106v
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIN5swift8Demangle17SubstitutionEntryEjEENS_22__unordered_map_hasherIS4_NS_4pairIKS4_jEENS4_6HasherENS_8equal_toIS4_EEEENS_21__unordered_map_equalIS4_S9_SC_SA_EENS_9allocatorIS9_EEE16__emplace_uniqueB9fqn220106IJS9_EEENS7_INS_15__hash_iteratorIPNS_11__hash_nodeIS5_PvEEEEbEEDpOT_ENKUlRS8_OS9_E_clESU_SV_
- __ZNKSt3__110__function12__value_funcIFNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEyyEEclB9fqn220100EOySA_
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_out_of_rangeB9fqn220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqn220100EPKcm
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqn220100IN4llvm9StringRefELi0EEERKT_
- __ZNSt3__125__throw_bad_function_callB9fqn220100Ev
- __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorIPN5swift8Demangle4NodeENS_9allocatorIS4_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__1plB9fqn220100IcNS_11char_traitsIcEENS_9allocatorIcEEEENS_12basic_stringIT_T0_T1_EERKS9_OS9_
- __ZSt28__throw_bad_array_new_lengthB9fqn220100v
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIN5swift8Demangle17SubstitutionEntryEjEENS_22__unordered_map_hasherIS4_NS_4pairIKS4_jEENS4_6HasherENS_8equal_toIS4_EEEENS_21__unordered_map_equalIS4_S9_SC_SA_EENS_9allocatorIS9_EEE16__emplace_uniqueB9fqn220100IJS9_EEENS7_INS_15__hash_iteratorIPNS_11__hash_nodeIS5_PvEEEEbEEDpOT_ENKUlRS8_OS9_E_clESU_SV_
Functions:
~ __ZN5swift8Demangle9Demangler16demangleOperatorEv : 5384 -> 5376
~ __ZN5swift8Demangle9Demangler18demangleIdentifierEv : 1900 -> 1872
~ __ZN5swift8Demangle6VectorIPNS0_4NodeEE9push_backERKS3_RNS0_11NodeFactoryE : 332 -> 328
~ __ZN5swift8Demangle9Demangler28demangleStandardSubstitutionEv : 1016 -> 1012
~ __ZN5swift8Demangle4Node8addChildEPS1_RNS0_11NodeFactoryE : 724 -> 720
~ __ZN5swift8Demangle9Demangler21demangleBoundGenericsERNS0_6VectorIPNS0_4NodeEEERS4_ : 440 -> 444
~ __ZN5swift8Demangle9Demangler26popRetroactiveConformancesEv : 372 -> 376
~ __ZN5swift8Demangle9Demangler8popTupleEv : 944 -> 948
~ __ZN5swift8Demangle9Demangler22popFunctionParamLabelsEPNS0_4NodeE : 2144 -> 2100
~ __ZN5swift8Demangle32makeSymbolicMangledNameStringRefEPKc : 76 -> 80
~ __ZN5swift8Demangle4Node15reverseChildrenEm : 112 -> 116
~ __ZN5swift8Demangle10CharVector6appendEiRNS0_11NodeFactoryE : 560 -> 544
~ __ZN5swift8Demangle10CharVector6appendEyRNS0_11NodeFactoryE : 436 -> 424
~ __ZN5swift8Demangle9Demangler26demangleMultiSubstitutionsEv : 496 -> 492
~ __ZN5swift8Demangle9Demangler19demangleBuiltinTypeEv : 2244 -> 2232
~ __ZN5swift8Demangle9Demangler17demangleArchetypeEv : 3344 -> 3332
~ __ZN5swift8Demangle9Demangler19demangleSpecialTypeEv : 4996 -> 4992
~ __ZN5swift8Demangle9Demangler26demangleOperatorIdentifierEv : 948 -> 960
~ __ZN5swift8Demangle9Demangler25demangleGenericParamIndexEv : 776 -> 764
~ __ZN5swift8Demangle9Demangler19demangleIntegerTypeEv : 796 -> 788
~ __ZN5swift8Demangle9Demangler15demangleNaturalEv : 124 -> 128
~ __ZN5swift8Demangle9Demangler13demangleIndexEv : 184 -> 180
~ __ZN5swift8Demangle9Demangler19demangleIndexAsNodeEv : 368 -> 364
~ __ZN5swift8Demangle9Demangler17demangleClangTypeEv : 548 -> 536
~ __ZN5swift8Demangle9Demangler7popPackEv : 552 -> 556
~ __ZN5swift8Demangle9Demangler10popSILPackEv : 740 -> 744
~ __ZN5swift8Demangle9Demangler11popTypeListEv : 404 -> 408
~ __ZN5swift8Demangle9Demangler29popAnyProtocolConformanceListEv : 424 -> 428
~ __ZN5swift8Demangle9Demangler33demangleDependentConformanceIndexEv : 520 -> 516
~ __ZN5swift8Demangle9Demangler16popAssocTypePathEv : 356 -> 360
~ __ZN5swift8Demangle9Demangler30demangleAssociatedTypeCompoundEPNS0_4NodeE : 1132 -> 1100
~ __ZN5swift8Demangle9Demangler49demangleGenericSpecializationWithDroppedArgumentsEv : 652 -> 664
~ __ZN5swift8Demangle9Demangler30demangleFunctionSpecializationEv : 1104 -> 1108
~ __ZN5swift8Demangle9Demangler37demangleAutoDiffSubsetParametersThunkEv : 792 -> 796
~ __ZN5swift8Demangle9Demangler48demangleAutoDiffSelfReorderingReabstractionThunkEv : 680 -> 684
~ __ZN5swift8Demangle9Demangler37demangleAutoDiffFunctionOrSimpleThunkENS0_4Node4KindE : 716 -> 720
~ __ZN5swift8Demangle9Demangler32demangleDifferentiabilityWitnessEv : 780 -> 784
~ __ZN5swift8Demangle9Demangler21demangleFuncSpecParamENS0_4Node4KindE : 2852 -> 2856
~ __ZN5swift8Demangle9Demangler39demangleSymbolicExtendedExistentialTypeEv : 744 -> 748
~ __ZN5swift8Demangle9Demangler45demangleConstrainedExistentialRequirementListEv : 412 -> 416
~ __ZN5swift8Demangle9Demangler20demangleProtocolListEv : 528 -> 532
~ __ZN5swift8Demangle9Demangler22demangleMacroExpansionEv : 1496 -> 1488
~ __ZN5swift8Demangle7Context13isThunkSymbolEN4llvm9StringRefE : 800 -> 772
~ __ZN5swift8Demangle7Context14getThunkTargetEN4llvm9StringRefE : 1080 -> 1052
~ __ZN5swift6Mangle10isNonAsciiEN4llvm9StringRefE : 56 -> 52
~ __ZN5swift6Mangle21needsPunycodeEncodingEN4llvm9StringRefE : 140 -> 144
~ __ZN5swift6Mangle17translateOperatorEN4llvm9StringRefE : 92 -> 88
~ __ZN5swift8Demangle9Demangler4dumpEv : 460 -> 464
~ __ZN5swift8Demangle11NodePrinter5printEPNS0_4NodeEjb : 27764 -> 27624
~ __ZN5swift8Demangle11NodePrinter17printFunctionTypeEPNS0_4NodeES3_j : 1728 -> 1676
~ __ZN5swift8Demangle11NodePrinter21printGenericSignatureEPNS0_4NodeEj : 1880 -> 1864
~ __ZN5swift8Demangle11NodePrinter36printFunctionSigSpecializationParamsEPNS0_4NodeEj : 2784 -> 2760
~ __Z20matchSequenceOfKindsPN5swift8Demangle4NodeENSt3__16vectorINS3_5tupleIJNS1_4KindEmEEENS3_9allocatorIS7_EEEE : 144 -> 148
~ __ZN5swift8Demangle19keyPathSourceStringEPKcm : 3368 -> 3352
~ __ZN12_GLOBAL__N_112OldDemangler24demangleBoundGenericArgsEPN5swift8Demangle4NodeEj : 644 -> 640
~ __ZN12_GLOBAL__N_112OldDemangler25demangleGenericParamIndexEj : 488 -> 496
~ __ZN5swift8Punycode14decodePunycodeEN4llvm9StringRefERNSt3__16vectorIjNS3_9allocatorIjEEEE : 824 -> 804
~ __ZNSt3__16vectorIjNS_9allocatorIjEEE6insertENS_11__wrap_iterIPKjEERS5_ : 480 -> 476
~ __ZN5swift8Punycode18encodePunycodeUTF8EN4llvm9StringRefERNSt3__112basic_stringIcNS3_11char_traitsIcEENS3_9allocatorIcEEEEb : 572 -> 568
~ __ZNSt3__114__split_bufferIjRNS_9allocatorIjEEE12emplace_backIJRKjEEEvDpOT_ : 408 -> 400
~ __ZN5swift8Demangle17SubstitutionEntry16identifierEqualsEPNS0_4NodeES3_ : 332 -> 316
~ __ZNK5swift8Demangle17SubstitutionEntry10deepEqualsEPNS0_4NodeES3_ : 372 -> 376
~ __ZN5swift8Demangle13RemanglerBase11hashForNodeEPNS0_4NodeEb : 372 -> 364
~ __ZN5swift8Demangle13RemanglerBase12entryForNodeEPNS0_4NodeEb : 520 -> 524
~ __ZN5swift8Demangle13RemanglerBase16findSubstitutionERKNS0_17SubstitutionEntryE : 260 -> 284
~ __ZN5swift8Demangle10mangleNodeEPNS0_4NodeEN4llvm12function_refIFS2_NS0_21SymbolicReferenceKindEPKvEEENS_6Mangle14ManglingFlavorE : 640 -> 636
~ __ZN5swift8Demangle16getUnspecializedEPNS0_4NodeERNS0_11NodeFactoryE : 1132 -> 1128
~ __ZN12_GLOBAL__N_19Remangler31mangleDependentGenericSignatureEPN5swift8Demangle4NodeEj : 1776 -> 1764
~ __ZN12_GLOBAL__N_19Remangler14mangleFunctionEPN5swift8Demangle4NodeEj : 1044 -> 1040
~ __ZN12_GLOBAL__N_19Remangler43mangleConstrainedExistentialRequirementListEPN5swift8Demangle4NodeEj : 284 -> 280
~ __ZN12_GLOBAL__N_19Remangler12mangleGlobalEPN5swift8Demangle4NodeEj : 616 -> 680
~ __ZN12_GLOBAL__N_19Remangler22mangleImplFunctionTypeEPN5swift8Demangle4NodeEj : 8072 -> 8068
~ __ZN12_GLOBAL__N_19Remangler26mangleSILBoxTypeWithLayoutEPN5swift8Demangle4NodeEj : 1000 -> 984
~ __ZN12_GLOBAL__N_19Remangler14mangleTypeListEPN5swift8Demangle4NodeEj : 300 -> 296
~ __ZN12_GLOBAL__N_19Remangler16mangleOpaqueTypeEPN5swift8Demangle4NodeEj : 1452 -> 1456
~ __ZN12_GLOBAL__N_19Remangler32mangleGlobalVariableOnceDeclListEPN5swift8Demangle4NodeEj : 556 -> 552
~ __ZN12_GLOBAL__N_19Remangler35mangleAutoDiffSubsetParametersThunkEPN5swift8Demangle4NodeEj : 1168 -> 1180
~ __ZN12_GLOBAL__N_19Remangler30mangleDifferentiabilityWitnessEPN5swift8Demangle4NodeEj : 1284 -> 1296
~ __ZN5swift6Mangle19SubstitutionMerging13tryMergeSubstIN12_GLOBAL__N_19RemanglerEEEbRT_N4llvm9StringRefEb : 840 -> 844
~ __ZN12_GLOBAL__N_19Remangler19mangleAttachedMacroEPN5swift8Demangle4NodeEjN4llvm9StringRefE : 416 -> 408
~ __ZN12_GLOBAL__N_19Remangler20mangleAnyNominalTypeEPN5swift8Demangle4NodeEj : 788 -> 784
~ __ZN12_GLOBAL__N_19Remangler21mangleConstrainedTypeEPN5swift8Demangle4NodeEj : 1084 -> 1048
~ __ZN5swift6Mangle16mangleIdentifierIN12_GLOBAL__N_19RemanglerEEEvRT_N4llvm9StringRefE : 3880 -> 3768
~ __ZN12_GLOBAL__N_19Remangler35mangleAutoDiffFunctionOrSimpleThunkEPN5swift8Demangle4NodeEN4llvm9StringRefEj : 884 -> 896
```
