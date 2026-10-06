## WeatherCore

> `/System/Library/PrivateFrameworks/WeatherCore.framework/WeatherCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2663c8` | `0x268240` | **`+0x1e78`** |
| `__TEXT.__oslogstring` | `0xe457` | `0xe5a7` | **`+0x150`** |
| `__TEXT.__cstring` | `0xc25a` | `0xc2ea` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0xae28` | `0xae80` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0x7001` | `0x7041` | **`+0x40`** |
| `__DATA.__data` | `0x3238` | `0x3258` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x10dd0` | `0x10df0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x15a98` | `0x15ab0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1050` | `0x1068` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x7878` | `0x7890` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x8c4f` | `0x8c5b` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2ab8` | `0x2ab0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x13f0` | `0x13f8` | **`+0x8`** |

### Other Changes

```diff

-1431.1.0.0.0
+1435.0.0.0.0

-  Functions: 17617
-  Symbols:   4367
-  CStrings:  1892
+  Functions: 17673
+  Symbols:   4374
+  CStrings:  1897
Symbols:
+ _OUTLINED_FUNCTION_199
+ _OUTLINED_FUNCTION_200
+ _OUTLINED_FUNCTION_201
+ _OUTLINED_FUNCTION_202
+ _OUTLINED_FUNCTION_203
+ _OUTLINED_FUNCTION_204
+ _symbolic _____Sg_ABt 10Foundation6LocaleV6RegionV
CStrings:
+ "Existing CRDT data is undecodable; removing corrupt bytes to recover. Error=%{public}s"
+ "Failed to persist remote data to the local store; not propagating it to avoid resurrecting stale/deleted entries"
+ "Merge produced no local change after external change event. Skipping KVS write-back to avoid sync churn."
+ "dynamicConditionAsDefault"
+ "weather.features.parasol.dynamicConditionAsDefault"
+ "weather.outlook.resolvedDynamicConditionAsDefault"
- "http://localhost/ping"
```
