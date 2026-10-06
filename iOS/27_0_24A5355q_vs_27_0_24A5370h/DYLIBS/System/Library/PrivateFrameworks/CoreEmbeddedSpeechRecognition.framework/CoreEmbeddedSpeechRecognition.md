## CoreEmbeddedSpeechRecognition

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/CoreEmbeddedSpeechRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f5a18` | `0x320e14` | **`+0x2b3fc`** |
| `__AUTH_CONST.__const` | `0x1f390` | `0x22498` | **`+0x3108`** |
| `__TEXT.__swift5_capture` | `0xb358` | `0xc5a0` | **`+0x1248`** |
| `__TEXT.__cstring` | `0xcf47` | `0xdb6e` | **`+0xc27`** |
| `__TEXT.__const` | `0x7668` | `0x80e8` | **`+0xa80`** |
| `__TEXT.__oslogstring` | `0xc162` | `0xcac2` | **`+0x960`** |
| `__AUTH_CONST.__objc_const` | `0xaaf0` | `0xb2f8` | **`+0x808`** |
| `__DATA.__bss` | `0x6e70` | `0x7510` | **`+0x6a0`** |
| `__AUTH_CONST.__cfstring` | `0x47e0` | `0x4e40` | **`+0x660`** |
| `__TEXT.__swift5_typeref` | `0x3c54` | `0x4248` | **`+0x5f4`** |
| `__TEXT.__swift5_reflstr` | `0x20f3` | `0x2673` | **`+0x580`** |
| `__DATA.__data` | `0x2b40` | `0x3078` | **`+0x538`** |
| `__TEXT.__eh_frame` | `0x51fc` | `0x56dc` | **`+0x4e0`** |
| `__TEXT.__unwind_info` | `0x4160` | `0x45a8` | **`+0x448`** |
| `__TEXT.__swift5_fieldmd` | `0x209c` | `0x24d4` | **`+0x438`** |
| `__TEXT.__constg_swiftt` | `0x21d8` | `0x2590` | **`+0x3b8`** |
| `__AUTH.__data` | `0x14a8` | `0x1840` | **`+0x398`** |
| `__DATA_CONST.__objc_selrefs` | `0x33c8` | `0x35f8` | **`+0x230`** |
| `__DATA_CONST.__got` | `0x1908` | `0x1a78` | **`+0x170`** |
| `__TEXT.__objc_methlist` | `0x4858` | `0x49c8` | **`+0x170`** |
| `__DATA_DIRTY.__objc_data` | `0x1668` | `0x17d0` | **`+0x168`** |
| `__AUTH_CONST.__auth_got` | `0x21a8` | `0x22d8` | **`+0x130`** |
| `__AUTH.__objc_data` | `0x12c8` | `0x13e0` | **`+0x118`** |
| `__DATA_DIRTY.__data` | `0x2360` | `0x2268` | **`-0xf8`** |
| `__DATA_CONST.__const` | `0x18f8` | `0x19a8` | **`+0xb0`** |
| `__DATA.__common` | `0x218` | `0x2b0` | **`+0x98`** |
| `__TEXT.__swift5_assocty` | `0x480` | `0x510` | **`+0x90`** |
| `__AUTH_CONST.__objc_intobj` | `0xd68` | `0xdb0` | **`+0x48`** |
| `__TEXT.__swift5_proto` | `0x474` | `0x4b4` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0xc10` | `0xbdc` | **`-0x34`** |
| `__TEXT.__swift5_types` | `0x24c` | `0x278` | **`+0x2c`** |
| `__DATA_CONST.__objc_classlist` | `0x3f0` | `0x418` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x6c0` | `0x6dc` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x2bc` | `0x2d4` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x21c` | `0x230` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x24c` | `0x260` | **`+0x14`** |
| `__DATA_CONST.__objc_arraydata` | `0x440` | `0x450` | **`+0x10`** |
| `__DATA_DIRTY.__common` | `0xe0` | `0xd0` | **`-0x10`** |
| `__TEXT.__swift5_protos` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1f8` | `0x200` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x500` | `0x504` | **`+0x4`** |

### Other Changes

```diff

-3600.64.114.1.5
+3600.70.8.0.0

+  - /System/Library/Frameworks/AppIntents.framework/AppIntents

+  - /System/Library/PrivateFrameworks/LinkMetadata.framework/LinkMetadata
+  - /System/Library/PrivateFrameworks/LinkServices.framework/LinkServices

+  - /usr/lib/swift/libswiftCoreAudio_Private.dylib

+  - /usr/lib/swift/libswift_StringProcessing.dylib

-  Functions: 9603
-  Symbols:   4537
-  CStrings:  2245
+  Functions: 10354
+  Symbols:   4720
+  CStrings:  2399
Symbols:
+ +[CESRBackgroundSystemTask submitOnDemandCascadeSetChangeProcessingBGST]
+ +[CESRBackgroundSystemTask submitOnDemandSpeechProfileResetAndRebuildBGST]
+ +[CESREntityCleanupHandler initialize]
+ +[CESREntityCleanupHandler sanitizeText:]
+ +[CESRSpeechProfileDispatcher _triggerForNotification:]
+ +[CESRUtilities isInteractionOnlyRankingEnabled]
+ -[CESREuclidProfileInsertion initWithField:cascadeItemType:sharedItemIdentifier:fieldType:assistantSchemaDomain:assistantSchemaType:assistantSchemaProperty:extractedType:]
+ -[CESRSpeechProfileAnalyticsLog .cxx_destruct]
+ -[CESRSpeechProfileAnalyticsLog _computeAggregateFromEntries:]
+ -[CESRSpeechProfileAnalyticsLog _readFile]
+ -[CESRSpeechProfileAnalyticsLog _writeFile:]
+ -[CESRSpeechProfileAnalyticsLog appendEntryWithTrigger:reason:locale:options:personaId:categories:totalItems:updateTimestampMicros:profileSizeBeforeBytes:profileSizeAfterBytes:durationMs:outcome:errorDescription:]
+ -[CESRSpeechProfileAnalyticsLog fileURL]
+ -[CESRSpeechProfileAnalyticsLog initWithFileURL:]
+ -[CESRSpeechProfileDispatcher _registerTrialExperimentUpdateHandler]
+ -[CESRSpeechProfileDispatcher handlePendingSetChangesWithCompletion:]
+ -[CESRSpeechProfileDispatcher runSpeechProfileResetAndRebuildWithCompletion:]
+ -[CESRSpeechProfileInstance lastUpdateCompletionTime]
+ -[CESRSpeechProfileSelfHelper logASRSpeechProfileUpdateFailedWithError:]
+ -[CESRSpeechProfileSite analyticsLog]
+ -[CESRSpeechProfileSiteManager _maintainSpeechProfilesAtAllSites:trigger:shouldDefer:]
+ -[CESRSpeechProfileSiteManager _maintainSpeechProfilesForSiteAtURL:maintenanceLevel:trigger:shouldDefer:]
+ -[CESRSpeechProfileSiteManager _resetAndRebuildAllSites]
+ -[CESRSpeechProfileSiteManager _userSpecificSpeechProfileSiteDirectories]
+ -[CESRSpeechProfileSiteManager performSpeechProfileMaintenance:trigger:shouldDefer:]
+ -[CESRSpeechProfileSiteManager resetAndRebuildAllSpeechProfileSites]
+ -[CESRSpeechProfileSiteWriter _fullRebuildForInvalidProfileInstance:locale:options:trigger:shouldDefer:]
+ -[CESRSpeechProfileSiteWriter _profileSizeForInstance:]
+ -[CESRSpeechProfileSiteWriter _updateProfileInstance:categoryGroup:trigger:reason:shouldDefer:]
+ -[CESRSpeechProfileSiteWriter _updateRequiredProfileInstancesWithSets:trigger:shouldDefer:]
+ -[CESRSpeechProfileSiteWriter _verifyAllSpeechProfileInstances:trigger:shouldDefer:]
+ -[CESRSpeechProfileSiteWriter _verifyProfileInstance:trigger:shouldDefer:]
+ -[CESRSpeechProfileSiteWriter verifyAllSpeechProfileInstances:trigger:shouldDefer:]
+ -[CESRSpeechProfileUpdater detectCategoriesToRebuild:allCategoriesAreDeferredResume:error:]
+ -[CESRSpeechProfileUpdater rebuildCategoryGroup:withSets:version:totalItems:error:]
+ GCC_except_table1003
+ GCC_except_table1008
+ GCC_except_table1124
+ GCC_except_table1188
+ GCC_except_table1189
+ GCC_except_table1190
+ GCC_except_table1191
+ GCC_except_table1192
+ GCC_except_table1193
+ GCC_except_table1198
+ GCC_except_table1228
+ GCC_except_table1355
+ GCC_except_table1361
+ GCC_except_table1366
+ GCC_except_table1370
+ GCC_except_table1414
+ GCC_except_table1422
+ GCC_except_table1427
+ GCC_except_table1431
+ GCC_except_table158
+ GCC_except_table164
+ GCC_except_table171
+ GCC_except_table178
+ GCC_except_table188
+ GCC_except_table247
+ GCC_except_table258
+ GCC_except_table293
+ GCC_except_table308
+ GCC_except_table345
+ GCC_except_table369
+ GCC_except_table372
+ GCC_except_table433
+ GCC_except_table454
+ GCC_except_table602
+ GCC_except_table614
+ GCC_except_table617
+ GCC_except_table620
+ GCC_except_table623
+ GCC_except_table626
+ GCC_except_table629
+ GCC_except_table632
+ GCC_except_table718
+ GCC_except_table72
+ GCC_except_table742
+ GCC_except_table79
+ GCC_except_table795
+ _CESRSpeechProfileAnalyticsLogFilename
+ _CESRSpeechProfileUpdateOutcomeDeferred
+ _CESRSpeechProfileUpdateOutcomeFailure
+ _CESRSpeechProfileUpdateOutcomeSuccess
+ _CESRSpeechProfileUpdateReasonDeferredResume
+ _CESRSpeechProfileUpdateReasonOptionsChanged
+ _CESRSpeechProfileUpdateReasonProfileError
+ _CESRSpeechProfileUpdateReasonProfileMissing
+ _CESRSpeechProfileUpdateReasonSetChanges
+ _CESRSpeechProfileUpdateReasonVersionMismatch
+ _CESRSpeechProfileUpdateTriggerAdminMaintenance
+ _CESRSpeechProfileUpdateTriggerAdminRebuild
+ _CESRSpeechProfileUpdateTriggerAssetUpdate
+ _CESRSpeechProfileUpdateTriggerDailyMaintenance
+ _CESRSpeechProfileUpdateTriggerFirstUnlock
+ _CESRSpeechProfileUpdateTriggerMobileAssetStartup
+ _CESRSpeechProfileUpdateTriggerPostInstallMigration
+ _CESRSpeechProfileUpdateTriggerPreferencesChanged
+ _CESRSpeechProfileUpdateTriggerSetUpdate
+ _CESRSpeechProfileUpdateTriggerSubscriptionsChanged
+ _CESRSpeechProfileUpdateTriggerUnknown
+ _NSFileSize
+ _NSTemporaryDirectory
+ _NSTextCheckingCityKey
+ _NSTextCheckingCountryKey
+ _NSTextCheckingPhoneKey
+ _NSTextCheckingStateKey
+ _NSTextCheckingStreetKey
+ _NSTextCheckingZIPKey
+ _OBJC_CLASS_$_ASRSchemaASRContextualEntityProcessingContext
+ _OBJC_CLASS_$_ASRSchemaASRContextualEntityProcessingEnded
+ _OBJC_CLASS_$_ASRSchemaASRContextualEntityProcessingStarted
+ _OBJC_CLASS_$_ASRSchemaASRContextualEntityRetrievalFailed
+ _OBJC_CLASS_$_ASRSchemaASRRecognitionResultTier1
+ _OBJC_CLASS_$_ASRSchemaASRToken
+ _OBJC_CLASS_$_ASRSchemaASRTokenTier1
+ _OBJC_CLASS_$_CESREncryptedLogger
+ _OBJC_CLASS_$_CESRSpeechProfileAnalyticsLog
+ _OBJC_CLASS_$_IFTSchemaIFTCustom
+ _OBJC_CLASS_$_IFTSchemaIFTTypeIdentifier
+ _OBJC_CLASS_$_LNAssistantDefinedSchemaConformance
+ _OBJC_CLASS_$_LNEntityMetadata
+ _OBJC_CLASS_$_LNMetadataProvider
+ _OBJC_CLASS_$_NSDataDetector
+ _OBJC_CLASS_$_NSMutableCharacterSet
+ _OBJC_CLASS_$_NSNull
+ _OBJC_CLASS_$_SFEncryptedLogger
+ _OBJC_IVAR_$_CESRSpeechProfileAnalyticsLog._fileURL
+ _OBJC_IVAR_$_CESRSpeechProfileDispatcher._pendingCascadeSets
+ _OBJC_IVAR_$_CESRSpeechProfileDispatcher._trialClient
+ _OBJC_IVAR_$_CESRSpeechProfileSite._analyticsLog
+ _OBJC_METACLASS_$_CESREncryptedLogger
+ _OBJC_METACLASS_$_CESRSpeechProfileAnalyticsLog
+ __CLASS_METHODS_CESREncryptedLogger
+ __DATA_CESREncryptedLogger
+ __DATA__TtC29CoreEmbeddedSpeechRecognition21CESRAppEntityResolver
+ __DATA__TtC29CoreEmbeddedSpeechRecognition26CESRNCBVQProfileSelfHelper
+ __DATA__TtC29CoreEmbeddedSpeechRecognition35CESREuclidProfileDebugDumpCollector
+ __DATA__TtC29CoreEmbeddedSpeechRecognitionP33_4A740B251FE694BD957F0CD9981F7F2B19AppEnumerationState
+ __INSTANCE_METHODS_CESREncryptedLogger
+ __IVARS__TtC29CoreEmbeddedSpeechRecognition21CESRAppEntityResolver
+ __IVARS__TtC29CoreEmbeddedSpeechRecognition26CESRNCBVQProfileSelfHelper
+ __IVARS__TtC29CoreEmbeddedSpeechRecognition35CESREuclidProfileDebugDumpCollector
+ __IVARS__TtC29CoreEmbeddedSpeechRecognitionP33_4A740B251FE694BD957F0CD9981F7F2B19AppEnumerationState
+ __METACLASS_DATA_CESREncryptedLogger
+ __METACLASS_DATA__TtC29CoreEmbeddedSpeechRecognition21CESRAppEntityResolver
+ __METACLASS_DATA__TtC29CoreEmbeddedSpeechRecognition26CESRNCBVQProfileSelfHelper
+ __METACLASS_DATA__TtC29CoreEmbeddedSpeechRecognition35CESREuclidProfileDebugDumpCollector
+ __METACLASS_DATA__TtC29CoreEmbeddedSpeechRecognitionP33_4A740B251FE694BD957F0CD9981F7F2B19AppEnumerationState
+ __OBJC_$_CLASS_METHODS_CESRBackgroundSystemTask
+ __OBJC_$_INSTANCE_METHODS_CESRSpeechProfileAnalyticsLog
+ __OBJC_$_INSTANCE_VARIABLES_CESRSpeechProfileAnalyticsLog
+ __OBJC_$_PROP_LIST_CESRSpeechProfileAnalyticsLog
+ __OBJC_CLASS_RO_$_CESRSpeechProfileAnalyticsLog
+ __OBJC_METACLASS_RO_$_CESRSpeechProfileAnalyticsLog
+ ___68-[CESRSpeechProfileDispatcher _registerTrialExperimentUpdateHandler]_block_invoke
+ ___68-[CESRSpeechProfileSiteManager resetAndRebuildAllSpeechProfileSites]_block_invoke
+ ___69-[CESRSpeechProfileDispatcher handlePendingSetChangesWithCompletion:]_block_invoke
+ ___72+[CESRBackgroundSystemTask submitOnDemandCascadeSetChangeProcessingBGST]_block_invoke
+ ___74+[CESRBackgroundSystemTask submitOnDemandSpeechProfileResetAndRebuildBGST]_block_invoke
+ ___77-[CESRSpeechProfileDispatcher runSpeechProfileResetAndRebuildWithCompletion:]_block_invoke
+ ___83-[CESRSpeechProfileUpdater rebuildCategoryGroup:withSets:version:totalItems:error:]_block_invoke
+ ___84-[CESRSpeechProfileSiteManager performSpeechProfileMaintenance:trigger:shouldDefer:]_block_invoke
+ ___84-[CESRSpeechProfileSiteWriter _verifyAllSpeechProfileInstances:trigger:shouldDefer:]_block_invoke
+ ___86-[CESRSpeechProfileSiteManager _maintainSpeechProfilesAtAllSites:trigger:shouldDefer:]_block_invoke
+ ___91-[CESRSpeechProfileSiteWriter _updateRequiredProfileInstancesWithSets:trigger:shouldDefer:]_block_invoke
+ ____registerOnDemandCascadeSetChangeProcessingBGST_block_invoke
+ ____registerOnDemandSpeechProfileResetAndRebuildBGST_block_invoke
+ ____runOnDemandCascadeSetChangeProcessing_block_invoke
+ ____runOnDemandSpeechProfileResetAndRebuild_block_invoke
+ ___block_descriptor_40_e8_32s_e38_v16?0"<TRINamespaceUpdateProtocol>"8ls32l8
+ ___block_descriptor_64_e8_32s40s48bs_e15_B16?0"NSURL"8ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48bs56r_e5_v8?0lr56l8s32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56bs64r_e21_v20?0"NSLocale"8C16ls32l8r64l8s40l8s48l8s56l8
+ ___block_descriptor_81_e8_32s40s48s56s64bs72r_e21_v20?0"NSLocale"8C16ls32l8r72l8s40l8s48l8s64l8s56l8
+ ___swift_memcpy112_8
+ __sharedTextDataTypeDetector
+ __sizeMB
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private_$_CoreEmbeddedSpeechRecognition
+ _associated conformance 29CoreEmbeddedSpeechRecognition0C13ProfileConfigC15LimitAllocationC0H8StrategyOs12CaseIterableAA8AllCasessAHP_Sl
+ _associated conformance 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC9LookupKey33_FF7729DD65F36DEC26AA3677FFDADB7ELLVSHAASQ
+ _associated conformance 29CoreEmbeddedSpeechRecognition29CESAContextualEntityRetrieverC9ErrorCodeOSHAASQ
+ _associated conformance 29CoreEmbeddedSpeechRecognition30CESAProfileMaintenanceTaskTypeOSHAASQ
+ _associated conformance So29NSDirectoryEnumerationOptionsVs10SetAlgebraSCSQ
+ _associated conformance So29NSDirectoryEnumerationOptionsVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So29NSDirectoryEnumerationOptionsVs9OptionSetSCSY
+ _associated conformance So29NSDirectoryEnumerationOptionsVs9OptionSetSCs0E7Algebra
+ _dynamic_cast_existential_0_class_conditional
+ _flat unique So21CCItemFieldEnumerable_p
+ _get_type_metadata 15Synchronization5MutexVy29CoreEmbeddedSpeechRecognition0E13ProfileConfigC0H0CSg6config_Sb15loadedFromTrialSSSg17trialExperimentIdAL0m9TreatmentO0tG noncopyable
+ _keypath_get_selector_bundleId
+ _objc_retain_x6
+ _swift_dynamicCastObjCProtocolConditional
+ _swift_isClassType
+ _symbolic $s29CoreEmbeddedSpeechRecognition15CascadeProviderP
+ _symbolic $s29CoreEmbeddedSpeechRecognition24InteractionStoreProviderP
+ _symbolic $s29CoreEmbeddedSpeechRecognition28CESRAssistantSchemaResolvingP
+ _symbolic $s29CoreEmbeddedSpeechRecognition28CESREuclidOriginItemResolverP
+ _symbolic SDySSSDySSSo16LNEntityMetadataCGG
+ _symbolic SDySSSDySS_____GG 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC15PropertyMappingV
+ _symbolic SDySSSDySS_____GGSg 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC15PropertyMappingV
+ _symbolic SDySSSaySo12CCSharedItemCGG
+ _symbolic SDySSSaySo12CCSharedItemCy______So13CCItemMessageCXcGGG So13CCItemContentP
+ _symbolic SDySSSaySo5CCSetCGG
+ _symbolic SDySSSo12CCSharedItemCG
+ _symbolic SDySSSo12CCSharedItemCy______So13CCItemMessageCXcGG So13CCItemContentP
+ _symbolic SDySSSo16LNEntityMetadataCG
+ _symbolic SDySSSo16LNEntityMetadataCGIgo_
+ _symbolic SDySS_____G 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC15PropertyMappingV
+ _symbolic SDySS_____SgG 29CoreEmbeddedSpeechRecognition20CESREuclidOriginItemV
+ _symbolic SSSg_AAt
+ _symbolic SS_SDySSSDySS_____GGt 29CoreEmbeddedSpeechRecognition0C13ProfileConfigC17AllLmeAssignmentsC
+ _symbolic SS_SDySSSo16LNEntityMetadataCGt
+ _symbolic SS_SDySS_____Gt 29CoreEmbeddedSpeechRecognition0C13ProfileConfigC17AllLmeAssignmentsC
+ _symbolic SS_SDySS_____Gt 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC15PropertyMappingV
+ _symbolic SS_SaySo12CCSharedItemCGt
+ _symbolic SS_SaySo5CCSetCGt
+ _symbolic SS_So12CCSharedItemCt
+ _symbolic SS_So16LNEntityMetadataCt
+ _symbolic SS______Sgt 29CoreEmbeddedSpeechRecognition20CESREuclidOriginItemV
+ _symbolic SS______t 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC15PropertyMappingV
+ _symbolic SS______t 6Speech11TranscriberC18MultisegmentResultV
+ _symbolic SaySS3key_SDySS_____G5valuetG 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC15PropertyMappingV
+ _symbolic SaySS3key______5valuetG 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC15PropertyMappingV
+ _symbolic SaySo12CCSharedItemCy______So13CCItemMessageCXcGGIgo_ So13CCItemContentP
+ _symbolic SaySo12CCSharedItemCy______So13CCItemMessageCXcGGz_Xx So13CCItemContentP
+ _symbolic SaySo17ASRSchemaASRTokenCG
+ _symbolic SaySo22ASRSchemaASRTokenTier1CG
+ _symbolic SaySo35LNAssistantDefinedSchemaConformanceCG
+ _symbolic Say_____G 29CoreEmbeddedSpeechRecognition0C13ProfileConfigC15LimitAllocationC0H8StrategyO
+ _symbolic Say_____G 29CoreEmbeddedSpeechRecognition31CESREuclidProfileDebugDumpEntryV
+ _symbolic Say_____GSg 23IntelligenceFlowContext0C4ItemO
+ _symbolic Say_____GSgz_Xx 23IntelligenceFlowContext0C4ItemO
+ _symbolic Sb7success_Sb10wasDroppedt
+ _symbolic ScGyytG
+ _symbolic ShySSGSg
+ _symbolic ShySSGz_Xx
+ _symbolic Shy_____G 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC9LookupKey33_FF7729DD65F36DEC26AA3677FFDADB7ELLV
+ _symbolic SiSg
+ _symbolic So17OS_dispatch_groupC
+ _symbolic So18LNMetadataProviderC
+ _symbolic So22CESRAppEntityCandidateC
+ _symbolic So32CCASRRankedEntityTermMetaContentCSg
+ _symbolic SsSg
+ _symbolic _____ 23IntelligenceFlowContext0C4ToolC17RequestParametersV
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition19AppEnumerationState33_4A740B251FE694BD957F0CD9981F7F2BLLC
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition20CESREuclidOriginItemV
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC15PropertyMappingV
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC9LookupKey33_FF7729DD65F36DEC26AA3677FFDADB7ELLV
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition22DefaultCascadeProviderV
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition26CESRNCBVQProfileSelfHelperC
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition29CESAContextualEntityRetrieverC9ErrorCodeO
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition30CESAProfileMaintenanceTaskTypeO
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition31CESREuclidProfileDebugDumpEntryV
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition35CESRDefaultEuclidOriginItemResolverV
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition35CESREuclidProfileDebugDumpCollectorC
+ _symbolic _____ 2os12OSSignposterV
+ _symbolic _____ 8Dispatch0A12TimeIntervalO
+ _symbolic _____ So29NSDirectoryEnumerationOptionsV
+ _symbolic _____ s15ContinuousClockV7InstantV
+ _symbolic _____Sg 23IntelligenceFlowContext0C4ItemO4KindO
+ _symbolic _____Sg 29CoreEmbeddedSpeechRecognition20CESREuclidOriginItemV
+ _symbolic _____Sg 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC
+ _symbolic _____Sg 29CoreEmbeddedSpeechRecognition21CESRRankedEntityCacheC
+ _symbolic _____Sg 29CoreEmbeddedSpeechRecognition35CESREuclidProfileDebugDumpCollectorC
+ _symbolic _____Sg6config_Sb15loadedFromTrialSSSg17trialExperimentIdAE0e9TreatmentG0t 29CoreEmbeddedSpeechRecognition0C13ProfileConfigC0F0C
+ _symbolic _____Sg_ABt 10Foundation16AttributedStringV
+ _symbolic ______p 29CoreEmbeddedSpeechRecognition15CascadeProviderP
+ _symbolic ______p 29CoreEmbeddedSpeechRecognition24InteractionStoreProviderP
+ _symbolic ______p 29CoreEmbeddedSpeechRecognition28CESREuclidOriginItemResolverP
+ _symbolic ______p So21CCItemFieldEnumerableP
+ _symbolic ______p s7CVarArgP
+ _symbolic ______pSg 29CoreEmbeddedSpeechRecognition28CESRAssistantSchemaResolvingP
+ _symbolic _____yS2S_G SD6ValuesV
+ _symbolic _____ySSSDySSSDySS_____GG_G SD8IteratorV 29CoreEmbeddedSpeechRecognition0D13ProfileConfigC17AllLmeAssignmentsC
+ _symbolic _____ySSSDySS_____G_G SD8IteratorV 29CoreEmbeddedSpeechRecognition0D13ProfileConfigC17AllLmeAssignmentsC
+ _symbolic _____ySSSaySo12CCSharedItemCG_G SD4KeysV
+ _symbolic _____ySSSaySo12CCSharedItemCG_G SD6ValuesV
+ _symbolic _____ySSSaySo22CESRAppEntityCandidateCG_G SD4KeysV
+ _symbolic _____ySSSaySo22CESRAppEntityCandidateCG__G SD4KeysV8IteratorV
+ _symbolic _____ySS______G SD6ValuesV 29CoreEmbeddedSpeechRecognition0D13ProfileConfigC13LmeAssignmentC
+ _symbolic _____ySS______G SD6ValuesV 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC15PropertyMappingV
+ _symbolic _____ySS______G SD8IteratorV 29CoreEmbeddedSpeechRecognition0D13ProfileConfigC17AllLmeAssignmentsC
+ _symbolic _____ySS______G SD8IteratorV 6Speech11TranscriberC18MultisegmentResultV
+ _symbolic _____ySaySS3key_SDySS_____G5valuetGG s16IndexingIteratorV 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC15PropertyMappingV
+ _symbolic _____ySaySS3key______5valuetGG s16IndexingIteratorV 29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC15PropertyMappingV
+ _symbolic _____ySay_____GG s16IndexingIteratorV 10Foundation3URLV
+ _symbolic _____ySay_____GG s16IndexingIteratorV 23IntelligenceFlowContext0E4ItemO4KindO
+ _symbolic _____ySay_____GG s16IndexingIteratorV 29CoreEmbeddedSpeechRecognition19ProcessedItemResultC
+ _symbolic _____ySay_____GG s16IndexingIteratorV 29CoreEmbeddedSpeechRecognition21EnrollmentResultStateO
+ _symbolic _____ySay_____GG s16IndexingIteratorV 29CoreEmbeddedSpeechRecognition31CESREuclidProfileDebugDumpEntryV
+ _symbolic _____ySsG 17_StringProcessing5RegexV
+ _symbolic _____ySs_G 17_StringProcessing5RegexV5MatchV
+ _symbolic _____ySs_GSg 17_StringProcessing5RegexV5MatchV
+ _symbolic _____y_____G s10ArraySliceV 20IntelligencePlatform11ViewServiceC027DefaultResolverInteractionsE0V20CandidateInteractionV
+ _symbolic _____y_____G s10ArraySliceV 29CoreEmbeddedSpeechRecognition21CESRRankedEntityEntryV
+ _symbolic _____y_____Sg6config_Sb15loadedFromTrialSSSg17trialExperimentIdAF0e9TreatmentG0tG 15Synchronization5MutexVAARi_zrlE 29CoreEmbeddedSpeechRecognition0E13ProfileConfigC0H0C
+ _symbolic _____y_____Sg6config_Sb15loadedFromTrialSSSg17trialExperimentIdAF0e9TreatmentG0tG 15Synchronization5_CellVAARi_zrlE 29CoreEmbeddedSpeechRecognition0E13ProfileConfigC0H0C
+ _symbolic _____y_____y_____GG s16IndexingIteratorV s10ArraySliceV 20IntelligencePlatform11ViewServiceC027DefaultResolverInteractionsG0V20CandidateInteractionV
+ _symbolic _____yyXlG s23_ContiguousArrayStorageC
- -[CESREuclidProfileInsertion initWithField:cascadeItemType:sharedItemIdentifier:fieldType:assistantSchemaDomain:assistantSchemaType:assistantSchemaProperty:extractedType:parentEntityIdentifier:]
- -[CESREuclidProfileInsertion parentEntityIdentifier]
- -[CESRSpeechProfileSelfHelper logASRSpeechProfileUpdateFailedWithReason:]
- -[CESRSpeechProfileSiteManager _maintainSpeechProfilesAtAllSites:shouldDefer:]
- -[CESRSpeechProfileSiteManager _maintainSpeechProfilesForSiteAtURL:maintenanceLevel:shouldDefer:]
- -[CESRSpeechProfileSiteManager _registerTrialExperimentUpdateHandler]
- -[CESRSpeechProfileSiteManager performSpeechProfileMaintenance:shouldDefer:]
- -[CESRSpeechProfileSiteManager setTrialClient:]
- -[CESRSpeechProfileSiteManager trialClient]
- -[CESRSpeechProfileSiteWriter _fullRebuildForInvalidProfileInstance:locale:options:shouldDefer:]
- -[CESRSpeechProfileSiteWriter _updateProfileInstance:categoryGroup:shouldDefer:]
- -[CESRSpeechProfileSiteWriter _updateRequiredProfileInstancesWithSets:shouldDefer:]
- -[CESRSpeechProfileSiteWriter _verifyAllSpeechProfileInstances:shouldDefer:]
- -[CESRSpeechProfileSiteWriter _verifyProfileInstance:shouldDefer:]
- -[CESRSpeechProfileSiteWriter verifyAllSpeechProfileInstances:shouldDefer:]
- -[CESRSpeechProfileUpdater detectCategoriesToRebuild:error:]
- -[CESRSpeechProfileUpdater rebuildCategoryGroup:withSets:version:error:]
- GCC_except_table1101
- GCC_except_table1160
- GCC_except_table1161
- GCC_except_table1162
- GCC_except_table1163
- GCC_except_table1164
- GCC_except_table1165
- GCC_except_table1170
- GCC_except_table1201
- GCC_except_table1327
- GCC_except_table1333
- GCC_except_table1338
- GCC_except_table1342
- GCC_except_table1386
- GCC_except_table1394
- GCC_except_table1399
- GCC_except_table1403
- GCC_except_table156
- GCC_except_table162
- GCC_except_table169
- GCC_except_table176
- GCC_except_table186
- GCC_except_table237
- GCC_except_table248
- GCC_except_table283
- GCC_except_table298
- GCC_except_table331
- GCC_except_table351
- GCC_except_table354
- GCC_except_table415
- GCC_except_table436
- GCC_except_table583
- GCC_except_table588
- GCC_except_table591
- GCC_except_table595
- GCC_except_table598
- GCC_except_table601
- GCC_except_table604
- GCC_except_table613
- GCC_except_table700
- GCC_except_table71
- GCC_except_table723
- GCC_except_table739
- GCC_except_table776
- GCC_except_table78
- GCC_except_table984
- GCC_except_table989
- _OBJC_IVAR_$_CESREuclidProfileInsertion._parentEntityIdentifier
- _OBJC_IVAR_$_CESRSpeechProfileSiteManager._trialClient
- _OBJC_IVAR_$_CESRSpeechProfileSiteWriter._queue
- __DATA__TtC29CoreEmbeddedSpeechRecognition20CESAAppEntityMapping
- __IVARS__TtC29CoreEmbeddedSpeechRecognition20CESAAppEntityMapping
- __METACLASS_DATA__TtC29CoreEmbeddedSpeechRecognition20CESAAppEntityMapping
- ___50-[CESRSpeechProfileSiteWriter _siteApplicableSets]_block_invoke
- ___69-[CESRSpeechProfileSiteManager _registerTrialExperimentUpdateHandler]_block_invoke
- ___72-[CESRSpeechProfileUpdater rebuildCategoryGroup:withSets:version:error:]_block_invoke
- ___76-[CESRSpeechProfileSiteManager performSpeechProfileMaintenance:shouldDefer:]_block_invoke
- ___76-[CESRSpeechProfileSiteWriter _verifyAllSpeechProfileInstances:shouldDefer:]_block_invoke
- ___78-[CESRSpeechProfileSiteManager _maintainSpeechProfilesAtAllSites:shouldDefer:]_block_invoke
- ___83-[CESRSpeechProfileSiteWriter _updateRequiredProfileInstancesWithSets:shouldDefer:]_block_invoke
- ___block_descriptor_48_e8_32s40w_e38_v16?0"<TRINamespaceUpdateProtocol>"8lw40l8s32l8
- ___block_descriptor_56_e8_32s40bs_e15_B16?0"NSURL"8ls32l8s40l8
- ___block_descriptor_64_e8_32s40bs48r_e5_v8?0lr48l8s32l8s40l8
- ___block_descriptor_72_e8_32s40s48bs56r_e21_v20?0"NSLocale"8C16ls32l8r56l8s40l8s48l8
- ___block_descriptor_73_e8_32s40s48s56bs64r_e21_v20?0"NSLocale"8C16ls32l8r64l8s40l8s56l8s48l8
- _get_type_metadata 15Synchronization5MutexVy29CoreEmbeddedSpeechRecognition0E13ProfileConfigC0H0CSg6config_Sb15loadedFromTrialtG noncopyable
- _symbolic SDySSSDySS_____GG 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC08PropertyG0V
- _symbolic SDySSSDySS_____GGSg 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC08PropertyG0V
- _symbolic SDySS_____G 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC08PropertyG0V
- _symbolic SDySo22CESRAppEntityCandidateCSo12CCSharedItemCG
- _symbolic SDySo22CESRAppEntityCandidateCSo12CCSharedItemCy______So13CCItemMessageCXcGG So13CCItemContentP
- _symbolic SS_SDySS_____Gt 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC08PropertyG0V
- _symbolic SS______t 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC08PropertyG0V
- _symbolic SaySDySSypGGIegr_
- _symbolic SaySS3key_SDySS_____G5valuetG 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC08PropertyG0V
- _symbolic SaySS3key______5valuetG 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC08PropertyG0V
- _symbolic SaySSGIegr_
- _symbolic SaySSSgGIegr_
- _symbolic ShySSGIegr_
- _symbolic ShySSGIgo_
- _symbolic So19BMDictationUserEditC
- _symbolic So22CESRAppEntityCandidateC_So12CCSharedItemCt
- _symbolic _____ 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC
- _symbolic _____ 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC08PropertyG0V
- _symbolic _____Igd_ s6UInt32V
- _symbolic _____Sg 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC
- _symbolic _____Sg6config_Sb15loadedFromTrialt 29CoreEmbeddedSpeechRecognition0C13ProfileConfigC0F0C
- _symbolic ______So13CCItemMessageCXcSg So13CCItemContentP
- _symbolic _____yS2S_G SD8IteratorV
- _symbolic _____ySSSaySo22CESRAppEntityCandidateCG_G SD6ValuesV
- _symbolic _____ySS______G SD4KeysV s6UInt32V
- _symbolic _____ySS______G SD6ValuesV 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC08PropertyH0V
- _symbolic _____ySaySS3key_SDySS_____G5valuetGG s16IndexingIteratorV 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC08PropertyI0V
- _symbolic _____ySaySS3key______5valuetGG s16IndexingIteratorV 29CoreEmbeddedSpeechRecognition20CESAAppEntityMappingC08PropertyI0V
- _symbolic _____ySaySo22CESRAppEntityCandidateCG_G s18EnumeratedSequenceV8IteratorV
- _symbolic _____ySay_____GG s16IndexingIteratorV 20IntelligencePlatform11ViewServiceC027DefaultResolverInteractionsE0V20CandidateInteractionV
- _symbolic _____ySbG 15Synchronization5_CellVAARi_zrlE
- _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE So16os_unfair_lock_sV
- _symbolic _____y_____G s11_SetStorageC 6Speech11TranscriberC19TranscriptionOptionO
- _symbolic _____y_____G s23_ContiguousArrayStorageC 6Speech11TranscriberC19TranscriptionOptionO
- _symbolic _____y_____Sg6config_Sb15loadedFromTrialtG 15Synchronization5MutexVAARi_zrlE 29CoreEmbeddedSpeechRecognition0E13ProfileConfigC0H0C
- _symbolic _____y_____Sg6config_Sb15loadedFromTrialtG 15Synchronization5_CellVAARi_zrlE 29CoreEmbeddedSpeechRecognition0E13ProfileConfigC0H0C
- _symbolic _____yytG 15Synchronization5_CellVAARi_zrlE
CStrings:
+ "\r"
+ "  Fill candidates by type: [%s]"
+ "\""
+ "\"\""
+ "\", original transcript \""
+ "\", replay type "
+ "%.2f"
+ "%.3f"
+ "%s (%@) Analytics log: %@"
+ "%s (%@) Completed profile update version: %@, for categories: %@"
+ "%s (%@) Completed speech profile update for category group: %@, with sets: %@"
+ "%s (%@) Failed to cancel categories: %@, error: %@"
+ "%s (%@) Failed to enumerate and add items from ranker: %@, error: %@"
+ "%s (%@) Failed to enumerate set: %@, error: %@"
+ "%s (%@) Failed to rebuild category group: %@, with sets: %@, error: %@"
+ "%s ASR interaction-only ranking is enabled via user default."
+ "%s Aborting Euclid profile update due to timeout."
+ "%s Accumulating %lu Cascade set change(s) pending processing."
+ "%s Analytics log could not be parsed, starting fresh, error: %@"
+ "%s Euclid profile update completed in %ss"
+ "%s Failed to enumerate sets for Euclid profile, error: %@"
+ "%s Failed to serialize analytics log, error: %@"
+ "%s Failed to write analytics log, error: %@"
+ "%s Failed to write update from Cascade to Euclid profile for set %@; continuing with remaining sets."
+ "%s Ignoring Trial namespace update because evaluation is enabled."
+ "%s On-Device ASR: BGST: %@ Cascade set change processing."
+ "%s On-Device ASR: BGST: %@ on-demand speech profile reset/rebuild."
+ "%s On-Device ASR: BGST: Triggering Cascade set change processing."
+ "%s On-Device ASR: BGST: Triggering on-demand speech profile reset and rebuild."
+ "%s Processing %lu Cascade set change(s)."
+ "%s Trial updates detected for namespace (%@), submitting on-demand speech-profile-reset-and-rebuild BGST."
+ "%s: Crashing since we failed to cancel the previous recognition"
+ "%s: Feature is disabled"
+ "%s: Missing assets for locale: %{public}s"
+ "%s: Unsupported taskHint: %{public}s"
+ "%s:Abort timeout to cancel the previous recognition"
+ ")"
+ "+[CESRUtilities isInteractionOnlyRankingEnabled]"
+ ","
+ ", ASR Alternatives: "
+ ", bookmark="
+ ", correctedText: "
+ ", correctedTextV2: "
+ ", for requestID "
+ ", overallTimeout: "
+ ", success="
+ ", variants: "
+ "-[CESRSpeechProfileAnalyticsLog _readFile]"
+ "-[CESRSpeechProfileAnalyticsLog _writeFile:]"
+ "-[CESRSpeechProfileDispatcher _notifyChangeToSets:]_block_invoke"
+ "-[CESRSpeechProfileDispatcher _registerTrialExperimentUpdateHandler]"
+ "-[CESRSpeechProfileDispatcher _registerTrialExperimentUpdateHandler]_block_invoke"
+ "-[CESRSpeechProfileDispatcher handlePendingSetChangesWithCompletion:]_block_invoke"
+ "-[CESRSpeechProfileSiteManager _maintainSpeechProfilesAtAllSites:trigger:shouldDefer:]"
+ "-[CESRSpeechProfileSiteManager _maintainSpeechProfilesForSiteAtURL:maintenanceLevel:trigger:shouldDefer:]"
+ "-[CESRSpeechProfileSiteWriter _fullRebuildForInvalidProfileInstance:locale:options:trigger:shouldDefer:]"
+ "-[CESRSpeechProfileSiteWriter _siteApplicableSets]"
+ "-[CESRSpeechProfileSiteWriter _updateProfileInstance:categoryGroup:trigger:reason:shouldDefer:]"
+ "-[CESRSpeechProfileSiteWriter _updateRequiredProfileInstancesWithSets:trigger:shouldDefer:]"
+ "-[CESRSpeechProfileSiteWriter _updateRequiredProfileInstancesWithSets:trigger:shouldDefer:]_block_invoke"
+ "-[CESRSpeechProfileSiteWriter _verifyAllSpeechProfileInstances:trigger:shouldDefer:]"
+ "-[CESRSpeechProfileSiteWriter _verifyProfileInstance:trigger:shouldDefer:]"
+ "-[CESRSpeechProfileSiteWriter logRequiredProfileInstances]"
+ "-[CESRSpeechProfileUpdater detectCategoriesToRebuild:allCategoriesAreDeferredResume:error:]"
+ "-[CESRSpeechProfileUpdater rebuildCategoryGroup:withSets:version:totalItems:error:]"
+ ".csv"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreSpeech/CoreEmbeddedSpeechRecognition/EuclidProfile/CESREuclidProfileInstance.h"
+ "/^[A-Za-z0-9._-]+$/"
+ "1 Best: "
+ "AFSpeechPhrase has multiple interpretations."
+ "App %s summary: sought=%ld found=%ld missed=%ld fillNeeded=%ld foundTypes=[%s]"
+ "App %s summary: sought=0 found=0 missed=0 fillNeeded=0 foundTypes=[] (enumeration skipped: interactionOnlyRanking + no ranked IDs)"
+ "App cap: %ld. Selected %ld apps with interactions + %ld zero-interaction fill apps. %ld apps skipped."
+ "Auto-derived maxAppsToProcess clamped to 1 (raw=%ld, itemLimit=%ld, perAppEntityMinimum=%ld)"
+ "CESABiomeContextualReplayRecord: audioSelectedForSampling: %{bool}d, usingFoundationModelTranscriber: %{bool}d"
+ "CESRAppEntityRanker requires SpeechProfileConfig but it is unavailable."
+ "CESRRankedEntityCache initialized at: %{public}s"
+ "Cache for %s was empty or unreadable — falling back to fresh InteractionStore rank."
+ "Cached %ld candidates for %s."
+ "Cascade enumeration incomplete for %s: continuing with next app"
+ "Contextual entity retrieval: hit overall timeout during retrieval"
+ "Contextual entity retrieval: hit overallTimeout during item processing"
+ "CoreEmbeddedSpeechRecognition.EntityLimits"
+ "CoreEmbeddedSpeechRecognition.Retrieval"
+ "Creating AFSpeechPackage with the following contents: "
+ "Debug dump written to: %{public}s"
+ "Deleting unreadable cache file for %s: %@"
+ "Division results in an overflow"
+ "Donating edit record to Biome."
+ "Euclid profile update exceeded deadline"
+ "EuclidProfile update: %ld sets processed, %ld fields accepted, %ld fields filtered, %ld field enumeration failures, %ld per-set write failures, %ld ranked-entity origin walks (uncached)"
+ "EuclidProfileDump_"
+ "Failed Link Registry lookup for %s.%s: %@"
+ "Failed to cache candidates for %s: %@"
+ "Failed to create ASRRecognitionResultTier1"
+ "Failed to fetch interaction candidates for %s: %@"
+ "Failed to initialize ASRSchemaASRToken"
+ "Failed to initialize ASRSchemaASRTokenTier1"
+ "Failed to list cache directory for purge: %@"
+ "Failed to process Cascade item for insertion (itemIdentifier=%{public}s), error: %@"
+ "Failed to purge %s: %@"
+ "Failed to write debug dump: %@"
+ "Fetched %ld interaction candidates for %s"
+ "Fides"
+ "Filled %ld items for %s (had %ld ranked, target min %ld)"
+ "First-pass allocation: %ld items across %ld apps. Remaining slots: %ld"
+ "Generating and ranking InteractionStore candidates for %ld sets..."
+ "InteractionStore returned %ld candidates for %s"
+ "Invalid configuration: itemLimit=%ld, perAppEntityMinimum=%ld"
+ "Link Registry pre-flight failed for %s: %@"
+ "Link Registry pre-flight: %ld/%ld apps have supported entity types"
+ "Loaded %ld cached candidate IDs for %s"
+ "Loading %ld cached rankings."
+ "Mismatched candidate sizes: expected %ld, got %ld"
+ "No change to the Euclid profile is required for set: %s"
+ "No valid bundleID on this set - skipping."
+ "Origin walk: AppIntents typeIdentifier is nil for %{private}s"
+ "Origin walk: CCItemFieldPredicate init failed for %{private}s"
+ "Origin walk: item content is not CCAppIntentsIndexedEntityContent for %{private}s"
+ "Origin walk: keyComponent failed for %{private}s"
+ "Origin walk: originItemIdentifier is not a UUID: %{private}s"
+ "Origin walk: setWithKey failed for %{private}s"
+ "Origin walk: singleItemInstance lookup failed for %{private}s"
+ "Presenting %ld Euclid alternatives of desired %ld"
+ "Processing results for replay transcript \""
+ "Processing results for replay type %s, for requestID %@"
+ "Purged expired cache file: %s (age: %lds)"
+ "Ranked entity cache unavailable - falling back to ASRRankedEntityTerm-only enrolment"
+ "Ranked schema info: fieldTypeValue could not be parsed from sourceItemIdentifier for %{private}s"
+ "Ranked schema info: makeSchemaInfo returned nil for entityIdentifier=%{public}s fieldType=%{public}hu"
+ "Ranked schema info: originItemIdentifier is nil"
+ "Ranker config: itemLimit=%ld perAppEntityMinimum=%ld sets=%ld maxAppsToProcess=%ld fillEnumerationThreshold=%ld maxInteractionsPerCandidate=%s maxRankedCandidatesPerApp=%s interactionOnlyRanking=%{bool}d"
+ "Ranking across %ld apps."
+ "Received corrected texts"
+ "Received corrected texts, interactionId: "
+ "Refusing to use invalid bundleId as filename: %s"
+ "Rejecting malformed LME mapping %s.%s.%s: templateName must start with \\NT- (primaryLme=\"%s\")"
+ "Retrieving and validating items from Cascade."
+ "Set alternativeSelection for CESRFidesASRRecord, interactionId: %s"
+ "Set correctedText for CESRFidesASRRecord, interactionId: %s"
+ "Set correctedTextV2 for CESRFidesASRRecord, interactionId: %s"
+ "Set recognized text: "
+ "Skipping %s: no supported entity types in Link Registry"
+ "Skipping AppIntents set with nil bundleId: %s"
+ "Skipping fill-to-minimum for %s: no interactions and set size %ld exceeds threshold %ld"
+ "Speech"
+ "SpeechMaintenance/ASRInteractionOnlyRankingEnabled"
+ "SpeechProfileAnalytics.json"
+ "SpeechProfileConfig: Trial fetch failed, falling back to bundled default."
+ "SpeechProfileConfig: bundled fallback also unavailable — config is nil."
+ "SpeechProfileConfig: loaded default config from Trial (no active experiment) namespace=%{public}s factor=%{public}s"
+ "SpeechProfileConfig: loaded default config from bundled fallback (Trial unavailable)."
+ "SpeechProfileConfig: loaded experimental config from Trial namespace=%{public}s factor=%{public}s experimentId=%{public}s treatmentId=%{public}s"
+ "Task cancelled after candidate generation."
+ "Task cancelled during cache loading."
+ "Task cancelled. Stopping ranking."
+ "Transcript: "
+ "Trimmed to %ld with limit=%ld."
+ "Variants contain correctedText: "
+ "XPC call timed out"
+ "XPC call to %s timed out during %s"
+ "_runOnDemandCascadeSetChangeProcessing"
+ "_runOnDemandCascadeSetChangeProcessing_block_invoke"
+ "_runOnDemandSpeechProfileResetAndRebuild"
+ "_runOnDemandSpeechProfileResetAndRebuild_block_invoke"
+ "accepted"
+ "admin_maintenance"
+ "admin_rebuild"
+ "aggregate"
+ "already enrolled via ASRRankedEntityTerm"
+ "alternatives: "
+ "app entity budget exceeded"
+ "asset_update"
+ "averageDurationMs"
+ "byLocale"
+ "byOptions"
+ "byReason"
+ "byTrigger"
+ "categories"
+ "com.apple.corespeech.euclid.debugDump"
+ "com.apple.corespeechd.cascadesetchange"
+ "com.apple.corespeechd.preheat"
+ "com.apple.corespeechd.speechprofileresetandrebuild"
+ "com.apple.siri.bg_system_task.on-demand-cascade-set-change-processing"
+ "com.apple.siri.bg_system_task.on-demand-speech-profile-reset-and-rebuild"
+ "configName:"
+ "correctedText: "
+ "correctedTextV2: "
+ "daily_maintenance"
+ "deferred"
+ "deferredCount"
+ "deferred_resume"
+ "drivableSink completed without success for "
+ "drivableSink completed without success for %s: %s"
+ "dropAndRemoveDatabase()"
+ "dropDatabase()"
+ "durationMs"
+ "enableCalendarLocationSanitization"
+ "errorDescription"
+ "failure"
+ "failureCount"
+ "fetchDatabase(language:databaseDirectoryURL:)"
+ "fieldType not in allowlist"
+ "fillEnumerationThreshold"
+ "filtered("
+ "first_unlock"
+ "interactionOnlyRanking"
+ "lastUpdateCompletionTime"
+ "locale"
+ "maxAppsToProcess"
+ "maxDurationMs"
+ "maxInteractionsPerCandidate"
+ "maxRankedCandidatesPerApp"
+ "mobile_asset_startup"
+ "not in ranked cache"
+ "numProcessedItems: "
+ "options_changed"
+ "outcome"
+ "overallTimeout"
+ "personaId"
+ "post_install_migration"
+ "preferences_changed"
+ "present"
+ "profileSizeAfterMB"
+ "profileSizeBeforeMB"
+ "profileSizeChangeMB"
+ "profile_error"
+ "profile_missing"
+ "ranked"
+ "reason"
+ "recentUpdates"
+ "set_changes"
+ "set_update"
+ "state="
+ "status,value,cascadeItemType,fieldType,itemIdentifier,assistantSchema,extractedType\n"
+ "subscriptions_changed"
+ "success"
+ "successCount"
+ "timestamp"
+ "totalItems"
+ "totalItemsProcessed"
+ "totalUpdateCount"
+ "uncapped"
+ "updateDatabase(with:)"
+ "updateTimestampMicros"
+ "user edit event: "
+ "version_mismatch"
+ "yyyy-MM-dd_HHmmss"
- "%s (%@) Completed profile update version: %@ for categories: %@"
- "%s (%@) Completed speech profile update for category group: %@ with sets: %@"
- "%s (%@) Enumeration for set: %@ aborted: %@"
- "%s (%@) Failed to cancel categories: %@ error: %@"
- "%s (%@) Failed to commit bookmark updates: %@"
- "%s (%@) Failed to enumerate and add items from ranker: %@ error: %@"
- "%s (%@) Failed to rebuild category group: %@ with sets: %@ error: %@"
- "%s About to process updates from %ld Cascade sets for Euclid profile."
- "%s Failed to write update from Cascade to Euclid profile."
- "%s Trial updates detected for namespace (%@), rebuilding all profiles for personalization experiments."
- ", numProcessedItems: "
- "-[CESRSpeechProfileSiteManager _maintainSpeechProfilesAtAllSites:shouldDefer:]"
- "-[CESRSpeechProfileSiteManager _maintainSpeechProfilesForSiteAtURL:maintenanceLevel:shouldDefer:]"
- "-[CESRSpeechProfileSiteManager _registerTrialExperimentUpdateHandler]"
- "-[CESRSpeechProfileSiteManager _registerTrialExperimentUpdateHandler]_block_invoke"
- "-[CESRSpeechProfileSiteWriter _fullRebuildForInvalidProfileInstance:locale:options:shouldDefer:]"
- "-[CESRSpeechProfileSiteWriter _siteApplicableSets]_block_invoke"
- "-[CESRSpeechProfileSiteWriter _updateProfileInstance:categoryGroup:shouldDefer:]"
- "-[CESRSpeechProfileSiteWriter _updateRequiredProfileInstancesWithSets:shouldDefer:]"
- "-[CESRSpeechProfileSiteWriter _updateRequiredProfileInstancesWithSets:shouldDefer:]_block_invoke"
- "-[CESRSpeechProfileSiteWriter _verifyAllSpeechProfileInstances:shouldDefer:]"
- "-[CESRSpeechProfileSiteWriter _verifyProfileInstance:shouldDefer:]"
- "-[CESRSpeechProfileUpdater detectCategoriesToRebuild:error:]"
- "-[CESRSpeechProfileUpdater rebuildCategoryGroup:withSets:version:error:]"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreSpeech/CoreEmbeddedSpeechRecognition/SpeechProfile/CESREuclidProfileInstance.h"
- "=== EuclidProfile Filtering Summary ==="
- "======================================="
- "AFSpeechPhrase has multiple interpretations. 1 Best: %s, ASR Alternatives: %s"
- "Added extracted entity insertion from field. [fieldType: %hu]"
- "Allocated %ld total candidates across apps with per-app minimum of %ld."
- "CESABiomeContextualReplayRecord: audioSelectedForSampling: %{bool}d, hasVisualContext: %{bool}d"
- "Cache does not exist or is not accessible for %s: %@"
- "Cached %ld candidates for bundleId=%s."
- "Calculating remaining slots: itemLimit(%ld) - allocatedCandidates.count(%ld) = %ld"
- "Candidate map now has a count of %ld"
- "Contextual entity retrieval: skipping processing remaining items due to timeout"
- "Creating AFSpeechPackage with the following contents: %s"
- "Directory contents: %s"
- "Donating edit record to Biome: %@"
- "Failed to determine default cache directory"
- "Failed to enumerate and rank items for set %s: %@"
- "Failed to initialize shared CESRRankedEntityCache: %@"
- "Failed to list directory contents: %@"
- "Failed to process Cascade item for insertion, error: %@"
- "Fields: processed %ld, filtered %ld"
- "Found %ld sets with cached rankings."
- "FoundationModelTranscriber: No installed assets for locale: %s"
- "Hydrating rankings from cache."
- "Identifying sets with cached rankings."
- "Invalid configuration values for ranking: itemLimit=%ld, perAppEntityMinimum=%ld"
- "Mismatched candidate sizes: expected %ld, got %ld candidates."
- "No bundleId found for set %s"
- "No candidates generated from set %s - moving on."
- "No candidates generated from set enumeration across all sets."
- "No change to the Euclid profile is required for this Cascade update."
- "No valid accessible cache found for %s: %@"
- "No valid bundleID on this set - moving on."
- "Parsing SpeechProfileConfig from Trial failed, falling back to known default local path."
- "Presenting %ld Euclid alternatives of desired %ld: %s"
- "Processed field value and extracted %ld entities. [fieldType: %hu, schema: %{public}s]"
- "Processed field value, skipped extraction (already extracted upstream). [fieldType: %hu, schema: %{public}s]"
- "Processing extracted entities from LME partition: %{public}s"
- "Processing other vocabulary: %{public}s"
- "Processing raw app entities from: %{public}s"
- "Processing results for replay transcript \"%s\", original transcript \"%s\", replay type %s, for requestID %@"
- "Ranking jointly across all apps."
- "Re-ranking %ld candidates across apps."
- "Received corrected texts, interactionId: %s, correctedText: %s, correctedTextV2: %s"
- "Selecting per-app minimum already exceeds item limit - discarding remaining candidates."
- "Set alternativeSelection for CESRFidesASRRecord, interactionId: %s, alternatives: %s"
- "Set correctedText for CESRFidesASRRecord, interactionId: %s, correctedText: %s"
- "Set correctedTextV2 for CESRFidesASRRecord, interactionId: %s, correctedTextV2: %s"
- "Set has less candidates than per-app minimum - skipping calling into ranker."
- "Set recognized text: %s"
- "Sets: processed %ld, filtered %ld (itemType: %ld, LME: %ld, app: %ld)"
- "Skipping extraction - field has extractedLme configured"
- "SpeechProfileConfig unavailable - cannot check extraction mappings"
- "Starting to generate candidates from sets which do not have cached rankings."
- "Successfully loaded SpeechProfileConfig from Trial."
- "Task has been cancelled. Stopping after item enumeration and before ranking."
- "Task has been cancelled. Stopping loading from cache."
- "Task has been cancelled. Stopping ranking."
- "There are %ld remaining candidates after allocation."
- "Transcript: %s"
- "TranscriptionOption"
- "Trimmed ranked candidates to %ld with itemLimit=%ld. Candidate map size is now %ld."
- "Variants contain correctedText: %s, variants: %s"
- "com.apple.corespeechd.speechprofilesetchange"
- "com.apple.siri.CESRSpeechProfileSiteWriter"
- "incremental"
- "key value "
- "numRetrievedItems: "
- "parentEntityIdentifier"
- "sets.count=%ld, itemLimit=%ld, perAppEntityMinimum=%ld"
```
