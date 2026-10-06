## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x317068` | `0x317a24` | **`+0x9bc`** |
| `__AUTH_CONST.__objc_const` | `0x47e80` | `0x47f48` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0xea48` | `0xeaed` | **`+0xa5`** |
| `__TEXT.__objc_methlist` | `0x2c788` | `0x2c818` | **`+0x90`** |
| `__TEXT.__cstring` | `0x2de92` | `0x2df00` | **`+0x6e`** |
| `__AUTH_CONST.__cfstring` | `0x24a20` | `0x24a80` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xbb08` | `0xbb58` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xf930` | `0xf978` | **`+0x48`** |
| `__DATA.__bss` | `0x998` | `0x9b8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x33e4` | `0x33ec` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xbe10` | `0xbe18` | **`+0x8`** |

### Other Changes

```diff

-4026.110.83.1.0
+4026.110.4.0.0

-  Functions: 21013
-  Symbols:   30239
-  CStrings:  6771
+  Functions: 21030
+  Symbols:   30262
+  CStrings:  6776
Symbols:
+ -[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:appVended:timeout:details:queue:completion:]
+ -[MRIRRoute appVendedContainerBundleID]
+ -[MRIRRoute appVended]
+ -[MRIRRoute setAppVendedContainerBundleID:]
+ -[MRNowPlayingAudioFormatController ignoreList]
+ -[MRNowPlayingAudioFormatController isBundleIDAllowed:]
+ -[MRNowPlayingAudioFormatController setIgnoreList:]
+ -[MRUserSettings appVendedRouteRecommendationsEnabled]
+ -[MRUserSettings disableRemoteMediaExtensionNetworkPolicies]
+ GCC_except_table73
+ _OBJC_IVAR_$_MRIRRoute._appVendedContainerBundleID
+ _OBJC_IVAR_$_MRNowPlayingAudioFormatController._ignoreList
+ ___115-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:appVended:timeout:details:queue:completion:]_block_invoke
+ ___115-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:appVended:timeout:details:queue:completion:]_block_invoke_2
+ ___115-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:appVended:timeout:details:queue:completion:]_block_invoke_3
+ ___115-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:appVended:timeout:details:queue:completion:]_block_invoke_4
+ ___115-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:appVended:timeout:details:queue:completion:]_block_invoke_5
+ ___51-[MRNowPlayingAudioFormatController setIgnoreList:]_block_invoke
+ ___54-[MRUserSettings appVendedRouteRecommendationsEnabled]_block_invoke
+ ___59-[MRNowPlayingAudioFormatController audioFormatApplication]_block_invoke
+ ___59-[MRNowPlayingAudioFormatController audioFormatContentInfo]_block_invoke
+ ___60-[MRUserSettings disableRemoteMediaExtensionNetworkPolicies]_block_invoke
+ ___block_descriptor_56_e8_32s40s48w_e5_v8?0lw48l8s32l8s40l8
+ ___block_descriptor_72_e8_32s40s48s56bs64bs_e58_v40?0"NSArray"8"NSArray"16"MRAVEndpoint"24"NSError"32ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ _appVendedRouteRecommendationsEnabled.__value
+ _appVendedRouteRecommendationsEnabled.onceToken
+ _disableRemoteMediaExtensionNetworkPolicies.onceToken
+ _disableRemoteMediaExtensionNetworkPolicies.result
- ___105-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:timeout:details:queue:completion:]_block_invoke
- ___105-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:timeout:details:queue:completion:]_block_invoke_2
- ___105-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:timeout:details:queue:completion:]_block_invoke_3
- ___105-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:timeout:details:queue:completion:]_block_invoke_4
- ___105-[MRAVLightweightReconnaissanceSession searchOutputDevices:protocolUID:timeout:details:queue:completion:]_block_invoke_5
- ___block_descriptor_96_e8_32s40s48s56s64s72s80bs_e58_v40?0"NSArray"8"NSArray"16"MRAVEndpoint"24"NSError"32ls32l8s40l8s48l8s80l8s56l8s64l8s72l8
CStrings:
+ "%{public}@ ignoring the following bundle ids: %{public}@"
+ "AppVendedRouteRecommendationsEnabled"
+ "Update: %{public}@<%{public}@> app-vended route: skipping audio discovery, searching RemoteControl directly"
+ "appVendedContainerBundleID"
+ "disableRemoteMediaExtensionNetworkPolicies"
```
