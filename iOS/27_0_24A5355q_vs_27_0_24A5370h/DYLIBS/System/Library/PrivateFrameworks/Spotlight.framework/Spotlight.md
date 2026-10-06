## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Spotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa1490` | `0xa2e90` | **`+0x1a00`** |
| `__TEXT.__swift5_typeref` | `0x79d` | `0x86f` | **`+0xd2`** |
| `__TEXT.__eh_frame` | `0x1200` | `0x12a0` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x5f35` | `0x5fd5` | **`+0xa0`** |
| `__TEXT.__const` | `0xf88` | `0x1018` | **`+0x90`** |
| `__DATA.__data` | `0x7a0` | `0x828` | **`+0x88`** |
| `__AUTH.__objc_data` | `0x3c8` | `0x418` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x403` | `0x453` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x13f0` | `0x1438` | **`+0x48`** |
| `__DATA_DIRTY.__objc_data` | `0xd40` | `0xd10` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x42c` | `0x45c` | **`+0x30`** |
| `__TEXT.__cstring` | `0x3b6a` | `0x3b9a` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x5648` | `0x5670` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x2f8` | `0x320` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1818` | `0x1840` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x31c0` | `0x31a0` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x4ba8` | `0x4bc8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1998` | `0x19b8` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x228` | `0x210` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x2e64` | `0x2e4c` | **`-0x18`** |
| `__TEXT.__swift_as_cont` | `0xf8` | `0x108` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x16c8` | `0x16d0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x5c` | `0x60` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0xc` | `0x10` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x80` | `0x84` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x60` | `0x64` | **`+0x4`** |

### Other Changes

```diff

-2444.104.0.0.0
+2448.100.0.0.0

-  Functions: 1847
-  Symbols:   3337
-  CStrings:  1004
+  Functions: 1860
+  Symbols:   3349
+  CStrings:  1005
Symbols:
+ +[SPKGenerativeSearchSiriTranscriptQuery activate]
+ +[SPKGenerativeSearchSiriTranscriptQuery deactivate]
+ +[SPKGenerativeSearchSiriTranscriptQuery defaultResultLimit]
+ +[SPKGenerativeSearchSiriTranscriptQuery isQuerySupported:]
+ +[SPKGenerativeSearchSiriTranscriptQuery preheat]
+ +[SPKGenerativeSearchSiriTranscriptQuery searchDomain]
+ +[SPKGenerativeSearchSiriTranscriptQuery sourceKind]
+ -[SPKGenerativeSearchSiriTranscriptQuery .cxx_destruct]
+ -[SPKGenerativeSearchSiriTranscriptQuery _cancel]
+ -[SPKGenerativeSearchSiriTranscriptQuery _injectTestClient:]
+ -[SPKGenerativeSearchSiriTranscriptQuery _start]
+ -[SPKGenerativeSearchSiriTranscriptQuery beginQuerySignpostInterval]
+ -[SPKGenerativeSearchSiriTranscriptQuery createActivity]
+ -[SPKGenerativeSearchSiriTranscriptQuery dealloc]
+ -[SPKGenerativeSearchSiriTranscriptQuery endQuerySignpostInterval]
+ -[SPKGenerativeSearchSiriTranscriptQuery handleEmptyResults]
+ -[SPKGenerativeSearchSiriTranscriptQuery handleQueryError:]
+ -[SPKGenerativeSearchSiriTranscriptQuery handleSuccessfulResults:queryContext:]
+ -[SPKGenerativeSearchSiriTranscriptQuery initWithUserQuery:queryGroupId:options:queryContext:]
+ -[SPKGenerativeSearchSiriTranscriptQuery isGenerativeSearchQuery]
+ -[SPKGenerativeSearchSiriTranscriptQuery queryResponseReceivedSignpostEvent:]
+ GCC_except_table17
+ _OBJC_CLASS_$_SPKGenerativeSearchSiriTranscriptQuery
+ _OBJC_IVAR_$_SPKGenerativeSearchSiriTranscriptQuery._client
+ _OBJC_IVAR_$_SPKGenerativeSearchSiriTranscriptQuery._injectedClient
+ _OBJC_IVAR_$_SPKGenerativeSearchSiriTranscriptQuery._queryQueue
+ _OBJC_METACLASS_$_SPKGenerativeSearchSiriTranscriptQuery
+ __OBJC_$_CLASS_METHODS_SPKGenerativeSearchSiriTranscriptQuery
+ __OBJC_$_INSTANCE_METHODS_SPKGenerativeSearchSiriTranscriptQuery
+ __OBJC_$_INSTANCE_VARIABLES_SPKGenerativeSearchSiriTranscriptQuery
+ __OBJC_CLASS_RO_$_SPKGenerativeSearchSiriTranscriptQuery
+ __OBJC_METACLASS_RO_$_SPKGenerativeSearchSiriTranscriptQuery
+ __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqn220106EPKvm
+ __ZNKSt3__18equal_toINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEclB9fqn220106ERKS6_S9_
+ __ZNSt3__110__pop_heapB9fqn220106INS_17_ClassicAlgPolicyEPFbRK17SPResultValueItemS4_ENS_11__wrap_iterIPS2_EEEEvT1_SA_RT0_NS_15iterator_traitsISA_E15difference_typeE
+ __ZNSt3__111__sift_downB9fqn220106INS_17_ClassicAlgPolicyELb0ERPFbRK17SPResultValueItemS4_ENS_11__wrap_iterIPS2_EEEEvT2_OT1_NS_15iterator_traitsISB_E15difference_typeESG_
+ __ZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4pairIU8__strongP22SFMutableResultSectionU8__strongP19NSMutableOrderedSetIP20SPSearchTopHitResultEEEEENS_22__unordered_map_hasherIS7_NS8_IKS7_SI_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SM_SQ_SO_EENS5_ISM_EEE22__deallocate_node_listB9fqn220106EPNS_16__hash_node_baseIPNS_11__hash_nodeISJ_PvEEEE
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqn220106Em
+ __ZNSt3__114__split_bufferI17SPResultValueItemRNS_9allocatorIS1_EEE5clearB9fqn220106Ev
+ __ZNSt3__116allocator_traitsINS_9allocatorI17SPResultValueItemEEE7destroyB9fqn220106IS2_Li0EEEvRS3_PT_
+ __ZNSt3__117__floyd_sift_downB9fqn220106INS_17_ClassicAlgPolicyERPFbRK17SPResultValueItemS4_ENS_11__wrap_iterIPS2_EEEET1_SB_OT0_NS_15iterator_traitsISB_E15difference_typeE
+ __ZNSt3__119__allocate_at_leastB9fqn220106INS_9allocatorI12IndexResultsEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqn220106INS_9allocatorI17SPResultValueItemEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqn220106INS_9allocatorI31SPResultValueItemHashTableEntryEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__121__murmur2_or_cityhashImLm64EE18__hash_len_0_to_16B9fqn220106EPKcm
+ __ZNSt3__121__murmur2_or_cityhashImLm64EE19__hash_len_17_to_32B9fqn220106EPKcm
+ __ZNSt3__121__murmur2_or_cityhashImLm64EE19__hash_len_33_to_64B9fqn220106EPKcm
+ __ZNSt3__122__hash_node_destructorINS_9allocatorINS_11__hash_nodeINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS1_IcEEEENS_4pairIU8__strongP22SFMutableResultSectionU8__strongP19NSMutableOrderedSetIP20SPSearchTopHitResultEEEEEPvEEEEEclB9fqn220106EPSM_
+ __ZNSt3__134__uninitialized_allocator_relocateB9fqn220106INS_9allocatorI12IndexResultsEEPS2_EEvRT_T0_S7_S7_
+ __ZNSt3__134__uninitialized_allocator_relocateB9fqn220106INS_9allocatorI17SPResultValueItemEEPS2_EEvRT_T0_S7_S7_
+ __ZNSt3__135__uninitialized_allocator_copy_implB9fqn220106INS_9allocatorI17SPResultValueItemEEPS2_S4_S4_EET2_RT_T0_T1_S5_
+ __ZNSt3__135__uninitialized_allocator_copy_implB9fqn220106INS_9allocatorI31SPResultValueItemHashTableEntryEEPS2_S4_S4_EET2_RT_T0_T1_S5_
+ __ZNSt3__16vectorI12IndexResultsNS_9allocatorIS1_EEE16__destroy_vectorclB9fqn220106Ev
+ __ZNSt3__16vectorI12IndexResultsNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorI12IndexResultsNS_9allocatorIS1_EEE20__throw_out_of_rangeB9fqn220106Ev
+ __ZNSt3__16vectorI12IndexResultsNS_9allocatorIS1_EEE5clearB9fqn220106Ev
+ __ZNSt3__16vectorI17SPResultValueItemNS_9allocatorIS1_EEE11__vallocateB9fqn220106Em
+ __ZNSt3__16vectorI17SPResultValueItemNS_9allocatorIS1_EEE16__destroy_vectorclB9fqn220106Ev
+ __ZNSt3__16vectorI17SPResultValueItemNS_9allocatorIS1_EEE16__init_with_sizeB9fqn220106IPS1_S6_EEvT_T0_m
+ __ZNSt3__16vectorI17SPResultValueItemNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorI17SPResultValueItemNS_9allocatorIS1_EEE5clearB9fqn220106Ev
+ __ZNSt3__16vectorI31SPResultValueItemHashTableEntryNS_9allocatorIS1_EEE11__vallocateB9fqn220106Em
+ __ZNSt3__16vectorI31SPResultValueItemHashTableEntryNS_9allocatorIS1_EEE16__destroy_vectorclB9fqn220106Ev
+ __ZNSt3__16vectorI31SPResultValueItemHashTableEntryNS_9allocatorIS1_EEE16__init_with_sizeB9fqn220106IPS1_S6_EEvT_T0_m
+ __ZNSt3__16vectorI31SPResultValueItemHashTableEntryNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorI31SPResultValueItemHashTableEntryNS_9allocatorIS1_EEE5clearB9fqn220106Ev
+ __ZNSt3__16vectorI31SPResultValueItemHashTableEntryNS_9allocatorIS1_EEEC2B9fqn220106EmRKS1_
+ __ZNSt3__19__sift_upB9fqn220106INS_17_ClassicAlgPolicyERPFbRK17SPResultValueItemS4_ENS_11__wrap_iterIPS2_EEEEvT1_SB_OT0_NS_15iterator_traitsISB_E15difference_typeE
+ __ZSt28__throw_bad_array_new_lengthB9fqn220106v
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4pairIU8__strongP22SFMutableResultSectionU8__strongP19NSMutableOrderedSetIP20SPSearchTopHitResultEEEEENS_22__unordered_map_hasherIS7_NS8_IKS7_SI_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SM_SQ_SO_EENS5_ISM_EEE16__emplace_uniqueB9fqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJOS7_EEENS10_IJEEEEEENS8_INS_15__hash_iteratorIPNS_11__hash_nodeISJ_PvEEEEbEEDpOT_ENKUlRSL_SZ_OS12_OS13_E_clES1E_SZ_S1F_S1G_
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4pairIU8__strongP22SFMutableResultSectionU8__strongP19NSMutableOrderedSetIP20SPSearchTopHitResultEEEEENS_22__unordered_map_hasherIS7_NS8_IKS7_SI_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SM_SQ_SO_EENS5_ISM_EEE16__emplace_uniqueB9fqn220106IJRKNS_21piecewise_construct_tENS_5tupleIJRSL_EEENS10_IJEEEEEENS8_INS_15__hash_iteratorIPNS_11__hash_nodeISJ_PvEEEEbEEDpOT_ENKUlS11_SZ_OS12_OS13_E_clES11_SZ_S1E_S1F_
+ ___48-[SPKGenerativeSearchSiriTranscriptQuery _start]_block_invoke
+ ___48-[SPKGenerativeSearchSiriTranscriptQuery _start]_block_invoke_2
+ ___49-[SPKGenerativeSearchSiriTranscriptQuery _cancel]_block_invoke
+ ___60+[SPKGenerativeSearchSiriTranscriptQuery defaultResultLimit]_block_invoke
+ ___swift_allocate_boxed_opaque_existential_1
+ ___swift_closure_destructor.174Tm
+ _swift_allocBox
+ _swift_getTupleTypeMetadata2
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _symbolic $s9Spotlight31TranscriptSearchClientProvidingP
+ _symbolic Say_____G13conversations______17l2RankingMetadatat 23GenerativeSearchAdapter16TranscriptDomainO012ConversationB6ResultV 0aB017L2RankingMetadataV
+ _symbolic Si6offset______7elementt 23GenerativeSearchAdapter16TranscriptDomainO012ConversationB6ResultV
+ _symbolic _____3key______5valuet 16GenerativeSearch014SiriTranscriptB7ContentV19SearchableAttributeO AA0B9TermScoreV
+ _symbolic _____Sg 16GenerativeSearch014SiriTranscriptB7ContentV
+ _symbolic _____Sg 16GenerativeSearch014SiriTranscriptB7ContentV06StoredE0O
+ _symbolic _____Sg 16GenerativeSearch33SiriTranscriptConversationContentV
+ _symbolic ______Sit 23GenerativeSearchAdapter16TranscriptDomainO012ConversationB6ResultV
+ _symbolic ______p 9Spotlight31TranscriptSearchClientProvidingP
+ _symbolic ______pSg 9Spotlight31TranscriptSearchClientProvidingP
+ _symbolic _____y_____G 16GenerativeSearch6ResultV AA014SiriTranscriptB7ContentV
+ _symbolic _____y_____G 16GenerativeSearch6ResultV AA33SiriTranscriptConversationContentV
+ _symbolic _____y_____GSg 16GenerativeSearch6ResultV AA33SiriTranscriptConversationContentV
- +[SPKGenerativeSearchGlobalQuery activate]
- +[SPKGenerativeSearchGlobalQuery deactivate]
- +[SPKGenerativeSearchGlobalQuery defaultResultLimit]
- +[SPKGenerativeSearchGlobalQuery isQuerySupported:]
- +[SPKGenerativeSearchGlobalQuery preheat]
- +[SPKGenerativeSearchGlobalQuery searchDomain]
- +[SPKGenerativeSearchGlobalQuery sourceKind]
- -[SPKGenerativeSearchGlobalQuery .cxx_destruct]
- -[SPKGenerativeSearchGlobalQuery _cancel]
- -[SPKGenerativeSearchGlobalQuery _injectTestClient:]
- -[SPKGenerativeSearchGlobalQuery _start]
- -[SPKGenerativeSearchGlobalQuery beginQuerySignpostInterval]
- -[SPKGenerativeSearchGlobalQuery buildEntityTypesFilter]
- -[SPKGenerativeSearchGlobalQuery createActivity]
- -[SPKGenerativeSearchGlobalQuery dealloc]
- -[SPKGenerativeSearchGlobalQuery endQuerySignpostInterval]
- -[SPKGenerativeSearchGlobalQuery handleEmptyResults]
- -[SPKGenerativeSearchGlobalQuery handleQueryError:]
- -[SPKGenerativeSearchGlobalQuery handleSuccessfulResults:queryContext:]
- -[SPKGenerativeSearchGlobalQuery initWithUserQuery:queryGroupId:options:queryContext:]
- -[SPKGenerativeSearchGlobalQuery isGenerativeSearchQuery]
- -[SPKGenerativeSearchGlobalQuery queryResponseReceivedSignpostEvent:]
- -[SPKGenerativeSearchGlobalQuery sendEmptyResponseIfNecessary]
- _OBJC_CLASS_$_SPKGenerativeSearchGlobalQuery
- _OBJC_IVAR_$_SPKGenerativeSearchGlobalQuery._client
- _OBJC_IVAR_$_SPKGenerativeSearchGlobalQuery._injectedClient
- _OBJC_IVAR_$_SPKGenerativeSearchGlobalQuery._queryQueue
- _OBJC_METACLASS_$_SPKGenerativeSearchGlobalQuery
- __OBJC_$_CLASS_METHODS_SPKGenerativeSearchGlobalQuery
- __OBJC_$_INSTANCE_METHODS_SPKGenerativeSearchGlobalQuery
- __OBJC_$_INSTANCE_VARIABLES_SPKGenerativeSearchGlobalQuery
- __OBJC_CLASS_RO_$_SPKGenerativeSearchGlobalQuery
- __OBJC_METACLASS_RO_$_SPKGenerativeSearchGlobalQuery
- __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqn220100EPKvm
- __ZNKSt3__18equal_toINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEclB9fqn220100ERKS6_S9_
- __ZNSt3__110__pop_heapB9fqn220100INS_17_ClassicAlgPolicyEPFbRK17SPResultValueItemS4_ENS_11__wrap_iterIPS2_EEEEvT1_SA_RT0_NS_15iterator_traitsISA_E15difference_typeE
- __ZNSt3__111__sift_downB9fqn220100INS_17_ClassicAlgPolicyELb0ERPFbRK17SPResultValueItemS4_ENS_11__wrap_iterIPS2_EEEEvT2_OT1_NS_15iterator_traitsISB_E15difference_typeESG_
- __ZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4pairIU8__strongP22SFMutableResultSectionU8__strongP19NSMutableOrderedSetIP20SPSearchTopHitResultEEEEENS_22__unordered_map_hasherIS7_NS8_IKS7_SI_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SM_SQ_SO_EENS5_ISM_EEE22__deallocate_node_listB9fqn220100EPNS_16__hash_node_baseIPNS_11__hash_nodeISJ_PvEEEE
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqn220100Em
- __ZNSt3__114__split_bufferI17SPResultValueItemRNS_9allocatorIS1_EEE5clearB9fqn220100Ev
- __ZNSt3__116allocator_traitsINS_9allocatorI17SPResultValueItemEEE7destroyB9fqn220100IS2_Li0EEEvRS3_PT_
- __ZNSt3__117__floyd_sift_downB9fqn220100INS_17_ClassicAlgPolicyERPFbRK17SPResultValueItemS4_ENS_11__wrap_iterIPS2_EEEET1_SB_OT0_NS_15iterator_traitsISB_E15difference_typeE
- __ZNSt3__119__allocate_at_leastB9fqn220100INS_9allocatorI12IndexResultsEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqn220100INS_9allocatorI17SPResultValueItemEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqn220100INS_9allocatorI31SPResultValueItemHashTableEntryEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__121__murmur2_or_cityhashImLm64EE18__hash_len_0_to_16B9fqn220100EPKcm
- __ZNSt3__121__murmur2_or_cityhashImLm64EE19__hash_len_17_to_32B9fqn220100EPKcm
- __ZNSt3__121__murmur2_or_cityhashImLm64EE19__hash_len_33_to_64B9fqn220100EPKcm
- __ZNSt3__122__hash_node_destructorINS_9allocatorINS_11__hash_nodeINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS1_IcEEEENS_4pairIU8__strongP22SFMutableResultSectionU8__strongP19NSMutableOrderedSetIP20SPSearchTopHitResultEEEEEPvEEEEEclB9fqn220100EPSM_
- __ZNSt3__134__uninitialized_allocator_relocateB9fqn220100INS_9allocatorI12IndexResultsEEPS2_EEvRT_T0_S7_S7_
- __ZNSt3__134__uninitialized_allocator_relocateB9fqn220100INS_9allocatorI17SPResultValueItemEEPS2_EEvRT_T0_S7_S7_
- __ZNSt3__135__uninitialized_allocator_copy_implB9fqn220100INS_9allocatorI17SPResultValueItemEEPS2_S4_S4_EET2_RT_T0_T1_S5_
- __ZNSt3__135__uninitialized_allocator_copy_implB9fqn220100INS_9allocatorI31SPResultValueItemHashTableEntryEEPS2_S4_S4_EET2_RT_T0_T1_S5_
- __ZNSt3__16vectorI12IndexResultsNS_9allocatorIS1_EEE16__destroy_vectorclB9fqn220100Ev
- __ZNSt3__16vectorI12IndexResultsNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorI12IndexResultsNS_9allocatorIS1_EEE20__throw_out_of_rangeB9fqn220100Ev
- __ZNSt3__16vectorI12IndexResultsNS_9allocatorIS1_EEE5clearB9fqn220100Ev
- __ZNSt3__16vectorI17SPResultValueItemNS_9allocatorIS1_EEE11__vallocateB9fqn220100Em
- __ZNSt3__16vectorI17SPResultValueItemNS_9allocatorIS1_EEE16__destroy_vectorclB9fqn220100Ev
- __ZNSt3__16vectorI17SPResultValueItemNS_9allocatorIS1_EEE16__init_with_sizeB9fqn220100IPS1_S6_EEvT_T0_m
- __ZNSt3__16vectorI17SPResultValueItemNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorI17SPResultValueItemNS_9allocatorIS1_EEE5clearB9fqn220100Ev
- __ZNSt3__16vectorI31SPResultValueItemHashTableEntryNS_9allocatorIS1_EEE11__vallocateB9fqn220100Em
- __ZNSt3__16vectorI31SPResultValueItemHashTableEntryNS_9allocatorIS1_EEE16__destroy_vectorclB9fqn220100Ev
- __ZNSt3__16vectorI31SPResultValueItemHashTableEntryNS_9allocatorIS1_EEE16__init_with_sizeB9fqn220100IPS1_S6_EEvT_T0_m
- __ZNSt3__16vectorI31SPResultValueItemHashTableEntryNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorI31SPResultValueItemHashTableEntryNS_9allocatorIS1_EEE5clearB9fqn220100Ev
- __ZNSt3__16vectorI31SPResultValueItemHashTableEntryNS_9allocatorIS1_EEEC2B9fqn220100EmRKS1_
- __ZNSt3__19__sift_upB9fqn220100INS_17_ClassicAlgPolicyERPFbRK17SPResultValueItemS4_ENS_11__wrap_iterIPS2_EEEEvT1_SB_OT0_NS_15iterator_traitsISB_E15difference_typeE
- __ZSt28__throw_bad_array_new_lengthB9fqn220100v
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4pairIU8__strongP22SFMutableResultSectionU8__strongP19NSMutableOrderedSetIP20SPSearchTopHitResultEEEEENS_22__unordered_map_hasherIS7_NS8_IKS7_SI_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SM_SQ_SO_EENS5_ISM_EEE16__emplace_uniqueB9fqn220100IJRKNS_21piecewise_construct_tENS_5tupleIJOS7_EEENS10_IJEEEEEENS8_INS_15__hash_iteratorIPNS_11__hash_nodeISJ_PvEEEEbEEDpOT_ENKUlRSL_SZ_OS12_OS13_E_clES1E_SZ_S1F_S1G_
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4pairIU8__strongP22SFMutableResultSectionU8__strongP19NSMutableOrderedSetIP20SPSearchTopHitResultEEEEENS_22__unordered_map_hasherIS7_NS8_IKS7_SI_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SM_SQ_SO_EENS5_ISM_EEE16__emplace_uniqueB9fqn220100IJRKNS_21piecewise_construct_tENS_5tupleIJRSL_EEENS10_IJEEEEEENS8_INS_15__hash_iteratorIPNS_11__hash_nodeISJ_PvEEEEbEEDpOT_ENKUlS11_SZ_OS12_OS13_E_clES11_SZ_S1E_S1F_
- ___40-[SPKGenerativeSearchGlobalQuery _start]_block_invoke
- ___40-[SPKGenerativeSearchGlobalQuery _start]_block_invoke_2
- ___41-[SPKGenerativeSearchGlobalQuery _cancel]_block_invoke
- ___52+[SPKGenerativeSearchGlobalQuery defaultResultLimit]_block_invoke
- ___swift_closure_destructor.156Tm
- _swift_retain_x26
- _symbolic SaySo8NSNumberCGSg
- _symbolic Say_____G 16GenerativeSearch10EntityTypeV
- _symbolic _____ 16GenerativeSearch0B6ResultV
CStrings:
+ "Executing transcript query [%s]: '%{private}s' limit: %ld"
+ "GenerativeSearchTranscriptQueryLatency"
+ "SPKGenerativeSearchSiriTranscriptQuery"
+ "SPKGenerativeSearchSiriTranscriptQuery Response"
+ "Transcript query [%s] cancelled during error handling"
+ "Transcript query [%s] cancelled with CancellationError"
+ "Transcript query [%s] failed: %s"
+ "Transcript query [%s] returned %ld/%ld conversations (filtered for conversationMatch + turnMatches)"
+ "Transcript search client not initialized"
+ "TranscriptSearchClient"
+ "[qid=%lu] Cancelling GenerativeSearch TranscriptQuery"
+ "[qid=%lu] Constructing result sections using %lu results received from GenerativeSearch TranscriptQuery."
+ "[qid=%lu] Error executing GenerativeSearch TranscriptQuery: [%ld] %@"
+ "[qid=%lu] No entity types enabled or received 0 results from GenerativeSearch TranscriptQuery, returning empty results"
+ "siriTranscript(conversation)"
+ "status=success conversationCount=%ld"
+ "transcriptClientAdapter is nil - cannot execute transcript query"
- "Executing global query [%s]: '%{private}s' entityTypes: %s limit: %ld"
- "GenerativeSearch"
- "GenerativeSearchGlobalQueryLatency"
- "Query [%s] cancelled during error handling"
- "Query [%s] cancelled with CancellationError"
- "Query [%s] failed: %s"
- "Query [%s] returned %ld results"
- "SPKGenerativeSearchGlobalQuery"
- "SPKGenerativeSearchGlobalQuery Response"
- "Skipping result with unsupported entity type '%s' (id=%s)"
- "[qid=%lu] Cancelling GenerativeSearch GlobalQuery"
- "[qid=%lu] Constructing result sections using %lu results received from GenerativeSearch GlobalQuery."
- "[qid=%lu] Error executing GenerativeSearch GlobalQuery: [%ld] %@"
- "[qid=%lu] No entity types enabled or received 0 results from GenerativeSearch GlobalQuery, returning empty results"
- "com.apple.TVRemoteUIService"
- "gsClient is nil - cannot execute query"
```
