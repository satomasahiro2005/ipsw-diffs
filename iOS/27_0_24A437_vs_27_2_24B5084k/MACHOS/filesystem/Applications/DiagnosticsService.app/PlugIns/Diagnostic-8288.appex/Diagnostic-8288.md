## Diagnostic-8288

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8288.appex/Diagnostic-8288`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe074` | `0x13108` | **`+0x5094`** |
| `__TEXT.__gcc_except_tab` | `0x16fc` | `0x2274` | **`+0xb78`** |
| `__DATA_CONST.__const` | `0x4a0` | `0x4d8` | **`+0x38`** |
| `__TEXT.__objc_stubs` | `0x3c0` | `0x3e0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1d` | `0x30` | **`+0x13`** |
| `__TEXT.__objc_methname` | `0x231` | `0x23c` | **`+0xb`** |
| `__DATA.__objc_selrefs` | `0x108` | `0x110` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x430` | `0x428` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-60.0.0.0.0
+62.0.0.0.0

-  CStrings:  395
+  CStrings:  397
Symbols:
+ __os_log_error_impl
- _NSLog
Functions:
~ __ZN17DeviceCMInterface38initAndActivateCaptureDeviceControllerEv : 348 -> 484
~ __ZN17DeviceCMInterface19setRgbConfigurationEiRK19RGBCamConfiguration : 3760 -> 5244
~ __ZN17DeviceCMInterface20enableJasperRgbVideoEv : 576 -> 900
~ __ZN17DeviceCMInterface26enableRGBOutputForStreamIdEi : 356 -> 480
~ __ZN17DeviceCMInterface28enableJasperPointCloudOutputEv : 512 -> 784
~ __ZN17DeviceCMInterface26configJasperRgbMultiStreamERK19JasperConfiguration : 1640 -> 2432
~ __ZN17DeviceCMInterface31setJasperMultiOutModeByStreamIdEjb : 624 -> 1056
~ __ZN17DeviceCMInterface18configJasperDeviceERK19JasperConfiguration : 3172 -> 4712
~ __ZN17DeviceCMInterface17enableSWRGBOutputEv : 212 -> 340
~ __ZN17DeviceCMInterface23requestControlOfStreamsEbj : 1344 -> 2100
~ __ZN17DeviceCMInterface23releaseControlOfStreamsEv : 384 -> 620
~ __ZN17DeviceCMInterface23enumerateStreamsIndicesEv : 960 -> 1340
~ __ZN17DeviceCMInterface30setPearlMultiOutModeByStreamIdEjb : 612 -> 1044
~ __ZN17DeviceCMInterface17setStreamPropertyEjPK10__CFStringPK12NSDictionary : 460 -> 736
~ __ZN17DeviceCMInterface19enablePearlIROutputEv : 748 -> 1016
~ __ZN17DeviceCMInterface20enablePearlRGBOutputEv : 212 -> 340
~ __ZN17DeviceCMInterface22setPearlIrCofigurationE20PearlProjectorIRType : 1940 -> 2940
~ __ZN17DeviceCMInterface26setPearlDepthConfigurationEyyb18PearlPdeOutputMode : 844 -> 1120
~ __ZN17DeviceCMInterface14startRgbStreamEi : 1052 -> 1780
~ __ZN17DeviceCMInterface17startJasperStreamEv : 1688 -> 2556
~ __ZN17DeviceCMInterface16stopJasperStreamEv : 524 -> 916
~ __ZN17DeviceCMInterface18startPearlIrStreamEv : 928 -> 1496
~ __ZN17DeviceCMInterface17stopPearlIrStreamEv : 524 -> 916
~ __ZN17DeviceCMInterface13stopRgbStreamEi : 516 -> 904
~ __ZN17DeviceCMInterface22validateJasperFwStatusEPj : 344 -> 476
~ __ZN17DeviceCMInterface18validateIrFwStatusEPj : 628 -> 1004
~ __ZN17DeviceCMInterface24enableDefaultDepthStreamEv : 224 -> 412
~ __ZN17DeviceCMInterface16setPearlMultiCamEv -> __ZN17DeviceCMInterface26getPearlProjectorHWVersionEPi : 960 -> 620
~ __ZN17DeviceCMInterface30enableSyncForEnumeratedStreamsEi -> __ZN17DeviceCMInterface16setPearlMultiCamEv : 560 -> 1504
~ __ZN17DeviceCMInterface17setPearlSyncSlaveEii -> __ZN17DeviceCMInterface30enableSyncForEnumeratedStreamsEi : 780 -> 856
~ __ZN17DeviceCMInterface21setPearlIRAsSyncSlaveEi -> __ZN17DeviceCMInterface17setPearlSyncSlaveEii : 12 -> 1192
~ __ZN17DeviceCMInterface20disablePearlSyncModeEi -> __ZN17DeviceCMInterface22setPearlRgbAsSyncSlaveEi : 316 -> 12
~ __ZN17DeviceCMInterface19setPearlFormatIndexEii -> __ZN17DeviceCMInterface20disablePearlSyncModeEi : 100 -> 436
~ __ZN17DeviceCMInterface17configPearlDeviceERK18PearlConfiguration -> __ZN17DeviceCMInterface19setPearlFormatIndexEii : 2736 -> 100
~ __ZN17DeviceCMInterface26getPearlProjectorHWVersionEPi -> __ZN17DeviceCMInterface17configPearlDeviceERK18PearlConfiguration : 432 -> 4652
~ __ZNK17DeviceCMInterface30getPearlConfigurationStringKeyEPK18PearlConfiguration : 476 -> 340
~ __ZN17DeviceCMInterface22isPDECaliobrationValidEPb : 388 -> 624
~ __ZN17DeviceCMInterface23getJasperProjectorFaultEPyPU15__autoreleasingP12NSDictionary : 436 -> 556
~ __ZN17DeviceCMInterface27getJasperProjectorWillFaultEPy : 476 -> 736
~ __ZN17DeviceCMInterface19getJasperResistanceEPy : 476 -> 736
~ __ZN17DeviceCMInterface27getPearlFloodProjectorFaultEPy : 624 -> 956
~ __ZN17DeviceCMInterface27getStructuredProjectorFaultEPy : 492 -> 700
~ __ZN17DeviceCMInterface20getAntliaFaultStatusEPy : 492 -> 700
~ __ZN17DeviceCMInterface28getProjectorCalibratedValuesEPU15__autoreleasingP12NSDictionary : 452 -> 692
~ __ZN17DeviceCMInterface19getDiagnosticReportEPU15__autoreleasingP12NSDictionary : 648 -> 1024
~ __ZN17DeviceCMInterface13releaseDeviceEv : 224 -> 340
~ __ZN17DeviceCMInterface13getRgbjReportERiS0_S0_S0_S0_ : 528 -> 880
~ __ZN17DeviceCMInterface24forceSaveWideJasperCalibEv : 280 -> 408
~ __ZN17DeviceCMInterface20setRgbjConfigurationEjjj : 492 -> 620
~ __ZN17DeviceCMInterface23setWideJasperExtrinsicsEffffff : 668 -> 796
~ __ZN17DeviceCMInterface15getPearlPleUUIDEPh : 436 -> 624
~ __ZN17DeviceCMInterface25getPearlRigelSerialNumberEPU15__autoreleasingP8NSString : 440 -> 664
~ __ZN17DeviceCMInterface23getPearlRigelOtpVersionEPi : 444 -> 632
~ __ZN17DeviceCMInterface18getGuadalupeValuesEPxS0_S0_PiS0_ : 1084 -> 1664
CStrings:
+ "%{public}s"
+ "QueryExtrinsicsDiagnostic %{public}s"
+ "UTF8String"
- "QueryExtrinsicsDiagnostic %s"
```
