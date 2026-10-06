## MediaControls

> `/System/Library/PrivateFrameworks/MediaControls.framework/MediaControls`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21fbec` | `0x222bdc` | **`+0x2ff0`** |
| `__TEXT.__const` | `0xb844` | `0xba64` | **`+0x220`** |
| `__AUTH_CONST.__const` | `0xa7f0` | `0xaa08` | **`+0x218`** |
| `__DATA.__common` | `0x720` | `0x8b0` | **`+0x190`** |
| `__TEXT.__swift5_reflstr` | `0x4a03` | `0x4b33` | **`+0x130`** |
| `__TEXT.__oslogstring` | `0x8799` | `0x86d9` | **`-0xc0`** |
| `__DATA.__bss` | `0x8898` | `0x8928` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x4b08` | `0x4b8c` | **`+0x84`** |
| `__AUTH.__objc_data` | `0x3828` | `0x3880` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0x1900` | `0x18a8` | **`-0x58`** |
| `__TEXT.__gcc_except_tab` | `0x1598` | `0x1548` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0x51a0` | `0x51e0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x15b94` | `0x15bd4` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x439e0` | `0x43a18` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x7740` | `0x7778` | **`+0x38`** |
| `__TEXT.__cstring` | `0x6f44` | `0x6f74` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x3398` | `0x3368` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x30a8` | `0x3080` | **`-0x28`** |
| `__TEXT.__swift5_capture` | `0x13d8` | `0x13f8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x88c8` | `0x88e8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xa6d8` | `0xa6f0` | **`+0x18`** |
| `__DATA.__data` | `0x4128` | `0x4138` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x50` | `0x5c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2010` | `0x2008` | **`-0x8`** |
| `__TEXT.__ustring` | `0x22` | `0x28` | **`+0x6`** |
| `__DATA.__objc_ivar` | `0x18d0` | `0x18cc` | **`-0x4`** |
| `__TEXT.__swift5_proto` | `0x5e8` | `0x5ec` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x604` | `0x608` | **`+0x4`** |

### Other Changes

```diff

-4026.100.79.0.0
+4026.110.83.1.0

+  - /System/Library/Frameworks/CoreText.framework/CoreText

+  - /System/Library/PrivateFrameworks/ProductKit.framework/ProductKit

-  Functions: 14347
-  Symbols:   13835
-  CStrings:  1625
+  Functions: 14388
+  Symbols:   13848
+  CStrings:  1624
Symbols:
+ -[MRUMarqueeLabel updateDimmed]
+ -[MRUMarqueeLabel updateMarquee]
+ -[MRUNowPlayingTimeControlsView sliderTouchChanged:]
+ -[MRURouteRecommendationPlatterViewController updateArtwork:]
+ -[MRURouteRecommendationPlatterViewController updateEndpointRoute:]
+ -[MRURouteRecommendationPlatterViewController updateNowPlayingInfo:]
+ -[MRURouteRecommendationPlatterViewController updateShowTVRemote:]
+ -[MRUVolumeViewController audioModuleController:listeningModeController:didChangePrimaryListeningModeConfigs:listeningMode:autoANCCapability:autoANCStrength:]
+ -[NSString(MRUTextSize) mru_containsExcessiveHeightCharacters]
+ GCC_except_table28
+ _CTFontCopySystemUIFontExcessiveLineHeightCharacterSet
+ _CTFontGetLanguageAwareOutsets
+ _MSVGetDeviceProductType
+ __OBJC_$_PROP_LIST_NSString_$_MRUTextSize
+ ___62-[NSString(MRUTextSize) mru_containsExcessiveHeightCharacters]_block_invoke
+ ___64-[MRUVolumeViewController updateEnvironmentSliderValueAnimated:]_block_invoke
+ ___64-[MRUVolumeViewController updateEnvironmentSliderValueAnimated:]_block_invoke_2
+ ___66-[MRUVolumeViewController updatePrimarySliderVolumeValueAnimated:]_block_invoke
+ ___66-[MRUVolumeViewController updatePrimarySliderVolumeValueAnimated:]_block_invoke_2
+ ___67-[MRURouteRecommendationPlatterViewController updateEndpointRoute:]_block_invoke
+ ___68-[MRUVolumeViewController updateSecondarySliderVolumeValueAnimated:]_block_invoke
+ ___68-[MRUVolumeViewController updateSecondarySliderVolumeValueAnimated:]_block_invoke_2
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
+ ___swift_memcpy177_8
+ _get_enum_tag_for_layout_string 13MediaControls17MultiOptionButtonC0D0V5AssetO
+ _mru_containsExcessiveHeightCharacters.onceToken
+ _mru_containsExcessiveHeightCharacters.sExcessiveHeightCharacters
+ _symbolic _____ 13MediaControls17MultiOptionButtonC0D0V5AssetO
+ _symbolic _____Sg 10ProductKit14iosmacHardwareV5ModelO
+ _symbolic _____Sg 13MediaControls17MultiOptionButtonC0D0V5AssetO
+ _symbolic _____Sg_ABt 13MediaControls17MultiOptionButtonC0D0V5AssetO
+ _type_layout_string 13MediaControls17MultiOptionButtonC0D0V5AssetO
- -[MRUAssetManager productKitImageForModelIdentifier:color:allowFallback:timeout:completion:]
- -[MRUAssetManager shouldUseProductKitFor:]
- -[MRURouteRecommendationPlatterViewController updateActionType]
- -[MRUVolumeViewController audioModuleController:listeningModeController:didChangePrimaryListeningMode:]
- GCC_except_table29
- _OBJC_IVAR_$_MRUMetadataController._dataSourceLock
- ___102-[MRURouteRecommendationPlatterViewController nowPlayingController:endpointController:didChangeRoute:]_block_invoke
- ___52-[MRUNowPlayingController imageForRoute:completion:]_block_invoke_4
- ___92-[MRUAssetManager productKitImageForModelIdentifier:color:allowFallback:timeout:completion:]_block_invoke
- ___block_descriptor_48_e8_32s40bs_e29_v24?0"UIImage"8"NSError"16ls32l8s40l8
- ___block_descriptor_48_e8_32s40r_e8_v12?0B8lr40l8s32l8
- _dispatch_semaphore_create
- _dispatch_semaphore_signal
- _dispatch_semaphore_wait
- _symbolic SS8fileName_So8NSBundleC6bundlet
- _symbolic Si4code_t
- _symbolic _____ 13MediaControls17ProductKitWrapperC5asset3for5color13allowFallback7timeout10completionySS_SSSbSdySo7UIImageCSg_s5Error_pSgtctFZ15CompletionValueL_O
- _symbolic ______p5error_t s5ErrorP
- _symbolic _____y_____G s11_SetStorageC 13MediaControls17MultiOptionButtonC0F4ViewC
CStrings:
+ "AudioAccessory"
+ "SpatialMultichannelHeadTracked"
+ "SpatialMultichannelOff"
+ "SpatialMultichannelOn"
+ "SpatialStereoHeadTracked"
+ "SpatialStereoOff"
+ "SpatialStereoOn"
+ "[MRPKW] No ProductKit image for %@"
+ "çÇ"
- "[AssetManager] PK request<%@> for model: %@, color: %@, allow fallback? %{BOOL}u, timeout: %f"
- "[AssetManager] PK response<%@> Asset found: %@"
- "[AssetManager] PK response<%@> Failed to obtain asset: %@"
- "[MRPKW] failed to get image; fileName: %@, bundle: %@"
- "[MRPKW] got image: %@"
- "person.and.sparkles.fill"
- "person.closed.fill"
- "person.open.fill"
- "person.spatialaudio.fill"
- "person.spatialaudio.stereo.fill"
```
