## callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x510b90` | `0x511ec0` | **`+0x1330`** |
| `__TEXT.__oslogstring` | `0x51943` | `0x51bf3` | **`+0x2b0`** |
| `__DATA_CONST.__const` | `0x276f8` | `0x27890` | **`+0x198`** |
| `__TEXT.__objc_methname` | `0x6e907` | `0x6ea97` | **`+0x190`** |
| `__TEXT.__const` | `0xf438` | `0xf568` | **`+0x130`** |
| `__TEXT.__cstring` | `0x1b79c` | `0x1b8ac` | **`+0x110`** |
| `__DATA.__bss` | `0xdc70` | `0xdd70` | **`+0x100`** |
| `__TEXT.__objc_stubs` | `0x3c920` | `0x3c9e0` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x86b0` | `0x8760` | **`+0xb0`** |
| `__DATA.__objc_const` | `0x3f5a8` | `0x3f640` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x961c` | `0x96a4` | **`+0x88`** |
| `__TEXT.__swift5_fieldmd` | `0x6c94` | `0x6d08` | **`+0x74`** |
| `__TEXT.__swift5_typeref` | `0x9118` | `0x9156` | **`+0x3e`** |
| `__TEXT.__swift5_capture` | `0x954c` | `0x9588` | **`+0x3c`** |
| `__TEXT.__objc_methlist` | `0x291c0` | `0x291f8` | **`+0x38`** |
| `__DATA.__data` | `0xffd8` | `0x10008` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x2614` | `0x2644` | **`+0x30`** |
| `__DATA.__objc_data` | `0xe218` | `0xe240` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x13598` | `0x135c0` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x12d86` | `0x12da6` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x950` | `0x968` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xeb80` | `0xeb98` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x6cc` | `0x6e0` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x14a8` | `0x14b8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x5a30` | `0x5a40` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x58c2` | `0x58d2` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x690` | `0x69c` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x2d28` | `0x2d30` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x90c` | `0x914` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2004` | `0x2008` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1616.100.2.2.1
+1620.100.1.2.3

-  Functions: 28330
-  Symbols:   2934
-  CStrings:  24117
+  Functions: 28340
+  Symbols:   2935
+  CStrings:  24138
Symbols:
+ _TUShouldUseSuperboxTelephonyProvider
CStrings:
+ "-[CSDCallStateController pickLocalRouteWithUniqueIdentifier:shouldWaitUntilAvailable:routeSelectionProvenance:]"
+ "-[CSDCallStateController pickPairedHostDeviceRouteWithUniqueIdentifier:shouldWaitUntilAvailable:routeSelectionProvenance:]"
+ "Clearing out pickWhenAvailable route %@ because user is picking available route %@"
+ "Dispatching invokeAudioSessionActivationStateChangedHandler onto observer's queue with active: %d"
+ "HoldTimePredictionError"
+ "Ignoring superseded Siri voice change (generation %ld)"
+ "Not picking prematurely selected audio route because it's a Speaker route originally selected for voicemail"
+ "Not pushing uplinkMuted %d to conference for call %@ since call should not own the mute handler under session-based muting"
+ "Picking local route with identifier: %@ (routeSelectionProvenance: %ld)"
+ "Picking paired device with identifier %@ (routeSelectionProvenance: %ld)"
+ "Re-asserting secondary camera opt-in for participant %llu on remote enable"
+ "Route %@ did not become available in %@ seconds"
+ "Siri output voice changed; debouncing call screening regeneration"
+ "Stopping waiting for route %@ to become available"
+ "T@\"NSNotificationCenter\",R,N,V_notificationCenter"
+ "Thumper calling unsupported for sender identity %@ (labelID %@): CT isSupported=%d, IDS thumperServiceEnabledForLabel=%d"
+ "Thumper calling unsupported for sender identity %@: empty telephony subscription label identifier"
+ "Vv36@0:8@\"NSString\"16B24q28"
+ "Vv36@0:8@16B24q28"
+ "Will pick route %@ when it becomes available to pick"
+ "[WARN] initWithTUConversation: conversation %@ has no provider identifier; not stamping %@ into context"
+ "_notificationCenter"
+ "_shouldLaunchInCallApplicationForCall:"
+ "_shouldLaunchInCallApplicationForCall: %d"
+ "_startObservingNotifications"
+ "conversationManager:conversationWillBeRemoved:"
+ "deviceIsGreenTea"
+ "eligibleToEnable"
+ "holdTimePrediction"
+ "initWithQueue:assistantServicesObserver:chManager:featureFlags:deviceSupport:notificationCenter:"
+ "notifyDelegatesOfConversationThatWillBeRemoved:"
+ "pickLocalRouteWithUniqueIdentifier:shouldWaitUntilAvailable:routeSelectionProvenance:"
+ "pickPairedHostDeviceRouteWithUniqueIdentifier:shouldWaitUntilAvailable:routeSelectionProvenance:"
+ "pickRouteWithUniqueIdentifier:shouldWaitUntilAvailable:routeSelectionProvenance:"
+ "pickWhenAvailableRoute"
+ "route: %@ (routeSelectionProvenance: %ld)"
+ "setEligibleToEnable:"
+ "voiceChangeGenerationDebouncer"
- "-[CSDCallStateController pickLocalRouteWithUniqueIdentifier:shouldWaitUntilAvailable:]"
- "-[CSDCallStateController pickPairedHostDeviceRouteWithUniqueIdentifier:shouldWaitUntilAvailable:]"
- "Clearing out pickWhenAvailable route identifier %@ because user is picking available route %@"
- "Not picking prematurely selected audio route because it's Speaker"
- "Picking local route with identifier: %@"
- "Picking paired device with identifier %@"
- "Route identifier %@ did not become available in %@ seconds"
- "Siri output voice changed and the call screening needs to be regenerated!"
- "Stopping waiting for route identifier %@ to become available"
- "Vv28@0:8@\"NSString\"16B24"
- "Will pick route identifier %@ when it becomes available to pick"
- "_shouldLaunchInCallApplicationForProviderOfCall:"
- "initWithQueue:assistantServicesObserver:chManager:featureFlags:deviceSupport:"
- "pickLocalRouteWithUniqueIdentifier:shouldWaitUntilAvailable:"
- "pickPairedHostDeviceRouteWithUniqueIdentifier:shouldWaitUntilAvailable:"
- "pickRouteWithUniqueIdentifier:shouldWaitUntilAvailable:"
- "pickWhenAvailableRouteIdentifier"
```
