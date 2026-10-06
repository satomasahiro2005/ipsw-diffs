## RelevanceServices

> `/System/Library/PrivateFrameworks/RelevanceServices.framework/RelevanceServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb668` | `0xdd1c` | **`+0x26b4`** |
| `__TEXT.__cstring` | `0x5d2` | `0x853` | **`+0x281`** |
| `__AUTH_CONST.__const` | `0x498` | `0x6e8` | **`+0x250`** |
| `__TEXT.__const` | `0x874` | `0xa24` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `—` | `0x120` | **`+0x120`** |
| `__TEXT.__constg_swiftt` | `0x1d4` | `0x2ec` | **`+0x118`** |
| `__AUTH_CONST.__objc_const` | `0x588` | `0x680` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0xa9` | `0x18f` | **`+0xe6`** |
| `__TEXT.__swift5_typeref` | `0x216` | `0x2e2` | **`+0xcc`** |
| `__TEXT.__unwind_info` | `0x3d0` | `0x498` | **`+0xc8`** |
| `__AUTH_CONST.__auth_got` | `0x4d8` | `0x590` | **`+0xb8`** |
| `__AUTH.__data` | `0xd0` | `0x180` | **`+0xb0`** |
| `__TEXT.__swift5_fieldmd` | `0x288` | `0x320` | **`+0x98`** |
| `__TEXT.__swift5_reflstr` | `0x2e2` | `0x350` | **`+0x6e`** |
| `__TEXT.__swift5_capture` | `0x20` | `0x78` | **`+0x58`** |
| `__DATA.__common` | `0x30` | `0x78` | **`+0x48`** |
| `__DATA.__data` | `0x358` | `0x390` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b8` | `0x1d8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x170` | `0x188` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__DATA.__bss` | `0xa30` | `0xa40` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x100` | `0x110` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x28` | `0x38` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x4` | `0xc` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x50` | `0x54` | **`+0x4`** |

### Other Changes

```diff

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 375
-  Symbols:   279
-  CStrings:  43
+  Functions: 444
+  Symbols:   319
+  CStrings:  60
Symbols:
+ _CFNotificationCenterPostNotification
+ _MobileGestalt_get_deviceSupportsAudioIntelligence
+ _OBJC_CLASS_$_NSHashTable
+ _OBJC_CLASS_$__TtCs12_SwiftObject
+ _OBJC_METACLASS_$__TtCs12_SwiftObject
+ _RSDeviceSupportsAudioIntelligence
+ _RSDeviceSupportsAudioIntelligence._supported
+ _RSDeviceSupportsAudioIntelligence.onceToken
+ __DATA__TtC17RelevanceServices36AudioUnderstandingSettingsController
+ __IVARS__TtC17RelevanceServices36AudioUnderstandingSettingsController
+ __METACLASS_DATA__TtC17RelevanceServices36AudioUnderstandingSettingsController
+ ___RSDeviceSupportsAudioIntelligence_block_invoke
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ _free
+ _objc_release_x27
+ _swift_conformsToProtocol2
+ _swift_coroFrameAlloc
+ _swift_deallocClassInstance
+ _swift_getForeignTypeMetadata
+ _swift_release_x24
+ _swift_retain_x19
+ _swift_retain_x24
+ _swift_retain_x25
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _symbolic $s17RelevanceServices26AudioUnderstandingSettingsP
+ _symbolic $s17RelevanceServices34AudioUnderstandingSettingsObserverP
+ _symbolic SS
+ _symbolic ScA_pSg
+ _symbolic ScPSg
+ _symbolic _____ 17RelevanceServices15ShazamAnalyticsV
+ _symbolic _____ 17RelevanceServices27AudioUnderstandingAnalyticsV
+ _symbolic _____ 17RelevanceServices36AudioUnderstandingSettingsControllerC
+ _symbolic _____ So39NHSSPrivacyDefaultsMicrophonePermissionV
+ _symbolic ______p 17RelevanceServices34AudioUnderstandingSettingsObserverP
+ _symbolic _____ySo11NSHashTableCyyXlGG 15Synchronization5MutexVAARi_zrlE
+ _symbolic x
+ _symbolic ytIeAgHr_
CStrings:
+ "MusicDetectedSeconds"
+ "MusicDetectionOptedIn"
+ "Sent AudioUnderstanding activation. type=%{public}s, enabled=%{bool,public}d, activeMinutes=%{public}ld, detectedMinutes=%{public}ld."
+ "Sent music detection duration. seconds=%ld, permission=%{public}s."
+ "audioBufferEnabled"
+ "audioIntelligence"
+ "audioUnderstanding"
+ "audioUnderstandingController"
+ "audioUnderstandingSecure"
+ "com.apple.RelevancePlatform.AudioUnderstanding"
+ "com.apple.RelevancePlatform.AudioUnderstandingPrefsDidChange"
+ "com.apple.RelevancePlatform.MindPalaceActiveStateDidChange"
+ "com.apple.RelevancePlatform.MindPalaceGlobalEnabledDidChange"
+ "com.apple.Shazam.MusicRecognition.MusicDetectionDuration"
+ "com.apple.audioUnderstanding.activation"
+ "com.apple.relevanced.AudioIntelligenceAvailabilityQueue"
+ "instantShazam"
```
