## Email

> `/System/Library/PrivateFrameworks/Email.framework/Email`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3e58` | `0xd6ea0` | **`+0x3048`** |
| `__DATA.__bss` | `0x1ce0` | `0x23c0` | **`+0x6e0`** |
| `__TEXT.__const` | `0x14bc` | `0x18bc` | **`+0x400`** |
| `__DATA_DIRTY.__objc_data` | `0x3470` | `0x3808` | **`+0x398`** |
| `__AUTH.__objc_data` | `0x470` | `0x1b0` | **`-0x2c0`** |
| `__AUTH_CONST.__const` | `0x1bb0` | `0x1e40` | **`+0x290`** |
| `__TEXT.__oslogstring` | `0x6583` | `0x67a3` | **`+0x220`** |
| `__TEXT.__swift5_fieldmd` | `0x4c4` | `0x610` | **`+0x14c`** |
| `__TEXT.__unwind_info` | `0x8008` | `0x8140` | **`+0x138`** |
| `__TEXT.__eh_frame` | `0x200` | `0x328` | **`+0x128`** |
| `__TEXT.__cstring` | `0xc0cf` | `0xc1df` | **`+0x110`** |
| `__TEXT.__gcc_except_tab` | `0x1ad64` | `0x1ae48` | **`+0xe4`** |
| `__TEXT.__swift5_reflstr` | `0x32f` | `0x40f` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x464` | `0x538` | **`+0xd4`** |
| `__AUTH_CONST.__cfstring` | `0xa360` | `0xa420` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x3cc` | `0x486` | **`+0xba`** |
| `__DATA.__data` | `0x2978` | `0x2a28` | **`+0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x16d88` | `0x16e08` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0xcfac` | `0xd02c` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0xb20` | `0xb88` | **`+0x68`** |
| `__TEXT.__swift5_proto` | `0xf8` | `0x130` | **`+0x38`** |
| `__DATA_CONST.__got` | `0xc70` | `0xc98` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x6248` | `0x6270` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0x230` | `0x250` | **`+0x20`** |
| `__TEXT.__ustring` | `0x154` | `0x170` | **`+0x1c`** |
| `__TEXT.__swift5_types` | `0x68` | `0x7c` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x4598` | `0x45a8` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0xac0` | `0xad0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x38` | `0x48` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x580` | `0x588` | **`+0x8`** |

### Other Changes

```diff

-3893.100.7.0.0
+3895.100.17.2.1

-  Functions: 5026
-  Symbols:   8894
-  CStrings:  2130
+  Functions: 5136
+  Symbols:   8936
+  CStrings:  2147
Symbols:
+ -[EMDiagnosticInfoGatherer downloadLimitDiagnosticsWithCompletionHandler:]
+ -[EMDiagnosticInfoGatherer(DonationVisualizationDebugging) donationVisualizationDataWithCompletionHandler:]
+ -[EMDiagnosticInfoGatherer(DonationVisualizationDebugging) donationVisualizationMessageDetailsForDatabaseID:completionHandler:]
+ _EMGenerativeModelsEnhancedSiriAvailabilityDidChange
+ _EMIsCurrentUserManagedAppleAccountForShare
+ _EMPersistenceStatisticsKeyAllKnownItemsIsPartial
+ _EMSearchIndexAgeBucketBodiesIndexedMetric
+ _EMSearchIndexAgeBucketHeadersIndexedMetric
+ _EMSearchIndexAgeBucketKeyPrefix
+ _EMSearchIndexAgeBucketTotalMetric
+ _EMStartObservingEnhancedSiriAvailability
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _OBJC_CLASS_$__TtC5Email34EMEnhancedSiriAvailabilityObserver
+ _OBJC_METACLASS_$__TtC5Email34EMEnhancedSiriAvailabilityObserver
+ _OUTLINED_FUNCTION_6
+ __CLASS_METHODS__TtC5Email34EMEnhancedSiriAvailabilityObserver
+ __DATA__TtC5Email34EMEnhancedSiriAvailabilityObserver
+ __INSTANCE_METHODS__TtC5Email34EMEnhancedSiriAvailabilityObserver
+ __IVARS__TtC5Email34EMEnhancedSiriAvailabilityObserver
+ __METACLASS_DATA__TtC5Email34EMEnhancedSiriAvailabilityObserver
+ __OBJC_$_INSTANCE_METHODS_EMDiagnosticInfoGatherer(DonationVisualizationDebugging)
+ ___80-[EMHideMyEmail generateReplyToEmailForRecipient:hmeAddress:account:completion:]_block_invoke_3
+ ___swift_destroy_boxed_opaque_existential_1
+ ___swift_memcpy0_1
+ ___swift_memcpy80_8
+ ___swift_memcpy8_8
+ _associated conformance 5Email26EMDownloadLimitDiagnosticsV10CodingKeys33_3EAB6CF011A973CBB1484E4E568085C7LLOSHAASQ
+ _associated conformance 5Email26EMDownloadLimitDiagnosticsV10CodingKeys33_3EAB6CF011A973CBB1484E4E568085C7LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 5Email26EMDownloadLimitDiagnosticsV10CodingKeys33_3EAB6CF011A973CBB1484E4E568085C7LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 5Email26EMDownloadLimitDiagnosticsV7AccountV10CodingKeys33_3EAB6CF011A973CBB1484E4E568085C7LLOSHAASQ
+ _associated conformance 5Email26EMDownloadLimitDiagnosticsV7AccountV10CodingKeys33_3EAB6CF011A973CBB1484E4E568085C7LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 5Email26EMDownloadLimitDiagnosticsV7AccountV10CodingKeys33_3EAB6CF011A973CBB1484E4E568085C7LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _swift_initStackObject
+ _swift_setDeallocating
+ _symbolic Say_____G 5Email26EMDownloadLimitDiagnosticsV7AccountV
+ _symbolic Sb
+ _symbolic _____ 5Email26EMDownloadLimitDiagnosticsV
+ _symbolic _____ 5Email26EMDownloadLimitDiagnosticsV10CodingKeys33_3EAB6CF011A973CBB1484E4E568085C7LLO
+ _symbolic _____ 5Email26EMDownloadLimitDiagnosticsV7AccountV
+ _symbolic _____ 5Email26EMDownloadLimitDiagnosticsV7AccountV10CodingKeys33_3EAB6CF011A973CBB1484E4E568085C7LLO
+ _symbolic _____ 5Email34EMEnhancedSiriAvailabilityObserverC
+ _symbolic ______ypt s11AnyHashableV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 5Email26EMDownloadLimitDiagnosticsV10CodingKeys33_3EAB6CF011A973CBB1484E4E568085C7LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 5Email26EMDownloadLimitDiagnosticsV7AccountV10CodingKeys33_3EAB6CF011A973CBB1484E4E568085C7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 5Email26EMDownloadLimitDiagnosticsV10CodingKeys33_3EAB6CF011A973CBB1484E4E568085C7LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 5Email26EMDownloadLimitDiagnosticsV7AccountV10CodingKeys33_3EAB6CF011A973CBB1484E4E568085C7LLO
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC s11AnyHashableV
+ _symbolic _____y_____ypG s18_DictionaryStorageC s11AnyHashableV
+ _type_layout_string 5Email26EMDownloadLimitDiagnosticsV
+ _type_layout_string 5Email26EMDownloadLimitDiagnosticsV7AccountV
- _EMIsManagedAppleAccount
- _EMPersistenceStatisticsKeyPercentIndexedLastMonth
- _EMPersistenceStatisticsKeyPercentIndexedLastTwoDays
- _EMPersistenceStatisticsKeyPercentUnindexedBodiesInFrecentMailboxes
- _EMUserDefaultHasCompletedAppleIntelligenceOnboarding
- __OBJC_$_INSTANCE_METHODS_EMDiagnosticInfoGatherer
- _get_type_metadata 15Synchronization5MutexVy5Email21ActivityStateObserverC0E0OG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "Categorizing…"
+ "EMEnhancedSiriIsAvailable"
+ "EMGenerativeModelsEnhancedSiriAvailabilityDidChange"
+ "EMHMERecipientCreationRequest.m"
+ "Enhanced Siri availability changed to isAvailable=%{bool}d; posting EMGenerativeModelsEnhancedSiriAvailabilityDidChange"
+ "Failed to parse HME address string: %{private}@"
+ "Generating replyTo for recipient:%{private}@ rawHME:%{private}@ processedHME:%{private}@"
+ "HME address parsed but has no simpleAddress: localPart=%{private}@ domain=%{private}@ isGroup=%{BOOL}d"
+ "Invalid HME address format"
+ "Missing required fields for HME request: hmeAddress=%{private}@ recipient=%{private}@"
+ "Unable to create a secure connection to the server (“%1$@” %2$@)."
+ "ageBucket"
+ "allKnownItemsIsPartial"
+ "bodiesIndexed"
+ "generateReplyToEmailForRecipient: missing required argument — account=%{public}@ recipientAddress=%{private}@ processedHMEAddress=%{private}@"
+ "headersIndexed"
+ "hmeAddress"
+ "messagesDownloadedCount"
+ "olderMessagesIndexedCount"
+ "overQuotaCount24h"
+ "recipient"
+ "serverRecentlyUnavailable"
+ "serverUnavailableCount24h"
+ "total"
- "% indexed last 2 days"
- "% indexed last month"
- "% unindexed bodies in frecent"
- "Categorizing..."
- "HasCompletedAppleIntelligenceOnboarding"
- "ReplyTo address Request %@ for recipient:%@ hmeAddress:%@"
- "Unable to create a secure connection to the server (”%1$@” %2$@)."
```
