## SiriAppIntentsRuntime

> `/System/Library/PrivateFrameworks/SiriAppIntentsRuntime.framework/SiriAppIntentsRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x815b4` | `0x86c20` | **`+0x566c`** |
| `__TEXT.__eh_frame` | `0x4818` | `0x50d0` | **`+0x8b8`** |
| `__TEXT.__oslogstring` | `0x348d` | `0x37bd` | **`+0x330`** |
| `__AUTH_CONST.__const` | `0x4648` | `0x4898` | **`+0x250`** |
| `__AUTH_CONST.__objc_const` | `0xcd0` | `0xee0` | **`+0x210`** |
| `__TEXT.__unwind_info` | `0x1ac0` | `0x1ca0` | **`+0x1e0`** |
| `__TEXT.__const` | `0x2808` | `0x29b0` | **`+0x1a8`** |
| `__AUTH.__data` | `0x570` | `0x6c8` | **`+0x158`** |
| `__TEXT.__swift5_capture` | `0x1880` | `0x19cc` | **`+0x14c`** |
| `__TEXT.__swift5_typeref` | `0x1385` | `0x1495` | **`+0x110`** |
| `__TEXT.__constg_swiftt` | `0xca4` | `0xd7c` | **`+0xd8`** |
| `__DATA.__data` | `0x828` | `0x8a8` | **`+0x80`** |
| `__TEXT.__swift_as_cont` | `0x2ec` | `0x36c` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x18e8` | `0x1960` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x940` | `0x9a8` | **`+0x68`** |
| `__TEXT.__swift_as_ret` | `0x17c` | `0x1d0` | **`+0x54`** |
| `__TEXT.__swift5_reflstr` | `0xcf6` | `0xd43` | **`+0x4d`** |
| `__TEXT.__swift_as_entry` | `0x1cc` | `0x214` | **`+0x48`** |
| `__DATA_DIRTY.__data` | `0xd28` | `0xd68` | **`+0x40`** |
| `__TEXT.__cstring` | `0x14b1` | `0x14f1` | **`+0x40`** |
| `__DATA_DIRTY.__objc_data` | `0x9d8` | `0x9c0` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x70` | `0x80` | **`+0x10`** |
| `__DATA_DIRTY.__common` | `0x110` | `0x100` | **`-0x10`** |
| `__DATA.__common` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xb4` | `0xbc` | **`+0x8`** |

### Other Changes

```diff

-3600.82.20.0.0
+3600.82.29.0.0

-  Functions: 2905
-  Symbols:   216
-  CStrings:  337
+  Functions: 3038
+  Symbols:   220
+  CStrings:  346
Symbols:
+ _objc_release_x1
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get
+ _swift_deletedAsyncMethodErrorTu
- _swift_retain_x9
CStrings:
+ "AIR: inferenceMetrics timeToFirstToken=%s extendLatency=%s totalInferenceTime=%s cachedTokens=%s inputTokens=%s outputTokens=%s thinkingTokens=%s firstTokenPreprocessingMs=%s"
+ "SecurityValidationEventProto"
+ "SessionManager teardown timed out; a Biome subscription may still be live. (rdar://181864363)"
+ "Starting to listen for SecurityValidationEventProto events."
+ "awaitWithTimeout(_:)"
+ "createEventStream: Biome subscription fan-out cancelled."
+ "createEventStream: Biome subscription fan-out failed: %@"
+ "listenSecurityValidationEventsProto: kind=emptyIDs — proto delivered a SecurityValidationEvent with no session/turn/query IDs. The vendored proto may not match IF's wire format (rdar://182856486); falling back to interactionId scoping, reintroducing the fragile lookup this change removes."
+ "listenSecurityValidationEventsProto: kind=streamEnded"
+ "retrieveAppleIntelligenceReportingInvocationStep(for:from:until:continuation:)"
+ "retrieveSecurityValidationEventsProto: kind=summary matched=%ld emptyIDs=%ld total=%ld sessionID=%s"
- "AIR: inferenceMetrics timeToFirstToken=%s extendLatency=%s totalInferenceTime=%s cachedTokens=%s inputTokens=%s outputTokens=%s"
- "Cannot send utterance: no active session. Call startSession() first."
```
