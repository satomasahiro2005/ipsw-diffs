## SiriAppIntents

> `/System/Library/PrivateFrameworks/SiriAppIntents.framework/SiriAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `—` | `0x80b00` | **`+0x80b00`** |
| `__AUTH.__data` | `0x834b0` | `0x15ab8` | **`-0x6d9f8`** |
| `__DATA.__data` | `0x54f18` | `0x42138` | **`-0x12de0`** |
| `__DATA_DIRTY.__bss` | `—` | `0x12300` | **`+0x12300`** |
| `__DATA.__bss` | `0x246e90` | `0x235390` | **`-0x11b00`** |
| `__TEXT.__text` | `0x1298da4` | `0x12a1ab8` | **`+0x8d14`** |
| `__AUTH.__objc_data` | `0x3ca0` | `—` | **`-0x3ca0`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x3ca0` | **`+0x3ca0`** |
| `__TEXT.__unwind_info` | `0x80bd0` | `0x7e998` | **`-0x2238`** |
| `__TEXT.__oslogstring` | `0x233d` | `0x2b7d` | **`+0x840`** |
| `__AUTH_CONST.__const` | `0x364c8` | `0x36ae0` | **`+0x618`** |
| `__TEXT.__const` | `0x19ca60` | `0x19d020` | **`+0x5c0`** |
| `__TEXT.__swift5_reflstr` | `0x42b7c` | `0x42d7c` | **`+0x200`** |
| `__TEXT.__swift5_fieldmd` | `0x4b3e4` | `0x4b578` | **`+0x194`** |
| `__TEXT.__swift5_capture` | `0x1b88` | `0x1d08` | **`+0x180`** |
| `__TEXT.__cstring` | `0x25517` | `0x25667` | **`+0x150`** |
| `__TEXT.__constg_swiftt` | `0x3c8dc` | `0x3c9bc` | **`+0xe0`** |
| `__TEXT.__eh_frame` | `0xb5e10` | `0xb5edc` | **`+0xcc`** |
| `__TEXT.__swift5_typeref` | `0x2a088` | `0x2a152` | **`+0xca`** |
| `__DATA_DIRTY.__common` | `—` | `0x78` | **`+0x78`** |
| `__TEXT.__swift5_assocty` | `0x6ff8` | `0x7070` | **`+0x78`** |
| `__DATA.__common` | `0xa0` | `0x40` | **`-0x60`** |
| `__AUTH_CONST.__objc_const` | `0x25b88` | `0x25bc8` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x12404` | `0x12444` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x13a0` | `0x13c0` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x38b0` | `0x38c4` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x324` | `0x32c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x194` | `0x19c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1d8` | `0x1e0` | **`+0x8`** |

### Other Changes

```diff

-3600.82.2.1.1
+3600.82.15.0.0

-  Functions: 203210
+  Functions: 203415

-  CStrings:  4136
+  CStrings:  4168
Symbols:
+ _objc_retain_x27
- _swift_willThrowTypedImpl
CStrings:
+ " orphanedRequests="
+ " orphanedResponses="
+ "%{public}s BidirectionalDelegate: Client is missing service entitlement. Rejecting connection."
+ "%{public}s Delegate: Client is missing service entitlement. Rejecting connection."
+ "PrivateCloudMetrics.Inference"
+ "PrivateCloudMetrics.KVCache"
+ "PrivateCloudMetrics.PrefixTrie"
+ "PrivateCloudMetrics.SpeculativeDecode"
+ "PrivateCloudMetrics.TopologicalPrompt"
+ "SiriTrajectory.extractEntries: failed to decode %s: %@"
+ "SiriTrajectory.extractEntries: failed to read %s: %@"
+ "SiriTrajectory.extractEntries: file not found at %s"
+ "SiriTrajectory.extractEntries: kind=entityIdCollision requestID=%s id=%s"
+ "SiriTrajectory.extractEntries: kind=summary entries=%ld decodeFailures=%ld depthCaps=%ld"
+ "SiriTrajectory: Failed to parse GMSPlannerRequestPayload JSON — replacing payload with redactedMarker"
+ "SiriTrajectory: Failed to parse GMSPlannerResponsePayload JSON — replacing payload with redactedMarker"
+ "SiriTrajectory: Failed to parse GMSTranscriptContent from plannerResponse bytes — replacing plannerResponse with sentinel"
+ "SiriTrajectory: Failed to parse SecurityValidationEventPayload JSON — replacing payload with redactedMarker"
+ "SiriTrajectory: Failed to parse SessionResumptionEventBundlePayload JSON — replacing payload with redactedMarker"
+ "SiriTrajectory: Failed to parse TranscriptProtoEvent JSON — replacing payload with redactedMarker"
+ "SiriTrajectory: Failed to re-serialize redacted GMSTranscriptContent for PlannerResponse — replacing plannerResponse with sentinel"
+ "SpanBuilder: GMSPlannerRequest JSON serialization failed plannerID=%s"
+ "SpanBuilder: GMSPlannerResponse JSON serialization failed plannerID=%s"
+ "SpanBuilder: build complete kind=summary events=%ld sessions=%ld spans=%ld srt=%ld replayPayloads=%ld%s"
+ "SpanBuilder: convertToGenAIInputMessages returned nil for %ld GMS event(s)"
+ "SpanBuilder: convertToGenAIOutputMessages returned nil for plannerID %s"
+ "SpanBuilder: convertToGenAIToolDefinitions returned nil for %ld tool(s)"
+ "SpanBuilder: routed %ld AI metrics event(s) to request groups via plannerID"
+ "XPC Client: bidirectional connection established"
+ "XPC Client: opening event stream for session %s"
+ "allowlisted"
+ "passthrough"
+ "siri.voice.expressivity_preset"
+ "siri.voice.pace_preset"
- "full"
- "seed"
```
