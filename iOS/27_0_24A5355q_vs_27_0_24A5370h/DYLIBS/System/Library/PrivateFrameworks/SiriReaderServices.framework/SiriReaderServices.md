## SiriReaderServices

> `/System/Library/PrivateFrameworks/SiriReaderServices.framework/SiriReaderServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x788` | `0x6bdc` | **`+0x6454`** |
| `__TEXT.__eh_frame` | `—` | `0x508` | **`+0x508`** |
| `__AUTH_CONST.__auth_got` | `0x0` | `0x368` | **`+0x368`** |
| `__TEXT.__cstring` | `0xae` | `0x362` | **`+0x2b4`** |
| `__AUTH_CONST.__const` | `0x60` | `0x2e8` | **`+0x288`** |
| `__TEXT.__oslogstring` | `0x36` | `0x27c` | **`+0x246`** |
| `__TEXT.__const` | `0x60` | `0x242` | **`+0x1e2`** |
| `__TEXT.__unwind_info` | `0x90` | `0x258` | **`+0x1c8`** |
| `__TEXT.__objc_methlist` | `0x1f0` | `0x388` | **`+0x198`** |
| `__AUTH_CONST.__objc_const` | `0x278` | `0x3d8` | **`+0x160`** |
| `__AUTH.__objc_data` | `0xa0` | `0x1c0` | **`+0x120`** |
| `__TEXT.__swift5_capture` | `—` | `0xe4` | **`+0xe4`** |
| `__TEXT.__swift5_typeref` | `—` | `0xd5` | **`+0xd5`** |
| `__DATA_CONST.__objc_selrefs` | `0x188` | `0x250` | **`+0xc8`** |
| `__TEXT.__constg_swiftt` | `—` | `0xc0` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0x0` | `0xb8` | **`+0xb8`** |
| `__DATA_CONST.__const` | `0x68` | `0x108` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x54` | **`+0x54`** |
| `__DATA.__bss` | `—` | `0x30` | **`+0x30`** |
| `__DATA.__data` | `0xc0` | `0xf0` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `—` | `0x2c` | **`+0x2c`** |
| `__TEXT.__swift_as_entry` | `—` | `0x2c` | **`+0x2c`** |
| `__TEXT.__swift_as_ret` | `—` | `0x2c` | **`+0x2c`** |
| `__AUTH.__data` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x27` | **`+0x27`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4` | `0xc` | **`+0x8`** |
| `__TEXT.__swift5_types` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_imageinfo`

### Other Changes

```diff

-3600.49.31.1.6
+3600.55.10.0.0

+  - /System/Library/Frameworks/UIKit.framework/UIKit

+  - /System/Library/PrivateFrameworks/SiriTTSService.framework/SiriTTSService

-  Functions: 15
-  Symbols:   86
-  CStrings:  10
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftCoreImage.dylib
+  - /usr/lib/swift/libswiftCoreLocation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftQuartzCore.dylib
+  - /usr/lib/swift/libswiftSpatial.dylib
+  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswift_Concurrency.dylib
+  - /usr/lib/swift/libswiftos.dylib
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 138
+  Symbols:   241
+  CStrings:  47
Symbols:
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isBlockedAppsEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isCarplayConversationModeEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isCarplayPersistentConversationModeEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isDrivingFocusMessageReadingEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isExpandedAttributionEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isEyesfreeRedesignEyesfreeDisabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isEyesfreeRedesignOnlySteeringwheelEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isHearablesDisableActivationAudioOutputOnlyEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isLinwoodAttachmentsEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isLinwoodCarplayBannerPreprocessEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isLinwoodDismissalEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isLinwoodLatencyV2Enabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isLinwoodMiniSnippetSummarizationEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isLinwoodTtsPauseResumeEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isLinwoodTwoshotEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isNonSpeakerActivationPermissionEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isPersistentSiriEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isSiriReadThisV2Enabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isSiriReadThisV3Enabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isSpeakerActivationPermissionEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isSpeechSynthesizerV2Enabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isVisualIntelligenceDirectRoutingEnabled]
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isWindowedLaunchEnabled]
+ +[SiriReaderConnection sharedReaderSessionBridge]
+ GCC_except_table10
+ _OBJC_CLASS_$_SRUIFSiriUIFeatureFlag
+ _OBJC_CLASS_$_SiriReaderDaemonReaderSessionBridge
+ _OBJC_IVAR_$_SiriReaderConnection._readerSessionBridge
+ _OBJC_IVAR_$_SiriReaderConnection._usesReaderSession
+ _OBJC_METACLASS_$_SRUIFSiriUIFeatureFlag
+ _OBJC_METACLASS_$_SiriReaderDaemonReaderSessionBridge
+ _UIImagePNGRepresentation
+ __DATA_SiriReaderDaemonReaderSessionBridge
+ __INSTANCE_METHODS_SiriReaderDaemonReaderSessionBridge
+ __IVARS_SiriReaderDaemonReaderSessionBridge
+ __METACLASS_DATA_SiriReaderDaemonReaderSessionBridge
+ __OBJC_$_CLASS_METHODS_SRUIFSiriUIFeatureFlag(SWEFeatureFlags)
+ __OBJC_$_CLASS_METHODS_SiriReaderConnection
+ __OBJC_CLASS_RO_$_SRUIFSiriUIFeatureFlag
+ __OBJC_METACLASS_RO_$_SRUIFSiriUIFeatureFlag
+ ___49+[SiriReaderConnection sharedReaderSessionBridge]_block_invoke
+ ___chkstk_darwin
+ ___swift_async_cont_functlets
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ ___swift_closure_destructor
+ ___swift_closure_destructor.16Tm
+ ___swift_destroy_boxed_opaque_existential_1Tm
+ ___swift_instantiateConcreteTypeFromMangledNameV2
+ ___swift_memcpy4_4
+ ___swift_noop_void_return
+ ___swift_project_boxed_opaque_existential_1
+ ___swift_reflection_version
+ __os_feature_enabled_impl
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftCoreFoundation_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreImage_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_FORCE_LOAD_$_swiftCoreLocation_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftDispatch_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftFoundation_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftMetal_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftOSLog_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftObjectiveC_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftQuartzCore
+ __swift_FORCE_LOAD_$_swiftQuartzCore_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftSpatial_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftUIKit
+ __swift_FORCE_LOAD_$_swiftUIKit_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swiftXPC_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swift_Builtin_float_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftos
+ __swift_FORCE_LOAD_$_swiftos_$_SiriReaderServices
+ __swift_FORCE_LOAD_$_swiftsimd
+ __swift_FORCE_LOAD_$_swiftsimd_$_SiriReaderServices
+ __swift_stdlib_malloc_size
+ _dispatch_once
+ _dispatch_semaphore_create
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_allocWithZone
+ _objc_alloc_init
+ _objc_release_x1
+ _objc_retainAutoreleaseReturnValue
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x19
+ _objc_retain_x25
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _sharedReaderSessionBridge.onceToken
+ _sharedReaderSessionBridge.sharedBridge
+ _swift_allocBox
+ _swift_allocObject
+ _swift_beginAccess
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_deallocObject
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getErrorValue
+ _swift_getForeignTypeMetadata
+ _swift_getObjectType
+ _swift_getSingletonMetadata
+ _swift_getTypeByMangledNameInContext2
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_lookUpClassMethod
+ _swift_projectBox
+ _swift_release
+ _swift_release_x19
+ _swift_release_x20
+ _swift_release_x27
+ _swift_release_x8
+ _swift_retain_x21
+ _swift_retain_x27
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_updateClassMetadata2
+ _symbolic $s18SiriReaderServices0B10SessioningP
+ _symbolic ScA_pSg
+ _symbolic ScPSg
+ _symbolic So21OS_dispatch_semaphoreC
+ _symbolic So8NSObjectC
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 18SiriReaderServices06DaemonB13SessionBridgeC
+ _symbolic _____ 2os6LoggerV
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ s6UInt32V
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic _____Sg 14SiriTTSService13ReaderArticleV12ArtworkImageO
+ _symbolic ______p 18SiriReaderServices0B10SessioningP
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 14SiriTTSService13ReaderArticleV14PlaybackStatusO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 14SiriTTSService13ReaderArticleV14PlaybackStatusO So16os_unfair_lock_sV
+ _symbolic _____z_Xx 14SiriTTSService13ReaderArticleV
+ _symbolic ytIeAgHr_
+ _type_layout_string So16os_unfair_lock_sV
- GCC_except_table8
CStrings:
+ "%s SiriReaderConnection: V3 path — using DaemonReaderSession via bridge"
+ "-[SiriReaderConnection init]"
+ "SiriUI"
+ "blocked_apps"
+ "carplay_conversation_mode"
+ "carplay_persistent_conversation_mode"
+ "com.apple.siri.SiriReaderServices"
+ "driving_focus_message_reading"
+ "endMediaSession failed: %{public}s"
+ "endMediaSession: invalid UUID string '%{public}s'"
+ "expanded_attribution"
+ "eyesfree_redesign_eyesfree_disabled"
+ "eyesfree_redesign_only_steeringwheel_enabled"
+ "getPlaybackStatus failed: %{public}s"
+ "getPlaybackStatus: invalid UUID string '%{public}s'"
+ "hearables_disable_activation_audio_output_only"
+ "linwood_attachments"
+ "linwood_carplay_banner_preprocess"
+ "linwood_dismissal"
+ "linwood_latency_v2"
+ "linwood_mini_snippet_summarization"
+ "linwood_tts_pause_resume"
+ "linwood_twoshot"
+ "non_speaker_activation_permission"
+ "pausePlayback failed: %{public}s"
+ "pausePlayback: invalid UUID string '%{public}s'"
+ "persistent_siri"
+ "readText failed: %{public}s"
+ "readText: invalid UUID string '%{public}s'"
+ "resumePlayback failed: %{public}s"
+ "resumePlayback: invalid UUID string '%{public}s'"
+ "siri_read_this_v2"
+ "siri_read_this_v3"
+ "speaker_activation_permission"
+ "speech_synthesizer_v2"
+ "visual_intelligence_direct_routing"
+ "windowed_launch"
```
