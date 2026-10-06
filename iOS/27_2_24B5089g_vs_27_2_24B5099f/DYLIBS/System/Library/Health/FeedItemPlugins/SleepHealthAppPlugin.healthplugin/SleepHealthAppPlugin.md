## SleepHealthAppPlugin

> `/System/Library/Health/FeedItemPlugins/SleepHealthAppPlugin.healthplugin/SleepHealthAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x195708` | `0x1958fc` | **`+0x1f4`** |
| `__TEXT.__cstring` | `0x7a09` | `0x7ba9` | **`+0x1a0`** |
| `__DATA.__bss` | `0xaf50` | `0xb050` | **`+0x100`** |
| `__TEXT.__const` | `0xcd64` | `0xcde4` | **`+0x80`** |
| `__DATA.__data` | `0x4e28` | `0x4e98` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x42c0` | `0x42e0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x7fc8` | `0x7fe8` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x6a88` | `0x6aa8` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x5b78` | `0x5b98` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x380b` | `0x382b` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0xc68` | `0xc80` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x140` | `0x154` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x2d08` | `0x2d18` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3c34` | `0x3c40` | **`+0xc`** |
| `__AUTH.__objc_data` | `0x4788` | `0x4790` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x89c` | `0x8a4` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x4412` | `0x4418` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x51c` | `0x520` | **`+0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 6908
+  Functions: 6910

-  CStrings:  957
+  CStrings:  963
CStrings:
+ "BreathingDisturbancesHighlightDateModel:init"
+ "BreathingDisturbancesInternalSettingsView:getMostRecentApneaEventSample"
+ "SleepApneaEventPDFSectionProvider:generateAlertsChart"
+ "SleepApneaEventPDFSectionProvider:generateBreathingDisturbancesChart"
+ "SleepAppDelegate+Routing:openBreathingDisturbancesRoom"
+ "SleepHealthAppPlugin/SleepScoreDaySummaryProviderDataSource.swift"
```
