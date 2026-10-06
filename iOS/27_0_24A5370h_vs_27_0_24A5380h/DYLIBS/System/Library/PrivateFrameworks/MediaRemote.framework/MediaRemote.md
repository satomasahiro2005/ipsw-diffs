## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x315894` | `0x315d6c` | **`+0x4d8`** |
| `__TEXT.__oslogstring` | `0xe4ad` | `0xe921` | **`+0x474`** |
| `__TEXT.__gcc_except_tab` | `0x6724` | `0x6338` | **`-0x3ec`** |
| `__AUTH_CONST.__cfstring` | `0x24660` | `0x248c0` | **`+0x260`** |
| `__TEXT.__cstring` | `0x2dc15` | `0x2dd34` | **`+0x11f`** |
| `__AUTH_CONST.__objc_const` | `0x47ca0` | `0x47d90` | **`+0xf0`** |
| `__DATA_DIRTY.__bss` | `0x520` | `0x5c8` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x8660` | `0x8700` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x2e40` | `0x2da0` | **`-0xa0`** |
| `__DATA.__bss` | `0xa00` | `0x978` | **`-0x88`** |
| `__DATA_CONST.__const` | `0xba40` | `0xbac8` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0x2c6a0` | `0x2c708` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0xbe08` | `0xbdb0` | **`-0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0xf8b0` | `0xf8d8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x14b0` | `0x14c8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x33c4` | `0x33d0` | **`+0xc`** |
| `__TEXT.__const` | `0x690` | `0x698` | **`+0x8`** |

### Other Changes

```diff

-4026.100.68.0.0
+4026.110.75.1.0

-  Functions: 21005
-  Symbols:   30218
-  CStrings:  6723
+  Functions: 20997
+  Symbols:   30222
+  CStrings:  6754
Symbols:
+ +[MRIRRoute _parsedCandidateIdentifier:]
+ -[MRAVConcreteRoutingDiscoverySession _maybeScheduleReload]
+ -[MRAVConcreteRoutingDiscoverySession setAlwaysAllowUpdates:]
+ -[MRAVLightweightReconnaissanceSession searchEndpointsForGroupUID:timeout:details:queue:completion:]
+ -[MRAVLightweightReconnaissanceSession searchEndpointsWithPredicate:timeout:details:queue:completion:]
+ -[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:timeout:details:queue:completion:]
+ -[MRAVRoutingDiscoverySession clientAlwaysAllowUpdatesStates]
+ -[MRAVRoutingDiscoverySession setClientAlwaysAllowUpdatesStates:]
+ -[MRAVRoutingDiscoverySessionWrapper _addCallbacksForSession:]
+ -[MRAVRoutingDiscoverySessionWrapper _currentVisibleEndpointsForSession:]
+ -[MRAVRoutingDiscoverySessionWrapper _currentVisibleOutputDevicesForSession:]
+ -[MRAVRoutingDiscoverySessionWrapper _removeCallbacksForSession:]
+ -[MRAVRoutingDiscoverySessionWrapper reevaluateAlwaysAllowUpdatesForSession:]
+ -[MRIRRoute candidateIdentifier]
+ -[MRIRRoute protocolIdentifier]
+ -[MRIRRoute setProtocolIdentifier:]
+ -[MRStaticRouteBannerRequest protocolName]
+ -[MRStaticRouteBannerRequest protocolUID]
+ -[MRStaticRouteBannerRequest setProtocolName:]
+ -[MRStaticRouteBannerRequest setProtocolUID:]
+ -[MRUserSettings companionRemoteControlServiceConnectionDelay]
+ -[MRUserSettings externalDeviceArtificialConnectionDelay]
+ -[MRUserSettings remoteSessionDefaultAssertionInterval]
+ _MRMediaRemoteRouteStatusErrorDomain
+ _OBJC_IVAR_$_MRAVConcreteRoutingDiscoverySession._outputDevicesCacheStale
+ _OBJC_IVAR_$_MRAVRoutingDiscoverySession._clientAlwaysAllowUpdatesStates
+ _OBJC_IVAR_$_MRAVRoutingDiscoverySessionWrapper._endpointsAwaitingInitialFire
+ _OBJC_IVAR_$_MRAVRoutingDiscoverySessionWrapper._endpointsCallbackToken
+ _OBJC_IVAR_$_MRAVRoutingDiscoverySessionWrapper._outputDevicesAwaitingInitialFire
+ _OBJC_IVAR_$_MRAVRoutingDiscoverySessionWrapper._outputDevicesCallbackToken
+ _OBJC_IVAR_$_MRIRRoute._protocolIdentifier
+ _OBJC_IVAR_$_MRStaticRouteBannerRequest._protocolName
+ _OBJC_IVAR_$_MRStaticRouteBannerRequest._protocolUID
+ ___100-[MRAVLightweightReconnaissanceSession searchEndpointsForGroupUID:timeout:details:queue:completion:]_block_invoke
+ ___100-[MRAVLightweightReconnaissanceSession searchEndpointsForGroupUID:timeout:details:queue:completion:]_block_invoke_2
+ ___102-[MRAVLightweightReconnaissanceSession searchEndpointsWithPredicate:timeout:details:queue:completion:]_block_invoke
+ ___102-[MRAVLightweightReconnaissanceSession searchEndpointsWithPredicate:timeout:details:queue:completion:]_block_invoke_2
+ ___102-[MRAVLightweightReconnaissanceSession searchEndpointsWithPredicate:timeout:details:queue:completion:]_block_invoke_3
+ ___105-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:timeout:details:queue:completion:]_block_invoke
+ ___105-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:timeout:details:queue:completion:]_block_invoke_2
+ ___105-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:timeout:details:queue:completion:]_block_invoke_3
+ ___105-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:timeout:details:queue:completion:]_block_invoke_4
+ ___105-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:timeout:details:queue:completion:]_block_invoke_5
+ ___49-[MRAVRoutingDiscoverySession alwaysAllowUpdates]_block_invoke
+ ___53-[MRAVRoutingDiscoverySession setAlwaysAllowUpdates:]_block_invoke
+ ___55-[MRUserSettings remoteSessionDefaultAssertionInterval]_block_invoke
+ ___57-[MRUserSettings externalDeviceArtificialConnectionDelay]_block_invoke
+ ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke
+ ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_2
+ ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_3
+ ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_4
+ ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_5
+ ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_6
+ ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_7
+ ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_8
+ ___59-[MRAVConcreteRoutingDiscoverySession _maybeScheduleReload]_block_invoke
+ ___59-[MRAVConcreteRoutingDiscoverySession _maybeScheduleReload]_block_invoke_2
+ ___60-[MRAVRoutingDiscoverySessionWrapper setAlwaysAllowUpdates:]_block_invoke
+ ___62-[MRAVRoutingDiscoverySessionWrapper _addCallbacksForSession:]_block_invoke
+ ___62-[MRAVRoutingDiscoverySessionWrapper _addCallbacksForSession:]_block_invoke_2
+ ___62-[MRUserSettings companionRemoteControlServiceConnectionDelay]_block_invoke
+ ___97+[MRProximityProvider _migrate:destinationEndpoint:destinationUID:outputDevice:label:completion:]_block_invoke_3
+ ___97+[MRProximityProvider _migrate:destinationEndpoint:destinationUID:outputDevice:label:completion:]_block_invoke_4
+ ___97+[MRProximityProvider _migrate:destinationEndpoint:destinationUID:outputDevice:label:completion:]_block_invoke_5
+ ___block_descriptor_160_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r_e45_v32?0"MRAVOutputDevice"8I16I20"NSString"24lr32l8r40l8r48l8r56l8r64l8r72l8r80l8r88l8r96l8r104l8r112l8r120l8r128l8r136l8r144l8r152l8
+ ___block_descriptor_40_e8_32w_e8_v16?08lw32l8
+ ___block_descriptor_48_e8_32s40s_e31_v32?08?<v?"NSArray">16^B24ls32l8s40l8
+ ___block_descriptor_76_e8_32s40s48s56bs64bs_e34_v24?0"MRAVEndpoint"8"NSError"16ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_80_e8_32s40s48s56s64bs72r_e34_v24?0"MRAVEndpoint"8"NSError"16ls32l8s40l8s48l8s64l8s56l8r72l8
+ ___block_descriptor_96_e8_32s40s48s56s64s72s80bs_e58_v40?0"NSArray"8"NSArray"16"MRAVEndpoint"24"NSError"32ls32l8s40l8s48l8s80l8s56l8s64l8s72l8
+ _companionRemoteControlServiceConnectionDelay.__interval
+ _companionRemoteControlServiceConnectionDelay.__once
+ _externalDeviceArtificialConnectionDelay.__interval
+ _externalDeviceArtificialConnectionDelay.__once
+ _kMRMediaRemotePushTokensUserInfoKey
+ _remoteSessionDefaultAssertionInterval.__interval
+ _remoteSessionDefaultAssertionInterval.__once
- -[MRAVConcreteRoutingDiscoverySession _onQueue_setTargetAudioSessionID:]
- -[MRAVConcreteRoutingDiscoverySession routingContextUID]
- -[MRAVConcreteRoutingDiscoverySession setRoutingContextUID:]
- -[MRAVConcreteRoutingDiscoverySession setTargetAudioSessionID:]
- -[MRAVConcreteRoutingDiscoverySession targetAudioSessionID]
- -[MRAVRoutingDiscoverySessionWrapper transferCallbacksFromSession:toSession:]
- -[MRAVRoutingDiscoverySessionWrapper transferEndpointsAddedCallbacksFromSession:toSession:]
- -[MRAVRoutingDiscoverySessionWrapper transferEndpointsChangedCallbacksFromSession:toSession:]
- -[MRAVRoutingDiscoverySessionWrapper transferEndpointsModifiedCallbacksFromSession:toSession:]
- -[MRAVRoutingDiscoverySessionWrapper transferEndpointsRemovedCallbacksFromSession:toSession:]
- -[MRAVRoutingDiscoverySessionWrapper transferOutputDevicesAddedCallbacksFromSession:toSession:]
- -[MRAVRoutingDiscoverySessionWrapper transferOutputDevicesChangedCallbacksFromSession:toSession:]
- -[MRAVRoutingDiscoverySessionWrapper transferOutputDevicesModifiedCallbacksFromSession:toSession:]
- -[MRAVRoutingDiscoverySessionWrapper transferOutputDevicesRemovedCallbacksFromSession:toSession:]
- -[MRUserSettings externalDeviceArtificalConnectionDelay]
- -[MRUserSettings remoteSessionGracePeriodDuration]
- GCC_except_table126
- _OBJC_IVAR_$_MRAVConcreteRoutingDiscoverySession._clientProvidedTargetAudioSessionID
- _OBJC_IVAR_$_MRAVConcreteRoutingDiscoverySession._routingContextUID
- _OBJC_IVAR_$_MRAVConcreteRoutingDiscoverySession._targetAudioSessionID
- _OBJC_IVAR_$_MRAVRoutingDiscoverySession._alwaysAllowUpdates
- _OBJC_IVAR_$_MRAVRoutingDiscoverySessionWrapper._endpointsTokensMap
- _OBJC_IVAR_$_MRAVRoutingDiscoverySessionWrapper._outputDevicesTokensMap
- ___101-[MRAVLightweightReconnaissanceSession searchEndpointsWithPredicate:timeout:reason:queue:completion:]_block_invoke
- ___101-[MRAVLightweightReconnaissanceSession searchEndpointsWithPredicate:timeout:reason:queue:completion:]_block_invoke_2
- ___101-[MRAVLightweightReconnaissanceSession searchEndpointsWithPredicate:timeout:reason:queue:completion:]_block_invoke_3
- ___101-[MRAVLightweightReconnaissanceSession searchEndpointsWithPredicate:timeout:reason:queue:completion:]_block_invoke_4
- ___56-[MRAVConcreteRoutingDiscoverySession routingContextUID]_block_invoke
- ___56-[MRUserSettings externalDeviceArtificalConnectionDelay]_block_invoke
- ___59-[MRAVConcreteRoutingDiscoverySession targetAudioSessionID]_block_invoke
- ___60-[MRAVConcreteRoutingDiscoverySession setRoutingContextUID:]_block_invoke
- ___61-[MRAVConcreteRoutingDiscoverySession initWithConfiguration:]_block_invoke_3
- ___63-[MRAVConcreteRoutingDiscoverySession setTargetAudioSessionID:]_block_invoke
- ___64-[MRAVRoutingDiscoverySessionWrapper addEndpointsAddedCallback:]_block_invoke_2
- ___66-[MRAVRoutingDiscoverySessionWrapper addEndpointsChangedCallback:]_block_invoke_2
- ___66-[MRAVRoutingDiscoverySessionWrapper addEndpointsRemovedCallback:]_block_invoke
- ___66-[MRAVRoutingDiscoverySessionWrapper addEndpointsRemovedCallback:]_block_invoke_2
- ___67-[MRAVRoutingDiscoverySessionWrapper addEndpointsModifiedCallback:]_block_invoke
- ___67-[MRAVRoutingDiscoverySessionWrapper addEndpointsModifiedCallback:]_block_invoke_2
- ___68-[MRAVRoutingDiscoverySessionWrapper addOutputDevicesAddedCallback:]_block_invoke_2
- ___70-[MRAVRoutingDiscoverySessionWrapper addOutputDevicesChangedCallback:]_block_invoke_2
- ___70-[MRAVRoutingDiscoverySessionWrapper addOutputDevicesRemovedCallback:]_block_invoke
- ___70-[MRAVRoutingDiscoverySessionWrapper addOutputDevicesRemovedCallback:]_block_invoke_2
- ___71-[MRAVRoutingDiscoverySessionWrapper addOutputDevicesModifiedCallback:]_block_invoke
- ___71-[MRAVRoutingDiscoverySessionWrapper addOutputDevicesModifiedCallback:]_block_invoke_2
- ___91-[MRAVRoutingDiscoverySessionWrapper transferEndpointsAddedCallbacksFromSession:toSession:]_block_invoke
- ___91-[MRAVRoutingDiscoverySessionWrapper transferEndpointsAddedCallbacksFromSession:toSession:]_block_invoke_2
- ___92-[MRAVLightweightReconnaissanceSession searchOutputDevices:reason:timeout:queue:completion:]_block_invoke
- ___92-[MRAVLightweightReconnaissanceSession searchOutputDevices:reason:timeout:queue:completion:]_block_invoke_2
- ___92-[MRAVLightweightReconnaissanceSession searchOutputDevices:reason:timeout:queue:completion:]_block_invoke_3
- ___92-[MRAVLightweightReconnaissanceSession searchOutputDevices:reason:timeout:queue:completion:]_block_invoke_4
- ___92-[MRAVLightweightReconnaissanceSession searchOutputDevices:reason:timeout:queue:completion:]_block_invoke_5
- ___93-[MRAVRoutingDiscoverySessionWrapper transferEndpointsChangedCallbacksFromSession:toSession:]_block_invoke
- ___93-[MRAVRoutingDiscoverySessionWrapper transferEndpointsChangedCallbacksFromSession:toSession:]_block_invoke_2
- ___93-[MRAVRoutingDiscoverySessionWrapper transferEndpointsRemovedCallbacksFromSession:toSession:]_block_invoke
- ___93-[MRAVRoutingDiscoverySessionWrapper transferEndpointsRemovedCallbacksFromSession:toSession:]_block_invoke_2
- ___94-[MRAVRoutingDiscoverySessionWrapper transferEndpointsModifiedCallbacksFromSession:toSession:]_block_invoke
- ___94-[MRAVRoutingDiscoverySessionWrapper transferEndpointsModifiedCallbacksFromSession:toSession:]_block_invoke_2
- ___95-[MRAVRoutingDiscoverySessionWrapper transferOutputDevicesAddedCallbacksFromSession:toSession:]_block_invoke
- ___95-[MRAVRoutingDiscoverySessionWrapper transferOutputDevicesAddedCallbacksFromSession:toSession:]_block_invoke_2
- ___97-[MRAVRoutingDiscoverySessionWrapper transferOutputDevicesChangedCallbacksFromSession:toSession:]_block_invoke
- ___97-[MRAVRoutingDiscoverySessionWrapper transferOutputDevicesChangedCallbacksFromSession:toSession:]_block_invoke_2
- ___97-[MRAVRoutingDiscoverySessionWrapper transferOutputDevicesRemovedCallbacksFromSession:toSession:]_block_invoke
- ___97-[MRAVRoutingDiscoverySessionWrapper transferOutputDevicesRemovedCallbacksFromSession:toSession:]_block_invoke_2
- ___98-[MRAVRoutingDiscoverySessionWrapper transferOutputDevicesModifiedCallbacksFromSession:toSession:]_block_invoke
- ___98-[MRAVRoutingDiscoverySessionWrapper transferOutputDevicesModifiedCallbacksFromSession:toSession:]_block_invoke_2
- ___99-[MRAVLightweightReconnaissanceSession searchEndpointsForGroupUID:timeout:reason:queue:completion:]_block_invoke
- ___99-[MRAVLightweightReconnaissanceSession searchEndpointsForGroupUID:timeout:reason:queue:completion:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48bs_e58_v40?0"NSArray"8"NSArray"16"MRAVEndpoint"24"NSError"32ls32l8s40l8s48l8
- ___block_descriptor_64_e8_32s40s48bs56r_e34_v24?0"MRAVEndpoint"8"NSError"16ls32l8s48l8s40l8r56l8
- ___block_descriptor_96_e8_32r40r48r56r64r72r80r88r_e45_v32?0"MRAVOutputDevice"8I16I20"NSString"24lr32l8r40l8r48l8r56l8r64l8r72l8r80l8r88l8
- _externalDeviceArtificalConnectionDelay.__interval
- _externalDeviceArtificalConnectionDelay.__once
CStrings:
+ " protocolName: %@"
+ " protocolUID: %@"
+ "%@%@\n%@ %@ %@"
+ "%ld bytes"
+ "CreateEndpoint"
+ "MRMediaRemoteRouteStatusErrorDomain"
+ "O"
+ "Received Notification %@"
+ "Update: %{public}@<%{public}@> audio session found %lu non-RC / custom-protocol devices, completing without RC discovery"
+ "Update: %{public}@<%{public}@> audio session found no legacy / custom-protocol devices, falling back to RemoteControl discovery"
+ "[ExternalRoutingDiscoverySession] Destination not yet ready. Enqueuing discoveryMode change..."
+ "[MRAVVolumeClientEndpoint] Creating %{public}@ with volumeController: %{public}@"
+ "[MRAVVolumeClientEndpoint] Mapping %{public}@ -> %{public}@"
+ "[MRAVVolumeClientEndpoint] ResolvedOutputDevices: %{public}@"
+ "[MRAVVolumeClientEndpoint] SharedAudioOutputContextOutputDevices: %{public}@"
+ "[MRAVVolumeClientEndpoint] SystemAudioOutputContextOutputDevices: %{public}@"
+ "[MRAVVolumeClientEndpoint] VolumeClientOutputDevices: %{public}@"
+ "[MRNowPlayingPushTokenManager]   token key: %{public}@ (%ld bytes)"
+ "[MRNowPlayingPushTokenManager] _handleTokensDidChange: delivering token to observer for %{public}@ (%ld bytes)"
+ "[MRNowPlayingPushTokenManager] _handleTokensDidChange: no token for observer %{public}@"
+ "[MRNowPlayingPushTokenManager] _handleTokensDidChange: notifying %ld observer(s)"
+ "[MRNowPlayingPushTokenManager] _handleTokensDidChange: received %ld token(s)"
+ "[MRNowPlayingPushTokenManager] observeUpdateTokenUpdatesForSessionID: %{public}@"
+ "[MRNowPlayingPushTokenManager] observeUpdateTokenUpdatesForSessionID: %{public}@ - delivering initial token (%ld bytes)"
+ "[MRNowPlayingPushTokenManager] observeUpdateTokenUpdatesForSessionID: %{public}@ - no initial token, refreshing from daemon"
+ "[MRNowPlayingPushTokenManager] updateTokenForSessionID: %{public}@ -> %{public}@"
+ "car: %lu;"
+ "companionRemoteControlServiceConnectionDelay"
+ "desktop: %lu;"
+ "externalDeviceArtificialConnectionDelay"
+ "gamingConsole: %lu;"
+ "kMRMediaRemotePushTokensUserInfoKey"
+ "laptop: %lu;"
+ "nil"
+ "phone: %lu;"
+ "pn"
+ "protocolIdentifier"
+ "puid"
+ "remoteSessionDefaultAssertionInterval"
+ "searchEndpointsWithPredicate"
+ "tablet: %lu;"
+ "v16@?0@8"
+ "wearable: %lu;"
+ "web: %lu;"
- "%@%@\n%@ %@"
- "MRAVLightweightReconnaissanceSession.searchOutputDevices-%@"
- "Receieved Notification %@"
- "RemoteSessionGracePeriodDuration"
- "[MRAVRoutingDiscoverySessionWrapper] <%p> Transferring callbacks from: %{public}@ to: %{public}@"
- "[MRAVVolumeClientEndpoint] Creating %@ with volumeController: %@"
- "[MRAVVolumeClientEndpoint] Mapping %@ -> %@"
- "[MRAVVolumeClientEndpoint] ResolvedOutputDevices: %@"
- "[MRAVVolumeClientEndpoint] SharedAudioOutputContextOutputDevices: %@"
- "[MRAVVolumeClientEndpoint] SystemAudioOutputContextOutputDevices: %@"
- "[MRAVVolumeClientEndpoint] VolumeClientOutputDevices: %@"
- "externalDeviceArtificalConnectionDelay"
- "now_playing_agent"
```
