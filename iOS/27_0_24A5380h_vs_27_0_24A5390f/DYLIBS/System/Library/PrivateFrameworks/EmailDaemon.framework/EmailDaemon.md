## EmailDaemon

> `/System/Library/PrivateFrameworks/EmailDaemon.framework/EmailDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28b224` | `0x28d200` | **`+0x1fdc`** |
| `__AUTH_CONST.__const` | `0x749b` | `0x76fb` | **`+0x260`** |
| `__TEXT.__cstring` | `0x28c8a` | `0x28eaa` | **`+0x220`** |
| `__AUTH_CONST.__cfstring` | `0xfae0` | `0xfce0` | **`+0x200`** |
| `__TEXT.__oslogstring` | `0x1af6f` | `0x1b12f` | **`+0x1c0`** |
| `__AUTH_CONST.__objc_const` | `0x22538` | `0x226a8` | **`+0x170`** |
| `__TEXT.__gcc_except_tab` | `0x4a1f0` | `0x4a340` | **`+0x150`** |
| `__TEXT.__swift5_capture` | `0x730` | `0x7fc` | **`+0xcc`** |
| `__TEXT.__objc_methlist` | `0x1333c` | `0x133dc` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x173d` | `0x17db` | **`+0x9e`** |
| `__TEXT.__unwind_info` | `0x110e8` | `0x11170` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0xb0b8` | `0xb128` | **`+0x70`** |
| `__TEXT.__const` | `0x51cc` | `0x522c` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xb48` | `0xb98` | **`+0x50`** |
| `__DATA.__data` | `0x3960` | `0x39a0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x9480` | `0x94b8` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x17d8` | `0x17f8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1e30` | `0x1e50` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x10b0` | `0x10d0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x10bf` | `0x10df` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1638` | `0x1654` | **`+0x1c`** |
| `__DATA.__objc_ivar` | `0x1470` | `0x1484` | **`+0x14`** |
| `__TEXT.__swift5_builtin` | `0xf0` | `0x104` | **`+0x14`** |
| `__TEXT.__eh_frame` | `0x16c8` | `0x16b8` | **`-0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x60` | `0x58` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x9d8` | `0x9e0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x420` | `0x428` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x118` | `0x120` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x5d0` | `0x5d8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1d0` | `0x1d4` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x40` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x44` | `0x48` | **`+0x4`** |

### Other Changes

```diff

-3895.100.17.2.1
+3897.100.8.2.5

-  Functions: 11472
-  Symbols:   15115
-  CStrings:  5447
+  Functions: 11529
+  Symbols:   15156
+  CStrings:  5469
Symbols:
+ -[EDDiagnosticInfoGatherer _promptUserForIndexingDiagnosticsConsent]
+ -[EDDiagnosticInfoGatherer _shouldCollectIndexingDiagnostics]
+ -[EDDiagnosticInfoGatherer databaseStatisticsForcingRefresh:completionHandler:]
+ -[EDFeatureSettingsAnalyticsCollector coreAnalyticsPeriodicEvent]
+ -[EDFeatureSettingsAnalyticsCollector initWithAnalyticsCollector:]
+ -[EDFeatureSettingsAnalyticsCollector(PlatformFields) addPlatformSpecificFieldsToEvent:]
+ -[EDPersistence lastSpotlightReportDate]
+ -[EDPersistence persistenceStatisticsForcingRefresh:]
+ -[EDPersistence searchableIndexStatisticsForcingRefresh:]
+ -[EDPersistence setLastSpotlightReportDate:]
+ -[EDPersistenceDatabaseConnection postTransactionBlocks]
+ -[EDPersistenceDatabaseConnection setPostTransactionBlocks:]
+ -[EDSearchableIndexPersistence _computeStatistics]
+ -[EDSearchableIndexPersistence logStatisticsSummary:]
+ -[EDSearchableIndexPersistence queueRedonationForDownloadedMessagesWithUnindexedBodiesWithCancelationToken:]
+ -[EDSearchableIndexPersistence statisticsForcingRefresh:]
+ _CFUserNotificationDisplayAlert
+ _EDFeatureSettingOff
+ _EDFeatureSettingOn
+ _EMPersistenceStatisticsKeyCalculatedAt
+ _EMUserDefaultHideMessageListAvatar
+ _OBJC_CLASS_$_EDFeatureSettingsAnalyticsCollector
+ _OBJC_IVAR_$_EDPersistence._lastSpotlightReportDate
+ _OBJC_IVAR_$_EDPersistenceDatabaseConnection._postTransactionBlocks
+ _OBJC_IVAR_$_EDSearchableIndexPersistence._cachedStatistics
+ _OBJC_IVAR_$_EDSearchableIndexPersistence._inflightStatisticsFuture
+ _OBJC_IVAR_$_EDSearchableIndexPersistence._statisticsLock
+ _OBJC_METACLASS_$_EDFeatureSettingsAnalyticsCollector
+ __OBJC_$_INSTANCE_METHODS_EDFeatureSettingsAnalyticsCollector(PlatformFields)
+ __OBJC_$_PROP_LIST_EDFeatureSettingsAnalyticsCollector
+ __OBJC_CLASS_PROTOCOLS_$_EDFeatureSettingsAnalyticsCollector
+ __OBJC_CLASS_RO_$_EDFeatureSettingsAnalyticsCollector
+ __OBJC_METACLASS_RO_$_EDFeatureSettingsAnalyticsCollector
+ ___108-[EDSearchableIndexPersistence queueRedonationForDownloadedMessagesWithUnindexedBodiesWithCancelationToken:]_block_invoke
+ ___50-[EDSearchableIndexPersistence _computeStatistics]_block_invoke
+ ___79-[EDDiagnosticInfoGatherer databaseStatisticsForcingRefresh:completionHandler:]_block_invoke
+ ___block_descriptor_49_ea8_32s40bs_e5_v8?0ls32l8s40l8
+ ___swift_closure_destructor.25Tm
+ ___swift_closure_destructor.44Tm
+ ___swift_memcpy4_4
+ _flat unique So12EFCancelable_p
+ _symbolic SbIegd_
+ _symbolic Sbz_Xx
+ _symbolic So26EDSearchableIndexTelemetryCSgXwz_Xx
+ _symbolic So46EDSearchableIndexDownloadStatisticsPersistenceC
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic ______p So12EFCancelableP
+ _symbolic _____ySb_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _type_layout_string So16os_unfair_lock_sV
- +[CSDonationProgress(EDPartialBackport) ed_donationProgressWithAllKnownItems:itemsNeedingDonation:donatedItems:partiallyDonatedItems:itemsNeedingDonationForRedonationRequests:dateOfNewestUndonatedItem:allKnownItemsIsPartial:]
- -[EDPersistenceDatabase performBlockAfterTransaction:]
- -[EDSearchableIndexPersistence queueRedonationForDownloadedMessagesWithUnindexedBodies]
- __OBJC_$_CATEGORY_CLASS_METHODS_CSDonationProgress_$_EDPartialBackport
- __OBJC_$_CATEGORY_CSDonationProgress_$_EDPartialBackport
- ___42-[EDSearchableIndexPersistence statistics]_block_invoke
- ___68-[EDDiagnosticInfoGatherer databaseStatisticsWithCompletionHandler:]_block_invoke
- ___87-[EDSearchableIndexPersistence queueRedonationForDownloadedMessagesWithUnindexedBodies]_block_invoke
CStrings:
+ "-[EDPersistence persistenceStatisticsForcingRefresh:]"
+ "-[EDPersistence searchableIndexStatisticsForcingRefresh:]"
+ "-[EDSearchableIndexPersistence _computeStatistics]"
+ "-[EDSearchableIndexPersistence queueRedonationForDownloadedMessagesWithUnindexedBodiesWithCancelationToken:]"
+ "Collect"
+ "Collect Mail Diagnostics?"
+ "Diagnostics consent prompt failed or timed out (error %d); skipping indexing diagnostics."
+ "Expiring %{public}s task; deferring and asking maintenance work to stop"
+ "IncludeAttachmentReplies"
+ "IncludeAttachmentRepliesAlways"
+ "IncludeAttachmentRepliesAsk"
+ "IncludeAttachmentRepliesNever"
+ "IncludeAttachmentRepliesWhenAdding"
+ "Never ask again"
+ "Reporting donation progress failure (reason %ld): %{public}@"
+ "Search index statistics (from cache, calculated %{public}@): indexable %ld, headers donated %ld, bodies donated %ld"
+ "Skip this time"
+ "Skipping Spotlight progress report: on battery, last report %.0fs ago"
+ "Statistics request coalesced onto an in-flight scan"
+ "Statistics request initiated a new scan"
+ "Statistics request served from cache"
+ "[Internal Only] A Tap-to-Radar being collected on this device requested Mail indexing logs, which scans every message to build indexing diagnostics. This can use significant CPU and battery for a few minutes."
+ "categorizationEnabled"
+ "com.apple.mail.feature.settings"
+ "com.apple.mail.searchableIndex.maintenanceCancelation"
+ "contactPhotosEnabled"
+ "includeAttachmentWithRepliesSelection"
+ "mailPrivacyProtectionEnabled"
+ "organizeByConversationEnabled"
+ "performBlockAfterTransaction called while not in a transaction — executing immediately"
+ "performBlockAfterTransaction: called with nil block"
+ "\x81"
- "-[EDPersistence persistenceStatistics]"
- "-[EDPersistence searchableIndexStatistics]"
- "-[EDSearchableIndexPersistence queueRedonationForDownloadedMessagesWithUnindexedBodies]"
- "-[EDSearchableIndexPersistence statistics]"
- "Donation progress: allKnownItemsIsPartial: initializer unavailable, deferring to legacy initializer (flag dropped)"
- "Donation progress: using new allKnownItemsIsPartial: initializer"
- "Failed to report donation progress: %{public}@"
- "_EDPersistencePostTransactionBlocks"
- "performBlockAfterTransaction called while not in a transaction"
- "performBlockAfterTransaction not supported (unit test?)."
```
