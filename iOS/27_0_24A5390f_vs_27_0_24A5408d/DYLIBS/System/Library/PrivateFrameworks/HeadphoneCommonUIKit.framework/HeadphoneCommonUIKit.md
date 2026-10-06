## HeadphoneCommonUIKit

> `/System/Library/PrivateFrameworks/HeadphoneCommonUIKit.framework/HeadphoneCommonUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9f738` | `0xbe97c` | **`+0x1f244`** |
| `__AUTH_CONST.__const` | `0x4838` | `0x74e0` | **`+0x2ca8`** |
| `__TEXT.__swift5_capture` | `0x1364` | `0x25c8` | **`+0x1264`** |
| `__AUTH_CONST.__objc_const` | `0x32e8` | `0x3ec0` | **`+0xbd8`** |
| `__TEXT.__oslogstring` | `0x6c7` | `0x11e7` | **`+0xb20`** |
| `__TEXT.__eh_frame` | `0xb28` | `0xd68` | **`+0x240`** |
| `__TEXT.__unwind_info` | `0x14f8` | `0x1680` | **`+0x188`** |
| `__DATA.__data` | `0x1ea8` | `0x2010` | **`+0x168`** |
| `__TEXT.__const` | `0x45f4` | `0x4754` | **`+0x160`** |
| `__TEXT.__cstring` | `0x2ff8` | `0x3138` | **`+0x140`** |
| `__DATA_CONST.__objc_selrefs` | `0x1360` | `0x1468` | **`+0x108`** |
| `__TEXT.__objc_methlist` | `0x122c` | `0x1334` | **`+0x108`** |
| `__AUTH.__data` | `0xb60` | `0xc48` | **`+0xe8`** |
| `__TEXT.__swift5_typeref` | `0x3dd6` | `0x3e90` | **`+0xba`** |
| `__DATA_CONST.__got` | `0x978` | `0xa30` | **`+0xb8`** |
| `__TEXT.__swift5_reflstr` | `0xa3d` | `0xadd` | **`+0xa0`** |
| `__AUTH_CONST.__auth_got` | `0x12b0` | `0x1338` | **`+0x88`** |
| `__TEXT.__swift5_fieldmd` | `0xef4` | `0xf70` | **`+0x7c`** |
| `__TEXT.__constg_swiftt` | `0x2214` | `0x2270` | **`+0x5c`** |
| `__TEXT.__swift_as_cont` | `0x48` | `0x78` | **`+0x30`** |
| `__DATA_CONST.__objc_protolist` | `0x68` | `0x88` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x34` | `0x54` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x1a4` | `0x1b8` | **`+0x14`** |
| `__DATA_CONST.__objc_protorefs` | `0x30` | `0x40` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x30` | `0x40` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x108` | `0x110` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1ac` | `0x1b4` | **`+0x8`** |

### Other Changes

```diff

-40.36.1.0.0
+40.41.1.1.4

+  - /System/Library/Frameworks/CoreHaptics.framework/CoreHaptics

-  Functions: 3151
-  Symbols:   1457
-  CStrings:  446
+  Functions: 3571
+  Symbols:   1502
+  CStrings:  496
Symbols:
+ _CHHapticDynamicParameterIDHapticIntensityControl
+ _CHHapticDynamicParameterIDHapticSharpnessControl
+ _CHHapticEventParameterIDHapticIntensity
+ _CHHapticEventParameterIDHapticSharpness
+ _CHHapticEventTypeHapticContinuous
+ _MobileGestalt_get_appleInternalInstallCapability
+ _MobileGestalt_get_current_device
+ _OBJC_CLASS_$_CHHapticDynamicParameter
+ _OBJC_CLASS_$_CHHapticEngine
+ _OBJC_CLASS_$_CHHapticEvent
+ _OBJC_CLASS_$_CHHapticEventParameter
+ _OBJC_CLASS_$_CHHapticPattern
+ _OBJC_CLASS_$_UIImpactFeedbackGenerator
+ __DATA__TtC20HeadphoneCommonUIKit22ContinuousHapticEngine
+ __IVARS__TtC20HeadphoneCommonUIKit22ContinuousHapticEngine
+ __METACLASS_DATA__TtC20HeadphoneCommonUIKit22ContinuousHapticEngine
+ __OBJC_$_PROP_LIST_CHHapticAdvancedPatternPlayer
+ __OBJC_$_PROP_LIST_CHHapticPatternPlayer
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CHHapticAdvancedPatternPlayer
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CHHapticPatternPlayer
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CHHapticAdvancedPatternPlayer
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CHHapticPatternPlayer
+ __OBJC_$_PROTOCOL_REFS_CHHapticAdvancedPatternPlayer
+ __OBJC_$_PROTOCOL_REFS_CHHapticPatternPlayer
+ __OBJC_LABEL_PROTOCOL_$_CHHapticAdvancedPatternPlayer
+ __OBJC_LABEL_PROTOCOL_$_CHHapticPatternPlayer
+ __OBJC_PROTOCOL_$_CHHapticAdvancedPatternPlayer
+ __OBJC_PROTOCOL_$_CHHapticPatternPlayer
+ _flat unique So29CHHapticAdvancedPatternPlayer_p
+ _swift_getErrorValue
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic SAySo7NSErrorCSgG
+ _symbolic ScTyyt_____GSg s5NeverO
+ _symbolic SiIegd_
+ _symbolic SiIegr_
+ _symbolic So14CHHapticEngineCSg
+ _symbolic _____ 20HeadphoneCommonUIKit22ContinuousHapticEngineC
+ _symbolic _____ So27CHHapticEngineStoppedReasonV
+ _symbolic _____SgXw 20HeadphoneCommonUIKit22ContinuousHapticEngineC
+ _symbolic _____SgXwz_Xx 20HeadphoneCommonUIKit22ContinuousHapticEngineC
+ _symbolic _____XDXMT 20HeadphoneCommonUIKit22ContinuousHapticEngineC
+ _symbolic ______pSg So29CHHapticAdvancedPatternPlayerP
+ _symbolic ______ypt s11AnyHashableV
CStrings:
+ ")"
+ "HeadphoneCommonUIKit/ContinuousHapticEngine.swift"
+ "[HAPTIC-ENGINE] buildPlayer #%ld: creating pattern + player"
+ "[HAPTIC-ENGINE] buildPlayer #%ld: player ready"
+ "[HAPTIC-ENGINE] ensureReady #%ld: FAILED — %s — engine=%{bool}d player=%{bool}d"
+ "[HAPTIC-ENGINE] ensureReady #%ld: building new engine"
+ "[HAPTIC-ENGINE] ensureReady #%ld: calling engine.start()"
+ "[HAPTIC-ENGINE] ensureReady #%ld: engine created OK"
+ "[HAPTIC-ENGINE] ensureReady #%ld: engine.start() succeeded"
+ "[HAPTIC-ENGINE] ensureReady #%ld: ready — engine+player up"
+ "[HAPTIC-ENGINE] ensureReady #%ld: reusing existing engine (engineStarted=%{bool}d)"
+ "[HAPTIC-ENGINE] forceRestart() — cancelling heartbeat, dropping engine+player"
+ "[HAPTIC-ENGINE] heartbeat tick #%ld: FAILED — %s (engineStarted=%{bool}d)"
+ "[HAPTIC-ENGINE] heartbeat tick #%ld: OK (engineStarted=%{bool}d)"
+ "[HAPTIC-ENGINE] heartbeat: exiting (cancelled=%{bool}d)"
+ "[HAPTIC-ENGINE] impact() post-check: engineStarted=%{bool}d player=%{bool}d"
+ "[HAPTIC-ENGINE] impact() post-check: engineStarted=false but player exists — forcing rebuild"
+ "[HAPTIC-ENGINE] impact() — engineStarted=%{bool}d player=%{bool}d"
+ "[HAPTIC-ENGINE] init supportsHaptics=%{bool}d"
+ "[HAPTIC-ENGINE] isPlayerHealthy(): probe THREW: %s"
+ "[HAPTIC-ENGINE] player completionHandler Task: nulling player, rebuilding"
+ "[HAPTIC-ENGINE] player completionHandler — pattern expired, error=%s — will rebuild"
+ "[HAPTIC-ENGINE] prewarm() — engine=%{bool}d player=%{bool}d engineStarted=%{bool}d"
+ "[HAPTIC-ENGINE] resetHandler Task running — nulling player only, rebuilding"
+ "[HAPTIC-ENGINE] resetHandler fired — engine alive but all players invalid"
+ "[HAPTIC-ENGINE] retry #%ld/%ld: scheduling rebuild in %fs (after attempt #%ld)"
+ "[HAPTIC-ENGINE] retry #%ld: running delayed ensureReady()"
+ "[HAPTIC-ENGINE] retry skipped — player already rebuilt"
+ "[HAPTIC-ENGINE] retry: max retries reached after attempt #%ld — giving up until next prewarm/start"
+ "[HAPTIC-ENGINE] start() — player=%{bool}d engineStarted=%{bool}d healthy=%{bool}d"
+ "[HAPTIC-ENGINE] start(): engineStarted=false but player exists — forcing rebuild"
+ "[HAPTIC-ENGINE] start(): health check FAILED — forcing rebuild (engineStarted=%{bool}d)"
+ "[HAPTIC-ENGINE] stop() — lastSent=(%f, %f) engineStarted=%{bool}d"
+ "[HAPTIC-ENGINE] stoppedHandler Task running — nulling engine+player, rebuilding"
+ "[HAPTIC-ENGINE] stoppedHandler fired — reason=%ld (%s)"
+ "[HAPTIC-ENGINE] teardown() — engine=%{bool}d player=%{bool}d engineStarted=%{bool}d"
+ "[HAPTIC-ENGINE] teardown: failed to stop haptic player: %s"
+ "[HAPTIC-ENGINE] updateIntensity sendParameters THREW: %s engineStarted=%{bool}d — marking player for rebuild"
+ "applicationSuspended"
+ "audioSessionInterrupt"
+ "com.apple.ConnectedAudio"
+ "enableSliderHaptics"
+ "engineDestroyed"
+ "gameControllerDisconnect"
+ "haptics"
+ "idleTimeout"
+ "nil"
+ "notifyWhenFinished"
+ "systemError"
+ "unknown("
```
