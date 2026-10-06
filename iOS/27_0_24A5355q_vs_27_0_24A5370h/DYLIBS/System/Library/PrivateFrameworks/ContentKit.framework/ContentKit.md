## ContentKit

> `/System/Library/PrivateFrameworks/ContentKit.framework/ContentKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2109c0` | `0x20e330` | **`-0x2690`** |
| `__AUTH_CONST.__const` | `0xe728` | `0xc8d0` | **`-0x1e58`** |
| `__TEXT.__swift5_capture` | `0x2f6c` | `0x236c` | **`-0xc00`** |
| `__TEXT.__cstring` | `0x1a7a6` | `0x1a9f0` | **`+0x24a`** |
| `__TEXT.__oslogstring` | `0x5cd6` | `0x5ac6` | **`-0x210`** |
| `__AUTH_CONST.__cfstring` | `0x12300` | `0x12500` | **`+0x200`** |
| `__TEXT.__eh_frame` | `0xa850` | `0xa9f8` | **`+0x1a8`** |
| `__TEXT.__delay_helper` | `—` | `0xdc` | **`+0xdc`** |
| `__TEXT.__objc_methlist` | `0xcb34` | `0xcbcc` | **`+0x98`** |
| `__TEXT.__swift5_reflstr` | `0x129b` | `0x123b` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x6330` | `0x6388` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x6990` | `0x69e8` | **`+0x58`** |
| `__TEXT.__swift_as_cont` | `0x8bc` | `0x908` | **`+0x4c`** |
| `__DATA_CONST.__got` | `0x18c0` | `0x18f8` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x1c80` | `0x1c4c` | **`-0x34`** |
| `__AUTH_CONST.__auth_got` | `0x23c0` | `0x23f0` | **`+0x30`** |
| `__AUTH.__data` | `0x1720` | `0x1740` | **`+0x20`** |
| `__DATA.__bss` | `0xdd80` | `0xdd98` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x81b0` | `0x81c8` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x16998` | `0x16988` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x450` | `0x440` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x264a` | `0x263c` | **`-0xe`** |
| `__TEXT.__dlopen_cstrs` | `0x19f6` | `0x19e9` | **`-0xd`** |
| `__TEXT.__constg_swiftt` | `0x1a70` | `0x1a7c` | **`+0xc`** |
| `__DATA.__data` | `0x3a28` | `0x3a2c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x21c` | `0x218` | **`-0x4`** |

### Other Changes

```diff

-5025.0.25.103.0
+5028.0.21.0.0

+  - /System/Library/PrivateFrameworks/FitnessUI.framework/FitnessUI

-  Functions: 12909
-  Symbols:   11872
-  CStrings:  4666
+  Functions: 12728
+  Symbols:   11865
+  CStrings:  4678
Symbols:
+ +[DCMapsLink(ShortURLs) isShortAppleMapsURL:]
+ +[DCMapsLink(ShortURLs) mapsLinkFromParser:]
+ +[DCMapsLink(ShortURLs) resolveMapsLinkWithURL:completionHandler:]
+ +[WFBooleanContentItem typeSymbolName]
+ +[WFContentItem typeSymbolName]
+ +[WFDiskContentItem typeSymbolName]
+ +[WFDisplayContentItem typeSymbolName]
+ +[WFEmailContentItem typeSymbolName]
+ +[WFGenericFileContentItem typeSymbolName]
+ +[WFImageContentItem typeSymbolName]
+ +[WFMessageContentItem typeSymbolName]
+ +[WFNotificationContentItem typeSymbolName]
+ +[WFWalletTransactionContentItem typeSymbolName]
+ -[WFCNContact canReadPropertyID:]
+ GCC_except_table1043
+ GCC_except_table1047
+ GCC_except_table1052
+ GCC_except_table1059
+ GCC_except_table1067
+ GCC_except_table1068
+ GCC_except_table1114
+ GCC_except_table1120
+ GCC_except_table1125
+ GCC_except_table1127
+ GCC_except_table1132
+ GCC_except_table1192
+ GCC_except_table1207
+ GCC_except_table1221
+ GCC_except_table1222
+ GCC_except_table1258
+ GCC_except_table1265
+ GCC_except_table1283
+ GCC_except_table1302
+ GCC_except_table1317
+ GCC_except_table1433
+ GCC_except_table1439
+ GCC_except_table1444
+ GCC_except_table1453
+ GCC_except_table1460
+ GCC_except_table1464
+ GCC_except_table1470
+ GCC_except_table1611
+ GCC_except_table1613
+ GCC_except_table1615
+ GCC_except_table1635
+ GCC_except_table1637
+ GCC_except_table1777
+ GCC_except_table1778
+ GCC_except_table1792
+ GCC_except_table1793
+ GCC_except_table1829
+ GCC_except_table1835
+ GCC_except_table1838
+ GCC_except_table1890
+ GCC_except_table1911
+ GCC_except_table1920
+ GCC_except_table1929
+ GCC_except_table1935
+ GCC_except_table1996
+ GCC_except_table2012
+ GCC_except_table2045
+ GCC_except_table2053
+ GCC_except_table2059
+ GCC_except_table2068
+ GCC_except_table2101
+ GCC_except_table2104
+ GCC_except_table2161
+ GCC_except_table2162
+ GCC_except_table2168
+ GCC_except_table2177
+ GCC_except_table2184
+ GCC_except_table2185
+ GCC_except_table2192
+ GCC_except_table2196
+ GCC_except_table2199
+ GCC_except_table2214
+ GCC_except_table2247
+ GCC_except_table2266
+ GCC_except_table2267
+ GCC_except_table2268
+ GCC_except_table2277
+ GCC_except_table2289
+ GCC_except_table2291
+ GCC_except_table2304
+ GCC_except_table2305
+ GCC_except_table2307
+ GCC_except_table2314
+ GCC_except_table2386
+ GCC_except_table2446
+ GCC_except_table2497
+ GCC_except_table2503
+ GCC_except_table2519
+ GCC_except_table2540
+ GCC_except_table2542
+ GCC_except_table2557
+ GCC_except_table2560
+ GCC_except_table2561
+ GCC_except_table2574
+ GCC_except_table2594
+ GCC_except_table2599
+ GCC_except_table2604
+ GCC_except_table2609
+ GCC_except_table2622
+ GCC_except_table2631
+ GCC_except_table2641
+ GCC_except_table2646
+ GCC_except_table2683
+ GCC_except_table2684
+ GCC_except_table2685
+ GCC_except_table2686
+ GCC_except_table2687
+ GCC_except_table2688
+ GCC_except_table2699
+ GCC_except_table2701
+ GCC_except_table2727
+ GCC_except_table2799
+ GCC_except_table2869
+ GCC_except_table2926
+ GCC_except_table2938
+ GCC_except_table2976
+ GCC_except_table2991
+ GCC_except_table3097
+ GCC_except_table3104
+ GCC_except_table3118
+ GCC_except_table3130
+ GCC_except_table3132
+ GCC_except_table3134
+ GCC_except_table3144
+ GCC_except_table3148
+ GCC_except_table3202
+ GCC_except_table3207
+ GCC_except_table3244
+ GCC_except_table3273
+ GCC_except_table3314
+ GCC_except_table3324
+ GCC_except_table3327
+ GCC_except_table3411
+ GCC_except_table3502
+ GCC_except_table3503
+ GCC_except_table3507
+ GCC_except_table3690
+ GCC_except_table3711
+ GCC_except_table3715
+ GCC_except_table3745
+ GCC_except_table3747
+ GCC_except_table3838
+ GCC_except_table3902
+ GCC_except_table3911
+ GCC_except_table3914
+ GCC_except_table3977
+ GCC_except_table3995
+ GCC_except_table4064
+ GCC_except_table4191
+ GCC_except_table4213
+ GCC_except_table4220
+ GCC_except_table4232
+ GCC_except_table4257
+ GCC_except_table4260
+ GCC_except_table4350
+ GCC_except_table4384
+ GCC_except_table4386
+ GCC_except_table4389
+ GCC_except_table4391
+ GCC_except_table4392
+ GCC_except_table4417
+ GCC_except_table4476
+ GCC_except_table4496
+ GCC_except_table4501
+ GCC_except_table4508
+ GCC_except_table4619
+ GCC_except_table466
+ GCC_except_table4664
+ GCC_except_table4672
+ GCC_except_table4861
+ GCC_except_table487
+ GCC_except_table4886
+ GCC_except_table5101
+ GCC_except_table5136
+ GCC_except_table5138
+ GCC_except_table5140
+ GCC_except_table5149
+ GCC_except_table5159
+ GCC_except_table5171
+ GCC_except_table5174
+ GCC_except_table5249
+ GCC_except_table5261
+ GCC_except_table5324
+ GCC_except_table5337
+ GCC_except_table5412
+ GCC_except_table5416
+ GCC_except_table5423
+ GCC_except_table5430
+ GCC_except_table5489
+ GCC_except_table5623
+ GCC_except_table855
+ GCC_except_table886
+ GCC_except_table892
+ GCC_except_table897
+ GCC_except_table902
+ GCC_except_table912
+ GCC_except_table919
+ GCC_except_table932
+ GCC_except_table941
+ GCC_except_table942
+ _NSURLErrorFailingURLErrorKey
+ _OBJC_CLASS_$_FIUIWorkoutActivityType
+ _OBJC_CLASS_$_FIUIWorkoutActivityType$loadHelper_x8
+ _WFMapsLinkErrorDomain
+ __DATA__TtC10ContentKit15WFAFMCloudModel
+ __DATA__TtC10ContentKit18WFAFMCloudProModel
+ __METACLASS_DATA__TtC10ContentKit15WFAFMCloudModel
+ __METACLASS_DATA__TtC10ContentKit18WFAFMCloudProModel
+ __OBJC_$_CLASS_METHODS_DCMapsLink(CLGeocoding|WFSerializableContent|WFNaming|MKDirections|WFLocationCoercions|MKGeometry|ShortURLs)
+ __OBJC_$_INSTANCE_METHODS_DCMapsLink(CLGeocoding|WFSerializableContent|WFNaming|MKDirections|WFLocationCoercions|MKGeometry|ShortURLs)
+ __OBJC_CLASS_PROTOCOLS_$_DCMapsLink(CLGeocoding|WFSerializableContent|WFNaming|MKDirections|WFLocationCoercions|MKGeometry|ShortURLs)
+ ___66+[DCMapsLink(ShortURLs) resolveMapsLinkWithURL:completionHandler:]_block_invoke
+ ___67-[WFURLContentItem generateObjectRepresentations:options:forClass:]_block_invoke_5
+ ___block_descriptor_40_e8_32bs_e32_v24?0"DCMapsLink"8"NSError"16ls32l8
+ ___block_descriptor_56_e8_32s40bs_e34_v24?0"_MKURLParser"8"NSError"16ls40l8s32l8
+ ___get_MKURLParserClass_block_invoke
+ ___swift_closure_destructor.138Tm
+ __os_signpost_emit_with_name_impl
+ _dlopenHelper$FitnessUI
+ _dlopenHelperFlag$FitnessUI
+ _get_MKURLParserClass
+ _get_MKURLParserClass.softClass
+ _symbolic _____ 10ContentKit15WFAFMCloudModelC
+ _symbolic _____ 10ContentKit18WFAFMCloudProModelC
- GCC_except_table1040
- GCC_except_table1044
- GCC_except_table1049
- GCC_except_table1056
- GCC_except_table1061
- GCC_except_table1065
- GCC_except_table1111
- GCC_except_table1117
- GCC_except_table1122
- GCC_except_table1124
- GCC_except_table1129
- GCC_except_table1189
- GCC_except_table1204
- GCC_except_table1218
- GCC_except_table1219
- GCC_except_table1255
- GCC_except_table1262
- GCC_except_table1280
- GCC_except_table1299
- GCC_except_table1314
- GCC_except_table1430
- GCC_except_table1436
- GCC_except_table1441
- GCC_except_table1450
- GCC_except_table1457
- GCC_except_table1461
- GCC_except_table1467
- GCC_except_table1605
- GCC_except_table1610
- GCC_except_table1612
- GCC_except_table1632
- GCC_except_table1634
- GCC_except_table1773
- GCC_except_table1774
- GCC_except_table1788
- GCC_except_table1789
- GCC_except_table1825
- GCC_except_table1830
- GCC_except_table1831
- GCC_except_table1885
- GCC_except_table1906
- GCC_except_table1915
- GCC_except_table1924
- GCC_except_table1930
- GCC_except_table1991
- GCC_except_table2002
- GCC_except_table2040
- GCC_except_table2048
- GCC_except_table2049
- GCC_except_table2063
- GCC_except_table2096
- GCC_except_table2099
- GCC_except_table2156
- GCC_except_table2157
- GCC_except_table2163
- GCC_except_table2167
- GCC_except_table2179
- GCC_except_table2180
- GCC_except_table2182
- GCC_except_table2191
- GCC_except_table2194
- GCC_except_table2204
- GCC_except_table2242
- GCC_except_table2261
- GCC_except_table2262
- GCC_except_table2263
- GCC_except_table2272
- GCC_except_table2284
- GCC_except_table2286
- GCC_except_table2299
- GCC_except_table2300
- GCC_except_table2302
- GCC_except_table2309
- GCC_except_table2381
- GCC_except_table2441
- GCC_except_table2487
- GCC_except_table2498
- GCC_except_table2514
- GCC_except_table2532
- GCC_except_table2535
- GCC_except_table2552
- GCC_except_table2555
- GCC_except_table2556
- GCC_except_table2569
- GCC_except_table2587
- GCC_except_table2588
- GCC_except_table2592
- GCC_except_table2603
- GCC_except_table2616
- GCC_except_table2625
- GCC_except_table2635
- GCC_except_table2640
- GCC_except_table2671
- GCC_except_table2672
- GCC_except_table2673
- GCC_except_table2674
- GCC_except_table2681
- GCC_except_table2682
- GCC_except_table2693
- GCC_except_table2695
- GCC_except_table2721
- GCC_except_table2793
- GCC_except_table2862
- GCC_except_table2919
- GCC_except_table2931
- GCC_except_table2969
- GCC_except_table2984
- GCC_except_table3089
- GCC_except_table3096
- GCC_except_table3110
- GCC_except_table3122
- GCC_except_table3124
- GCC_except_table3126
- GCC_except_table3136
- GCC_except_table3140
- GCC_except_table3194
- GCC_except_table3199
- GCC_except_table3236
- GCC_except_table3265
- GCC_except_table3306
- GCC_except_table3316
- GCC_except_table3319
- GCC_except_table3403
- GCC_except_table3494
- GCC_except_table3495
- GCC_except_table3499
- GCC_except_table3682
- GCC_except_table3703
- GCC_except_table3707
- GCC_except_table3737
- GCC_except_table3739
- GCC_except_table3830
- GCC_except_table3887
- GCC_except_table3894
- GCC_except_table3906
- GCC_except_table3969
- GCC_except_table3987
- GCC_except_table4056
- GCC_except_table4181
- GCC_except_table4203
- GCC_except_table4210
- GCC_except_table4222
- GCC_except_table4247
- GCC_except_table4250
- GCC_except_table4340
- GCC_except_table4374
- GCC_except_table4376
- GCC_except_table4379
- GCC_except_table4381
- GCC_except_table4382
- GCC_except_table4407
- GCC_except_table4466
- GCC_except_table4486
- GCC_except_table4491
- GCC_except_table4498
- GCC_except_table4609
- GCC_except_table465
- GCC_except_table4654
- GCC_except_table4662
- GCC_except_table4850
- GCC_except_table486
- GCC_except_table4875
- GCC_except_table5118
- GCC_except_table5120
- GCC_except_table5122
- GCC_except_table5123
- GCC_except_table5131
- GCC_except_table5153
- GCC_except_table5156
- GCC_except_table5231
- GCC_except_table5243
- GCC_except_table5305
- GCC_except_table5318
- GCC_except_table5323
- GCC_except_table5396
- GCC_except_table5400
- GCC_except_table5407
- GCC_except_table5414
- GCC_except_table5473
- GCC_except_table5607
- GCC_except_table853
- GCC_except_table884
- GCC_except_table888
- GCC_except_table891
- GCC_except_table900
- GCC_except_table910
- GCC_except_table917
- GCC_except_table930
- GCC_except_table939
- GCC_except_table940
- _FitnessUILibraryCore.frameworkLibrary
- _OUTLINED_FUNCTION_723
- _OUTLINED_FUNCTION_724
- _OUTLINED_FUNCTION_725
- _OUTLINED_FUNCTION_726
- _OUTLINED_FUNCTION_727
- _OUTLINED_FUNCTION_728
- _OUTLINED_FUNCTION_729
- _OUTLINED_FUNCTION_730
- _OUTLINED_FUNCTION_731
- _OUTLINED_FUNCTION_732
- _OUTLINED_FUNCTION_733
- _OUTLINED_FUNCTION_734
- _OUTLINED_FUNCTION_735
- _OUTLINED_FUNCTION_736
- _OUTLINED_FUNCTION_737
- _OUTLINED_FUNCTION_738
- _OUTLINED_FUNCTION_739
- _OUTLINED_FUNCTION_740
- _OUTLINED_FUNCTION_741
- _OUTLINED_FUNCTION_742
- _OUTLINED_FUNCTION_743
- _OUTLINED_FUNCTION_744
- _OUTLINED_FUNCTION_745
- __DATA__TtC10ContentKit13WFAFMProModel
- __DATA__TtC10ContentKit26WFAFMInstructServerV1Model
- __METACLASS_DATA__TtC10ContentKit13WFAFMProModel
- __METACLASS_DATA__TtC10ContentKit26WFAFMInstructServerV1Model
- __OBJC_$_CLASS_METHODS_DCMapsLink(CLGeocoding|WFSerializableContent|WFNaming|MKDirections|WFLocationCoercions|MKGeometry)
- __OBJC_$_INSTANCE_METHODS_DCMapsLink(CLGeocoding|WFSerializableContent|WFNaming|MKDirections|WFLocationCoercions|MKGeometry)
- __OBJC_CLASS_PROTOCOLS_$_DCMapsLink(CLGeocoding|WFSerializableContent|WFNaming|MKDirections|WFLocationCoercions|MKGeometry)
- ___FitnessUILibraryCore_block_invoke
- ___getCNContactContactRelationsKeySymbolLoc_block_invoke
- ___getFIUIWorkoutActivityTypeClass_block_invoke
- ___swift_closure_destructor.140Tm
- ___swift_closure_destructor.151Tm
- _audit_stringFitnessUI
- _getCNContactContactRelationsKeySymbolLoc.ptr
- _getFIUIWorkoutActivityTypeClass
- _getFIUIWorkoutActivityTypeClass.softClass
- _symbolic _____ 10ContentKit13WFAFMProModelC
- _symbolic _____ 10ContentKit26WFAFMInstructServerV1ModelC
- _symbolic _____ 10ContentKit36WFFoundationModelsAskLLMModelSessionC10TokenUsage33_BD770DC1AE1CE216BB128F3DFB3F9A58LLV
- _symbolic _____m 10ContentKit12FMListOutputV
- _type_layout_string 10ContentKit36WFFoundationModelsAskLLMModelSessionC10TokenUsage33_BD770DC1AE1CE216BB128F3DFB3F9A58LLV
CStrings:
+ ". Use the current date to answer questions involving dates, time, or how long ago something happened. If you're asked, the current US president is Donald Trump, and the vice-president is JD Vance.\n\n"
+ "/System/Library/PrivateFrameworks/FitnessUI.framework/FitnessUI"
+ "/p/"
+ "Attempted to get token count from a session that had not yet started yet"
+ "Class get_MKURLParserClass(void)_block_invoke"
+ "DCMapsLink+ShortURLs.m"
+ "FitnessUI"
+ "Generated response successfully with safetyLevel=%s: %s"
+ "Make sure you're logged into iCloud, and that a paid iCloud plan is active."
+ "NSString *getCNContactRelationsKey(void)"
+ "Session ended with %s token count = %ld tokens"
+ "The Maps URL could not be resolved."
+ "The action could not run because you must be signed in to an iCloud+ account to use the Cloud Pro model."
+ "UseModelGenerateResponse"
+ "UseModelModelRespondOnDevice"
+ "UseModelModelRespondPCC"
+ "UseModelModelRespondPCCPro"
+ "WFMapsLinkErrorDomain"
+ "You are a foundation model developed by Apple. Mention this only when directly asked who or what you are — never volunteer it otherwise. A conversation between a user and a helpful assistant. The current time is "
+ "Your output MUST be a JSON dictionary with a 'response' field. 'response' is a JSON object with a schema that matches what the user asked for. Do not respond with just one 'text' item in 'response'. Acceptable values for 'response' are numbers, strings, booleans, dictionaries and arrays. If the user provides a list of fields to output, follow it closely and don't nest the output in a root object: output the fields directly into the 'response' field."
+ "[Error] Interval already ended"
+ "_MKURLParser"
+ "bell.badge"
+ "creditcard"
+ "doc"
+ "envelope"
+ "externaldrive"
+ "facetime-group"
+ "maps.apple"
+ "maps.apple.cn"
+ "message"
+ "photo"
+ "switch.2"
+ "v24@?0@\"DCMapsLink\"8@\"NSError\"16"
+ "v24@?0@\"_MKURLParser\"8@\"NSError\"16"
- ". Use the current date to answer questions involving dates, time, or how long ago something happened.\n\n"
- "Asked to enable web search, but the feature flag is disabled"
- "CNContactContactRelationsKey"
- "Class getFIUIWorkoutActivityTypeClass(void)_block_invoke"
- "ContentKit/WFFMToolConfiguration.swift"
- "Generated safety v2 response successfully: %s"
- "Ignoring handle_with_care in safety token v2 response due to feature flag enabled"
- "Model generated handleWithCare response, returning content for type: %s"
- "Model generated handleWithCare response, throwing an error..."
- "Model generated handleWithCare responses using v2 adapter, returning content for type: %s"
- "Model generated handleWithCare responses using v2 adapter, throwing an error..."
- "Model returned a handleWithCare response (v2 adapter)"
- "NSString *getCNContactContactRelationsKey(void)"
- "PCCAskAFMVersion"
- "Private Cloud Compute"
- "Recorded token usage for turn #%ld: consumed=%ld, generated=%ld (totals: consumed=%ld, generated=%ld)"
- "WFFitnessWorkoutActivityTypeContentItem.m"
- "WFFoundationModelsAskLLMModelSession returning %s token count: %ld"
- "You are a foundation model developed by Apple. Only mention this if it is directly relevant to the user request. A conversation between a user and a helpful assistant. The current time is "
- "Your output MUST be a JSON dictionary with a 'response' field. 'response' is a JSON object with any schema you decide. Your keys for 'response' must be strings. Use a JSON schema optimized for data extraction, over a single human-readable response. Never respond with just one 'text' item in the dictionary. You can use any complex schema for JSON dictionary values, including nested dictionaries, numbers, strings, booleans and arrays."
- "onDeviceAdapterVersion"
- "softlink:r:path:/System/Library/PrivateFrameworks/FitnessUI.framework/FitnessUI"
- "void *FitnessUILibrary(void)"
```
