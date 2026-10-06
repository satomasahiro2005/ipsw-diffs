## pipelined

> `/usr/libexec/pipelined`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x376354` | `0x375b74` | **`-0x7e0`** |
| `__TEXT.__objc_methtype` | `0x6268` | `0x62d2` | **`+0x6a`** |
| `__TEXT.__gcc_except_tab` | `0x2e768` | `0x2e754` | **`-0x14`** |
| `__TEXT.__unwind_info` | `0x12a80` | `0x12a90` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0xae3d` | `0xae45` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 12882
+  Functions: 12878
CStrings:
+ "@32@0:8r^{?=i{?=dd}ddddddddidi{?=dd}diIiiidB}16r^{?=dddddfffBi{?=dd}diiB{?=ddBBidqddd}{?={?=iddddd{?=dd}dd}iQiiiidB}{?=dd}if{?=dd}ddiBddddddddBB{?=dd}diddddddiddi{?=I}{?=if}B{?=dddffffff}}24"
+ "T{?=dddddfffBi{?=dd}diiB{?=ddBBidqddd}{?={?=iddddd{?=dd}dd}iQiiiidB}{?=dd}if{?=dd}ddiBddddddddBB{?=dd}diddddddiddi{?=I}{?=if}B{?=dddffffff}},N,V_locationPrivate"
+ "T{?=dddddfffBi{?=dd}diiB{?=ddBBidqddd}{?={?=iddddd{?=dd}dd}iQiiiidB}{?=dd}if{?=dd}ddiBddddddddBB{?=dd}diddddddiddi{?=I}{?=if}B{?=dddffffff}},R,N,V_gpsLocationPrivate"
+ "v624@0:8{?=dddddfffBi{?=dd}diiB{?=ddBBidqddd}{?={?=iddddd{?=dd}dd}iQiiiidB}{?=dd}if{?=dd}ddiBddddddddBB{?=dd}diddddddiddi{?=I}{?=if}B{?=dddffffff}}16"
+ "{?=\"odometer\"d\"deltaDistance\"d\"deltaDistanceAccuracy\"d\"timestampGps\"d\"machtime\"d\"horzUncSemiMaj\"f\"horzUncSemiMin\"f\"horzUncSemiMajAz\"f\"isFitnessMatch\"B\"matchQuality\"i\"matchCoordinate\"{?=\"latitude\"d\"longitude\"d}\"matchCourse\"d\"matchFormOfWay\"i\"matchRoadClass\"i\"matchShifted\"B\"mapMatcherData\"{?=\"rawUnmodifiedCourse\"d\"rawUnmodifiedCourseUnc\"d\"isStatic\"B\"isMounted\"B\"estimatedLane\"i\"estimatedLaneProbability\"d\"estimatedLaneFeatureID\"q\"flowlineSnapLat\"d\"flowlineSnapLon\"d\"flowlineSnapCourse\"d}\"trackRunData\"{?=\"lapInformation\"{?=\"lapCount\"i\"currentLapStartTime\"d\"currentLapDurationInSeconds\"d\"currentLapDistanceInMeters\"d\"previousLapDurationInSeconds\"d\"previousLapDistanceInMeters\"d\"previousLapPositionAtCompletionInDegrees\"{?=\"latitude\"d\"longitude\"d}\"currentTrackRunSessionDurationInSeconds\"d\"currentTrackRunSessionDistanceInMeters\"d}\"laneNumber\"i\"trackId\"Q\"estimatedLaneNumber\"i\"laneCount\"i\"estimatedLaneConfidence\"i\"trackProximity\"i\"distanceToTrackMeters\"d\"odometerHasBeenCorrected\"B}\"pressure\"{?=\"value\"d\"std\"d}\"undulationModel\"i\"undulation\"f\"specialCoordinate\"{?=\"latitude\"d\"longitude\"d}\"specialHorizontalAccuracy\"d\"machContinuousTime\"d\"originDevice\"i\"isMatcherPropagatedCoordinates\"B\"slope\"d\"maxAbsSlope\"d\"groundAltitude\"d\"groundAltitudeUncertainty\"d\"rawHorizontalAccuracy\"d\"rawAltitude\"d\"rawVerticalAccuracy\"d\"rawCourseAccuracy\"d\"isCoordinateFused\"B\"isCoordinateFusedWithVL\"B\"fusedCoordinate\"{?=\"latitude\"d\"longitude\"d}\"fusedHorizontalAccuracy\"d\"fusedReferenceFrame\"i\"fusedAltitude\"d\"fusedVerticalAccuracy\"d\"fusedCourse\"d\"fusedCourseAccuracy\"d\"smoothedGPSAltitude\"d\"smoothedGPSAltitudeUncertainty\"d\"positionContextState\"i\"probabilityPositionContextStateIndoor\"d\"probabilityPositionContextStateOutdoor\"d\"batchedLocationFixType\"i\"wifiZaxisData\"{?=\"numberOfZaxisSlamApsUsed\"I}\"demFlatnessMetricData\"{?=\"demNumContiguousFlatPoints\"i\"confidence\"f}\"isTrustedForTimeZone\"B\"wirelessClientInfo\"{?=\"latitudeDegrees\"d\"longitudeDegrees\"d\"mslAltitudeMeters\"d\"horizontalAccuracyMeters\"f\"verticalAccuracyMeters\"f\"speedMetersPerSecond\"f\"speedAccuracyMetersPerSecond\"f\"courseDegrees\"f\"courseAccuracyDegrees\"f}}"
+ "{?=dddddfffBi{?=dd}diiB{?=ddBBidqddd}{?={?=iddddd{?=dd}dd}iQiiiidB}{?=dd}if{?=dd}ddiBddddddddBB{?=dd}diddddddiddi{?=I}{?=if}B{?=dddffffff}}16@0:8"
- "@32@0:8r^{?=i{?=dd}ddddddddidi{?=dd}diIiiidB}16r^{?=dddddfffBi{?=dd}diiB{?=ddBBidqddd}{?={?=iddddd{?=dd}dd}iQiiiidB}{?=dd}if{?=dd}ddiBddddddddBB{?=dd}diddddddiddi{?=I}{?=if}B{?=dddff}}24"
- "T{?=dddddfffBi{?=dd}diiB{?=ddBBidqddd}{?={?=iddddd{?=dd}dd}iQiiiidB}{?=dd}if{?=dd}ddiBddddddddBB{?=dd}diddddddiddi{?=I}{?=if}B{?=dddff}},N,V_locationPrivate"
- "T{?=dddddfffBi{?=dd}diiB{?=ddBBidqddd}{?={?=iddddd{?=dd}dd}iQiiiidB}{?=dd}if{?=dd}ddiBddddddddBB{?=dd}diddddddiddi{?=I}{?=if}B{?=dddff}},R,N,V_gpsLocationPrivate"
- "v608@0:8{?=dddddfffBi{?=dd}diiB{?=ddBBidqddd}{?={?=iddddd{?=dd}dd}iQiiiidB}{?=dd}if{?=dd}ddiBddddddddBB{?=dd}diddddddiddi{?=I}{?=if}B{?=dddff}}16"
- "{?=\"odometer\"d\"deltaDistance\"d\"deltaDistanceAccuracy\"d\"timestampGps\"d\"machtime\"d\"horzUncSemiMaj\"f\"horzUncSemiMin\"f\"horzUncSemiMajAz\"f\"isFitnessMatch\"B\"matchQuality\"i\"matchCoordinate\"{?=\"latitude\"d\"longitude\"d}\"matchCourse\"d\"matchFormOfWay\"i\"matchRoadClass\"i\"matchShifted\"B\"mapMatcherData\"{?=\"rawUnmodifiedCourse\"d\"rawUnmodifiedCourseUnc\"d\"isStatic\"B\"isMounted\"B\"estimatedLane\"i\"estimatedLaneProbability\"d\"estimatedLaneFeatureID\"q\"flowlineSnapLat\"d\"flowlineSnapLon\"d\"flowlineSnapCourse\"d}\"trackRunData\"{?=\"lapInformation\"{?=\"lapCount\"i\"currentLapStartTime\"d\"currentLapDurationInSeconds\"d\"currentLapDistanceInMeters\"d\"previousLapDurationInSeconds\"d\"previousLapDistanceInMeters\"d\"previousLapPositionAtCompletionInDegrees\"{?=\"latitude\"d\"longitude\"d}\"currentTrackRunSessionDurationInSeconds\"d\"currentTrackRunSessionDistanceInMeters\"d}\"laneNumber\"i\"trackId\"Q\"estimatedLaneNumber\"i\"laneCount\"i\"estimatedLaneConfidence\"i\"trackProximity\"i\"distanceToTrackMeters\"d\"odometerHasBeenCorrected\"B}\"pressure\"{?=\"value\"d\"std\"d}\"undulationModel\"i\"undulation\"f\"specialCoordinate\"{?=\"latitude\"d\"longitude\"d}\"specialHorizontalAccuracy\"d\"machContinuousTime\"d\"originDevice\"i\"isMatcherPropagatedCoordinates\"B\"slope\"d\"maxAbsSlope\"d\"groundAltitude\"d\"groundAltitudeUncertainty\"d\"rawHorizontalAccuracy\"d\"rawAltitude\"d\"rawVerticalAccuracy\"d\"rawCourseAccuracy\"d\"isCoordinateFused\"B\"isCoordinateFusedWithVL\"B\"fusedCoordinate\"{?=\"latitude\"d\"longitude\"d}\"fusedHorizontalAccuracy\"d\"fusedReferenceFrame\"i\"fusedAltitude\"d\"fusedVerticalAccuracy\"d\"fusedCourse\"d\"fusedCourseAccuracy\"d\"smoothedGPSAltitude\"d\"smoothedGPSAltitudeUncertainty\"d\"positionContextState\"i\"probabilityPositionContextStateIndoor\"d\"probabilityPositionContextStateOutdoor\"d\"batchedLocationFixType\"i\"wifiZaxisData\"{?=\"numberOfZaxisSlamApsUsed\"I}\"demFlatnessMetricData\"{?=\"demNumContiguousFlatPoints\"i\"confidence\"f}\"isTrustedForTimeZone\"B\"wirelessClientInfo\"{?=\"latitudeDegrees\"d\"longitudeDegrees\"d\"mslAltitudeMeters\"d\"horizontalAccuracyMeters\"f\"verticalAccuracyMeters\"f}}"
- "{?=dddddfffBi{?=dd}diiB{?=ddBBidqddd}{?={?=iddddd{?=dd}dd}iQiiiidB}{?=dd}if{?=dd}ddiBddddddddBB{?=dd}diddddddiddi{?=I}{?=if}B{?=dddff}}16@0:8"
```
