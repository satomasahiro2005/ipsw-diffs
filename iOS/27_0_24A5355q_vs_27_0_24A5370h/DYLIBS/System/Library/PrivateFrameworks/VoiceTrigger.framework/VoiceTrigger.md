## VoiceTrigger

> `/System/Library/PrivateFrameworks/VoiceTrigger.framework/VoiceTrigger`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd7ecc` | `0xd7cb0` | **`-0x21c`** |
| `__AUTH_CONST.__const` | `0x3eb0` | `0x3ef8` | **`+0x48`** |
| `__TEXT.__cstring` | `0xee27` | `0xee46` | **`+0x1f`** |
| `__TEXT.__gcc_except_tab` | `0x7c98` | `0x7cac` | **`+0x14`** |
| `__TEXT.__const` | `0x1508` | `0x1518` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2f48` | `0x2f50` | **`+0x8`** |

### Other Changes

```diff

-3600.20.1.0.0
+3600.26.1.0.0

-  Functions: 3042
-  Symbols:   5493
-  CStrings:  2196
+  Functions: 3047
+  Symbols:   5500
+  CStrings:  2197
Symbols:
+ GCC_except_table2036
+ GCC_except_table2038
+ GCC_except_table2083
+ GCC_except_table2089
+ GCC_except_table2092
+ GCC_except_table2096
+ GCC_except_table2102
+ GCC_except_table2116
+ GCC_except_table2117
+ GCC_except_table2118
+ GCC_except_table2119
+ GCC_except_table2120
+ GCC_except_table2145
+ GCC_except_table2191
+ GCC_except_table2234
+ GCC_except_table2235
+ GCC_except_table2236
+ GCC_except_table2237
+ GCC_except_table2238
+ GCC_except_table2278
+ GCC_except_table2280
+ GCC_except_table2286
+ GCC_except_table2287
+ GCC_except_table2289
+ GCC_except_table2290
+ GCC_except_table2305
+ GCC_except_table2311
+ GCC_except_table2312
+ GCC_except_table2313
+ GCC_except_table2314
+ GCC_except_table2320
+ GCC_except_table2321
+ GCC_except_table2333
+ GCC_except_table2335
+ GCC_except_table2378
+ GCC_except_table2385
+ GCC_except_table2414
+ GCC_except_table2422
+ GCC_except_table2423
+ GCC_except_table2424
+ GCC_except_table2425
+ GCC_except_table2426
+ GCC_except_table2433
+ GCC_except_table2442
+ GCC_except_table2444
+ GCC_except_table2457
+ GCC_except_table2539
+ GCC_except_table2542
+ GCC_except_table2552
+ GCC_except_table2560
+ GCC_except_table2566
+ GCC_except_table2567
+ GCC_except_table2573
+ GCC_except_table2574
+ GCC_except_table2575
+ GCC_except_table2576
+ GCC_except_table2583
+ GCC_except_table2584
+ GCC_except_table2585
+ GCC_except_table2616
+ GCC_except_table2630
+ GCC_except_table2631
+ GCC_except_table2651
+ GCC_except_table2662
+ GCC_except_table2663
+ GCC_except_table2664
+ GCC_except_table2665
+ GCC_except_table2767
+ GCC_except_table2827
+ GCC_except_table2853
+ GCC_except_table2889
+ GCC_except_table2890
+ GCC_except_table2892
+ GCC_except_table2893
+ GCC_except_table2896
+ GCC_except_table2906
+ __ZN11NSATSpeaker18calcModelNormScaleEv
+ __ZN11NSATSpeaker5scoreERK6NArrayIfERKfS5_
+ __ZN6NArrayIPKcE6resizeERKj
+ __ZN6NArrayIPKcE9fromArrayEPKS1_RKj
+ __ZN6NArrayIPKcED0Ev
+ __ZN6NArrayIPKcED1Ev
+ __ZN6NArrayIPKcEaSERKS2_
+ __ZNK11NSATSpeaker10bubbleSortEPfRKj
+ __ZNK11NSATSpeaker14findPercentileEPfRKjRKf
+ __ZNK11NSATSpeaker15findTopNAverageEPfRKjS2_RKbRKf
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE15__init_buf_ptrsB9fqe220106Ev
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__124__put_character_sequenceB9fqe220106IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
+ __ZNSt3__16vectorIPKtNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZTI6NArrayIPKcE
+ __ZTS6NArrayIPKcE
+ __ZTV6NArrayIPKcE
- GCC_except_table2031
- GCC_except_table2033
- GCC_except_table2078
- GCC_except_table2079
- GCC_except_table2081
- GCC_except_table2082
- GCC_except_table2093
- GCC_except_table2097
- GCC_except_table2105
- GCC_except_table2106
- GCC_except_table2107
- GCC_except_table2109
- GCC_except_table2140
- GCC_except_table2186
- GCC_except_table2227
- GCC_except_table2228
- GCC_except_table2229
- GCC_except_table2230
- GCC_except_table2231
- GCC_except_table2261
- GCC_except_table2263
- GCC_except_table2265
- GCC_except_table2267
- GCC_except_table2269
- GCC_except_table2285
- GCC_except_table2296
- GCC_except_table2297
- GCC_except_table2298
- GCC_except_table2299
- GCC_except_table2300
- GCC_except_table2310
- GCC_except_table2316
- GCC_except_table2328
- GCC_except_table2330
- GCC_except_table2373
- GCC_except_table2380
- GCC_except_table2408
- GCC_except_table2409
- GCC_except_table2410
- GCC_except_table2417
- GCC_except_table2419
- GCC_except_table2421
- GCC_except_table2428
- GCC_except_table2437
- GCC_except_table2439
- GCC_except_table2452
- GCC_except_table2534
- GCC_except_table2537
- GCC_except_table2547
- GCC_except_table2555
- GCC_except_table2556
- GCC_except_table2557
- GCC_except_table2558
- GCC_except_table2569
- GCC_except_table2570
- GCC_except_table2571
- GCC_except_table2578
- GCC_except_table2579
- GCC_except_table2580
- GCC_except_table2611
- GCC_except_table2625
- GCC_except_table2626
- GCC_except_table2645
- GCC_except_table2646
- GCC_except_table2657
- GCC_except_table2658
- GCC_except_table2659
- GCC_except_table2762
- GCC_except_table2822
- GCC_except_table2848
- GCC_except_table2884
- GCC_except_table2885
- GCC_except_table2886
- GCC_except_table2887
- GCC_except_table2888
- GCC_except_table2901
- GCC_except_table492
- __ZNK11NSATSpeaker10bubbleSortEPKfPfRKj
- __ZNK11NSATSpeaker14findPercentileEPKfRKjRS0_
- __ZNK11NSATSpeaker15findTopNAverageEPKfRKjS3_RKbRS0_
- __ZNK11NSATSpeaker18calcModelNormScaleEv
- __ZNK11NSATSpeaker5scoreERK6NArrayIfERKfS5_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE15__init_buf_ptrsB9fqe220100Ev
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__124__put_character_sequenceB9fqe220100IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
- __ZNSt3__16vectorIPKtNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
CStrings:
+ "Apple clang version 21.0.0 (clang-2100.3.23.3) [+internal-os]"
+ "Novalib gitrelno_unavailable Release Tue Jun 16 00:14:57 2026"
+ "Tue Jun 16 00:14:57 2026"
+ "Tue Jun 16 00:14:57 PDT 2026"
+ "zero-size matrix not supported"
- "Apple clang version 21.0.0 (clang-2100.3.19.4) [+internal-os]"
- "Novalib gitrelno_unavailable Release Thu May 21 09:57:28 2026"
- "Thu May 21 09:57:28 2026"
- "Thu May 21 09:57:28 PDT 2026"
```
