## HealthArchivableViews

> `/System/Library/PrivateFrameworks/HealthArchivableViews.framework/HealthArchivableViews`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b394` | `0x2d984` | **`+0x25f0`** |
| `__DATA_DIRTY.__bss` | `—` | `0x400` | **`+0x400`** |
| `__DATA.__bss` | `0xff8` | `0xcf8` | **`-0x300`** |
| `__DATA_DIRTY.__data` | `—` | `0x1f0` | **`+0x1f0`** |
| `__TEXT.__const` | `0x13a4` | `0x14d4` | **`+0x130`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x128` | **`+0x128`** |
| `__AUTH_CONST.__const` | `0xc58` | `0xd58` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0xb88` | `0xc78` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x916` | `0x9e7` | **`+0xd1`** |
| `__TEXT.__swift5_reflstr` | `0x413` | `0x4d3` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x6f3` | `0x7b2` | **`+0xbf`** |
| `__AUTH.__data` | `0x438` | `0x3a0` | **`-0x98`** |
| `__TEXT.__constg_swiftt` | `0x5b0` | `0x63c` | **`+0x8c`** |
| `__DATA.__data` | `0xd48` | `0xcc8` | **`-0x80`** |
| `__AUTH_CONST.__auth_got` | `0xe60` | `0xed8` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x3dc` | `0x450` | **`+0x74`** |
| `__TEXT.__unwind_info` | `0xb10` | `0xb80` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x81c` | `0x86c` | **`+0x50`** |
| `__AUTH.__objc_data` | `0x378` | `0x330` | **`-0x48`** |
| `__TEXT.__objc_methlist` | `0x4dc` | `0x50c` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x878` | `0x8a0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x818` | `0x830` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x108` | `0x120` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x440` | `0x450` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x20c` | `0x21c` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x54` | `0x60` | **`+0xc`** |
| `__DATA.__common` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x7c` | `0x84` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x60` | `0x64` | **`+0x4`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 928
-  Symbols:   611
-  CStrings:  104
+  Functions: 982
+  Symbols:   636
+  CStrings:  109
Symbols:
+ -[_HAVHeartRateCoordinator _applyHeartRateData:isBackfill:]
+ _AnalyticsSendEventLazy
+ _HKImproveHealthAndActivityAnalyticsAllowed
+ _OBJC_CLASS_$_HAVHeartRateComplicationSampleReporter
+ _OBJC_IVAR_$__HAVHeartRateCoordinator._sampleReporter
+ _OBJC_METACLASS_$_HAVHeartRateComplicationSampleReporter
+ __DATA_HAVHeartRateComplicationSampleReporter
+ __INSTANCE_METHODS_HAVHeartRateComplicationSampleReporter
+ __IVARS_HAVHeartRateComplicationSampleReporter
+ __METACLASS_DATA_HAVHeartRateComplicationSampleReporter
+ ___swift_allocate_value_buffer
+ ___swift_memcpy32_8
+ ___swift_project_value_buffer
+ __swiftEmptyDictionarySingleton
+ _bzero
+ _objc_retain_x25
+ _objc_retain_x26
+ _swift_initStackObject
+ _swift_setDeallocating
+ _swift_stdlib_random
+ _symbolic _____ 10Foundation4DateV
+ _symbolic _____ 21HealthArchivableViews39LiveHeartRateComplicationSampleReporterC
+ _symbolic _____ 21HealthArchivableViews45LiveHeartRateComplicationSampleAnalyticsEventV
+ _symbolic _____ So19HRCHeartRateContextV
+ _symbolic _____Sg 21HealthArchivableViews39LiveHeartRateComplicationSampleReporterC
+ _symbolic y_____c 21HealthArchivableViews45LiveHeartRateComplicationSampleAnalyticsEventV
+ _type_layout_string 21HealthArchivableViews45LiveHeartRateComplicationSampleAnalyticsEventV
- -[_HAVHeartRateCoordinator _applyHeartRateData:]
- _swift_bridgeObjectRelease_n
CStrings:
+ "HealthArchivableViews/LiveHeartRateComplicationSampleAnalyticsEvent.swift"
+ "[%{public}s] %{public}s is not in the current analytics config; it may not be registered on the Core Analytics portal."
+ "[%{public}s] sampled in; IH&A allowed: %{bool,public}d"
+ "com.apple.health.HeartRateComplication"
+ "seconds_since_the_last_published_5s_sample"
+ "seconds_since_the_start_of_complication"
- "com.apple.Health"
```
