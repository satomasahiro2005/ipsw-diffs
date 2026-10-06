## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3154a0` | `0x315894` | **`+0x3f4`** |
| `__TEXT.__gcc_except_tab` | `0x6380` | `0x6724` | **`+0x3a4`** |
| `__DATA_CONST.__const` | `0xb8c8` | `0xba40` | **`+0x178`** |
| `__AUTH_CONST.__cfstring` | `0x24540` | `0x24660` | **`+0x120`** |
| `__TEXT.__cstring` | `0x2daf8` | `0x2dc15` | **`+0x11d`** |
| `__TEXT.__oslogstring` | `0xe467` | `0xe4ad` | **`+0x46`** |
| `__AUTH_CONST.__objc_const` | `0x47c60` | `0x47ca0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x2c660` | `0x2c6a0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xbdc8` | `0xbe08` | **`+0x40`** |
| `__DATA.__bss` | `0x9d0` | `0xa00` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xf880` | `0xf8b0` | **`+0x30`** |
| `__DATA_DIRTY.__bss` | `0x530` | `0x520` | **`-0x10`** |

### Other Changes

```diff

-4026.100.60.1.0
+4026.100.68.0.0

-  Functions: 20995
-  Symbols:   30197
-  CStrings:  6713
+  Functions: 21005
+  Symbols:   30218
+  CStrings:  6723
Symbols:
+ +[MRAVLocalEndpoint sharedSystemScreenLocalEndpoint]
+ -[MRNowPlayingOriginClientManager _resolveActiveSystemEndpointWithType:requestName:requestType:requestID:timeout:failOnTimeout:queue:completion:]
+ -[MRNowPlayingOriginClientManager resolveActiveSystemEndpointWithType:timeout:failOnTimeout:queue:completion:]
+ -[MRUserSettings ignoreUGLSender]
+ -[MRUserSettings simulatedLaunchApplicationError]
+ -[NSArray(MRAVAdditions) mr_outputDevicesIncludingClusterMembers]
+ _MRAVEndpointResolveActiveSystemEndpointWithTypeReturningError
+ _MRNowPlayingInfoDurationStringLocalizationKeyContinuous
+ _MRNowPlayingInfoDurationStringLocalizationKeyLive
+ ___110-[MRNowPlayingOriginClientManager resolveActiveSystemEndpointWithType:timeout:failOnTimeout:queue:completion:]_block_invoke
+ ___110-[MRNowPlayingOriginClientManager resolveActiveSystemEndpointWithType:timeout:failOnTimeout:queue:completion:]_block_invoke_2
+ ___110-[MRNowPlayingOriginClientManager resolveActiveSystemEndpointWithType:timeout:failOnTimeout:queue:completion:]_block_invoke_3
+ ___145-[MRNowPlayingOriginClientManager _resolveActiveSystemEndpointWithType:requestName:requestType:requestID:timeout:failOnTimeout:queue:completion:]_block_invoke
+ ___33-[MRUserSettings ignoreUGLSender]_block_invoke
+ ___49-[MRUserSettings simulatedLaunchApplicationError]_block_invoke
+ ___50-[MRContentItem setNowPlayingInfo:policy:request:]_block_invoke_18
+ ___50-[MRContentItem setNowPlayingInfo:policy:request:]_block_invoke_19
+ ___65-[NSArray(MRAVAdditions) mr_outputDevicesIncludingClusterMembers]_block_invoke
+ ___MRAVEndpointResolveActiveSystemEndpointWithTypeReturningError_block_invoke
+ ___block_descriptor_113_e8_32s40s48s56s64s72s80bs_e30_v24?0"NSString"8"NSError"16ls32l8s40l8s48l8s56l8s64l8s72l8s80l8
+ ___block_descriptor_129_e8_32s40s48s56s64s72s80s88s96bs_e34_v24?0"MRAVEndpoint"8"NSError"16ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8
+ ___block_descriptor_40_e8_32s_e37_16?0"MRAVOutputDeviceDescription"8ls32l8
+ ___block_descriptor_48_e8_32s40r_e18_v16?0"NSString"8ls32l8r40l8
+ ___block_descriptor_89_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ _ignoreUGLSender.__value
+ _ignoreUGLSender.onceToken
+ _kMRMediaRemoteNowPlayingInfoDurationStringLocalizationKey
+ _kMRMediaRemoteNowPlayingInfoLocalizedDurationString
+ _resolveActiveSystemEndpointWithType:timeout:failOnTimeout:queue:completion:.onceToken
+ _resolveActiveSystemEndpointWithType:timeout:failOnTimeout:queue:completion:.workerQueue
+ _simulatedLaunchApplicationError.__error
+ _simulatedLaunchApplicationError.__once
- -[MRNowPlayingOriginClientManager _resolveActiveSystemEndpointWithType:requestName:requestType:requestID:timeout:queue:completion:]
- _OUTLINED_FUNCTION_52
- _OUTLINED_FUNCTION_53
- ___131-[MRNowPlayingOriginClientManager _resolveActiveSystemEndpointWithType:requestName:requestType:requestID:timeout:queue:completion:]_block_invoke
- ___96-[MRNowPlayingOriginClientManager resolveActiveSystemEndpointWithType:timeout:queue:completion:]_block_invoke_2
- ___96-[MRNowPlayingOriginClientManager resolveActiveSystemEndpointWithType:timeout:queue:completion:]_block_invoke_3
- ___block_descriptor_112_e8_32s40s48s56s64s72s80bs_e30_v24?0"NSString"8"NSError"16ls32l8s40l8s48l8s56l8s64l8s72l8s80l8
- ___block_descriptor_128_e8_32s40s48s56s64s72s80s88s96bs_e34_v24?0"MRAVEndpoint"8"NSError"16ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8
- ___block_descriptor_88_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- _resolveActiveSystemEndpointWithType:timeout:queue:completion:.onceToken
- _resolveActiveSystemEndpointWithType:timeout:queue:completion:.workerQueue
CStrings:
+ "CONTINUOUS_PLAYBACK_DURATION"
+ "LIVE_PLAYBACK_DURATION"
+ "MRDSimulatedLaunchApplicationErrorCode"
+ "MRDSimulatedLaunchApplicationErrorDomain"
+ "[MRAVConcreteOutputDevice] GroupID mismatch on <%@:%@> : <%@> -> <%@>"
+ "ignoreUGLSender"
+ "kMRMediaRemoteNowPlayingInfoDurationStringLocalizationKey"
+ "kMRMediaRemoteNowPlayingInfoLocalizedDurationString"
+ "mr_routeClusterType"
+ "mr_routeSubtype"
+ "mr_routeType"
- "supportsVolumeControl"
```
