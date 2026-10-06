## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Spotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2e90` | `0x9ab9c` | **`-0x82f4`** |
| `__TEXT.__oslogstring` | `0x5fd5` | `0x5428` | **`-0xbad`** |
| `__DATA.__bss` | `0xbd0` | `0x890` | **`-0x340`** |
| `__AUTH.__objc_data` | `0x418` | `0x130` | **`-0x2e8`** |
| `__TEXT.__cstring` | `0x3b9a` | `0x38ca` | **`-0x2d0`** |
| `__AUTH_CONST.__objc_const` | `0x4bc8` | `0x4918` | **`-0x2b0`** |
| `__TEXT.__objc_methlist` | `0x2e4c` | `0x2b9c` | **`-0x2b0`** |
| `__AUTH_CONST.__const` | `0x16d0` | `0x1460` | **`-0x270`** |
| `__AUTH_CONST.__cfstring` | `0x31a0` | `0x2f40` | **`-0x260`** |
| `__DATA_DIRTY.__objc_data` | `0xd10` | `0xf20` | **`+0x210`** |
| `__TEXT.__const` | `0x1018` | `0xe08` | **`-0x210`** |
| `__TEXT.__eh_frame` | `0x12a0` | `0x1090` | **`-0x210`** |
| `__DATA_CONST.__objc_selrefs` | `0x3070` | `0x2e70` | **`-0x200`** |
| `__TEXT.__unwind_info` | `0x1840` | `0x1678` | **`-0x1c8`** |
| `__DATA_DIRTY.__data` | `0x1b0` | `0x330` | **`+0x180`** |
| `__AUTH.__data` | `0x188` | `0x28` | **`-0x160`** |
| `__TEXT.__swift5_reflstr` | `0x453` | `0x31d` | **`-0x136`** |
| `__AUTH_CONST.__auth_got` | `0x1438` | `0x1338` | **`-0x100`** |
| `__DATA_DIRTY.__bss` | `0x5d0` | `0x6d0` | **`+0x100`** |
| `__TEXT.__gcc_except_tab` | `0x5670` | `0x558c` | **`-0xe4`** |
| `__DATA.__data` | `0x828` | `0x750` | **`-0xd8`** |
| `__DATA_CONST.__got` | `0x19b8` | `0x18f8` | **`-0xc0`** |
| `__DATA_CONST.__const` | `0xed8` | `0xe28` | **`-0xb0`** |
| `__TEXT.__swift5_typeref` | `0x86f` | `0x7cf` | **`-0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x320` | `0x298` | **`-0x88`** |
| `__TEXT.__swift5_capture` | `0x424` | `0x3a4` | **`-0x80`** |
| `__TEXT.__constg_swiftt` | `0x45c` | `0x404` | **`-0x58`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x28` | **`-0x28`** |
| `__DATA.__objc_ivar` | `0x3fc` | `0x3d8` | **`-0x24`** |
| `__AUTH_CONST.__objc_intobj` | `0x210` | `0x1f8` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0x78` | `0x60` | **`-0x18`** |
| `__TEXT.__swift5_mpenum` | `0x14` | `—` | **`-0x14`** |
| `__TEXT.__swift5_proto` | `0x60` | `0x50` | **`-0x10`** |
| `__DATA.__common` | `0x8` | `—` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x158` | `0x150` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x98` | `0x90` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x40` | `0x38` | **`-0x8`** |

### Other Changes

```diff

-2448.100.0.0.0
+2451.1.101.0.0

-  - /System/Library/Frameworks/CoreML.framework/CoreML

+  - /System/Library/PrivateFrameworks/HybridSearch.framework/HybridSearch
+  - /System/Library/PrivateFrameworks/HybridSearchAdapter.framework/HybridSearchAdapter

-  Functions: 1860
-  Symbols:   3349
-  CStrings:  1005
+  Functions: 1717
+  Symbols:   3223
+  CStrings:  935
Symbols:
+ +[SPKGenerativeSearchSiriTranscriptQuery isQuerySupported:queryContext:]
+ -[SPClientSession dealloc]
+ -[SPFederatedQueryTask prepareAndSend:force:moreComing:reason:]
+ -[SPFederatedQueryTask searchQuery:gotResultSet:replace:partiallyComplete:reason:update:complete:delayedTopHit:unchanged:forceStable:blendingDuration:geoEntityString:supportedAppScopes:showMoreInAppInfo:]
+ -[SPFederatedQueryTask sendResults:reset:partiallyComplete:update:complete:delayedTopHit:reason:]
+ -[SPFederatedQueryTask sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:reason:]
+ -[SPFederatedQueryTask serverSideDedupe:]
+ -[SPQueryTask resultQualityTier]
+ -[SPQueryTask setResultQualityTier:]
+ -[SPSearchQueryContext(GenerativeSearch) isDeviceLocked]
+ _CFNotificationCenterRemoveObserver
+ _CFPreferencesSynchronize
+ _OBJC_IVAR_$_SPQueryTask._resultQualityTier
+ _OBJC_IVAR_$_SPSiriDeservingQuery._siriDeservingDecisions
+ _SSAppExclusionsEnabled
+ _SSGetDisabledAppSet
+ _SSGetDisabledBundleSet
+ _SSInvalidateAppExclusionsDisabledIDsCache
+ _SSRemindersIntegrationAccountIdentifier
+ _SSResultTypeIsServer
+ __SPTCCSiriAccessChangedCallback
+ ___107-[SPFederatedQueryTask sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:reason:]_block_invoke
+ ___107-[SPFederatedQueryTask sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:reason:]_block_invoke_2
+ ___27-[SPClientSession activate]_block_invoke_2
+ ____SPTCCSiriAccessChangedCallback_block_invoke
+ ___block_descriptor_40_e8_32s_e39_v32?0"SFMutableResultSection"8Q16^B24ls32l8
+ _activate.sTCCObserverOnce
+ _kCFPreferencesAnyHost
+ _kCFPreferencesCurrentUser
+ _notify_cancel
+ _sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:reason:.contactKeysToFetch
+ _sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:reason:.onceToken
+ _sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:reason:.onceTokenContact
+ _sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:reason:.store
+ _symbolic SDySS_____y_____GGSg 12HybridSearch6ResultV AA11MailContentV
+ _symbolic SDySS_____y_____GGSg 12HybridSearch6ResultV AA21MailAttachmentContentV
+ _symbolic SS______y_____Gt 12HybridSearch6ResultV AA11MailContentV
+ _symbolic SS______y_____Gt 12HybridSearch6ResultV AA21MailAttachmentContentV
+ _symbolic Say_____G 19HybridSearchAdapter027TextUnderstandingExtractionB6ResultO
+ _symbolic Say_____G13conversations______17l2RankingMetadatat 19HybridSearchAdapter16TranscriptDomainO012ConversationB6ResultV 0aB017L2RankingMetadataV
+ _symbolic Say_____G7results______17l2RankingMetadatat 19HybridSearchAdapter04MailB6ResultO 0aB017L2RankingMetadataV
+ _symbolic Shy_____G 12HybridSearch10EntityTypeV
+ _symbolic Si6offset______7elementt 19HybridSearchAdapter04MailB6ResultO
+ _symbolic Si6offset______7elementt 19HybridSearchAdapter16TranscriptDomainO012ConversationB6ResultV
+ _symbolic _____ 12HybridSearch15RetrievalResultV
+ _symbolic _____ 19HybridSearchAdapter027TextUnderstandingExtractionB6ClientV
+ _symbolic _____ 19HybridSearchAdapter04MailB6ClientV
+ _symbolic _____ 19HybridSearchAdapter04MailB6ResultO
+ _symbolic _____ 9Spotlight21TranscriptCompositeIDO
+ _symbolic _____3key______5valuet 12HybridSearch014SiriTranscriptB7ContentV19SearchableAttributeO AA0B9TermScoreV
+ _symbolic _____3key______5valuet 12HybridSearch11MailContentV19SearchableAttributeO AA0B9TermScoreV
+ _symbolic _____3key______5valuet 12HybridSearch16DraftMailContentV19SearchableAttributeO AA0B9TermScoreV
+ _symbolic _____3key______5valuet 12HybridSearch21MailAttachmentContentV19SearchableAttributeO AA0B9TermScoreV
+ _symbolic _____Sg 12HybridSearch014SiriTranscriptB7ContentV
+ _symbolic _____Sg 12HybridSearch014SiriTranscriptB7ContentV06StoredE0O
+ _symbolic _____Sg 12HybridSearch33SiriTranscriptConversationContentV
+ _symbolic _____Sg 19HybridSearchAdapter33TextUnderstandingExtractionFilterO
+ _symbolic ______Sit 19HybridSearchAdapter16TranscriptDomainO012ConversationB6ResultV
+ _symbolic _____ySS_____y_____GG s18_DictionaryStorageC 12HybridSearch6ResultV AC11MailContentV
+ _symbolic _____ySS_____y_____GG s18_DictionaryStorageC 12HybridSearch6ResultV AC21MailAttachmentContentV
+ _symbolic _____y_____G 12HybridSearch15ComposableQueryV AA022TextUnderstandingEventB7ContentV
+ _symbolic _____y_____G 12HybridSearch15ComposableQueryV AA023TextUnderstandingFlightB7ContentV
+ _symbolic _____y_____G 12HybridSearch15ComposableQueryV AA033TextUnderstandingHotelReservationB7ContentV
+ _symbolic _____y_____G 12HybridSearch15ComposableQueryV AA038TextUnderstandingRestaurantReservationB7ContentV
+ _symbolic _____y_____G 12HybridSearch15ComposableQueryV AA11MailContentV
+ _symbolic _____y_____G 12HybridSearch15ComposableQueryV AA21MailAttachmentContentV
+ _symbolic _____y_____G 12HybridSearch5QueryV AA11MailContentV
+ _symbolic _____y_____G 12HybridSearch5QueryV AA21MailAttachmentContentV
+ _symbolic _____y_____G 12HybridSearch6ResultV AA014SiriTranscriptB7ContentV
+ _symbolic _____y_____G 12HybridSearch6ResultV AA022TextUnderstandingEventB7ContentV
+ _symbolic _____y_____G 12HybridSearch6ResultV AA023TextUnderstandingFlightB7ContentV
+ _symbolic _____y_____G 12HybridSearch6ResultV AA033TextUnderstandingDeliveryTrackingB7ContentV
+ _symbolic _____y_____G 12HybridSearch6ResultV AA033TextUnderstandingHotelReservationB7ContentV
+ _symbolic _____y_____G 12HybridSearch6ResultV AA038TextUnderstandingRestaurantReservationB7ContentV
+ _symbolic _____y_____G 12HybridSearch6ResultV AA039TextUnderstandingIdentificationDocumentB7ContentV
+ _symbolic _____y_____G 12HybridSearch6ResultV AA11MailContentV
+ _symbolic _____y_____G 12HybridSearch6ResultV AA16DraftMailContentV
+ _symbolic _____y_____G 12HybridSearch6ResultV AA21MailAttachmentContentV
+ _symbolic _____y_____G 12HybridSearch6ResultV AA33SiriTranscriptConversationContentV
+ _symbolic _____y_____G s11_SetStorageC 12HybridSearch10EntityTypeV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12HybridSearch10EntityTypeV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12HybridSearch14AttributeValueO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 19HybridSearchAdapter027TextUnderstandingExtractionE6ResultO
+ _symbolic _____y_____GSg 12HybridSearch6ResultV AA33SiriTranscriptConversationContentV
+ _symbolic _____y__________G 12HybridSearch14QueryPredicateO AA022TextUnderstandingEventB7ContentV19FilterableAttributeO AE010SearchableJ0O
+ _symbolic _____y__________G 12HybridSearch14QueryPredicateO AA023TextUnderstandingFlightB7ContentV19FilterableAttributeO AE010SearchableJ0O
+ _symbolic _____y__________G 12HybridSearch14QueryPredicateO AA033TextUnderstandingHotelReservationB7ContentV19FilterableAttributeO AE010SearchableK0O
+ _symbolic _____y__________G 12HybridSearch14QueryPredicateO AA038TextUnderstandingRestaurantReservationB7ContentV19FilterableAttributeO AE010SearchableK0O
+ _symbolic _____y__________G 12HybridSearch14QueryPredicateO AA11MailContentV19FilterableAttributeO AE010SearchableH0O
+ _symbolic _____y__________G 12HybridSearch14QueryPredicateO AA21MailAttachmentContentV19FilterableAttributeO AE010SearchableI0O
- +[SPSiriDeservingQuery corespotlightBundleId]
- +[SPSiriDeservingQuery createAskSiriAttributeSet]
- +[SPSiriDeservingQuery createAskSiriSectionWithResults:]
- +[SPSiriDeservingQuery initialize]
- +[SPSiriDeservingQuery isGibberish:]
- +[SPSiriDeservingQuery queryParserManager]
- +[SPSiriDeservingQuery searchDomain]
- +[SPSiriDeservingQuery sourceKind]
- -[SPClientSession disabledBundleIds]
- -[SPFederatedQueryTask prepareAndSend:isSiriDeserving:force:moreComing:reason:]
- -[SPFederatedQueryTask searchQuery:gotResultSet:replace:partiallyComplete:reason:update:complete:delayedTopHit:isSiriDeserving:unchanged:forceStable:blendingDuration:geoEntityString:supportedAppScopes:showMoreInAppInfo:]
- -[SPFederatedQueryTask sendResults:reset:partiallyComplete:update:complete:delayedTopHit:isSiriDeserving:reason:]
- -[SPFederatedQueryTask sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:isSiriDeserving:reason:]
- -[SPFederatedQueryTask serverSideDedupe:isSiriDeserving:]
- -[SPFederatedQueryTask setSiriDeservingQuery:]
- -[SPFederatedQueryTask siriDeservingDecisions]
- -[SPFederatedQueryTask siriDeservingQuery]
- -[SPFederatedQueryTask siriResult]
- -[SPQueryTask sentIsSiriDeserving]
- -[SPQueryTask setSentIsSiriDeserving:]
- -[SPQueryTask siriDeservingDecisions]
- -[SPQueryTask siriResult]
- -[SPSiriDeservingQuery .cxx_destruct]
- -[SPSiriDeservingQuery _cancel]
- -[SPSiriDeservingQuery _start]
- -[SPSiriDeservingQuery _stripAskSiriResultsFromSections:]
- -[SPSiriDeservingQuery automaticallyNotDeservingReason]
- -[SPSiriDeservingQuery cancelTimeout]
- -[SPSiriDeservingQuery configuredSiriResult]
- -[SPSiriDeservingQuery configuredSiriSection]
- -[SPSiriDeservingQuery createActivity]
- -[SPSiriDeservingQuery createCompactRankingAttrsFromAttributeSet:rankConfig:]
- -[SPSiriDeservingQuery csAttributeSet]
- -[SPSiriDeservingQuery csSearchQuery]
- -[SPSiriDeservingQuery dealloc]
- -[SPSiriDeservingQuery determineIfQueryStringIsSiriDeserving]
- -[SPSiriDeservingQuery fetchAttributes]
- -[SPSiriDeservingQuery getCorespotlightAttributesForSiriResult:]
- -[SPSiriDeservingQuery hasObservedStrongQuality]
- -[SPSiriDeservingQuery initWithUserQuery:queryGroupId:options:queryContext:]
- -[SPSiriDeservingQuery isSiriQuery]
- -[SPSiriDeservingQuery legacyIsDeservingGivenSections:topHitResult:]
- -[SPSiriDeservingQuery scoreForResult:]
- -[SPSiriDeservingQuery setConfiguredSiriResult:]
- -[SPSiriDeservingQuery setConfiguredSiriSection:]
- -[SPSiriDeservingQuery setCsAttributeSet:]
- -[SPSiriDeservingQuery setCsSearchQuery:]
- -[SPSiriDeservingQuery setHasObservedStrongQuality:]
- -[SPSiriDeservingQuery setSiriDeservingQueue:]
- -[SPSiriDeservingQuery setTimeout:]
- -[SPSiriDeservingQuery setupSiriResultWithAttributeSet:]
- -[SPSiriDeservingQuery shortCircuitSiriDeserving:]
- -[SPSiriDeservingQuery shouldReturnEarly]
- -[SPSiriDeservingQuery shouldShortCircuitSiriDeserving]
- -[SPSiriDeservingQuery siriDeservingQueue]
- -[SPSiriDeservingQuery startTimeout]
- -[SPSiriDeservingQuery timeout]
- -[SPSiriDeservingQuery topScoreForSections:]
- GCC_except_table15
- GCC_except_table17
- _NLScriptLatin
- _NSFileProtectionNone
- _OBJC_CLASS_$_MLDictionaryFeatureProvider
- _OBJC_CLASS_$_MLFeatureDescription
- _OBJC_CLASS_$_MLModel
- _OBJC_CLASS_$_MLMultiArray
- _OBJC_CLASS_$_NLContextualEmbedding
- _OBJC_CLASS_$_NLLanguageRecognizer
- _OBJC_CLASS_$_NSError
- _OBJC_CLASS_$_OS_dispatch_queue
- _OBJC_CLASS_$_QPQueryParserManager
- _OBJC_CLASS_$_SPSiriDeservingMLClassifier
- _OBJC_CLASS_$_SPUISResultBuilder
- _OBJC_CLASS_$_SSMixedRankingUtilities
- _OBJC_IVAR_$_SPFederatedQueryTask._siriDeservingQuery
- _OBJC_IVAR_$_SPQueryTask._sentIsSiriDeserving
- _OBJC_IVAR_$_SPSiriDeservingQuery._configuredSiriResult
- _OBJC_IVAR_$_SPSiriDeservingQuery._configuredSiriSection
- _OBJC_IVAR_$_SPSiriDeservingQuery._csAttributeSet
- _OBJC_IVAR_$_SPSiriDeservingQuery._csSearchQuery
- _OBJC_IVAR_$_SPSiriDeservingQuery._decisions
- _OBJC_IVAR_$_SPSiriDeservingQuery._decisionsLock
- _OBJC_IVAR_$_SPSiriDeservingQuery._hasObservedStrongQuality
- _OBJC_IVAR_$_SPSiriDeservingQuery._siriDeservingQueue
- _OBJC_IVAR_$_SPSiriDeservingQuery._timeout
- _OBJC_METACLASS_$_SPSiriDeservingMLClassifier
- _QPQueryParserCopyDefaultOptionsForContext
- _SPGetDisabledAppSet
- _SPGetDisabledBundleSet
- _SPLogForSPLogCategorySiriDeserving
- _SSForcedSpotlightMaxChars
- _SSForcedSpotlightMaxWordCount
- _SSNumberOfResultsToConsiderForSiriDeserving
- _SSSiriDeservingEarlyExitTimeout
- _SSSiriDeservingHeuristicDisabled
- _SSSiriDeservingMinChars
- _SSSiriDeservingMinWordCount
- _SSSiriDeservingRegexDisabled
- _SSSiriDeservingScoreThreshold
- _SSSpotlightBundleIdentifier
- _SSStringForSpotlightResultQuality
- _SSStringHasAtLeastWordCount
- _UTTypeItem
- __CLASS_METHODS_SPSiriDeservingMLClassifier
- __CLASS_PROPERTIES_SPSiriDeservingMLClassifier
- __DATA_SPSiriDeservingMLClassifier
- __INSTANCE_METHODS_SPSiriDeservingMLClassifier
- __IVARS_SPSiriDeservingMLClassifier
- __METACLASS_DATA_SPSiriDeservingMLClassifier
- __PROPERTIES_SPSiriDeservingMLClassifier
- ___123-[SPFederatedQueryTask sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:isSiriDeserving:reason:]_block_invoke
- ___123-[SPFederatedQueryTask sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:isSiriDeserving:reason:]_block_invoke_2
- ___30-[SPSiriDeservingQuery _start]_block_invoke
- ___36-[SPSiriDeservingQuery startTimeout]_block_invoke
- ___42+[SPSiriDeservingQuery queryParserManager]_block_invoke
- ___53+[SPSiriDeservingQuery stripAskSiriResultsFromArray:]_block_invoke
- ___64-[SPSiriDeservingQuery getCorespotlightAttributesForSiriResult:]_block_invoke
- ___64-[SPSiriDeservingQuery getCorespotlightAttributesForSiriResult:]_block_invoke_2
- ___77-[SPSiriDeservingQuery createCompactRankingAttrsFromAttributeSet:rankConfig:]_block_invoke
- ___block_descriptor_40_e8_32s_e47_v32?0"SFSearchResult_SpotlightExtras"8Q16^B24ls32l8
- ___block_descriptor_40_e8_32w_e50_v24?0"CSSearchableItemAttributeSet"8"NSError"16lw32l8
- ___block_descriptor_41_e8_32s_e5_v8?0ls32l8
- ___block_descriptor_48_e8_32s40s_e39_v32?0"SFMutableResultSection"8Q16^B24ls32l8s40l8
- ___block_descriptor_56_e8_32bs40r48w_e17_v16?0"NSError"8lw48l8r40l8s32l8
- ___swift_memcpy8_8
- __swift_stdlib_bridgeErrorToNSError
- _associated conformance 9Spotlight16QueryDestinationOSHAASQ
- _block_copy_helper
- _block_descriptor
- _block_destroy_helper
- _get_enum_tag_for_layout_string 9Spotlight25SiriDeservingMLClassifierC0D5ErrorO
- _isMacOS
- _kQPParseAttributeSearchtoolContextIdentifier
- _kQPQueryOptionEmbeddingGenerationTimeoutKey
- _kQPQueryParseOptionsEmbeddingsSFCEnabledKey
- _kQPQueryParserOptionBundleIdentifierKey
- _kQPQueryParserOptionContextIdentifierKey
- _kQPQueryParserOptionEmbeddingsEnabledKey
- _queryParserManager.manager
- _queryParserManager.onceToken
- _sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:isSiriDeserving:reason:.contactKeysToFetch
- _sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:isSiriDeserving:reason:.onceToken
- _sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:isSiriDeserving:reason:.onceTokenContact
- _sendResults:reset:partiallyComplete:update:complete:unchanged:delayedTopHit:isSiriDeserving:reason:.store
- _swift_getObjCClassFromMetadata
- _swift_isEscapingClosureAtFileLocation
- _swift_retain_x2
- _symbolic Ig_
- _symbolic SDySS_____y_____GGSg 16GenerativeSearch6ResultV AA11MailContentV
- _symbolic SDySS_____y_____GGSg 16GenerativeSearch6ResultV AA21MailAttachmentContentV
- _symbolic SS______y_____Gt 16GenerativeSearch6ResultV AA11MailContentV
- _symbolic SS______y_____Gt 16GenerativeSearch6ResultV AA21MailAttachmentContentV
- _symbolic SaySdG
- _symbolic Say_____G 23GenerativeSearchAdapter027TextUnderstandingExtractionB6ResultO
- _symbolic Say_____G So17OS_dispatch_queueC8DispatchE10AttributesV
- _symbolic Say_____G13conversations______17l2RankingMetadatat 23GenerativeSearchAdapter16TranscriptDomainO012ConversationB6ResultV 0aB017L2RankingMetadataV
- _symbolic Say_____G7results______17l2RankingMetadatat 23GenerativeSearchAdapter04MailB6ResultO 0aB017L2RankingMetadataV
- _symbolic Shy_____G 16GenerativeSearch10EntityTypeV
- _symbolic Si6offset______7elementt 23GenerativeSearchAdapter04MailB6ResultO
- _symbolic Si6offset______7elementt 23GenerativeSearchAdapter16TranscriptDomainO012ConversationB6ResultV
- _symbolic So17OS_dispatch_queueC
- _symbolic So21NLContextualEmbeddingCSg
- _symbolic So7MLModelC
- _symbolic So8NSObjectCSg
- _symbolic _____ 16GenerativeSearch15RetrievalResultV
- _symbolic _____ 23GenerativeSearchAdapter027TextUnderstandingExtractionB6ClientV
- _symbolic _____ 23GenerativeSearchAdapter04MailB6ClientV
- _symbolic _____ 23GenerativeSearchAdapter04MailB6ResultO
- _symbolic _____ 9Spotlight16QueryDestinationO
- _symbolic _____ 9Spotlight25SiriDeservingMLClassifierC
- _symbolic _____ 9Spotlight25SiriDeservingMLClassifierC0D5ErrorO
- _symbolic _____3key______5valuet 16GenerativeSearch014SiriTranscriptB7ContentV19SearchableAttributeO AA0B9TermScoreV
- _symbolic _____3key______5valuet 16GenerativeSearch11MailContentV19SearchableAttributeO AA0B9TermScoreV
- _symbolic _____3key______5valuet 16GenerativeSearch16DraftMailContentV19SearchableAttributeO AA0B9TermScoreV
- _symbolic _____3key______5valuet 16GenerativeSearch21MailAttachmentContentV19SearchableAttributeO AA0B9TermScoreV
- _symbolic _____Sg 16GenerativeSearch014SiriTranscriptB7ContentV
- _symbolic _____Sg 16GenerativeSearch014SiriTranscriptB7ContentV06StoredE0O
- _symbolic _____Sg 16GenerativeSearch33SiriTranscriptConversationContentV
- _symbolic _____Sg 23GenerativeSearchAdapter33TextUnderstandingExtractionFilterO
- _symbolic ______Sit 23GenerativeSearchAdapter16TranscriptDomainO012ConversationB6ResultV
- _symbolic _____ySS_____y_____GG s18_DictionaryStorageC 16GenerativeSearch6ResultV AC11MailContentV
- _symbolic _____ySS_____y_____GG s18_DictionaryStorageC 16GenerativeSearch6ResultV AC21MailAttachmentContentV
- _symbolic _____ySaySdGG s23_ContiguousArrayStorageC
- _symbolic _____ySdG s23_ContiguousArrayStorageC
- _symbolic _____y_____G 16GenerativeSearch15ComposableQueryV AA022TextUnderstandingEventB7ContentV
- _symbolic _____y_____G 16GenerativeSearch15ComposableQueryV AA023TextUnderstandingFlightB7ContentV
- _symbolic _____y_____G 16GenerativeSearch15ComposableQueryV AA033TextUnderstandingHotelReservationB7ContentV
- _symbolic _____y_____G 16GenerativeSearch15ComposableQueryV AA038TextUnderstandingRestaurantReservationB7ContentV
- _symbolic _____y_____G 16GenerativeSearch15ComposableQueryV AA11MailContentV
- _symbolic _____y_____G 16GenerativeSearch15ComposableQueryV AA21MailAttachmentContentV
- _symbolic _____y_____G 16GenerativeSearch5QueryV AA11MailContentV
- _symbolic _____y_____G 16GenerativeSearch5QueryV AA21MailAttachmentContentV
- _symbolic _____y_____G 16GenerativeSearch6ResultV AA014SiriTranscriptB7ContentV
- _symbolic _____y_____G 16GenerativeSearch6ResultV AA022TextUnderstandingEventB7ContentV
- _symbolic _____y_____G 16GenerativeSearch6ResultV AA023TextUnderstandingFlightB7ContentV
- _symbolic _____y_____G 16GenerativeSearch6ResultV AA033TextUnderstandingDeliveryTrackingB7ContentV
- _symbolic _____y_____G 16GenerativeSearch6ResultV AA033TextUnderstandingHotelReservationB7ContentV
- _symbolic _____y_____G 16GenerativeSearch6ResultV AA038TextUnderstandingRestaurantReservationB7ContentV
- _symbolic _____y_____G 16GenerativeSearch6ResultV AA039TextUnderstandingIdentificationDocumentB7ContentV
- _symbolic _____y_____G 16GenerativeSearch6ResultV AA11MailContentV
- _symbolic _____y_____G 16GenerativeSearch6ResultV AA16DraftMailContentV
- _symbolic _____y_____G 16GenerativeSearch6ResultV AA21MailAttachmentContentV
- _symbolic _____y_____G 16GenerativeSearch6ResultV AA33SiriTranscriptConversationContentV
- _symbolic _____y_____G s11_SetStorageC 16GenerativeSearch10EntityTypeV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 16GenerativeSearch10EntityTypeV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 16GenerativeSearch14AttributeValueO
- _symbolic _____y_____G s23_ContiguousArrayStorageC 23GenerativeSearchAdapter027TextUnderstandingExtractionE6ResultO
- _symbolic _____y_____GSg 16GenerativeSearch6ResultV AA33SiriTranscriptConversationContentV
- _symbolic _____y__________G 16GenerativeSearch14QueryPredicateO AA022TextUnderstandingEventB7ContentV19FilterableAttributeO AE010SearchableJ0O
- _symbolic _____y__________G 16GenerativeSearch14QueryPredicateO AA023TextUnderstandingFlightB7ContentV19FilterableAttributeO AE010SearchableJ0O
- _symbolic _____y__________G 16GenerativeSearch14QueryPredicateO AA033TextUnderstandingHotelReservationB7ContentV19FilterableAttributeO AE010SearchableK0O
- _symbolic _____y__________G 16GenerativeSearch14QueryPredicateO AA038TextUnderstandingRestaurantReservationB7ContentV19FilterableAttributeO AE010SearchableK0O
- _symbolic _____y__________G 16GenerativeSearch14QueryPredicateO AA11MailContentV19FilterableAttributeO AE010SearchableH0O
- _symbolic _____y__________G 16GenerativeSearch14QueryPredicateO AA21MailAttachmentContentV19FilterableAttributeO AE010SearchableI0O
- _symbolic _____yyXlG s23_ContiguousArrayStorageC
- _type_layout_string 9Spotlight25SiriDeservingMLClassifierC0D5ErrorO
CStrings:
+ "(_kMDItemBundleID=%@ && kMDItemAccountIdentifier=\"%@\")"
+ "(kMDItemDisableSearchInSpotlight!=1 || %@ || %@)"
+ "CLEAR"
+ "[qid=%lu] resultQualityTier=%ld (topHitSection=%d launchConfident=%d qualityCap=%ld lacksAnchor=%d topHitIsServer=%d blenderTier=%ld)"
+ "[qid=%lu][SPKGenerativeSearchMailQuery] Disabled: device is locked"
+ "[qid=%lu][SPKGenerativeSearchSiriTranscriptQuery] Disabled: device is locked"
+ "_kMDItemBundleID=%@"
+ "com.apple.spotlight.tcc.siriAccessChanged"
- " / "
- "(kMDItemDisableSearchInSpotlight!=1 || _kMDItemBundleID=%@)"
- "** = \"ask siri*\"cdwt"
- "6"
- "AlreadySet"
- "Ask Siri"
- "BadResults"
- "CS attribute fetch completed but self is nil"
- "Could not determine expected embedding size from model"
- "Error indexing Ask Siri item: %@"
- "Error searching Ask Siri item: %@"
- "ForcedSpotlightMaxChars"
- "ForcedSpotlightMaxWordCount"
- "None"
- "PegasusInstantAnswer"
- "Regex"
- "SPSiriDeservingQuery"
- "SiriDeservingClassifierV0107"
- "SiriDeservingMLClassifier: Could not find SiriDeservingClassifier.mlmodelc in bundle"
- "SiriDeservingMLClassifier: Failed to initialize - %@"
- "SiriDeservingMLClassifier: Failed to reload embedding model"
- "SiriDeservingMLClassifier: Reloaded embedding model"
- "SiriDeservingMLClassifier: Unloaded embedding model"
- "SiriDeservingQuery"
- "SiriTopHit"
- "Spotlight.SiriDeservingMLClassifier"
- "Timeout"
- "YES"
- "[qid=%lu] CS attribute fetch completed: attributeSet=%s, error=%@"
- "[qid=%lu] _cancel called, timeout=%s"
- "[qid=%lu] _processResponse: received PriorityTimeout, cancelled=%d"
- "[qid=%lu] _processResponse: timeout fired, query eligible — forcing isSiriDeserving=YES"
- "[qid=%lu] _start: campoEnabled=%d"
- "[qid=%lu] _start: sendEmptyResponseIfNecessary returned YES, bailing"
- "[qid=%lu] cancelTimer decision: isDeserving=%d finished=%d quality=%@ topHit=%d askSiriTop=%d strongEvidence=%d -> cancel=%d"
- "[qid=%lu] cancelling timeout: %@"
- "[qid=%lu] determineIfQueryStringIsSiriDeserving took %.3fms"
- "[qid=%lu] isDeserving: FINAL=%d (decisions=0x%lx)"
- "[qid=%lu] isDeserving: NO (%@)"
- "[qid=%lu] isDeserving: Pegasus instant answer present → siri-deserving"
- "[qid=%lu] isDeserving: askSiriWasTopResult=YES but quality=%@ >= Strong, falling through to quality path"
- "[qid=%lu] isDeserving: askSiriWasTopResult=YES, quality=%@ < Strong → returning YES"
- "[qid=%lu] isDeserving: blender path — quality=%@, threshold=%@, finished=%d → isDeserving=%d"
- "[qid=%lu] isDeserving: blender quality=%@ >= Strong but NO top hit exists — overriding to YES"
- "[qid=%lu] isDeserving: classifier=YES but no >= Strong observed → routing Siri"
- "[qid=%lu] isDeserving: firstResult=(%{sensitive}@), firstSection=%{sensitive}@, (topHit=%d, usesTopHitDisplay=%d, showAboveFilters=%d, isTophitsSection=%d) sections: %{sensitive}@"
- "[qid=%lu] isDeserving: legacy score path — topScore=%.4f, threshold=%.4f, askSiriScore=%.4f → isDeserving=%d"
- "[qid=%lu] isDeserving: quality=None (finished=%d, csPriorityComplete=%d, timedOut=%d) → siri-deserving"
- "[qid=%lu] isDeserving: quality=None on intermediate, deferring (blender=%s, askSiriWasTopResult=%d)"
- "[qid=%lu] prepareAndSend: DROPPED — infinitePatience=YES, moreComing=%d, sectionCount=%lu"
- "[qid=%lu] prepareAndSend: DROPPED — no sections to send at siri timeout (moreComing=%d)"
- "[qid=%lu] prepareAndSend: reason=SiriTimeout, moreComing=%d, infinitePatience=%d, sectionCount=%lu, isSiriDeserving=%d"
- "[qid=%lu] sendFinishedDomains: reason=SiriTimeout, force=%d, regularTokens=%ld, slowTokens=%ld, moreComing=%d, infinitePatience=%d, didSendResults=%d"
- "[qid=%lu] short circuiting siri deserving decision because: %@"
- "[qid=%lu] shouldShortCircuitSiriDeserving: NO"
- "[qid=%lu] shouldShortCircuitSiriDeserving: YES (timeout)"
- "[qid=%lu] siri timeout: not siri-deserving, skipping UI update"
- "[qid=%lu] siriDeservingResponse: isDeserving=NO"
- "[qid=%lu] siriDeservingResponse: isDeserving=YES, section=%s, siriResult=%s"
- "[qid=%lu] timeout started (%.0fms from now)"
- "[qid=%lu][SPKGenerativeSearchMailQuery] Disabled: device is locked (deviceAuthenticationState=%lu)"
- "[qid=%lu][len=%lu][finished=%d][isSiriDeserving=%d] %{sensitive}@\ndecisions=%@\nsiriScore=%.4f\nfirstResultScore=%.4f\nfirstResult:%{sensitive}@\n\n%@"
- "_kMDItemDomainIdentifier = \"%@\""
- "active"
- "classLabel_probs"
- "com.apple.CloudDocs.MobileDocumentsFileProvider"
- "com.apple.CloudDocs.iCloudDriveFileProvider"
- "com.apple.CloudDocs.iCloudDriveFileProviderManaged"
- "com.apple.FileProvider.LocalStorage"
- "com.apple.parsec.web_index"
- "com.apple.spotlight.related_search"
- "com.apple.spotlight.siri-deserving-classifier"
- "com.apple.spotlight.siriDomain"
- "n/a"
- "nil"
- "siritimeout"
- "v24@?0@\"CSSearchableItemAttributeSet\"8@\"NSError\"16"
- "v32@?0@\"SFSearchResult_SpotlightExtras\"8Q16^B24"
```
