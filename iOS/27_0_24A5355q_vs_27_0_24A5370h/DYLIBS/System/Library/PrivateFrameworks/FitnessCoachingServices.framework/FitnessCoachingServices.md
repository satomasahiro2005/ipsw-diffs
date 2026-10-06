## FitnessCoachingServices

> `/System/Library/PrivateFrameworks/FitnessCoachingServices.framework/FitnessCoachingServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb9dc0` | `0xba4a0` | **`+0x6e0`** |
| `__TEXT.__eh_frame` | `0xb150` | `0xb278` | **`+0x128`** |
| `__AUTH_CONST.__auth_got` | `0x12c0` | `0x12f0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x34a4` | `0x34d4` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x3300` | `0x3330` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0xb3c` | `0xb58` | **`+0x1c`** |
| `__DATA.__data` | `0x7e0` | `0x7f8` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x29a8` | `0x2998` | **`-0x10`** |
| `__TEXT.__const` | `0x5eec` | `0x5efc` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x2439` | `0x2443` | **`+0xa`** |
| `__DATA_CONST.__got` | `0xa70` | `0xa68` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x42c` | `0x430` | **`+0x4`** |

### Other Changes

```diff

-2027.0.9.0.0
+2027.0.11.0.0

-  Functions: 2752
-  Symbols:   1301
-  CStrings:  511
+  Functions: 2764
+  Symbols:   1302
+  CStrings:  512
Symbols:
+ ___swift_closure_destructor.88Tm
+ _symbolic SS_ypt
+ _symbolic Say_____G 11SeymourCore27WorkoutPlanNotificationItemV
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _symbolic _____ySSypG s18_DictionaryStorageC
- ___swift_closure_destructor.89Tm
- _symbolic _____Sg 11SeymourCore16WorkoutPlanErrorO
- _symbolic _____Sg_ABt 11SeymourCore16WorkoutPlanErrorO
- _symbolic _____y_____G s23_ContiguousArrayStorageC 11SeymourCore27WorkoutPlanNotificationItemV
CStrings:
+ "Failed to fetch workout plan notification schedule: %@"
+ "[%s] At least one workout scheduled for today has been completed, shouldFire = NO"
+ "[%s] No plan workouts scheduled for today, skipping for today"
- "[%s] No F+ plan workouts scheduled for today, skipping for today"
- "[%s] Some workouts scheduled for today but at least one has been completed, shouldFire = NO"
```
