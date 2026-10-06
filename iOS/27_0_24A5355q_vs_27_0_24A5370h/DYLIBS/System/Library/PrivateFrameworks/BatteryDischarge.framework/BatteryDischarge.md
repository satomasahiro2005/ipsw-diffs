## BatteryDischarge

> `/System/Library/PrivateFrameworks/BatteryDischarge.framework/BatteryDischarge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x177c` | `0x1e38` | **`+0x6bc`** |
| `__DATA.__bss` | `—` | `0x300` | **`+0x300`** |
| `__TEXT.__const` | `0xa2` | `0x25a` | **`+0x1b8`** |
| `__AUTH_CONST.__const` | `0x168` | `0x1f8` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0xae` | `0xf0` | **`+0x42`** |
| `__AUTH_CONST.__auth_got` | `0x198` | `0x1d8` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x80` | `0xb0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x11b` | `0xeb` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xc8` | `0xf8` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__cstring` | `0x42` | `0x62` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `—` | `0x18` | **`+0x18`** |
| `__DATA.__data` | `0x38` | `0x48` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x30` | `0x40` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x58` | `0x64` | **`+0xc`** |
| `__TEXT.__swift5_reflstr` | `0xb` | `0x14` | **`+0x9`** |
| `__AUTH.__objc_data` | `0xf8` | `0xf0` | **`-0x8`** |
| `__AUTH_CONST.__objc_const` | `0xf0` | `0xe8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x70` | `0x68` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x4` | `0xc` | **`+0x8`** |

### Other Changes

```diff

-4.0.0.502.1
+9.0.0.0.0

-  Functions: 47
-  Symbols:   96
+  Functions: 79
+  Symbols:   107
Symbols:
+ _associated conformance 16BatteryDischarge0B11ThermalModeOSHAASQ
+ _associated conformance 16BatteryDischarge0B15TerminationKindOSHAASQ
+ _swift_getWitnessTable
+ _swift_release_x21
+ _swift_release_x23
+ _swift_retain_x21
+ _symbolic $sSY
+ _symbolic Si
+ _symbolic _____ 16BatteryDischarge0B11ThermalModeO
+ _symbolic _____ 16BatteryDischarge0B15TerminationKindO
+ _symbolic _____IeyBy_ 10ObjectiveC8ObjCBoolV
+ _symbolic _____SiSdS3iAAIeyByyyyyyy_ 10ObjectiveC8ObjCBoolV
- _symbolic SbSdIegyy_
CStrings:
+ "Failed to get XPC proxy"
+ "Failed to get XPC proxy for startDischarge"
- "Failed to get XPC proxy for startFastDischarge"
- "Failed to get XPC proxy for startSlowDischarge"
```
