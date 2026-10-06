## AssistantServices

> `/System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bd8f8` | `0x1bbff8` | **`-0x1900`** |
| `__TEXT.__oslogstring` | `0x12e85` | `0x12bed` | **`-0x298`** |
| `__AUTH_CONST.__objc_const` | `0x39808` | `0x39640` | **`-0x1c8`** |
| `__AUTH_CONST.__cfstring` | `0x29980` | `0x29b20` | **`+0x1a0`** |
| `__TEXT.__gcc_except_tab` | `0x24f8` | `0x2358` | **`-0x1a0`** |
| `__TEXT.__cstring` | `0x415a9` | `0x41423` | **`-0x186`** |
| `__TEXT.__objc_methlist` | `0x20d7c` | `0x20c84` | **`-0xf8`** |
| `__DATA_CONST.__objc_selrefs` | `0xd048` | `0xcf58` | **`-0xf0`** |
| `__DATA_CONST.__const` | `0x8d58` | `0x8ca8` | **`-0xb0`** |
| `__AUTH_CONST.__objc_intobj` | `0x2880` | `0x27f0` | **`-0x90`** |
| `__DATA.__data` | `0x4ad0` | `0x4a70` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x8c28` | `0x8bd8` | **`-0x50`** |
| `__AUTH_CONST.__const` | `0x3f20` | `0x3f40` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1818` | `0x17f8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x87e0` | `0x8800` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x2900` | `0x28e4` | **`-0x1c`** |
| `__TEXT.__const` | `0x480` | `0x490` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xfb8` | `0xfb0` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x620` | `0x618` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xfc0` | `0xfb8` | **`-0x8`** |

### Other Changes

```diff

-3600.62.21.1.5
+3600.68.16.1.1

+  - /System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices

-  Functions: 12859
-  Symbols:   23486
-  CStrings:  9255
+  Functions: 12845
+  Symbols:   23459
+  CStrings:  9241
Symbols:
+ +[AFDictationSecureTouchAuthenticator requestAuthenticationMessageForClientVersionedPID:completionBlock:]
+ -[AFConfirmationOutcomeDescriptor input]
+ -[AFConfirmationOutcomeDescriptor setInput:]
+ -[AFLocalization _buildVoiceMapsFromSource:]
+ -[AFNetworkAvailability _publish]
+ -[AFPreferences restrictedBundleIdsForAction]
+ -[AFPreferences restrictedBundleIdsForInfo]
+ -[AFPreferences setRestrictedBundleIdsForAction:]
+ -[AFPreferences setRestrictedBundleIdsForInfo:]
+ -[AFPreferences(Accessibility) appleIntelligenceFallbackExplicitlySet]
+ -[AFPreferences(Accessibility) linwoodEverAvailable]
+ -[AFPreferences(Accessibility) setLinwoodEverAvailable:]
+ -[AFRequestInfo resumeSessionId]
+ -[AFRequestInfo setResumeSessionId:]
+ -[AFSettingsConnection deleteCloudSyncDataWithCompletion:]
+ -[AFSettingsConnection deleteLocalSyncDataWithCompletion:]
+ -[AFSettingsConnection disableCloudSyncWithCompletion:]
+ -[AFSettingsConnection enableCloudSyncWithCompletion:]
+ -[AFSiriAudioRoute isBluetoothVehicle]
+ -[AFSiriAvailability currentOrchestrationMode]
+ -[AFSiriAvailability desiredOrchestrationModeIfEnabled]
+ -[AFSiriAvailability initWithIsAvailable:siriLocale:desiredOrchestrationMode:desiredOrchestrationModeIfEnabled:currentOrchestrationMode:unavailabilityReasons:allCapabilities:linwoodEverAvailable:]
+ -[AFSiriAvailability initWithIsAvailable:siriLocale:desiredOrchestrationMode:desiredOrchestrationModeIfEnabled:currentOrchestrationMode:unavailabilityReasons:allCapabilities:linwoodEverAvailable:bootUUID:]
+ -[AFSiriAvailability initWithIsAvailable:siriLocale:desiredOrchestrationMode:desiredOrchestrationModeIfEnabled:unavailabilityReasons:allCapabilities:linwoodEverAvailable:]
+ -[AFSiriAvailability initWithIsAvailable:siriLocale:desiredOrchestrationMode:desiredOrchestrationModeIfEnabled:unavailabilityReasons:allCapabilities:linwoodEverAvailable:bootUUID:]
+ -[AFSiriAvailability isLinwoodCapableAndEverAvailable]
+ -[AFSiriAvailability linwoodEverAvailable]
+ GCC_except_table10070
+ GCC_except_table10075
+ GCC_except_table10139
+ GCC_except_table10254
+ GCC_except_table10646
+ GCC_except_table10692
+ GCC_except_table10733
+ GCC_except_table10821
+ GCC_except_table10861
+ GCC_except_table10892
+ GCC_except_table10897
+ GCC_except_table10898
+ GCC_except_table10902
+ GCC_except_table1100
+ GCC_except_table11091
+ GCC_except_table11262
+ GCC_except_table11291
+ GCC_except_table11392
+ GCC_except_table11396
+ GCC_except_table11425
+ GCC_except_table1166
+ GCC_except_table1172
+ GCC_except_table11813
+ GCC_except_table11815
+ GCC_except_table11818
+ GCC_except_table11827
+ GCC_except_table11887
+ GCC_except_table11908
+ GCC_except_table11933
+ GCC_except_table11939
+ GCC_except_table12080
+ GCC_except_table12084
+ GCC_except_table12086
+ GCC_except_table12089
+ GCC_except_table12095
+ GCC_except_table12099
+ GCC_except_table12105
+ GCC_except_table12309
+ GCC_except_table12657
+ GCC_except_table12791
+ GCC_except_table12794
+ GCC_except_table12796
+ GCC_except_table1298
+ GCC_except_table1300
+ GCC_except_table1514
+ GCC_except_table1551
+ GCC_except_table1557
+ GCC_except_table1561
+ GCC_except_table1590
+ GCC_except_table1956
+ GCC_except_table2091
+ GCC_except_table2298
+ GCC_except_table2311
+ GCC_except_table2315
+ GCC_except_table2327
+ GCC_except_table2331
+ GCC_except_table2436
+ GCC_except_table2438
+ GCC_except_table2510
+ GCC_except_table2554
+ GCC_except_table2916
+ GCC_except_table2923
+ GCC_except_table2927
+ GCC_except_table2929
+ GCC_except_table2974
+ GCC_except_table2976
+ GCC_except_table2982
+ GCC_except_table2988
+ GCC_except_table2992
+ GCC_except_table2996
+ GCC_except_table2999
+ GCC_except_table3001
+ GCC_except_table3006
+ GCC_except_table3008
+ GCC_except_table3013
+ GCC_except_table3025
+ GCC_except_table3028
+ GCC_except_table3042
+ GCC_except_table3044
+ GCC_except_table3046
+ GCC_except_table3048
+ GCC_except_table3050
+ GCC_except_table3052
+ GCC_except_table3054
+ GCC_except_table3097
+ GCC_except_table3123
+ GCC_except_table3180
+ GCC_except_table3213
+ GCC_except_table3586
+ GCC_except_table3843
+ GCC_except_table4040
+ GCC_except_table4048
+ GCC_except_table4106
+ GCC_except_table4482
+ GCC_except_table4486
+ GCC_except_table4531
+ GCC_except_table4537
+ GCC_except_table4562
+ GCC_except_table4568
+ GCC_except_table4776
+ GCC_except_table4885
+ GCC_except_table4896
+ GCC_except_table4929
+ GCC_except_table4932
+ GCC_except_table5009
+ GCC_except_table5013
+ GCC_except_table5023
+ GCC_except_table5034
+ GCC_except_table5047
+ GCC_except_table5132
+ GCC_except_table5134
+ GCC_except_table5158
+ GCC_except_table5273
+ GCC_except_table5336
+ GCC_except_table5339
+ GCC_except_table5343
+ GCC_except_table5360
+ GCC_except_table5374
+ GCC_except_table5448
+ GCC_except_table5506
+ GCC_except_table5532
+ GCC_except_table5803
+ GCC_except_table5944
+ GCC_except_table5957
+ GCC_except_table6000
+ GCC_except_table6094
+ GCC_except_table6289
+ GCC_except_table6412
+ GCC_except_table6426
+ GCC_except_table6438
+ GCC_except_table6445
+ GCC_except_table6446
+ GCC_except_table6449
+ GCC_except_table6455
+ GCC_except_table6543
+ GCC_except_table6545
+ GCC_except_table6547
+ GCC_except_table6565
+ GCC_except_table6571
+ GCC_except_table6614
+ GCC_except_table6626
+ GCC_except_table6799
+ GCC_except_table6885
+ GCC_except_table6939
+ GCC_except_table7202
+ GCC_except_table7205
+ GCC_except_table7206
+ GCC_except_table7403
+ GCC_except_table7462
+ GCC_except_table7730
+ GCC_except_table7733
+ GCC_except_table7745
+ GCC_except_table7746
+ GCC_except_table7759
+ GCC_except_table7760
+ GCC_except_table7761
+ GCC_except_table7767
+ GCC_except_table7805
+ GCC_except_table7811
+ GCC_except_table7817
+ GCC_except_table7885
+ GCC_except_table7887
+ GCC_except_table7922
+ GCC_except_table7925
+ GCC_except_table8064
+ GCC_except_table8160
+ GCC_except_table8162
+ GCC_except_table8164
+ GCC_except_table8166
+ GCC_except_table8180
+ GCC_except_table8186
+ GCC_except_table824
+ GCC_except_table827
+ GCC_except_table8309
+ GCC_except_table8316
+ GCC_except_table834
+ GCC_except_table8685
+ GCC_except_table8700
+ GCC_except_table8707
+ GCC_except_table8723
+ GCC_except_table8814
+ GCC_except_table8823
+ GCC_except_table8846
+ GCC_except_table8876
+ GCC_except_table8931
+ GCC_except_table8955
+ GCC_except_table9332
+ GCC_except_table9346
+ GCC_except_table9349
+ GCC_except_table9352
+ GCC_except_table9355
+ GCC_except_table9531
+ GCC_except_table9534
+ GCC_except_table9595
+ GCC_except_table9603
+ GCC_except_table9608
+ GCC_except_table9621
+ GCC_except_table965
+ GCC_except_table9781
+ GCC_except_table9881
+ _AFAssistantServiceEmitLaunchMetadataReportedForRequestId
+ _AFAssistantServiceLoadedTimestampInNs
+ _AFAssistantServiceMarkLoaded
+ _AFAssistantServiceRecordSpawnTime
+ _AFAssistantServiceSpawnTimestampInNs
+ _AFBobbleV2Supported.forcedResult
+ _AFBobbleV2Supported.hasLogged
+ _AFBobbleV2Supported.lastResult
+ _AFIsLinwoodEnabledAndWasEverAvailable
+ _AFIsLinwoodUserSettingExplicitlySet
+ _AFSiriAvailabilityCurrentOrchestrationModeKey
+ _AFSiriAvailabilityDesiredOrchestrationModeIfEnabledKey
+ _AFSiriAvailabilityLinwoodEverAvailableKey
+ _AFSiriUnavailabilityReasonsFromAFSiriLinwoodCapabilities
+ _OBJC_CLASS_$_AFDictationSecureTouchAuthenticator
+ _OBJC_CLASS_$_BKSHIDEventAuthenticationMessage
+ _OBJC_CLASS_$_ORCHSchemaORCHAssistantServiceLaunchMetadataReported
+ _OBJC_IVAR_$_AFConfirmationOutcomeDescriptor._input
+ _OBJC_IVAR_$_AFDictationConnection._lastBroadcastNetworkAvailability
+ _OBJC_IVAR_$_AFNetworkAvailability._publishedState
+ _OBJC_IVAR_$_AFRequestInfo._resumeSessionId
+ _OBJC_IVAR_$_AFSiriAvailability._currentOrchestrationMode
+ _OBJC_IVAR_$_AFSiriAvailability._desiredOrchestrationModeIfEnabled
+ _OBJC_IVAR_$_AFSiriAvailability._linwoodEverAvailable
+ _OBJC_METACLASS_$_AFDictationSecureTouchAuthenticator
+ __AFComputeAvailability
+ __AFSiriAppSettingsRestrictedBundleIdsForAction
+ __AFSiriAppSettingsRestrictedBundleIdsForInfo
+ __AFSiriAppSettingsSetRestrictedBundleIdsForAction
+ __AFSiriAppSettingsSetRestrictedBundleIdsForInfo
+ __AFSiriAppSettingsSetValueForKey
+ __AFSiriAppSettingsValueForKey
+ __OBJC_$_CATEGORY_AceObject_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CATEGORY_NSArray_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CATEGORY_NSDate_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CATEGORY_NSDictionary_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CATEGORY_NSNull_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CATEGORY_NSString_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CATEGORY_NSURL_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CLASS_METHODS_AFDictationSecureTouchAuthenticator
+ __OBJC_$_CLASS_METHODS_AFVoiceInfo(SiriTTSServiceAdditions|AFLocalizationAdditions|VSAdditions)
+ __OBJC_$_CLASS_METHODS_NSString(AFSecurityDigestibleChunksProvider|AFPreferences|AssistantServices|AFSiriRequest|ShortDescription)
+ __OBJC_$_CLASS_METHODS_NSURL(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport|AMOSExtensions|STSiriMessage)
+ __OBJC_$_INSTANCE_METHODS_AFClockTimer(AFClockTimerMutability|ClockItem)
+ __OBJC_$_INSTANCE_METHODS_AFVoiceInfo(SiriTTSServiceAdditions|AFLocalizationAdditions|VSAdditions)
+ __OBJC_$_INSTANCE_METHODS_AceObject(AFSecurityDigestibleChunksProvider|AssistantAdditions|AnalyticsContextVending)
+ __OBJC_$_INSTANCE_METHODS_NSArray(AFSecurityDigestibleChunksProvider|AFCollectionUtilities)
+ __OBJC_$_INSTANCE_METHODS_NSDate(AFSecurityDigestibleChunksProvider|AssistantAdditions)
+ __OBJC_$_INSTANCE_METHODS_NSDictionary(AFSecurityDigestibleChunksProvider|AFCollectionUtilities)
+ __OBJC_$_INSTANCE_METHODS_NSNull(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport)
+ __OBJC_$_INSTANCE_METHODS_NSString(AFSecurityDigestibleChunksProvider|AFPreferences|AssistantServices|AFSiriRequest|ShortDescription)
+ __OBJC_$_INSTANCE_METHODS_NSURL(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport|AMOSExtensions|STSiriMessage)
+ __OBJC_$_PROP_LIST_NSArray_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_PROP_LIST_NSDate_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_PROP_LIST_NSDictionary_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_PROP_LIST_NSString_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_AFDictationSecureTouchService
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_AFIntelligenceFlowActionDescriptor
+ __OBJC_CATEGORY_PROTOCOLS_$_NSArray_$_AFSecurityDigestibleChunksProvider
+ __OBJC_CATEGORY_PROTOCOLS_$_NSDate_$_AFSecurityDigestibleChunksProvider
+ __OBJC_CATEGORY_PROTOCOLS_$_NSDictionary_$_AFSecurityDigestibleChunksProvider
+ __OBJC_CATEGORY_PROTOCOLS_$_NSString_$_AFSecurityDigestibleChunksProvider
+ __OBJC_CLASS_PROTOCOLS_$_AFClockTimer(AFClockTimerMutability|ClockItem)
+ __OBJC_CLASS_PROTOCOLS_$_AceObject(AFSecurityDigestibleChunksProvider|AssistantAdditions|AnalyticsContextVending)
+ __OBJC_CLASS_PROTOCOLS_$_NSNull(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport)
+ __OBJC_CLASS_PROTOCOLS_$_NSURL(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport|AMOSExtensions|STSiriMessage)
+ __OBJC_CLASS_RO_$_AFDictationSecureTouchAuthenticator
+ __OBJC_METACLASS_RO_$_AFDictationSecureTouchAuthenticator
+ ___105+[AFDictationSecureTouchAuthenticator requestAuthenticationMessageForClientVersionedPID:completionBlock:]_block_invoke
+ ___105+[AFDictationSecureTouchAuthenticator requestAuthenticationMessageForClientVersionedPID:completionBlock:]_block_invoke_2
+ ___44-[AFLocalization _buildVoiceMapsFromSource:]_block_invoke
+ ___54-[AFSettingsConnection enableCloudSyncWithCompletion:]_block_invoke
+ ___55-[AFSettingsConnection disableCloudSyncWithCompletion:]_block_invoke
+ ___58-[AFSettingsConnection deleteCloudSyncDataWithCompletion:]_block_invoke
+ ___58-[AFSettingsConnection deleteLocalSyncDataWithCompletion:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e54_v24?0"BKSHIDEventAuthenticationMessage"8"NSError"16ls40l8s32l8
+ ___getAVSystemController_RouteDescriptionKey_BTDetails_EndpointTypeSymbolLoc_block_invoke
+ ___getAVSystemController_RouteDescriptionKey_BTDetails_EndpointType_VehicleSymbolLoc_block_invoke
+ _getAVSystemController_RouteDescriptionKey_BTDetails_EndpointTypeSymbolLoc.ptr
+ _getAVSystemController_RouteDescriptionKey_BTDetails_EndpointType_VehicleSymbolLoc.ptr
+ _kSiriAppSettingsDomain
+ _sAssistantServiceFirstRequestConsumed
+ _sAssistantServiceLoadedTimestampInNs
+ _sAssistantServiceSpawnTimestampInNs
- +[AFFeatureFlags(SWEFeatureFlags) isCrossDeviceArbitrationFeedbackEnabled]
- -[AFArbitrationParticipationContext .cxx_destruct]
- -[AFArbitrationParticipationContext advertisements]
- -[AFArbitrationParticipationContext decisionIsWon]
- -[AFArbitrationParticipationContext deviceClass]
- -[AFArbitrationParticipationContext lastActivationTime]
- -[AFArbitrationParticipationContext ownAdvertisement]
- -[AFArbitrationParticipationContext requestStartDate]
- -[AFArbitrationParticipationContext scoreBoosters]
- -[AFArbitrationParticipationContext setAdvertisements:]
- -[AFArbitrationParticipationContext setDecisionIsWon:]
- -[AFArbitrationParticipationContext setDeviceClass:]
- -[AFArbitrationParticipationContext setLastActivationTime:]
- -[AFArbitrationParticipationContext setOwnAdvertisement:]
- -[AFArbitrationParticipationContext setRequestStartDate:]
- -[AFArbitrationParticipationContext setScoreBoosters:]
- -[AFArbitrationParticipationContext setTriggerType:]
- -[AFArbitrationParticipationContext setVoiceTriggerDate:]
- -[AFArbitrationParticipationContext triggerType]
- -[AFArbitrationParticipationContext voiceTriggerDate]
- -[AFArbitrationParticipationController .cxx_destruct]
- -[AFArbitrationParticipationController _publishFeedbackArbitrationRecordForNearMiss]
- -[AFArbitrationParticipationController _publishFeedbackArbitrationRecord]
- -[AFArbitrationParticipationController _resetSettingsConnection]
- -[AFArbitrationParticipationController _updateUserFeedbackParticipationAllAdvertisements:session:ownRecord:won:triggerType:lastActivationTime:requestStartDate:voiceTriggerDate:scoreBoosters:deviceClass:]
- -[AFArbitrationParticipationController arbitrationDidUpdateWithContext:session:completion:]
- -[AFArbitrationParticipationController arbitrationEndedAdvertising:]
- -[AFArbitrationParticipationController arbitrationEndedTask:]
- -[AFArbitrationParticipationController arbitrationSessionWillStart:]
- -[AFArbitrationParticipationController dealloc]
- -[AFArbitrationParticipationController init]
- -[AFArbitrationParticipationController participationsForUserFeedback]
- -[AFArbitrationParticipationController participationsPublished]
- -[AFArbitrationParticipationController queue]
- -[AFArbitrationParticipationController requestWillPresentUsefulUserResult:]
- -[AFArbitrationParticipationController setParticipationsForUserFeedback:]
- -[AFArbitrationParticipationController setParticipationsPublished:]
- -[AFArbitrationParticipationController setQueue:]
- -[AFArbitrationParticipationController setSettingsConnection:]
- -[AFArbitrationParticipationController settingsConnection]
- -[AFMyriadCoordinator _triggerTypeForArbitrationParticipationFrom:]
- -[AFMyriadCoordinator _updateArbitrationParticipationContextWithCompletion:]
- -[AFPreferences _setLinwoodEnabledMeDevice:]
- -[AFPreferences linwoodEnabledMeDevice]
- -[AFSettingsConnection isLinwoodEnabledOnAnyHomeDevice:]
- -[AFSettingsConnection publishFeedbackArbitrationParticipation:]
- -[AFSiriAvailability initWithIsAvailable:siriLocale:desiredOrchestrationMode:unavailabilityReasons:allCapabilities:bootUUID:]
- GCC_except_table10055
- GCC_except_table10060
- GCC_except_table10124
- GCC_except_table10239
- GCC_except_table1053
- GCC_except_table10631
- GCC_except_table10681
- GCC_except_table10725
- GCC_except_table10813
- GCC_except_table10853
- GCC_except_table10884
- GCC_except_table10889
- GCC_except_table10890
- GCC_except_table10894
- GCC_except_table1097
- GCC_except_table11083
- GCC_except_table11254
- GCC_except_table11283
- GCC_except_table11380
- GCC_except_table11384
- GCC_except_table11421
- GCC_except_table11447
- GCC_except_table11835
- GCC_except_table11837
- GCC_except_table11840
- GCC_except_table11849
- GCC_except_table11902
- GCC_except_table11923
- GCC_except_table11948
- GCC_except_table11954
- GCC_except_table12094
- GCC_except_table12098
- GCC_except_table12100
- GCC_except_table12103
- GCC_except_table12109
- GCC_except_table12113
- GCC_except_table12119
- GCC_except_table12323
- GCC_except_table12671
- GCC_except_table12805
- GCC_except_table12808
- GCC_except_table12810
- GCC_except_table1455
- GCC_except_table1462
- GCC_except_table1466
- GCC_except_table1468
- GCC_except_table1513
- GCC_except_table1515
- GCC_except_table1521
- GCC_except_table1527
- GCC_except_table1531
- GCC_except_table1535
- GCC_except_table1538
- GCC_except_table1540
- GCC_except_table1545
- GCC_except_table1547
- GCC_except_table1552
- GCC_except_table1564
- GCC_except_table1567
- GCC_except_table1583
- GCC_except_table1585
- GCC_except_table1589
- GCC_except_table1591
- GCC_except_table1593
- GCC_except_table1636
- GCC_except_table1662
- GCC_except_table1719
- GCC_except_table1750
- GCC_except_table2116
- GCC_except_table2371
- GCC_except_table2568
- GCC_except_table2576
- GCC_except_table2634
- GCC_except_table3010
- GCC_except_table3014
- GCC_except_table3059
- GCC_except_table3065
- GCC_except_table3090
- GCC_except_table3096
- GCC_except_table3305
- GCC_except_table3414
- GCC_except_table3425
- GCC_except_table3458
- GCC_except_table3461
- GCC_except_table3542
- GCC_except_table3552
- GCC_except_table3563
- GCC_except_table3576
- GCC_except_table3660
- GCC_except_table3663
- GCC_except_table3686
- GCC_except_table3801
- GCC_except_table3864
- GCC_except_table3867
- GCC_except_table3871
- GCC_except_table3888
- GCC_except_table3902
- GCC_except_table3976
- GCC_except_table4034
- GCC_except_table4060
- GCC_except_table4331
- GCC_except_table4471
- GCC_except_table4484
- GCC_except_table4522
- GCC_except_table4616
- GCC_except_table4870
- GCC_except_table4873
- GCC_except_table4880
- GCC_except_table5011
- GCC_except_table5146
- GCC_except_table5212
- GCC_except_table5218
- GCC_except_table5344
- GCC_except_table5346
- GCC_except_table5560
- GCC_except_table5597
- GCC_except_table5603
- GCC_except_table5607
- GCC_except_table5627
- GCC_except_table5633
- GCC_except_table5636
- GCC_except_table6002
- GCC_except_table6137
- GCC_except_table6268
- GCC_except_table6391
- GCC_except_table6404
- GCC_except_table6405
- GCC_except_table6417
- GCC_except_table6424
- GCC_except_table6428
- GCC_except_table6434
- GCC_except_table6522
- GCC_except_table6524
- GCC_except_table6526
- GCC_except_table6544
- GCC_except_table6550
- GCC_except_table6593
- GCC_except_table6605
- GCC_except_table6775
- GCC_except_table6861
- GCC_except_table6915
- GCC_except_table7178
- GCC_except_table7181
- GCC_except_table7182
- GCC_except_table7379
- GCC_except_table7438
- GCC_except_table7725
- GCC_except_table7728
- GCC_except_table7740
- GCC_except_table7741
- GCC_except_table7754
- GCC_except_table7755
- GCC_except_table7756
- GCC_except_table7762
- GCC_except_table7800
- GCC_except_table7806
- GCC_except_table7812
- GCC_except_table7880
- GCC_except_table7882
- GCC_except_table7917
- GCC_except_table7920
- GCC_except_table8059
- GCC_except_table8155
- GCC_except_table8157
- GCC_except_table8159
- GCC_except_table8161
- GCC_except_table8175
- GCC_except_table8181
- GCC_except_table8304
- GCC_except_table8311
- GCC_except_table841
- GCC_except_table854
- GCC_except_table858
- GCC_except_table8673
- GCC_except_table8688
- GCC_except_table8695
- GCC_except_table870
- GCC_except_table8711
- GCC_except_table874
- GCC_except_table8802
- GCC_except_table8811
- GCC_except_table8834
- GCC_except_table8864
- GCC_except_table8919
- GCC_except_table8943
- GCC_except_table9320
- GCC_except_table9325
- GCC_except_table9328
- GCC_except_table9331
- GCC_except_table9334
- GCC_except_table9519
- GCC_except_table9522
- GCC_except_table9586
- GCC_except_table9592
- GCC_except_table9606
- GCC_except_table9766
- GCC_except_table979
- GCC_except_table981
- GCC_except_table9866
- _AFBobbleV2Supported.result
- _AFDeviceIsLinwoodCapableWithAsrOnServer
- _AFMeDeviceLinwoodEnablementDidChangeNotification
- _OBJC_CLASS_$_AFArbitrationParticipationContext
- _OBJC_CLASS_$_AFArbitrationParticipationController
- _OBJC_CLASS_$_SCDAFAdvertisement
- _OBJC_CLASS_$_SCDAFBoost
- _OBJC_CLASS_$_SCDAFDevice
- _OBJC_CLASS_$_SCDAFParticipation
- _OBJC_IVAR_$_AFArbitrationParticipationContext._advertisements
- _OBJC_IVAR_$_AFArbitrationParticipationContext._decisionIsWon
- _OBJC_IVAR_$_AFArbitrationParticipationContext._deviceClass
- _OBJC_IVAR_$_AFArbitrationParticipationContext._lastActivationTime
- _OBJC_IVAR_$_AFArbitrationParticipationContext._ownAdvertisement
- _OBJC_IVAR_$_AFArbitrationParticipationContext._requestStartDate
- _OBJC_IVAR_$_AFArbitrationParticipationContext._scoreBoosters
- _OBJC_IVAR_$_AFArbitrationParticipationContext._triggerType
- _OBJC_IVAR_$_AFArbitrationParticipationContext._voiceTriggerDate
- _OBJC_IVAR_$_AFArbitrationParticipationController._participationsForUserFeedback
- _OBJC_IVAR_$_AFArbitrationParticipationController._participationsPublished
- _OBJC_IVAR_$_AFArbitrationParticipationController._queue
- _OBJC_IVAR_$_AFArbitrationParticipationController._settingsConnection
- _OBJC_IVAR_$_AFMyriadCoordinator._arbitrationEventsDelegate
- _OBJC_METACLASS_$_AFArbitrationParticipationContext
- _OBJC_METACLASS_$_AFArbitrationParticipationController
- __OBJC_$_CATEGORY_AceObject_$_AssistantAdditions
- __OBJC_$_CATEGORY_NSArray_$_AFCollectionUtilities
- __OBJC_$_CATEGORY_NSDate_$_AssistantAdditions
- __OBJC_$_CATEGORY_NSDictionary_$_AFCollectionUtilities
- __OBJC_$_CATEGORY_NSNull_$_AFBundleResourceSupport
- __OBJC_$_CATEGORY_NSString_$_AFPreferences
- __OBJC_$_CATEGORY_NSURL_$_AFBundleResourceSupport
- __OBJC_$_CLASS_METHODS_AFVoiceInfo(AFLocalizationAdditions|SiriTTSServiceAdditions|VSAdditions)
- __OBJC_$_CLASS_METHODS_NSString(AFPreferences|AssistantServices|AFSecurityDigestibleChunksProvider|AFSiriRequest|ShortDescription)
- __OBJC_$_CLASS_METHODS_NSURL(AFBundleResourceSupport|AMOSExtensions|AFSecurityDigestibleChunksProvider|STSiriMessage)
- __OBJC_$_INSTANCE_METHODS_AFArbitrationParticipationContext
- __OBJC_$_INSTANCE_METHODS_AFArbitrationParticipationController
- __OBJC_$_INSTANCE_METHODS_AFClockTimer(ClockItem|AFClockTimerMutability)
- __OBJC_$_INSTANCE_METHODS_AFVoiceInfo(AFLocalizationAdditions|SiriTTSServiceAdditions|VSAdditions)
- __OBJC_$_INSTANCE_METHODS_AceObject(AssistantAdditions|AFSecurityDigestibleChunksProvider|AnalyticsContextVending)
- __OBJC_$_INSTANCE_METHODS_NSArray(AFCollectionUtilities|AFSecurityDigestibleChunksProvider)
- __OBJC_$_INSTANCE_METHODS_NSDate(AssistantAdditions|AFSecurityDigestibleChunksProvider)
- __OBJC_$_INSTANCE_METHODS_NSDictionary(AFCollectionUtilities|AFSecurityDigestibleChunksProvider)
- __OBJC_$_INSTANCE_METHODS_NSNull(AFBundleResourceSupport|AFSecurityDigestibleChunksProvider)
- __OBJC_$_INSTANCE_METHODS_NSString(AFPreferences|AssistantServices|AFSecurityDigestibleChunksProvider|AFSiriRequest|ShortDescription)
- __OBJC_$_INSTANCE_METHODS_NSURL(AFBundleResourceSupport|AMOSExtensions|AFSecurityDigestibleChunksProvider|STSiriMessage)
- __OBJC_$_INSTANCE_VARIABLES_AFArbitrationParticipationContext
- __OBJC_$_INSTANCE_VARIABLES_AFArbitrationParticipationController
- __OBJC_$_PROP_LIST_AFArbitrationParticipationContext
- __OBJC_$_PROP_LIST_AFArbitrationParticipationController
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_AFArbitrationEventUpdatesDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_AFArbitrationEventUpdatesDelegate
- __OBJC_$_PROTOCOL_REFS_AFArbitrationEventUpdatesDelegate
- __OBJC_CLASS_PROTOCOLS_$_AFArbitrationParticipationController
- __OBJC_CLASS_PROTOCOLS_$_AFClockTimer(ClockItem|AFClockTimerMutability)
- __OBJC_CLASS_PROTOCOLS_$_AceObject(AssistantAdditions|AFSecurityDigestibleChunksProvider|AnalyticsContextVending)
- __OBJC_CLASS_PROTOCOLS_$_NSArray(AFCollectionUtilities|AFSecurityDigestibleChunksProvider)
- __OBJC_CLASS_PROTOCOLS_$_NSDate(AssistantAdditions|AFSecurityDigestibleChunksProvider)
- __OBJC_CLASS_PROTOCOLS_$_NSDictionary(AFCollectionUtilities|AFSecurityDigestibleChunksProvider)
- __OBJC_CLASS_PROTOCOLS_$_NSNull(AFBundleResourceSupport|AFSecurityDigestibleChunksProvider)
- __OBJC_CLASS_PROTOCOLS_$_NSString(AFPreferences|AssistantServices|AFSecurityDigestibleChunksProvider|AFSiriRequest|ShortDescription)
- __OBJC_CLASS_PROTOCOLS_$_NSURL(AFBundleResourceSupport|AMOSExtensions|AFSecurityDigestibleChunksProvider|STSiriMessage)
- __OBJC_CLASS_RO_$_AFArbitrationParticipationContext
- __OBJC_CLASS_RO_$_AFArbitrationParticipationController
- __OBJC_LABEL_PROTOCOL_$_AFArbitrationEventUpdatesDelegate
- __OBJC_METACLASS_RO_$_AFArbitrationParticipationContext
- __OBJC_METACLASS_RO_$_AFArbitrationParticipationController
- __OBJC_PROTOCOL_$_AFArbitrationEventUpdatesDelegate
- ___203-[AFArbitrationParticipationController _updateUserFeedbackParticipationAllAdvertisements:session:ownRecord:won:triggerType:lastActivationTime:requestStartDate:voiceTriggerDate:scoreBoosters:deviceClass:]_block_invoke
- ___28-[AFLocalization _voiceMaps]_block_invoke
- ___28-[AFLocalization _voiceMaps]_block_invoke_2
- ___36-[AFMyriadCoordinator _loseElection]_block_invoke
- ___36-[AFNetworkAvailability isAvailable]_block_invoke
- ___56-[AFSettingsConnection isLinwoodEnabledOnAnyHomeDevice:]_block_invoke
- ___56-[AFSettingsConnection isLinwoodEnabledOnAnyHomeDevice:]_block_invoke_2
- ___57-[AFMyriadCoordinator requestWillPresentUsefulUserResult]_block_invoke
- ___61-[AFArbitrationParticipationController arbitrationEndedTask:]_block_invoke
- ___64-[AFSettingsConnection publishFeedbackArbitrationParticipation:]_block_invoke
- ___68-[AFArbitrationParticipationController arbitrationEndedAdvertising:]_block_invoke
- ___68-[AFArbitrationParticipationController arbitrationSessionWillStart:]_block_invoke
- ___73-[AFArbitrationParticipationController _publishFeedbackArbitrationRecord]_block_invoke
- ___75-[AFArbitrationParticipationController requestWillPresentUsefulUserResult:]_block_invoke
- ___76-[AFMyriadCoordinator _updateArbitrationParticipationContextWithCompletion:]_block_invoke
- ___91-[AFArbitrationParticipationController arbitrationDidUpdateWithContext:session:completion:]_block_invoke
- ___block_descriptor_40_e8_32s_e35_v32?0"SCDAFParticipation"8Q16^B24ls32l8
- ___block_descriptor_48_e8_32r40w_e5_v8?0lw40l8r32l8
- ___block_descriptor_64_e8_32s40s48s56bs_e35_v16?0"CDASchemaCDAScoreBoosters"8ls32l8s40l8s48l8s56l8
- ___block_descriptor_72_e8_32s40s48s56r64r_e31_v32?0"AFMyriadRecord"8Q16^B24ls32l8s40l8s48l8r56l8r64l8
- __voiceMaps.onceToken
- __voiceMaps.voiceMaps
- _kAFLinwoodEnabledMeDeviceKey
- _notificationNearMissCallback
CStrings:
+ "%@, {event = %ld (%@), presentationMode = %ld, turnId = %@, deviceIdentifier = %@, time = %f, hostTime = %llu"
+ "%s #LinwoodAvailability AFIsLinwoodEnabledAndAvailable: desiredOrchestrationMode=%lu isAvailable=%d result=%d"
+ "%s Index %li out of bounds"
+ "%s SiriInstrumentation or SiriAnalytics not available, skipping assistant_service launch metadata emission"
+ "%s [AFNetworkAvailability] isAvailable (cached): %d"
+ "%s [AFNetworkAvailability] isAvailable (computed live): %d"
+ "%s assistant_service launch metadata emitted: isFirstRequest=%d spawnNs=%llu loadedNs=%llu"
+ "%s desiredOrchestrationMode = %lu, linwoodEverAvailable = %d"
+ "%s requestId=%@ is malformed, skipping assistant_service launch metadata emission"
+ "%s spawn/loaded timestamps not recorded (process is not assistant_service?), skipping emission"
+ ", audioFileURL = %@"
+ ", endpointerOperationMode = %@"
+ ", useAutomaticEndpointing = %d"
+ "-[AFSettingsConnection deleteCloudSyncDataWithCompletion:]_block_invoke"
+ "-[AFSettingsConnection deleteLocalSyncDataWithCompletion:]_block_invoke"
+ "-[AFSettingsConnection disableCloudSyncWithCompletion:]_block_invoke"
+ "-[AFSettingsConnection enableCloudSyncWithCompletion:]_block_invoke"
+ "-[AFTreeNode childNodeAtIndex:]"
+ "-[AFTreeNode insertChildNode:atIndex:]"
+ "-[AFTreeNode removeChildNodeAtIndex:]"
+ "<%@: %p; isAvailable: %@; siriLocale: %@; desiredOrchestrationMode: %@; desiredOrchestrationModeIfEnabled: %@; unavailabilityReasons: %@; linwoodEverAvailable:%@; bootUUID:%@ fromCurrentBoot:%@>"
+ "AFAssistantServiceEmitLaunchMetadataReportedForRequestId"
+ "AFBobbleV2Supported"
+ "AFIsLinwoodEnabledAndWasEverAvailable"
+ "AFSiriAvailability {\n  isAvailable: %@\n  siriLocale: %@\n  desiredOrchestrationMode: %@\n  desiredOrchestrationModeIfEnabled: %@\n  unavailabilityReasons: %@\n  linwoodEverAvailable:%@  bootUUID: %@\n  fromCurrentBoot: %@\n}"
+ "AVSystemController_RouteDescriptionKey_BTDetails_EndpointType"
+ "AVSystemController_RouteDescriptionKey_BTDetails_EndpointType_Vehicle"
+ "AccessRestricted"
+ "CP_CLIENT_EVENT"
+ "DeviceNotCapable"
+ "EnterpriseRestricted"
+ "LanguageIsNotSupported"
+ "Linwood Ever Available"
+ "NSString *getAVSystemController_RouteDescriptionKey_BTDetails_EndpointType(void)"
+ "NSString *getAVSystemController_RouteDescriptionKey_BTDetails_EndpointType_Vehicle(void)"
+ "NotChinaSKU"
+ "RestrictedBundleIdsForAction"
+ "RestrictedBundleIdsForInfo"
+ "UseCaseDisabled"
+ "_hybridUODEnabled"
+ "_resumeSessionId"
+ "_skipGeneratingSpeechPacket"
+ "com.apple.siri.appsettings"
+ "currentOrchestrationMode"
+ "desiredOrchestrationModeIfEnabled"
+ "linwoodEverAvailable"
+ "uuid: %@, timestamp: %llu, requestId: %@, turnId: %@, options: %lu, notifyState: %@, text: %@, directAction: %@, handoffOriginDeviceName: %@, handOffData: %@, handoffURL: %@, handoffRequiresUserInteraction: %d, handoffNotification: %@, correctedSpeech: %@, startRequest: %@, activationEvent: %@, invocationSource: %ld, speechRequestOptions: %@, testRequestOptions: %@, requestCompletionOptions: %@, sharedUserID: %@, confidenceScore: %lu, nonspeakerConfidenceScores: %@, SuggestionRequestType: %@, intelligenceFlowActionDescriptor: %@, isAlwaysAllowedWhileDeviceLocked: %@, explicitRequestContext: %@, announcementContext: %@, resumeSessionId: %@"
+ "v24@?0@\"BKSHIDEventAuthenticationMessage\"8@\"NSError\"16"
+ "}"
- "#%02X"
- "%@, {event = %ld (%@), presentationMode = %ld, turnId = %@, deviceIdentifier = %@, time = %f, hostTime = %llu%@}"
- "%@_%@"
- "%s #myriad #feedback"
- "%s #myriad #feedback Created participation for %@"
- "%s #myriad #feedback action: publishing %lu pariticipations"
- "%s #myriad #feedback arbitration event delgate failed."
- "%s #myriad #feedback event: arbitrationDidUpdateWithContext"
- "%s #myriad #feedback event: arbitrationEndedAdvertising"
- "%s #myriad #feedback event: arbitrationEndedTask"
- "%s #myriad #feedback event: arbitrationSessionWillStart"
- "%s #myriad #feedback event: requestWillPresentUsefulUserResult"
- "%s #myriad #feedback getPreviousBoostsWithCompletion"
- "%s #myriad #feedback myriad sessionid is nil. Returning"
- "%s #myriad #feedback near miss!"
- "%s #myriad #feedback participation already published throwing out."
- "%s #myriad #feedback participation without request start date, throwing out"
- "%s #myriad #feedback recordType: %@, type: %@"
- "%s #myriad #feedback removing participation with nil result"
- "%s #myriad #feedback scoreBoosters from myriadInstrumentation: %@"
- "%s #myriad #feedback session is nil."
- "%s #myriad #feedback unable to find SCDAFParticipation in: %@"
- "%s #myriad #feedback unable to find SCDAFParticipation with myriad sessionId: %@"
- "%s Found nil SCDAF Class: %@, %@, %@."
- "%s [AFNetworkAvailability] Object was deallocated, returning"
- "%s [AFNetworkAvailability] isAvailable set to: %d"
- "%s [AFNetworkAvailability] returning: %d"
- "%s desiredOrchestrationMode = %lu, isAvailable = %d"
- "-[AFArbitrationParticipationController _publishFeedbackArbitrationRecordForNearMiss]"
- "-[AFArbitrationParticipationController _publishFeedbackArbitrationRecord]"
- "-[AFArbitrationParticipationController _publishFeedbackArbitrationRecord]_block_invoke"
- "-[AFArbitrationParticipationController _updateUserFeedbackParticipationAllAdvertisements:session:ownRecord:won:triggerType:lastActivationTime:requestStartDate:voiceTriggerDate:scoreBoosters:deviceClass:]"
- "-[AFArbitrationParticipationController arbitrationDidUpdateWithContext:session:completion:]_block_invoke"
- "-[AFArbitrationParticipationController arbitrationEndedAdvertising:]_block_invoke"
- "-[AFArbitrationParticipationController arbitrationEndedTask:]_block_invoke"
- "-[AFArbitrationParticipationController arbitrationSessionWillStart:]_block_invoke"
- "-[AFArbitrationParticipationController requestWillPresentUsefulUserResult:]_block_invoke"
- "-[AFMyriadCoordinator _triggerTypeForArbitrationParticipationFrom:]"
- "-[AFMyriadCoordinator _updateArbitrationParticipationContextWithCompletion:]"
- "-[AFMyriadCoordinator _updateArbitrationParticipationContextWithCompletion:]_block_invoke"
- "-[AFMyriadCoordinator _updateArbitrationParticipationContextWithCompletion:]_block_invoke_2"
- "-[AFMyriadCoordinator requestWillPresentUsefulUserResult]"
- "-[AFNetworkAvailability isAvailable]_block_invoke"
- "-[AFSettingsConnection publishFeedbackArbitrationParticipation:]_block_invoke"
- "<%@: %p; isAvailable: %@; siriLocale: %@; desiredOrchestrationMode: %@; unavailabilityReasons: %@; bootUUID:%@ fromCurrentBoot:%@>"
- "AFArbitrationParticipationQueue"
- "AFBobbleV2Supported_block_invoke"
- "AFMeDeviceLinwoodEnablementDidChangeNotification"
- "AFSettingsServiceXPCInterface"
- "AFSiriAvailability {\n  isAvailable: %@\n  siriLocale: %@\n  desiredOrchestrationMode: %@\n  unavailabilityReasons: %@\n  bootUUID: %@\n  fromCurrentBoot: %@\n}"
- "ASROnByDefault"
- "Linwood Enabled Me Device"
- "SiriCrossDeviceArbitration"
- "audioFileURL = %@"
- "com.apple.voicetrigger.NearTrigger"
- "endpointerOperationMode = %@"
- "notificationNearMissCallback"
- "useAutomaticEndpointing = %d"
- "userFeedback"
- "userFeedbackOptInWithProfile"
- "uuid: %@, timestamp: %llu, requestId: %@, turnId: %@, options: %lu, notifyState: %@ text: %@ directAction: %@ handoffOriginDeviceName: %@ handOffData: %@ handoffURL: %@ handoffRequiresUserInteraction ? %d handoffNotification %@ correctedSpeech: %@ startRequest: %@ activationEvent: %@ invocationSource: %ld speechRequestOptions: %@ testRequestOptions: %@ requestCompletionOptions: %@ sharedUserID: %@ confidenceScore: %lu nonspeakerConfidenceScores: %@ SuggestionRequestType: %@ intelligenceFlowActionDescriptor: %@ isAlwaysAllowedWhileDeviceLocked: %@ explicitRequestContext: %@ announcementContext: %@"
- "v16@?0@\"CDASchemaCDAScoreBoosters\"8"
- "v32@?0@\"SCDAFParticipation\"8Q16^B24"
```
