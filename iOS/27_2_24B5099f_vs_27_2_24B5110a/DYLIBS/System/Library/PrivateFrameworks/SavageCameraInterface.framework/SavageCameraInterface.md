## SavageCameraInterface

> `/System/Library/PrivateFrameworks/SavageCameraInterface.framework/SavageCameraInterface`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a58` | `0x38e0` | **`+0xe88`** |
| `__DATA_CONST.__const` | `0x78` | `0x808` | **`+0x790`** |
| `__TEXT.__oslogstring` | `0x4a4` | `0x6bb` | **`+0x217`** |
| `__TEXT.__cstring` | `0x67e` | `0x88b` | **`+0x20d`** |
| `__AUTH_CONST.__auth_got` | `0x1b8` | `0x210` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__TEXT.__const` | `0xc0` | `0xd0` | **`+0x10`** |

### Other Changes

```diff

-10.61.0.0.0
+10.66.0.0.0

-  Functions: 18
-  Symbols:   100
-  CStrings:  97
+  Functions: 20
+  Symbols:   115
+  CStrings:  136
Symbols:
+ _CFEqual
+ _CFStringCreateWithCString
+ _IORegistryEntryFromPath
+ _SavageCamInterfaceCheckPersonalizationStatus
+ _SavageCamInterfaceExtractUID
+ __ZL19kDeviceChannelsInfo
+ __ZZ28SavageCamInterfaceExtractUIDE7yeidTag
+ _close
+ _free
+ _fstat
+ _glob
+ _globfree
+ _malloc_type_malloc
+ _open
+ _read
CStrings:
+ "%02x"
+ "%s: Extracted UID = %s from %s\n"
+ "%s: Failed to extract UID from %s File\n"
+ "%s: Failed to open %s\n"
+ "%s: Failed to read %s\n"
+ "%s: IOReg UID property for %s channel : %s = %s\n"
+ "%s: Malformed or unexpected-length 'yeid' value, returning\n"
+ "%s: No %s File found or not permitted to read\n"
+ "%s: No current UID published in IORegistry for %s\n"
+ "%s: Re-personalization detection is not supported for this Platform\n"
+ "%s: Unable to read platform ID from /arm-io/isp : node missing, property missing, or access denied)\n"
+ "%s: channel=%s personalizationState=%s\n"
+ "/private/preboot/*/usr/standalone/firmware/%s"
+ "FRONT_CAMERA"
+ "FRONT_CAMERA_RENO"
+ "FRONT_CAMERA_SWIDE"
+ "FRONT_INFRARED"
+ "IODeviceTree:/arm-io/isp"
+ "NO_CAMERA"
+ "NeedsPersonalization"
+ "Personalized"
+ "REAR_CAMERA"
+ "REAR_CAMERA_SWIDE"
+ "REAR_CAMERA_TELE"
+ "REAR_INFRARED"
+ "REAR_JASPER"
+ "Savage/SavagePatch.DER"
+ "SavageCamInterfaceCheckPersonalizationStatus"
+ "SavageCamInterfaceExtractUID"
+ "SavageUID"
+ "UNKNOWN_CHANNEL"
+ "Unknown"
+ "Yonkers/YonkersPatch.DER"
+ "YonkersIR/YonkersIR1Patch.DER"
+ "YonkersIR/YonkersIR2Patch.DER"
+ "YonkersIR1UID"
+ "YonkersIR2UID"
+ "YonkersUID"
+ "sensor-type"
```
