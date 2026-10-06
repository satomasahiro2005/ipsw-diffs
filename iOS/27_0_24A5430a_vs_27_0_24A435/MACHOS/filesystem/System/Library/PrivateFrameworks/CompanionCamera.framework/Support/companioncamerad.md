## companioncamerad

> `/System/Library/PrivateFrameworks/CompanionCamera.framework/Support/companioncamerad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24064` | `0x27c68` | **`+0x3c04`** |
| `__TEXT.__objc_methname` | `0x3870` | `0x3ff2` | **`+0x782`** |
| `__DATA.__objc_const` | `0x4df8` | `0x5550` | **`+0x758`** |
| `__TEXT.__objc_methlist` | `0x30a4` | `0x3574` | **`+0x4d0`** |
| `__TEXT.__cstring` | `0x14e8` | `0x1934` | **`+0x44c`** |
| `__DATA_CONST.__cfstring` | `0x1020` | `0x13c0` | **`+0x3a0`** |
| `__TEXT.__objc_stubs` | `0x20c0` | `0x2320` | **`+0x260`** |
| `__DATA.__objc_data` | `0xe60` | `0xff0` | **`+0x190`** |
| `__DATA.__objc_selrefs` | `0xfd0` | `0x1160` | **`+0x190`** |
| `__TEXT.__unwind_info` | `0x8f0` | `0x9f8` | **`+0x108`** |
| `__TEXT.__objc_methtype` | `0x1301` | `0x13db` | **`+0xda`** |
| `__TEXT.__oslogstring` | `0x7bd` | `0x891` | **`+0xd4`** |
| `__TEXT.__objc_classname` | `0x4c1` | `0x57f` | **`+0xbe`** |
| `__DATA_CONST.__const` | `0xc78` | `0xd28` | **`+0xb0`** |
| `__DATA_CONST.__objc_intobj` | `0x18` | `0xc0` | **`+0xa8`** |
| `__TEXT.__gcc_except_tab` | `0xc4` | `0x164` | **`+0xa0`** |
| `__DATA.__objc_ivar` | `0x2a4` | `0x2ec` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x740` | `0x780` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x138` | `0x160` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x170` | `0x198` | **`+0x28`** |
| `__DATA_CONST.__objc_superrefs` | `0x150` | `0x178` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x3b0` | `0x3d0` | **`+0x20`** |
| `__DATA.__bss` | `0x60` | `0x70` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-  Functions: 1041
-  Symbols:   168
-  CStrings:  1095
+  Functions: 1146
+  Symbols:   176
+  CStrings:  1203
Symbols:
+ _CFPreferencesGetAppBooleanValue
+ _OBJC_CLASS_$_NSCountedSet
+ _OBJC_CLASS_$_NSMutableString
+ __dispatch_main_q
+ __dispatch_source_type_signal
+ _objc_sync_enter
+ _objc_sync_exit
+ _signal
CStrings:
+ "%@: %lu\n"
+ "-[NCCompanionCamera startPersonalPhotographerCapture:]"
+ "-[NCCompanionCamera stopPersonalPhotographerCapture:]"
+ "-[NCCompanionCamera xpc_didStopPersonalPhotographerCapture]"
+ "-[NCCompanionCamera xpc_willStartPersonalPhotographerCapture]"
+ "@\"NSCountedSet\""
+ "@\"NSObject<OS_os_log>\""
+ "CameraAppLaunch"
+ "CameraAppLaunchFailed"
+ "CameraAppLaunchhSucceeded"
+ "CameraPreviewIDSSocketCreationFailed"
+ "CloseCameraMessageReceived"
+ "Count of events:\n%@"
+ "DaemonXPCConnectionInterruption"
+ "DaemonXPCConnectionInvalidation"
+ "DaemonXPCConnectionReceived"
+ "DeviceLowStorageSpace"
+ "EndingSoon"
+ "FigCameraViewfinderCreation"
+ "FigCameraViewfinderSessionDidBegin"
+ "FigCameraViewfinderSessionDidEnd"
+ "FigCameraViewfinderSessionOpenPreviewStream"
+ "FigCameraViewfinderSessionPreviewStreamDidClose"
+ "FigCameraViewfinderSessionPreviewStreamDidOpen"
+ "FigCameraViewfinderStarted"
+ "NCStartPersonalPhotographerCaptureRequest"
+ "NCStartPersonalPhotographerCaptureResponse"
+ "NCStopPersonalPhotographerCaptureRequest"
+ "NCStopPersonalPhotographerCaptureResponse"
+ "NoSubjectDetected"
+ "Normal"
+ "OpenCameraMessageReceived"
+ "Repeated event: %@"
+ "Reset events."
+ "StringAsPersonalPhotographerMode:"
+ "StringAsPersonalPhotographerSessionTimerState:"
+ "StringAsPersonalPhotographerStatus:"
+ "StringAsPersonalPhotographerSupport:"
+ "SubjectDetected"
+ "TB,N,V_capturingPersonalPhotographer"
+ "Ti,N,V_personalPhotographerMode"
+ "Ti,N,V_personalPhotographerSessionTimerState"
+ "Ti,N,V_personalPhotographerStatus"
+ "Ti,N,V_personalPhotographerSupport"
+ "Unexpected event: %@"
+ "ViewfinderReliability"
+ "ViewfinderReliability_CheckRepeatedEvents"
+ "ViewfinderReliability_CheckUnexpectedEvents"
+ "Vv28@0:8B16@?<v@?@\"NSOrderedSet\"q@\"NSOrderedSet\"qB@\"NSDate\"B@\"NSDate\"qBBfBff@\"NSArray\"fqqqqqqqqBBQqqqqqqB>20"
+ "_capturingPersonalPhotographer"
+ "_checkForRepeatedEvent:"
+ "_checkForUnexpectedEvent:"
+ "_events"
+ "_log"
+ "_personalPhotographerMode"
+ "_personalPhotographerSessionTimerState"
+ "_personalPhotographerStatus"
+ "_personalPhotographerSupport"
+ "_print"
+ "_printSource"
+ "_registerSources"
+ "_reset"
+ "_resetSource"
+ "appendString:"
+ "capturingPersonalPhotographer"
+ "containsObject:"
+ "countForObject:"
+ "hasCapturingPersonalPhotographer"
+ "hasPersonalPhotographerMode"
+ "hasPersonalPhotographerSessionTimerState"
+ "hasPersonalPhotographerStatus"
+ "hasPersonalPhotographerSupport"
+ "logEvent:"
+ "personalPhotographerMode"
+ "personalPhotographerMode: %ld"
+ "personalPhotographerModeAsString:"
+ "personalPhotographerSessionTimerState"
+ "personalPhotographerSessionTimerState: %ld"
+ "personalPhotographerSessionTimerStateAsString:"
+ "personalPhotographerStatus"
+ "personalPhotographerStatus: %ld"
+ "personalPhotographerStatusAsString:"
+ "personalPhotographerSupport"
+ "personalPhotographerSupport: %ld"
+ "personalPhotographerSupportAsString:"
+ "set"
+ "setCapturingPersonalPhotographer:"
+ "setHasCapturingPersonalPhotographer:"
+ "setHasPersonalPhotographerMode:"
+ "setHasPersonalPhotographerSessionTimerState:"
+ "setHasPersonalPhotographerStatus:"
+ "setHasPersonalPhotographerSupport:"
+ "setPersonalPhotographerMode:"
+ "setPersonalPhotographerSessionTimerState:"
+ "setPersonalPhotographerStatus:"
+ "setPersonalPhotographerSupport:"
+ "sharedInstance"
+ "startPersonalPhotographerCapture:"
+ "stopPersonalPhotographerCapture:"
+ "string"
+ "v240@?0@\"NSOrderedSet\"8q16@\"NSOrderedSet\"24q32B40@\"NSDate\"44B52@\"NSDate\"56q64B72B76f80B84f88f92@\"NSArray\"96f104q108q116q124q132q140q148q156q164B172B176Q180q188q196q204q212q220q228B236"
+ "v24@0:8q16"
+ "xpc_didStopPersonalPhotographerCapture"
+ "xpc_personalPhotographerModeDidChange:"
+ "xpc_personalPhotographerSessionTimerStateDidChange:"
+ "xpc_personalPhotographerStatusDidChange:"
+ "xpc_personalPhotographerSupportDidChange:"
+ "xpc_startPersonalPhotographerSessionWithReply:"
+ "xpc_stopPersonalPhotographerSessionWithReply:"
+ "xpc_willStartPersonalPhotographerCapture"
+ "{?=\"capturePauseDate\"b1\"captureStartDate\"b1\"captureDevice\"b1\"captureMode\"b1\"currentZoomMagnification\"b1\"flashMode\"b1\"flashSupport\"b1\"hdrMode\"b1\"hdrSupport\"b1\"irisMode\"b1\"irisSupport\"b1\"maximumZoomMagnification\"b1\"minimumZoomMagnification\"b1\"orientation\"b1\"personalPhotographerMode\"b1\"personalPhotographerSessionTimerState\"b1\"personalPhotographerStatus\"b1\"personalPhotographerSupport\"b1\"shallowDepthOfFieldStatus\"b1\"sharedLibraryMode\"b1\"sharedLibrarySupport\"b1\"stereoCaptureStatus\"b1\"zoomAmount\"b1\"burstSupport\"b1\"capturing\"b1\"capturingPaused\"b1\"capturingPersonalPhotographer\"b1\"isSpatialCapture\"b1\"supportsMomentCapture\"b1\"toggleCameraDeviceSupport\"b1\"viewfinderSessionActive\"b1\"zoomMagnificationSupport\"b1\"zoomSupport\"b1}"
- "Vv28@0:8B16@?<v@?@\"NSOrderedSet\"q@\"NSOrderedSet\"qB@\"NSDate\"B@\"NSDate\"qBBfBff@\"NSArray\"fqqqqqqqqBBQqq>20"
- "v204@?0@\"NSOrderedSet\"8q16@\"NSOrderedSet\"24q32B40@\"NSDate\"44B52@\"NSDate\"56q64B72B76f80B84f88f92@\"NSArray\"96f104q108q116q124q132q140q148q156q164B172B176Q180q188q196"
- "{?=\"capturePauseDate\"b1\"captureStartDate\"b1\"captureDevice\"b1\"captureMode\"b1\"currentZoomMagnification\"b1\"flashMode\"b1\"flashSupport\"b1\"hdrMode\"b1\"hdrSupport\"b1\"irisMode\"b1\"irisSupport\"b1\"maximumZoomMagnification\"b1\"minimumZoomMagnification\"b1\"orientation\"b1\"shallowDepthOfFieldStatus\"b1\"sharedLibraryMode\"b1\"sharedLibrarySupport\"b1\"stereoCaptureStatus\"b1\"zoomAmount\"b1\"burstSupport\"b1\"capturing\"b1\"capturingPaused\"b1\"isSpatialCapture\"b1\"supportsMomentCapture\"b1\"toggleCameraDeviceSupport\"b1\"viewfinderSessionActive\"b1\"zoomMagnificationSupport\"b1\"zoomSupport\"b1}"
```
