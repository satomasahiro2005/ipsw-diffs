## identityservicesd

> `/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/identityservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xabbdac` | `0xac2d88` | **`+0x6fdc`** |
| `__TEXT.__oslogstring` | `0x882ed` | `0x88a8d` | **`+0x7a0`** |
| `__TEXT.__objc_methname` | `0x7b635` | `0x7bac5` | **`+0x490`** |
| `__TEXT.__cstring` | `0x5962e` | `0x59a3e` | **`+0x410`** |
| `__TEXT.__objc_stubs` | `0x49e20` | `0x4a120` | **`+0x300`** |
| `__DATA_CONST.__cfstring` | `0x36300` | `0x365c0` | **`+0x2c0`** |
| `__DATA.__objc_const` | `0x522a0` | `0x52520` | **`+0x280`** |
| `__DATA_CONST.__got` | `0x4368` | `0x45d0` | **`+0x268`** |
| `__DATA_CONST.__const` | `0x30bc0` | `0x30dd0` | **`+0x210`** |
| `__TEXT.__objc_methlist` | `0x2c2b4` | `0x2c414` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x16ee0` | `0x17018` | **`+0x138`** |
| `__DATA.__objc_data` | `0xf680` | `0xf7a8` | **`+0x128`** |
| `__TEXT.__swift5_reflstr` | `0x8f65` | `0x9085` | **`+0x120`** |
| `__DATA.__bss` | `0x24cd0` | `0x24dd0` | **`+0x100`** |
| `__DATA.__objc_selrefs` | `0x16cf0` | `0x16dd0` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x24410` | `0x2434c` | **`-0xc4`** |
| `__TEXT.__constg_swiftt` | `0x7e90` | `0x7f50` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x992c` | `0x99e8` | **`+0xbc`** |
| `__TEXT.__objc_methtype` | `0x14349` | `0x143e9` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0xa10e` | `0xa1a8` | **`+0x9a`** |
| `__DATA.__data` | `0x16880` | `0x167f0` | **`-0x90`** |
| `__TEXT.__eh_frame` | `0x12794` | `0x1281c` | **`+0x88`** |
| `__TEXT.__auth_stubs` | `0x7680` | `0x7700` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x2108` | `0x2180` | **`+0x78`** |
| `__TEXT.__const` | `0x6e520` | `0x6e590` | **`+0x70`** |
| `__TEXT.__objc_classname` | `0x8930` | `0x8980` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x3b50` | `0x3b90` | **`+0x40`** |
| `__DATA_CONST.__auth_ptr` | `0xea8` | `0xed8` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x34ec` | `0x3508` | **`+0x1c`** |
| `__DATA_CONST.__objc_intobj` | `0x1aa0` | `0x1ab8` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x14b8` | `0x14c0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x940` | `0x948` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1008` | `0x100c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__ustring`

### Other Changes

```diff

-1996.100.2.2.2
+1998.100.2.0.0

-  Functions: 32259
-  Symbols:   2935
-  CStrings:  32902
+  Functions: 32339
+  Symbols:   2949
+  CStrings:  32993
Symbols:
+ _IDSDeviceTypeFromProductName
+ _OBJC_CLASS_$_IDSUTunControlChannelRestartMetric
+ _OBJC_CLASS_$__TtC17identityservicesd23IDSGroupAgentController
+ _OBJC_METACLASS_$__TtC17identityservicesd23IDSGroupAgentController
+ _SecTaskCopySigningIdentifier
+ _SecTaskCopyTeamIdentifier
+ _SecTaskCreateWithAuditToken
+ _SecTaskGetCodeSignStatus
+ _kIDSGlobalLinkGroupAgentPublicKeyParticipantIDKey
+ _kIDSGlobalLinkGroupAgentPublicKeyPayloadKey
+ _kIDSGlobalLinkGroupAgentPublicKeyRelayIDKey
+ _kIDSGlobalLinkGroupAgentPublicKeySignedPayloadKey
+ _kIDSTapToRadarDeviceClassesKey
+ _kIDSTapToRadarRemoteDeviceSelectionsKey
+ _nw_agent_client_get_uuid
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "\nlastGDR:\n"
+ "        Transparency: kt(%@-%@)"
+ "        Transparency: kt(%@-%@)\n"
+ "  %@  (%.0f s ago)\n"
+ "  (never)\n"
+ "  Found bad alias, owned by sibling phone account: %@ => %@"
+ "  Found bad vetted alias, owned by sibling phone account: %@ => %@"
+ "  token: %@\n    added:   %@\n    removed: %@\n    deviceType: %@ (%ld)\n"
+ " => Phone aliases to filter: %@"
+ " => Skipping alias owned by sibling phone account: %@"
+ "%@: client %@ encode_ids_connection with connection %@, lcid:%@, rcid:%@, remote nw_interface_type:%d"
+ "%@: client %@ invoking nw_candidate_encode_endpoint_for_ids_connection with remote public key: %@ with length: %lu and bonjour service name: %@"
+ "%@: client %@ invoking nw_candidate_endpoint_for_ids_connection!"
+ "%@: client %@ storing evaluator:%@, responding with endpoints: %@"
+ "%s: initialized for sessionID: %s"
+ "%s: sessionID is nil!"
+ "%s: sessionID: %@ does not match: %s"
+ "%s: sessionID: %s, keyCount: %ld"
+ "%s: sessionID: %s, size: %ld"
+ "%{public}s called more than once; ignoring duplicate. {pushUUID: %{public}s, batchIdentifier: %{public}s}"
+ "(unknown:%ld)"
+ "16:49:52"
+ "<%@> link:%@ didReceiveGroupAgentKeyMaterial from %@ to %@"
+ "<%@> link:%@ didReceiveReliableUnicastServerMaterial:%@"
+ "<none>"
+ "@\"_TtC17identityservicesd23IDSGroupAgentController\""
+ "@36@0:8B16d20Q28"
+ "@88@0:8@16@24@32I40@44@52@60@68@76B84"
+ "ALLOWING 1st-party caller missing entitlements"
+ "Account store not loaded yet; deferring SIM->user synchronization until accounts are available"
+ "AppleTV"
+ "AppleWatch"
+ "AudioAccessory"
+ "B64@0:8@16@24i32@36@44B52@?56"
+ "Called [NRDevicePreferences setQuickRelayPresence:] {presence:%d}"
+ "Checking existing dependent registration count=%ld (notifiable=%ld)"
+ "Checking extended offline period extendedOffline=%d lastGDRdate=%f threshold=%f"
+ "Desktop"
+ "DeviceType"
+ "EnforceFirstPartyListeners"
+ "Error fetching off-grid fallback tokens from sender key cache: %@"
+ "Falling back to %ld tokens from sender key cache for off-grid sender key selection"
+ "First-party listener enforcement %{public}s - signingID=%{public}@ processName=%{public}@ pid=%d services=%@"
+ "IDSNWSocketPairConnection: _startOutgoingStallTimer: stall time: %f seconds"
+ "IncomingBatchMessage"
+ "Jun 27 2026"
+ "Nearby"
+ "NewDeviceAlert"
+ "Not adding registered phone alias {uniqueID: %@, phoneAlias: %@}"
+ "REJECTING 3rd-party caller with no entitlements"
+ "Reality"
+ "Sending IDS register request to server"
+ "T@\"IDSCoreAnalyticsLogger\",&,N,V_coreAnalyticsLogger"
+ "T@\"IDSPersistentMap\",&,N,V_lastGDRDate"
+ "T@?,N,R"
+ "TB,R,N,V_isPlatformBinary"
+ "TB,R,N,V_shown"
+ "TQ,R,N,V_suppressionReason"
+ "Ti,N,V_restartAttempts"
+ "Tq,N,V_deviceType"
+ "UPDATE firewall_record SET last_seen_date = ?, last_modified_date = ? WHERE handle = ? AND category = ? AND is_donated = ?;"
+ "Unable to sign IDSGroupAgent Public Key Blob with error :%@"
+ "Under first data protection lock - deferring batchset processing."
+ "[%@] [TTR] [Local] IDS UTun connection reported issues"
+ "_TtC17identityservicesd23IDSGroupAgentController"
+ "_cleanupAppleIDAliasesForPhoneAccount:"
+ "_deviceType"
+ "_groupAgentController"
+ "_isPlatformBinary"
+ "_isRecoveringFromExtendedOffline"
+ "_lastGDRDate"
+ "_newSetupInfoWithContext:entitlements:isPlatformBinary:"
+ "_notifiableRegistrationCountForService:"
+ "_phoneAliasIsAuthoritativelyOwnedByPhoneNumberAccount:"
+ "_phoneAliasesToFilter"
+ "_priorityBoostedTopicsMap"
+ "_restartAttempts"
+ "_setupListenerConnection:listenerID:pid:setupInfo:entitlements:isPlatformBinary:setupCompletionBlock:"
+ "_shouldProvideSetupInfoForEntitlements:isPlatformBinary:"
+ "_shown"
+ "_suppressionReason"
+ "browse_handler: client %@ already called for serviceName: %@"
+ "browse_handler: client %@ could not create session."
+ "browse_handler: client %@ failed to copy public key from options=%@, parameters=%@\n"
+ "browse_handler: client %@ failed to find QUIC protocol options from parameters=%@\n"
+ "browse_handler: client %@ invalid message invitation type: %lu from destination: %@"
+ "browse_handler: client %@ isClient: %d\n"
+ "browse_handler: client %@ local public key: %@ with length: %lu"
+ "browse_handler: client %@ no advertise descriptor available"
+ "browse_handler: client %@ not an application service advertise descriptor, found type=%d"
+ "browse_handler: client %@ received invitation, message: %@ from destination: %@"
+ "browse_handler: client %@ stop: no advertise descriptor available"
+ "browse_handler: client %@ stop: not an application service advertise descriptor, found type=%d"
+ "browse_handler: stop_browse_handler called for client:%@ serviceName:%@"
+ "computedOnlyAccountInfoKeys"
+ "containsValueForKey:"
+ "deinit: deallocating for sessionID: %s"
+ "didReceiveGroupAgentKeyMaterial - alternateDelegate:%@ from %@ to %@"
+ "failed"
+ "failureIgnored"
+ "flow_handler: client %@ assigning local endpoint %@ for resolved endpoint %@"
+ "flow_handler: client %@ has no endpoint and is not a listener, assigning nil"
+ "flow_handler: client %@ starting flow to %@\n"
+ "flow_handler: client %@ stopped flow to endpoint %@\n"
+ "iPad"
+ "iPhone"
+ "iPod"
+ "identityservicesd.IDSGroupAgentController"
+ "ids-utun-ttr-stall-timeout"
+ "init(sessionID:reliableUnicastRegistrationCompletionBlock:)"
+ "initWithASQUICEnabled:"
+ "initWithKTValidation:KTState:ktError:"
+ "initWithKeyTransparencyVerifier:peerIDManager:messageEnforcementEnabled:"
+ "initWithRemoteObject:localObject:ID:capabilities:entitlements:services:notificationServices:commands:bundleID:isPlatformBinary:"
+ "initWithSessionID:reliableUnicastRegistrationCompletionBlock:"
+ "initWithShown:timeSinceRemoval:suppressionReason:"
+ "initWithToken:dateAdded:deviceType:"
+ "initWithUTunPriority:connectionTime:isASQUIC:"
+ "internalStartConnectionWithEndpoint:service:parameters:serviceConnector:trafficClass:priority:isASQUIC:completionHandler:"
+ "isPlatformBinary"
+ "ktState"
+ "lastGDRDate is nil"
+ "link:didReceiveGroupAgentKeyMaterial:fromParticipantID:toParticipantID:"
+ "localKeyMaterialSigningHandler called!"
+ "localPublicKeyBlob"
+ "markGDRProcessed:"
+ "optIn"
+ "priorityBoost"
+ "publicKeyVerifySignedData from %@ to %@"
+ "publicKeyVerifySignedData: failed to verify signature with error: %@"
+ "publicKeyVerifySignedData: succeeded to verify signature with error: %@"
+ "reliableUnicastRegistrationCompletionBlock"
+ "resolveEndpoint:withParams:options:agentResolveResponse:clientID:"
+ "resolve_handler: client %@ could not create session."
+ "resolve_handler: client %@ failed to copy public key from options=%@, parameters=%@\n"
+ "resolve_handler: client %@ failed to find QUIC protocol options from parameters=%@\n"
+ "resolve_handler: client %@ invalid message response type: %lu from destination: %@"
+ "resolve_handler: client %@ isClient: %d\n"
+ "resolve_handler: client %@ local public key: %@ with length: %lu"
+ "resolve_handler: client %@ remote accepted invitation, message: %@ from destination: %@"
+ "resolve_handler: client %@ remote declined invitation, message: %@ from destination: %@"
+ "resolve_handler: client %@ resolve request for endpoint %@\n"
+ "resolve_handler: client %@ resolveEndpoint"
+ "resolve_handler: client %@ responding with endpoints %@"
+ "resolve_handler: client %@ response destination %@ is not in destination array %@."
+ "resolve_handler: stop_resolve_handler called for client %@ endpoint:%@"
+ "resolve_handler: stop_resolve_handler called for client:%@ endpoint:%@"
+ "restartAttempts"
+ "sender-key-offgrid-cache-fallback-enabled"
+ "setCoreAnalyticsLogger:"
+ "setDeviceType:"
+ "setGroupAgentLocalPublicKeyBlob:"
+ "setLastGDRDate:"
+ "setLocalParticipantID(_:sessionID:)"
+ "setLocalParticipantID:sessionID:"
+ "setLocalPublicKeyBlob:"
+ "setLocalPublicKeyData(_:localKeyMaterialSigningHandler:)"
+ "setLocalPublicKeyData:localKeyMaterialSigningHandler:"
+ "setPriorityBoostedTopics:"
+ "setQuickRelayPresence:"
+ "setReliableUnicastServerMaterial(_:)"
+ "setReliableUnicastServerMaterial:"
+ "setRemotePublicKeyData(_:)"
+ "setRemotePublicKeyData:"
+ "setRestartAttempts:"
+ "setWithCapacity:"
+ "shown"
+ "startControlChannelWithDevice %@ detected control channel set up issue, restarting. Attempt: %d"
+ "suppressionReason"
+ "tokenAdded:forService:ownPushToken:registrationDate:hardwareVersion:"
+ "v48@0:8@16@\"NSData\"24@\"NSNumber\"32@\"NSNumber\"40"
+ "v72@0:8@16r*24@32@40i48q52B60@?64"
+ "wasProcessed(message:)"
+ "wasStored(guid:)"
- "\nlastGDRDateMap:\n"
- "        Transparency: kt(%@)"
- "        Transparency: kt(%@)\n"
- "  (empty)\n"
- "  Found bad alias, it was my phone number: %@ => %@"
- "  Found bad vetted alias, it was my phone number: %@ => %@"
- "  token: %@\n    added:   %@\n    removed: %@\n"
- "  token: %@  lastGDR: %@  (%.0f s ago)\n"
- " => Found my phone numbers: %@"
- " => Not adding, this is my phone number"
- "%@: encode_ids_connection with connection %@, lcid:%@, rcid:%@, remote nw_interface_type:%d"
- "%@: invoking nw_candidate_encode_endpoint_for_ids_connection with remote public key length: %lu"
- "%@: invoking nw_candidate_endpoint_for_ids_connection!"
- "%@: storing evaluator:%@, responding with endpoints: %@"
- "22:13:37"
- "<%@> link:%@ didReceiveReliableUnicastServerMaterial:%@, Registration Completion block is nil!"
- "@84@0:8@16@24@32I40@44@52@60@68@76"
- "B60@0:8@16@24i32@36@44@?52"
- "Checking existing dependent registration count=%ld"
- "Checking extended offline period extendedOffline=%d ownToken=%@, mapKeyCount=%lu lastGDRdate=%f threshold=%f"
- "Client starting flow to %@\n"
- "Client stopped flow to endpoint %@\n"
- "DeviceAddedAlertShown"
- "EnforceEntitlementCheckForListeners"
- "IDSGroupSessionMessageParticipantUpdateTypeKeyExchangeRequest"
- "IDSGroupSessionMessageParticipantUpdateTypeKeyExchangeResponse"
- "Jun 16 2026"
- "Not adding registered phone alias to appleID account {uniqueID: %@, phoneAlias: %@}"
- "Received incoming Group Session Message: %@"
- "Rejecting listener setup for portName %@ pid %d: caller holds no IDS entitlements"
- "T@\"IDSPersistentMap\",&,N,V_lastGDRDateMap"
- "TimeSinceRemoval"
- "[%@] IDS UTun connection reported issues"
- "_existingRegistrationCountForService:"
- "_isRecoveringFromExtendedOfflineForPushToken:"
- "_lastGDRDateMap"
- "_newSetupInfoWithContext:entitlements:"
- "_reliableUnicastRegistrationCompletionBlock"
- "_setupListenerConnection:listenerID:pid:setupInfo:entitlements:setupCompletionBlock:"
- "browse_handler: Failed to copy public key from options=%@, parameters=%@, agent_client=%@\n"
- "browse_handler: Failed to find QUIC protocol options from parameters=%@, agent_client=%@\n"
- "browse_handler: No advertise descriptor available"
- "browse_handler: Not an application service advertise descriptor, found type=%d"
- "browse_handler: already called for serviceName: %@"
- "browse_handler: could not create session."
- "browse_handler: invalid message invitation type: %lu from destination: %@"
- "browse_handler: isClient: %d\n"
- "browse_handler: local public key length: %lu"
- "browse_handler: received invitation, message: %@ from destination: %@"
- "browse_handler: received key exchange request, message: %@ from destination: %@"
- "failing"
- "initWithKeyTransparencyVerifier:messageEnforcementEnabled:"
- "initWithRemoteObject:localObject:ID:capabilities:entitlements:services:notificationServices:commands:bundleID:"
- "initWithTimeSinceRemoval:"
- "initWithUTunPriority:connectionTime:"
- "internalStartConnectionWithEndpoint:service:parameters:serviceConnector:trafficClass:priority:completionHandler:"
- "lastGDRDate is nil (ownToken=%@, mapKeyCount=%lu)"
- "lastGDRDateMap"
- "markGDRProcessedForPushToken:date:"
- "optOutFailing"
- "resolveEndpoint:withParams:options:agentResolveResponse:"
- "resolve_handler: Failed to copy public key from options=%@, parameters=%@, agent_client=%@\n"
- "resolve_handler: Failed to find QUIC protocol options from parameters=%@, agent_client=%@\n"
- "resolve_handler: could not create session."
- "resolve_handler: invalid message response type: %lu from destination: %@"
- "resolve_handler: isClient: %d\n"
- "resolve_handler: local public key length: %lu"
- "resolve_handler: received key exchange response, message: %@ from destination: %@"
- "resolve_handler: remote accepted invitation, message: %@ from destination: %@"
- "resolve_handler: remote declined invitation, message: %@ from destination: %@"
- "resolve_handler: resolve request for endpoint %@\n"
- "resolve_handler: resolveEndpoint for client %@"
- "resolve_handler: response destination %@ is not in destination array %@."
- "resolve_handler: stop_resolve_handler called for client:%@"
- "resolve_handler: stop_resolve_handler called for endpoint:%@"
- "sendKeyExchangeRequestWithOptions:"
- "sendKeyExchangeResponseWithOptions:"
- "sessionOptions"
- "setKtError:"
- "setKtValidation:"
- "setLastGDRDateMap:"
- "tokenAdded:forService:ownPushToken:registrationDate:"
- "v68@0:8@16r*24@32@40i48q52@?60"
```
