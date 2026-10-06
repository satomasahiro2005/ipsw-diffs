## batteryintelligenced

> `/usr/libexec/batteryintelligenced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48b40` | `0x45e60` | **`-0x2ce0`** |
| `__DATA.__objc_const` | `0x84f0` | `0x7b90` | **`-0x960`** |
| `__TEXT.__objc_methlist` | `0x3854` | `0x33ec` | **`-0x468`** |
| `__DATA.__objc_data` | `0x1590` | `0x12c0` | **`-0x2d0`** |
| `__DATA_CONST.__objc_arraydata` | `0xef8` | `0xd48` | **`-0x1b0`** |
| `__TEXT.__objc_classname` | `0x8f6` | `0x776` | **`-0x180`** |
| `__TEXT.__oslogstring` | `0x8e23` | `0x8d1a` | **`-0x109`** |
| `__TEXT.__unwind_info` | `0xdb8` | `0xcb8` | **`-0x100`** |
| `__DATA_CONST.__objc_arrayobj` | `0x5e8` | `0x510` | **`-0xd8`** |
| `__DATA_CONST.__cfstring` | `0x4380` | `0x42c0` | **`-0xc0`** |
| `__TEXT.__cstring` | `0x3986` | `0x38f0` | **`-0x96`** |
| `__DATA_CONST.__objc_classlist` | `0x228` | `0x1e0` | **`-0x48`** |
| `__DATA_CONST.__objc_superrefs` | `0x208` | `0x1c0` | **`-0x48`** |
| `__DATA.__objc_ivar` | `0x3c8` | `0x3a4` | **`-0x24`** |
| `__DATA_CONST.__got` | `0x358` | `0x340` | **`-0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-222.0.1.0.0
+228.0.0.0.0

-  Functions: 1695
+  Functions: 1597

-  CStrings:  2773
+  CStrings:  2757
CStrings:
+ "Error reading battery virtual temp from ASBM. Returning kInvalidValue %ld"
- "6t6qz674si"
- "BatteryTemperatureReader returning value %@"
- "Could not load battery_analysis_tt80_model_6t6qz674si.mlmodelc in the bundle resource"
- "Could not load battery_analysis_tt80_model_bkwqiw7f79.mlmodelc in the bundle resource"
- "Could not load battery_analysis_tt80_model_xtgs7ejyqa.mlmodelc in the bundle resource"
- "Unable to get battery properties: %d"
- "battery_analysis_tt80_model_6t6qz674si"
- "battery_analysis_tt80_model_6t6qz674siInput"
- "battery_analysis_tt80_model_6t6qz674siOutput"
- "battery_analysis_tt80_model_bkwqiw7f79"
- "battery_analysis_tt80_model_bkwqiw7f79Input"
- "battery_analysis_tt80_model_bkwqiw7f79Output"
- "battery_analysis_tt80_model_xtgs7ejyqa"
- "battery_analysis_tt80_model_xtgs7ejyqaInput"
- "battery_analysis_tt80_model_xtgs7ejyqaOutput"
- "bkwqiw7f79"
- "xtgs7ejyqa"
```
