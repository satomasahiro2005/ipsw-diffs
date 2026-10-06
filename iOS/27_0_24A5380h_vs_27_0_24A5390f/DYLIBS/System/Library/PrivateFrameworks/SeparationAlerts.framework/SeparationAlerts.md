## SeparationAlerts

> `/System/Library/PrivateFrameworks/SeparationAlerts.framework/SeparationAlerts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x2d0` | `0x50` | **`-0x280`** |
| `__DATA_DIRTY.__objc_data` | `0xaf0` | `0xd70` | **`+0x280`** |
| `__TEXT.__text` | `0x3c5c0` | `0x3c784` | **`+0x1c4`** |
| `__AUTH_CONST.__objc_const` | `0x70f0` | `0x7180` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x2d20` | `0x2d60` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x47fc` | `0x482c` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0xa3ef` | `0xa418` | **`+0x29`** |
| `__DATA_CONST.__objc_selrefs` | `0x2760` | `0x2788` | **`+0x28`** |
| `__TEXT.__cstring` | `0x2030` | `0x2055` | **`+0x25`** |
| `__DATA.__bss` | `0x30` | `0x20` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x18` | `0x28` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x5a4` | `0x5b0` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x498` | `0x4a0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3f8` | `0x400` | **`+0x8`** |

### Other Changes

```diff

-107.0.25.0.0
+107.0.26.0.0

-  Functions: 1335
-  Symbols:   2517
-  CStrings:  779
+  Functions: 1339
+  Symbols:   2525
+  CStrings:  781
Symbols:
+ -[SASuppressionManager minHistoricalFamiliarity]
+ -[SASuppressionManager setMinHistoricalFamiliarity:]
+ -[SASuppressionResult initWithFamiliarLocation:shortReunionTime:personalVehicle:vehicularMotion:bookendedTravelBTHint:insufficientScanAirTimeWhileTraveling:insufficientScanAirTimeForLBAndBookended:numSafeLocations:recentFamiliarity:historicalFamiliarity:distanceFromHome:predictedLocationReturnTime:contextProbability:minPredictedReunionProbability:minHistoricalFamiliarity:]
+ -[SASuppressionResult minHistoricalFamiliarity]
+ -[SASuppressionResult minPredictedReunionProbability]
+ _OBJC_IVAR_$_SASuppressionManager._minHistoricalFamiliarity
+ _OBJC_IVAR_$_SASuppressionResult._minHistoricalFamiliarity
+ _OBJC_IVAR_$_SASuppressionResult._minPredictedReunionProbability
+ _SATrialFactorMinHistoricalFamiliarity
- -[SASuppressionResult initWithFamiliarLocation:shortReunionTime:personalVehicle:vehicularMotion:bookendedTravelBTHint:insufficientScanAirTimeWhileTraveling:insufficientScanAirTimeForLBAndBookended:numSafeLocations:recentFamiliarity:historicalFamiliarity:distanceFromHome:predictedLocationReturnTime:contextProbability:]
CStrings:
+ "en_US_POSIX"
+ "minHistoricalFamiliarity"
+ "u"
+ "{\"msg%{public}.0s\":\"#SASuppressionManager received Trial config update\", \"namespace\":\"%{public}@\", \"configKeys\":%{public}lu, \"familiarLocationPolicy\":%{public}hhd, \"shortReunionTimePolicy\":%{public}hhd, \"personalVehiclePolicy\":%{public}hhd, \"vehicularMotionPolicy\":%{public}hhd, \"bookendedTravelBTHintPolicy\":%{public}hhd, \"insufficientScanWhileTravelingPolicy\":%{public}hhd, \"insufficientScanLBAndBookendedPolicy\":%{public}hhd, \"zeroSafeLocationsOverride\":%{public}hhd, \"maxDistanceFromHomeForFamiliar\":\"%{public}f\", \"maxPredictedReunionTime\":\"%{public}f\", \"minPredictedReunionProbability\":\"%{public}f\", \"minScanAirTimeWhileTravelingForAlert\":\"%{public}f\", \"minScanAirTimeForLBAndBookendedAlert\":\"%{public}f\", \"minHistoricalFamiliarity\":\"%{public}f\"}"
- "e"
- "{\"msg%{public}.0s\":\"#SASuppressionManager received Trial config update\", \"namespace\":\"%{public}@\", \"configKeys\":%{public}lu, \"familiarLocationPolicy\":%{public}hhd, \"shortReunionTimePolicy\":%{public}hhd, \"personalVehiclePolicy\":%{public}hhd, \"vehicularMotionPolicy\":%{public}hhd, \"bookendedTravelBTHintPolicy\":%{public}hhd, \"insufficientScanWhileTravelingPolicy\":%{public}hhd, \"insufficientScanLBAndBookendedPolicy\":%{public}hhd, \"zeroSafeLocationsOverride\":%{public}hhd, \"maxDistanceFromHomeForFamiliar\":\"%{public}f\", \"maxPredictedReunionTime\":\"%{public}f\", \"minPredictedReunionProbability\":\"%{public}f\", \"minScanAirTimeWhileTravelingForAlert\":\"%{public}f\", \"minScanAirTimeForLBAndBookendedAlert\":\"%{public}f\"}"
```
