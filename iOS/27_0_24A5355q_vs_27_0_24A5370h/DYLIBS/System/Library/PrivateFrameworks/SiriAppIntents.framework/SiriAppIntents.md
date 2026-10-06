## SiriAppIntents

> `/System/Library/PrivateFrameworks/SiriAppIntents.framework/SiriAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1288b54` | `0x1298da4` | **`+0x10250`** |
| `__DATA.__bss` | `0x244c10` | `0x246e90` | **`+0x2280`** |
| `__TEXT.__const` | `0x19b260` | `0x19ca60` | **`+0x1800`** |
| `__TEXT.__eh_frame` | `0xb52a4` | `0xb5e10` | **`+0xb6c`** |
| `__AUTH_CONST.__const` | `0x359b0` | `0x364c8` | **`+0xb18`** |
| `__AUTH.__data` | `0x82f08` | `0x834b0` | **`+0x5a8`** |
| `__DATA.__data` | `0x549a8` | `0x54f18` | **`+0x570`** |
| `__TEXT.__swift5_fieldmd` | `0x4af90` | `0x4b3e4` | **`+0x454`** |
| `__TEXT.__unwind_info` | `0x80798` | `0x80bd0` | **`+0x438`** |
| `__TEXT.__cstring` | `0x250e7` | `0x25517` | **`+0x430`** |
| `__TEXT.__swift5_reflstr` | `0x427bc` | `0x42b7c` | **`+0x3c0`** |
| `__TEXT.__constg_swiftt` | `0x3c5f0` | `0x3c8dc` | **`+0x2ec`** |
| `__TEXT.__oslogstring` | `0x207d` | `0x233d` | **`+0x2c0`** |
| `__TEXT.__swift5_typeref` | `0x29e28` | `0x2a088` | **`+0x260`** |
| `__AUTH_CONST.__objc_const` | `0x25a20` | `0x25b88` | **`+0x168`** |
| `__TEXT.__swift5_proto` | `0x122ec` | `0x12404` | **`+0x118`** |
| `__AUTH_CONST.__auth_got` | `0x1298` | `0x13a0` | **`+0x108`** |
| `__TEXT.__swift5_assocty` | `0x6f20` | `0x6ff8` | **`+0xd8`** |
| `__DATA_CONST.__const` | `0x1ab60` | `0x1ac10` | **`+0xb0`** |
| `__TEXT.__swift5_capture` | `0x1af0` | `0x1b88` | **`+0x98`** |
| `__TEXT.__swift_as_cont` | `0x2bc` | `0x324` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x3c50` | `0x3ca0` | **`+0x50`** |
| `__TEXT.__swift5_types` | `0x3870` | `0x38b0` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x198` | `0x1d8` | **`+0x40`** |
| `__DATA.__common` | `0x70` | `0xa0` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x164` | `0x194` | **`+0x30`** |
| `__DATA_CONST.__objc_protolist` | `0x30` | `0x50` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x20` | `0x30` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2f4` | `0x300` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x720` | `0x728` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f8` | `0x300` | **`+0x8`** |

### Other Changes

```diff

-3600.69.1.1.2
+3600.82.2.1.1

-  Functions: 202331
-  Symbols:   227
-  CStrings:  4098
+  Functions: 203210
+  Symbols:   232
+  CStrings:  4136
Symbols:
+ __os_signpost_emit_with_name_impl
+ _objc_release_x9
+ _os_variant_has_internal_content
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
CStrings:
+ "%{public}s BidirectionalDelegate: '%{public}s' is unreadable on RemoteXPC transport. Conformers using `useRemoteXPC = true` must set `clientApplicationIdentifierEntitlementRequired = false`. Rejecting connection."
+ "%{public}s Delegate: '%{public}s' is unreadable on RemoteXPC transport. Conformers using `useRemoteXPC = true` must set `clientApplicationIdentifierEntitlementRequired = false`. Rejecting connection."
+ "CommandLine - running (concurrent async): %s %s"
+ "DiagnosticOTelExporter: Starting trajectory export from %s profile=%s"
+ "MessageTypes.SecurityValidationEventPayload"
+ "MessageTypes.SessionResumptionEventBundlePayload"
+ "MessageTypes.SiriVoiceMetadata"
+ "Security Validation"
+ "SecurityValidationEvent"
+ "SessionResumptionEventBundle"
+ "SiriTrajectory: Starting trajectory export for session %s profile=%s from %s to %s"
+ "TrajectoryCollector: Timed out fetching voice metadata"
+ "TrajectoryCollector: voice metadata fetch failed kind=fetchError error=%s"
+ "XPC client fetching voice metadata"
+ "[Error] Interval already ended"
+ "_replay_payload.json"
+ "apple.parsec.sam.v1alpha.SAMBatchItemServiceDebug"
+ "apple.parsec.sam.v1alpha.SAMBatchSearchResponseMetadata"
+ "apple.parsec.sam.v1alpha.SAMQueryMetadata"
+ "apple.parsec.sam.v1alpha.SAMSafetySignals"
+ "bytes=%ld"
+ "com.apple.private.siriappintentsd.orchestrator"
+ "com.apple.siriappintentsd"
+ "count=%ld bytes=%ld"
+ "decode.gmsEvents"
+ "decode.gmsTools"
+ "decode.modelInformation"
+ "decode.plannerResponse"
+ "decode.status"
+ "full"
+ "indirectPromptInjection"
+ "pegasus.trace_url"
+ "runWithConcurrentOutputAsync(_:args:timeout:)"
+ "security.classification_result"
+ "security.classifier"
+ "security.model_input"
+ "security.validation_type"
+ "seed"
+ "siri.voice.footprint"
+ "siri.voice.gender"
+ "siri.voice.is_custom"
+ "siri.voice.language_code"
+ "siri.voice.variant"
- "DiagnosticOTelExporter: Starting trajectory export from %s"
- "Framework Directive"
- "SiriTrajectory: Starting trajectory export for session %s from %s to %s"
- "XPC client retreiving Zinc server config"
- "framework_directive"
```
