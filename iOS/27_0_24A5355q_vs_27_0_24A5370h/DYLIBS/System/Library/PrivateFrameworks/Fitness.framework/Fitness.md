## Fitness

> `/System/Library/PrivateFrameworks/Fitness.framework/Fitness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5fd70` | `0x60acc` | **`+0xd5c`** |
| `__AUTH_CONST.__const` | `0x2af0` | `0x2c28` | **`+0x138`** |
| `__TEXT.__swift5_typeref` | `0xb00` | `0xc0c` | **`+0x10c`** |
| `__TEXT.__oslogstring` | `0x2b8d` | `0x2c39` | **`+0xac`** |
| `__TEXT.__swift5_capture` | `0x530` | `0x5b4` | **`+0x84`** |
| `__TEXT.__unwind_info` | `0x1a28` | `0x1a58` | **`+0x30`** |
| `__TEXT.__const` | `0x2250` | `0x227c` | **`+0x2c`** |
| `__DATA_CONST.__objc_selrefs` | `0x22f8` | `0x2318` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x6e8` | `0x704` | **`+0x1c`** |
| `__DATA.__common` | `0x38` | `0x50` | **`+0x18`** |
| `__DATA.__data` | `0xa40` | `0xa58` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x7d0` | `0x7e0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x844` | `0x854` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xdd8` | `0xde0` | **`+0x8`** |
| `__DATA.__bss` | `0x2bf0` | `0x2bf8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0xeb0` | `0xea8` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x58` | `0x5c` | **`+0x4`** |

### Other Changes

```diff

-2027.0.51.0.0
+2027.0.55.0.0

-  Functions: 2288
-  Symbols:   2649
-  CStrings:  1096
+  Functions: 2311
+  Symbols:   2661
+  CStrings:  1098
Symbols:
+ _OBJC_CLASS_$_HKStatisticsCollection
+ _OBJC_CLASS_$_HKStatisticsCollectionQuery
+ ___swift_closure_destructor.120Tm
+ _swift_allocBox
+ _swift_release_n
+ _swift_retain_n
+ _symbolic ScsySo22HKStatisticsCollectionC______pG s5ErrorP
+ _symbolic Sd
+ _symbolic So22HKStatisticsCollectionCSg______pSgIeggg_ s5ErrorP
+ _symbolic So27HKStatisticsCollectionQueryC
+ _symbolic _____ 7Fitness0A3LogO
+ _symbolic _____ySo22HKStatisticsCollectionC______p_G Scs12ContinuationV s5ErrorP
+ _symbolic _____ySo22HKStatisticsCollectionC______p_G Scs8IteratorV s5ErrorP
+ _symbolic _____ySo22HKStatisticsCollectionC______p__G Scs12ContinuationV11YieldResultO s5ErrorP
+ _symbolic _____ySo22HKStatisticsCollectionC______p__G Scs12ContinuationV15BufferingPolicyO s5ErrorP
- ___swift_closure_destructor.117Tm
- _symbolic _____Sg 9HealthKit37HKStatisticsCollectionQueryDescriptorV6ResultV
- _symbolic _____ySo16HKQuantitySampleCG 9HealthKit17HKSamplePredicateV
CStrings:
+ "HK stats update for %{public}s: total=%{private}f, mostRecent=%{public}s"
+ "Notifying %{public}ld pedometer observers; current data steps=%{private}s pushes=%{private}s"
```
