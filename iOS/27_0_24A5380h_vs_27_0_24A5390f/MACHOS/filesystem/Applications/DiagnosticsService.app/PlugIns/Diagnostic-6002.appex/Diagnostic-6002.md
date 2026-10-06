## Diagnostic-6002

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6002.appex/Diagnostic-6002`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c830` | `0x1cfe0` | **`+0x7b0`** |
| `__TEXT.__cstring` | `0x4683` | `0x49dd` | **`+0x35a`** |
| `__DATA_CONST.__cfstring` | `0x3600` | `0x37a0` | **`+0x1a0`** |
| `__TEXT.__gcc_except_tab` | `0x3044` | `0x3154` | **`+0x110`** |
| `__TEXT.__objc_stubs` | `0x1d60` | `0x1dc0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x23bf` | `0x2419` | **`+0x5a`** |
| `__TEXT.__unwind_info` | `0x818` | `0x850` | **`+0x38`** |
| `__TEXT.__const` | `0x147` | `0x123` | **`-0x24`** |
| `__TEXT.__auth_stubs` | `0xb50` | `0xb30` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0xa30` | `0xa48` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x5c0` | `0x5b0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x428` | `0x438` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-58.0.0.0.0
+60.0.0.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 354
-  Symbols:   466
-  CStrings:  1090
+  Functions: 359
+  Symbols:   470
+  CStrings:  1106
Symbols:
+ _CFDictionaryGetTypeID
+ _MGCopyAnswer
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_CLASS_$_PDPeridotCameraSystemCalibrationData
+ __Z20getCurrentIOSVersionv
+ __ZN17DeviceCMInterface19getDiagnosticReportEPU15__autoreleasingP12NSDictionary
+ __ZN17DeviceCMInterface20getAntliaFaultStatusEPy
+ __ZN17DeviceCMInterface28getProjectorCalibratedValuesEPU15__autoreleasingP12NSDictionary
- __ZdaPvSt19__type_descriptor_t
- __ZnamSt19__type_descriptor_t
- _bzero
- _sysctlbyname
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DepthDiagnostics/RGBJ/ViewController.mm"
+ "DiagnosticReport"
+ "HWModelStr"
+ "PeridotDepth has no nominal Wide->Peridot extrinsics for %@; refusing to write fallback (would be 180 deg wrong, rdar://155526786)"
+ "ProjectorAntliaFaultStatus"
+ "ProjectorCalibratedValues"
+ "getAntliaFaultStatus failed with OSStatus 0x%x for stream id %d (%@)"
+ "getAntliaFaultStatus failed, ir stream id invalid"
+ "getDiagnosticReport failed with OSStatus 0x%x for stream id %d (%@)"
+ "getDiagnosticReport failed, ir stream id invalid"
+ "getDiagnosticReport returned unexpected CF type (not a dictionary) for stream id %d"
+ "getNominalWideToPeridotExtrinsics:forDeviceName:"
+ "getProjectorCalibratedValues failed with OSStatus 0x%x for stream id %d (%@)"
+ "getProjectorCalibratedValues failed, ir stream id invalid"
+ "operatingSystemVersionString"
+ "processInfo"
+ "set wide jasper extrinsics from PeridotDepth nominal"
+ "unknown device for nominal extrinsics"
- "hw.model"
- "set wide jasper extrinsics to 0"
```
