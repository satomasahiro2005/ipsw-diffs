## IntelligenceFlowPlannerRuntime

> `/System/Library/PrivateFrameworks/IntelligenceFlowPlannerRuntime.framework/IntelligenceFlowPlannerRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f2c90` | `0x728164` | **`+0x354d4`** |
| `__TEXT.__eh_frame` | `0x3b924` | `0x3c724` | **`+0xe00`** |
| `__AUTH_CONST.__const` | `0x26220` | `0x26d08` | **`+0xae8`** |
| `__TEXT.__oslogstring` | `0x2262c` | `0x22fdc` | **`+0x9b0`** |
| `__TEXT.__const` | `0x28910` | `0x29120` | **`+0x810`** |
| `__DATA.__bss` | `0x24e80` | `0x25650` | **`+0x7d0`** |
| `__TEXT.__cstring` | `0x1598a` | `0x15f0a` | **`+0x580`** |
| `__TEXT.__unwind_info` | `0x153e8` | `0x14ef0` | **`-0x4f8`** |
| `__AUTH_CONST.__auth_got` | `0xaa80` | `0xaeb0` | **`+0x430`** |
| `__TEXT.__swift5_reflstr` | `0xa393` | `0xa683` | **`+0x2f0`** |
| `__DATA_CONST.__got` | `0x5008` | `0x52e8` | **`+0x2e0`** |
| `__DATA.__data` | `0x5250` | `0x5518` | **`+0x2c8`** |
| `__DATA_DIRTY.__data` | `0xf0d8` | `0xee60` | **`-0x278`** |
| `__TEXT.__swift5_typeref` | `0xd218` | `0xd488` | **`+0x270`** |
| `__TEXT.__swift5_fieldmd` | `0xbb8c` | `0xbda4` | **`+0x218`** |
| `__TEXT.__swift5_capture` | `0x7148` | `0x7338` | **`+0x1f0`** |
| `__AUTH.__data` | `0x4608` | `0x4740` | **`+0x138`** |
| `__AUTH_CONST.__objc_const` | `0x8c18` | `0x8d18` | **`+0x100`** |
| `__DATA_DIRTY.__bss` | `0x7610` | `0x7510` | **`-0x100`** |
| `__TEXT.__swift_as_cont` | `0x2ba0` | `0x2c08` | **`+0x68`** |
| `__TEXT.__swift5_assocty` | `0x900` | `0x948` | **`+0x48`** |
| `__TEXT.__swift5_builtin` | `0x2e4` | `0x320` | **`+0x3c`** |
| `__TEXT.__swift5_proto` | `0x18c0` | `0x18f8` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x740` | `0x770` | **`+0x30`** |
| `__DATA.__common` | `0x161` | `0x189` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xb50` | `0xb78` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0xb8e4` | `0xb908` | **`+0x24`** |
| `__TEXT.__swift5_types` | `0xe14` | `0xe38` | **`+0x24`** |
| `__TEXT.__swift5_mpenum` | `0xe4` | `0xf4` | **`+0x10`** |
| `__DATA_DIRTY.__common` | `0x410` | `0x408` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x10a0` | `0x1098` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x1dc` | `0x1d8` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x161c` | `0x1620` | **`+0x4`** |

### Other Changes

```diff

-3600.147.12.501.3
+3600.151.4.501.6

-  Functions: 32766
-  Symbols:   517
-  CStrings:  3592
+  Functions: 33357
+  Symbols:   519
+  CStrings:  3646
Symbols:
+ _IOSurfacePropertyKeyAllocSize
+ _OBJC_CLASS_$_INPersonHandle
CStrings:
+ " Always respond in English, irrespective of the user's request language."
+ " in availableModels; got "
+ "\"kind\":\"FileEntity\""
+ "\"kind\":\"OnScreenText\""
+ "%s %s: AgenticPlannerService: Ending the progressive planning loop and returning - Reason: Normal completion (planningDone=true) after %ld meaningful steps"
+ "%s Cannot compute tokenDistance.\ncandidateTitle: '%s', queryString: '%s', but  exactMatchScore is nil for candidate: %s"
+ "%{public}s served-bundle PCC connection not yet ready — re-arming check-in deadline (completionEstimate: %{public}s)"
+ "AnnouncementReadIntent"
+ "AnnouncementReplyIntent"
+ "AnnouncementSendIntent"
+ "AnnouncementStopPlaybackIntent"
+ "AppSchemaResolver#getApp: One %s tool found for companion-paired request, resolving with bundleId: %s"
+ "ApplicationEntity"
+ "Confirmed user id does not match selected user id"
+ "Failed to insert GMSProtoGMSPlannerRequest into feature store: %{private}@"
+ "Failed to insert promptcraft ContentBlocks_PromptInput into feature store: %{private}@"
+ "Focused Entities ("
+ "Injected synthetic span match: %s (%s)"
+ "Me card not specified"
+ "Multi-user decision for [%{public}s]: confirmation required"
+ "Multi-user decision for [%{public}s]: known/confident user classification always allowed."
+ "Multi-user decision for [%{public}s]: user previously confirmed"
+ "Multi-user decision for [ask_user_to_confirm]: Always allow ask_user_to_confirm"
+ "No selected user found"
+ "Passthrough capture is unavailable on this platform"
+ "PlayTrailerIntent"
+ "Running MultiUserRequirementEvaluator.evaluate because it is a remote request."
+ "Running progressive planning step (meaningful: "
+ "SIRI_INTELLIGENCE_FLOW_PLANNER"
+ "SiriPCCAgentRouter can only route .chat requests; got a non-chat (completion) request"
+ "SiriPCCAgentRouter contextHeadroomFraction must be in [0, 1); got "
+ "SiriPCCAgentRouter only supports logical request bundle "
+ "SiriPCCAgentRouter requires "
+ "ToolCandidateGenerator#filterOutSiriKitFlowToolsWithoutClientSupport: dropping SiriKit companion tool with no client support: %s"
+ "ToolCandidateGenerator#filterOutSiriKitFlowToolsWithoutClientSupport: filter bypassed (hasFilter=%{bool}d, hasClientDeviceIDSIdentifier=%{bool}d, hasTargetDeviceIdsId=%{bool}d), returning all %ld candidate(s)"
+ "User selected has unexpected classification of None"
+ "User with unknown classification should never been handled on companion."
+ "Visual Intelligence disabled via user default; returning .none"
+ "Visual Intelligence disabled via user default; skipping image capture"
+ "[%s] File data is empty (0 bytes); skipping so Transferable fallback can fire."
+ "[%s] PCC rejected prefixID as unrecognized — retrying with full system prompt"
+ "[AgentSystemPrompt] Failed to load AgentInstructionsData: %{public}s"
+ "[AgentSystemPrompt][PlatformInstructions] Injected tool catalog appendix (fallback)"
+ "[AgentSystemPrompt][PlatformInstructions] Injected tool catalog appendix via template"
+ "[AgentSystemPrompt][PlatformInstructions] No request event found — cannot emit platform instructions"
+ "[AgentSystemPrompt][PlatformInstructions] Template render failed: %{public}s, falling back to ToolCatalogAppendix"
+ "[AgentSystemPrompt][SpanMatchInstructions] Failed to render: %{public}s"
+ "[AgentSystemPrompt][SpanMatchInstructions] Injected span match instructions"
+ "[INSIGHTS_TIMELINE|Planning Loop|Repeated tool call on ODM — handing off to PCC|🏳️|]"
+ "[ReduceSensitiveContent] Injecting parental controls restricted only (Screen Time restriction active)"
+ "[ReduceSensitiveContent] No injection — neither u18 nor Screen Time restriction active"
+ "[SessionSummarization] getCurrentRequestEvent() unexpectedly called during translation"
+ "[Tool Result Sanitization] Called on '%s' (%ld extra literal(s))"
+ "[Tool Result Sanitization] Called on '%{sensitive}s' (%ld extra literal(s))"
+ "[on-device-routing] %{public}s: active bundle %{public}s is not a routable bundle; not routing"
+ "[on-device-routing] %{public}s: disabled by preference/trial; using single-generator path"
+ "[on-device-routing] %{public}s: failed to construct router: %{public}s; using single-generator path"
+ "[on-device-routing] %{public}s: failed to prewarm routable model %{public}s: %{public}s"
+ "[on-device-routing] %{public}s: non-PCC mode %{public}s; not routing"
+ "[on-device-routing] %{public}s: prewarmed extra routable models=%{public}s (default=%{public}s)"
+ "[on-device-routing] %{public}s: prewarming routable model %{public}s urgency=%{public}s"
+ "[on-device-routing] %{public}s: routed bundle %{public}s not held (plannerBundle=%{public}s held=%{public}s reason=%{public}s); cannot serve"
+ "[on-device-routing] %{public}s: routing plugin installed (bundles=%{public}s)"
+ "[on-device-routing] %{public}s: serving routed bundle %{public}s (reason=%{public}s terminal=%{bool,public}d)"
+ "[on-device-routing] [%s] thoughtBudget=%{public}s for served bundle %{public}s"
+ "[on-device-routing] enablement from trial (%{public}s): %{bool,public}d"
+ "[on-device-routing] enablement set via UserDefaults to %{bool,public}d"
+ "[on-device-routing] plannerID=%{public}s step=%{public}ld requiredModelBundle=%{public}s terminal=%{bool,public}d routeReason=%{public}s"
+ "[on-device-routing] plannerID=%{public}s step=%{public}ld routing failed: %{public}s"
+ "[on-device-routing] plannerID=%{public}s terminal decision: no deselected generators to tear down (chosen=%{public}s)"
+ "[on-device-routing] plannerID=%{public}s terminal decision: tore down deselected generators bundles=[%{public}s] (kept %{public}s)"
+ "[on-device-routing] pre-bind decide failed: %{public}s"
+ "[on-device-routing] prewarming planner bundle %{public}s urgency=%{public}s routing=%{public}s"
+ "attachment"
+ "carplay_ultra_tools"
+ "com.apple.fm.language.instruct_server_v2.lw_planner_upgradeable"
+ "com.apple.fm.language.instruct_server_v2.lw_planner_v5"
+ "context_length"
+ "current_camera_view"
+ "editable_text_field"
+ "file_attachment"
+ "findExistingSpanMatchFromTranscript(transcriptEvents:queryEventId:)"
+ "find_tool"
+ "init(transcriptView:agentOutputPublisher:hydrationService:entityService:concurrencySafeToolExecutionSession:toolbox:plannerToolbox:defaultDateTimeContext:queryAugmentationServiceProvider:appSchemaResolver:contextPromptRenderer:agentFunctionCallUuid:templateContextAutoGenerateToolCall:toolboxInput:imageCaptureAndRetrievalService:deviceAuthenticationStateCalculator:userContext:userContextResolver:featureFlagProvider:preferencesProvider:annotations:outputGuardrail:provenanceRegistry:appExclusionService:searchDedupRecorder:)"
+ "language_game_sections"
+ "mitigation_eligible"
+ "multi_turn"
+ "none"
+ "onDeviceRoutingPluginEnabled"
+ "stageLaunderedScreenshot: imageData.count=%ld, identifier=%s"
+ "systemRequirement %{public}s"
+ "systemRequirement type: userIdentityConfirmationRequired"
+ "u18_model_guidelines_restricted_mdm"
+ "writing_tool_name"
- "\nIf the user asks you 'to answer', without specifying what to answer, call the `answer_call` tool with the above live call.\n"
- "%s %s: AgenticPlannerService: Ending the progressive planning loop and returning - Reason: Normal completion (planningDone=true) after %ld steps"
- "AppSchemaResolver#getApp: One client tool found for companion-paired request, resolving with client bundleId: %s"
- "Building per-entity open action using %s tool"
- "Cached passthrough camera image task for requestID: %s"
- "CommsAppResolver#resolveApp: companion-paired comms request with no explicit app will default to 1P: %s"
- "DRM content detected in view"
- "Error querying tool database for openEntity: %@"
- "Failed to build passthrough AgentMediaEntity"
- "Failed to insert GMSProtoGMSPlannerRequest into feature store: %@"
- "Failed to insert promptcraft ContentBlocks_PromptInput into feature store: %@"
- "Failed to load passthrough camera image from MixedRealityFrame provider after %ld attempts in %s seconds. Returning nil."
- "Found %ld open-entity tools for %s"
- "Matched open-entity tool %s for entity type %s"
- "MixedRealityFrame provider available, starting image capture with requestID: %s"
- "No cached gaze found for requestID: %s"
- "No locale/request context; skipping per-entity openAction augmentation"
- "No open-entity tool accepts entity type %s for %s"
- "No openEntity tool for %s; falling back to launchApp"
- "Passthrough camera image successfully loaded after %ld attempts in %s seconds."
- "Running progressive planning step "
- "[AgentSystemPrompt][CatalogAppendix] Injected tool catalog appendix"
- "[AgentSystemPrompt][CatalogAppendix] No request event found — cannot emit catalog appendix"
- "[ReduceSensitiveContent] Injecting restricted only (MDM restriction active)"
- "[ReduceSensitiveContent] No injection — neither u18 nor MDM restriction active"
- "[ResultCollection] Container lookup failed for %s: %@"
- "[ResultCollection] Found container %s for %s"
- "[ResultCollection] No container definition found for %s"
- "[Tool Result Sanitization] Called on '%s' to sanitize %ld pattern(s)"
- "[Tool Result Sanitization] Called on '%{sensitive}s' to sanitize %ld pattern(s)"
- "entityOpenAction"
- "failed to donate passthrough AgentMediaEntity to entity service: %@"
- "findExistingSpanMatchFromTranscript(eventsFromLatestRequest:queryEventId:)"
- "getOrCreatePassthroughImageRetrievalResponse for requestID: %s"
- "init(transcriptView:agentOutputPublisher:hydrationService:entityService:concurrencySafeToolExecutionSession:toolbox:plannerToolbox:defaultDateTimeContext:queryAugmentationServiceProvider:appSchemaResolver:contextPromptRenderer:agentFunctionCallUuid:templateContextAutoGenerateToolCall:toolboxInput:imageCaptureAndRetrievalService:deviceAuthenticationStateCalculator:userContext:userContextResolver:featureFlagProvider:preferencesProvider:annotations:outputGuardrail:provenanceRegistry:appExclusionService:)"
- "no cached passthrough capture for requestID: %s; not staging"
- "no entity service — passthrough AgentMediaEntity not donated; image will not reach model"
- "no pixel buffer available from MixedRealityFrame provider"
- "passthrough AgentMediaEntity donation error: %@"
- "resolvePassthroughFrameData using cached task for requestID: %s"
```
