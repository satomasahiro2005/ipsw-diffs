## SafariSafeBrowsing

> `/System/Library/PrivateFrameworks/SafariSafeBrowsing.framework/SafariSafeBrowsing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x84028` | `0x83e8c` | **`-0x19c`** |
| `__AUTH.__objc_data` | `0x3b8` | `0x548` | **`+0x190`** |
| `__DATA_DIRTY.__objc_data` | `0x410` | `0x280` | **`-0x190`** |
| `__DATA_DIRTY.__bss` | `0x3c8` | `0x370` | **`-0x58`** |
| `__DATA.__bss` | `0x150` | `0x1a0` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x300` | `0x310` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4018` | `0x4008` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x8ba8` | `0x8ba4` | **`-0x4`** |

### Other Changes

```diff

-625.1.20.10.3
+625.1.22.10.3
Functions:
~ __ZN7Backend6Google16computePathPartsENSt3__111__wrap_iterIPKhEES5_S5_S5_ : 488 -> 476
~ __ZN7Backend6Google20computeHostNamePartsENSt3__111__wrap_iterIPKhEES5_b : 676 -> 668
~ __ZN7Backend6Google13percentEscapeERNSt3__16vectorIhNS1_9allocatorIhEEEE : 536 -> 532
~ -[_SSBServiceStatus activeTransactions] : 224 -> 216
~ __ZNSt3__135__uninitialized_allocator_copy_implB9sqn220106INS_9allocatorIN7Backend6Google12DatabaseInfoEEEPS4_S6_S6_EET2_RT_T0_T1_S7_ : 196 -> 180
~ __ZN7Backend6Google20DatabaseUpdateWriter19writeHashSizeBucketEhNS0_12HashIteratorES2_S2_S2_ : 676 -> 660
~ __ZNK7Backend6Google39FetchThreatListUpdatesRequestSerializer14serializedDataEv : 340 -> 332
~ __ZNK7Backend6Google13FullHashCache6lookupERKNSt3__15arrayIhLm32EEEh : 444 -> 436
~ __ZN7Backend6Google13FullHashCache20expirationTimerFiredEv : 852 -> 828
~ __ZNSt3__134__uninitialized_allocator_relocateB9sqn220106INS_9allocatorIN7Backend6Google20HashesSearchResponse8FullHash14FullHashDetailEEEPS6_EEvRT_T0_SB_SB_ : 160 -> 144
~ ____ZN7Backend6Google15FullHashFetcher11fetchHashesENSt3__16vectorINS0_15FullHashRequestENS2_9allocatorIS4_EEEEPU24objcproto13OS_xpc_object8NSObjectP18ProxyConfigurationPU28objcproto17OS_dispatch_queueS8_NS2_8functionIFvNS2_8optionalINS2_7variantIJNS0_22FindFullHashesResponseENS0_20HashesSearchResponseEEEEEEEEE_block_invoke : 2276 -> 2240
~ __ZNSt3__134__uninitialized_allocator_relocateB9sqn220106INS_9allocatorIN12SafeBrowsing13ServiceStatus10ConnectionEEEPS4_EEvRT_T0_S9_S9_ : 152 -> 136
~ __ZN7Backend14ListManagement14DiffApplicator15computeChecksumERKNSt3__16vectorINS2_12basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEENS7_IS9_EEEE : 320 -> 308
~ __ZN7Backend14ListManagement14DiffApplicator23computeManifestChecksumERKNSt3__16vectorINS0_10FileUpdateENS2_9allocatorIS4_EEEE : 436 -> 420
~ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERNS_7greaterImEEPmLb1EEEvT1_S6_T0_NS_15iterator_traitsIS6_E15difference_typeEb : 1432 -> 1424
~ __ZNSt3__127__insertion_sort_incompleteB9sqn220106INS_17_ClassicAlgPolicyERNS_7greaterImEEPmEEbT1_S6_T0_ : 656 -> 640
~ __ZNSt3__116__insertion_sortB9sqn220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEEvT1_SC_T0_ : 324 -> 276
~ __ZNSt3__127__insertion_sort_incompleteB9sqn220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEEbT1_SC_T0_ : 1116 -> 1072
~ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERZN7Backend14ListManagement14DiffApplicator23computeManifestChecksumERKNS_6vectorINS3_10FileUpdateENS_9allocatorIS6_EEEEE3$_0PS6_Lb0EEEvT1_SF_T0_NS_15iterator_traitsISF_E15difference_typeEb : 6052 -> 6088
~ __ZNSt3__127__insertion_sort_incompleteB9sqn220106INS_17_ClassicAlgPolicyERZN7Backend14ListManagement14DiffApplicator23computeManifestChecksumERKNS_6vectorINS3_10FileUpdateENS_9allocatorIS6_EEEEE3$_0PS6_EEbT1_SF_T0_ : 1072 -> 1040
~ __ZNK12SafeBrowsing13SafeHashCache11containsAllERKNSt3__16vectorINS1_5arrayIhLm32EEENS1_9allocatorIS4_EEEE : 156 -> 140
~ __ZNSt3__16__treeINS_12__value_typeINS_5arrayIhLm32EEENS_15__list_iteratorIS3_PvEEEENS_19__map_value_compareIS3_NS_4pairIKS3_S6_EENS_4lessIS3_EEEENS_9allocatorISB_EEE12__find_equalB9sqn220106IS3_EENS9_IPNS_15__tree_end_nodeIPNS_16__tree_node_baseIS5_EEEERSM_EERKT_ : 156 -> 148
~ __ZNKSt3__16__treeINS_12__value_typeINS_5arrayIhLm32EEENS_15__list_iteratorIS3_PvEEEENS_19__map_value_compareIS3_NS_4pairIKS3_S6_EENS_4lessIS3_EEEENS_9allocatorISB_EEE14__count_uniqueIS3_EEmRKT_ : 132 -> 120
~ __ZN12SafeBrowsing7Service25initializeDatabaseManagerERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEERKNS1_6vectorIS7_NS5_IS7_EEEEN7Backend6Google21DatabaseConfigurationE : 1364 -> 1340
~ __ZN12SafeBrowsing7Service22handleGetServiceStatusEPU24objcproto13OS_xpc_object8NSObject : 708 -> 696
~ __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9sqn220106EPKvm : 532 -> 520
~ sub_29adfed38 -> sub_291b55bac : 624 -> 616
~ sub_29adfefa8 -> sub_291b55e14 : 800 -> 792
```
