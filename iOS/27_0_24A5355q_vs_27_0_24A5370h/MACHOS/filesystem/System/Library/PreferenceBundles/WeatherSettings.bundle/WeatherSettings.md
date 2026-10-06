## WeatherSettings

> `/System/Library/PreferenceBundles/WeatherSettings.bundle/WeatherSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7a8c` | `0x80fc` | **`+0x670`** |
| `__DATA.__bss` | `0x5b0` | `0x290` | **`-0x320`** |
| `__TEXT.__const` | `0x450` | `0x2c8` | **`-0x188`** |
| `__TEXT.__cstring` | `0x881` | `0x921` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x1120` | `0x11c0` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x1b2f` | `0x1bbf` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x161` | `0x1b1` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x700` | `0x740` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x2f0` | `0x2b0` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0x1a0` | `0x1d8` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x1e0` | `0x1b0` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x79c` | `0x7cc` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x78` | `0x48` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0x618` | `0x640` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x14` | **`-0x28`** |
| `__DATA.__data` | `0x270` | `0x290` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x800` | `0x820` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x198` | `0x17b` | **`-0x1d`** |
| `__TEXT.__swift5_proto` | `0x2c` | `0x14` | **`-0x18`** |
| `__DATA.__objc_const` | `0xad8` | `0xae8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x408` | `0x418` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2b0` | `0x2a0` | **`-0x10`** |
| `__DATA.__objc_data` | `0x410` | `0x418` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x24` | `0x1c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1431.1.0.0.0
+1435.0.0.0.0

-  Functions: 283
-  Symbols:   166
-  CStrings:  384
+  Functions: 268
+  Symbols:   167
+  CStrings:  393
Symbols:
+ _swift_deletedMethodError
+ _swift_getObjCClassMetadata
- _swift_beginAccess
CStrings:
+ "Failed to read PreferredWeatherCondition in preferredWeatherCondition"
+ "dynamicConditionAsDefault"
+ "dynamicWeatherConditionLabel"
+ "preferred-weather-condition-dynamic-default"
+ "preferred-weather-condition-temperature-default"
+ "setName:"
+ "temperatureWeatherConditionLabel"
+ "updateWeatherConditionLabels"
+ "weather.features.parasol.dynamicConditionAsDefault"
```
