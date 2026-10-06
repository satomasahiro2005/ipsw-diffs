## WorkoutHealthPlugin

> `/System/Library/Health/Plugins/WorkoutHealthPlugin.bundle/WorkoutHealthPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x125cc` | `0x12550` | **`-0x7c`** |
| `__TEXT.__oslogstring` | `0x1106` | `0x1130` | **`+0x2a`** |
| `__TEXT.__objc_stubs` | `0x1940` | `0x1920` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x3a0` | `0x3b0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x236f` | `0x2365` | **`-0xa`** |
| `__DATA.__objc_selrefs` | `0x9e0` | `0x9d8` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1a0` | `0x1a8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x288` | `0x280` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2027.1.51.0.0
+2027.1.60.0.1

-  Functions: 213
+  Functions: 212

-  CStrings:  594
+  CStrings:  593
Symbols:
+ _FISetWorkoutGymKitDetectionMode
+ _kNLConnectedGymPreferencesNFCDetectionMode
- ___os_log_helper_16_2_3_8_64_8_64_8_64
- _objc_msgSend$boolValue
Functions:
~ +[WOWorkoutGymKitNFCManager enableGymKitNFCDefaultForHopliteOOPIfNeeded] : 968 -> 948
- ___os_log_helper_16_2_3_8_64_8_64_8_64
CStrings:
+ "[WorkoutGymKitNFC] GymKit detection already set (mode=%@ legacy=%@), skipping seeding the default"
+ "[WorkoutGymKitNFC] One time Enable NFC Default For HopliteOOP, set %@ = AlwaysOn"
- "[WorkoutGymKitNFC] %@ already set to %@, skipping setting %@"
- "[WorkoutGymKitNFC] One time Enable NFC Default For HopliteOOP, set %@ = YES"
- "boolValue"
```
