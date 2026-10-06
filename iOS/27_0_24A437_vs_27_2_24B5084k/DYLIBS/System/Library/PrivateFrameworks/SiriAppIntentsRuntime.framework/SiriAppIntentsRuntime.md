## SiriAppIntentsRuntime

> `/System/Library/PrivateFrameworks/SiriAppIntentsRuntime.framework/SiriAppIntentsRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x86c58` | `0x9d554` | **`+0x168fc`** |
| `__DATA.__bss` | `0x1400` | `0x2880` | **`+0x1480`** |
| `__TEXT.__const` | `0x29b0` | `0x3810` | **`+0xe60`** |
| `__TEXT.__eh_frame` | `0x50d0` | `0x5d60` | **`+0xc90`** |
| `__AUTH_CONST.__const` | `0x4898` | `0x53f0` | **`+0xb58`** |
| `__TEXT.__oslogstring` | `0x37bd` | `0x404d` | **`+0x890`** |
| `__TEXT.__swift5_typeref` | `0x1495` | `0x1acb` | **`+0x636`** |
| `__TEXT.__unwind_info` | `0x1ca0` | `0x21f0` | **`+0x550`** |
| `__AUTH.__data` | `0x6c8` | `0xae8` | **`+0x420`** |
| `__DATA.__data` | `0x8a8` | `0xc48` | **`+0x3a0`** |
| `__TEXT.__constg_swiftt` | `0xd7c` | `0x10d4` | **`+0x358`** |
| `__TEXT.__swift5_capture` | `0x19cc` | `0x1cc4` | **`+0x2f8`** |
| `__TEXT.__swift5_fieldmd` | `0x9a8` | `0xc84` | **`+0x2dc`** |
| `__AUTH_CONST.__objc_const` | `0xee0` | `0x1120` | **`+0x240`** |
| `__TEXT.__cstring` | `0x14f1` | `0x16d1` | **`+0x1e0`** |
| `__TEXT.__swift5_reflstr` | `0xd43` | `0xeea` | **`+0x1a7`** |
| `__AUTH_CONST.__auth_got` | `0x1960` | `0x1af0` | **`+0x190`** |
| `__TEXT.__swift5_proto` | `0x104` | `0x1ac` | **`+0xa8`** |
| `__TEXT.__swift_as_cont` | `0x36c` | `0x3ec` | **`+0x80`** |
| `__DATA_DIRTY.__objc_data` | `0x9c0` | `0xa20` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__TEXT.__swift_as_entry` | `0x214` | `0x264` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0x98` | `0xe0` | **`+0x48`** |
| `__TEXT.__swift5_types` | `0xbc` | `0x104` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x404` | `0x448` | **`+0x44`** |
| `__DATA.__common` | `0x90` | `0xd0` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x1d0` | `0x208` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x440` | `0x458` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x50` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0x90` | **`+0x10`** |
| `__DATA_DIRTY.__common` | `0x100` | `0xf8` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x4` | `0x8` | **`+0x4`** |

### Other Changes

```diff

-3600.82.29.0.0
+3605.15.1.0.0

-  Functions: 3051
-  Symbols:   220
-  CStrings:  346
+  Functions: 3608
+  Symbols:   228
+  CStrings:  384
Symbols:
+ _NSProcessInfoPowerStateDidChangeNotification
+ _NSProcessInfoThermalStateDidChangeNotification
+ _OBJC_CLASS_$_NSProcessInfo
+ _swift_getEnumCaseMultiPayload
+ _swift_makeBoxUnique
+ _swift_storeEnumTagMultiPayload
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
- _OBJC_CLASS_$_AFConnection
CStrings:
+ "AFSettingsConnection"
+ "DeviceThermalNotificationHandler: kind=streamEnded"
+ "DeviceThermalNotificationHandler: streaming thermal transitions, seeded=%ld"
+ "DeviceThermalStateRecorder: started observing thermal transitions"
+ "Failed to encode device thermal state: %@"
+ "Failed to resolve most recent session: %@"
+ "FetchMostRecentSessionServerTimeoutSeconds"
+ "Most recent session resolved: %s from %s to %s"
+ "MostRecentSessionResolver: all events for session %s were undecodable; skipping candidate"
+ "MostRecentSessionResolver: every event in slice failed to decode (%ld); first error: %s"
+ "MostRecentSessionResolver: skipped %ld undecodable event(s) in slice"
+ "No recent Siri session found within the searched lookback"
+ "Releasing the AFSettingsConnection injection session."
+ "Requesting events for %s from %s until %s."
+ "Resolving most recent session withinLast %fs"
+ "SearchAgentHydrationEventProto"
+ "Server-side timeout (%fs) fired for fetchMostRecentSession"
+ "SiriTrajectoryInstrumentationEvent"
+ "Starting to listen for SearchAgent HydrationEventProto events."
+ "Starting to listen for SiriTrajectoryInstrumentationEvent events."
+ "Transcript.Payload"
+ "XPCServer: Failed to decode SearchAgentProtoHydrationEvent: %@. InteractionId: %s"
+ "XPCServer: Failed to decode SiriTrajectoryInstrumentationEvent proto: %@. InteractionId: %s"
+ "XPCServer: SearchAgent HydrationEvent missing sessionID. Skipping event."
+ "XPCServer: Skipping SearchAgent HydrationEventProto event with empty protoBytes."
+ "XPCServer: Skipping SiriTrajectoryInstrumentationEvent event with empty protoBinaryData."
+ "com.apple.siriappintentsd.most-recent-session-resolve"
+ "fetchDeviceThermalState(forRequestID:from:to:with:)"
+ "fetchDeviceThermalState: no recorded sample for requestID=%s"
+ "fetchDeviceThermalState: requestID=%s thermalLevel=%ld lowPowerMode=%{bool}d"
+ "listenSearchAgentHydrationEventProto: kind=streamEnded"
+ "listenSiriTrajectoryInstrumentationEvent: kind=%s — dropping rather than scoping to interactionId (rdar://182856486)"
+ "listenSiriTrajectoryInstrumentationEvent: kind=streamEnded"
+ "missingSessionID"
+ "protoBinaryData"
+ "rawPayload"
+ "requestEvents(for:from:until:with:)"
+ "resolveMostRecentSessionOffCooperativePool(withinLast:fetch:fetchSession:)"
+ "retrieveSearchAgentHydration: kind=summary matched=%ld total=%ld sessionID=%s"
+ "retrieveSessionResumptionEventBundle: kind=summary matched=%ld yielded=%ld total=%ld embeddedEvents=%ld sessionID=%s"
+ "retrieveSiriTrajectoryInstrumentationEvent: kind=summary matched=%ld emptyIDs=%ld missingSessionID=%ld total=%ld sessionID=%s"
- "AFConnection ends the session."
- "Requesting events for %s until %s."
- "requestEvents(for:with:)"
```
