## CinematicFraming

> `/System/Library/PrivateFrameworks/CinematicFraming.framework/CinematicFraming`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x317bc` | `0x31748` | **`-0x74`** |
| `__AUTH_CONST.__cfstring` | `0x1720` | `0x1780` | **`+0x60`** |
| `__TEXT.__cstring` | `0x33ae` | `0x33cc` | **`+0x1e`** |
| `__TEXT.__oslogstring` | `0x5b2d` | `0x5b22` | **`-0xb`** |
| `__DATA_CONST.__objc_selrefs` | `0x16b8` | `0x16b0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x9a8` | `0x9b0` | **`+0x8`** |

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3

-  Symbols:   1642
-  CStrings:  656
+  Symbols:   1643
+  CStrings:  659
Symbols:
+ _MGGetBoolAnswer
+ _MGGetStringAnswer
- _MGCopyAnswer
Functions:
~ -[VCCamera initWithDictionary:] : 2736 -> 2728
~ -[VCCamera dictionaryRepresentation] : 1472 -> 1464
~ -[VCShaders initWithContext:] : 500 -> 492
~ -[VCProcessor getPhysicalCameraToVirtualCameraTransform] : 148 -> 144
~ +[VCProcessor warpCGRect:fromCamera:toCamera:] : 480 -> 476
~ __ZL23zRotationForOrientation33CinematicFramingCameraOrientationb : 132 -> 140
~ -[VCProcessor _updateOutputCameraForRollCorrection] : 2288 -> 2284
~ __ZL22isViewFrustumContainedP8VCCameraS0_f : 428 -> 420
~ -[VCProcessor _setOutputPixelBufferAttachments] : 1488 -> 1484
~ -[KalmanFilterPrivate _predict:] : 292 -> 284
~ -[KalmanFilterPrivate _update:] : 264 -> 260
~ -[CinematicTracker init] : 212 -> 204
~ -[CinematicTracker processFaceDetections:bodyDetections:atTime:inView:] : 1380 -> 1372
~ -[CinematicTracker resetTracksFramingProperties] : 188 -> 184
~ -[CinematicTracker processDetections:ofType:atTime:] : 2128 -> 2124
~ -[CinematicTracker updateBodyFacePairsAtTime:] : 2576 -> 2568
~ -[DeskCamRenderingSession _updateSubjectRectangleInSensorSpace:withDetections:] : 556 -> 552
~ -[DeskCamRenderingSession processBuffer:outputPixelBuffer:] : 2924 -> 2920
~ -[DeskCamRenderingSession _estimateSubjectRectangleInFramingSpaceFromSubjectRectangleInSensorSpace:] : 336 -> 332
~ -[DeskCamRenderingSession _updateDeskEdgeDetectionDataInOutputSpace] : 996 -> 992
~ -[DeskCamRenderingSession _filterAutoZoomScalingFactor:] : 3056 -> 3064
~ -[DeskCamRenderingSession _transformMatrixWithOutputCropRectangle:] : 860 -> 836
~ -[DeskCamRenderingSession _compileShaders] : 112 -> 132
~ -[SceneFramingEngine updateTargetViewportForFloatingWithTracks:atTime:] : 908 -> 904
~ -[SceneFramingEngine updateSubjectMovement:atTime:] : 384 -> 388
~ -[SceneFramingEngine isSubjectRectStationary:] : 324 -> 332
~ -[SceneFramingEngine calculateBaselineViewportForTracks:atTime:] : 972 -> 968
~ -[SceneFramingEngine calculateSubjectEnclosingRectangleForTracks:withBaselineWidth:currentViewport:atTime:] : 1188 -> 1184
~ -[DeskCamSession _deviceType] : 632 -> 696
~ _computeNumberOfCCWRotationsFromInputToFramingSpaceForCameraOrientation : 104 -> 112
~ +[SubjectSelectionSession filterDetectedObjects:usedFaceIDs:usedBodyIDs:filteredObjects:] : 776 -> 768
~ -[SubjectSelectionSession _runGazeDetection:faceObjects:selectedFaceRects:] : 796 -> 792
~ -[SubjectSelectionSession _convertDetectionArrayToDict:bodyObjects:faceRects:bodyRects:] : 580 -> 572
~ -[SubjectSelectionSession _pairFaceBody:bodyObjects:face2Body:body2Face:] : 1256 -> 1252
~ -[SubjectSelectionSession _selectPairRects:bodyRects:face2Body:body2Face:selectedFaceRects:selectedBodyRects:] : 612 -> 604
~ -[SubjectSelectionSession _updateDetectionRects:bodyObjects:timestamp:] : 4212 -> 4208
~ -[SubjectSelectionSession _selectAllObjects:bodyObjects:usedFaceIDs:usedBodyIDs:] : 668 -> 660
~ -[SubjectSelectionSession _selectSingleSubject:bodyRects:selectedFaceRects:selectedBodyRects:timestamp:inputPixelBuffer:] : 996 -> 988
~ __ZN15SpringAnimationIdLm4EE6updateEd : 412 -> 408
~ -[CinematicFramingSessionOptions loadFramingStyleSpecificOptions:] : 336 -> 332
~ -[CinematicFramingSessionInputMetadata _parseDetectedObjectsInfoWithFilteredFaceIDs:filteredBodyIDs:] : 900 -> 896
~ -[DeskCamSessionInputMetadata _parseDetectedObjectsInfo:] : 816 -> 812
~ -[CinematicFramingRenderer processBuffer:cropRect:outputPixelBuffer:] : 1956 -> 1960
~ -[CinematicFramingRenderer _filterDetectionsInInputImageCoordinates:trackType:] : 948 -> 932
~ -[CinematicFramingRenderer warpMetadataInInputImageCoordinatesToFramingSpace:] : 480 -> 472
~ -[CinematicFramingRenderer _rotationMatrixForDisplayRect:] : 2040 -> 2028
~ -[CinematicFramingRenderer _createComputePipelinesForShaders:] : 660 -> 656
~ -[DeskCamRenderingSession _deskEdgeDetectorResult] : 1596 -> 1608
CStrings:
+ "<<<< DeskCamSession >>>> %s: [DeskView][>deviceType] deviceIsPortableMac: %@"
+ "<<<< DeskCamSession >>>> %s: [DeskView][>deviceType] marketingDeviceFamilyName: %@"
+ "Apple Display"
+ "DeviceIsPortableMac"
+ "Mac"
+ "MarketingDeviceFamilyName"
+ "NO"
+ "YES"
+ "iPhone"
- "<<<< DeskCamSession >>>> %s: Assuming that machine with name \"Mac xxx\" is a MacBook"
- "<<<< DeskCamSession >>>> %s: [DeskView][>deviceType] physicalHardwareNameString: (%@)."
- "Mac xxx"
- "MacBook"
- "PhysicalHardwareNameString"
- "iMac"
```
