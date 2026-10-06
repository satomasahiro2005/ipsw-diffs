## BrightnessControl

> `/System/Library/PrivateFrameworks/BrightnessControl.framework/BrightnessControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b8bc` | `0x1b8fc` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x2c60` | `0x2c80` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2067` | `0x2077` | **`+0x10`** |

### Other Changes

```diff

-2300.40.37.0.0
+2300.40.39.0.0

-  CStrings:  605
+  CStrings:  606
Functions:
~ -[BCNativeBrtControl parseCapabilities:withDCPEndpoint:andError:] : 1268 -> 1332
CStrings:
+ "grimaldi-lux-cap"
```
