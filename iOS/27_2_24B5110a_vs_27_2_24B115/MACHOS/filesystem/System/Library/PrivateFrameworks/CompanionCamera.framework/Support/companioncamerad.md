## companioncamerad

> `/System/Library/PrivateFrameworks/CompanionCamera.framework/Support/companioncamerad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26f2c` | `0x27ac4` | **`+0xb98`** |
| `__TEXT.__cstring` | `0x1676` | `0x18e9` | **`+0x273`** |
| `__DATA_CONST.__cfstring` | `0x1100` | `0x1360` | **`+0x260`** |
| `__TEXT.__objc_stubs` | `0x2120` | `0x22a0` | **`+0x180`** |
| `__DATA.__objc_const` | `0x5408` | `0x5520` | **`+0x118`** |
| `__TEXT.__objc_methname` | `0x3e9e` | `0x3f68` | **`+0xca`** |
| `__DATA_CONST.__objc_intobj` | `0x18` | `0xc0` | **`+0xa8`** |
| `__TEXT.__gcc_except_tab` | `0xc4` | `0x164` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x34d4` | `0x3554` | **`+0x80`** |
| `__DATA_CONST.__const` | `0xca0` | `0xd18` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x10d8` | `0x1138` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x9a0` | `0x9f8` | **`+0x58`** |
| `__DATA.__objc_data` | `0xfa0` | `0xff0` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x847` | `0x891` | **`+0x4a`** |
| `__TEXT.__auth_stubs` | `0x740` | `0x780` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x139c` | `0x13ce` | **`+0x32`** |
| `__DATA_CONST.__got` | `0x130` | `0x158` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x3b0` | `0x3d0` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x569` | `0x57f` | **`+0x16`** |
| `__DATA.__bss` | `0x60` | `0x70` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2d8` | `0x2e8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x190` | `0x198` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x170` | `0x178` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-  Functions: 1127
-  Symbols:   167
-  CStrings:  1149
+  Functions: 1143
+  Symbols:   175
+  CStrings:  1192
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
+ "_checkForRepeatedEvent:"
+ "_checkForUnexpectedEvent:"
+ "_events"
+ "_log"
+ "_print"
+ "_printSource"
+ "_registerSources"
+ "_reset"
+ "_resetSource"
+ "appendString:"
+ "containsObject:"
+ "countForObject:"
+ "logEvent:"
+ "set"
+ "sharedInstance"
+ "string"
+ "v24@0:8q16"
```
