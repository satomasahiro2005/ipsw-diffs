## AVSystemRouting

> `/System/Library/Frameworks/AVSystemRouting.framework/AVSystemRouting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x211cc` | `0x22c4c` | **`+0x1a80`** |
| `__TEXT.__eh_frame` | `0x12e0` | `0x14d8` | **`+0x1f8`** |
| `__AUTH_CONST.__const` | `0x1330` | `0x14c0` | **`+0x190`** |
| `__TEXT.__const` | `0x1808` | `0x1988` | **`+0x180`** |
| `__AUTH_CONST.__cfstring` | `0x8a0` | `0x9a0` | **`+0x100`** |
| `__TEXT.__swift5_capture` | `0x878` | `0x960` | **`+0xe8`** |
| `__TEXT.__swift5_typeref` | `0x694` | `0x766` | **`+0xd2`** |
| `__AUTH_CONST.__objc_const` | `0x2088` | `0x2140` | **`+0xb8`** |
| `__TEXT.__objc_methlist` | `0xd04` | `0xdb4` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0xc60` | `0xcf0` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x978` | `0x9e8` | **`+0x70`** |
| `__AUTH.__data` | `0xb38` | `0xba0` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x770` | `0x7b8` | **`+0x48`** |
| `__TEXT.__cstring` | `0xbfa` | `0xc3a` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x398` | `0x3b8` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x3d4` | `0x3ec` | **`+0x18`** |
| `__DATA.__bss` | `0xc90` | `0xca0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x218` | `0x228` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xac` | `0xbc` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xb4` | `0xc4` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x688` | `0x680` | **`-0x8`** |

### Other Changes

```diff

-360.63.1.11.2
+360.66.1.11.1

-  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

-  Functions: 1020
-  Symbols:   891
-  CStrings:  126
+  Functions: 1067
+  Symbols:   905
+  CStrings:  133
Symbols:
+ -[AVSRSerializationHelper dictionaryFromMediaSelectionOptionSourceWithDisplayName:identifier:extendedLanguageTag:mediaCharacteristics:]
+ -[AVSRSerializationHelper dictionaryFromMetadataWithHasVideo:presentationSize:hasAudio:hasLegible:title:subtitle:artworks:]
+ -[AVSRSerializationHelper dictionaryFromPlaybackPositionWithPosition:hostTime:rate:]
+ -[AVSRSerializationHelper dictionaryFromSeekRequestWithPosition:tolerance:]
+ -[AVSRSerializationHelper dictionaryFromTimelineSegmentWithTimeRange:segmentType:marked:requiresLinearPlayback:identifier:]
+ -[AVSRSerializationHelper playbackPositionFromDictionary:]
+ -[AVSystemMediaSourceExtensionImpl _mediaSelectionOptionsForKey:]
+ -[AVSystemMediaSourceExtensionImpl _setMediaSelectionOption:forKey:propertyName:]
+ -[AVSystemMediaSourceExtensionImpl audioDescriptionOptions]
+ -[AVSystemMediaSourceExtensionImpl currentAudioDescriptionOption]
+ -[AVSystemMediaSourceExtensionImpl error]
+ -[AVSystemMediaSourceExtensionImpl playbackPosition]
+ -[AVSystemMediaSourceExtensionImpl seekToPosition:tolerance:]
+ -[AVSystemMediaSourceExtensionImpl setCurrentAudioDescriptionOption:]
+ -[AVSystemRoutePlaybackControl audioDescriptionOptions]
+ -[AVSystemRoutePlaybackControl currentAudioDescriptionOption]
+ -[AVSystemRoutePlaybackControl error]
+ -[AVSystemRoutePlaybackControl playbackPosition]
+ -[AVSystemRoutePlaybackControl seekToPosition:tolerance:]
+ -[AVSystemRoutePlaybackControl setCurrentAudioDescriptionOption:]
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentArtwork
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentMetadata
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentURLArtwork
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentVideoProperties
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceMediaSelectionOption
+ _OBJC_CLASS_$_AVPlaybackUserInterfacePlaybackPosition
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceTimelineSegment
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfaceMediaSelectionControllable
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfaceMetadataProviding
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfacePlaybackControllable
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfaceTimeControllable
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfaceVolumeControllable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVPlaybackUserInterfaceMediaSelectionControllable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVPlaybackUserInterfaceMetadataProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVPlaybackUserInterfacePlaybackControllable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVPlaybackUserInterfaceTimeControllable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVPlaybackUserInterfaceVolumeControllable
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AVPlaybackUserInterfaceMediaSelectionControllable
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AVPlaybackUserInterfaceMetadataProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AVPlaybackUserInterfacePlaybackControllable
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AVPlaybackUserInterfaceTimeControllable
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AVPlaybackUserInterfaceVolumeControllable
+ __OBJC_$_PROTOCOL_REFS_AVPlaybackUserInterfaceControllable
+ __OBJC_$_PROTOCOL_REFS_AVPlaybackUserInterfaceMediaSelectionControllable
+ __OBJC_$_PROTOCOL_REFS_AVPlaybackUserInterfaceMetadataProviding
+ __OBJC_$_PROTOCOL_REFS_AVPlaybackUserInterfacePlaybackControllable
+ __OBJC_$_PROTOCOL_REFS_AVPlaybackUserInterfaceTimeControllable
+ __OBJC_$_PROTOCOL_REFS_AVPlaybackUserInterfaceVolumeControllable
+ __OBJC_LABEL_PROTOCOL_$_AVPlaybackUserInterfaceControllable
+ __OBJC_LABEL_PROTOCOL_$_AVPlaybackUserInterfaceMediaSelectionControllable
+ __OBJC_LABEL_PROTOCOL_$_AVPlaybackUserInterfaceMetadataProviding
+ __OBJC_LABEL_PROTOCOL_$_AVPlaybackUserInterfacePlaybackControllable
+ __OBJC_LABEL_PROTOCOL_$_AVPlaybackUserInterfaceTimeControllable
+ __OBJC_LABEL_PROTOCOL_$_AVPlaybackUserInterfaceVolumeControllable
+ __OBJC_PROTOCOL_$_AVPlaybackUserInterfaceControllable
+ __OBJC_PROTOCOL_$_AVPlaybackUserInterfaceMediaSelectionControllable
+ __OBJC_PROTOCOL_$_AVPlaybackUserInterfaceMetadataProviding
+ __OBJC_PROTOCOL_$_AVPlaybackUserInterfacePlaybackControllable
+ __OBJC_PROTOCOL_$_AVPlaybackUserInterfaceTimeControllable
+ __OBJC_PROTOCOL_$_AVPlaybackUserInterfaceVolumeControllable
+ ___61-[AVSystemMediaSourceExtensionImpl seekToPosition:tolerance:]_block_invoke
+ ___81-[AVSystemMediaSourceExtensionImpl _setMediaSelectionOption:forKey:propertyName:]_block_invoke
+ ___swift_closure_destructor.18Tm
+ ___swift_closure_destructor.245Tm
+ ___swift_closure_destructor.435Tm
+ ___swift_closure_destructor.464Tm
+ ___swift_closure_destructor.473Tm
+ _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit023AVPlaybackUserInterfaceD12ControllableAA11Observation10Observable
+ _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit35AVPlaybackUserInterfaceControllableAaE0mnO17MetadataProviding
+ _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit35AVPlaybackUserInterfaceControllableAaE0mno14MediaSelectionP0
+ _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit35AVPlaybackUserInterfaceControllableAaE0mno4TimeP0
+ _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit35AVPlaybackUserInterfaceControllableAaE0mno6VolumeP0
+ _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit35AVPlaybackUserInterfaceControllableAaE0mnodP0
+ _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit39AVPlaybackUserInterfaceTimeControllableAA11Observation10Observable
+ _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit40AVPlaybackUserInterfaceMetadataProvidingAA11Observation10Observable
+ _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit41AVPlaybackUserInterfaceVolumeControllableAA11Observation10Observable
+ _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit49AVPlaybackUserInterfaceMediaSelectionControllableAA11Observation10Observable
+ _flat unique So35AVPlaybackUserInterfaceControllable_p
+ _generic environment So8NSObjectCRbzSo35AVPlaybackUserInterfaceControllableRzl
+ _kCMTimeZero
+ _keypath_get_selector_audioDescriptionOptions
+ _keypath_get_selector_currentAudioDescriptionOption
+ _keypath_get_selector_error
+ _keypath_get_selector_playbackPosition
+ _objc_retain_x28
+ _symbolic SaySo38AVPlaybackUserInterfaceTimelineSegmentCG
+ _symbolic SaySo43AVPlaybackUserInterfaceMediaSelectionOptionCG
+ _symbolic So38AVPlaybackUserInterfaceContentMetadataC
+ _symbolic So38AVPlaybackUserInterfaceTimelineSegmentC
+ _symbolic So39AVPlaybackUserInterfacePlaybackPositionC
+ _symbolic So43AVPlaybackUserInterfaceMediaSelectionOptionC
+ _symbolic So43AVPlaybackUserInterfaceMediaSelectionOptionCSg
+ _symbolic _____ 5AVKit38AVPlaybackUserInterfaceContentMetadataV
+ _symbolic _____ So36AVPlaybackUserInterfacePlaybackStateV
+ _symbolic _____ So39AVPlaybackUserInterfaceSeekCapabilitiesV
+ _symbolic _____Sg 5AVKit38AVPlaybackUserInterfaceContentMetadataV15VideoPropertiesV
+ _symbolic ______pSg So35AVPlaybackUserInterfaceControllableP
+ _symbolic _____ySaySo38AVPlaybackUserInterfaceTimelineSegmentCGG 10Foundation24NSKeyValueObservedChangeV
+ _symbolic _____ySaySo43AVPlaybackUserInterfaceMediaSelectionOptionCGG 10Foundation24NSKeyValueObservedChangeV
+ _symbolic _____ySo38AVPlaybackUserInterfaceContentMetadataCG 10Foundation24NSKeyValueObservedChangeV
+ _symbolic _____ySo38AVPlaybackUserInterfaceTimelineSegmentCG 10Foundation24NSKeyValueObservedChangeV
+ _symbolic _____ySo39AVPlaybackUserInterfacePlaybackPositionCG 10Foundation24NSKeyValueObservedChangeV
+ _symbolic _____ySo43AVPlaybackUserInterfaceMediaSelectionOptionCSgG 10Foundation24NSKeyValueObservedChangeV
+ _type_layout_string So39AVPlaybackUserInterfaceSeekCapabilitiesV
- -[AVSRSerializationHelper dictionaryFromMediaSelectionOptionSourceWithDisplayName:identifier:extendedLanguageTag:]
- -[AVSRSerializationHelper dictionaryFromMetadataWithAudioOnly:presentationSize:title:subtitle:albumArtworks:]
- -[AVSRSerializationHelper dictionaryFromTimelineSegmentWithTimeRange:auxiliaryContent:marked:requiresLinearPlayback:identifier:]
- -[AVSystemMediaSourceExtensionImpl currentPlaybackPosition]
- -[AVSystemMediaSourceExtensionImpl playbackError]
- -[AVSystemMediaSourceExtensionImpl setCurrentPlaybackPosition:]
- -[AVSystemRoutePlaybackControl currentPlaybackPosition]
- -[AVSystemRoutePlaybackControl playbackError]
- -[AVSystemRoutePlaybackControl setCurrentPlaybackPosition:]
- _CGSizeZero
- _OBJC_CLASS_$_AVInterfaceAlbumArtwork
- _OBJC_CLASS_$_AVInterfaceMediaSelectionOptionSource
- _OBJC_CLASS_$_AVInterfaceMetadata
- _OBJC_CLASS_$_AVInterfaceTimelineSegment
- __OBJC_$_PROP_LIST_AVInterfaceMediaSelectionControllable
- __OBJC_$_PROP_LIST_AVInterfaceMetadataProviding
- __OBJC_$_PROP_LIST_AVInterfacePlaybackControllable
- __OBJC_$_PROP_LIST_AVInterfaceTimeControllable
- __OBJC_$_PROP_LIST_AVInterfaceVolumeControllable
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVInterfaceMediaSelectionControllable
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVInterfaceMetadataProviding
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVInterfacePlaybackControllable
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVInterfaceTimeControllable
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVInterfaceVolumeControllable
- __OBJC_$_PROTOCOL_METHOD_TYPES_AVInterfaceMediaSelectionControllable
- __OBJC_$_PROTOCOL_METHOD_TYPES_AVInterfaceMetadataProviding
- __OBJC_$_PROTOCOL_METHOD_TYPES_AVInterfacePlaybackControllable
- __OBJC_$_PROTOCOL_METHOD_TYPES_AVInterfaceTimeControllable
- __OBJC_$_PROTOCOL_METHOD_TYPES_AVInterfaceVolumeControllable
- __OBJC_$_PROTOCOL_REFS_AVInterfaceControllable
- __OBJC_$_PROTOCOL_REFS_AVInterfaceMediaSelectionControllable
- __OBJC_$_PROTOCOL_REFS_AVInterfaceMetadataProviding
- __OBJC_$_PROTOCOL_REFS_AVInterfacePlaybackControllable
- __OBJC_$_PROTOCOL_REFS_AVInterfaceTimeControllable
- __OBJC_$_PROTOCOL_REFS_AVInterfaceVolumeControllable
- __OBJC_LABEL_PROTOCOL_$_AVInterfaceControllable
- __OBJC_LABEL_PROTOCOL_$_AVInterfaceMediaSelectionControllable
- __OBJC_LABEL_PROTOCOL_$_AVInterfaceMetadataProviding
- __OBJC_LABEL_PROTOCOL_$_AVInterfacePlaybackControllable
- __OBJC_LABEL_PROTOCOL_$_AVInterfaceTimeControllable
- __OBJC_LABEL_PROTOCOL_$_AVInterfaceVolumeControllable
- __OBJC_PROTOCOL_$_AVInterfaceControllable
- __OBJC_PROTOCOL_$_AVInterfaceMediaSelectionControllable
- __OBJC_PROTOCOL_$_AVInterfaceMetadataProviding
- __OBJC_PROTOCOL_$_AVInterfacePlaybackControllable
- __OBJC_PROTOCOL_$_AVInterfaceTimeControllable
- __OBJC_PROTOCOL_$_AVInterfaceVolumeControllable
- ___58-[AVSystemMediaSourceExtensionImpl setCurrentAudioOption:]_block_invoke
- ___60-[AVSystemMediaSourceExtensionImpl setCurrentLegibleOption:]_block_invoke
- ___63-[AVSystemMediaSourceExtensionImpl setCurrentPlaybackPosition:]_block_invoke
- ___swift_closure_destructor.19Tm
- ___swift_closure_destructor.236Tm
- ___swift_closure_destructor.412Tm
- ___swift_closure_destructor.441Tm
- ___swift_closure_destructor.450Tm
- _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit011AVInterfaceD12ControllableAA11Observation10Observable
- _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit23AVInterfaceControllableAaE0M17MetadataProviding
- _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit23AVInterfaceControllableAaE0m14MediaSelectionN0
- _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit23AVInterfaceControllableAaE0m4TimeN0
- _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit23AVInterfaceControllableAaE0m6VolumeN0
- _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit23AVInterfaceControllableAaE0mdN0
- _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit27AVInterfaceTimeControllableAA11Observation10Observable
- _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit28AVInterfaceMetadataProvidingAA11Observation10Observable
- _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit29AVInterfaceVolumeControllableAA11Observation10Observable
- _associated conformance 15AVSystemRouting0A20RoutePlaybackControl33_9923179369F9DD5FC0D4384DC7CF8771LLC5AVKit37AVInterfaceMediaSelectionControllableAA11Observation10Observable
- _flat unique So23AVInterfaceControllable_p
- _generic environment So8NSObjectCRbzSo23AVInterfaceControllableRzl
- _get_type_metadata 15Synchronization5MutexVy15AVSystemRouting23WeakDataDelegateWrapper33_9923179369F9DD5FC0D4384DC7CF8771LLCSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySO15AVSystemRouting19WeakObserverWrapper33_31ADC135A6F2193423E699A1B77CFCCELLCGG noncopyable
- _keypath_get_selector_currentPlaybackPosition
- _keypath_get_selector_playbackError
- _swift_retain_x1
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic SaySo26AVInterfaceTimelineSegmentCG
- _symbolic SaySo37AVInterfaceMediaSelectionOptionSourceCG
- _symbolic So19AVInterfaceMetadataC
- _symbolic So26AVInterfaceTimelineSegmentC
- _symbolic So37AVInterfaceMediaSelectionOptionSourceC
- _symbolic So37AVInterfaceMediaSelectionOptionSourceCSg
- _symbolic _____ 5AVKit19AVInterfaceMetadataV
- _symbolic _____ So24AVInterfacePlaybackStateV
- _symbolic _____ So27AVInterfaceSeekCapabilitiesV
- _symbolic ______pSg So23AVInterfaceControllableP
- _symbolic _____ySaySo26AVInterfaceTimelineSegmentCGG 10Foundation24NSKeyValueObservedChangeV
- _symbolic _____ySaySo37AVInterfaceMediaSelectionOptionSourceCGG 10Foundation24NSKeyValueObservedChangeV
- _symbolic _____ySo19AVInterfaceMetadataCG 10Foundation24NSKeyValueObservedChangeV
- _symbolic _____ySo26AVInterfaceTimelineSegmentCG 10Foundation24NSKeyValueObservedChangeV
- _symbolic _____ySo37AVInterfaceMediaSelectionOptionSourceCSgG 10Foundation24NSKeyValueObservedChangeV
- _symbolic _____y_____G 10Foundation24NSKeyValueObservedChangeV So6CMTimea
- _type_layout_string So27AVInterfaceSeekCapabilitiesV
CStrings:
+ "artworks"
+ "audioDescriptionOptions"
+ "currentAudioDescriptionOption"
+ "error"
+ "hasLegible"
+ "hasVideo"
+ "hostTime"
+ "mediaCharacteristics"
+ "playbackPosition"
+ "position"
+ "rate"
+ "segmentType"
+ "tolerance"
- "albumArtworks"
- "audioOnly"
- "auxiliaryContent"
- "currentPlaybackPosition"
- "playbackError"
- "setCurrentPlaybackPosition:"
```
