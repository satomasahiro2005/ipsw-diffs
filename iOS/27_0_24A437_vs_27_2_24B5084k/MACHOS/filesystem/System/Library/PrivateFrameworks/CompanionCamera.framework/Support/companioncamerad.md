## companioncamerad

> `/System/Library/PrivateFrameworks/CompanionCamera.framework/Support/companioncamerad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27c68` | `0x26f2c` | **`-0xd3c`** |
| `__DATA_CONST.__cfstring` | `0x13c0` | `0x1100` | **`-0x2c0`** |
| `__TEXT.__cstring` | `0x1934` | `0x1676` | **`-0x2be`** |
| `__TEXT.__objc_stubs` | `0x2320` | `0x2120` | **`-0x200`** |
| `__TEXT.__objc_methname` | `0x3ff2` | `0x3e9e` | **`-0x154`** |
| `__DATA.__objc_const` | `0x5550` | `0x5408` | **`-0x148`** |
| `__DATA_CONST.__objc_intobj` | `0xc0` | `0x18` | **`-0xa8`** |
| `__TEXT.__gcc_except_tab` | `0x164` | `0xc4` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x3574` | `0x34d4` | **`-0xa0`** |
| `__DATA.__objc_selrefs` | `0x1160` | `0x10d8` | **`-0x88`** |
| `__DATA_CONST.__const` | `0xd28` | `0xca0` | **`-0x88`** |
| `__TEXT.__unwind_info` | `0x9f8` | `0x9a0` | **`-0x58`** |
| `__DATA.__objc_data` | `0xff0` | `0xfa0` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x891` | `0x847` | **`-0x4a`** |
| `__TEXT.__auth_stubs` | `0x780` | `0x740` | **`-0x40`** |
| `__TEXT.__objc_methtype` | `0x13db` | `0x139c` | **`-0x3f`** |
| `__DATA_CONST.__got` | `0x160` | `0x130` | **`-0x30`** |
| `__DATA_CONST.__auth_got` | `0x3d0` | `0x3b0` | **`-0x20`** |
| `__TEXT.__objc_classname` | `0x57f` | `0x569` | **`-0x16`** |
| `__DATA.__objc_ivar` | `0x2ec` | `0x2d8` | **`-0x14`** |
| `__DATA.__bss` | `0x70` | `0x60` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x198` | `0x190` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x178` | `0x170` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-2024.100.18.0.0
+2024.200.2.0.0

-  Functions: 1146
-  Symbols:   176
-  CStrings:  1203
+  Functions: 1127
+  Symbols:   167
+  CStrings:  1149
Symbols:
- _CFPreferencesGetAppBooleanValue
- _OBJC_CLASS_$_NSCountedSet
- _OBJC_CLASS_$_NSMutableString
- _OBJC_CLASS_$_NSNotificationCenter
- __dispatch_main_q
- __dispatch_source_type_signal
- _objc_sync_enter
- _objc_sync_exit
- _signal
CStrings:
+ "@28@0:8q16i24"
+ "initWithCode:status:"
- "%@, date: %@"
- "%@: %lu\n"
- "@\"NSCountedSet\""
- "@\"NSDate\""
- "@\"NSObject<OS_os_log>\""
- "@36@0:8q16i24@28"
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
- "T@\"NSDate\",R,N,V_date"
- "Unexpected event: %@"
- "ViewfinderErrorReporterDidReportErrorNotification"
- "ViewfinderReliability"
- "ViewfinderReliability_CheckRepeatedEvents"
- "ViewfinderReliability_CheckUnexpectedEvents"
- "_checkForRepeatedEvent:"
- "_checkForUnexpectedEvent:"
- "_date"
- "_events"
- "_log"
- "_print"
- "_printSource"
- "_registerSources"
- "_reset"
- "_resetSource"
- "appendString:"
- "containsObject:"
- "countForObject:"
- "defaultCenter"
- "initWithCode:status:date:"
- "logEvent:"
- "now"
- "postNotificationName:object:userInfo:"
- "set"
- "sharedInstance"
- "string"
- "stringFromDate:"
- "ttrDescriptionWithDateFormatter:"
- "v24@0:8q16"
```
