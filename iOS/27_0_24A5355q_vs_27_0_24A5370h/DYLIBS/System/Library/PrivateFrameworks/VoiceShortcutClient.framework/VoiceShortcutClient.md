## VoiceShortcutClient

> `/System/Library/PrivateFrameworks/VoiceShortcutClient.framework/VoiceShortcutClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15038c` | `0x152bec` | **`+0x2860`** |
| `__AUTH_CONST.__objc_const` | `0x1a358` | `0x1a678` | **`+0x320`** |
| `__AUTH_CONST.__const` | `0xa158` | `0xa418` | **`+0x2c0`** |
| `__TEXT.__cstring` | `0x17ebe` | `0x180e0` | **`+0x222`** |
| `__TEXT.__const` | `0xff40` | `0x10100` | **`+0x1c0`** |
| `__DATA.__bss` | `0x1b310` | `0x1b4a0` | **`+0x190`** |
| `__TEXT.__objc_methlist` | `0xcc3c` | `0xcdbc` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x6f90` | `0x70d8` | **`+0x148`** |
| `__DATA.__data` | `0x4520` | `0x4620` | **`+0x100`** |
| `__DATA_CONST.__objc_selrefs` | `0x5fc8` | `0x60b0` | **`+0xe8`** |
| `__TEXT.__eh_frame` | `0x6340` | `0x63f0` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x3ead` | `0x3f5d` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x3714` | `0x37b0` | **`+0x9c`** |
| `__TEXT.__swift5_typeref` | `0x39c7` | `0x3a61` | **`+0x9a`** |
| `__TEXT.__swift5_reflstr` | `0x16b4` | `0x1644` | **`-0x70`** |
| `__AUTH_CONST.__cfstring` | `0x199c0` | `0x19a20` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x3e48` | `0x3ea0` | **`+0x58`** |
| `__AUTH_CONST.__objc_dictobj` | `0x230` | `0x258` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1e50` | `0x1e70` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x1ba0` | `0x1bc0` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x708` | `0x6e8` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x2d08` | `0x2d24` | **`+0x1c`** |
| `__DATA.__objc_ivar` | `0xcfc` | `0xd14` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x11f0` | `0x1208` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x4b0` | `0x4c8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x191c` | `0x1908` | **`-0x14`** |
| `__TEXT.__swift5_proto` | `0xda8` | `0xdbc` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x1c0` | `0x1d4` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x450` | `0x45c` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0xe4` | `0xf0` | **`+0xc`** |
| `__DATA.__common` | `0xa8` | `0xb0` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x3740` | `0x3748` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x998` | `0x9a0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x7e8` | `0x7f0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x4c` | `0x50` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xfc` | `0x100` | **`+0x4`** |

### Other Changes

```diff

-5025.0.25.103.0
+5028.0.21.0.0

-  Functions: 10664
-  Symbols:   11611
-  CStrings:  4367
+  Functions: 10783
+  Symbols:   11664
+  CStrings:  4389
Symbols:
+ +[WFLocalizationBundleCache sharedCache]
+ +[WFLocalizationContext bundleCacheHitCount]
+ +[WFLocalizationContext bundleCacheMissCount]
+ +[WFLocalizationContext cacheAllLocales]
+ +[WFLocalizationContext resetBundleCache]
+ +[WFLocalizationContext setCacheAllLocales:]
+ -[WFChooseFromListDialogRequest isDestructive]
+ -[WFChooseFromListDialogRequest setIsDestructive:]
+ -[WFLocalizationBundleCache .cxx_destruct]
+ -[WFLocalizationBundleCache bundleForURL:]
+ -[WFLocalizationBundleCache hitCount]
+ -[WFLocalizationBundleCache init]
+ -[WFLocalizationBundleCache missCount]
+ -[WFLocalizationBundleCache reset]
+ -[WFOutOfProcessWorkflowController hydrateEncodedRemoteHydrationRequest:completionHandler:]
+ -[WFOutOfProcessWorkflowControllerXPCProxy hydrateEncodedRemoteHydrationRequest:completionHandler:]
+ -[WFSageWorkflowRunnerClient hydrateEncodedRemoteHydrationRequest:completionHandler:]
+ GCC_except_table1001
+ GCC_except_table1143
+ GCC_except_table1147
+ GCC_except_table1169
+ GCC_except_table1170
+ GCC_except_table1171
+ GCC_except_table1180
+ GCC_except_table1249
+ GCC_except_table1280
+ GCC_except_table1324
+ GCC_except_table1325
+ GCC_except_table1326
+ GCC_except_table1416
+ GCC_except_table1420
+ GCC_except_table1455
+ GCC_except_table1473
+ GCC_except_table1500
+ GCC_except_table1505
+ GCC_except_table1511
+ GCC_except_table1556
+ GCC_except_table1560
+ GCC_except_table1561
+ GCC_except_table1572
+ GCC_except_table1577
+ GCC_except_table1650
+ GCC_except_table1651
+ GCC_except_table1710
+ GCC_except_table1786
+ GCC_except_table1803
+ GCC_except_table1852
+ GCC_except_table1873
+ GCC_except_table1875
+ GCC_except_table1877
+ GCC_except_table1939
+ GCC_except_table1940
+ GCC_except_table1942
+ GCC_except_table1951
+ GCC_except_table1959
+ GCC_except_table1961
+ GCC_except_table1982
+ GCC_except_table2107
+ GCC_except_table2130
+ GCC_except_table2173
+ GCC_except_table2203
+ GCC_except_table2258
+ GCC_except_table2269
+ GCC_except_table2294
+ GCC_except_table2317
+ GCC_except_table2322
+ GCC_except_table2325
+ GCC_except_table235
+ GCC_except_table2400
+ GCC_except_table2465
+ GCC_except_table2472
+ GCC_except_table2480
+ GCC_except_table2697
+ GCC_except_table2750
+ GCC_except_table2754
+ GCC_except_table2759
+ GCC_except_table2790
+ GCC_except_table2910
+ GCC_except_table2913
+ GCC_except_table2926
+ GCC_except_table2931
+ GCC_except_table2956
+ GCC_except_table3173
+ GCC_except_table3243
+ GCC_except_table3255
+ GCC_except_table3258
+ GCC_except_table3333
+ GCC_except_table3339
+ GCC_except_table3345
+ GCC_except_table337
+ GCC_except_table3498
+ GCC_except_table3499
+ GCC_except_table3566
+ GCC_except_table358
+ GCC_except_table3673
+ GCC_except_table3681
+ GCC_except_table3683
+ GCC_except_table3684
+ GCC_except_table3689
+ GCC_except_table3690
+ GCC_except_table3691
+ GCC_except_table3693
+ GCC_except_table3733
+ GCC_except_table3832
+ GCC_except_table3861
+ GCC_except_table3862
+ GCC_except_table3863
+ GCC_except_table4072
+ GCC_except_table4079
+ GCC_except_table4082
+ GCC_except_table4085
+ GCC_except_table4087
+ GCC_except_table4095
+ GCC_except_table4200
+ GCC_except_table4204
+ GCC_except_table4217
+ GCC_except_table4324
+ GCC_except_table4375
+ GCC_except_table4404
+ GCC_except_table4409
+ GCC_except_table4412
+ GCC_except_table4415
+ GCC_except_table4418
+ GCC_except_table4421
+ GCC_except_table4426
+ GCC_except_table4430
+ GCC_except_table4433
+ GCC_except_table4435
+ GCC_except_table4438
+ GCC_except_table4441
+ GCC_except_table4448
+ GCC_except_table4453
+ GCC_except_table4458
+ GCC_except_table4475
+ GCC_except_table4479
+ GCC_except_table4492
+ GCC_except_table4510
+ GCC_except_table483
+ GCC_except_table494
+ GCC_except_table504
+ GCC_except_table706
+ GCC_except_table868
+ _OBJC_CLASS_$_OS_voucher
+ _OBJC_CLASS_$_WFLocalizationBundleCache
+ _OBJC_IVAR_$_WFChooseFromListDialogRequest._isDestructive
+ _OBJC_IVAR_$_WFLocalizationBundleCache._bundleByURL
+ _OBJC_IVAR_$_WFLocalizationBundleCache._hitCount
+ _OBJC_IVAR_$_WFLocalizationBundleCache._lock
+ _OBJC_IVAR_$_WFLocalizationBundleCache._missCount
+ _OBJC_IVAR_$_WFWorkflowRunnerClient._progressSubscriberLock
+ _OBJC_METACLASS_$_WFLocalizationBundleCache
+ _OUTLINED_FUNCTION_138
+ _OUTLINED_FUNCTION_139
+ _OUTLINED_FUNCTION_140
+ _OUTLINED_FUNCTION_141
+ _OUTLINED_FUNCTION_142
+ _OUTLINED_FUNCTION_143
+ _OUTLINED_FUNCTION_144
+ __OBJC_$_CLASS_METHODS_WFLocalizationBundleCache
+ __OBJC_$_CLASS_PROP_LIST_WFLocalizationBundleCache
+ __OBJC_$_INSTANCE_METHODS_WFLocalizationBundleCache
+ __OBJC_$_INSTANCE_VARIABLES_WFLocalizationBundleCache
+ __OBJC_$_PROP_LIST_WFLocalizationBundleCache
+ __OBJC_CLASS_RO_$_WFLocalizationBundleCache
+ __OBJC_METACLASS_RO_$_WFLocalizationBundleCache
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIPU8__strongP21WFDebouncerPokeReasonEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
+ __ZNSt3__15dequeIU8__strongP21WFDebouncerPokeReasonNS_9allocatorIS3_EEED2B9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___40+[WFLocalizationBundleCache sharedCache]_block_invoke
+ ___99-[WFOutOfProcessWorkflowControllerXPCProxy hydrateEncodedRemoteHydrationRequest:completionHandler:]_block_invoke
+ ___swift_closure_destructor.15Tm
+ __cacheAllLocales
+ _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationEventStreamVyxGAA08XPCEventG0AA0F0AaEP_AA0H0
+ _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV10CodingKeysOSHAASQ
+ _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV10CodingKeysOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV10CodingKeysOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV21XPCEventDecodingError33_08694074C2DE9F1872C48A0BC4A47D2FLLOSHAASQ
+ _class_getClassMethod
+ _sharedCache.cache
+ _sharedCache.onceToken
+ _swift_dynamicCastMetatype
+ _symbolic $s19VoiceShortcutClient40DistributedNotificationEventStreamSourceP
+ _symbolic SS8typeName_SS16bundleIdentifiert
+ _symbolic Sccyyt______pG s5ErrorP
+ _symbolic So10OS_voucherCSg
+ _symbolic _____ 19VoiceShortcutClient17DistnotedMatchingO
+ _symbolic _____ 19VoiceShortcutClient20WFEntityPrewarmErrorO
+ _symbolic _____ 19VoiceShortcutClient24DistnotedMatchingTrustedO
+ _symbolic _____ 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV
+ _symbolic _____ 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV10CodingKeysO
+ _symbolic _____ 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV21XPCEventDecodingError33_08694074C2DE9F1872C48A0BC4A47D2FLLO
+ _type_layout_string 19VoiceShortcutClient20WFEntityPrewarmErrorO
+ _type_layout_string 19VoiceShortcutClient37XPCDistributedNotificationStreamEventV
+ _voucher_adopt
+ _voucher_copy
- GCC_except_table1140
- GCC_except_table1144
- GCC_except_table1166
- GCC_except_table1167
- GCC_except_table1168
- GCC_except_table1177
- GCC_except_table1246
- GCC_except_table1277
- GCC_except_table1316
- GCC_except_table1318
- GCC_except_table1320
- GCC_except_table1413
- GCC_except_table1417
- GCC_except_table1452
- GCC_except_table1470
- GCC_except_table1497
- GCC_except_table1502
- GCC_except_table1508
- GCC_except_table1553
- GCC_except_table1555
- GCC_except_table1557
- GCC_except_table1569
- GCC_except_table1574
- GCC_except_table1647
- GCC_except_table1648
- GCC_except_table1705
- GCC_except_table1781
- GCC_except_table1798
- GCC_except_table1847
- GCC_except_table1868
- GCC_except_table1870
- GCC_except_table1872
- GCC_except_table1930
- GCC_except_table1932
- GCC_except_table1934
- GCC_except_table1946
- GCC_except_table1954
- GCC_except_table1956
- GCC_except_table1977
- GCC_except_table2101
- GCC_except_table2124
- GCC_except_table2167
- GCC_except_table2197
- GCC_except_table2252
- GCC_except_table2263
- GCC_except_table2288
- GCC_except_table2311
- GCC_except_table2316
- GCC_except_table2319
- GCC_except_table234
- GCC_except_table2394
- GCC_except_table2459
- GCC_except_table2466
- GCC_except_table2474
- GCC_except_table256
- GCC_except_table2691
- GCC_except_table2744
- GCC_except_table2748
- GCC_except_table2753
- GCC_except_table2784
- GCC_except_table2904
- GCC_except_table2907
- GCC_except_table2914
- GCC_except_table2925
- GCC_except_table2944
- GCC_except_table3154
- GCC_except_table3224
- GCC_except_table3236
- GCC_except_table3239
- GCC_except_table3314
- GCC_except_table3320
- GCC_except_table3326
- GCC_except_table336
- GCC_except_table3479
- GCC_except_table3480
- GCC_except_table3547
- GCC_except_table357
- GCC_except_table3634
- GCC_except_table3654
- GCC_except_table3655
- GCC_except_table3662
- GCC_except_table3664
- GCC_except_table3665
- GCC_except_table3670
- GCC_except_table3671
- GCC_except_table3714
- GCC_except_table3813
- GCC_except_table3842
- GCC_except_table3843
- GCC_except_table3844
- GCC_except_table4053
- GCC_except_table4060
- GCC_except_table4063
- GCC_except_table4066
- GCC_except_table4068
- GCC_except_table4076
- GCC_except_table4181
- GCC_except_table4185
- GCC_except_table4198
- GCC_except_table4305
- GCC_except_table4356
- GCC_except_table4385
- GCC_except_table4390
- GCC_except_table4393
- GCC_except_table4396
- GCC_except_table4399
- GCC_except_table4402
- GCC_except_table4407
- GCC_except_table4411
- GCC_except_table4414
- GCC_except_table4416
- GCC_except_table4419
- GCC_except_table4422
- GCC_except_table4429
- GCC_except_table4434
- GCC_except_table4439
- GCC_except_table4456
- GCC_except_table4460
- GCC_except_table4473
- GCC_except_table4491
- GCC_except_table480
- GCC_except_table485
- GCC_except_table498
- GCC_except_table703
- GCC_except_table865
- GCC_except_table998
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIPU8__strongP21WFDebouncerPokeReasonEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
- __ZNSt3__15dequeIU8__strongP21WFDebouncerPokeReasonNS_9allocatorIS3_EEED2B9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- ___swift_closure_destructor.10Tm
- _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V10CodingKeysOSHAASQ
- _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V10CodingKeysOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V10CodingKeysOs0H3KeyAAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V21XPCEventDecodingError33_08694074C2DE9F1872C48A0BC4A47D2FLLOSHAASQ
- _associated conformance 19VoiceShortcutClient37XPCDistributedNotificationEventStreamVAA08XPCEventG0AA0F0AaDP_AA0H0
- _objc_sync_enter
- _objc_sync_exit
- _symbolic _____ 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V
- _symbolic _____ 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V10CodingKeysO
- _symbolic _____ 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V21XPCEventDecodingError33_08694074C2DE9F1872C48A0BC4A47D2FLLO
- _type_layout_string 19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V
- _xpc_add_bundle
CStrings:
+ "; cannot prewarm."
+ "A"
+ "AskVQAIntent"
+ "Cannot prewarm: no entity metadata for %s in %s"
+ "LNQueryPropertyResolution"
+ "No entity metadata for "
+ "OneShotDescribeSceneIntent"
+ "Prewarming connection for %s from %s"
+ "Property resolution not available request will return all properties"
+ "additionalDeferredProperties:"
+ "com.apple.accessibility.MagnifierAngel"
+ "com.apple.distnoted.matching.trusted"
+ "deferredPropertyResolutionConcurrencyLimit"
+ "deferredPropertyResolutionTimeout"
+ "entityServiceHydration"
+ "id"
+ "immediate"
+ "includedProperties:"
+ "maximumArrayPropertyItemCount"
+ "maximumEntityDepth"
+ "propertyResolution"
+ "reasons"
+ "retryCount"
+ "setDeferredPropertyResolutionConcurrencyLimit:"
+ "setDeferredPropertyResolutionTimeout:"
+ "setMaximumArrayPropertyItemCount:"
+ "setMaximumEntityDepth:"
+ "setPropertyResolution:"
+ "testingConfig"
+ "timestamp"
- "performHydration"
- "use_model_external_partners"
- "use_model_fm"
- "use_model_hide_legacy_chatgpt"
- "use_model_pro"
- "use_model_v10"
- "use_model_web_search_via_pcc"
- "use_model_zap"
```
