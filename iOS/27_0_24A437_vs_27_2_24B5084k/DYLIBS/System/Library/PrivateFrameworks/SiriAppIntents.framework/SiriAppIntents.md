## SiriAppIntents

> `/System/Library/PrivateFrameworks/SiriAppIntents.framework/SiriAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13437fc` | `0x13573a0` | **`+0x13ba4`** |
| `__DATA.__bss` | `0x244810` | `0x248610` | **`+0x3e00`** |
| `__TEXT.__const` | `0x1a6f20` | `0x1a9c40` | **`+0x2d20`** |
| `__TEXT.__eh_frame` | `0xba5a0` | `0xbc024` | **`+0x1a84`** |
| `__TEXT.__unwind_info` | `0x81e20` | `0x83278` | **`+0x1458`** |
| `__AUTH.__data` | `0x18ae0` | `0x19ac8` | **`+0xfe8`** |
| `__TEXT.__swift5_fieldmd` | `0x4d7f4` | `0x4e2a8` | **`+0xab4`** |
| `__TEXT.__swift5_reflstr` | `0x4451c` | `0x44f5c` | **`+0xa40`** |
| `__TEXT.__cstring` | `0x27d57` | `0x28757` | **`+0xa00`** |
| `__DATA.__data` | `0x44748` | `0x44f28` | **`+0x7e0`** |
| `__AUTH_CONST.__const` | `0x3a440` | `0x39d10` | **`-0x730`** |
| `__TEXT.__constg_swiftt` | `0x3e3f8` | `0x3eab8` | **`+0x6c0`** |
| `__TEXT.__oslogstring` | `0x2f5d` | `0x35ad` | **`+0x650`** |
| `__TEXT.__swift5_capture` | `0x2278` | `0x1c38` | **`-0x640`** |
| `__DATA_CONST.__const` | `0x1b1a0` | `0x1b750` | **`+0x5b0`** |
| `__TEXT.__swift5_typeref` | `0x2b5e4` | `0x2bb16` | **`+0x532`** |
| `__AUTH_CONST.__objc_const` | `0x26de8` | `0x271f8` | **`+0x410`** |
| `__TEXT.__swift5_proto` | `0x12bfc` | `0x12dec` | **`+0x1f0`** |
| `__DATA_DIRTY.__data` | `0x80940` | `0x807d8` | **`-0x168`** |
| `__TEXT.__swift5_assocty` | `0x7418` | `0x74f0` | **`+0xd8`** |
| `__TEXT.__swift5_types` | `0x3ab0` | `0x3b20` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x230` | `0x280` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x3ca0` | `0x3c50` | **`-0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1538` | `0x1560` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x338` | `0x360` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x30c` | `0x330` | **`+0x24`** |
| `__TEXT.__swift_as_ret` | `0x22c` | `0x208` | **`-0x24`** |
| `__DATA.__common` | `0x58` | `0x70` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x778` | `0x780` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x148` | `0x150` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1d0` | `0x1c8` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x39c` | `0x3a0` | **`+0x4`** |

### Other Changes

```diff

-3600.82.29.0.0
+3605.15.1.0.0

-  Functions: 208855
-  Symbols:   245
-  CStrings:  4486
+  Functions: 210358
+  Symbols:   247
+  CStrings:  4562
Symbols:
+ _NSCocoaErrorDomain
+ _swift_getExistentialTypeMetadata
+ _swift_getTupleTypeMetadata3
- _objc_release_x9
CStrings:
+ " conversionFailures="
+ " failed to decode: "
+ " is not supported by any siriappintentsd version (no longer backed by an XPC API); this device's daemon is at interface version "
+ " notEitherFormat="
+ "\"Siri AI\" Feature Flag is disabled"
+ ") does not support "
+ "; it requires version "
+ "Accumulated Latency: "
+ "At/Above Threshold"
+ "Classifier Error"
+ "Classifier Unavailable"
+ "Could not connect to siriappintentsd: "
+ "Could not determine the most recent Siri session: "
+ "Current locale is not supported with Siri AI"
+ "Entity Hydration"
+ "Failed to write the trajectory file at "
+ "Handoff Declined"
+ "IntelligenceFlow.FeatureStore.InstrumentationEvent"
+ "IntelligenceFlow.Instrumentation.CrossEncoderEntityScore"
+ "IntelligenceFlow.Instrumentation.CrossEncoderFilteringEvent"
+ "IntelligenceFlow.Instrumentation.EntityMetadata"
+ "IntelligenceFlow.Instrumentation.HydrationEvent"
+ "IntelligenceFlow.Instrumentation.PlannerShownEvent"
+ "IntelligenceFlow.Instrumentation.PreHydrationEvent"
+ "IntelligenceFlow.Instrumentation.PreRenderingEvent"
+ "IntelligenceFlow.Instrumentation.RankingDecisionEvent"
+ "IntelligenceFlow.Instrumentation.SearchInvocationCorrelationEvent"
+ "Level of Detail: "
+ "MessageTypes.DeviceThermalStatePayload"
+ "Model Asset Version: "
+ "No events were found for session "
+ "Pegasus Threshold: "
+ "Planner Tool Call ID: "
+ "Score (Pegasus): "
+ "SearchAgent: Hydration"
+ "SessionResumptionEventBundle: kind=decodePartial %{public}s sessionID=%s"
+ "SessionResumptionEventBundle: kind=summary %{public}s sessionID=%s"
+ "Siri AI is not supported on this device"
+ "Siri Trajectory Instrumentation"
+ "SiriTrajectory: SiriTrajectoryInstrumentationEvent payload wasn't trafficClassifierDecision (failed to parse, or a future consolidated arm) — falling through to the default redaction policy"
+ "SiriTrajectory: export cancelled by the caller for session %s"
+ "SiriTrajectory: export failed for session %s kind=%s reason=%s"
+ "SiriTrajectory: export found no events for session %s kind=%s"
+ "SiriTrajectory: kind=summary redactSessionResumptionBundle sentineledEvents=%ld total=%ld"
+ "SiriTrajectory: most-recent-session lookup could not reach the daemon: %@"
+ "SiriTrajectory: most-recent-session lookup failed: %@"
+ "SiriTrajectory: most-recent-session lookup timed out after %fs"
+ "SiriTrajectory: most-recent-session lookup write failed at %s: %@"
+ "SiriTrajectory: no recent Siri session on this device (searched the daemon's full horizon)"
+ "SiriTrajectory: resolved %s, observed %s → %s, padded ±%fs to %s → %s"
+ "The connection to siriappintentsd dropped while fetching events for session "
+ "The daemon failed to fetch events for session "
+ "The daemon returned events for session "
+ "The siriappintentsd daemon on this device (interface version "
+ "Timed out waiting for the daemon to return events for session "
+ "Traffic Classifier Decision"
+ "TrafficClassifier.Decision"
+ "TrafficClassifierDecision"
+ "Trajectory export failed: "
+ "TrajectoryCollector: Cancelled while fetching events for session %s"
+ "TrajectoryCollector: all events failed conversion session=%s conversionFailures=%ld kind=conversionFailed"
+ "TrajectoryCollector: fetch failed session=%s kind=%s terminal=true error=%s"
+ "TrajectoryCollector: fetch failed session=%s kind=timedOut terminal=true"
+ "TrajectoryCollector: session empty session=%s kind=hadNoEvents breakdown=[%s]"
+ "Unrecognized Availability Status (Please update your SiriHelios client)"
+ "XPC client resolving most recent session withinLast %fs"
+ "connectionInterrupted"
+ "daemonConnectionInterrupted"
+ "daemonUnavailable"
+ "eventConversionFailed"
+ "eventFetchFailed"
+ "eventFetchTimedOut"
+ "invalidTrajectoryFormat"
+ "kind=streamingFetch session=%s windowed=%{bool}d daemonVersion=%ld from %s until %s"
+ "lowPowerModeEnabled"
+ "most-recent-session lookup"
+ "outputWriteFailed"
+ "redactedSentinel="
+ "sessionHadNoEvents"
+ "sessionID failureCount underlying "
+ "sessionID underlying "
+ "sessionLookupFailed"
+ "thermalStateRawValue"
+ "url underlying "
+ "→ PCC (redirected)"
- "\"Linwood\" Feature Flag is disabled"
- "BuildVersion"
- "Current locale is not supported with Linwood"
- "DeviceClass"
- "HWModel"
- "Linwood is not supported on this device"
- "UniqueDeviceID"
- "Unrecognized Availabilty Status (Please update your SiriHelios client)"
- "XPC client executes requestEvents for siriSessionID: %s on XPC Server"
```
