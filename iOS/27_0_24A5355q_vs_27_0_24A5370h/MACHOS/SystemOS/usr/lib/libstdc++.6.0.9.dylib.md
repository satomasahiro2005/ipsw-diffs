## libstdc++.6.0.9.dylib

> `/usr/lib/libstdc++.6.0.9.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4bb78` | `0x4b9e0` | **`-0x198`** |
| `__TEXT.__gcc_except_tab` | `0x394c` | `0x3958` | **`+0xc`** |

### Same-size Content Changes

- `__AUTH_CONST.__const`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 2383
+  Functions: 2382
Functions:
~ __ZN9__gnu_cxx17__pool_alloc_base9_M_refillEm : 144 -> 136
~ __ZN9__gnu_cxx17__pool_alloc_base17_M_allocate_chunkEmRi : 400 -> 392
~ __ZN9__gnu_cxx6__poolILb1EE16_M_reserve_blockEmm : 400 -> 404
~ __ZN9__gnu_cxx6__poolILb1EE16_M_reclaim_blockEPcm : 400 -> 404
~ __ZN9__gnu_cxx6__poolILb0EE13_M_initializeEv : 236 -> 228
~ __ZN9__gnu_cxx6__poolILb1EE13_M_initializeEv : 704 -> 708
~ __ZN12_GLOBAL__N_121_M_destroy_thread_keyEPv : 88 -> 100
~ __ZN9__gnu_cxx6__poolILb1EE13_M_initializeEPFvPvE : 704 -> 708
~ __ZNSt6locale5_Impl18_M_check_same_nameEv : 112 -> 108
~ __ZNKSt5ctypeIcE7scan_isEmPKcS2_ : 220 -> 212
~ __ZNKSt5ctypeIcE8scan_notEmPKcS2_ : 220 -> 212
~ __ZStlsIfcSt11char_traitsIcEERSt13basic_ostreamIT0_T1_ES6_RKSt7complexIT_E : 624 -> 628
~ __ZStlsIdcSt11char_traitsIcEERSt13basic_ostreamIT0_T1_ES6_RKSt7complexIT_E : 616 -> 620
~ __ZStlsIecSt11char_traitsIcEERSt13basic_ostreamIT0_T1_ES6_RKSt7complexIT_E : 616 -> 620
~ __ZStlsIfwSt11char_traitsIwEERSt13basic_ostreamIT0_T1_ES6_RKSt7complexIT_E : 748 -> 752
~ __ZStlsIdwSt11char_traitsIwEERSt13basic_ostreamIT0_T1_ES6_RKSt7complexIT_E : 740 -> 744
~ __ZStlsIewSt11char_traitsIwEERSt13basic_ostreamIT0_T1_ES6_RKSt7complexIT_E : 740 -> 744
~ __ZNK11__gnu_debug16_Error_formatter15_M_print_stringEPKc : 688 -> 696
~ __ZNKSt6locale4nameEv : 500 -> 492
~ __ZNSt6locale5_ImplD2Ev : 324 -> 320
~ __ZNSt6locale5_ImplC2ERKS0_m : 408 -> 384
~ __ZNSt6locale5_Impl19_M_replace_categoryEPKS0_PKPKNS_2idE : 84 -> 76
~ __ZNSt6locale5_Impl16_M_install_facetEPKNS_2idEPKNS_5facetE : 524 -> 508
~ __ZNSt6localeC2EPKc : 1476 -> 1468
~ __ZNSt6locale5_Impl21_M_replace_categoriesEPKS0_i : 356 -> 352
~ __ZNSt6locale5_ImplC2EPKcm : 1980 -> 1992
~ __ZNSt12strstreambuf8_M_setupEPcS0_l : 160 -> 148
~ __ZNSt9basic_iosIcSt11char_traitsIcEE7copyfmtERKS2_ : 400 -> 384
~ __ZNSt9basic_iosIwSt11char_traitsIwEE7copyfmtERKS2_ : 400 -> 384
~ __ZNSi6sentryC2ERSib : 448 -> 444
~ __ZSt2wsIcSt11char_traitsIcEERSt13basic_istreamIT_T0_ES6_ : 344 -> 340
~ __ZStrsIcSt11char_traitsIcEERSt13basic_istreamIT_T0_ES6_PS3_ : 944 -> 904
~ __ZStrsIcSt11char_traitsIcESaIcEERSt13basic_istreamIT_T0_ES7_RSbIS4_S5_T1_E : 916 -> 896
~ __ZNKSt9money_getIcSt19istreambuf_iteratorIcSt11char_traitsIcEEE10_M_extractILb1EEES3_S3_S3_RSt8ios_baseRSt12_Ios_IostateRSs : 2588 -> 2564
~ __ZNKSt9money_getIcSt19istreambuf_iteratorIcSt11char_traitsIcEEE10_M_extractILb0EEES3_S3_S3_RSt8ios_baseRSt12_Ios_IostateRSs : 2588 -> 2564
~ __ZNKSt9money_putIcSt19ostreambuf_iteratorIcSt11char_traitsIcEEE9_M_insertILb1EEES3_S3_RSt8ios_basecRKSs : 1416 -> 1400
~ __ZNKSt9money_putIcSt19ostreambuf_iteratorIcSt11char_traitsIcEEE9_M_insertILb0EEES3_S3_RSt8ios_basecRKSs : 1416 -> 1400
~ __ZStL17__verify_groupingPKcmRKSs : 176 -> 180
~ __ZNKSt7num_getIcSt19istreambuf_iteratorIcSt11char_traitsIcEEE6do_getES3_S3_RSt8ios_baseRSt12_Ios_IostateRb : 596 -> 588
~ __ZNKSt7num_putIcSt19ostreambuf_iteratorIcSt11char_traitsIcEEE6do_putES3_RSt8ios_basecb : 416 -> 408
~ __ZSt13__int_to_charIcmEiPT_T0_PKS0_St13_Ios_Fmtflagsb : 176 -> 168
~ __ZNKSt8time_getIcSt19istreambuf_iteratorIcSt11char_traitsIcEEE21_M_extract_via_formatES3_S3_RSt8ios_baseRSt12_Ios_IostateP2tmPKc : 2524 -> 2508
~ __ZNKSt8time_getIcSt19istreambuf_iteratorIcSt11char_traitsIcEEE14do_get_weekdayES3_S3_RSt8ios_baseRSt12_Ios_IostateP2tm : 684 -> 676
~ __ZNKSt8time_getIcSt19istreambuf_iteratorIcSt11char_traitsIcEEE15_M_extract_nameES3_S3_RiPPKcmRSt8ios_baseRSt12_Ios_Iostate : 848 -> 840
~ __ZNKSt8time_getIcSt19istreambuf_iteratorIcSt11char_traitsIcEEE16do_get_monthnameES3_S3_RSt8ios_baseRSt12_Ios_IostateP2tm : 728 -> 720
~ __ZNKSt8time_getIcSt19istreambuf_iteratorIcSt11char_traitsIcEEE11do_get_yearES3_S3_RSt8ios_baseRSt12_Ios_IostateP2tm : 484 -> 476
~ __ZNKSt8time_getIcSt19istreambuf_iteratorIcSt11char_traitsIcEEE14_M_extract_numES3_S3_RiiimRSt8ios_baseRSt12_Ios_Iostate : 476 -> 472
~ _OUTLINED_FUNCTION_0 : 32 -> 16
~ _OUTLINED_FUNCTION_2 : 56 -> 32
~ _OUTLINED_FUNCTION_8 : 20 -> 60
~ _OUTLINED_FUNCTION_11 : 12 -> 60
~ _OUTLINED_FUNCTION_12 : 44 -> 60
~ _OUTLINED_FUNCTION_13 : 44 -> 12
~ _OUTLINED_FUNCTION_14 : 12 -> 44
~ _OUTLINED_FUNCTION_15 : 60 -> 44
~ _OUTLINED_FUNCTION_16 : 40 -> 44
~ _OUTLINED_FUNCTION_17 : 24 -> 44
~ _OUTLINED_FUNCTION_18 : 24 -> 12
~ _OUTLINED_FUNCTION_19 : 24 -> 28
~ _OUTLINED_FUNCTION_20 : 56 -> 40
~ _OUTLINED_FUNCTION_21 : 56 -> 24
~ _OUTLINED_FUNCTION_23 : 24 -> 36
~ _OUTLINED_FUNCTION_27 : 36 -> 20
~ _OUTLINED_FUNCTION_29 : 20 -> 12
~ _OUTLINED_FUNCTION_33 : 12 -> 20
~ _OUTLINED_FUNCTION_35 : 24 -> 12
~ _OUTLINED_FUNCTION_36 : 32 -> 24
~ _OUTLINED_FUNCTION_38 : 24 -> 32
~ __ZStrsIwSt11char_traitsIwESaIwEERSt13basic_istreamIT_T0_ES7_RSbIS4_S5_T1_E : 780 -> 776
~ __ZN9__gnu_cxx18stdio_sync_filebufIcSt11char_traitsIcEE6xsgetnEPcl : 80 -> 76
~ __ZSt16__ostream_insertIcSt11char_traitsIcEERSt13basic_ostreamIT_T0_ES6_PKS3_l : 896 -> 880
~ __ZSt16__ostream_insertIwSt11char_traitsIwEERSt13basic_ostreamIT_T0_ES6_PKS3_l : 892 -> 876
~ __ZStlsIwSt11char_traitsIwEERSt13basic_ostreamIT_T0_ES6_PKc : 356 -> 360
~ __ZNSt15basic_stringbufIcSt11char_traitsIcESaIcEE7seekoffExSt12_Ios_SeekdirSt13_Ios_Openmode : 376 -> 372
~ __ZNSt15basic_stringbufIcSt11char_traitsIcESaIcEE7seekposESt4fposI11__mbstate_tESt13_Ios_Openmode : 260 -> 256
~ __ZNSt15basic_stringbufIwSt11char_traitsIwESaIwEE7seekoffExSt12_Ios_SeekdirSt13_Ios_Openmode : 388 -> 384
~ __ZNSt15basic_stringbufIwSt11char_traitsIwESaIwEE7seekposESt4fposI11__mbstate_tESt13_Ios_Openmode : 264 -> 260
~ __ZNKSs5rfindEcm : 68 -> 76
~ __ZNKSs13find_first_ofEPKcmm : 128 -> 124
~ __ZNKSs12find_last_ofEPKcmm : 116 -> 112
~ __ZNKSs12find_last_ofEcm : 68 -> 76
~ __ZNKSs17find_first_not_ofERKSsm : 116 -> 112
~ __ZNKSs17find_first_not_ofEPKcmm : 116 -> 112
~ __ZNKSs17find_first_not_ofEPKcm : 128 -> 124
~ __ZNKSs17find_first_not_ofEcm : 60 -> 56
~ __ZNKSs16find_last_not_ofEPKcmm : 116 -> 112
~ __ZNKSs16find_last_not_ofEcm : 68 -> 64
~ __ZSt6searchIPKcS1_PFbRS0_S2_EET_S5_S5_T0_S6_T1_ : 300 -> 328
~ __ZSt17__gslice_to_indexmRKSt8valarrayImES2_RS0_ : 364 -> 352
~ __ZNKSt9money_getIwSt19istreambuf_iteratorIwSt11char_traitsIwEEE10_M_extractILb1EEES3_S3_S3_RSt8ios_baseRSt12_Ios_IostateRSs : 2496 -> 2480
~ __ZNKSt9money_getIwSt19istreambuf_iteratorIwSt11char_traitsIwEEE10_M_extractILb0EEES3_S3_S3_RSt8ios_baseRSt12_Ios_IostateRSs : 2496 -> 2480
~ __ZNKSt9money_putIwSt19ostreambuf_iteratorIwSt11char_traitsIwEEE9_M_insertILb1EEES3_S3_RSt8ios_basewRKSbIwS2_SaIwEE : 1292 -> 1288
~ __ZNKSt9money_putIwSt19ostreambuf_iteratorIwSt11char_traitsIwEEE9_M_insertILb0EEES3_S3_RSt8ios_basewRKSbIwS2_SaIwEE : 1292 -> 1288
~ __ZNKSt7num_getIwSt19istreambuf_iteratorIwSt11char_traitsIwEEE6do_getES3_S3_RSt8ios_baseRSt12_Ios_IostateRb : 592 -> 584
~ __ZNKSt7num_putIwSt19ostreambuf_iteratorIwSt11char_traitsIwEEE6do_putES3_RSt8ios_basewb : 416 -> 408
~ __ZNKSt8time_getIwSt19istreambuf_iteratorIwSt11char_traitsIwEEE14do_get_weekdayES3_S3_RSt8ios_baseRSt12_Ios_IostateP2tm : 684 -> 676
~ __ZNKSt8time_getIwSt19istreambuf_iteratorIwSt11char_traitsIwEEE15_M_extract_nameES3_S3_RiPPKwmRSt8ios_baseRSt12_Ios_Iostate : 840 -> 832
~ __ZNKSt8time_getIwSt19istreambuf_iteratorIwSt11char_traitsIwEEE16do_get_monthnameES3_S3_RSt8ios_baseRSt12_Ios_IostateP2tm : 728 -> 720
~ _OUTLINED_FUNCTION_19 : 28 -> 44
~ _OUTLINED_FUNCTION_20 : 44 -> 12
~ _OUTLINED_FUNCTION_21 : 12 -> 40
~ _OUTLINED_FUNCTION_22 : 40 -> 24
~ _OUTLINED_FUNCTION_25 : 24 -> 36
~ _OUTLINED_FUNCTION_29 : 36 -> 20
- _OUTLINED_FUNCTION_37
~ __ZNKSbIwSt11char_traitsIwESaIwEE4findEPKwmm : 168 -> 156
~ __ZNKSbIwSt11char_traitsIwESaIwEE5rfindEPKwmm : 120 -> 112
~ __ZNKSbIwSt11char_traitsIwESaIwEE5rfindEwm : 64 -> 72
~ __ZNKSbIwSt11char_traitsIwESaIwEE13find_first_ofERKS2_m : 112 -> 108
~ __ZNKSbIwSt11char_traitsIwESaIwEE13find_first_ofEPKwmm : 124 -> 120
~ __ZNKSbIwSt11char_traitsIwESaIwEE13find_first_ofEPKwm : 132 -> 128
~ __ZNKSbIwSt11char_traitsIwESaIwEE12find_last_ofEPKwmm : 124 -> 120
~ __ZNKSbIwSt11char_traitsIwESaIwEE12find_last_ofEwm : 64 -> 72
~ __ZNKSbIwSt11char_traitsIwESaIwEE17find_first_not_ofEPKwmm : 120 -> 116
~ __ZNKSbIwSt11char_traitsIwESaIwEE17find_first_not_ofEwm : 56 -> 52
~ __ZNKSbIwSt11char_traitsIwESaIwEE16find_last_not_ofEPKwmm : 124 -> 120
~ __ZNKSbIwSt11char_traitsIwESaIwEE16find_last_not_ofEwm : 64 -> 60
~ __ZSt6searchIPKwS1_PFbRS0_S2_EET_S5_S5_T0_S6_T1_ : 300 -> 328
~ __ZNKSt5ctypeIwE8do_widenEc : 12 -> 16
~ __ZNKSt5ctypeIwE8do_widenEPKcS2_Pw : 44 -> 40
~ __ZNSt5ctypeIwE19_M_initialize_ctypeEv : 136 -> 128
~ __ZNSt10moneypunctIcLb1EE24_M_initialize_moneypunctEPiPKc : 220 -> 224
~ __ZNSt10moneypunctIcLb0EE24_M_initialize_moneypunctEPiPKc : 220 -> 224
~ __ZNSt10moneypunctIwLb1EE24_M_initialize_moneypunctEPiPKc : 236 -> 232
~ __ZNSt10moneypunctIwLb0EE24_M_initialize_moneypunctEPiPKc : 236 -> 232
~ __ZNSt8numpunctIcE22_M_initialize_numpunctEPi : 268 -> 272
~ __ZNSt8numpunctIwE22_M_initialize_numpunctEPi : 268 -> 260
~ __ZNKSt7num_putIcSt19ostreambuf_iteratorIcSt11char_traitsIcEEE13_M_insert_intIlEES3_S3_RSt8ios_basecT_ : 444 -> 468
~ __ZNKSt7num_putIcSt19ostreambuf_iteratorIcSt11char_traitsIcEEE13_M_insert_intImEES3_S3_RSt8ios_basecT_ : 372 -> 388
~ __ZNKSt7num_putIcSt19ostreambuf_iteratorIcSt11char_traitsIcEEE13_M_insert_intIxEES3_S3_RSt8ios_basecT_ : 444 -> 468
~ __ZNKSt7num_putIcSt19ostreambuf_iteratorIcSt11char_traitsIcEEE13_M_insert_intIyEES3_S3_RSt8ios_basecT_ : 372 -> 388
~ __ZNKSt7num_putIcSt19ostreambuf_iteratorIcSt11char_traitsIcEEE15_M_insert_floatIdEES3_S3_RSt8ios_baseccT_ : 604 -> 600
~ __ZNKSt7num_putIcSt19ostreambuf_iteratorIcSt11char_traitsIcEEE15_M_insert_floatIeEES3_S3_RSt8ios_baseccT_ : 604 -> 600
```
