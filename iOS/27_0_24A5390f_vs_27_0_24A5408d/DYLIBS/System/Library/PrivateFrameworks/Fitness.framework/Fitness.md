## Fitness

> `/System/Library/PrivateFrameworks/Fitness.framework/Fitness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b8a8` | `0x5e2f4` | **`+0x2a4c`** |
| `__TEXT.__oslogstring` | `0x2c39` | `0x2d49` | **`+0x110`** |
| `__TEXT.__const` | `0x21ec` | `0x228c` | **`+0xa0`** |
| `__AUTH.__data` | `0x638` | `0x6c0` | **`+0x88`** |
| `__TEXT.__constg_swiftt` | `0x70c` | `0x784` | **`+0x78`** |
| `__TEXT.__eh_frame` | `0xa98` | `0xaf8` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x19a0` | `0x1a00` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0xc0c` | `0xc50` | **`+0x44`** |
| `__AUTH_CONST.__auth_got` | `0xde0` | `0xe20` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x4b20` | `0x4b60` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x9d8` | `0xa18` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x4ac` | `0x4e8` | **`+0x3c`** |
| `__TEXT.__cstring` | `0x5dde` | `0x5e0e` | **`+0x30`** |
| `__DATA.__bss` | `0x2bf8` | `0x2c10` | **`+0x18`** |
| `__DATA.__data` | `0xa58` | `0xa70` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x1310` | `0x1328` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x854` | `0x86c` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x7e0` | `0x7f0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x78` | `0x68` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x3c` | `0x30` | **`-0xc`** |
| `__TEXT.__swift_as_entry` | `0x4c` | `0x44` | **`-0x8`** |

### Other Changes

```diff

-2027.0.61.0.0
+2027.0.68.0.0

+  - /System/Library/Frameworks/UIKit.framework/UIKit

+  - /usr/lib/swift/libswiftCoreImage.dylib

+  - /usr/lib/swift/libswiftSpatial.dylib

-  Functions: 2270
-  Symbols:   2661
-  CStrings:  1098
+  Functions: 2295
+  Symbols:   2678
+  CStrings:  1101
Symbols:
+ _FIDailyDistanceMilesBedtimeSuggestionThreshold
+ _FIDailyPushesBedtimeSuggestionThreshold
+ _FIDailyStepsBedtimeSuggestionThreshold
+ _UIApplicationProtectedDataDidBecomeAvailable
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreImage_$_Fitness
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftSpatial_$_Fitness
+ __swift_FORCE_LOAD_$_swiftUIKit
+ __swift_FORCE_LOAD_$_swiftUIKit_$_Fitness
+ _swift_retain_x10
+ _swift_task_deinitOnExecutor
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
+ _symbolic SDy_____ScTyyt_____GG 7Fitness19FIPedometerProviderC0B10MetricTypeO s5NeverO
+ _symbolic Shy_____G 7Fitness19FIPedometerProviderC0B10MetricTypeO
+ _symbolic _____Sg_ABt 10Foundation12NotificationV
+ _symbolic _____y_____G s11_SetStorageC 7Fitness19FIPedometerProviderC0D10MetricTypeO
+ _symbolic _____y_____ScTyyt_____GG s18_DictionaryStorageC 7Fitness19FIPedometerProviderC0D10MetricTypeO s5NeverO
- __swift_implicitisolationactor_to_executor_cast
- _symbolic Scgyyt______pG s5ErrorP
CStrings:
+ "%s authorization denied for %{public}s — stopping query and disabling restarts"
+ "Fitness/FIPedometerProvider.swift"
+ "Pedometer query failed for %{public}s: %{public}s"
+ "Protected data became available — restarting %{public}ld parked pedometer queries"
+ "Protected data inaccessible for %{public}s — parking metric until device unlocks"
+ "Restarting pedometer query for %{public}s. Attempt: %{public}ld, delay: %{public}lds"
- "%s authorization denied — stopping query and disabling restarts"
- "Pedometer queries failed: %s"
- "Restarting pedometer queries. Retry attempt: %ld"
```
