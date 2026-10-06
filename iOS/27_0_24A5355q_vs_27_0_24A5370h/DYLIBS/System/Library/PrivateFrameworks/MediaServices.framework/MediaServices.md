## MediaServices

> `/System/Library/PrivateFrameworks/MediaServices.framework/MediaServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x598cc` | `0x59e48` | **`+0x57c`** |
| `__AUTH_CONST.__objc_const` | `0x9bf0` | `0x9cc8` | **`+0xd8`** |
| `__TEXT.__cstring` | `0x5f95` | `0x6023` | **`+0x8e`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f48` | `0x2fb0` | **`+0x68`** |
| `__AUTH_CONST.__cfstring` | `0x59c0` | `0x5a20` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x5744` | `0x5784` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x2c82` | `0x2c42` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x14a0` | `0x14c8` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x6ac` | `0x6c4` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x16d0` | `0x16e8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x107c` | `0x1090` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x680` | `0x688` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x250` | `0x258` | **`+0x8`** |
| `__DATA.__bss` | `0x248` | `0x244` | **`-0x4`** |

### Other Changes

```diff

-4026.100.38.0.0
+4026.100.65.0.0

+  - /System/Library/PrivateFrameworks/Trial.framework/Trial

-  Functions: 2111
-  Symbols:   4426
-  CStrings:  1116
+  Functions: 2117
+  Symbols:   4442
+  CStrings:  1119
Symbols:
+ -[MSVArtworkServiceRequest qualityOfService]
+ -[MSVArtworkServiceRequest setQualityOfService:]
+ -[MSVTrialExperiment .cxx_destruct]
+ -[MSVTrialExperiment identifiers]
+ -[MSVTrialExperiment initWithNamespaceName:]
+ GCC_except_table1017
+ GCC_except_table1125
+ GCC_except_table1209
+ GCC_except_table1217
+ GCC_except_table1223
+ GCC_except_table1273
+ GCC_except_table1425
+ GCC_except_table1456
+ GCC_except_table1460
+ GCC_except_table1461
+ GCC_except_table1464
+ GCC_except_table1465
+ GCC_except_table1469
+ GCC_except_table1476
+ GCC_except_table1478
+ GCC_except_table1481
+ GCC_except_table1486
+ GCC_except_table1554
+ GCC_except_table1566
+ GCC_except_table1568
+ GCC_except_table1599
+ GCC_except_table1602
+ GCC_except_table1603
+ GCC_except_table1607
+ GCC_except_table1616
+ GCC_except_table1640
+ GCC_except_table1649
+ GCC_except_table1653
+ GCC_except_table1657
+ GCC_except_table1698
+ GCC_except_table1882
+ GCC_except_table2014
+ GCC_except_table2051
+ GCC_except_table2067
+ GCC_except_table2068
+ GCC_except_table2069
+ GCC_except_table419
+ GCC_except_table427
+ GCC_except_table703
+ GCC_except_table723
+ GCC_except_table834
+ GCC_except_table856
+ GCC_except_table860
+ GCC_except_table867
+ GCC_except_table873
+ _OBJC_CLASS_$_TRIClient
+ _OBJC_IVAR_$_MSVArtworkServiceRequest._qualityOfService
+ _OBJC_IVAR_$_MSVTrialExperiment._identifiers
+ _OBJC_IVAR_$_MSVTrialExperiment._identifiersFetched
+ _OBJC_IVAR_$_MSVTrialExperiment._lock
+ _OBJC_IVAR_$_MSVTrialExperiment._namespaceName
+ _OBJC_IVAR_$_MSVTrialExperiment._trialClient
+ __OBJC_$_INSTANCE_VARIABLES_MSVTrialExperiment
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__111__sift_downB9fqe220106INS_17_ClassicAlgPolicyELb0ERPFb14sortColorEntryS2_EPS2_EEvT2_OT1_NS_15iterator_traitsIS7_E15difference_typeESC_
+ __ZNSt3__111__sift_downB9fqe220106INS_17_ClassicAlgPolicyELb0ERPFb22sortQuantizeColorEntryS2_EPS2_EEvT2_OT1_NS_15iterator_traitsIS7_E15difference_typeESC_
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorI7ITColorEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIdEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERPFb14sortColorEntryS2_EPS2_EEbT1_S7_T0_
+ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERPFb22sortQuantizeColorEntryS2_EPS2_EEbT1_S7_T0_
+ __ZNSt3__16vectorI14sortColorEntryNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI22sortQuantizeColorEntryNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI7ITColorNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIdNS_9allocatorIdEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__17__sort4B9fqe220106INS_17_ClassicAlgPolicyERPFb14sortColorEntryS2_EPS2_Li0EEEvT1_S7_S7_S7_T0_
+ __ZNSt3__17__sort4B9fqe220106INS_17_ClassicAlgPolicyERPFb22sortQuantizeColorEntryS2_EPS2_Li0EEEvT1_S7_S7_S7_T0_
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___44-[MSVTrialExperiment initWithNamespaceName:]_block_invoke
+ ___block_descriptor_48_e8_32s40w_e38_v16?0"<TRINamespaceUpdateProtocol>"8ls32l8w40l8
- GCC_except_table1015
- GCC_except_table1123
- GCC_except_table1207
- GCC_except_table1215
- GCC_except_table1219
- GCC_except_table1413
- GCC_except_table1449
- GCC_except_table1450
- GCC_except_table1452
- GCC_except_table1454
- GCC_except_table1457
- GCC_except_table1459
- GCC_except_table1466
- GCC_except_table1470
- GCC_except_table1474
- GCC_except_table1475
- GCC_except_table1548
- GCC_except_table1560
- GCC_except_table1562
- GCC_except_table1593
- GCC_except_table1596
- GCC_except_table1597
- GCC_except_table1601
- GCC_except_table1610
- GCC_except_table1634
- GCC_except_table1643
- GCC_except_table1647
- GCC_except_table1651
- GCC_except_table1692
- GCC_except_table1876
- GCC_except_table2008
- GCC_except_table2045
- GCC_except_table2061
- GCC_except_table2062
- GCC_except_table2063
- GCC_except_table417
- GCC_except_table425
- GCC_except_table701
- GCC_except_table721
- GCC_except_table832
- GCC_except_table836
- GCC_except_table858
- GCC_except_table865
- GCC_except_table871
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__111__sift_downB9fqe220100INS_17_ClassicAlgPolicyELb0ERPFb14sortColorEntryS2_EPS2_EEvT2_OT1_NS_15iterator_traitsIS7_E15difference_typeESC_
- __ZNSt3__111__sift_downB9fqe220100INS_17_ClassicAlgPolicyELb0ERPFb22sortQuantizeColorEntryS2_EPS2_EEvT2_OT1_NS_15iterator_traitsIS7_E15difference_typeESC_
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorI7ITColorEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIdEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__127__insertion_sort_incompleteB9fqe220100INS_17_ClassicAlgPolicyERPFb14sortColorEntryS2_EPS2_EEbT1_S7_T0_
- __ZNSt3__127__insertion_sort_incompleteB9fqe220100INS_17_ClassicAlgPolicyERPFb22sortQuantizeColorEntryS2_EPS2_EEbT1_S7_T0_
- __ZNSt3__16vectorI14sortColorEntryNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI22sortQuantizeColorEntryNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI7ITColorNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIdNS_9allocatorIdEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__17__sort4B9fqe220100INS_17_ClassicAlgPolicyERPFb14sortColorEntryS2_EPS2_Li0EEEvT1_S7_S7_S7_T0_
- __ZNSt3__17__sort4B9fqe220100INS_17_ClassicAlgPolicyERPFb22sortQuantizeColorEntryS2_EPS2_Li0EEEvT1_S7_S7_S7_T0_
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
CStrings:
+ "%lld"
+ "<%@: %p No experiment>"
+ "<%@: %p experimentID:%@ treatmentID:%@ deploymentID:%ld>"
+ "MSVArtworkServiceRequestQualityOfService"
+ "v16@?0@\"<TRINamespaceUpdateProtocol>\"8"
- "<%@: %p Not supported>"
- "MSVTrialExperiment is currently not supported on this platform."
```
