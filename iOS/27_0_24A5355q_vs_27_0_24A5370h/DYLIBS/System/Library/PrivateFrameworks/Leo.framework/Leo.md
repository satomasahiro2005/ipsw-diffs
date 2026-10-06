## Leo

> `/System/Library/PrivateFrameworks/Leo.framework/Leo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x1600` | `0x1480` | **`-0x180`** |
| `__TEXT.__cstring` | `0xaea9` | `0xade5` | **`-0xc4`** |
| `__TEXT.__text` | `0x3d584` | `0x3d610` | **`+0x8c`** |
| `__TEXT.__const` | `0x1ad0` | `0x1a50` | **`-0x80`** |
| `__TEXT.__eh_frame` | `0x2a50` | `0x2a00` | **`-0x50`** |
| `__AUTH_CONST.__auth_got` | `0xde0` | `0xe10` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x1358` | `0x1330` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x1530` | `0x1508` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1a40` | `0x1a60` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x922` | `0x906` | **`-0x1c`** |
| `__TEXT.__swift5_reflstr` | `0x70e` | `0x71e` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xd8` | `0xcc` | **`-0xc`** |
| `__TEXT.__swift5_typeref` | `0x8f8` | `0x900` | **`+0x8`** |
| `__TEXT.__swift5_fieldmd` | `0x8d4` | `0x8d0` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x90` | `0x8c` | **`-0x4`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

+  - /System/Library/PrivateFrameworks/PhotoFoundation.framework/PhotoFoundation

-  Functions: 1787
-  Symbols:   1174
-  CStrings:  363
+  Functions: 1769
+  Symbols:   1176
+  CStrings:  361
Symbols:
+ _OUTLINED_FUNCTION_101
+ _OUTLINED_FUNCTION_102
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt12out_of_rangeC1B9fqe220106EPKc
+ __ZNSt3__111__sift_downB9fqe220106INS_17_ClassicAlgPolicyELb0ERNS_6__lessIvvEEPNS_4pairIjjEEEEvT2_OT1_NS_15iterator_traitsIS8_E15difference_typeESD_
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220106ILi0EEEPKc
+ __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE15__init_buf_ptrsB9fqe220106Ev
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorINS_10shared_ptrIN4axis9Polygon2DEEEEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220106Ev
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__120__throw_out_of_rangeB9fqe220106EPKc
+ __ZNSt3__122__hash_node_destructorINS_9allocatorINS_11__hash_nodeINS_17__hash_value_typeIjNS_6vectorItNS1_ItEEEEEEPvEEEEEclB9fqe220106EPS9_
+ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_4pairIjjEEEEbT1_S8_T0_
+ __ZNSt3__16__treeImNS_4lessImEENS_9allocatorImEEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeImPvEE
+ __ZNSt3__16vectorI12_LEORPNTokenNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI27LEOItemFetchedLexemeDetailsNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS_10shared_ptrIN4axis6Ring2DEEENS_9allocatorIS4_EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorINS_10shared_ptrIN4axis6Ring2DEEENS_9allocatorIS4_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS_10shared_ptrIN4axis9Polygon2DEEENS_9allocatorIS4_EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorINS_10shared_ptrIN4axis9Polygon2DEEENS_9allocatorIS4_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS_4pairIjjEENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS_9monostateENS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIbNS_9allocatorIbEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorItNS_9allocatorItEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__17__sort3B9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_4pairIjjEELi0EEEbT1_S8_S8_T0_
+ __ZNSt3__17__sort5B9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_4pairIjjEELi0EEEvT1_S8_S8_S8_S8_T0_
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIjjEENS_22__unordered_map_hasherIjNS_4pairIKjjEENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS6_SA_S8_EENS_9allocatorIS6_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS5_EEENSL_IJEEEEEENS4_INS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSM_SK_OSN_OSO_E_clESM_SK_SZ_S10_
+ _objc_retain_x9
+ _sqlite3_carray_bind_v2
+ _symbolic Say_____G s5Int32V
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5Int32V
+ _symbolic _____y______G 3Leo16AttributeContextC16UnsafeBlobBufferV 15PhotoFoundation14Float16StorageV
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt12out_of_rangeC1B9fqe220100EPKc
- __ZNSt3__111__sift_downB9fqe220100INS_17_ClassicAlgPolicyELb0ERNS_6__lessIvvEEPNS_4pairIjjEEEEvT2_OT1_NS_15iterator_traitsIS8_E15difference_typeESD_
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220100ILi0EEEPKc
- __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE15__init_buf_ptrsB9fqe220100Ev
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorINS_10shared_ptrIN4axis9Polygon2DEEEEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220100Ev
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__120__throw_out_of_rangeB9fqe220100EPKc
- __ZNSt3__122__hash_node_destructorINS_9allocatorINS_11__hash_nodeINS_17__hash_value_typeIjNS_6vectorItNS1_ItEEEEEEPvEEEEEclB9fqe220100EPS9_
- __ZNSt3__127__insertion_sort_incompleteB9fqe220100INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_4pairIjjEEEEbT1_S8_T0_
- __ZNSt3__16__treeImNS_4lessImEENS_9allocatorImEEE14__tree_deleterclB9fqe220100EPNS_11__tree_nodeImPvEE
- __ZNSt3__16vectorI12_LEORPNTokenNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI27LEOItemFetchedLexemeDetailsNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorINS_10shared_ptrIN4axis6Ring2DEEENS_9allocatorIS4_EEE16__destroy_vectorclB9fqe220100Ev
- __ZNSt3__16vectorINS_10shared_ptrIN4axis6Ring2DEEENS_9allocatorIS4_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorINS_10shared_ptrIN4axis9Polygon2DEEENS_9allocatorIS4_EEE16__destroy_vectorclB9fqe220100Ev
- __ZNSt3__16vectorINS_10shared_ptrIN4axis9Polygon2DEEENS_9allocatorIS4_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorINS_4pairIjjEENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorINS_9monostateENS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIbNS_9allocatorIbEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorItNS_9allocatorItEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__17__sort3B9fqe220100INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_4pairIjjEELi0EEEbT1_S8_S8_T0_
- __ZNSt3__17__sort5B9fqe220100INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_4pairIjjEELi0EEEvT1_S8_S8_S8_S8_T0_
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIjjEENS_22__unordered_map_hasherIjNS_4pairIKjjEENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS6_SA_S8_EENS_9allocatorIS6_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS5_EEENSL_IJEEEEEENS4_INS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSM_SK_OSN_OSO_E_clESM_SK_SZ_S10_
- _associated conformance 3Leo14Float16StorageVSHAASQ
- _symbolic _____ 3Leo14Float16StorageV
- _symbolic _____ s6UInt16V
- _symbolic _____y______G 3Leo16AttributeContextC16UnsafeBlobBufferV AA14Float16StorageV
- _type_layout_string 3Leo14Float16StorageV
CStrings:
+ "DELETE FROM lexicon WHERE lexeme_id NOT IN "
+ "RecencyType"
- "CREATE TEMPORARY TABLE IF NOT EXISTS used_lexemes (lexeme_id INT UNIQUE)"
- "DELETE FROM lexicon WHERE lexeme_id NOT IN (SELECT lexeme_id FROM used_lexemes)"
- "DROP TABLE IF EXISTS used_lexemes"
- "INSERT OR IGNORE INTO used_lexemes VALUES (?)"
```
