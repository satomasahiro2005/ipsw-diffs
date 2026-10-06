## SiriAppIntents

> `/System/Library/PrivateFrameworks/SiriAppIntents.framework/SiriAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12ec1a4` | `0x13436c4` | **`+0x57520`** |
| `__DATA.__bss` | `0x237990` | `0x244810` | **`+0xce80`** |
| `__TEXT.__const` | `0x19f040` | `0x1a6f20` | **`+0x7ee0`** |
| `__TEXT.__eh_frame` | `0xb7840` | `0xba5a0` | **`+0x2d60`** |
| `__TEXT.__unwind_info` | `0x7fec0` | `0x81e60` | **`+0x1fa0`** |
| `__AUTH.__data` | `0x16da0` | `0x18ae0` | **`+0x1d40`** |
| `__DATA.__data` | `0x42aa8` | `0x44748` | **`+0x1ca0`** |
| `__AUTH_CONST.__const` | `0x38ac0` | `0x3a440` | **`+0x1980`** |
| `__TEXT.__swift5_fieldmd` | `0x4c008` | `0x4d7f4` | **`+0x17ec`** |
| `__TEXT.__cstring` | `0x26c37` | `0x27d57` | **`+0x1120`** |
| `__TEXT.__constg_swiftt` | `0x3d2f0` | `0x3e3f8` | **`+0x1108`** |
| `__TEXT.__swift5_reflstr` | `0x435ec` | `0x4451c` | **`+0xf30`** |
| `__TEXT.__swift5_typeref` | `0x2a6bc` | `0x2b5e4` | **`+0xf28`** |
| `__TEXT.__swift5_proto` | `0x12588` | `0x12bfc` | **`+0x674`** |
| `__AUTH_CONST.__objc_const` | `0x26790` | `0x26de8` | **`+0x658`** |
| `__DATA_DIRTY.__data` | `0x80490` | `0x80940` | **`+0x4b0`** |
| `__DATA_CONST.__const` | `0x1ad60` | `0x1b1a0` | **`+0x440`** |
| `__TEXT.__swift5_assocty` | `0x7100` | `0x7418` | **`+0x318`** |
| `__TEXT.__swift5_types` | `0x3960` | `0x3ab0` | **`+0x150`** |
| `__AUTH.__objc_data` | `0x140` | `0x230` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0x2ecd` | `0x2f5d` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0x14f8` | `0x1538` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x374` | `0x39c` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x258` | `0x26c` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x218` | `0x22c` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x768` | `0x778` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x1c0` | `0x1d0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x340` | `0x338` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x140` | `0x148` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x30` | `0x34` | **`+0x4`** |

### Other Changes

```diff

-3600.82.20.0.0
+3600.82.29.0.0

-  Functions: 205150
-  Symbols:   240
-  CStrings:  4345
+  Functions: 208784
+  Symbols:   245
+  CStrings:  4486
Symbols:
+ _gethostname
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_retain_x9
CStrings:
+ "  First Token Preprocessing: "
+ "  Thinking Tokens: "
+ ".CharacterTypedWith"
+ ".EntityPropertyStorage"
+ ".IntentSideEffectBehavior"
+ ".IntentStateChange"
+ ".ModelRepresentationMetadata"
+ ".ProtocolPropertyMap"
+ ".RepresentationComponent"
+ ".SpotlightAttributes"
+ ".StateChangeWithBehavior"
+ ".SyncedIdentifier"
+ "AccessLevelHigh"
+ "AccessLevelLow"
+ "AccessLevelUnknown"
+ "Active remote session not found"
+ "Agent Thought Signature"
+ "Agent error (agent: "
+ "AssistantDismissalPolicyDismiss"
+ "AssistantDismissalPolicyRetain"
+ "AssistantDismissalPolicyUnknown"
+ "Audio remote error"
+ "Audio stream consumer error"
+ "Audio stream provider error"
+ "Companion transport error"
+ "ConfirmationConditionsForceSideEffectsConfirmation"
+ "DateExpressibleAsYearlessDate"
+ "DateExpressibleAsYearlessOrFullDate"
+ "DiagnosticOTelExporter: Exported session summary to %s"
+ "Event has no recognized payload key"
+ "Failed to execute"
+ "IntelligenceFlow.FeatureStore.SecurityValidationEventPayload"
+ "Internal error: XPC client reverse-channel object has an unexpected type"
+ "KIND_CHOICE"
+ "KIND_CONFIRMATION"
+ "KIND_UNKNOWN"
+ "KindCustom"
+ "KindDefault"
+ "Link transport unavailable"
+ "ModelRepresentationComponentKindText"
+ "ModelRepresentationComponentKindUnspecified"
+ "ModelRepresentationComponentKindVisual"
+ "ModelRepresentationLevelFull"
+ "ModelRepresentationLevelSummary"
+ "ModelRepresentationLevelUnspecified"
+ "No active companion device IDs identifier set"
+ "No companion IDs identifier found"
+ "No model-facing description available"
+ "OmniSearch.Instrumentation.SessionQueryLinkEvent"
+ "OmniSearch: SessionQueryLink"
+ "ParameterModeEmoji"
+ "ParameterModeStandard"
+ "ParameterModeUnspecified"
+ "Planner internal component error"
+ "Remote session cleaned up after timeout"
+ "Result: Continuation"
+ "Send message failed"
+ "Session coordinator error"
+ "SupportedFeatureImagePlayground"
+ "SupportedFeatureShortcuts"
+ "SupportedFeatureSystemAssistant"
+ "SupportedFeatureUnspecified"
+ "SupportedFeatureVisualIntelligence"
+ "SupportedFeatureWritingTools"
+ "ToolKit.EntityInstanceIdentifier"
+ "ToolKit.ModelRepresentation"
+ "Transcript.AgentThoughtSignature"
+ "Unable to create remote session"
+ "Unknown session error"
+ "XPC client startSession handshake failed for clientSessionId: %s: %@"
+ "YearlessOrFullDate"
+ "accessLevel"
+ "actionCreated"
+ "agentAction"
+ "agentIntent"
+ "apple.parsec.device_expert.v1alpha.AgentExtension"
+ "apple.parsec.device_expert.v1alpha.AgentInput"
+ "apple.parsec.device_expert.v1alpha.DeviceExpertSearchRequest"
+ "apple.parsec.device_expert.v1alpha.DeviceExpertSearchResponse"
+ "apple.parsec.device_expert.v1alpha.QuickAnswersExtension"
+ "apple.parsec.device_expert.v1alpha.QuickAnswersInput"
+ "apple.parsec.sam.v1alpha.SAMSelfLogs"
+ "apple.parsec.sam.v1alpha.SkimmerGuidance"
+ "apple.parsec.search.NumberFormat"
+ "assistantDismissalPolicy"
+ "attributeKey"
+ "batchable"
+ "behavior"
+ "character"
+ "characterTypedWith"
+ "choice"
+ "clientApplicationId"
+ "clientSpecificMetadata"
+ "confirmation"
+ "criticalError"
+ "customAttributeKey"
+ "customLabel"
+ "destinationAgentID"
+ "developerDefinedError"
+ "entityData"
+ "entityType"
+ "fullRepresentationPropertyIdentifiers"
+ "gen_ai.usage.reasoning_tokens"
+ "inputVariablePythonName"
+ "instanceIdentifier"
+ "interventionRequired"
+ "keyPathsToRender"
+ "level"
+ "modelRepresentation"
+ "paired"
+ "parameterMode"
+ "personaUniqueIdentifier"
+ "pirpb.LocaleAlias"
+ "plannerModelFacingError"
+ "plannerResponse"
+ "prebuiltAppIntentError"
+ "propertyIdentifiers"
+ "protocolProperties"
+ "provenance"
+ "rawInitiatedSpans"
+ "rawValue"
+ "representations"
+ "searchfoundation.NormalizedRect"
+ "siri.planner.assets"
+ "siri.planner.assets_count"
+ "siri.planner.system_version"
+ "snippetRepresentable"
+ "spotlightAttributes"
+ "stable"
+ "stateChangeRawValue"
+ "stateChangeWithBehavior"
+ "structuredAgentId"
+ "summaryRepresentationPropertyIdentifiers"
+ "supportedComponentKinds"
+ "supportedContentTypeIdentifiers"
+ "supportedFeatures"
+ "supportedLevels"
+ "syncableIdentifier"
+ "transferable"
+ "userIdentity"
+ "useragentpb.OriginatingDevice"
+ "useragentpb.OsVersion"
+ "visual"
- "Local object should be SiriAppIntentsXPCClient.ReverseServer"
- "SiriAppIntents/XPCServiceClient.swift"
```
