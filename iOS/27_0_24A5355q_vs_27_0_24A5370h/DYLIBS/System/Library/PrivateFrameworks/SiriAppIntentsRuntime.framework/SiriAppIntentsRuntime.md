## SiriAppIntentsRuntime

> `/System/Library/PrivateFrameworks/SiriAppIntentsRuntime.framework/SiriAppIntentsRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b4e4` | `0x7982c` | **`-0x1cb8`** |
| `__AUTH_CONST.__const` | `0x49e8` | `0x4288` | **`-0x760`** |
| `__TEXT.__swift5_capture` | `0x1980` | `0x16e8` | **`-0x298`** |
| `__TEXT.__oslogstring` | `0x32c0` | `0x305d` | **`-0x263`** |
| `__TEXT.__cstring` | `0x157b` | `0x13d1` | **`-0x1aa`** |
| `__DATA.__data` | `0xc28` | `0xd28` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0x11be` | `0x1297` | **`+0xd9`** |
| `__AUTH.__data` | `0xb08` | `0xba8` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0xb88` | `0xc24` | **`+0x9c`** |
| `__TEXT.__const` | `0x2650` | `0x26e8` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x1a68` | `0x19f0` | **`-0x78`** |
| `__TEXT.__swift5_reflstr` | `0xce6` | `0xc86` | **`-0x60`** |
| `__DATA.__common` | `0x1e0` | `0x198` | **`-0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x3f0` | `0x430` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x8a8` | `0x8d4` | **`+0x2c`** |
| `__TEXT.__swift_as_ret` | `0x19c` | `0x178` | **`-0x24`** |
| `__AUTH.__objc_data` | `0xa48` | `0xa60` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x108` | `0x120` | **`+0x18`** |
| `__TEXT.__eh_frame` | `0x4680` | `0x4668` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0xb0` | `0x98` | **`-0x18`** |
| `__TEXT.__swift_as_cont` | `0x2fc` | `0x2e4` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x1d4` | `0x1c0` | **`-0x14`** |
| `__TEXT.__objc_methlist` | `0x3dc` | `0x3e8` | **`+0xc`** |
| `__AUTH_CONST.__objc_const` | `0xc10` | `0xc18` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xa4` | `0xac` | **`+0x8`** |

### Other Changes

```diff

-3600.69.1.1.2
+3600.82.2.1.1

+  - /System/Library/PrivateFrameworks/IntelligenceFlowPlannerSupport.framework/IntelligenceFlowPlannerSupport

-  Functions: 2808
-  Symbols:   209
-  CStrings:  344
+  Functions: 2753
+  Symbols:   212
+  CStrings:  320
Symbols:
+ _OBJC_CLASS_$_AFLocalization
+ _OBJC_CLASS_$_AFPreferences
+ _OBJC_CLASS_$_AFVoiceInfo
+ _bzero
+ _objc_retain_x26
+ _swift_checkMetadataState
+ _swift_cvw_allocateGenericValueMetadataWithLayoutString
+ _swift_cvw_enumFn_getEnumTag
+ _swift_getGenericMetadata
- _OBJC_CLASS_$_NSError
- _OBJC_CLASS_$_NSHTTPURLResponse
- _OBJC_CLASS_$_NSURLSession
- _os_variant_has_internal_content
- _swift_dynamicCastObjCClass
- _swift_isUniquelyReferenced_nonNull
CStrings:
+ "%{public}s Connection rejected: no bundle ID provided"
+ "%{public}s ✅ Connection accepted from: %{public}s"
+ "SecurityValidationEvent"
+ "SessionResumptionEventBundle"
+ "Starting to listen for SecurityValidationEvent events."
+ "Starting to listen for SessionResumptionEventBundle events."
+ "Transcript.Timepoint"
+ "XPC server fetching voice metadata"
+ "[SessionResumptionBundle] Failed to serialize SessionResumptionEventBundlePayload"
+ "fetchRawInferenceEventData(for:requestTimestamp:with:)"
+ "kind=parseFailed fetchRawInferenceEventData plannerID=%s outputLen=%ld lineCount=%ld parseFailures=%ld"
+ "kind=summary status=failed fetchRawInferenceEventData plannerID=%s error=%s"
+ "listenSecurityValidationEvents: kind=streamEnded"
+ "listenSessionResumptionEventBundle: kind=streamEnded"
+ "rawDate"
+ "retrieveSecurityValidationEvents: kind=summary count=%ld"
+ "timepoint"
- "/Library/Managed Preferences/mobile/com.apple.intelligenceflow.plist"
- "/usr/local/bin/thtool"
- "0123456789abcdefABCDEF"
- "AgenticPlannerRoutingOverride"
- "Bad server response: %s"
- "Connection rejected: '%s' not in allowlist.\nTo add this client, submit a PR adding it to allowedClients in XPCServer.swift"
- "Connection rejected: no bundle ID provided"
- "Either sessionID or startDate must be provided."
- "Exporting trajectory data for sessionID=%s startDate=%s endDate=%s"
- "Failed to convert PCC Config string to data"
- "Failed to export trajectory data: %@"
- "Failed to get PCC Config JSON: %@"
- "Failed to parse PCC Config JSON as dictionary"
- "Failed to read IntelligenceFlowDefaults: %@"
- "Failed to run iftool CLI: %@"
- "Fetched contect was NOT a valid String"
- "Fetched contect was NOT a valid [String: Any] JSON dictionary"
- "Fetching content from: %s"
- "Found empty Zinc URL: %s"
- "Got PCC Config JSON: %s"
- "Got Zinc server config JSON: %s"
- "IntelligenceFlowConfig"
- "IntelligenceFlowDefaults("
- "LocalFeatureStoreDataSource: Error discovering sessions: %@"
- "Obtained Zinc server URL: %s"
- "PlannerType"
- "Received invalid URL string: %s"
- "TrajectoryExportHandler: export complete spans=%ld bytes=%ld replayPayloads=%ld elapsed=%s"
- "TrajectoryExportHandler: starting export sessionID=%s startDate=%s endDate=%s"
- "Unable to parse Zinc server URL from: '%s'"
- "Zinc URL not found"
- "Zinc URL not found when tried to fetch server SHA"
- "Zinc URL not found when tried to fetch server config"
- "[Replay] Found requestIdentifier: %s for plannerID: %s"
- "agenticPlannerZincUrl"
- "agentic_planner_dev_server"
- "com.apple.SiriHUD"
- "com.apple.intelligenceflow.IntelligenceFlowRuntime.IntelligenceFlowInternalDiagnostics"
- "com.apple.siriappintentsd"
- "com.apple.siriappintentstool"
- "✅ Connection accepted from allowed client: %s"
```
