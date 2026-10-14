## Nexus

> `/System/Library/PrivateFrameworks/Nexus.framework/Nexus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17f634` | `0x17f424` | **`-0x210`** |
| `__TEXT.__cstring` | `0x3e84` | `0x3f44` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x2cbe` | `0x2d3e` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x3c78` | `0x3cf0` | **`+0x78`** |
| `__TEXT.__const` | `0x10310` | `0x10340` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0xc6a0` | `0xc6b8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x5ab0` | `0x5ab8` | **`+0x8`** |

### Other Changes

```diff

-910.29.0.0.0
+910.31.0.0.0

-  Functions: 7049
+  Functions: 7054

-  CStrings:  931
+  CStrings:  940
Symbols:
+ _MobileGestalt_get_deviceHousingColor
- _MobileGestalt_copy_deviceColor_obj
CStrings:
+ "AudioAccessory11,1"
+ "HomeAccessory17,1"
+ "HomeAccessory17,2"
+ "rosePink"
+ "silver"
+ "spaceGrey"
+ "starlight"
+ "updateFaceEnrollment"
+ "updateVoiceEnrollment"
```
