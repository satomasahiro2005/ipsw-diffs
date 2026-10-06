## SpotlightServices

> `/System/Library/PrivateFrameworks/SpotlightServices.framework/SpotlightServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x147d20` | `0x15ef68` | **`+0x17248`** |
| `__AUTH_CONST.__objc_const` | `0x158b0` | `0x18168` | **`+0x28b8`** |
| `__TEXT.__objc_methlist` | `0xc970` | `0xe5d0` | **`+0x1c60`** |
| `__AUTH_CONST.__cfstring` | `0x36040` | `0x36c20` | **`+0xbe0`** |
| `__DATA_CONST.__objc_selrefs` | `0x83b8` | `0x8d68` | **`+0x9b0`** |
| `__TEXT.__cstring` | `0x3a1ba` | `0x3a94a` | **`+0x790`** |
| `__AUTH.__objc_data` | `0x1288` | `0x1828` | **`+0x5a0`** |
| `__TEXT.__unwind_info` | `0x2e10` | `0x31d0` | **`+0x3c0`** |
| `__TEXT.__oslogstring` | `0xb77b` | `0xb9cb` | **`+0x250`** |
| `__DATA.__objc_ivar` | `0x13d8` | `0x15b0` | **`+0x1d8`** |
| `__DATA_CONST.__const` | `0xfff0` | `0x100d0` | **`+0xe0`** |
| `__DATA_CONST.__objc_classlist` | `0x540` | `0x5d0` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x1b90` | `0x1c18` | **`+0x88`** |
| `__DATA_CONST.__objc_superrefs` | `0x3a0` | `0x428` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0x2aa0` | `0x2b20` | **`+0x80`** |
| `__TEXT.__dlopen_cstrs` | `0xd1` | `0x12f` | **`+0x5e`** |
| `__TEXT.__gcc_except_tab` | `0x5010` | `0x5068` | **`+0x58`** |
| `__DATA.__bss` | `0x5f8` | `0x638` | **`+0x40`** |
| `__DATA_DIRTY.__bss` | `0x5498` | `0x54b8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xf30` | `0xf40` | **`+0x10`** |

### Other Changes

```diff

-2444.104.0.0.0
+2448.100.0.0.0

-  - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices

-  Functions: 5806
-  Symbols:   10580
-  CStrings:  7824
+  Functions: 6436
+  Symbols:   11464
+  CStrings:  7931
Symbols:
+ +[FeatureStoreLogger _instrumentableEventQueue]
+ +[FeatureStoreLogger insertSpotlightInstrumentableEvent:]
+ +[SPOTLIGHTINSTRUMENTATIONMatchInfo valueArrayType]
+ +[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent rrfScoredItemsType]
+ +[SPOTLIGHTINSTRUMENTATIONRetrievedItem additionalMetadataType]
+ +[SPOTLIGHTINSTRUMENTATIONRetrievedItem matchInfoType]
+ +[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent retrievedItemsType]
+ +[SSEngagementPolicy isCampoEnabledOverrideActiveForTesting]
+ +[SSEngagementPolicy resetCampoEnabledOverrideForTesting]
+ +[SSEngagementPolicy setCampoEnabledOverrideForTesting:]
+ +[SSEngagementPolicy shouldSuppressEngagementForResult:isSearchToolClient:]
+ -[PRSRankingItem _instrumentableDates]
+ -[PRSRankingItem _instrumentableDocumentSignals]
+ -[PRSRankingItem _instrumentableLink]
+ -[PRSRankingItem _instrumentableScore]
+ -[PRSRankingItem _normalizeNameForLogging:]
+ -[PRSRankingItem _resolvedName]
+ -[PRSRankingItem instrumentableItemIdentifiers]
+ -[PRSRankingItem instrumentableRetrievedItem]
+ -[PRSRankingItem setSuppressEngagement:]
+ -[PRSRankingItem suppressEngagement]
+ -[PRSRankingItemRanker cerberusQUSignalsEvent:signalsPerTool:]
+ -[SFSearchResult_SpotlightExtras applyEngagementPolicyWithIsSearchToolClient:]
+ -[SFSearchResult_SpotlightExtras setSuppressEngagement:]
+ -[SFSearchResult_SpotlightExtras suppressEngagement]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata description]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata hasKey]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata hasValue]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata hash]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata key]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata setKey:]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata setValue:]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata value]
+ -[SPOTLIGHTINSTRUMENTATIONAdditionalMetadata writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent description]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent earliestTokenFromQu]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasEarliestTokenFromQu]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasHasQueryContextEmbedding]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasInferredIntentType]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasIntentType]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasIsFinal]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasLatestTokenFromQu]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasParsedPersonFromQu]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasParsedQueryFromQu]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasQueryContextEmbedding]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasQueryDate]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasQueryTime]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasQueryType]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasQuery]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasType]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasUserSpecifiedEndDate]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hasUserSpecifiedStartDate]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent hash]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent inferredIntentType]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent intentType]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent isFinal]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent latestTokenFromQu]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent parsedPersonFromQu]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent parsedQueryFromQu]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent queryDate]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent queryTime]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent queryType]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent query]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setEarliestTokenFromQu:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setHasEarliestTokenFromQu:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setHasHasQueryContextEmbedding:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setHasIsFinal:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setHasLatestTokenFromQu:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setHasQueryContextEmbedding:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setHasQueryTime:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setHasType:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setInferredIntentType:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setIntentType:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setIsFinal:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setLatestTokenFromQu:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setParsedPersonFromQu:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setParsedQueryFromQu:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setQuery:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setQueryDate:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setQueryTime:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setQueryType:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setType:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setUserSpecifiedEndDate:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent setUserSpecifiedStartDate:]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent type]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent userSpecifiedEndDate]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent userSpecifiedStartDate]
+ -[SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONDates .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONDates contentCreationDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates contentModificationDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONDates copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONDates description]
+ -[SPOTLIGHTINSTRUMENTATIONDates dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONDates endDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates hasContentCreationDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates hasContentModificationDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates hasEndDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates hasLastUsedDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates hasReceivedDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates hasSentDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates hasStartDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates hash]
+ -[SPOTLIGHTINSTRUMENTATIONDates isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONDates lastUsedDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONDates readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONDates receivedDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates sentDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates setContentCreationDate:]
+ -[SPOTLIGHTINSTRUMENTATIONDates setContentModificationDate:]
+ -[SPOTLIGHTINSTRUMENTATIONDates setEndDate:]
+ -[SPOTLIGHTINSTRUMENTATIONDates setLastUsedDate:]
+ -[SPOTLIGHTINSTRUMENTATIONDates setReceivedDate:]
+ -[SPOTLIGHTINSTRUMENTATIONDates setSentDate:]
+ -[SPOTLIGHTINSTRUMENTATIONDates setStartDate:]
+ -[SPOTLIGHTINSTRUMENTATIONDates startDate]
+ -[SPOTLIGHTINSTRUMENTATIONDates writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals cardType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals description]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals detectedEventType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals detectedEventTypes]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals documentEmbeddingAvailable]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasCardType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasDetectedEventType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasDetectedEventTypes]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasDocumentEmbeddingAvailable]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasIsCalendarFlightEventType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasIsCalendarHotelEventType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasIsCalendarOtherReservationEventType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasIsCalendarRestaurantEventType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasIsFileType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasIsMailCategoryHighImpact]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasIsMailCategoryPromotions]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasLinkType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasLink]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasMostRecentTimeToQueryInMinutes]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hasStartDueDateToNowInSeconds]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals hash]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals isCalendarFlightEventType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals isCalendarHotelEventType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals isCalendarOtherReservationEventType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals isCalendarRestaurantEventType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals isFileType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals isMailCategoryHighImpact]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals isMailCategoryPromotions]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals linkType]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals link]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals mostRecentTimeToQueryInMinutes]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setCardType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setDetectedEventType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setDetectedEventTypes:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setDocumentEmbeddingAvailable:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setHasDocumentEmbeddingAvailable:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setHasIsCalendarFlightEventType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setHasIsCalendarHotelEventType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setHasIsCalendarOtherReservationEventType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setHasIsCalendarRestaurantEventType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setHasIsFileType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setHasIsMailCategoryHighImpact:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setHasIsMailCategoryPromotions:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setHasMostRecentTimeToQueryInMinutes:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setHasStartDueDateToNowInSeconds:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setIsCalendarFlightEventType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setIsCalendarHotelEventType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setIsCalendarOtherReservationEventType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setIsCalendarRestaurantEventType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setIsFileType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setIsMailCategoryHighImpact:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setIsMailCategoryPromotions:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setLink:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setLinkType:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setMostRecentTimeToQueryInMinutes:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals setStartDueDateToNowInSeconds:]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals startDueDateToNowInSeconds]
+ -[SPOTLIGHTINSTRUMENTATIONDocumentSignals writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers appEntityInstanceId]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers bundleId]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers contentUrl]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers description]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers hasAppEntityInstanceId]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers hasBundleId]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers hasContentUrl]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers hasIdentifier]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers hasMdItemIdentifier]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers hasMessageHeader]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers hasMessageId]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers hasName]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers hash]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers identifier]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers mdItemIdentifier]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers messageHeader]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers messageId]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers name]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers setAppEntityInstanceId:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers setBundleId:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers setContentUrl:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers setIdentifier:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers setMdItemIdentifier:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers setMessageHeader:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers setMessageId:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers setName:]
+ -[SPOTLIGHTINSTRUMENTATIONItemIdentifiers writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore categoryEngagementProbability]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore description]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore experimentalScore]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore hasCategoryEngagementProbability]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore hasExperimentalScore]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore hasOriginalL2Score]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore hasParsecEnumScore]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore hasWithinBundleScore]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore hash]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore originalL2Score]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore parsecEnumScore]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore setCategoryEngagementProbability:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore setExperimentalScore:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore setHasCategoryEngagementProbability:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore setHasExperimentalScore:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore setHasOriginalL2Score:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore setHasParsecEnumScore:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore setHasWithinBundleScore:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore setOriginalL2Score:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore setParsecEnumScore:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore setWithinBundleScore:]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore withinBundleScore]
+ -[SPOTLIGHTINSTRUMENTATIONL2VectorScore writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONLink .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONLink copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONLink copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONLink description]
+ -[SPOTLIGHTINSTRUMENTATIONLink dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONLink hasIsInferred]
+ -[SPOTLIGHTINSTRUMENTATIONLink hasIsPromoted]
+ -[SPOTLIGHTINSTRUMENTATIONLink hasName]
+ -[SPOTLIGHTINSTRUMENTATIONLink hasType]
+ -[SPOTLIGHTINSTRUMENTATIONLink hasUrl]
+ -[SPOTLIGHTINSTRUMENTATIONLink hash]
+ -[SPOTLIGHTINSTRUMENTATIONLink isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONLink isInferred]
+ -[SPOTLIGHTINSTRUMENTATIONLink isPromoted]
+ -[SPOTLIGHTINSTRUMENTATIONLink mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONLink name]
+ -[SPOTLIGHTINSTRUMENTATIONLink readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONLink setHasIsInferred:]
+ -[SPOTLIGHTINSTRUMENTATIONLink setHasIsPromoted:]
+ -[SPOTLIGHTINSTRUMENTATIONLink setIsInferred:]
+ -[SPOTLIGHTINSTRUMENTATIONLink setIsPromoted:]
+ -[SPOTLIGHTINSTRUMENTATIONLink setName:]
+ -[SPOTLIGHTINSTRUMENTATIONLink setType:]
+ -[SPOTLIGHTINSTRUMENTATIONLink setUrl:]
+ -[SPOTLIGHTINSTRUMENTATIONLink type]
+ -[SPOTLIGHTINSTRUMENTATIONLink url]
+ -[SPOTLIGHTINSTRUMENTATIONLink writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo addValueArray:]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo attributeKey]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo clearValueArrays]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo description]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo hasAttributeKey]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo hash]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo setAttributeKey:]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo setValueArrays:]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo valueArrayAtIndex:]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo valueArraysCount]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo valueArrays]
+ -[SPOTLIGHTINSTRUMENTATIONMatchInfo writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem description]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem hasItemIdentifiers]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem hasRrfScores]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem hash]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem itemIdentifiers]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem rrfScores]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem setItemIdentifiers:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem setRrfScores:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItem writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent addRrfScoredItems:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent clearRrfScoredItems]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent description]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent hash]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent rrfScoredItemsAtIndex:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent rrfScoredItemsCount]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent rrfScoredItems]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent setRrfScoredItems:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores denseScore]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores description]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores finalScore]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores hasDenseScore]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores hasFinalScore]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores hasRankDense]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores hasRankSparse]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores hasRawScore]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores hasSparseScore]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores hasWDense]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores hasWSparse]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores hash]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores rankDense]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores rankSparse]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores rawScore]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setDenseScore:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setFinalScore:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setHasDenseScore:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setHasFinalScore:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setHasRankDense:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setHasRankSparse:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setHasRawScore:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setHasSparseScore:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setHasWDense:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setHasWSparse:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setRankDense:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setRankSparse:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setRawScore:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setSparseScore:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setWDense:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores setWSparse:]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores sparseScore]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores wDense]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores wSparse]
+ -[SPOTLIGHTINSTRUMENTATIONRRFScores writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem addAdditionalMetadata:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem addMatchInfo:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem additionalMetadataAtIndex:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem additionalMetadatasCount]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem additionalMetadatas]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem clearAdditionalMetadatas]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem clearMatchInfos]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem dates]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem description]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem documentSignals]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem hasDates]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem hasDocumentSignals]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem hasItemIdentifiers]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem hasItemIndex]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem hasRetrievalType]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem hasScore]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem hasSearchTermsMatchTitle]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem hash]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem itemIdentifiers]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem itemIndex]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem matchInfoAtIndex:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem matchInfosCount]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem matchInfos]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem retrievalType]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem score]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem searchTermsMatchTitle]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem setAdditionalMetadatas:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem setDates:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem setDocumentSignals:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem setHasItemIndex:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem setHasSearchTermsMatchTitle:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem setItemIdentifiers:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem setItemIndex:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem setMatchInfos:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem setRetrievalType:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem setScore:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem setSearchTermsMatchTitle:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItem writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent StringAsRetrievalPhase:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent addRetrievedItems:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent clearRetrievedItems]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent description]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent hasRetrievalPhase]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent hash]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent retrievalPhaseAsString:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent retrievalPhase]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent retrievedItemsAtIndex:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent retrievedItemsCount]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent retrievedItems]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent setHasRetrievalPhase:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent setRetrievalPhase:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent setRetrievedItems:]
+ -[SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONScore adjustedSparseScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONScore copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONScore description]
+ -[SPOTLIGHTINSTRUMENTATIONScore dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONScore embeddingSimilarity]
+ -[SPOTLIGHTINSTRUMENTATIONScore engagement]
+ -[SPOTLIGHTINSTRUMENTATIONScore finalScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore freshness]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasAdjustedSparseScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasEmbeddingSimilarity]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasEngagement]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasFinalScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasFreshness]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasKeywordMatchScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasLikelihood]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasNormalizedGsL1LexicalScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasNormalizedGsL2RelevanceScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasOriginalTopicalityScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasPommesCalibratedL1Score]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasPommesL1Score]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasPommesL2Score]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasProjectedEmbeddingSimilarity]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasRawGsL2Score]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasRawScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasSearchtoolL2Score]
+ -[SPOTLIGHTINSTRUMENTATIONScore hasTopicality]
+ -[SPOTLIGHTINSTRUMENTATIONScore hash]
+ -[SPOTLIGHTINSTRUMENTATIONScore isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONScore keywordMatchScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore likelihood]
+ -[SPOTLIGHTINSTRUMENTATIONScore mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONScore normalizedGsL1LexicalScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore normalizedGsL2RelevanceScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore originalTopicalityScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore pommesCalibratedL1Score]
+ -[SPOTLIGHTINSTRUMENTATIONScore pommesL1Score]
+ -[SPOTLIGHTINSTRUMENTATIONScore pommesL2Score]
+ -[SPOTLIGHTINSTRUMENTATIONScore projectedEmbeddingSimilarity]
+ -[SPOTLIGHTINSTRUMENTATIONScore rawGsL2Score]
+ -[SPOTLIGHTINSTRUMENTATIONScore rawScore]
+ -[SPOTLIGHTINSTRUMENTATIONScore readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONScore searchtoolL2Score]
+ -[SPOTLIGHTINSTRUMENTATIONScore setAdjustedSparseScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setEmbeddingSimilarity:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setEngagement:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setFinalScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setFreshness:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasAdjustedSparseScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasEmbeddingSimilarity:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasEngagement:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasFinalScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasFreshness:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasKeywordMatchScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasLikelihood:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasNormalizedGsL1LexicalScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasNormalizedGsL2RelevanceScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasOriginalTopicalityScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasPommesCalibratedL1Score:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasPommesL1Score:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasPommesL2Score:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasProjectedEmbeddingSimilarity:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasRawGsL2Score:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasRawScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasSearchtoolL2Score:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setHasTopicality:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setKeywordMatchScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setLikelihood:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setNormalizedGsL1LexicalScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setNormalizedGsL2RelevanceScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setOriginalTopicalityScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setPommesCalibratedL1Score:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setPommesL1Score:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setPommesL2Score:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setProjectedEmbeddingSimilarity:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setRawGsL2Score:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setRawScore:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setSearchtoolL2Score:]
+ -[SPOTLIGHTINSTRUMENTATIONScore setTopicality:]
+ -[SPOTLIGHTINSTRUMENTATIONScore topicality]
+ -[SPOTLIGHTINSTRUMENTATIONScore writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent description]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent hasSearchMethod]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent hash]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent searchMethod]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent setSearchMethod:]
+ -[SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent description]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent event]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent hasEvent]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent hasSessionId]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent hash]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent sessionId]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent setEvent:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent setSessionId:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent writeTo:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf .cxx_destruct]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf StringAsEvent:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf cerberusQuSignalsEvent]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf clearOneofValuesForEvent]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf copyTo:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf copyWithZone:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf description]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf dictionaryRepresentation]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf eventAsString:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf event]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf hasCerberusQuSignalsEvent]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf hasEvent]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf hasRetrievedItemsEvent]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf hasRrfRankedItemsEvent]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf hasSearchMetadataEvent]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf hash]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf isEqual:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf mergeFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf readFrom:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf retrievedItemsEvent]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf rrfRankedItemsEvent]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf searchMetadataEvent]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf setCerberusQuSignalsEvent:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf setEvent:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf setHasEvent:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf setRetrievedItemsEvent:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf setRrfRankedItemsEvent:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf setSearchMetadataEvent:]
+ -[SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf writeTo:]
+ GCC_except_table266
+ GCC_except_table330
+ GCC_except_table333
+ GCC_except_table339
+ GCC_except_table345
+ GCC_except_table70
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONAdditionalMetadata._key
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONAdditionalMetadata._value
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._earliestTokenFromQu
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._has
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._hasQueryContextEmbedding
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._inferredIntentType
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._intentType
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._isFinal
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._latestTokenFromQu
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._parsedPersonFromQu
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._parsedQueryFromQu
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._query
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._queryDate
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._queryTime
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._queryType
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._type
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._userSpecifiedEndDate
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent._userSpecifiedStartDate
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDates._contentCreationDate
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDates._contentModificationDate
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDates._endDate
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDates._lastUsedDate
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDates._receivedDate
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDates._sentDate
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDates._startDate
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._cardType
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._detectedEventType
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._detectedEventTypes
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._documentEmbeddingAvailable
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._has
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._isCalendarFlightEventType
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._isCalendarHotelEventType
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._isCalendarOtherReservationEventType
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._isCalendarRestaurantEventType
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._isFileType
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._isMailCategoryHighImpact
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._isMailCategoryPromotions
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._link
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._linkType
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._mostRecentTimeToQueryInMinutes
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals._startDueDateToNowInSeconds
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers._appEntityInstanceId
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers._bundleId
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers._contentUrl
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers._identifier
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers._mdItemIdentifier
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers._messageHeader
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers._messageId
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers._name
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONL2VectorScore._categoryEngagementProbability
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONL2VectorScore._experimentalScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONL2VectorScore._has
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONL2VectorScore._originalL2Score
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONL2VectorScore._parsecEnumScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONL2VectorScore._withinBundleScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONLink._has
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONLink._isInferred
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONLink._isPromoted
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONLink._name
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONLink._type
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONLink._url
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONMatchInfo._attributeKey
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONMatchInfo._valueArrays
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItem._itemIdentifiers
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItem._rrfScores
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent._rrfScoredItems
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRRFScores._denseScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRRFScores._finalScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRRFScores._has
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRRFScores._rankDense
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRRFScores._rankSparse
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRRFScores._rawScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRRFScores._sparseScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRRFScores._wDense
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRRFScores._wSparse
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem._additionalMetadatas
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem._dates
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem._documentSignals
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem._has
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem._itemIdentifiers
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem._itemIndex
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem._matchInfos
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem._retrievalType
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem._score
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem._searchTermsMatchTitle
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent._has
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent._retrievalPhase
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent._retrievedItems
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._adjustedSparseScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._embeddingSimilarity
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._engagement
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._finalScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._freshness
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._has
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._keywordMatchScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._likelihood
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._normalizedGsL1LexicalScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._normalizedGsL2RelevanceScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._originalTopicalityScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._pommesCalibratedL1Score
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._pommesL1Score
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._pommesL2Score
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._projectedEmbeddingSimilarity
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._rawGsL2Score
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._rawScore
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._searchtoolL2Score
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONScore._topicality
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent._searchMethod
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent._event
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent._sessionId
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf._cerberusQuSignalsEvent
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf._event
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf._has
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf._retrievedItemsEvent
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf._rrfRankedItemsEvent
+ OBJC_IVAR_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf._searchMetadataEvent
+ _GenerativeModelsLibraryCore.frameworkLibrary
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONAdditionalMetadata
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONDates
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONL2VectorScore
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONLink
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONMatchInfo
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItem
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONRRFScores
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONScore
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent
+ _OBJC_CLASS_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf
+ _OBJC_CLASS_$_SSEngagementPolicy
+ _OBJC_IVAR_$_PRSRankingItem._suppressEngagement
+ _OBJC_IVAR_$_SFSearchResult_SpotlightExtras._suppressEngagement
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONAdditionalMetadata
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONDates
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONL2VectorScore
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONLink
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONMatchInfo
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItem
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONRRFScores
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONScore
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent
+ _OBJC_METACLASS_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf
+ _OBJC_METACLASS_$_SSEngagementPolicy
+ _PBDataWriterWriteBOOLField
+ _PBDataWriterWriteInt32Field
+ _PBDataWriterWriteInt64Field
+ _PBDataWriterWriteUint32Field
+ _SPOTLIGHTINSTRUMENTATIONAdditionalMetadataReadFrom
+ _SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEventReadFrom
+ _SPOTLIGHTINSTRUMENTATIONDatesReadFrom
+ _SPOTLIGHTINSTRUMENTATIONDocumentSignalsReadFrom
+ _SPOTLIGHTINSTRUMENTATIONItemIdentifiersReadFrom
+ _SPOTLIGHTINSTRUMENTATIONL2VectorScoreReadFrom
+ _SPOTLIGHTINSTRUMENTATIONLinkReadFrom
+ _SPOTLIGHTINSTRUMENTATIONMatchInfoReadFrom
+ _SPOTLIGHTINSTRUMENTATIONRRFScoredItemReadFrom
+ _SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEventReadFrom
+ _SPOTLIGHTINSTRUMENTATIONRRFScoresReadFrom
+ _SPOTLIGHTINSTRUMENTATIONRetrievedItemReadFrom
+ _SPOTLIGHTINSTRUMENTATIONRetrievedItemsEventReadFrom
+ _SPOTLIGHTINSTRUMENTATIONScoreReadFrom
+ _SPOTLIGHTINSTRUMENTATIONSearchMetadataEventReadFrom
+ _SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOfReadFrom
+ _SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventReadFrom
+ _SSCampoEnabled.onceToken
+ __OBJC_$_CLASS_METHODS_SPOTLIGHTINSTRUMENTATIONMatchInfo
+ __OBJC_$_CLASS_METHODS_SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent
+ __OBJC_$_CLASS_METHODS_SPOTLIGHTINSTRUMENTATIONRetrievedItem
+ __OBJC_$_CLASS_METHODS_SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent
+ __OBJC_$_CLASS_METHODS_SSEngagementPolicy
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONAdditionalMetadata
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONDates
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONDocumentSignals
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONItemIdentifiers
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONL2VectorScore
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONLink
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONMatchInfo
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONRRFScoredItem
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONRRFScores
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONRetrievedItem
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONScore
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent
+ __OBJC_$_INSTANCE_METHODS_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONAdditionalMetadata
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONDates
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONDocumentSignals
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONItemIdentifiers
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONL2VectorScore
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONLink
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONMatchInfo
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONRRFScoredItem
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONRRFScores
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONRetrievedItem
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONScore
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent
+ __OBJC_$_INSTANCE_VARIABLES_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONAdditionalMetadata
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONDates
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONDocumentSignals
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONItemIdentifiers
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONL2VectorScore
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONLink
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONMatchInfo
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONRRFScoredItem
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONRRFScores
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONRetrievedItem
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONScore
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent
+ __OBJC_$_PROP_LIST_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONAdditionalMetadata
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONDates
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONL2VectorScore
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONLink
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONMatchInfo
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItem
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONRRFScores
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONScore
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent
+ __OBJC_CLASS_PROTOCOLS_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONAdditionalMetadata
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONDates
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONL2VectorScore
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONLink
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONMatchInfo
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItem
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONRRFScores
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONScore
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent
+ __OBJC_CLASS_RO_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf
+ __OBJC_CLASS_RO_$_SSEngagementPolicy
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONAdditionalMetadata
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONCerberusQUSignalsEvent
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONDates
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONDocumentSignals
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONItemIdentifiers
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONL2VectorScore
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONLink
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONMatchInfo
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItem
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONRRFScoredItemsEvent
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONRRFScores
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONRetrievedItem
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONRetrievedItemsEvent
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONScore
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONSearchMetadataEvent
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEvent
+ __OBJC_METACLASS_RO_$_SPOTLIGHTINSTRUMENTATIONSpotlightInstrumentableEventOneOf
+ __OBJC_METACLASS_RO_$_SSEngagementPolicy
+ ___47+[FeatureStoreLogger _instrumentableEventQueue]_block_invoke
+ ___57+[FeatureStoreLogger insertSpotlightInstrumentableEvent:]_block_invoke
+ ___GenerativeModelsLibraryCore_block_invoke
+ ___SSCampoEnabled_block_invoke
+ ___getGMAvailabilityWrapperClass_block_invoke
+ __addMetadata
+ __instrumentableEventQueue.onceToken
+ __instrumentableEventQueue.queue
+ _audit_stringGenerativeModels
+ _enableNotificationBundle
+ _getGMAvailabilityWrapperClass.softClass
+ _sCampoEnabledOverrideActive
+ _sCampoEnabledOverrideValue
- GCC_except_table264
- GCC_except_table329
- GCC_except_table332
- GCC_except_table338
- GCC_except_table343
- _AFIsLinwoodEnabledAndAvailable
- _objc_release_x10
CStrings:
+ "%"
+ "%ld"
+ "(unknown: %i)"
+ "Class getGMAvailabilityWrapperClass(void)_block_invoke"
+ "FeatureStoreLogger: Failed to create FeatureStore stream for SpotlightInstrumentableEventProto"
+ "FeatureStoreLogger: Failed to create JSON string for SpotlightInstrumentableEvent"
+ "FeatureStoreLogger: FeatureStore insert failed for SpotlightInstrumentableEvent: %{public}@"
+ "FeatureStoreLogger: JSON serialization failed for SpotlightInstrumentableEvent: %{public}@"
+ "FeatureStoreLogger: dictionaryRepresentation returned nil for SpotlightInstrumentableEvent"
+ "GMAvailabilityWrapper"
+ "PBUNSET"
+ "RETRIEVAL_STEP_FINAL"
+ "RETRIEVAL_STEP_INITIAL_RETRIEVAL"
+ "RETRIEVAL_STEP_OUTPUT"
+ "RETRIEVAL_STEP_RERANKING"
+ "RETRIEVAL_STEP_UNKNOWN"
+ "SSCampoEnabled: GenerativeModels framework or GMAvailabilityWrapper class not available; treating Enhanced Siri as not shown"
+ "SSDefaults.m"
+ "SpotlightInstrumentableEventProto"
+ "[SpotlightRanking] [SearchTool] [RRF] query=%@ identifier=%@ bundleId=%@ sparseScore=%f denseScore=%f rank_sparse=%lu rank_dense=%lu w_sparse=%f w_dense=%f rawScore=%f finalScore=%f retrieval_type=%d"
+ "_suppressEngagement"
+ "additional_metadata"
+ "adjusted_sparse_score"
+ "attribute_key"
+ "card_type"
+ "category_engagement_probability"
+ "cerberus_qu_signals_event"
+ "com.apple.spotlight.FeatureStoreLogger.instrumentable"
+ "content_creation_date"
+ "content_modification_date"
+ "content_url"
+ "dates"
+ "detected_event_type"
+ "detected_event_types"
+ "document_embedding_available"
+ "document_signals"
+ "earliest_token_from_qu"
+ "embedding_similarity"
+ "end_date"
+ "event"
+ "experimental_score"
+ "final_score"
+ "has_query_context_embedding"
+ "inferred_intent_type"
+ "intent_type"
+ "is_calendar_flight_event_type"
+ "is_calendar_hotel_event_type"
+ "is_calendar_other_reservation_event_type"
+ "is_calendar_restaurant_event_type"
+ "is_file_type"
+ "is_final"
+ "is_inferred"
+ "is_mail_category_high_impact"
+ "is_mail_category_promotions"
+ "is_promoted"
+ "item_identifiers"
+ "item_index"
+ "key"
+ "keyword_match_score"
+ "last_used_date"
+ "latest_token_from_qu"
+ "link_type"
+ "match_info"
+ "md_item_identifier"
+ "message_header"
+ "message_id"
+ "most_recent_time_to_query_in_minutes"
+ "normalized_gs_l1_lexical_score"
+ "normalized_gs_l2_relevance_score"
+ "original_topicality_score"
+ "parsec_enum_score"
+ "parsed_person_from_qu"
+ "parsed_query_from_qu"
+ "pommes_calibrated_l1_score"
+ "pommes_l2_score"
+ "projected_embedding_similarity"
+ "query_date"
+ "query_time"
+ "query_type"
+ "rank_dense"
+ "rank_sparse"
+ "raw_gs_l2_score"
+ "raw_score"
+ "received_date"
+ "retrieval_phase"
+ "retrieval_type"
+ "retrieved_items"
+ "retrieved_items_event"
+ "rrf_ranked_items_event"
+ "rrf_scored_items"
+ "rrf_scores"
+ "search_metadata_event"
+ "search_method"
+ "search_terms_match_title"
+ "searchtool_l2_score"
+ "sent_date"
+ "softlink:o:path:/System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels"
+ "sparse_score"
+ "start_date"
+ "start_due_date_to_now_in_seconds"
+ "url"
+ "user_specified_end_date"
+ "user_specified_start_date"
+ "value_array"
+ "void *GenerativeModelsLibrary(void)"
+ "w_dense"
+ "w_sparse"
+ "within_bundle_score"
- "[SpotlightRanking] [SearchTool] [RRF] query=%@ identifier=%@ bundleId=%@ sparseScore=%f denseScore=%f rank_sparse=%lu rank_dense=%lu w_sparse=%f w_dense=%f rawScore=%f finalScore=%f"
```
