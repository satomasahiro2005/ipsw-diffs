## CompanionCamera

> `/System/Library/PrivateFrameworks/CompanionCamera.framework/CompanionCamera`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9a14` | `0x8d00` | **`-0xd14`** |
| `__AUTH_CONST.__cfstring` | `0xa00` | `0x720` | **`-0x2e0`** |
| `__TEXT.__cstring` | `0xfc7` | `0xd07` | **`-0x2c0`** |
| `__AUTH_CONST.__objc_const` | `0xbd8` | `0xa90` | **`-0x148`** |
| `__AUTH_CONST.__objc_intobj` | `0xf0` | `0x48` | **`-0xa8`** |
| `__TEXT.__gcc_except_tab` | `0x118` | `0x78` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0xbdc` | `0xb3c` | **`-0xa0`** |
| `__DATA_CONST.__const` | `0x478` | `0x3f0` | **`-0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x898` | `0x810` | **`-0x88`** |
| `__TEXT.__unwind_info` | `0x2b8` | `0x258` | **`-0x60`** |
| `__DATA_DIRTY.__objc_data` | `0x140` | `0xf0` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x60b` | `0x5c1` | **`-0x4a`** |
| `__DATA_CONST.__got` | `0xd0` | `0xa8` | **`-0x28`** |
| `__DATA.__objc_ivar` | `0x8c` | `0x78` | **`-0x14`** |
| `__DATA_DIRTY.__bss` | `0x40` | `0x30` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x28` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x20` | `0x18` | **`-0x8`** |

### Other Changes

```diff

-2024.100.18.0.0
+2024.200.2.0.0

-  Functions: 272
-  Symbols:   493
-  CStrings:  167
+  Functions: 253
+  Symbols:   448
+  CStrings:  139
Symbols:
+ -[ViewfinderErrorReport initWithCode:status:]
- +[ViewfinderReliability sharedInstance]
- -[ViewfinderErrorReport .cxx_destruct]
- -[ViewfinderErrorReport date]
- -[ViewfinderErrorReport initWithCode:status:date:]
- -[ViewfinderErrorReport ttrDescriptionWithDateFormatter:]
- -[ViewfinderReliability .cxx_destruct]
- -[ViewfinderReliability _checkForRepeatedEvent:]
- -[ViewfinderReliability _checkForUnexpectedEvent:]
- -[ViewfinderReliability _print]
- -[ViewfinderReliability _registerSources]
- -[ViewfinderReliability _reset]
- -[ViewfinderReliability init]
- -[ViewfinderReliability logEvent:]
- GCC_except_table3
- GCC_except_table5
- GCC_except_table8
- GCC_except_table9
- _CFPreferencesGetAppBooleanValue
- _NSStringFromViewfinderReliabiliyEvent
- _OBJC_CLASS_$_NSCountedSet
- _OBJC_CLASS_$_NSMutableString
- _OBJC_CLASS_$_NSNotificationCenter
- _OBJC_CLASS_$_ViewfinderReliability
- _OBJC_IVAR_$_ViewfinderErrorReport._date
- _OBJC_IVAR_$_ViewfinderReliability._events
- _OBJC_IVAR_$_ViewfinderReliability._log
- _OBJC_IVAR_$_ViewfinderReliability._printSource
- _OBJC_IVAR_$_ViewfinderReliability._resetSource
- _OBJC_METACLASS_$_ViewfinderReliability
- _ViewfinderErrorReportKey
- _ViewfinderErrorReporterDidReportErrorNotification
- __OBJC_$_CLASS_METHODS_ViewfinderReliability
- __OBJC_$_INSTANCE_METHODS_ViewfinderReliability
- __OBJC_$_INSTANCE_VARIABLES_ViewfinderReliability
- __OBJC_CLASS_RO_$_ViewfinderReliability
- __OBJC_METACLASS_RO_$_ViewfinderReliability
- ___39+[ViewfinderReliability sharedInstance]_block_invoke
- ___41-[ViewfinderReliability _registerSources]_block_invoke
- ___41-[ViewfinderReliability _registerSources]_block_invoke_2
- __dispatch_source_type_signal
- __os_log_fault_impl
- _objc_enumerationMutation
- _objc_sync_enter
- _objc_sync_exit
- _os_variant_has_internal_diagnostics
- _signal
CStrings:
- "!"
- "%@, date: %@"
- "%@: %lu\n"
- "CameraAppLaunch"
- "CameraAppLaunchFailed"
- "CameraAppLaunchhSucceeded"
- "CameraPreviewIDSSocketCreationFailed"
- "CloseCameraMessageReceived"
- "Count of events:\n%@"
- "DaemonXPCConnectionInterruption"
- "DaemonXPCConnectionInvalidation"
- "DaemonXPCConnectionReceived"
- "ErrorReport"
- "FigCameraViewfinderCreation"
- "FigCameraViewfinderSessionDidBegin"
- "FigCameraViewfinderSessionDidEnd"
- "FigCameraViewfinderSessionOpenPreviewStream"
- "FigCameraViewfinderSessionPreviewStreamDidClose"
- "FigCameraViewfinderSessionPreviewStreamDidOpen"
- "FigCameraViewfinderStarted"
- "OpenCameraMessageReceived"
- "Repeated event: %@"
- "Reset events."
- "Unexpected event: %@"
- "ViewfinderErrorReporterDidReportErrorNotification"
- "ViewfinderReliability"
- "ViewfinderReliability_CheckRepeatedEvents"
- "ViewfinderReliability_CheckUnexpectedEvents"
```
