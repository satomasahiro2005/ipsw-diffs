## CoreAudioKit

> `/System/Library/Frameworks/CoreAudioKit.framework/CoreAudioKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf632c` | `0xf6890` | **`+0x564`** |
| `__TEXT.__const` | `0x4e0a` | `0x4e4a` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x158c4` | `0x158e6` | **`+0x22`** |
| `__DATA.__data` | `0x3ac8` | `0x3ae8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xa68` | `0xa88` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2718` | `0x2730` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2948` | `0x2960` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x16b8` | `0x16c8` | **`+0x10`** |
| `__DATA.__bss` | `0x2a80` | `0x2a90` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2073` | `0x2083` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x21e0` | `0x21ec` | **`+0xc`** |
| `__TEXT.__oslogstring` | `0x4c5` | `0x4c4` | **`-0x1`** |

### Other Changes

```diff

-292.0.0.0.0
+294.0.0.0.0

-  Functions: 3558
-  Symbols:   3330
+  Functions: 3565
+  Symbols:   3333
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__110unique_ptrI19NetworkDriverRTDataNS_14default_deleteIS1_EEE5resetB9fqe220106EPS1_
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__114__split_bufferINS_10unique_ptrIN19NetworkDriverRTData12LatencyEventENS_14default_deleteIS3_EEEERNS_9allocatorIS6_EEE17__destruct_at_endB9fqe220106EPS6_
+ __ZNSt3__116__if_likely_elseB9fqe220106IZNS_6vectorIN19NetworkDriverRTData12LatencyEventENS_9allocatorIS3_EEE12emplace_backIJRKS3_EEERS3_DpOT_EUlvE_ZNS7_IJS9_EEESA_SD_EUlvE0_EEvbT_T0_
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIN19NetworkDriverRTData12LatencyEventEEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorINS_10unique_ptrIN19NetworkDriverRTData12LatencyEventENS_14default_deleteIS4_EEEEEENS_16allocator_traitsIS8_EEEENS_19__allocation_resultINT0_7pointerENSC_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERZ43-[NetworkDriverAdapter deviceErrorsChanged]E3$_1PZ43-[NetworkDriverAdapter deviceErrorsChanged]E10ErrorEntryEEbT1_S6_T0_
+ __ZNSt3__16vectorIN19NetworkDriverRTData12LatencyEventENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS_10unique_ptrIN19NetworkDriverRTData12LatencyEventENS_14default_deleteIS3_EEEENS_9allocatorIS6_EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorINS_10unique_ptrIN19NetworkDriverRTData12LatencyEventENS_14default_deleteIS3_EEEENS_9allocatorIS6_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS_10unique_ptrIN19NetworkDriverRTData12LatencyEventENS_14default_deleteIS3_EEEENS_9allocatorIS6_EEE22__base_destruct_at_endB9fqe220106EPS6_
+ __ZNSt3__16vectorIZ43-[NetworkDriverAdapter deviceErrorsChanged]E10ErrorEntryNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIZ43-[NetworkDriverAdapter deviceErrorsChanged]E10ErrorEntryNS_9allocatorIS1_EEED1B9fqe220106Ev
+ __ZNSt3__17__sort3B9fqe220106INS_17_ClassicAlgPolicyERZ43-[NetworkDriverAdapter deviceErrorsChanged]E3$_1PZ43-[NetworkDriverAdapter deviceErrorsChanged]E10ErrorEntryLi0EEEbT1_S6_S6_T0_
+ __ZNSt3__17__sort5B9fqe220106INS_17_ClassicAlgPolicyERZ43-[NetworkDriverAdapter deviceErrorsChanged]E3$_1PZ43-[NetworkDriverAdapter deviceErrorsChanged]E10ErrorEntryLi0EEEvT1_S6_S6_S6_S6_T0_
+ __ZNSt3__19iter_swapB9fqe220106IPZ43-[NetworkDriverAdapter deviceErrorsChanged]E10ErrorEntryS2_EEvT_T0_
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ _symbolic _____ 10Foundation6LocaleV
+ _symbolic _____y_____G 7SwiftUI11EnvironmentV 10Foundation6LocaleV
+ _symbolic _____y______G 7SwiftUI11EnvironmentV7ContentO 10Foundation6LocaleV
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__110unique_ptrI19NetworkDriverRTDataNS_14default_deleteIS1_EEE5resetB9fqe220100EPS1_
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__114__split_bufferINS_10unique_ptrIN19NetworkDriverRTData12LatencyEventENS_14default_deleteIS3_EEEERNS_9allocatorIS6_EEE17__destruct_at_endB9fqe220100EPS6_
- __ZNSt3__116__if_likely_elseB9fqe220100IZNS_6vectorIN19NetworkDriverRTData12LatencyEventENS_9allocatorIS3_EEE12emplace_backIJRKS3_EEERS3_DpOT_EUlvE_ZNS7_IJS9_EEESA_SD_EUlvE0_EEvbT_T0_
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIN19NetworkDriverRTData12LatencyEventEEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorINS_10unique_ptrIN19NetworkDriverRTData12LatencyEventENS_14default_deleteIS4_EEEEEENS_16allocator_traitsIS8_EEEENS_19__allocation_resultINT0_7pointerENSC_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__127__insertion_sort_incompleteB9fqe220100INS_17_ClassicAlgPolicyERZ43-[NetworkDriverAdapter deviceErrorsChanged]E3$_1PZ43-[NetworkDriverAdapter deviceErrorsChanged]E10ErrorEntryEEbT1_S6_T0_
- __ZNSt3__16vectorIN19NetworkDriverRTData12LatencyEventENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorINS_10unique_ptrIN19NetworkDriverRTData12LatencyEventENS_14default_deleteIS3_EEEENS_9allocatorIS6_EEE16__destroy_vectorclB9fqe220100Ev
- __ZNSt3__16vectorINS_10unique_ptrIN19NetworkDriverRTData12LatencyEventENS_14default_deleteIS3_EEEENS_9allocatorIS6_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorINS_10unique_ptrIN19NetworkDriverRTData12LatencyEventENS_14default_deleteIS3_EEEENS_9allocatorIS6_EEE22__base_destruct_at_endB9fqe220100EPS6_
- __ZNSt3__16vectorIZ43-[NetworkDriverAdapter deviceErrorsChanged]E10ErrorEntryNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIZ43-[NetworkDriverAdapter deviceErrorsChanged]E10ErrorEntryNS_9allocatorIS1_EEED1B9fqe220100Ev
- __ZNSt3__17__sort3B9fqe220100INS_17_ClassicAlgPolicyERZ43-[NetworkDriverAdapter deviceErrorsChanged]E3$_1PZ43-[NetworkDriverAdapter deviceErrorsChanged]E10ErrorEntryLi0EEEbT1_S6_S6_T0_
- __ZNSt3__17__sort5B9fqe220100INS_17_ClassicAlgPolicyERZ43-[NetworkDriverAdapter deviceErrorsChanged]E3$_1PZ43-[NetworkDriverAdapter deviceErrorsChanged]E10ErrorEntryLi0EEEvT1_S6_S6_S6_S6_T0_
- __ZNSt3__19iter_swapB9fqe220100IPZ43-[NetworkDriverAdapter deviceErrorsChanged]E10ErrorEntryS2_EEvT_T0_
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
```
