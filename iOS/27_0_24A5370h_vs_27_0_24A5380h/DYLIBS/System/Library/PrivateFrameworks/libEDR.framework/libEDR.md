## libEDR

> `/System/Library/PrivateFrameworks/libEDR.framework/libEDR`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1e49` | `0x1e21` | **`-0x28`** |
| `__TEXT.__oslogstring` | `0xe25` | `0xe4a` | **`+0x25`** |
| `__TEXT.__text` | `0xfac8` | `0xfac0` | **`-0x8`** |

### Other Changes

```diff

-69.0.0.0.0
+70.0.0.0.0

-  CStrings:  357
+  CStrings:  356
Functions:
~ _EDRServerSetDisplayBrightnessForDisplay : 852 -> 832
~ _EDRServerAddDisplay : 392 -> 396
~ sub_2b7ecda4c -> sub_2b9d76a3c : 820 -> 828
CStrings:
+ "libEDR - EDRServerSetDisplayBrightnessForDisplay: (display: %d, targetBrightness: %f, maxLuminance: %f, ambientIlluminance: %f, brightnessScaler: %f)\n"
- "EDRServerSetDisplayBrightnessForDisplay"
- "libEDR - %s: (display: %d, targetBrightness: %f, maxLuminance: %f, ambientIlluminance: %f, brightnessScaler: %f)\n"
```
