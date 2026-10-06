## MediaControls

> `/System/Library/PrivateFrameworks/MediaControls.framework/MediaControls`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x208f14` | `0x20a0d4` | **`+0x11c0`** |
| `__DATA_DIRTY.__bss` | `0x25b0` | `0x28a0` | **`+0x2f0`** |
| `__DATA.__bss` | `0x8608` | `0x8348` | **`-0x2c0`** |
| `__DATA_DIRTY.__objc_data` | `0x70e8` | `0x7250` | **`+0x168`** |
| `__AUTH.__objc_data` | `0x3218` | `0x30c0` | **`-0x158`** |
| `__AUTH_CONST.__objc_const` | `0x42c90` | `0x42de0` | **`+0x150`** |
| `__TEXT.__objc_methlist` | `0x156b4` | `0x15784` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x6b34` | `0x6be4` | **`+0xb0`** |
| `__DATA_CONST.__got` | `0x17c0` | `0x1860` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x5120` | `0x51a0` | **`+0x80`** |
| `__DATA_DIRTY.__data` | `0x3308` | `0x3378` | **`+0x70`** |
| `__TEXT.__const` | `0xb464` | `0xb414` | **`-0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xa4d8` | `0xa518` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x83c8` | `0x8408` | **`+0x40`** |
| `__AUTH.__data` | `0x1188` | `0x1158` | **`-0x30`** |
| `__DATA.__data` | `0x3f60` | `0x3f88` | **`+0x28`** |
| `__DATA.__common` | `0x4f8` | `0x4d8` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `0x9c0` | `0x9e0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x4763` | `0x4783` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x47c4` | `0x47dc` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x3010` | `0x3000` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x18a4` | `0x18b0` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1f90` | `0x1f88` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x468` | `0x470` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x5c4` | `0x5c8` | **`+0x4`** |

### Other Changes

```diff

-4026.100.68.0.0
+4026.110.75.1.0

-  Functions: 13856
-  Symbols:   13703
-  CStrings:  1585
+  Functions: 13879
+  Symbols:   13725
+  CStrings:  1590
Symbols:
+ +[MRUStringsProvider routeRecommendationCastConnected]
+ +[MRUStringsProvider routeRecommendationConnectedToProtocolName:protocolUID:]
+ +[MRUStringsProvider routeRecommendationTapToCast]
+ +[MRUStringsProvider routeRecommendationTapToProtocolName:protocolUID:]
+ -[MRUAmbientCompactNowPlayingView _viewForMode:]
+ -[MRUAmbientCompactNowPlayingView artworkView]
+ -[MRUAmbientCompactNowPlayingView mode]
+ -[MRUAmbientCompactNowPlayingView setMode:]
+ -[MRUAmbientCompactNowPlayingViewController artworkView:didChangeArtworkImage:]
+ -[MRUAmbientCompactNowPlayingViewController updateMode]
+ -[MRUAmbientCompactNowPlayingViewController updateWaveformVisibility]
+ -[MRUAmbientCompactNowPlayingViewController waveformController:routeSupportsWaveformDidChange:]
+ -[MRUWaveformController addObserver:]
+ -[MRUWaveformController observers]
+ -[MRUWaveformController removeObserver:]
+ -[MRUWaveformController setObservers:]
+ _OBJC_IVAR_$_MRUAmbientCompactNowPlayingView._artworkView
+ _OBJC_IVAR_$_MRUAmbientCompactNowPlayingView._mode
+ _OBJC_IVAR_$_MRUMetadataController._dataSourceLock
+ _OBJC_IVAR_$_MRUWaveformController._observers
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MRUWaveformControllerObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MRUWaveformControllerObserver
+ __OBJC_$_PROTOCOL_REFS_MRUWaveformControllerObserver
+ __OBJC_LABEL_PROTOCOL_$_MRUWaveformControllerObserver
+ __OBJC_PROTOCOL_$_MRUWaveformControllerObserver
+ ___43-[MRUAmbientCompactNowPlayingView setMode:]_block_invoke
+ ___43-[MRUAmbientCompactNowPlayingView setMode:]_block_invoke_2
+ ___43-[MRUAmbientCompactNowPlayingView setMode:]_block_invoke_3
- -[MRUAmbientCompactNowPlayingView setShowWaveform:]
- -[MRUAmbientCompactNowPlayingView showWaveform]
- _OBJC_IVAR_$_MRUAmbientCompactNowPlayingView._showWaveform
- ___51-[MRUAmbientCompactNowPlayingView setShowWaveform:]_block_invoke
- ___58-[MRUAmbientCompactNowPlayingViewController updateArtwork]_block_invoke
- ___block_descriptor_40_e8_32s_e29_v24?0"UIImage"8"NSError"16ls32l8
CStrings:
+ "ROUTE_RECOMMENDATION_CAST_CONNECTED"
+ "ROUTE_RECOMMENDATION_PROTOCOL_CONNECTED_%@"
+ "ROUTE_RECOMMENDATION_TAP_TO_CAST"
+ "ROUTE_RECOMMENDATION_TAP_TO_PROTOCOL_%@"
+ "protocol_name_in_recommendations"
```
