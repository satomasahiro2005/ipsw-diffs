## BrightnessControl

> `/System/Library/PrivateFrameworks/BrightnessControl.framework/BrightnessControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b40c` | `0x1b454` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x2c20` | `0x2c40` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2037` | `0x2047` | **`+0x10`** |

### Other Changes

```diff

-2300.0.18.502.1
+2300.2.7.0.0

-  CStrings:  603
+  CStrings:  604
Functions:
~ -[BCAppleBacklightBrtControl initWithService:] : 6640 -> 6676
~ +[BCNativeBrtControl parsePanelLimits:toCapabilities:] : 576 -> 612
CStrings:
+ "MinNitsPanel"
```
