## HomeKit

> `/System/Library/Frameworks/HomeKit.framework/HomeKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bc9dc` | `0x3c4e68` | **`+0x848c`** |
| `__TEXT.__eh_frame` | `0x65b8` | `0x7ac0` | **`+0x1508`** |
| `__TEXT.__cstring` | `0x2eadf` | `0x2fd2d` | **`+0x124e`** |
| `__AUTH_CONST.__cfstring` | `0x2a960` | `0x2b600` | **`+0xca0`** |
| `__AUTH_CONST.__objc_const` | `0x483b0` | `0x49030` | **`+0xc80`** |
| `__TEXT.__const` | `0x5d58` | `0x65d8` | **`+0x880`** |
| `__TEXT.__swift5_reflstr` | `0x98f` | `0x1142` | **`+0x7b3`** |
| `__AUTH.__data` | `0x1108` | `0x1728` | **`+0x620`** |
| `__DATA.__bss` | `0x8e88` | `0x9388` | **`+0x500`** |
| `__TEXT.__unwind_info` | `0xc590` | `0xca50` | **`+0x4c0`** |
| `__TEXT.__constg_swiftt` | `0x1778` | `0x1bc8` | **`+0x450`** |
| `__TEXT.__objc_methlist` | `0x28504` | `0x288dc` | **`+0x3d8`** |
| `__TEXT.__oslogstring` | `0x56d11` | `0x56f17` | **`+0x206`** |
| `__DATA_CONST.__objc_selrefs` | `0xe0b8` | `0xe2a0` | **`+0x1e8`** |
| `__TEXT.__swift5_fieldmd` | `0x1210` | `0x13ec` | **`+0x1dc`** |
| `__AUTH_CONST.__const` | `0x6280` | `0x60b0` | **`-0x1d0`** |
| `__AUTH_CONST.__auth_got` | `0x1878` | `0x19b0` | **`+0x138`** |
| `__DATA.__data` | `0x5210` | `0x5290` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x1e80` | `0x1efc` | **`+0x7c`** |
| `__TEXT.__gcc_except_tab` | `0x67dc` | `0x6844` | **`+0x68`** |
| `__DATA_CONST.__got` | `0x1dd0` | `0x1e18` | **`+0x48`** |
| `__TEXT.__swift5_assocty` | `0x2d8` | `0x320` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x8ba8` | `0x8be8` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x27d8` | `0x2810` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x92c` | `0x8fc` | **`-0x30`** |
| `__TEXT.__swift_as_cont` | `0x468` | `0x448` | **`-0x20`** |
| `__TEXT.__swift5_types` | `0x1cc` | `0x1b0` | **`-0x1c`** |
| `__DATA.__common` | `0x90` | `0xa8` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x228` | `0x23c` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x4a8` | `0x4b8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1368` | `0x1370` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1e0` | `0x1e8` | **`+0x8`** |

### Other Changes

```diff

-1468.5.0.0.6
+1479.0.0.1.0

-  - /System/Library/Frameworks/PDFKit.framework/PDFKit

-  Functions: 17255
-  Symbols:   27159
-  CStrings:  12278
+  Functions: 17468
+  Symbols:   27266
+  CStrings:  12403
Symbols:
+ +[HMMediaDestination identifierForParentIdentifier:]
+ +[HMMediaDestinationControllerData identifierForParentIdentifier:]
+ +[HMMediaSystemData derivedDestinationIdentifierForGroupIdentifier:]
+ -[HMAccessCodeAddRequestValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessCodeConstraints hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessCodeModificationResponseValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessCodeRemoveRequestValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessCodeUpdateRequestValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessCodeUserInformation hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessCodeUserInformationValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessCodeValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessory hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessoryAccessCode hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessoryAccessCodeConstraintsFetchResponseValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessoryAccessCodeFetchResponseValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessoryAccessCodeValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessoryCapabilities supportsAudioDestinationHomePodGeneration2HomeTheater]
+ -[HMAccessoryCapabilities supportsAudioDestinationHomeTheater]
+ -[HMAccessoryCapabilities supportsAudioDestinationMediaSystemHomePodGeneration2]
+ -[HMAccessoryCapabilities supportsAudioDestinationMediaSystemMini]
+ -[HMAccessoryCapabilities supportsAudioDestinationMediaSystem]
+ -[HMAccessoryCapabilities supportsAudioDestinationMiniHomeTheater]
+ -[HMAccessoryCapabilities supportsHomeTheaterSourceHomePodGeneration2]
+ -[HMAccessoryCapabilities supportsHomeTheaterSourceHomePodMini]
+ -[HMAccessoryCapabilities supportsHomeTheaterSourceOriginalHomePod]
+ -[HMAccessoryDiagnosticsMetadata hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessoryNetworkProtectionGroup hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessorySettingFetchResult hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessorySettingsFetchRequestMessagePayload hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessorySettingsFetchResponseMessagePayload hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessorySettingsMessenger hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessorySettingsPartialFetchFailureInformation hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessorySettingsUpdateRequestMessagePayload hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessorySetupCompletedInfo hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessorySetupRequest hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAccessorySetupResult hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAddAccessoryRequest hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAnnounceUserSettings hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAudioAnalysisAggregateEventBulletin hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAudioAnalysisEventBulletin hmf_appendAttributeDescriptionsToString:options:]
+ -[HMAudioAnalysisEventBulletinBoardNotification hmf_appendAttributeDescriptionsToString:options:]
+ -[HMBooleanSetting hmf_appendAttributeDescriptionsToString:options:]
+ -[HMBoundedIntegerSetting hmf_appendAttributeDescriptionsToString:options:]
+ -[HMBulletinBoardNotification hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCHIPAccessoryOperationalIdentity hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCHIPAccessoryPairing hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCHIPAccessorySetupPayload hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCHIPEcosystem hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCHIPHome hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCHIPVendor hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCHIPVendorMetadataProduct hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCHIPVendorMetadataVendor hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraBulletinBoardNotificationCondition hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraBulletinBoardSmartNotification hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraClip hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraClipAssetContext hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraClipSignificantEvent hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraClipVideoAssetContext hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraClipVideoDataSegment hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraClipVideoFrame hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraClipVideoFrameEvent hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraClipVideoSegment hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraSignificantEvent hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraSignificantEventPersonFamiliarityNotificationCondition hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraSignificantEventReasonNotificationCondition hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraSnapshot hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraStreamAudioPreferences hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraStreamPreferences hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraStreamVideoPreferences hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraUserNotificationSettings hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCameraUserSettings hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCharacteristic hmf_appendAttributeDescriptionsToString:options:]
+ -[HMCoreAnalyticsMetricEvent initWithName:fieldData:]
+ -[HMDevice hmf_appendAttributeDescriptionsToString:options:]
+ -[HMFaceClassification hmf_appendAttributeDescriptionsToString:options:]
+ -[HMFaceCrop hmf_appendAttributeDescriptionsToString:options:]
+ -[HMHome internalUUID]
+ -[HMHomeAccessCode hmf_appendAttributeDescriptionsToString:options:]
+ -[HMHomeAccessCodeValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMHomeCloudShareResponse initWithOwnerUser:participant:clientInfo:]
+ -[HMHomeFetchLightProfileSettingsResult hmf_appendAttributeDescriptionsToString:options:]
+ -[HMHomeManagerConfiguration hmf_appendAttributeDescriptionsToString:options:]
+ -[HMHomePersonManagerSettings hmf_appendAttributeDescriptionsToString:options:]
+ -[HMHomeTheaterSystem hmf_appendAttributeDescriptionsToString:options:]
+ -[HMHomeTheaterSystem shortDescription]
+ -[HMHomeWalletKey hmf_appendAttributeDescriptionsToString:options:]
+ -[HMHomeWalletKeyDeviceState hmf_appendAttributeDescriptionsToString:options:]
+ -[HMImmutableSetting hmf_appendAttributeDescriptionsToString:options:]
+ -[HMImmutableSettingValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMImmutableStringSetting hmf_appendAttributeDescriptionsToString:options:]
+ -[HMIncomingHomeInvitation hmf_appendAttributeDescriptionsToString:options:]
+ -[HMLanguageSetting hmf_appendAttributeDescriptionsToString:options:]
+ -[HMLanguageValueListSetting hmf_appendAttributeDescriptionsToString:options:]
+ -[HMLightProfileSettings hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMMClientRequestHandlerOptions hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMMClientResponseHandlerOptions hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMMMessageDestination hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMMRegistrationOptions hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMMRequestOptions hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMatterBulletinBoardNotification hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaDestination hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaDestinationController data]
+ -[HMMediaDestinationController hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaDestinationController setData:]
+ -[HMMediaDestinationControllerData hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaDestinationControllerRequestMessagePayload hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaGroup hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaGroup metricType]
+ -[HMMediaGroupConfigurationRequest hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaGroupConfigurationRequest metricType]
+ -[HMMediaGroupConfigurationRequestPayload hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaGroupDestination hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaGroupStageRequestPayload hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaGroupStageRequestPayload initWithDestinations:destinationControllersData:groups:removedGroupIdentifiers:metricType:]
+ -[HMMediaGroupStageRequestPayload metricType]
+ -[HMMediaGroupStagingManager didMergedHome:]
+ -[HMMediaGroupStagingManager hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaGroupStagingManager metricStartTime]
+ -[HMMediaGroupStagingManager metricType]
+ -[HMMediaGroupStagingManager setMetricStartTime:]
+ -[HMMediaGroupStagingManager setMetricType:]
+ -[HMMediaGroupStagingManager stagedDataExistsInHome:]
+ -[HMMediaGroupsController committedGroups]
+ -[HMMediaGroupsController createGroupResponseHandlerWithMetricType:startTime:completion:]
+ -[HMMediaGroupsController hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaGroupsController removeGroupResponseHandlerWithGroup:startTime:completion:]
+ -[HMMediaSystemData hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMediaSystemData shortDescription]
+ -[HMMissingWalletKey hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMissingWalletKeyValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMModernMessagingClient hmf_appendAttributeDescriptionsToString:options:]
+ -[HMMultiuserSettingsMessenger hmf_appendAttributeDescriptionsToString:options:]
+ -[HMPerson hmf_appendAttributeDescriptionsToString:options:]
+ -[HMPersonFaceCrop hmf_appendAttributeDescriptionsToString:options:]
+ -[HMPersonLink hmf_appendAttributeDescriptionsToString:options:]
+ -[HMPhotosPersonManagerSettings hmf_appendAttributeDescriptionsToString:options:]
+ -[HMProtoAccessoryCapabilities hasSupports1299912b90f3]
+ -[HMProtoAccessoryCapabilities hasSupportsAudioDestinationHomePodGeneration2HomeTheater]
+ -[HMProtoAccessoryCapabilities hasSupportsAudioDestinationHomeTheater]
+ -[HMProtoAccessoryCapabilities hasSupportsAudioDestinationMediaSystemHomePodGeneration2]
+ -[HMProtoAccessoryCapabilities hasSupportsAudioDestinationMediaSystemMini]
+ -[HMProtoAccessoryCapabilities hasSupportsAudioDestinationMediaSystem]
+ -[HMProtoAccessoryCapabilities hasSupportsAudioDestinationMiniHomeTheater]
+ -[HMProtoAccessoryCapabilities hasSupportsHomeTheaterSourceHomePodGeneration2]
+ -[HMProtoAccessoryCapabilities hasSupportsHomeTheaterSourceHomePodMini]
+ -[HMProtoAccessoryCapabilities hasSupportsHomeTheaterSourceOriginalHomePod]
+ -[HMProtoAccessoryCapabilities hasSupportsd711b2f2f198]
+ -[HMProtoAccessoryCapabilities hasSupportseac3b4015a2e]
+ -[HMProtoAccessoryCapabilities setHasSupports1299912b90f3:]
+ -[HMProtoAccessoryCapabilities setHasSupportsAudioDestinationHomePodGeneration2HomeTheater:]
+ -[HMProtoAccessoryCapabilities setHasSupportsAudioDestinationHomeTheater:]
+ -[HMProtoAccessoryCapabilities setHasSupportsAudioDestinationMediaSystem:]
+ -[HMProtoAccessoryCapabilities setHasSupportsAudioDestinationMediaSystemHomePodGeneration2:]
+ -[HMProtoAccessoryCapabilities setHasSupportsAudioDestinationMediaSystemMini:]
+ -[HMProtoAccessoryCapabilities setHasSupportsAudioDestinationMiniHomeTheater:]
+ -[HMProtoAccessoryCapabilities setHasSupportsHomeTheaterSourceHomePodGeneration2:]
+ -[HMProtoAccessoryCapabilities setHasSupportsHomeTheaterSourceHomePodMini:]
+ -[HMProtoAccessoryCapabilities setHasSupportsHomeTheaterSourceOriginalHomePod:]
+ -[HMProtoAccessoryCapabilities setHasSupportsd711b2f2f198:]
+ -[HMProtoAccessoryCapabilities setHasSupportseac3b4015a2e:]
+ -[HMProtoAccessoryCapabilities setSupports1299912b90f3:]
+ -[HMProtoAccessoryCapabilities setSupportsAudioDestinationHomePodGeneration2HomeTheater:]
+ -[HMProtoAccessoryCapabilities setSupportsAudioDestinationHomeTheater:]
+ -[HMProtoAccessoryCapabilities setSupportsAudioDestinationMediaSystem:]
+ -[HMProtoAccessoryCapabilities setSupportsAudioDestinationMediaSystemHomePodGeneration2:]
+ -[HMProtoAccessoryCapabilities setSupportsAudioDestinationMediaSystemMini:]
+ -[HMProtoAccessoryCapabilities setSupportsAudioDestinationMiniHomeTheater:]
+ -[HMProtoAccessoryCapabilities setSupportsHomeTheaterSourceHomePodGeneration2:]
+ -[HMProtoAccessoryCapabilities setSupportsHomeTheaterSourceHomePodMini:]
+ -[HMProtoAccessoryCapabilities setSupportsHomeTheaterSourceOriginalHomePod:]
+ -[HMProtoAccessoryCapabilities setSupportsd711b2f2f198:]
+ -[HMProtoAccessoryCapabilities setSupportseac3b4015a2e:]
+ -[HMProtoAccessoryCapabilities supports1299912b90f3]
+ -[HMProtoAccessoryCapabilities supportsAudioDestinationHomePodGeneration2HomeTheater]
+ -[HMProtoAccessoryCapabilities supportsAudioDestinationHomeTheater]
+ -[HMProtoAccessoryCapabilities supportsAudioDestinationMediaSystemHomePodGeneration2]
+ -[HMProtoAccessoryCapabilities supportsAudioDestinationMediaSystemMini]
+ -[HMProtoAccessoryCapabilities supportsAudioDestinationMediaSystem]
+ -[HMProtoAccessoryCapabilities supportsAudioDestinationMiniHomeTheater]
+ -[HMProtoAccessoryCapabilities supportsHomeTheaterSourceHomePodGeneration2]
+ -[HMProtoAccessoryCapabilities supportsHomeTheaterSourceHomePodMini]
+ -[HMProtoAccessoryCapabilities supportsHomeTheaterSourceOriginalHomePod]
+ -[HMProtoAccessoryCapabilities supportsd711b2f2f198]
+ -[HMProtoAccessoryCapabilities supportseac3b4015a2e]
+ -[HMRemovedUserInfo hmf_appendAttributeDescriptionsToString:options:]
+ -[HMResidentDevice hmf_appendAttributeDescriptionsToString:options:]
+ -[HMRestrictedGuestHomeAccessSchedule hmf_appendAttributeDescriptionsToString:options:]
+ -[HMRestrictedGuestHomeAccessSettings hmf_appendAttributeDescriptionsToString:options:]
+ -[HMService hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSettingBooleanValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSettingIntegerValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSettingLanguageValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSettingStringValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSettingVersionValue hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSetupAccessoryDescription hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSetupAccessoryPayload deferredMatterOnboardingURL]
+ -[HMSetupAccessoryPayload hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSetupAccessoryPayload setDeferredMatterOnboardingURL:]
+ -[HMSiriEndpointApplyOnboardingSelectionsPayload hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSiriEndpointApplyOnboardingSelectionsResponsePayload hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSiriEndpointDeleteSiriHistoryMessagePayload hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSiriEndpointOnboardingSelections hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSiriEndpointProfile hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSoftwareUpdateDescriptor hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSoftwareUpdateProgressV2 hmf_appendAttributeDescriptionsToString:options:]
+ -[HMSoftwareUpdateV2 hmf_appendAttributeDescriptionsToString:options:]
+ -[HMStringListSetting hmf_appendAttributeDescriptionsToString:options:]
+ -[HMUserActionPrediction hmf_appendAttributeDescriptionsToString:options:]
+ -[HMUserInviteInformation hmf_appendAttributeDescriptionsToString:options:]
+ -[HMVendorModelEntry hmf_appendAttributeDescriptionsToString:options:]
+ -[HMWeekDaySchedule hmf_appendAttributeDescriptionsToString:options:]
+ -[HMWeekDayScheduleRule hmf_appendAttributeDescriptionsToString:options:]
+ -[HMXPCConnection hmf_appendAttributeDescriptionsToString:options:]
+ -[HMXPCMessageTransportConfiguration hmf_appendAttributeDescriptionsToString:options:]
+ -[HMYearDayScheduleRule hmf_appendAttributeDescriptionsToString:options:]
+ -[_HMCameraUserSettings hmf_appendAttributeDescriptionsToString:options:]
+ -[_HMSiriEndpointProfile hmf_appendAttributeDescriptionsToString:options:]
+ GCC_except_table10197
+ GCC_except_table10210
+ GCC_except_table10261
+ GCC_except_table10264
+ GCC_except_table10266
+ GCC_except_table10279
+ GCC_except_table10280
+ GCC_except_table10348
+ GCC_except_table10351
+ GCC_except_table10352
+ GCC_except_table10712
+ GCC_except_table10750
+ GCC_except_table10763
+ GCC_except_table11138
+ GCC_except_table11140
+ GCC_except_table11142
+ GCC_except_table11143
+ GCC_except_table11153
+ GCC_except_table11177
+ GCC_except_table11178
+ GCC_except_table11181
+ GCC_except_table11184
+ GCC_except_table11193
+ GCC_except_table11194
+ GCC_except_table11195
+ GCC_except_table11292
+ GCC_except_table11324
+ GCC_except_table11325
+ GCC_except_table11373
+ GCC_except_table11399
+ GCC_except_table11412
+ GCC_except_table11438
+ GCC_except_table11442
+ GCC_except_table11491
+ GCC_except_table11492
+ GCC_except_table11493
+ GCC_except_table11494
+ GCC_except_table11495
+ GCC_except_table11496
+ GCC_except_table11497
+ GCC_except_table11498
+ GCC_except_table11499
+ GCC_except_table11500
+ GCC_except_table11501
+ GCC_except_table11502
+ GCC_except_table11503
+ GCC_except_table11504
+ GCC_except_table11505
+ GCC_except_table11506
+ GCC_except_table11529
+ GCC_except_table1154
+ GCC_except_table11556
+ GCC_except_table1158
+ GCC_except_table116
+ GCC_except_table1165
+ GCC_except_table11666
+ GCC_except_table11667
+ GCC_except_table11670
+ GCC_except_table11736
+ GCC_except_table11738
+ GCC_except_table11746
+ GCC_except_table11757
+ GCC_except_table11759
+ GCC_except_table11764
+ GCC_except_table11765
+ GCC_except_table11766
+ GCC_except_table11988
+ GCC_except_table12189
+ GCC_except_table12192
+ GCC_except_table12197
+ GCC_except_table12201
+ GCC_except_table12207
+ GCC_except_table12212
+ GCC_except_table12214
+ GCC_except_table12220
+ GCC_except_table12304
+ GCC_except_table12306
+ GCC_except_table12325
+ GCC_except_table12326
+ GCC_except_table12327
+ GCC_except_table12328
+ GCC_except_table12347
+ GCC_except_table12353
+ GCC_except_table12356
+ GCC_except_table12358
+ GCC_except_table1240
+ GCC_except_table12436
+ GCC_except_table12444
+ GCC_except_table12445
+ GCC_except_table12450
+ GCC_except_table12456
+ GCC_except_table12458
+ GCC_except_table12460
+ GCC_except_table12462
+ GCC_except_table12464
+ GCC_except_table12466
+ GCC_except_table12468
+ GCC_except_table1249
+ GCC_except_table12601
+ GCC_except_table12657
+ GCC_except_table12796
+ GCC_except_table12803
+ GCC_except_table12808
+ GCC_except_table13004
+ GCC_except_table13057
+ GCC_except_table1317
+ GCC_except_table1319
+ GCC_except_table1324
+ GCC_except_table1326
+ GCC_except_table13270
+ GCC_except_table13278
+ GCC_except_table13299
+ GCC_except_table1330
+ GCC_except_table13310
+ GCC_except_table13315
+ GCC_except_table13318
+ GCC_except_table13332
+ GCC_except_table13337
+ GCC_except_table13343
+ GCC_except_table13348
+ GCC_except_table13353
+ GCC_except_table13358
+ GCC_except_table13363
+ GCC_except_table13372
+ GCC_except_table13423
+ GCC_except_table13427
+ GCC_except_table13435
+ GCC_except_table13440
+ GCC_except_table13454
+ GCC_except_table13459
+ GCC_except_table13466
+ GCC_except_table13482
+ GCC_except_table13483
+ GCC_except_table13487
+ GCC_except_table13490
+ GCC_except_table13495
+ GCC_except_table13502
+ GCC_except_table13511
+ GCC_except_table13545
+ GCC_except_table13599
+ GCC_except_table13615
+ GCC_except_table13625
+ GCC_except_table13720
+ GCC_except_table13762
+ GCC_except_table13766
+ GCC_except_table13767
+ GCC_except_table13768
+ GCC_except_table13778
+ GCC_except_table13779
+ GCC_except_table13803
+ GCC_except_table13804
+ GCC_except_table13878
+ GCC_except_table13900
+ GCC_except_table13903
+ GCC_except_table14048
+ GCC_except_table14245
+ GCC_except_table14250
+ GCC_except_table14253
+ GCC_except_table14315
+ GCC_except_table14348
+ GCC_except_table14353
+ GCC_except_table14354
+ GCC_except_table14355
+ GCC_except_table14356
+ GCC_except_table14358
+ GCC_except_table14367
+ GCC_except_table14369
+ GCC_except_table14371
+ GCC_except_table14374
+ GCC_except_table14375
+ GCC_except_table14376
+ GCC_except_table14377
+ GCC_except_table14378
+ GCC_except_table14379
+ GCC_except_table14381
+ GCC_except_table14383
+ GCC_except_table14385
+ GCC_except_table14387
+ GCC_except_table14510
+ GCC_except_table14513
+ GCC_except_table14533
+ GCC_except_table14535
+ GCC_except_table14536
+ GCC_except_table1517
+ GCC_except_table1542
+ GCC_except_table158
+ GCC_except_table159
+ GCC_except_table1610
+ GCC_except_table1677
+ GCC_except_table1680
+ GCC_except_table1698
+ GCC_except_table1766
+ GCC_except_table1768
+ GCC_except_table1779
+ GCC_except_table1781
+ GCC_except_table1909
+ GCC_except_table1961
+ GCC_except_table1964
+ GCC_except_table2038
+ GCC_except_table2127
+ GCC_except_table2128
+ GCC_except_table2177
+ GCC_except_table2445
+ GCC_except_table2448
+ GCC_except_table2451
+ GCC_except_table2456
+ GCC_except_table2460
+ GCC_except_table2469
+ GCC_except_table2482
+ GCC_except_table2484
+ GCC_except_table2485
+ GCC_except_table2490
+ GCC_except_table2491
+ GCC_except_table2492
+ GCC_except_table2493
+ GCC_except_table3037
+ GCC_except_table3042
+ GCC_except_table3068
+ GCC_except_table3071
+ GCC_except_table3084
+ GCC_except_table3121
+ GCC_except_table3137
+ GCC_except_table3140
+ GCC_except_table3166
+ GCC_except_table3168
+ GCC_except_table3170
+ GCC_except_table3172
+ GCC_except_table3337
+ GCC_except_table3364
+ GCC_except_table3365
+ GCC_except_table3412
+ GCC_except_table3414
+ GCC_except_table3438
+ GCC_except_table3440
+ GCC_except_table3443
+ GCC_except_table3444
+ GCC_except_table3468
+ GCC_except_table3470
+ GCC_except_table3478
+ GCC_except_table3480
+ GCC_except_table3487
+ GCC_except_table3488
+ GCC_except_table3489
+ GCC_except_table3491
+ GCC_except_table3492
+ GCC_except_table3493
+ GCC_except_table3494
+ GCC_except_table3495
+ GCC_except_table3578
+ GCC_except_table3601
+ GCC_except_table3604
+ GCC_except_table3607
+ GCC_except_table3610
+ GCC_except_table3613
+ GCC_except_table3616
+ GCC_except_table3619
+ GCC_except_table3684
+ GCC_except_table3685
+ GCC_except_table3731
+ GCC_except_table3738
+ GCC_except_table3739
+ GCC_except_table3740
+ GCC_except_table3743
+ GCC_except_table3744
+ GCC_except_table3745
+ GCC_except_table3747
+ GCC_except_table3755
+ GCC_except_table3777
+ GCC_except_table3784
+ GCC_except_table3788
+ GCC_except_table3791
+ GCC_except_table3794
+ GCC_except_table3835
+ GCC_except_table3839
+ GCC_except_table3843
+ GCC_except_table3848
+ GCC_except_table3856
+ GCC_except_table3860
+ GCC_except_table3869
+ GCC_except_table3871
+ GCC_except_table4024
+ GCC_except_table4026
+ GCC_except_table4028
+ GCC_except_table4150
+ GCC_except_table4154
+ GCC_except_table4157
+ GCC_except_table4161
+ GCC_except_table4162
+ GCC_except_table4165
+ GCC_except_table4171
+ GCC_except_table4179
+ GCC_except_table4202
+ GCC_except_table4204
+ GCC_except_table4206
+ GCC_except_table4209
+ GCC_except_table4210
+ GCC_except_table4212
+ GCC_except_table4215
+ GCC_except_table4290
+ GCC_except_table4304
+ GCC_except_table4307
+ GCC_except_table4309
+ GCC_except_table4312
+ GCC_except_table4319
+ GCC_except_table4373
+ GCC_except_table4438
+ GCC_except_table4453
+ GCC_except_table4456
+ GCC_except_table4549
+ GCC_except_table4551
+ GCC_except_table4556
+ GCC_except_table4560
+ GCC_except_table4563
+ GCC_except_table4565
+ GCC_except_table4573
+ GCC_except_table4822
+ GCC_except_table4825
+ GCC_except_table4837
+ GCC_except_table4913
+ GCC_except_table4957
+ GCC_except_table5050
+ GCC_except_table5310
+ GCC_except_table5405
+ GCC_except_table5424
+ GCC_except_table5434
+ GCC_except_table5574
+ GCC_except_table5583
+ GCC_except_table5596
+ GCC_except_table5603
+ GCC_except_table5646
+ GCC_except_table5648
+ GCC_except_table5676
+ GCC_except_table5678
+ GCC_except_table5680
+ GCC_except_table5682
+ GCC_except_table5689
+ GCC_except_table5695
+ GCC_except_table5701
+ GCC_except_table5711
+ GCC_except_table5717
+ GCC_except_table572
+ GCC_except_table577
+ GCC_except_table5798
+ GCC_except_table5807
+ GCC_except_table5809
+ GCC_except_table5819
+ GCC_except_table5821
+ GCC_except_table5823
+ GCC_except_table5825
+ GCC_except_table5827
+ GCC_except_table5833
+ GCC_except_table5837
+ GCC_except_table585
+ GCC_except_table5850
+ GCC_except_table5852
+ GCC_except_table5854
+ GCC_except_table5856
+ GCC_except_table586
+ GCC_except_table5875
+ GCC_except_table5905
+ GCC_except_table5954
+ GCC_except_table5966
+ GCC_except_table5968
+ GCC_except_table5992
+ GCC_except_table5993
+ GCC_except_table5994
+ GCC_except_table5995
+ GCC_except_table6060
+ GCC_except_table6214
+ GCC_except_table6215
+ GCC_except_table6327
+ GCC_except_table6329
+ GCC_except_table6357
+ GCC_except_table6359
+ GCC_except_table6377
+ GCC_except_table6423
+ GCC_except_table6518
+ GCC_except_table6538
+ GCC_except_table6539
+ GCC_except_table6540
+ GCC_except_table6542
+ GCC_except_table6545
+ GCC_except_table6546
+ GCC_except_table6548
+ GCC_except_table6874
+ GCC_except_table6880
+ GCC_except_table6882
+ GCC_except_table6892
+ GCC_except_table6893
+ GCC_except_table7096
+ GCC_except_table7100
+ GCC_except_table7174
+ GCC_except_table7199
+ GCC_except_table7203
+ GCC_except_table7205
+ GCC_except_table7206
+ GCC_except_table7345
+ GCC_except_table7352
+ GCC_except_table744
+ GCC_except_table747
+ GCC_except_table7472
+ GCC_except_table752
+ GCC_except_table7527
+ GCC_except_table7529
+ GCC_except_table7531
+ GCC_except_table755
+ GCC_except_table7553
+ GCC_except_table756
+ GCC_except_table7581
+ GCC_except_table7593
+ GCC_except_table7610
+ GCC_except_table7616
+ GCC_except_table7627
+ GCC_except_table7629
+ GCC_except_table7631
+ GCC_except_table7633
+ GCC_except_table7635
+ GCC_except_table7637
+ GCC_except_table7639
+ GCC_except_table7641
+ GCC_except_table7643
+ GCC_except_table7645
+ GCC_except_table7647
+ GCC_except_table7649
+ GCC_except_table7651
+ GCC_except_table7656
+ GCC_except_table7670
+ GCC_except_table7671
+ GCC_except_table7694
+ GCC_except_table7696
+ GCC_except_table7721
+ GCC_except_table7734
+ GCC_except_table7752
+ GCC_except_table778
+ GCC_except_table7939
+ GCC_except_table795
+ GCC_except_table814
+ GCC_except_table8274
+ GCC_except_table83
+ GCC_except_table8317
+ GCC_except_table8410
+ GCC_except_table8419
+ GCC_except_table8594
+ GCC_except_table8596
+ GCC_except_table8597
+ GCC_except_table8598
+ GCC_except_table8600
+ GCC_except_table8602
+ GCC_except_table8603
+ GCC_except_table8604
+ GCC_except_table8639
+ GCC_except_table864
+ GCC_except_table8642
+ GCC_except_table8643
+ GCC_except_table8646
+ GCC_except_table8649
+ GCC_except_table8650
+ GCC_except_table867
+ GCC_except_table868
+ GCC_except_table8693
+ GCC_except_table8694
+ GCC_except_table8695
+ GCC_except_table8702
+ GCC_except_table8703
+ GCC_except_table8705
+ GCC_except_table8793
+ GCC_except_table8794
+ GCC_except_table8795
+ GCC_except_table8833
+ GCC_except_table8847
+ GCC_except_table8915
+ GCC_except_table8943
+ GCC_except_table8944
+ GCC_except_table8945
+ GCC_except_table8947
+ GCC_except_table8950
+ GCC_except_table8951
+ GCC_except_table8956
+ GCC_except_table91
+ GCC_except_table9103
+ GCC_except_table9104
+ GCC_except_table9105
+ GCC_except_table9109
+ GCC_except_table9164
+ GCC_except_table9185
+ GCC_except_table9265
+ GCC_except_table9267
+ GCC_except_table9269
+ GCC_except_table9271
+ GCC_except_table9279
+ GCC_except_table9326
+ GCC_except_table9338
+ GCC_except_table934
+ GCC_except_table9340
+ GCC_except_table9356
+ GCC_except_table938
+ GCC_except_table9385
+ GCC_except_table939
+ GCC_except_table940
+ GCC_except_table941
+ GCC_except_table942
+ GCC_except_table943
+ GCC_except_table945
+ GCC_except_table947
+ GCC_except_table954
+ GCC_except_table955
+ GCC_except_table9574
+ GCC_except_table9575
+ GCC_except_table9610
+ GCC_except_table9649
+ GCC_except_table9651
+ GCC_except_table9717
+ GCC_except_table9739
+ GCC_except_table9778
+ GCC_except_table9780
+ GCC_except_table9782
+ GCC_except_table9847
+ GCC_except_table9879
+ GCC_except_table9881
+ GCC_except_table9885
+ GCC_except_table9902
+ GCC_except_table9904
+ GCC_except_table9910
+ GCC_except_table9914
+ GCC_except_table9917
+ GCC_except_table9924
+ GCC_except_table9928
+ GCC_except_table9934
+ GCC_except_table9946
+ GCC_except_table9949
+ GCC_except_table9957
+ GCC_except_table9960
+ GCC_except_table9962
+ GCC_except_table9964
+ GCC_except_table9984
+ GCC_except_table9994
+ OBJC_IVAR_$_HMProtoAccessoryCapabilities._supports1299912b90f3
+ OBJC_IVAR_$_HMProtoAccessoryCapabilities._supportsAudioDestinationHomePodGeneration2HomeTheater
+ OBJC_IVAR_$_HMProtoAccessoryCapabilities._supportsAudioDestinationHomeTheater
+ OBJC_IVAR_$_HMProtoAccessoryCapabilities._supportsAudioDestinationMediaSystem
+ OBJC_IVAR_$_HMProtoAccessoryCapabilities._supportsAudioDestinationMediaSystemHomePodGeneration2
+ OBJC_IVAR_$_HMProtoAccessoryCapabilities._supportsAudioDestinationMediaSystemMini
+ OBJC_IVAR_$_HMProtoAccessoryCapabilities._supportsAudioDestinationMiniHomeTheater
+ OBJC_IVAR_$_HMProtoAccessoryCapabilities._supportsHomeTheaterSourceHomePodGeneration2
+ OBJC_IVAR_$_HMProtoAccessoryCapabilities._supportsHomeTheaterSourceHomePodMini
+ OBJC_IVAR_$_HMProtoAccessoryCapabilities._supportsHomeTheaterSourceOriginalHomePod
+ OBJC_IVAR_$_HMProtoAccessoryCapabilities._supportsd711b2f2f198
+ OBJC_IVAR_$_HMProtoAccessoryCapabilities._supportseac3b4015a2e
+ _HMAddMediaSystemHintsRequest
+ _HMFFormatAttributeValue
+ _HMRemoveMediaSystemHintsRequest
+ _NSLocaleLanguageCode
+ _OBJC_IVAR_$_HMCoreAnalyticsMetricEvent._fieldData
+ _OBJC_IVAR_$_HMMediaDestinationController._data
+ _OBJC_IVAR_$_HMMediaGroupStageRequestPayload._metricType
+ _OBJC_IVAR_$_HMMediaGroupStagingManager._metricStartTime
+ _OBJC_IVAR_$_HMMediaGroupStagingManager._metricType
+ _OBJC_IVAR_$_HMSetupAccessoryPayload._deferredMatterOnboardingURL
+ __DATA__TtCV7HomeKit20ResidentCapabilitiesP33_5D29CBA69468E03C22D4A3D2DBE7046713_StorageClass
+ __IVARS__TtCV7HomeKit20ResidentCapabilitiesP33_5D29CBA69468E03C22D4A3D2DBE7046713_StorageClass
+ __METACLASS_DATA__TtCV7HomeKit20ResidentCapabilitiesP33_5D29CBA69468E03C22D4A3D2DBE7046713_StorageClass
+ __OBJC_$_CATEGORY_NSCoder_$_ObjectCache
+ __OBJC_$_CLASS_METHODS_HMHome(HomeKit|HomeKit1|HomeKit2|SwiftExtensions|AccessCode|WalletInternal|Wallet|Light|MediaGroupSettingsControllerFactory|ThreadResidentCommissioning|SiriEndpointProfilesMessengerFactory|HMActionExecution|Person|Person_Internal|Matter|CHIP|AutomationBuilders|HMAccessory|HMRoom|HMZone|HMServiceGroup|HMUser|HMActionSet|HMTrigger|RemoteAccess|HMSoftwareUpdate|HMMediaProfile|NetworkRouter|HMUserActionPredictions|ThreadManagement|HMHomeHub|PowerAssertionInfo|HomeNetworkInfo|HomeLocationFeedback|MediaGroupReadinessCheck|HomeActivityState|ResidentSelection|HMModernMessaging|HMModernMessagingInternal|Trigger|Biome|Climate)
+ __OBJC_$_INSTANCE_METHODS_HMHome(HomeKit|HomeKit1|HomeKit2|SwiftExtensions|AccessCode|WalletInternal|Wallet|Light|MediaGroupSettingsControllerFactory|ThreadResidentCommissioning|SiriEndpointProfilesMessengerFactory|HMActionExecution|Person|Person_Internal|Matter|CHIP|AutomationBuilders|HMAccessory|HMRoom|HMZone|HMServiceGroup|HMUser|HMActionSet|HMTrigger|RemoteAccess|HMSoftwareUpdate|HMMediaProfile|NetworkRouter|HMUserActionPredictions|ThreadManagement|HMHomeHub|PowerAssertionInfo|HomeNetworkInfo|HomeLocationFeedback|MediaGroupReadinessCheck|HomeActivityState|ResidentSelection|HMModernMessaging|HMModernMessagingInternal|Trigger|Biome|Climate)
+ __OBJC_$_INSTANCE_METHODS_NSCoder(ObjectCache|HMExtensions)
+ __OBJC_CLASS_PROTOCOLS_$_HMHome(HomeKit|HomeKit1|HomeKit2|SwiftExtensions|AccessCode|WalletInternal|Wallet|Light|MediaGroupSettingsControllerFactory|ThreadResidentCommissioning|SiriEndpointProfilesMessengerFactory|HMActionExecution|Person|Person_Internal|Matter|CHIP|AutomationBuilders|HMAccessory|HMRoom|HMZone|HMServiceGroup|HMUser|HMActionSet|HMTrigger|RemoteAccess|HMSoftwareUpdate|HMMediaProfile|NetworkRouter|HMUserActionPredictions|ThreadManagement|HMHomeHub|PowerAssertionInfo|HomeNetworkInfo|HomeLocationFeedback|MediaGroupReadinessCheck|HomeActivityState|ResidentSelection|HMModernMessaging|HMModernMessagingInternal|Trigger|Biome|Climate)
+ ___53-[HMMediaGroupStagingManager stagedDataExistsInHome:]_block_invoke
+ ___64-[HMCameraClip hmf_appendAttributeDescriptionsToString:options:]_block_invoke
+ ___75-[HMMediaGroupsController hmf_appendAttributeDescriptionsToString:options:]_block_invoke
+ ___84-[HMMediaGroupsController removeGroupResponseHandlerWithGroup:startTime:completion:]_block_invoke
+ ___89-[HMMediaGroupsController createGroupResponseHandlerWithMetricType:startTime:completion:]_block_invoke
+ ___block_descriptor_56_e8_32s40bs48w_e34_v24?0"NSError"8"NSDictionary"16lw48l8s32l8s40l8
+ ___block_descriptor_56_e8_32s40bs_e5_v8?0ls40l8s32l8
+ ___block_descriptor_56_e8_32s40s48r_e20_v24?0"NSUUID"8^B16ls32l8r48l8s40l8
+ ___block_descriptor_64_e8_32s40bs_e34_v24?0"NSError"8"NSDictionary"16ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls56l8s32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e34_v24?0"NSError"8"NSDictionary"16ls32l8s40l8s48l8s64l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ ___swift_memcpy24_8
+ _associated conformance 7HomeKit17NotificationEventV10CodingKeys33_673C7FAE7163133A589BA1C0DB422376LLOSHAASQ
+ _associated conformance 7HomeKit17NotificationEventV10CodingKeys33_673C7FAE7163133A589BA1C0DB422376LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 7HomeKit17NotificationEventV10CodingKeys33_673C7FAE7163133A589BA1C0DB422376LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit17NotificationEventV16FoundationModels29ConvertibleToGeneratedContentAaD19PromptRepresentable
+ _associated conformance 7HomeKit17NotificationEventV16FoundationModels29ConvertibleToGeneratedContentAaD25InstructionsRepresentable
+ _associated conformance 7HomeKit17NotificationEventV16FoundationModels9GenerableAA18PartiallyGeneratedAdEP_AD015ConvertibleFromI7Content
+ _associated conformance 7HomeKit17NotificationEventV16FoundationModels9GenerableAaD29ConvertibleToGeneratedContent
+ _associated conformance 7HomeKit17NotificationEventV16FoundationModels9GenerableAaD31ConvertibleFromGeneratedContent
+ _associated conformance 7HomeKit17NotificationEventV18PartiallyGeneratedVs12IdentifiableAA2IDsAFP_SH
+ _associated conformance 7HomeKit20ResidentCapabilitiesV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 7HomeKit20ResidentCapabilitiesV21InternalSwiftProtobuf26_MessageImplementationBaseAaD0H0
+ _associated conformance 7HomeKit20ResidentCapabilitiesV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit20ResidentCapabilitiesVSHAASQ
+ _associated conformance 7HomeKit21NotificationEventTypeO16FoundationModels29ConvertibleToGeneratedContentAaD19PromptRepresentable
+ _associated conformance 7HomeKit21NotificationEventTypeO16FoundationModels29ConvertibleToGeneratedContentAaD25InstructionsRepresentable
+ _associated conformance 7HomeKit21NotificationEventTypeO16FoundationModels9GenerableAA18PartiallyGeneratedAdEP_AD015ConvertibleFromJ7Content
+ _associated conformance 7HomeKit21NotificationEventTypeO16FoundationModels9GenerableAaD29ConvertibleToGeneratedContent
+ _associated conformance 7HomeKit21NotificationEventTypeO16FoundationModels9GenerableAaD31ConvertibleFromGeneratedContent
+ _associated conformance 7HomeKit21NotificationEventTypeOSHAASQ
+ _associated conformance 7HomeKit21NotificationEventTypeOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 7HomeKit30NotificationSummarizationInputV10CodingKeys33_673C7FAE7163133A589BA1C0DB422376LLOSHAASQ
+ _associated conformance 7HomeKit30NotificationSummarizationInputV10CodingKeys33_673C7FAE7163133A589BA1C0DB422376LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 7HomeKit30NotificationSummarizationInputV10CodingKeys33_673C7FAE7163133A589BA1C0DB422376LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 7HomeKit30NotificationSummarizationInputV16FoundationModels29ConvertibleToGeneratedContentAaD19PromptRepresentable
+ _associated conformance 7HomeKit30NotificationSummarizationInputV16FoundationModels29ConvertibleToGeneratedContentAaD25InstructionsRepresentable
+ _associated conformance 7HomeKit30NotificationSummarizationInputV16FoundationModels9GenerableAA18PartiallyGeneratedAdEP_AD015ConvertibleFromJ7Content
+ _associated conformance 7HomeKit30NotificationSummarizationInputV16FoundationModels9GenerableAaD29ConvertibleToGeneratedContent
+ _associated conformance 7HomeKit30NotificationSummarizationInputV16FoundationModels9GenerableAaD31ConvertibleFromGeneratedContent
+ _associated conformance 7HomeKit30NotificationSummarizationInputV18PartiallyGeneratedVs12IdentifiableAA2IDsAFP_SH
+ _hm_mediaGroupCreated
+ _hm_mediaGroupRemoved
+ _hm_mediaGroupStagingResults
+ _logCategory._hmf_once_t67
+ _logCategory._hmf_once_v68
+ _symbolic $s16FoundationModels9GenerableP
+ _symbolic $ss12IdentifiableP
+ _symbolic SS4name_______p5valuet 16FoundationModels29ConvertibleToGeneratedContentP
+ _symbolic SS_______pt 16FoundationModels29ConvertibleToGeneratedContentP
+ _symbolic SaySS_______ptG 16FoundationModels29ConvertibleToGeneratedContentP
+ _symbolic Say_____G 7HomeKit17NotificationEventV
+ _symbolic Say_____G 7HomeKit17NotificationEventV18PartiallyGeneratedV
+ _symbolic Say_____G 7HomeKit21NotificationEventTypeO
+ _symbolic Say_____GSg 7HomeKit17NotificationEventV18PartiallyGeneratedV
+ _symbolic SbSg
+ _symbolic _____ 16FoundationModels12GenerationIDV
+ _symbolic _____ 21InternalSwiftProtobuf14UnknownStorageV
+ _symbolic _____ 7HomeKit17NotificationEventV
+ _symbolic _____ 7HomeKit17NotificationEventV10CodingKeys33_673C7FAE7163133A589BA1C0DB422376LLO
+ _symbolic _____ 7HomeKit17NotificationEventV18PartiallyGeneratedV
+ _symbolic _____ 7HomeKit20ResidentCapabilitiesV
+ _symbolic _____ 7HomeKit20ResidentCapabilitiesV13_StorageClass33_5D29CBA69468E03C22D4A3D2DBE70467LLC
+ _symbolic _____ 7HomeKit21NotificationEventTypeO
+ _symbolic _____ 7HomeKit30NotificationSummarizationInputV
+ _symbolic _____ 7HomeKit30NotificationSummarizationInputV10CodingKeys33_673C7FAE7163133A589BA1C0DB422376LLO
+ _symbolic _____ 7HomeKit30NotificationSummarizationInputV18PartiallyGeneratedV
+ _symbolic _____Sg 16FoundationModels12GenerationIDV
+ _symbolic _____Sg 7HomeKit21NotificationEventTypeO
+ _symbolic ______Say_____GAAt 16FoundationModels6PromptV 7HomeKit17NotificationEventV
+ _symbolic _____ySJG s11_SetStorageC
+ _symbolic _____ySS4name_______p5valuetG s23_ContiguousArrayStorageC 16FoundationModels29ConvertibleToGeneratedContentP
+ _symbolic _____ySS_______ptG s23_ContiguousArrayStorageC 16FoundationModels29ConvertibleToGeneratedContentP
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7HomeKit17NotificationEventV10CodingKeys33_673C7FAE7163133A589BA1C0DB422376LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7HomeKit30NotificationSummarizationInputV10CodingKeys33_673C7FAE7163133A589BA1C0DB422376LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7HomeKit17NotificationEventV10CodingKeys33_673C7FAE7163133A589BA1C0DB422376LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7HomeKit30NotificationSummarizationInputV10CodingKeys33_673C7FAE7163133A589BA1C0DB422376LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 16FoundationModels16GenerationSchemaV8PropertyV
+ _type_layout_string 7HomeKit17NotificationEventV
+ _type_layout_string 7HomeKit30NotificationSummarizationInputV
- -[HMAccessCodeAddRequestValue attributeDescriptions]
- -[HMAccessCodeConstraints attributeDescriptions]
- -[HMAccessCodeModificationResponseValue attributeDescriptions]
- -[HMAccessCodeRemoveRequestValue attributeDescriptions]
- -[HMAccessCodeUpdateRequestValue attributeDescriptions]
- -[HMAccessCodeUserInformation attributeDescriptions]
- -[HMAccessCodeUserInformationValue attributeDescriptions]
- -[HMAccessCodeValue attributeDescriptions]
- -[HMAccessory attributeDescriptions]
- -[HMAccessoryAccessCode attributeDescriptions]
- -[HMAccessoryAccessCodeConstraintsFetchResponseValue attributeDescriptions]
- -[HMAccessoryAccessCodeFetchResponseValue attributeDescriptions]
- -[HMAccessoryAccessCodeValue attributeDescriptions]
- -[HMAccessoryDiagnosticsMetadata attributeDescriptions]
- -[HMAccessoryNetworkProtectionGroup attributeDescriptions]
- -[HMAccessorySettingFetchResult attributeDescriptions]
- -[HMAccessorySettingsFetchRequestMessagePayload attributeDescriptions]
- -[HMAccessorySettingsFetchResponseMessagePayload attributeDescriptions]
- -[HMAccessorySettingsMessenger attributeDescriptions]
- -[HMAccessorySettingsPartialFetchFailureInformation attributeDescriptions]
- -[HMAccessorySettingsUpdateRequestMessagePayload attributeDescriptions]
- -[HMAccessorySetupCompletedInfo attributeDescriptions]
- -[HMAccessorySetupRequest attributeDescriptions]
- -[HMAccessorySetupResult attributeDescriptions]
- -[HMAddAccessoryRequest attributeDescriptions]
- -[HMAnnounceUserSettings attributeDescriptions]
- -[HMAudioAnalysisAggregateEventBulletin attributeDescriptions]
- -[HMAudioAnalysisEventBulletin attributeDescriptions]
- -[HMAudioAnalysisEventBulletinBoardNotification attributeDescriptions]
- -[HMBooleanSetting attributeDescriptions]
- -[HMBoundedIntegerSetting attributeDescriptions]
- -[HMBulletinBoardNotification attributeDescriptions]
- -[HMCHIPAccessoryOperationalIdentity attributeDescriptions]
- -[HMCHIPAccessoryPairing attributeDescriptions]
- -[HMCHIPAccessorySetupPayload attributeDescriptions]
- -[HMCHIPEcosystem attributeDescriptions]
- -[HMCHIPHome attributeDescriptions]
- -[HMCHIPVendor attributeDescriptions]
- -[HMCHIPVendorMetadataProduct attributeDescriptions]
- -[HMCHIPVendorMetadataVendor attributeDescriptions]
- -[HMCameraBulletinBoardNotificationCondition attributeDescriptions]
- -[HMCameraBulletinBoardSmartNotification attributeDescriptions]
- -[HMCameraClip attributeDescriptions]
- -[HMCameraClipAssetContext attributeDescriptions]
- -[HMCameraClipSignificantEvent attributeDescriptions]
- -[HMCameraClipVideoAssetContext attributeDescriptions]
- -[HMCameraClipVideoDataSegment attributeDescriptions]
- -[HMCameraClipVideoFrame attributeDescriptions]
- -[HMCameraClipVideoFrameEvent attributeDescriptions]
- -[HMCameraClipVideoSegment attributeDescriptions]
- -[HMCameraSignificantEvent attributeDescriptions]
- -[HMCameraSignificantEventPersonFamiliarityNotificationCondition attributeDescriptions]
- -[HMCameraSignificantEventReasonNotificationCondition attributeDescriptions]
- -[HMCameraSnapshot attributeDescriptions]
- -[HMCameraStreamAudioPreferences attributeDescriptions]
- -[HMCameraStreamPreferences attributeDescriptions]
- -[HMCameraStreamVideoPreferences attributeDescriptions]
- -[HMCameraUserNotificationSettings attributeDescriptions]
- -[HMCameraUserSettings attributeDescriptions]
- -[HMCharacteristic attributeDescriptions]
- -[HMDevice attributeDescriptions]
- -[HMFaceClassification attributeDescriptions]
- -[HMFaceCrop attributeDescriptions]
- -[HMHomeAccessCode attributeDescriptions]
- -[HMHomeAccessCodeValue attributeDescriptions]
- -[HMHomeCloudShareResponse initWithOwnerUser:pariticipant:clientInfo:]
- -[HMHomeFetchLightProfileSettingsResult attributeDescriptions]
- -[HMHomeManagerConfiguration attributeDescriptions]
- -[HMHomePersonManagerSettings attributeDescriptions]
- -[HMHomeTheaterSystem attributeDescriptions]
- -[HMHomeWalletKey attributeDescriptions]
- -[HMHomeWalletKeyDeviceState attributeDescriptions]
- -[HMImmutableSetting attributeDescriptions]
- -[HMImmutableSettingValue attributeDescriptions]
- -[HMImmutableStringSetting attributeDescriptions]
- -[HMIncomingHomeInvitation attributeDescriptions]
- -[HMLanguageSetting attributeDescriptions]
- -[HMLanguageValueListSetting attributeDescriptions]
- -[HMLightProfileSettings attributeDescriptions]
- -[HMMMClientRequestHandlerOptions attributeDescriptions]
- -[HMMMClientResponseHandlerOptions attributeDescriptions]
- -[HMMMMessageDestination attributeDescriptions]
- -[HMMMRegistrationOptions attributeDescriptions]
- -[HMMMRequestOptions attributeDescriptions]
- -[HMMatterBulletinBoardNotification attributeDescriptions]
- -[HMMediaDestination attributeDescriptions]
- -[HMMediaDestinationController attributeDescriptions]
- -[HMMediaDestinationController initWithIdentifier:destinationIdentifier:supportedOptions:availableDestinationIdentifiers:]
- -[HMMediaDestinationController mergeSupportedOptionsWithNewController:]
- -[HMMediaDestinationController setAvailableDestinationIdentifiers:]
- -[HMMediaDestinationController setDestinationIdentifier:]
- -[HMMediaDestinationController setSupportedOptions:]
- -[HMMediaDestinationControllerData attributeDescriptions]
- -[HMMediaDestinationControllerRequestMessagePayload attributeDescriptions]
- -[HMMediaGroup attributeDescriptions]
- -[HMMediaGroupConfigurationRequest attributeDescriptions]
- -[HMMediaGroupConfigurationRequestPayload attributeDescriptions]
- -[HMMediaGroupDestination attributeDescriptions]
- -[HMMediaGroupStageRequestPayload attributeDescriptions]
- -[HMMediaGroupStageRequestPayload initWithDestinations:destinationControllersData:groups:removedGroupIdentifiers:]
- -[HMMediaGroupStagingManager attributeDescriptions]
- -[HMMediaGroupsController attributeDescriptions]
- -[HMMediaGroupsController createGroupResponseHandlerWithCompletion:]
- -[HMMediaGroupsController removeGroupResponseHandlerWithGroup:completion:]
- -[HMMediaSystemData attributeDescriptions]
- -[HMMissingWalletKey attributeDescriptions]
- -[HMMissingWalletKeyValue attributeDescriptions]
- -[HMModernMessagingClient attributeDescriptions]
- -[HMMultiuserSettingsMessenger attributeDescriptions]
- -[HMPerson attributeDescriptions]
- -[HMPersonFaceCrop attributeDescriptions]
- -[HMPersonLink attributeDescriptions]
- -[HMPhotosPersonManagerSettings attributeDescriptions]
- -[HMRemovedUserInfo attributeDescriptions]
- -[HMResidentDevice attributeDescriptions]
- -[HMRestrictedGuestHomeAccessSchedule attributeDescriptions]
- -[HMRestrictedGuestHomeAccessSettings attributeDescriptions]
- -[HMService attributeDescriptions]
- -[HMSettingBooleanValue attributeDescriptions]
- -[HMSettingIntegerValue attributeDescriptions]
- -[HMSettingLanguageValue attributeDescriptions]
- -[HMSettingStringValue attributeDescriptions]
- -[HMSettingVersionValue attributeDescriptions]
- -[HMSetupAccessoryDescription attributeDescriptions]
- -[HMSetupAccessoryPayload attributeDescriptions]
- -[HMSiriEndpointApplyOnboardingSelectionsPayload attributeDescriptions]
- -[HMSiriEndpointApplyOnboardingSelectionsResponsePayload attributeDescriptions]
- -[HMSiriEndpointDeleteSiriHistoryMessagePayload attributeDescriptions]
- -[HMSiriEndpointOnboardingSelections attributeDescriptions]
- -[HMSiriEndpointProfile attributeDescriptions]
- -[HMSoftwareUpdateDescriptor attributeDescriptions]
- -[HMSoftwareUpdateProgressV2 attributeDescriptions]
- -[HMSoftwareUpdateV2 attributeDescriptions]
- -[HMStringListSetting attributeDescriptions]
- -[HMUserActionPrediction attributeDescriptions]
- -[HMUserInviteInformation attributeDescriptions]
- -[HMVendorModelEntry attributeDescriptions]
- -[HMWeekDaySchedule attributeDescriptions]
- -[HMWeekDayScheduleRule attributeDescriptions]
- -[HMXPCConnection attributeDescriptions]
- -[HMXPCMessageTransportConfiguration attributeDescriptions]
- -[HMYearDayScheduleRule attributeDescriptions]
- -[_HMCameraUserSettings attributeDescriptions]
- -[_HMSiriEndpointProfile attributeDescriptions]
- GCC_except_table10145
- GCC_except_table10146
- GCC_except_table10147
- GCC_except_table10151
- GCC_except_table10206
- GCC_except_table10227
- GCC_except_table10306
- GCC_except_table10308
- GCC_except_table10310
- GCC_except_table10312
- GCC_except_table10320
- GCC_except_table10367
- GCC_except_table1037
- GCC_except_table10379
- GCC_except_table10381
- GCC_except_table10397
- GCC_except_table10426
- GCC_except_table10615
- GCC_except_table10616
- GCC_except_table10651
- GCC_except_table10684
- GCC_except_table10687
- GCC_except_table10690
- GCC_except_table10692
- GCC_except_table10771
- GCC_except_table10791
- GCC_except_table10792
- GCC_except_table10793
- GCC_except_table10832
- GCC_except_table10834
- GCC_except_table10836
- GCC_except_table10901
- GCC_except_table10933
- GCC_except_table10935
- GCC_except_table10939
- GCC_except_table10956
- GCC_except_table10958
- GCC_except_table10964
- GCC_except_table10968
- GCC_except_table10971
- GCC_except_table10978
- GCC_except_table10982
- GCC_except_table10988
- GCC_except_table11000
- GCC_except_table11003
- GCC_except_table11011
- GCC_except_table11012
- GCC_except_table11014
- GCC_except_table11016
- GCC_except_table11018
- GCC_except_table11038
- GCC_except_table11048
- GCC_except_table11251
- GCC_except_table11264
- GCC_except_table11315
- GCC_except_table11333
- GCC_except_table11334
- GCC_except_table114
- GCC_except_table11402
- GCC_except_table11405
- GCC_except_table11406
- GCC_except_table11753
- GCC_except_table11791
- GCC_except_table11804
- GCC_except_table12179
- GCC_except_table12181
- GCC_except_table12183
- GCC_except_table12184
- GCC_except_table12194
- GCC_except_table12218
- GCC_except_table12225
- GCC_except_table12234
- GCC_except_table12235
- GCC_except_table12236
- GCC_except_table12359
- GCC_except_table12361
- GCC_except_table12365
- GCC_except_table12366
- GCC_except_table1241
- GCC_except_table12414
- GCC_except_table1243
- GCC_except_table12440
- GCC_except_table12453
- GCC_except_table12479
- GCC_except_table12483
- GCC_except_table1250
- GCC_except_table12532
- GCC_except_table12533
- GCC_except_table12534
- GCC_except_table12535
- GCC_except_table12536
- GCC_except_table12537
- GCC_except_table12538
- GCC_except_table12539
- GCC_except_table12540
- GCC_except_table12541
- GCC_except_table12542
- GCC_except_table12543
- GCC_except_table12544
- GCC_except_table12545
- GCC_except_table12546
- GCC_except_table12547
- GCC_except_table12570
- GCC_except_table1258
- GCC_except_table12597
- GCC_except_table12707
- GCC_except_table12708
- GCC_except_table12711
- GCC_except_table12777
- GCC_except_table12779
- GCC_except_table1278
- GCC_except_table12787
- GCC_except_table12798
- GCC_except_table12800
- GCC_except_table12805
- GCC_except_table12806
- GCC_except_table12807
- GCC_except_table1289
- GCC_except_table1294
- GCC_except_table1297
- GCC_except_table13029
- GCC_except_table1311
- GCC_except_table1316
- GCC_except_table13230
- GCC_except_table13233
- GCC_except_table13238
- GCC_except_table13242
- GCC_except_table13248
- GCC_except_table13253
- GCC_except_table13255
- GCC_except_table13260
- GCC_except_table1327
- GCC_except_table1332
- GCC_except_table13345
- GCC_except_table13347
- GCC_except_table13366
- GCC_except_table13368
- GCC_except_table13369
- GCC_except_table1337
- GCC_except_table13374
- GCC_except_table13388
- GCC_except_table13394
- GCC_except_table13397
- GCC_except_table13399
- GCC_except_table1342
- GCC_except_table1346
- GCC_except_table13477
- GCC_except_table13486
- GCC_except_table13491
- GCC_except_table13497
- GCC_except_table13499
- GCC_except_table13501
- GCC_except_table13503
- GCC_except_table13505
- GCC_except_table13509
- GCC_except_table1351
- GCC_except_table13642
- GCC_except_table13698
- GCC_except_table13699
- GCC_except_table13700
- GCC_except_table13701
- GCC_except_table13711
- GCC_except_table13712
- GCC_except_table13736
- GCC_except_table13737
- GCC_except_table13811
- GCC_except_table13833
- GCC_except_table13836
- GCC_except_table13979
- GCC_except_table1402
- GCC_except_table1406
- GCC_except_table1414
- GCC_except_table14176
- GCC_except_table14181
- GCC_except_table14184
- GCC_except_table1419
- GCC_except_table14246
- GCC_except_table14279
- GCC_except_table14284
- GCC_except_table14285
- GCC_except_table14286
- GCC_except_table14287
- GCC_except_table14291
- GCC_except_table14293
- GCC_except_table14295
- GCC_except_table14298
- GCC_except_table14299
- GCC_except_table14300
- GCC_except_table14301
- GCC_except_table14302
- GCC_except_table14303
- GCC_except_table14305
- GCC_except_table14307
- GCC_except_table14309
- GCC_except_table14311
- GCC_except_table1433
- GCC_except_table1438
- GCC_except_table14431
- GCC_except_table14434
- GCC_except_table1445
- GCC_except_table14454
- GCC_except_table14456
- GCC_except_table14457
- GCC_except_table1461
- GCC_except_table1462
- GCC_except_table1464
- GCC_except_table1466
- GCC_except_table1469
- GCC_except_table1474
- GCC_except_table1481
- GCC_except_table1486
- GCC_except_table1490
- GCC_except_table1524
- GCC_except_table156
- GCC_except_table157
- GCC_except_table1578
- GCC_except_table1693
- GCC_except_table1696
- GCC_except_table1701
- GCC_except_table1704
- GCC_except_table1705
- GCC_except_table1727
- GCC_except_table1744
- GCC_except_table1763
- GCC_except_table1813
- GCC_except_table1816
- GCC_except_table1817
- GCC_except_table1883
- GCC_except_table1887
- GCC_except_table1888
- GCC_except_table1889
- GCC_except_table1890
- GCC_except_table1891
- GCC_except_table1892
- GCC_except_table1894
- GCC_except_table1896
- GCC_except_table1903
- GCC_except_table1904
- GCC_except_table1944
- GCC_except_table1954
- GCC_except_table2049
- GCC_except_table2257
- GCC_except_table2261
- GCC_except_table2268
- GCC_except_table2343
- GCC_except_table2352
- GCC_except_table2420
- GCC_except_table2422
- GCC_except_table2425
- GCC_except_table2427
- GCC_except_table2429
- GCC_except_table2433
- GCC_except_table2619
- GCC_except_table2644
- GCC_except_table2712
- GCC_except_table2779
- GCC_except_table2782
- GCC_except_table2800
- GCC_except_table2868
- GCC_except_table2870
- GCC_except_table2881
- GCC_except_table2883
- GCC_except_table2995
- GCC_except_table3066
- GCC_except_table3069
- GCC_except_table3143
- GCC_except_table3232
- GCC_except_table3233
- GCC_except_table3282
- GCC_except_table3550
- GCC_except_table3553
- GCC_except_table3556
- GCC_except_table3561
- GCC_except_table3565
- GCC_except_table3574
- GCC_except_table3587
- GCC_except_table3589
- GCC_except_table3590
- GCC_except_table3595
- GCC_except_table3596
- GCC_except_table3597
- GCC_except_table3598
- GCC_except_table4141
- GCC_except_table4172
- GCC_except_table4188
- GCC_except_table4225
- GCC_except_table4241
- GCC_except_table4244
- GCC_except_table4270
- GCC_except_table4272
- GCC_except_table4274
- GCC_except_table4276
- GCC_except_table4441
- GCC_except_table4468
- GCC_except_table4469
- GCC_except_table4516
- GCC_except_table4518
- GCC_except_table4542
- GCC_except_table4544
- GCC_except_table4547
- GCC_except_table4572
- GCC_except_table4574
- GCC_except_table4582
- GCC_except_table4584
- GCC_except_table4591
- GCC_except_table4592
- GCC_except_table4593
- GCC_except_table4595
- GCC_except_table4596
- GCC_except_table4597
- GCC_except_table4598
- GCC_except_table4599
- GCC_except_table4681
- GCC_except_table4704
- GCC_except_table4707
- GCC_except_table4710
- GCC_except_table4713
- GCC_except_table4716
- GCC_except_table4719
- GCC_except_table4722
- GCC_except_table4787
- GCC_except_table4788
- GCC_except_table4834
- GCC_except_table4841
- GCC_except_table4842
- GCC_except_table4843
- GCC_except_table4846
- GCC_except_table4847
- GCC_except_table4848
- GCC_except_table4850
- GCC_except_table4858
- GCC_except_table4880
- GCC_except_table4887
- GCC_except_table4891
- GCC_except_table4894
- GCC_except_table4897
- GCC_except_table4938
- GCC_except_table4942
- GCC_except_table4946
- GCC_except_table4951
- GCC_except_table4959
- GCC_except_table4963
- GCC_except_table4972
- GCC_except_table4974
- GCC_except_table5213
- GCC_except_table5217
- GCC_except_table5221
- GCC_except_table5224
- GCC_except_table5228
- GCC_except_table5229
- GCC_except_table5232
- GCC_except_table5238
- GCC_except_table5242
- GCC_except_table5246
- GCC_except_table5274
- GCC_except_table5276
- GCC_except_table5278
- GCC_except_table5305
- GCC_except_table5307
- GCC_except_table5309
- GCC_except_table5312
- GCC_except_table5315
- GCC_except_table5318
- GCC_except_table5393
- GCC_except_table5407
- GCC_except_table5410
- GCC_except_table5412
- GCC_except_table5415
- GCC_except_table5422
- GCC_except_table5475
- GCC_except_table5540
- GCC_except_table5555
- GCC_except_table5558
- GCC_except_table5650
- GCC_except_table5651
- GCC_except_table5653
- GCC_except_table5658
- GCC_except_table5662
- GCC_except_table5665
- GCC_except_table5667
- GCC_except_table5675
- GCC_except_table570
- GCC_except_table573
- GCC_except_table581
- GCC_except_table584
- GCC_except_table5915
- GCC_except_table5918
- GCC_except_table5930
- GCC_except_table6006
- GCC_except_table6143
- GCC_except_table6334
- GCC_except_table6346
- GCC_except_table6348
- GCC_except_table6372
- GCC_except_table6373
- GCC_except_table6374
- GCC_except_table6375
- GCC_except_table6430
- GCC_except_table6440
- GCC_except_table6592
- GCC_except_table6593
- GCC_except_table6705
- GCC_except_table6707
- GCC_except_table6735
- GCC_except_table6737
- GCC_except_table6755
- GCC_except_table6801
- GCC_except_table6896
- GCC_except_table6916
- GCC_except_table6917
- GCC_except_table6918
- GCC_except_table6920
- GCC_except_table6923
- GCC_except_table6924
- GCC_except_table6926
- GCC_except_table7252
- GCC_except_table7258
- GCC_except_table7260
- GCC_except_table7270
- GCC_except_table7271
- GCC_except_table7474
- GCC_except_table7478
- GCC_except_table7662
- GCC_except_table7665
- GCC_except_table7757
- GCC_except_table776
- GCC_except_table7776
- GCC_except_table7786
- GCC_except_table783
- GCC_except_table788
- GCC_except_table7926
- GCC_except_table7935
- GCC_except_table7948
- GCC_except_table7955
- GCC_except_table7998
- GCC_except_table8000
- GCC_except_table8028
- GCC_except_table8030
- GCC_except_table8032
- GCC_except_table8034
- GCC_except_table8041
- GCC_except_table8047
- GCC_except_table8053
- GCC_except_table8063
- GCC_except_table8069
- GCC_except_table81
- GCC_except_table8150
- GCC_except_table8159
- GCC_except_table8161
- GCC_except_table8171
- GCC_except_table8173
- GCC_except_table8175
- GCC_except_table8177
- GCC_except_table8179
- GCC_except_table8185
- GCC_except_table8189
- GCC_except_table8202
- GCC_except_table8204
- GCC_except_table8206
- GCC_except_table8208
- GCC_except_table8227
- GCC_except_table8257
- GCC_except_table8265
- GCC_except_table8290
- GCC_except_table8294
- GCC_except_table8296
- GCC_except_table8297
- GCC_except_table8436
- GCC_except_table8443
- GCC_except_table8563
- GCC_except_table8618
- GCC_except_table8620
- GCC_except_table8622
- GCC_except_table8644
- GCC_except_table8672
- GCC_except_table8684
- GCC_except_table8701
- GCC_except_table8707
- GCC_except_table8718
- GCC_except_table8720
- GCC_except_table8722
- GCC_except_table8726
- GCC_except_table8728
- GCC_except_table8730
- GCC_except_table8732
- GCC_except_table8734
- GCC_except_table8736
- GCC_except_table8738
- GCC_except_table8740
- GCC_except_table8742
- GCC_except_table8747
- GCC_except_table8761
- GCC_except_table8762
- GCC_except_table8785
- GCC_except_table8787
- GCC_except_table8812
- GCC_except_table8825
- GCC_except_table8843
- GCC_except_table89
- GCC_except_table9030
- GCC_except_table9317
- GCC_except_table9360
- GCC_except_table9453
- GCC_except_table9462
- GCC_except_table9637
- GCC_except_table9639
- GCC_except_table9640
- GCC_except_table9641
- GCC_except_table9645
- GCC_except_table9647
- GCC_except_table9682
- GCC_except_table9685
- GCC_except_table9686
- GCC_except_table9689
- GCC_except_table9692
- GCC_except_table9693
- GCC_except_table9736
- GCC_except_table9745
- GCC_except_table9746
- GCC_except_table9748
- GCC_except_table9767
- GCC_except_table9836
- GCC_except_table9837
- GCC_except_table9838
- GCC_except_table984
- GCC_except_table9876
- GCC_except_table9890
- GCC_except_table9986
- GCC_except_table9987
- GCC_except_table9988
- GCC_except_table9990
- GCC_except_table9993
- GCC_except_table9998
- _OBJC_CLASS_$_HMFAttributeDescription
- _OBJC_IVAR_$_HMMediaDestinationController._availableDestinationIdentifiers
- _OBJC_IVAR_$_HMMediaDestinationController._destinationIdentifier
- _OBJC_IVAR_$_HMMediaDestinationController._identifier
- _OBJC_IVAR_$_HMMediaDestinationController._supportedOptions
- __OBJC_$_CATEGORY_NSCoder_$_HMExtensions
- __OBJC_$_CLASS_METHODS_HMHome(HomeKit|HomeKit1|SwiftExtensions|HomeKit2|HMAccessory|HMRoom|HMZone|HMServiceGroup|HMUser|HMActionSet|HMTrigger|RemoteAccess|HMSoftwareUpdate|HMMediaProfile|NetworkRouter|HMUserActionPredictions|ThreadManagement|HMHomeHub|PowerAssertionInfo|HomeNetworkInfo|HomeLocationFeedback|MediaGroupReadinessCheck|HomeActivityState|ResidentSelection|HMModernMessaging|HMModernMessagingInternal|Trigger|Biome|Climate|AccessCode|WalletInternal|Wallet|Light|MediaGroupSettingsControllerFactory|ThreadResidentCommissioning|SiriEndpointProfilesMessengerFactory|HMActionExecution|Person|Person_Internal|Matter|CHIP|AutomationBuilders)
- __OBJC_$_INSTANCE_METHODS_HMHome(HomeKit|HomeKit1|SwiftExtensions|HomeKit2|HMAccessory|HMRoom|HMZone|HMServiceGroup|HMUser|HMActionSet|HMTrigger|RemoteAccess|HMSoftwareUpdate|HMMediaProfile|NetworkRouter|HMUserActionPredictions|ThreadManagement|HMHomeHub|PowerAssertionInfo|HomeNetworkInfo|HomeLocationFeedback|MediaGroupReadinessCheck|HomeActivityState|ResidentSelection|HMModernMessaging|HMModernMessagingInternal|Trigger|Biome|Climate|AccessCode|WalletInternal|Wallet|Light|MediaGroupSettingsControllerFactory|ThreadResidentCommissioning|SiriEndpointProfilesMessengerFactory|HMActionExecution|Person|Person_Internal|Matter|CHIP|AutomationBuilders)
- __OBJC_$_INSTANCE_METHODS_NSCoder(HMExtensions|ObjectCache)
- __OBJC_CLASS_PROTOCOLS_$_HMHome(HomeKit|HomeKit1|SwiftExtensions|HomeKit2|HMAccessory|HMRoom|HMZone|HMServiceGroup|HMUser|HMActionSet|HMTrigger|RemoteAccess|HMSoftwareUpdate|HMMediaProfile|NetworkRouter|HMUserActionPredictions|ThreadManagement|HMHomeHub|PowerAssertionInfo|HomeNetworkInfo|HomeLocationFeedback|MediaGroupReadinessCheck|HomeActivityState|ResidentSelection|HMModernMessaging|HMModernMessagingInternal|Trigger|Biome|Climate|AccessCode|WalletInternal|Wallet|Light|MediaGroupSettingsControllerFactory|ThreadResidentCommissioning|SiriEndpointProfilesMessengerFactory|HMActionExecution|Person|Person_Internal|Matter|CHIP|AutomationBuilders)
- ___37-[HMCameraClip attributeDescriptions]_block_invoke
- ___48-[HMMediaGroupsController attributeDescriptions]_block_invoke
- ___67-[HMHome(Climate) fetchRoomsSupportingLocalPresenceWithCompletion:]_block_invoke_2
- ___68-[HMMediaGroupsController createGroupResponseHandlerWithCompletion:]_block_invoke
- ___74-[HMMediaGroupsController removeGroupResponseHandlerWithGroup:completion:]_block_invoke
- ___block_descriptor_56_e8_32s40bs48w_e34_v24?0"NSError"8"NSDictionary"16lw48l8s40l8s32l8
- ___block_descriptor_56_e8_32s40bs_e5_v8?0ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48bs_e20_v24?0"NSUUID"8^B16ls32l8s48l8s40l8
- ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
- ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
- ___block_descriptor_72_e8_32s40s48s56s64bs_e34_v24?0"NSError"8"NSDictionary"16ls32l8s64l8s40l8s48l8s56l8
- ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s64l8s48l8s56l8
- ___swift_allocate_boxed_opaque_existential_1Tm
- _associated conformance So18HMClientConnectionC7HomeKitE10DeviceInfoV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
- _associated conformance So18HMClientConnectionC7HomeKitE10DeviceInfoV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0G3KeyACs23CustomStringConvertible
- _associated conformance So18HMClientConnectionC7HomeKitE10DeviceInfoV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0G3KeyACs28CustomDebugStringConvertible
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO014StopPublishingF7MessageVAC19HMFMessagePrototypeO07RequestI0AC0L7PayloadAiJP_AI0M0
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO014StopPublishingF7MessageVAC19HMFMessagePrototypeO07RequestI0AC15ResponsePayloadAiJP_AI0N0
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs23CustomStringConvertible
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs28CustomDebugStringConvertible
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageVAC19HMFMessagePrototypeO07RequestH0AC0K7PayloadAiJP_AI0L0
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageVAC19HMFMessagePrototypeO07RequestH0AC15ResponsePayloadAiJP_AI0M0
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs23CustomStringConvertible
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs28CustomDebugStringConvertible
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV06DeviceF0V10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV06DeviceF0V10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0L3KeyACs23CustomStringConvertible
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV06DeviceF0V10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0L3KeyACs28CustomDebugStringConvertible
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOSHACSQ
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs23CustomStringConvertible
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLOs0K3KeyACs28CustomDebugStringConvertible
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageVAC19HMFMessagePrototypeO07RequestH0AC0K7PayloadAiJP_AI0L0
- _associated conformance So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageVAC19HMFMessagePrototypeO07RequestH0AC15ResponsePayloadAiJP_AI0M0
- _associated conformance So18HMClientConnectionC7HomeKitE14DeviceIdentityVSHACSQ
- _kAddMediaSystemHintsRequest
- _kRemoveMediaSystemHintsRequest
- _symbolic Say_____G So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV06DeviceF0V
- _symbolic _____ So18HMClientConnectionC7HomeKitE10DeviceInfoV
- _symbolic _____ So18HMClientConnectionC7HomeKitE10DeviceInfoV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO
- _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO014StopPublishingF7MessageV
- _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV
- _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV14RequestPayloadV
- _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV
- _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV14RequestPayloadV
- _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV
- _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV06DeviceF0V
- _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV06DeviceF0V10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____ So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____ So18HMClientConnectionC7HomeKitE14DeviceIdentityV
- _symbolic _____ So18HMClientConnectionC7HomeKitE17RemoteContextInfoV
- _symbolic ___________t So18HMClientConnectionC7HomeKitE14DeviceIdentityV AbCE17RemoteContextInfoV
- _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE10DeviceInfoV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishI7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveI7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveI7MessageV15ResponsePayloadV06DeviceI0V10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveI7MessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE10DeviceInfoV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishI7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveI7MessageV14RequestPayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveI7MessageV15ResponsePayloadV06DeviceI0V10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveI7MessageV15ResponsePayloadV10CodingKeys33_8002F1C780D7280AF241490993F54F92LLO
- _symbolic _____y__________G s18_DictionaryStorageC So18HMClientConnectionC7HomeKitE14DeviceIdentityV 10Foundation4DataV
- _symbolic _____y__________G s18_DictionaryStorageC So18HMClientConnectionC7HomeKitE14DeviceIdentityV AdEE17RemoteContextInfoV
- _symbolic _____y___________tG s23_ContiguousArrayStorageC So18HMClientConnectionC7HomeKitE14DeviceIdentityV AdEE17RemoteContextInfoV
- _type_layout_string So18HMClientConnectionC7HomeKitE13RemoteContextO07PublishF7MessageV14RequestPayloadV
- _type_layout_string So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV14RequestPayloadV
- _type_layout_string So18HMClientConnectionC7HomeKitE13RemoteContextO08RetrieveF7MessageV15ResponsePayloadV
CStrings:
+ ", Access Mode Change: %@"
+ ", Access Modes: %@"
+ ", Accessory Being Replaced: %@"
+ ", Accessory Category: %@"
+ ", Accessory IDs: %@"
+ ", Accessory Name: %@"
+ ", Accessory Server Identifier: %@"
+ ", Accessory UUID: %@"
+ ", Activity Zones Included: %@"
+ ", Activity Zones: %@"
+ ", Add And Setup: %@"
+ ", Add Request Identifier: %@"
+ ", Added Accessory UUIDs: %@"
+ ", Administrator: %@"
+ ", Announce Access Allowed: %@"
+ ", App Bundle ID: %@"
+ ", App Bundle URL: %@"
+ ", App Identifier: %@"
+ ", App Store ID: %@"
+ ", Aspect Ratio: %@"
+ ", Audio: %@"
+ ", BLE Proximity Pairing: %@"
+ ", Bounding Box: %@"
+ ", Bulletins: %@"
+ ", Bundle ID: %@"
+ ", Byte Length: %@"
+ ", Byte Offset: %@"
+ ", CHIP Setup Payload: %@"
+ ", Cache Policy: %@"
+ ", Camera Profile UUID: %@"
+ ", Cameras Access Level: %@"
+ ", Can Add Wallet Key Error Code: %@"
+ ", Can Add Wallet Key: %@"
+ ", Cancellation Reason: %@"
+ ", Capabilities: %@"
+ ", Capture Date: %@"
+ ", Category Number: %@"
+ ", Category: %@"
+ ", Certification Status: %@"
+ ", Clip UUID: %@"
+ ", Codecs: %@"
+ ", Color: %@"
+ ", Commissioned Over NFC Without Power: %@"
+ ", Communication Protocol: %@"
+ ", Complete: %@"
+ ", Condition: %@"
+ ", Confidence level: %@"
+ ", Confidence: %@"
+ ", Controllable: %@"
+ ", Custom URL: %@"
+ ", Data Representation Length: %@"
+ ", Date Components: %@"
+ ", Date Created: %@"
+ ", Date Interval: %@"
+ ", Date: %@"
+ ", Delegate Queue: %@"
+ ", Device Identifier: %@"
+ ", Device Type ID: %@"
+ ", Device Type: %@"
+ ", Device: %@"
+ ", Discretionary: %@"
+ ", Discriminator: %@"
+ ", Do Network Scan: %@"
+ ", DoesHomeHasCameras: %@"
+ ", Duration: %@"
+ ", Ecosystem: %@"
+ ", Enabled: %@"
+ ", Endpoint ID: %@"
+ ", Error: %@"
+ ", Events: %@"
+ ", Expiration Date: %@"
+ ", Express Enabled: %@"
+ ", Express Enablement Conflicting Pass Description: %@"
+ ", External Person UUID: %@"
+ ", Face Bounding Box: %@"
+ ", Face Classification Enabled: %@"
+ ", Face Classification: %@"
+ ", Face Crop: %@"
+ ", Features: %@"
+ ", File URL: %@"
+ ", Firmware Version: %@"
+ ", Frames: %@"
+ ", HLS Playlist Byte Count: %@"
+ ", Has Ownership Token: %@"
+ ", Has Setup Code: %@"
+ ", Has Short Discriminator: %@"
+ ", Home ID: %@"
+ ", Home Name: %@"
+ ", Home UUID: %@"
+ ", Home Unique Identifier: %@"
+ ", Home: %@"
+ ", HomeUUID: %@"
+ ", ID: %@"
+ ", IDS Identifier: %@"
+ ", IDS Token: %@"
+ ", IDSTopic: %@"
+ ", Identifier: %@"
+ ", Importing From Photo Library Enabled: %@"
+ ", Inactive Updating Level: %@"
+ ", Index: %@"
+ ", Installation Guide URL: %@"
+ ", Instance ID: %@"
+ ", Inviter Name: %@"
+ ", Inviter UserID: %@"
+ ", Is Apple Vendor: %@"
+ ", Is Current Device: %@"
+ ", Is Paired: %@"
+ ", Is RG: %@"
+ ", Is System Commissioner: %@"
+ ", Is Thread Accessory: %@"
+ ", KTSC: %@"
+ ", Label: %@"
+ ", Location Authorization: %@"
+ ", Mach Service Name: %@"
+ ", Manually Disabled: %@"
+ ", Manufacturer Name: %@"
+ ", Manufacturer: %@"
+ ", Marketing Name: %@"
+ ", Matter Bulletins: %@"
+ ", Matter NodeID: %@"
+ ", Matter Onboarding URL: %@"
+ ", Matter Payload: %@"
+ ", Matter Setup Payload Entitled: %@"
+ ", Maximum Quality: %@"
+ ", MessageName: %@"
+ ", Minimum Required: %@"
+ ", Model: %@"
+ ", NFC Prox Pairing: %@"
+ ", Name: %@"
+ ", Natural Lighting Enabled: %@"
+ ", Network Commissioning State: %@"
+ ", NodeID: %@"
+ ", Notification Settings: %@"
+ ", Options: %@"
+ ", Owned: %@"
+ ", Payload: %@"
+ ", PeerDestination: %@"
+ ", Person Familiarity: %@"
+ ", Person Manager UUID: %@"
+ ", Person UUID: %@"
+ ", Person: %@"
+ ", Presence: %@"
+ ", Process ID: %@"
+ ", Process Name: %@"
+ ", Product Data Alternates: %@"
+ ", Product Data: %@"
+ ", Product Group: %@"
+ ", Product ID: %@"
+ ", Product Info: %@"
+ ", Product Number: %@"
+ ", Quality: %@"
+ ", Rapport IRK: %@"
+ ", Reachability Event: %@"
+ ", Reachable: %@"
+ ", Reason: %@"
+ ", Recording Triggers: %@"
+ ", Region of Interest: %@"
+ ", Remote Access Allowed: %@"
+ ", Required Entitlements: %@"
+ ", Required HTTP Headers: %@"
+ ", Requires Custom Flow: %@"
+ ", Requires Home Data Access: %@"
+ ", Requires Setup Payload URL: %@"
+ ", Resolutions: %@"
+ ", Restricted Guest: %@"
+ ", Restricted guest access settings: %@"
+ ", Root Public Key (HASH): %@"
+ ", Root Public Key: %@"
+ ", SPI Entitled: %@"
+ ", Serial Number: %@"
+ ", Settings: %@"
+ ", Setup Accessory Payload Entitled: %@"
+ ", Setup Accessory Payload: %@"
+ ", Setup Auth Token UUID: %@"
+ ", Setup Auth Token: %@"
+ ", Setup Code: %@"
+ ", Setup ID: %@"
+ ", Setup Initiated By Other Matter Ecosystem: %@"
+ ", Setup Payload String: %@"
+ ", Setup Payload URL: %@"
+ ", Sharing Face Classifications Enabled: %@"
+ ", Should Connect: %@"
+ ", Significant Event Reason: %@"
+ ", Significant Events: %@"
+ ", Size: %@"
+ ", Slot Identifier: %@"
+ ", Smart Bulletin Condition: %@"
+ ", Smart Bulletin: %@"
+ ", Source: %@"
+ ", Start Date: %@"
+ ", Status: %@"
+ ", Store ID: %@"
+ ", Suggested Accessory Name: %@"
+ ", Suggested Room UUID: %@"
+ ", Suggested Room Unique Identifier: %@"
+ ", Supported Features: %@"
+ ", Supports BTLE: %@"
+ ", Supports CHIP: %@"
+ ", Supports HH2: %@"
+ ", Supports IP: %@"
+ ", Supports Resident Selection: %@"
+ ", Supports WAC: %@"
+ ", System Commissioner Pairing UUID: %@"
+ ", Take Ownership: %@"
+ ", Target Fragment Duration: %@"
+ ", Thread Identifier: %@"
+ ", Time Offset: %@"
+ ", Time offset within clip: %@"
+ ", TransportRestriction: %@"
+ ", TransportTypes: %@"
+ ", Type: %@"
+ ", URL: %@"
+ ", UUID: %@"
+ ", UWB Enabled: %@"
+ ", Unassociated Face Crop UUID: %@"
+ ", Unique ID: %@"
+ ", User ID: %@"
+ ", UserRestriction: %@"
+ ", UserUUID: %@"
+ ", Vendor ID: %@"
+ ", Vendor: %@"
+ ", Video Segments Count: %@"
+ ", Video: %@"
+ ", Wallet Key: %@"
+ ", accessCodeValue: %@"
+ ", accessory: %@"
+ ", accessoryAccessCodeValue: %@"
+ ", accessoryAccessCodeValues: %@"
+ ", accessoryUUID: %@"
+ ", accessoryUniqueIdentifier: %@"
+ ", activeIdentifier: %@"
+ ", airPlayEnabled: %@"
+ ", allowHeySiri: %@"
+ ", allowedAccessories: %@"
+ ", allowedCharacterSets: %@"
+ ", announceEnabled: %@"
+ ", associatedGroupIdentifier: %@"
+ ", audioDestinationIdentifier: %@"
+ ", audioDestinationName: %@"
+ ", audioDestinationType: %@"
+ ", audioGroupIdentifier: %@"
+ ", availableDestinationIdentifiers: %@"
+ ", boolValue: %@"
+ ", capability: %@"
+ ", category: %@"
+ ", consentVersion: %@"
+ ", constraints: %@"
+ ", dateRemoved: %@"
+ ", daysOfTheWeek: %@"
+ ", destinationControllersData: %@"
+ ", destinationIdentifier: %@"
+ ", destinationIdentifiers: %@"
+ ", destinations: %@"
+ ", deviceNotificationMode: %@"
+ ", documentationMetadata: %@"
+ ", doorbellChimeEnabled: %@"
+ ", downloadSize: %@"
+ ", endDate: %@"
+ ", endTime: %@"
+ ", error: %@"
+ ", estimatedTimeRemaining: %@"
+ ", explicitContentAllowed: %@"
+ ", failureInformation: %@"
+ ", failureType: %@"
+ ", failureTypes: %@"
+ ", groupIdentifier: %@"
+ ", groups: %@"
+ ", hasRestrictions: %@"
+ ", homeIdentifier: %@"
+ ", humanReadableUpdateName: %@"
+ ", identifier: %@"
+ ", inputLanguageCode: %@"
+ ", integerValue: %@"
+ ", isDefaultName: %@"
+ ", keyPath: %@"
+ ", keyPaths: %@"
+ ", labelIdentifier: %@"
+ ", languageValue: %@"
+ ", languageValues: %@"
+ ", leftDestinationIdentifier: %@"
+ ", legacyIdentifier: %@"
+ ", lightWhenUsingSiriEnabled: %@"
+ ", manuallyDisabled: %@"
+ ", manufacturer: %@"
+ ", maxValue: %@"
+ ", maximumAllowedAccessCodes: %@"
+ ", maximumLength: %@"
+ ", messageTargetUUID: %@"
+ ", minValue: %@"
+ ", minimumLength: %@"
+ ", multifunctionButton: %@"
+ ", name: %@"
+ ", needsOnboarding: %@"
+ ", onboardingResult: %@"
+ ", onboardingSelections: %@"
+ ", operationType: %@"
+ ", outputVoiceGenderCode: %@"
+ ", outputVoiceLanguageCode: %@"
+ ", parentIdentifier: %@"
+ ", percentageComplete: %@"
+ ", personLinks: %@"
+ ", predictionGroupType: %@"
+ ", predictionScore: %@"
+ ", predictionTargetUUID: %@"
+ ", predictionType: %@"
+ ", privacyPolicyURL: %@"
+ ", product Group: %@"
+ ", product Number: %@"
+ ", productID: %@"
+ ", rampFeatureEnabledOnServer: %@"
+ ", reason: %@"
+ ", removedGroupIdentifiers: %@"
+ ", removedUserInfo: %@"
+ ", rgSchedule: %@"
+ ", rightDestinationIdentifier: %@"
+ ", room: %@"
+ ", rootPublicKey Hash: %@"
+ ", rules: %@"
+ ", schedule: %@"
+ ", sessionHubIdentifier: %@"
+ ", sessionState: %@"
+ ", setting: %@"
+ ", settingValue: %@"
+ ", settings: %@"
+ ", shareSiriAnalyticsEnabled: %@"
+ ", simpleLabel: %@"
+ ", siriEnabled: %@"
+ ", siriEndpointVersion: %@"
+ ", siriEngineVersion: %@"
+ ", snapshotPath: %@"
+ ", stagedControllersData: %@"
+ ", stagedDestinations: %@"
+ ", stagedGroups: %@"
+ ", startDate: %@"
+ ", startTime: %@"
+ ", state: %@"
+ ", status: %@"
+ ", stringListValue: %@"
+ ", stringValue: %@"
+ ", supportOptions: %@"
+ ", supportedOptions: %@"
+ ", targetGroupUUID: %@"
+ ", targetProtectionMode: %@"
+ ", targetServiceUUID: %@"
+ ", type: %@"
+ ", uniqueIdentifier: %@"
+ ", updateOptions: %@"
+ ", updatedAccessCodeValue: %@"
+ ", uploadDestination: %@"
+ ", uploadType: %@"
+ ", urlParameters: %@"
+ ", user: %@"
+ ", userID: %@"
+ ", userInformation: %@"
+ ", userInformationValue: %@"
+ ", userUUID: %@"
+ ", valueStepSize: %@"
+ ", vendorID: %@"
+ ", version: %@"
+ ", voiceName: %@"
+ ", weekDayRules: %@"
+ ", yearDayRules: %@"
+ "222AA6C0-21DB-4EE6-8E62-019974477350"
+ "5CC65005-CE51-4781-9F78-3429557B6FD4"
+ "<ADC %@ d:%@ o:%@>"
+ "<HTS %@ n:%@ d:%@ t:%@>"
+ "<MD %@ o:%@>"
+ "<MG %@ n:%@>"
+ "<MG %@>"
+ "<MSY %@ n:%@ L:%@ R:%@>"
+ "A sequence of smart home notification events to summarize"
+ "A smart home notification event"
+ "Configuring home: %{sensitive}@ with context: %@ location services enabled:%@"
+ "Creating HMSoftwareUpdateProgressV2 for accessory: %@, progress: %@"
+ "EE041E8C-28B9-4250-B2E2-0C032BDDDF1A"
+ "Event trigger evaluation condition evaluated to false"
+ "HMMediaGroupStageRequestPayloadMetricTypeKey"
+ "Home did not sync staged data before timeout, firing staging results failure metric"
+ "Home synced staged data in %ld ms, firing staging results metric"
+ "Notification event category"
+ "Ordered list of notification events, earliest first"
+ "Pair-setup failed because Core Data not ready for ECDSA"
+ "Rewrite the following events as one short summary in past tense.\n\nInput:"
+ "Rewrite the following events as one short summary in past tense.\n\nInput: "
+ "Start handling home location status update notification in home %{sensitive}@"
+ "Summarizing (typed): asset=%{public}s, useCase=%{public}s"
+ "The category of this event"
+ "The human-readable event text as it appears in the notification"
+ "Unexpected rawValue \""
+ "Updating home location from %{sensitive}@ to %{sensitive}@"
+ "[%{public}@] Configuring home: %{sensitive}@ with context: %@ location services enabled:%@"
+ "[%{public}@] Creating HMSoftwareUpdateProgressV2 for accessory: %@, progress: %@"
+ "[%{public}@] Home did not sync staged data before timeout, firing staging results failure metric"
+ "[%{public}@] Home synced staged data in %ld ms, firing staging results metric"
+ "[%{public}@] Start handling home location status update notification in home %{sensitive}@"
+ "[%{public}@] Updating home location from %{sensitive}@ to %{sensitive}@"
+ "[%{public}@] network.router: Received AccessoryNetworkProtectionGroupRemovedNotification"
+ "accessoryAttributed"
+ "accessoryState"
+ "cameraDetection"
+ "cameraMode"
+ "caption"
+ "climate"
+ "com.apple.homekit.MediaGroupCreated"
+ "com.apple.homekit.MediaGroupRemoved"
+ "com.apple.homekit.MediaGroupStagingResults"
+ "fieldData"
+ "geofenceArrival"
+ "geofenceDeparture"
+ "matterOnboardingURL"
+ "mediaGroupType"
+ "network.router: Received AccessoryNetworkProtectionGroupRemovedNotification"
+ "parentDeviceType"
+ "supports1299912b90f3"
+ "supportsAudioDestinationHomePodGeneration2HomeTheater"
+ "supportsAudioDestinationHomeTheater"
+ "supportsAudioDestinationMediaSystem"
+ "supportsAudioDestinationMediaSystemHomePodGeneration2"
+ "supportsAudioDestinationMediaSystemMini"
+ "supportsAudioDestinationMiniHomeTheater"
+ "supportsHomeTheaterSourceHomePodGeneration2"
+ "supportsHomeTheaterSourceHomePodMini"
+ "supportsHomeTheaterSourceOriginalHomePod"
+ "supportsd711b2f2f198"
+ "supportseac3b4015a2e"
+ "timespan"
+ "userDefinedDeviceType"
- "Access Mode Change"
- "Access Modes"
- "Accessory Being Replaced"
- "Accessory Category"
- "Accessory IDs"
- "Accessory Name"
- "Accessory Server Identifier"
- "Accessory UUID"
- "Activity Zones"
- "Activity Zones Included"
- "Add And Setup"
- "Add Request Identifier"
- "Added Accessory UUIDs"
- "Announce Access Allowed"
- "App Bundle ID"
- "App Bundle URL"
- "App Identifier"
- "App Store ID"
- "Aspect Ratio"
- "Audio"
- "BLE Proximity Pairing"
- "Bounding Box"
- "Bulletins:"
- "Bundle ID"
- "Byte Length"
- "Byte Offset"
- "CHIP Setup Payload"
- "Cache Policy"
- "Camera Profile UUID"
- "Cameras Access Level"
- "Can Add Wallet Key"
- "Can Add Wallet Key Error Code"
- "Cancellation Reason"
- "Capabilities"
- "Capture Date"
- "Category Number"
- "Certification Status"
- "Clip UUID"
- "Codecs"
- "Color"
- "Commissioned Over NFC Without Power"
- "Communication Protocol"
- "Condition"
- "Confidence"
- "Confidence level"
- "Configuring home: %@ with context: %@ location services enabled:%@"
- "Controllable"
- "Creating HMSoftwareUpdateV2 for accessory: %@, progress: %@"
- "Custom URL"
- "Data Representation Length"
- "Date"
- "Date Components"
- "Date Created"
- "Date Interval"
- "Delegate Queue"
- "Device"
- "Device Identifier"
- "Device Type"
- "Device Type ID"
- "Discretionary"
- "Discriminator"
- "Do Network Scan"
- "DoesHomeHasCameras"
- "Duration"
- "Ecosystem"
- "Endpoint ID"
- "Event trigger evaluation condition evalutated to false"
- "Events"
- "Expiration Date"
- "Express Enabled"
- "Express Enablement Conflicting Pass Description"
- "External Person UUID"
- "Face Bounding Box"
- "Face Classification"
- "Face Classification Enabled"
- "Face Crop"
- "Failed to get media group identifier from response payload: %@"
- "Features"
- "File URL"
- "Firmware Version"
- "Frames"
- "HLS Playlist Byte Count"
- "Has Ownership Token"
- "Has Setup Code"
- "Has Short Discriminator"
- "Home ID"
- "Home Name"
- "Home UUID"
- "Home Unique Identifier"
- "HomeUUID"
- "ID"
- "IDS Identifier"
- "IDS Token"
- "IDSTopic"
- "Identifier"
- "Importing From Photo Library Enabled"
- "Inactive Updating Level"
- "Index"
- "Installation Guide URL"
- "Instance ID"
- "Inviter Name"
- "Inviter UserID"
- "Is Apple Vendor"
- "Is Current Device"
- "Is Paired"
- "Is RG"
- "Is System Commissioner"
- "Is Thread Accessory"
- "KTSC"
- "Location Authorization"
- "Mach Service Name"
- "Manually Disabled"
- "Manufacturer Name"
- "Marketing Name"
- "Matter Bulletins"
- "Matter NodeID"
- "Matter Payload"
- "Matter Setup Payload Entitled"
- "Maximum Quality"
- "MessageName"
- "Minimum Required"
- "NFC Prox Pairing"
- "Natural Lighting Enabled"
- "Network Commissioning State"
- "NodeID"
- "Notification Settings"
- "Options"
- "Owned"
- "Payload"
- "PeerDestination"
- "Person Familiarity"
- "Person Manager UUID"
- "Person UUID"
- "Presence"
- "Process ID"
- "Process Name"
- "Product Data"
- "Product Data Alternates"
- "Product Group"
- "Product ID"
- "Product Info"
- "Product Number"
- "Quality"
- "Rapport IRK"
- "Reachability Event"
- "Reachable"
- "Reason"
- "Recording Triggers"
- "Region of Interest"
- "Remote Access Allowed"
- "Required Entitlements"
- "Required HTTP Headers"
- "Requires Custom Flow"
- "Requires Home Data Access"
- "Requires Setup Payload URL"
- "Resolutions"
- "Restricted guest access settings"
- "Root Public Key"
- "Root Public Key (HASH)"
- "SPI Entitled"
- "Serial Number"
- "Setup Accessory Payload"
- "Setup Accessory Payload Entitled"
- "Setup Auth Token"
- "Setup Auth Token UUID"
- "Setup Code"
- "Setup ID"
- "Setup Initiated By Other Matter Ecosystem"
- "Setup Payload String"
- "Setup Payload URL"
- "Sharing Face Classifications Enabled"
- "Should Connect"
- "Significant Event Reason"
- "Significant Events"
- "Size"
- "Slot Identifier"
- "Smart Bulletin"
- "Smart Bulletin Condition"
- "Source"
- "Start Date"
- "Start handling home location status update notification in home %@"
- "Status"
- "Store ID"
- "Suggested Accessory Name"
- "Suggested Room UUID"
- "Suggested Room Unique Identifier"
- "Supported Features"
- "Supports BTLE"
- "Supports CHIP"
- "Supports HH2"
- "Supports IP"
- "Supports Resident Selection"
- "Supports WAC"
- "System Commissioner Pairing UUID"
- "Take Ownership"
- "Target Fragment Duration"
- "Thread Identifier"
- "Time Offset"
- "Time offset within clip"
- "TransportRestriction"
- "TransportTypes"
- "Type"
- "URL"
- "UWB Enabled"
- "Unassociated Face Crop UUID"
- "Unique ID"
- "Updating home location from %@ to %@"
- "User ID"
- "UserRestriction"
- "UserUUID"
- "Vendor"
- "Vendor ID"
- "Video"
- "Video Segments Count"
- "Wallet Key"
- "[%{public}@] Configuring home: %@ with context: %@ location services enabled:%@"
- "[%{public}@] Creating HMSoftwareUpdateV2 for accessory: %@, progress: %@"
- "[%{public}@] Failed to get media group identifier from response payload: %@"
- "[%{public}@] Start handling home location status update notification in home %@"
- "[%{public}@] Updating home location from %@ to %@"
- "accessCodeValue"
- "accessoryAccessCodeValue"
- "accessoryAccessCodeValues"
- "activeIdentifier"
- "airPlayEnabled"
- "allowHeySiri"
- "allowedAccessories"
- "allowedCharacterSets"
- "announceEnabled"
- "audioDestinationName"
- "boolValue"
- "consentVersion"
- "constraints"
- "dateRemoved"
- "daysOfTheWeek"
- "deviceNotificationMode"
- "documentationMetadata"
- "doorbellChimeEnabled"
- "endDate"
- "endTime"
- "explicitContentAllowed"
- "failureTypes"
- "groupIdentifier"
- "hasRestrictions"
- "hm.remoteContext.publishContext"
- "hm.remoteContext.retrieveContext"
- "hm.remoteContext.stopPublishingContext"
- "integerValue"
- "labelIdentifier"
- "languageValues"
- "legacyIdentifier"
- "lightWhenUsingSiriEnabled"
- "manuallyDisabled"
- "maximumAllowedAccessCodes"
- "maximumLength"
- "minimumLength"
- "multifunctionButton"
- "needsOnboarding"
- "onboardingResult"
- "onboardingSelections"
- "operationType"
- "predictionGroupType"
- "predictionScore"
- "predictionTargetUUID"
- "privacyPolicyURL"
- "product Group"
- "product Number"
- "productID"
- "rampFeatureEnabledOnServer"
- "removedUserInfo"
- "rgSchedule"
- "rootPublicKey Hash"
- "rules"
- "schedule"
- "sessionHubIdentifier"
- "sessionState"
- "shareSiriAnalyticsEnabled"
- "simpleLabel"
- "siriEnabled"
- "siriEndpointVersion"
- "siriEngineVersion"
- "snapshotPath"
- "stagedControllersData"
- "stagedDestinations"
- "stagedGroups"
- "startDate"
- "startTime"
- "supportOptions"
- "targetGroupUUID"
- "targetProtectionMode"
- "targetServiceUUID"
- "updateOptions"
- "updatedAccessCodeValue"
- "uploadDestination"
- "uploadType"
- "urlParameters"
- "userInformation"
- "userInformationValue"
- "valueStepSize"
- "vendorID"
- "weekDayRules"
- "yearDayRules"
```
