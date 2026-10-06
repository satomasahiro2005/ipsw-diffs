## Diagnostic-8288

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8288.appex/Diagnostic-8288`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xda14` | `0xe04c` | **`+0x638`** |
| `__TEXT.__cstring` | `0x3090` | `0x329d` | **`+0x20d`** |
| `__DATA_CONST.__cfstring` | `0x21c0` | `0x2300` | **`+0x140`** |
| `__TEXT.__gcc_except_tab` | `0x1630` | `0x16fc` | **`+0xcc`** |
| `__TEXT.__unwind_info` | `0x408` | `0x430` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x6b0` | `0x6c0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x368` | `0x370` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-58.0.0.0.0
+60.0.0.0.0

-  Functions: 145
-  Symbols:   322
-  CStrings:  383
+  Functions: 148
+  Symbols:   326
+  CStrings:  393
Symbols:
+ _CFDictionaryGetTypeID
+ __ZN17DeviceCMInterface19getDiagnosticReportEPU15__autoreleasingP12NSDictionary
+ __ZN17DeviceCMInterface20getAntliaFaultStatusEPy
+ __ZN17DeviceCMInterface28getProjectorCalibratedValuesEPU15__autoreleasingP12NSDictionary
CStrings:
+ "DiagnosticReport"
+ "ProjectorAntliaFaultStatus"
+ "ProjectorCalibratedValues"
+ "getAntliaFaultStatus failed with OSStatus 0x%x for stream id %d (%@)"
+ "getAntliaFaultStatus failed, ir stream id invalid"
+ "getDiagnosticReport failed with OSStatus 0x%x for stream id %d (%@)"
+ "getDiagnosticReport failed, ir stream id invalid"
+ "getDiagnosticReport returned unexpected CF type (not a dictionary) for stream id %d"
+ "getProjectorCalibratedValues failed with OSStatus 0x%x for stream id %d (%@)"
+ "getProjectorCalibratedValues failed, ir stream id invalid"
```
