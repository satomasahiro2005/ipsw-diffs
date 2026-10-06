## WeatherCore

> `/System/Library/PrivateFrameworks/WeatherCore.framework/WeatherCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x268240` | `0x26938c` | **`+0x114c`** |
| `__DATA_DIRTY.__data` | `0xa090` | `0xafd8` | **`+0xf48`** |
| `__DATA.__bss` | `0x1c790` | `0x1ba90` | **`-0xd00`** |
| `__DATA_DIRTY.__bss` | `0x16e40` | `0x17b40` | **`+0xd00`** |
| `__AUTH.__data` | `0x12f8` | `0x608` | **`-0xcf0`** |
| `__DATA.__data` | `0x3258` | `0x3018` | **`-0x240`** |
| `__AUTH.__objc_data` | `0x308` | `0x180` | **`-0x188`** |
| `__DATA_DIRTY.__objc_data` | `0xbe0` | `0xd68` | **`+0x188`** |
| `__TEXT.__swift5_reflstr` | `0x7041` | `0x7191` | **`+0x150`** |
| `__TEXT.__cstring` | `0xc2ea` | `0xc3aa` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x15ab0` | `0x15b40` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x7890` | `0x7920` | **`+0x90`** |
| `__DATA.__common` | `0x1a8` | `0x158` | **`-0x50`** |
| `__DATA_DIRTY.__common` | `0xd0` | `0x120` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x10df0` | `0x10dc8` | **`-0x28`** |
| `__TEXT.__const` | `0x22028` | `0x22048` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2ab0` | `0x2aa8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1068` | `0x1070` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xae80` | `0xae88` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x8c5b` | `0x8c5c` | **`+0x1`** |

### Other Changes

```diff

-1435.0.0.0.0
+1439.0.0.0.0

-  Functions: 17673
-  Symbols:   4374
-  CStrings:  1897
+  Functions: 17697
+  Symbols:   4372
+  CStrings:  1903
Symbols:
+ _symbolic SiSg
- _get_type_metadata 15Synchronization5MutexVyScTy11WeatherCore31PredictedLocationsAuthorizationOs5NeverOGSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "highlightActiveLookahead"
+ "imminentRainLookahead"
+ "severeAlertOnsetWindow"
+ "significantPrecipRateMMPerHour"
+ "tenDayMinQualifyingDays"
+ "todayMinSignificantHours"
```
