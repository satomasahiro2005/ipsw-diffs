## ExtensionFoundation

> `/System/Library/Frameworks/ExtensionFoundation.framework/ExtensionFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1166f4` | `0x116898` | **`+0x1a4`** |
| `__TEXT.__eh_frame` | `0x4798` | `0x4790` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x4300` | `0x42f8` | **`-0x8`** |

### Other Changes

```diff

-289.1.0.0.0
+289.2.0.0.0
Functions:
~ ___72+[EXConcreteExtension beginMatchingExtensionsWithAttributes:completion:]_block_invoke_2 : 552 -> 548
~ -[EXConcreteExtension dealloc] : 592 -> 588
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_yXlTt0g5Tf4g_n : 252 -> 276
~ _$s19ExtensionFoundation15QueryControllerC6resumeyyF : 1652 -> 1664
~ __EXAuditTokenHasRequiredEntitlements : 600 -> 596
~ _$s19ExtensionFoundation22_EXDiscoveryControllerC10identities8matchingAA14_EXQueryResultCAA01_G0C_tFyyXEfU_ : 364 -> 372
~ _$s19ExtensionFoundation03AppA5PointV09extensionD7Records12capabilitiesACSayAA8DatabaseV0aD6Record_pG_AC12CapabilitiesVtKcfC : 508 -> 532
~ _$s19ExtensionFoundation17CapabilityManagerC0C4Pack33_9664FE1351C0001FC65643A20F092796LLVMr : 324 -> 316
~ _$s19ExtensionFoundation23LocalLSDatabaseObserverC6update8identity4hostAA03AppA5PointV7MonitorC5StateVAJ8IdentityV_AA10AuditTokenVtKFZSayAA8DatabaseV0aJ6Record_pGArS_pXEfU0_ : 2140 -> 2132
~ _$s19ExtensionFoundation23LocalLSDatabaseObserverC6update8identity4hostAA03AppA5PointV7MonitorC5StateVAJ8IdentityV_AA10AuditTokenVtKFZ : 2456 -> 2504
~ _$s19ExtensionFoundation23LocalLSDatabaseObserverC6canAdd21extensionPointRecords4hostSbSayAA8DatabaseV0aI6Record_pG_AA10AuditTokenVtFZTf4nnd_n : 628 -> 640
~ _$sSMsSKRzrlE14_insertionSort6within9sortedEnd2byySny5IndexSlQzG_AFSb7ElementSTQz_AItKXEtKFSrySSG_Tg5 : 272 -> 288
~ _$s19ExtensionFoundation14_EXActiveQueryC6updateyyF : 8900 -> 9020
~ _$s19ExtensionFoundation23LocalLSDatabaseObserverC7results3for4host7optionsSayAA03AppA8IdentityVG10identities_Si15unapprovedCountSi08disabledN0tAA8DatabaseV0A11PointRecord_p_AA10AuditTokenVAA0jaQ0V7MonitorC7OptionsVtFZTf4nnnd_n : 6852 -> 6876
~ ___swift_closure_destructor : 128 -> 136
~ ___swift_closure_destructor : 120 -> 128
~ _$sSlsE3mapySayqd__Gqd__7ElementQzqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFShySo20_EXExtensionIdentityCG_AGs5NeverOTg5088$s19ExtensionFoundation15QueryControllerC15resultDidUpdateyyAA014_EXQueryResultG0CFSo20_dE8CAHXEfU_Shy10Foundation4UUIDVG0hU00jK0CTf1cn_nTf4nnd_n : 1440 -> 1424
~ _$sSlsE3mapySayqd__Gqd__7ElementQzqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFShySo20_EXExtensionIdentityCG_AGs5NeverOTg5082$s19ExtensionFoundation15QueryControllerC22remapCurrentIdentitiesyyFyyYbXEfU_So20_dE8CAFXEfU_0H10Foundation0jK0CTf1cn_nTf4nd_n : 780 -> 772
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 280 -> 276
~ _$sSDsSQR_rlE2eeoiySbSDyxq_G_ABtFZSS_SSTt1g5 : 396 -> 392
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_ypTt0g5Tf4g_n : 256 -> 276
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCs11AnyHashableV_ypTt0g5Tf4g_n : 256 -> 264
~ _$s19ExtensionFoundation09_InnerAppA8IdentityPAAE12capabilitiesSaySSGvgAA0daE0V06RecordE0V_Tg5 : 1116 -> 1124
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_SDySSypGTt0g5Tf4g_nTm : 244 -> 268
~ _$ss17_NativeDictionaryV8setValue_6forKey8isUniqueyq_n_xSbtFSS_SSTg5 : 388 -> 384
~ _$sSDyq_SgxcisSS_SSTg5 : 324 -> 320
~ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFSS_SSTg5 : 692 -> 684
~ _$s19ExtensionFoundation03AppA7ProcessV13configurationA2C13ConfigurationV_tYaKcfcAA05InnercaD0CyYaKcfU_TA : 240 -> 244
~ +[NSUUID(ExtensionKitAdditions) _EX_UUIDWithDigestBytes:size:] : 208 -> 212
~ ___81+[EXConcreteExtension extensionsWithMatchingAttributes:synchronously:completion:]_block_invoke : 396 -> 392
~ -[NSMutableDictionary(ExtensionKitAdditions) _EX_overlayDictionary:] : 388 -> 384
~ _$s19ExtensionFoundation15EXExtensionMainyS2i_SpySPys4Int8VGGSgtF15extractArgumentL_4nameSSSgSS_tF : 784 -> 800
~ _$s7Network15NWApplicationIDV19ExtensionFoundationE011findEncodeda3AppC033_FA5A5127B348FED6EA31068C17FE374ELL4fromSSSgSaySSG_tFZTf4nd_n : 204 -> 208
~ -[EXConcreteExtension _initWithPKPlugin:identity:] : 976 -> 972
~ -[EXExtensionContextImplementation completeRequestReturningItems:completionHandler:] : 1136 -> 1132
~ ___33-[_EXDefaults extensionItemTypes]_block_invoke : 540 -> 536
~ -[EXExtensionContextImplementation initWithInputItems:listenerEndpoint:contextUUID:extensionContext:] : 1124 -> 1116
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_SSTt0g5Tf4g_n : 272 -> 276
~ sub_186e2814c -> sub_186f1b270 : 316 -> 308
~ sub_186e28288 -> sub_186f1b3a4 : 308 -> 300
~ -[EXConcreteExtension _itemProviderForPayload:extensionContext:] : 568 -> 564
~ ___37-[EXConcreteExtension _dropAssertion]_block_invoke : 296 -> 292
~ ___52-[EXConcreteExtension _hostWillEnterForegroundNote:]_block_invoke : 336 -> 332
~ ___51-[EXConcreteExtension _hostDidEnterBackgroundNote:]_block_invoke : 336 -> 332
~ ___49-[EXConcreteExtension _hostWillResignActiveNote:]_block_invoke : 336 -> 332
~ ___48-[EXConcreteExtension _hostDidBecomeActiveNote:]_block_invoke : 336 -> 332
~ -[EXExtensionPointCatalog initWithEnumerator:] : 464 -> 460
~ ___131+[EXConcreteExtension(NSExtensionActiveWebPageAlternative) _inputItemsByApplyingActiveWebPageAlternative:ifNeededByActivationRule:]_block_invoke : 492 -> 488
~ ___141+[EXConcreteExtension(NSExtensionActiveWebPageAlternative) _dictionaryIncludingOnlyItemsWithRegisteredTypeIdentifier:fromMatchingDictionary:]_block_invoke : 548 -> 544
~ _EXExtensionIsSafeKeyPathForObjectsInCollection : 376 -> 372
~ _EXExtensionIsSafeKeyPathForSubcollectionsOfClassOfCollection : 352 -> 348
~ _EXExtensionIsSafePredicateForObjectWithSubquerySubstitutions : 740 -> 736
~ -[_EXExtensionPredicateBuilder predicateForRejectExceptOtherTypesRule:type:otherTypes:] : 468 -> 464
~ -[_EXExtensionPredicateBuilder makePredicate] : 472 -> 464
~ _EXExtensionIsSafeExpressionForObjectWithSubquerySubstitutions : 2064 -> 2060
~ -[NSDictionary(ExtensionKitAdditions) _EX_objectForKeys:ofClass:] : 312 -> 308
~ -[EXFrameworkScanner enumerateBundlesWithPathExtension:atURL:block:] : 732 -> 728
~ -[EXFrameworkScanner enumerateAppexptAtURL:block:] : 724 -> 720
~ -[EXFrameworkScanner enumerateFrameworksBundlesWithFrameworkURL:block:] : 432 -> 428
~ -[EXFrameworkScanner main] : 472 -> 468
~ -[_EXCopyingLoadOperator initWithCoder:] : 648 -> 644
~ -[_EXCopyingLoadOperator encodeWithCoder:] : 920 -> 912
~ +[_EXTCCUtil photoServiceAuthorizationStatusWithExtensionUUID:error:] : 672 -> 668
~ +[NSUUID(ExtensionKitAdditions) _EX_UUIDByXORingUUIDs:] : 328 -> 324
~ +[EXExtensionPointEnumerator enumeratePlatformExtensionPointsWithBlock:] : 756 -> 752
~ +[EXExtensionPointEnumerator enumerateExtensionPointsInDirectoryAtURL:block:] : 832 -> 828
~ -[EXExtensionPointEnumerator initWithSDKDictionary:urls:config:] : 1888 -> 1880
~ -[EXExtensionPointEnumerator translateXPCCacheDictionary:] : 664 -> 660
~ -[EXExtensionPointEnumerator nextObject] : 2568 -> 2560
~ +[EXOSExtensionEnumerator enumerateExtensionsInDirectoryAtURL:block:] : 1016 -> 1012
~ -[EXOSExtensionEnumerator initWithCacheURLs:paths:] : 872 -> 868
~ ___32-[_EXDefaults itemProviderTypes]_block_invoke : 440 -> 436
~ ___25-[_EXDefaults imageTypes]_block_invoke : 304 -> 300
~ -[EXPKService discoverSubsystems] : 776 -> 772
~ -[EXPKService mergeSubsystemList:from:] : 292 -> 288
~ _$sSo23LSRestrictionReasonMaskVs25ExpressibleByArrayLiteralSCsACP05arrayG0x0fG7ElementQzd_tcfCTW : 172 -> 176
~ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFs11AnyHashableV_19ExtensionFoundation17CapabilityManagerC0O6Driver_pTg5 : 696 -> 692
~ _$ss17_NativeDictionaryV4copyyyFSS_ypTg5 : 412 -> 388
~ _$ss17_NativeDictionaryV4copyyyF10Foundation4DataV_09ExtensionD08DatabaseV07_DarwinF6RecordVTg5Tm : 592 -> 588
~ _$ss17_NativeDictionaryV4copyyyF19ExtensionFoundation03AppD5PointV7MonitorC8IdentityV_AH18ObserverControllerC0J033_5D985BB42A36A6D664ED77CA96129115LLVTg5 : 468 -> 456
~ _$ss17_NativeDictionaryV4copyyyF19ExtensionFoundation10AuditTokenV_So12RBSAssertionCTg5 : 360 -> 352
~ _$ss17_NativeDictionaryV4copyyyFSS_SSTg5 : 376 -> 372
~ _$ss17_NativeDictionaryV4copyyyFs11AnyHashableV_19ExtensionFoundation17CapabilityManagerC0H6Driver_pTg5 : 392 -> 384
~ _$ss17_NativeDictionaryV7_insert2at3key5valueys10_HashTableV6BucketV_xnq_ntFs11AnyHashableV_19ExtensionFoundation17CapabilityManagerC0N6Driver_pTg5 : 132 -> 128
~ _$s10Foundation4DataVyACxcSTRzs5UInt8V7ElementRtzlufcySwXEfU2_SS8UTF8ViewV_Tg5 : 692 -> 688
~ _$s7Network15NWApplicationIDV19ExtensionFoundationE7setSelf4fromySS_tKFZTf4nd_n : 552 -> 556
~ ___swift_closure_destructor.27 : 148 -> 156
~ _$s19ExtensionFoundation16ListenerDelegateC8listener_10didReceive11withContextySo019BSServiceConnectionC0C_So0jK4Host_So0jK0CXcSo13BSXPCDecoding_ptFyyYacfU2_TA : 352 -> 356
~ _$s19ExtensionFoundation16ListenerDelegateC8listener_10didReceive11withContextySo019BSServiceConnectionC0C_So0jK4Host_So0jK0CXcSo13BSXPCDecoding_ptFyyYacfU1_TA : 328 -> 320
~ _$sSo30_EXAppExtensionPointEnumeratorC0B10FoundationE0bC0C8platforms6UInt32VvgTo : 36 -> 32
~ _$sSo30_EXAppExtensionPointEnumeratorC0B10FoundationE0bC0C8platforms6UInt32Vvg : 36 -> 32
~ _$s19ExtensionFoundation03AppA15PointEnumeratorV8IteratorV4nextAC0aD0VSgyF : 1328 -> 1332
~ _$sSl19ExtensionFoundationSS7ElementRtzrlE8contains33_1F29963F4EAD81515B217A48FDB01BC2LL8platformSbAA8PlatformO_tFSaySSG_Tg5 : 144 -> 160
~ _$ss17_NativeDictionaryV5merge_8isUnique16uniquingKeysWithyqd__n_Sbq_q__q_tqd_0_YKXEtqd_0_YKSTRd__s5ErrorRd_0_x_q_t7ElementRtd__r0_lFSS_yps15LazyMapSequenceVySDySSypGSS_yptGs5NeverOTg5146$s19ExtensionFoundation03AppA15PointEnumeratorV8IteratorV20normalizedAttributes3keySDySSypGSgSS10identifier_AA8PlatformO8platformt_tFypyp_yptXEfU_Tf1nncn_n : 756 -> 752
~ _$sSTsE21_copySequenceContents12initializing8IteratorQz_SitSry7ElementQzG_tFShy19ExtensionFoundation03AppG8IdentityVG_Tg5 : 352 -> 348
~ _$s19ExtensionFoundation03AppA15PointEnumeratorV8IteratorVyAeCcfCTf4xd_nTf4nngn_n : 808 -> 824
~ _$sSo19LSApplicationRecordC19ExtensionFoundationE24requiresAppSuiteSettingsSbvg : 1048 -> 1052
~ _$sSTsSQ7ElementRpzrlE8containsySbABFSaySSG_Tg5 : 116 -> 132
~ _$sSlsE3mapySayqd__Gqd__7ElementQzqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFShy19ExtensionFoundation03AppD5PointVG_SSs5NeverOTg504$s19d12Foundation03f2A5G51V7MonitorC8IdentityV16debugDescriptionSSvgSSACXEfU_Tf1cn_n : 560 -> 564
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZ19ExtensionFoundation8DatabaseV07_DarwinB6RecordV_Tt1g5 : 208 -> 224
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZSS_Tt1g5 : 136 -> 144
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZ19ExtensionFoundation03AppB8IdentityV_Tt1g5 : 476 -> 496
~ _$s19ExtensionFoundation03AppA5PointV7MonitorC5StateV16debugDescriptionSSvg : 384 -> 392
~ _$s19ExtensionFoundation03AppA5PointV16debugDescriptionSSvg : 276 -> 288
~ _$s19ExtensionFoundation03AppA5PointV7MonitorC18ObserverControllerC0F033_5D985BB42A36A6D664ED77CA96129115LLV06removeE0yyAEF : 476 -> 464
~ _$s19ExtensionFoundation03AppA5PointV7MonitorC18ObserverControllerC0F033_5D985BB42A36A6D664ED77CA96129115LLV8onUpdateyyAE5StateVYaFTY0_ : 816 -> 832
~ _$sSa6append10contentsOfyqd__n_t7ElementQyd__RszSTRd__lFSJ_SSTg5 : 432 -> 428
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF10Foundation4UUIDV_Tg5 : 472 -> 476
~ _$sSh4hash4intoys6HasherVz_tF19ExtensionFoundation03AppD5PointV_Tg5 : 364 -> 360
~ _$s19ExtensionFoundation03AppA5PointV7MonitorC8IdentityVwst : 68 -> 64
~ _$sSh9formUnionyyqd__n7ElementQyd__RszSTRd__lF19ExtensionFoundation03AppD8IdentityV_SayAFGTg5Tf4gn_n : 100 -> 112
~ _$s19ExtensionFoundation04_AppA5PointV10identifier8platformACSS_AA8PlatformOtKcfC : 516 -> 520
~ _$s19ExtensionFoundation15QueryControllerC7suspendyyF : 1128 -> 1144
~ _$s19ExtensionFoundation8_EXQueryC11ValuesQueryVwst : 100 -> 96
~ _$sSlsE3mapySayqd__Gqd__7ElementQzqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFShys11AnyHashableVG_19ExtensionFoundation24_EXServiceClientObserver_ps5NeverOTg504$s19f13Foundation16_hi66C06ActiveD5Query33_591406279EDD09BF7033B88E7B83DCFDLLC07ServiceD11j41SetC10allObjectsSayAA01_cdN0_pGvgAaJ_ps11dE6VXEfU_Tf1cn_n : 604 -> 584
~ _$s19ExtensionFoundation16_EXServiceClientC15fetchExtensions4with10completionySayAA8_EXQueryCG_yAA01_I6ResultCctF : 1492 -> 1508
~ _$s19ExtensionFoundation16_EXServiceClientC06ActiveD5Query33_591406279EDD09BF7033B88E7B83DCFDLLC5query_15resultDidUpdate5replyyAA8_EXQueryC_AA01_r6ResultP0CyyctF13$sIeyB_Ieg_TRIeyB_Tf1nncn_n : 772 -> 776
~ _$s19ExtensionFoundation16_EXServiceClientC3add13queryObserveryAA01_cdG0_p_tFyytz_tYbXEfU_ : 1348 -> 1344
~ _$s19ExtensionFoundation16_EXServiceClientC8ObserverC8activate10connectionySo15NSXPCConnectionC_tKF : 2496 -> 2492
~ _$s19ExtensionFoundation16_EXServiceClientC8ObserverC8activate10connectionySo15NSXPCConnectionC_tKFyAA7ServiceC0E6UpdateCSg_s5Error_pSgtcfU1_ : 808 -> 812
~ _$s19ExtensionFoundation16_EXServiceClientC8ObserverC8observer_5replyyAA7ServiceC0E6UpdateC_yyctF13$sIeyB_Ieg_TRIeyB_Tf1ncn_nTf4nng_n : 840 -> 860
~ _$sSlsE3mapySayqd__Gqd__7ElementQzqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFShySo28LSApplicationExtensionRecordCG_0E10Foundation8DatabaseV01_eF0Vs5NeverOTg504$s19e11Foundation8h15V18_Applicationf60V011applicationA7RecordsSayAC01_aE0VGvgAHSo013LSApplicationaS6CXEfU_Tf1cn_n : 768 -> 760
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_SbTt0g5Tf4g_n : 244 -> 268
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfC10Foundation4UUIDV_So18_EXNSExtensionShimC09ExtensionC0E14ImplementationC7RequestVTt0g5Tf4g_n : 464 -> 460
~ _$ss15_arrayForceCastySayq_GSayxGr0_lF19ExtensionFoundation8DatabaseV01_D11PointRecordV_AF0dgH0_pTg5 : 244 -> 260
~ _$ss15_arrayForceCastySayq_GSayxGr0_lFyp_So22LSExtensionPointRecordCTg5Tm : 240 -> 256
~ _$ss15_arrayForceCastySayq_GSayxGr0_lFSo15NSExtensionItemC_ypTg5 : 504 -> 512
~ _$ss15_arrayForceCastySayq_GSayxGr0_lFSo6NSUUIDC_10Foundation4UUIDVTg5 : 844 -> 852
~ _$s19ExtensionFoundation03AppA5PointV10DefinitionV10buildBlockyA2C4NameV_xxQptRvzAC9AttributeRzlFZ : 2016 -> 2044
~ _$s19ExtensionFoundation03AppA5PointV10DefinitionV10buildBlockyA2C10IdentifierV_AC5ScopeVxxQptRvzAC9AttributeRzlFZ : 1388 -> 1384
~ _$s19ExtensionFoundation03AppA5PointV09extensionD7RecordsACSaySo011LSExtensionD6RecordCG_tKcfC : 460 -> 480
~ _$s19ExtensionFoundation03AppA7ProcessV19_CapabilityEndpointV17makeXPCConnectionSo15NSXPCConnectionCyKFySo36BSServiceConnectionInitiatingOptions_pXEfU_ySo13BSXPCEncoding_pXEfU_TA : 124 -> 128
~ ___swift_closure_destructor.36Tm : 140 -> 148
~ _$s19ExtensionFoundation08_ServiceA7ProcessV13configurationA2C13ConfigurationV_tYaKcfcAC5Inner33_B444E02B49700CE9F619AE54934FF0D0LLVyYaKcfU_TA : 240 -> 244
~ _$s19ExtensionFoundation7ServiceC21ObserverConfigurationC6encode4withySo7NSCoderC_tF : 540 -> 548
~ _$s19ExtensionFoundation7ServiceC14ObserverUpdateC10identities13disabledCount09unelectedH0AESayAA03AppA8IdentityVG_S2itcfc : 516 -> 528
~ _$s19ExtensionFoundation7ServiceC21ObserverConfigurationC5coderAESgSo7NSCoderC_tcfcTf4gn_n : 1656 -> 1636
~ _$sShyShyxGqd__nc7ElementQyd__RszSTRd__lufC10Foundation4UUIDV_SayAFGTt0g5Tf4g_n : 408 -> 428
~ _$s27LightweightCodeRequirements07ProcessB11RequirementV19ExtensionFoundationE03preD4LWCR_10substituteSDySSyXlGAG_SS_yXltSgSS_yXltXEtFZ17processDictionaryL_yA2GF : 3456 -> 3464
~ _$s27LightweightCodeRequirements07ProcessB11RequirementV19ExtensionFoundationE03preD4LWCR_10substituteSDySSyXlGAG_SS_yXltSgSS_yXltXEtFZ12processArrayL_ySayyXlGAJF : 576 -> 588
~ _$ss17_NativeDictionaryV5merge20trappingOnDuplicatesyqd__n_tSTRd__x_q_t7ElementRtd__lFSS_yXlSaySS_yXltGTg5Tf4gn_n : 488 -> 500
~ _$s19ExtensionFoundation03AppA5PointV10CapabilityPAAE8activate3forAC01_E18ActivationResponseVqd___tYaKAA0cA0Rd__lFSbSo15NSXPCConnectionC_AA0E15SessionIdentityVtYaYbcfU_TA : 256 -> 260
~ _$sSD8_VariantV11removeValue6forKeyq_Sgx_tFs11AnyHashableV_19ExtensionFoundation17CapabilityManagerC0J6Driver_pTg5 : 180 -> 176
~ _$ss10_NativeSetV4copyyyF19ExtensionFoundation03AppD5PointV_Tg5 : 340 -> 336
~ _$ss10_NativeSetV4copyyyF19ExtensionFoundation03AppD8IdentityV_Tg5Tm : 332 -> 328
~ _$sSl19ExtensionFoundationAA04_AppA5QueryV7ElementRtzrlE11toEXQueries33_CDD6639443F09112848BD34A3597427CLLSayAA8_EXQueryCGyFSayACG_Tg5 : 1388 -> 1408
~ _$s19ExtensionFoundation16_QueryControllerC21makeResultAsyncStream4withScSySayxGGSayAA8_EXQueryCG_tAA04_AppA16IdentityProtocolRzlFZyScS12ContinuationVyAF_GXEfU_AA01_kaL0V_Tg5 : 776 -> 780
~ _$s19ExtensionFoundation16_QueryControllerC21makeResultAsyncStream4withScSySayxGGSayAA8_EXQueryCG_tAA04_AppA16IdentityProtocolRzlFZyScS12ContinuationVyAF_GXEfU_ySaySo012_EXExtensionL0CGcfU_AA01_kaL0V_Tg5 : 1084 -> 1100
~ ___swift_closure_destructor.37 : 140 -> 148
~ _$ss21_arrayConditionalCastySayq_GSgSayxGr0_lFyp_So12_EXSceneRoleaTg5 : 264 -> 268
~ _$ss10SetAlgebraPs7ElementQz012ArrayLiteralC0RtzrlE05arrayE0xAFd_tcfC19ExtensionFoundation03AppG8IdentityV16_MatchingOptionsV_Tg5 : 196 -> 188
~ _$s19ExtensionFoundation03AppA8IdentityV8matching03appA8PointIDs7optionsAC10IdentitiesVSaySSG_AC16_MatchingOptionsVtKFZ : 1416 -> 1428
~ _$s19ExtensionFoundation03AppA8IdentityV10IdentitiesV15extensionPoints7options_AESayAA01_cA5PointVGSg_AC16_MatchingOptionsVSbACctc33_561A8376487B9064A369D61EFCA7CBE2LlfcyScS12ContinuationVySayACG_GXEfU_ : 2220 -> 2244
~ _$s19ExtensionFoundation03AppA8IdentityV10IdentitiesV15extensionPoints7options_AESayAA01_cA5PointVGSg_AC16_MatchingOptionsVSbACctc33_561A8376487B9064A369D61EFCA7CBE2LlfcyScS12ContinuationVySayACG_GXEfU_ySaySo012_EXExtensionD0CGcfU1_ : 1048 -> 1060
~ ___swift_closure_destructorTm : 124 -> 132
~ _$s19ExtensionFoundation22_CapabilityHostSessionV13configurationA2C13ConfigurationV_tYaKcfCTY2_ : 3104 -> 3100
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF19ExtensionFoundation23CapabilityConfigurationV_Tg5Tm : 480 -> 484
~ _$s19ExtensionFoundation03AppA7ProcessV13ConfigurationV10_TaskStateO2eeoiySbAG_AGtFZTf4nnd_n : 512 -> 508
~ _$s19ExtensionFoundation03AppA7ProcessV13ConfigurationV25AssertionAttributesPresetV2eeoiySbAG_AGtFZTf4nnd_n : 512 -> 508
~ _$s19ExtensionFoundation03AppA5PointV12CapabilitiesV7BuilderV10buildBlockyAExxQpRvzAC10CapabilityRzlFZ : 752 -> 748
~ _$s19ExtensionFoundation17CapabilityManagerC0C4Pack33_9664FE1351C0001FC65643A20F092796LLVyAFy_xxQp_QPGxxQpcfC : 664 -> 620
~ _$s19ExtensionFoundation17CapabilityManagerC0C4Pack33_9664FE1351C0001FC65643A20F092796LLV8activate4with3for7manageryAA01_C10Activating_p_qd__ACtKAA03AppA0Rd__lF : 2832 -> 2824
~ _$s19ExtensionFoundation17CapabilityManagerC0C4Pack33_9664FE1351C0001FC65643A20F092796LLV8activate4with3for7manageryAA01_C10Activating_p_qd__ACtKAA03AppA0Rd__lFyyYacfU_TA : 400 -> 404
~ _$s19ExtensionFoundation17CapabilityManagerC6DriverC6resume4with7manageryAA01_C10Activating_p_ACtFTf4ndn_n : 1160 -> 1148
~ _$s19ExtensionFoundation17CapabilityManagerC6DriverC6resume4with7manageryAA01_C10Activating_p_ACtFyyYaKcfU_TA : 260 -> 264
~ _$sSlsE3mapySayqd__Gqd__7ElementQzqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFShys11AnyHashableVG_yXlXps5NeverOTg5058$s19ExtensionFoundation8DefaultsV10plistTypesSayyXlXpGvgZyn5Xps11dE6VXEfU_Tf1cn_n : 616 -> 592
~ _$ss12_setDownCastyShyq_GShyxGSHRzSHR_r0_lFs11AnyHashableV_SSTg5 : 360 -> 356
~ _$sSr15_stableSortImpl2byySbx_xtKXE_tKFySryxGz_SiztKXEfU_SS_Tg5 : 1332 -> 1312
~ _$sSr13_mergeTopRuns_6buffer2bySbSaySnySiGGz_SpyxGSbx_xtKXEtKFSS_Tg5 : 652 -> 672
~ _$s19ExtensionFoundation09_InnerAppA8IdentityPAAE12capabilitiesSaySSGvgAA0daE0V05ValueE0V_Tg5 : 992 -> 1000
~ _$s19ExtensionFoundation09_InnerAppA8IdentityPAAE28alternateSandboxProfileNamesSaySSGvgAA0daE0V05ValueE0V_Tg5 : 628 -> 644
~ _$s19ExtensionFoundation09_InnerAppA8IdentityPAAE28alternateSandboxProfileNamesSaySSGvgAA0daE0V06RecordE0V_Tg5 : 888 -> 896
~ _$s19ExtensionFoundation03AppA8IdentityV06RecordD0V16supportedPersonaSaySo10_EXPersonaCGSgvg : 304 -> 316
```
