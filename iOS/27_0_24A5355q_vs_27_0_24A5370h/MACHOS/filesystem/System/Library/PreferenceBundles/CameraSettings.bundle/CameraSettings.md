## CameraSettings

> `/System/Library/PreferenceBundles/CameraSettings.bundle/CameraSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3adb0` | `0x39514` | **`-0x189c`** |
| `__TEXT.__swift5_typeref` | `0x74ba` | `0x6312` | **`-0x11a8`** |
| `__TEXT.__objc_stubs` | `0x3640` | `0x3740` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x18f0` | `0x1800` | **`-0xf0`** |
| `__TEXT.__eh_frame` | `0xf4c` | `0xe84` | **`-0xc8`** |
| `__DATA.__data` | `0x1108` | `0x1050` | **`-0xb8`** |
| `__TEXT.__objc_methname` | `0x41e7` | `0x4267` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x35c` | `0x2e8` | **`-0x74`** |
| `__DATA.__bss` | `0xd30` | `0xda0` | **`+0x70`** |
| `__TEXT.__cstring` | `0x5159` | `0x51a9` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x4f0` | `0x53c` | **`+0x4c`** |
| `__TEXT.__unwind_info` | `0xe20` | `0xdd8` | **`-0x48`** |
| `__DATA.__objc_selrefs` | `0x10c0` | `0x1100` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1bc0` | `0x1b90` | **`-0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x678` | `0x658` | **`-0x20`** |
| `__DATA_CONST.__cfstring` | `0x42a0` | `0x42c0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x930` | `0x910` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0xdf0` | `0xdd8` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0x138` | `0x150` | **`+0x18`** |
| `__TEXT.__const` | `0x1af4` | `0x1b04` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xf0` | `0xfc` | **`+0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x6ec` | `0x6f0` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x5c` | `0x60` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x50` | `0x54` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x4c` | `0x48` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-4162.0.0.0.3
+4167.0.0.0.2

-  Functions: 1132
-  Symbols:   408
-  CStrings:  1367
+  Functions: 1114
+  Symbols:   407
+  CStrings:  1375
Symbols:
- __swift_stdlib_strtod_clocale
CStrings:
+ "CAM_ENABLE_VIDEO_AND_CINEMATIC_STABILIZATION_FOOTER"
+ "CAM_VCC_GAUGE_AX_LABEL"
+ "Refreshed VCC – capacity: %.2f GB, max capacity: %.2f GB"
+ "Refreshed maximumCapacity – max capacity: %.2f GB"
+ "Restored cached VCC info (busy) – capacity: %.2f GB, max capacity: %.2f GB"
+ "VCC raw values – remainingCapacity (clamped): %lld bytes (%.2f GB), maximumCapacity: %lld bytes (%.2f GB), initialCapacity: %lld bytes (%.2f GB)"
+ "_entryCapacityGB"
+ "_maximumCapacityGB"
+ "initWithDouble:"
+ "initialCapacity"
+ "labelColor"
+ "remainingCapacity"
+ "setLocale:"
+ "setMaximumFractionDigits:"
+ "setMinimumFractionDigits:"
+ "setNumberStyle:"
+ "systemBackgroundColor"
- "CAM_VCC_STORAGE_FORMAT_GB"
- "CAM_VCC_STORAGE_FORMAT_TB"
- "Refreshed VCC – capacity: %.2f GB, total free: %.2f GB"
- "Refreshed maximumCapacity – total free: %.2f GB"
- "Restored cached VCC info (busy) – capacity: %.2f GB, total free: %.2f GB"
- "VCC raw values – capacity: %lld bytes (%.2f GB), maximumCapacity: %lld bytes (%.2f GB)"
- "_isKeypadActive"
- "_totalFreeGB"
- "capacity"
```
