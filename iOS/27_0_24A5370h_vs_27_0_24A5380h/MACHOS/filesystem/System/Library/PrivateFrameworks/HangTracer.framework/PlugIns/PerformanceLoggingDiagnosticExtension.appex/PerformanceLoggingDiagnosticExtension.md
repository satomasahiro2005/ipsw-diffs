## PerformanceLoggingDiagnosticExtension

> `/System/Library/PrivateFrameworks/HangTracer.framework/PlugIns/PerformanceLoggingDiagnosticExtension.appex/PerformanceLoggingDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x812c` | `0x81c8` | **`+0x9c`** |
| `__TEXT.__objc_methname` | `0x345d` | `0x34d4` | **`+0x77`** |
| `__DATA.__objc_const` | `0x17b0` | `0x17e0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x12a4` | `0x12c9` | **`+0x25`** |
| `__DATA_CONST.__cfstring` | `0x1440` | `0x1460` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x8bc` | `0x8cc` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x780` | `0x788` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x558` | `0x560` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xf8` | `0x100` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1c4` | `0x1c8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-415.0.0.0.0
+421.0.0.0.0

-  Functions: 249
-  Symbols:   272
-  CStrings:  751
+  Functions: 250
+  Symbols:   273
+  CStrings:  755
Symbols:
+ _kHTPrefsShouldMonitorCPURoleForAppExtensions
CStrings:
+ "ShouldMonitorCPURoleForAppExtensions"
+ "TB,R,V_shouldMonitorCPURoleForAppExtensions"
+ "_shouldMonitorCPURoleForAppExtensions"
+ "shouldMonitorCPURoleForAppExtensions"
```
