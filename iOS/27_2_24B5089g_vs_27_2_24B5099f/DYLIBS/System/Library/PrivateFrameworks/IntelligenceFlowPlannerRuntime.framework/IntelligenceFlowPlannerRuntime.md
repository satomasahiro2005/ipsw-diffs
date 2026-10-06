## IntelligenceFlowPlannerRuntime

> `/System/Library/PrivateFrameworks/IntelligenceFlowPlannerRuntime.framework/IntelligenceFlowPlannerRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x781054` | `0x7a21f4` | **`+0x211a0`** |
| `__TEXT.__eh_frame` | `0x3f2f8` | `0x405d0` | **`+0x12d8`** |
| `__TEXT.__unwind_info` | `0x163d8` | `0x17550` | **`+0x1178`** |
| `__AUTH_CONST.__const` | `0x26e48` | `0x27558` | **`+0x710`** |
| `__TEXT.__oslogstring` | `0x2374c` | `0x23d8c` | **`+0x640`** |
| `__TEXT.__const` | `0x2a580` | `0x2a840` | **`+0x2c0`** |
| `__TEXT.__cstring` | `0x178ba` | `0x17b2a` | **`+0x270`** |
| `__TEXT.__swift5_capture` | `0x6dcc` | `0x7004` | **`+0x238`** |
| `__AUTH_CONST.__auth_got` | `0xb640` | `0xb860` | **`+0x220`** |
| `__DATA_CONST.__got` | `0x5358` | `0x54a0` | **`+0x148`** |
| `__DATA.__bss` | `0x25050` | `0x25180` | **`+0x130`** |
| `__TEXT.__swift5_typeref` | `0xd9f8` | `0xdb1e` | **`+0x126`** |
| `__AUTH.__data` | `0x4640` | `0x4760` | **`+0x120`** |
| `__DATA.__data` | `0x5290` | `0x5388` | **`+0xf8`** |
| `__TEXT.__swift_as_cont` | `0x2e78` | `0x2f6c` | **`+0xf4`** |
| `__TEXT.__constg_swiftt` | `0xbedc` | `0xbfa4` | **`+0xc8`** |
| `__TEXT.__swift5_reflstr` | `0xae33` | `0xaef3` | **`+0xc0`** |
| `__TEXT.__swift_as_ret` | `0x178c` | `0x1834` | **`+0xa8`** |
| `__TEXT.__swift5_fieldmd` | `0xc570` | `0xc614` | **`+0xa4`** |
| `__AUTH_CONST.__objc_const` | `0x9618` | `0x96a8` | **`+0x90`** |
| `__TEXT.__swift_as_entry` | `0x1178` | `0x11c8` | **`+0x50`** |
| `__DATA_DIRTY.__data` | `0x10268` | `0x10220` | **`-0x48`** |
| `__DATA_CONST.__const` | `0x7b8` | `0x7c8` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xebc` | `0xecc` | **`+0x10`** |
| `__DATA.__common` | `0x129` | `0x131` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x478` | `0x480` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x196c` | `0x1974` | **`+0x8`** |

### Other Changes

```diff

-3605.16.9.501.1
+3605.21.1.501.4

-  Functions: 34682
-  Symbols:   478
-  CStrings:  3770
+  Functions: 35183
+  Symbols:   479
+  CStrings:  3801
Symbols:
+ _NSMultipleUnderlyingErrorsKey
CStrings:
+ " Key data points (e.g. for retrieval or list queries, name the items themselves) must appear in the prose or via ui_entity_rendering for entities that have ui_entity_rendering_text_components, or associated renderable entities of web search results — by calling ui_entity_rendering on those entities you have already presented their data to the user, do not restate it in either <"
+ " Questions go in <followUp>, never the response body. When asking the user to choose among candidate entities, use ask_user_to_pick with them instead, as <followUp> cannot present them."
+ "# Tool Catalog Appendix"
+ "## First check\nIf the request is not aimed at you, call `mitigate` and stop.\nNever call `mitigate` if the user is addressing Siri by name.\nTalking about Siri is not addressing Siri."
+ "%s %ld consecutive guardrail violations reached limit of %ld, locking conversation"
+ "%s %ld/%ld consecutive violations, replacing response"
+ "%s Failed to post SafetyIncident: %@"
+ "%s: AgenticPlannerService: fuzzy match found a non-schematized shortcut, but shortcuts can't run on the originating device; declining"
+ "%s: Failed to post selected contextual mitigation before streaming lockout: %@"
+ "%s: In-app search capability query failed, offering search_in_app anyway: %{sensitive}@"
+ "%s: Output content safety rejected by PCC — replacing response"
+ "%s: Skipping search_in_app — no span-matched app supports in-app search: %{public}s"
+ "%s: [RateLimit] kind: %{public}s, pccCode: %{public}s, retryAfter: %{public}s, retryable: %{bool,public}d"
+ "%s: failed to post rate-limit ExecutionError: %@"
+ "%s: finalApprovalWithOverride failed during %s: %@"
+ "%s: finalApprovalWithOverride failed during output safety rejection: %@"
+ "%s: finalApprovalWithSubstitution failed during %s: %@"
+ "%s: insert_text unavailable for this device idiom — suppressing writing instructions"
+ "%{public}s isPassiveCameraEnabled=%{bool,public}d"
+ "%{public}s isTypeToSiri=%{bool,public}d"
+ ": [PCCOutputGuardrail]"
+ "<elided: budget exhausted>"
+ "<expanded below as an underlying node>"
+ "<field depth cap>"
+ ">. By calling ui_entity_rendering on entities with ui_entity_rendering_text_components, or associated renderable entities of web search results you have already presented their data to the user — do not restate it after <"
+ "GMS output stream failed with PCC privacy-proxy error: %@"
+ "Missing dialog resources for %{public}s"
+ "OutputGuardrailLazyModelLoad"
+ "PrivateCloudComputeError"
+ "SpeculativeExecution: Retry path - refinement modified output, abandoning speculative work and retrying"
+ "ToolSequenceSafetyValidator: %s threshold reached — count=%ld, threshold=%ld (transcript: %ld, persisted: %ld)"
+ "[CloudGuardrail] sending %{public}s"
+ "[ForegroundAppSource] Client foreground app %s matched candidates %s"
+ "[ForegroundAppSource] Client reported no foreground app"
+ "[ForegroundAppSource] Local device foreground apps %s"
+ "[MarkdownResponseStreamConsumer]"
+ "[OutputGuardrailLockout] No dialog generated for guardrail replacement"
+ "[PCCPrivacyProxy] underlying error chain deeper than %ld, giving up"
+ "[SanitizerGuardrailModel] Initialized, prewarm deferred to first use (useCaseIdentifier: %s)"
+ "[UnclassifiedInferenceError] hierarchy:\n%{public}s"
+ "[handleCitation] Withholding pill for id=%s; no attributable source for '%{public}s'"
+ "localizedDescription"
+ "mangledSwiftTypeName"
+ "on_screen_context"
+ "recitation rejection"
+ "resuming flow tool after dismissal StatementID: %s"
- " If you ask a question, wrap it in <followUp> — it will be spoken so you must not duplicate the question outside the tag."
- " Key data points (e.g. for retrieval or list queries, name the items themselves) must appear in the prose or via ui_entity_rendering for entities that have ui_entity_rendering_text_components — by calling ui_entity_rendering on those entities you have already presented their data to the user, do not restate it in either <"
- "# Tool Catalog Appendix\n\n"
- "## First check\nIf the user is not making a clear request/question, call `mitigate` and stop"
- "%s: finalApprovalWithOverride failed during recitation rejection: %@"
- ">. By calling ui_entity_rendering on entities with ui_entity_rendering_text_components you have already presented their data to the user — do not restate it after <"
- "Missing .actionNotAllowed dialog resources"
- "SpeculativeExecution: Retry path - refinement modified output, cancelling speculative work and retrying"
- "ToolSequenceSafetyValidator: %s threshold reached — count=%ld, threshold=%ld (persisted: %ld)"
- "[MarkdownResponseStreamConsumer] %ld consecutive guardrail violations reached limit of %ld, locking conversation"
- "[MarkdownResponseStreamConsumer] %ld/%ld consecutive violations, replacing response"
- "[MarkdownResponseStreamConsumer] Failed to post SafetyIncident: %@"
- "[MarkdownResponseStreamConsumer] No dialog generated for guardrail replacement"
- "[handleCitation] No displayName for entity citation id=%s"
- "forceReduceSensitiveContent"
```
