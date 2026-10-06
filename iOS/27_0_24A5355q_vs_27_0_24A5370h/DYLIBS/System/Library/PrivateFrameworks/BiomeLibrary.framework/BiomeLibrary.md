## BiomeLibrary

> `/System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72fd64` | `0x74170c` | **`+0x119a8`** |
| `__AUTH_CONST.__objc_const` | `0x9f9c0` | `0xa14e0` | **`+0x1b20`** |
| `__TEXT.__objc_methlist` | `0x4edac` | `0x4f9e4` | **`+0xc38`** |
| `__TEXT.__cstring` | `0x4d11c` | `0x4dc45` | **`+0xb29`** |
| `__AUTH_CONST.__cfstring` | `0x49fc0` | `0x4aaa0` | **`+0xae0`** |
| `__DATA_CONST.__objc_selrefs` | `0x122a8` | `0x12688` | **`+0x3e0`** |
| `__DATA_CONST.__const` | `0x1e520` | `0x1e8c8` | **`+0x3a8`** |
| `__AUTH.__objc_data` | `0xa6b0` | `0xa8e0` | **`+0x230`** |
| `__DATA_CONST.__objc_arraydata` | `0xae08` | `0xafc8` | **`+0x1c0`** |
| `__TEXT.__unwind_info` | `0xf530` | `0xf6f0` | **`+0x1c0`** |
| `__DATA.__objc_ivar` | `0x7ebc` | `0x8060` | **`+0x1a4`** |
| `__AUTH_CONST.__const` | `0x99d8` | `0x9ad8` | **`+0x100`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x65a0` | `0x6648` | **`+0xa8`** |
| `__TEXT.__const` | `0x46a8` | `0x4718` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x1bb8` | `0x1bf0` | **`+0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x22a8` | `0x22e0` | **`+0x38`** |
| `__DATA_CONST.__objc_superrefs` | `0x1ae8` | `0x1b20` | **`+0x38`** |

### Other Changes

```diff

-409.0.1.0.0
+420.0.0.0.0

-  Functions: 28203
-  Symbols:   52082
-  CStrings:  9599
+  Functions: 28467
+  Symbols:   52579
+  CStrings:  9686
Symbols:
+ +[BMCommAppsCallContextCardsFedStats columns]
+ +[BMCommAppsCallContextCardsFedStats eventWithData:dataVersion:]
+ +[BMCommAppsCallContextCardsFedStats latestDataVersion]
+ +[BMCommAppsCallContextCardsFedStats protoFields]
+ +[BMCommAppsCallContextCardsFedStats validKeyPaths]
+ +[BML1Score columns]
+ +[BML1Score eventWithData:dataVersion:]
+ +[BML1Score latestDataVersion]
+ +[BML1Score protoFields]
+ +[BML1Score validKeyPaths]
+ +[BML2Score columns]
+ +[BML2Score eventWithData:dataVersion:]
+ +[BML2Score latestDataVersion]
+ +[BML2Score protoFields]
+ +[BML2Score validKeyPaths]
+ +[BMMessageFeatures columns]
+ +[BMMessageFeatures eventWithData:dataVersion:]
+ +[BMMessageFeatures latestDataVersion]
+ +[BMMessageFeatures protoFields]
+ +[BMMessageFeatures validKeyPaths]
+ +[BMQueryMatchInfo columns]
+ +[BMQueryMatchInfo eventWithData:dataVersion:]
+ +[BMQueryMatchInfo latestDataVersion]
+ +[BMQueryMatchInfo protoFields]
+ +[BMQueryMatchInfo validKeyPaths]
+ +[BMRankedMailItem columns]
+ +[BMRankedMailItem eventWithData:dataVersion:]
+ +[BMRankedMailItem latestDataVersion]
+ +[BMRankedMailItem protoFields]
+ +[BMRankedMailItem validKeyPaths]
+ +[BMResultsRankedGLP columns]
+ +[BMResultsRankedGLP eventWithData:dataVersion:]
+ +[BMResultsRankedGLP latestDataVersion]
+ +[BMResultsRankedGLP protoFields]
+ +[BMResultsRankedGLP validKeyPaths]
+ +[BMTrustKitTKWalletOrderExtractionDomains columns]
+ +[BMTrustKitTKWalletOrderExtractionDomains eventWithData:dataVersion:]
+ +[BMTrustKitTKWalletOrderExtractionDomains latestDataVersion]
+ +[BMTrustKitTKWalletOrderExtractionDomains protoFields]
+ +[BMTrustKitTKWalletOrderExtractionDomains validKeyPaths]
+ +[_BMCommAppsCallIntelligenceLibraryNode CallContextCardsFedStats]
+ +[_BMCommAppsCallIntelligenceLibraryNode configurationForCallContextCardsFedStats]
+ +[_BMCommAppsCallIntelligenceLibraryNode storeConfigurationForCallContextCardsFedStats]
+ +[_BMCommAppsCallIntelligenceLibraryNode syncPolicyForCallContextCardsFedStats]
+ +[_BMTrustKitDecisioningLibraryNode TKWalletOrderExtractionDomains]
+ +[_BMTrustKitDecisioningLibraryNode configurationForTKWalletOrderExtractionDomains]
+ +[_BMTrustKitDecisioningLibraryNode storeConfigurationForTKWalletOrderExtractionDomains]
+ +[_BMTrustKitDecisioningLibraryNode syncPolicyForTKWalletOrderExtractionDomains]
+ -[BMCommAppsCallContextCardsFedStats .cxx_destruct]
+ -[BMCommAppsCallContextCardsFedStats cardTitle]
+ -[BMCommAppsCallContextCardsFedStats dataVersion]
+ -[BMCommAppsCallContextCardsFedStats description]
+ -[BMCommAppsCallContextCardsFedStats engagementType]
+ -[BMCommAppsCallContextCardsFedStats filteredReason]
+ -[BMCommAppsCallContextCardsFedStats initByReadFrom:]
+ -[BMCommAppsCallContextCardsFedStats initWithCardTitle:filteredReason:engagementType:]
+ -[BMCommAppsCallContextCardsFedStats initWithJSONDictionary:error:]
+ -[BMCommAppsCallContextCardsFedStats isEqual:]
+ -[BMCommAppsCallContextCardsFedStats jsonDictionary]
+ -[BMCommAppsCallContextCardsFedStats serialize]
+ -[BMCommAppsCallContextCardsFedStats writeTo:]
+ -[BML1Score bm25]
+ -[BML1Score cosineSim]
+ -[BML1Score dataVersion]
+ -[BML1Score description]
+ -[BML1Score hasBm25]
+ -[BML1Score hasCosineSim]
+ -[BML1Score hasL1Rank]
+ -[BML1Score hasRrf]
+ -[BML1Score initByReadFrom:]
+ -[BML1Score initWithBm25:cosineSim:rrf:l1Rank:]
+ -[BML1Score initWithJSONDictionary:error:]
+ -[BML1Score isEqual:]
+ -[BML1Score jsonDictionary]
+ -[BML1Score l1Rank]
+ -[BML1Score rrf]
+ -[BML1Score serialize]
+ -[BML1Score setHasBm25:]
+ -[BML1Score setHasCosineSim:]
+ -[BML1Score setHasL1Rank:]
+ -[BML1Score setHasRrf:]
+ -[BML1Score writeTo:]
+ -[BML2Score baseL2Score]
+ -[BML2Score dataVersion]
+ -[BML2Score description]
+ -[BML2Score engagementMultiplier]
+ -[BML2Score finalL2Score]
+ -[BML2Score hasBaseL2Score]
+ -[BML2Score hasEngagementMultiplier]
+ -[BML2Score hasFinalL2Score]
+ -[BML2Score hasQualityMultiplier]
+ -[BML2Score hasQuerymatchMultiplier]
+ -[BML2Score hasRanktrustMultiplier]
+ -[BML2Score hasStructuralMultiplier]
+ -[BML2Score hasTemporalMultiplier]
+ -[BML2Score initByReadFrom:]
+ -[BML2Score initWithBaseL2Score:temporalMultiplier:querymatchMultiplier:engagementMultiplier:structuralMultiplier:qualityMultiplier:ranktrustMultiplier:finalL2Score:]
+ -[BML2Score initWithJSONDictionary:error:]
+ -[BML2Score isEqual:]
+ -[BML2Score jsonDictionary]
+ -[BML2Score qualityMultiplier]
+ -[BML2Score querymatchMultiplier]
+ -[BML2Score ranktrustMultiplier]
+ -[BML2Score serialize]
+ -[BML2Score setHasBaseL2Score:]
+ -[BML2Score setHasEngagementMultiplier:]
+ -[BML2Score setHasFinalL2Score:]
+ -[BML2Score setHasQualityMultiplier:]
+ -[BML2Score setHasQuerymatchMultiplier:]
+ -[BML2Score setHasRanktrustMultiplier:]
+ -[BML2Score setHasStructuralMultiplier:]
+ -[BML2Score setHasTemporalMultiplier:]
+ -[BML2Score structuralMultiplier]
+ -[BML2Score temporalMultiplier]
+ -[BML2Score writeTo:]
+ -[BMMailRankerEvent initWithSessionId:queryId:resultsRanked:resultsRankedGLP:]
+ -[BMMailRankerEvent resultsRankedGLP]
+ -[BMMailRankerEvent(Deprecation) initWithSessionId:queryId:resultsRanked:]
+ -[BMMessageFeatures attachmentCount]
+ -[BMMessageFeatures dataVersion]
+ -[BMMessageFeatures daysSinceReceived]
+ -[BMMessageFeatures daysSinceSent]
+ -[BMMessageFeatures description]
+ -[BMMessageFeatures hasAttachmentCount]
+ -[BMMessageFeatures hasAttachments]
+ -[BMMessageFeatures hasDaysSinceReceived]
+ -[BMMessageFeatures hasDaysSinceSent]
+ -[BMMessageFeatures hasHasAttachments]
+ -[BMMessageFeatures hasHasThreadId]
+ -[BMMessageFeatures hasIsFlagged]
+ -[BMMessageFeatures hasIsJunk]
+ -[BMMessageFeatures hasIsReplied]
+ -[BMMessageFeatures hasIsReply]
+ -[BMMessageFeatures hasIsUnread]
+ -[BMMessageFeatures hasRecipientCount]
+ -[BMMessageFeatures hasThreadId]
+ -[BMMessageFeatures initByReadFrom:]
+ -[BMMessageFeatures initWithIsUnread:isFlagged:isJunk:isReply:isReplied:daysSinceReceived:daysSinceSent:hasAttachments:attachmentCount:recipientCount:hasThreadId:]
+ -[BMMessageFeatures initWithJSONDictionary:error:]
+ -[BMMessageFeatures isEqual:]
+ -[BMMessageFeatures isFlagged]
+ -[BMMessageFeatures isJunk]
+ -[BMMessageFeatures isReplied]
+ -[BMMessageFeatures isReply]
+ -[BMMessageFeatures isUnread]
+ -[BMMessageFeatures jsonDictionary]
+ -[BMMessageFeatures recipientCount]
+ -[BMMessageFeatures serialize]
+ -[BMMessageFeatures setHasAttachmentCount:]
+ -[BMMessageFeatures setHasDaysSinceReceived:]
+ -[BMMessageFeatures setHasDaysSinceSent:]
+ -[BMMessageFeatures setHasHasAttachments:]
+ -[BMMessageFeatures setHasHasThreadId:]
+ -[BMMessageFeatures setHasIsFlagged:]
+ -[BMMessageFeatures setHasIsJunk:]
+ -[BMMessageFeatures setHasIsReplied:]
+ -[BMMessageFeatures setHasIsReply:]
+ -[BMMessageFeatures setHasIsUnread:]
+ -[BMMessageFeatures setHasRecipientCount:]
+ -[BMMessageFeatures writeTo:]
+ -[BMQueryMatchInfo bodyMatchCount]
+ -[BMQueryMatchInfo dataVersion]
+ -[BMQueryMatchInfo description]
+ -[BMQueryMatchInfo hasBodyMatchCount]
+ -[BMQueryMatchInfo hasExactPhraseMatchInBody]
+ -[BMQueryMatchInfo hasExactPhraseMatchInRecipient]
+ -[BMQueryMatchInfo hasExactPhraseMatchInSender]
+ -[BMQueryMatchInfo hasExactPhraseMatchInSubject]
+ -[BMQueryMatchInfo hasHasExactPhraseMatchInBody]
+ -[BMQueryMatchInfo hasHasExactPhraseMatchInRecipient]
+ -[BMQueryMatchInfo hasHasExactPhraseMatchInSender]
+ -[BMQueryMatchInfo hasHasExactPhraseMatchInSubject]
+ -[BMQueryMatchInfo hasLastTokenIsExactInSender]
+ -[BMQueryMatchInfo hasLastTokenIsExactInSubject]
+ -[BMQueryMatchInfo hasLastTokenMatchesSender]
+ -[BMQueryMatchInfo hasLastTokenMatchesSubject]
+ -[BMQueryMatchInfo hasMatchedTokens]
+ -[BMQueryMatchInfo hasQueryIndex]
+ -[BMQueryMatchInfo hasRecipientMatchCount]
+ -[BMQueryMatchInfo hasSenderMatchCount]
+ -[BMQueryMatchInfo hasSubjectMatchCount]
+ -[BMQueryMatchInfo hasTotalQueryTokens]
+ -[BMQueryMatchInfo initByReadFrom:]
+ -[BMQueryMatchInfo initWithJSONDictionary:error:]
+ -[BMQueryMatchInfo initWithQueryIndex:subjectMatchCount:senderMatchCount:recipientMatchCount:bodyMatchCount:totalQueryTokens:matchedTokens:lastTokenMatchesSubject:lastTokenMatchesSender:lastTokenIsExactInSubject:lastTokenIsExactInSender:hasExactPhraseMatchInSubject:hasExactPhraseMatchInSender:hasExactPhraseMatchInRecipient:hasExactPhraseMatchInBody:]
+ -[BMQueryMatchInfo isEqual:]
+ -[BMQueryMatchInfo jsonDictionary]
+ -[BMQueryMatchInfo lastTokenIsExactInSender]
+ -[BMQueryMatchInfo lastTokenIsExactInSubject]
+ -[BMQueryMatchInfo lastTokenMatchesSender]
+ -[BMQueryMatchInfo lastTokenMatchesSubject]
+ -[BMQueryMatchInfo matchedTokens]
+ -[BMQueryMatchInfo queryIndex]
+ -[BMQueryMatchInfo recipientMatchCount]
+ -[BMQueryMatchInfo senderMatchCount]
+ -[BMQueryMatchInfo serialize]
+ -[BMQueryMatchInfo setHasBodyMatchCount:]
+ -[BMQueryMatchInfo setHasHasExactPhraseMatchInBody:]
+ -[BMQueryMatchInfo setHasHasExactPhraseMatchInRecipient:]
+ -[BMQueryMatchInfo setHasHasExactPhraseMatchInSender:]
+ -[BMQueryMatchInfo setHasHasExactPhraseMatchInSubject:]
+ -[BMQueryMatchInfo setHasLastTokenIsExactInSender:]
+ -[BMQueryMatchInfo setHasLastTokenIsExactInSubject:]
+ -[BMQueryMatchInfo setHasLastTokenMatchesSender:]
+ -[BMQueryMatchInfo setHasLastTokenMatchesSubject:]
+ -[BMQueryMatchInfo setHasMatchedTokens:]
+ -[BMQueryMatchInfo setHasQueryIndex:]
+ -[BMQueryMatchInfo setHasRecipientMatchCount:]
+ -[BMQueryMatchInfo setHasSenderMatchCount:]
+ -[BMQueryMatchInfo setHasSubjectMatchCount:]
+ -[BMQueryMatchInfo setHasTotalQueryTokens:]
+ -[BMQueryMatchInfo subjectMatchCount]
+ -[BMQueryMatchInfo totalQueryTokens]
+ -[BMQueryMatchInfo writeTo:]
+ -[BMRankedMailItem .cxx_destruct]
+ -[BMRankedMailItem dataVersion]
+ -[BMRankedMailItem description]
+ -[BMRankedMailItem initByReadFrom:]
+ -[BMRankedMailItem initWithJSONDictionary:error:]
+ -[BMRankedMailItem initWithResultId:l1Score:l2Score:queryMatchInfo:messageFeatures:]
+ -[BMRankedMailItem isEqual:]
+ -[BMRankedMailItem jsonDictionary]
+ -[BMRankedMailItem l1Score]
+ -[BMRankedMailItem l2Score]
+ -[BMRankedMailItem messageFeatures]
+ -[BMRankedMailItem queryMatchInfo]
+ -[BMRankedMailItem resultId]
+ -[BMRankedMailItem serialize]
+ -[BMRankedMailItem writeTo:]
+ -[BMResultsRankedGLP .cxx_destruct]
+ -[BMResultsRankedGLP _rankedMailItemJSONArray]
+ -[BMResultsRankedGLP dataVersion]
+ -[BMResultsRankedGLP description]
+ -[BMResultsRankedGLP hasIsSemanticSearchEligible]
+ -[BMResultsRankedGLP hasIsSemanticSearchTriggered]
+ -[BMResultsRankedGLP hasQueryAnalysisTiming]
+ -[BMResultsRankedGLP hasRankingTiming]
+ -[BMResultsRankedGLP hasRetrievalTiming]
+ -[BMResultsRankedGLP initByReadFrom:]
+ -[BMResultsRankedGLP initWithIsSemanticSearchEligible:isSemanticSearchTriggered:queryAnalysisTiming:retrievalTiming:rankingTiming:sectionType:rankedMailItem:]
+ -[BMResultsRankedGLP initWithJSONDictionary:error:]
+ -[BMResultsRankedGLP isEqual:]
+ -[BMResultsRankedGLP isSemanticSearchEligible]
+ -[BMResultsRankedGLP isSemanticSearchTriggered]
+ -[BMResultsRankedGLP jsonDictionary]
+ -[BMResultsRankedGLP queryAnalysisTiming]
+ -[BMResultsRankedGLP rankedMailItem]
+ -[BMResultsRankedGLP rankingTiming]
+ -[BMResultsRankedGLP retrievalTiming]
+ -[BMResultsRankedGLP sectionType]
+ -[BMResultsRankedGLP serialize]
+ -[BMResultsRankedGLP setHasIsSemanticSearchEligible:]
+ -[BMResultsRankedGLP setHasIsSemanticSearchTriggered:]
+ -[BMResultsRankedGLP setHasQueryAnalysisTiming:]
+ -[BMResultsRankedGLP setHasRankingTiming:]
+ -[BMResultsRankedGLP setHasRetrievalTiming:]
+ -[BMResultsRankedGLP writeTo:]
+ -[BMTrustKitTKWalletOrderExtractionDomains .cxx_destruct]
+ -[BMTrustKitTKWalletOrderExtractionDomains dataVersion]
+ -[BMTrustKitTKWalletOrderExtractionDomains description]
+ -[BMTrustKitTKWalletOrderExtractionDomains deviceLanguage]
+ -[BMTrustKitTKWalletOrderExtractionDomains domain]
+ -[BMTrustKitTKWalletOrderExtractionDomains initByReadFrom:]
+ -[BMTrustKitTKWalletOrderExtractionDomains initWithDomain:uafVersion:recordId:recordZone:recordVersion:locale:deviceLanguage:matchStatus:]
+ -[BMTrustKitTKWalletOrderExtractionDomains initWithJSONDictionary:error:]
+ -[BMTrustKitTKWalletOrderExtractionDomains isEqual:]
+ -[BMTrustKitTKWalletOrderExtractionDomains jsonDictionary]
+ -[BMTrustKitTKWalletOrderExtractionDomains locale]
+ -[BMTrustKitTKWalletOrderExtractionDomains matchStatus]
+ -[BMTrustKitTKWalletOrderExtractionDomains recordId]
+ -[BMTrustKitTKWalletOrderExtractionDomains recordVersion]
+ -[BMTrustKitTKWalletOrderExtractionDomains recordZone]
+ -[BMTrustKitTKWalletOrderExtractionDomains serialize]
+ -[BMTrustKitTKWalletOrderExtractionDomains uafVersion]
+ -[BMTrustKitTKWalletOrderExtractionDomains writeTo:]
+ _BMCommAppsCallContextCardsFedStatsCardTitleColumn
+ _BMCommAppsCallContextCardsFedStatsEngagementTypeAsString
+ _BMCommAppsCallContextCardsFedStatsEngagementTypeColumn
+ _BMCommAppsCallContextCardsFedStatsEngagementTypeDecode
+ _BMCommAppsCallContextCardsFedStatsEngagementTypeFromString
+ _BMCommAppsCallContextCardsFedStatsEngagementTypeFromString.sortedEnums
+ _BMCommAppsCallContextCardsFedStatsEngagementTypeFromString.sortedStrings
+ _BMCommAppsCallContextCardsFedStatsFilteredReasonAsString
+ _BMCommAppsCallContextCardsFedStatsFilteredReasonColumn
+ _BMCommAppsCallContextCardsFedStatsFilteredReasonDecode
+ _BMCommAppsCallContextCardsFedStatsFilteredReasonFromString
+ _BMCommAppsCallContextCardsFedStatsFilteredReasonFromString.sortedEnums
+ _BMCommAppsCallContextCardsFedStatsFilteredReasonFromString.sortedStrings
+ _BMCommAppsCallIntelligenceCallContextCardsFedStatsIdentifier
+ _BML1ScoreBm25Column
+ _BML1ScoreCosineSimColumn
+ _BML1ScoreL1RankColumn
+ _BML1ScoreRrfColumn
+ _BML2ScoreBaseL2ScoreColumn
+ _BML2ScoreEngagementMultiplierColumn
+ _BML2ScoreFinalL2ScoreColumn
+ _BML2ScoreQualityMultiplierColumn
+ _BML2ScoreQuerymatchMultiplierColumn
+ _BML2ScoreRanktrustMultiplierColumn
+ _BML2ScoreStructuralMultiplierColumn
+ _BML2ScoreTemporalMultiplierColumn
+ _BMMailRankerEventResultsRankedGLPColumn
+ _BMMessageFeaturesAttachmentCountColumn
+ _BMMessageFeaturesDaysSinceReceivedColumn
+ _BMMessageFeaturesDaysSinceSentColumn
+ _BMMessageFeaturesHasAttachmentsColumn
+ _BMMessageFeaturesHasThreadIdColumn
+ _BMMessageFeaturesIsFlaggedColumn
+ _BMMessageFeaturesIsJunkColumn
+ _BMMessageFeaturesIsRepliedColumn
+ _BMMessageFeaturesIsReplyColumn
+ _BMMessageFeaturesIsUnreadColumn
+ _BMMessageFeaturesRecipientCountColumn
+ _BMQueryMatchInfoBodyMatchCountColumn
+ _BMQueryMatchInfoHasExactPhraseMatchInBodyColumn
+ _BMQueryMatchInfoHasExactPhraseMatchInRecipientColumn
+ _BMQueryMatchInfoHasExactPhraseMatchInSenderColumn
+ _BMQueryMatchInfoHasExactPhraseMatchInSubjectColumn
+ _BMQueryMatchInfoLastTokenIsExactInSenderColumn
+ _BMQueryMatchInfoLastTokenIsExactInSubjectColumn
+ _BMQueryMatchInfoLastTokenMatchesSenderColumn
+ _BMQueryMatchInfoLastTokenMatchesSubjectColumn
+ _BMQueryMatchInfoMatchedTokensColumn
+ _BMQueryMatchInfoQueryIndexColumn
+ _BMQueryMatchInfoRecipientMatchCountColumn
+ _BMQueryMatchInfoSenderMatchCountColumn
+ _BMQueryMatchInfoSubjectMatchCountColumn
+ _BMQueryMatchInfoTotalQueryTokensColumn
+ _BMRankedMailItemL1ScoreColumn
+ _BMRankedMailItemL2ScoreColumn
+ _BMRankedMailItemMessageFeaturesColumn
+ _BMRankedMailItemQueryMatchInfoColumn
+ _BMRankedMailItemResultIdColumn
+ _BMResultsRankedGLPIsSemanticSearchEligibleColumn
+ _BMResultsRankedGLPIsSemanticSearchTriggeredColumn
+ _BMResultsRankedGLPQueryAnalysisTimingColumn
+ _BMResultsRankedGLPRankedMailItemColumn
+ _BMResultsRankedGLPRankingTimingColumn
+ _BMResultsRankedGLPRetrievalTimingColumn
+ _BMResultsRankedGLPSectionTypeColumn
+ _BMTrustKitDecisioningTKWalletOrderExtractionDomainsIdentifier
+ _BMTrustKitTKWalletOrderExtractionDomainsDeviceLanguageColumn
+ _BMTrustKitTKWalletOrderExtractionDomainsDomainColumn
+ _BMTrustKitTKWalletOrderExtractionDomainsLocaleColumn
+ _BMTrustKitTKWalletOrderExtractionDomainsMatchStatusColumn
+ _BMTrustKitTKWalletOrderExtractionDomainsRecordIdColumn
+ _BMTrustKitTKWalletOrderExtractionDomainsRecordVersionColumn
+ _BMTrustKitTKWalletOrderExtractionDomainsRecordZoneColumn
+ _BMTrustKitTKWalletOrderExtractionDomainsUafVersionColumn
+ _OBJC_CLASS_$_BMCommAppsCallContextCardsFedStats
+ _OBJC_CLASS_$_BML1Score
+ _OBJC_CLASS_$_BML2Score
+ _OBJC_CLASS_$_BMMessageFeatures
+ _OBJC_CLASS_$_BMQueryMatchInfo
+ _OBJC_CLASS_$_BMRankedMailItem
+ _OBJC_CLASS_$_BMResultsRankedGLP
+ _OBJC_CLASS_$_BMTrustKitTKWalletOrderExtractionDomains
+ _OBJC_IVAR_$_BMCommAppsCallContextCardsFedStats._cardTitle
+ _OBJC_IVAR_$_BMCommAppsCallContextCardsFedStats._dataVersion
+ _OBJC_IVAR_$_BMCommAppsCallContextCardsFedStats._engagementType
+ _OBJC_IVAR_$_BMCommAppsCallContextCardsFedStats._filteredReason
+ _OBJC_IVAR_$_BML1Score._bm25
+ _OBJC_IVAR_$_BML1Score._cosineSim
+ _OBJC_IVAR_$_BML1Score._dataVersion
+ _OBJC_IVAR_$_BML1Score._hasBm25
+ _OBJC_IVAR_$_BML1Score._hasCosineSim
+ _OBJC_IVAR_$_BML1Score._hasL1Rank
+ _OBJC_IVAR_$_BML1Score._hasRrf
+ _OBJC_IVAR_$_BML1Score._l1Rank
+ _OBJC_IVAR_$_BML1Score._rrf
+ _OBJC_IVAR_$_BML2Score._baseL2Score
+ _OBJC_IVAR_$_BML2Score._dataVersion
+ _OBJC_IVAR_$_BML2Score._engagementMultiplier
+ _OBJC_IVAR_$_BML2Score._finalL2Score
+ _OBJC_IVAR_$_BML2Score._hasBaseL2Score
+ _OBJC_IVAR_$_BML2Score._hasEngagementMultiplier
+ _OBJC_IVAR_$_BML2Score._hasFinalL2Score
+ _OBJC_IVAR_$_BML2Score._hasQualityMultiplier
+ _OBJC_IVAR_$_BML2Score._hasQuerymatchMultiplier
+ _OBJC_IVAR_$_BML2Score._hasRanktrustMultiplier
+ _OBJC_IVAR_$_BML2Score._hasStructuralMultiplier
+ _OBJC_IVAR_$_BML2Score._hasTemporalMultiplier
+ _OBJC_IVAR_$_BML2Score._qualityMultiplier
+ _OBJC_IVAR_$_BML2Score._querymatchMultiplier
+ _OBJC_IVAR_$_BML2Score._ranktrustMultiplier
+ _OBJC_IVAR_$_BML2Score._structuralMultiplier
+ _OBJC_IVAR_$_BML2Score._temporalMultiplier
+ _OBJC_IVAR_$_BMMailRankerEvent._resultsRankedGLP
+ _OBJC_IVAR_$_BMMessageFeatures._attachmentCount
+ _OBJC_IVAR_$_BMMessageFeatures._dataVersion
+ _OBJC_IVAR_$_BMMessageFeatures._daysSinceReceived
+ _OBJC_IVAR_$_BMMessageFeatures._daysSinceSent
+ _OBJC_IVAR_$_BMMessageFeatures._hasAttachmentCount
+ _OBJC_IVAR_$_BMMessageFeatures._hasAttachments
+ _OBJC_IVAR_$_BMMessageFeatures._hasDaysSinceReceived
+ _OBJC_IVAR_$_BMMessageFeatures._hasDaysSinceSent
+ _OBJC_IVAR_$_BMMessageFeatures._hasHasAttachments
+ _OBJC_IVAR_$_BMMessageFeatures._hasHasThreadId
+ _OBJC_IVAR_$_BMMessageFeatures._hasIsFlagged
+ _OBJC_IVAR_$_BMMessageFeatures._hasIsJunk
+ _OBJC_IVAR_$_BMMessageFeatures._hasIsReplied
+ _OBJC_IVAR_$_BMMessageFeatures._hasIsReply
+ _OBJC_IVAR_$_BMMessageFeatures._hasIsUnread
+ _OBJC_IVAR_$_BMMessageFeatures._hasRecipientCount
+ _OBJC_IVAR_$_BMMessageFeatures._hasThreadId
+ _OBJC_IVAR_$_BMMessageFeatures._isFlagged
+ _OBJC_IVAR_$_BMMessageFeatures._isJunk
+ _OBJC_IVAR_$_BMMessageFeatures._isReplied
+ _OBJC_IVAR_$_BMMessageFeatures._isReply
+ _OBJC_IVAR_$_BMMessageFeatures._isUnread
+ _OBJC_IVAR_$_BMMessageFeatures._recipientCount
+ _OBJC_IVAR_$_BMQueryMatchInfo._bodyMatchCount
+ _OBJC_IVAR_$_BMQueryMatchInfo._dataVersion
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasBodyMatchCount
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasExactPhraseMatchInBody
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasExactPhraseMatchInRecipient
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasExactPhraseMatchInSender
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasExactPhraseMatchInSubject
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasHasExactPhraseMatchInBody
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasHasExactPhraseMatchInRecipient
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasHasExactPhraseMatchInSender
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasHasExactPhraseMatchInSubject
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasLastTokenIsExactInSender
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasLastTokenIsExactInSubject
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasLastTokenMatchesSender
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasLastTokenMatchesSubject
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasMatchedTokens
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasQueryIndex
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasRecipientMatchCount
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasSenderMatchCount
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasSubjectMatchCount
+ _OBJC_IVAR_$_BMQueryMatchInfo._hasTotalQueryTokens
+ _OBJC_IVAR_$_BMQueryMatchInfo._lastTokenIsExactInSender
+ _OBJC_IVAR_$_BMQueryMatchInfo._lastTokenIsExactInSubject
+ _OBJC_IVAR_$_BMQueryMatchInfo._lastTokenMatchesSender
+ _OBJC_IVAR_$_BMQueryMatchInfo._lastTokenMatchesSubject
+ _OBJC_IVAR_$_BMQueryMatchInfo._matchedTokens
+ _OBJC_IVAR_$_BMQueryMatchInfo._queryIndex
+ _OBJC_IVAR_$_BMQueryMatchInfo._recipientMatchCount
+ _OBJC_IVAR_$_BMQueryMatchInfo._senderMatchCount
+ _OBJC_IVAR_$_BMQueryMatchInfo._subjectMatchCount
+ _OBJC_IVAR_$_BMQueryMatchInfo._totalQueryTokens
+ _OBJC_IVAR_$_BMRankedMailItem._dataVersion
+ _OBJC_IVAR_$_BMRankedMailItem._l1Score
+ _OBJC_IVAR_$_BMRankedMailItem._l2Score
+ _OBJC_IVAR_$_BMRankedMailItem._messageFeatures
+ _OBJC_IVAR_$_BMRankedMailItem._queryMatchInfo
+ _OBJC_IVAR_$_BMRankedMailItem._resultId
+ _OBJC_IVAR_$_BMResultsRankedGLP._dataVersion
+ _OBJC_IVAR_$_BMResultsRankedGLP._hasIsSemanticSearchEligible
+ _OBJC_IVAR_$_BMResultsRankedGLP._hasIsSemanticSearchTriggered
+ _OBJC_IVAR_$_BMResultsRankedGLP._hasQueryAnalysisTiming
+ _OBJC_IVAR_$_BMResultsRankedGLP._hasRankingTiming
+ _OBJC_IVAR_$_BMResultsRankedGLP._hasRetrievalTiming
+ _OBJC_IVAR_$_BMResultsRankedGLP._isSemanticSearchEligible
+ _OBJC_IVAR_$_BMResultsRankedGLP._isSemanticSearchTriggered
+ _OBJC_IVAR_$_BMResultsRankedGLP._queryAnalysisTiming
+ _OBJC_IVAR_$_BMResultsRankedGLP._rankedMailItem
+ _OBJC_IVAR_$_BMResultsRankedGLP._rankingTiming
+ _OBJC_IVAR_$_BMResultsRankedGLP._retrievalTiming
+ _OBJC_IVAR_$_BMResultsRankedGLP._sectionType
+ _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionDomains._dataVersion
+ _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionDomains._deviceLanguage
+ _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionDomains._domain
+ _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionDomains._locale
+ _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionDomains._matchStatus
+ _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionDomains._recordId
+ _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionDomains._recordVersion
+ _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionDomains._recordZone
+ _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionDomains._uafVersion
+ _OBJC_METACLASS_$_BMCommAppsCallContextCardsFedStats
+ _OBJC_METACLASS_$_BML1Score
+ _OBJC_METACLASS_$_BML2Score
+ _OBJC_METACLASS_$_BMMessageFeatures
+ _OBJC_METACLASS_$_BMQueryMatchInfo
+ _OBJC_METACLASS_$_BMRankedMailItem
+ _OBJC_METACLASS_$_BMResultsRankedGLP
+ _OBJC_METACLASS_$_BMTrustKitTKWalletOrderExtractionDomains
+ __OBJC_$_CLASS_METHODS_BMCommAppsCallContextCardsFedStats
+ __OBJC_$_CLASS_METHODS_BML1Score
+ __OBJC_$_CLASS_METHODS_BML2Score
+ __OBJC_$_CLASS_METHODS_BMMessageFeatures
+ __OBJC_$_CLASS_METHODS_BMQueryMatchInfo
+ __OBJC_$_CLASS_METHODS_BMRankedMailItem
+ __OBJC_$_CLASS_METHODS_BMResultsRankedGLP
+ __OBJC_$_CLASS_METHODS_BMTrustKitTKWalletOrderExtractionDomains
+ __OBJC_$_CLASS_PROP_LIST_BMCommAppsCallContextCardsFedStats
+ __OBJC_$_CLASS_PROP_LIST_BML1Score
+ __OBJC_$_CLASS_PROP_LIST_BML2Score
+ __OBJC_$_CLASS_PROP_LIST_BMMessageFeatures
+ __OBJC_$_CLASS_PROP_LIST_BMQueryMatchInfo
+ __OBJC_$_CLASS_PROP_LIST_BMRankedMailItem
+ __OBJC_$_CLASS_PROP_LIST_BMResultsRankedGLP
+ __OBJC_$_CLASS_PROP_LIST_BMTrustKitTKWalletOrderExtractionDomains
+ __OBJC_$_INSTANCE_METHODS_BMCommAppsCallContextCardsFedStats
+ __OBJC_$_INSTANCE_METHODS_BML1Score
+ __OBJC_$_INSTANCE_METHODS_BML2Score
+ __OBJC_$_INSTANCE_METHODS_BMMailRankerEvent(Deprecation)
+ __OBJC_$_INSTANCE_METHODS_BMMessageFeatures
+ __OBJC_$_INSTANCE_METHODS_BMQueryMatchInfo
+ __OBJC_$_INSTANCE_METHODS_BMRankedMailItem
+ __OBJC_$_INSTANCE_METHODS_BMResultsRankedGLP
+ __OBJC_$_INSTANCE_METHODS_BMTrustKitTKWalletOrderExtractionDomains
+ __OBJC_$_INSTANCE_VARIABLES_BMCommAppsCallContextCardsFedStats
+ __OBJC_$_INSTANCE_VARIABLES_BML1Score
+ __OBJC_$_INSTANCE_VARIABLES_BML2Score
+ __OBJC_$_INSTANCE_VARIABLES_BMMessageFeatures
+ __OBJC_$_INSTANCE_VARIABLES_BMQueryMatchInfo
+ __OBJC_$_INSTANCE_VARIABLES_BMRankedMailItem
+ __OBJC_$_INSTANCE_VARIABLES_BMResultsRankedGLP
+ __OBJC_$_INSTANCE_VARIABLES_BMTrustKitTKWalletOrderExtractionDomains
+ __OBJC_$_PROP_LIST_BMCommAppsCallContextCardsFedStats
+ __OBJC_$_PROP_LIST_BML1Score
+ __OBJC_$_PROP_LIST_BML2Score
+ __OBJC_$_PROP_LIST_BMMessageFeatures
+ __OBJC_$_PROP_LIST_BMQueryMatchInfo
+ __OBJC_$_PROP_LIST_BMRankedMailItem
+ __OBJC_$_PROP_LIST_BMResultsRankedGLP
+ __OBJC_$_PROP_LIST_BMTrustKitTKWalletOrderExtractionDomains
+ __OBJC_CLASS_PROTOCOLS_$_BMCommAppsCallContextCardsFedStats
+ __OBJC_CLASS_PROTOCOLS_$_BML1Score
+ __OBJC_CLASS_PROTOCOLS_$_BML2Score
+ __OBJC_CLASS_PROTOCOLS_$_BMMessageFeatures
+ __OBJC_CLASS_PROTOCOLS_$_BMQueryMatchInfo
+ __OBJC_CLASS_PROTOCOLS_$_BMRankedMailItem
+ __OBJC_CLASS_PROTOCOLS_$_BMResultsRankedGLP
+ __OBJC_CLASS_PROTOCOLS_$_BMTrustKitTKWalletOrderExtractionDomains
+ __OBJC_CLASS_RO_$_BMCommAppsCallContextCardsFedStats
+ __OBJC_CLASS_RO_$_BML1Score
+ __OBJC_CLASS_RO_$_BML2Score
+ __OBJC_CLASS_RO_$_BMMessageFeatures
+ __OBJC_CLASS_RO_$_BMQueryMatchInfo
+ __OBJC_CLASS_RO_$_BMRankedMailItem
+ __OBJC_CLASS_RO_$_BMResultsRankedGLP
+ __OBJC_CLASS_RO_$_BMTrustKitTKWalletOrderExtractionDomains
+ __OBJC_METACLASS_RO_$_BMCommAppsCallContextCardsFedStats
+ __OBJC_METACLASS_RO_$_BML1Score
+ __OBJC_METACLASS_RO_$_BML2Score
+ __OBJC_METACLASS_RO_$_BMMessageFeatures
+ __OBJC_METACLASS_RO_$_BMQueryMatchInfo
+ __OBJC_METACLASS_RO_$_BMRankedMailItem
+ __OBJC_METACLASS_RO_$_BMResultsRankedGLP
+ __OBJC_METACLASS_RO_$_BMTrustKitTKWalletOrderExtractionDomains
+ ___27+[BMRankedMailItem columns]_block_invoke
+ ___27+[BMRankedMailItem columns]_block_invoke_2
+ ___27+[BMRankedMailItem columns]_block_invoke_3
+ ___27+[BMRankedMailItem columns]_block_invoke_4
+ ___28+[BMMailRankerEvent columns]_block_invoke_2
+ ___29+[BMResultsRankedGLP columns]_block_invoke
+ ___BMCommAppsCallContextCardsFedStatsEngagementTypeFromString_block_invoke
+ ___BMCommAppsCallContextCardsFedStatsFilteredReasonFromString_block_invoke
- +[BMTrustKitTKWalletOrderExtractionMissedMatches columns]
- +[BMTrustKitTKWalletOrderExtractionMissedMatches eventWithData:dataVersion:]
- +[BMTrustKitTKWalletOrderExtractionMissedMatches latestDataVersion]
- +[BMTrustKitTKWalletOrderExtractionMissedMatches protoFields]
- +[BMTrustKitTKWalletOrderExtractionMissedMatches validKeyPaths]
- +[_BMTrustKitDecisioningLibraryNode TKWalletOrderExtractionMissedMatches]
- +[_BMTrustKitDecisioningLibraryNode configurationForTKWalletOrderExtractionMissedMatches]
- +[_BMTrustKitDecisioningLibraryNode storeConfigurationForTKWalletOrderExtractionMissedMatches]
- +[_BMTrustKitDecisioningLibraryNode syncPolicyForTKWalletOrderExtractionMissedMatches]
- -[BMMailRankerEvent initWithSessionId:queryId:resultsRanked:]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches .cxx_destruct]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches dataVersion]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches description]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches deviceLanguage]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches initByReadFrom:]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches initWithJSONDictionary:error:]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches initWithUnmatchedDomain:uafVersion:recordId:recordZone:recordVersion:locale:deviceLanguage:]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches isEqual:]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches jsonDictionary]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches locale]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches recordId]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches recordVersion]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches recordZone]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches serialize]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches uafVersion]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches unmatchedDomain]
- -[BMTrustKitTKWalletOrderExtractionMissedMatches writeTo:]
- _BMTrustKitDecisioningTKWalletOrderExtractionMissedMatchesIdentifier
- _BMTrustKitTKWalletOrderExtractionMissedMatchesDeviceLanguageColumn
- _BMTrustKitTKWalletOrderExtractionMissedMatchesLocaleColumn
- _BMTrustKitTKWalletOrderExtractionMissedMatchesRecordIdColumn
- _BMTrustKitTKWalletOrderExtractionMissedMatchesRecordVersionColumn
- _BMTrustKitTKWalletOrderExtractionMissedMatchesRecordZoneColumn
- _BMTrustKitTKWalletOrderExtractionMissedMatchesUafVersionColumn
- _BMTrustKitTKWalletOrderExtractionMissedMatchesUnmatchedDomainColumn
- _OBJC_CLASS_$_BMTrustKitTKWalletOrderExtractionMissedMatches
- _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionMissedMatches._dataVersion
- _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionMissedMatches._deviceLanguage
- _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionMissedMatches._locale
- _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionMissedMatches._recordId
- _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionMissedMatches._recordVersion
- _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionMissedMatches._recordZone
- _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionMissedMatches._uafVersion
- _OBJC_IVAR_$_BMTrustKitTKWalletOrderExtractionMissedMatches._unmatchedDomain
- _OBJC_METACLASS_$_BMTrustKitTKWalletOrderExtractionMissedMatches
- __OBJC_$_CLASS_METHODS_BMTrustKitTKWalletOrderExtractionMissedMatches
- __OBJC_$_CLASS_PROP_LIST_BMTrustKitTKWalletOrderExtractionMissedMatches
- __OBJC_$_INSTANCE_METHODS_BMMailRankerEvent
- __OBJC_$_INSTANCE_METHODS_BMTrustKitTKWalletOrderExtractionMissedMatches
- __OBJC_$_INSTANCE_VARIABLES_BMTrustKitTKWalletOrderExtractionMissedMatches
- __OBJC_$_PROP_LIST_BMTrustKitTKWalletOrderExtractionMissedMatches
- __OBJC_CLASS_PROTOCOLS_$_BMTrustKitTKWalletOrderExtractionMissedMatches
- __OBJC_CLASS_RO_$_BMTrustKitTKWalletOrderExtractionMissedMatches
- __OBJC_METACLASS_RO_$_BMTrustKitTKWalletOrderExtractionMissedMatches
CStrings:
+ "84A12F68-F914-451C-AFEF-442805BCD64D"
+ "BMCommAppsCallContextCardsFedStats with cardTitle: %@, filteredReason: %@, engagementType: %@"
+ "BML1Score with bm25: %@, cosineSim: %@, rrf: %@, l1Rank: %@"
+ "BML2Score with baseL2Score: %@, temporalMultiplier: %@, querymatchMultiplier: %@, engagementMultiplier: %@, structuralMultiplier: %@, qualityMultiplier: %@, ranktrustMultiplier: %@, finalL2Score: %@"
+ "BMMailRankerEvent with sessionId: %@, queryId: %@, resultsRanked: %@, resultsRankedGLP: %@"
+ "BMMessageFeatures with isUnread: %@, isFlagged: %@, isJunk: %@, isReply: %@, isReplied: %@, daysSinceReceived: %@, daysSinceSent: %@, hasAttachments: %@, attachmentCount: %@, recipientCount: %@, hasThreadId: %@"
+ "BMQueryMatchInfo with queryIndex: %@, subjectMatchCount: %@, senderMatchCount: %@, recipientMatchCount: %@, bodyMatchCount: %@, totalQueryTokens: %@, matchedTokens: %@, lastTokenMatchesSubject: %@, lastTokenMatchesSender: %@, lastTokenIsExactInSubject: %@, lastTokenIsExactInSender: %@, hasExactPhraseMatchInSubject: %@, hasExactPhraseMatchInSender: %@, hasExactPhraseMatchInRecipient: %@, hasExactPhraseMatchInBody: %@"
+ "BMRankedMailItem with resultId: %@, l1Score: %@, l2Score: %@, queryMatchInfo: %@, messageFeatures: %@"
+ "BMResultsRankedGLP with isSemanticSearchEligible: %@, isSemanticSearchTriggered: %@, queryAnalysisTiming: %@, retrievalTiming: %@, rankingTiming: %@, sectionType: %@, rankedMailItem: %@"
+ "BMTrustKitTKWalletOrderExtractionDomains with domain: %@, uafVersion: %@, recordId: %@, recordZone: %@, recordVersion: %@, locale: %@, deviceLanguage: %@, matchStatus: %@"
+ "BusinessNameNotInItem"
+ "CallContextCardsFedStats"
+ "CarReservationForName"
+ "CarReservationForNameAndID"
+ "CarReservationID"
+ "CommApps.CallIntelligence.CallContextCardsFedStats"
+ "FlightArrivalAirportCode"
+ "FlightArrivalDateTime"
+ "FlightArrivalTimeZone"
+ "FlightCarrierName"
+ "FlightConfirmationNumber"
+ "FlightDepartureAirportCode"
+ "FlightDepartureDateTime"
+ "FlightDepartureTimeZone"
+ "HotelReservationForName"
+ "HotelReservationForNameAndID"
+ "HotelReservationId"
+ "NoEngagement"
+ "NotFiltered"
+ "ReadAloudPaused"
+ "ReadAloudStarted"
+ "RestaurantConfirmationNumber"
+ "RestaurantName"
+ "RestaurantNameAndConfirmationNumber"
+ "ShowReservationAndTitleOrVenue"
+ "ShowReservationID"
+ "ShowTitleOrVenue"
+ "TKWalletOrderExtractionDomains"
+ "TrustKit.Decisioning.TKWalletOrderExtractionDomains"
+ "TuPartialExtraction"
+ "ViewSource"
+ "ViewSourceAndReadAloudPaused"
+ "ViewSourceAndReadAloudStarted"
+ "attachmentCount"
+ "baseL2Score"
+ "bm25"
+ "bodyMatchCount"
+ "cardTitle"
+ "com.apple.callservicesd"
+ "cosineSim"
+ "daysSinceReceived"
+ "daysSinceSent"
+ "engagementMultiplier"
+ "filteredReason"
+ "finalL2Score"
+ "hasAttachments"
+ "hasExactPhraseMatchInBody"
+ "hasExactPhraseMatchInRecipient"
+ "hasExactPhraseMatchInSender"
+ "hasExactPhraseMatchInSubject"
+ "hasThreadId"
+ "isReply"
+ "isUnread"
+ "l1Rank"
+ "l1Score_json"
+ "l2Score_json"
+ "lastTokenIsExactInSender"
+ "lastTokenIsExactInSubject"
+ "lastTokenMatchesSender"
+ "lastTokenMatchesSubject"
+ "matchStatus"
+ "matchedTokens"
+ "messageFeatures"
+ "messageFeatures_json"
+ "qualityMultiplier"
+ "queryIndex"
+ "queryMatchInfo"
+ "queryMatchInfo_json"
+ "querymatchMultiplier"
+ "rankedMailItem"
+ "rankedMailItem_json"
+ "ranktrustMultiplier"
+ "recipientCount"
+ "recipientMatchCount"
+ "resultsRankedGLP"
+ "resultsRankedGLP_json"
+ "rrf"
+ "senderMatchCount"
+ "structuralMultiplier"
+ "subjectMatchCount"
+ "temporalMultiplier"
+ "totalQueryTokens"
- "BMMailRankerEvent with sessionId: %@, queryId: %@, resultsRanked: %@"
- "BMTrustKitTKWalletOrderExtractionMissedMatches with unmatchedDomain: %@, uafVersion: %@, recordId: %@, recordZone: %@, recordVersion: %@, locale: %@, deviceLanguage: %@"
- "TKWalletOrderExtractionMissedMatches"
- "TrustKit.Decisioning.TKWalletOrderExtractionMissedMatches"
- "unmatchedDomain"
```
