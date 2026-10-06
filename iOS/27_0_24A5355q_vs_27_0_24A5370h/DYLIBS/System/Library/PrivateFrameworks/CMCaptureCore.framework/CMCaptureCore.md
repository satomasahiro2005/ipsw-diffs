## CMCaptureCore

> `/System/Library/PrivateFrameworks/CMCaptureCore.framework/CMCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x143a0` | `0x145a0` | **`+0x200`** |
| `__TEXT.__text` | `0x1f88` | `0x20a0` | **`+0x118`** |
| `__TEXT.__cstring` | `0xdda3` | `0xde84` | **`+0xe1`** |
| `__DATA_CONST.__const` | `0x57a0` | `0x5808` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x88` | `0x90` | **`+0x8`** |

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3

-  Functions: 13
-  Symbols:   2924
-  CStrings:  2595
+  Functions: 14
+  Symbols:   2941
+  CStrings:  2611
Symbols:
+ _CFAutorelease
+ _CFStringAppend
+ _CFStringCreateMutable
+ _FigCaptureStillImageNRFProcessingFlagsToShortString
+ _kFigCaptureSampleBufferMetadata_SmartStyleEditInfos
+ _kFigCaptureSampleBufferMetadata_StructuredLightAutoFocusEnabled
+ _kFigCaptureSampleBufferMetadata_TimeOfFlightAutoFocusEnabled
+ _kFigCaptureStillImageProcessingMetadataKey_StillImageNRFProcessingFlags
+ _kFigCaptureStreamAHKey_MTE
+ _kFigCaptureStreamAHKey_TE
+ _kFigCaptureStreamMetadata_AH
+ _kFigCaptureStreamMetadata_InputSignals
+ _kFigCaptureStreamMetadata_Signals
+ _kFigCaptureStreamProperty_AHE
+ _kFigCaptureStreamProperty_LCTE
+ _kFigCaptureStreamProperty_MSS
+ _kFigQuicktimeMetadataKey_SmartStyleEditInfos
CStrings:
+ ", "
+ "AH"
+ "AHE"
+ "DisableDNR"
+ "InputSignals"
+ "LCTE"
+ "MSS"
+ "MTE"
+ "NonPhotoFormat"
+ "Signals"
+ "SmartStyleEditInfos"
+ "StillImageNRFProcessingFlags"
+ "StructuredLightAutoFocusEnabled"
+ "TE"
+ "TimeOfFlightAutoFocusEnabled"
+ "com.apple.quicktime.smartstyle.edit.infos"
+ "description=CameraCapture_CMCore-753.0.0.122.3"
- "description=CameraCapture_CMCore-748.0.0.122.2"
```
