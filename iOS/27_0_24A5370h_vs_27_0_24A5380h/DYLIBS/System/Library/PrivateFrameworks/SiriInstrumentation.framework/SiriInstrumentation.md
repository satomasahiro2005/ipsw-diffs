## SiriInstrumentation

> `/System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1baa8` | `0x28ff0` | **`+0xd548`** |
| `__DATA_DIRTY.__objc_data` | `0x24d28` | `0x17970` | **`-0xd3b8`** |
| `__TEXT.__text` | `0xd5604c` | `0xd5bff4` | **`+0x5fa8`** |
| `__AUTH_CONST.__objc_const` | `0x178d10` | `0x179730` | **`+0xa20`** |
| `__TEXT.__objc_methlist` | `0x1070fc` | `0x10789c` | **`+0x7a0`** |
| `__AUTH_CONST.__cfstring` | `0x7eaa0` | `0x7ee00` | **`+0x360`** |
| `__TEXT.__cstring` | `0x9393d` | `0x93c3b` | **`+0x2fe`** |
| `__DATA.__bss` | `0x1f180` | `0x1f400` | **`+0x280`** |
| `__DATA_CONST.__const` | `0x3d020` | `0x3d1c0` | **`+0x1a0`** |
| `__DATA_CONST.__objc_selrefs` | `0x41e28` | `0x41fa8` | **`+0x180`** |
| `__DATA_DIRTY.__data` | `0x3b8` | `0x238` | **`-0x180`** |
| `__AUTH.__data` | `—` | `0x160` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x334b8` | `0x33610` | **`+0x158`** |
| `__DATA_DIRTY.__bss` | `0x100` | `—` | **`-0x100`** |
| `__TEXT.__const` | `0x17570` | `0x17654` | **`+0xe4`** |
| `__DATA.__objc_ivar` | `0x12864` | `0x128ec` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0x24549` | `0x245a9` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x7db4` | `0x7e14` | **`+0x60`** |
| `__TEXT.__swift5_builtin` | `0x4948` | `0x4984` | **`+0x3c`** |
| `__DATA.__data` | `0x3408` | `0x3440` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x6828` | `0x6850` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x66f0` | `0x6718` | **`+0x28`** |
| `__DATA_CONST.__objc_superrefs` | `0x66a0` | `0x66c8` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x1e88` | `0x1e9a` | **`+0x12`** |
| `__TEXT.__swift5_proto` | `0x1360` | `0x136c` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0xefc` | `0xf08` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x930` | `0x928` | **`-0x8`** |

### Other Changes

```diff

-3600.77.1.0.0
+3600.79.1.0.0

-  Functions: 92694
-  Symbols:   130426
-  CStrings:  17322
+  Functions: 92861
+  Symbols:   130655
+  CStrings:  17350
Symbols:
+ -[GMSSchemaGMSExtendedInferenceMetrics deleteInputStreamStepIdentifier]
+ -[GMSSchemaGMSExtendedInferenceMetrics hasInputStreamStepIdentifier]
+ -[GMSSchemaGMSExtendedInferenceMetrics inputStreamStepIdentifier]
+ -[GMSSchemaGMSExtendedInferenceMetrics setHasInputStreamStepIdentifier:]
+ -[GMSSchemaGMSExtendedInferenceMetrics setInputStreamStepIdentifier:]
+ -[ODDSiriSchemaODDAppleIntelligenceProperties addProviders:]
+ -[ODDSiriSchemaODDAppleIntelligenceProperties clearProviders]
+ -[ODDSiriSchemaODDAppleIntelligenceProperties deleteProviders]
+ -[ODDSiriSchemaODDAppleIntelligenceProperties providersAtIndex:]
+ -[ODDSiriSchemaODDAppleIntelligenceProperties providersCount]
+ -[ODDSiriSchemaODDAppleIntelligenceProperties providers]
+ -[ODDSiriSchemaODDAppleIntelligenceProperties setProviders:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts .cxx_destruct]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts deleteTurnCounts]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts dictionaryRepresentation]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts hasTurnCounts]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts hash]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts initWithDictionary:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts initWithJSON:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts isEqual:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts jsonData]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts readFrom:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts setHasTurnCounts:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts setTurnCounts:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts turnCounts]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts writeTo:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest .cxx_destruct]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest counts]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest deleteCounts]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest deleteDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest dictionaryRepresentation]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest dimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest hasCounts]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest hasDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest hash]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest initWithDictionary:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest initWithJSON:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest isEqual:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest jsonData]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest readFrom:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest setCounts:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest setDimensions:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest setHasCounts:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest setHasDimensions:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest writeTo:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported .cxx_destruct]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported addDigests:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported clearDigests]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported deleteDigests]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported deleteFixedDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported dictionaryRepresentation]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported digestsAtIndex:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported digestsCount]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported digests]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported fixedDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported hasFixedDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported hash]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported initWithDictionary:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported initWithJSON:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported isEqual:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported jsonData]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported readFrom:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported setDigests:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported setFixedDimensions:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported setHasFixedDimensions:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported writeTo:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions .cxx_destruct]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions addProviderName:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions assistantDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions clearProviderName]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions deleteAssistantDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions deleteHasSiriExtensionsEnabled]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions deleteProviderName]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions deleteRequestType]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions dictionaryRepresentation]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hasAssistantDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hasHasSiriExtensionsEnabled]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hasRequestType]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hasSiriExtensionsEnabled]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hash]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions initWithDictionary:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions initWithJSON:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions isEqual:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions jsonData]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions providerNameAtIndex:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions providerNameCount]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions providerNames]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions readFrom:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions requestType]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setAssistantDimensions:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setHasAssistantDimensions:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setHasHasSiriExtensionsEnabled:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setHasRequestType:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setHasSiriExtensionsEnabled:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setProviderNames:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setRequestType:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions writeTo:]
+ -[ODDSiriSchemaODDSiriClientEvent assistantSiriExtensionsDigestsReported]
+ -[ODDSiriSchemaODDSiriClientEvent deleteAssistantSiriExtensionsDigestsReported]
+ -[ODDSiriSchemaODDSiriClientEvent hasAssistantSiriExtensionsDigestsReported]
+ -[ODDSiriSchemaODDSiriClientEvent setAssistantSiriExtensionsDigestsReported:]
+ -[ODDSiriSchemaODDSiriClientEvent setHasAssistantSiriExtensionsDigestsReported:]
+ -[ODDSiriSchemaODDSiriExtensionProvider .cxx_destruct]
+ -[ODDSiriSchemaODDSiriExtensionProvider deleteIsProviderEnabled]
+ -[ODDSiriSchemaODDSiriExtensionProvider deleteIsProviderInstalled]
+ -[ODDSiriSchemaODDSiriExtensionProvider deleteProviderName]
+ -[ODDSiriSchemaODDSiriExtensionProvider dictionaryRepresentation]
+ -[ODDSiriSchemaODDSiriExtensionProvider hasIsProviderEnabled]
+ -[ODDSiriSchemaODDSiriExtensionProvider hasIsProviderInstalled]
+ -[ODDSiriSchemaODDSiriExtensionProvider hasProviderName]
+ -[ODDSiriSchemaODDSiriExtensionProvider hash]
+ -[ODDSiriSchemaODDSiriExtensionProvider initWithDictionary:]
+ -[ODDSiriSchemaODDSiriExtensionProvider initWithJSON:]
+ -[ODDSiriSchemaODDSiriExtensionProvider isEqual:]
+ -[ODDSiriSchemaODDSiriExtensionProvider isProviderEnabled]
+ -[ODDSiriSchemaODDSiriExtensionProvider isProviderInstalled]
+ -[ODDSiriSchemaODDSiriExtensionProvider jsonData]
+ -[ODDSiriSchemaODDSiriExtensionProvider providerName]
+ -[ODDSiriSchemaODDSiriExtensionProvider readFrom:]
+ -[ODDSiriSchemaODDSiriExtensionProvider setHasIsProviderEnabled:]
+ -[ODDSiriSchemaODDSiriExtensionProvider setHasIsProviderInstalled:]
+ -[ODDSiriSchemaODDSiriExtensionProvider setHasProviderName:]
+ -[ODDSiriSchemaODDSiriExtensionProvider setIsProviderEnabled:]
+ -[ODDSiriSchemaODDSiriExtensionProvider setIsProviderInstalled:]
+ -[ODDSiriSchemaODDSiriExtensionProvider setProviderName:]
+ -[ODDSiriSchemaODDSiriExtensionProvider writeTo:]
+ -[ODDSiriSchemaODDVoiceProperties deleteExpressivity]
+ -[ODDSiriSchemaODDVoiceProperties deletePace]
+ -[ODDSiriSchemaODDVoiceProperties expressivity]
+ -[ODDSiriSchemaODDVoiceProperties hasExpressivity]
+ -[ODDSiriSchemaODDVoiceProperties hasPace]
+ -[ODDSiriSchemaODDVoiceProperties pace]
+ -[ODDSiriSchemaODDVoiceProperties setExpressivity:]
+ -[ODDSiriSchemaODDVoiceProperties setHasExpressivity:]
+ -[ODDSiriSchemaODDVoiceProperties setHasPace:]
+ -[ODDSiriSchemaODDVoiceProperties setPace:]
+ -[SAMSchemaSAMServerEventMetadata deleteSamDomainQueryId]
+ -[SAMSchemaSAMServerEventMetadata hasSamDomainQueryId]
+ -[SAMSchemaSAMServerEventMetadata samDomainQueryId]
+ -[SAMSchemaSAMServerEventMetadata setHasSamDomainQueryId:]
+ -[SAMSchemaSAMServerEventMetadata setSamDomainQueryId:]
+ -[SASchemaSARequestStarted agentActionId]
+ -[SASchemaSARequestStarted deleteAgentActionId]
+ -[SASchemaSARequestStarted hasAgentActionId]
+ -[SASchemaSARequestStarted setAgentActionId:]
+ -[SASchemaSARequestStarted setHasAgentActionId:]
+ -[SIRIXAGENTSchemaSIRIXAGENTInvocationStarted .cxx_destruct]
+ -[SIRIXAGENTSchemaSIRIXAGENTInvocationStarted agentActionId]
+ -[SIRIXAGENTSchemaSIRIXAGENTInvocationStarted deleteAgentActionId]
+ -[SIRIXAGENTSchemaSIRIXAGENTInvocationStarted hasAgentActionId]
+ -[SIRIXAGENTSchemaSIRIXAGENTInvocationStarted setAgentActionId:]
+ -[SIRIXAGENTSchemaSIRIXAGENTInvocationStarted setHasAgentActionId:]
+ -[TASchemaTAConfirmationRequestStarted .cxx_destruct]
+ -[TASchemaTAConfirmationRequestStarted agentActionId]
+ -[TASchemaTAConfirmationRequestStarted deleteAgentActionId]
+ -[TASchemaTAConfirmationRequestStarted hasAgentActionId]
+ -[TASchemaTAConfirmationRequestStarted setAgentActionId:]
+ -[TASchemaTAConfirmationRequestStarted setHasAgentActionId:]
+ OBJC_IVAR_$_GMSSchemaGMSExtendedInferenceMetrics._inputStreamStepIdentifier
+ OBJC_IVAR_$_ODDSiriSchemaODDAppleIntelligenceProperties._providers
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsCounts._turnCounts
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest._counts
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest._dimensions
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported._digests
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported._fixedDimensions
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._assistantDimensions
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._has
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._hasSiriExtensionsEnabled
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._providerNames
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._requestType
+ OBJC_IVAR_$_ODDSiriSchemaODDSiriClientEvent._assistantSiriExtensionsDigestsReported
+ OBJC_IVAR_$_ODDSiriSchemaODDSiriExtensionProvider._has
+ OBJC_IVAR_$_ODDSiriSchemaODDSiriExtensionProvider._isProviderEnabled
+ OBJC_IVAR_$_ODDSiriSchemaODDSiriExtensionProvider._isProviderInstalled
+ OBJC_IVAR_$_ODDSiriSchemaODDSiriExtensionProvider._providerName
+ OBJC_IVAR_$_ODDSiriSchemaODDVoiceProperties._expressivity
+ OBJC_IVAR_$_ODDSiriSchemaODDVoiceProperties._pace
+ OBJC_IVAR_$_SAMSchemaSAMServerEventMetadata._samDomainQueryId
+ OBJC_IVAR_$_SASchemaSARequestStarted._agentActionId
+ OBJC_IVAR_$_SIRIXAGENTSchemaSIRIXAGENTInvocationStarted._agentActionId
+ OBJC_IVAR_$_TASchemaTAConfirmationRequestStarted._agentActionId
+ _OBJC_CLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ _OBJC_CLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ _OBJC_CLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ _OBJC_CLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ _OBJC_CLASS_$_ODDSiriSchemaODDSiriExtensionProvider
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsCounts._hasTurnCounts
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest._hasCounts
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest._hasDimensions
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported._hasFixedDimensions
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._hasAssistantDimensions
+ _OBJC_IVAR_$_ODDSiriSchemaODDSiriClientEvent._hasAssistantSiriExtensionsDigestsReported
+ _OBJC_IVAR_$_ODDSiriSchemaODDSiriExtensionProvider._hasProviderName
+ _OBJC_IVAR_$_SAMSchemaSAMServerEventMetadata._hasSamDomainQueryId
+ _OBJC_IVAR_$_SASchemaSARequestStarted._hasAgentActionId
+ _OBJC_IVAR_$_SIRIXAGENTSchemaSIRIXAGENTInvocationStarted._hasAgentActionId
+ _OBJC_IVAR_$_TASchemaTAConfirmationRequestStarted._hasAgentActionId
+ _OBJC_METACLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ _OBJC_METACLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ _OBJC_METACLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ _OBJC_METACLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ _OBJC_METACLASS_$_ODDSiriSchemaODDSiriExtensionProvider
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDSiriExtensionProvider
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDSiriExtensionProvider
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDSiriExtensionProvider
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDSiriExtensionProvider
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDSiriExtensionProvider
+ _symbolic _____ So013ODDSiriSchemaA20ExtensionRequestTypeV
+ _symbolic _____ So17SISchemaVoicePaceV
+ _symbolic _____ So25SISchemaVoiceExpressivityV
- _swift_willThrowTypedImpl
CStrings:
+ "!!"
+ "ODDINTELLIGENCEFEATUREREPORTINGUSECASE_SIRIAI_MODELS"
+ "ODDSIRIEXTENSIONREQUESTTYPE_THIRD_PARTY_PROVIDER_REQUEST"
+ "ODDSIRIEXTENSIONREQUESTTYPE_UNKNOWN"
+ "ODDSIRIEXTENSIONREQUESTTYPE_VISUAL_INTELLIGENCE"
+ "VOICEEXPRESSIVITY_PRESET1"
+ "VOICEEXPRESSIVITY_PRESET2"
+ "VOICEEXPRESSIVITY_PRESET3"
+ "VOICEEXPRESSIVITY_PRESET4"
+ "VOICEEXPRESSIVITY_PRESET5"
+ "VOICEEXPRESSIVITY_PRESET_UNSPECIFIED"
+ "VOICEEXPRESSIVITY_UNKNOWN"
+ "VOICEPACE_PRESET1"
+ "VOICEPACE_PRESET2"
+ "VOICEPACE_PRESET3"
+ "VOICEPACE_PRESET4"
+ "VOICEPACE_PRESET5"
+ "VOICEPACE_PRESET_UNSPECIFIED"
+ "VOICEPACE_UNKNOWN"
+ "assistantSiriExtensionsDigestsReported"
+ "com.apple.aiml.siri.odd.ODDSiriClientEvent.ODDAssistantSiriExtensionsDigestsReported"
+ "expressivity"
+ "hasSiriExtensionsEnabled"
+ "inputStreamStepIdentifier"
+ "isProviderEnabled"
+ "isProviderInstalled"
+ "pace"
+ "providers"
```
