## CMCaptureCore

> `/System/Library/PrivateFrameworks/CMCaptureCore.framework/CMCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20a0` | `0x1fd4` | **`-0xcc`** |
| `__AUTH_CONST.__cfstring` | `0x14760` | `0x14740` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x5878` | `0x5880` | **`+0x8`** |
| `__TEXT.__cstring` | `0xdf4e` | `0xdf56` | **`+0x8`** |

### Other Changes

```diff

-761.0.0.0.3
+764.22.5.122.2

-  CStrings:  2625
+  CStrings:  2624
Symbols:
+ _CFStringCreateWithFormat
+ _kFigCaptureDeviceMultiCamConfigurationKey_BuiltInMicrophoneIsRecording
- _CFStringAppend
- _CFStringCreateMutable
Functions:
~ _FigCaptureStillImageNRFProcessingFlagsToShortString : 284 -> 80
CStrings:
+ "%llu"
+ "BuiltInMicrophoneIsRecording"
+ "description=CameraCapture_CMCore-764.22.5.122.2"
- ", "
- "DisableDNR"
- "NonPhotoFormat"
- "description=CameraCapture_CMCore-761.0.0.0.3"
```
