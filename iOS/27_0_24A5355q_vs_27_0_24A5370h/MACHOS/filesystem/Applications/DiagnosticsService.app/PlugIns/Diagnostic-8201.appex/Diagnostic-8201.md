## Diagnostic-8201

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8201.appex/Diagnostic-8201`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2229c` | `0x223d0` | **`+0x134`** |
| `__TEXT.__cstring` | `0x5c87` | `0x5cad` | **`+0x26`** |
| `__TEXT.__oslogstring` | `0x99e` | `0x9c4` | **`+0x26`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  960
+  CStrings:  961
Functions:
~ __ZN17DeviceCMInterface19setRgbConfigurationEiRK19RGBCamConfiguration : 3764 -> 3760
~ __ZN17DeviceCMInterface18configJasperDeviceERK19JasperConfiguration : 3176 -> 3172
~ __Z14logMainResultsP12NSDictionaryii : 1280 -> 1276
~ sub_10000de48 -> sub_10000de3c : 5612 -> 5608
~ __ZN28HxISPCaptureDeviceController9FindGroupEj : 320 -> 316
~ __ZN28HxISPCaptureDeviceControllerC2Ev : 220 -> 240
~ __ZN28HxISPCaptureDeviceControllerD2Ev : 156 -> 184
~ __ZN28HxISPCaptureDeviceController10deactivateEv : 400 -> 440
~ sub_10000fd78 -> sub_10000fdbc : 348 -> 352
~ __ZN28HxISPCaptureDeviceController17SetStreamPropertyEjPK10__CFStringPKv : 312 -> 308
~ __ZN28HxISPCaptureDeviceController16SetGroupPropertyEjPK10__CFStringPKv : 492 -> 496
~ __ZN28HxISPCaptureDeviceController17CopyGroupPropertyEjPK10__CFStringPv : 496 -> 500
~ sub_1000158d8 -> sub_100015924 : 3456 -> 3540
~ _decompressReferenceFrames : 5480 -> 5616
~ _checkSecureStreamingAndVerifySignatures : 488 -> 500
CStrings:
+ "Generating reference frames files...\n"
```
