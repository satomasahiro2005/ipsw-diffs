## BiomeLibrary

> `/System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x748b3c` | `0x753ffc` | **`+0xb4c0`** |
| `__AUTH_CONST.__objc_const` | `0xa1d40` | `0xa2900` | **`+0xbc0`** |
| `__TEXT.__cstring` | `0x4e0ec` | `0x4e720` | **`+0x634`** |
| `__AUTH_CONST.__cfstring` | `0x4acc0` | `0x4b060` | **`+0x3a0`** |
| `__TEXT.__objc_methlist` | `0x4fd44` | `0x500dc` | **`+0x398`** |
| `__DATA_CONST.__objc_selrefs` | `0x12748` | `0x12948` | **`+0x200`** |
| `__DATA_CONST.__const` | `0x1e9b8` | `0x1eb28` | **`+0x170`** |
| `__DATA_CONST.__objc_arraydata` | `0xb0a8` | `0xb218` | **`+0x170`** |
| `__DATA.__objc_ivar` | `0x80f4` | `0x81f4` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0xf768` | `0xf778` | **`+0x10`** |

### Other Changes

```diff

-426.0.0.0.0
+435.0.0.0.0

-  Functions: 28554
-  Symbols:   52727
-  CStrings:  9707
+  Functions: 28633
+  Symbols:   52914
+  CStrings:  9737
Symbols:
+ +[BMSiriUnifiedSiriTurn columns]
+ +[BMSiriUnifiedSiriTurn eventWithData:dataVersion:]
+ +[BMSiriUnifiedSiriTurn latestDataVersion]
+ +[BMSiriUnifiedSiriTurn protoFields]
+ +[BMSiriUnifiedSiriTurn validKeyPaths]
+ +[_BMSiriLibraryNode UnifiedSiriTurn]
+ +[_BMSiriLibraryNode configurationForUnifiedSiriTurn]
+ +[_BMSiriLibraryNode storeConfigurationForUnifiedSiriTurn]
+ +[_BMSiriLibraryNode syncPolicyForUnifiedSiriTurn]
+ -[BMGeneratedImageImageGeneration assetIdentifier]
+ -[BMGeneratedImageImageGeneration initWithPromptIdentifier:imageIdentifier:promptAfterRewrite:promptAfterAssembly:imageForPersonalization:featureModel:generatedImage:secondImageForPersonalization:thirdImageForPersonalization:assetIdentifier:]
+ -[BMGeneratedImageImageGeneration(Deprecation) initWithPromptIdentifier:imageIdentifier:promptAfterRewrite:promptAfterAssembly:imageForPersonalization:featureModel:generatedImage:secondImageForPersonalization:thirdImageForPersonalization:]
+ -[BMGeneratedImageImageInteraction assetIdentifier]
+ -[BMGeneratedImageImageInteraction initWithImageIdentifier:promptIdentifer:engaged:numViews:timeViewed:saved:shared:copied:inserted:duplicated:captionAdded:usedAsWallpaper:reportAConcern:deleted:assetIdentifier:]
+ -[BMGeneratedImageImageInteraction(Deprecation) initWithImageIdentifier:promptIdentifer:engaged:numViews:timeViewed:saved:shared:copied:inserted:duplicated:captionAdded:usedAsWallpaper:reportAConcern:deleted:]
+ -[BMGeneratedImageUserInteraction assetIdentifier]
+ -[BMGeneratedImageUserInteraction initWithTimestamp:prompt:tokenLength:identifier:topic:usage:userInterfaceLanguage:userSetRegionFormat:personalization:result:feature:style:hair:facialHair:accessories:additionalDescription:sessionIdentifier:isLastPrompt:promptIdentifier:collectionIdentifier:aspectRatio:resolution:numPeople:promptAction:parentPromptIdentifier:directManipulation:featureModel:generationSource:pregeneration:assetIdentifier:]
+ -[BMGeneratedImageUserInteraction(Deprecation) initWithTimestamp:prompt:tokenLength:identifier:topic:usage:userInterfaceLanguage:userSetRegionFormat:personalization:result:feature:style:hair:facialHair:accessories:additionalDescription:sessionIdentifier:isLastPrompt:promptIdentifier:collectionIdentifier:aspectRatio:resolution:numPeople:promptAction:parentPromptIdentifier:directManipulation:featureModel:generationSource:pregeneration:]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsBusinessCard]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsDriverLicense]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsEmployeeCard]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsFailedGatingHeuristic]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsFailedGatingModel]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsGreenCard]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsInsuranceCard]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsMedicalCard]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsMembershipCard]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsNationalID]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsPassGateWithoutResults]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsPassport]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsSocialSecurityNumber]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsStateID]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsStudentCard]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsTransitCard]
+ -[BMMediaAnalysisProcessingResults hasNumberOfAssetsUnknown]
+ -[BMMediaAnalysisProcessingResults initWithNumberOfAssetsAnalyzed:numberOfAssetsFailedGatingHeuristic:numberOfAssetsFailedGatingModel:numberOfAssetsPassGateWithoutResults:numberOfAssetsPassGateWithResults:numberOfAssetsUnknown:numberOfAssetsPassport:numberOfAssetsDriverLicense:numberOfAssetsBusinessCard:numberOfAssetsGreenCard:numberOfAssetsSocialSecurityNumber:numberOfAssetsMedicalCard:numberOfAssetsInsuranceCard:numberOfAssetsMembershipCard:numberOfAssetsTransitCard:numberOfAssetsStateID:numberOfAssetsStudentCard:numberOfAssetsEmployeeCard:numberOfAssetsNationalID:]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsBusinessCard]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsDriverLicense]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsEmployeeCard]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsFailedGatingHeuristic]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsFailedGatingModel]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsGreenCard]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsInsuranceCard]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsMedicalCard]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsMembershipCard]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsNationalID]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsPassGateWithoutResults]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsPassport]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsSocialSecurityNumber]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsStateID]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsStudentCard]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsTransitCard]
+ -[BMMediaAnalysisProcessingResults numberOfAssetsUnknown]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsBusinessCard:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsDriverLicense:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsEmployeeCard:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsFailedGatingHeuristic:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsFailedGatingModel:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsGreenCard:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsInsuranceCard:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsMedicalCard:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsMembershipCard:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsNationalID:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsPassGateWithoutResults:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsPassport:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsSocialSecurityNumber:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsStateID:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsStudentCard:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsTransitCard:]
+ -[BMMediaAnalysisProcessingResults setHasNumberOfAssetsUnknown:]
+ -[BMSiriUnifiedSiriTurn .cxx_destruct]
+ -[BMSiriUnifiedSiriTurn asrLocation]
+ -[BMSiriUnifiedSiriTurn assistantId]
+ -[BMSiriUnifiedSiriTurn clockStartTime]
+ -[BMSiriUnifiedSiriTurn dataSharingOptInState]
+ -[BMSiriUnifiedSiriTurn dataVersion]
+ -[BMSiriUnifiedSiriTurn description]
+ -[BMSiriUnifiedSiriTurn deviceAggregationId]
+ -[BMSiriUnifiedSiriTurn deviceType]
+ -[BMSiriUnifiedSiriTurn dictationUsedLocale]
+ -[BMSiriUnifiedSiriTurn didResumeSiriApp]
+ -[BMSiriUnifiedSiriTurn didUseOnScreenAwareness]
+ -[BMSiriUnifiedSiriTurn didUseWKASummarization]
+ -[BMSiriUnifiedSiriTurn executionCategory]
+ -[BMSiriUnifiedSiriTurn experimentInfos]
+ -[BMSiriUnifiedSiriTurn genAiRequestOutcome]
+ -[BMSiriUnifiedSiriTurn hasDidResumeSiriApp]
+ -[BMSiriUnifiedSiriTurn hasDidUseOnScreenAwareness]
+ -[BMSiriUnifiedSiriTurn hasDidUseWKASummarization]
+ -[BMSiriUnifiedSiriTurn hasIsCarPlay]
+ -[BMSiriUnifiedSiriTurn hasIsContextualFollowUp]
+ -[BMSiriUnifiedSiriTurn hasIsExplicitGenAiRequest]
+ -[BMSiriUnifiedSiriTurn hasIsGenAIAttempted]
+ -[BMSiriUnifiedSiriTurn hasIsLlmSiriEnabled]
+ -[BMSiriUnifiedSiriTurn hasIsTurnTaken]
+ -[BMSiriUnifiedSiriTurn initByReadFrom:]
+ -[BMSiriUnifiedSiriTurn initWithJSONDictionary:error:]
+ -[BMSiriUnifiedSiriTurn initWithTurnId:invocationTime:clockStartTime:deviceType:systemBuild:programCode:dataSharingOptInState:siriInputLocale:deviceAggregationId:userAggregationId:userAggregationIdRotationDate:userAggregationIdExpirationDate:invocationSource:productId:requestType:productArea:siriResponse:dictationUsedLocale:asrLocation:nlLocation:mhAudioVendorId:mhAudioProductId:thirdPartyGenAIAgent:genAiRequestOutcome:experimentInfos:isLlmSiriEnabled:isGenAIAttempted:isTurnTaken:isCarPlay:isExplicitGenAiRequest:userUtterance:responseText:assistantId:executionCategory:didUseWKASummarization:didUseOnScreenAwareness:isContextualFollowUp:didResumeSiriApp:orchestrationMode:]
+ -[BMSiriUnifiedSiriTurn invocationSource]
+ -[BMSiriUnifiedSiriTurn invocationTime]
+ -[BMSiriUnifiedSiriTurn isCarPlay]
+ -[BMSiriUnifiedSiriTurn isContextualFollowUp]
+ -[BMSiriUnifiedSiriTurn isEqual:]
+ -[BMSiriUnifiedSiriTurn isExplicitGenAiRequest]
+ -[BMSiriUnifiedSiriTurn isGenAIAttempted]
+ -[BMSiriUnifiedSiriTurn isLlmSiriEnabled]
+ -[BMSiriUnifiedSiriTurn isTurnTaken]
+ -[BMSiriUnifiedSiriTurn jsonDictionary]
+ -[BMSiriUnifiedSiriTurn mhAudioProductId]
+ -[BMSiriUnifiedSiriTurn mhAudioVendorId]
+ -[BMSiriUnifiedSiriTurn nlLocation]
+ -[BMSiriUnifiedSiriTurn orchestrationMode]
+ -[BMSiriUnifiedSiriTurn productArea]
+ -[BMSiriUnifiedSiriTurn productId]
+ -[BMSiriUnifiedSiriTurn programCode]
+ -[BMSiriUnifiedSiriTurn requestType]
+ -[BMSiriUnifiedSiriTurn responseText]
+ -[BMSiriUnifiedSiriTurn serialize]
+ -[BMSiriUnifiedSiriTurn setHasDidResumeSiriApp:]
+ -[BMSiriUnifiedSiriTurn setHasDidUseOnScreenAwareness:]
+ -[BMSiriUnifiedSiriTurn setHasDidUseWKASummarization:]
+ -[BMSiriUnifiedSiriTurn setHasIsCarPlay:]
+ -[BMSiriUnifiedSiriTurn setHasIsContextualFollowUp:]
+ -[BMSiriUnifiedSiriTurn setHasIsExplicitGenAiRequest:]
+ -[BMSiriUnifiedSiriTurn setHasIsGenAIAttempted:]
+ -[BMSiriUnifiedSiriTurn setHasIsLlmSiriEnabled:]
+ -[BMSiriUnifiedSiriTurn setHasIsTurnTaken:]
+ -[BMSiriUnifiedSiriTurn siriInputLocale]
+ -[BMSiriUnifiedSiriTurn siriResponse]
+ -[BMSiriUnifiedSiriTurn systemBuild]
+ -[BMSiriUnifiedSiriTurn thirdPartyGenAIAgent]
+ -[BMSiriUnifiedSiriTurn turnId]
+ -[BMSiriUnifiedSiriTurn userAggregationIdExpirationDate]
+ -[BMSiriUnifiedSiriTurn userAggregationIdRotationDate]
+ -[BMSiriUnifiedSiriTurn userAggregationId]
+ -[BMSiriUnifiedSiriTurn userUtterance]
+ -[BMSiriUnifiedSiriTurn writeTo:]
+ _BMGeneratedImageImageGenerationAssetIdentifierColumn
+ _BMGeneratedImageImageInteractionAssetIdentifierColumn
+ _BMGeneratedImageUserInteractionAssetIdentifierColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsBusinessCardColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsDriverLicenseColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsEmployeeCardColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsFailedGatingHeuristicColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsFailedGatingModelColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsGreenCardColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsInsuranceCardColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsMedicalCardColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsMembershipCardColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsNationalIDColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsPassGateWithoutResultsColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsPassportColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsSocialSecurityNumberColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsStateIDColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsStudentCardColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsTransitCardColumn
+ _BMMediaAnalysisProcessingResultsNumberOfAssetsUnknownColumn
+ _BMSiriUnifiedSiriTurnAsrLocationColumn
+ _BMSiriUnifiedSiriTurnAssistantIdColumn
+ _BMSiriUnifiedSiriTurnClockStartTimeColumn
+ _BMSiriUnifiedSiriTurnDataSharingOptInStateColumn
+ _BMSiriUnifiedSiriTurnDeviceAggregationIdColumn
+ _BMSiriUnifiedSiriTurnDeviceTypeColumn
+ _BMSiriUnifiedSiriTurnDictationUsedLocaleColumn
+ _BMSiriUnifiedSiriTurnDidResumeSiriAppColumn
+ _BMSiriUnifiedSiriTurnDidUseOnScreenAwarenessColumn
+ _BMSiriUnifiedSiriTurnDidUseWKASummarizationColumn
+ _BMSiriUnifiedSiriTurnExecutionCategoryColumn
+ _BMSiriUnifiedSiriTurnExperimentInfosColumn
+ _BMSiriUnifiedSiriTurnGenAiRequestOutcomeColumn
+ _BMSiriUnifiedSiriTurnIdentifier
+ _BMSiriUnifiedSiriTurnInvocationSourceColumn
+ _BMSiriUnifiedSiriTurnInvocationTimeColumn
+ _BMSiriUnifiedSiriTurnIsCarPlayColumn
+ _BMSiriUnifiedSiriTurnIsContextualFollowUpColumn
+ _BMSiriUnifiedSiriTurnIsExplicitGenAiRequestColumn
+ _BMSiriUnifiedSiriTurnIsGenAIAttemptedColumn
+ _BMSiriUnifiedSiriTurnIsLlmSiriEnabledColumn
+ _BMSiriUnifiedSiriTurnIsTurnTakenColumn
+ _BMSiriUnifiedSiriTurnMhAudioProductIdColumn
+ _BMSiriUnifiedSiriTurnMhAudioVendorIdColumn
+ _BMSiriUnifiedSiriTurnNlLocationColumn
+ _BMSiriUnifiedSiriTurnOrchestrationModeColumn
+ _BMSiriUnifiedSiriTurnProductAreaColumn
+ _BMSiriUnifiedSiriTurnProductIdColumn
+ _BMSiriUnifiedSiriTurnProgramCodeColumn
+ _BMSiriUnifiedSiriTurnRequestTypeColumn
+ _BMSiriUnifiedSiriTurnResponseTextColumn
+ _BMSiriUnifiedSiriTurnSiriInputLocaleColumn
+ _BMSiriUnifiedSiriTurnSiriResponseColumn
+ _BMSiriUnifiedSiriTurnSystemBuildColumn
+ _BMSiriUnifiedSiriTurnThirdPartyGenAIAgentColumn
+ _BMSiriUnifiedSiriTurnTurnIdColumn
+ _BMSiriUnifiedSiriTurnUserAggregationIdColumn
+ _BMSiriUnifiedSiriTurnUserAggregationIdExpirationDateColumn
+ _BMSiriUnifiedSiriTurnUserAggregationIdRotationDateColumn
+ _BMSiriUnifiedSiriTurnUserUtteranceColumn
+ _OBJC_CLASS_$_BMSiriUnifiedSiriTurn
+ _OBJC_IVAR_$_BMGeneratedImageImageGeneration._assetIdentifier
+ _OBJC_IVAR_$_BMGeneratedImageImageInteraction._assetIdentifier
+ _OBJC_IVAR_$_BMGeneratedImageUserInteraction._assetIdentifier
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsBusinessCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsDriverLicense
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsEmployeeCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsFailedGatingHeuristic
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsFailedGatingModel
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsGreenCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsInsuranceCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsMedicalCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsMembershipCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsNationalID
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsPassGateWithoutResults
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsPassport
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsSocialSecurityNumber
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsStateID
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsStudentCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsTransitCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._hasNumberOfAssetsUnknown
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsBusinessCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsDriverLicense
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsEmployeeCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsFailedGatingHeuristic
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsFailedGatingModel
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsGreenCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsInsuranceCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsMedicalCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsMembershipCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsNationalID
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsPassGateWithoutResults
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsPassport
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsSocialSecurityNumber
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsStateID
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsStudentCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsTransitCard
+ _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._numberOfAssetsUnknown
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._asrLocation
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._assistantId
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._dataSharingOptInState
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._dataVersion
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._deviceAggregationId
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._deviceType
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._dictationUsedLocale
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._didResumeSiriApp
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._didUseOnScreenAwareness
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._didUseWKASummarization
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._executionCategory
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._experimentInfos
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._genAiRequestOutcome
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasDidResumeSiriApp
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasDidUseOnScreenAwareness
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasDidUseWKASummarization
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasIsCarPlay
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasIsContextualFollowUp
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasIsExplicitGenAiRequest
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasIsGenAIAttempted
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasIsLlmSiriEnabled
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasIsTurnTaken
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasRaw_clockStartTime
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasRaw_invocationTime
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasRaw_userAggregationIdExpirationDate
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._hasRaw_userAggregationIdRotationDate
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._invocationSource
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._isCarPlay
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._isContextualFollowUp
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._isExplicitGenAiRequest
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._isGenAIAttempted
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._isLlmSiriEnabled
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._isTurnTaken
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._mhAudioProductId
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._mhAudioVendorId
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._nlLocation
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._orchestrationMode
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._productArea
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._productId
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._programCode
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._raw_clockStartTime
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._raw_invocationTime
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._raw_userAggregationIdExpirationDate
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._raw_userAggregationIdRotationDate
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._requestType
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._responseText
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._siriInputLocale
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._siriResponse
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._systemBuild
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._thirdPartyGenAIAgent
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._turnId
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._userAggregationId
+ _OBJC_IVAR_$_BMSiriUnifiedSiriTurn._userUtterance
+ _OBJC_METACLASS_$_BMSiriUnifiedSiriTurn
+ __OBJC_$_CLASS_METHODS_BMSiriUnifiedSiriTurn
+ __OBJC_$_CLASS_PROP_LIST_BMSiriUnifiedSiriTurn
+ __OBJC_$_INSTANCE_METHODS_BMSiriUnifiedSiriTurn
+ __OBJC_$_INSTANCE_VARIABLES_BMSiriUnifiedSiriTurn
+ __OBJC_$_PROP_LIST_BMSiriUnifiedSiriTurn
+ __OBJC_CLASS_PROTOCOLS_$_BMSiriUnifiedSiriTurn
+ __OBJC_CLASS_RO_$_BMSiriUnifiedSiriTurn
+ __OBJC_METACLASS_RO_$_BMSiriUnifiedSiriTurn
- +[BMMediaAnalysisProcessingSession columns]
- +[BMMediaAnalysisProcessingSession eventWithData:dataVersion:]
- +[BMMediaAnalysisProcessingSession latestDataVersion]
- +[BMMediaAnalysisProcessingSession protoFields]
- +[BMMediaAnalysisProcessingSession validKeyPaths]
- +[_BMMediaAnalysisTextUnderstandingLibraryNode ProcessingSession]
- +[_BMMediaAnalysisTextUnderstandingLibraryNode configurationForProcessingSession]
- +[_BMMediaAnalysisTextUnderstandingLibraryNode storeConfigurationForProcessingSession]
- +[_BMMediaAnalysisTextUnderstandingLibraryNode syncPolicyForProcessingSession]
- -[BMGeneratedImageImageGeneration initWithPromptIdentifier:imageIdentifier:promptAfterRewrite:promptAfterAssembly:imageForPersonalization:featureModel:generatedImage:secondImageForPersonalization:thirdImageForPersonalization:]
- -[BMGeneratedImageImageInteraction initWithImageIdentifier:promptIdentifer:engaged:numViews:timeViewed:saved:shared:copied:inserted:duplicated:captionAdded:usedAsWallpaper:reportAConcern:deleted:]
- -[BMGeneratedImageUserInteraction initWithTimestamp:prompt:tokenLength:identifier:topic:usage:userInterfaceLanguage:userSetRegionFormat:personalization:result:feature:style:hair:facialHair:accessories:additionalDescription:sessionIdentifier:isLastPrompt:promptIdentifier:collectionIdentifier:aspectRatio:resolution:numPeople:promptAction:parentPromptIdentifier:directManipulation:featureModel:generationSource:pregeneration:]
- -[BMMediaAnalysisProcessingResults .cxx_destruct]
- -[BMMediaAnalysisProcessingResults initWithSubcategory:numberOfAssetsAnalyzed:numberOfAssetsPassGateWithResults:]
- -[BMMediaAnalysisProcessingResults subcategory]
- -[BMMediaAnalysisProcessingSession dataVersion]
- -[BMMediaAnalysisProcessingSession description]
- -[BMMediaAnalysisProcessingSession hasNumberOfAssetsAnalyzed]
- -[BMMediaAnalysisProcessingSession hasNumberOfAssetsDownloadThrottled]
- -[BMMediaAnalysisProcessingSession hasNumberOfAssetsGatedByHeuristic]
- -[BMMediaAnalysisProcessingSession hasNumberOfAssetsGated]
- -[BMMediaAnalysisProcessingSession hasNumberOfAssetsHardFailure]
- -[BMMediaAnalysisProcessingSession hasNumberOfAssetsNoResource]
- -[BMMediaAnalysisProcessingSession hasNumberOfAssetsPassGateWithResults]
- -[BMMediaAnalysisProcessingSession hasNumberOfAssetsPassGateWithoutResults]
- -[BMMediaAnalysisProcessingSession hasNumberOfAssetsSoftFailure]
- -[BMMediaAnalysisProcessingSession hasTimeAnalyzingFullInSeconds]
- -[BMMediaAnalysisProcessingSession hasTimeAnalyzingGatingInSeconds]
- -[BMMediaAnalysisProcessingSession hasTimeDownloadingInSeconds]
- -[BMMediaAnalysisProcessingSession initByReadFrom:]
- -[BMMediaAnalysisProcessingSession initWithJSONDictionary:error:]
- -[BMMediaAnalysisProcessingSession initWithNumberOfAssetsAnalyzed:numberOfAssetsGated:numberOfAssetsGatedByHeuristic:numberOfAssetsPassGateWithResults:numberOfAssetsPassGateWithoutResults:numberOfAssetsNoResource:numberOfAssetsDownloadThrottled:numberOfAssetsSoftFailure:numberOfAssetsHardFailure:timeDownloadingInSeconds:timeAnalyzingGatingInSeconds:timeAnalyzingFullInSeconds:]
- -[BMMediaAnalysisProcessingSession isEqual:]
- -[BMMediaAnalysisProcessingSession jsonDictionary]
- -[BMMediaAnalysisProcessingSession numberOfAssetsAnalyzed]
- -[BMMediaAnalysisProcessingSession numberOfAssetsDownloadThrottled]
- -[BMMediaAnalysisProcessingSession numberOfAssetsGatedByHeuristic]
- -[BMMediaAnalysisProcessingSession numberOfAssetsGated]
- -[BMMediaAnalysisProcessingSession numberOfAssetsHardFailure]
- -[BMMediaAnalysisProcessingSession numberOfAssetsNoResource]
- -[BMMediaAnalysisProcessingSession numberOfAssetsPassGateWithResults]
- -[BMMediaAnalysisProcessingSession numberOfAssetsPassGateWithoutResults]
- -[BMMediaAnalysisProcessingSession numberOfAssetsSoftFailure]
- -[BMMediaAnalysisProcessingSession serialize]
- -[BMMediaAnalysisProcessingSession setHasNumberOfAssetsAnalyzed:]
- -[BMMediaAnalysisProcessingSession setHasNumberOfAssetsDownloadThrottled:]
- -[BMMediaAnalysisProcessingSession setHasNumberOfAssetsGated:]
- -[BMMediaAnalysisProcessingSession setHasNumberOfAssetsGatedByHeuristic:]
- -[BMMediaAnalysisProcessingSession setHasNumberOfAssetsHardFailure:]
- -[BMMediaAnalysisProcessingSession setHasNumberOfAssetsNoResource:]
- -[BMMediaAnalysisProcessingSession setHasNumberOfAssetsPassGateWithResults:]
- -[BMMediaAnalysisProcessingSession setHasNumberOfAssetsPassGateWithoutResults:]
- -[BMMediaAnalysisProcessingSession setHasNumberOfAssetsSoftFailure:]
- -[BMMediaAnalysisProcessingSession setHasTimeAnalyzingFullInSeconds:]
- -[BMMediaAnalysisProcessingSession setHasTimeAnalyzingGatingInSeconds:]
- -[BMMediaAnalysisProcessingSession setHasTimeDownloadingInSeconds:]
- -[BMMediaAnalysisProcessingSession timeAnalyzingFullInSeconds]
- -[BMMediaAnalysisProcessingSession timeAnalyzingGatingInSeconds]
- -[BMMediaAnalysisProcessingSession timeDownloadingInSeconds]
- -[BMMediaAnalysisProcessingSession writeTo:]
- _BMMediaAnalysisProcessingResultsSubcategoryColumn
- _BMMediaAnalysisProcessingSessionNumberOfAssetsAnalyzedColumn
- _BMMediaAnalysisProcessingSessionNumberOfAssetsDownloadThrottledColumn
- _BMMediaAnalysisProcessingSessionNumberOfAssetsGatedByHeuristicColumn
- _BMMediaAnalysisProcessingSessionNumberOfAssetsGatedColumn
- _BMMediaAnalysisProcessingSessionNumberOfAssetsHardFailureColumn
- _BMMediaAnalysisProcessingSessionNumberOfAssetsNoResourceColumn
- _BMMediaAnalysisProcessingSessionNumberOfAssetsPassGateWithResultsColumn
- _BMMediaAnalysisProcessingSessionNumberOfAssetsPassGateWithoutResultsColumn
- _BMMediaAnalysisProcessingSessionNumberOfAssetsSoftFailureColumn
- _BMMediaAnalysisProcessingSessionTimeAnalyzingFullInSecondsColumn
- _BMMediaAnalysisProcessingSessionTimeAnalyzingGatingInSecondsColumn
- _BMMediaAnalysisProcessingSessionTimeDownloadingInSecondsColumn
- _BMMediaAnalysisTextUnderstandingProcessingSessionIdentifier
- _OBJC_CLASS_$_BMMediaAnalysisProcessingSession
- _OBJC_IVAR_$_BMMediaAnalysisProcessingResults._subcategory
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._dataVersion
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._hasNumberOfAssetsAnalyzed
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._hasNumberOfAssetsDownloadThrottled
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._hasNumberOfAssetsGated
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._hasNumberOfAssetsGatedByHeuristic
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._hasNumberOfAssetsHardFailure
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._hasNumberOfAssetsNoResource
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._hasNumberOfAssetsPassGateWithResults
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._hasNumberOfAssetsPassGateWithoutResults
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._hasNumberOfAssetsSoftFailure
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._hasTimeAnalyzingFullInSeconds
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._hasTimeAnalyzingGatingInSeconds
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._hasTimeDownloadingInSeconds
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._numberOfAssetsAnalyzed
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._numberOfAssetsDownloadThrottled
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._numberOfAssetsGated
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._numberOfAssetsGatedByHeuristic
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._numberOfAssetsHardFailure
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._numberOfAssetsNoResource
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._numberOfAssetsPassGateWithResults
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._numberOfAssetsPassGateWithoutResults
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._numberOfAssetsSoftFailure
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._timeAnalyzingFullInSeconds
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._timeAnalyzingGatingInSeconds
- _OBJC_IVAR_$_BMMediaAnalysisProcessingSession._timeDownloadingInSeconds
- _OBJC_METACLASS_$_BMMediaAnalysisProcessingSession
- __OBJC_$_CLASS_METHODS_BMMediaAnalysisProcessingSession
- __OBJC_$_CLASS_PROP_LIST_BMMediaAnalysisProcessingSession
- __OBJC_$_INSTANCE_METHODS_BMMediaAnalysisProcessingSession
- __OBJC_$_INSTANCE_VARIABLES_BMMediaAnalysisProcessingSession
- __OBJC_$_PROP_LIST_BMMediaAnalysisProcessingSession
- __OBJC_CLASS_PROTOCOLS_$_BMMediaAnalysisProcessingSession
- __OBJC_CLASS_RO_$_BMMediaAnalysisProcessingSession
- __OBJC_METACLASS_RO_$_BMMediaAnalysisProcessingSession
CStrings:
+ "$\x8c"
+ "BMGeneratedImageImageGeneration with promptIdentifier: %@, imageIdentifier: %@, promptAfterRewrite: %@, promptAfterAssembly: %@, imageForPersonalization: %@, featureModel: %@, generatedImage: %@, secondImageForPersonalization: %@, thirdImageForPersonalization: %@, assetIdentifier: %@"
+ "BMGeneratedImageImageInteraction with imageIdentifier: %@, promptIdentifer: %@, engaged: %@, numViews: %@, timeViewed: %@, saved: %@, shared: %@, copied: %@, inserted: %@, duplicated: %@, captionAdded: %@, usedAsWallpaper: %@, reportAConcern: %@, deleted: %@, assetIdentifier: %@"
+ "BMGeneratedImageUserInteraction with timestamp: %@, prompt: %@, tokenLength: %@, identifier: %@, topic: %@, usage: %@, userInterfaceLanguage: %@, userSetRegionFormat: %@, personalization: %@, result: %@, feature: %@, style: %@, hair: %@, facialHair: %@, accessories: %@, additionalDescription: %@, sessionIdentifier: %@, isLastPrompt: %@, promptIdentifier: %@, collectionIdentifier: %@, aspectRatio: %@, resolution: %@, numPeople: %@, promptAction: %@, parentPromptIdentifier: %@, directManipulation: %@, featureModel: %@, generationSource: %@, pregeneration: %@, assetIdentifier: %@"
+ "BMMediaAnalysisProcessingResults with numberOfAssetsAnalyzed: %@, numberOfAssetsFailedGatingHeuristic: %@, numberOfAssetsFailedGatingModel: %@, numberOfAssetsPassGateWithoutResults: %@, numberOfAssetsPassGateWithResults: %@, numberOfAssetsUnknown: %@, numberOfAssetsPassport: %@, numberOfAssetsDriverLicense: %@, numberOfAssetsBusinessCard: %@, numberOfAssetsGreenCard: %@, numberOfAssetsSocialSecurityNumber: %@, numberOfAssetsMedicalCard: %@, numberOfAssetsInsuranceCard: %@, numberOfAssetsMembershipCard: %@, numberOfAssetsTransitCard: %@, numberOfAssetsStateID: %@, numberOfAssetsStudentCard: %@, numberOfAssetsEmployeeCard: %@, numberOfAssetsNationalID: %@"
+ "BMSiriUnifiedSiriTurn with turnId: %@, invocationTime: %@, clockStartTime: %@, deviceType: %@, systemBuild: %@, programCode: %@, dataSharingOptInState: %@, siriInputLocale: %@, deviceAggregationId: %@, userAggregationId: %@, userAggregationIdRotationDate: %@, userAggregationIdExpirationDate: %@, invocationSource: %@, productId: %@, requestType: %@, productArea: %@, siriResponse: %@, dictationUsedLocale: %@, asrLocation: %@, nlLocation: %@, mhAudioVendorId: %@, mhAudioProductId: %@, thirdPartyGenAIAgent: %@, genAiRequestOutcome: %@, experimentInfos: %@, isLlmSiriEnabled: %@, isGenAIAttempted: %@, isTurnTaken: %@, isCarPlay: %@, isExplicitGenAiRequest: %@, userUtterance: %@, responseText: %@, assistantId: %@, executionCategory: %@, didUseWKASummarization: %@, didUseOnScreenAwareness: %@, isContextualFollowUp: %@, didResumeSiriApp: %@, orchestrationMode: %@"
+ "DB807AE6-4640-4DA1-864E-1E1825224923"
+ "Siri.UnifiedSiriTurn"
+ "UnifiedSiriTurn"
+ "assetIdentifier"
+ "assistantId"
+ "clockStartTime"
+ "dataSharingOptInState"
+ "dictationUsedLocale"
+ "didResumeSiriApp"
+ "didUseOnScreenAwareness"
+ "didUseWKASummarization"
+ "experimentInfos"
+ "genAiRequestOutcome"
+ "invocationTime"
+ "isCarPlay"
+ "isContextualFollowUp"
+ "isExplicitGenAiRequest"
+ "isGenAIAttempted"
+ "isLlmSiriEnabled"
+ "isTurnTaken"
+ "mhAudioProductId"
+ "mhAudioVendorId"
+ "numberOfAssetsBusinessCard"
+ "numberOfAssetsDriverLicense"
+ "numberOfAssetsEmployeeCard"
+ "numberOfAssetsFailedGatingHeuristic"
+ "numberOfAssetsFailedGatingModel"
+ "numberOfAssetsGreenCard"
+ "numberOfAssetsInsuranceCard"
+ "numberOfAssetsMedicalCard"
+ "numberOfAssetsMembershipCard"
+ "numberOfAssetsNationalID"
+ "numberOfAssetsPassport"
+ "numberOfAssetsSocialSecurityNumber"
+ "numberOfAssetsStateID"
+ "numberOfAssetsStudentCard"
+ "numberOfAssetsTransitCard"
+ "numberOfAssetsUnknown"
+ "responseText"
+ "siriResponse"
+ "thirdPartyGenAIAgent"
+ "userUtterance"
+ "\xbf\v"
- "$\x8b"
- "248D78D8-6358-4D36-AE4F-AF09B4853F2F"
- "BMGeneratedImageImageGeneration with promptIdentifier: %@, imageIdentifier: %@, promptAfterRewrite: %@, promptAfterAssembly: %@, imageForPersonalization: %@, featureModel: %@, generatedImage: %@, secondImageForPersonalization: %@, thirdImageForPersonalization: %@"
- "BMGeneratedImageImageInteraction with imageIdentifier: %@, promptIdentifer: %@, engaged: %@, numViews: %@, timeViewed: %@, saved: %@, shared: %@, copied: %@, inserted: %@, duplicated: %@, captionAdded: %@, usedAsWallpaper: %@, reportAConcern: %@, deleted: %@"
- "BMGeneratedImageUserInteraction with timestamp: %@, prompt: %@, tokenLength: %@, identifier: %@, topic: %@, usage: %@, userInterfaceLanguage: %@, userSetRegionFormat: %@, personalization: %@, result: %@, feature: %@, style: %@, hair: %@, facialHair: %@, accessories: %@, additionalDescription: %@, sessionIdentifier: %@, isLastPrompt: %@, promptIdentifier: %@, collectionIdentifier: %@, aspectRatio: %@, resolution: %@, numPeople: %@, promptAction: %@, parentPromptIdentifier: %@, directManipulation: %@, featureModel: %@, generationSource: %@, pregeneration: %@"
- "BMMediaAnalysisProcessingResults with subcategory: %@, numberOfAssetsAnalyzed: %@, numberOfAssetsPassGateWithResults: %@"
- "BMMediaAnalysisProcessingSession with numberOfAssetsAnalyzed: %@, numberOfAssetsGated: %@, numberOfAssetsGatedByHeuristic: %@, numberOfAssetsPassGateWithResults: %@, numberOfAssetsPassGateWithoutResults: %@, numberOfAssetsNoResource: %@, numberOfAssetsDownloadThrottled: %@, numberOfAssetsSoftFailure: %@, numberOfAssetsHardFailure: %@, timeDownloadingInSeconds: %@, timeAnalyzingGatingInSeconds: %@, timeAnalyzingFullInSeconds: %@"
- "MediaAnalysis.TextUnderstanding.ProcessingSession"
- "ProcessingSession"
- "numberOfAssetsDownloadThrottled"
- "numberOfAssetsGated"
- "numberOfAssetsGatedByHeuristic"
- "numberOfAssetsHardFailure"
- "numberOfAssetsNoResource"
- "numberOfAssetsSoftFailure"
- "subcategory"
- "timeAnalyzingFullInSeconds"
- "timeAnalyzingGatingInSeconds"
- "timeDownloadingInSeconds"
```
