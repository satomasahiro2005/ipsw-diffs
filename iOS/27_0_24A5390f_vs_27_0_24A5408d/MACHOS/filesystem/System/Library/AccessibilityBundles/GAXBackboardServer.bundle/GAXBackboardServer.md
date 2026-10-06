## GAXBackboardServer

> `/System/Library/AccessibilityBundles/GAXBackboardServer.bundle/GAXBackboardServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2acd8` | `0x2b560` | **`+0x888`** |
| `__TEXT.__oslogstring` | `0x3ef4` | `0x41e2` | **`+0x2ee`** |
| `__TEXT.__objc_methname` | `0x8b7f` | `0x8d43` | **`+0x1c4`** |
| `__TEXT.__objc_stubs` | `0x6880` | `0x6940` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x460b` | `0x46b9` | **`+0xae`** |
| `__DATA_CONST.__cfstring` | `0x3600` | `0x36a0` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x7e8` | `0x84c` | **`+0x64`** |
| `__TEXT.__objc_methlist` | `0x2834` | `0x2894` | **`+0x60`** |
| `__DATA.__objc_const` | `0x29c0` | `0x2a10` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xa60` | `0xaa0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x1e98` | `0x1ec8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x16a0` | `0x16a8` | **`+0x8`** |
| `__TEXT.__const` | `0x180` | `0x188` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1a4` | `0x1a8` | **`+0x4`** |
| `__TEXT.__objc_methtype` | `0x1868` | `0x186b` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1061.0.0.0.0
+1064.0.0.0.0

-  Functions: 955
-  Symbols:   580
-  CStrings:  2231
+  Functions: 965
+  Symbols:   581
+  CStrings:  2256
Symbols:
+ _GAXUIMessageKeyShouldDriveSiriAssessmentRestriction
CStrings:
+ "App-relaunch block-all-events exceeded 5 minutes without a terminal verification outcome; releasing to avoid stranding input"
+ "GAXBackboard creating userInterfaceClient with identifier %@ (this client is not invalidated until GAXBackboard is deallocated, which does not happen for this singleton)"
+ "GAXBackboard init starting"
+ "GAXBackboard sharedInstance first created. Caller: %@"
+ "NEW"
+ "OLD"
+ "Releasing app-relaunch block-all-events reason (%{public}@)"
+ "Session app is effective and active but device is restricted; lifting restriction"
+ "SessionDrivesSiriAssessmentRestriction"
+ "Siri assessment restriction ownership: entitlement=%{public}s (legacy=%d new=%d) -> GAX %{public}s drive Siri"
+ "T@\"AXDispatchTimer\",&,N,V_appRelaunchBlockAllEventsWatchdogTimer"
+ "Transitioned to GAXServerModeDisabled. userInterfaceClient %@ is not invalidated here (rdar://182430437) so its AXUIServer service registration remains active."
+ "WILL"
+ "_appRelaunchBlockAllEventsWatchdogTimer"
+ "_releaseVerifyAppRelaunchBlockAllEventsIfSetWithContext:"
+ "appRelaunchBlockAllEventsWatchdogTimer"
+ "applyUnmanagedSelfLockRestrictionsForStyle:shouldDriveSiriAssessmentRestriction:withUserInterfaceClient:"
+ "none"
+ "processWithAuditTokenOwnsSiriAssessmentRestriction:"
+ "removeUnmanagedSelfLockRestrictionsWithUserInterfaceClient:shouldDriveSiriAssessmentRestriction:"
+ "sessionDrivesSiriAssessmentRestriction"
+ "setAppRelaunchBlockAllEventsWatchdogTimer:"
+ "setSessionDrivesSiriAssessmentRestriction:"
+ "should drive siri assessment restriction"
+ "terminal verification event"
+ "v36@0:8q16B24@28"
+ "verification finished"
+ "watchdog timeout"
+ "will NOT"
- "Action button press blocked. Mode: %i"
- "applyUnmanagedSelfLockRestrictionsForStyle:withUserInterfaceClient:"
- "removeUnmanagedSelfLockRestrictionsWithUserInterfaceClient:"
- "v32@0:8q16@24"
```
