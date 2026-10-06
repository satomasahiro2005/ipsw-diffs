## MobileAsset

> `/System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e060` | `0x8e848` | **`+0x7e8`** |
| `__AUTH_CONST.__auth_got` | `0x0` | `0x588` | **`+0x588`** |
| `__DATA_CONST.__objc_arraydata` | `0x350` | `0x7d0` | **`+0x480`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x108` | `0x1c8` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x13e91` | `0x13f25` | **`+0x94`** |
| `__AUTH_CONST.__const` | `0x7e0` | `0x860` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x10120` | `0x10180` | **`+0x60`** |
| `__TEXT.__eh_frame` | `—` | `0x48` | **`+0x48`** |
| `__DATA.__bss` | `0x1c8` | `0x1f8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1f88` | `0x1fb8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x27a0` | `0x27c8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x38a8` | `0x38c8` | **`+0x20`** |
| `__TEXT.__const` | `0x2c4` | `0x2da` | **`+0x16`** |
| `__TEXT.__oslogstring` | `0xbba3` | `0xbbb4` | **`+0x11`** |
| `__TEXT.__gcc_except_tab` | `0x1394` | `0x13a4` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `—` | `0xa` | **`+0xa`** |
| `__DATA.__data` | `0x358` | `0x360` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x6f64` | `0x6f6c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_imageinfo`

### Other Changes

```diff

-2215.0.20.0.0
+2215.40.18.0.0

-  Functions: 3106
-  Symbols:   5091
-  CStrings:  2858
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  Functions: 3117
+  Symbols:   5120
+  CStrings:  2861
Symbols:
+ -[MAAutoAssetMigrationResults migrationDate]
+ -[MAAutoAssetMigrationResults setMigrationDate:]
+ -[MADownloadOptions summary]
+ _OBJC_IVAR_$_MAAutoAssetMigrationResults._migrationDate
+ __MAClientLogDateFormatter
+ __MAClientLogDateFormatter.dateFormatter
+ __MAClientLogDateFormatter.onceToken
+ __MAClientLogSpacedDateFormatter
+ __MAClientLogSpacedDateFormatter.onceToken
+ __MAClientLogSpacedDateFormatter.spacedDateFormatter
+ ____MAClientLogDateFormatter_block_invoke
+ ____MAClientLogSpacedDateFormatter_block_invoke
+ ___block_descriptor_32_e23_v16?0"MAPushChannel"8l
+ ___swift_instantiateConcreteTypeFromMangledNameV2
+ ___swift_reflection_version
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftCoreFoundation_$_MobileAsset
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftDispatch_$_MobileAsset
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftFoundation_$_MobileAsset
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftObjectiveC_$_MobileAsset
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swiftXPC_$_MobileAsset
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swift_Builtin_float_$_MobileAsset
+ _objc_retainAutoreleasedReturnValue
+ _swift_bridgeObjectRelease
+ _swift_getTypeByMangledNameInContext2
+ _swift_once
+ _swift_willThrow
+ _symbolic _____ySiG s11_SetStorageC
- -[MAPushNotificationController setVerboseLogging:]
- -[MAPushNotificationController verboseLogging]
- _OBJC_IVAR_$_MAPushNotificationController._verboseLogging
- ___block_descriptor_40_e8_32s_e23_v16?0"MAPushChannel"8ls32l8
CStrings:
+ "Caching server for %{public}@ %{public}@ is enabled: %d"
+ "Decoded MAAssetDiff %0llx/%0llx = %0llx"
+ "PreinstalledMigrationFileExists"
+ "Refresh state completed with purpose:%@ result:%ld success:%@"
+ "Secure"
+ "[MigrationResults>>>\nSuccessully migrated assets:\n%@\nFailed migrated assets:\n%@\nSetupError:\n%@\nMigrationDate:\n%@\n<<<]"
+ "cellular:%@|timeout:%ld|discretionary:%@|sessionId:%@|expensive:%@|power:%@|WiFi:%@"
+ "migrationDate"
- "Refresh state completed with result:%ld success:%@"
- "Refreshing with purpose: %@"
- "SecureMA"
- "Using caching server for %{public}@ %{public}@ is enabled: %d"
- "[MigrationResults>>>\nSuccessully migrated assets:\n%@\nFailed migrated assets:\n%@\nSetupError:\n%@\n<<<]"
```
