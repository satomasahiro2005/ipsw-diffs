## MediaDevice

> `/System/Library/Frameworks/MediaDevice.framework/MediaDevice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e824` | `0x314d4` | **`+0x2cb0`** |
| `__DATA.__bss` | `0xc90` | `0xf90` | **`+0x300`** |
| `__TEXT.__const` | `0xea8` | `0x1098` | **`+0x1f0`** |
| `__TEXT.__eh_frame` | `0xe60` | `0xf80` | **`+0x120`** |
| `__AUTH_CONST.__const` | `0x13a0` | `0x14b8` | **`+0x118`** |
| `__AUTH_CONST.__cfstring` | `0x3a0` | `0x480` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0xadc` | `0xbbc` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0xeeb` | `0xf7b` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x7b0` | `0x840` | **`+0x90`** |
| `__TEXT.__cstring` | `0xcaf` | `0xd2f` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x686` | `0x6e2` | **`+0x5c`** |
| `__DATA_CONST.__objc_selrefs` | `0x408` | `0x460` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x6e4` | `0x734` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x850` | `0x898` | **`+0x48`** |
| `__DATA.__data` | `0x538` | `0x578` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x90` | `0xc0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x42c` | `0x454` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x250` | `0x270` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x379` | `0x399` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x34c` | `0x368` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0x68` | `0x80` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x5c` | `0x64` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x30` | `0x34` | **`+0x4`** |

### Other Changes

```diff

-360.63.1.11.2
+360.66.1.11.1

-  Functions: 763
-  Symbols:   435
-  CStrings:  171
+  Functions: 807
+  Symbols:   452
+  CStrings:  183
Symbols:
+ -[MDESerializationHelper dictionaryFromMediaSelectionOptionSourceWithDisplayName:identifier:extendedLanguageTag:mediaCharacteristics:]
+ -[MDESerializationHelper dictionaryFromMetadataWithHasVideo:presentationSize:hasAudio:hasLegible:title:subtitle:artworks:]
+ -[MDESerializationHelper dictionaryFromPlaybackPositionWithPosition:hostTime:rate:]
+ -[MDESerializationHelper dictionaryFromSeekRequestWithPosition:tolerance:]
+ -[MDESerializationHelper dictionaryFromTimelineSegmentWithTimeRange:segmentType:marked:requiresLinearPlayback:identifier:]
+ -[MDESerializationHelper playbackPositionFromDictionary:]
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentArtwork
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentMetadata
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentURLArtwork
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentVideoProperties
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceMediaSelectionOption
+ _OBJC_CLASS_$_AVPlaybackUserInterfacePlaybackPosition
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceTimelineSegment
+ ___NSArray0__struct
+ _associated conformance So21AVMediaCharacteristicaSHSCSQ
+ _associated conformance So21AVMediaCharacteristicas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So21AVMediaCharacteristicas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _objc_retain_x7
+ _swift_dynamicCastObjCClass
+ _swift_getForeignTypeMetadata
+ _symbolic $ss21_ObjectiveCBridgeableP
+ _symbolic So8NSStringC
+ _symbolic _____ So21AVMediaCharacteristica
+ _symbolic _____Sg 5AVKit38AVPlaybackUserInterfaceContentMetadataV15VideoPropertiesV
+ _symbolic _____Sg_ABt 5AVKit38AVPlaybackUserInterfaceContentMetadataV15VideoPropertiesV
+ _symbolic ______XlSg 5AVKit35AVPlaybackUserInterfaceControllableP
+ _symbolic _____yxGSgXwz_x_qd_______Rz_____Rd__r__lXX 11MediaDevice32_SMCBridgeExtensionConfigurationC AA0abD0P 5AVKit35AVPlaybackUserInterfaceControllableP
+ _type_layout_string So21AVMediaCharacteristica
- -[MDESerializationHelper dictionaryFromMediaSelectionOptionSourceWithDisplayName:identifier:extendedLanguageTag:]
- -[MDESerializationHelper dictionaryFromMetadataWithAudioOnly:presentationSize:title:subtitle:albumArtworks:]
- -[MDESerializationHelper dictionaryFromTimelineSegmentWithTimeRange:auxiliaryContent:marked:requiresLinearPlayback:identifier:]
- _OBJC_CLASS_$_AVInterfaceAlbumArtwork
- _OBJC_CLASS_$_AVInterfaceMediaSelectionOptionSource
- _OBJC_CLASS_$_AVInterfaceMetadata
- _OBJC_CLASS_$_AVInterfaceTimelineSegment
- _objc_retain_x25
- _objc_retain_x4
- _symbolic ______XlSg 5AVKit23AVInterfaceControllableP
- _symbolic _____yxGSgXwz_x_qd_______Rz_____Rd__r__lXX 11MediaDevice32_SMCBridgeExtensionConfigurationC AA0abD0P 5AVKit23AVInterfaceControllableP
CStrings:
+ "AVPlaybackUserInterfaceControllable state: %s"
+ "artworks"
+ "audioDescriptionOptions"
+ "audioDescriptionOptions changed, count: %ld"
+ "currentAudioDescriptionOption"
+ "currentAudioDescriptionOption changed to: %s"
+ "currentAudioDescriptionOption changed to: nil"
+ "error changed to: %s"
+ "hasAudio"
+ "hasLegible"
+ "hasVideo"
+ "hostTime"
+ "mediaCharacteristics"
+ "playbackPosition"
+ "playbackPosition did change to: %f @ rate %f"
+ "position"
+ "rate"
+ "segmentType"
+ "tolerance"
- "AVInterfaceControllable state: %s"
- "albumArtworks"
- "audioOnly"
- "auxiliaryContent"
- "currentPlaybackPosition"
- "currentPlaybackPosition did change to: %f"
- "playbackError changed to: %s"
```
