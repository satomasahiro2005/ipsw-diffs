## WeatherDaemon

> `/System/Library/PrivateFrameworks/WeatherDaemon.framework/WeatherDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x240f18` | `0x240cbc` | **`-0x25c`** |
| `__TEXT.__cstring` | `0x3e05` | `0x3ec5` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x14230` | `0x142d0` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0xd365` | `0xd3b5` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x2874` | `0x28b4` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x1140` | `0x1138` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x9140` | `0x9138` | **`-0x8`** |

### Other Changes

```diff

-1444.1.0.0.0
+1454.1.0.0.0

-  Functions: 15315
+  Functions: 15329

-  CStrings:  1334
+  CStrings:  1337
CStrings:
+ "CREATE INDEX IF NOT EXISTS index_dayForecast_id_startsAt ON dayForecast (id, startsAt);"
+ "CREATE INDEX IF NOT EXISTS index_hourForecast_id_startsAt ON hourForecast (id, startsAt);"
+ "Failed to create granular forecast indices (cache usable, unindexed): %@"
```
