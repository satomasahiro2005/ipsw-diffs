## Diagnostic-8288

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8288.appex/Diagnostic-8288`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd9b0` | `0xda14` | **`+0x64`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ __Z22ConvertDataToHexStringPK8__CFData : 132 -> 148
~ __ZN28HxISPCaptureDeviceController9FindGroupEj : 320 -> 316
~ __ZN28HxISPCaptureDeviceControllerC2Ev : 220 -> 240
~ __ZN28HxISPCaptureDeviceControllerD2Ev : 156 -> 184
~ __ZN28HxISPCaptureDeviceController10deactivateEv : 400 -> 440
~ sub_100001a74 -> sub_100001ad8 : 348 -> 352
~ __ZN28HxISPCaptureDeviceController17SetStreamPropertyEjPK10__CFStringPKv : 312 -> 308
~ __ZN28HxISPCaptureDeviceController16SetGroupPropertyEjPK10__CFStringPKv : 492 -> 496
~ __ZN28HxISPCaptureDeviceController17CopyGroupPropertyEjPK10__CFStringPv : 496 -> 500
~ __ZN17DeviceCMInterface19setRgbConfigurationEiRK19RGBCamConfiguration : 3764 -> 3760
~ __ZN17DeviceCMInterface18configJasperDeviceERK19JasperConfiguration : 3176 -> 3172
```
