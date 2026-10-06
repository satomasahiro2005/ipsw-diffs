## terminusd

> `/usr/libexec/terminusd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f8a04` | `0x1fc2a4` | **`+0x38a0`** |
| `__TEXT.__cstring` | `0x50cb9` | `0x5167c` | **`+0x9c3`** |
| `__DATA_CONST.__cfstring` | `0xdb80` | `0xdf00` | **`+0x380`** |
| `__TEXT.__objc_methname` | `0x136f5` | `0x138f5` | **`+0x200`** |
| `__DATA_CONST.__const` | `0x4d08` | `0x4e60` | **`+0x158`** |
| `__DATA_CONST.__got` | `0xda0` | `0xef0` | **`+0x150`** |
| `__DATA.__objc_const` | `0x19ab8` | `0x19c00` | **`+0x148`** |
| `__TEXT.__objc_stubs` | `0x93a0` | `0x94c0` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x2d7e` | `0x2dee` | **`+0x70`** |
| `__TEXT.__objc_methtype` | `0x443f` | `0x44ab` | **`+0x6c`** |
| `__TEXT.__auth_stubs` | `0x3e90` | `0x3ef0` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x460` | `0x4a4` | **`+0x44`** |
| `__DATA.__objc_selrefs` | `0x2ed0` | `0x2f10` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3130` | `0x3170` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x1f58` | `0x1f88` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x5bdc` | `0x5c04` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x1fb0` | `0x1fd4` | **`+0x24`** |
| `__DATA.__bss` | `0xcb8` | `0xcd8` | **`+0x20`** |
| `__DATA.__data` | `0x1918` | `0x1938` | **`+0x20`** |
| `__TEXT.__const` | `0x71c` | `0x72c` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x61fc` | `0x61f4` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-914.0.1.0.4
+914.0.14.502.2

-  Functions: 3992
-  Symbols:   1530
-  CStrings:  11586
+  Functions: 4019
+  Symbols:   1544
+  CStrings:  11666
Symbols:
+ _$s9WiFiAware10WAEndpointV19performanceForecastSDyAA17WAPerformanceModeOAA0gF0VGvg
+ _$s9WiFiAware17WAPerformanceModeOSHAAMc
+ _$s9WiFiAware17WAPerformanceModeOSQAAMc
+ _$s9WiFiAware21WAPerformanceForecastV14signalStrengthSdSgvg
+ _$s9WiFiAware21WAPerformanceForecastVMa
+ _CFUserNotificationCreate
+ _CFUserNotificationReceiveResponse
+ _OBJC_CLASS_$_LSApplicationWorkspace
+ _OBJC_CLASS_$_NSURLComponents
+ _OBJC_CLASS_$_NSURLQueryItem
+ _createStringFromNRQuickRelayPresence
+ _kCFUserNotificationAlertHeaderKey
+ _kCFUserNotificationAlertMessageKey
+ _kCFUserNotificationAlternateButtonTitleKey
+ _kCFUserNotificationDefaultButtonTitleKey
+ _nrXPCKeyDevicePreferencesQuickRelayPresence
+ _xpc_event_publisher_fire_with_reply
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_willThrowTypedImpl
CStrings:
+ "%llu-%@"
+ "%s%.30s:%-4d %@ Wi-Fi Aware consecutive failure count: %lu -> %lu"
+ "%s%.30s:%-4d %@: Wi-Fi Aware suppressed; not setting up a NAN datapath"
+ "%s%.30s:%-4d %@: rejecting Wi-Fi Aware activate request since we are a multicast source; distribution will flow over Wi-Fi"
+ "%s%.30s:%-4d %@: rejecting Wi-Fi Aware probe request, we are a multicast source"
+ "%s%.30s:%-4d %@: sending a Wi-Fi Aware deactivate request"
+ "%s%.30s:%-4d Already pairing with device %@, ignoring discovery update"
+ "%s%.30s:%-4d Cancel Wi-Fi Aware Probing operation; RSSI: %f"
+ "%s%.30s:%-4d NRDTriggerTapToRadar: CFUserNotificationCreate failed: %d"
+ "%s%.30s:%-4d NRDTriggerTapToRadar: suppressed for %@ (rate-limited)"
+ "%s%.30s:%-4d Not accepting Wi-Fi Aware connection to %@: device is a multicast source"
+ "%s%.30s:%-4d Not establishing Wi-Fi Aware since it is not supported."
+ "%s%.30s:%-4d Not marking %@ as my distributee: reachable over wired"
+ "%s%.30s:%-4d Probed Wi-Fi Aware RSSI %f for %@"
+ "%s%.30s:%-4d Probing with %@ has succeeded, cancel Wi-Fi Aware"
+ "%s%.30s:%-4d Skipping Wi-Fi Aware bring-up with distributor: device is a multicast source"
+ "%s%.30s:%-4d Tearing down Wi-Fi Aware link with %@: device is a multicast source"
+ "%s%.30s:%-4d Waiting for the browser to cancel the operation, RSSI: %f"
+ "%s%.30s:%-4d Wi-Fi Aware probing succeeded with %@"
+ "%s%.30s:%-4d [XPC event: %@] receive XPC reply for %@ : %@"
+ "%s%.30s:%-4d setQuickRelayPresence: %@ -> %@"
+ "+[NRXPCEventManager postAppSvcListenEventForASName:]_block_invoke"
+ ", WA-probed"
+ "-[NRApplicationServiceManager processActiveServiceQueriesIfNeeded]_block_invoke_2"
+ "-[NRApplicationServiceManager processIncomingRemotePayloadRequestForDeviceID:requestOptions:]"
+ "-[NRApplicationServiceManager serviceDiscoveryClient:didRequestRemotePayloadForDevice:requestOptions:completion:]"
+ "-[NRBabelManager neighbourWiFiAwareDidDisconnect:errored:]"
+ "-[NRBabelManager releaseWiFiAwareDataPathWithDistributor]"
+ "-[NRBabelManager startWiFiAwareConnectionWithDistributee:probingOnly:]"
+ "-[NRBabelNeighbour setConsecutiveWiFiAwareFailures:]"
+ "-[NRBabelNeighbour startWiFiAwareConnectionProbingOnly:]"
+ "-[NRBabelNeighbour startWiFiAwareConnectionProbingOnly:]_block_invoke"
+ "-[NRDDeviceConductor requestRemotePayloadForASClient:requestOptions:]"
+ "-[NRDDeviceConductor setQuickRelayPresence:forConnection:]"
+ "-[NRDiscoveryClient addWiFiAwareDeviceEndpointWithDeviceID:instanceName:rssi:]"
+ "-[NRDiscoveryClient client:didProbeRSSI:forDeviceID:serviceName:]"
+ "-[NRLinkDirector setQuickRelayPresence:forConnection:nrUUID:]"
+ "212336"
+ "21:23:18"
+ "675393"
+ "914.0.14.502.2"
+ "@44@0:8Q16@24@32B40"
+ "Classification"
+ "ComponentID"
+ "ComponentName"
+ "ComponentVersion"
+ "Description"
+ "Dismiss"
+ "File Radar"
+ "Jun 30 2026"
+ "Keywords"
+ "NRDTTRLastPromptTime"
+ "NRDTriggerTapToRadar"
+ "NRDTriggerTapToRadar_block_invoke_2"
+ "Not Applicable"
+ "Other Bug"
+ "Reproducibility"
+ "Title"
+ "URL"
+ "Wi-Fi Aware probe success"
+ "[%@] terminusd reported issues"
+ "_appSvcRequiresPriorityDonation"
+ "_consecutiveWiFiAwareFailures"
+ "_lastNeighbourProbedMyWaRSSITimestamp"
+ "_lastWaRSSIProbingTimestamp"
+ "_pendingRemotePayloadRequestOptions"
+ "_quickRelayPresence"
+ "_quickRelayPresenceConnectionID"
+ "_receivedRemotePayloadRequestOptions"
+ "_sdQueryQueue"
+ "_waProbingOnly"
+ "all"
+ "an error occurred in waiting state: %@"
+ "an unknown issue (type %u)"
+ "browserWithService:delegate:delegateQueue:probingOnly:"
+ "client:didProbeRSSI:forDeviceID:serviceName:"
+ "com.apple.terminusd.ttr"
+ "data stall"
+ "data stalled over %sOutput"
+ "defaultWorkspace"
+ "discovered Wi-Fi Aware endpoint for device %llu with RSSI %f"
+ "discovered endpoint has no realtime signalStrength forecast"
+ "got nil lastWaRSSIProbingTimestamp and non-nil lastWaRSSI for neighbour %@"
+ "neighbourWiFiAwareDidDisconnect:errored:"
+ "openURL:configuration:completionHandler:"
+ "probingOnly"
+ "produceRemotePayloadForScopes:requestOptions:completionHandler:"
+ "queryItemWithName:value:"
+ "requestRemotePayloadForASClient:requestOptions:"
+ "setIsCurrentRouteThroughPrimaryAssistDevice:"
+ "setQueryItems:"
+ "tap-to-radar://new"
+ "terminusd detected a %@. Tap 'File Radar' to capture a sysdiagnose."
+ "terminusd detected an issue"
+ "terminusd has detected a connectivity issue - %@ (type: %@)\n\nPlease attach a sysdiagnose taken near the time of this prompt."
+ "terminusd.ASM.SDQuery"
+ "timeIntervalSinceReferenceDate"
+ "v28@0:8@\"NRBabelNeighbour\"16B24"
+ "v32@0:8@\"NRApplicationServiceClient\"16@\"NSData\"24"
+ "v48@0:8@\"NRWiFiAwareClient\"16d24Q32@\"NSString\"40"
+ "v48@0:8@16d24Q32@40"
- "%s%.30s:%-4d Already pairing with device %@"
- "%s%.30s:%-4d Cancel Wi-Fi Aware Probing connection; RSSI: %f"
- "%s%.30s:%-4d Waiting for the browser to cancel the connection, RSSI: %f"
- "-[NRApplicationServiceManager processActiveServiceQueriesIfNeeded]_block_invoke"
- "-[NRApplicationServiceManager processIncomingRemotePayloadRequestForDeviceID:]"
- "-[NRApplicationServiceManager serviceDiscoveryClient:didRequestRemotePayloadForDevice:completion:]"
- "-[NRBabelManager neighbourWiFiAwareDidDisconnect:]"
- "-[NRBabelManager startWiFiAwareConnectionWithDistributee:]"
- "-[NRBabelNeighbour startWiFiAwareConnection]"
- "-[NRBabelNeighbour startWiFiAwareConnection]_block_invoke"
- "-[NRDDeviceConductor requestRemotePayloadForASClient:]"
- "19:49:34"
- "914.0.1.0.4"
- "Jun 18 2026"
- "_lastWaRSSITimestamp"
- "browserWithService:delegate:delegateQueue:"
- "got nil lastWaRSSITimestamp and non-nil lastWaRSSI for neighbour %@"
- "neighbourWiFiAwareDidDisconnect:"
- "produceRemotePayloadForScopes:completionHandler:"
- "requestRemotePayloadForASClient:"
- "v24@0:8@\"NRApplicationServiceClient\"16"
```
