## PredictedContextAlgorithms

> `/System/Library/PrivateFrameworks/PredictedContextAlgorithms.framework/PredictedContextAlgorithms`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x98124` | `0x983ec` | **`+0x2c8`** |
| `__TEXT.__oslogstring` | `0x699a` | `0x6a51` | **`+0xb7`** |
| `__AUTH_CONST.__cfstring` | `0x4340` | `0x4380` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2fa0` | `0x2fa8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x6de4` | `0x6dec` | **`+0x8`** |
| `__TEXT.__cstring` | `0x31fa` | `0x31f6` | **`-0x4`** |

### Other Changes

```diff

-46.0.0.0.0
+46.0.1.0.0

-  Functions: 2921
-  Symbols:   5401
-  CStrings:  1061
+  Functions: 2922
+  Symbols:   5402
+  CStrings:  1063
Symbols:
+ -[PCWorkoutPredictionAlgorithm _locationMatchesRecord:visitPlaceType:visitLat:visitLon:]
+ -[PCWorkoutPredictionAlgorithm _passesLocDowLocTimeGateForActivityType:currentVisit:workoutTypeLocationMap:]
- -[PCWorkoutPredictionAlgorithm _hasUserWorkedOutForActivityType:nearCurrentVisit:workoutTypeLocationMap:]
CStrings:
+ "dow"
+ "hour"
+ "lat"
+ "locDoW_locTime gate FAIL for %{public}@: locDow=%{public}d, locTime=%{public}d (n=%{public}lu, vDow=%{public}ld, vHour=%{public}.2f)"
+ "locDoW_locTime gate PASS for %{public}@ (vDow=%{public}ld, vHour=%{public}.2f)"
+ "locDoW_locTime gate rejected %{public}@ at this visit, skipping cluster %{public}@"
+ "locDoW_locTime gate: no prior %{public}@ workouts"
+ "locDoW_locTime gate: visit missing dow/hour, rejecting %{public}@"
+ "locDoW_locTime gate: visit missing location/time context for %{public}@"
+ "lon"
- "Found %@ workout with matching placeType: %@"
- "Found %@ workout within %.1f miles: %.3f miles"
- "No location context in current visit"
- "No location data found for activity type: %@"
- "No matching %@ workout locations found near this visit"
- "User has not done %@ workouts at current location, skipping cluster %@"
- "locations"
- "placeTypes"
```
