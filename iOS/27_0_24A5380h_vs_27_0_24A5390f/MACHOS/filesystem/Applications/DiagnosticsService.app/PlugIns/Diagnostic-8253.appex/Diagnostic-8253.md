## Diagnostic-8253

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8253.appex/Diagnostic-8253`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13160` | `0x13828` | **`+0x6c8`** |
| `__TEXT.__cstring` | `0x3d03` | `0x3f1c` | **`+0x219`** |
| `__DATA_CONST.__cfstring` | `0x3240` | `0x33a0` | **`+0x160`** |
| `__TEXT.__gcc_except_tab` | `0x226c` | `0x2358` | **`+0xec`** |
| `__TEXT.__objc_stubs` | `0x820` | `0x860` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x600` | `0x630` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x60a` | `0x633` | **`+0x29`** |
| `__DATA.__objc_selrefs` | `0x230` | `0x240` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x700` | `0x710` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x390` | `0x398` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x320` | `0x328` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-58.0.0.0.0
+60.0.0.0.0

-  Functions: 213
-  Symbols:   355
-  CStrings:  570
+  Functions: 217
+  Symbols:   361
+  CStrings:  583
Symbols:
+ _CFDictionaryGetTypeID
+ _OBJC_CLASS_$_NSProcessInfo
+ __Z20getCurrentIOSVersionv
+ __ZN17DeviceCMInterface19getDiagnosticReportEPU15__autoreleasingP12NSDictionary
+ __ZN17DeviceCMInterface20getAntliaFaultStatusEPy
+ __ZN17DeviceCMInterface28getProjectorCalibratedValuesEPU15__autoreleasingP12NSDictionary
CStrings:
+ "DiagnosticReport"
+ "IOS_VERSION"
+ "ProjectorAntliaFaultStatus"
+ "ProjectorCalibratedValues"
+ "getAntliaFaultStatus failed with OSStatus 0x%x for stream id %d (%@)"
+ "getAntliaFaultStatus failed, ir stream id invalid"
+ "getDiagnosticReport failed with OSStatus 0x%x for stream id %d (%@)"
+ "getDiagnosticReport failed, ir stream id invalid"
+ "getDiagnosticReport returned unexpected CF type (not a dictionary) for stream id %d"
+ "getProjectorCalibratedValues failed with OSStatus 0x%x for stream id %d (%@)"
+ "getProjectorCalibratedValues failed, ir stream id invalid"
+ "operatingSystemVersionString"
+ "processInfo"
```
