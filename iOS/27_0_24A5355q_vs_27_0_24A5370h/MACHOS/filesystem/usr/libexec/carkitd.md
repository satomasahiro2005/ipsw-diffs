## carkitd

> `/usr/libexec/carkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91e3c` | `0x944c0` | **`+0x2684`** |
| `__TEXT.__oslogstring` | `0x10da1` | `0x11351` | **`+0x5b0`** |
| `__TEXT.__objc_methname` | `0x18584` | `0x18914` | **`+0x390`** |
| `__DATA_CONST.__cfstring` | `0x7020` | `0x7200` | **`+0x1e0`** |
| `__TEXT.__objc_stubs` | `0x11340` | `0x11500` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x6252` | `0x63f2` | **`+0x1a0`** |
| `__DATA.__objc_const` | `0x146b0` | `0x147a0` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x7a6c` | `0x7b44` | **`+0xd8`** |
| `__TEXT.__unwind_info` | `0x2150` | `0x21f8` | **`+0xa8`** |
| `__DATA.__objc_selrefs` | `0x4fc8` | `0x5068` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x188c` | `0x1920` | **`+0x94`** |
| `__DATA_CONST.__const` | `0x3700` | `0x3790` | **`+0x90`** |
| `__DATA_CONST.__objc_arrayobj` | `0xa8` | `0xc0` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x918` | `0x930` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x7b4` | `0x7c8` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x18c0` | `0x18d0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x496e` | `0x497e` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xc70` | `0xc78` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x958` | `0x960` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x908` | `0x910` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1d8` | `0x1e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-789.1.0.0.0
+792.0.0.0.0

-  Functions: 3378
-  Symbols:   744
-  CStrings:  6620
+  Functions: 3420
+  Symbols:   746
+  CStrings:  6688
Symbols:
+ __dispatch_source_type_timer
+ _dispatch_source_set_timer
CStrings:
+ "@32@0:8@16d24"
+ "Auto-dismissing bulletin %@ %@"
+ "CRDiagnosticsBulletin"
+ "Descriptor missing required fields"
+ "Descriptor must be an NSDictionary"
+ "Diagnostics bulletin created with recordID %@"
+ "Diagnostics bulletin not presented: CARUserAlerts unavailable"
+ "Empty session identifier"
+ "Failed to create statistics observation for logging file receiver"
+ "Missing statisticsPublisher entitlement"
+ "Missing test-automation entitlement"
+ "No active logging file receiver; observer registered for direct publish only"
+ "Presenting diagnostics bulletin: %@, timeout: %f"
+ "Registered observer for direct statistics publish (connection %i)"
+ "Statistics observer connection from process %i invalidated; removed (%lu remaining)"
+ "Successfully set up vehicle statistics observer with logging"
+ "System"
+ "T@\"NSDictionary\",&,N,V_carKeyInfo"
+ "T@\"NSMapTable\",&,N,V_statisticsObserversByConnection"
+ "T@\"NSMutableDictionary\",&,N,V_syntheticSessions"
+ "T@\"NSObject<OS_dispatch_source>\",&,N,V_autoDismissTimer"
+ "T@\"NSString\",C,N,V_header"
+ "TB,N,V_overrideHeader"
+ "Ultra-capable HU delivered Classic with no prior preference; recording Ultra opt-out for %@"
+ "Unknown synthetic session identifier"
+ "XPC client pid %i invalidated; tearing down %lu synthetic session(s)"
+ "_autoDismissTimer"
+ "_cancelAutoDismissTimerForBulletin:"
+ "_handleAutoDismissForBulletin:"
+ "_header"
+ "_mainQueue_announceSyntheticSessionForHostWithDescriptor:sessionIdentifier:"
+ "_mainQueue_cleanupSyntheticSessionsForPID:"
+ "_overrideHeader"
+ "_scheduleAutoDismissForBulletin:"
+ "_statisticsObserversByConnection"
+ "_syntheticSessions"
+ "acquireSyntheticCarPlaySession from pid %i rejected: missing %@ entitlement"
+ "acquireSyntheticCarPlaySession from pid %i, descriptor=%{public}@"
+ "acquireSyntheticCarPlaySessionWithDescriptor:reply:"
+ "autoDismissTimer"
+ "carKeyInfo"
+ "clusterAssetIdentifierDidChange"
+ "com.apple.carkit.SyntheticSessionError"
+ "com.apple.carkit.synthetic-session-changed"
+ "com.apple.private.carkit.statisticsPublisher"
+ "com.apple.springboard.testautomation"
+ "extraHostProperties"
+ "fe80::1%lo0"
+ "header"
+ "initWithMessage:timeoutInterval:"
+ "initWithSession:assetIdentifier:"
+ "overrideHeader"
+ "pid"
+ "presentBulletin:"
+ "presentWaitingOnStartSessionPromptWithResponseHandler:"
+ "publishAccessoryStatistics: delivering to %lu observer(s)"
+ "publishAccessoryStatistics: rejected - process %i missing %@ entitlement"
+ "publishAccessoryStatistics:reply:"
+ "received response for waiting on start session prompt"
+ "setAutoDismissTimer:"
+ "setCarKeyInfo:"
+ "setHeader:"
+ "setOverrideHeader:"
+ "setStatisticsObserversByConnection:"
+ "setSyntheticSessions:"
+ "statisticsObserversByConnection"
+ "stopSyntheticCarPlaySession %@"
+ "stopSyntheticCarPlaySession from pid %i rejected: missing %@ entitlement"
+ "stopSyntheticCarPlaySession: unknown session %@"
+ "stopSyntheticCarPlaySessionWithIdentifier:reply:"
+ "synthetic"
+ "synthetic descriptor missing screens[]; rejecting"
+ "synthetic descriptor's screens[0] missing 'identifier'; rejecting"
+ "synthetic session %@ announce: calling _mainQueue_startSessionForHost: with deviceID=%@"
+ "synthetic session %@ announce: failed to build CARSessionRequestHost from hostProperties=%@"
+ "synthetic session %@ announce: success=%@ error=%@"
+ "synthetic session %@ stored; posted Darwin notification"
+ "synthetic-1.0"
+ "syntheticSessions"
+ "v32@0:8@\"NSDictionary\"16@?<v@?@\"NSString\"@\"NSError\">24"
+ "waiting on start session prompt dismissed by user, canceling pairing flow"
+ "wiredCarPlaySimulator"
- "@\"NSDictionary\"24@0:8@\"CRPairingPromptFlowController\"16"
- "CRDiagnosticsAlert"
- "Failed to create statistics observation"
- "No active logging file receiver, cannot observe statistics"
- "No active logging session"
- "OK"
- "Presenting diagnostics alert: %@, timeOut Interval: %f"
- "Successfully set up vehicle statistics observer"
- "T@\"NSString\",&,N,V_bannerMessage"
- "_bannerMessage"
- "bannerMessage"
- "lookupCarcapabilitiesForSession:plistURL:completionHandler:"
- "presentWaitingOnStartSessionPrompt"
- "setBannerMessage:"
```
