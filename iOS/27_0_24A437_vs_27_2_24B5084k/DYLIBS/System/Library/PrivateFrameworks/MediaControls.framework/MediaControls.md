## MediaControls

> `/System/Library/PrivateFrameworks/MediaControls.framework/MediaControls`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2257d4` | `0x2264e8` | **`+0xd14`** |
| `__AUTH_CONST.__const` | `0xaa80` | `0xab98` | **`+0x118`** |
| `__TEXT.__objc_methlist` | `0x15d1c` | `0x15d94` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0x141c` | `0x148c` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x44730` | `0x44780` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x1548` | `0x1598` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xa788` | `0xa7c8` | **`+0x40`** |
| `__TEXT.__const` | `0xbd04` | `0xbcd4` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x8960` | `0x8990` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1898` | `0x18a8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x18cc` | `0x18d4` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-4026.110.4.0.0
+4026.200.11.0.0

-  Functions: 14440
-  Symbols:   13857
+  Functions: 14458
+  Symbols:   13872
Symbols:
+ +[UIFont(MRUDefaults) mru_ambientRouteFont]
+ -[MRUAmbientNowPlayingView layoutAxis]
+ -[MRUAmbientNowPlayingView routingButtonSymbolConfigurationForLayoutAxis:wideGlyph:]
+ -[MRUAmbientNowPlayingView setRoute:]
+ -[MRUAmbientNowPlayingView updateAxisDependentConfiguration]
+ -[MRUAmbientNowPlayingView updateRouteLabelFont]
+ -[MRUAmbientNowPlayingView updateRouteLabelVisibilityForSliderExpanded:]
+ -[MRUAmbientNowPlayingView updateRoutingButtonAsset]
+ -[MRUAmbientNowPlayingVolumeControlsView setVisibilityDidUpdateHandler:]
+ -[MRUAmbientNowPlayingVolumeControlsView visibilityDidUpdateHandler]
+ -[MRUSystemOutputDeviceRouteControllerControlCenterEndpointDataSource _updateIsPhoneCallActive]
+ -[MRUSystemOutputDeviceRouteControllerControlCenterEndpointDataSource volumeCategoryDidChangeNotification:]
+ _MRAVVolumeClientEndpointVolumeCategoryDidChangeNotification
+ _MRUAmbientNowPlayingVerticalLayoutArtworkGutter
+ _MRUAmbientNowPlayingVerticalLayoutAuxiliaryRowHeight
+ _MRUAmbientNowPlayingVerticalLayoutRouteLabelSpacing
+ _OBJC_IVAR_$_MRUAmbientNowPlayingView._appliedConfigurationAxis
+ _OBJC_IVAR_$_MRUAmbientNowPlayingView._routeLabel
+ _OBJC_IVAR_$_MRUAmbientNowPlayingView._routingButtonGlyphSize
+ _OBJC_IVAR_$_MRUAmbientNowPlayingView._routingButtonImage
+ _OBJC_IVAR_$_MRUAmbientNowPlayingVolumeControlsView._visibilityDidUpdateHandler
+ _UIFontTextStyleTitle3
+ ___42-[MRUAmbientNowPlayingView initWithFrame:]_block_invoke
+ ___swift_closure_destructor.37Tm
- -[MRUAmbientNowPlayingView setShadowView:]
- -[MRUAmbientNowPlayingView shadowView]
- -[MRUSystemOutputDeviceRouteControllerControlCenterEndpointDataSource routeDidChangeNotification:]
- _MRUAmbientNowPlayingVerticalLayoutHorizontalCompactMargin
- _MRUAmbientNowPlayingVerticalLayoutVerticalCompactMargin
- _MRUAmbientNowPlayingVolumeControlsPackageInsets
- _OBJC_IVAR_$_MRUAmbientNowPlayingView._routingButtonSymbolConfiguration
- _OBJC_IVAR_$_MRUAmbientNowPlayingView._routingButtonSymbolConfigurationSmall
- _OBJC_IVAR_$_MRUAmbientNowPlayingView._shadowView
```
