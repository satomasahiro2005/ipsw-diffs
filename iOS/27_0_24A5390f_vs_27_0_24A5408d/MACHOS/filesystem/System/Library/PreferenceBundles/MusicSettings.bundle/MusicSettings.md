## MusicSettings

> `/System/Library/PreferenceBundles/MusicSettings.bundle/MusicSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14e2c` | `0x17b20` | **`+0x2cf4`** |
| `__TEXT.__auth_stubs` | `0xd40` | `0xf60` | **`+0x220`** |
| `__TEXT.__eh_frame` | `0x98` | `0x280` | **`+0x1e8`** |
| `__TEXT.__swift5_typeref` | `0xc20` | `0xdae` | **`+0x18e`** |
| `__DATA.__bss` | `0x530` | `0x3b0` | **`-0x180`** |
| `__DATA.__data` | `0x698` | `0x7d8` | **`+0x140`** |
| `__DATA_CONST.__auth_got` | `0x6b0` | `0x7c0` | **`+0x110`** |
| `__TEXT.__cstring` | `0x1f3d` | `0x1e6d` | **`-0xd0`** |
| `__TEXT.__unwind_info` | `0x538` | `0x600` | **`+0xc8`** |
| `__TEXT.__objc_stubs` | `0x2f80` | `0x3020` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x3950` | `0x39e0` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x5a8` | `0x628` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x1d20` | `0x1d80` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x80` | `0xdc` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0xb00` | `0xab0` | **`-0x50`** |
| `__TEXT.__const` | `0x754` | `0x704` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0x308` | `0x2dc` | **`-0x2c`** |
| `__DATA.__objc_selrefs` | `0x10b0` | `0x10d8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xc7c` | `0xc9c` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x154` | `0x134` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x134` | `0x14d` | **`+0x19`** |
| `__TEXT.__swift_as_cont` | `0x4` | `0x18` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x28` | `0x1c` | **`-0xc`** |
| `__TEXT.__swift_as_entry` | `0x4` | `0x10` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `—` | `0xc` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x290` | `0x288` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x28` | `0x24` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`

### Other Changes

```diff

-4026.100.79.0.0
+4026.110.1.0.0

-  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 456
-  Symbols:   313
-  CStrings:  944
+  Functions: 485
+  Symbols:   326
+  CStrings:  950
Symbols:
+ _OBJC_CLASS_$_LSApplicationWorkspace
+ __swiftEmptyDictionarySingleton
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_endAccess
+ _swift_errorRelease
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getSingletonMetadata
+ _swift_release_x24
+ _swift_release_x25
+ _swift_retain_x20
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_task_create
CStrings:
+ "\n\n%@"
+ "Audio Quality Settings"
+ "HI_RES_LOSSLESS_TRANSITIONS_WARN"
+ "To use AutoMix or Crossfade, change the current audio quality from Hi-Res Lossless."
+ "Transitions and Audio Quality"
+ "_messageByAppendingTransitionsWarningIfNeeded:"
+ "_referenceMusicSettingsController"
+ "defaultWorkspace"
+ "openSensitiveURL:withOptions:"
+ "stringByAppendingFormat:"
- "Beginnings and endings of songs blend together seamlessly. Albums and some genres will still play without transitions. AutoMix unavailable while using AirPlay."
- "Beginnings and endings of songs blend together seamlessly. Albums and some genres will still play without transitions. Unavailable while using AirPlay."
- "BufferedAirPlayAudioPipelineSenderSideMixing"
- "BufferedAirPlaySpeedRamps"
```
