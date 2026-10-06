## mediaremoted

> `/System/Library/PrivateFrameworks/MediaRemote.framework/Support/mediaremoted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42f40c` | `0x431114` | **`+0x1d08`** |
| `__TEXT.__oslogstring` | `0x27649` | `0x27a49` | **`+0x400`** |
| `__DATA.__bss` | `0x12980` | `0x12b70` | **`+0x1f0`** |
| `__DATA.__objc_data` | `0xa030` | `0x9e98` | **`-0x198`** |
| `__DATA.__objc_const` | `0x27770` | `0x275e0` | **`-0x190`** |
| `__DATA_CONST.__const` | `0x1c2c8` | `0x1c3c8` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x40745` | `0x40835` | **`+0xf0`** |
| `__TEXT.__swift5_typeref` | `0x588f` | `0x57cb` | **`-0xc4`** |
| `__TEXT.__objc_methtype` | `0x80a8` | `0x8008` | **`-0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x4ce3` | `0x4d83` | **`+0xa0`** |
| `__DATA.__data` | `0xc1b0` | `0xc120` | **`-0x90`** |
| `__TEXT.__const` | `0x10700` | `0x10790` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x2e78` | `0x2f00` | **`+0x88`** |
| `__TEXT.__cstring` | `0x1951b` | `0x1949b` | **`-0x80`** |
| `__TEXT.__objc_methlist` | `0x1554c` | `0x154cc` | **`-0x80`** |
| `__DATA_CONST.__cfstring` | `0xe3a0` | `0xe340` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0xc728` | `0xc6d0` | **`-0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x4670` | `0x4620` | **`-0x50`** |
| `__TEXT.__swift5_capture` | `0x4c30` | `0x4bec` | **`-0x44`** |
| `__TEXT.__auth_stubs` | `0x6b80` | `0x6ba0` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x6bb8` | `0x6bd8` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x274a0` | `0x274c0` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x7124` | `0x7108` | **`-0x1c`** |
| `__DATA.__common` | `0x438` | `0x450` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x35d0` | `0x35e0` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x658` | `0x648` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0xa24` | `0xa34` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x16e0` | `0x16e8` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xbff0` | `0xbfe8` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xf30` | `0xf28` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xae0` | `0xad8` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x1e0` | `0x1d8` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x4c8` | `0x4c0` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x300` | `0x308` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x5884` | `0x5888` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x1e8` | `0x1ec` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x20c` | `0x210` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-4026.100.68.0.0
+4026.110.75.1.0

-  Functions: 17668
-  Symbols:   3544
-  CStrings:  15194
+  Functions: 17651
+  Symbols:   3548
+  CStrings:  15192
Symbols:
+ _$s10Foundation4DateV026timeIntervalSinceReferenceB0Sdvg
+ _$s10Foundation4DateV1goiySbAC_ACtFZ
+ _$s10Foundation4DateV8advanced2byACSd_tF
+ _MRMediaRemoteRouteStatusErrorDomain
+ _MRRequestDetailsInitiatorBanner
+ _kMRMediaRemotePushTokensUserInfoKey
- _$s8Dispatch0A3QoSV13userInitiatedACvgZ
- _OBJC_CLASS_$_NSISO8601DateFormatter
CStrings:
+ "$__lazy_storage_$__assertedBundleIdentifiers"
+ "$__lazy_storage_$_assertionTimers"
+ "$__lazy_storage_$_assertions"
+ "$__lazy_storage_$_unboundedAssertions"
+ "(%@)"
+ ".activeSystemSession"
+ "@\"MRDRemoteSessionAssertionController\""
+ "Artificial Delay..."
+ "Assertion controller state"
+ "Bounded assertions:\n"
+ "Clearing feeds — now-playing controller could not resolve a player: %{public}s"
+ "Client requested disconnect of %@-%@"
+ "Controller reloading for invalidation — awaiting post-reload state"
+ "Error clearing paused feed: %@"
+ "Group sessions not supported"
+ "MRDRemoteSessionAssertionController"
+ "Microphone connection not supported"
+ "Paused entity expiration timer fired — clearing paused feed"
+ "RemoteSessionAssertionControllerDidUpdateAssertedBundleIdentifiers"
+ "Reset. All previous connections are invalid. (Typically due to mediaremoted crash on watch)"
+ "Retaining feeds — transient now-playing controller error: %{public}s"
+ "T@\"MRDRemoteSessionAssertionController\",&,N,V_assertionController"
+ "T@\"NSDictionary\",N,R"
+ "T@\"NSString\",C,N,V_remoteSessionAssertionControllerState"
+ "UNABLE_TO_CONNECT_ALERT_MESSAGE_FORMAT_%@_%@"
+ "UNABLE_TO_CONNECT_ALERT_MESSAGE_NO_PROTOCOL_FORMAT_%@"
+ "UNABLE_TO_CONNECT_ALERT_TITLE"
+ "Unbounded assertions:\n"
+ "Update: %{public}@<%{public}@> Artificial Delay. Waiting <%lf> seconds."
+ "Will clear paused feed"
+ "[%s] Cannot post notification to: %s, because no XPC client was found"
+ "[%s] Item: %{public}s, is not picked in session: %{public}s, connection type %{public}s does not match existing picked items: [%{public}s] -> .set"
+ "[%s] Item: %{public}s, is not picked in session: %{public}s, not RC context, connection type %{public}s does not match existing picked items: [%{public}s] -> .set"
+ "[%s] assertForBundleIdentifier - cleared assertion: %s"
+ "[%s] assertForBundleIdentifier - created assertion: %s"
+ "[%s] assertForBundleIdentifier - updated assertion: %s"
+ "[%s] handleActiveSystemEndpointDidChange - assert for active session bundle: %s"
+ "[%s] handleActiveSystemEndpointDidChange - clear active session assertion for bundle: %s"
+ "[%s] handleDisplayLayoutDidChange - assert for foreground bundles: %s"
+ "[%s] handleDisplayLayoutDidChange - clear foreground assertion for bundle: %s"
+ "[%s] setAssertedBundleIdentifiers - value: %s"
+ "[AVRoutingServer] Route Connect Error %ld: Ignoring because error for \"%{public}@\" because the status code has not changed and already prompted user."
+ "[AVRoutingServer] Route Connect Error %{public}@: %{public}@: %{public}@"
+ "[IDSCompanionRemoteControlService] Disconnecting remoteControlChannel destination=%@, session=%@, error=%@"
+ "[IDSCompanionRemoteControlService] Disconnecting remoteControlChannelForDestination=%@, session=%@, error=%@"
+ "[IDSCompanionRemoteControlService] Ignoring disconnect for unknown remoteControlChannel <%@-%@>"
+ "[MRDRRC.EVAL]"
+ "[MRDRRC].RV Current protocol is not compatible with recommended protocol: %@ vs %@. Skipping recomendation"
+ "_TtCC12mediaremoted32RemoteSessionAssertionControllerP33_D53393D704DB0D1BA555EC4116BD05189Assertion"
+ "_assertionController"
+ "_handleAssertedBundleIdentifiersDidChangeNotification:"
+ "_onWorkerQueue_disconnectRemoteControlChannelForDestination:session:error:"
+ "_publishOutputDeviceUID:forType:"
+ "_publishedOutputDeviceUIDs"
+ "_publishedUIDsLock"
+ "_remoteSessionAssertionControllerState"
+ "_routeStatusErrorWithStatus:failureReason:"
+ "assertedBundleIdentifiers"
+ "assertionController"
+ "companionRemoteControlServiceConnectionDelay"
+ "connectRemoteControlChannel"
+ "didUpdateAssertedBundleIdentifiers"
+ "externalDeviceArtificialConnectionDelay"
+ "notificationCancellables"
+ "pausedExpirationTimer"
+ "playerLastPlayingDate"
+ "protocolIdentifier"
+ "remoteSessionAssertionControllerState"
+ "remoteSessionDefaultAssertionInterval"
+ "searchEndpointsForGroupUID:timeout:details:queue:completion:"
+ "searchOutputDevices:protocolUID:timeout:details:queue:completion:"
+ "session disconnected"
+ "session ended"
+ "setAssertionController:"
+ "setProtocolIdentifier:"
+ "setRemoteSessionAssertionControllerState:"
+ "\xf1"
- "\n activeBundleIDs="
- "\nGrace Periods: "
- "<RemoteSessionAssertion: bundleID="
- "@\"MRDNowPlayingSessionAppMonitor\""
- "@\"MRDRemoteSessionAssertion\""
- "@40@0:8@16@24d32"
- "AIRPLAY_BUSY_ALERT_MESSAGE_FORMAT_%@"
- "AIRPLAY_BUSY_ALERT_TITLE"
- "AIRPLAY_BUSY_ATV_ALERT_TITLE"
- "AIRPLAY_GENERIC_ALERT_MESSAGE_FORMAT_%@"
- "AIRPLAY_NOT_CONNETED_ALERT_MESSAGE_FORMAT_%@"
- "AIRPLAY_OUT_OF_RANGE_ALERT_MESSAGE_FORMAT_%@"
- "Active Bundles: "
- "Active System Endpoint"
- "App foregrounded"
- "Artifical Delay..."
- "DeltaOTSBannerTapped"
- "MRDIDSCompanionRemoteControlService.setConnectionState"
- "MRDNowPlayingSessionAppMonitor"
- "MRDRemoteSessionAssertion"
- "MRDRemoteSessionAssertionManager"
- "MRDRemoteSessionAssertionManagerObserver"
- "Nearby device in session"
- "New replacement connection %@-%@ established"
- "RouteRecommendation.AirPlay"
- "T@\"MRDNowPlayingSessionAppMonitor\",&,N,V_appMonitor"
- "T@\"MRDRemoteSessionAssertion\",&,N,V_aseAssertion"
- "T@\"MRDRemoteSessionAssertionManager\",N,R"
- "T@\"NSString\",C,N,V_aseCurrentBundleID"
- "T@\"NSString\",C,N,V_remoteSessionAssertionManagerState"
- "TB,R,N,GisConnected"
- "TB,R,N,GisPaired"
- "[%s] Cancelled grace period for %{public}s"
- "[%s] Created assertion %{public}s for %{public}s reason: %{public}s duration: %f"
- "[%s] Created assertion for foregrounded app: %s"
- "[%s] Ended assertion %{public}s for %{public}s reason: %{public}s"
- "[%s] Ended grace period for %{public}s"
- "[%s] Notifying observers with %ld active bundle IDs"
- "[%s] Removed assertion for backgrounded app: %s"
- "[%s] Started grace period for %{public}s"
- "[AVRoutingServer] AirPlay Error %ld: %{public}@: %{public}@"
- "[AVRoutingServer] AirPlay Error %ld: Ignoring because error for \"%{public}@\" because the status code has not changed and already prompted user."
- "[IDSCompanionRemoteControlService] Disconnecting remoteControlChannel from %@-%@..."
- "[MRDNowPlayingSessionServer] ASE changed to app-vended session for %{public}@"
- "[MRDNowPlayingSessionServer] ASE moved away from app-vended session %{public}@"
- "[MRDNowPlayingSessionServer] Returning assertion info for %{public}@: %lu active bundle IDs, %lu assertions, %lu grace periods"
- "_appMonitor"
- "_aseAssertion"
- "_aseCurrentBundleID"
- "_remoteSessionAssertionManagerState"
- "_updateASEAssertionForSession:"
- "activeBundleIDs"
- "addOutputDevices:initiator:withReplyQueue:completion:"
- "appMonitor"
- "aseAssertion"
- "aseCurrentBundleID"
- "assertedBundleIDs"
- "cancelled"
- "com.apple.mediaremote.remote-session-assertions"
- "coriander"
- "createAssertionWithBundleID:reason:"
- "createAssertionWithBundleID:reason:duration:"
- "externalDeviceArtificalConnectionDelay"
- "gracePeriods"
- "handleLayoutChange"
- "isTimeBounded"
- "mediaremoted.RemoteSessionAssertion"
- "paired"
- "remoteSessionAssertionManager:didUpdateBundleIDs:"
- "remoteSessionAssertionManagerState"
- "remoteSessionGracePeriodDuration"
- "searchOutputDevices:reason:timeout:queue:completion:"
- "setAppMonitor:"
- "setAseAssertion:"
- "setAseCurrentBundleID:"
- "setRemoteSessionAssertionManagerState:"
- "stringFromDate:"
- "v32@0:8@\"MRDRemoteSessionAssertionManager\"16@\"NSSet\"24"
- "\xd1"
```
