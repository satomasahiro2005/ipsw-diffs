## PerformanceLoggingDiagnosticExtension

> `/System/Library/PrivateFrameworks/HangTracer.framework/PlugIns/PerformanceLoggingDiagnosticExtension.appex/PerformanceLoggingDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81e4` | `0x823c` | **`+0x58`** |
| `__TEXT.__const` | `0x1e0` | `0x1b0` | **`-0x30`** |
| `__TEXT.__objc_methname` | `0x34d4` | `0x34e8` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x540` | `0x550` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x788` | `0x790` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x8cc` | `0x8d4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-426.0.0.0.0
+430.0.0.0.0

-  Functions: 250
-  Symbols:   273
-  CStrings:  755
+  Functions: 251
+  Symbols:   274
+  CStrings:  756
Symbols:
+ _objc_opt_new
Functions:
~ sub_100002d2c : 7684 -> 7656
+ sub_100004b14
CStrings:
+ "allTaskingPrefNames"
```
