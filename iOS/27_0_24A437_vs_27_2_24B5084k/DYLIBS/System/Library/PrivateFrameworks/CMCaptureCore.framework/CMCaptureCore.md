## CMCaptureCore

> `/System/Library/PrivateFrameworks/CMCaptureCore.framework/CMCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x14f40` | `0x15080` | **`+0x140`** |
| `__TEXT.__text` | `0x2058` | `0x2124` | **`+0xcc`** |
| `__TEXT.__cstring` | `0xea86` | `0xeb2f` | **`+0xa9`** |
| `__DATA_CONST.__const` | `0x5af0` | `0x5b30` | **`+0x40`** |

### Other Changes

```diff

-764.22.13.0.0
+764.40.4.122.1

-  Symbols:   3033
-  CStrings:  2688
+  Symbols:   3042
+  CStrings:  2698
Symbols:
+ _CFStringAppend
+ _CFStringCreateMutable
+ _kFigCaptureStreamMetadata_AEStatsUpdated
+ _kFigCaptureStreamMetadata_AFStatsUpdated
+ _kFigCaptureStreamMetadata_AWBStatsUpdated
+ _kFigCaptureStreamMetadata_RawValidBufferRect
+ _kFigCaptureStreamMetadata_SmartTapAlgorithmMetadata
+ _kFigCaptureStreamProperty_DelayedRawStreamingEnabled
+ _kFigCaptureStreamSegmentFocusTrackingConfigurationKey_FacePrioritizationEnabled
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_FocusBias
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_MaskConfidence
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_ObjectID
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_TotalPoints
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_ValidCoverage
- _CFStringCreateWithFormat
- _kFigCaptureSegmentFocusTrackingSalientObjectMetadata_HasMask
- _kFigCaptureSegmentFocusTrackingSalientObjectMetadata_Mask
- _kFigCaptureSegmentFocusTrackingSalientObjectMetadata_MaskAttachedMediaKey
- _kFigCaptureSegmentFocusTrackingSalientObjectMetadata_TrackedForContinuousAutoFocus
Functions:
~ _FigCaptureStillImageNRFProcessingFlagsToShortString : 80 -> 284
CStrings:
+ ", "
+ "AEStatsUpdated"
+ "AFStatsUpdated"
+ "AWBStatsUpdated"
+ "DelayedRawStreamingEnabled"
+ "DisableDNR"
+ "FacePrioritizationEnabled"
+ "FocusBias"
+ "MaskConfidence"
+ "NonPhotoFormat"
+ "ObjectID"
+ "RawValidBufferRect"
+ "SmartTapAlgorithmMetadata"
+ "TotalPoints"
+ "ValidCoverage"
+ "description=CameraCapture_CMCore-764.40.4.122.1"
- "%llu"
- "HasMask"
- "Mask"
- "MaskAttachedMediaKey"
- "TrackedForContinuousAutoFocus"
- "description=CameraCapture_CMCore-764.22.13"
```
