## FoundationModels

> `/System/Library/Frameworks/FoundationModels.framework/FoundationModels`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22968c` | `0x1feae4` | **`-0x2aba8`** |
| `__DATA.__bss` | `0x23690` | `0x1e3d0` | **`-0x52c0`** |
| `__TEXT.__const` | `0x1e338` | `0x1a628` | **`-0x3d10`** |
| `__AUTH_CONST.__const` | `0x16240` | `0x12fa8` | **`-0x3298`** |
| `__TEXT.__constg_swiftt` | `0x8070` | `0x69e0` | **`-0x1690`** |
| `__TEXT.__swift5_typeref` | `0x715b` | `0x5e51` | **`-0x130a`** |
| `__TEXT.__eh_frame` | `0xf2c8` | `0xdfe8` | **`-0x12e0`** |
| `__TEXT.__swift5_fieldmd` | `0x9004` | `0x8044` | **`-0xfc0`** |
| `__AUTH_CONST.__objc_const` | `0x1fa8` | `0x1388` | **`-0xc20`** |
| `__DATA_DIRTY.__data` | `0x4b70` | `0x3f70` | **`-0xc00`** |
| `__TEXT.__unwind_info` | `0x7e08` | `0x7248` | **`-0xbc0`** |
| `__TEXT.__swift5_reflstr` | `0x596c` | `0x4e4d` | **`-0xb1f`** |
| `__TEXT.__cstring` | `0x5eba` | `0x53aa` | **`-0xb10`** |
| `__DATA.__data` | `0x4a38` | `0x3f50` | **`-0xae8`** |
| `__TEXT.__oslogstring` | `0x1d4c` | `0x135c` | **`-0x9f0`** |
| `__AUTH_CONST.__auth_got` | `0x28f0` | `0x2420` | **`-0x4d0`** |
| `__TEXT.__swift5_proto` | `0x1564` | `0x1250` | **`-0x314`** |
| `__DATA_CONST.__got` | `0xde0` | `0xbb0` | **`-0x230`** |
| `__TEXT.__objc_methlist` | `0x31c` | `0x110` | **`-0x20c`** |
| `__DATA_DIRTY.__objc_data` | `0x510` | `0x320` | **`-0x1f0`** |
| `__TEXT.__swift5_assocty` | `0x1680` | `0x14a0` | **`-0x1e0`** |
| `__TEXT.__swift5_types` | `0xb44` | `0x9a0` | **`-0x1a4`** |
| `__DATA_CONST.__objc_selrefs` | `0x458` | `0x300` | **`-0x158`** |
| `__AUTH.__data` | `0x2d38` | `0x2c78` | **`-0xc0`** |
| `__DATA_CONST.__const` | `0x478` | `0x3b8` | **`-0xc0`** |
| `__TEXT.__swift_as_cont` | `0x644` | `0x588` | **`-0xbc`** |
| `__DATA_DIRTY.__bss` | `0x2200` | `0x2180` | **`-0x80`** |
| `__DATA.__common` | `0x278` | `0x210` | **`-0x68`** |
| `__AUTH.__objc_data` | `0x90` | `0xf0` | **`+0x60`** |
| `__DATA_CONST.__objc_classlist` | `0xe0` | `0x88` | **`-0x58`** |
| `__TEXT.__swift5_capture` | `0x1064` | `0x1014` | **`-0x50`** |
| `__TEXT.__swift5_protos` | `0xbc` | `0x70` | **`-0x4c`** |
| `__TEXT.__swift_as_entry` | `0x3f0` | `0x3a8` | **`-0x48`** |
| `__TEXT.__swift_as_ret` | `0x4e0` | `0x49c` | **`-0x44`** |
| `__DATA_CONST.__objc_protolist` | `0x38` | `—` | **`-0x38`** |
| `__DATA_CONST.__objc_protorefs` | `0x28` | `—` | **`-0x28`** |
| `__DATA_DIRTY.__common` | `0x188` | `0x160` | **`-0x28`** |
| `__TEXT.__swift5_builtin` | `0x21c` | `0x208` | **`-0x14`** |
| `__TEXT.__swift5_mpenum` | `0x13c` | `0x128` | **`-0x14`** |

### Other Changes

```diff

-2.0.68.1.101
+2.1.7.1.102

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  - /System/Library/PrivateFrameworks/IntelligencePlatformLibrary_AppleInternal.framework/IntelligencePlatformLibrary_AppleInternal

-  - /System/Library/PrivateFrameworks/ProactiveDaemonSupport.framework/ProactiveDaemonSupport
+  - /System/Library/PrivateFrameworks/PrivateCloudCompute.framework/PrivateCloudCompute

-  Functions: 10956
-  Symbols:   322
-  CStrings:  669
+  Functions: 9905
+  Symbols:   317
+  CStrings:  564
Symbols:
+ _AnalyticsSendEventLazy
+ _objc_release_x1
+ _objc_retain_x27
+ _swift_continuation_resume
+ _swift_continuation_throwingResume
+ _swift_dynamicCastMetatype
+ _swift_release_x10
+ _swift_release_x12
+ _swift_retain_x10
- _CGImageCreateWithPNGDataProvider
- _OBJC_CLASS_$_NSXPCConnection
- _OBJC_CLASS_$_NSXPCInterface
- _OBJC_CLASS_$_NSXPCListener
- __os_activity_create
- __swift_stdlib_reportUnimplementedInitializer
- _dlsym
- _objc_lookUpClass
- _objc_retain_x24
- _os_activity_scope_enter
- _os_activity_scope_leave
- _swift_getTupleTypeMetadata3
- _swift_isEscapingClosureAtFileLocation
- _swift_isaMask
CStrings:
+ "\". Call `supportsDataEntryType(_:)` on the model to check which content types it accepts before including a data entry in a transcript, or route this content to a different model that opts into it."
+ "'body(content:)' should not be called on OnActivateDynamicInstructionsModifier."
+ "'body(content:)' should not be called on OnDeactivateDynamicInstructionsModifier."
+ ". Remove the attachment(s) or use a model that accepts them."
+ "AppleGMSLanguageModel"
+ "Audio embedding segments are not supported by ServerLanguageModel."
+ "Couldn't resolve the model's details: %@"
+ "Data attachments are not supported."
+ "FoundationModels/ImageReferenceSchemaConstraint.swift"
+ "FoundationModels/SessionManagedPropertyCache.swift"
+ "Missing 'audioEmbedding'"
+ "Missing 'data' payload for data attachment"
+ "No attachment labels found in transcript, but tool \"%s\" requires an attachment label parameter. This tool is now disabled."
+ "No quota tracked for feature %{public}s."
+ "OpenAI-Compatible-Custom-Routing:"
+ "Private Cloud Compute quotas are unavailable on this platform."
+ "Private Cloud Compute tracks no quota for the feature "
+ "PrivateCloudComputeLanguageModel"
+ "PromptStream_V1 dropping custom content; it can't stream as an input delta."
+ "PromptStream_V1 dropping image content; it can't stream as an input delta."
+ "PromptStream_V1 dropping structured content; it can't stream as an input delta."
+ "ServerLanguageModel"
+ "SystemLanguageModel."
+ "The model produced an empty response."
+ "The model rejected a data entry with content type \""
+ "The selected model does not accept custom content of type(s): "
+ "Timed out resolving the model's details."
+ "Transcript must end with a .prompt, .toolOutput, or .response entry."
+ "Unexpected data entry %{public}s with content type %{public}s reached Apple GMS lowering; skipping."
+ "Warning that no usage quota is defined for a feature"
+ "Warning that usage quotas can't be read on the current platform"
+ "_x>TpzS\"geq$pz!#bRy^YxS%pT&y`dB=geW#fd%J"
+ "audio embedding ("
+ "audioEmbedding"
+ "com.apple.FoundationModels.inferenceSummary"
+ "data"
+ "pipBackedServerLanguageModel"
+ "prompt streaming"
- "\n\nIf you are the best to answer the question according to your description, you\ncan answer it.\n\nIf another agent is better for answering the question according to its\ndescription, call the agent transfer function for that agent.\nWhen transferring, do not generate any text other than the function call.\n"
- "\nAgent description: "
- "\nYour parent agent is "
- " agent. The transfer always succeeds."
- "%s: Called for agent: %s"
- "%{public}s Delegate: Client is missing '%{public}s' entitlement. This entitlement is required. Rejecting connection."
- "%{public}s Delegate: Got connection request."
- "%{public}s Delegate: Rejecting connection from %{public}d: lacking entitlement '%{public}s'"
- "%{public}s Delegate: XPC connection for service from %{public}d"
- "%{public}s Delegate: clientApplicationIdentifier: %{public}s"
- "%{public}s Delegate: connection interrupted."
- "%{public}s Delegate: connection invalidated."
- "%{public}s Delegate: connection rejected by server instance."
- "%{public}s: Connection to XPC Server interrupted."
- "%{public}s: Connection to XPC Server invalidated."
- "%{public}s: did not create connection."
- "%{public}s: error during call: %{public}@."
- "%{public}s: establishing connection."
- ". If neither the other agents nor\nyou are best for answering the question according to the descriptions, transfer\nto your parent agent. If you don't have parent agent, try answer by yourself."
- "After tool callback requested to exit run loop after %s"
- "Agent cancelled. Session ID: %s"
- "Agent finished with error. Session ID: %s. Error: %@"
- "Agent finished with unknown termination reason. Session ID: %s"
- "Agent finished. Session ID: %s"
- "AgentTransferRequestProcessor can only be used with LLMAgent. Instead got: "
- "AgentTransferTool"
- "Attachments are not supported in Agents."
- "BasicRequestProcessor can only be used with LLMAgent. Instead got: "
- "BidirectionalXPCServiceClientConnection: Attempt to establish a connection without a live delegate object."
- "Cannot generate content as the invocation context does not contain an LLMAgent. Instead got: "
- "Custom Responses are not supported in Agents."
- "Custom attachments are not supported."
- "Custom segments are not supported in Transcript_V1"
- "Exiting run loop after tool callback from %s"
- "Expected exactly one transcript entry"
- "Failed to create Internal XPC service"
- "Failed to emit SessionEndEvent: %@"
- "Failed to emit SessionStartEvent: %@"
- "Failed to extract agent transfer: %@"
- "Failed to find agent '%s' with ancestry %s in hierarchy"
- "Failed to initialize EventReporter: %@"
- "FinalResponseTool"
- "FoundationModels.DynamicDelegate"
- "FoundationModels.GenerativeAgentsTransportXPCTransferCallbackHandler"
- "FoundationModels.Server"
- "FoundationModels/AgentDefinition_V1.swift"
- "FoundationModels/AgentEventCollectingStream.swift"
- "FoundationModels/AgentTool.swift"
- "FoundationModels/AgentTransferRequestProcessor.swift"
- "FoundationModels/BaseLLMFlow.swift"
- "FoundationModels/BasicRequestProcessor.swift"
- "FoundationModels/ContentsRequestProcessor.swift"
- "FoundationModels/DynamicXPCService.swift"
- "FoundationModels/GenerativeAgentClientXPCServiceServer.swift"
- "FoundationModels/InstructionsRequestProcessor.swift"
- "FoundationModels/PromptCompletion+InferenceResponse.swift"
- "FoundationModels/ShortcutsAPIStubs.swift"
- "FoundationModels/TranscriptEvent_V1.swift"
- "GenerativeAgentDefinition: context: %{private}s"
- "GenerativeAgentDefinition: info.transcriptView: %{private}s"
- "GenerativeAgentRunner"
- "GenerativeAgentsModelCall"
- "GenerativeAgentsRunner"
- "GenerativeAgentsTransportXPCClient.agentDefinitionInfo"
- "GenerativeAgentsTransportXPCClient.transferToAgent"
- "GenerativeAgentsTransportXPCTransferCallbackProtocol: onNewEvent: error: %@"
- "GenerativeModelsAgentRunner: Last event contained a transfer to agent %s. New destinationAncestorNames: %s."
- "GenerativeModelsAgentRunner: Last event was from agent %s (ancestry: %s)."
- "GenerativeModelsAgentRunner: Last event was from user. Running agent based on routing logic: %s."
- "GenerativeModelsAgentRunner: lastSessionEvent.author is agent %s, and the agent to actually run is %s"
- "GenerativeModelsAgentRunner: lastSessionEvent: %{private}s)."
- "ImplicitRootDynamicInstructions"
- "InstructionsRequestProcessor can only be used with LLMAgent. Instead got: "
- "Invalid starting state, last event is a function call: %s"
- "Invalid starting state, last event is a web-search call: %s"
- "Invalid starting state, last event is instructions: %s"
- "Invalid starting state, no session events"
- "Missing 'custom' payload for custom attachment"
- "Object schemas require a 'title' key"
- "OutOfProcessAgent.runImplementation: terminalAgentAction: %s"
- "Protocol"
- "RecencyBasedAgentRouter.agentToRun: Latest agent event author: %s (ancenstors: %s)."
- "Running agent with session ID: %s"
- "Session ended without producing a response."
- "Should never be called directly."
- "Should not be called."
- "Starting to run: %s for session ID: %s"
- "StructuredInputAgentTransferTool"
- "The argument passed in is: "
- "The name of the agent to transfer to"
- "Tool call: %s failed with error: %@"
- "Transcript must end with a .prompt or .toolOutput entry."
- "Transfer the question to another agent. The transfer always succeeds. This agent transfer tool supports the following agents: ["
- "Transfer the question to the "
- "TransferToAgentCallbackHandler: cleanup: lastTask: error: %@"
- "TransferToAgentCallbackHandler: onNewEvent: lastLastTask: error: %@"
- "TransferToAgentCallbackHandler: onNewEvent: onNewEvent: error: %@"
- "Transferring to agent (destination: %s): %s"
- "Unknown action type: "
- "Unknown author type: "
- "Unsupported TranscriptEvent version: "
- "Unsupported annotation type"
- "Unsupported audio format"
- "Unsupported finish reason"
- "Unsupported moderation type"
- "Unsupported toolCall type"
- "Using afterToolCallback response for tool: %s"
- "Using beforeToolCallback response for tool: %s"
- "You attempted to call `agentRespond(to:)` a second time before letting the first call complete. This is a programmer error."
- "You attempted to call `agentStreamResponse_V1(to:)` a second time before letting the first call complete. This is a programmer error."
- "You have a list of other agents to transfer to:\n"
- "_os_activity_current"
- "` tool returned: "
- "` with arguments: "
- "action"
- "actions"
- "additionalRequestParameters"
- "agentDefinitionInfo"
- "agentDefinitionInfos"
- "agentName"
- "agentTransfer"
- "agent_transfer_tool"
- "agent_transfer_tool: Called for agent: %s"
- "agent_transfer_tool: Requested invalid agent: %s"
- "ancestorAgentNames"
- "application-identifier"
- "author"
- "base onReceiveEvent onFinish "
- "body should not be called."
- "branch"
- "com.apple.GenerativeAgents"
- "com.apple.GenerativeModels"
- "com.apple.generativeagentstransportd.transport"
- "com.apple.private.GenerativeAgentsTransport.runtime"
- "com.apple.private.GenerativeAgentsTransport.runtime."
- "destination"
- "init()"
- "invocationIdentifier"
- "originalProcessParentAgentInfo"
- "outOfProcessAgentID"
- "sessionIdentifier"
- "useCaseIdentifier"
- "version1"
```
