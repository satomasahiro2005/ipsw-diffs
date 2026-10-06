## CMCaptureCore

> `/System/Library/PrivateFrameworks/CMCaptureCore.framework/CMCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x15080` | `0x15160` | **`+0xe0`** |
| `__TEXT.__text` | `0x2124` | `0x2068` | **`-0xbc`** |
| `__TEXT.__cstring` | `0xeb29` | `0xebbd` | **`+0x94`** |
| `__DATA_CONST.__const` | `0x5b30` | `0x5ba8` | **`+0x78`** |

### Other Changes

```diff

-764.40.5.0.0
+764.40.7.0.0

-  Symbols:   3042
-  CStrings:  2698
+  Symbols:   3056
+  CStrings:  2705
Symbols:
+ _CFStringCreateWithFormat
+ _kFigAppleMakerNote_SegmentFocusTracking
+ _kFigAppleMakerNote_SegmentFocusTrackingKey_Enabled
+ _kFigAppleMakerNote_SegmentFocusTrackingKey_FocusBias
+ _kFigAppleMakerNote_SegmentFocusTrackingKey_MaskConfidence
+ _kFigAppleMakerNote_SegmentFocusTrackingKey_ObjectID
+ _kFigAppleMakerNote_SegmentFocusTrackingKey_TotalPoints
+ _kFigAppleMakerNote_SegmentFocusTrackingKey_ValidCoverage
+ _kFigCaptureStreamLCBKey_OpticalCenterForLensX
+ _kFigCaptureStreamLCBKey_OpticalCenterForLensY
+ _kFigCaptureStreamLCBKey_RadialDistortionEnabled
+ _kFigCaptureStreamLCBKey_RadialDistortionK1
+ _kFigCaptureStreamLCBKey_RadialDistortionK2
+ _kFigCaptureStreamLCBKey_RadialDistortionK3
+ _kFigCaptureStreamLCBKey_RadialDistortionMaxR
+ _kFigCaptureStreamLCBKey_RadialDistortionRPeak
- _CFStringAppend
- _CFStringCreateMutable
Functions:
~ _FigCaptureCopySerializableKeys : 6680 -> 6696
~ _FigCaptureStillImageNRFProcessingFlagsToShortString : 284 -> 80
CStrings:
+ "%llu"
+ "107"
+ "OpticalCenterForLensX"
+ "OpticalCenterForLensY"
+ "RadialDistortionEnabled"
+ "RadialDistortionK1"
+ "RadialDistortionK2"
+ "RadialDistortionK3"
+ "RadialDistortionMaxR"
+ "RadialDistortionRPeak"
+ "description=CameraCapture_CMCore-764.40.7"
- ", "
- "DisableDNR"
- "NonPhotoFormat"
- "description=CameraCapture_CMCore-764.40.5"
```
