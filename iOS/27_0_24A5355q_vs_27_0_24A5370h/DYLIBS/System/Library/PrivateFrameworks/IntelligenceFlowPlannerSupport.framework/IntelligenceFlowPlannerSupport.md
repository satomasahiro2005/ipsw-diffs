## IntelligenceFlowPlannerSupport

> `/System/Library/PrivateFrameworks/IntelligenceFlowPlannerSupport.framework/IntelligenceFlowPlannerSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe1ee44` | `0xe6d464` | **`+0x4e620`** |
| `__DATA.__bss` | `0x11ca08` | `0x121238` | **`+0x4830`** |
| `__AUTH_CONST.__const` | `0x79e48` | `0x7d970` | **`+0x3b28`** |
| `__TEXT.__const` | `0xb9738` | `0xbba78` | **`+0x2340`** |
| `__DATA_DIRTY.__bss` | `0x35800` | `0x34500` | **`-0x1300`** |
| `__AUTH.__data` | `0x16668` | `0x17848` | **`+0x11e0`** |
| `__TEXT.__eh_frame` | `0xa4bd0` | `0xa5ab0` | **`+0xee0`** |
| `__AUTH_CONST.__auth_got` | `0x152f8` | `0x16138` | **`+0xe40`** |
| `__TEXT.__swift5_typeref` | `0x23b18` | `0x24914` | **`+0xdfc`** |
| `__DATA.__data` | `0x17d80` | `0x18970` | **`+0xbf0`** |
| `__DATA_DIRTY.__data` | `0x1b308` | `0x1a718` | **`-0xbf0`** |
| `__TEXT.__oslogstring` | `0x1f3b9` | `0x1feb9` | **`+0xb00`** |
| `__TEXT.__swift5_capture` | `0xa444` | `0xad8c` | **`+0x948`** |
| `__TEXT.__cstring` | `0x25e6f` | `0x2665f` | **`+0x7f0`** |
| `__TEXT.__swift5_fieldmd` | `0x20834` | `0x20f9c` | **`+0x768`** |
| `__TEXT.__swift5_reflstr` | `0x10073` | `0x107d6` | **`+0x763`** |
| `__TEXT.__swift5_assocty` | `0xb6f0` | `0xbd98` | **`+0x6a8`** |
| `__TEXT.__unwind_info` | `0x3e998` | `0x3efa8` | **`+0x610`** |
| `__AUTH_CONST.__objc_const` | `0x7080` | `0x6b10` | **`-0x570`** |
| `__TEXT.__swift5_proto` | `0xcb04` | `0xce60` | **`+0x35c`** |
| `__TEXT.__constg_swiftt` | `0x1c15c` | `0x1c2e8` | **`+0x18c`** |
| `__TEXT.__swift_as_entry` | `0x3908` | `0x37cc` | **`-0x13c`** |
| `__TEXT.__swift_as_ret` | `0x4d1c` | `0x4c14` | **`-0x108`** |
| `__TEXT.__swift_as_cont` | `0x6380` | `0x62c4` | **`-0xbc`** |
| `__DATA_CONST.__objc_classlist` | `0x578` | `0x508` | **`-0x70`** |
| `__TEXT.__swift5_types` | `0x2dfc` | `0x2e60` | **`+0x64`** |
| `__DATA_CONST.__objc_selrefs` | `0xc98` | `0xcf0` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x2d0` | `0x310` | **`+0x40`** |
| `__DATA.__common` | `0x400` | `0x438` | **`+0x38`** |
| `__DATA_CONST.__const` | `0xcd8` | `0xca8` | **`-0x30`** |
| `__DATA_CONST.__objc_protolist` | `0xa0` | `0xc0` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x50` | `0x60` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x1bc` | `0x1c4` | **`+0x8`** |

### Other Changes

```diff

-3600.138.6.501.17
+3600.144.5.501.3

+  - /System/Library/Frameworks/FileProvider.framework/FileProvider

+  - /System/Library/PrivateFrameworks/EntityService.framework/EntityService
+  - /System/Library/PrivateFrameworks/Espresso.framework/Espresso

-  Functions: 92955
-  Symbols:   508
-  CStrings:  5038
+  Functions: 94460
+  Symbols:   535
+  CStrings:  5119
Symbols:
+ _CLLocationCoordinate2DIsValid
+ _NSFileProviderDomainDefaultIdentifier
+ _OBJC_CLASS_$_CSSearchableIndex
+ _OBJC_CLASS_$_FPItemID
+ _OBJC_CLASS_$_FPItemManager
+ _OBJC_CLASS_$_MLArrayBatchProvider
+ _OBJC_CLASS_$_MLPredictionOptions
+ _OBJC_CLASS_$_PLANNERSchemaPLANNERContextPredictorFalseNegativeDetected
+ _OBJC_CLASS_$_PLANNERTOOLSSchemaPLANNERTOOLSEntityHydrationInfo
+ __CFURLCopySecurityScopeFromFileURL
+ _e5rt_buffer_object_create_from_data_pointer
+ _e5rt_buffer_object_release
+ _e5rt_execution_stream_create
+ _e5rt_execution_stream_encode_operation
+ _e5rt_execution_stream_execute_sync
+ _e5rt_execution_stream_operation_create_precompiled_compute_operation_with_options
+ _e5rt_execution_stream_operation_prepare_op_for_encode
+ _e5rt_execution_stream_operation_release
+ _e5rt_execution_stream_operation_retain_input_port
+ _e5rt_execution_stream_operation_retain_output_port
+ _e5rt_execution_stream_release
+ _e5rt_execution_stream_reset
+ _e5rt_get_last_error_message
+ _e5rt_io_port_bind_buffer_object
+ _e5rt_io_port_release
+ _e5rt_precompiled_compute_op_create_options_create
+ _e5rt_precompiled_compute_op_create_options_release
+ _e5rt_precompiled_compute_op_create_options_set_allocate_intermediate_buffers
+ _objc_retain_x10
- _OBJC_CLASS_$_LSApplicationWorkspace
- _swift_release_x10
CStrings:
+ " to check if the user wants to hear the content of the notification entity, no need to call prepare_notifications."
+ "\"kind\":\"CalendarEntity\""
+ "\"level_of_detail\":\"full\""
+ "# The user pointed their camera at something and wants the assistant to respond with information about what they see.\nThe user's message includes an image showing what they are looking at in the real world. Do not ask questions.\n- Focus on the main subject. If no single subject stands out, cover multiple subjects or give a brief scene overview.\n- Two sentences max, under 400 characters. One idea per sentence; omit the second if it adds nothing useful.\n- Name the subject in the first sentence; **bold** subject names and creators. Use the most specific accurate name (the venue, not the complex; the sub-brand, not the parent).\n- Open with the subject as the grammatical subject of the sentence; don't preface with \"This is…\" or \"You're looking at…\".\n- Surface non-obvious details — historical context, specs, provenance — not what the eye already sees. The user is at the location; don't describe where they are.\n- Prefer accuracy over specificity. State answers directly; when confidence is low, step up to a broader category rather than hedging or guessing a brand or model.\n- No nutrition info, no marketing language, no advice. Don't mention the attachment type.\n- Puzzles: give a hint. Simple math: answer only.\n- If the subject is sensitive (health/medical, politically incendiary, provocatively religious) or unidentifiable, respond with: \"What would you like to know?\" and follow user instructions"
+ "%s: ToolKitCache re-warmed entries for containers %s:\n  toolCache: %ld key(s) and %ld value(s) total\n  typeCache: %ld key(s) and %ld value(s) total\n  systemToolProtocolCache: %ld key(s) modified, and %ld value(s) total\n  systemTypeProtocolCache: %ld key(s) modified, and %ld value(s) total\n  containerCache: %ld key(s) and %ld value(s) total"
+ "%{public}s Embedding batch output missing encodings at index %{public}ld for input of length %{public}ld"
+ "%{public}s Embedding batch result at index %{public}ld has unexpected shape %{public}s or dataType %{public}ld for input of length %{public}ld"
+ "%{public}s Embedding batch returned %{public}ld results for %{public}ld inputs"
+ "' for attendee_ids; expected ContactEntity or an IntentPerson-exportable entity"
+ "' was flagged by safety check"
+ ", allowsEagerUnlock: "
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/IntelligenceFlowSupport/IntelligenceFlowPlannerSupport/EntityMatcher/Matchers/FunBenchAirInstalledAppsMatcher.swift"
+ "App doesn't support liking/disliking content"
+ "Audio.UpdateAudioAffinity#call caught %@ - %s doesn't support updating affinity"
+ "Audio.UpdateAudioAffinity#call caught %@, rethrowing..."
+ "CONTENT RESTRICTION: This result is subject to a legal content restriction and must not be summarized, paraphrased, or answered. Do not generate any response about this topic from your own knowledge. You must immediately decline this request to the user."
+ "Companion mode: Watch-attributed UserNotificationEntity arriving on iPhone — identifier=%{public}s"
+ "Computation.MathCalculation render: searchAndResolveResult has no query results"
+ "Computation.MathCalculation: Agent handoff returned no result for '%{sensitive}s'"
+ "Computation.MathCalculation: Search agent invocation failed for '%{sensitive}s': %@"
+ "Context Predictor Model: %{public}s failed (code=%u): %{private}s"
+ "Context Predictor Model: input length mismatch"
+ "Context Predictor Model: no precompiled .mlmodelc found for language '%s'"
+ "Context Predictor Model: stream reset warning (code=%u)"
+ "Curated trim — dropping extra %{public}s entry (limit %{public}ld reached)"
+ "Curated trim — no toolbox available, skipping"
+ "Dropping OTA Enigma asset for %{public}s — embedded is_custom_install=true"
+ "Dropping OTA Enigma asset for %{public}s — major mismatch (OTA=%{public}s, embedded=%{public}s)"
+ "ETA distance measurement unit class: %{public}s symbol: %{public}s"
+ "ETA distance unit %{public}s (symbol: %{public}s) not a UnitLength and symbol not recognized; falling back to meters"
+ "EnigmaRegexMatcher: evicted %{public}ld compiled regexes (%{public}s)"
+ "Failed resolution, falling back to direct url. Error type: %s, code: %ld"
+ "Failed to create PLANNERContextPredictorFalseNegativeDetected"
+ "Hydration failed for %{public}s: %@. Falling back to originalEntity."
+ "Hydration returned non-entity for %{public}s; falling back to originalEntity"
+ "If a notification is long, introduce the app name and use "
+ "Link transport to companion is not yet available"
+ "LiveServiceEntity"
+ "ModelCache evicting all models: %{public}s"
+ "No fields were processed"
+ "Notifications.PrepareNotifications: all hydrated notifications were partially hydrated (stale Spotlight index entries)"
+ "Notifications.PrepareNotifications: dropping partially hydrated notification %{public}s"
+ "Notifications.PrepareNotifications: entity did not match companion-mode conditions — bundleId=%{public}s typeName=%{public}s"
+ "Notifications.PrepareNotifications: skipping non-UserNotificationEntity — bundleId=%{public}s typeName=%{public}s"
+ "PLANNERContextPredictorFalseNegativeDetected event created: prediction=%s, tool=%s"
+ "PLANNERSchemaPLANNERClientEvent (PLANNERContextPredictorFalseNegativeDetected) emitted to SELF"
+ "Phone.MakeCall: Group call — overriding to FaceTime bundle (isGroupConversationCall=%{bool}d, destinations.count=%ld)"
+ "PlannerToolMetadataStore: evicting metadata cache (%{public}s)"
+ "Play.Play@%s Overriding app parameter with counterpart bundleId: %s"
+ "Processing file at: %{sensitive}s"
+ "RemoteAgentInvocationResultPayload.V1.payload"
+ "RemoteAgentPrimitiveAction.primitiveAction"
+ "RemoteDialogTypeTool"
+ "RemoteRecommendedAction.recommendation"
+ "RemoteSearchAgentCallReturn.actionEventID (invalid UUID)"
+ "RemoteSearchAgentCallReturn.callActionEventID (invalid UUID)"
+ "RemoteSearchAndResolveResultConversionError.unsupportedRecommendation("
+ "RemoteSearchResultSnippetType"
+ "RemoteSearchResultSource.source"
+ "Rendering place entity with neither commonName nor address (coordinates-only, full rendering)"
+ "Rendering place entity with neither name/commonName nor address (coordinates-only)"
+ "Search-LoD upfront prefetch ("
+ "SecureURLResolver error fetching itemID: type=%s, code=%ld"
+ "SecureURLResolver fetchURL: %{sensitive}s from uniqueIdentifier: %{sensitive}s, no sandboxExtension."
+ "SecureURLResolver fetchURL: %{sensitive}s from uniqueIdentifier: %{sensitive}s, sandboxExtension = %{sensitive}s)"
+ "SecureURLResolver retrieved itemID, hasID=%{bool}d from uniqueIdentifier length=%ld"
+ "SecureURLResolver retrieved itemID: %{sensitive}s from uniqueIdentifier: %{sensitive}s"
+ "Text content for field '"
+ "The exact coordinate in the image where the user is currently gazing."
+ "The virtual content entity the user is currently focused on in the scene."
+ "VersionedTranscriptProtoGeneratedSnippetResponse.Storage version"
+ "VersionedTranscriptProtoRemoteAgentCallAction.Storage version"
+ "VersionedTranscriptProtoRemoteAgentInvocationRequest.Storage version"
+ "VersionedTranscriptProtoRemoteAgentInvocationResult.Storage version"
+ "VersionedTranscriptProtoRemoteAgentInvocationResultPayload.Storage version"
+ "VersionedTranscriptProtoRemoteAgentPrimitiveAction.Storage version"
+ "VersionedTranscriptProtoRemoteCandidateEntity.Storage version"
+ "VersionedTranscriptProtoRemoteConfirmationResolution.Storage version"
+ "VersionedTranscriptProtoRemoteDisambiguation.Storage version"
+ "VersionedTranscriptProtoRemoteExternalAgentDialogOutcome.Storage version"
+ "VersionedTranscriptProtoRemoteExternalAgentOutcome.Storage version"
+ "VersionedTranscriptProtoRemoteRecommendedAction.Storage version"
+ "VersionedTranscriptProtoRemoteResolveResult.Storage version"
+ "VersionedTranscriptProtoRemoteResolvedResolution.Storage version"
+ "VersionedTranscriptProtoRemoteSearchAgentCallReturn.Storage version"
+ "VersionedTranscriptProtoRemoteSearchAndResolveResult.Storage version"
+ "VersionedTranscriptProtoRemoteSearchEntry.Storage version"
+ "VersionedTranscriptProtoRemoteSearchResultSource.Storage version"
+ "VersionedTranscriptProtoRemoteSingleQueryResult.Storage version"
+ "VersionedTranscriptProtoRemoteToolConstraint.Storage version"
+ "VersionedTranscriptProtoSystemTurnCanceled.Storage version"
+ "WarmupAudioQueueResult"
+ "Writing Tools review UI can only target a single focused field — pass one entry per call, or set show_review_ui: false on each entry to insert without review."
+ "[Calendar.extractPerson]: Entity type '%s' is not ContactEntity, not IntentPerson-exportable, and has no 'person: PersonValue' property"
+ "[Calendar.extractPerson]: Passing IntentPerson-exportable entity '%s' through to Executor"
+ "[Calendar.extractPerson]: Passing IntentPerson-exportable entityIdentifier '%s' through to Executor"
+ "[Calendar.extractPerson]: Primitive Person"
+ "[Calendar.extractPerson]: Successfully extracted person from ContactEntity"
+ "[Calendar.extractPerson]: Unwrapped 'person' property from wrapper entity '%s'"
+ "[FileDerivativeHelper] FDS error: domain=%s code=%ld"
+ "[FileDerivativeHelper] didStartAccessing=%{bool}d for: %{sensitive}s"
+ "[FileDerivativeHelper] error reading url resources values. error: %{sensitive}@"
+ "[FileDerivativeHelper] extraction completed. url: %{sensitive}s secure: %{bool}d length: %ld"
+ "[FileDerivativeHelper] folder: %{sensitive}s [no content]"
+ "[FileDerivativeHelper] symlinks are not supported for text extraction: url: %{sensitive}s"
+ "[Find Tool Result Rendering] Failed to load agent instructions metadata: %@"
+ "[Find Tool Result Rendering] Template '%s' not found for locale %s"
+ "[InsertText] Output guardrail violation for entity_id=%{public}s, rejecting insert"
+ "[InsertText] call fieldCount=%{public}ld"
+ "[KNOWN_LIMITATION] SiriX mini tools do not work reliably in ifrunner. The SiriX daemon stack is not fully available in standalone mode, so results may be missing, incorrect, or the tool may fail entirely. Tool: SafariReadPage"
+ "[PostRenderCE] (%ld additional results filtered by cross-encoder)"
+ "[PostRenderCE] CE version unknown, using default threshold"
+ "[PostRenderCE] CE version=1.2.0 using v120 threshold"
+ "[PostRenderCE] CE version=1.3.0 using v130 threshold"
+ "[PostRenderCE] failed to query CE version: %@, using default threshold"
+ "[Search Rendering] results empty, falling back to deprecated entityResolutions (%ld resolutions)"
+ "[Search-LoD] Prefetch budget: %s (deadline-now=%s, renderReserve=%ldms) for %ld entities at %s LoD"
+ "[Search-LoD] Prefetch completed in %s (%ld/%ld hydrated)"
+ "[Search-LoD] Prefetch hit budget (%s) after %s. Abandoning; render fallback will serve from donation cache."
+ "[Search-LoD] Prefetch skipped: budget exhausted (remaining=%s, renderReserve=%ldms). Returning unhydrated; render fallback will serve from donation cache."
+ "[Search-LoD] Prefetch threw unexpectedly after %s: %@. Returning unhydrated."
+ "[Search-LoD] Prefetch unbounded (no deadline) for %ld entities at %s LoD"
+ "[SearchResultFileEntityRendering] file derivative error type: %s, code: %ld"
+ "[SearchResultFileEntityRendering] got secure url = %{bool}d"
+ "[SearchResultFileEntityRendering] successfully extracted text content from file at: %{sensitive}s"
+ "[VI stage 2] get_entity_details called: %ld entity/entities requested, level=%s"
+ "[WKASafetyAction] Safety action signal for sub-query '%s', appending error to global_entities"
+ "[attribute] Called with targetBundleId=%s, count=%ld, deviceIDSId=%s"
+ "[attribute] Containers lookup failed for bundleId=%s: %@"
+ "[attribute] No matching container found for bundleId=%s, deviceIDSId=%s"
+ "[attribute] Skipped: siriCompanion flag disabled"
+ "[renderLocalEntityValues] Applicable entity type ID: %s"
+ "_parentSfCardData"
+ "`update` requires at least one of: `content`, `name`, `attachments`, `is_pinned`, or `folder_id`."
+ "allowsEagerUnlock"
+ "appSearchResults"
+ "buffer_object_create '"
+ "callActionEventId"
+ "com.apple.Carousel"
+ "com.apple.Music"
+ "com.apple.NanoBooks"
+ "com.apple.NanoMusic"
+ "com.apple.NanoReminders"
+ "com.apple.SiriApp"
+ "com.apple.TVMusic"
+ "com.apple.iBooks"
+ "com.apple.nanomusicrecognition"
+ "com.apple.reminders"
+ "coreSpotlight"
+ "destinationAgentId"
+ "dictionaryRepresentation"
+ "direct"
+ "disableBus"
+ "disableFerry"
+ "disableSubway"
+ "disableTrain"
+ "emit(eventType:contextConfiguration:trId:timestamp:isolatedStreamUUID:emitter:)"
+ "encode_operation"
+ "entity sourceBundleId "
+ "entityRecommendation"
+ "entityRecommendationReasoning"
+ "executePlayTrailer(context:mediaEntity:bundleId:)"
+ "executePlayVideoContent(context:mediaEntity:bundleId:route:)"
+ "executeVideoPlayAction(isTrailer:context:entity:route:)"
+ "execution_stream_create"
+ "execution_stream_operation_create"
+ "fetchFileProviderURL()"
+ "fields array must not be empty"
+ "fileProvider"
+ "fileProviderDomainIdentifier"
+ "fileUniqueIdentifier"
+ "high"
+ "image_read_aloud"
+ "isRemoteRequest(localDeviceIDSIdentifier:)"
+ "isRemoteTVOSRequest(localDeviceIDSIdentifier:)"
+ "linkTransportUnavailable"
+ "low"
+ "matchEntitySpans(query:)"
+ "medium"
+ "model.specialization.bundle"
+ "noRecommendation"
+ "notAvailableInGuestUserMode"
+ "plannerTool.globalSearch.wkaSafetyActionDecline"
+ "prepare_op_for_encode"
+ "preserved_ranges"
+ "privacyTagNotification"
+ "privacyTagNotification("
+ "provideURLFromCoreSpotlight()"
+ "resolution_guidance"
+ "safari_read_page"
+ "set_allocate_intermediate_buffers"
+ "total_interactions"
+ "ui_entity_rendering_text_components"
+ "value identifier "
+ "visual entity identifier appended, ID=%s, passthrough=%{bool}d"
+ "warmEntries(forContainers:toolbox:locale:)"
+ "willPassThroughDialog"
- " additional results filtered by cross-encoder)"
- " additional results truncated)"
- " to check if the user wants to hear it before reading, let them know the app name."
- "# The user pointed their camera at something and wants the assistant to respond with information about what they see.\nThe user's message includes an image showing what they are looking at in the real world. Do not ask questions.\n- Focus on the main subject. If no single subject stands out, cover multiple subjects or give a brief scene overview.\n- Two sentences max, under 400 characters. One idea per sentence; omit the second if it adds nothing useful.\n- Name the subject in the first sentence; **bold** subject names and creators. Use the most specific accurate name (the venue, not the complex; the sub-brand, not the parent).\n- Open with the subject as the grammatical subject of the sentence; don't preface with \"This is…\" or \"You're looking at…\".\n- Surface non-obvious details — historical context, specs, provenance — not what the eye already sees. The user is at the location; don't describe where they are.\n- Prefer accuracy over specificity. State answers directly; when confidence is low, step up to a broader category rather than hedging or guessing a brand or model.\n- No nutrition info, no marketing language, no advice. Don't mention the attachment type.\n- Puzzles: give a hint. Simple math: answer only.\n- If the subject is sensitive (health/medical, politically incendiary, provocatively religious) or unidentifiable, respond only: \"What would you like to know?\""
- "%s: Skipping reply prompt for announce use case"
- "%s: ToolKitCache re-warmed entries for container %s:\n  toolCache: %ld key(s) and %ld value(s) total\n  typeCache: %ld key(s) and %ld value(s) total\n  systemToolProtocolCache: %ld key(s) modified, and %ld value(s) total\n  systemTypeProtocolCache: %ld key(s) modified, and %ld value(s) total\n  containerCache: %ld key(s) and %ld value(s) total"
- "' for attendee_ids, expected ContactEntity"
- ") exceeds limit ("
- "ALWAYS retrieve gaze when the user's query contains ambiguous references like 'this', 'that', 'it', 'these', or 'the one' that refer to something visible in the image (not to prior conversation context) and the image contains multiple possible referents. Retrieve gaze INSTEAD of asking the user to disambiguate."
- "ALWAYS retrieve when the user's query involves an action on a specific entity and there are multiple virtual content entities of the same kind visible on screen — e.g., 'open this', 'play that', 'select this one'. Use the gazed-at entity to disambiguate INSTEAD of asking the user to clarify which one they mean."
- "Computation.MathCalculation: Search agent call failed for '%s': %@"
- "Context Predictor Model: asset found at '%s' but no .mlmodelc or .mlpackage present"
- "Context Predictor Model: compiling from '%s'"
- "Context Predictor Model: no asset found for language '%s' and no saved model available — ensure model is sideloaded at ~/Library/Application Support/IntelligenceFlow/generic/context_predictor/context_filter.mlpackage"
- "Context Predictor output missing 'out' feature"
- "Context Predictor: Deleting precompiled model at %s"
- "Context Predictor: Saving precompiled model at %s"
- "Context Predictor: Using the precompiled model at %s"
- "ContextPredictorCompiledModel"
- "Error: bbox must have exactly 4 elements"
- "Error: could not resolve entity"
- "Failed to embed \"%s\". Received embedding shaped: %s and data type: %ld, which are unexpected."
- "Failed to hydrate stopwatch entity, using original: %@"
- "Failed to insert PlaceDescriptorEntity into mappings"
- "Failed to insert ambient sound entity into mappings"
- "Failed to insert classical music recording entity into mappings"
- "Failed to insert event entity into mappings"
- "Failed to insert song entity into mappings"
- "Failed to save context predictor compiled model: %@"
- "Global entity rendering length ("
- "IdentifyObject: bbox must have exactly 4 elements, got %ld"
- "IdentifyObject: failed to resolve entity for model-facing ID: %s"
- "IdentifyObject: resolved %s → %s"
- "IdentifyObjectBuiltIn: run() hit (no image capture service available)"
- "If a notification is long, use "
- "LiveCameraFeedEntity"
- "Missing 'commonName' and 'address' properties in place entity"
- "Missing 'commonName' and 'address' properties in place entity (full rendering)"
- "Normalized 0-1 bounding box x maximum"
- "Normalized 0-1 bounding box x minimum"
- "Normalized 0-1 bounding box y maximum"
- "Normalized 0-1 bounding box y minimum"
- "Notifications.PrepareNotifications: Not a UserNotificationEntity: %s"
- "Notifications.PrepareNotifications: hydration returned empty for read usecase"
- "Phone.MakeCall: Group conversation call — overriding to FaceTime bundle"
- "Processing file at: %s"
- "Rendered CalendarEventEntity as: %s"
- "Rendered CalendarEventEntity as: %{sensitive}s"
- "Rendering EventEntity with properties: %s"
- "Rendering EventEntity with properties: %{sensitive}s"
- "Retrieves spatial data and posts visual capture context for a bounding box selection to downstream clients."
- "TR Embedding output is not MLDictionaryFeatureProvider"
- "Text content was flagged by safety check"
- "The exact coordinate in the image where the user is currently gazing. IMPORTANT: You MUST call get_entity_details on this entity to retrieve the gaze coordinates BEFORE asking the user to clarify or pick between options. Use the gaze point to determine which object in the image the user is referring to."
- "The model-facing entity ID referencing the image capture to retrieve data for"
- "The query names a specific object (e.g., 'what brand is the laptop'). The query is about the whole scene (e.g., 'what room is this'). Only one plausible referent exists in the image."
- "The user names a specific entity explicitly (e.g., 'open Safari'). Only one entity of the relevant kind is on screen. The query is about the whole scene or a physical object."
- "The virtual content entity the user is currently focused on. IMPORTANT: You MUST call get_entity_details on this entity to retrieve the identity of the gazed-at object BEFORE asking the user to clarify or pick between options. Use the gazed-at entity to determine which on-screen entity the user is referring to."
- "Unexpected output shape: %s or dataType: %ld"
- "[Calendar.extractPerson]: Primitive Person %{private}s"
- "[Calendar.extractPerson]: Received unrecognized entity type '%s' for attendee_ids, expected ContactEntity"
- "[Calendar.extractPerson]: Successfully extracted person from ContactEntity: %{private}s"
- "[EntityHydration] Rendering %ld entities (should be <=10 after filtering)"
- "[FileDerivativeHelper] FDS error: %@"
- "[FileDerivativeHelper] extracting text from file at: %s"
- "[FileDerivativeHelper] folder: %s [no content]"
- "[FileDerivativeHelper] symlinks are not supported for text extraction: url: %s"
- "[HydrationService] Failed to hydrate entities: %@"
- "[HydrationService] Failed to hydrate entity value: %@"
- "[HydrationService] Failed to hydrate entity with identifier '%s': %@"
- "[HydrationService] Failed to resolve reference: %s error: %@"
- "[InsertText] Output guardrail violation, rejecting insert"
- "[InsertText] call entity_id=%{public}s textLen=%{public}ld"
- "[KNOWN_LIMITATION] SiriX mini tools do not work reliably in ifrunner. The SiriX daemon stack is not fully available in standalone mode, so results may be missing, incorrect, or the tool may fail entirely. Tool: SafariReader"
- "[SearchResultFileEntityRendering] file derivative error:%s"
- "[SearchTag] Emitted DataClassificationTag.searchRequest for samRequestId %s"
- "[SearchTag] Failed to emit DataClassificationTag.searchRequest for samRequestId %s"
- "[SearchTag] No samRequestId in global result metadata, skipping tag emission"
- "[SearchTag] emitSearchRequestTags called with %{public}ld global result(s)"
- "[SearchTag] resultList.source=%{public}s metadataKeys=[%{public}s]"
- "[TokenBudget] Local entities budget: %ld tokens"
- "[TokenBudget] Local entities consumed %ld/%ld tokens"
- "[liveCameraFeed] openCameraForModeSwitch: camera URL dispatched"
- "[liveCameraFeed] openCameraForModeSwitch: failed to create open operation"
- "[passthroughCamera] entity identifier appended, ID=%s"
- "[transientLiveCameraFeed] snapshot file found — entity identifier appended, cloudID=%s"
- "[visualModelRep] entity with visual component(s) — identifier appended"
- "__PARTIAL_ENTITY__"
- "`update` requires at least one of: `content`, `name`, `attachments`, `tags`, `is_pinned`, or `folder_id`."
- "accident"
- "camera://configuration?capturemode=intelligence&capturedevice=back&issiricontinuation=1"
- "child_endangerment_abuse_exploitation"
- "com.apple.intelligenceflow.visual_capture.identify_object"
- "construction"
- "context_filter.mlpackage"
- "emitToolRetrievalEvent(eventType:contextConfiguration:trId:timestamp:isolatedStreamUUID:)"
- "executePlayTrailer(context:mediaEntity:bundleId:routeEntities:)"
- "executePlayVideoContent(context:mediaEntity:bundleId:routeEntities:)"
- "executeVideoPlayAction(isTrailer:context:entity:routeEntities:)"
- "harm_intent"
- "hazard"
- "identify_object_of_interest_for_request"
- "info unavailable"
- "isRemoteRequest()"
- "isRemoteTVOSRequest()"
- "liveCameraFeed"
- "missingNameAndAddress"
- "peripheral_image_entity_id"
- "resetCache(reason:)"
- "road_closure"
- "self_harm_suicide"
- "speed_trap"
- "traffic_jam"
- "warmEntries(forContainer:toolbox:locale:)"
- "when_NOT_to_retrieve"
- "when_to_retrieve"
```
