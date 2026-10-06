## CoreEmbeddedSpeechRecognition

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/CoreEmbeddedSpeechRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3265bc` | `0x33147c` | **`+0xaec0`** |
| `__AUTH_CONST.__const` | `0x227c8` | `0x23330` | **`+0xb68`** |
| `__TEXT.__cstring` | `0xdbf4` | `0xe069` | **`+0x475`** |
| `__TEXT.__swift5_capture` | `0xc68c` | `0xcafc` | **`+0x470`** |
| `__TEXT.__unwind_info` | `0x4658` | `0x4920` | **`+0x2c8`** |
| `__TEXT.__oslogstring` | `0xcb3d` | `0xcdd5` | **`+0x298`** |
| `__AUTH_CONST.__objc_const` | `0xb380` | `0xb550` | **`+0x1d0`** |
| `__TEXT.__eh_frame` | `0x5944` | `0x5a6c` | **`+0x128`** |
| `__TEXT.__objc_methlist` | `0x4a10` | `0x4b28` | **`+0x118`** |
| `__AUTH_CONST.__objc_intobj` | `0xdb0` | `0xea0` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x4e40` | `0x4f20` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0x4385` | `0x42bc` | **`-0xc9`** |
| `__DATA.__data` | `0x23c0` | `0x2478` | **`+0xb8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3620` | `0x36d8` | **`+0xb8`** |
| `__TEXT.__gcc_except_tab` | `0xbdc` | `0xc88` | **`+0xac`** |
| `__TEXT.__swift5_reflstr` | `0x26b2` | `0x2753` | **`+0xa1`** |
| `__AUTH.__data` | `0xaf0` | `0xb88` | **`+0x98`** |
| `__TEXT.__dlopen_cstrs` | `0x6c` | `0xdc` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x19d0` | `0x1a38` | **`+0x68`** |
| `__TEXT.__const` | `0x8458` | `0x84c0` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x2550` | `0x25a8` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x1090` | `0x10e0` | **`+0x50`** |
| `__DATA.__bss` | `0x5948` | `0x5998` | **`+0x50`** |
| `__DATA_DIRTY.__data` | `0x3e80` | `0x3e30` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0x263c` | `0x2688` | **`+0x4c`** |
| `__DATA.__common` | `0x148` | `0x168` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x6d0` | `0x6e8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x504` | `0x514` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1a70` | `0x1a80` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x420` | `0x430` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x258` | `0x264` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x22c8` | `0x22d0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x200` | `0x208` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x1bb8` | `0x1bc0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x2d0` | `0x2d8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x288` | `0x28c` | **`+0x4`** |

### Other Changes

```diff

-3600.70.32.0.0
+3600.70.47.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 10426
-  Symbols:   4738
-  CStrings:  2407
+  Functions: 10611
+  Symbols:   4805
+  CStrings:  2445
Symbols:
+ +[CESRDiagnosticReporter sharedInstance]
+ +[CESRSpeechItemRanker_ASRRankedEntityTerm getRank:forItem:]
+ +[CESRSpeechProfileSelfHelper _cascadeEntitySourcesFromEnrolledCounts:]
+ +[CESRSpeechProfileSelfHelper _updateReasonForTrigger:]
+ -[CESRDiagnosticReporter .cxx_destruct]
+ -[CESRDiagnosticReporter _submitASRIssueReport:withContext:]
+ -[CESRDiagnosticReporter init]
+ -[CESRDiagnosticReporter queue]
+ -[CESRDiagnosticReporter reporter]
+ -[CESRDiagnosticReporter setQueue:]
+ -[CESRDiagnosticReporter setReporter:]
+ -[CESRDiagnosticReporter submitASRIssueReport:withContext:]
+ -[CESRDiagnosticReporter submitASRIssueReportAsync:withContext:]
+ -[CESRSpeechProfileBuilder beginWithCategoriesAndVersions:trigger:error:]
+ -[CESRSpeechProfileMetrics addEnrolledEntitiesCount:forCascadeFieldType:]
+ -[CESRSpeechProfileMetrics addEnrolledEntityForCascadeFieldType:]
+ -[CESRSpeechProfileMetrics numEnrolledEntitiesPerCascadeFieldType]
+ -[CESRSpeechProfileMetrics setSpeechProfileSize:]
+ -[CESRSpeechProfileMetrics speechProfileSize]
+ -[CESRSpeechProfileSelfHelper logASRSpeechProfileUpdateEndedWithTotalNumEntitiesReceived:entityMetrics:entityCleanupMetrics:entityExtractionMetrics:cascadeEntitySources:speechProfileSize:]
+ -[CESRSpeechProfileSelfHelper logASRSpeechProfileUpdateStartedWithTrigger:]
+ -[CESRSpeechProfileSiteManager _rebuildAllSites:trigger:]
+ -[CESRSpeechProfileSiteManager _rebuildSiteAtURL:shouldDefer:trigger:]
+ -[CESRSpeechProfileSiteManager _resetAndRebuildAllSitesWithTrigger:]
+ -[CESRSpeechProfileSiteWriter rebuildRequiredProfileInstances:trigger:]
+ -[CESRSpeechProfileUpdater rebuildCategoryGroup:withSets:version:trigger:totalItems:error:]
+ GCC_except_table1032
+ GCC_except_table1037
+ GCC_except_table1153
+ GCC_except_table1217
+ GCC_except_table1218
+ GCC_except_table1219
+ GCC_except_table1220
+ GCC_except_table1221
+ GCC_except_table1222
+ GCC_except_table1227
+ GCC_except_table1257
+ GCC_except_table1384
+ GCC_except_table1390
+ GCC_except_table1395
+ GCC_except_table1399
+ GCC_except_table1443
+ GCC_except_table1451
+ GCC_except_table1456
+ GCC_except_table1460
+ GCC_except_table257
+ GCC_except_table268
+ GCC_except_table303
+ GCC_except_table318
+ GCC_except_table355
+ GCC_except_table379
+ GCC_except_table382
+ GCC_except_table443
+ GCC_except_table464
+ GCC_except_table507
+ GCC_except_table516
+ GCC_except_table636
+ GCC_except_table639
+ GCC_except_table643
+ GCC_except_table646
+ GCC_except_table649
+ GCC_except_table652
+ GCC_except_table655
+ GCC_except_table658
+ GCC_except_table661
+ GCC_except_table747
+ GCC_except_table771
+ GCC_except_table824
+ _AnalyticsSendEventLazy
+ _CESRSpeechProfileUpdateTriggerSiriLanguageChanged
+ _CESRSpeechProfileUpdateTriggerTrialExperiment
+ _OBJC_CLASS_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ _OBJC_CLASS_$_CESRDiagnosticReporter
+ _OBJC_IVAR_$_CESRDiagnosticReporter._queue
+ _OBJC_IVAR_$_CESRDiagnosticReporter._reporter
+ _OBJC_IVAR_$_CESRSpeechProfileMetrics._numEnrolledEntitiesPerCascadeFieldType
+ _OBJC_IVAR_$_CESRSpeechProfileMetrics._speechProfileSize
+ _OBJC_METACLASS_$_CESRDiagnosticReporter
+ _SymptomDiagnosticReporterLibrary
+ _SymptomDiagnosticReporterLibraryCore.frameworkLibrary
+ __DATA__TtC29CoreEmbeddedSpeechRecognition25CESREntityRankingCAHelper
+ __METACLASS_DATA__TtC29CoreEmbeddedSpeechRecognition25CESREntityRankingCAHelper
+ __OBJC_$_CLASS_METHODS_CESRDiagnosticReporter
+ __OBJC_$_CLASS_METHODS_CESRSpeechItemRanker_ASRRankedEntityTerm
+ __OBJC_$_INSTANCE_METHODS_CESRDiagnosticReporter
+ __OBJC_$_INSTANCE_VARIABLES_CESRDiagnosticReporter
+ __OBJC_$_PROP_LIST_CESRDiagnosticReporter
+ __OBJC_CLASS_RO_$_CESRDiagnosticReporter
+ __OBJC_METACLASS_RO_$_CESRDiagnosticReporter
+ ___40+[CESRDiagnosticReporter sharedInstance]_block_invoke
+ ___55+[CESRSpeechProfileSelfHelper _updateReasonForTrigger:]_block_invoke
+ ___57-[CESRSpeechProfileSiteManager _rebuildAllSites:trigger:]_block_invoke
+ ___60-[CESRDiagnosticReporter _submitASRIssueReport:withContext:]_block_invoke
+ ___64-[CESRDiagnosticReporter submitASRIssueReportAsync:withContext:]_block_invoke
+ ___73-[CESRSpeechProfileBuilder beginWithCategoriesAndVersions:trigger:error:]_block_invoke
+ ___91-[CESRSpeechProfileUpdater rebuildCategoryGroup:withSets:version:trigger:totalItems:error:]_block_invoke
+ ___SymptomDiagnosticReporterLibraryCore_block_invoke
+ ___block_descriptor_40_e8_32s_e22_v16?0"NSDictionary"8ls32l8
+ ___block_descriptor_56_e8_32s40s48bs_e15_B16?0"NSURL"8ls32l8s48l8s40l8
+ ___block_descriptor_80_e8_32s40bs48r56r64r72r_e39_B32?0"CCSharedItem"8"NSString"16^24ls32l8r48l8r56l8r64l8r72l8s40l8
+ ___getSDRDiagnosticReporterClass_block_invoke
+ ___getkSymptomDiagnosticReplyReasonStringSymbolLoc_block_invoke
+ ___getkSymptomDiagnosticReplyReasonSymbolLoc_block_invoke
+ ___getkSymptomDiagnosticReplySuccessSymbolLoc_block_invoke
+ ___swift_memcpy33_8
+ ___swift_memcpy49_8
+ __updateReasonForTrigger:.onceToken
+ __updateReasonForTrigger:.reasonsByTrigger
+ _audit_stringSymptomDiagnosticReporter
+ _dlerror
+ _getSDRDiagnosticReporterClass.softClass
+ _getkSymptomDiagnosticReplyReasonStringSymbolLoc.ptr
+ _getkSymptomDiagnosticReplyReasonSymbolLoc.ptr
+ _getkSymptomDiagnosticReplySuccessSymbolLoc.ptr
+ _kCESRDiagnosticReporterASRSnapshotTime
+ _kCESRDiagnosticReporterASRTypeKey
+ _kCESRDiagnosticReporterCancelPreviousRecognitionTimeout
+ _kCESRDiagnosticReporterDomainKey
+ _sharedInstance.sharedReporter
+ _symbolic SDySS_____G 29CoreEmbeddedSpeechRecognition24CESREntityRankingMetricsV22DonatedAppEntityMetricV
+ _symbolic SDySS_____G 29CoreEmbeddedSpeechRecognition24CESREntityRankingMetricsV23AcceptedAppEntityMetricV
+ _symbolic SS______t 29CoreEmbeddedSpeechRecognition24CESREntityRankingMetricsV22DonatedAppEntityMetricV
+ _symbolic SS______t 29CoreEmbeddedSpeechRecognition24CESREntityRankingMetricsV23AcceptedAppEntityMetricV
+ _symbolic _____ 29CoreEmbeddedSpeechRecognition25CESREntityRankingCAHelperC
+ _symbolic _____Sg 29CoreEmbeddedSpeechRecognition24CESREntityRankingMetricsV22DonatedAppEntityMetricV
+ _symbolic _____Sg 29CoreEmbeddedSpeechRecognition24CESREntityRankingMetricsV23AcceptedAppEntityMetricV
+ _symbolic _____Sg s6UInt32V
+ _symbolic _____XDXMT 29CoreEmbeddedSpeechRecognition25CESREntityRankingCAHelperC
+ _symbolic _____ySS______G SD4KeysV 29CoreEmbeddedSpeechRecognition24CESREntityRankingMetricsV22DonatedAppEntityMetricV
+ _symbolic _____ySS______G SD4KeysV 29CoreEmbeddedSpeechRecognition24CESREntityRankingMetricsV23AcceptedAppEntityMetricV
+ _symbolic _____ySo12CCSharedItemCG s10ArraySliceV
- -[CESRSpeechItemRanker_ASRRankedEntityTerm _allCodepathsDetected]
- -[CESRSpeechProfileBuilder beginWithCategoriesAndVersions:error:]
- -[CESRSpeechProfileSelfHelper logASRSpeechProfileUpdateEndedWithTotalNumEntitiesReceived:entityMetrics:entityCleanupMetrics:entityExtractionMetrics:]
- -[CESRSpeechProfileSelfHelper logASRSpeechProfileUpdateStarted]
- -[CESRSpeechProfileSiteManager _rebuildAllSites:]
- -[CESRSpeechProfileSiteManager _rebuildSiteAtURL:shouldDefer:]
- -[CESRSpeechProfileSiteManager _resetAndRebuildAllSites]
- -[CESRSpeechProfileSiteWriter rebuildRequiredProfileInstances:]
- -[CESRSpeechProfileUpdater rebuildCategoryGroup:withSets:version:totalItems:error:]
- GCC_except_table1005
- GCC_except_table1010
- GCC_except_table1126
- GCC_except_table1190
- GCC_except_table1191
- GCC_except_table1192
- GCC_except_table1193
- GCC_except_table1194
- GCC_except_table1195
- GCC_except_table1200
- GCC_except_table1230
- GCC_except_table1357
- GCC_except_table1363
- GCC_except_table1368
- GCC_except_table1372
- GCC_except_table1416
- GCC_except_table1424
- GCC_except_table1429
- GCC_except_table1433
- GCC_except_table249
- GCC_except_table260
- GCC_except_table295
- GCC_except_table310
- GCC_except_table347
- GCC_except_table371
- GCC_except_table374
- GCC_except_table435
- GCC_except_table456
- GCC_except_table604
- GCC_except_table609
- GCC_except_table612
- GCC_except_table616
- GCC_except_table619
- GCC_except_table622
- GCC_except_table625
- GCC_except_table628
- GCC_except_table634
- GCC_except_table720
- GCC_except_table744
- GCC_except_table797
- ___49-[CESRSpeechProfileSiteManager _rebuildAllSites:]_block_invoke
- ___65-[CESRSpeechProfileBuilder beginWithCategoriesAndVersions:error:]_block_invoke
- ___83-[CESRSpeechProfileUpdater rebuildCategoryGroup:withSets:version:totalItems:error:]_block_invoke
- ___block_descriptor_48_e8_32s40bs_e15_B16?0"NSURL"8ls32l8s40l8
- ___block_descriptor_56_e8_32s40bs48r_e39_B32?0"CCSharedItem"8"NSString"16^24ls32l8r48l8s40l8
- ___swift_memcpy12_4
- _symbolic SDySSSaySo12CCSharedItemCGG
- _symbolic SDySSSaySo12CCSharedItemCy______So13CCItemMessageCXcGGG So13CCItemContentP
- _symbolic SDySSSo12CCSharedItemCy______So13CCItemMessageCXcGG So13CCItemContentP
- _symbolic SS_SaySo12CCSharedItemCGt
- _symbolic SaySo12CCSharedItemCy______So13CCItemMessageCXcGGIgo_ So13CCItemContentP
- _symbolic SaySo12CCSharedItemCy______So13CCItemMessageCXcGGz_Xx So13CCItemContentP
- _symbolic _____yS2S_G SD6ValuesV
- _symbolic _____ySSSaySo12CCSharedItemCG_G SD4KeysV
- _symbolic _____ySSSaySo12CCSharedItemCG_G SD6ValuesV
CStrings:
+ "  Unranked candidates collected: %ld"
+ "%s App Entities enrolled by rank class: ranked=%lu, incremental=%lu, unranked=%lu"
+ "%s CESRDiagnosticReporter: auto bug capture dampened for signature: %@ with error code: %@ reason: %@"
+ "%s Enrollment %@. Codepaths: didIngestAppEntities=%@, didExtractAppEntities=%@, hadRankedCandidates=%@, hadIncrementalCandidates=%@, hadUnrankedCandidates=%@"
+ "-[CESRDiagnosticReporter _submitASRIssueReport:withContext:]_block_invoke"
+ "-[CESRSpeechProfileBuilder beginWithCategoriesAndVersions:trigger:error:]_block_invoke"
+ "-[CESRSpeechProfileSiteManager _rebuildAllSites:trigger:]"
+ "-[CESRSpeechProfileSiteManager _rebuildSiteAtURL:shouldDefer:trigger:]"
+ "-[CESRSpeechProfileUpdater rebuildCategoryGroup:withSets:version:trigger:totalItems:error:]"
+ "7e22cf8b-ae4f-41d4-8f00-5cf6fa3c0065"
+ "<%@: %p; totalNumEntitiesReceived: %u; isCleanupIngestionEnabled: %d; numEntitiesContainingEmoji: %u; numEntitiesContainingSpecialCharacters: %u; numEntitiesCleaned: %u; isExtractionIngestionEnabled: %d; isExtractionSetupSuccessful: %d; numEntitiesExtractionAttempted: %u; numEntitiesContainingExtractions: %u; numEntitiesExtracted: %u; speechProfileSize: %llu; numEnrolledEntitiesPerCascadeFieldType: %@>"
+ "<no source id>"
+ "ASR"
+ "App %s summary: sought=%ld found=%ld missed=%ld fillNeeded=%ld"
+ "CESRDiagnosticReporter"
+ "Cannot clear Cascade set: empty LME template."
+ "Cleared %ld of %ld ranked-entity Cascade partitions (kept %ld)."
+ "Cleared Cascade set for LME template %s (full donation with no items)."
+ "Cleared ranked-entity Cascade partition for LME template %s."
+ "CoreSpeech"
+ "Failed to build predicate for id=%s: %@"
+ "Failed to list cache directory: %@"
+ "Failed to remove %s during full purge: %@"
+ "Removed cache file during full purge: %s"
+ "Retrieved %ld of %ld requested items for set %s."
+ "SDRDiagnosticReporter"
+ "Skipping fill-to-minimum for %s: set size %ld exceeds threshold %ld"
+ "Task cancelled during ranked-entity partition cleanup. Stopping."
+ "c186a7a1-882c-4813-86eb-97a5f0365f8d"
+ "com.apple.com.apple.siri.asr.speechprofile.AppEntityPartitionEnumerated"
+ "com.apple.siri.asr.speechprofile.AppEntitiesEnumerated"
+ "extractionOnlyTemplatesOverride"
+ "kSymptomDiagnosticReplyReason"
+ "kSymptomDiagnosticReplyReasonString"
+ "kSymptomDiagnosticReplySuccess"
+ "num_donating_first_party_apps"
+ "num_donating_third_party_apps"
+ "num_empty_title_display_representations"
+ "num_entities_present"
+ "num_ranked_entities_accepted"
+ "num_unranked_entities_accepted"
+ "siri_language_changed"
+ "softlink:r:path:/System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter"
+ "source_bundle_id"
+ "total_num_entities_accepted"
+ "total_num_entities_present"
+ "total_num_ranked_entities_accepted"
+ "total_num_unranked_entities_accepted"
+ "trial_experiment"
+ "v16@?0@\"NSDictionary\"8"
- "  Fill candidates by type: [%s]"
- "%s Enrollment %@. Codepaths: didIngestAppEntities=%@, didQualifyForAppEntityRanking=%@, didExtractAppEntities=%@"
- "-[CESRSpeechProfileBuilder beginWithCategoriesAndVersions:error:]_block_invoke"
- "-[CESRSpeechProfileSiteManager _rebuildAllSites:]"
- "-[CESRSpeechProfileSiteManager _rebuildSiteAtURL:shouldDefer:]"
- "-[CESRSpeechProfileUpdater rebuildCategoryGroup:withSets:version:totalItems:error:]"
- "<%@: %p; totalNumEntitiesReceived: %u; isCleanupIngestionEnabled: %d; numEntitiesContainingEmoji: %u; numEntitiesContainingSpecialCharacters: %u; numEntitiesCleaned: %u; isExtractionIngestionEnabled: %d; isExtractionSetupSuccessful: %d; numEntitiesExtractionAttempted: %u; numEntitiesContainingExtractions: %u; numEntitiesExtracted: %u>"
- "A"
- "App %s summary: sought=%ld found=%ld missed=%ld fillNeeded=%ld foundTypes=[%s]"
- "App %s summary: sought=0 found=0 missed=0 fillNeeded=0 foundTypes=[] (enumeration skipped: interactionOnlyRanking + no ranked IDs)"
- "Failed to list cache directory for purge: %@"
- "corespeechd"
```
