## libcoreroutine.dylib

> `/usr/lib/libcoreroutine.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bd79c` | `0x6be004` | **`+0x868`** |
| `__TEXT.__oslogstring` | `0x89e8d` | `0x89da2` | **`-0xeb`** |
| `__AUTH_CONST.__objc_dictobj` | `0x348` | `0x2a8` | **`-0xa0`** |
| `__DATA_CONST.__objc_arraydata` | `0x2e58` | `0x2dd8` | **`-0x80`** |
| `__TEXT.__gcc_except_tab` | `0x2ef98` | `0x2effc` | **`+0x64`** |
| `__TEXT.__cstring` | `0x4ae89` | `0x4aed2` | **`+0x49`** |
| `__AUTH_CONST.__objc_intobj` | `0x4bc0` | `0x4c08` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x2c300` | `0x2c340` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x10658` | `0x10680` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x3510` | `0x3518` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xf268` | `0xf260` | **`-0x8`** |

### Other Changes

```diff

-1119.0.0.0.0
+1122.0.0.0.0

-  Functions: 22020
-  Symbols:   33958
-  CStrings:  16422
+  Functions: 22022
+  Symbols:   33961
+  CStrings:  16420
Symbols:
+ -[RTBGSystemTaskScheduler _reportTaskFinishedWithIdentifier:stimulationDate:error:didDefer:systemRequestedDeferral:]
+ -[RTFloorTransitionExtractor _largeTransitionExistsInGapFrom:to:transitions:]
+ -[RTFloorTransitionExtractor findLabeledDataForTime:labeledData:lookingForEnd:transitions:]
+ _RPOptionStatusFlags
+ ___61-[RTXPCActivityManager unregisterTaskWithIdentifier:handler:]_block_invoke
+ ___block_descriptor_105_e8_32s40s48s56s64s72s80s88r_e5_v8?0ls32l8s40l8s48l8s56l8s64l8r88l8s72l8s80l8
+ ___block_descriptor_80_e8_32s40s48s56bs64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_96_e8_32s40s48s56s64s72s80r_e20_v20?0"NSError"8B16ls32l8s40l8s48l8s56l8r80l8s64l8s72l8
- -[RTBGSystemTaskScheduler _reportTaskFinishedWithIdentifier:stimulationDate:error:isDeferred:]
- -[RTFloorTransitionExtractor findLabeledDataForTime:labeledData:lookingForEnd:]
- -[RTVisitFloorMap assignFloorLabelsToSimplifiedData:groupedAltitudeData:clusteringResult:]
- ___block_descriptor_105_e8_32s40s48s56s64s72s80s88r_e5_v8?0ls32l8s40l8r88l8s48l8s56l8s64l8s72l8s80l8
- ___block_descriptor_96_e8_32s40s48s56s64s72s80r_e20_v20?0"NSError"8B16ls32l8s40l8r80l8s48l8s56l8s64l8s72l8
CStrings:
+ "#altimeter,%{public}@,floor_count_histogram,k,%lu,visits,%lu,fraction,%.3f,loiUUID,%{private}@"
+ "#altimeter,%{public}@,selected_cluster_count,%lu,visits_with_count,%lu,fraction,%.3f,loiUUID,%{private}@"
+ "#altimeter,built labeled grouped data,validCount,%lu,totalGrouped,%lu,visitUUID,%{private}@"
+ "#altimeter,findLabeledDataForTime,dropping feature,backwardCandidateIdx,%lu,reason,largeTransitionInGap,visitUUID,%{private}@"
+ "#altimeter,findLabeledDataForTime,dropping feature,forwardCandidateIdx,%lu,reason,largeTransitionInGap,visitUUID,%{private}@"
+ "#altimeter,initial k-mean clustering group number guess for LOI learning,clusterCount,%d,qualifyingVisitsCount,%lu,totalVisits,%lu"
+ "#altimeter,initial loi floor map guess,floorIdx,%d,initialCenter,%.3f,qualifyingVisitCount,%lu"
+ "#altimeter,invalid clustering result for labeled data construction,assignmentsCount,%lu,groupedCount,%lu,floorCount,%lu,visitUUID,%{private}@"
+ "%@, %@, scheduler, %@, run finished, identifier, %@, group, %@, error, %@, latency, %.2f, system requested deferral, %d, did defer, %d"
+ "%@, ignoring provider error and labeling visit with remaining placeInferences, error, %@"
+ "%@.%@.BGSTRegisterLaunchHandler.%@"
+ "%@.%@.BGSTSubmitTaskRequest.%@"
+ "13:46:21"
+ "Aug  4 2026"
+ "ignoring provider error and labeling visit with remaining placeInferences, error, %@"
+ "systemRequestedDeferral"
- "#altimeter,added grouped segment,floorIndex,%d,startTime,%.3f,endTime,%.3f,altitude,%.3f,visitUUID,%{private}@"
- "#altimeter,added simplified point,floorIndex,%d,pointAltitude,%.3f,floorAltitude,%.3f,distance,%.3f,visitUUID,%{private}@"
- "#altimeter,assignFloorLabelsToSimplifiedData,empty grouped data,visitUUID,%{private}@"
- "#altimeter,assignFloorLabelsToSimplifiedData,empty simplified data,visitUUID,%{private}@"
- "#altimeter,assignFloorLabelsToSimplifiedData,invalid clustering result data,visitUUID,%{private}@"
- "#altimeter,assignFloorLabelsToSimplifiedData,no clustering result,visitUUID,%{private}@"
- "#altimeter,completed floor label assignment,totalAssignedPoints,%lu,groupedSegmentsUsed,%lu,additionalSimplifiedPoints,%lu,visitUUID,%{private}@"
- "#altimeter,excluded simplified point without floor assignment,pointAltitude,%.3f,timestamp,%.3f,visitUUID,%{private}@"
- "#altimeter,no labeled Simplified Data found, skipped floor transition extraction,visitUUID,%{private}@"
- "#altimeter,skipping simplified point that overlaps with already used grouped segment,pointTime,%.3f,visitUUID,%{private}@"
- "#altimeter,starting floor label assignment,simplifiedDataCount,%lu,groupedDataCount,%lu,floorCount,%lu,visitUUID,%{private}@"
- "%@, %@, scheduler, %@, run finished, identifier, %@, group, %@, error, %@, latency, %.2f, is deferred, %d"
- "%@, %@, task deferred by client, identifier: %@"
- "%@, %@, task expired by system, identifier: %@"
- "%@, %@, task failed, identifier: %@, error: %@"
- "06:38:08"
- "@min.doubleValue"
- "Jul 11 2026"
```
