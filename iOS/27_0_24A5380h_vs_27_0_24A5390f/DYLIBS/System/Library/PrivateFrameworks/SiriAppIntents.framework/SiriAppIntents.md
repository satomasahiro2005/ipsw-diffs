## SiriAppIntents

> `/System/Library/PrivateFrameworks/SiriAppIntents.framework/SiriAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12a1ab8` | `0x12ec1a4` | **`+0x4a6ec`** |
| `__DATA.__bss` | `0x235390` | `0x237990` | **`+0x2600`** |
| `__TEXT.__const` | `0x19d020` | `0x19f040` | **`+0x2020`** |
| `__AUTH_CONST.__const` | `0x36ae0` | `0x38ac0` | **`+0x1fe0`** |
| `__TEXT.__eh_frame` | `0xb5edc` | `0xb7840` | **`+0x1964`** |
| `__TEXT.__cstring` | `0x25667` | `0x26c37` | **`+0x15d0`** |
| `__TEXT.__unwind_info` | `0x7e998` | `0x7fec0` | **`+0x1528`** |
| `__AUTH.__data` | `0x15ab8` | `0x16da0` | **`+0x12e8`** |
| `__AUTH_CONST.__objc_const` | `0x25bc8` | `0x26790` | **`+0xbc8`** |
| `__TEXT.__swift5_fieldmd` | `0x4b578` | `0x4c008` | **`+0xa90`** |
| `__DATA.__data` | `0x42138` | `0x42aa8` | **`+0x970`** |
| `__TEXT.__constg_swiftt` | `0x3c9bc` | `0x3d2f0` | **`+0x934`** |
| `__TEXT.__swift5_reflstr` | `0x42d7c` | `0x435ec` | **`+0x870`** |
| `__DATA_DIRTY.__data` | `0x80b00` | `0x80490` | **`-0x670`** |
| `__TEXT.__swift5_capture` | `0x1d08` | `0x2278` | **`+0x570`** |
| `__TEXT.__swift5_typeref` | `0x2a152` | `0x2a6bc` | **`+0x56a`** |
| `__TEXT.__oslogstring` | `0x2b7d` | `0x2ecd` | **`+0x350`** |
| `__DATA_CONST.__const` | `0x1ac10` | `0x1ad60` | **`+0x150`** |
| `__TEXT.__swift5_proto` | `0x12444` | `0x12588` | **`+0x144`** |
| `__AUTH.__objc_data` | `—` | `0x140` | **`+0x140`** |
| `__AUTH_CONST.__auth_got` | `0x13c0` | `0x14f8` | **`+0x138`** |
| `__TEXT.__swift5_types` | `0x38c4` | `0x3960` | **`+0x9c`** |
| `__TEXT.__swift5_assocty` | `0x7070` | `0x7100` | **`+0x90`** |
| `__TEXT.__swift_as_cont` | `0x32c` | `0x374` | **`+0x48`** |
| `__DATA_CONST.__objc_classlist` | `0x728` | `0x768` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x300` | `0x340` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x1e0` | `0x218` | **`+0x38`** |
| `__TEXT.__swift_as_entry` | `0x19c` | `0x1c0` | **`+0x24`** |
| `__DATA.__common` | `0x40` | `0x58` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x300` | `0x30c` | **`+0xc`** |

### Other Changes

```diff

-3600.82.15.0.0
+3600.82.20.0.0

-  Functions: 203415
-  Symbols:   232
-  CStrings:  4168
+  Functions: 205150
+  Symbols:   240
+  CStrings:  4345
Symbols:
+ _CFBooleanGetTypeID
+ _CFGetTypeID
+ _OBJC_CLASS_$_NSISO8601DateFormatter
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _OBJC_CLASS_$_NSRegularExpression
+ _memcmp
+ _memset
+ _objc_retainAutorelease
CStrings:
+ "  Error: Link Transport Unavailable\n"
+ " (allowsEagerUnlock)"
+ " (companionIfSessionID: "
+ "(no user fields populated)"
+ ".AppExclusionResult"
+ ".PrivacyTagNotification"
+ ".StartedRemoteSession"
+ "</?(?:coreResponse|standalone_answer)>|<supplemental_material\\s*/>"
+ "<citation\\b[^>]*/?>"
+ "Action: Call Return"
+ "Active Remote Session Not Found"
+ "Apple Intelligence Not Available"
+ "ChatService.submitToResponsePresented"
+ "ChatService.submitToResponseReceived"
+ "Classification: "
+ "Client Transcript Event Version Too High"
+ "Client Transcript Event Version Too Low"
+ "Companion Error: "
+ "Context.StructuredContextSiriRequestContextInvocationContext"
+ "Context.StructuredContextSiriRequestContextInvocationContextWindowDescriptor"
+ "Destination Agent: "
+ "Device Restricted"
+ "EntityCollection"
+ "EntitySearchResult"
+ "Final Post Process → SRT End"
+ "Final → Chat Presented"
+ "Final → SRT End"
+ "Invocation Request"
+ "MainContentViewModel.startNewChat"
+ "Max Timeout Reached"
+ "No request timestamp available for plannerID"
+ "Only Member in Home: "
+ "Personal Request Handled"
+ "PersonalRequestHandled"
+ "Preliminary Score"
+ "Privacy Tag Notification"
+ "PromptSubmission"
+ "Remote Agent Call"
+ "Remote Agent Call Return"
+ "Remote Agent Invocation Request"
+ "Remote Agent Invocation Result"
+ "Remote Session Cleaned Up After Timeout"
+ "Request: present (content redacted)"
+ "Response: present (content redacted)"
+ "Result: Unrecognized ("
+ "Result: Unspecified"
+ "SRT could not be computed (unexpected state)"
+ "Selected By Identity Guard Flow"
+ "Selection Reason: "
+ "Siri Disabled While Locked"
+ "Siri Shared User ID: "
+ "SiriTrajectory.extractEntries: kind=result entityEntries=%ld enrichedWithProperties=%ld added=%ld upgraded=%ld merged=%ld skipped=%ld"
+ "SiriTrajectory.extractEntries: kind=summary decodeFailures=%ld depthCaps=%ld elementCaps=%ld"
+ "SiriTrajectory.extractEntries: kind=summary type=image entries=%ld decodeFailures=%ld depthCaps=%ld"
+ "SiriTrajectory.extractEntries: kind=supplementary unreferencedEntities=%ld"
+ "SiriTrajectory.extractEntries: kind=version build=2026-07-02-phase3b-onscreentext"
+ "SiriTrajectory.extractEntries: phase1 decodeFailures=%ld parseFailures=%ld"
+ "SiriTrajectory.extractEntries: phase1 depthCaps=%ld"
+ "SiriTrajectory.extractEntries: phase1 requestsWithEntities=%ld storedEntries=%ld"
+ "SpanBuilder: build complete kind=summary events=%ld sessions=%ld spans=%ld srt=%ld replayPayloads=%ld rawInferenceEvents=%ld%s"
+ "Started Remote Session"
+ "Submission.submit"
+ "Sufficient Audio Processed Score"
+ "Transcript.PersonalRequestHandled"
+ "Transcript.ResponseTargetUser"
+ "Unable To Create Remote Session ("
+ "Unrecognized Final Score Reason (Please file a radar)"
+ "Unrecognized Guard Flow Type (Please file a radar)"
+ "Unrecognized Session Creation Failure Reason (Please file a radar)"
+ "Unrecognized User Selection Reason (Please file a radar)"
+ "User Input → Skimmer"
+ "UserAgeSetting_adult"
+ "UserAgeSetting_u13"
+ "UserAgeSetting_u18"
+ "UserAgeSetting_unspecified"
+ "VersionedTranscript.IntelligenceFlowError"
+ "VersionedTranscript.SiriRequestContextInvocationContext"
+ "VersionedTranscript.SiriRequestContextInvocationContextWindowDescriptor"
+ "\\s*This answer is from\\b.*\\z"
+ "^(NS|SA|SAUI|AS|UI|CL|CN|EK|DA|com\\.apple|\\$|\\{)"
+ "^[A-Za-z][A-Za-z0-9_]*$"
+ "__PARTIAL_ENTITY__"
+ "absoluteEndTime"
+ "aceCommandOutputData"
+ "aceCommandPayloads"
+ "acousticFtmMitigated"
+ "actionConfirmation"
+ "actionRequirement"
+ "action_confirmation"
+ "action_requirement"
+ "adBlockerMitigated"
+ "ask_user_to_pick"
+ "backgroundWindows"
+ "clientcoordinator"
+ "colorBlue"
+ "colorGreen"
+ "colorRed"
+ "com.apple.AgentCanvasKit"
+ "com.apple.CampoUI"
+ "com.apple.siri.analytics"
+ "deactivationRequested"
+ "deviceSelectionDecision"
+ "durationMs"
+ "duration_s"
+ "endMs"
+ "end_time"
+ "entities_level_of_detail"
+ "entities_level_of_details_available"
+ "entityIdentifiers"
+ "eval.applications"
+ "eval.asr_hypothesis"
+ "eval.assistant_message"
+ "eval.assistant_source"
+ "eval.cancel_reason"
+ "eval.context_requirement"
+ "eval.contextual_mitigation"
+ "eval.dialog_superseded_by_assistant"
+ "eval.entity_resolution"
+ "eval.funbench.agent_id"
+ "eval.has_visual_representation"
+ "eval.input_modality"
+ "eval.mitigation_decision"
+ "eval.on_screen_context"
+ "eval.referenced_entity_ids"
+ "eval.resolved_entities"
+ "eval.retrieval_confidence"
+ "eval.retrieval_query"
+ "eval.retrieval_rewritten_query"
+ "eval.retrieved_tools"
+ "eval.search_kind"
+ "eval.session_summary"
+ "eval.tool_retrieval"
+ "eval.trajectory.duration_s"
+ "eval.trajectory.end_time"
+ "eval.trajectory.id"
+ "eval.trajectory.labels"
+ "eval.trajectory.locale"
+ "eval.trajectory.metadata_json"
+ "eval.trajectory.schema_version"
+ "eval.trajectory.source"
+ "eval.trajectory.start_time"
+ "eval.trajectory.tags"
+ "eval.trajectory.tokens.input"
+ "eval.trajectory.tokens.output"
+ "eval.trajectory.tokens.total"
+ "eval.user_age_setting"
+ "eval.user_canceled"
+ "eval.user_message"
+ "eval.voice_attributes"
+ "executorGateResult"
+ "foregroundWindow"
+ "gen_ai.agent.name"
+ "gen_ai.conversation.id"
+ "gen_ai.system_instructions"
+ "gen_ai.tool.call.arguments"
+ "gen_ai.tool.call.id"
+ "gen_ai.tool.call.result"
+ "gen_ai.tool.name"
+ "hasVisualRepresentation"
+ "imageRetrievalResponse(visual=true)"
+ "invoke_agent SiriAgent"
+ "kind=summary fetchRawInferenceEventDataBatch fallback=perCall plannerIDs=%ld"
+ "kind=summary fetchRawInferenceEventDataBatch path=batch plannerIDs=%ld"
+ "kind=summary rawInferenceEvents payloads=%ld errors=%ld requested=%ld"
+ "kvlistValue"
+ "labels"
+ "level_of_details_available"
+ "missing start anchor"
+ "missing start and end anchors"
+ "model.inference.raw_event_data"
+ "newRequestStarted"
+ "parameterConfirmation"
+ "parameterDisambiguation"
+ "parameterNeedsValue"
+ "parameterNotAllowed"
+ "parameter_confirmation"
+ "parameter_disambiguation"
+ "parameter_needs_value"
+ "parameter_not_allowed"
+ "phase"
+ "plannerID is not a valid UUID"
+ "requestCanceledFromUI"
+ "requestDelagateReplacedForUnknownReason"
+ "runtimeNotSelected"
+ "schema_version"
+ "searchAndResolveResult"
+ "search_and_resolve_result"
+ "serializedAceCommand"
+ "siri_eval_pipeline.trajectory"
+ "source"
+ "startMs"
+ "start_time"
+ "tags"
+ "token_summary"
+ "tool_call_response"
+ "tool_response_raw"
+ "total_input_tokens"
+ "total_output_tokens"
+ "total_tokens"
+ "trajectory_id"
+ "unhandled_payload_keys"
- ".AnswerSynthesisToolQuery"
- "Answer Synthesis"
- "Context.ActivatedSkill"
- "RemoteExecutorGateResult"
- "SessionResumptionContext"
- "SessionRetrieved"
- "SiriTrajectory.extractEntries: kind=entityIdCollision requestID=%s id=%s"
- "SiriTrajectory.extractEntries: kind=summary entries=%ld decodeFailures=%ld depthCaps=%ld"
- "Skill Retrieval Request"
- "Skill Retrieval Response"
- "SpanBuilder: build complete kind=summary events=%ld sessions=%ld spans=%ld srt=%ld replayPayloads=%ld%s"
- "Transcript.AnswerSynthesisExpression"
- "Transcript.AnswerSynthesisExtractionCandidate"
- "Transcript.RemoteExecutorGateResult"
- "Transcript.SessionResumptionContext"
- "Transcript.SessionRetrieved"
- "Transcript.SessionRetrievedPayload"
- "Transcript.SkillRetrievalRequest"
- "Transcript.SkillRetrievalResponse"
- "UserSpeakingEnd "
- "anchors found but SRT computation failed"
- "live camera feed"
- "missing start anchors"
- "missing start anchors and end anchor"
```
