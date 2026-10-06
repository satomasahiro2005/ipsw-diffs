## cameraispd

> `/usr/libexec/cameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ce40` | `0x7e754` | **`+0x1914`** |
| `__DATA.__data` | `0x3bdde0` | `0x3be2c0` | **`+0x4e0`** |
| `__TEXT.__cstring` | `0x77aa` | `0x7c83` | **`+0x4d9`** |
| `__DATA_CONST.__cfstring` | `0x2bc0` | `0x3060` | **`+0x4a0`** |
| `__TEXT.__objc_stubs` | `0xf80` | `0x11e0` | **`+0x260`** |
| `__TEXT.__objc_methname` | `0x1295` | `0x13f2` | **`+0x15d`** |
| `__TEXT.__gcc_except_tab` | `0x18e0` | `0x1a2c` | **`+0x14c`** |
| `__DATA.__objc_selrefs` | `0x4f8` | `0x590` | **`+0x98`** |
| `__DATA_CONST.__const` | `0x9a28` | `0x9ac0` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x1248` | `0x12c0` | **`+0x78`** |
| `__TEXT.__auth_stubs` | `0x1f20` | `0x1f90` | **`+0x70`** |
| `__DATA_CONST.__got` | `0xc98` | `0xcd8` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0xfa0` | `0xfd8` | **`+0x38`** |
| `__DATA.__common` | `0xf` | `0x10` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 1561
-  Symbols:   918
-  CStrings:  1844
+  Functions: 1578
+  Symbols:   933
+  CStrings:  1916
Symbols:
+ _AnalyticsSendEventLazy
+ _IOSurfaceGetBytesPerRow
+ _IOSurfaceGetHeight
+ _IOSurfaceGetWidth
+ _OBJC_CLASS_$_ABDMetadata
+ _OBJC_CLASS_$_ABDProcessor
+ ___cxa_atexit
+ _kFigCaptureStreamMetadata_AEApertureActiveSignals
+ _kFigCaptureStreamMetadata_AEInputSignals
+ _kFigCaptureStreamMetadata_AESignals
+ _kFigCaptureStreamMetadata_ApertureDiameter
+ _kFigCaptureStreamMetadata_ApertureHealth
+ _kFigCaptureStreamMetadata_ISPApertureData
+ _kFigCaptureStreamMetadata_MagneticInterferenceMitigated
+ _kFigCaptureStreamMetadata_SensorSigningSignatureRect
+ _kFigCaptureStreamMetadata_TargetFNumber
+ _kFigCaptureStreamMetadata_TemporalNoiseReductionMachineLearningImageRegistrationEnabled
+ _kFigCaptureStreamMetadata_TimewarpActualFrameRate
+ _kFigCaptureStreamMetadata_TimewarpDecimationLevel
+ _kFigCaptureStreamMetadata_TimewarpDecimationTag
+ _kFigCaptureStreamMetadata_TimewarpDesiredFrameRate
+ _kFigCaptureStreamMetadata_TimewarpSequenceCaptureID
+ _kFigCaptureStreamMetadata_TimewarpShouldSkipFrame
+ _work_interval_join_port
+ _work_interval_leave
- _kFigCaptureStreamMetadata_AD
- _kFigCaptureStreamMetadata_AH
- _kFigCaptureStreamMetadata_ActiveSignals
- _kFigCaptureStreamMetadata_IAD
- _kFigCaptureStreamMetadata_IREnabled
- _kFigCaptureStreamMetadata_InputSignals
- _kFigCaptureStreamMetadata_MIM
- _kFigCaptureStreamMetadata_RatioNumber
- _kFigCaptureStreamMetadata_Signals
- _kFigCaptureStreamProperty_SSSR
CStrings:
+ "%s took %llu usec"
+ "%s%s-%04d.raw"
+ "%s: ABDNet: Received %lu buffers (%lu)"
+ "/usr/local/share/firmware/isp/dcs_v6x_isp_fw.bin"
+ "/var/mobile/Media/DCIM/%s-ABD-"
+ "@\"NSDictionary\"8@?0"
+ "ABDNet: ABDProcessor not available - is ISPKit missing?"
+ "ABDNet: Bad inputs"
+ "ABDNet: Created pixel buffer: %zux%zu[%zu]"
+ "ABDNet: Dump input buffers"
+ "ABDNet: Dump output buffers"
+ "ABDNet: Execution"
+ "ABDNet: Extra info version mismatch: expected %d, got %d"
+ "ABDNet: Not familiar with this buffer. Not copying it anymore"
+ "ABDNet: Surface"
+ "ABDNet: Surface ID: %d, %zux%zu[%zu] - received %dx%d[%d]"
+ "ABDNet: Unknown configuration ID %d"
+ "ABDNet: disabled by environment"
+ "ABDNet: expected %d buffers, got %d"
+ "ABDNetDumpRate"
+ "ABDNetEnable"
+ "ABDNetPeriodic event: %@"
+ "ABDNetPriodic analytics: unknown resolution! w=%zu, h=%zu"
+ "ABDNetProcessot invalid"
+ "ABDNetVerbose"
+ "AGain"
+ "DGain"
+ "EffectiveFPS"
+ "ExposureIntegrationTime"
+ "ExposureTime"
+ "FrontCameraRenoModuleSerialNumString"
+ "GLFramesInPeriod"
+ "InferenceTime"
+ "InputResolution"
+ "LLFramesInPeriod"
+ "LuxLevel"
+ "Mapping: 0x%llx to %@"
+ "ModelReloaded"
+ "ModelSwitched"
+ "ModelSwitchesInPeriod"
+ "ModelType"
+ "SIFR"
+ "SmartTapAlgorithmMetadata"
+ "TotalGain"
+ "TotalLatency"
+ "com.apple.applecamerad.ABDNetPeriodic"
+ "com.apple.isp.frontrenocamerapower"
+ "com.apple.isp.frontrenocamerasensorconfig"
+ "enumerateKeysAndObjectsUsingBlock:"
+ "inferenceTime"
+ "input"
+ "lastProcessingStats"
+ "modelReloaded"
+ "nameOfConfig:"
+ "noiseAddbackFactor"
+ "now"
+ "numberWithDouble:"
+ "numberWithFloat:"
+ "numberWithUnsignedLong:"
+ "numberWithUnsignedLongLong:"
+ "output"
+ "outputRaw"
+ "process:into:configId:metadata:"
+ "raw"
+ "setAnalogGain:"
+ "setBufferHeight:"
+ "setBufferMap"
+ "setBufferWidth:"
+ "setHrdRatio:"
+ "setLuxLevel:"
+ "setTotalGain:"
+ "unsignedLongLongValue"
+ "v32@?0@8@16^B24"
- "ISPABDProcessor: ISPKit support not available"
```
