## findmydeviced

> `/usr/libexec/findmydeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f8934` | `0x5475b8` | **`+0x4ec84`** |
| `__TEXT.__eh_frame` | `0x27748` | `0x2ba34` | **`+0x42ec`** |
| `__DATA.__bss` | `0x29020` | `0x2d240` | **`+0x4220`** |
| `__TEXT.__const` | `0x46a76` | `0x48f26` | **`+0x24b0`** |
| `__TEXT.__oslogstring` | `0x1d859` | `0x1f479` | **`+0x1c20`** |
| `__DATA_CONST.__const` | `0x1dd60` | `0x1f410` | **`+0x16b0`** |
| `__DATA.__data` | `0xb320` | `0xc2d0` | **`+0xfb0`** |
| `__TEXT.__unwind_info` | `0xff60` | `0x10dd8` | **`+0xe78`** |
| `__TEXT.__swift5_fieldmd` | `0x6f18` | `0x785c` | **`+0x944`** |
| `__TEXT.__swift5_reflstr` | `0x57fe` | `0x609e` | **`+0x8a0`** |
| `__TEXT.__cstring` | `0xe02e` | `0xe8ae` | **`+0x880`** |
| `__TEXT.__constg_swiftt` | `0x5ccc` | `0x64ac` | **`+0x7e0`** |
| `__TEXT.__swift5_typeref` | `0x4e1e` | `0x5550` | **`+0x732`** |
| `__DATA.__objc_const` | `0x1ed48` | `0x1f448` | **`+0x700`** |
| `__TEXT.__objc_methname` | `0x205e5` | `0x20a69` | **`+0x484`** |
| `__TEXT.__swift_as_cont` | `0x211c` | `0x2444` | **`+0x328`** |
| `__TEXT.__swift5_capture` | `0x1e60` | `0x2168` | **`+0x308`** |
| `__TEXT.__objc_methtype` | `0x3e2c` | `0x404c` | **`+0x220`** |
| `__TEXT.__swift5_proto` | `0x1418` | `0x1638` | **`+0x220`** |
| `__TEXT.__swift_as_ret` | `0x14a0` | `0x16a8` | **`+0x208`** |
| `__TEXT.__objc_classname` | `0x2b46` | `0x2d36` | **`+0x1f0`** |
| `__DATA.__objc_data` | `0x55c0` | `0x5780` | **`+0x1c0`** |
| `__TEXT.__objc_stubs` | `0x18b20` | `0x18ca0` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0x10944` | `0x10a94` | **`+0x150`** |
| `__TEXT.__swift5_assocty` | `0xc40` | `0xd90` | **`+0x150`** |
| `__TEXT.__auth_stubs` | `0x4e60` | `0x4f90` | **`+0x130`** |
| `__TEXT.__swift_as_entry` | `0xd98` | `0xe9c` | **`+0x104`** |
| `__DATA_CONST.__auth_ptr` | `0x1e38` | `0x1f28` | **`+0xf0`** |
| `__DATA.__objc_selrefs` | `0x7188` | `0x7260` | **`+0xd8`** |
| `__TEXT.__swift5_types` | `0x838` | `0x8f0` | **`+0xb8`** |
| `__DATA_CONST.__auth_got` | `0x2740` | `0x27d8` | **`+0x98`** |
| `__DATA_CONST.__got` | `0x1b90` | `0x1c10` | **`+0x80`** |
| `__DATA.__common` | `0xa00` | `0xa60` | **`+0x60`** |
| `__TEXT.__swift5_builtin` | `0x208` | `0x244` | **`+0x3c`** |
| `__DATA_CONST.__objc_classlist` | `0x910` | `0x940` | **`+0x30`** |
| `__TEXT.__swift5_mpenum` | `0x138` | `0x160` | **`+0x28`** |
| `__DATA_CONST.__objc_protolist` | `0x2b0` | `0x2d0` | **`+0x20`** |
| `__TEXT.__swift5_acfuncs` | `0xf0` | `0x104` | **`+0x14`** |
| `__DATA_CONST.__objc_protorefs` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x3c` | `0x40` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-482.31.6.16.16
+482.31.6.16.21

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

+  - /System/Library/PrivateFrameworks/Rapport.framework/Rapport

+  - /System/Library/PrivateFrameworks/TVRemoteCore.framework/TVRemoteCore

-  Functions: 16540
-  Symbols:   2717
-  CStrings:  10383
+  Functions: 17538
+  Symbols:   2756
+  CStrings:  10625
Symbols:
+ _$s10Foundation4DateV11distantPastACvgZ
+ _$s15Synchronization5MutexVMa
+ _$s15Synchronization5_CellVMn
+ _$s19FindMyDaemonSupport20ActorServiceProtocolPAAE4nameSSvg
+ _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0efG5ErrorOMn
+ _$s23FindMyDeviceAccessories22LocalFindableAccessoryV17FindingTechnologyO4btcsyA2EmFWC
+ _$s23FindMyDeviceAccessories40LocalFindableAccessoryServerXPCInterfaceP19accessoryIdentifier012forCompanionK010Foundation4UUIDVSS_tYaKFTq
+ _$s23FindMyDeviceAccessories40LocalFindableAccessoryServerXPCInterfaceP19accessoryIdentifier012forCompanionK010Foundation4UUIDVSS_tYaKFTqTE
+ _$sSON
+ _$sSSSesWP
+ _$sSa28_allocateBufferUninitialized15minimumCapacitys06_ArrayB0VyxGSi_tFZ
+ _$sSb10FoundationE19_bridgeToObjectiveCSo8NSNumberCyF
+ _$sSf10FoundationE19_bridgeToObjectiveCSo8NSNumberCyF
+ _$sSh10FoundationE36_unconditionallyBridgeFromObjectiveCyShyxGSo5NSSetCSgFZ
+ _$sSi10FoundationE19_bridgeToObjectiveCSo8NSNumberCyF
+ _$sSy10FoundationE8containsySbqd__SyRd__lF
+ _$ss10__CocoaSetV5countSivg
+ _$ss15ContinuousClockV7InstantVSQsMc
+ _$ss17CodingUserInfoKeyV8rawValueABSgSS_tcfC
+ _$ss17CodingUserInfoKeyVMa
+ _$ss17CodingUserInfoKeyVMn
+ _$ss17CodingUserInfoKeyVSHsWP
+ _$ss17CodingUserInfoKeyVSQsWP
+ _$ss5ErrorP10FindMyBaseE6domainSSvg
+ _$ss7DecoderP8userInfoSDys010CodingUserC3KeyVypGvgTj
+ _$ss8DurationV10componentss5Int64V7seconds_AE11attosecondstvg
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_SPFindingSessionEvent
+ _OBJC_CLASS_$_SwiftNativeNSObject
+ _OBJC_CLASS_$_TVRCDevice
+ _OBJC_CLASS_$_TVRCDeviceQuery
+ _OBJC_METACLASS_$_SwiftNativeNSObject
+ _RPErrorDomain
+ _SecRandomCopyBytes
+ _kSecRandomDefault
+ _swift_continuation_resume
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
CStrings:
+ " task "
+ "$__lazy_storage_$_query"
+ "%{public}s failed to enable reflector mode due to TVRemoteMessageSessionError.timeout"
+ "%{public}s failed to enable reflector mode due to invalid response"
+ "%{public}s failed to enable reflector mode: %{public}@"
+ "%{public}s failed to enable reflector mode: TimeoutError"
+ "%{public}s failure to stopBTCS: %{public}@"
+ "%{public}s stopping."
+ "%{public}s v2 start finding failed, falling back to v1: %{public}@"
+ "%{public}s with error %{public}@"
+ "%{public}s with event %{private,mask.hash}@"
+ "%{public}s: Accessory connected to companion during BTCS finding"
+ "%{public}s: Accessory not connect"
+ "%{public}s: Already enabling reflector mode, aborting."
+ "%{public}s: Already monitoring connection status."
+ "%{public}s: BTCS session not active, returning"
+ "%{public}s: Error sending stop BTCS command: %{public}@"
+ "%{public}s: FastAdvertising session not active, returning"
+ "%{public}s: Reflector mode enabled successfully"
+ "%{public}s: Sending StartBTCS Command"
+ "%{public}s: Starting Reflector mode enablement"
+ "%{public}s: not sending event as there is no active BTCS session."
+ ".disableBTCSReflector"
+ ".disableReflector"
+ ".enableBTCSReflector"
+ ".enableReflector"
+ ".motionIndication"
+ ".startAggressiveAdvertisingB519"
+ ".startBTB519Finding"
+ ".startConnectableAdvertising"
+ ".startConnectableAdvertisingV2"
+ ".stopAggressiveAdvertisingB519"
+ ".stopBTB519Finding"
+ ".stopConnectableAdvertising"
+ ": unsupported platform"
+ "Accessory %{private,mask.hash}s matches companion identifier %{private,mask.hash}s"
+ "B24@0:8@\"TVRCDevice\"16"
+ "Cancelled when pinging companion"
+ "Companion capable, looking up companion identifier"
+ "Companion identifier %{private,mask.hash}s is not a valid UUID"
+ "Companion identifier found: %s"
+ "Companion in invalidState"
+ "Companion response: connected to some accessory"
+ "Companion response: not connected to any accessory"
+ "Companion unavailable"
+ "Creating new remote message session to %s for message %s v%ld"
+ "Creating new remote message session to %s for message %s v%ld (expecting response)"
+ "Detected non-matching tvRemote accessory: %{public}s"
+ "Device %s %s: already connected, skipping connect"
+ "Device %s %s: calling device.connect() for %s"
+ "Device %s %s: calling sendFindMyPayload for submission %s"
+ "Device %s %s: connect %s skipped, already connected"
+ "Device %s %s: connected"
+ "Device %s %s: connectionState=%ld, initiating connect %s (timeout=%s)"
+ "Device %s %s: disconnected (reason='%ld'), error: %s"
+ "Device %s %s: disconnecting and stopping query"
+ "Device %s %s: failing %ld pending connection(s) due to disconnect"
+ "Device %s %s: resuming %ld pending connection(s)"
+ "Device %s %s: sendFindMyPayload for submission %s returned %ld bytes"
+ "Device %s %s: sendFindMyPayload for submission %s returned error: %@"
+ "Device %s %s: submission %s failed due to invalidated device, disconnecting"
+ "Device %s %s: submission %s failed due to timeout during send, disconnecting"
+ "Device %s %s: submission %s failed: %@"
+ "Device %s %s: submission %s succeeded (response %ld bytes)"
+ "Device %s %s: submitting payload %s (%ld bytes)"
+ "Device %s %s: unknown connectionState=%ld, skipping connect"
+ "Disconnected from %{public}s"
+ "Disconnecting device %s and stopping query on dealloc"
+ "Error getting client proxy for accessory event update: %{public}@"
+ "Error loading shared accessories: %@"
+ "Error messaging companion to start btcs: %{public}@"
+ "Error notifying clients of accessory disconnected event: %{public}@)"
+ "Error performing action for "
+ "Error performing action for %s: unsupported platform"
+ "Error pinging companion: %{public}@"
+ "Error preparing companion identifier lookup for identifier %{private,mask.hash}s: %@"
+ "F5873412-D314-B885-A5AA-EFA546123981"
+ "F5873413-D314-B885-A5AA-EFA546123982"
+ "Failed to get capabilities for accessory %s: %@"
+ "Failed to invalidate remote message session to: %{public}s, error: %{public}@"
+ "Failed to read local connectable Bluetooth address, error: %{public}@"
+ "Failed to send %s v%ld to %s: %@"
+ "Failed to start BTCS session error: %@"
+ "Fetching local finder MAC address"
+ "Invalidating remote message session to %s"
+ "Invalidating remote message session to: %{public}s"
+ "Looking up companion identifier %{private,mask.hash}s across %{public}ld accessories"
+ "Messaging companion to start btcs"
+ "Messaging companion to start fast advertisement"
+ "Messaging companion to start play sound"
+ "Messaging companion to stop fast advertisement"
+ "Messaging companion to stop play sound"
+ "No accessory matches companion identifier %{private,mask.hash}s"
+ "No companion identifier for accessory %{private,mask.hash}s: %{public}@"
+ "No remote message session to invalidate for %s"
+ "Not setting stopped playing state from companion due to ongoing play sound being initiated"
+ "Notifying %{public}ld clients for accessory error"
+ "Notifying %{public}ld clients for accessory event update"
+ "Performing action for %s"
+ "Query for %s started"
+ "Query for %s: TVRCDeviceQuery failed to start"
+ "Query for %s: cannot start search, query not idle"
+ "Query for %s: device %s %s found in initial query results"
+ "Query for %s: device %s %s found via update handler"
+ "Query for %s: mismatching device %s %s found in initial query results"
+ "Query for %s: mismatching device %s %s found via update handler"
+ "Query for %s: search cancelled"
+ "Query for %s: search interrupted: %@"
+ "Query for %s: search timed out after %s"
+ "Query for %s: starting device search (timeout=%s)"
+ "Received response for %s v%ld from %s"
+ "Response from companion for start play sound: %hhu"
+ "Restarting BTCS reflectorMode"
+ "Running pre-invalidation of companion connection to start with a fresh connection"
+ "Sending BTCS .peripheralLost event"
+ "Sending message %s v%ld to %s using existing session"
+ "Sending message %s v%ld to %s using existing session (expecting response)"
+ "Session for %s: awaiting in-progress connect"
+ "Session for %s: failed to decode response for %s v%ld: %@"
+ "Session for %s: failed to encode message %s v%ld: %@"
+ "Session for %s: received response for %s v%ld (%ld bytes)"
+ "Session for %s: reusing connected device"
+ "Session for %s: send of %s v%ld completed"
+ "Session for %s: send of %s v%ld failed: %@. Resetting state to idle"
+ "Session for %s: send of %s v%ld got non-fatal error: %@)"
+ "Session for %s: sending %s v%ld (%ld bytes, no response expected)"
+ "Session for %s: sending %s v%ld (%ld bytes, response expected)"
+ "Session for %s: state connecting -> connected"
+ "Session for %s: state connecting -> idle (search failed: %@)"
+ "Session for %s: state idle -> connecting (searching for device)"
+ "Successful fetch of local finder MAC address: %s"
+ "Successful response from companion for stop play sound"
+ "Successful response from start BTCS command"
+ "Successfully sent %s v%ld to %s"
+ "TVRCDeviceDelegate"
+ "TVRCDeviceQueryDelegate"
+ "Unexpected connected accessory for companion, expected %s, got %s"
+ "Unexpected local Bluetooth address length %{public}ld"
+ "Updating date of last button press from companion: %s, previous last button press: %s)"
+ "Updating sound playing state from companion: %hhu"
+ "_TtC13findmydeviced22TVRemoteMessageService"
+ "_TtC13findmydeviced22TVRemoteMessageSession"
+ "_TtCC13findmydeviced19OwnerCommandService14CommandTimings"
+ "_TtCC13findmydeviced22TVRemoteMessageSessionP33_1C428E201A258257110DC220D3860C2D15QueryTrampoline"
+ "_TtCC13findmydeviced22TVRemoteMessageSessionP33_1C428E201A258257110DC220D3860C2D16DeviceTrampoline"
+ "_TtCCC13findmydeviced16BTFindingService14FindingSession16StartBTCSTimings"
+ "_connectedAt"
+ "_execute(command:connectionOptions:executeOnlyIfConnected:timings:)"
+ "accessoryIdentifier(forCompanionIdentifier:)"
+ "btChannelSounding"
+ "btRSSI"
+ "btcs"
+ "btcsEnableReflectorMode"
+ "com.apple.findmy.btcs.event"
+ "com.apple.findmy.btcs.prewarming"
+ "com.apple.findmy.btcs.start"
+ "command"
+ "companionAvailable"
+ "companionConnectedDuration"
+ "companionDeviceOnlineDuration"
+ "companionPing"
+ "companionPingDuration"
+ "companionStartFindingDuration"
+ "companionStateDuration"
+ "confirmedRouteWait"
+ "confirmedRouteWaitDuration"
+ "connect(connection:)"
+ "connectedLocalFindableAccessoryID"
+ "connectionDuration"
+ "connections"
+ "containsIdentifier:"
+ "detectedNearbyDuration"
+ "device:disconnectedForReason:error:"
+ "device:encounteredAuthenticationChallenge:"
+ "device:removedSupportedButtons:added:"
+ "device:updatedAttentionState:"
+ "device:updatedFindMyRemoteSupport:"
+ "device:updatedNowPlayingInfo:"
+ "device:updatedPairedRemoteInfo:"
+ "device:updatedSiriRemoteFindingSessionState:"
+ "device:updatedTopShelfInfo:"
+ "deviceBeganConnecting:"
+ "deviceConnected:"
+ "deviceQueryDidUpdateDevices:"
+ "deviceShouldAllowConnectionAuthentication:"
+ "didUpdateSuggestedDevices:"
+ "disconnectWithType:"
+ "enableBTCSReflectorMode()"
+ "execute(command:connectionOptions:executeOnlyIfConnected:timings:)"
+ "find_0"
+ "find_1"
+ "finderMACAddress"
+ "findmydeviced.DeviceTrampoline"
+ "findmydeviced.QueryTrampoline"
+ "findmydeviced/TVRemoteMessagePingV1.swift"
+ "findmydeviced/TVRemoteMessageStartPlaySoundV1.swift"
+ "forCompanionIdentifier"
+ "hasActiveBTCSSession"
+ "initWithBeaconID:event:peripheralID:motionState:"
+ "initWithInteger:"
+ "lastButtonPress"
+ "notifyClientsOfAccessory(error:)"
+ "notifyClientsOfAccessory(event:btcsSessionOnly:)"
+ "notifyClientsOfButtonPressDuringFastAdvertising()"
+ "notifyCompanionConnectedIfNeeded(accessoryIdentifier:)"
+ "payload"
+ "ping"
+ "query"
+ "reflectorModeEnabled"
+ "search(timeout:)"
+ "send(payloadData:submission:)"
+ "sendFindMyPayload:response:"
+ "sendLocalFindable(centralManager:discovery:config:record:command:executeOnlyIfConnected:timings:)"
+ "sendStartBTCSCommand"
+ "sendStartBTCSCommand(finderMACAddress:timings:)"
+ "sendStartBTCSCommandDuration"
+ "sendStopBTCSCommand()"
+ "setDevicesUpdatedHandler:"
+ "setupMetrics"
+ "sound_0"
+ "sound_1"
+ "startBTCS(beacon:connection:)"
+ "startBTCS(finderMACAddress:)"
+ "startBTCS:completion:"
+ "startWithCompletionHandler:"
+ "stop"
+ "stopBTCS(beacon:connection:)"
+ "stopBTCS:completion:"
+ "stopConnectionMonitoring()"
+ "submissions"
+ "timeout finderMACAddress "
+ "tvRemoteMessageResolver"
+ "unpair"
+ "updateAccessoryEvent:"
+ "v16@?0@\"NSSet\"8"
+ "v24@0:8@\"SPFindingSessionEvent\"16"
+ "v24@0:8@\"TVRCDevice\"16"
+ "v24@0:8@\"TVRCDeviceQuery\"16"
+ "v24@?0@\"NSData\"8@\"NSError\"16"
+ "v32@0:8@\"TVRCDevice\"16@\"TVRCDeviceAuthenticationChallenge\"24"
+ "v32@0:8@\"TVRCDevice\"16@\"TVRCNowPlayingInfo\"24"
+ "v32@0:8@\"TVRCDevice\"16@\"TVRCSiriRemoteInfo\"24"
+ "v32@0:8@\"TVRCDevice\"16@\"TVRCTopShelfInfo\"24"
+ "v32@0:8@\"TVRCDevice\"16q24"
+ "v40@0:8@\"TVRCDevice\"16@\"NSSet\"24@\"NSSet\"32"
+ "v40@0:8@\"TVRCDevice\"16q24@\"NSError\"32"
- "Disconnected from %{public}s, error: %{public}@"
- "_execute(command:connectionOptions:executeOnlyIfConnected:)"
- "execute(command:connectionOptions:executeOnlyIfConnected:)"
- "sendLocalFindable(centralManager:discovery:config:record:command:executeOnlyIfConnected:)"
```
