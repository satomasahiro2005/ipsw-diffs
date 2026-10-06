## HeadphoneSettingsUI

> `/System/Library/PrivateFrameworks/HeadphoneSettingsUI.framework/HeadphoneSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20de9c` | `0x21bd58` | **`+0xdebc`** |
| `__AUTH_CONST.__const` | `0x10bf8` | `0x11a30` | **`+0xe38`** |
| `__TEXT.__swift5_capture` | `0x4ff0` | `0x5550` | **`+0x560`** |
| `__DATA.__bss` | `0xfc78` | `0xffa8` | **`+0x330`** |
| `__TEXT.__const` | `0xd6d4` | `0xd984` | **`+0x2b0`** |
| `__TEXT.__oslogstring` | `0x69ff` | `0x6bef` | **`+0x1f0`** |
| `__TEXT.__swift5_typeref` | `0xc64e` | `0xc812` | **`+0x1c4`** |
| `__TEXT.__constg_swiftt` | `0x49b4` | `0x4ad8` | **`+0x124`** |
| `__TEXT.__swift5_reflstr` | `0x202b` | `0x214b` | **`+0x120`** |
| `__DATA_DIRTY.__objc_data` | `0x558` | `0x668` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x3f48` | `0x4040` | **`+0xf8`** |
| `__DATA.__data` | `0x3b00` | `0x3bf0` | **`+0xf0`** |
| `__TEXT.__cstring` | `0xa69e` | `0xa78e` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0xa770` | `0xa850` | **`+0xe0`** |
| `__TEXT.__swift5_fieldmd` | `0x2260` | `0x22ec` | **`+0x8c`** |
| `__DATA_CONST.__objc_selrefs` | `0x2860` | `0x28d8` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x2348` | `0x23a0` | **`+0x58`** |
| `__TEXT.__swift5_assocty` | `0xd78` | `0xda8` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x17c0` | `0x17e8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x36cc` | `0x36ec` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0xb04` | `0xb24` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1060` | `0x1078` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x384` | `0x398` | **`+0x14`** |
| `__AUTH.__data` | `0x2b58` | `0x2b68` | **`+0x10`** |
| `__DATA.__common` | `0x598` | `0x5a8` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x520` | `0x528` | **`+0x8`** |

### Other Changes

```diff

-40.33.1.0.0
+40.36.1.0.0

-  Functions: 9356
-  Symbols:   4110
-  CStrings:  1710
+  Functions: 9581
+  Symbols:   4131
+  CStrings:  1728
Symbols:
+ _NSFontAttributeName
+ _OBJC_CLASS_$_UIImpactFeedbackGenerator
+ _UIFontTextStyleLargeTitle
+ _associated conformance So21NSAttributedStringKeyaSHSCSQ
+ _associated conformance So21NSAttributedStringKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So21NSAttributedStringKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _symbolic SS4text______8maxWidtht 12CoreGraphics7CGFloatV
+ _symbolic SaySS4text______8maxWidthtG 12CoreGraphics7CGFloatV
+ _symbolic SaySo18NSLayoutConstraintCG
+ _symbolic SaySo6UIViewC9container_So7UILabelC5labeltG
+ _symbolic So13MRContentItemC
+ _symbolic So18NSLayoutConstraintCSg
+ _symbolic So21MRContentItemMetadataCSg
+ _symbolic So25UIImpactFeedbackGeneratorCSg
+ _symbolic So6UIViewC9container_So7UILabelC5labelt
+ _symbolic _____ 19HeadphoneSettingsUI28DebugFitFeatureGroupProviderV
+ _symbolic _____ So21NSAttributedStringKeya
+ _symbolic _____7leading_AA8trailingt 12CoreGraphics7CGFloatV
+ _symbolic ______ypt So21NSAttributedStringKeya
+ _symbolic _____ySaySo6UIViewC9container_So7UILabelC5labeltGG s18EnumeratedSequenceV
+ _symbolic _____ySaySo6UIViewC9container_So7UILabelC5labeltG_G s18EnumeratedSequenceV8IteratorV
+ _type_layout_string 19HeadphoneSettingsUI28DebugFitFeatureGroupProviderV
+ _type_layout_string So21NSAttributedStringKeya
- _OBJC_CLASS_$_UIFontDescriptor
- _UIFontTextStyleBody
CStrings:
+ "EQ_LABEL_"
+ "FitTestFeature hasContent: %{bool}d supported: %{bool}d forceShow: %{bool}d"
+ "ForceShowFitTest"
+ "HIGHHIGH!"
+ "Internal: ear tip fit test."
+ "LOWLOWLOW"
+ "Live Translation: Support: contentReady: %{bool}d, capability: %{bool}d, featureEnabled: %{bool}d aiAvailable: %{bool}d"
+ "LiveTranslationPlaceCardFeature: supported optIn:%{bool}d engaged:%{bool}d  dismissed:%{bool}d optedOut:%{bool}d capable:%{bool}d aiAvailable: %{bool}d"
+ "MIDMIDMID"
+ "Test Ear Tip Fit"
+ "[AudioPlayerVM] Artwork loaded for %ld items, item: %s"
+ "[AudioPlayerVM] contentItemsDidUpdate for %ld item: %s"
+ "[AudioPlayerVM] contentItemsDidUpdate: no content items or playbackQueue %s %s"
+ "[AudioPlayerVM] playbackQueueDidChange - no now playing item in new queue"
+ "[AudioPlayerVM] playbackQueueDidChange - now playing id: %s, metadata: %s"
+ "[NowPlayingViewModel] metadata dump: title=%s subtitle=%s subtitleShort=%s albumArtist=%s trackArtist=%s album=%s"
+ "_FONT_"
+ "airpods"
+ "debugEQLabels"
+ "deviceIdentifier"
+ "forceEQLongLabels"
+ "nil"
- "FitTestFeature hasContent: %{bool}d supported: %{bool}d"
- "Live Translation: Support: contentReady: %{bool}d, capability: %{bool}d, featureEnabled: %{bool}d"
- "LiveTranslationPlaceCardFeature: supported  optIn:%{bool}d  engaged:%{bool}d  dismissed:%{bool}d optedOut:%{bool}d capable:%{bool}d"
- "[AudioPlayerVM] Artwork loaded for %ld items"
```
