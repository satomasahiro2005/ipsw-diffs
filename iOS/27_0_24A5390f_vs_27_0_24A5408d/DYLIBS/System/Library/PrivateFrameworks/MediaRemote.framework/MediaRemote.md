## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3168f0` | `0x317068` | **`+0x778`** |
| `__TEXT.__cstring` | `0x2ddca` | `0x2de92` | **`+0xc8`** |
| `__AUTH_CONST.__cfstring` | `0x249a0` | `0x24a20` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0xe9d8` | `0xea48` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x63a4` | `0x6368` | **`-0x3c`** |
| `__TEXT.__objc_methlist` | `0x2c758` | `0x2c788` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xf908` | `0xf930` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xbde8` | `0xbe10` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x3460` | `0x3440` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x47ea0` | `0x47e80` | **`-0x20`** |
| `__DATA_CONST.__const` | `0xbaf8` | `0xbb08` | **`+0x10`** |
| `__TEXT.__const` | `0x6a0` | `0x6b0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x33e8` | `0x33e4` | **`-0x4`** |

### Other Changes

```diff

-4026.100.79.0.0
+4026.110.83.1.0

-  Functions: 21006
-  Symbols:   30236
-  CStrings:  6763
+  Functions: 21013
+  Symbols:   30239
+  CStrings:  6771
Symbols:
+ -[MRAVLocalControlCenterEndpoint _newVolumeController]
+ -[MRAVVolumeClientEndpoint _initWithSliderType:uniqueIdentifier:]
+ -[MRAVVolumeClientEndpoint _newVolumeController]
+ -[MRAVVolumeClientEndpoint _onVolumeQueue_maybeLazyInitVolumeController]
+ -[MRAudioIntentDetails dictionaryRepresentation]
+ -[MRAudioIntentDetails initWithDictionaryRepresentation:]
+ -[MRMediaRemoteService triggerClusterErrorDialogForRouteUID:status:completion:]
+ -[MRUserSettings clearClusterConnectionThrottleOnNetworkChange]
+ GCC_except_table124
+ GCC_except_table145
+ GCC_except_table352
+ _MRCreateUUIDv5
+ _MRNowPlayingCreateDerivedIdentifier
+ _MRNowPlayingGetArtworkSize
+ ___52-[MRProximityProvider _migrateForDevice:completion:]_block_invoke_2
+ ___65-[MRAVVolumeClientEndpoint _initWithSliderType:uniqueIdentifier:]_block_invoke
+ ___65-[MRAVVolumeClientEndpoint _initWithSliderType:uniqueIdentifier:]_block_invoke_2
+ ___79-[MRMediaRemoteService triggerClusterErrorDialogForRouteUID:status:completion:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48s56bs_e35_v16?0"MRMigrationBehaviorResult"8ls32l8s40l8s48l8s56l8
+ _currentDeviceRoutingSymbolName.lock
+ _kMRNowPlayingRootNamespace
- -[MRAVLocalControlCenterEndpoint .cxx_destruct]
- -[MRAVLocalControlCenterEndpoint controlCenterVolumeController]
- -[MRAVLocalControlCenterEndpoint setControlCenterVolumeController:]
- -[MRAVVolumeClientEndpoint _initWithAVVolumeClient:sliderType:uniqueIdentifier:]
- GCC_except_table119
- GCC_except_table122
- GCC_except_table125
- GCC_except_table143
- GCC_except_table350
- _OBJC_IVAR_$_MRAVLocalControlCenterEndpoint._controlCenterVolumeController
- __OBJC_$_INSTANCE_VARIABLES_MRAVLocalControlCenterEndpoint
- __OBJC_$_PROP_LIST_MRAVLocalControlCenterEndpoint
- ___66+[MRDeviceIdentifierSymbolProvider currentDeviceRoutingSymbolName]_block_invoke
- ___80-[MRAVVolumeClientEndpoint _initWithAVVolumeClient:sliderType:uniqueIdentifier:]_block_invoke
- ___80-[MRAVVolumeClientEndpoint _initWithAVVolumeClient:sliderType:uniqueIdentifier:]_block_invoke_2
- ___80-[MRAVVolumeClientEndpoint _initWithAVVolumeClient:sliderType:uniqueIdentifier:]_block_invoke_3
- ___block_descriptor_56_e8_32s40s48bs_e35_v16?0"MRMigrationBehaviorResult"8ls32l8s40l8s48l8
- _currentDeviceRoutingSymbolName.onceToken
CStrings:
+ "-[MRAVVolumeClientEndpoint _newVolumeController]"
+ "Infra6GSteerNoCandidate"
+ "MRXPC_ROUTE_STATUS_KEY"
+ "UnsupportedProtocolRequiredRevertToLocal"
+ "[MRAVVolumeClientEndpoint] Creating %{public}@"
+ "[MRAVVolumeClientEndpoint] Initializing volumeController.."
+ "[MRAVVolumeClientEndpoint] VolumeController unavailable; will retry on next activation"
+ "clearClusterConnectionThrottleOnNetworkChange"
+ "migrateForDevice"
- "[MRAVVolumeClientEndpoint] Creating %{public}@ with volumeController: %{public}@"
```
