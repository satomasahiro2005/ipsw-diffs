## BrightnessControl

> `/System/Library/PrivateFrameworks/BrightnessControl.framework/BrightnessControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b45c` | `0x1b8bc` | **`+0x460`** |
| `__AUTH_CONST.__cfstring` | `0x2c40` | `0x2c60` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2047` | `0x2067` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x908` | `0x918` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7a8` | `0x7b8` | **`+0x10`** |

### Other Changes

```diff

-2300.2.9.0.0
+2300.40.37.0.0

-  Functions: 660
-  Symbols:   1158
-  CStrings:  604
+  Functions: 664
+  Symbols:   1162
+  CStrings:  605
Symbols:
+ +[BCNativeBrtControl parsePanelLimits:toCapabilities:ignoreLmidCalibration:]
+ _interpolate_value_in_table
+ _load_mapping_table_from_defaults
+ _mapping_table_is_valid
+ _save_mapping_table_to_defaults
- +[BCNativeBrtControl parsePanelLimits:toCapabilities:]
CStrings:
+ "lmid-calibration-ignore"
```
