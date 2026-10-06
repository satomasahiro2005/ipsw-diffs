## IntelligenceFlowPlannerRuntime

> `/System/Library/PrivateFrameworks/IntelligenceFlowPlannerRuntime.framework/IntelligenceFlowPlannerRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x728164` | `0x741a10` | **`+0x198ac`** |
| `__TEXT.__eh_frame` | `0x3c724` | `0x3cda4` | **`+0x680`** |
| `__TEXT.__oslogstring` | `0x22fdc` | `0x2355c` | **`+0x580`** |
| `__TEXT.__cstring` | `0x15f0a` | `0x163ea` | **`+0x4e0`** |
| `__TEXT.__const` | `0x29120` | `0x29570` | **`+0x450`** |
| `__TEXT.__unwind_info` | `0x14ef0` | `0x15338` | **`+0x448`** |
| `__AUTH_CONST.__const` | `0x26d08` | `0x27100` | **`+0x3f8`** |
| `__AUTH.__data` | `0x4740` | `0x4aa8` | **`+0x368`** |
| `__TEXT.__swift5_reflstr` | `0xa683` | `0xa9c3` | **`+0x340`** |
| `__TEXT.__swift5_fieldmd` | `0xbda4` | `0xc03c` | **`+0x298`** |
| `__DATA.__data` | `0x5518` | `0x56d8` | **`+0x1c0`** |
| `__TEXT.__swift5_typeref` | `0xd488` | `0xd646` | **`+0x1be`** |
| `__AUTH_CONST.__auth_got` | `0xaeb0` | `0xb038` | **`+0x188`** |
| `__AUTH_CONST.__objc_const` | `0x8d18` | `0x8e90` | **`+0x178`** |
| `__TEXT.__constg_swiftt` | `0xb908` | `0xba4c` | **`+0x144`** |
| `__DATA_CONST.__got` | `0x52e8` | `0x53e8` | **`+0x100`** |
| `__TEXT.__swift_as_cont` | `0x2c08` | `0x2c60` | **`+0x58`** |
| `__DATA_DIRTY.__data` | `0xee60` | `0xee30` | **`-0x30`** |
| `__DATA.__common` | `0x189` | `0x1b1` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x770` | `0x790` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xb78` | `0xb98` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0xe38` | `0xe58` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x1098` | `0x10b8` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x1620` | `0x1638` | **`+0x18`** |
| `__DATA.__bss` | `0x25650` | `0x25660` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x7338` | `0x7328` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x430` | `0x438` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x18f8` | `0x18f4` | **`-0x4`** |
| `__TEXT.__swift5_protos` | `0x1d8` | `0x1d4` | **`-0x4`** |

### Other Changes

```diff

-3600.151.4.501.6
+3600.156.3.501.1

+  - /System/Library/Frameworks/DataDetection.framework/DataDetection

-  Functions: 33357
-  Symbols:   519
-  CStrings:  3646
+  Functions: 33697
+  Symbols:   527
+  CStrings:  3686
Symbols:
+ _CGImageSourceCopyPropertiesAtIndex
+ _IOSurfaceGetAllocSize
+ _IOSurfaceGetHeight
+ _IOSurfaceGetWidth
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_SFPerformIntentCommand
+ _kCGImagePropertyPixelHeight
+ _kCGImagePropertyPixelWidth
CStrings:
+ "\n<coverBlock imageID=\""
+ " If you ask a question, wrap it in <followUp> — it will be spoken so you must not duplicate the question outside the tag."
+ "\"kind\":\"AttachmentFileEntity\""
+ "%s %s insert_text implied by the invocation surface — skipping validation"
+ "%s: retrieved-tool trim — %ld → %ld tools"
+ "By the way, I'm an assistant powered by AI and may make mistakes. Always verify important details."
+ "CreateDraftMailTool"
+ "DeleteEventIntent"
+ "DeleteRemindersIntent"
+ "ForwardDraftMailTool"
+ "Keep in mind, I'm an assistant powered by AI and may make mistakes. Always verify important details."
+ "Native-Gemini-Custom-Routing"
+ "NoteAppendTextIntent"
+ "OpenAI-Compatible-Custom-Routing"
+ "PlannerRequestSecurityMetadata: Built classification cache with %ld entries, extracted %ld plain user requests from %ld events, currentRequestIsMultimodal=%{bool}d, isInsertTextImpliedInvocation=%{bool}d"
+ "ReplyDraftMailTool"
+ "SendDraftMailTool"
+ "SiriPCCAgentRouter was re-invoked with a terminal previousDecision; a sticky Pro route must be reused, not re-derived"
+ "Type identifier does not erase to custom: %s"
+ "Unrecognized cross-device payload"
+ "UpdateDraftMailTool"
+ "UpdateEventIntent"
+ "UpdateNoteIntent"
+ "[AgentSystemPrompt] Failed to load image content handling template: %{public}s"
+ "[AgentSystemPrompt][ImageDirective] Failed to render image content handling instruction: %{public}s"
+ "[AgentSystemPrompt][PlatformInstructions] Injected platform_base block"
+ "[AgentSystemPrompt][PlatformInstructions] Platform unchanged — not re-emitting"
+ "[INSIGHTS_TIMELINE|Security|Action Validation - Skipped (insert_text implied by surface)|🔒|⏭️]"
+ "[TOOL DESCRIPTION]"
+ "[TOOL] create_draft_email\n[TOOL DESCRIPTION] Creates and drafts email messages including new emails, replies, reply-all, and forwards. Handles recipients (to, CC, BCC), subject, body content, file attachments, and account selection. Works with Writing Tools to compose email body text. Supports responding to existing emails by ID with reply or forward actions."
+ "[TOOL] insert_text\n[TOOL DESCRIPTION] insert text, type text, paste text, enter text, input text, add text, write text, put text, text into message, text into field, type into app, paste into textbox, enter into input, insert into notes, type in safari, paste message, input field, text field, typing text, entering text, inserting text"
+ "[TOOL] save_parking_location\n[TOOL DESCRIPTION] Save the user's parking location with an optional note."
+ "[ThirdPartyProviderSession] Marked first Siri response following a third-party provider session"
+ "[URLSecurity] Streaming hold-back: match reaches buffer end (matchedURL=%{public}s)"
+ "[URLSecurity] Streaming hold-back: no whitespace after match (matchedURL=%{public}s tail=%{public}s)"
+ "[URLSecurity] Unauthorized URL in direct response — tagging as unsafe: url=%{public}s variants=%{public}s authorizedCount=%ld authorizedSample=%{public}s imageWasInContext=%{bool,public}d"
+ "[WKACitations] RESPONSETOOLSCitationsAttributed emitted: responseToolsId=%s, count=%ld"
+ "[WKACitations] RequestLink emitted: plannerID=%s to responseToolsId=%s"
+ "[handleCitation] Built photo entity card for id=%s"
+ "[handleCoverBlock] No glossary entity found for imageID=%s"
+ "[handleCoverBlock] No image sidecar data for imageID=%s"
+ "[handleCoverBlock] Resolved cover block for imageID=%s, snippetId=%s"
+ "[handleCoverBlock] Sidecar for imageID=%s has no imageUrl"
+ "[makeCitationCardSection] Failed to encode entity-open identifier for id=%{public}s, errorType: %{public}s"
+ "[on-device-routing] %{public}s: serving routed bundle %{public}s (%{public}s)"
+ "[on-device-routing] asset-warmer throwaway prewarm .default for %{public}s; real serving session left un-prewarmed"
+ "[on-device-routing] committed decide failed: %{public}s"
+ "[on-device-routing] failed to build asset-warmer for %{public}s: %{public}s"
+ "[on-device-routing] failed to create routable model %{public}s: %{public}s"
+ "[on-device-routing] judgeCurrentTranscript: no renderer seeded yet; skipping"
+ "[on-device-routing] plannerID=%{public}s change-boundary prewarm %{public}s urgency=imminent (reason=%{public}s terminal=%{bool,public}d)"
+ "[on-device-routing] plannerID=%{public}s participant-driven re-judge requiredModelBundle=%{public}s terminal=%{bool,public}d routeReason=%{public}s"
+ "[on-device-routing] plannerID=%{public}s terminal decision emptied the routable set: chosen %{public}s was not held"
+ "[on-device-routing] plannerID=%{public}s terminal decision: tore down deselected generator %{public}s (kept %{public}s)"
+ "[on-device-routing] prewarming planner bundle %{public}s kind=%{public}s routing=%{public}s"
+ "[on-device-routing] prewarming routable model %{public}s urgency=imminent (initial tier)"
+ "[on-device-routing] routable set=%{public}s (default=%{public}s) assetWarmers=%{public}ld"
+ "[on-device-routing] routing plugin installed (bundles=%{public}s, initialTier=%{public}s)"
+ "ambiguous_contact_relationships"
+ "buildStructuredResponse(toolName:responseMode:onScreenContext:siriContextInfo:localeSettings:spanMatchTemplateContext:userGender:requestDateTimeContext:currentDateTime:prerequestTemplateAdditionalInput:renderedConversationFragments:mode:)"
+ "com.apple.siri.attribution.openEntity"
+ "contacts.CreateContactIntent"
+ "crisis_tool"
+ "executing action after dismissal with location result StatementID: %s"
+ "findSpanMatch(query:traceId:spanMatchId:sessionID:siriRequestContext:)"
+ "get_tools_tool"
+ "header_x-goog-api-key"
+ "imageComponents(): failed to transform user prompt"
+ "imageID title subTitle parsedTag "
+ "imagePromptComponentValue(of:identifier:)"
+ "mail.ForwardMailIntent"
+ "mail.ReplyMailIntent"
+ "maps.MapsUpdateParkingLocationIntent"
+ "photosQueryAttributedString"
+ "photosSourceAppBundleIDs"
+ "queryDecorationCollection(qdInput:toolboxResources:qdLookback:toolExecutionSession:sessionId:isLinwoodCapable:)"
+ "uncached_delta_tool_call"
+ "uncached_delta_tool_definitions"
+ "uncached_delta_tool_result"
+ "uncached_delta_transcript_text"
+ "uncached_delta_user_query"
- " Key data points (e.g. for retrieval or list queries, name the items themselves) must appear inside <"
- ">. By calling ui_entity_rendering on entities with ui_entity_rendering_text_components you have already presented their data to the user — do not restate it after <"
- "Before you move on, always verify important details. I'm an AI that may make mistakes."
- "By the way, always verify important details. As an AI, I may make mistakes."
- "Oh, and just a quick note: always verify important details. As an AI, I may make mistakes."
- "One last thing, I'm an AI that may make mistakes, so always cross-check key information."
- "OpenAI-Compatible-Custom-Routing:"
- "PlannerRequestSecurityMetadata: Built classification cache with %ld entries, extracted %ld plain user requests from %ld events, currentRequestIsMultimodal=%{bool}d"
- "[AgentSystemPrompt][PlatformInstructions] Injected tool catalog appendix (fallback)"
- "[AgentSystemPrompt][PlatformInstructions] Injected tool catalog appendix via template"
- "[SiriRequestContextRenderer] Unrecognized responseMode — defaulting to Voice"
- "[TOOL] compose_writing_assistant\n[TOOL DESCRIPTION] Writing Tools: Composes, generates, or drafts new text content such as emails, messages, notes, or stories"
- "[URLSecurity] Streaming hold-back: match reaches buffer end (matchEnd=%{public}ld bufferLen=%{public}ld matchedURL=%{public}s)"
- "[URLSecurity] Streaming hold-back: no whitespace after match (matchEnd=%{public}ld bufferLen=%{public}ld matchedURL=%{public}s tail=%{public}s)"
- "[URLSecurity] Unauthorized URL in direct response: url=%{public}s variants=%{public}s authorizedCount=%ld authorizedSample=%{public}s imageWasInContext=%{bool,public}d"
- "[on-device-routing] %{public}s: failed to prewarm routable model %{public}s: %{public}s"
- "[on-device-routing] %{public}s: prewarmed extra routable models=%{public}s (default=%{public}s)"
- "[on-device-routing] %{public}s: prewarming routable model %{public}s urgency=%{public}s"
- "[on-device-routing] %{public}s: routing plugin installed (bundles=%{public}s)"
- "[on-device-routing] %{public}s: serving routed bundle %{public}s (reason=%{public}s terminal=%{bool,public}d)"
- "[on-device-routing] plannerID=%{public}s step=%{public}ld requiredModelBundle=%{public}s terminal=%{bool,public}d routeReason=%{public}s"
- "[on-device-routing] plannerID=%{public}s step=%{public}ld routing failed: %{public}s"
- "[on-device-routing] plannerID=%{public}s terminal decision: no deselected generators to tear down (chosen=%{public}s)"
- "[on-device-routing] plannerID=%{public}s terminal decision: tore down deselected generators bundles=[%{public}s] (kept %{public}s)"
- "[on-device-routing] prewarming planner bundle %{public}s urgency=%{public}s routing=%{public}s"
- "baselineAIDisclaimer.variation.3"
- "baselineAIDisclaimer.variation.4"
- "buildStructuredResponse(toolName:responseMode:onScreenContext:siriContextInfo:localeSettings:spanMatchTemplateContext:userGender:voiceGender:requestDateTimeContext:currentDateTime:prerequestTemplateAdditionalInput:renderedConversationFragments:mode:)"
- "com.apple.MobileAddressBook.CreateContactIntent"
- "com.apple.mobilecal.DeleteEventIntent"
- "com.apple.mobilecal.UpdateEventIntent"
- "com.apple.mobilenotes.DeleteNotesLinkAction"
- "com.apple.mobilenotes.NoteAppendTextIntent"
- "com.apple.mobilenotes.UpdateNoteIntent"
- "com.apple.reminders.DeleteRemindersAppIntent"
- "com.apple.reminders.UpdateReminderAppIntent"
- "findSpanMatch(query:traceId:spanMatchId:)"
- "imagePromptComponentValue(of:)"
- "invocation source is context menu; using context menu image source"
- "queryDecorationCollection(qdInput:toolboxResources:qdLookback:toolExecutionSession:sessionId:)"
- "voiceGender"
```
