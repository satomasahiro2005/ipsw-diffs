## BiomeLibrary

> `/System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x74170c` | `0x748b3c` | **`+0x7430`** |
| `__AUTH_CONST.__objc_const` | `0xa14e0` | `0xa1d40` | **`+0x860`** |
| `__AUTH.__objc_data` | `0xa8e0` | `0xb080` | **`+0x7a0`** |
| `__DATA_DIRTY.__objc_data` | `0xbf80` | `0xb990` | **`-0x5f0`** |
| `__TEXT.__cstring` | `0x4dc45` | `0x4e0ec` | **`+0x4a7`** |
| `__TEXT.__objc_methlist` | `0x4f9e4` | `0x4fd44` | **`+0x360`** |
| `__AUTH_CONST.__cfstring` | `0x4aaa0` | `0x4acc0` | **`+0x220`** |
| `__DATA_CONST.__const` | `0x1e8c8` | `0x1e9b8` | **`+0xf0`** |
| `__DATA_CONST.__objc_arraydata` | `0xafc8` | `0xb0a8` | **`+0xe0`** |
| `__DATA_CONST.__objc_selrefs` | `0x12688` | `0x12748` | **`+0xc0`** |
| `__TEXT.__const` | `0x4718` | `0x47b8` | **`+0xa0`** |
| `__DATA.__objc_ivar` | `0x8060` | `0x80f4` | **`+0x94`** |
| `__TEXT.__unwind_info` | `0xf6f0` | `0xf768` | **`+0x78`** |
| `__TEXT.__constg_swiftt` | `0x560` | `0x5b8` | **`+0x58`** |
| `__AUTH.__data` | `0xc8` | `0x118` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x1f0` | `0x210` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x6648` | `0x6660` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x22e0` | `0x22f8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x172` | `0x17e` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x1bf0` | `0x1bf8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1b20` | `0x1b28` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x7c` | `0x84` | **`+0x8`** |

### Other Changes

```diff

-420.0.0.0.0
+426.0.0.0.0

-  Functions: 28467
-  Symbols:   52579
-  CStrings:  9686
+  Functions: 28554
+  Symbols:   52727
+  CStrings:  9707
Symbols:
+ +[BMSiriODDAssistantLLMSiriDigests columns]
+ +[BMSiriODDAssistantLLMSiriDigests eventWithData:dataVersion:]
+ +[BMSiriODDAssistantLLMSiriDigests latestDataVersion]
+ +[BMSiriODDAssistantLLMSiriDigests protoFields]
+ +[BMSiriODDAssistantLLMSiriDigests validKeyPaths]
+ +[_BMSiriODDILibraryNode ODDAssistantLLMSiriDigests]
+ +[_BMSiriODDILibraryNode configurationForODDAssistantLLMSiriDigests]
+ +[_BMSiriODDILibraryNode storeConfigurationForODDAssistantLLMSiriDigests]
+ +[_BMSiriODDILibraryNode syncPolicyForODDAssistantLLMSiriDigests]
+ -[BMSiriODDAssistantLLMSiriDigests .cxx_destruct]
+ -[BMSiriODDAssistantLLMSiriDigests asrLocation]
+ -[BMSiriODDAssistantLLMSiriDigests audioInterfaceProductId]
+ -[BMSiriODDAssistantLLMSiriDigests audioInterfaceVendorId]
+ -[BMSiriODDAssistantLLMSiriDigests contextualFollowUpCount]
+ -[BMSiriODDAssistantLLMSiriDigests dataSharingOptInStatus]
+ -[BMSiriODDAssistantLLMSiriDigests dataVersion]
+ -[BMSiriODDAssistantLLMSiriDigests description]
+ -[BMSiriODDAssistantLLMSiriDigests deviceAggregationId]
+ -[BMSiriODDAssistantLLMSiriDigests deviceType]
+ -[BMSiriODDAssistantLLMSiriDigests digestDate]
+ -[BMSiriODDAssistantLLMSiriDigests executionCategory]
+ -[BMSiriODDAssistantLLMSiriDigests hasContextualFollowUpCount]
+ -[BMSiriODDAssistantLLMSiriDigests hasOnScreenAwarenessCount]
+ -[BMSiriODDAssistantLLMSiriDigests hasSiriAppResumeCount]
+ -[BMSiriODDAssistantLLMSiriDigests hasTotalTurnCount]
+ -[BMSiriODDAssistantLLMSiriDigests hasValidTurnCount]
+ -[BMSiriODDAssistantLLMSiriDigests hasWkaSummarizationCount]
+ -[BMSiriODDAssistantLLMSiriDigests initByReadFrom:]
+ -[BMSiriODDAssistantLLMSiriDigests initWithJSONDictionary:error:]
+ -[BMSiriODDAssistantLLMSiriDigests initWithOddId:deviceAggregationId:userAggregationId:digestDate:userAggregationIdRotationDate:userAggregationIdExpirationDate:deviceType:programCode:systemBuild:dataSharingOptInStatus:viewInterface:audioInterfaceVendorId:audioInterfaceProductId:asrLocation:nlLocation:siriInputLocaleLanguageCode:siriInputLocaleCountryCode:subDomain:invocationSource:executionCategory:orchestrationMode:totalTurnCount:validTurnCount:wkaSummarizationCount:onScreenAwarenessCount:contextualFollowUpCount:siriAppResumeCount:]
+ -[BMSiriODDAssistantLLMSiriDigests invocationSource]
+ -[BMSiriODDAssistantLLMSiriDigests isEqual:]
+ -[BMSiriODDAssistantLLMSiriDigests jsonDictionary]
+ -[BMSiriODDAssistantLLMSiriDigests nlLocation]
+ -[BMSiriODDAssistantLLMSiriDigests oddId]
+ -[BMSiriODDAssistantLLMSiriDigests onScreenAwarenessCount]
+ -[BMSiriODDAssistantLLMSiriDigests orchestrationMode]
+ -[BMSiriODDAssistantLLMSiriDigests programCode]
+ -[BMSiriODDAssistantLLMSiriDigests serialize]
+ -[BMSiriODDAssistantLLMSiriDigests setHasContextualFollowUpCount:]
+ -[BMSiriODDAssistantLLMSiriDigests setHasOnScreenAwarenessCount:]
+ -[BMSiriODDAssistantLLMSiriDigests setHasSiriAppResumeCount:]
+ -[BMSiriODDAssistantLLMSiriDigests setHasTotalTurnCount:]
+ -[BMSiriODDAssistantLLMSiriDigests setHasValidTurnCount:]
+ -[BMSiriODDAssistantLLMSiriDigests setHasWkaSummarizationCount:]
+ -[BMSiriODDAssistantLLMSiriDigests siriAppResumeCount]
+ -[BMSiriODDAssistantLLMSiriDigests siriInputLocaleCountryCode]
+ -[BMSiriODDAssistantLLMSiriDigests siriInputLocaleLanguageCode]
+ -[BMSiriODDAssistantLLMSiriDigests subDomain]
+ -[BMSiriODDAssistantLLMSiriDigests systemBuild]
+ -[BMSiriODDAssistantLLMSiriDigests totalTurnCount]
+ -[BMSiriODDAssistantLLMSiriDigests userAggregationIdExpirationDate]
+ -[BMSiriODDAssistantLLMSiriDigests userAggregationIdRotationDate]
+ -[BMSiriODDAssistantLLMSiriDigests userAggregationId]
+ -[BMSiriODDAssistantLLMSiriDigests validTurnCount]
+ -[BMSiriODDAssistantLLMSiriDigests viewInterface]
+ -[BMSiriODDAssistantLLMSiriDigests wkaSummarizationCount]
+ -[BMSiriODDAssistantLLMSiriDigests writeTo:]
+ _BMSiriODDAssistantLLMSiriDigestsAsrLocationColumn
+ _BMSiriODDAssistantLLMSiriDigestsAudioInterfaceProductIdColumn
+ _BMSiriODDAssistantLLMSiriDigestsAudioInterfaceVendorIdColumn
+ _BMSiriODDAssistantLLMSiriDigestsContextualFollowUpCountColumn
+ _BMSiriODDAssistantLLMSiriDigestsDataSharingOptInStatusColumn
+ _BMSiriODDAssistantLLMSiriDigestsDeviceAggregationIdColumn
+ _BMSiriODDAssistantLLMSiriDigestsDeviceTypeColumn
+ _BMSiriODDAssistantLLMSiriDigestsDigestDateColumn
+ _BMSiriODDAssistantLLMSiriDigestsExecutionCategoryColumn
+ _BMSiriODDAssistantLLMSiriDigestsInvocationSourceColumn
+ _BMSiriODDAssistantLLMSiriDigestsNlLocationColumn
+ _BMSiriODDAssistantLLMSiriDigestsOddIdColumn
+ _BMSiriODDAssistantLLMSiriDigestsOnScreenAwarenessCountColumn
+ _BMSiriODDAssistantLLMSiriDigestsOrchestrationModeColumn
+ _BMSiriODDAssistantLLMSiriDigestsProgramCodeColumn
+ _BMSiriODDAssistantLLMSiriDigestsSiriAppResumeCountColumn
+ _BMSiriODDAssistantLLMSiriDigestsSiriInputLocaleCountryCodeColumn
+ _BMSiriODDAssistantLLMSiriDigestsSiriInputLocaleLanguageCodeColumn
+ _BMSiriODDAssistantLLMSiriDigestsSubDomainColumn
+ _BMSiriODDAssistantLLMSiriDigestsSystemBuildColumn
+ _BMSiriODDAssistantLLMSiriDigestsTotalTurnCountColumn
+ _BMSiriODDAssistantLLMSiriDigestsUserAggregationIdColumn
+ _BMSiriODDAssistantLLMSiriDigestsUserAggregationIdExpirationDateColumn
+ _BMSiriODDAssistantLLMSiriDigestsUserAggregationIdRotationDateColumn
+ _BMSiriODDAssistantLLMSiriDigestsValidTurnCountColumn
+ _BMSiriODDAssistantLLMSiriDigestsViewInterfaceColumn
+ _BMSiriODDAssistantLLMSiriDigestsWkaSummarizationCountColumn
+ _BMSiriODDIODDAssistantLLMSiriDigestsIdentifier
+ _OBJC_CLASS_$_BMSiriODDAssistantLLMSiriDigests
+ _OBJC_CLASS_$__TtC12BiomeLibrary37_BMIPBridgePrivateMLClientLibraryNode
+ _OBJC_CLASS_$__TtC12BiomeLibrary40_BMIPBridgeUnilogSafariSearchLibraryNode
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._asrLocation
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._audioInterfaceProductId
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._audioInterfaceVendorId
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._contextualFollowUpCount
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._dataSharingOptInStatus
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._dataVersion
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._deviceAggregationId
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._deviceType
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._executionCategory
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._hasContextualFollowUpCount
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._hasOnScreenAwarenessCount
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._hasRaw_digestDate
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._hasRaw_userAggregationIdExpirationDate
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._hasRaw_userAggregationIdRotationDate
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._hasSiriAppResumeCount
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._hasTotalTurnCount
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._hasValidTurnCount
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._hasWkaSummarizationCount
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._invocationSource
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._nlLocation
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._oddId
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._onScreenAwarenessCount
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._orchestrationMode
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._programCode
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._raw_digestDate
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._raw_userAggregationIdExpirationDate
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._raw_userAggregationIdRotationDate
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._siriAppResumeCount
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._siriInputLocaleCountryCode
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._siriInputLocaleLanguageCode
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._subDomain
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._systemBuild
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._totalTurnCount
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._userAggregationId
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._validTurnCount
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._viewInterface
+ _OBJC_IVAR_$_BMSiriODDAssistantLLMSiriDigests._wkaSummarizationCount
+ _OBJC_METACLASS_$_BMSiriODDAssistantLLMSiriDigests
+ _OBJC_METACLASS_$__TtC12BiomeLibrary37_BMIPBridgePrivateMLClientLibraryNode
+ _OBJC_METACLASS_$__TtC12BiomeLibrary40_BMIPBridgeUnilogSafariSearchLibraryNode
+ _OUTLINED_FUNCTION_44
+ _OUTLINED_FUNCTION_45
+ _OUTLINED_FUNCTION_46
+ __CLASS_METHODS__TtC12BiomeLibrary37_BMIPBridgePrivateMLClientLibraryNode
+ __CLASS_METHODS__TtC12BiomeLibrary40_BMIPBridgeUnilogSafariSearchLibraryNode
+ __DATA__TtC12BiomeLibrary37_BMIPBridgePrivateMLClientLibraryNode
+ __DATA__TtC12BiomeLibrary40_BMIPBridgeUnilogSafariSearchLibraryNode
+ __METACLASS_DATA__TtC12BiomeLibrary37_BMIPBridgePrivateMLClientLibraryNode
+ __METACLASS_DATA__TtC12BiomeLibrary40_BMIPBridgeUnilogSafariSearchLibraryNode
+ __OBJC_$_CLASS_METHODS_BMSiriODDAssistantLLMSiriDigests
+ __OBJC_$_CLASS_PROP_LIST_BMSiriODDAssistantLLMSiriDigests
+ __OBJC_$_INSTANCE_METHODS_BMSiriODDAssistantLLMSiriDigests
+ __OBJC_$_INSTANCE_VARIABLES_BMSiriODDAssistantLLMSiriDigests
+ __OBJC_$_PROP_LIST_BMSiriODDAssistantLLMSiriDigests
+ __OBJC_CLASS_PROTOCOLS_$_BMSiriODDAssistantLLMSiriDigests
+ __OBJC_CLASS_RO_$_BMSiriODDAssistantLLMSiriDigests
+ __OBJC_METACLASS_RO_$_BMSiriODDAssistantLLMSiriDigests
+ _symbolic _____ 12BiomeLibrary026_BMIPBridgePrivateMLClientB4NodeC
+ _symbolic _____ 12BiomeLibrary029_BMIPBridgeUnilogSafariSearchB4NodeC
CStrings:
+ "0D1711B6-123F-473E-ABF7-AEF17A03E024"
+ "BMSiriODDAssistantLLMSiriDigests with oddId: %@, deviceAggregationId: %@, userAggregationId: %@, digestDate: %@, userAggregationIdRotationDate: %@, userAggregationIdExpirationDate: %@, deviceType: %@, programCode: %@, systemBuild: %@, dataSharingOptInStatus: %@, viewInterface: %@, audioInterfaceVendorId: %@, audioInterfaceProductId: %@, asrLocation: %@, nlLocation: %@, siriInputLocaleLanguageCode: %@, siriInputLocaleCountryCode: %@, subDomain: %@, invocationSource: %@, executionCategory: %@, orchestrationMode: %@, totalTurnCount: %@, validTurnCount: %@, wkaSummarizationCount: %@, onScreenAwarenessCount: %@, contextualFollowUpCount: %@, siriAppResumeCount: %@"
+ "ErrorAccountLocked"
+ "ErrorBotDetectionOrCaptcha"
+ "ErrorInvalidCredentials"
+ "ErrorUnableToFindSignInForm"
+ "LongTermAggregationId"
+ "ODDAssistantLLMSiriDigests"
+ "PrivateMLClient."
+ "RecitationMetrics"
+ "Siri.ODDI.ODDAssistantLLMSiriDigests"
+ "Unilog.SafariSearch."
+ "contextualFollowUpCount"
+ "digestDate"
+ "executionCategory"
+ "onScreenAwarenessCount"
+ "orchestrationMode"
+ "siriAppResumeCount"
+ "siriInputLocaleCountryCode"
+ "siriInputLocaleLanguageCode"
+ "userAggregationIdExpirationDate"
+ "userAggregationIdRotationDate"
+ "wkaSummarizationCount"
- "ErrorBotDetectionFailure"
- "ErrorUnableToSignInWithCredentials"
```
