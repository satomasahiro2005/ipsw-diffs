## FitnessSettings

> `/System/Library/PreferenceBundles/FitnessSettings.bundle/FitnessSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e6a4` | `0x21750` | **`+0x30ac`** |
| `__TEXT.__swift5_typeref` | `0x2181` | `0x2b89` | **`+0xa08`** |
| `__TEXT.__const` | `0x12c2` | `0x1592` | **`+0x2d0`** |
| `__DATA.__data` | `0x1178` | `0x13d8` | **`+0x260`** |
| `__DATA.__bss` | `0x910` | `0xac0` | **`+0x1b0`** |
| `__TEXT.__cstring` | `0x76c` | `0x88c` | **`+0x120`** |
| `__TEXT.__constg_swiftt` | `0x6b0` | `0x794` | **`+0xe4`** |
| `__TEXT.__auth_stubs` | `0x1680` | `0x1750` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x840` | `0x8b8` | **`+0x78`** |
| `__DATA_CONST.__auth_got` | `0xb48` | `0xbb0` | **`+0x68`** |
| `__DATA_CONST.__auth_ptr` | `0x540` | `0x5a0` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x3e0` | `0x430` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xd98` | `0xde0` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x6f8` | `0x6c8` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `0x140` | `0x170` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x3b0` | `0x3d8` | **`+0x28`** |
| `__DATA.__objc_const` | `0x630` | `0x650` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xa16` | `0xa36` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x464` | `0x478` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0x5a2` | `0x5b2` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x40` | `0x4c` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x44` | `0x4c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.1.36.0.0
+2027.1.45.0.0

-  Functions: 695
-  Symbols:   221
-  CStrings:  214
+  Functions: 759
+  Symbols:   226
+  CStrings:  222
Symbols:
+ _FISetWorkoutGymKitDetectionMode
+ _FIWorkoutGymKitDetectionIsMutedToday
+ _FIWorkoutGymKitDetectionMode
+ _FIWorkoutGymKitDetectionSetMutedForToday
+ _swift_retain_x24
+ _swift_retain_x27
+ _swift_retain_x28
- _FIUIIsWorkoutNFCAllDayEnabled
- _FIUISetWorkoutNFCAllDayEnabled
CStrings:
+ "GYMKIT_ALWAYS_ALLOW"
+ "GYMKIT_DETECT_EQUIPMENT_ALWAYS_ON"
+ "GYMKIT_DETECT_EQUIPMENT_DISABLED"
+ "GYMKIT_DETECT_EQUIPMENT_MUTED_DESCRIPTION"
+ "GYMKIT_DETECT_EQUIPMENT_ON_WITH_WORKOUTS"
+ "GYMKIT_ONLY_IN_FITNESS_APP"
+ "_isGymKitMutedToday"
+ "_storedGymKitDetectionMode"
+ "gymkit-detection"
- "_detectGymEquipment"
```
