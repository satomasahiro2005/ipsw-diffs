## AppleNeuralEngine

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/AppleNeuralEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x545e8` | `0x54de8` | **`+0x800`** |
| `__DATA_CONST.__const` | `0x890` | `0x908` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0xb365` | `0xb3d8` | **`+0x73`** |
| `__AUTH_CONST.__objc_const` | `0x3c48` | `0x3c70` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x13a8` | `0x13d0` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x654c` | `0x6570` | **`+0x24`** |
| `__TEXT.__objc_methlist` | `0x2aec` | `0x2b0c` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x19c0` | `0x19d0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2f0` | `0x2f8` | **`+0x8`** |
| `__TEXT.__cstring` | `0x36f0` | `0x36ee` | **`-0x2`** |

### Other Changes

```diff

-382.7.4.0.0
+382.9.0.0.0

-  Functions: 1690
-  Symbols:   2215
-  CStrings:  1388
+  Functions: 1698
+  Symbols:   2223
+  CStrings:  1390
Symbols:
+ +[_ANEErrors requestCancelledErrorForMethod:]
+ -[_ANEClient compiledModelExistsInCacheFor:]
+ -[_ANEDaemonConnection compiledModelExistsInCacheFor:withReply:]
+ GCC_except_table67
+ __ZNKSt9type_infoeqB9fqe220106ERKS_
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__110unique_ptrINS_11__hash_nodeINS_17__hash_value_typeIy25MutableWeightsBufferEntryEEPvEENS_22__hash_node_destructorINS_9allocatorIS6_EEEEED1B9fqe220106Ev
+ __ZNSt3__112__hash_tableINS_17__hash_value_typeIy25MutableWeightsBufferEntryEENS_22__unordered_map_hasherIyNS_4pairIKyS2_EENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS7_SB_S9_EENS_9allocatorIS7_EEE22__deallocate_node_listB9fqe220106EPNS_16__hash_node_baseIPNS_11__hash_nodeIS3_PvEEEE
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220106Ev
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIy19MutableWeightsEntryEENS_22__unordered_map_hasherIyNS_4pairIKyS2_EENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIy25MutableWeightsBufferEntryEENS_22__unordered_map_hasherIyNS_4pairIKyS2_EENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
+ ___44-[_ANEClient compiledModelExistsInCacheFor:]_block_invoke
+ ___44-[_ANEClient compiledModelExistsInCacheFor:]_block_invoke_2
+ ___64-[_ANEDaemonConnection compiledModelExistsInCacheFor:withReply:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e20_v20?0B8"NSError"12ls32l8s40l8
+ ___block_descriptor_56_e8_32s40r_e20_v20?0B8"NSError"12lr40l8s32l8
+ ___block_descriptor_64_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
- +[_ANEStrings vm_tmpBaseDirectory]
- GCC_except_table76
- __ZNKSt9type_infoeqB9fqe220100ERKS_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__110unique_ptrINS_11__hash_nodeINS_17__hash_value_typeIy25MutableWeightsBufferEntryEEPvEENS_22__hash_node_destructorINS_9allocatorIS6_EEEEED1B9fqe220100Ev
- __ZNSt3__112__hash_tableINS_17__hash_value_typeIy25MutableWeightsBufferEntryEENS_22__unordered_map_hasherIyNS_4pairIKyS2_EENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS7_SB_S9_EENS_9allocatorIS7_EEE22__deallocate_node_listB9fqe220100EPNS_16__hash_node_baseIPNS_11__hash_nodeIS3_PvEEEE
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220100Ev
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIy19MutableWeightsEntryEENS_22__unordered_map_hasherIyNS_4pairIKyS2_EENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIy25MutableWeightsBufferEntryEENS_22__unordered_map_hasherIyNS_4pairIKyS2_EENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
CStrings:
+ "%@: Request cancelled"
+ "[proxy compiledModelExistsInCacheFor:%@ ...] returned exists = %d with error = %@"
+ "compiledModelExistsInCacheFor:%@"
- "/var/tmp/com.apple.ane/"
```
