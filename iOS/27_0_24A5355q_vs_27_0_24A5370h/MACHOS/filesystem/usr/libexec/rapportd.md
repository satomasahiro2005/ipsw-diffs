## rapportd

> `/usr/libexec/rapportd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1820ec` | `0x1940b8` | **`+0x11fcc`** |
| `__TEXT.__cstring` | `0x35fd6` | `0x36cb6` | **`+0xce0`** |
| `__TEXT.__objc_methname` | `0x1bc61` | `0x1c650` | **`+0x9ef`** |
| `__DATA.__objc_const` | `0x11660` | `0x11c90` | **`+0x630`** |
| `__TEXT.__objc_stubs` | `0x12f80` | `0x13520` | **`+0x5a0`** |
| `__TEXT.__objc_methlist` | `0x9bc8` | `0xa0b0` | **`+0x4e8`** |
| `__DATA_CONST.__const` | `0x8028` | `0x8448` | **`+0x420`** |
| `__DATA.__objc_data` | `0x29f8` | `0x2d80` | **`+0x388`** |
| `__TEXT.__const` | `0x5c38` | `0x5fb0` | **`+0x378`** |
| `__TEXT.__swift5_typeref` | `0x139a` | `0x1710` | **`+0x376`** |
| `__TEXT.__oslogstring` | `0x3152` | `0x3492` | **`+0x340`** |
| `__DATA.__data` | `0x37a0` | `0x3ad8` | **`+0x338`** |
| `__DATA.__bss` | `0x43f0` | `0x4720` | **`+0x330`** |
| `__TEXT.__objc_methtype` | `0x47d1` | `0x4aa1` | **`+0x2d0`** |
| `__TEXT.__unwind_info` | `0x5680` | `0x5948` | **`+0x2c8`** |
| `__TEXT.__constg_swiftt` | `0xbf0` | `0xe50` | **`+0x260`** |
| `__DATA.__objc_selrefs` | `0x5c30` | `0x5e30` | **`+0x200`** |
| `__TEXT.__auth_stubs` | `0x3830` | `0x39a0` | **`+0x170`** |
| `__DATA_CONST.__auth_ptr` | `0x550` | `0x670` | **`+0x120`** |
| `__TEXT.__swift5_fieldmd` | `0xe2c` | `0xf3c` | **`+0x110`** |
| `__TEXT.__swift5_reflstr` | `0xec4` | `0xfc4` | **`+0x100`** |
| `__DATA_CONST.__auth_got` | `0x1c28` | `0x1ce0` | **`+0xb8`** |
| `__TEXT.__objc_classname` | `0x103f` | `0x10bf` | **`+0x80`** |
| `__TEXT.__swift5_assocty` | `0x130` | `0x190` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0xb18` | `0xb78` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x2500` | `0x24ac` | **`-0x54`** |
| `__DATA_CONST.__got` | `0x9e0` | `0xa28` | **`+0x48`** |
| `__DATA_CONST.__objc_arraydata` | `0xa0` | `0x58` | **`-0x48`** |
| `__DATA.__objc_ivar` | `0x10e4` | `0x1124` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x6760` | `0x67a0` | **`+0x40`** |
| `__DATA_CONST.__objc_arrayobj` | `0x48` | `0x18` | **`-0x30`** |
| `__DATA_CONST.__objc_dictobj` | `0x78` | `0x50` | **`-0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x388` | `0x3a0` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x360` | `0x378` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x64` | `0x78` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x1b8` | `0x1cc` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0xe8` | `0xfc` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x168` | `0x178` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0xc0` | `0xc8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x220` | `0x228` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x4c84` | `0x4c7c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-740.100.2.0.0
+743.100.4.0.0

-  Functions: 8250
-  Symbols:   1383
-  CStrings:  10662
+  Functions: 8571
+  Symbols:   1449
+  CStrings:  10842
Symbols:
+ _$s10Foundation9PredicateV8evaluateySbxxQpKF
+ _$s10Foundation9PredicateVMn
+ _$s10Foundation9PredicateVyxxQp_QPGs23CustomStringConvertibleAAMc
+ _$s19ArrayLiteralElements013ExpressibleByaB0PTl
+ _$s2os6LoggerVMn
+ _$s7Elements10SetAlgebraPTl
+ _$s7Network18FilterableEndpointP9osVersionAA9OSVersionVvgTq
+ _$s7Network9NWBrowserC10DescriptorO7OptionsV18constructPredicatey10Foundation0F0VyAA18FilterableEndpoint_p_QPGSgAI4DataVFZ
+ _$s7Network9OSVersionV5major5minor5patchACSi_S2itcfC
+ _$sBbWV
+ _$sSSSysMc
+ _$sSTsSy7ElementRpzrlE6joined9separatorS2S_tF
+ _$sSh10FoundationE19_bridgeToObjectiveCSo5NSSetCyF
+ _$sShyxGSTsMc
+ _$sSo13os_log_type_ta0A0E4infoABvgZ
+ _$ss10SetAlgebraMp
+ _$ss10SetAlgebraP10isDisjoint4withSbx_tFTq
+ _$ss10SetAlgebraP10isSuperset2ofSbx_tFTq
+ _$ss10SetAlgebraP11subtractingyxxFTq
+ _$ss10SetAlgebraP12intersectionyxxFTq
+ _$ss10SetAlgebraP16formIntersectionyyxFTq
+ _$ss10SetAlgebraP19symmetricDifferenceyxxnFTq
+ _$ss10SetAlgebraP23formSymmetricDifferenceyyxnFTq
+ _$ss10SetAlgebraP5unionyxxnFTq
+ _$ss10SetAlgebraP6insertySb8inserted_7ElementQz17memberAfterInserttAFnFTq
+ _$ss10SetAlgebraP6removey7ElementQzSgAEFTq
+ _$ss10SetAlgebraP6update4with7ElementQzSgAFn_tFTq
+ _$ss10SetAlgebraP7isEmptySbvgTq
+ _$ss10SetAlgebraP8containsySb7ElementQzFTq
+ _$ss10SetAlgebraP8isSubset2ofSbx_tFTq
+ _$ss10SetAlgebraP8subtractyyxFTq
+ _$ss10SetAlgebraP9formUnionyyxnFTq
+ _$ss10SetAlgebraPSQTb
+ _$ss10SetAlgebraPs25ExpressibleByArrayLiteralTb
+ _$ss10SetAlgebraPsEyxqd__ncSTRd__7ElementQyd__ACRtzlufC
+ _$ss10SetAlgebraPxycfCTq
+ _$ss10SetAlgebraPyxqd__ncSTRd__7ElementQyd__ACRtzlufCTq
+ _$ss11AnyHashableV13_rawHashValue4seedS2i_tF
+ _$ss11AnyHashableV2eeoiySbAB_ABtFZ
+ _$ss11AnyHashableVMn
+ _$ss11AnyHashableVN
+ _$ss11AnyHashableVSHsWP
+ _$ss11AnyHashableVyABxcSHRzlufC
+ _$ss25ExpressibleByArrayLiteralMp
+ _$ss25ExpressibleByArrayLiteralP05arrayD0x0cD7ElementQzd_tcfCTq
+ _$ss6HasherV5_hash4seed_S2i_s6UInt64VtFZ
+ _$ss6UInt64VMn
+ _$ss6UInt64VN
+ _$ss9OptionSetMp
+ _$ss9OptionSetP8rawValuex03RawD0Qz_tcfCTq
+ _$ss9OptionSetPSYTb
+ _$ss9OptionSetPs0B7AlgebraTb
+ _NSLocalizedDescriptionKey
+ _OBJC_CLASS_$_SDServiceDatabase
+ _clock_gettime_nsec_np
+ _nw_agent_set_resolve_flags
+ _nw_endpoint_get_contact_id
+ _nw_endpoint_get_device_id
+ _nw_endpoint_get_device_model
+ _nw_endpoint_get_device_name
+ _nw_txt_record_apply
+ _nw_txt_record_find_key
+ _objc_retain_x10
+ _swift_getFunctionTypeMetadata0
+ _swift_release_x12
+ _uuid_compare
CStrings:
+ " altEP=%@"
+ " devices=%@"
+ " no altEP"
+ " no devices"
+ "### RegisterEventID: a handler already exists for eventID '%{public}s'"
+ "### RegisterRequestID: a handler already exists for request ID:'%{public}s'"
+ "### Reject message for proxy device (%@) on unauthenticated connection: %@"
+ "%@ Adding device %@"
+ "%@ DISCOVER: Added ineligible device (%lu total) to RPNWDiscoverySession[%@] - %@"
+ "%@ DISCOVER: Adding endpoint due to device change in RPNWDiscoverySession[%@] - %@"
+ "%@ DISCOVER: Adding endpoint due to query add in RPNWDiscoverySession[%@] - %@"
+ "%@ DISCOVER: Flushing %lu batched browse result updates in RPNWDiscoverySession[%@]"
+ "%@ DISCOVER: Found QR result %@ in RPNWDiscoverySession[%@]"
+ "%@ DISCOVER: Found query result %@ in RPNWDiscoverySession[%@]"
+ "%@ DISCOVER: Lost QR result %@ in RPNWDiscoverySession[%@]"
+ "%@ DISCOVER: Lost query result %@ in RPNWDiscoverySession[%@]"
+ "%@ DISCOVER: Now %lu batched browse result updates pending in RPNWDiscoverySession[%@]"
+ "%@ DISCOVER: Removed ineligible device (%lu total) to RPNWDiscoverySession[%@] - %@"
+ "%@ DISCOVER: Removing endpoint due to device change in RPNWDiscoverySession[%@] - %@"
+ "%@ DISCOVER: Removing endpoint due to query loss in RPNWDiscoverySession[%@] - %@"
+ "%@ DISCOVER: Updated query result %@ in RPNWDiscoverySession[%@]"
+ "%@ DISCOVER: Updating endpoint due to device change in RPNWDiscoverySession[%@] - %@"
+ "%@ DISCOVER: Updating endpoint due to query update in RPNWDiscoverySession[%@] - %@"
+ "%@ Incoming connection ready signaling READY (framer already bound)"
+ "%@ PAIRING RESOLVE: No device found for endpoint ID=%@\n"
+ "%@ RESOLVE: Adding QR/ALT endpoint %@\n"
+ "%@ RESOLVE: No alternate endpoints available\n"
+ "%@ RESOLVE: No device, checking for alternate endpoints\n"
+ "%@ RESOLVE: Redirecting to alternate endpoints %@\n"
+ "%@ Replacing device %@"
+ "%@ Restricting device name to '%@'"
+ "+[RPNWEndpoint updateClientBrowseResult:browseResponse:token:agentUUID:agentClientID:agentClientPID:applicationService:discoverySessionID:predicate:]"
+ "-[RPCompanionLinkDaemon _serverBTRotatingIdentifierChanged]"
+ "-[RPCompanionLinkDaemon deliverEventID:event:options:cnx:]"
+ "-[RPCompanionLinkDaemon deliverRequestID:request:options:responseHandler:cnx:]"
+ "-[RPCompanionLinkDaemon handleAndLaunchReceivingProcessForServiceType:receivedRequestID:request:options:responseHandler:cnx:]"
+ "-[RPCompanionLinkDaemon handleAndLaunchReceivingProcessForServiceType:receivedRequestID:request:options:responseHandler:cnx:]_block_invoke_2"
+ "-[RPCompanionLinkDaemon launchXPCListenerForService:additionalPayload:completion:]"
+ "-[RPCompanionLinkDaemon launchXPCListenerForService:additionalPayload:completion:]_block_invoke_2"
+ "-[RPCompanionLinkXPCConnection companionLinkSetAdvertisesPublicBluetoothAddress:completion:]"
+ "-[RPCompanionLinkXPCConnection connectionInvalidatedCore]_block_invoke_4"
+ "-[RPDaemonXPCConnection launchListenerForService:completion:]"
+ "-[RPNWDestination _addOrUpdate:]"
+ "-[RPNWDestination updateEndpoint:applicationService:]"
+ "-[RPNWDestination updateWithDestination:remove:]"
+ "-[RPNWDiscoverySession _ineligibleDevicesAdd:]"
+ "-[RPNWDiscoverySession _ineligibleDevicesRemove:]"
+ "-[RPNWDiscoverySession _serviceDiscoveryEvaluateDevice:]"
+ "-[RPNWDiscoverySession _serviceDiscoveryHandleQRResults:results:]_block_invoke"
+ "-[RPNWDiscoverySession _serviceDiscoveryHandleResults:results:]_block_invoke"
+ "-[RPNWDiscoverySession _serviceDiscoveryIsSupportedByDevice:]"
+ "-[RPNWDiscoverySession batchUpdateClientBrowseResult:]"
+ "-[RPNWDiscoverySession startDiscovery:controlFlags:deviceFilter:]_block_invoke_5"
+ "-[RPNWDiscoverySession updateClientBrowseResult]"
+ "-[RPNWDiscoverySession updateMappingForDevice:]"
+ "-[RPRemoteDisplayDaemon _isClientWithinAWDLTimeoutGracePeriod:currentTime:]"
+ "-[RPServiceDiscoveryClient _serviceDiscoveryDo:]"
+ "-[RPServiceDiscoveryClient isSupportedByDevice:]"
+ "-[RPServiceDiscoveryClient startAvertisementForAdvertiseDescriptor:withMetadata:completionHandler:]_block_invoke_2"
+ "-[RPServiceDiscoveryClient startQueryForBrowseDescriptor:resultHandler:completionHandler:]_block_invoke_2"
+ "@\"OS_dispatch_queue\"16@0:8"
+ "@\"RPNWDestination\""
+ "@\"_TtC8rapportd24RPMessageHandlerProvider\""
+ "@24@0:8^{_NSZone=}16"
+ "@24@0:8r*16"
+ "Activating"
+ "Adding endpoint mapping [%@:%@] for destination '%@' and session '%@'\n"
+ "Advertising public Bluetooth address is not supported on this device"
+ "Assertion for LaunchOnDemand of '%@' failed: %@\n"
+ "B32@0:8@16Q24"
+ "B48@0:8@\"NSString\"16@\"NSDictionary\"24@\"NSDictionary\"32@\"RPConnection\"40"
+ "B48@?0@\"NSString\"8@\"NSDictionary\"16@\"NSDictionary\"24@?<v@?@\"NSDictionary\"@\"NSDictionary\"@\"NSError\">32@\"RPConnection\"40"
+ "B56@0:8@\"NSString\"16@\"NSDictionary\"24@\"NSDictionary\"32@?<v@?@\"NSDictionary\"@\"NSDictionary\"@\"NSError\">40@\"RPConnection\"48"
+ "B56@0:8@16@24@32@?40@48"
+ "Bluetooth rotating identifier changed: %.6a\n"
+ "Changed to %@ after updating"
+ "Deregistered event ID: %s"
+ "Deregistered request ID: %s"
+ "Endpoint at index %ld DID match predicate, keeping endpoint"
+ "Endpoint at index %ld did NOT match predicate, filtering out endpoint"
+ "Failed to filter endpoints: %@"
+ "Failed to get device for paring from endpoint %@\n"
+ "Filtered endpoint count: %ld"
+ "Flushed all pending actions"
+ "Found existing endpoint '%@' eligible for update by '%@'\n"
+ "Found existing endpoint '%@' with equal destination '%@'\n"
+ "HomeKit SelfAccessory identifier changed: %@ -> %@"
+ "Invalid state A[%c] I[%c] to start advertisement for %@"
+ "Invalid state A[%c] I[%c] to start query for %@"
+ "Invalid state A[%c] I[%c] to stop advertisement %@"
+ "Invalid state A[%c] I[%c] to stop query %@"
+ "Invalid state A[%c] I[%c] to update advertisement %@"
+ "Invalidating"
+ "Keeping endpoint '%@'"
+ "Keeping endpoint '%@' after removing destination '%@'"
+ "LECAHap"
+ "LECAHapLow"
+ "LECATmap"
+ "LECATmapLow"
+ "LaunchListenerForService"
+ "LaunchOnDemand response for '%@' failed"
+ "Missing entitlement for %@ of '%@'"
+ "No LaunchOnDemand handler for '%@'"
+ "No filter, returning endpoints"
+ "Not adding mapping for invalid destination %@"
+ "Now %lu pending actions"
+ "Original endpoint count: %ld, found predicate: %s"
+ "RPMessageHandlingProtocol"
+ "RPNWDestination"
+ "RPNWDestination<%p>"
+ "Received eventID (%s): %{public}s"
+ "Received requestID (%s): %{public}s"
+ "Register event ID %{public}s with handlers: %{public}s"
+ "Register request ID %{public}s with handlers: %{public}s"
+ "Removed destination '%@' from endpoint '%@'"
+ "Removing endpoint '%@' after removing destination '%@'"
+ "Requested to trigger LaunchOnDemand for '%@' with %@\n"
+ "Setting Agent Resolve Flags\n"
+ "Skipping AWDL timeout for '%@' - registered %.3fs ago\n"
+ "Skipping AWDL timeout for '%s' - registered %ss ago"
+ "T@\"NSArray\",R,C,N"
+ "T@\"NSMutableArray\",&,N,V_alternativeEndpoints"
+ "T@\"NSMutableArray\",&,N,V_ineligibleDevices"
+ "T@\"NSString\",C,N,V_deviceID"
+ "T@\"OS_dispatch_queue\",&,N"
+ "T@\"RPCompanionLinkDevice\",R,N"
+ "T@\"RPNWDestination\",&,N,V_destination"
+ "T@\"_TtC8rapportd24RPMessageHandlerProvider\",R,N,V_messageHandlerProvider"
+ "T@?,N,C"
+ "TB,N,V_advertisesPublicBluetoothAddress"
+ "TB,N,V_batchingClientBrowseResults"
+ "TB,N,V_peerHasAcked"
+ "TB,R,N,GisValid"
+ "TQ,N,V_pendingClientBrowseResults"
+ "Trigger LaunchOnDemand of '%@' failed: %@\n"
+ "T{?=qqq},N,V_deviceOperatingSystemVersion"
+ "Unchanged %@ after update"
+ "Unknown service '%@'"
+ "Updating endpoint '%@' to remove destination '%@'"
+ "Updating endpoint for destination '%@'"
+ "_TtC8rapportd16RPMessageHandler"
+ "_TtC8rapportd24RPMessageHandlerProvider"
+ "_addOrUpdate:"
+ "_advertisesPublicBluetoothAddress"
+ "_alternativeEndpoints"
+ "_anyXPCClientWantsPublicBluetoothAddressAdvertised"
+ "_awdlClientTimestamps"
+ "_batchingClientBrowseResults"
+ "_btAdvAddrPublicData"
+ "_btAdvAddrPublicStr"
+ "_coalescingIdentifiers"
+ "_deviceID"
+ "_deviceOperatingSystemVersion"
+ "_handleReceivedRequestID:request:options:responseHandler:cnx:"
+ "_ineligibleDevices"
+ "_ineligibleDevicesAdd:"
+ "_ineligibleDevicesCheck:"
+ "_ineligibleDevicesMatchResult:"
+ "_ineligibleDevicesRemove:"
+ "_initWithDevice:alternateEndpoint:"
+ "_isClientWithinAWDLTimeoutGracePeriod:currentTime:"
+ "_isEqualToDestination:"
+ "_isEqualToQueryResult:"
+ "_isPublicBluetoothAddressAdvertisingSupported"
+ "_messageHandlerProvider"
+ "_nsStringFromNullableCString:"
+ "_peerHasAcked"
+ "_pendingClientBrowseResults"
+ "_receivedEventID:onXPCCnx:event:options:rpCnx:"
+ "_receivedRequestID:onXPCCnx:request:options:responseHandler:rpCnx:"
+ "_remove:"
+ "_serverBTRotatingIdentifierChanged"
+ "_serviceDiscoveryEvaluateDevice:"
+ "_serviceDiscoveryFindDevices:"
+ "_serviceDiscoveryIsSupportedByDevice:"
+ "_setNeedsUpdate"
+ "_shortDescription"
+ "_updateAWDLAdvertiserClients:"
+ "_updateDeviceInfo"
+ "_updateOptionsWithAuthFlags:"
+ "_updatePending"
+ "addMappingForDestination:endpointID:"
+ "advertisesPublicBluetoothAddress"
+ "advertisesPublicBluetoothAddress -> %d from %#{pid}\n"
+ "alternativeEndpoints"
+ "batchUpdateClientBrowseResult:"
+ "batchingClientBrowseResults"
+ "canUpdateWithDestination:"
+ "com.apple.rapport.AdvertisePublicBluetoothAddress"
+ "com.apple.rapport.LaunchListener"
+ "companionLinkSetAdvertisesPublicBluetoothAddress:completion:"
+ "copyWithZone:"
+ "deliverEventID:event:options:cnx:"
+ "deliverRequestID:request:options:responseHandler:cnx:"
+ "destinationWithAlternateEndpoint:"
+ "destinationWithDevice:"
+ "device.identifier"
+ "deviceOperatingSystemVersion"
+ "endpoint.destination.preferredDevice"
+ "eventHandlers"
+ "handleAndLaunchReceivingProcessForServiceType:receivedRequestID:request:options:responseHandler:cnx:"
+ "handleEventIDDeregistration:"
+ "handleEventIDRegistration:options:handler:"
+ "handleRequestIDDeregistration:"
+ "handleRequestIDRegistration:options:handler:"
+ "handlers"
+ "handlersForStatusFlags:"
+ "hasToDeliverMessage:event:options:"
+ "ineligibleDevices"
+ "initWithDestination:applicationService:endpointID:discoverySessionID:shouldAutomapListener:"
+ "initWithDomain:code:userInfo:"
+ "intersectsSet:"
+ "invalid"
+ "isGuest"
+ "isQRAllowed:serviceProvider:"
+ "isServiceDiscoveryEnabled:serviceProvider:"
+ "isSupportedByDevice:"
+ "isValid"
+ "launchListenerForService:completion:"
+ "launchXPCListenerForService:additionalPayload:completion:"
+ "log"
+ "matchesEndpointInfo:"
+ "messageHandlerProvider"
+ "peerHasAcked"
+ "pendingClientBrowseResults"
+ "preferredDevice"
+ "processEventID:event:options:cnx:"
+ "processRequestID:request:options:responseHandler:cnx:"
+ "q24@?0@\"RPCompanionLinkDevice\"8@\"RPCompanionLinkDevice\"16"
+ "receivedEventID:event:options:cnx:"
+ "receivedRequestID:request:options:responseHandler:cnx:"
+ "registerForDaemonEvents"
+ "removeDestination:"
+ "requestHandlers"
+ "rpPBA"
+ "setAdvertisesPublicBluetoothAddress:"
+ "setAlternativeEndpoints:"
+ "setBatchingClientBrowseResults:"
+ "setDeviceID:"
+ "setDeviceOperatingSystemVersion:"
+ "setIneligibleDevices:"
+ "setPeerHasAcked:"
+ "setPendingClientBrowseResults:"
+ "setServerFlags:"
+ "setXpcServiceLaunchHandler:"
+ "sortUsingComparator:"
+ "statusFlag"
+ "txtRecordForApplicationService:"
+ "updateClientBrowseResult:browseResponse:token:agentUUID:agentClientID:agentClientPID:applicationService:discoverySessionID:predicate:"
+ "updateEndpoint:applicationService:"
+ "updateMappingForDestination:"
+ "updateWithDestination:remove:"
+ "v24@0:8@\"OS_dispatch_queue\"16"
+ "v32@?0r*8r*16Q24"
+ "v40@0:8@\"NSString\"16@\"NSDictionary\"24@?<B@?@\"NSString\"@\"NSDictionary\"@\"NSDictionary\"@?<v@?@\"NSDictionary\"@\"NSDictionary\"@\"NSError\">@\"RPConnection\">32"
+ "v40@0:8@\"NSString\"16@\"NSDictionary\"24@?<v@?@\"NSString\"@\"NSDictionary\"@\"NSDictionary\"@\"RPConnection\">32"
+ "v40@?0@\"NSString\"8@\"NSDictionary\"16@\"NSDictionary\"24@\"RPConnection\"32"
+ "v56@?0@\"NSString\"8@\"NSString\"16@\"NSDictionary\"24@\"NSDictionary\"32@?<v@?@\"NSDictionary\"@\"NSDictionary\"@\"NSError\">40@\"RPConnection\"48"
+ "v84@0:8@16@?24@32@40@48i56@60@68@76"
+ "wifiP2PClientTimestamps"
+ "xpcRequestIDServiceMap"
+ "xpcServiceLaunchHandler"
- " alternative=%@ "
- "%@ DISCOVER: Adding QR endpoint %@ to endpoint %@ in RPNWDiscoverySession[%@]"
- "%@ DISCOVER: Evaluating %lu endpoints in RPNWDiscoverySession[%@]"
- "%@ DISCOVER: Produced %lu endpoints from evaluation in RPNWDiscoverySession[%@]"
- "%@ DISCOVER: RPNWDiscoverySession[%@]: Skipping service discovery evaluation."
- "%@ DISCOVER: Service available only via QR in RPNWDiscoverySession[%@] - %@"
- "%@ Incoming connection ready signaling READY"
- "%@ RESOLVE: Adding QR endpoint %@\n"
- "+[RPNWEndpoint updateClientBrowseResult:browseResponse:token:agentUUID:agentClientID:agentClientPID:applicationService:discoverySessionID:predicate:transform:]_block_invoke"
- "+[RPNWPeer updateEndpoint:forDevice:applicationService:]"
- "-[RPCompanionLinkDaemon _deliverEventID:event:options:unauth:cnx:outError:]"
- "-[RPCompanionLinkDaemon _handleAndLaunchReceivingProcessForServiceType:receivedRequestID:request:options:responseHandler:unauth:cnx:]"
- "-[RPCompanionLinkDaemon _handleAndLaunchReceivingProcessForServiceType:receivedRequestID:request:options:responseHandler:unauth:cnx:]_block_invoke_2"
- "-[RPCompanionLinkDaemon _receivedEventID:event:options:unauth:cnx:]"
- "-[RPCompanionLinkDaemon _receivedRequestID:request:options:responseHandler:unauth:cnx:]"
- "-[RPCompanionLinkDaemon _sessionHandleStartRequest:options:cnx:responseHandler:]_block_invoke_3"
- "-[RPCompanionLinkXPCConnection connectionInvalidatedCore]_block_invoke_2"
- "-[RPNWDiscoverySession _serviceDiscoveryEvaluate:completion:]"
- "-[RPNWDiscoverySession _serviceDiscoveryEvaluate:completion:]_block_invoke_2"
- "-[RPNWDiscoverySession _serviceDiscoveryEvaluate:completion:]_block_invoke_3"
- "-[RPNWDiscoverySession _serviceDiscoveryEvaluateDevice:result:]_block_invoke"
- "-[RPNWDiscoverySession startDiscovery:controlFlags:deviceFilter:]_block_invoke_2"
- "-[RPNWDiscoverySession updateClientBrowseResult]_block_invoke"
- "-[RPNWEndpoint addAlternativeRepresentationDevice:]"
- "-[RPServiceDiscoveryClient isSupportedByDevice:completionHandler:]_block_invoke"
- "Adding device to existing endpoint: '%@'\n"
- "Alternative device exists on endpoint, updating to main device on endpoint"
- "B60@0:8@16@24@32@40B48@52"
- "B68@0:8@16@24@32@40@?48B56@60"
- "Endpoint already contains alternative device\n"
- "EventID '%@' for proxy device on unauthenticated connection is not allowed"
- "Found existing endpoint alternative device to update '%@'\n"
- "Ignoring received event '%@' from unauthenticated device (%@)\n"
- "Ignoring received event '%@' from unauthenticated device (%@) \n"
- "LECA1"
- "LECA2"
- "LECA3"
- "LECA4"
- "LaunchOnDemand response failed"
- "Proxy device %@ is not found"
- "T@\"NSObject<OS_dispatch_queue>\",&,N"
- "T@\"NSObject<OS_nw_endpoint>\",&,N,V_qrEndpoint"
- "T@\"RPCompanionLinkDevice\",&,N,V_alternativeDevice"
- "T@\"RPCompanionLinkDevice\",&,N,V_device"
- "_alternativeDevice"
- "_deliverEventID:event:options:unauth:cnx:outError:"
- "_handleAndLaunchReceivingProcessForServiceType:receivedRequestID:request:options:responseHandler:unauth:cnx:"
- "_handleReceivedRequestID:request:options:responseHandler:unauth:cnx:"
- "_qrEndpoint"
- "_qrEndpointForIDSDeviceIdentifier:"
- "_receivedEventID:event:options:unauth:cnx:"
- "_receivedEventID:onXPCCnx:event:options:unauth:rpCnx:"
- "_receivedRequestID:onXPCCnx:request:options:responseHandler:unauth:rpCnx:"
- "_receivedRequestID:request:options:responseHandler:unauth:cnx:"
- "_serviceDiscoveryEvaluate:completion:"
- "_serviceDiscoveryEvaluateDevice:result:"
- "_xpcRequestIDServiceMap"
- "addAlternativeRepresentationDevice:"
- "alternativeDevice"
- "arrayWithCapacity:"
- "avconference.avctester"
- "com.apple.anqe.test.service"
- "com.apple.siri.companionlink.watch"
- "createTXTRecordForEndpoint:alternativeDevice:applicationService:"
- "createTXTRecordForEndpoint:applicationService:"
- "endpoint.device.identifier"
- "initWithDevice:applicationService:endpointID:discoverySessionID:shouldAutomapListener:"
- "isSupportedByDevice:completionHandler:"
- "qrEndpoint"
- "remoteappintents.watch"
- "setAlternativeDevice:"
- "setQrEndpoint:"
- "siri_watch"
- "updateClientBrowseResult:browseResponse:token:agentUUID:agentClientID:agentClientPID:applicationService:discoverySessionID:predicate:transform:"
- "updateEndpoint:forDevice:applicationService:"
- "v24@0:8@\"NSObject<OS_dispatch_queue>\"16"
- "v24@?0@\"NSArray\"8@\"NSArray\"16"
- "v24@?0@\"NSArray\"8@?<v@?@\"NSArray\"@\"NSArray\">16"
- "v60@0:8@16@24@32@?40B48@52"
- "v60@0:8@16@24@32B40@44^@52"
- "v68@0:8@16@24@32@40@?48B56@60"
- "v92@0:8@16@?24@32@40@48i56@60@68@76@?84"
```
