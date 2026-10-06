## Fitness

> `/System/Library/PrivateFrameworks/Fitness.framework/Fitness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e678` | `0x6eb70` | **`+0x4f8`** |
| `__TEXT.__oslogstring` | `0x30e9` | `0x3239` | **`+0x150`** |
| `__AUTH_CONST.__cfstring` | `0x52e0` | `0x5300` | **`+0x20`** |
| `__TEXT.__cstring` | `0x6140` | `0x6160` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1d28` | `0x1d40` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xf20` | `0xf30` | **`+0x10`** |
| `__TEXT.__const` | `0x2c68` | `0x2c78` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1338` | `0x1340` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x454` | `0x450` | **`-0x4`** |

### Other Changes

```diff

-2027.1.22.0.0
+2027.1.27.0.0

-  Functions: 2641
-  Symbols:   2846
-  CStrings:  1134
+  Functions: 2650
+  Symbols:   2856
+  CStrings:  1139
Symbols:
+ GCC_except_table75
+ _FISetWorkoutGymKitDetectionMode
+ _FIWorkoutGymKitDetectionIsMutedToday
+ _FIWorkoutGymKitDetectionMode
+ _FIWorkoutGymKitDetectionModeForPairedWatch
+ _FIWorkoutGymKitDetectionSetMutedForToday
+ _HKConnectedGymIsMutedToday
+ _HKConnectedGymSetMutedForToday
+ __FIWorkoutGymKitDetectionMode
+ _getNPKExpressGymKitAvailabilityManagerClass
+ _kNLConnectedGymPreferencesNFCDetectionMode
- GCC_except_table74
CStrings:
+ "ConnectedGymNFCDetectionMode"
+ "FICelebrationAssetURLProvider: FitnessUIAssets bundle is nil for achievement: %@"
+ "FICelebrationAssetURLProvider: FitnessUIAssets bundle is nil for goal type %ld"
+ "FICelebrationAssetURLProvider: Movie not found for achievement: %@, resource: %@/%@.%@"
+ "FICelebrationAssetURLProvider: Movie not found for goal type %ld, resource: %@/%@.%@"
```
