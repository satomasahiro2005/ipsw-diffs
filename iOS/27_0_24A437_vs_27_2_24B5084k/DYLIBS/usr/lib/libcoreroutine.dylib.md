## libcoreroutine.dylib

> `/usr/lib/libcoreroutine.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6be004` | `0x6bf554` | **`+0x1550`** |
| `__TEXT.__oslogstring` | `0x89da2` | `0x8a106` | **`+0x364`** |
| `__TEXT.__gcc_except_tab` | `0x2effc` | `0x2f0f0` | **`+0xf4`** |
| `__AUTH_CONST.__objc_const` | `0x56920` | `0x56a10` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x4aed2` | `0x4afc2` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x34e30` | `0x34ee8` | **`+0xb8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b4a8` | `0x1b508` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x3738` | `0x3778` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x2c340` | `0x2c360` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xf260` | `0xf278` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x28ec` | `0x2900` | **`+0x14`** |
| `__TEXT.__const` | `0x4bd8` | `0x4be8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x10680` | `0x10688` | **`+0x8`** |

### Other Changes

```diff

-1122.0.0.0.0
+1123.0.0.0.0

-  Functions: 22022
-  Symbols:   33961
-  CStrings:  16420
+  Functions: 22042
+  Symbols:   33983
+  CStrings:  16431
Symbols:
+ -[RTTripClusterManager _donationPlaceConfidenceForLocationOfInterest:]
+ -[RTTripClusterManager _nearestLocationOfInterest:toLocation:withinDistance:]
+ -[RTTripClusterProcessorOptions setWalkingArrivalMaxHorizontalAccuracy_m:]
+ -[RTTripClusterProcessorOptions setWalkingArrivalRadius_m:]
+ -[RTTripClusterProcessorOptions setWalkingArrivalRequiredConsecutiveFixes:]
+ -[RTTripClusterProcessorOptions walkingArrivalMaxHorizontalAccuracy_m]
+ -[RTTripClusterProcessorOptions walkingArrivalRadius_m]
+ -[RTTripClusterProcessorOptions walkingArrivalRequiredConsecutiveFixes]
+ -[RTTripClusterWalkAndBikeTripStats .cxx_destruct]
+ -[RTTripClusterWalkAndBikeTripStats _activeWalkingDurationForSortedLocations:destinationLatitude:destinationLongitude:segmentStartDate:wallClockDuration:]
+ -[RTTripClusterWalkAndBikeTripStats _activeWalkingDurationForTripSegment:]
+ -[RTTripClusterWalkAndBikeTripStats initWithTripSegmentManager:options:]
+ -[RTTripClusterWalkAndBikeTripStats options]
+ -[RTTripClusterWalkAndBikeTripStats setOptions:]
+ -[RTTripClusterWalkAndBikeTripStats setTripSegmentManager:]
+ -[RTTripClusterWalkAndBikeTripStats tripSegmentManager]
+ -[RTTripClusterWalkAndBikeTripStats updateWalkAndBikeStats:isTripSegmentBeforeDriving:isTerminalTripSegment:]
+ _OBJC_IVAR_$_RTTripClusterProcessorOptions._walkingArrivalMaxHorizontalAccuracy_m
+ _OBJC_IVAR_$_RTTripClusterProcessorOptions._walkingArrivalRadius_m
+ _OBJC_IVAR_$_RTTripClusterProcessorOptions._walkingArrivalRequiredConsecutiveFixes
+ _OBJC_IVAR_$_RTTripClusterWalkAndBikeTripStats._options
+ _OBJC_IVAR_$_RTTripClusterWalkAndBikeTripStats._tripSegmentManager
+ _RTApplicationManagerBundleIdMapsIntents
+ ___74-[RTTripClusterWalkAndBikeTripStats _activeWalkingDurationForTripSegment:]_block_invoke
- -[RTTripClusterWalkAndBikeTripStats init]
- -[RTTripClusterWalkAndBikeTripStats updateWalkAndBikeStats:isTripSegmentBeforeDriving:]
CStrings:
+ "%@,Error computing distance to destination,%@"
+ "%@,_activeWalkingDurationForSortedLocations,arrival not confirmed,falling back to wall-clock duration,%.1f"
+ "%@,_activeWalkingDurationForSortedLocations,implausible active duration,%.1f,falling back to wall-clock duration,%.1f"
+ "%@,_activeWalkingDurationForSortedLocations,leg never left arrival radius,maxDistance,%.1f,falling back to wall-clock duration,%.1f"
+ "%@,_activeWalkingDurationForTripSegment,tripID,%@,no location data,fetchError,%@,semaError,%@,falling back to wall-clock duration,%.1f"
+ "%@,_activeWalkingDurationForTripSegment,tripID,%@,tripDistance,%.1f,wallClockDuration,%.1f,activeWalkingDuration,%.1f"
+ "%@:%@, found location of interest for location %@ with name '%@', place confidence, %.3f, derived from %lu visits"
+ "%@:%@, location of interest, %@, has no visits, donating place confidence, %.3f"
+ "%@:%@, location of interest, %@, has out of range place confidence, %.3f, clamping"
+ "-[RTTripClusterWalkAndBikeTripStats _activeWalkingDurationForTripSegment:]"
+ "-[RTTripClusterWalkAndBikeTripStats updateWalkAndBikeStats:isTripSegmentBeforeDriving:isTerminalTripSegment:]"
+ "06:17:53"
+ "<%@: %p, downsampleFactor,%ld,windowSize,%ld,maxLocationPerTrip,%ld,maxProcessedTripSegments,%ld,useMaxProcessedTripSegments,%@,purgeClustersDataBase,%@,distBetweenTrips_km,%.2f,distanceThreshold_m,%.2f,unreachableDistance_m,%.2f,clusterLifeTimeThreshold_d,%ld,lengthDeviationThreshold_m,%.2f,locationThresholdRadius_m,%.2f,distAccuracyThreshold_m,%.2f,writeTripSegmentsToFile,%@,enableClusterProcessing,%@,saveToHTML,%@,clusterProcessorMode,%ld,learnedRoutesCurrentLocationSPIEnabled,%@,maxCleanUpOperationsCountPerRun,%ld,maxRouteRehydrationsCountPerRun,%ld,maxDeletionAttemptsForClusterData,%ld,rehydrateRouteLocationsFromWaypoints,%@,cleanUpClusterWithDuplicateWaypoints,%@,cleanUpOrphanedLocalStoreEntries,%@,walkingArrivalRadius_m,%.2f,walkingArrivalMaxHorizontalAccuracy_m,%.2f,walkingArrivalRequiredConsecutiveFixes,%ld>"
+ "Sep  5 2026"
+ "com.apple.Maps.MapsIntents"
+ "\x92"
- "%@:%@, found location of interest for location %@ with name '%@'"
- "-[RTTripClusterWalkAndBikeTripStats updateWalkAndBikeStats:isTripSegmentBeforeDriving:]"
- "21:30:39"
- "<%@: %p, downsampleFactor,%ld,windowSize,%ld,maxLocationPerTrip,%ld,maxProcessedTripSegments,%ld,useMaxProcessedTripSegments,%@,purgeClustersDataBase,%@,distBetweenTrips_km,%.2f,distanceThreshold_m,%.2f,unreachableDistance_m,%.2f,clusterLifeTimeThreshold_d,%ld,lengthDeviationThreshold_m,%.2f,locationThresholdRadius_m,%.2f,distAccuracyThreshold_m,%.2f,writeTripSegmentsToFile,%@,enableClusterProcessing,%@,saveToHTML,%@,clusterProcessorMode,%ld,learnedRoutesCurrentLocationSPIEnabled,%@,maxCleanUpOperationsCountPerRun,%ld,maxRouteRehydrationsCountPerRun,%ld,maxDeletionAttemptsForClusterData,%ld,rehydrateRouteLocationsFromWaypoints,%@,cleanUpClusterWithDuplicateWaypoints,%@,cleanUpOrphanedLocalStoreEntries,%@>"
- "Aug  8 2026"
```
