## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x315d6c` | `0x3168f0` | **`+0xb84`** |
| `__AUTH_CONST.__objc_const` | `0x47d90` | `0x47ea0` | **`+0x110`** |
| `__AUTH_CONST.__cfstring` | `0x248c0` | `0x249a0` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0xe921` | `0xe9d8` | **`+0xb7`** |
| `__TEXT.__cstring` | `0x2dd34` | `0x2ddca` | **`+0x96`** |
| `__TEXT.__gcc_except_tab` | `0x6338` | `0x63a4` | **`+0x6c`** |
| `__TEXT.__objc_methlist` | `0x2c708` | `0x2c758` | **`+0x50`** |
| `__DATA_DIRTY.__data` | `0x48` | `0x88` | **`+0x40`** |
| `__DATA.__data` | `0x1ce0` | `0x1ca8` | **`-0x38`** |
| `__TEXT.__unwind_info` | `0xbdb0` | `0xbde8` | **`+0x38`** |
| `__DATA_CONST.__const` | `0xbac8` | `0xbaf8` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xf8d8` | `0xf908` | **`+0x30`** |
| `__DATA.__bss` | `0x978` | `0x998` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x33d0` | `0x33e8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x14c8` | `0x14d0` | **`+0x8`** |
| `__TEXT.__const` | `0x698` | `0x6a0` | **`+0x8`** |

### Other Changes

```diff

-4026.110.75.1.0
+4026.100.79.0.0

-  Functions: 20997
-  Symbols:   30222
-  CStrings:  6754
+  Functions: 21006
+  Symbols:   30236
+  CStrings:  6763
Symbols:
+ +[MRSystemMediaBundles _offProcessPlaybackHostBundleIDsForBundle:]
+ +[MRSystemMediaBundles processBundleID:mayDonateEntitiesForBundleID:]
+ -[MRAVOutputDevice(MRAVRoutingDiscoverySessionAdditions) mr_debugName]
+ -[MRCreateHostedEndpointResponseMessage details]
+ -[MRCreateHostedEndpointResponseMessage initWithGroupUID:details:]
+ -[MRUserSettings bypassAvailabilityChecksForLiveAppEntityFeedDonations]
+ -[_MRCreateHostedEndpointResponseProtobuf details]
+ -[_MRCreateHostedEndpointResponseProtobuf hasDetails]
+ -[_MRCreateHostedEndpointResponseProtobuf setDetails:]
+ OBJC_IVAR_$__MRCreateHostedEndpointResponseProtobuf._details
+ _MRMediaRemoteCopyDisabledReasonDescription
+ _OBJC_CLASS_$_NSBlockOperation
+ _OBJC_IVAR_$_MRAVRoutingDiscoverySession._lastLoggedEndpoints
+ _OBJC_IVAR_$_MRAVRoutingDiscoverySession._lastLoggedOutputDevicesOutputDevices
+ _OBJC_IVAR_$_MRAVRoutingDiscoverySession._verboseEndpointLoggingQueue
+ _OBJC_IVAR_$_MRAVRoutingDiscoverySession._verboseOutputDeviceLoggingQueue
+ _OBJC_IVAR_$_MRUserSettings._bypassAvailabilityChecksForLiveAppEntityFeedDonations
+ __OBJC_$_INSTANCE_METHODS_MRAVOutputDevice(MRAVRoutingDiscoverySessionAdditions)
+ ___66+[MRSystemMediaBundles _offProcessPlaybackHostBundleIDsForBundle:]_block_invoke
+ ___71-[MRUserSettings bypassAvailabilityChecksForLiveAppEntityFeedDonations]_block_invoke
+ __offProcessPlaybackHostBundleIDsForBundle:.__musicHosts
+ __offProcessPlaybackHostBundleIDsForBundle:.__once
+ __offProcessPlaybackHostBundleIDsForBundle:.__podcastsHosts
+ _bypassAvailabilityChecksForLiveAppEntityFeedDonations.onceToken
- -[MRCreateHostedEndpointResponseMessage initWithGroupUID:]
- _MRUserSettingsGroupSessionBoopContext
- _MRUserSettingsGroupSessionNearbyDiscoveryContext
- _MRUserSettingsNearbyDeviceIdentifiersContext
- _MRUserSettingsRoutePickerAirPlayAllowListContext
- _MRUserSettingsRoutePickerAirPlayDenyListContext
- _MRUserSettingsSystemVolumeCapabilitiesDidChangeContext
- _MRUserSettingsSystemVolumeDidChangeContext
- __OBJC_$_INSTANCE_METHODS_MRAVOutputDevice
- __OBJC_$_PROP_LIST_MRAVOutputDevice
CStrings:
+ "%{public}@ - Verbose Endpoints changed\n%{public}@"
+ "%{public}@ - Verbose Output devices changed\n%{public}@"
+ "BypassAvailabilityChecksForLiveAppEntityFeedDonations"
+ "LowPerformance"
+ "LowPowerMode"
+ "PlayingAd"
+ "ThermalPressure"
+ "[MRIDSCompanionConnection] Message Sent<%lu>: data=%@ type=%@ destination=%@ session=%@ idsID=%@"
+ "[MRIDSCompanionConnection] Message received<%@>: data=%@ type=%@ destination=%@ session=%@ replyID=%@ idsGUID=%@"
+ "[MRIDSCompanionConnection] Unhandled message<%@>: no handler for type=%@ destination=%@ session=%@ idsGUID=%@"
+ "com.apple.AirMusic"
+ "com.apple.AirPodcasts"
- "Attempting to send IDS messages before first unlock"
- "[MRIDSCompanionConnection] Message Sent<%lu>: data=%@ type=%@ destination=%@ session=%@"
- "[MRIDSCompanionConnection] Message received<%@>: data=%@ type=%@ destination=%@ session=%@ replyID=%@"
```
