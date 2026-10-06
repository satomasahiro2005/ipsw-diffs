## IntelligenceFlowPlannerRuntime

> `/System/Library/PrivateFrameworks/IntelligenceFlowPlannerRuntime.framework/IntelligenceFlowPlannerRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bbf64` | `0x6ddbac` | **`+0x21c48`** |
| `__AUTH_CONST.__const` | `0x24428` | `0x25cc8` | **`+0x18a0`** |
| `__TEXT.__unwind_info` | `0x13c68` | `0x14c50` | **`+0xfe8`** |
| `__TEXT.__cstring` | `0x14c4a` | `0x159ca` | **`+0xd80`** |
| `__DATA.__bss` | `0x25cf0` | `0x26840` | **`+0xb50`** |
| `__TEXT.__const` | `0x278a0` | `0x281c0` | **`+0x920`** |
| `__TEXT.__eh_frame` | `0x3a798` | `0x3aff0` | **`+0x858`** |
| `__TEXT.__swift5_capture` | `0x67c4` | `0x6fd4` | **`+0x810`** |
| `__TEXT.__oslogstring` | `0x2147c` | `0x21b9c` | **`+0x720`** |
| `__TEXT.__swift5_typeref` | `0xcb60` | `0xd02e` | **`+0x4ce`** |
| `__AUTH.__data` | `0x65c0` | `0x6970` | **`+0x3b0`** |
| `__TEXT.__swift5_fieldmd` | `0xb548` | `0xb8cc` | **`+0x384`** |
| `__DATA.__data` | `0x6668` | `0x69d0` | **`+0x368`** |
| `__TEXT.__constg_swiftt` | `0xb310` | `0xb65c` | **`+0x34c`** |
| `__TEXT.__swift5_reflstr` | `0x9d53` | `0xa073` | **`+0x320`** |
| `__AUTH_CONST.__auth_got` | `0xa660` | `0xa888` | **`+0x228`** |
| `__DATA_CONST.__got` | `0x4d90` | `0x4ed0` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x8700` | `0x87f0` | **`+0xf0`** |
| `__TEXT.__swift_as_cont` | `0x2a5c` | `0x2b34` | **`+0xd8`** |
| `__TEXT.__swift_as_ret` | `0x1534` | `0x15d4` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0xad8` | `0xb40` | **`+0x68`** |
| `__DATA_DIRTY.__data` | `0xafa0` | `0xb000` | **`+0x60`** |
| `__TEXT.__swift5_proto` | `0x183c` | `0x1898` | **`+0x5c`** |
| `__AUTH.__objc_data` | `0x638` | `0x688` | **`+0x50`** |
| `__TEXT.__swift5_types` | `0xda8` | `0xde8` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0x1048` | `0x1060` | **`+0x18`** |
| `__DATA.__common` | `0x289` | `0x291` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x3f8` | `0x400` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x1d4` | `0x1dc` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x350` | `0x34c` | **`-0x4`** |

### Other Changes

```diff

-3600.138.6.501.17
+3600.144.5.501.3

+  - /System/Library/Frameworks/QuartzCore.framework/QuartzCore

-  Functions: 31742
-  Symbols:   498
-  CStrings:  3501
+  Functions: 32520
+  Symbols:   516
+  CStrings:  3570
Symbols:
+ _CACurrentMediaTime
+ _OBJC_CLASS_$_CPSchemaCPClientEvent
+ _OBJC_CLASS_$_CPSchemaCPClientEventMetadata
+ _OBJC_CLASS_$_CPSchemaCPModelInferenceContext
+ _OBJC_CLASS_$_CPSchemaCPModelInferenceEnded
+ _OBJC_CLASS_$_CPSchemaCPModelInferenceFailed
+ _OBJC_CLASS_$_CPSchemaCPModelInferenceStarted
+ _OBJC_CLASS_$_CPSchemaCPPredictionContext
+ _OBJC_CLASS_$_CPSchemaCPPredictionEnded
+ _OBJC_CLASS_$_CPSchemaCPPredictionFailed
+ _OBJC_CLASS_$_CPSchemaCPPredictionStarted
+ _OBJC_CLASS_$_CPSchemaCPSkimmerInferenceContext
+ _OBJC_CLASS_$_CPSchemaCPSkimmerInferenceEnded
+ _OBJC_CLASS_$_CPSchemaCPSkimmerInferenceStarted
+ _OBJC_CLASS_$_CPSchemaCPWarmupContext
+ _OBJC_CLASS_$_CPSchemaCPWarmupEnded
+ _OBJC_CLASS_$_CPSchemaCPWarmupFailed
+ _OBJC_CLASS_$_CPSchemaCPWarmupStarted
+ _OBJC_CLASS_$_INFile
+ _clock_gettime_nsec_np
+ _objc_retain_x9
+ _swift_release_x11
- _CFDataCreateMutable
- _CGBitmapContextCreateImage
- _CGImageGetHeight
- _CGImageGetWidth
CStrings:
+ "\n\n<supplemental_material/>\n\n"
+ " Key data points (e.g. for retrieval or list queries, name the items themselves) must appear in the prose or via ui_entity_rendering for entities that have ui_entity_rendering_text_components — by calling ui_entity_rendering on those entities you have already presented their data to the user, do not restate it in either <"
+ " Key data points (e.g. for retrieval or list queries, name the items themselves) must appear inside <"
+ " The user did not expand the UI — they only saw what was inside <"
+ " The user expanded the UI to see what was after <"
+ " The user might not expand the UI to see past <"
+ " and picked option "
+ "%s PCC connection established — proceeding with PCC inference"
+ "%s PCC not yet connected — guarding inference with a check-in deadline (completionEstimate: %s)"
+ "%s [PlannerToolExecutor] --force-find-args: forced auto_present_results=false, purpose=use_to_inform_user"
+ "%s: Did not find client context in transcript or stream. Defaulting to empty UserContext."
+ "%s: finalApprovalWithOverride failed during recitation rejection: %@"
+ ") - cancelling inference"
+ ". Adapt your response format accordingly. "
+ "</standalone_answer>"
+ "<baseline_ai_disclaimer>"
+ "<standalone_answer>"
+ "<supplemental_material/>"
+ "<ui_entity_rendering "
+ "<ui_entity_rendering/>"
+ "> in this turn — so <"
+ "> in your previous response and therefore saw the full response."
+ "> must directly answer the question, not introduce the supplemental material that follows. For lengthy answers, still provide the information that the user is after inside <"
+ "> on your previous turn."
+ ">. By calling ui_entity_rendering on entities with ui_entity_rendering_text_components you have already presented their data to the user — do not restate it after <"
+ "AgenticResolver.resolve"
+ "AssistantAlarmEntity"
+ "Before you move on, always verify important details. I'm an AI that may make mistakes."
+ "By the way, always verify important details. As an AI, I may make mistakes."
+ "Cannot commit transient attachments: imageCaptureAndRetrievalService is nil"
+ "Did not find any tools conforming to %s from the specified app bundle ID %s. If a tool is expected from this app, this could be an indexing issue."
+ "Failed to build passthrough AgentMediaEntity"
+ "Failed to cancel laundered screenshot reservation: %@"
+ "Failed to donate transient media entity"
+ "Failed to persist laundered screenshot media: %@"
+ "Failed to reserve identifier for laundered screenshot: %@"
+ "JRAppResolver [watchOS heuristic]: disambiguating"
+ "JRAppResolver [watchOS heuristic]: no candidate-app interactions, disambiguating"
+ "JRAppResolver [watchOS heuristic]: only one candidate app with interactions, resolving to %s"
+ "JRAppResolver [watchOS heuristic]: resolved to %s (%ld/%ld)"
+ "Matched open-entity tool %s for entity type %s"
+ "Network inference evaluation: isConnected=%{bool}d, rtt=%s"
+ "No entity service available to stage transient media"
+ "No open-entity tool accepts entity type %s for %s"
+ "Oh, and just a quick note: always verify important details. As an AI, I may make mistakes."
+ "One last thing, I'm an AI that may make mistakes, so always cross-check key information."
+ "PCC connection established by check-in deadline (%s) — letting inference complete"
+ "PCC connection not ready after check-in deadline ("
+ "Response mode changed from "
+ "Retrieved enum value for query '%s': %s with exact match"
+ "Reusing active gaze aware capture, requestID: %s"
+ "Using gaze aware capture provider for passthrough, requestID: %s"
+ "[AgentRequestTranslator] Failed to register selected disambiguation entity (selectedIndex=%{public}ld); falling back to index-only message"
+ "[AgentRequestTranslator] No triggering disambiguation action for selectedIndex %{public}ld; falling back to index-only message"
+ "[AgentRequestTranslator] Selected index %{public}ld out of range for %{public}ld disambiguation entities; falling back to index-only message"
+ "[AgentRequestTranslator] Triggering disambiguation action has no/empty 'entities' parameter (selectedIndex=%{public}ld); falling back to index-only message"
+ "[AgentSystemPrompt] Injected response mode transition directive: %{public}s → %{public}s"
+ "[AgenticPlanner] Using PCC prefixID: %{public}s"
+ "[INSIGHTS_TIMELINE|Context Predictor|Running|🔧|]"
+ "[INSIGHTS_TIMELINE|Model Inference|"
+ "[INSIGHTS_TIMELINE|Planner Tool Execution|Forced find args (FROG)|⚙️|]"
+ "[SELF] Failed to create CPSchemaCPClientEvent"
+ "[SELF] Failed to create CPSchemaCPClientEventMetadata"
+ "[SELF] Failed to create CPSchemaCPModelInferenceContext"
+ "[SELF] Failed to create CPSchemaCPPredictionContext"
+ "[SELF] Failed to create CPSchemaCPSkimmerInferenceContext"
+ "[SELF] Failed to create CPSchemaCPWarmupContext"
+ "[SearchListSnippetTransform] mergedView called: %ld item(s): [%s]"
+ "[SessionSummarization] isFirstTaskSinceLastSessionResumeBoundary() unexpectedly called during translation"
+ "[SiriRequestContextRenderer] Unrecognized responseMode — defaulting to Voice"
+ "[TOOL] start_call\n[TOOL DESCRIPTION] Make phone calls, FaceTime calls, video and audio calls to one or more recipients. Supports conference and group calls, callback to the most recent caller, and redialing the most recent outgoing call, including emergency and crisis support services."
+ "[TOOL] update_note\n[TOOL DESCRIPTION] Update and modify existing notes by changing titles, moving between folders, managing tags and attachments, pinning and unpinning notes. Append text and markdown-formatted content to notes. Apply text formatting including bold, italic, underline, and strikethrough. Set paragraph styles such as headings, titles, body text, and lists. Replace selected text in notes. Add, remove, check, and uncheck checklist items."
+ "[URLSecurity][%s] URLProvenanceCheckError caught at PTE — rendering per-tool guidance"
+ "[UserLocation] augmenter set userLocation (accuracy=%fm)"
+ "[UserLocation] augmenter: no user location on transcript"
+ "[UserLocation] createSystemResponse set userLocation (accuracy=%fm)"
+ "[UserLocation] createSystemResponse: no user location on transcript"
+ "[VI stage 1] renderLiveEntities: count=%ld ODM=%{bool}d"
+ "[handleCitation] Filtering internal IF entity for id=%s"
+ "[visualStatusUpdate] deferred: posting with keys: %s"
+ "[visualStatusUpdate] eager: posting with keys: %s"
+ "associatedRequestID"
+ "auto_present_results"
+ "baselineAIDisclaimer.variation.1"
+ "baselineAIDisclaimer.variation.2"
+ "baselineAIDisclaimer.variation.3"
+ "baselineAIDisclaimer.variation.4"
+ "baseline_ai_disclaimer"
+ "camera://configuration?capturemode=intelligence&capturedevice=back&issiricontinuation=1"
+ "com.apple.CameraOverlayAngel"
+ "com.apple.camera"
+ "com.apple.mobilecal.DeleteEventIntent"
+ "com.apple.mobilecal.UpdateEventIntent"
+ "com.apple.mobilenotes.DeleteNotesLinkAction"
+ "com.apple.mobilenotes.NoteAppendTextIntent"
+ "com.apple.mobilenotes.UpdateNoteIntent"
+ "com.apple.reminders.DeleteRemindersAppIntent"
+ "com.apple.reminders.UpdateReminderAppIntent"
+ "failed to donate passthrough AgentMediaEntity to entity service: %@"
+ "get_entity_details"
+ "imageRetrievalResponse"
+ "init(transcriptView:agentOutputPublisher:hydrationService:entityService:concurrencySafeToolExecutionSession:toolbox:plannerToolbox:defaultDateTimeContext:queryAugmentationServiceProvider:appSchemaResolver:contextPromptRenderer:agentFunctionCallUuid:templateContextAutoGenerateToolCall:toolboxInput:imageCaptureAndRetrievalService:deviceAuthenticationStateCalculator:userContext:userContextResolver:featureFlagProvider:preferencesProvider:annotations:outputGuardrail:provenanceRegistry:)"
+ "laundered-screenshot-"
+ "laundered-screenshot.jpg"
+ "no cached passthrough capture for requestID: %s; not staging"
+ "no entity service — passthrough AgentMediaEntity not donated; image will not reach model"
+ "no image capture request in the transcript; not staging passthrough"
+ "notes.UpdateNoteIntent"
+ "notifySpeechPartial: forwarding partial to gaze tracker, partialEndInstant=%f, wallClockFallback=%{bool}d"
+ "passthrough AgentMediaEntity donation error: %@"
+ "phone.StartCallIntent"
+ "requiresCanvasDisplay"
+ "requiresPersistence"
+ "resolvePassthroughFrameData using cached task for requestID: %s"
+ "standalone_answer"
+ "supplemental_material"
+ "transcriptTag snippetContent "
+ "ui_entity_rendering"
- " is out of range for "
- "%s %s:\nPCC network inference not preferred, passing to on-device: %s"
- "%s PCC network availability check passed — proceeding with PCC inference"
- "%s: CrossDeviceContextArrivalNotifier stream was empty, so trying to search for existing UserContext in transcript."
- "%s: Did not successfully find existing client context even in the transcript. Defaulting to using empty UserContext."
- "%s: PCC network availability indeterminate, proceeding optimistically with PCC"
- "Always verify important details. Siri is an AI that may make mistakes."
- "CVPixelBuffer to Data: Converted to Data successfully"
- "CVPixelBuffer to Data: Failed to create CGImage from CIImage."
- "CVPixelBuffer to Data: Failed to create image destination"
- "CVPixelBuffer to Data: Failed to create mutable data"
- "CVPixelBuffer to Data: Failed to finalize image destination"
- "CVPixelBuffer to Data: Failed to visualize gaze on CGImage."
- "CVPixelBuffer to Data: No gaze coordinates provided, skipping visualization."
- "CVPixelBuffer to Data: Visualized gaze location on CGImage."
- "Cannot post passthrough imageRetrievalResponse because lastImageCaptureRequest is %s and imageCaptureAndRetrievalService is %s"
- "DefaultPromptRenderingContext.fetchEditingContext"
- "Drawing point at %f, %f"
- "Entity donation error: %@"
- "Entity service couldn't be unwrapped"
- "Failed to build PassthroughCameraEntity"
- "Failed to register entity with planner tool context"
- "Network inference evaluation: preferred=%{bool}d, connectionOK=%{bool}d, rtt=%s"
- "No 'entities' parameter found in disambiguation action"
- "No disambiguation action found for disambiguation response"
- "TLCFE at identifier LOD; deferring image to get_entity_details path"
- "UserTurnStartedEvent not found for image retrieval"
- "[DefaultPromptRenderingContext] fetchEditingContext failed: %@"
- "[INSIGHTS_TIMELINE|PlannerServiceRun|PCC network unavailable on first turn|🏳️|]"
- "[SearchListSnippetTransform] Processing %ld item(s): [%s]"
- "[SessionSummarization] isFirstTaskInCurrentSession() unexpectedly called during translation"
- "[URLSecurity][%s] URLSecurityCheckError caught at PTE — rendering per-tool guidance"
- "[liveCameraFeed] AgentMediaStore upload failed: %@"
- "[liveCameraFeed] Snapshot stored in AgentMediaStore — cloudID=%{public}s"
- "[liveCameraFeed] snapshotFile data is empty; skipping AgentMediaStore upload"
- "com.apple.UIKitCore.RequestEditingContext"
- "com.apple.fm.service.lw.v1"
- "com.apple.mobilecal."
- "com.apple.mobilenotes."
- "com.apple.reminders."
- "failed to donate entity to entity service: %@"
- "getOrCreatePassthroughImageRetrievalResponse using cached task"
- "init(transcriptView:agentOutputPublisher:hydrationService:entityService:concurrencySafeToolExecutionSession:toolbox:plannerToolbox:defaultDateTimeContext:queryAugmentationServiceProvider:appSchemaResolver:contextPromptRenderer:agentFunctionCallUuid:templateContextAutoGenerateToolCall:toolboxInput:imageCaptureAndRetrievalService:deviceAuthenticationStateCalculator:userContext:featureFlagProvider:preferencesProvider:annotations:outputGuardrail:urlSecurityRegistry:)"
- "no cached passthrough image task for requestID: %s; not retrieving image"
- "no image capture request in the transcript; not retrieving image"
- "retrieveImageFromCaptureRequest passthrough reservedEntityID: %s"
- "retrieveSerializedCameraCalibrationData(entityId: %s): %s"
- "retrieveSerializedDevicePoseData(entityId: %s): %s"
- "targetWindowIdentifier"
```
