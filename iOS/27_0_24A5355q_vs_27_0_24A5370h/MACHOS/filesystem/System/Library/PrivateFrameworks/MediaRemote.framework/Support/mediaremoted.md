## mediaremoted

> `/System/Library/PrivateFrameworks/MediaRemote.framework/Support/mediaremoted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x432a04` | `0x42f40c` | **`-0x35f8`** |
| `__TEXT.__objc_methname` | `0x40145` | `0x40745` | **`+0x600`** |
| `__TEXT.__objc_stubs` | `0x27240` | `0x274a0` | **`+0x260`** |
| `__DATA.__objc_const` | `0x27590` | `0x27770` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x27779` | `0x27649` | **`-0x130`** |
| `__TEXT.__eh_frame` | `0x6ac8` | `0x6bb8` | **`+0xf0`** |
| `__DATA.__objc_selrefs` | `0xbf20` | `0xbff0` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x1548c` | `0x1554c` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x5941` | `0x588f` | **`-0xb2`** |
| `__TEXT.__cstring` | `0x1946b` | `0x1951b` | **`+0xb0`** |
| `__DATA.__objc_data` | `0xa0c0` | `0xa030` | **`-0x90`** |
| `__DATA_CONST.__cfstring` | `0xe320` | `0xe3a0` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x4c63` | `0x4ce3` | **`+0x80`** |
| `__DATA.__data` | `0xc140` | `0xc1b0` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x4bcc` | `0x4c30` | **`+0x64`** |
| `__TEXT.__const` | `0x10760` | `0x10700` | **`-0x60`** |
| `__TEXT.__constg_swiftt` | `0x70c4` | `0x7124` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1c278` | `0x1c2c8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xc6e8` | `0xc728` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x16c0` | `0x16e0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x6b60` | `0x6b80` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x4966` | `0x4946` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x80c8` | `0x80a8` | **`-0x20`** |
| `__DATA.__bss` | `0x12970` | `0x12980` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x35c0` | `0x35d0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2e68` | `0x2e78` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x4d8` | `0x4c8` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0xf38` | `0xf30` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xae8` | `0xae0` | **`-0x8`** |
| `__TEXT.__swift5_fieldmd` | `0x4678` | `0x4670` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x5888` | `0x5884` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.100.60.1.0
+4026.100.68.0.0

-  Functions: 17662
-  Symbols:   3539
-  CStrings:  15147
+  Functions: 17668
+  Symbols:   3544
+  CStrings:  15194
Symbols:
+ _$s12MediaControl11PreferencesC34enableDiscoverylessEndpointEntriesSbvgZ
+ _$s12MediaControl14RoutingSessionV14NowPlayingInfoV9PublisherV27applicationBundleIdentifierSSvg
+ _$s12MediaControl14RoutingSessionV14NowPlayingInfoV9publisherAE9PublisherVvg
+ _$s12MediaControl14RoutingSessionV14nowPlayingInfoAC03NowfG0VSgvg
+ _$s12MediaControl15RoutingControlsV022RequestAdditionalItemsB0V17sessionIdentifier4kindAESS_AE4KindOtcfC
+ _$s12MediaControl15RoutingControlsV022RequestAdditionalItemsB0V4KindO15findAndShowMoreyA2GmFWC
+ _$s12MediaControl15RoutingControlsV022RequestAdditionalItemsB0V4KindO8findMoreyA2GmFWC
+ _$s12MediaControl15RoutingControlsV022RequestAdditionalItemsB0V4KindO8showMoreyA2GmFWC
+ _$s12MediaControl15RoutingControlsV022RequestAdditionalItemsB0V4KindOMa
+ _MRAVEndpointDidBecomeStaleNotification
- _$s10Foundation4DateV13distantFutureACvgZ
- _$s12MediaControl15RoutingControlsV022RequestAdditionalItemsB0V17sessionIdentifierAESS_tcfC
- _$sShyxGSHsMc
- _$sSq16debugDescriptionSSvg
- _MRMediaRemoteApplicationIsSystemClassicalRoomApplication
CStrings:
+ "    clusterLeaderAttempt = %lu/%lu\n"
+ "    clusterLeaderLastError = %@\n"
+ "    clusterLeaderNextRetry = %@ (in %.1fs)\n"
+ "    groupLeaderAttempt = %lu/%lu\n"
+ "    groupLeaderLastError = %@\n"
+ "    groupLeaderNextRetry = %@ (in %.1fs)\n"
+ "$__lazy_storage_$_discoveryRequiredTargetedGroupIdentifiers"
+ "$__lazy_storage_$_dismissedPlaybackSessionIdentifiers"
+ "$__lazy_storage_$_targetedGroupIdentifiers"
+ "$__lazy_storage_$_unmappedTargetedItems"
+ ", requiresDiscovery: "
+ "Client %{public}@ failed to reply to command (commandID=%{public}@) with error=%@"
+ "Command is an AVRCP command: skipping straight to call observer check to determine whether we should ignore the command or not. (commandID=%{public}@)"
+ "ConnectToGroupLeaderDelay"
+ "Discovery Mode: "
+ "Ignoring command because a phone call or FaceTime is active. (commandID=%{public}@)"
+ "Ignoring command because of active SharePlay activity. (commandID=%{public}@)"
+ "MRDConnectToClusterLeaderOperation"
+ "MRDConnectToGroupLeaderOperation"
+ "PreemptiveRemoteControlConnectionManager.connectToClusterLeaderOperation"
+ "PreemptiveRemoteControlConnectionManager.connectToGroupLeaderOperation"
+ "RestrictedCommandClients Mode - launch suppressed"
+ "Simulating launch failure for %{public}@ with error=%@"
+ "T@\"NSDate\",&,N,V_clusterLeaderNextRetryDate"
+ "T@\"NSDate\",&,N,V_groupLeaderNextRetryDate"
+ "T@\"NSError\",&,N,V_clusterLeaderLastError"
+ "T@\"NSError\",&,N,V_groupLeaderLastError"
+ "T@\"NSString\",&,N,V_suppressedBundleID"
+ "TQ,N,V_clusterLeaderAttempt"
+ "TQ,N,V_clusterLeaderRetryGeneration"
+ "TQ,N,V_groupLeaderAttempt"
+ "TQ,N,V_groupLeaderRetryGeneration"
+ "Targeted Group Identifiers:\n  "
+ "Targeted Items:\n  "
+ "The client that registered the custom origin %{public}@ no longer exists, so this command will be ignored. (commandID=%{public}@)"
+ "Update: %{public}@<%{public}@> Rejecting endpoint %@ because not our discoverable groupLeader"
+ "Using previously routed app %{public}@ for context %{public}@ (commandID=%{public}@)"
+ "[%s] handleConnectedEntry<%s> - endpoint disconnected"
+ "[%s] handleConnectedEntry<%s> - endpoint is stale"
+ "[%s] handleSetActiveItem<%{public}s> - existing session for item: %{public}s cannot start native playback. Falling through to create a fresh endpoint"
+ "[%s] routeRecommendationDismissed - no complete session found for dismissed recommendation: %s"
+ "[%s] routeRecommendationDismissed - suppressing playback session: %s for dismissed recommendation: %s"
+ "[%s] setDiscoveryIsStable - value: %{bool,public}d"
+ "[%s] setShouldSuppressLocalRecommendation - value: %{bool}d"
+ "[%s] setTargetedGroupIdentifiers - value: %{public}s"
+ "[%s] setTargetedItemIdentifiers - value: %{public}s"
+ "[%s] updateDiscovery - enable because entries: %s require discovery and targeted items: %s have no entry"
+ "[PreemptiveRemoteControlConnectionManager] Scheduling clusterLeader reconnect %.1fs after disconnect"
+ "[PreemptiveRemoteControlConnectionManager] Scheduling clusterLeader retry %lu/%lu in %.1fs"
+ "[PreemptiveRemoteControlConnectionManager] Scheduling groupLeader reconnect %.1fs after disconnect"
+ "[PreemptiveRemoteControlConnectionManager] Scheduling groupLeader retry %lu/%lu in %.1fs"
+ "[PreemptiveRemoteControlConnectionManager] clusterLeader disconnected: %{public}@"
+ "[PreemptiveRemoteControlConnectionManager] clusterLeader retry budget exhausted (%lu attempts); waiting for topology change"
+ "[PreemptiveRemoteControlConnectionManager] groupLeader disconnected: %{public}@"
+ "[PreemptiveRemoteControlConnectionManager] groupLeader retry budget exhausted (%lu attempts); waiting for topology change"
+ "[RestrictedCommandClients Mode] Suppressing launch of %{public}@ for command %@"
+ "_clearClusterLeaderRetry"
+ "_clearGroupLeaderRetry"
+ "_clusterLeaderAttempt"
+ "_clusterLeaderLastError"
+ "_clusterLeaderNextRetryDate"
+ "_clusterLeaderRetryGeneration"
+ "_endpointShouldPostVolumeNotifications:outputDevice:externalDevice:"
+ "_endpointSupportsVolumeControl:externalDevice:"
+ "_executeAfterDelay"
+ "_findEndpointContainingGroupID:andDeviceID:deviceInfo:requestID:completion:"
+ "_groupLeaderAttempt"
+ "_groupLeaderLastError"
+ "_groupLeaderNextRetryDate"
+ "_groupLeaderRetryGeneration"
+ "_handleClusterLeaderDidDisconnect:"
+ "_handleGroupLeaderDidDisconnect:"
+ "_isEndpointsDesignatedGroupLeader:externalDevice:"
+ "_reevaluateVolumeControlCapabilitiesForEndpoint:externalDevice:"
+ "_scheduleClusterLeaderRetryIfNeeded"
+ "_scheduleGroupLeaderRetryIfNeeded"
+ "_suppressedBundleID"
+ "adjustVolume:details:queue:completion:"
+ "canStartNativePlayback"
+ "clusterLeaderAttempt"
+ "clusterLeaderLastError"
+ "clusterLeaderNextRetryDate"
+ "clusterLeaderRetryGeneration"
+ "discoveryIsStable"
+ "discoveryStabilityToken"
+ "dismissed playback session: "
+ "groupLeaderAttempt"
+ "groupLeaderLastError"
+ "groupLeaderNextRetryDate"
+ "groupLeaderRetryGeneration"
+ "isMirroringActive"
+ "mr_outputDevicesIncludingClusterMembers"
+ "retryPending"
+ "setClusterLeaderAttempt:"
+ "setClusterLeaderLastError:"
+ "setClusterLeaderNextRetryDate:"
+ "setClusterLeaderRetryGeneration:"
+ "setGroupLeaderAttempt:"
+ "setGroupLeaderLastError:"
+ "setGroupLeaderNextRetryDate:"
+ "setGroupLeaderRetryGeneration:"
+ "setSuppressedBundleID:"
+ "sharedSystemScreenLocalEndpoint"
+ "shouldSuppressLocalRecommendation"
+ "simulatedLaunchApplicationError"
+ "suppressedBundleID"
+ "targetedItemIdentifiers"
- "$__lazy_storage_$_dismissedGroups"
- ".observingDismissedRecommendations"
- ".observingLocalOnly"
- "@\"MRDClientSuppressionController\""
- "Client %{public}@ failed to reply to command with error=%@"
- "Command is an AVRCP command: skipping straight to call observer check to determine whether we should ignore the command or not."
- "ElectedPlayerSuppressionLapseDates"
- "Ignoring command because a phone call or FaceTime is active."
- "Ignoring command because of active SharePlay activity."
- "MRDClientSuppressionController"
- "MRDConenctToClusterLeaderOperation"
- "MRDConenctToGroupLeaderOperation"
- "PreemptiveRemoteControlConnectionManager.conenctToClusterLeaderOperation"
- "PreemptiveRemoteControlConnectionManager.conenctToGroupLeaderOperation"
- "Targeted Identifiers:\n  "
- "The client that registered the custom origin %{public}@ no longer exists, so this command will be ignored."
- "Using previously routed app %{public}@ for context %{public}@"
- "[%s] Cleared suppression for client %{public}s"
- "[%s] Client %{public}s is currently playing, lapse date was already at future"
- "[%s] Client %{public}s is currently playing, setting to future"
- "[%s] Client %{public}s is playing but suppression has lapsed (lapse date was %{public}s), removing"
- "[%s] Client %{public}s is playing on at least one origin, resetting suppression timer (distantFuture)"
- "[%s] Client %{public}s is still playing on at least one origin, keeping suppression timer paused (distantFuture)"
- "[%s] Client %{public}s paused on all origins and was previously playing, starting suppression timer (lapse at %{public}s)"
- "[%s] Client %{public}s paused on all origins, but lapse date was already set (lapse at %{public}s)"
- "[%s] Client %{public}s suppression timer still running (lapse at %{public}s)"
- "[%s] Client %{public}s was playing when stored but is no longer playing, setting lapse date now (lapse at %{public}s)"
- "[%s] Failed to parse notification: %s"
- "[%s] Loaded %ld suppression lapse date(s) from persistence"
- "[%s] Populated playing client origins from server: %ld bundle(s) playing"
- "[%s] Startup: Client %{public}s is playing on origin %{public}s"
- "[%s] Suppressing client %{public}s (currently paused on all origins, lapse at %{public}s)"
- "[%s] Suppressing client %{public}s (currently playing on some origin, timer paused)"
- "[%s] Suppression for %{public}s has lapsed (lapse date was %{public}s), removing"
- "[%s] Suppression for %{public}s has lapsed (lapse date: %{public}s), removing"
- "[%s] routeRecommendationDismissed - group: %s for dismissed recommendation: %s is already tracked as dismissed"
- "[%s] routeRecommendationDismissed - no session found for dismissed recommendation: %s"
- "[%s] routeRecommendationDismissed - suppressing topology: %s, for playback session: %s"
- "[%s] setDismissedGroups - value: %s"
- "[%s] setTargetedIdentifiers - value: %{public}s"
- "[%s] update - clear suppressed group: %s"
- "[%s] update - suppress dismissed groups: %s"
- "[%s] updateDiscovery - enable because of targeted identifiers"
- "[MRDAVHostedExternalDevice] Hosted endpoint <%{public}@> reevaluating volume control because %{public}@ changed from <%{public}@> to <%{public}@>"
- "_clientSuppressionController"
- "_endpointShouldPostVolumeNotifications:outputDevice:"
- "_endpointSupportsVolumeControl:"
- "_findEndpointContainingGroupID:andDeviceID:requestID:completion:"
- "_onSerialQueue_isEndpointsDesignatedGroupLeader:"
- "_reevaluateVolumeControlCapabilitiesForEndpoint:"
- "clearSuppressionForClient:"
- "create remoteControlConnection to clusterLeader"
- "create remoteControlConnection to groupLeader"
- "dismissed groups updated"
- "dismissedActivitySuppressionInterval"
- "electedPlayerSuppressionLapseDates"
- "setElectedPlayerSuppressionLapseDates:"
- "systemAppMatchers"
- "targetedIdentifiers"
- "topology"
```
