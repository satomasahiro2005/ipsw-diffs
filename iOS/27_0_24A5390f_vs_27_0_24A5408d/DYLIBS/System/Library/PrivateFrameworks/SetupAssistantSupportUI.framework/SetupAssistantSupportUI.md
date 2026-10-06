## SetupAssistantSupportUI

> `/System/Library/PrivateFrameworks/SetupAssistantSupportUI.framework/SetupAssistantSupportUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x892b0` | `0x79e2c` | **`-0xf484`** |
| `__DATA.__bss` | `0x5200` | `0x4498` | **`-0xd68`** |
| `__TEXT.__eh_frame` | `0x27b0` | `0x1aa8` | **`-0xd08`** |
| `__AUTH_CONST.__const` | `0x4c78` | `0x4070` | **`-0xc08`** |
| `__TEXT.__const` | `0x5334` | `0x48a0` | **`-0xa94`** |
| `__TEXT.__unwind_info` | `0x2400` | `0x1f58` | **`-0x4a8`** |
| `__TEXT.__constg_swiftt` | `0x30a4` | `0x2c18` | **`-0x48c`** |
| `__AUTH_CONST.__objc_const` | `0xa330` | `0x9ed0` | **`-0x460`** |
| `__AUTH.__data` | `0x3270` | `0x2e40` | **`-0x430`** |
| `__TEXT.__swift5_reflstr` | `0x1a99` | `0x178f` | **`-0x30a`** |
| `__TEXT.__swift5_fieldmd` | `0x1d2c` | `0x1a3c` | **`-0x2f0`** |
| `__TEXT.__swift5_typeref` | `0x43de` | `0x416f` | **`-0x26f`** |
| `__TEXT.__oslogstring` | `0x1b62` | `0x1937` | **`-0x22b`** |
| `__TEXT.__cstring` | `0x1a33` | `0x184b` | **`-0x1e8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1538` | `0x13a0` | **`-0x198`** |
| `__AUTH_CONST.__auth_got` | `0x1480` | `0x1328` | **`-0x158`** |
| `__DATA.__data` | `0x1770` | `0x1668` | **`-0x108`** |
| `__TEXT.__swift5_capture` | `0x934` | `0x858` | **`-0xdc`** |
| `__TEXT.__swift_as_cont` | `0x19c` | `0xe8` | **`-0xb4`** |
| `__TEXT.__swift5_builtin` | `0x1e0` | `0x154` | **`-0x8c`** |
| `__DATA_CONST.__got` | `0x6f0` | `0x668` | **`-0x88`** |
| `__TEXT.__swift5_assocty` | `0x2b8` | `0x240` | **`-0x78`** |
| `__TEXT.__swift_as_ret` | `0xd0` | `0x5c` | **`-0x74`** |
| `__TEXT.__swift5_proto` | `0x290` | `0x224` | **`-0x6c`** |
| `__TEXT.__swift_as_entry` | `0xc8` | `0x74` | **`-0x54`** |
| `__TEXT.__swift5_types` | `0x220` | `0x1ec` | **`-0x34`** |
| `__DATA_CONST.__const` | `0x3a0` | `0x370` | **`-0x30`** |
| `__AUTH.__objc_data` | `0xf30` | `0xf10` | **`-0x20`** |
| `__AUTH_CONST.__cfstring` | `0x4e0` | `0x4c0` | **`-0x20`** |
| `__DATA.__common` | `0x110` | `0xf8` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x1b0` | `0x198` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x1a78` | `0x1a68` | **`-0x10`** |
| `__TEXT.__swift5_protos` | `0x34` | `0x28` | **`-0xc`** |

### Other Changes

```diff

-565.0.0.0.0
+567.100.0.0.0

-  - /System/Library/Frameworks/AVKit.framework/AVKit

-  - /System/Library/Frameworks/MediaPlayer.framework/MediaPlayer

-  - /System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote
-  - /System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset

-  - /usr/lib/swift/libswiftAVFoundation.dylib

-  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Functions: 3235
-  Symbols:   1719
-  CStrings:  351
+  Functions: 2893
+  Symbols:   1630
+  CStrings:  321
Symbols:
- +[SASUILogging newFeaturesCategory]
- _MRMediaRemoteSetCanBeNowPlayingApplication
- _OBJC_CLASS_$_AVPlaybackSpeed
- _OBJC_CLASS_$_AVPlayer
- _OBJC_CLASS_$_AVPlayerViewController
- _OBJC_CLASS_$_AVPlayerViewControllerConfiguration
- _OBJC_CLASS_$_MAAsset
- _OBJC_CLASS_$_MAAssetQuery
- _OBJC_CLASS_$_MADownloadOptions
- _OBJC_CLASS_$_MPNowPlayingInfoCenter
- _OBJC_CLASS_$_NSProcessInfo
- _OBJC_CLASS_$_NSValue
- __DATA__TtC23SetupAssistantSupportUI18NewFeaturesContext
- __DATA__TtC23SetupAssistantSupportUI18NewFeaturesHandler
- __DATA__TtCFE23SetupAssistantSupportUICSo8AVPlayer16untilReadyToPlayFzZT_T_L_4Done
- __IVARS__TtC23SetupAssistantSupportUI18NewFeaturesContext
- __IVARS__TtC23SetupAssistantSupportUI18NewFeaturesHandler
- __IVARS__TtCFE23SetupAssistantSupportUICSo8AVPlayer16untilReadyToPlayFzZT_T_L_4Done
- __METACLASS_DATA__TtC23SetupAssistantSupportUI18NewFeaturesContext
- __METACLASS_DATA__TtC23SetupAssistantSupportUI18NewFeaturesHandler
- __METACLASS_DATA__TtCFE23SetupAssistantSupportUICSo8AVPlayer16untilReadyToPlayFzZT_T_L_4Done
- ___swift_closure_destructor.90Tm
- ___swift_memcpy24_4
- ___swift_memcpy57_8
- __swift_FORCE_LOAD_$_swiftAVFoundation
- __swift_FORCE_LOAD_$_swiftAVFoundation_$_SetupAssistantSupportUI
- __swift_FORCE_LOAD_$_swiftCoreMIDI
- __swift_FORCE_LOAD_$_swiftCoreMIDI_$_SetupAssistantSupportUI
- _associated conformance 23SetupAssistantSupportUI18NewFeaturesContextC13ChapterMarker33_AFD277CCE9E118F37A3E1DEF4BF7976CLLV10CodingKeysOSHAASQ
- _associated conformance 23SetupAssistantSupportUI18NewFeaturesContextC13ChapterMarker33_AFD277CCE9E118F37A3E1DEF4BF7976CLLV10CodingKeysOs0R3KeyAAs23CustomStringConvertible
- _associated conformance 23SetupAssistantSupportUI18NewFeaturesContextC13ChapterMarker33_AFD277CCE9E118F37A3E1DEF4BF7976CLLV10CodingKeysOs0R3KeyAAs28CustomDebugStringConvertible
- _associated conformance 23SetupAssistantSupportUI18NewFeaturesContextCSHAASQ
- _associated conformance 23SetupAssistantSupportUI18NewFeaturesContextCSLAASQ
- _associated conformance 23SetupAssistantSupportUI24NewFeaturesProviderErrorO10Foundation13CustomNSErrorAAs0H0
- _associated conformance 23SetupAssistantSupportUI24NewFeaturesProviderErrorOSHAASQ
- _kCMTimeZero
- _keypath_get_selector_rate
- _keypath_get_selector_status
- _swift_allocError
- _swift_continuation_resume
- _swift_continuation_throwingResume
- _swift_defaultActor_deallocate
- _swift_defaultActor_destroy
- _swift_defaultActor_initialize
- _swift_release_x10
- _symbolic $s23SetupAssistantSupportUI19NewFeaturesDelegateP
- _symbolic $s23SetupAssistantSupportUI19NewFeaturesProviderP
- _symbolic $s23SetupAssistantSupportUI27NewFeaturesAssetAcquisitionP
- _symbolic BD
- _symbolic Say_____G 23SetupAssistantSupportUI18NewFeaturesContextC
- _symbolic Say_____G 23SetupAssistantSupportUI18NewFeaturesContextC13ChapterMarker33_AFD277CCE9E118F37A3E1DEF4BF7976CLLV
- _symbolic Say_____GSg 23SetupAssistantSupportUI18NewFeaturesContextC
- _symbolic ScCyyt______pG s5ErrorP
- _symbolic SccySb_____G s5NeverO
- _symbolic Sccy__________G So13MAPurgeResultV s5NeverO
- _symbolic Sccy__________G So13MAQueryResultV s5NeverO
- _symbolic Sccy__________G So16MADownloadResultV s5NeverO
- _symbolic Sccy__________G So22MACancelDownloadResultV s5NeverO
- _symbolic Sccyyt_____G s5NeverO
- _symbolic So12AVPlayerItemCSg
- _symbolic So22AVPlayerViewControllerCSg
- _symbolic So8AVPlayerC
- _symbolic So8AVPlayerCSg
- _symbolic _____ 23SetupAssistantSupportUI18NewFeaturesContextC
- _symbolic _____ 23SetupAssistantSupportUI18NewFeaturesContextC13ChapterMarker33_AFD277CCE9E118F37A3E1DEF4BF7976CLLV
- _symbolic _____ 23SetupAssistantSupportUI18NewFeaturesContextC13ChapterMarker33_AFD277CCE9E118F37A3E1DEF4BF7976CLLV10CodingKeysO
- _symbolic _____ 23SetupAssistantSupportUI18NewFeaturesHandlerC
- _symbolic _____ 23SetupAssistantSupportUI24NewFeaturesProviderErrorO
- _symbolic _____ So11CMTimeFlagsV
- _symbolic _____ So13MAPurgeResultV
- _symbolic _____ So13MAQueryResultV
- _symbolic _____ So14AVPlayerStatusV
- _symbolic _____ So16MADownloadResultV
- _symbolic _____ So22MACancelDownloadResultV
- _symbolic _____ So6CMTimea
- _symbolic _____ So8AVPlayerC23SetupAssistantSupportUIE16untilReadyToPlayyyYaKF4DoneL_C
- _symbolic _____ s5Int64V
- _symbolic _____ s6UInt32V
- _symbolic _____Sg 10Foundation21NSKeyValueObservationC
- _symbolic _____Sg 23SetupAssistantSupportUI18NewFeaturesContextC
- _symbolic _____SgXw 23SetupAssistantSupportUI18NewFeaturesHandlerC
- _symbolic _____SgXwz_Xx 23SetupAssistantSupportUI18NewFeaturesHandlerC
- _symbolic _____Sg_ABt 10Foundation3URLV
- _symbolic ______pSgXw 23SetupAssistantSupportUI19NewFeaturesDelegateP
- _symbolic _____y_____G s22KeyedDecodingContainerV 23SetupAssistantSupportUI18NewFeaturesContextC13ChapterMarker33_AFD277CCE9E118F37A3E1DEF4BF7976CLLV10CodingKeysO
- _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
- _type_layout_string 23SetupAssistantSupportUI18NewFeaturesContextC13ChapterMarker33_AFD277CCE9E118F37A3E1DEF4BF7976CLLV
- _type_layout_string So11CMTimeFlagsV
- _type_layout_string So6CMTimea
CStrings:
- "Asset state: %ld"
- "Assets already loaded, skipping asset lookup"
- "Catalog download result: %ld"
- "Continuing video playback"
- "Handling boundary time: %f"
- "Loading assets from override location: %s"
- "Loading downloaded asset for: %s"
- "Pausing video now, at time: %f"
- "Preparing to pause at beginning of context: %s"
- "Query result: %ld"
- "Resetting and pausing video playback"
- "Unable to use downloadable asset due to error: %@, using local asset: %s.mp4"
- "Unexpectedly got invalid boundary time callback"
- "accessibilityEndTime"
- "accessibilityStartTime"
- "assetDownloadFailed"
- "assetInvalid"
- "assetNotDownloaded"
- "assetNotLoaded"
- "assetPurgeFailed"
- "assetQueryFailed"
- "assetQueryFoundNone"
- "assetUnavailable"
- "com.apple.MobileAsset.SetupAssistantNewFeaturesIntroduction"
- "invalidContext"
- "newFeaturesVideo-"
- "newfeatures"
- "playerNotConfigured"
- "retrieveAssetFromServer()"
- "untilReadyToPlay()"
```
