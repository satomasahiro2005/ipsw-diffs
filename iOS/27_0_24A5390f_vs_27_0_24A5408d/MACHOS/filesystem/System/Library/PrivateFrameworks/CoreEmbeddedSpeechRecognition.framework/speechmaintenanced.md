## speechmaintenanced

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/speechmaintenanced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f34c` | `0x479e0` | **`+0x8694`** |
| `__TEXT.__eh_frame` | `0x20c0` | `0x26f8` | **`+0x638`** |
| `__TEXT.__oslogstring` | `0x253e` | `0x288e` | **`+0x350`** |
| `__TEXT.__unwind_info` | `0xa08` | `0xb80` | **`+0x178`** |
| `__DATA.__data` | `0xd90` | `0xf00` | **`+0x170`** |
| `__DATA_CONST.__const` | `0xfa8` | `0x1110` | **`+0x168`** |
| `__DATA.__objc_const` | `0xc30` | `0xd88` | **`+0x158`** |
| `__TEXT.__const` | `0xbf0` | `0xd40` | **`+0x150`** |
| `__TEXT.__swift5_typeref` | `0x82b` | `0x939` | **`+0x10e`** |
| `__TEXT.__cstring` | `0x3b5` | `0x4b5` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0xe01` | `0xf01` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0x67c` | `0x72c` | **`+0xb0`** |
| `__TEXT.__swift5_capture` | `0x474` | `0x4f8` | **`+0x84`** |
| `__DATA.__bss` | `0x580` | `0x600` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x9e0` | `0xa60` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x1790` | `0x17f0` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x4d0` | `0x52c` | **`+0x5c`** |
| `__TEXT.__swift5_fieldmd` | `0x4c8` | `0x520` | **`+0x58`** |
| `__TEXT.__objc_classname` | `0x2c7` | `0x317` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x150` | `0x18c` | **`+0x3c`** |
| `__DATA_CONST.__auth_got` | `0xbd0` | `0xc00` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x370` | `0x390` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2c8` | `0x2e0` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x98` | `0xb0` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0xb4` | `0xcc` | **`+0x18`** |
| `__DATA.__common` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x3c` | `0x40` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x44` | `0x48` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-3600.70.32.0.0
+3600.70.47.0.0

-  Functions: 641
-  Symbols:   546
-  CStrings:  378
+  Functions: 726
+  Symbols:   555
+  CStrings:  402
Symbols:
+ _$s29CoreEmbeddedSpeechRecognition0C13ProfileConfigC15EntityFilteringC23extractionOnlyTemplatesShySSGvg
+ _$s29CoreEmbeddedSpeechRecognition11CESRCascadeO27clearRankedEntityPartitions18excludingTemplatesyShySSG_tYaKFZ
+ _$s29CoreEmbeddedSpeechRecognition11CESRCascadeO27clearRankedEntityPartitions18excludingTemplatesyShySSG_tYaKFZTu
+ _$s29CoreEmbeddedSpeechRecognition11CESRCascadeO30removeAllRankedEntityTermItemsyyYaKFZ
+ _$s29CoreEmbeddedSpeechRecognition11CESRCascadeO30removeAllRankedEntityTermItemsyyYaKFZTu
+ _$s29CoreEmbeddedSpeechRecognition21CESRAppEntityResolverC18appIntentsProperty03forF2Id8inDomain15withIndexingKeySSSgSS_S2StF
+ _$s29CoreEmbeddedSpeechRecognition21CESRRankedEntityCacheC09removeAllG5FilesyyF
+ _$s29CoreEmbeddedSpeechRecognition24CESREntityRankingMetricsV22DonatedAppEntityMetricVN
+ _$s29CoreEmbeddedSpeechRecognition24CESREntityRankingMetricsV23AcceptedAppEntityMetricVN
+ _$s29CoreEmbeddedSpeechRecognition25CESREntityRankingCAHelperC03logF5Ended7metricsyAA0eF7MetricsV_tF
+ _$s29CoreEmbeddedSpeechRecognition25CESREntityRankingCAHelperCACycfc
+ _$s29CoreEmbeddedSpeechRecognition25CESREntityRankingCAHelperCMa
- _$sSo5CCSetC29CoreEmbeddedSpeechRecognitionSo13CCItemContent_So0F7MessageCXcRszSo0f4MetaG0_AFXcRs_rlE15isHighVolumeSetSbyF
- _AFIsLinwoodCapableIgnoringUserSetting
- _CESRSpeechCategoryName_notetitle
CStrings:
+ "Added items for cascade set %@ exceed the per-app limit (%ld). Skipping; deferred to the next full rebuild."
+ "Cancelled speech maintenance task %s."
+ "Cleared entity allocation change registry during entity allocation cleanup."
+ "Entity allocation enablement transition detected: disabling entity processing."
+ "Entity allocation enablement transition detected: enabling entity processing."
+ "Entity allocation was re-enabled before the scheduled cleanup ran; skipping cleanup."
+ "Failed to cancel speech maintenance task %s with error: %@"
+ "Failed to clear entity allocation change registry during entity allocation cleanup: %@"
+ "Failed to clear stale ranked-entity partitions: %@"
+ "Failed to construct EntityManager for entity allocation cleanup: %@"
+ "Failed to perform NCBVQ profile generation on Cascade update for sets: %s, error: %@"
+ "Failed to perform NCBVQ profile generation on model catalog asset notification, error: %@"
+ "Failed to remove ranked entity items from Cascade during entity allocation cleanup: %@"
+ "Failed to submit speech maintenance task %s with error: %@"
+ "Final entity limit dropped %ld entities (from %ld to %ld)."
+ "Ranked entity cache unavailable; skipping cache purge during entity allocation cleanup."
+ "Speech maintenance task %s has been scheduled."
+ "Speech maintenance task %s has no pending request to cancel."
+ "_TtC18speechmaintenanced39SMEntityAllocationEnablementCoordinator"
+ "cancelTaskRequestWithIdentifier:error:"
+ "com.apple.modelcatalog.asset-set-updated.com.apple.modelcatalog"
+ "com.apple.siri.bg_system_task.on-demand-ranking-cleanup"
+ "com.apple.siri.entity-allocation-ranking-or-cleanup"
+ "com.apple.siri.orchestration.capabilities.didChange"
+ "extractionOnlyTemplates"
+ "isDailyRankingTaskRegistered"
+ "isEntityAllocationEnabled"
+ "onDisableTransition"
+ "onEnableTransition"
+ "setGroupConcurrencyLimit:"
+ "setGroupName:"
+ "setScheduleAfter:"
- "Bookmark is nil. Incremental updates for this set will be skipped until the next full rebuild."
- "Enumerated %ld removed items from cascade set %@."
- "Failed to perform NCBVQProfileUpdate for sets %s: %@"
- "Failed to submit speech maintenance task with error: %@"
- "Number of added items (%ld) from cascade set %@ exceeds the per-app limit. They will not be processed for incremental allocation."
- "Skipping incremental allocation for high volume set=%@."
- "Speech maintenance task has been scheduled."
- "deviceSupportsLinwood: %{bool}d"
```
