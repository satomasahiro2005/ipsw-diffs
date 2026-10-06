## CDMFoundation

> `/System/Library/PrivateFrameworks/CDMFoundation.framework/CDMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x271878` | `0x270dd0` | **`-0xaa8`** |
| `__TEXT.__const` | `0xd500` | `0xd360` | **`-0x1a0`** |
| `__DATA.__bss` | `0x9f30` | `0x9da0` | **`-0x190`** |
| `__AUTH_CONST.__objc_const` | `0x12770` | `0x12860` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0x56a4` | `0x55d4` | **`-0xd0`** |
| `__DATA_DIRTY.__objc_data` | `0x4a50` | `0x49b0` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x1b921` | `0x1b882` | **`-0x9f`** |
| `__TEXT.__swift5_typeref` | `0x42b2` | `0x421e` | **`-0x94`** |
| `__TEXT.__swift5_reflstr` | `0x30fa` | `0x306a` | **`-0x90`** |
| `__TEXT.__eh_frame` | `0x7af8` | `0x7a74` | **`-0x84`** |
| `__TEXT.__swift5_fieldmd` | `0x3dfc` | `0x3d80` | **`-0x7c`** |
| `__AUTH_CONST.__objc_intobj` | `0x558` | `0x5d0` | **`+0x78`** |
| `__AUTH_CONST.__const` | `0xc8a0` | `0xc840` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x1200` | `0x11b8` | **`-0x48`** |
| `__DATA.__data` | `0x1cb8` | `0x1cf8` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x4960` | `0x4920` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x4e28` | `0x4e50` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x198` | `0x1c0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x80a0` | `0x8080` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x1e08` | `0x1e28` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x7e78` | `0x7e58` | **`-0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x48` | `0x60` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x9c0` | `0x9ac` | **`-0x14`** |
| `__TEXT.__swift_as_ret` | `0x284` | `0x270` | **`-0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x5360` | `0x5350` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x440` | `0x434` | **`-0xc`** |
| `__TEXT.__swift_as_entry` | `0x248` | `0x23c` | **`-0xc`** |
| `__TEXT.__oslogstring` | `0x1dbec` | `0x1dbe3` | **`-0x9`** |
| `__DATA_CONST.__got` | `0x26b8` | `0x26b0` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8d8` | `0x8d0` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x140` | `0x148` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x4b0` | `0x4a8` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0xb438` | `0xb440` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x8594` | `0x859c` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0xa0` | `0x98` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x57c` | `0x574` | **`-0x8`** |

### Other Changes

```diff

-3600.25.7.1.1
+3600.31.3.0.0

-  - /System/Library/PrivateFrameworks/AIMLExperimentationAnalytics.framework/AIMLExperimentationAnalytics

-  Functions: 12825
-  Symbols:   8826
-  CStrings:  4583
+  Functions: 12808
+  Symbols:   8832
+  CStrings:  4575
Symbols:
+ +[CDMPostProcessUtils copyVocDefinedValueIdentifiers:entitySpans:fromMatchingSpans:toParseGraph:]
+ +[CDMPostProcessUtils vocSpan:matchesParentEntity:definedValue:]
+ -[CDMClient(NLU) processText:requestConnectionId:nlContext:previousUtterances:completionHandler:]
+ -[CDMFoundationClient waitForDataDispatcherCompletionWithTimeout:]
+ -[CDMServiceCenter waitForQueueDrain]
+ GCC_except_table102
+ GCC_except_table1056
+ GCC_except_table1057
+ GCC_except_table106
+ GCC_except_table1063
+ GCC_except_table1066
+ GCC_except_table107
+ GCC_except_table1085
+ GCC_except_table1086
+ GCC_except_table1099
+ GCC_except_table1104
+ GCC_except_table1115
+ GCC_except_table1126
+ GCC_except_table1129
+ GCC_except_table1146
+ GCC_except_table1147
+ GCC_except_table1148
+ GCC_except_table1153
+ GCC_except_table1159
+ GCC_except_table1162
+ GCC_except_table1187
+ GCC_except_table1188
+ GCC_except_table1189
+ GCC_except_table119
+ GCC_except_table1190
+ GCC_except_table121
+ GCC_except_table1248
+ GCC_except_table1249
+ GCC_except_table1250
+ GCC_except_table1278
+ GCC_except_table130
+ GCC_except_table1301
+ GCC_except_table1302
+ GCC_except_table1303
+ GCC_except_table131
+ GCC_except_table132
+ GCC_except_table1320
+ GCC_except_table1321
+ GCC_except_table1322
+ GCC_except_table1323
+ GCC_except_table1348
+ GCC_except_table1349
+ GCC_except_table1350
+ GCC_except_table1351
+ GCC_except_table1391
+ GCC_except_table1397
+ GCC_except_table1398
+ GCC_except_table1399
+ GCC_except_table1400
+ GCC_except_table141
+ GCC_except_table142
+ GCC_except_table1421
+ GCC_except_table143
+ GCC_except_table144
+ GCC_except_table1443
+ GCC_except_table1446
+ GCC_except_table1448
+ GCC_except_table1449
+ GCC_except_table1630
+ GCC_except_table1658
+ GCC_except_table1662
+ GCC_except_table1678
+ GCC_except_table1680
+ GCC_except_table1722
+ GCC_except_table1723
+ GCC_except_table1724
+ GCC_except_table1727
+ GCC_except_table1728
+ GCC_except_table1732
+ GCC_except_table1733
+ GCC_except_table1749
+ GCC_except_table1773
+ GCC_except_table1784
+ GCC_except_table1785
+ GCC_except_table1786
+ GCC_except_table1787
+ GCC_except_table1789
+ GCC_except_table179
+ GCC_except_table1790
+ GCC_except_table1795
+ GCC_except_table1799
+ GCC_except_table1808
+ GCC_except_table1809
+ GCC_except_table1810
+ GCC_except_table1851
+ GCC_except_table1853
+ GCC_except_table1874
+ GCC_except_table190
+ GCC_except_table191
+ GCC_except_table192
+ GCC_except_table1923
+ GCC_except_table1925
+ GCC_except_table1926
+ GCC_except_table193
+ GCC_except_table1930
+ GCC_except_table1948
+ GCC_except_table1949
+ GCC_except_table1950
+ GCC_except_table1951
+ GCC_except_table1952
+ GCC_except_table1953
+ GCC_except_table1966
+ GCC_except_table1967
+ GCC_except_table1968
+ GCC_except_table1969
+ GCC_except_table1970
+ GCC_except_table1989
+ GCC_except_table1990
+ GCC_except_table1991
+ GCC_except_table1992
+ GCC_except_table2010
+ GCC_except_table2013
+ GCC_except_table2014
+ GCC_except_table2021
+ GCC_except_table2032
+ GCC_except_table2124
+ GCC_except_table2125
+ GCC_except_table2127
+ GCC_except_table2132
+ GCC_except_table2134
+ GCC_except_table2135
+ GCC_except_table2142
+ GCC_except_table2156
+ GCC_except_table2157
+ GCC_except_table2159
+ GCC_except_table2160
+ GCC_except_table2161
+ GCC_except_table2168
+ GCC_except_table2170
+ GCC_except_table2181
+ GCC_except_table2182
+ GCC_except_table2184
+ GCC_except_table2189
+ GCC_except_table2191
+ GCC_except_table2192
+ GCC_except_table2270
+ GCC_except_table2271
+ GCC_except_table2272
+ GCC_except_table2273
+ GCC_except_table2274
+ GCC_except_table2275
+ GCC_except_table2310
+ GCC_except_table2330
+ GCC_except_table2331
+ GCC_except_table2332
+ GCC_except_table2333
+ GCC_except_table2334
+ GCC_except_table2335
+ GCC_except_table2419
+ GCC_except_table2421
+ GCC_except_table2422
+ GCC_except_table2423
+ GCC_except_table2424
+ GCC_except_table2426
+ GCC_except_table2446
+ GCC_except_table2469
+ GCC_except_table2470
+ GCC_except_table2477
+ GCC_except_table2478
+ GCC_except_table2479
+ GCC_except_table2480
+ GCC_except_table2481
+ GCC_except_table2482
+ GCC_except_table249
+ GCC_except_table251
+ GCC_except_table2512
+ GCC_except_table2514
+ GCC_except_table2517
+ GCC_except_table2544
+ GCC_except_table2545
+ GCC_except_table2572
+ GCC_except_table258
+ GCC_except_table260
+ GCC_except_table263
+ GCC_except_table265
+ GCC_except_table268
+ GCC_except_table271
+ GCC_except_table273
+ GCC_except_table283
+ GCC_except_table296
+ GCC_except_table301
+ GCC_except_table302
+ GCC_except_table314
+ GCC_except_table320
+ GCC_except_table322
+ GCC_except_table323
+ GCC_except_table329
+ GCC_except_table335
+ GCC_except_table370
+ GCC_except_table379
+ GCC_except_table380
+ GCC_except_table381
+ GCC_except_table413
+ GCC_except_table414
+ GCC_except_table428
+ GCC_except_table54
+ GCC_except_table555
+ GCC_except_table57
+ GCC_except_table602
+ GCC_except_table603
+ GCC_except_table604
+ GCC_except_table605
+ GCC_except_table61
+ GCC_except_table663
+ GCC_except_table664
+ GCC_except_table665
+ GCC_except_table666
+ GCC_except_table681
+ GCC_except_table689
+ GCC_except_table696
+ GCC_except_table698
+ GCC_except_table699
+ GCC_except_table701
+ GCC_except_table706
+ GCC_except_table709
+ GCC_except_table711
+ GCC_except_table716
+ GCC_except_table724
+ GCC_except_table760
+ GCC_except_table761
+ GCC_except_table762
+ GCC_except_table80
+ GCC_except_table81
+ GCC_except_table855
+ GCC_except_table865
+ GCC_except_table872
+ GCC_except_table873
+ GCC_except_table874
+ GCC_except_table875
+ GCC_except_table90
+ GCC_except_table906
+ GCC_except_table918
+ GCC_except_table923
+ GCC_except_table928
+ GCC_except_table929
+ GCC_except_table96
+ GCC_except_table981
+ GCC_except_table982
+ GCC_except_table983
+ GCC_except_table984
+ _OUTLINED_FUNCTION_622
+ __OBJC_$_PROTOCOL_REFS_CDMUserInitiatedQOSCommand
+ __OBJC_CLASS_PROTOCOLS_$_CDMAssistantNLUCommand
+ __OBJC_CLASS_PROTOCOLS_$_CDMEmbeddingGraphRequestCommand
+ __OBJC_CLASS_PROTOCOLS_$_CDMPlannerGraphRequestCommand
+ __OBJC_CLASS_PROTOCOLS_$_CDMShortcutDetectorRequestCommand
+ __OBJC_CLASS_PROTOCOLS_$_CDMSsuInferenceGraphRequestCommand
+ __OBJC_LABEL_PROTOCOL_$_CDMUserInitiatedQOSCommand
+ __OBJC_PROTOCOL_$_CDMUserInitiatedQOSCommand
+ __OBJC_PROTOCOL_REFERENCE_$_CDMUserInitiatedQOSCommand
+ __ZNKSt3__114default_deleteIN4siri8ontology9MatchInfoEEclB9fqe220106EPS3_
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__110unique_ptrIN2PB6WriterENS_14default_deleteIS2_EEED1B9fqe220106Ev
+ __ZNSt3__110unique_ptrIN4siri8ontology13UsoEntitySpanENS_14default_deleteIS3_EEED1B9fqe220106Ev
+ __ZNSt3__110unique_ptrIN4siri8ontology13UsoIdentifierENS_14default_deleteIS3_EEED1B9fqe220106Ev
+ __ZNSt3__110unique_ptrIN4siri8ontology8UsoGraphENS_14default_deleteIS3_EEED1B9fqe220106Ev
+ __ZNSt3__111make_uniqueB9fqe220106IN4siri8ontology13UsoEntitySpanEJELi0EEENS_10unique_ptrIT_NS_14default_deleteIS5_EEEEDpOT0_
+ __ZNSt3__112basic_stringIDsNS_11char_traitsIDsEENS_9allocatorIDsEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220106ILi0EEEPKc
+ __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9fqe220106Ej
+ __ZNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220106Ev
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220106Ev
+ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220106Ev
+ __ZNSt3__120__optional_copy_baseINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEELb0EEC2B9fqe220106ERKS7_
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__123__optional_storage_baseINS_10unique_ptrIN4siri8ontology9MatchInfoENS_14default_deleteIS4_EEEELb0EE13__assign_fromB9fqe220106INS_27__optional_move_assign_baseIS7_Lb0EEEEEvOT_
+ __ZNSt3__123__optional_storage_baseINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEELb0EE13__assign_fromB9fqe220106INS_27__optional_move_assign_baseIS6_Lb0EEEEEvOT_
+ __ZNSt3__124__put_character_sequenceB9fqe220106IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
+ __ZNSt3__16vectorINS_10unique_ptrIN4siri8ontology12SpanPropertyENS_14default_deleteIS4_EEEENS_9allocatorIS7_EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorINS_10unique_ptrIN4siri8ontology14AsrAlternativeENS_14default_deleteIS4_EEEENS_9allocatorIS7_EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE16__init_with_sizeB9fqe220106IPfS5_EEvT_T0_m
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__18optionalINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEC1B9fqe220106IPKcLi0EEEOT_
+ ___37-[CDMServiceCenter waitForQueueDrain]_block_invoke
+ ___66-[CDMFoundationClient waitForDataDispatcherCompletionWithTimeout:]_block_invoke
+ ___block_descriptor_40_ea8_32s_e5_v8?0ls32l8
+ ___block_descriptor_65_e8_32s40s48s56bs_e29_v32?0"<CDMService>"8Q16^B24ls32l8s40l8s56l8s48l8
+ ___definedValueIdentifierAllowList_block_invoke
+ __xpc_type_data
+ _definedValueIdentifierAllowList.allowList
+ _definedValueIdentifierAllowList.onceToken
+ _dispatch_barrier_async
+ _dispatch_barrier_sync
+ _xpc_create_from_plist
+ _xpc_data_get_bytes_ptr
+ _xpc_data_get_length
+ _xpc_dictionary_get_value
- +[CDMCcqrServiceUtils isNLRouterAssetAvailable:]
- -[CDMCcqrAerCbRService skipServiceSetup:]
- GCC_except_table103
- GCC_except_table104
- GCC_except_table1049
- GCC_except_table1052
- GCC_except_table1054
- GCC_except_table1055
- GCC_except_table1081
- GCC_except_table1082
- GCC_except_table1095
- GCC_except_table1100
- GCC_except_table1111
- GCC_except_table1118
- GCC_except_table1125
- GCC_except_table1141
- GCC_except_table1142
- GCC_except_table1143
- GCC_except_table1144
- GCC_except_table1150
- GCC_except_table1155
- GCC_except_table117
- GCC_except_table1176
- GCC_except_table1177
- GCC_except_table1178
- GCC_except_table1179
- GCC_except_table122
- GCC_except_table123
- GCC_except_table1244
- GCC_except_table1245
- GCC_except_table1246
- GCC_except_table1274
- GCC_except_table128
- GCC_except_table1282
- GCC_except_table1283
- GCC_except_table1284
- GCC_except_table1285
- GCC_except_table129
- GCC_except_table1305
- GCC_except_table1306
- GCC_except_table1307
- GCC_except_table1337
- GCC_except_table134
- GCC_except_table1342
- GCC_except_table1343
- GCC_except_table1344
- GCC_except_table135
- GCC_except_table1387
- GCC_except_table1393
- GCC_except_table1394
- GCC_except_table1395
- GCC_except_table1396
- GCC_except_table140
- GCC_except_table1417
- GCC_except_table1433
- GCC_except_table1434
- GCC_except_table1435
- GCC_except_table1436
- GCC_except_table1623
- GCC_except_table1651
- GCC_except_table1655
- GCC_except_table1671
- GCC_except_table1673
- GCC_except_table1700
- GCC_except_table1701
- GCC_except_table1702
- GCC_except_table1703
- GCC_except_table1704
- GCC_except_table1706
- GCC_except_table1712
- GCC_except_table1742
- GCC_except_table1747
- GCC_except_table175
- GCC_except_table1750
- GCC_except_table1753
- GCC_except_table1755
- GCC_except_table1756
- GCC_except_table1758
- GCC_except_table1759
- GCC_except_table1780
- GCC_except_table1792
- GCC_except_table180
- GCC_except_table1801
- GCC_except_table1802
- GCC_except_table1803
- GCC_except_table182
- GCC_except_table1841
- GCC_except_table1845
- GCC_except_table1868
- GCC_except_table187
- GCC_except_table189
- GCC_except_table1912
- GCC_except_table1913
- GCC_except_table1917
- GCC_except_table1920
- GCC_except_table1931
- GCC_except_table1932
- GCC_except_table1933
- GCC_except_table1935
- GCC_except_table1936
- GCC_except_table1940
- GCC_except_table1954
- GCC_except_table1961
- GCC_except_table1962
- GCC_except_table1963
- GCC_except_table1964
- GCC_except_table1978
- GCC_except_table1983
- GCC_except_table1985
- GCC_except_table1986
- GCC_except_table2004
- GCC_except_table2007
- GCC_except_table2008
- GCC_except_table2015
- GCC_except_table2026
- GCC_except_table2118
- GCC_except_table2119
- GCC_except_table2120
- GCC_except_table2121
- GCC_except_table2122
- GCC_except_table2129
- GCC_except_table2136
- GCC_except_table2144
- GCC_except_table2145
- GCC_except_table2147
- GCC_except_table2148
- GCC_except_table2149
- GCC_except_table2158
- GCC_except_table2162
- GCC_except_table2175
- GCC_except_table2176
- GCC_except_table2177
- GCC_except_table2178
- GCC_except_table2179
- GCC_except_table2180
- GCC_except_table2258
- GCC_except_table2259
- GCC_except_table2260
- GCC_except_table2261
- GCC_except_table2262
- GCC_except_table2263
- GCC_except_table2304
- GCC_except_table2306
- GCC_except_table2307
- GCC_except_table2308
- GCC_except_table2309
- GCC_except_table2311
- GCC_except_table2316
- GCC_except_table233
- GCC_except_table239
- GCC_except_table2403
- GCC_except_table2404
- GCC_except_table2405
- GCC_except_table2406
- GCC_except_table2407
- GCC_except_table2408
- GCC_except_table2440
- GCC_except_table2463
- GCC_except_table2464
- GCC_except_table2465
- GCC_except_table2472
- GCC_except_table2473
- GCC_except_table2474
- GCC_except_table2475
- GCC_except_table2476
- GCC_except_table250
- GCC_except_table2506
- GCC_except_table2508
- GCC_except_table2511
- GCC_except_table252
- GCC_except_table2538
- GCC_except_table2539
- GCC_except_table2566
- GCC_except_table259
- GCC_except_table261
- GCC_except_table264
- GCC_except_table267
- GCC_except_table269
- GCC_except_table279
- GCC_except_table292
- GCC_except_table294
- GCC_except_table297
- GCC_except_table310
- GCC_except_table316
- GCC_except_table317
- GCC_except_table318
- GCC_except_table319
- GCC_except_table331
- GCC_except_table366
- GCC_except_table371
- GCC_except_table376
- GCC_except_table377
- GCC_except_table406
- GCC_except_table409
- GCC_except_table424
- GCC_except_table52
- GCC_except_table55
- GCC_except_table551
- GCC_except_table59
- GCC_except_table594
- GCC_except_table595
- GCC_except_table600
- GCC_except_table601
- GCC_except_table654
- GCC_except_table657
- GCC_except_table659
- GCC_except_table660
- GCC_except_table677
- GCC_except_table679
- GCC_except_table680
- GCC_except_table685
- GCC_except_table686
- GCC_except_table693
- GCC_except_table700
- GCC_except_table702
- GCC_except_table703
- GCC_except_table705
- GCC_except_table720
- GCC_except_table756
- GCC_except_table757
- GCC_except_table758
- GCC_except_table77
- GCC_except_table78
- GCC_except_table851
- GCC_except_table856
- GCC_except_table859
- GCC_except_table861
- GCC_except_table862
- GCC_except_table869
- GCC_except_table88
- GCC_except_table902
- GCC_except_table912
- GCC_except_table913
- GCC_except_table914
- GCC_except_table915
- GCC_except_table94
- GCC_except_table969
- GCC_except_table970
- GCC_except_table971
- GCC_except_table972
- GCC_except_table98
- _OBJC_CLASS_$_NLRouterExperimentTrialController
- _OBJC_CLASS_$_TRIClient
- _OBJC_METACLASS_$_NLRouterExperimentTrialController
- _OUTLINED_FUNCTION_616
- _OUTLINED_FUNCTION_636
- _OUTLINED_FUNCTION_637
- _OUTLINED_FUNCTION_638
- _OUTLINED_FUNCTION_639
- __DATA_NLRouterExperimentTrialController
- __INSTANCE_METHODS_NLRouterExperimentTrialController
- __IVARS_NLRouterExperimentTrialController
- __METACLASS_DATA_NLRouterExperimentTrialController
- __PROPERTIES_NLRouterExperimentTrialController
- __ZNKSt3__114default_deleteIN4siri8ontology9MatchInfoEEclB9fqe220100EPS3_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__110unique_ptrIN2PB6WriterENS_14default_deleteIS2_EEED1B9fqe220100Ev
- __ZNSt3__110unique_ptrIN4siri8ontology13UsoEntitySpanENS_14default_deleteIS3_EEED1B9fqe220100Ev
- __ZNSt3__110unique_ptrIN4siri8ontology13UsoIdentifierENS_14default_deleteIS3_EEED1B9fqe220100Ev
- __ZNSt3__110unique_ptrIN4siri8ontology8UsoGraphENS_14default_deleteIS3_EEED1B9fqe220100Ev
- __ZNSt3__111make_uniqueB9fqe220100IN4siri8ontology13UsoEntitySpanEJELi0EEENS_10unique_ptrIT_NS_14default_deleteIS5_EEEEDpOT0_
- __ZNSt3__112basic_stringIDsNS_11char_traitsIDsEENS_9allocatorIDsEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220100ILi0EEEPKc
- __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9fqe220100Ej
- __ZNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220100Ev
- __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220100Ev
- __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220100Ev
- __ZNSt3__120__optional_copy_baseINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEELb0EEC2B9fqe220100ERKS7_
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__123__optional_storage_baseINS_10unique_ptrIN4siri8ontology9MatchInfoENS_14default_deleteIS4_EEEELb0EE13__assign_fromB9fqe220100INS_27__optional_move_assign_baseIS7_Lb0EEEEEvOT_
- __ZNSt3__123__optional_storage_baseINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEELb0EE13__assign_fromB9fqe220100INS_27__optional_move_assign_baseIS6_Lb0EEEEEvOT_
- __ZNSt3__124__put_character_sequenceB9fqe220100IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
- __ZNSt3__16vectorINS_10unique_ptrIN4siri8ontology12SpanPropertyENS_14default_deleteIS4_EEEENS_9allocatorIS7_EEE16__destroy_vectorclB9fqe220100Ev
- __ZNSt3__16vectorINS_10unique_ptrIN4siri8ontology14AsrAlternativeENS_14default_deleteIS4_EEEENS_9allocatorIS7_EEE16__destroy_vectorclB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIfNS_9allocatorIfEEE16__init_with_sizeB9fqe220100IPfS5_EEvT_T0_m
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__18optionalINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEC1B9fqe220100IPKcLi0EEEOT_
- ___block_descriptor_64_e8_32s40s48s56bs_e29_v32?0"<CDMService>"8Q16^B24ls32l8s40l8s56l8s48l8
- ___swift_closure_destructor.65Tm
- _associated conformance 13CDMFoundation33NLRouterExperimentTrialControllerC0C5ErrorOSHAASQ
- _symbolic $s13CDMFoundation32ExperimentationAnalyticsManagingP
- _symbolic $s13CDMFoundation36NLRouterExperimentControllerProtocolP
- _symbolic _____ 13CDMFoundation33NLRouterExperimentTrialControllerC
- _symbolic _____ 13CDMFoundation33NLRouterExperimentTrialControllerC0C5ErrorO
- _symbolic ______p 13CDMFoundation32ExperimentationAnalyticsManagingP
- _symbolic ______p 13CDMFoundation36NLRouterExperimentControllerProtocolP
CStrings:
+ "%s Attached VOC DefinedValue identifier for node %d (element %u) from span [%u-%u]"
+ "%s CDMServiceCenter waitForQueueDrain: _cdmServiceCenterQueue drained. CDMServiceCenterId: %@"
+ "%s CDMServiceCenter waitForQueueDrain: waiting for _cdmServiceCenterQueue to drain. CDMServiceCenterId: %@"
+ "%s Skipping VOC DefinedValue alignment for node %d (element %u): alignment already exists for this node"
+ "%s [WARN]: CDMFoundationClient forceCleanup: CDMDataDispatcherCompletionQueue did not drain within 3 s — proceeding with cleanup"
+ "+[CDMPostProcessUtils copyVocDefinedValueIdentifiers:entitySpans:fromMatchingSpans:toParseGraph:]"
+ "-[CDMServiceCenter waitForQueueDrain]"
+ "FullPlanner is not enabled. Decision: %s, updated to: %s"
+ "Intelligence Flow is not enabled. Decision: %s, updated to: %s"
+ "com.apple.distnoted.matching.trusted"
- "%s AssetPath Info for NLRouter.  %@"
- "%s Checking CDMCcqrAerCbRService assets for locale: %@"
- "%s Checking NLRouter assets for locale: %@"
- "%s NLRouter CDM assets manager failed to setup with error: %@."
- "%s NLRouter assets not available"
- "%s NLRouter assets not available due to error %@."
- "%s Skip CDMCcqrAerCbRService setup as NLRouter service requirements met"
- "+[CDMCcqrServiceUtils isNLRouterAssetAvailable:]"
- "Emitting experiment trigger logging"
- "Error emitting experiment trigger logging: %@; bypassing experiment"
- "FullPlanner is not enabled. Post experiment decision: %s, updated to: %s"
- "Intelligence Flow is not enabled. Post experiment decision: %s, updated to: %s"
- "Received NLRouter response: %s (modified by A/B; original: %s)"
- "SIRI_UNDERSTANDING_NL_ROUTER"
- "Skip CCQR service setup as NLRouter service requirements met."
- "Unable to convert strings to UUIDs, preventing trigger logging."
- "b3989158-e981-45c1-9299-66e46f148788"
- "com.apple.distnoted.matching"
```
