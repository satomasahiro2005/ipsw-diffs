## libLinearAlgebra.dylib

> `/System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libLinearAlgebra.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x114bc` | `0x114e0` | **`+0x24`** |
| `__TEXT.__gcc_except_tab` | `0x178` | `0x170` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2a0` | `0x298` | **`-0x8`** |

### Other Changes

```diff

-1606.0.0.0.0
+1612.0.0.0.0
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorINS_4pairIi6edge_tEEEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIP4edgeEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIP4nodeEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIP8subgraphEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIiEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorINS_4pairIi6edge_tEENS_9allocatorIS3_EEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorINS_4pairIi6edge_tEENS_9allocatorIS3_EEE16__init_with_sizeB9fqe220106IPS3_S8_EEvT_T0_m
+ __ZNSt3__16vectorINS_4pairIi6edge_tEENS_9allocatorIS3_EEE18__insert_with_sizeB9fqe220106INS_17_ClassicAlgPolicyENS_11__wrap_iterIPS3_EESB_EESB_NS9_IPKS3_EET0_T1_l
+ __ZNSt3__16vectorINS_4pairIi6edge_tEENS_9allocatorIS3_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIP4edgeNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIP4nodeNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIP8subgraphNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIiNS_9allocatorIiEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIiNS_9allocatorIiEEE16__init_with_sizeB9fqe220106IPiS5_EEvT_T0_m
+ __ZNSt3__16vectorIiNS_9allocatorIiEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorINS_4pairIi6edge_tEEEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIP4edgeEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIP4nodeEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIP8subgraphEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIiEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorINS_4pairIi6edge_tEENS_9allocatorIS3_EEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorINS_4pairIi6edge_tEENS_9allocatorIS3_EEE16__init_with_sizeB9fqe220100IPS3_S8_EEvT_T0_m
- __ZNSt3__16vectorINS_4pairIi6edge_tEENS_9allocatorIS3_EEE18__insert_with_sizeB9fqe220100INS_17_ClassicAlgPolicyENS_11__wrap_iterIPS3_EESB_EESB_NS9_IPKS3_EET0_T1_l
- __ZNSt3__16vectorINS_4pairIi6edge_tEENS_9allocatorIS3_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIP4edgeNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIP4nodeNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIP8subgraphNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIiNS_9allocatorIiEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIiNS_9allocatorIiEEE16__init_with_sizeB9fqe220100IPiS5_EEvT_T0_m
- __ZNSt3__16vectorIiNS_9allocatorIiEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ _la_dispose : 184 -> 180
~ __ZN5graph8optimizeEPKPFbRS_R8subgraphEi : 160 -> 164
~ __ZL11binary_evalP4la_sP7slice_s : 860 -> 856
~ __ZL10unary_evalP4la_sP7slice_s : 204 -> 200
~ __ZL19copy_to_user_bufferP4la_s14la_transpose_tS0_P9storage_s : 2020 -> 2028
~ __ZL16build_eval_graphR5graphR8subgraphR4node : 828 -> 824
~ __ZL9eval_predP4la_sP7slice_slPS0_S2_PbS3_ : 352 -> 344
~ __ZL6factorR5graphR8subgraph : 1880 -> 1888
~ __ZL17merge_product_sumR5graphR8subgraph : 1224 -> 1220
~ __ZN8subgraph19removeEdgeWithIndexEi : 76 -> 108
~ __ZNSt3__16vectorINS_4pairIi6edge_tEENS_9allocatorIS3_EEE18__insert_with_sizeB9fqe220100INS_17_ClassicAlgPolicyENS_11__wrap_iterIPS3_EESB_EESB_NS9_IPKS3_EET0_T1_l -> __ZNSt3__16vectorINS_4pairIi6edge_tEENS_9allocatorIS3_EEE18__insert_with_sizeB9fqe220106INS_17_ClassicAlgPolicyENS_11__wrap_iterIPS3_EESB_EESB_NS9_IPKS3_EET0_T1_l : 576 -> 584
~ _la_splat_from_vector_element : 616 -> 612
~ _la_matrix_to_float_buffer : 628 -> 620
~ _la_matrix_to_double_buffer : 628 -> 620
~ _dGeneralToGeneralStorage : 356 -> 364
~ _slice_for_product : 120 -> 116
~ _slice_for_outer_product : 172 -> 168
~ _copy_packed_diagonal : 656 -> 664
~ _copy_identity : 696 -> 712
~ _getGeneralSliceFromGeneral : 944 -> 948
~ _la_vector_to_float_buffer : 456 -> 460
~ _la_vector_to_double_buffer : 456 -> 460
~ _eval_solve_top : 3700 -> 3668
~ _getOperandWorkingStorage : 392 -> 388
~ _eval_inf_norm : 476 -> 484
~ _eval_l1_norm : 436 -> 452
~ _eval_product_add : 1304 -> 1300
~ __ZN8subgraph10updateCostER5graph : 292 -> 300
~ __ZN8subgraph8evaluateER5graph : 2296 -> 2252
~ __ZN8subgraph10removeNodeER5graphR4node : 604 -> 628
~ __ZN8subgraph19moveOutEdgesToNewSGER5graphRS_R4node : 208 -> 220
~ __ZN8subgraph13mergeWithSuccER5graph : 560 -> 572
~ __ZNSt3__16vectorINS_4pairIi6edge_tEENS_9allocatorIS3_EEE6insertENS_11__wrap_iterIPKS3_EEOS3_ : 468 -> 460
```
