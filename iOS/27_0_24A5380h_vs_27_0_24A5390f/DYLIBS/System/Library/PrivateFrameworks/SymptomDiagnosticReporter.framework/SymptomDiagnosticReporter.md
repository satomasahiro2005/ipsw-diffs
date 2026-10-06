## SymptomDiagnosticReporter

> `/System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8230` | `0x828c` | **`+0x5c`** |
| `__AUTH_CONST.__cfstring` | `0x21e0` | `0x2200` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x56c` | `0x584` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4b0` | `0x4b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2b8` | `0x2c0` | **`+0x8`** |
| `__TEXT.__cstring` | `0x133e` | `0x1342` | **`+0x4`** |

### Other Changes

```diff

-467.0.0.0.0
+469.0.0.0.0

-  Functions: 193
-  Symbols:   501
-  CStrings:  340
+  Functions: 195
+  Symbols:   503
+  CStrings:  341
Symbols:
+ +[SDRDiagnosticReporter setBasebandChipset:]
+ +[SDRDiagnosticReporter setWiFiChipset:]
+ GCC_except_table119
+ GCC_except_table135
+ GCC_except_table15
+ GCC_except_table49
+ GCC_except_table64
- GCC_except_table117
- GCC_except_table13
- GCC_except_table133
- GCC_except_table47
- GCC_except_table62
CStrings:
+ "int"
```
