## CarKit

> `/System/Library/PrivateFrameworks/CarKit.framework/CarKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x61d2c` | `0x628a8` | **`+0xb7c`** |
| `__TEXT.__oslogstring` | `0x6ae6` | `0x6c86` | **`+0x1a0`** |
| `__AUTH_CONST.__cfstring` | `0x5c60` | `0x5d80` | **`+0x120`** |
| `__TEXT.__cstring` | `0x5a9d` | `0x5bbd` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0x102b8` | `0x10390` | **`+0xd8`** |
| `__TEXT.__objc_methlist` | `0x6354` | `0x63ec` | **`+0x98`** |
| `__DATA_CONST.__const` | `0x2040` | `0x20a0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x36f0` | `0x3750` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1be0` | `0x1c18` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x9f8` | `0xa1c` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0xac8` | `0xae0` | **`+0x18`** |
| `__AUTH_CONST.__const` | `0x1bb0` | `0x1bc0` | **`+0x10`** |
| `__DATA.__data` | `0x11a0` | `0x1190` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x870` | `0x880` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x72c` | `0x738` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x188` | `0x17e` | **`-0xa`** |

### Other Changes

```diff

-799.3.0.0.0
+807.2.0.0.0

-  Functions: 3044
-  Symbols:   4739
-  CStrings:  1419
+  Functions: 3058
+  Symbols:   4762
+  CStrings:  1436
Symbols:
+ +[CARSession _stringForAppearanceMode:]
+ -[CARScreenInfo descriptionForScreenType]
+ -[CARSession _videoPlaybackAudioOnlyMode]
+ -[CARSession carPlaySnoopCollectionPath]
+ -[CARSession createRemoteControlSession:channelID:withoutReply:sendAsIs:qualityOfService:streamPriority:sendSocketBufferSize:error:]
+ -[CARSession handleDDPChangeWithAppearance:screenID:]
+ -[CARSession lastPlayingVideoAppBundleId]
+ -[CARSession setLastPlayingVideoAppBundleId:]
+ -[CARSessionChannel initWithSession:channelType:channelID:withoutReply:sendAsIs:qualityOfService:streamPriority:sendSocketBufferSize:]
+ -[CARSessionChannel sendSocketBufferSize]
+ GCC_except_table104
+ GCC_except_table118
+ GCC_except_table123
+ GCC_except_table160
+ GCC_except_table184
+ GCC_except_table190
+ GCC_except_table218
+ _CARScreenTypeForDisplayIndex
+ _CARkAPEndpointProperty_SnoopCollectionPath
+ _CRFetchTapToRadarDraftBannerInfo
+ _OBJC_IVAR_$_CARSession._lastPlayingVideoAppBundleId
+ _OBJC_IVAR_$_CARSession._videoPlaybackAvailable
+ _OBJC_IVAR_$_CARSessionChannel._sendSocketBufferSize
+ __OBJC_$_CLASS_METHODS__TtC6CarKit18CRDisplayScaleInfo(CarKit|CarKit1)
+ __OBJC_$_INSTANCE_METHODS__TtC6CarKit18CRDisplayScaleInfo(CarKit|CarKit1)
+ ___132-[CARSession createRemoteControlSession:channelID:withoutReply:sendAsIs:qualityOfService:streamPriority:sendSocketBufferSize:error:]_block_invoke
+ ___53-[CARSession handleDDPChangeWithAppearance:screenID:]_block_invoke
+ ___CRFetchTapToRadarDraftBannerInfo_block_invoke
+ ___CRFetchTapToRadarDraftBannerInfo_block_invoke_2
+ ___CRFetchTapToRadarDraftBannerInfo_block_invoke_3
+ ___block_descriptor_48_e8_32bs40bs_e33_v32?0q8"NSString"16"NSError"24ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s_e5_v8?0ls32l8s40l8
+ _kFigEndpointAirPlayVideoPlaybackAudioOnlyMode_Forced
+ _kFigEndpointRemoteControlSessionCreationOption_SendSocketBufferSize
+ _kVideoPlayback_PlayerEventRef
- -[CARSession createRemoteControlSession:channelID:withoutReply:sendAsIs:qualityOfService:streamPriority:error:]
- -[CARSession handleDDPChangeAppearance:screenID:]
- GCC_except_table102
- GCC_except_table116
- GCC_except_table155
- GCC_except_table179
- GCC_except_table185
- GCC_except_table213
- __OBJC_$_INSTANCE_METHODS__TtC6CarKit18CRDisplayScaleInfo(CarKit)
- ___111-[CARSession createRemoteControlSession:channelID:withoutReply:sendAsIs:qualityOfService:streamPriority:error:]_block_invoke
- ___49-[CARSession handleDDPChangeAppearance:screenID:]_block_invoke
- _symbolic _____ySSG s23_ContiguousArrayStorageC
CStrings:
+ " %@[ui=%@ map=%@]"
+ "%{public}s   %{public}s"
+ "%{public}s %{public}s"
+ "Attempting to start remote control session for channel %{public}@ channelID: %{public}@ withoutReply: %d sendAsIs: %d qualityOfService: %{public}@ streamPriority: %{public}@ sendSocketBufferSize: %{public}@"
+ "BackButton"
+ "DDP appearance: raw=%{public}@ resolved=%{public}@ screenID=%{public}@"
+ "HidVideoButton"
+ "No MFi certificate serial number for the current session"
+ "SnoopCollectionPath"
+ "Video is playing in audio only mode for app %@"
+ "Video playback player event: %@"
+ "VideoPlaybackPlayerEvent_ButtonTapped"
+ "VideoPlayback_PlayerEvent"
+ "[Appearance-Init]"
+ "[Appearance-Init] locationNightMode=%d, nightMode=%d, appearancePreference=%{public}@, resolved:%{public}@"
+ "[Appearance-State]"
+ "[Appearance-Update] Preference %{public}@ -> %{public}@"
+ "[Appearance-Update] Screen %{public}@: appearance %{public}@ -> %{public}@"
+ "[Appearance-Update] Screen %{public}@: mapAppearance %{public}@ -> %{public}@"
+ "[Appearance-Update] nightMode: %d -> %d"
+ "com.apple.WebKit.GPU"
+ "com.apple.mobilesafari"
+ "dark(1)"
+ "endpoint is MFi Mutual Authenticated"
+ "endpoint is MFi SAP authenticated"
+ "endpoint is NOT authenticated"
+ "endpoint is not authenticayed because it is missing serial data."
+ "light(0)"
+ "v32@?0q8@\"NSString\"16@\"NSError\"24"
- "Attempting to start remote control session for channel %{public}@"
- "DDP appearance: mode=%{public}@ screenID=%{public}@"
- "Forced"
- "Initial CARAppearanceState state: %{public}s"
- "Initial state: locationNightMode=%d, nightMode=%d, appearancePreference=%{public}@"
- "New state: %{public}s"
- "Preference %{public}@ -> %{public}@"
- "Screen %{public}@: appearance %{public}@ -> %{public}@"
- "Screen %{public}@: mapAppearance %{public}@ -> %{public}@"
- "endpoint is authenticated"
- "nightMode: %d -> %d"
- "withDDPAppearanceMode: undefined mode for screenID=%{public}s, keeping screen in AirPlay"
```
