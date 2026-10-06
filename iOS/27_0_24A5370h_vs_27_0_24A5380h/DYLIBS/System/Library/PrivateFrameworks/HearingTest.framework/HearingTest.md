## HearingTest

> `/System/Library/PrivateFrameworks/HearingTest.framework/HearingTest`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd0998` | `0xdc388` | **`+0xb9f0`** |
| `__TEXT.__oslogstring` | `0x7f61` | `0x8951` | **`+0x9f0`** |
| `__TEXT.__cstring` | `0x1ef2` | `0x2472` | **`+0x580`** |
| `__TEXT.__eh_frame` | `0x29ec` | `0x2f3c` | **`+0x550`** |
| `__AUTH_CONST.__const` | `0xcb84` | `0xcf94` | **`+0x410`** |
| `__TEXT.__const` | `0x4e20` | `0x5200` | **`+0x3e0`** |
| `__TEXT.__swift5_reflstr` | `0x2a87` | `0x2e07` | **`+0x380`** |
| `__AUTH.__objc_data` | `0x19e0` | `0x1c50` | **`+0x270`** |
| `__TEXT.__swift5_fieldmd` | `0x236c` | `0x25d4` | **`+0x268`** |
| `__TEXT.__constg_swiftt` | `0x2618` | `0x2814` | **`+0x1fc`** |
| `__AUTH_CONST.__objc_const` | `0x3e68` | `0x4058` | **`+0x1f0`** |
| `__TEXT.__unwind_info` | `0x1b88` | `0x1d68` | **`+0x1e0`** |
| `__DATA.__bss` | `0x4a80` | `0x4bf0` | **`+0x170`** |
| `__TEXT.__swift5_capture` | `0x28ec` | `0x29cc` | **`+0xe0`** |
| `__DATA.__data` | `0x1458` | `0x1518` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x1564` | `0x160e` | **`+0xaa`** |
| `__TEXT.__swift_as_cont` | `0x11c` | `0x188` | **`+0x6c`** |
| `__AUTH_CONST.__auth_got` | `0xdc8` | `0xdf8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x544` | `0x574` | **`+0x30`** |
| `__AUTH.__data` | `0x1f90` | `0x1fb0` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x58` | `0x74` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x80` | `0x94` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x1a4` | `0x1b4` | **`+0x10`** |
| `__DATA.__common` | `0x91` | `0x99` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xe0` | `0xe8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x680` | `0x688` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x268` | `0x270` | **`+0x8`** |

### Other Changes

```diff

-400.38.0.0.0
+400.39.0.0.0

-  Functions: 3741
-  Symbols:   1094
-  CStrings:  735
+  Functions: 3876
+  Symbols:   1126
+  CStrings:  814
Symbols:
+ _OBJC_CLASS_$_NSTimer
+ _OBJC_CLASS_$__TtC11HearingTest26KagraCLIReplacementManager
+ _OBJC_METACLASS_$__TtC11HearingTest26KagraCLIReplacementManager
+ __DATA__TtC11HearingTest26KagraCLIReplacementManager
+ __INSTANCE_METHODS__TtC11HearingTest26KagraCLIReplacementManager
+ __IVARS__TtC11HearingTest26KagraCLIReplacementManager
+ __METACLASS_DATA__TtC11HearingTest26KagraCLIReplacementManager
+ ___swift_memcpy114_8
+ ___swift_memcpy121_8
+ _get_enum_tag_for_layout_string 11HearingTest12KagraCommand33_7F31AA47CF9215F198953C6DA9C1783ELLO
+ _swift_deletedAsyncMethodErrorTu
+ _swift_getAtKeyPath
+ _swift_getKeyPath
+ _swift_readAtKeyPath
+ _swift_setAtWritableKeyPath
+ _symbolic Say_____G 11HearingTest12KagraCommand33_7F31AA47CF9215F198953C6DA9C1783ELLO
+ _symbolic ScCyyt______pG s5ErrorP
+ _symbolic So14NSUserDefaultsC
+ _symbolic So15NSRecursiveLockC
+ _symbolic So7NSTimerCSg
+ _symbolic _____ 11HearingTest12KagraCommand33_7F31AA47CF9215F198953C6DA9C1783ELLO
+ _symbolic _____ 11HearingTest18PlayToneParameters33_7F31AA47CF9215F198953C6DA9C1783ELLV
+ _symbolic _____ 11HearingTest26KagraCLIReplacementManagerC
+ _symbolic _____ 11HearingTest26KagraCLIReplacementManagerC12CachedValues33_7F31AA47CF9215F198953C6DA9C1783ELLV
+ _symbolic _____10parameters_t 11HearingTest18PlayToneParameters33_7F31AA47CF9215F198953C6DA9C1783ELLV
+ _symbolic _____Sg 11HearingTest12HTTonePlayerC
+ _symbolic _____SgXw 11HearingTest26KagraCLIReplacementManagerC
+ _symbolic _____XDXMT 11HearingTest26KagraCLIReplacementManagerC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11HearingTest12KagraCommand33_7F31AA47CF9215F198953C6DA9C1783ELLO
+ _type_layout_string 11HearingTest12KagraCommand33_7F31AA47CF9215F198953C6DA9C1783ELLO
+ _type_layout_string 11HearingTest18PlayToneParameters33_7F31AA47CF9215F198953C6DA9C1783ELLV
+ _type_layout_string 11HearingTest26KagraCLIReplacementManagerC12CachedValues33_7F31AA47CF9215F198953C6DA9C1783ELLV
CStrings:
+ " Hz is outside safe range (20-20000 Hz)"
+ " is outside safe range (0.0-1.0)"
+ " rear vent occluded"
+ ". Cannot select calibration table — using an incorrect table would produce wrong dBFS levels."
+ "HTKagraCLIReplacementEnabled"
+ "HearingTest/KagraCLIReplacementManager.swift"
+ "KagraHTModeStart"
+ "KagraPlayFrequency"
+ "KagraPlayNumberOfPulses"
+ "KagraPlayOccluded"
+ "KagraPlayPauseDuration"
+ "KagraPlayPilotDuration"
+ "KagraPlayPilotFrequency"
+ "KagraPlayPilotToneEnabled"
+ "KagraPlayPilotVolume"
+ "KagraPlayPulseDuration"
+ "KagraPlayStartDelay"
+ "KagraPlayTrigger"
+ "KagraPlaydBHLLevel"
+ "Pilot tone frequency "
+ "PilotToneEnabled"
+ "Play Tone (freq: "
+ "PlayNumberOfPulses"
+ "PlayPauseDuration"
+ "PlayPilotDuration"
+ "PlayPilotFrequency"
+ "PlayPulseDuration"
+ "Unknown headphone device: "
+ "[%{public}s] %s changed: %s -> %s"
+ "[%{public}s] Cached values initialized"
+ "[%{public}s] Command completed successfully: %s"
+ "[%{public}s] Command execution finished: %s"
+ "[%{public}s] Command failed: %s - Error: %@"
+ "[%{public}s] Command queue is empty, no processing needed"
+ "[%{public}s] Command queue processing already in progress"
+ "[%{public}s] Command queue processing completed - all commands executed"
+ "[%{public}s] Enqueued %ld command(s). Queue size: %ld"
+ "[%{public}s] Enqueued command: %s"
+ "[%{public}s] Executing HTMode start command"
+ "[%{public}s] Executing HTMode stop command"
+ "[%{public}s] Executing Play command with parameters - freq: %f, device: %s"
+ "[%{public}s] Executing command: %s"
+ "[%{public}s] HTMode Start changed: %{bool}d -> %{bool}d"
+ "[%{public}s] HTMode started successfully"
+ "[%{public}s] HTMode stopped successfully"
+ "[%{public}s] Initial KagraHTModeStart: %{bool}d"
+ "[%{public}s] Initial KagraPlayTrigger: %{bool}d"
+ "[%{public}s] KagraCLIReplacementManager deinitialized"
+ "[%{public}s] KagraCLIReplacementManager initialized for CLI replacement functionality"
+ "[%{public}s] KagraCLIReplacementManager initialized with timer-based polling"
+ "[%{public}s] Main tone playback completed"
+ "[%{public}s] Pilot tone playback completed"
+ "[%{public}s] Pilot tone playback completed successfully"
+ "[%{public}s] Pilot tone playback disabled via parameters"
+ "[%{public}s] Pilot tone playback failed: %@"
+ "[%{public}s] Play Trigger changed: %{bool}d -> %{bool}d"
+ "[%{public}s] Playing main tone - freq: %f, level: %f"
+ "[%{public}s] Playing pilot tone at %f Hz on main thread"
+ "[%{public}s] Polling already active"
+ "[%{public}s] Polling already inactive"
+ "[%{public}s] Processing command: %s - %ld remaining"
+ "[%{public}s] Reset KagraPlayTrigger to false"
+ "[%{public}s] Starting command queue processing with %ld command(s)"
+ "[%{public}s] Starting main tone playback"
+ "[%{public}s] Starting pilot tone playback"
+ "[%{public}s] Starting timer-based UserDefaults polling with interval: %fs"
+ "[%{public}s] Starting tone sequence with dBFS: %f"
+ "[%{public}s] Stopping timer-based UserDefaults polling"
+ "[%{public}s] Timer-based polling started successfully"
+ "[%{public}s] Timer-based polling stopped"
+ "[%{public}s] Tone sequence completed successfully"
+ "[%{public}s] Using %s%s table"
+ "com.apple.HearingTest.CommandExecution"
+ "com.apple.HearingTest.KagraCLIReplacementManager"
+ "com.apple.HearingTest.PilotTone"
+ "com.apple.UIKit"
+ "com.apple.iOS"
+ "playMainTone(audioDeviceTest:frequency:dBFSLevel:side:numberOfPulses:pulseDuration:pauseDuration:volume:)"
+ "playPilotTone(audioDeviceTest:device:pilotVolume:pilotDuration:pilotFrequency:startDelay:volume:occluded:)"
```
