## WeatherWidget

> `/private/var/staged_system_apps/Weather.app/PlugIns/WeatherWidget.appex/WeatherWidget`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdf28c` | `0xe1648` | **`+0x23bc`** |
| `__DATA.__bss` | `0x11810` | `0xffe0` | **`-0x1830`** |
| `__TEXT.__const` | `0xcfe4` | `0xc3d4` | **`-0xc10`** |
| `__DATA.__data` | `0x6428` | `0x6fb8` | **`+0xb90`** |
| `__DATA_CONST.__const` | `0x4898` | `0x4510` | **`-0x388`** |
| `__TEXT.__unwind_info` | `0x3390` | `0x3060` | **`-0x330`** |
| `__TEXT.__eh_frame` | `0x253c` | `0x2270` | **`-0x2cc`** |
| `__TEXT.__swift5_typeref` | `0xbcce` | `0xbebe` | **`+0x1f0`** |
| `__TEXT.__constg_swiftt` | `0x2ef8` | `0x2d1c` | **`-0x1dc`** |
| `__TEXT.__auth_stubs` | `0x5670` | `0x5500` | **`-0x170`** |
| `__TEXT.__cstring` | `0x3e84` | `0x3d54` | **`-0x130`** |
| `__TEXT.__swift5_fieldmd` | `0x28c4` | `0x27b4` | **`-0x110`** |
| `__TEXT.__oslogstring` | `0x4425` | `0x451c` | **`+0xf7`** |
| `__DATA_CONST.__auth_got` | `0x2b40` | `0x2a88` | **`-0xb8`** |
| `__DATA_CONST.__auth_ptr` | `0x1830` | `0x1780` | **`-0xb0`** |
| `__DATA_CONST.__got` | `0xfb8` | `0xf60` | **`-0x58`** |
| `__TEXT.__swift5_types` | `0x3a4` | `0x34c` | **`-0x58`** |
| `__TEXT.__swift5_proto` | `0x844` | `0x7f0` | **`-0x54`** |
| `__TEXT.__swift5_reflstr` | `0x23b1` | `0x2361` | **`-0x50`** |
| `__TEXT.__swift5_assocty` | `0xca8` | `0xc60` | **`-0x48`** |
| `__TEXT.__swift_as_cont` | `0xb4` | `0x80` | **`-0x34`** |
| `__TEXT.__swift_as_entry` | `0x124` | `0xf4` | **`-0x30`** |
| `__TEXT.__objc_methname` | `0x1b25` | `0x1afd` | **`-0x28`** |
| `__TEXT.__swift5_builtin` | `0xa0` | `0x78` | **`-0x28`** |
| `__TEXT.__objc_methtype` | `0x76a` | `0x74a` | **`-0x20`** |
| `__DATA.__objc_const` | `0x1c40` | `0x1c50` | **`+0x10`** |
| `__DATA.__objc_data` | `0xab8` | `0xac0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x4f8` | `0x500` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5f8` | `0x600` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xd4` | `0xd0` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-1431.1.0.0.0
+1435.0.0.0.0

-  - /System/Library/Frameworks/DeveloperToolsSupport.framework/DeveloperToolsSupport

-  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 6080
-  Symbols:   259
-  CStrings:  822
+  Functions: 5022
+  Symbols:   258
+  CStrings:  817
Symbols:
+ _swift_makeBoxUnique
- _OBJC_CLASS_$_NSDateFormatter
- _swift_isaMask
CStrings:
+ "Failed to read PreferredWeatherCondition in preferredWeatherCondition"
+ "^[%@](styles: ['lowercaseSmallCaps'])"
+ "dynamicConditionAsDefault"
+ "locationUpdate: CoreLocation success but the fix's timestamp is stale; downgrading to .cached so the next refresh fires in ~5 min. timestamp=%{public}s"
+ "timestamp"
+ "weather.features.parasol.dynamicConditionAsDefault"
- " • ^[%@](styles: ['lowercaseSmallCaps'])"
- "Kinda Bad for you"
- "Placeholder text for the sunrise sunset widget description string"
- "Placeholder text for the sunrise sunset widget title string"
- "Very Bad for you"
- "WeatherWidget/DailyForecastContentView.swift"
- "WeatherWidget/DataDenseContentView.swift"
- "WeatherWidget/DataDenseTableView.swift"
- "WeatherWidget/WidgetContentView.swift"
- "kilometersPerHour"
- "watchos"
```
