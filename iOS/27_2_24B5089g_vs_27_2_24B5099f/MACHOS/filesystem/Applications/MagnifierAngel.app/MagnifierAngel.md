## MagnifierAngel

> `/Applications/MagnifierAngel.app/MagnifierAngel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x94e3c` | `0x998ec` | **`+0x4ab0`** |
| `__TEXT.__oslogstring` | `0x1fcd` | `0x215d` | **`+0x190`** |
| `__TEXT.__objc_methname` | `0x33f5` | `0x3565` | **`+0x170`** |
| `__TEXT.__objc_stubs` | `0x1460` | `0x1580` | **`+0x120`** |
| `__TEXT.__eh_frame` | `0x5acc` | `0x5bc4` | **`+0xf8`** |
| `__TEXT.__swift5_reflstr` | `0x1a59` | `0x1b39` | **`+0xe0`** |
| `__DATA.__objc_const` | `0x1fd8` | `0x2098` | **`+0xc0`** |
| `__DATA.__objc_data` | `0x1130` | `0x11c0` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x1434` | `0x14a4` | **`+0x70`** |
| `__DATA.__data` | `0x2b68` | `0x2bb8` | **`+0x50`** |
| `__TEXT.__const` | `0x3d84` | `0x3dd4` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2158` | `0x21a8` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x9b0` | `0x9f8` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x1080` | `0x10c8` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0xe00` | `0xe3c` | **`+0x3c`** |
| `__DATA_CONST.__const` | `0x2f88` | `0x2fb0` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x36f0` | `0x3710` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x7a2e` | `0x7a16` | **`-0x18`** |
| `__DATA.__bss` | `0x2cd8` | `0x2ce8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1b80` | `0x1b90` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x114d` | `0x115d` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xb00` | `0xb08` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1d4` | `0x1d8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x1ec` | `0x1f0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-291.4.2.0.0
+291.4.4.0.0

-  Functions: 2302
-  Symbols:   1494
-  CStrings:  910
+  Functions: 2319
+  Symbols:   1497
+  CStrings:  931
Symbols:
+ _$s16MagnifierSupport15MAGOutputEngineC24isAnnouncingImageCaptionSbvgTj
+ _$s16MagnifierSupport9DetectionV28sceneInterruptSampleIntervalSdvgZ
+ _OBJC_CLASS_$_AXLiveRecognitionAskParameters
CStrings:
+ "%s: Cannot start ARService. activeSessionPid=%d"
+ "%s: pid=%d released the camera. activeSessionPid=%d"
+ "%s: pid=%d took the camera. startedLiveRecognition=%{bool}d"
+ "Camera is held by pid=%d bundleIdentifier=%{public}s"
+ "Camera owner pid=%d is no longer scheduled. Clearing activeSessionPid"
+ "Camera was released before the warning could show. Will start ARService"
+ "Image descriptions: view changed mid-announcement; regenerating"
+ "ask"
+ "automaticCaptureEnabled"
+ "current"
+ "currentState"
+ "defaultQuestionText"
+ "imageCaptionTask"
+ "inFlightSceneFingerprint"
+ "interruptHashDistanceThreshold"
+ "interruptLuminanceThreshold"
+ "isActive"
+ "isAskOnly"
+ "isRunning"
+ "lastSceneInterruptCheckTime"
+ "pendingSceneInterruptFingerprint"
+ "preferredInputType"
+ "setLiveRecognitionAskSessionUsesActivity:"
+ "taskState"
+ "useDefaultQuestion"
+ "volumeButtonRecaptureEnabled"
- "%s: Cannot start ARService. activeSessionPid != 0"
- "liveRecognitionDefaultQuestionText"
- "liveRecognitionPreferredAskInputType"
- "liveRecognitionUseDefaultQuestion"
- "liveRecognitionVolumeButtonRecaptureEnabled"
```
