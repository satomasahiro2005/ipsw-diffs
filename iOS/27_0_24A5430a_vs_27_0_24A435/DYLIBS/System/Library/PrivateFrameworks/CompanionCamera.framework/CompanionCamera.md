## CompanionCamera

> `/System/Library/PrivateFrameworks/CompanionCamera.framework/CompanionCamera`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80c8` | `0x9a14` | **`+0x194c`** |
| `__TEXT.__cstring` | `0xb61` | `0xfc7` | **`+0x466`** |
| `__AUTH_CONST.__cfstring` | `0x780` | `0xa00` | **`+0x280`** |
| `__TEXT.__objc_methlist` | `0xa54` | `0xbdc` | **`+0x188`** |
| `__AUTH_CONST.__objc_const` | `0xa60` | `0xbd8` | **`+0x178`** |
| `__DATA_CONST.__objc_selrefs` | `0x770` | `0x898` | **`+0x128`** |
| `__TEXT.__oslogstring` | `0x53b` | `0x60b` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x3a0` | `0x460` | **`+0xc0`** |
| `__AUTH_CONST.__objc_intobj` | `0x48` | `0xf0` | **`+0xa8`** |
| `__TEXT.__gcc_except_tab` | `0x78` | `0x118` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x238` | `0x2b8` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x400` | `0x478` | **`+0x78`** |
| `__DATA_DIRTY.__objc_data` | `0xf0` | `0x140` | **`+0x50`** |
| `__DATA_CONST.__got` | `0xb0` | `0xd0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x78` | `0x8c` | **`+0x14`** |
| `__DATA_DIRTY.__bss` | `0x30` | `0x40` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x20` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 233
-  Symbols:   429
-  CStrings:  135
+  Functions: 272
+  Symbols:   493
+  CStrings:  167
Symbols:
+ +[ViewfinderReliability sharedInstance]
+ -[CCCameraConnection _personalPhotographerMode]
+ -[CCCameraConnection _personalPhotographerSessionTimerState]
+ -[CCCameraConnection _personalPhotographerStatus]
+ -[CCCameraConnection _personalPhotographerSupport]
+ -[CCCameraConnection didStopPersonalPhotographerCapture]
+ -[CCCameraConnection personalPhotographerModeDidChange:]
+ -[CCCameraConnection personalPhotographerSessionTimerStateDidChange:]
+ -[CCCameraConnection personalPhotographerStatusDidChange:]
+ -[CCCameraConnection personalPhotographerSupportDidChange:]
+ -[CCCameraConnection willStartPersonalPhotographerCapture]
+ -[CCCameraConnection xpc_startPersonalPhotographerSessionWithReply:]
+ -[CCCameraConnection xpc_stopPersonalPhotographerSessionWithReply:]
+ -[CCCameraConnectionInternal xpc_startPersonalPhotographerSessionWithReply:]
+ -[CCCameraConnectionInternal xpc_stopPersonalPhotographerSessionWithReply:]
+ -[ViewfinderReliability .cxx_destruct]
+ -[ViewfinderReliability _checkForRepeatedEvent:]
+ -[ViewfinderReliability _checkForUnexpectedEvent:]
+ -[ViewfinderReliability _print]
+ -[ViewfinderReliability _registerSources]
+ -[ViewfinderReliability _reset]
+ -[ViewfinderReliability init]
+ -[ViewfinderReliability logEvent:]
+ GCC_except_table3
+ GCC_except_table5
+ GCC_except_table8
+ GCC_except_table9
+ _CFPreferencesGetAppBooleanValue
+ _NCPersonalPhotographerModeFromCCPersonalPhotographerMode
+ _NCPersonalPhotographerSessionTimerStateFromCCPersonalPhotographerSessionTimerState
+ _NCPersonalPhotographerStatusFromCCPersonalPhotographerStatus
+ _NCPersonalPhotographerSupportFromCCPersonalPhotographerSupport
+ _NSStringFromViewfinderReliabiliyEvent
+ _OBJC_CLASS_$_NSCountedSet
+ _OBJC_CLASS_$_NSMutableString
+ _OBJC_CLASS_$_ViewfinderReliability
+ _OBJC_IVAR_$_CCCameraConnection._capturingPersonalPhotographer
+ _OBJC_IVAR_$_ViewfinderReliability._events
+ _OBJC_IVAR_$_ViewfinderReliability._log
+ _OBJC_IVAR_$_ViewfinderReliability._printSource
+ _OBJC_IVAR_$_ViewfinderReliability._resetSource
+ _OBJC_METACLASS_$_ViewfinderReliability
+ __OBJC_$_CLASS_METHODS_ViewfinderReliability
+ __OBJC_$_INSTANCE_METHODS_ViewfinderReliability
+ __OBJC_$_INSTANCE_VARIABLES_ViewfinderReliability
+ __OBJC_CLASS_RO_$_ViewfinderReliability
+ __OBJC_METACLASS_RO_$_ViewfinderReliability
+ ___39+[ViewfinderReliability sharedInstance]_block_invoke
+ ___41-[ViewfinderReliability _registerSources]_block_invoke
+ ___41-[ViewfinderReliability _registerSources]_block_invoke_2
+ ___56-[CCCameraConnection didStopPersonalPhotographerCapture]_block_invoke
+ ___56-[CCCameraConnection personalPhotographerModeDidChange:]_block_invoke
+ ___58-[CCCameraConnection personalPhotographerStatusDidChange:]_block_invoke
+ ___58-[CCCameraConnection willStartPersonalPhotographerCapture]_block_invoke
+ ___59-[CCCameraConnection personalPhotographerSupportDidChange:]_block_invoke
+ ___67-[CCCameraConnection xpc_stopPersonalPhotographerSessionWithReply:]_block_invoke
+ ___68-[CCCameraConnection xpc_startPersonalPhotographerSessionWithReply:]_block_invoke
+ ___69-[CCCameraConnection personalPhotographerSessionTimerStateDidChange:]_block_invoke
+ __dispatch_source_type_signal
+ __os_log_fault_impl
+ _objc_enumerationMutation
+ _objc_sync_enter
+ _objc_sync_exit
+ _os_variant_has_internal_diagnostics
+ _signal
- _objc_release_x24
CStrings:
+ "%@: %lu\n"
+ "-[CCCameraConnection didStopPersonalPhotographerCapture]"
+ "-[CCCameraConnection personalPhotographerModeDidChange:]"
+ "-[CCCameraConnection personalPhotographerSessionTimerStateDidChange:]"
+ "-[CCCameraConnection personalPhotographerStatusDidChange:]"
+ "-[CCCameraConnection personalPhotographerSupportDidChange:]"
+ "-[CCCameraConnection willStartPersonalPhotographerCapture]"
+ "-[CCCameraConnection xpc_startPersonalPhotographerSessionWithReply:]"
+ "-[CCCameraConnection xpc_stopPersonalPhotographerSessionWithReply:]"
+ "CameraAppLaunch"
+ "CameraAppLaunchFailed"
+ "CameraAppLaunchhSucceeded"
+ "CameraPreviewIDSSocketCreationFailed"
+ "CloseCameraMessageReceived"
+ "Count of events:\n%@"
+ "DaemonXPCConnectionInterruption"
+ "DaemonXPCConnectionInvalidation"
+ "DaemonXPCConnectionReceived"
+ "FigCameraViewfinderCreation"
+ "FigCameraViewfinderSessionDidBegin"
+ "FigCameraViewfinderSessionDidEnd"
+ "FigCameraViewfinderSessionOpenPreviewStream"
+ "FigCameraViewfinderSessionPreviewStreamDidClose"
+ "FigCameraViewfinderSessionPreviewStreamDidOpen"
+ "FigCameraViewfinderStarted"
+ "OpenCameraMessageReceived"
+ "Repeated event: %@"
+ "Reset events."
+ "Unexpected event: %@"
+ "ViewfinderReliability"
+ "ViewfinderReliability_CheckRepeatedEvents"
+ "ViewfinderReliability_CheckUnexpectedEvents"
+ "supportedCaptureDevices:%@ captureDevice:%@ supportedCaptureModes:%@ captureMode:%@ capturing:%d captureStartDate:%@ capturingPaused:%d capturePauseDate:%@ orientation:%@ toggleCameraDeviceSupport:%d zoomSupport:%d zoomAmount:%f zoomMagnificationSupport:%d minimumZoomMagnification:%f maximumZoomMagnification:%f significantZoomMagnifications:%@ currentZoomMagnification:%f flashSupport:%@ flashMode:%@ hdrSupport:%@ hdrMode:%@ irisSupport:%@ irisMode:%@ sharedLibrarySupport:%@ sharedLibraryMode:%@ supportsMomentCapture:%d burstSupport:%d viewfinderSessionState:%lu shallowDepthOfFieldStatus:%@ stereoCaptureStatus:%@ personalPhotographerSupport:%ld personalPhotographerMode:%ld personalPhotographerStatus:%ld personalPhotographerSessionTimerState:%ld"
+ "\xf0Q"
- "supportedCaptureDevices:%@ captureDevice:%@ supportedCaptureModes:%@ captureMode:%@ capturing:%d captureStartDate:%@ capturingPaused:%d capturePauseDate:%@ orientation:%@ toggleCameraDeviceSupport:%d zoomSupport:%d zoomAmount:%f zoomMagnificationSupport:%d minimumZoomMagnification:%f maximumZoomMagnification:%f significantZoomMagnifications:%@ currentZoomMagnification:%f flashSupport:%@ flashMode:%@ hdrSupport:%@ hdrMode:%@ irisSupport:%@ irisMode:%@ sharedLibrarySupport:%@ sharedLibraryMode:%@ supportsMomentCapture:%d burstSupport:%d viewfinderSessionState:%lu shallowDepthOfFieldStatus:%@ stereoCaptureStatus:%@"
- "\xf0A"
```
