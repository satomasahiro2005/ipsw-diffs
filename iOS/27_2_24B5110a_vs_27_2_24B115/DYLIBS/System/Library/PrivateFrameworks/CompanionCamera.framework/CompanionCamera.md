## CompanionCamera

> `/System/Library/PrivateFrameworks/CompanionCamera.framework/CompanionCamera`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8d00` | `0x9870` | **`+0xb70`** |
| `__AUTH_CONST.__cfstring` | `0x720` | `0x9a0` | **`+0x280`** |
| `__TEXT.__cstring` | `0xd07` | `0xf7a` | **`+0x273`** |
| `__AUTH_CONST.__objc_const` | `0xa90` | `0xba8` | **`+0x118`** |
| `__AUTH_CONST.__objc_intobj` | `0x48` | `0xf0` | **`+0xa8`** |
| `__TEXT.__gcc_except_tab` | `0x78` | `0x118` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0xb3c` | `0xbbc` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x3f0` | `0x468` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x810` | `0x878` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x258` | `0x2b8` | **`+0x60`** |
| `__DATA_DIRTY.__objc_data` | `0x190` | `0x1e0` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x5c1` | `0x60b` | **`+0x4a`** |
| `__DATA_CONST.__got` | `0xa8` | `0xc8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x78` | `0x88` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x40` | `0x50` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x20` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 253
-  Symbols:   448
-  CStrings:  139
+  Functions: 269
+  Symbols:   486
+  CStrings:  163
Symbols:
+ +[ViewfinderReliability sharedInstance]
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
+ _NSStringFromViewfinderReliabiliyEvent
+ _OBJC_CLASS_$_NSCountedSet
+ _OBJC_CLASS_$_NSMutableString
+ _OBJC_CLASS_$_ViewfinderReliability
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
+ __dispatch_source_type_signal
+ __os_log_fault_impl
+ _objc_enumerationMutation
+ _objc_sync_enter
+ _objc_sync_exit
+ _os_variant_has_internal_diagnostics
+ _signal
CStrings:
+ "%@: %lu\n"
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
```
