## SessionTrackerAppSettings

> `/System/Library/NanoPreferenceBundles/Applications/SessionTrackerAppSettings.bundle/SessionTrackerAppSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23294` | `0x23bb8` | **`+0x924`** |
| `__DATA_CONST.__cfstring` | `0x2aa0` | `0x2c00` | **`+0x160`** |
| `__TEXT.__cstring` | `0x3203` | `0x3323` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x4611` | `0x46d1` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x26a8` | `0x2760` | **`+0xb8`** |
| `__TEXT.__objc_methlist` | `0x1cac` | `0x1d5c` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x3c60` | `0x3ce0` | **`+0x80`** |
| `__TEXT.__dlopen_cstrs` | `0x54` | `0xa8` | **`+0x54`** |
| `__DATA.__objc_data` | `0x1418` | `0x1468` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x1380` | `0x13b8` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0x755` | `0x775` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xa10` | `0xa30` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xc0` | `0xd4` | **`+0x14`** |
| `__DATA.__bss` | `0x4e0` | `0x4f0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x12b8` | `0x12a8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x508` | `0x510` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x120` | `0x128` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x90` | `0x98` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x148` | `0x14c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2027.1.36.0.0
+2027.1.45.0.0

-  Functions: 924
-  Symbols:   433
-  CStrings:  1314
+  Functions: 940
+  Symbols:   435
+  CStrings:  1333
Symbols:
+ _FISetWorkoutGymKitDetectionMode
+ _FIWorkoutGymKitDetectionModeForPairedWatch
+ _OBJC_CLASS_$_HPRFSessionTrackerGymKitController
+ _OBJC_METACLASS_$_HPRFSessionTrackerGymKitController
+ _objc_retainAutorelease
- _FIUIIsWorkoutNFCAllDayEnabled
- _FIUISetWorkoutNFCAllDayEnabled
- _objc_retain_x9
CStrings:
+ " %@"
+ "HPRFSessionTrackerGymKitController"
+ "NFC_ALWAYS_ON_VALUE"
+ "NFC_DISABLED_PENDING_WATCH_UPDATE_FOOTER"
+ "NFC_DISABLED_VALUE"
+ "NFC_ENABLED_GROUP_ID"
+ "NFC_ENABLED_LABEL"
+ "NFC_MODE_ALWAYS_ON_ID"
+ "NFC_MODE_GROUP_ID"
+ "NFC_MODE_ON_WITH_WORKOUTS_ID"
+ "NFC_ON_WITH_WORKOUTS_VALUE"
+ "SessionTrackerGymKitSettings"
+ "_persistConnectedGymDetectionMode:"
+ "appendFormat:"
+ "connectedGymDetectionMode:"
+ "connectedGymDetectionModeValue:"
+ "f90f4d4f-f87c-41a0-b174-ad80e6d8214a"
+ "isConnectedGymDetectionEnabled:"
+ "numberWithInt:"
+ "selectConnectedGymDetectionModeSpecifier"
+ "setConnectedGymDetectionEnabled:specifier:"
+ "setConnectedGymDetectionMode:specifier:"
- "%@ %@"
- "NFCAlwaysOn:"
- "setNFCAlwaysOn:specifier:"
```
