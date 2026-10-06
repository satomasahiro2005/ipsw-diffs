## RTSCV1

> `/System/Library/VideoProcessors/RTSCV1.bundle/RTSCV1`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15c48` | `0x15c58` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4c0` | `0x4b8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3
Functions:
~ _FigMotionGetMotionDataFromISP : 808 -> 816
~ _FigMotionGetISPHallData : 1056 -> 1100
~ _FigMotionComputeQuaternionForTimeStamp : 1192 -> 1188
~ _FigMotionComputeLensMovementAndSagForTimeStamp : 984 -> 980
~ -[RTSCKalmanFilter4DOF reset] : 72 -> 84
~ -[RTSCKalmanFilter4DOF _updateInternalForIndex:withMeasurement:noiseCovariance:] : 704 -> 712
~ -[RTSCProcessorV1 _updateTransformAndMetadataForPreview] : 1112 -> 1104
~ -[RTSCAutocovarianceDynamicsAnalyzer4DOF updateWithData:atTime:] : 556 -> 552
~ -[RTSCRealTimeStabilization _setDefaultParametersWithCameraExtrinsics:] : 672 -> 676
~ -[RTSCRealTimeStabilization _extractMetadataAndMotionDataFromDictionary:calibration:cameraMetadata:cameraPose:oisOffset:sagOffset:] : 2440 -> 2464
~ -[RTSCRealTimeStabilization _computeClampedRollingShutterTransformForBoundingRect:] : 752 -> 748
~ -[RTSCRealTimeStabilization _applySmoothingToCameraModel:filterPole:] : 204 -> 228
~ -[RTSCRealTimeStabilization _applyFinalAdjustmentsToStabilizedCameraForInputPose:cameraMetadata:] : 1456 -> 1460
~ -[RTSCRealTimeStabilization _computeHomographyFromRotation:focalLength:inputOpticalCenter:outputOpticalCenter:] : 384 -> 376
~ -[RTSCRealTimeStabilization _computeHomographyForStabilizedCamera:inputPose:oisOffset:cameraMetadata:rollingShutterTransform:] : 452 -> 448
~ _rts_computeBoundingMarginsForHomography : 356 -> 352
~ -[RTSCRealTimeStabilization _clampStabilizedCamera:ToBoundingCorners:boundingEllipse:currentBoundingMargin:inputPose:oisOffset:cameraMetadata:] : 1036 -> 1044
~ -[RTSCRealTimeStabilization updateStabilizationHomographyUsingMetadata:inputCalibration:pixelBufferDimensions:outputFOVRect:] : 2036 -> 2040
~ -[RTSCFaceReframer _applyRotationAdjustmentsToReframingCorrection:stabilizationMetadata:cameraMetadata:] : 1596 -> 1592
~ -[RTSCFaceReframer _computeHomographyFromRotation:focalLength:inputOpticalCenter:outputOpticalCenter:] : 368 -> 360
~ -[RTSCFaceReframer _clampRotationCorrection:shiftCorrection:ToBoundingCorners:boundingEllipse:currentBoundingMargin:cameraMetadata:] : 356 -> 348
~ -[RTSCPanning3DAnalyzer updateWithPose:atTime:] : 980 -> 976
~ -[RTSCRollingShutterModel resetToCenterPosition:withPose:principalPoint:focalLength:] : 240 -> 236
~ -[RTSCRollingShutterModel updateModelAtRow:withPose:principalPoint:] : 588 -> 580
~ -[RTSCRollingShutterModel fitNormalizedBackwardsTransformForBufferSize:limitFactor:] : 388 -> 380
~ -[RTSCFaceDataCovarianceEstimator updateCovarianceWithFaceBox:atTime:] : 436 -> 432
~ -[RTSCFaceTrackerV2 _updateTrackingStateFromPrevFrame:atTime:bufferSize:] : 484 -> 476
~ -[RTSCFaceReframingV1 updateFacesWithMetadata:bufferSize:cameraMatrix:rotationFromPrevFrame:atTime:] : 760 -> 752
~ -[RTSCFaceReframingV1 updateFaceCorrectionAfterStabilization:viewPort:boundingRect:boundingCircle:] : 440 -> 432
~ -[RTSCFaceReframingV1 _estimateRatiosOfProjectedCorners:cornerRadii:toMaxCornerShifts:maxRadius:circleCenter:forRotation:] : 628 -> 616
```
