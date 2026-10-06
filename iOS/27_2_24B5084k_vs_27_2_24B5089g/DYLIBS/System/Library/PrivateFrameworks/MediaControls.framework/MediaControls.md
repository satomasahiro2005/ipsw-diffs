## MediaControls

> `/System/Library/PrivateFrameworks/MediaControls.framework/MediaControls`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3880` | `0x82a8` | **`+0x4a28`** |
| `__DATA_DIRTY.__objc_data` | `0x72c8` | `0x28a0` | **`-0x4a28`** |
| `__DATA_DIRTY.__data` | `0x33b8` | `0x5b8` | **`-0x2e00`** |
| `__DATA.__bss` | `0x8b28` | `0xafe8` | **`+0x24c0`** |
| `__DATA_DIRTY.__bss` | `0x28a0` | `0x3f0` | **`-0x24b0`** |
| `__AUTH.__data` | `0x1238` | `0x34d8` | **`+0x22a0`** |
| `__DATA.__data` | `0x4218` | `0x4d68` | **`+0xb50`** |
| `__DATA.__common` | `0x8b0` | `0x1250` | **`+0x9a0`** |
| `__DATA_DIRTY.__common` | `0xa00` | `0x60` | **`-0x9a0`** |
| `__TEXT.__text` | `0x2264e8` | `0x2268f8` | **`+0x410`** |
| `__AUTH_CONST.__objc_const` | `0x44780` | `0x44848` | **`+0xc8`** |
| `__TEXT.__objc_methlist` | `0x15d94` | `0x15de4` | **`+0x50`** |
| `__TEXT.__const` | `0xbcd4` | `0xbd04` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x51e0` | `0x5200` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xa7c8` | `0xa7e8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x3080` | `0x3090` | **`+0x10`** |
| `__TEXT.__cstring` | `0x6f64` | `0x6f74` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2028` | `0x2030` | **`+0x8`** |

### Other Changes

```diff

-4026.200.11.0.0
+4026.200.15.0.0

-  Functions: 14458
-  Symbols:   13872
-  CStrings:  1623
+  Functions: 14463
+  Symbols:   13884
+  CStrings:  1624
Symbols:
+ +[UIFont(MRUDefaults) mru_ambientSubtitleFontForAxis:]
+ +[UIFont(MRUDefaults) mru_ambientTimeFontForAxis:]
+ +[UIFont(MRUDefaults) mru_ambientTitleFontForAxis:]
+ -[MRUAmbientNowPlayingView prefersAltLayout]
+ -[MRUAmbientNowPlayingVolumeControlsView maximumValueViewStyleForSlider:]
+ -[MRUCAPackageView(MRUVisualStylingProviderAdditions) mru_applyBlendColor:alpha:]
+ -[MRUVisualStylingProvider applyBlendStyle:toView:traitCollection:]
+ -[UIView(MRUVisualStylingProviderAdditions) mru_applyBlendColor:alpha:]
+ _CGColorGetAlpha
+ _MRUAmbientNowPlayingSliderStretchLimit
+ _MRUAmbientNowPlayingTimeControlsBottomInsetForLayoutAxis
+ _MRUAmbientNowPlayingVerticalLayoutSliderToTimeLabelSpacing
+ _MRUAmbientNowPlayingVerticalLayoutTimeControlsBottomInset
+ _MRUAmbientNowPlayingVerticalLayoutTransportControlsButtonSize
+ _MRUAmbientNowPlayingVerticalLayoutTransportControlsCenterOffset
+ _MRUAmbientNowPlayingVerticalLayoutTransportControlsPackageScale
- +[UIFont(MRUDefaults) mru_ambientSubtitleFont]
- +[UIFont(MRUDefaults) mru_ambientTimeFont]
- +[UIFont(MRUDefaults) mru_ambientTitleFont]
- -[MRUNowPlayingTimeControlsView timeLabelsAlpha]
CStrings:
+ "AmbientVertical"
```
